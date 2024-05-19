### Roster Details<br />
Team Name: TSM<br />
Roster: CYPHER, interz, JACKZ, MoDo, valde<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [200](../standings_global.md)<br />
Regional Rank: [132]( ../standings_europe.md)<br />
Final Rank Value:  714.4<br />
<br />
Final Rank Value (714.4) = Starting Rank Value (705.0) + Head To Head Adjustments (9.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.154<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.0
- 400 + ( ( 0.154 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 705.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     5465 | 2023-12-16 | RUSH B (Russian team) | L   | 0.259      | -            | -                | -                | -             |    -3.20 | CYPHER, interz, JACKZ, MoDo, valde |
|           22 |     5580 | 2023-12-15 | Pompa Team            | W   | 0.252      | 0.143        | 0.000 (0.000)    | 0.014 (0.000)    | false (0.000) |     1.98 | CYPHER, interz, JACKZ, MoDo, valde |
|           21 |     5691 | 2023-12-11 | RUSH B (Russian team) | L   | 0.225      | -            | -                | -                | -             |    -2.82 | CYPHER, interz, JACKZ, MoDo, valde |
|           20 |     5746 | 2023-12-10 | Preasy Esport         | L   | 0.216      | -            | -                | -                | -             |    -1.42 | CYPHER, interz, JACKZ, MoDo, valde |
|           19 |     5828 | 2023-12-08 | BIG Academy           | L   | 0.206      | -            | -                | -                | -             |    -2.25 | CYPHER, interz, JACKZ, MoDo, valde |
|           18 |     5904 | 2023-12-07 | IKLA                  | W   | 0.196      | 0.371        | 0.001 (0.000)    | 0.125 (0.009)    | false (0.000) |     2.83 | CYPHER, interz, JACKZ, MoDo, valde |
|           17 |     5974 | 2023-12-05 | Zero Tenacity         | W   | 0.186      | 0.371        | 0.095 (0.007)    | 1.000 (0.069)    | false (0.000) |     4.69 | CYPHER, interz, JACKZ, MoDo, valde |
|           16 |     6005 | 2023-12-05 | GODSENT               | L   | 0.183      | -            | -                | -                | -             |    -2.17 | CYPHER, interz, JACKZ, MoDo, valde |
|           15 |     6067 | 2023-12-03 | Zero Tenacity         | W   | 0.169      | 0.371        | 0.095 (0.006)    | 1.000 (0.063)    | false (0.000) |     4.31 | CYPHER, interz, JACKZ, MoDo, valde |
|           14 |     6169 | 2023-12-01 | Legacy                | W   | 0.157      | 0.371        | 0.061 (0.004)    | 0.262 (0.015)    | false (0.000) |     4.50 | CYPHER, interz, JACKZ, MoDo, valde |
|           13 |     6208 | 2023-11-30 | TY                    | W   | 0.151      | 0.371        | 0.011 (0.001)    | 0.055 (0.003)    | false (0.000) |     2.28 | CYPHER, interz, JACKZ, MoDo, valde |
|           12 |     6214 | 2023-11-30 | GenOne                | L   | 0.151      | -            | -                | -                | -             |    -2.91 | CYPHER, interz, JACKZ, MoDo, valde |
|           11 |     6525 | 2023-11-23 | Nexus Gaming          | W   | 0.104      | 0.371        | 0.031 (0.001)    | 0.772 (0.030)    | false (0.000) |     2.63 | CYPHER, interz, JACKZ, MoDo, valde |
|           10 |     6529 | 2023-11-23 | L&G                   | W   | 0.104      | 0.371        | 0.000 (0.000)    | 0.010 (0.000)    | false (0.000) |     0.76 | CYPHER, interz, JACKZ, MoDo, valde |
|            9 |     6784 | 2023-11-17 | SINNERS Esports       | L   | 0.064      | -            | -                | -                | -             |    -0.34 | CYPHER, interz, JACKZ, MoDo, valde |
|            8 |     6835 | 2023-11-16 | 3DMAX                 | W   | 0.057      | 0.589        | 0.062 (0.002)    | 0.393 (0.013)    | false (0.000) |     1.44 | CYPHER, interz, JACKZ, MoDo, valde |
|            7 |     6883 | 2023-11-15 | Kappa Bar             | L   | 0.052      | -            | -                | -                | -             |    -0.87 | CYPHER, interz, JACKZ, MoDo, valde |
|            6 |     6954 | 2023-11-13 | BIG                   | L   | 0.039      | -            | -                | -                | -             |    -0.02 | CYPHER, interz, JACKZ, MoDo, valde |
|            5 |     7101 | 2023-11-10 | L&G                   | W   | 0.017      | 0.371        | -                | 0.064 (0.000)    | false (0.000) |     0.16 | CYPHER, interz, JACKZ, MoDo, valde |
|            4 |     7131 | 2023-11-09 | Entropiq              | L   | 0.012      | -            | -                | -                | -             |    -0.14 | CYPHER, interz, JACKZ, MoDo, valde |
|            3 |     7144 | 2023-11-09 | Lilmix                | L   | 0.011      | -            | -                | -                | -             |    -0.17 | CYPHER, interz, JACKZ, MoDo, valde |
|            2 |     7187 | 2023-11-08 | Sashi Esport          | W   | 0.005      | 0.371        | 0.013 (0.000)    | -                | -             |     0.08 | CYPHER, interz, JACKZ, MoDo, valde |
|            1 |     7208 | 2023-11-08 | EYEBALLERS            | L   | 0.004      | -            | -                | -                | -             |    -0.02 | CYPHER, interz, JACKZ, MoDo, valde |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,306.67)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-13 |      0.238 | $3,000.00      | $714.03         |
| 2023-12-12 |      0.231 | $1,000.00      | $231.06         |
| 2023-11-18 |      0.072 | $5,000.00      | $361.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
