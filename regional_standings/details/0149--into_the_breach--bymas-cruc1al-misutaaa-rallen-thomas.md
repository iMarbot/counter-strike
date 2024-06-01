### Roster Details<br />
Team Name: Into The Breach<br />
Roster: Bymas, CRUC1AL, misutaaa, rallen, Thomas<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [149](../standings_global.md)<br />
Regional Rank: [103]( ../standings_europe.md)<br />
Final Rank Value:  777.1<br />
<br />
Final Rank Value (777.1) = Starting Rank Value (722.1) + Head To Head Adjustments (55.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.262[<sup>1</sup>](#table2)
- Bounty Collected: 0.323[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 722.1
- 400 + ( ( 0.158 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 722.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     6046 | 2024-02-15 | 3DMAX              | L   | 0.504      | -            | -                | -                | -         |    -4.47 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           22 |     6102 | 2024-02-14 | BetBoom Team       | L   | 0.497      | -            | -                | -                | -         |    -0.50 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           21 |     6121 | 2024-02-14 | G2 Esports         | L   | 0.496      | -            | -                | -                | -         |    -0.05 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           20 |     6368 | 2024-02-07 | ex-Preasy Esport   | L   | 0.448      | -            | -                | -                | -         |    -4.58 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           19 |     6383 | 2024-02-06 | Metizport          | W   | 0.443      | 0.371        | 0.088 (0.014)    | 0.698 (0.115)    | 0 (0.000) |    10.47 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           18 |     6476 | 2024-02-04 | SINNERS Esports    | W   | 0.429      | 0.371        | 0.011 (0.002)    | 0.560 (0.089)    | 0 (0.000) |    10.41 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           17 |     6638 | 2024-02-02 | Gaimin Gladiators  | L   | 0.416      | -            | -                | -                | -         |    -0.75 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           16 |     6694 | 2024-02-01 | BLEED Esports      | W   | 0.409      | 0.371        | 0.248 (0.038)    | 0.677 (0.103)    | 0 (0.000) |    11.94 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           15 |     6778 | 2024-01-29 | EXO Clan           | L   | 0.392      | -            | -                | -                | -         |    -2.70 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           14 |     6801 | 2024-01-29 | B8                 | W   | 0.392      | 0.143        | 0.168 (0.009)    | 0.952 (0.053)    | 0 (0.000) |    10.99 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           13 |     6844 | 2024-01-29 | BIG Academy        | W   | 0.388      | 0.371        | 0.003 (0.000)    | 0.086 (0.012)    | 0 (0.000) |     5.79 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           12 |     6858 | 2024-01-28 | ex-Anonymo Esports | L   | 0.384      | -            | -                | -                | -         |    -6.30 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           11 |     6863 | 2024-01-28 | Sashi Esport       | W   | 0.384      | 0.143        | 0.000 (0.000)    | 0.091 (0.005)    | 0 (0.000) |     3.19 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|           10 |     6869 | 2024-01-28 | BLEED Esports      | W   | 0.383      | 0.143        | 0.248 (0.014)    | 0.677 (0.037)    | 0 (0.000) |    11.42 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            9 |     6960 | 2024-01-27 | 9INE               | L   | 0.377      | -            | -                | -                | -         |    -8.46 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            8 |     6968 | 2024-01-27 | ex-Anonymo Esports | W   | 0.377      | 0.143        | 0.002 (0.000)    | 0.204 (0.011)    | 0 (0.000) |     5.69 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            7 |     7093 | 2024-01-25 | BLEED Esports      | L   | 0.362      | -            | -                | -                | -         |    -0.58 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            6 |     7510 | 2024-01-17 | ex-Guild Eagles    | L   | 0.312      | -            | -                | -                | -         |    -2.10 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            5 |     7516 | 2024-01-17 | Soda Gaming        | W   | 0.312      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.70 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            4 |     7526 | 2024-01-17 | Entropiq           | W   | 0.312      | 0.143        | -                | 0.241 (0.011)    | 0 (0.000) |     4.08 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            3 |     7555 | 2024-01-17 | Passion UA         | W   | 0.311      | 0.143        | 0.057 (0.003)    | 1.000 (0.044)    | -         |     8.12 | Bymas, CRUC1AL, misutaaa, rallen, Thomas |
|            2 |     9333 | 2023-12-04 | ex-Anonymo Esports | L   | 0.018      | -            | -                | -                | -         |    -0.30 | Bymas, CRUC1AL, misutaaa, rallen, tomiko |
|            1 |     9353 | 2023-12-03 | 9Pandas            | L   | 0.011      | -            | -                | -                | -         |    -0.03 | Bymas, CRUC1AL, misutaaa, rallen, tomiko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($461.67)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
