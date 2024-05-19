### Roster Details<br />
Team Name: Begrip Gaming<br />
Roster: Ariant0, Karma, Reedz, titulus, treckiz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [335](../standings_global.md)<br />
Regional Rank: [205]( ../standings_europe.md)<br />
Final Rank Value:  537.4<br />
<br />
Final Rank Value (537.4) = Starting Rank Value (639.8) + Head To Head Adjustments (-102.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.8
- 400 + ( ( 0.121 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 639.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       46 | 2024-05-04 | Lemoncats             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.076 (0.011)    | false (0.000) |    12.72 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           29 |       92 | 2024-05-03 | Endless b00mers       | L   | 1.000      | -            | -                | -                | -             |   -17.56 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           28 |      182 | 2024-05-01 | Podwars               | L   | 1.000      | -            | -                | -                | -             |   -17.77 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           27 |      510 | 2024-04-24 | Johnny Speeds         | L   | 1.000      | -            | -                | -                | -             |    -3.06 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           26 |     1003 | 2024-04-16 | Full Kareta           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |     7.85 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           25 |     1136 | 2024-04-12 | Young Gods            | L   | 1.000      | -            | -                | -                | -             |   -19.70 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           24 |     1209 | 2024-04-10 | AURA (Swedish team)   | L   | 1.000      | -            | -                | -                | -             |   -13.05 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           23 |     1911 | 2024-03-23 | KILLBOX               | L   | 0.911      | -            | -                | -                | -             |   -18.53 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           22 |     2026 | 2024-03-20 | E-Town Gaming         | W   | 0.892      | 0.143        | 0.000 (0.000)    | 0.033 (0.004)    | false (0.000) |     6.69 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           21 |     2133 | 2024-03-17 | Kappa Borr            | L   | 0.872      | -            | -                | -                | -             |   -16.05 | Ariant0, Karma, Reedz, titulus, treckiz    |
|           20 |     2480 | 2024-03-09 | XI Esport             | L   | 0.819      | -            | -                | -                | -             |   -11.63 | Ariant0, Karma, nimaaz, Reedz, shateri     |
|           19 |     2686 | 2024-03-05 | EP Genesis            | L   | 0.792      | -            | -                | -                | -             |   -16.25 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           18 |     2764 | 2024-03-04 | GamerLegion Academy   | L   | 0.784      | -            | -                | -                | -             |    -7.18 | Darber, Goody, leaf, nestee, rud           |
|           17 |     2882 | 2024-03-02 | Preasy Esport         | L   | 0.771      | -            | -                | -                | -             |    -9.37 | beccie, Equip, Griller, Skejs, VireZ       |
|           16 |     3103 | 2024-02-25 | Natus Vincere Youth   | W   | 0.731      | 0.289        | 0.013 (0.003)    | 0.306 (0.065)    | false (0.000) |    14.20 | cmtry, dziugss, froz1k, qzr, UNBR0KEN      |
|           15 |     3310 | 2024-02-21 | Dynamo Eclot Thunders | W   | 0.704      | 0.289        | 0.000 (0.000)    | 0.035 (0.007)    | false (0.000) |     4.34 | Ariant0, Karma, Reedz, shateri, titulus    |
|           14 |     4386 | 2024-01-24 | AVEZ                  | L   | 0.518      | -            | -                | -                | -             |    -7.34 | Ariant0, Karma, Reedz, shateri, titulus    |
|           13 |     4546 | 2024-01-20 | Young Gods            | W   | 0.492      | 0.289        | 0.000 (0.000)    | 0.204 (0.029)    | false (0.000) |     4.32 | Cham, Focus, MaiL09, viz, Wonder           |
|           12 |     5205 | 2024-01-03 | Lilmix                | L   | 0.379      | -            | -                | -                | -             |    -5.14 | Ariant0, Karma, Reedz, shateri, titulus    |
|           11 |     5216 | 2024-01-03 | Kappa Bar             | W   | 0.378      | 0.143        | 0.002 (0.000)    | 0.149 (0.008)    | false (0.000) |     6.57 | Ariant0, Karma, Reedz, shateri, titulus    |
|           10 |     5883 | 2023-12-07 | Monte Gen             | L   | 0.199      | -            | -                | -                | -             |    -1.85 | Gizmy, leen, n0te, ryu, shield             |
|            9 |     5939 | 2023-12-06 | GamerLegion Academy   | L   | 0.191      | -            | -                | -                | -             |    -1.28 | aNdu, Darber, leaf, nestee, rud            |
|            8 |     5965 | 2023-12-05 | Young Gods            | W   | 0.186      | 0.143        | 0.000 (0.000)    | 0.204 (0.005)    | false (0.000) |     1.73 | Focus, Lindcs, MaiL09, viz, Wonder         |
|            7 |     6018 | 2023-12-04 | Monte Gen             | W   | 0.178      | 0.289        | 0.019 (0.001)    | 0.155 (0.008)    | false (0.000) |     3.97 | Gizmy, leen, n0te, ryu, shield             |
|            6 |     6165 | 2023-12-01 | Natus Vincere Youth   | W   | 0.158      | 0.289        | 0.013 (0.001)    | 0.306 (0.014)    | false (0.000) |     3.13 | Ariant0, Karma, Reedz, shateri, titulus    |
|            5 |     6200 | 2023-11-30 | LODIS                 | W   | 0.152      | -            | -                | -                | -             |     1.02 | atoom, freo, Majster, n0tice, wonsz        |
|            4 |     6324 | 2023-11-28 | FALKE ESPORTS         | L   | 0.138      | -            | -                | -                | -             |    -2.99 | Ariant0, Karma, Reedz, shateri, titulus    |
|            3 |     6729 | 2023-11-18 | Alliance              | L   | 0.071      | -            | -                | -                | -             |    -0.45 | avid, b0denmaster, PlesseN, robiin, twist  |
|            2 |     6995 | 2023-11-12 | Lemondogs             | W   | 0.032      | -            | -                | -                | -             |     0.29 | flaw, hemzk9, pyth, Radifaction, xelos     |
|            1 |     7176 | 2023-11-08 | Pungrottorna          | W   | 0.005      | -            | -                | -                | -             |     0.05 | Ariant0, Karma, Reedz, shateri, titulus    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102.62)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
