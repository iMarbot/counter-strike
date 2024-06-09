### Roster Details<br />
Team Name: Atrix Esports<br />
Roster: LyttleZ, mari, s1non, segalla, sofiaxyz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [324](../standings_global.md)<br />
Regional Rank: [75]( ../standings_americas.md)<br />
Final Rank Value:  626.9<br />
<br />
Final Rank Value (626.9) = Starting Rank Value (682.4) + Head To Head Adjustments (-55.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 682.4
- 400 + ( ( 0.139 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 682.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |       41 | 2024-05-29 | Vikings KR           | L   | 1.000      | -            | -                | -                | -         |   -11.75 | LyttleZ, mari, s1non, segalla, sofiaxyz    |
|           19 |      202 | 2024-05-26 | MIBR Female          | L   | 1.000      | -            | -                | -                | -         |   -13.63 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|           18 |      259 | 2024-05-25 | ex-DIVINA Female     | W   | 1.000      | 0.250        | 0.004 (0.001)    | 0.053 (0.013)    | 0 (0.000) |    14.19 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|           17 |      842 | 2024-05-18 | Angels               | L   | 1.000      | -            | -                | -                | -         |   -21.09 | LyttleZ, Rosseti, s1non, segalla, sofiaxyz |
|           16 |      850 | 2024-05-18 | beliebers            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.78 | LyttleZ, Rosseti, s1non, segalla, sofiaxyz |
|           15 |      863 | 2024-05-18 | pugdesonesto         | L   | 1.000      | -            | -                | -                | -         |   -19.41 | LyttleZ, Rosseti, s1non, segalla, sofiaxyz |
|           14 |     2186 | 2024-04-27 | FURIA Esports Female | L   | 0.985      | -            | -                | -                | -         |   -11.42 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|           13 |     2192 | 2024-04-27 | ODDIK Academy        | L   | 0.984      | -            | -                | -                | -         |   -18.05 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|           12 |     2201 | 2024-04-27 | pugdesonesto         | W   | 0.984      | 0.143        | 0.001 (0.000)    | 0.146 (0.021)    | 0 (0.000) |    10.10 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|           11 |     2728 | 2024-04-19 | Illusion             | W   | 0.931      | 0.332        | 0.003 (0.001)    | 0.028 (0.009)    | 0 (0.000) |    10.31 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|           10 |     3170 | 2024-04-11 | ex-DIVINA Female     | W   | 0.878      | 0.332        | 0.004 (0.001)    | 0.053 (0.015)    | 0 (0.000) |    12.37 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            9 |     3565 | 2024-04-04 | MIBR Female          | L   | 0.831      | -            | -                | -                | -         |   -12.64 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            8 |     3871 | 2024-03-27 | w7m esports Female   | W   | 0.778      | 0.332        | 0.010 (0.002)    | 0.091 (0.024)    | 0 (0.000) |    11.96 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            7 |     4031 | 2024-03-24 | Rocket.GG            | L   | 0.758      | -            | -                | -                | -         |   -13.70 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            6 |     4033 | 2024-03-24 | NIGERIA ACADEMY      | W   | 0.757      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.32 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            5 |     4062 | 2024-03-23 | Bulls 95             | W   | 0.753      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.14 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            4 |     4153 | 2024-03-21 | FURIA Esports Female | L   | 0.738      | -            | -                | -                | -         |    -7.64 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            3 |     4522 | 2024-03-14 | GENKID4M4            | W   | 0.692      | 0.332        | 0.004 (0.001)    | 0.032 (0.007)    | 0 (0.000) |    10.50 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            2 |     4974 | 2024-03-06 | Fluxo Demons         | L   | 0.638      | -            | -                | -                | -         |    -5.80 | bokor, LyttleZ, mari, s1non, sofiaxyz      |
|            1 |     7552 | 2024-01-20 | Baludinhas           | L   | 0.332      | -            | -                | -                | -         |    -6.08 | bokor, LyttleZ, mari, s1non, sofiaxyz      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,708.11)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $250.00        | $250.00         |
| 2024-04-19 |      0.931 | $1,500.00      | $1,396.88       |
| 2024-03-25 |      0.766 | $79.96         | $61.24          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
