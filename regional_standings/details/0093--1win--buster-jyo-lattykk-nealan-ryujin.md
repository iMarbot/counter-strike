### Roster Details<br />
Team Name: 1win<br />
Roster: buster, Jyo, lattykk, neaLaN, Ryujin<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [93](../standings_global.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
Final Rank Value:  870.9<br />
<br />
Final Rank Value (870.9) = Starting Rank Value (681.5) + Head To Head Adjustments (189.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.384[<sup>2</sup>](#table1)
- Opponent Network: 0.184[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 681.5
- 400 + ( ( 0.142 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 681.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       28 | 2024-05-05 | Guild Eagles     | W   | 1.000      | 0.143        | 0.037 (0.005)    | 0.586 (0.084)    | 0 (0.000) |    19.60 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           16 |       53 | 2024-05-04 | NOM Esports      | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.374 (0.139)    | 0 (0.000) |    11.15 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           15 |      141 | 2024-05-02 | Soda Gaming      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.16 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           14 |      181 | 2024-05-01 | V1dar Gaming     | W   | 1.000      | 0.371        | -                | 0.345 (0.128)    | 0 (0.000) |     8.69 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           13 |      272 | 2024-04-29 | Passion UA       | W   | 1.000      | 0.371        | 0.114 (0.042)    | 0.980 (0.364)    | 0 (0.000) |    19.43 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           12 |      282 | 2024-04-29 | Dynamo Eclot     | L   | 1.000      | -            | -                | -                | -         |    -8.56 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           11 |      284 | 2024-04-29 | SINNERS Esports  | L   | 1.000      | -            | -                | -                | -         |   -10.57 | buster, Jyo, lattykk, neaLaN, Ryujin |
|           10 |      373 | 2024-04-27 | Nemiga Gaming    | L   | 1.000      | -            | -                | -                | -         |    -2.90 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            9 |      481 | 2024-04-25 | Permitta Esports | W   | 1.000      | 0.435        | 0.063 (0.027)    | 1.000 (0.435)    | 0 (0.000) |    20.72 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            8 |      581 | 2024-04-23 | HAVU Gaming      | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.213 (0.093)    | 0 (0.000) |    13.67 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            7 |      661 | 2024-04-21 | Nemiga Gaming    | L   | 1.000      | -            | -                | -                | -         |    -2.55 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            6 |      710 | 2024-04-20 | EsmagaB          | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.559 (0.080)    | 0 (0.000) |    17.55 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            5 |     1007 | 2024-04-16 | ENCE Academy     | W   | 1.000      | 0.143        | 0.028 (0.004)    | -                | 0 (0.000) |    19.20 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            4 |     1053 | 2024-04-15 | ARCRED           | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.825 (0.306)    | 0 (0.000) |    19.47 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            3 |     1294 | 2024-04-09 | Aurora Gaming    | L   | 1.000      | -            | -                | -                | -         |    -0.40 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            2 |     1325 | 2024-04-08 | 9Pandas          | W   | 1.000      | 0.143        | 0.085 (0.012)    | 0.661 (0.094)    | -         |    28.59 | buster, Jyo, lattykk, neaLaN, Ryujin |
|            1 |     1342 | 2024-04-08 | Aurora Gaming    | W   | 1.000      | 0.143        | 1.000 (0.143)    | 0.799 (0.114)    | -         |    31.19 | buster, Jyo, lattykk, neaLaN, Ryujin |

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
