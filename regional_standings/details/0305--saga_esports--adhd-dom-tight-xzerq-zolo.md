### Roster Details<br />
Team Name: SAGA Esports<br />
Roster: ADHD, DOM, Tight, xZerq, Zolo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [305](../standings_global.md)<br />
Regional Rank: [186]( ../standings_europe.md)<br />
Final Rank Value:  605.1<br />
<br />
Final Rank Value (605.1) = Starting Rank Value (606.7) + Head To Head Adjustments (-1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.101[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 606.7
- 400 + ( ( 0.104 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 606.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     1888 | 2024-03-23 | DUSTY           | L   | 0.912      | -            | -                | -                | -             |    -9.87 | ADHD, DOM, Tight, xZerq, Zolo |
|           16 |     1937 | 2024-03-22 | Þór             | W   | 0.905      | 0.143        | 0.000 (0.000)    | 0.169 (0.022)    | true (0.905)  |    12.60 | ADHD, DOM, Tight, xZerq, Zolo |
|           15 |     2264 | 2024-03-14 | FH              | W   | 0.852      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.56 | ADHD, DOM, Tight, xZerq, Zolo |
|           14 |     3481 | 2024-02-17 | ÍBV Esports     | W   | 0.679      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.60 | ADHD, DOM, Tight, xZerq, Zolo |
|           13 |     3669 | 2024-02-13 | Breiðablik      | L   | 0.652      | -            | -                | -                | -             |   -12.52 | ADHD, DOM, Tight, xZerq, Zolo |
|           12 |     3809 | 2024-02-08 | Þór             | L   | 0.619      | -            | -                | -                | -             |   -11.83 | ADHD, DOM, Tight, xZerq, Zolo |
|           11 |     4535 | 2024-01-20 | Young Prodigies | W   | 0.492      | 0.143        | 0.000 (0.000)    | 0.065 (0.005)    | false (0.000) |     3.66 | ADHD, DOM, Tight, xZerq, Zolo |
|           10 |     4640 | 2024-01-18 | Ármann          | W   | 0.480      | 0.143        | 0.000 (0.000)    | 0.097 (0.007)    | false (0.000) |     5.35 | ADHD, DOM, Tight, xZerq, Zolo |
|            9 |     4989 | 2024-01-11 | DUSTY           | L   | 0.432      | -            | -                | -                | -             |    -3.81 | ADHD, DOM, Tight, xZerq, Zolo |
|            8 |     5976 | 2023-12-05 | ÍA Akranes      | W   | 0.186      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | false (0.000) |     1.40 | ADHD, DOM, Tight, xZerq, Zolo |
|            7 |     6192 | 2023-11-30 | FH              | W   | 0.153      | 0.143        | 0.000 (0.000)    | 0.040 (0.001)    | false (0.000) |     1.14 | ADHD, DOM, Tight, xZerq, Zolo |
|            6 |     6660 | 2023-11-19 | DUSTY           | L   | 0.079      | -            | -                | -                | -             |    -0.68 | ADHD, DOM, Tight, xZerq, Zolo |
|            5 |     6662 | 2023-11-19 | Young Prodigies | W   | 0.079      | 0.143        | 0.000 (0.000)    | 0.065 (0.001)    | false (0.000) |     0.59 | ADHD, DOM, Tight, xZerq, Zolo |
|            4 |     6910 | 2023-11-14 | Ármann          | W   | 0.046      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | false (0.000) |     0.34 | ADHD, DOM, Tight, xZerq, Zolo |
|            3 |     6915 | 2023-11-14 | Þór             | W   | 0.046      | 0.143        | 0.000 (0.000)    | 0.169 (0.001)    | false (0.000) |     0.52 | ADHD, DOM, Tight, xZerq, Zolo |
|            2 |     6950 | 2023-11-13 | ÍBV Esports     | W   | 0.039      | -            | -                | -                | -             |     0.29 | ADHD, DOM, Tight, xZerq, Zolo |
|            1 |     7119 | 2023-11-09 | ÍBV Esports     | W   | 0.013      | -            | -                | -                | -             |     0.10 | ADHD, DOM, Tight, xZerq, Zolo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($993.31)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
