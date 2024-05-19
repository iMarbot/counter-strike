### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, Gizmy, kRaSnaL, ryu, Woro2k<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [25](../standings_global.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
Final Rank Value:  1330.6<br />
<br />
Final Rank Value (1330.6) = Starting Rank Value (1368.1) + Head To Head Adjustments (-37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.588[<sup>1</sup>](#table2)
- Bounty Collected: 0.558[<sup>2</sup>](#table1)
- Opponent Network: 0.231[<sup>2</sup>](#table1)
- LAN Wins: 0.575[<sup>2</sup>](#table1)

The average of these factors is 0.488<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1368.1
- 400 + ( ( 0.488 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1368.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       17 | 2024-05-05 | FURIA Esports         | W   | 1.000      | 0.889        | 0.384 (0.341)    | 0.361 (0.321)    | 1 (1.000) |    21.51 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           35 |       78 | 2024-05-04 | FORZE Esports         | W   | 1.000      | 0.889        | 0.210 (0.187)    | 0.574 (0.510)    | 1 (1.000) |     9.33 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           34 |      139 | 2024-05-02 | ENCE                  | L   | 1.000      | -            | -                | -                | -         |   -11.33 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           33 |      196 | 2024-05-01 | Team Liquid           | L   | 1.000      | -            | -                | -                | -         |   -10.76 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           32 |      235 | 2024-04-30 | FORZE Esports         | W   | 1.000      | 0.889        | 0.210 (0.187)    | 0.574 (0.510)    | 1 (1.000) |     8.39 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           31 |      803 | 2024-04-19 | OG                    | L   | 1.000      | -            | -                | -                | -         |   -13.35 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           30 |     1108 | 2024-04-13 | Rebels Gaming         | W   | 1.000      | 0.500        | 0.121 (0.060)    | 0.376 (0.188)    | -         |     9.18 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           29 |     1530 | 2024-04-03 | Metizport             | L   | 0.985      | -            | -                | -                | -         |   -22.85 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           28 |     1541 | 2024-04-03 | Apeks                 | W   | 0.984      | 0.143        | 0.253 (0.036)    | 0.459 (0.065)    | -         |    15.68 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           27 |     1573 | 2024-04-02 | GamerLegion           | W   | 0.978      | -            | -                | -                | -         |    21.64 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           26 |     1583 | 2024-04-02 | Ninjas in Pyjamas     | L   | 0.977      | -            | -                | -                | -         |   -21.90 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           25 |     1619 | 2024-03-31 | RUSH B (Russian team) | L   | 0.965      | -            | -                | -                | -         |   -28.85 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           24 |     1695 | 2024-03-28 | Betera Esports        | L   | 0.945      | -            | -                | -                | -         |   -28.00 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           23 |     1820 | 2024-03-26 | System5               | W   | 0.932      | -            | -                | -                | -         |     0.31 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k |
|           22 |     2498 | 2024-03-09 | Metizport             | L   | 0.818      | -            | -                | -                | -         |   -21.25 | DemQQ, kRaSnaL, leen, sdy, Woro2k  |
|           21 |     2553 | 2024-03-07 | Imperial Esports      | W   | 0.806      | 0.535        | 0.674 (0.291)    | 0.549 (0.237)    | -         |    16.28 | DemQQ, kRaSnaL, leen, sdy, Woro2k  |
|           20 |     3326 | 2024-02-21 | Astralis              | L   | 0.703      | -            | -                | -                | -         |    -7.01 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           19 |     3375 | 2024-02-20 | Apeks                 | L   | 0.697      | -            | -                | -                | -         |   -10.82 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           18 |     3405 | 2024-02-19 | Nexus Gaming          | W   | 0.692      | 0.143        | -                | 0.772 (0.076)    | 1 (0.692) |     1.28 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k |
|           17 |     3423 | 2024-02-19 | Gaimin Gladiators     | L   | 0.690      | -            | -                | -                | -         |   -12.52 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k |
|           16 |     3440 | 2024-02-18 | Aurora Gaming         | W   | 0.686      | 0.143        | 1.000 (0.098)    | 0.799 (0.078)    | -         |    14.94 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           15 |     3448 | 2024-02-18 | SINNERS Esports       | W   | 0.685      | -            | -                | -                | -         |     1.93 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           14 |     3493 | 2024-02-17 | Aurora Gaming         | W   | 0.678      | 0.143        | 1.000 (0.097)    | 0.799 (0.077)    | -         |    15.55 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           13 |     3500 | 2024-02-17 | The Chosen Few        | W   | 0.677      | -            | -                | -                | -         |     0.78 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           12 |     3867 | 2024-02-06 | G2 Esports            | L   | 0.604      | -            | -                | -                | -         |    -1.23 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           11 |     3907 | 2024-02-05 | Cloud9                | W   | 0.597      | 1.000        | 0.487 (0.291)    | 0.419 (0.250)    | 1 (0.597) |    16.79 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|           10 |     3930 | 2024-02-04 | GamerLegion           | L   | 0.590      | -            | -                | -                | -         |    -4.12 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            9 |     5358 | 2023-12-17 | Apeks                 | L   | 0.265      | -            | -                | -                | -         |    -3.79 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            8 |     5440 | 2023-12-16 | BESTIA                | W   | 0.259      | -            | -                | -                | 1 (0.259) |     0.19 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            7 |     5566 | 2023-12-15 | Virtus.pro            | L   | 0.253      | -            | -                | -                | -         |    -1.09 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            6 |     5586 | 2023-12-15 | BESTIA                | W   | 0.251      | -            | -                | -                | 1 (0.251) |     0.18 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            5 |     6388 | 2023-11-26 | Eternal Fire          | W   | 0.125      | -            | -                | -                | 1 (0.125) |     3.60 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            4 |     6410 | 2023-11-26 | Virtus.pro            | W   | 0.122      | 0.500        | 0.454 (0.028)    | -                | 1 (0.122) |     3.34 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            3 |     6481 | 2023-11-24 | Nouns Esports         | W   | 0.111      | -            | -                | -                | 1 (0.111) |     0.09 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            2 |     6496 | 2023-11-24 | TYLOO                 | W   | 0.109      | -            | -                | -                | -         |     0.50 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |
|            1 |     7182 | 2023-11-08 | SINNERS Esports       | L   | 0.005      | -            | -                | -                | -         |    -0.15 | br0, DemQQ, kRaSnaL, sdy, Woro2k   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,515.06)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.20) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-10 |      0.826 | $7,500.00      | $6,191.84       |
| 2024-02-11 |      0.638 | $16,000.00     | $10,208.15      |
| 2023-12-17 |      0.266 | $10,000.00     | $2,661.81       |
| 2023-12-10 |      0.219 | $5,500.00      | $1,202.11       |
| 2023-11-26 |      0.125 | $50,000.00     | $6,251.16       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
