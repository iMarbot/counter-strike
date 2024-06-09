### Roster Details<br />
Team Name: Steel Helmet<br />
Roster: 18yM, AE, captainMo, DD, XiaosaGe<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [286](../standings_global.md)<br />
Regional Rank: [44]( ../standings_asia.md)<br />
Final Rank Value:  656.4<br />
<br />
Final Rank Value (656.4) = Starting Rank Value (677.1) + Head To Head Adjustments (-20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.200[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.1
- 400 + ( ( 0.136 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 677.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2780 | 2024-04-19 | NewHappy                           | L   | 0.929      | -            | -                | -                | -         |   -12.08 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           26 |     2840 | 2024-04-18 | ATOX Esports                       | L   | 0.922      | -            | -                | -                | -         |    -1.86 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           25 |     3350 | 2024-04-09 | Nemiga Gaming                      | L   | 0.861      | -            | -                | -                | -         |    -1.44 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           24 |     3395 | 2024-04-08 | Astralis                           | L   | 0.854      | -            | -                | -                | -         |    -0.13 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           23 |     4955 | 2024-03-07 | AP Gaming                          | L   | 0.642      | -            | -                | -                | -         |    -4.96 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           22 |     4964 | 2024-03-06 | ATOX Esports                       | L   | 0.641      | -            | -                | -                | -         |    -0.91 | 18yM, AE, captainMo, ChildKing, XiaosaGe |
|           21 |     6898 | 2024-02-01 | GR Gaming                          | L   | 0.409      | -            | -                | -                | -         |    -4.75 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           20 |     6905 | 2024-02-01 | NewHappy                           | L   | 0.408      | -            | -                | -                | -         |    -6.44 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           19 |     7364 | 2024-01-24 | -72C                               | L   | 0.356      | -            | -                | -                | -         |    -4.74 | 18yM, AE, Attacker, captainMo, XiaosaGe  |
|           18 |     7427 | 2024-01-23 | The Huns Esports                   | L   | 0.349      | -            | -                | -                | -         |    -2.70 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           17 |     7429 | 2024-01-23 | Eruption                           | W   | 0.349      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | 0 (0.000) |     4.20 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           16 |     7433 | 2024-01-23 | Secret.New                         | W   | 0.348      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.84 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           15 |     7435 | 2024-01-22 | HXY                                | W   | 0.348      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.81 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           14 |     7483 | 2024-01-22 | GR Gaming                          | W   | 0.343      | 0.143        | 0.007 (0.000)    | 0.428 (0.021)    | 0 (0.000) |     6.82 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           13 |     7485 | 2024-01-22 | SR Nacague                         | W   | 0.343      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     1.86 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           12 |     7615 | 2024-01-20 | NewHappy                           | L   | 0.328      | -            | -                | -                | -         |    -5.10 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           11 |     7619 | 2024-01-19 | Nirvana Esports                    | W   | 0.327      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     1.80 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           10 |     7683 | 2024-01-18 | Wings Up Gaming                    | L   | 0.321      | -            | -                | -                | -         |    -5.05 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            9 |     8123 | 2024-01-12 | Rare Atom                          | W   | 0.276      | 0.143        | 0.011 (0.000)    | 0.139 (0.005)    | 0 (0.000) |     4.68 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            8 |     8127 | 2024-01-12 | Nirvana Esports                    | W   | 0.276      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     1.54 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            7 |     8133 | 2024-01-11 | WDNMD                              | W   | 0.274      | 0.143        | -                | 0.008 (0.000)    | 0 (0.000) |     2.45 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            6 |     8146 | 2024-01-11 | Change The Game                    | W   | 0.274      | 0.143        | 0.003 (0.000)    | 0.022 (0.001)    | 0 (0.000) |     3.81 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            5 |     8583 | 2023-12-24 | NewHappy                           | L   | 0.148      | -            | -                | -                | -         |    -2.35 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            4 |     8591 | 2023-12-23 | Wings Up Gaming                    | W   | 0.142      | 0.143        | 0.006 (0.000)    | 0.086 (0.002)    | -         |     2.23 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            3 |     8596 | 2023-12-23 | Secret                             | W   | 0.141      | -            | -                | -                | -         |     0.80 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            2 |     8603 | 2023-12-22 | Rare Atom                          | L   | 0.141      | -            | -                | -                | -         |    -2.03 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            1 |     9790 | 2023-12-02 | Guangdong University of Technology | L   | 0.002      | -            | -                | -                | -         |    -0.04 | 18yM, AE, captainMo, DD, xiaosaGe        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,580.65)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
