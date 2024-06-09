### Roster Details<br />
Team Name: Foxed Gaming<br />
Roster: artysan, DBL, Fraaank, kiyoshi, zykes<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [455](../standings_global.md)<br />
Regional Rank: [275]( ../standings_europe.md)<br />
Final Rank Value:  450.4<br />
<br />
Final Rank Value (450.4) = Starting Rank Value (491.7) + Head To Head Adjustments (-41.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.045<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 491.7
- 400 + ( ( 0.045 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 491.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2140 | 2024-04-28 | Static            | L   | 0.990      | -            | -                | -                | -         |   -12.48 | artysan, DBL, Fraaank, kiyoshi, zykes |
|           14 |     2501 | 2024-04-22 | Vanir             | W   | 0.950      | 0.143        | 0.000 (0.000)    | 0.052 (0.007)    | 0 (0.000) |    15.30 | artysan, DBL, Fraaank, kiyoshi, zykes |
|           13 |     2736 | 2024-04-19 | Static            | L   | 0.931      | -            | -                | -                | -         |   -12.16 | artysan, B3NJ1, DBL, kiyoshi, Strope  |
|           12 |     2742 | 2024-04-19 | TOOMUCHVIDEOGAMES | W   | 0.930      | 0.143        | 0.000 (0.000)    | 0.101 (0.013)    | 0 (0.000) |    18.39 | artysan, B3NJ1, DBL, kiyoshi, Strope  |
|           11 |     3021 | 2024-04-15 | INFURITY Gaming   | L   | 0.903      | -            | -                | -                | -         |   -10.42 | artysan, DBL, Fraaank, kiyoshi, zykes |
|           10 |     3373 | 2024-04-08 | Apeks Legends     | L   | 0.857      | -            | -                | -                | -         |   -16.18 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            9 |     4312 | 2024-03-18 | Metizport X       | L   | 0.717      | -            | -                | -                | -         |    -4.66 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            8 |     4602 | 2024-03-13 | En av de lette    | L   | 0.684      | -            | -                | -                | -         |    -3.90 | DBL, Fraaank, kiyoshi, sido, zykes    |
|            7 |     4678 | 2024-03-12 | Nordix Esport     | L   | 0.677      | -            | -                | -                | -         |    -6.10 | Brave, DBL, Fraaank, kiyoshi, zykes   |
|            6 |     4735 | 2024-03-11 | Nordix Esport     | L   | 0.671      | -            | -                | -                | -         |    -6.35 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            5 |     4778 | 2024-03-10 | 777 Esports       | L   | 0.664      | -            | -                | -                | -         |    -3.78 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            4 |     4996 | 2024-03-06 | Center Gaming     | L   | 0.637      | -            | -                | -                | -         |   -12.79 | DBL, Fraaank, kiyoshi, sido, zykes    |
|            3 |     6388 | 2024-02-12 | Bitfix Gaming     | W   | 0.484      | 0.143        | 0.000 (0.000)    | 0.020 (0.001)    | 0 (0.000) |     5.46 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            2 |     6610 | 2024-02-05 | Wizard esports    | W   | 0.438      | 0.143        | 0.004 (0.000)    | 0.110 (0.007)    | 0 (0.000) |     9.50 | artysan, DBL, Fraaank, kiyoshi, zykes |
|            1 |     6728 | 2024-02-03 | EYEBALLERS        | L   | 0.424      | -            | -                | -                | -         |    -1.13 | artysan, DBL, Fraaank, kiyoshi, zykes |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
