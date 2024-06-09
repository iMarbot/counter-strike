### Roster Details<br />
Team Name: esmagaB<br />
Roster: Ag1l, aragornN, P3R3IIRA, pr, rafaxF<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [123](../standings_global.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
Final Rank Value:  826.3<br />
<br />
Final Rank Value (826.3) = Starting Rank Value (859.9) + Head To Head Adjustments (-33.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.293[<sup>2</sup>](#table1)
- Opponent Network: 0.157[<sup>2</sup>](#table1)
- LAN Wins: 0.130[<sup>2</sup>](#table1)

The average of these factors is 0.226<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 859.9
- 400 + ( ( 0.226 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 859.9


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
|           65 |       83 | 2024-05-29 | TNL                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.60 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           64 |      351 | 2024-05-24 | CYBERSHOKE Esports   | L   | 1.000      | -            | -                | -                | -         |   -17.94 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           63 |      363 | 2024-05-24 | GamerLegion Academy  | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    13.66 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           62 |      402 | 2024-05-23 | Team Spirit Academy  | L   | 1.000      | -            | -                | -                | -         |   -17.27 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           61 |     1080 | 2024-05-16 | VP.Prodigy           | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.829 (0.309)    | 0 (0.000) |    15.89 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           60 |     1321 | 2024-05-13 | Lilmix               | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.593 (0.221)    | 0 (0.000) |    14.92 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           59 |     1456 | 2024-05-11 | AL-QATRAO            | L   | 1.000      | -            | -                | -                | -         |   -17.09 | Ag1l, aragornN, fox, pr, rafaxF               |
|           58 |     1641 | 2024-05-08 | RoundsGG             | W   | 1.000      | 0.372        | -                | 0.251 (0.094)    | 0 (0.000) |     6.45 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           57 |     1941 | 2024-05-02 | ENRAGE               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.42 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           56 |     2011 | 2024-05-01 | Young Gods           | W   | 1.000      | 0.372        | -                | 0.240 (0.089)    | 0 (0.000) |     6.68 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           55 |     2347 | 2024-04-25 | Grannys Knockers     | L   | 0.970      | -            | -                | -                | -         |   -16.72 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           54 |     2405 | 2024-04-24 | RUBY                 | W   | 0.964      | 0.372        | 0.007 (0.002)    | 0.738 (0.265)    | 0 (0.000) |    21.24 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           53 |     2463 | 2024-04-23 | DMS                  | L   | 0.957      | -            | -                | -                | -         |   -13.55 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           52 |     2630 | 2024-04-20 | 1win                 | L   | 0.937      | -            | -                | -                | -         |    -7.85 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           51 |     2753 | 2024-04-19 | Team Secret          | W   | 0.930      | -            | -                | -                | -         |     9.04 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           50 |     2813 | 2024-04-18 | Illuminar Gaming     | L   | 0.924      | -            | -                | -                | -         |   -14.97 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           49 |     2903 | 2024-04-17 | 500                  | W   | 0.916      | 0.143        | -                | 0.479 (0.063)    | -         |    18.07 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           48 |     2970 | 2024-04-16 | ex-KRC Genk Esports  | W   | 0.910      | 0.372        | -                | 0.173 (0.058)    | -         |     9.16 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           47 |     3181 | 2024-04-11 | AscendX Esports      | W   | 0.877      | -            | -                | -                | -         |     2.55 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           46 |     3420 | 2024-04-07 | HOTU                 | L   | 0.850      | -            | -                | -                | -         |   -13.13 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           45 |     3427 | 2024-04-07 | Team PeeP            | W   | 0.849      | -            | -                | -                | -         |     6.20 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           44 |     3898 | 2024-03-27 | 500                  | L   | 0.777      | -            | -                | -                | -         |   -10.38 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           43 |     3980 | 2024-03-26 | Fnatic               | W   | 0.771      | 0.143        | 0.147 (0.016)    | -                | -         |    21.01 | P3R3IIRA, pr, rafaxF, SeabraEZ, Sprayy        |
|           42 |     5251 | 2024-03-03 | Rhyno Esports        | W   | 0.616      | 0.143        | 0.029 (0.003)    | -                | 1 (0.616) |    14.07 | DDias, krazy, renatoohaxx, snapy, TMKj        |
|           41 |     5351 | 2024-03-02 | OVERFRAG             | W   | 0.609      | -            | -                | -                | 1 (0.609) |     5.47 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           40 |     5414 | 2024-02-29 | Zero Tenacity        | L   | 0.598      | -            | -                | -                | -         |    -4.09 | aVN, brutmonster, Cjoffo, nEMANHA, simke      |
|           39 |     5428 | 2024-02-29 | GenOne               | L   | 0.597      | -            | -                | -                | -         |   -13.43 | devoduvek, drac, Revol, SIXER, unshaark       |
|           38 |     5455 | 2024-02-28 | RoundsGG             | W   | 0.591      | -            | -                | -                | -         |     5.46 | Kollo, LYNXi, m0n0xx, p12, Welho              |
|           37 |     5573 | 2024-02-26 | Nexus Gaming         | L   | 0.577      | -            | -                | -                | -         |    -6.81 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           36 |     5698 | 2024-02-24 | 500                  | L   | 0.563      | -            | -                | -                | -         |    -9.08 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           35 |     5775 | 2024-02-23 | INGLORIOUS           | L   | 0.557      | -            | -                | -                | -         |   -10.22 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           34 |     6062 | 2024-02-18 | Alliance             | L   | 0.522      | -            | -                | -                | -         |    -8.29 | avid, b0denmaster, PlesseN, robiin, twist     |
|           33 |     6271 | 2024-02-14 | Insilio              | L   | 0.498      | -            | -                | -                | -         |    -5.46 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           32 |     6281 | 2024-02-14 | MOUZ NXT             | L   | 0.497      | -            | -                | -                | -         |    -2.96 | Burmylov, Chr1zN, Neityu, PR, sirah           |
|           31 |     6433 | 2024-02-11 | Young Ninjas         | L   | 0.477      | -            | -                | -                | -         |    -6.35 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           30 |     6455 | 2024-02-10 | Verdant              | L   | 0.470      | -            | -                | -                | -         |    -4.47 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e       |
|           29 |     6516 | 2024-02-08 | Endpoint             | L   | 0.457      | -            | -                | -                | -         |    -5.25 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher     |
|           28 |     6545 | 2024-02-07 | FAVBET Team          | W   | 0.451      | 0.371        | 0.008 (0.001)    | 0.845 (0.142)    | -         |     6.88 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           27 |     6573 | 2024-02-06 | Lemondogs            | W   | 0.444      | -            | -                | -                | -         |     2.87 | dZ, hechtikal, hemzk9, xelos, zeak            |
|           26 |     6578 | 2024-02-06 | V1dar Gaming         | L   | 0.443      | -            | -                | -                | -         |   -10.28 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           25 |     6626 | 2024-02-05 | VaselineWorms        | W   | 0.437      | 0.371        | -                | 0.418 (0.068)    | -         |     4.41 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           24 |     6635 | 2024-02-05 | ex-Anonymo Esports   | L   | 0.436      | -            | -                | -                | -         |    -9.08 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           23 |     6677 | 2024-02-04 | ARCRED               | W   | 0.429      | -            | -                | -                | -         |     5.29 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           22 |     6710 | 2024-02-03 | Rhyno Esports        | L   | 0.424      | -            | -                | -                | -         |    -3.94 | DDias, krazy, renatoohaxx, snapy, TMKj        |
|           21 |     6879 | 2024-02-01 | AL-QATRAO            | W   | 0.410      | 0.143        | 0.007 (0.000)    | -                | -         |     4.70 | drext, frozzen, hdstr, nesto, shr             |
|           20 |     6889 | 2024-02-01 | The Agency Clan      | W   | 0.410      | -            | -                | -                | -         |     1.64 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           19 |     6952 | 2024-01-31 | Viperio              | W   | 0.402      | -            | -                | -                | -         |     2.44 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           18 |     7018 | 2024-01-29 | 500                  | L   | 0.392      | -            | -                | -                | -         |    -7.28 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           17 |     7055 | 2024-01-29 | Betera Esports       | L   | 0.389      | -            | -                | -                | -         |    -6.92 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           16 |     7339 | 2024-01-24 | Kappa Bar            | W   | 0.358      | -            | -                | -                | -         |     1.45 | dezt, jayzaR, pupcake, TIM, upE               |
|           15 |     7471 | 2024-01-22 | DASH                 | W   | 0.344      | -            | -                | -                | -         |     3.08 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           14 |     7761 | 2024-01-17 | Insilio              | L   | 0.312      | -            | -                | -                | -         |    -4.23 | faydett, FpSSS, Pipw, Polt, sugaR             |
|           13 |     7773 | 2024-01-17 | Natus Vincere Junior | W   | 0.312      | 0.143        | 0.010 (0.000)    | -                | -         |     4.00 | dem0n, fnl, Krabeni, Magic, makazze           |
|           12 |     7784 | 2024-01-17 | Apeks                | W   | 0.311      | 0.143        | 0.085 (0.004)    | -                | -         |     8.77 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           11 |     7809 | 2024-01-17 | Infinite Gaming      | W   | 0.311      | -            | -                | -                | -         |     1.27 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           10 |     7883 | 2024-01-16 | Aurora Young Blud    | L   | 0.305      | -            | -                | -                | -         |    -5.44 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            9 |     7899 | 2024-01-16 | M1X                  | W   | 0.304      | -            | -                | -                | -         |     1.90 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            8 |     7922 | 2024-01-16 | sappe                | W   | 0.304      | -            | -                | -                | -         |     0.71 | Bernard, G1DO, luosrevo, v1d, v1N             |
|            7 |     8045 | 2024-01-13 | Betera Esports       | L   | 0.283      | -            | -                | -                | -         |    -4.86 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            6 |     8078 | 2024-01-12 | Team Walkover        | W   | 0.279      | -            | -                | -                | -         |     1.20 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            5 |     8096 | 2024-01-12 | Kronjyllands Esport  | W   | 0.278      | -            | -                | -                | -         |     1.00 | Avou, emili0, fa1th, grumpyMonk, Jiace        |
|            4 |     8252 | 2024-01-10 | Pera Esports         | L   | 0.265      | -            | -                | -                | -         |    -3.49 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            3 |     8273 | 2024-01-10 | Aurora Young Blud    | W   | 0.265      | -            | -                | -                | -         |     3.48 | bl1x1, bluewh1te, Easy, sh1geo, VILBy         |
|            2 |     8566 | 2023-12-29 | Metizport            | L   | 0.183      | -            | -                | -                | -         |    -1.98 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            1 |     8573 | 2023-12-27 | The Witchers         | L   | 0.171      | -            | -                | -                | -         |    -3.77 | Dragon, fear, Sdaim, smooya, synyx            |

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
