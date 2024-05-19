### Roster Details<br />
Team Name: TBA.ECF<br />
Roster: amster, byr9, kensizor, Polbandana, s4ltovsk1yy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [126](../standings_global.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
Final Rank Value:  809.2<br />
<br />
Final Rank Value (809.2) = Starting Rank Value (632.5) + Head To Head Adjustments (176.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.117[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.5
- 400 + ( ( 0.117 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 632.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      194 | 2024-05-01 | ThunderFlash                 | L   | 1.000      | -            | -                | -                | -             |   -14.68 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           28 |      258 | 2024-04-30 | Copenhagen Wolves            | W   | 1.000      | 0.333        | -                | 0.417 (0.139)    | false (0.000) |     9.07 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           27 |      288 | 2024-04-29 | Gaimin Gladiators            | W   | 1.000      | 0.384        | 0.194 (0.075)    | 0.989 (0.380)    | false (0.000) |    29.42 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           26 |      493 | 2024-04-25 | HAVU Gaming                  | W   | 1.000      | 0.384        | 0.024 (0.009)    | 0.213 (0.082)    | false (0.000) |    14.07 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           25 |      522 | 2024-04-24 | Nemiga Gaming                | L   | 1.000      | -            | -                | -                | -             |    -2.21 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           24 |      530 | 2024-04-24 | Eternal Fire Academy         | W   | 1.000      | -            | -                | -                | false (0.000) |     6.10 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           23 |     1005 | 2024-04-16 | Young Ninjas                 | W   | 1.000      | 0.371        | 0.074 (0.027)    | 0.338 (0.126)    | false (0.000) |    24.12 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           22 |     1800 | 2024-03-26 | TSM                          | L   | 0.932      | -            | -                | -                | -             |   -15.33 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           21 |     2108 | 2024-03-18 | DASH                         | W   | 0.876      | -            | -                | -                | false (0.000) |    13.94 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           20 |     2136 | 2024-03-17 | L&G                          | W   | 0.872      | 0.143        | 0.012 (0.001)    | -                | false (0.000) |    12.76 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           19 |     2147 | 2024-03-17 | DASH                         | L   | 0.871      | -            | -                | -                | -             |   -13.18 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           18 |     2173 | 2024-03-16 | ROSOMAHA                     | W   | 0.865      | -            | -                | -                | false (0.000) |     8.28 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |
|           17 |     2914 | 2024-03-01 | Endpoint                     | L   | 0.765      | -            | -                | -                | -             |    -8.57 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher       |
|           16 |     3248 | 2024-02-22 | DASH                         | W   | 0.712      | 0.371        | -                | 0.251 (0.066)    | false (0.000) |    11.56 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           15 |     3299 | 2024-02-21 | CYBERSHOKE Esports           | W   | 0.705      | 0.371        | 0.004 (0.001)    | 0.220 (0.058)    | false (0.000) |    11.10 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           14 |     3350 | 2024-02-20 | Ex-Anonymo Esports           | W   | 0.698      | 0.371        | 0.019 (0.005)    | 0.295 (0.077)    | -             |    13.17 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           13 |     3529 | 2024-02-16 | Team Spirit Academy          | W   | 0.672      | 0.371        | 0.021 (0.005)    | 0.422 (0.105)    | -             |    14.63 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           12 |     3818 | 2024-02-08 | GenOne                       | W   | 0.618      | 0.371        | -                | 0.323 (0.074)    | -             |     7.08 | devoduvek, drac, Revol, SIXER, unshaark         |
|           11 |     3946 | 2024-02-03 | UNiTY esports (Slovak team)  | W   | 0.585      | 0.143        | 0.055 (0.005)    | 0.727 (0.061)    | -             |    15.11 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|           10 |     3954 | 2024-02-03 | 9Pandas                      | W   | 0.585      | 0.143        | 0.085 (0.007)    | -                | -             |    17.28 | clax, d1Ledez, glowiing, iDISBALANCE, seized    |
|            9 |     3983 | 2024-02-03 | HIMARSpeek                   | W   | 0.584      | -            | -                | -                | -             |     3.58 | 2kEloLover, darky, GeT FiGhT, OG_JOY, steffe    |
|            8 |     4167 | 2024-01-29 | Insilio                      | L   | 0.553      | -            | -                | -                | -             |    -2.91 | faydett, FpSSS, Pipw, Polt, sugaR               |
|            7 |     4179 | 2024-01-29 | ALTERNATE aTTaX              | W   | 0.553      | 0.143        | 0.110 (0.009)    | -                | -             |    15.68 | amster, byr9, munch, Polbandana, s4ltovsk1yy    |
|            6 |     4726 | 2024-01-17 | PARIVISION                   | L   | 0.472      | -            | -                | -                | -             |    -3.23 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            5 |     5085 | 2024-01-09 | Entropiq                     | L   | 0.419      | -            | -                | -                | -             |    -3.93 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            4 |     5090 | 2024-01-09 | Ex-Anonymo Esports           | W   | 0.418      | -            | -                | -                | -             |     9.35 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            3 |     5116 | 2024-01-09 | TEAM MAX (European mix-team) | W   | 0.418      | -            | -                | -                | -             |     4.43 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            2 |     6868 | 2023-11-15 | FORZE Esports                | L   | 0.052      | -            | -                | -                | -             |    -0.50 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy  |
|            1 |     6880 | 2023-11-15 | TUSTE CHOPAKI                | W   | 0.052      | -            | -                | -                | -             |     0.50 | asran, GruBy, mASKED, Mride, sk1tt              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
