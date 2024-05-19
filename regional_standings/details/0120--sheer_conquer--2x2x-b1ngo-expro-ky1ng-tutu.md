### Roster Details<br />
Team Name: Sheer Conquer<br />
Roster: 2X2X, B1NGO, EXPRO, Ky1ng, tutu<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [120](../standings_global.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
Final Rank Value:  820.4<br />
<br />
Final Rank Value (820.4) = Starting Rank Value (753.5) + Head To Head Adjustments (66.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.407[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.178<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.5
- 400 + ( ( 0.178 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 753.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       73 | 2024-05-04 | Noobs But Diligent | L   | 1.000      | -            | -                | -                | -             |   -17.94 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|           10 |       86 | 2024-05-04 | AP Gaming          | L   | 1.000      | -            | -                | -                | -             |   -14.82 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            9 |      772 | 2024-04-20 | Noobs But Diligent | W   | 1.000      | 0.143        | 0.027 (0.004)    | 0.174 (0.025)    | false (0.000) |    13.28 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            8 |      782 | 2024-04-19 | XNL Gaming         | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.000 (0.000)    | false (0.000) |     5.29 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            7 |      956 | 2024-04-17 | TYLOO              | L   | 1.000      | -            | -                | -                | -             |    -8.18 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            6 |      964 | 2024-04-17 | DEWA United        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | false (0.000) |     6.07 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            5 |     1015 | 2024-04-16 | GR Gaming          | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.495 (0.071)    | false (0.000) |    20.56 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            4 |     1123 | 2024-04-13 | StudFarm Esport    | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.069 (0.010)    | false (0.000) |    10.61 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            3 |     1125 | 2024-04-13 | AP Gaming          | W   | 1.000      | 0.143        | 0.082 (0.012)    | 0.152 (0.022)    | false (0.000) |    18.92 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            2 |     1423 | 2024-04-06 | StudFarm Esport    | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.069 (0.010)    | false (0.000) |    12.32 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |
|            1 |     1429 | 2024-04-06 | AP Gaming          | W   | 1.000      | 0.143        | 0.082 (0.012)    | 0.152 (0.022)    | false (0.000) |    20.70 | 2X2X, B1NGO, EXPRO, Ky1ng, tutu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,527.33)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $1,381.73      | $1,381.73       |
| 2024-04-20 |      1.000 | $1,381.25      | $1,381.25       |
| 2024-04-13 |      1.000 | $1,381.78      | $1,381.78       |
| 2024-04-06 |      1.000 | $1,382.57      | $1,382.57       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
