### Roster Details<br />
Team Name: Rare Atom<br />
Roster: Childking, L1haNg, risk, somebody, Summer<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [114](../standings_global.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
Final Rank Value:  851.3<br />
<br />
Final Rank Value (851.3) = Starting Rank Value (757.4) + Head To Head Adjustments (94.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.286[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 757.4
- 400 + ( ( 0.176 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 757.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      424 | 2024-05-23 | MOUZ NXT           | L   | 1.000      | -            | -                | -                | -         |   -10.43 | Childking, L1haNg, risk, somebody, Summer |
|           15 |      917 | 2024-05-18 | Sangal Esports     | L   | 1.000      | -            | -                | -                | -         |    -8.50 | Childking, L1haNg, risk, somebody, Summer |
|           14 |      966 | 2024-05-17 | NOM Esports        | L   | 1.000      | -            | -                | -                | -         |   -22.68 | ChildKing, L1haNg, risk, somebody, Summer |
|           13 |     1278 | 2024-05-14 | DMS                | L   | 1.000      | -            | -                | -                | -         |   -13.71 | ChildKing, L1haNg, risk, somebody, Summer |
|           12 |     1346 | 2024-05-13 | NOM Esports        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.360 (0.051)    | 0 (0.000) |     6.92 | ChildKing, L1haNg, risk, somebody, Summer |
|           11 |     2566 | 2024-04-21 | ATOX Esports       | W   | 0.942      | 0.143        | 0.047 (0.006)    | 0.609 (0.082)    | 0 (0.000) |    24.37 | ChildKing, L1haNg, risk, somebody, Summer |
|           10 |     2587 | 2024-04-20 | NewHappy           | W   | 0.940      | 0.143        | 0.020 (0.003)    | 0.231 (0.031)    | 0 (0.000) |     8.48 | ChildKing, L1haNg, risk, somebody, Summer |
|            9 |     2772 | 2024-04-19 | The MongolZ        | L   | 0.929      | -            | -                | -                | -         |    -0.62 | ChildKing, L1haNg, risk, somebody, Summer |
|            8 |     2785 | 2024-04-19 | TYLOO              | W   | 0.928      | 0.143        | 0.035 (0.005)    | 0.433 (0.057)    | 0 (0.000) |    17.56 | ChildKing, L1haNg, risk, somebody, Summer |
|            7 |     2830 | 2024-04-18 | Lynn Vision Gaming | W   | 0.923      | 0.143        | 0.063 (0.008)    | 0.431 (0.057)    | 0 (0.000) |    22.56 | ChildKing, L1haNg, risk, somebody, Summer |
|            6 |     2846 | 2024-04-18 | The MongolZ        | L   | 0.922      | -            | -                | -                | -         |    -0.50 | ChildKing, L1haNg, risk, somebody, Summer |
|            5 |     2852 | 2024-04-18 | Lynn Vision Gaming | W   | 0.921      | 0.143        | 0.063 (0.008)    | 0.431 (0.057)    | 0 (0.000) |    24.22 | ChildKing, L1haNg, risk, somebody, Summer |
|            4 |     2855 | 2024-04-17 | Rooster            | W   | 0.921      | 0.143        | 0.014 (0.002)    | 0.229 (0.030)    | 0 (0.000) |    17.42 | ChildKing, L1haNg, risk, somebody, Summer |
|            3 |     2916 | 2024-04-17 | Team NKT           | W   | 0.915      | 0.143        | 0.000 (0.000)    | 0.050 (0.007)    | 0 (0.000) |     6.04 | ChildKing, L1haNg, risk, somebody, Summer |
|            2 |     2923 | 2024-04-17 | MIRAI Gaming       | W   | 0.915      | 0.143        | 0.000 (0.000)    | 0.200 (0.026)    | 0 (0.000) |    11.17 | ChildKing, L1haNg, risk, somebody, Summer |
|            1 |     2979 | 2024-04-16 | Born In Far East   | W   | 0.909      | 0.143        | 0.001 (0.000)    | 0.139 (0.018)    | 0 (0.000) |    11.67 | ChildKing, L1haNg, risk, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,507.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
