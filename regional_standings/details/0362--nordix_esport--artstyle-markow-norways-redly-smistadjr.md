### Roster Details<br />
Team Name: Nordix Esport<br />
Roster: artstyle, markow, Norways, Redly, Smistadjr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [362](../standings_global.md)<br />
Regional Rank: [216]( ../standings_europe.md)<br />
Final Rank Value:  599.3<br />
<br />
Final Rank Value (599.3) = Starting Rank Value (642.5) + Head To Head Adjustments (-43.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.268[<sup>1</sup>](#table2)
- Bounty Collected: 0.200[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 642.5
- 400 + ( ( 0.119 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 642.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     1521 | 2024-05-10 | Static          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.158 (0.023)    | 0 (0.000) |    12.96 | artstyle, markow, Norways, Redly, Smistadjr |
|           15 |     2141 | 2024-04-28 | Vanir           | L   | 0.990      | -            | -                | -                | -         |   -21.12 | artstyle, markow, Norways, Redly, Smistadjr |
|           14 |     2508 | 2024-04-22 | INFURITY Gaming | L   | 0.950      | -            | -                | -                | -         |   -17.36 | artstyle, markow, Norways, Redly, Smistadjr |
|           13 |     2560 | 2024-04-21 | Apeks           | L   | 0.943      | -            | -                | -                | -         |   -14.25 | artstyle, markow, Norways, Redly, Smistadjr |
|           12 |     3019 | 2024-04-15 | Apeks Legends   | L   | 0.903      | -            | -                | -                | -         |   -19.88 | artstyle, markow, Norways, Redly, Smistadjr |
|           11 |     3254 | 2024-04-10 | Metizport X     | W   | 0.870      | 0.143        | 0.008 (0.001)    | 0.210 (0.026)    | 0 (0.000) |    15.51 | artstyle, markow, Norways, Redly, Smistadjr |
|           10 |     4309 | 2024-03-18 | 777 Esports     | L   | 0.718      | -            | -                | -                | -         |    -7.34 | artstyle, markow, Norways, Redly, Smistadjr |
|            9 |     4375 | 2024-03-17 | En av de lette  | L   | 0.710      | -            | -                | -                | -         |    -8.30 | artstyle, markow, Norways, Redly, Smistadjr |
|            8 |     4417 | 2024-03-16 | Static          | W   | 0.704      | 0.143        | 0.000 (0.000)    | 0.158 (0.016)    | 0 (0.000) |     6.79 | artstyle, markow, Norways, Redly, Smistadjr |
|            7 |     4603 | 2024-03-13 | Center Gaming   | W   | 0.684      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     4.38 | artstyle, markow, Norways, Redly, Smistadjr |
|            6 |     4678 | 2024-03-12 | Foxed Gaming    | W   | 0.677      | 0.143        | 0.000 (0.000)    | 0.077 (0.007)    | 0 (0.000) |     6.10 | artstyle, markow, Norways, Redly, Smistadjr |
|            5 |     4735 | 2024-03-11 | Foxed Gaming    | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.077 (0.007)    | 0 (0.000) |     6.35 | artstyle, markow, Norways, Redly, Smistadjr |
|            4 |     4995 | 2024-03-06 | En av de lette  | L   | 0.637      | -            | -                | -                | -         |    -7.43 | artstyle, markow, Norways, Redly, Smistadjr |
|            3 |     5186 | 2024-03-04 | Bitfix Gaming   | W   | 0.624      | 0.143        | 0.000 (0.000)    | 0.020 (0.002)    | 0 (0.000) |     3.92 | artstyle, markow, Norways, Redly, Smistadjr |
|            2 |     6390 | 2024-02-12 | Wizard esports  | L   | 0.484      | -            | -                | -                | -         |    -7.95 | artstyle, markow, Norways, Redly, Smistadjr |
|            1 |     6622 | 2024-02-05 | Static          | W   | 0.437      | 0.143        | 0.000 (0.000)    | 0.158 (0.010)    | 0 (0.000) |     4.39 | artstyle, markow, Norways, Redly, Smistadjr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($566.95)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
