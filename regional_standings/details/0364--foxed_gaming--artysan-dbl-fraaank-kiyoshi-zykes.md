### Roster Details<br />
Team Name: Foxed Gaming<br />
Roster: artysan, DBL, Fraaank, kiyoshi, zykes<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [364](../standings_global.md)<br />
Regional Rank: [228]( ../standings_europe.md)<br />
Final Rank Value:  364.3<br />
<br />
Final Rank Value (364.3) = Starting Rank Value (402.3) + Head To Head Adjustments (-38.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 402.3
- 400 + ( ( 0.001 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 402.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      309 | 2024-04-28 | Static                          | L   | 1.000      | -            | -                | -                | -         |    -9.77 | artysan, DBL, Fraaank, kiyoshi, zykes |
|           14 |      603 | 2024-04-22 | Vanir                           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |    15.70 | artysan, DBL, Fraaank, kiyoshi, zykes |
|           13 |      805 | 2024-04-19 | Static                          | L   | 1.000      | -            | -                | -                | -         |   -10.07 | artysan, B3NJ1, DBL, kiyoshi, Strope  |
|           12 |      808 | 2024-04-19 | TOOMUCHVIDEOGAMES               | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.161 (0.023)    | 0 (0.000) |    24.14 | artysan, B3NJ1, DBL, kiyoshi, Strope  |
|           11 |     1050 | 2024-04-15 | INFURITY Gaming                 | L   | 1.000      | -            | -                | -                | -         |   -10.56 | artysan, DBL, Fraaank, kiyoshi, zykes |
|           10 |     1331 | 2024-04-08 | Apeks Legends                   | L   | 1.000      | -            | -                | -                | -         |   -15.23 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            9 |     2090 | 2024-03-18 | Metizport X                     | L   | 0.878      | -            | -                | -                | -         |    -7.08 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            8 |     2315 | 2024-03-13 | En av de lette                  | L   | 0.845      | -            | -                | -                | -         |    -3.00 | DBL, Fraaank, kiyoshi, sido, zykes    |
|            7 |     2373 | 2024-03-12 | Nordix Esport                   | L   | 0.838      | -            | -                | -                | -         |   -11.52 | Brave, DBL, Fraaank, kiyoshi, zykes   |
|            6 |     2416 | 2024-03-11 | Nordix Esport                   | L   | 0.832      | -            | -                | -                | -         |   -12.31 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            5 |     2451 | 2024-03-10 | 777 Esports                     | L   | 0.825      | -            | -                | -                | -         |    -3.27 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            4 |     2613 | 2024-03-06 | Center Gaming                   | L   | 0.799      | -            | -                | -                | -         |   -13.11 | DBL, Fraaank, kiyoshi, sido, zykes    |
|            3 |     3719 | 2024-02-12 | Bitfix Gaming                   | W   | 0.645      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     9.62 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            2 |     3887 | 2024-02-05 | Wizard esports (Norwegian team) | W   | 0.599      | 0.143        | 0.000 (0.000)    | 0.122 (0.010)    | 0 (0.000) |     9.29 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            1 |     3966 | 2024-02-03 | EYEBALLERS                      | L   | 0.585      | -            | -                | -                | -         |    -0.83 | artysan, DBL, Fraaank, kiyoshi, zykes |

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
