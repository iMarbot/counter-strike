### Roster Details<br />
Team Name: Steel Helmet<br />
Roster: 18yM, AE, captainMo, DD, XiaosaGe<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [234](../standings_global.md)<br />
Regional Rank: [42]( ../standings_asia.md)<br />
Final Rank Value:  678.5<br />
<br />
Final Rank Value (678.5) = Starting Rank Value (705.2) + Head To Head Adjustments (-26.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.385[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.2
- 400 + ( ( 0.154 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 705.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |      845 | 2024-04-19 | High Five (Chinese team)           | L   | 1.000      | -            | -                | -                | -             |   -12.44 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           27 |      896 | 2024-04-18 | ATOX Esports                       | L   | 1.000      | -            | -                | -                | -             |    -3.84 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           26 |     1312 | 2024-04-09 | Nemiga Gaming                      | L   | 1.000      | -            | -                | -                | -             |    -1.43 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           25 |     1352 | 2024-04-08 | Astralis                           | L   | 1.000      | -            | -                | -                | -             |    -0.34 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           24 |     2583 | 2024-03-07 | AP Gaming                          | L   | 0.803      | -            | -                | -                | -             |    -6.14 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           23 |     2590 | 2024-03-06 | ATOX Esports                       | L   | 0.802      | -            | -                | -                | -             |    -2.79 | 18yM, AE, captainMo, ChildKing, XiaosaGe |
|           22 |     4090 | 2024-02-01 | GR Gaming                          | L   | 0.570      | -            | -                | -                | -             |    -6.40 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           21 |     4096 | 2024-02-01 | NewHappy                           | L   | 0.569      | -            | -                | -                | -             |    -7.54 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           20 |     4391 | 2024-01-24 | -72C                               | L   | 0.517      | -            | -                | -                | -             |    -6.94 | 18yM, AE, Attacker, captainMo, XiaosaGe  |
|           19 |     4437 | 2024-01-23 | The Huns Esports                   | L   | 0.510      | -            | -                | -                | -             |    -4.06 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           18 |     4439 | 2024-01-23 | Aravt                              | W   | 0.510      | 0.143        | 0.000 (0.000)    | 0.143 (0.010)    | false (0.000) |     4.96 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           17 |     4442 | 2024-01-23 | Secret.New                         | W   | 0.509      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     2.24 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           16 |     4443 | 2024-01-22 | HXY                                | W   | 0.509      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     2.27 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           15 |     4481 | 2024-01-22 | GR Gaming                          | W   | 0.504      | 0.143        | 0.006 (0.000)    | 0.495 (0.036)    | false (0.000) |    10.03 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           14 |     4483 | 2024-01-22 | SR Nacague                         | W   | 0.504      | 0.143        | 0.000 (0.000)    | 0.022 (0.002)    | false (0.000) |     2.38 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           13 |     4576 | 2024-01-20 | NewHappy                           | L   | 0.489      | -            | -                | -                | -             |    -6.18 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           12 |     4580 | 2024-01-19 | Nirvana Esports                    | W   | 0.488      | 0.143        | 0.000 (0.000)    | 0.031 (0.002)    | false (0.000) |     2.38 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           11 |     4628 | 2024-01-18 | Wings Up Gaming                    | L   | 0.482      | -            | -                | -                | -             |    -7.01 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           10 |     4947 | 2024-01-12 | Rare Atom                          | W   | 0.437      | 0.143        | 0.026 (0.002)    | 0.259 (0.016)    | false (0.000) |     7.79 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            9 |     4950 | 2024-01-12 | Nirvana Esports                    | W   | 0.437      | 0.143        | 0.000 (0.000)    | 0.031 (0.002)    | false (0.000) |     2.19 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            8 |     4956 | 2024-01-11 | WDNMD                              | W   | 0.436      | 0.143        | -                | 0.015 (0.001)    | false (0.000) |     3.69 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            7 |     4968 | 2024-01-11 | Change The Game                    | W   | 0.435      | 0.143        | 0.007 (0.000)    | 0.034 (0.002)    | false (0.000) |     5.90 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            6 |     5267 | 2023-12-24 | NewHappy                           | L   | 0.309      | -            | -                | -                | -             |    -4.16 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            5 |     5275 | 2023-12-23 | Wings Up Gaming                    | W   | 0.303      | 0.143        | 0.018 (0.001)    | 0.172 (0.007)    | -             |     5.03 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            4 |     5280 | 2023-12-23 | Secret (Chinese team)              | W   | 0.302      | 0.143        | -                | 0.018 (0.001)    | -             |     1.56 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            3 |     5287 | 2023-12-22 | Rare Atom                          | L   | 0.302      | -            | -                | -                | -             |    -4.06 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            2 |     6134 | 2023-12-02 | Guangdong University of Technology | L   | 0.163      | -            | -                | -                | -             |    -3.02 | 18yM, AE, captainMo, DD, xiaosaGe        |
|            1 |     6892 | 2023-11-15 | MIRAI Gaming                       | L   | 0.050      | -            | -                | -                | -             |    -0.80 | 18yM, AE, captainMo, DD, XiaosaGe        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
