### Roster Details<br />
Team Name: NAVI Javelins<br />
Roster: Angelka, Hanka, LETi, Liina, vicu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [97](../standings_global.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
Final Rank Value:  872.9<br />
<br />
Final Rank Value (872.9) = Starting Rank Value (777.3) + Head To Head Adjustments (95.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.382[<sup>1</sup>](#table2)
- Bounty Collected: 0.277[<sup>2</sup>](#table1)
- Opponent Network: 0.066[<sup>2</sup>](#table1)
- LAN Wins: 0.016[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.3
- 400 + ( ( 0.185 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 777.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      763 | 2024-05-19 | Team Pigeons         | W   | 1.000      | 0.281        | 0.024 (0.007)    | 0.350 (0.099)    | 0 (0.000) |    17.50 | Angelka, Hanka, LETi, Liina, vicu |
|           25 |      802 | 2024-05-19 | BIG EQUIPA           | W   | 1.000      | 0.281        | -                | 0.267 (0.075)    | 0 (0.000) |    12.21 | Angelka, Hanka, LETi, Liina, vicu |
|           24 |      897 | 2024-05-18 | Team Spirit Female   | W   | 1.000      | 0.281        | 0.005 (0.001)    | 0.216 (0.061)    | 0 (0.000) |     8.10 | Angelka, Hanka, LETi, Liina, vicu |
|           23 |      921 | 2024-05-18 | Permitta W           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.18 | Angelka, Hanka, LETi, Liina, vicu |
|           22 |     2694 | 2024-04-19 | Crescent             | W   | 0.930      | 0.331        | 0.007 (0.002)    | 0.228 (0.070)    | 0 (0.000) |     8.03 | Angelka, Hanka, LETi, Liina, vicu |
|           21 |     2904 | 2024-04-16 | Team Pigeons         | W   | 0.910      | 0.303        | 0.024 (0.007)    | 0.350 (0.097)    | 0 (0.000) |    16.28 | Angelka, Hanka, LETi, Liina, vicu |
|           20 |     2950 | 2024-04-15 | NIP Impact           | W   | 0.904      | 0.303        | 0.007 (0.002)    | 0.303 (0.083)    | 0 (0.000) |    11.08 | Angelka, Hanka, LETi, Liina, vicu |
|           19 |     2983 | 2024-04-14 | Astralis Women       | W   | 0.896      | -            | -                | -                | -         |     6.96 | Angelka, Hanka, LETi, Liina, vicu |
|           18 |     3042 | 2024-04-13 | Team Pigeons         | L   | 0.889      | -            | -                | -                | -         |   -11.70 | Angelka, Hanka, LETi, Liina, vicu |
|           17 |     3126 | 2024-04-11 | Team Spirit Female   | W   | 0.876      | 0.303        | 0.005 (0.001)    | 0.216 (0.057)    | -         |     8.59 | Angelka, Hanka, LETi, Liina, vicu |
|           16 |     3250 | 2024-04-09 | NIP Impact           | L   | 0.863      | -            | -                | -                | -         |   -16.59 | Angelka, Hanka, LETi, Liina, vicu |
|           15 |     3494 | 2024-04-04 | Team Spirit Female   | W   | 0.830      | 0.331        | 0.005 (0.001)    | 0.216 (0.059)    | -         |     8.86 | Angelka, Hanka, LETi, Liina, vicu |
|           14 |     3551 | 2024-04-03 | Let Her Cook         | L   | 0.824      | -            | -                | -                | -         |   -20.85 | Angelka, Hanka, LETi, Liina, vicu |
|           13 |     4421 | 2024-03-14 | 1win Gang            | W   | 0.691      | 0.331        | 0.004 (0.001)    | 0.118 (0.027)    | -         |     5.89 | Angelka, Hanka, LETi, Liina, vicu |
|           12 |     4862 | 2024-03-06 | Fearless Cheetahs    | W   | 0.638      | 0.331        | 0.006 (0.001)    | 0.149 (0.031)    | -         |     6.69 | Angelka, Hanka, LETi, Liina, vicu |
|           11 |     5458 | 2024-02-25 | BIG EQUIPA           | W   | 0.570      | -            | -                | -                | -         |     6.75 | Angelka, Hanka, LETi, Liina, vicu |
|           10 |     5464 | 2024-02-25 | ENCE Athena          | W   | 0.569      | -            | -                | -                | -         |     6.49 | Angelka, Hanka, LETi, Liina, vicu |
|            9 |     5548 | 2024-02-24 | Crescent             | W   | 0.563      | -            | -                | -                | -         |     6.76 | Angelka, Hanka, LETi, Liina, vicu |
|            8 |     6454 | 2024-02-04 | VIOLET               | W   | 0.431      | -            | -                | -                | -         |     2.56 | Angelka, Hanka, LETi, Liina, vicu |
|            7 |     6463 | 2024-02-04 | ENCE Athena          | W   | 0.430      | -            | -                | -                | -         |     4.75 | Angelka, Hanka, LETi, Liina, vicu |
|            6 |     6503 | 2024-02-03 | wwaves               | W   | 0.424      | -            | -                | -                | -         |     2.31 | Angelka, Hanka, LETi, Liina, vicu |
|            5 |     8967 | 2023-12-10 | Team Pigeons         | L   | 0.057      | -            | -                | -                | -         |    -0.90 | Angelka, Hanka, LETi, Liina, vicu |
|            4 |     8976 | 2023-12-10 | Fluxo Demons         | W   | 0.056      | 0.524        | 0.026 (0.001)    | -                | 1 (0.056) |     1.10 | Angelka, Hanka, LETi, Liina, vicu |
|            3 |     9040 | 2023-12-09 | FURIA Esports Female | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.86 | Angelka, Hanka, LETi, Liina, vicu |
|            2 |     9102 | 2023-12-08 | NOFEAR5              | L   | 0.044      | -            | -                | -                | -         |    -0.94 | Angelka, Hanka, LETi, Liina, vicu |
|            1 |     9112 | 2023-12-08 | TSM Shimmer          | W   | 0.043      | -            | -                | -                | 1 (0.043) |     0.58 | Angelka, Hanka, LETi, Liina, vicu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,292.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-04-16 |      0.910 | $3,500.00      | $3,185.97       |
| 2024-02-25 |      0.570 | $633.95        | $361.26         |
| 2024-02-04 |      0.431 | $750.00        | $323.13         |
| 2023-12-10 |      0.057 | $25,000.00     | $1,421.88       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
