### Roster Details<br />
Team Name: esmagaB<br />
Roster: Ag1l, aragornN, P3R3IIRA, pr, rafaxF<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [124](../standings_global.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
Final Rank Value:  818.6<br />
<br />
Final Rank Value (818.6) = Starting Rank Value (855.7) + Head To Head Adjustments (-37.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.130[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 855.7
- 400 + ( ( 0.224 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 855.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |      342 | 2024-05-24 | CYBERSHOKE Esports   | L   | 1.000      | -            | -                | -                | -         |   -18.01 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           58 |      354 | 2024-05-24 | GamerLegion Academy  | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    14.17 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           57 |      394 | 2024-05-23 | Team Spirit Academy  | L   | 1.000      | -            | -                | -                | -         |   -18.17 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           56 |     1070 | 2024-05-16 | VP.Prodigy           | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.752 (0.280)    | 0 (0.000) |    14.93 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           55 |     1310 | 2024-05-13 | Lilmix               | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.581 (0.216)    | 0 (0.000) |    14.79 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           54 |     1443 | 2024-05-11 | AL-QATRAO            | L   | 1.000      | -            | -                | -                | -         |   -16.94 | Ag1l, aragornN, fox, pr, rafaxF               |
|           53 |     1624 | 2024-05-08 | RoundsGG             | W   | 1.000      | 0.372        | -                | 0.202 (0.075)    | 0 (0.000) |     5.65 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           52 |     1982 | 2024-05-01 | Young Gods           | W   | 1.000      | 0.372        | -                | 0.240 (0.089)    | 0 (0.000) |     6.68 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           51 |     2364 | 2024-04-24 | RUBY                 | W   | 0.964      | 0.372        | 0.012 (0.004)    | 0.728 (0.261)    | 0 (0.000) |    21.66 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           50 |     2415 | 2024-04-23 | DMS                  | L   | 0.957      | -            | -                | -                | -         |   -13.28 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           49 |     2577 | 2024-04-20 | 1win                 | L   | 0.937      | -            | -                | -                | -         |    -7.07 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           48 |     2697 | 2024-04-19 | Team Secret          | W   | 0.930      | -            | -                | -                | 0 (0.000) |     9.51 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           47 |     2757 | 2024-04-18 | Illuminar Gaming     | L   | 0.924      | -            | -                | -                | -         |   -14.34 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           46 |     2847 | 2024-04-17 | 500                  | W   | 0.916      | 0.143        | -                | 0.479 (0.063)    | 0 (0.000) |    18.50 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           45 |     3114 | 2024-04-11 | AscendX Esports      | W   | 0.877      | -            | -                | -                | -         |     2.65 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           44 |     3339 | 2024-04-07 | HOTU                 | L   | 0.850      | -            | -                | -                | -         |   -13.14 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           43 |     3346 | 2024-04-07 | Team PeeP            | W   | 0.849      | -            | -                | -                | -         |     6.38 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           42 |     3805 | 2024-03-27 | 500                  | L   | 0.777      | -            | -                | -                | -         |   -10.26 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           41 |     3883 | 2024-03-26 | Fnatic               | W   | 0.771      | 0.143        | 0.147 (0.016)    | 0.480 (0.053)    | -         |    21.12 | P3R3IIRA, pr, rafaxF, SeabraEZ, Sprayy        |
|           40 |     5103 | 2024-03-03 | Rhyno Esports        | W   | 0.616      | 0.143        | 0.029 (0.003)    | -                | 1 (0.616) |    14.11 | DDias, krazy, renatoohaxx, snapy, TMKj        |
|           39 |     5202 | 2024-03-02 | OVERFRAG             | W   | 0.609      | -            | -                | -                | 1 (0.609) |     5.67 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           38 |     5264 | 2024-02-29 | Zero Tenacity        | L   | 0.598      | -            | -                | -                | -         |    -3.70 | aVN, brutmonster, Cjoffo, nEMANHA, simke      |
|           37 |     5278 | 2024-02-29 | GenOne               | L   | 0.597      | -            | -                | -                | -         |   -13.31 | devoduvek, drac, Revol, SIXER, unshaark       |
|           36 |     5304 | 2024-02-28 | RoundsGG             | W   | 0.591      | -            | -                | -                | -         |     5.20 | Kollo, LYNXi, m0n0xx, p12, Welho              |
|           35 |     5416 | 2024-02-26 | Nexus Gaming         | L   | 0.577      | -            | -                | -                | -         |    -6.21 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           34 |     5538 | 2024-02-24 | 500                  | L   | 0.563      | -            | -                | -                | -         |    -8.99 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           33 |     5615 | 2024-02-23 | INGLORIOUS           | L   | 0.557      | -            | -                | -                | -         |   -10.09 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           32 |     5889 | 2024-02-18 | Alliance             | L   | 0.522      | -            | -                | -                | -         |    -8.12 | avid, b0denmaster, PlesseN, robiin, twist     |
|           31 |     6090 | 2024-02-14 | Insilio              | L   | 0.498      | -            | -                | -                | -         |    -5.22 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           30 |     6100 | 2024-02-14 | MOUZ NXT             | L   | 0.497      | -            | -                | -                | -         |    -2.98 | Burmylov, Chr1zN, Neityu, PR, sirah           |
|           29 |     6245 | 2024-02-11 | Young Ninjas         | L   | 0.477      | -            | -                | -                | -         |    -6.13 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           28 |     6267 | 2024-02-10 | Verdant              | L   | 0.470      | -            | -                | -                | -         |    -4.36 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e       |
|           27 |     6328 | 2024-02-08 | Endpoint             | L   | 0.457      | -            | -                | -                | -         |    -5.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher     |
|           26 |     6353 | 2024-02-07 | FAVBET Team          | W   | 0.451      | 0.371        | 0.008 (0.001)    | 0.666 (0.112)    | -         |     7.01 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           25 |     6382 | 2024-02-06 | V1dar Gaming         | L   | 0.443      | -            | -                | -                | -         |   -10.41 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           24 |     6434 | 2024-02-05 | ex-Anonymo Esports   | L   | 0.436      | -            | -                | -                | -         |    -8.98 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           23 |     6474 | 2024-02-04 | ARCRED               | W   | 0.429      | -            | -                | -                | -         |     5.32 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           22 |     6507 | 2024-02-03 | Rhyno Esports        | L   | 0.424      | -            | -                | -                | -         |    -3.92 | DDias, krazy, renatoohaxx, snapy, TMKj        |
|           21 |     6670 | 2024-02-01 | AL-QATRAO            | W   | 0.410      | 0.143        | 0.007 (0.000)    | -                | -         |     4.76 | drext, frozzen, hdstr, nesto, shr             |
|           20 |     6680 | 2024-02-01 | The Agency Clan      | W   | 0.410      | -            | -                | -                | -         |     1.68 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           19 |     6739 | 2024-01-31 | Viperio              | W   | 0.402      | -            | -                | -                | -         |     2.44 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           18 |     6802 | 2024-01-29 | 500                  | L   | 0.392      | -            | -                | -                | -         |    -7.23 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           17 |     6839 | 2024-01-29 | Betera Esports       | L   | 0.389      | -            | -                | -                | -         |    -6.89 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           16 |     7109 | 2024-01-24 | Kappa Bar            | W   | 0.358      | -            | -                | -                | -         |     1.47 | dezt, jayzaR, pupcake, TIM, upE               |
|           15 |     7228 | 2024-01-22 | DASH                 | W   | 0.344      | 0.371        | -                | 0.358 (0.046)    | -         |     2.99 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           14 |     7512 | 2024-01-17 | Insilio              | L   | 0.312      | -            | -                | -                | -         |    -4.08 | faydett, FpSSS, Pipw, Polt, sugaR             |
|           13 |     7524 | 2024-01-17 | Natus Vincere Junior | W   | 0.312      | 0.143        | 0.010 (0.000)    | -                | -         |     4.03 | dem0n, fnl, Krabeni, Magic, makazze           |
|           12 |     7535 | 2024-01-17 | Apeks                | W   | 0.311      | 0.143        | 0.085 (0.004)    | -                | -         |     8.80 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           11 |     7560 | 2024-01-17 | Infinite Gaming      | W   | 0.311      | -            | -                | -                | -         |     1.29 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           10 |     7634 | 2024-01-16 | Aurora Young Blud    | L   | 0.305      | -            | -                | -                | -         |    -5.44 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            9 |     7650 | 2024-01-16 | M1X                  | W   | 0.304      | -            | -                | -                | -         |     1.94 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            8 |     7673 | 2024-01-16 | sappe                | W   | 0.304      | -            | -                | -                | -         |     0.72 | Bernard, G1DO, luosrevo, v1d, v1N             |
|            7 |     7792 | 2024-01-13 | Betera Esports       | L   | 0.283      | -            | -                | -                | -         |    -4.82 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            6 |     7825 | 2024-01-12 | Team Walkover        | W   | 0.279      | -            | -                | -                | -         |     1.22 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            5 |     7843 | 2024-01-12 | Kronjyllands Esport  | W   | 0.278      | -            | -                | -                | -         |     1.02 | Avou, emili0, fa1th, grumpyMonk, Jiace        |
|            4 |     7998 | 2024-01-10 | Pera Esports         | L   | 0.265      | -            | -                | -                | -         |    -3.38 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            3 |     8019 | 2024-01-10 | Aurora Young Blud    | W   | 0.265      | -            | -                | -                | -         |     3.48 | bl1x1, bluewh1te, Easy, sh1geo, VILBy         |
|            2 |     8309 | 2023-12-29 | Metizport            | L   | 0.183      | -            | -                | -                | -         |    -1.97 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            1 |     8316 | 2023-12-27 | The Witchers         | L   | 0.171      | -            | -                | -                | -         |    -3.75 | Dragon, fear, Sdaim, smooya, synyx            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,545.82)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $539.35        | $539.35         |
| 2024-03-03 |      0.616 | $3,255.19      | $2,006.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
