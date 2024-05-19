### Roster Details<br />
Team Name: Rare Atom<br />
Roster: EXPRO, kory, phzy, somebody, Summer<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [110](../standings_global.md)<br />
Regional Rank: [13]( ../standings_asia.md)<br />
Final Rank Value:  839.1<br />
<br />
Final Rank Value (839.1) = Starting Rank Value (749.4) + Head To Head Adjustments (89.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 749.4
- 400 + ( ( 0.176 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 749.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2629 | 2024-03-06 | Cloud9             | L   | 0.798      | -            | -                | -                | -         |    -0.15 | EXPRO, kory, phzy, somebody, Summer |
|           26 |     4050 | 2024-02-02 | GR Gaming          | W   | 0.577      | 0.143        | -                | 0.495 (0.041)    | 0 (0.000) |     9.27 | EXPRO, kory, phzy, somebody, Summer |
|           25 |     4052 | 2024-02-02 | TYLOO              | W   | 0.576      | 0.143        | 0.131 (0.011)    | 0.592 (0.049)    | 0 (0.000) |    14.78 | EXPRO, kory, phzy, somebody, Summer |
|           24 |     4121 | 2024-01-31 | Team NKT           | W   | 0.564      | 0.143        | 0.016 (0.001)    | 0.259 (0.021)    | 0 (0.000) |     8.98 | EXPRO, kory, phzy, somebody, Summer |
|           23 |     4123 | 2024-01-31 | Lynn Vision Gaming | W   | 0.564      | 0.143        | 0.155 (0.013)    | 0.554 (0.045)    | 0 (0.000) |    16.53 | EXPRO, kory, phzy, somebody, Summer |
|           22 |     4128 | 2024-01-31 | ATOX Esports       | L   | 0.563      | -            | -                | -                | -         |    -2.96 | EXPRO, kory, phzy, somebody, Summer |
|           21 |     4357 | 2024-01-25 | AP Gaming          | W   | 0.524      | 0.143        | 0.082 (0.006)    | 0.152 (0.011)    | 0 (0.000) |    11.39 | EXPRO, kory, phzy, somebody, Summer |
|           20 |     4361 | 2024-01-25 | Wings Up Gaming    | L   | 0.523      | -            | -                | -                | -         |    -8.56 | EXPRO, kory, phzy, somebody, Summer |
|           19 |     4363 | 2024-01-25 | NewHappy           | W   | 0.523      | 0.143        | 0.014 (0.001)    | 0.170 (0.013)    | 0 (0.000) |     8.11 | EXPRO, kory, phzy, somebody, Summer |
|           18 |     4368 | 2024-01-24 | Change The Game    | W   | 0.522      | -            | -                | -                | 0 (0.000) |     5.30 | EXPRO, kory, phzy, somebody, Summer |
|           17 |     4392 | 2024-01-24 | Aravt              | W   | 0.517      | 0.143        | -                | 0.143 (0.011)    | 0 (0.000) |     4.17 | EXPRO, kory, phzy, somebody, Summer |
|           16 |     4395 | 2024-01-24 | Drippy Lab         | W   | 0.517      | -            | -                | -                | 0 (0.000) |     1.82 | EXPRO, kory, phzy, somebody, Summer |
|           15 |     4482 | 2024-01-22 | ATOX Esports       | L   | 0.504      | -            | -                | -                | -         |    -2.31 | EXPRO, kory, phzy, somebody, Summer |
|           14 |     4485 | 2024-01-22 | NOBackstab         | W   | 0.504      | -            | -                | -                | 0 (0.000) |     1.76 | EXPRO, kory, phzy, somebody, Summer |
|           13 |     4511 | 2024-01-21 | TYLOO              | L   | 0.497      | -            | -                | -                | -         |    -2.64 | EXPRO, kory, phzy, somebody, Summer |
|           12 |     4516 | 2024-01-21 | NewHappy           | W   | 0.496      | 0.143        | 0.014 (0.001)    | 0.170 (0.012)    | -         |     8.25 | EXPRO, kory, phzy, somebody, Summer |
|           11 |     4577 | 2024-01-20 | Wings Up Gaming    | W   | 0.489      | 0.143        | 0.018 (0.001)    | 0.172 (0.012)    | -         |     7.45 | EXPRO, kory, phzy, somebody, Summer |
|           10 |     4581 | 2024-01-19 | SHPL               | W   | 0.488      | 0.143        | 0.044 (0.003)    | 0.151 (0.011)    | -         |    10.47 | EXPRO, kory, phzy, somebody, Summer |
|            9 |     4629 | 2024-01-18 | NewHappy           | L   | 0.482      | -            | -                | -                | -         |    -7.00 | EXPRO, kory, phzy, somebody, Summer |
|            8 |     4947 | 2024-01-12 | Steel Helmet       | L   | 0.437      | -            | -                | -                | -         |    -7.79 | EXPRO, kory, phzy, somebody, Summer |
|            7 |     4951 | 2024-01-12 | SHPL               | W   | 0.437      | 0.143        | 0.044 (0.003)    | -                | -         |     9.51 | EXPRO, kory, phzy, somebody, Summer |
|            6 |     4971 | 2024-01-11 | 侧面男孩               | W   | 0.435      | -            | -                | -                | -         |     1.68 | EXPRO, kory, phzy, somebody, Summer |
|            5 |     5276 | 2023-12-23 | NewHappy           | L   | 0.303      | -            | -                | -                | -         |    -4.83 | EXPRO, kory, phzy, somebody, Summer |
|            4 |     5282 | 2023-12-22 | Lynn Vision Gaming | L   | 0.302      | -            | -                | -                | -         |    -0.48 | EXPRO, kory, phzy, somebody, Summer |
|            3 |     5287 | 2023-12-22 | Steel Helmet       | W   | 0.302      | 0.143        | 0.025 (0.001)    | -                | -         |     4.06 | EXPRO, kory, phzy, somebody, Summer |
|            2 |     5490 | 2023-12-16 | MIRAI Gaming       | W   | 0.257      | -            | -                | -                | -         |     3.56 | EXPRO, kory, phzy, somebody, Summer |
|            1 |     6891 | 2023-11-15 | LYG Gaming         | L   | 0.050      | -            | -                | -                | -         |    -0.71 | EXPRO, kory, phzy, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,127.89)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
