### Roster Details<br />
Team Name: Steel Helmet<br />
Roster: 18yM, AE, captainMo, DD, XiaosaGe<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [279](../standings_global.md)<br />
Regional Rank: [44]( ../standings_asia.md)<br />
Final Rank Value:  656.4<br />
<br />
Final Rank Value (656.4) = Starting Rank Value (677.5) + Head To Head Adjustments (-21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.200[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.5
- 400 + ( ( 0.136 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 677.5


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
|           27 |     2724 | 2024-04-19 | NewHappy                           | L   | 0.929      | -            | -                | -                | -         |   -11.92 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           26 |     2784 | 2024-04-18 | ATOX Esports                       | L   | 0.922      | -            | -                | -                | -         |    -2.20 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           25 |     3270 | 2024-04-09 | Nemiga Gaming                      | L   | 0.861      | -            | -                | -                | -         |    -1.39 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           24 |     3314 | 2024-04-08 | Astralis                           | L   | 0.854      | -            | -                | -                | -         |    -0.13 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           23 |     4825 | 2024-03-07 | AP Gaming                          | L   | 0.642      | -            | -                | -                | -         |    -4.94 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           22 |     4833 | 2024-03-06 | ATOX Esports                       | L   | 0.641      | -            | -                | -                | -         |    -1.11 | 18yM, AE, captainMo, ChildKing, XiaosaGe |
|           21 |     6689 | 2024-02-01 | GR Gaming                          | L   | 0.409      | -            | -                | -                | -         |    -4.76 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           20 |     6696 | 2024-02-01 | NewHappy                           | L   | 0.408      | -            | -                | -                | -         |    -6.44 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           19 |     7129 | 2024-01-24 | -72C                               | L   | 0.356      | -            | -                | -                | -         |    -4.75 | 18yM, AE, Attacker, captainMo, XiaosaGe  |
|           18 |     7187 | 2024-01-23 | The Huns Esports                   | L   | 0.349      | -            | -                | -                | -         |    -2.71 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           17 |     7189 | 2024-01-23 | Eruption                           | W   | 0.349      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | 0 (0.000) |     4.23 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           16 |     7193 | 2024-01-23 | Secret.New                         | W   | 0.348      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.79 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           15 |     7194 | 2024-01-22 | HXY                                | W   | 0.348      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     1.81 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           14 |     7240 | 2024-01-22 | GR Gaming                          | W   | 0.343      | 0.143        | 0.007 (0.000)    | 0.428 (0.021)    | 0 (0.000) |     6.81 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           13 |     7242 | 2024-01-22 | SR Nacague                         | W   | 0.343      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     1.86 | 18yM, Attacker, captainMo, DD, XiaosaGe  |
|           12 |     7371 | 2024-01-20 | NewHappy                           | L   | 0.328      | -            | -                | -                | -         |    -5.10 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           11 |     7375 | 2024-01-19 | Nirvana Esports                    | W   | 0.327      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     1.79 | 18yM, AE, captainMo, DD, XiaosaGe        |
|           10 |     7436 | 2024-01-18 | Wings Up Gaming                    | L   | 0.321      | -            | -                | -                | -         |    -5.05 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            9 |     7870 | 2024-01-12 | Rare Atom                          | W   | 0.276      | 0.143        | 0.011 (0.000)    | 0.139 (0.005)    | 0 (0.000) |     4.68 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            8 |     7874 | 2024-01-12 | Nirvana Esports                    | W   | 0.276      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     1.54 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            7 |     7880 | 2024-01-11 | WDNMD                              | W   | 0.274      | 0.143        | -                | 0.008 (0.000)    | 0 (0.000) |     2.44 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            6 |     7893 | 2024-01-11 | Change The Game                    | W   | 0.274      | 0.143        | 0.003 (0.000)    | 0.022 (0.001)    | 0 (0.000) |     3.81 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            5 |     8326 | 2023-12-24 | NewHappy                           | L   | 0.148      | -            | -                | -                | -         |    -2.35 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            4 |     8334 | 2023-12-23 | Wings Up Gaming                    | W   | 0.142      | 0.143        | 0.006 (0.000)    | 0.086 (0.002)    | -         |     2.23 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            3 |     8339 | 2023-12-23 | Secret                             | W   | 0.141      | 0.143        | -                | 0.006 (0.000)    | -         |     0.79 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            2 |     8346 | 2023-12-22 | Rare Atom                          | L   | 0.141      | -            | -                | -                | -         |    -2.03 | 18yM, AE, captainMo, DD, XiaosaGe        |
|            1 |     9508 | 2023-12-02 | Guangdong University of Technology | L   | 0.002      | -            | -                | -                | -         |    -0.04 | 18yM, AE, captainMo, DD, xiaosaGe        |

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
