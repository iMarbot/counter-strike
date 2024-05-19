### Roster Details<br />
Team Name: Souls-Land<br />
Roster: FreakiN, Harborboy, SundanceK1d, wh1mzzz, xrt<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [356](../standings_global.md)<br />
Regional Rank: [57]( ../standings_asia.md)<br />
Final Rank Value:  454.5<br />
<br />
Final Rank Value (454.5) = Starting Rank Value (441.3) + Head To Head Adjustments (13.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.080[<sup>2</sup>](#table1)

The average of these factors is 0.021<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 441.3
- 400 + ( ( 0.021 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 441.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      684 | 2024-04-20 | Team Invictum        | L   | 1.000      | -            | -                | -                | -             |   -13.39 | FreakiN, Harborboy, SundanceK1d, wh1mzzz, xrt   |
|           10 |      797 | 2024-04-19 | Team Invictum        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | false (0.000) |    17.58 | FreakiN, Harborboy, SundanceK1d, wh1mzzz, xrt   |
|            9 |      801 | 2024-04-19 | Team Sodality        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | false (0.000) |    18.09 | FreakiN, Harborboy, SundanceK1d, wh1mzzz, xrt   |
|            8 |     3183 | 2024-02-24 | Rum Bumpers          | L   | 0.723      | -            | -                | -                | -             |    -4.35 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt   |
|            7 |     3196 | 2024-02-23 | BTEC NEDS            | W   | 0.720      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | true (0.720)  |    10.27 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt   |
|            6 |     3436 | 2024-02-18 | The Last Resort      | L   | 0.686      | -            | -                | -                | -             |    -4.21 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt   |
|            5 |     3571 | 2024-02-15 | K10                  | L   | 0.666      | -            | -                | -                | -             |    -1.92 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt   |
|            4 |     3667 | 2024-02-13 | Viperio              | L   | 0.652      | -            | -                | -                | -             |    -4.43 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt   |
|            3 |     3783 | 2024-02-09 | The Last Resort      | L   | 0.626      | -            | -                | -                | -             |    -4.24 | Deg1l, EthanChen, Harborboy, SundanceK1d, xrt   |
|            2 |     6803 | 2023-11-16 | Raptors Esports Club | L   | 0.059      | -            | -                | -                | -             |    -0.15 | Harborboy, Kisynergy, SundanceK1d, wh1mzzz, xrt |
|            1 |     6923 | 2023-11-14 | Verdant              | L   | 0.045      | -            | -                | -                | -             |    -0.06 | Harborboy, Kisynergy, SundanceK1d, wh1mzzz, xrt |

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
