### Roster Details<br />
Team Name: Nouns Esports<br />
Roster: Bwills, cJ, cynic, MarKE, nosraC<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [196](../standings_global.md)<br />
Regional Rank: [36]( ../standings_americas.md)<br />
Final Rank Value:  727.1<br />
<br />
Final Rank Value (727.1) = Starting Rank Value (723.9) + Head To Head Adjustments (3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.358[<sup>1</sup>](#table2)
- Bounty Collected: 0.277[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.012[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.9
- 400 + ( ( 0.163 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 723.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     5335 | 2023-12-17 | FPL Friends      | L   | 0.267      | -            | -                | -                | -             |    -4.91 | Bwills, cJ, cynic, MarKE, nosraC |
|           16 |     5339 | 2023-12-17 | Carpe Diem       | W   | 0.267      | 0.294        | 0.009 (0.001)    | 0.178 (0.014)    | false (0.000) |     4.22 | Bwills, cJ, cynic, MarKE, nosraC |
|           15 |     5422 | 2023-12-16 | Team DNA         | W   | 0.261      | 0.294        | 0.000 (0.000)    | 0.009 (0.001)    | false (0.000) |     1.14 | Bwills, cJ, cynic, MarKE, nosraC |
|           14 |     5424 | 2023-12-16 | Mythic           | W   | 0.261      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.14 | Bwills, cJ, cynic, MarKE, nosraC |
|           13 |     5627 | 2023-12-13 | M80              | L   | 0.241      | -            | -                | -                | -             |    -0.29 | Bwills, cJ, cynic, MarKE, nosraC |
|           12 |     5685 | 2023-12-11 | Akimbo Esports   | W   | 0.227      | 0.303        | 0.000 (0.000)    | 0.015 (0.001)    | false (0.000) |     1.46 | Bwills, cJ, cynic, MarKE, nosraC |
|           11 |     5825 | 2023-12-08 | Party Astronauts | L   | 0.207      | -            | -                | -                | -             |    -2.50 | Bwills, cJ, cynic, MarKE, nosraC |
|           10 |     5862 | 2023-12-07 | Carpe Diem       | W   | 0.201      | 0.500        | 0.009 (0.001)    | 0.178 (0.018)    | false (0.000) |     3.24 | Bwills, cJ, cynic, MarKE, nosraC |
|            9 |     5916 | 2023-12-06 | BOSS             | L   | 0.194      | -            | -                | -                | -             |    -1.68 | Bwills, cJ, cynic, MarKE, nosraC |
|            8 |     5962 | 2023-12-05 | Evil Geniuses    | W   | 0.187      | 0.500        | 0.006 (0.001)    | 0.009 (0.001)    | false (0.000) |     2.48 | Bwills, cJ, cynic, MarKE, nosraC |
|            7 |     6077 | 2023-12-02 | CatEvil          | L   | 0.167      | -            | -                | -                | -             |    -3.36 | Bwills, cJ, cynic, MarKE, nosraC |
|            6 |     6437 | 2023-11-25 | Eternal Fire     | L   | 0.118      | -            | -                | -                | -             |    -0.01 | bwills, cJ, cynic, MarKE, nosraC |
|            5 |     6481 | 2023-11-24 | Monte            | L   | 0.111      | -            | -                | -                | -             |    -0.09 | bwills, cJ, cynic, MarKE, nosraC |
|            4 |     6495 | 2023-11-24 | Eternal Fire     | W   | 0.110      | 0.500        | 0.409 (0.022)    | 0.462 (0.025)    | true (0.110)  |     3.45 | bwills, cJ, cynic, MarKE, nosraC |
|            3 |     6762 | 2023-11-17 | ARCRED           | L   | 0.066      | -            | -                | -                | -             |    -0.74 | Bwills, cJ, cynic, MarKE, nosraC |
|            2 |     7081 | 2023-11-10 | Elevate          | L   | 0.020      | -            | -                | -                | -             |    -0.26 | Bwills, cJ, cynic, MarKE, nosraC |
|            1 |     7155 | 2023-11-08 | Rocket           | L   | 0.007      | -            | -                | -                | -             |    -0.13 | Bwills, cJ, cynic, MarKE, nosraC |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,536.71)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-17 |      0.267 | $1,000.00      | $267.31         |
| 2023-12-13 |      0.241 | $1,000.00      | $240.51         |
| 2023-12-10 |      0.221 | $7,500.00      | $1,653.82       |
| 2023-11-26 |      0.125 | $3,000.00      | $375.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
