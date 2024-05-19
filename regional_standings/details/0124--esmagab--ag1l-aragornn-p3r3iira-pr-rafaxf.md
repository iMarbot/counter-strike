### Roster Details<br />
Team Name: EsmagaB<br />
Roster: Ag1l, aragornN, P3R3IIRA, pr, rafaxF<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [124](../standings_global.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
Final Rank Value:  812.4<br />
<br />
Final Rank Value (812.4) = Starting Rank Value (874.7) + Head To Head Adjustments (-62.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.358[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.105[<sup>2</sup>](#table1)
- LAN Wins: 0.172[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 874.7
- 400 + ( ( 0.239 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 874.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      202 | 2024-05-01 | Young Gods               | W   | 1.000      | 0.371        | -                | 0.204 (0.076)    | false (0.000) |     5.16 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           46 |      469 | 2024-04-25 | Grindas                  | L   | 1.000      | -            | -                | -                | -             |   -19.50 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           45 |      521 | 2024-04-24 | RUBY                     | W   | 1.000      | 0.371        | 0.012 (0.004)    | 0.882 (0.327)    | false (0.000) |    22.75 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           44 |      572 | 2024-04-23 | DMS                      | L   | 1.000      | -            | -                | -                | -             |   -16.33 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           43 |      710 | 2024-04-20 | 1win                     | L   | 1.000      | -            | -                | -                | -             |   -17.55 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           42 |      819 | 2024-04-19 | Team Secret              | W   | 1.000      | 0.143        | -                | 0.368 (0.053)    | false (0.000) |    10.53 | anarkez, Kind0, Maze, NOPEEj, Tauson          |
|           41 |      874 | 2024-04-18 | Illuminar Gaming         | L   | 1.000      | -            | -                | -                | -             |   -15.59 | ANeraX, Furlan, keis, phr, ultimate           |
|           40 |      946 | 2024-04-17 | 500                      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.660 (0.094)    | false (0.000) |    20.85 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           39 |     1172 | 2024-04-11 | AscendX Esports          | W   | 1.000      | -            | -                | -                | false (0.000) |     2.71 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           38 |     1370 | 2024-04-07 | Team PeeP                | W   | 1.000      | -            | -                | -                | false (0.000) |     2.96 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF          |
|           37 |     1749 | 2024-03-27 | 500                      | L   | 0.938      | -            | -                | -                | -             |   -11.31 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           36 |     1817 | 2024-03-26 | Fnatic                   | W   | 0.932      | 0.143        | 0.334 (0.044)    | 0.683 (0.091)    | false (0.000) |    26.53 | P3R3IIRA, pr, rafaxF, SeabraEZ, Sprayy        |
|           35 |     2814 | 2024-03-03 | Rhyno Esports            | W   | 0.777      | 0.143        | 0.047 (0.005)    | 0.446 (0.050)    | true (0.777)  |    15.42 | DDias, krazy, renatoohaxx, snapy, TMKj        |
|           34 |     2892 | 2024-03-02 | OVERFRAG                 | W   | 0.770      | 0.143        | 0.004 (0.000)    | -                | true (0.770)  |     5.21 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           33 |     2944 | 2024-02-29 | Zero Tenacity            | L   | 0.759      | -            | -                | -                | -             |    -7.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke      |
|           32 |     2958 | 2024-02-29 | GenOne                   | L   | 0.758      | -            | -                | -                | -             |   -18.52 | devoduvek, drac, Revol, SIXER, unshaark       |
|           31 |     2978 | 2024-02-28 | RoundsGG                 | W   | 0.752      | 0.371        | -                | 0.170 (0.048)    | false (0.000) |     9.32 | Kollo, LYNXi, m0n0xx, p12, Welho              |
|           30 |     3073 | 2024-02-26 | Nexus Gaming             | L   | 0.738      | -            | -                | -                | -             |    -8.32 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           29 |     3157 | 2024-02-24 | 500                      | L   | 0.725      | -            | -                | -                | -             |   -10.51 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           28 |     3218 | 2024-02-23 | INGLORIOUS               | L   | 0.718      | -            | -                | -                | -             |   -12.02 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           27 |     3461 | 2024-02-18 | Alliance                 | L   | 0.684      | -            | -                | -                | -             |   -10.31 | avid, b0denmaster, PlesseN, robiin, twist     |
|           26 |     3619 | 2024-02-14 | Insilio                  | L   | 0.659      | -            | -                | -                | -             |    -6.74 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           25 |     3628 | 2024-02-14 | MOUZ NXT                 | L   | 0.658      | -            | -                | -                | -             |    -4.50 | Burmylov, Chr1zN, Neityu, PR, sirah           |
|           24 |     3756 | 2024-02-11 | Young Ninjas             | L   | 0.638      | -            | -                | -                | -             |    -7.69 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           23 |     3819 | 2024-02-08 | Endpoint                 | L   | 0.618      | -            | -                | -                | -             |    -9.65 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher     |
|           22 |     3838 | 2024-02-07 | BLESSED (Ukrainian team) | W   | 0.612      | 0.371        | 0.018 (0.004)    | 0.781 (0.178)    | -             |     8.10 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           21 |     3863 | 2024-02-06 | V1dar Gaming             | L   | 0.604      | -            | -                | -                | -             |   -15.43 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           20 |     3933 | 2024-02-04 | ARCRED                   | W   | 0.590      | 0.143        | 0.004 (0.000)    | 0.825 (0.070)    | -             |     8.11 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           19 |     3952 | 2024-02-03 | Rhyno Esports            | L   | 0.585      | -            | -                | -                | -             |    -8.22 | DDias, krazy, renatoohaxx, snapy, TMKj        |
|           18 |     4073 | 2024-02-01 | AL-QATRAO                | W   | 0.571      | -            | -                | -                | -             |     4.94 | drext, frozzen, hdstr, nesto, shr             |
|           17 |     4082 | 2024-02-01 | The Agency Clan          | W   | 0.571      | -            | -                | -                | -             |     2.13 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           16 |     4127 | 2024-01-31 | Viperio                  | W   | 0.563      | 0.333        | -                | 0.321 (0.060)    | -             |     3.50 | mAnGo, MMS, pandi7o, ReegaN, zodi             |
|           15 |     4175 | 2024-01-29 | 500                      | L   | 0.553      | -            | -                | -                | -             |   -10.08 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           14 |     4199 | 2024-01-29 | Betera Esports           | L   | 0.551      | -            | -                | -                | -             |   -10.26 | alex666, lollipop21k, MaSvAl, nifee, sad      |
|           13 |     4377 | 2024-01-24 | Kappa Bar                | W   | 0.519      | -            | -                | -                | -             |     3.77 | dezt, jayzaR, pupcake, TIM, upE               |
|           12 |     4470 | 2024-01-22 | DASH                     | W   | 0.505      | -            | -                | -                | -             |     4.22 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|           11 |     4693 | 2024-01-17 | Insilio                  | L   | 0.473      | -            | -                | -                | -             |    -6.27 | faydett, FpSSS, Pipw, Polt, sugaR             |
|           10 |     4704 | 2024-01-17 | Natus Vincere Junior     | W   | 0.473      | 0.143        | 0.025 (0.002)    | -                | -             |     6.50 | dem0n, fnl, Krabeni, Magic, makazze           |
|            9 |     4713 | 2024-01-17 | Apeks                    | W   | 0.472      | 0.143        | 0.253 (0.017)    | -                | -             |    14.20 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            8 |     4733 | 2024-01-17 | Infinite Gaming          | W   | 0.472      | -            | -                | -                | -             |     1.04 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            7 |     4786 | 2024-01-16 | Aurora Young Blud        | L   | 0.466      | -            | -                | -                | -             |    -7.92 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            6 |     4918 | 2024-01-12 | Team Walkover            | W   | 0.440      | -            | -                | -                | -             |     1.94 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            5 |     4928 | 2024-01-12 | Kronjyllands Esport      | W   | 0.439      | -            | -                | -                | -             |     1.52 | Avou, emili0, fa1th, grumpyMonk, Jiace        |
|            4 |     5040 | 2024-01-10 | Pera Esports             | L   | 0.426      | -            | -                | -                | -             |    -5.61 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            3 |     5055 | 2024-01-10 | Aurora Young Blud        | W   | 0.426      | 0.143        | 0.017 (0.001)    | -                | -             |     5.88 | bl1x1, bluewh1te, Easy, sh1geo, VILBy         |
|            2 |     5250 | 2023-12-29 | Metizport                | L   | 0.344      | -            | -                | -                | -             |    -3.44 | Ag1l, aragornN, NOPEEj, pr, rafaxF            |
|            1 |     5257 | 2023-12-27 | The Witchers             | L   | 0.332      | -            | -                | -                | -             |    -6.58 | Dragon, fear, Sdaim, smooya, synyx            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,530.76)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
