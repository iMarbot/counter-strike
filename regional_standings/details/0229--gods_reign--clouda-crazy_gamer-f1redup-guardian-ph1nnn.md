### Roster Details<br />
Team Name: Gods Reign<br />
Roster: clouda, Crazy_Gamer, f1redup, GuardiaN, Ph1NNN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [229](../standings_global.md)<br />
Regional Rank: [28]( ../standings_asia.md)<br />
Final Rank Value:  702.3<br />
<br />
Final Rank Value (702.3) = Starting Rank Value (703.8) + Head To Head Adjustments (-1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.8
- 400 + ( ( 0.149 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 703.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     6534 | 2024-02-08 | True Rippers       | L   | 0.455      | -            | -                | -                | -         |    -7.06 | clouda, Crazy_Gamer, f1redup, GuardiaN, Ph1NNN |
|           25 |     6539 | 2024-02-07 | Made In 4No        | W   | 0.454      | 0.435        | 0.010 (0.002)    | 0.106 (0.021)    | 1 (0.454) |     6.93 | clouda, Crazy_Gamer, f1redup, GuardiaN, Ph1NNN |
|           24 |     6642 | 2024-02-05 | GR Gaming          | L   | 0.435      | -            | -                | -                | -         |    -5.24 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           23 |     6846 | 2024-02-02 | Gods Reign         | W   | 0.415      | 0.143        | 0.086 (0.005)    | 0.461 (0.027)    | 0 (0.000) |     9.94 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           22 |     6901 | 2024-02-01 | 2ez Gaming         | L   | 0.409      | -            | -                | -                | -         |    -8.14 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           21 |     6951 | 2024-01-31 | True Rippers       | W   | 0.402      | 0.143        | 0.025 (0.001)    | 0.241 (0.014)    | 0 (0.000) |     7.71 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           20 |     6956 | 2024-01-30 | Eruption           | L   | 0.401      | -            | -                | -                | -         |    -8.07 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           19 |     7052 | 2024-01-29 | Firedup Gaming     | W   | 0.390      | 0.143        | 0.000 (0.000)    | 0.032 (0.002)    | 0 (0.000) |     4.38 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           18 |     7206 | 2024-01-27 | Enigma Gaming      | W   | 0.376      | 0.143        | 0.004 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     5.80 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           17 |     7371 | 2024-01-24 | LYG Gaming         | L   | 0.356      | -            | -                | -                | -         |    -5.26 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           16 |     7527 | 2024-01-21 | Troublemakers      | L   | 0.336      | -            | -                | -                | -         |    -5.90 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           15 |     7537 | 2024-01-20 | Myth Avenue Gaming | L   | 0.334      | -            | -                | -                | -         |    -5.58 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           14 |     7667 | 2024-01-19 | SR Nacague         | W   | 0.322      | 0.143        | 0.000 (0.000)    | 0.044 (0.002)    | 0 (0.000) |     2.38 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           13 |     7677 | 2024-01-19 | RESILIENCE         | W   | 0.321      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.49 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           12 |     7822 | 2024-01-17 | Myth Avenue Gaming | W   | 0.310      | 0.143        | 0.005 (0.000)    | 0.192 (0.009)    | 0 (0.000) |     4.62 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           11 |     7827 | 2024-01-17 | SR Nacague         | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.044 (0.002)    | 0 (0.000) |     2.35 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           10 |     7834 | 2024-01-17 | Drippy Lab         | W   | 0.309      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.55 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            9 |     7849 | 2024-01-17 | darkside           | W   | 0.308      | -            | -                | -                | -         |     1.53 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            8 |     8743 | 2023-12-17 | MIRAI Gaming       | L   | 0.102      | -            | -                | -                | -         |    -1.58 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            7 |     8770 | 2023-12-17 | Marcos Gaming      | L   | 0.102      | -            | -                | -                | -         |    -1.42 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            6 |     8779 | 2023-12-16 | IKARI              | W   | 0.101      | -            | -                | -                | -         |     0.49 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            5 |     9013 | 2023-12-15 | Born In Far East   | L   | 0.089      | -            | -                | -                | -         |    -1.38 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            4 |     9248 | 2023-12-10 | RAVENS             | W   | 0.056      | -            | -                | -                | -         |     0.27 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            3 |     9301 | 2023-12-09 | MIRAI Gaming       | L   | 0.049      | -            | -                | -                | -         |    -0.77 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            2 |     9384 | 2023-12-08 | Guardian 5         | W   | 0.043      | -            | -                | -                | -         |     0.21 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            1 |     9450 | 2023-12-07 | ZEUSGG             | L   | 0.036      | -            | -                | -                | -         |    -0.77 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,222.52)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-10 |      0.469 | $2,500.00      | $1,171.59       |
| 2023-12-17 |      0.102 | $500.00        | $50.94          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
