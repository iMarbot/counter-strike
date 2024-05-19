### Roster Details<br />
Team Name: Wings Up Gaming<br />
Roster: ChildKing, flying, gas, Marek, risk<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [155](../standings_global.md)<br />
Regional Rank: [24]( ../standings_asia.md)<br />
Final Rank Value:  772.1<br />
<br />
Final Rank Value (772.1) = Starting Rank Value (718.6) + Head To Head Adjustments (53.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.363[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 718.6
- 400 + ( ( 0.161 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 718.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     4333 | 2024-01-26 | The Huns Esports   | L   | 0.531      | -            | -                | -                | -             |    -5.21 | ChildKing, flying, gas, Marek, risk |
|           20 |     4340 | 2024-01-26 | TYLOO              | L   | 0.530      | -            | -                | -                | -             |    -2.86 | ChildKing, flying, gas, Marek, risk |
|           19 |     4361 | 2024-01-25 | Rare Atom          | W   | 0.523      | 0.143        | 0.026 (0.002)    | 0.259 (0.019)    | false (0.000) |     8.56 | ChildKing, flying, gas, Marek, risk |
|           18 |     4364 | 2024-01-25 | GR Gaming          | W   | 0.523      | 0.143        | 0.006 (0.000)    | 0.495 (0.037)    | false (0.000) |     9.60 | ChildKing, flying, gas, Marek, risk |
|           17 |     4393 | 2024-01-24 | LYG Gaming         | W   | 0.517      | 0.143        | 0.004 (0.000)    | 0.380 (0.028)    | false (0.000) |     8.70 | ChildKing, flying, gas, Marek, risk |
|           16 |     4401 | 2024-01-24 | MIRAI Gaming       | W   | 0.517      | 0.143        | 0.000 (0.000)    | 0.246 (0.018)    | false (0.000) |     7.15 | ChildKing, flying, gas, Marek, risk |
|           15 |     4479 | 2024-01-22 | The Huns Esports   | L   | 0.504      | -            | -                | -                | -             |    -4.66 | ChildKing, flying, gas, Marek, risk |
|           14 |     4487 | 2024-01-22 | -72C               | W   | 0.504      | 0.143        | 0.003 (0.000)    | 0.300 (0.022)    | false (0.000) |     8.78 | ChildKing, flying, gas, Marek, risk |
|           13 |     4577 | 2024-01-20 | Rare Atom          | L   | 0.489      | -            | -                | -                | -             |    -7.45 | ChildKing, flying, gas, Marek, risk |
|           12 |     4625 | 2024-01-19 | Lynn Vision Gaming | L   | 0.482      | -            | -                | -                | -             |    -0.77 | ChildKing, flying, gas, Marek, risk |
|           11 |     4628 | 2024-01-18 | Steel Helmet       | W   | 0.482      | 0.143        | 0.025 (0.002)    | 0.174 (0.012)    | false (0.000) |     7.01 | ChildKing, flying, gas, Marek, risk |
|           10 |     5181 | 2024-01-06 | TYLOO              | L   | 0.397      | -            | -                | -                | -             |    -1.90 | ChildKing, flying, gas, Marek, risk |
|            9 |     5183 | 2024-01-06 | ATOX Esports       | W   | 0.396      | 0.143        | 0.112 (0.006)    | 0.769 (0.043)    | false (0.000) |    10.95 | ChildKing, flying, gas, Marek, risk |
|            8 |     5193 | 2024-01-05 | TYLOO              | L   | 0.389      | -            | -                | -                | -             |    -1.80 | ChildKing, flying, gas, Marek, risk |
|            7 |     5195 | 2024-01-04 | NewHappy           | W   | 0.384      | 0.143        | 0.014 (0.001)    | 0.170 (0.009)    | false (0.000) |     6.98 | ChildKing, flying, gas, Marek, risk |
|            6 |     5201 | 2024-01-03 | Team NKT           | W   | 0.382      | 0.143        | 0.016 (0.001)    | 0.259 (0.014)    | false (0.000) |     7.00 | ChildKing, flying, gas, Marek, risk |
|            5 |     5220 | 2024-01-03 | ATOX Esports       | L   | 0.376      | -            | -                | -                | -             |    -1.31 | ChildKing, flying, gas, Marek, risk |
|            4 |     5242 | 2024-01-01 | The Huns Esports   | W   | 0.369      | 0.143        | 0.002 (0.000)    | 0.434 (0.023)    | false (0.000) |     8.79 | ChildKing, flying, gas, Marek, risk |
|            3 |     5275 | 2023-12-23 | Steel Helmet       | L   | 0.303      | -            | -                | -                | -             |    -5.03 | ChildKing, flying, gas, Marek, risk |
|            2 |     5283 | 2023-12-22 | TYLOO              | L   | 0.302      | -            | -                | -                | -             |    -1.25 | ChildKing, flying, gas, Marek, risk |
|            1 |     5285 | 2023-12-22 | MungYu Esports     | W   | 0.302      | -            | -                | -                | -             |     2.23 | ChildKing, flying, gas, Marek, risk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,792.93)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
