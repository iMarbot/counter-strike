### Roster Details<br />
Team Name: Reason Gaming<br />
Roster: Byfield, Cha0s, CJE, FincHY, Rezzed<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [242](../standings_global.md)<br />
Regional Rank: [160]( ../standings_europe.md)<br />
Final Rank Value:  691.2<br />
<br />
Final Rank Value (691.2) = Starting Rank Value (806.6) + Head To Head Adjustments (-115.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.313[<sup>2</sup>](#table1)

The average of these factors is 0.200<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 806.6
- 400 + ( ( 0.200 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 806.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       42 | 2024-05-29 | Dreams To Legends       | L   | 1.000      | -            | -                | -                | -         |   -23.77 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|           16 |      223 | 2024-05-26 | Monte Gen               | L   | 1.000      | -            | -                | -                | -         |   -10.86 | Byfield, Cha0s, CJE, FinchY, Rezzed |
|           15 |      227 | 2024-05-26 | Nexus Gaming            | L   | 1.000      | -            | -                | -                | -         |   -10.48 | Byfield, Cha0s, CJE, FinchY, Rezzed |
|           14 |      266 | 2024-05-25 | Preasy Esport           | L   | 1.000      | -            | -                | -                | -         |   -16.97 | Byfield, Cha0s, CJE, FinchY, Rezzed |
|           13 |      293 | 2024-05-25 | Young Ninjas            | L   | 1.000      | -            | -                | -                | -         |    -9.99 | Byfield, Cha0s, CJE, FinchY, Rezzed |
|           12 |     2555 | 2024-04-20 | Team Sodality           | L   | 0.937      | -            | -                | -                | -         |   -24.19 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|           11 |     2669 | 2024-04-19 | BLUEJAYS Royal          | W   | 0.932      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.93 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|           10 |     2671 | 2024-04-19 | Costco Guys             | W   | 0.932      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.06 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            9 |     3630 | 2024-04-01 | Verdant                 | L   | 0.809      | -            | -                | -                | -         |    -7.12 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            8 |     3647 | 2024-03-31 | Ahoka                   | W   | 0.803      | 0.143        | 0.003 (0.000)    | 0.044 (0.005)    | 1 (0.803) |    10.89 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            7 |     3657 | 2024-03-31 | p0dbots                 | W   | 0.802      | 0.143        | 0.002 (0.000)    | 0.044 (0.005)    | 1 (0.802) |     7.72 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            6 |     3675 | 2024-03-30 | Ahoka                   | L   | 0.797      | -            | -                | -                | -         |   -14.11 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            5 |     3690 | 2024-03-30 | The Mighty Sun          | W   | 0.796      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.796) |     2.62 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            4 |     5425 | 2024-02-26 | Permitta Esports        | L   | 0.575      | -            | -                | -                | -         |    -4.58 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            3 |     5572 | 2024-02-24 | The Last Resort         | L   | 0.562      | -            | -                | -                | -         |   -11.89 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            2 |     5590 | 2024-02-23 | Disco Diggers           | W   | 0.559      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.559) |     1.72 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            1 |     6287 | 2024-02-09 | ex-Raptors Esports Club | L   | 0.465      | -            | -                | -                | -         |   -10.37 | Byfield, Cha0s, CJE, FincHY, RezzeD |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,277.61)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
