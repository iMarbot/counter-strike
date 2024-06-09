### Roster Details<br />
Team Name: Wings Up Gaming<br />
Roster: ChildKing, flying, gas, Marek, risk<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [220](../standings_global.md)<br />
Regional Rank: [27]( ../standings_asia.md)<br />
Final Rank Value:  707.7<br />
<br />
Final Rank Value (707.7) = Starting Rank Value (675.1) + Head To Head Adjustments (32.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.1
- 400 + ( ( 0.135 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 675.1


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
|           21 |     7280 | 2024-01-26 | The Huns Esports   | L   | 0.370      | -            | -                | -                | -         |    -3.08 | ChildKing, flying, gas, Marek, risk |
|           20 |     7287 | 2024-01-26 | TYLOO              | L   | 0.368      | -            | -                | -                | -         |    -4.13 | ChildKing, flying, gas, Marek, risk |
|           19 |     7317 | 2024-01-25 | Rare Atom          | W   | 0.362      | 0.143        | 0.011 (0.001)    | 0.139 (0.007)    | 0 (0.000) |     6.03 | ChildKing, flying, gas, Marek, risk |
|           18 |     7320 | 2024-01-25 | GR Gaming          | W   | 0.362      | 0.143        | 0.007 (0.000)    | 0.428 (0.022)    | 0 (0.000) |     7.03 | ChildKing, flying, gas, Marek, risk |
|           17 |     7366 | 2024-01-24 | LYG Gaming         | W   | 0.356      | 0.143        | 0.001 (0.000)    | 0.275 (0.014)    | 0 (0.000) |     6.06 | ChildKing, flying, gas, Marek, risk |
|           16 |     7374 | 2024-01-24 | MIRAI Gaming       | W   | 0.356      | 0.143        | 0.000 (0.000)    | 0.200 (0.010)    | 0 (0.000) |     5.83 | ChildKing, flying, gas, Marek, risk |
|           15 |     7481 | 2024-01-22 | The Huns Esports   | L   | 0.343      | -            | -                | -                | -         |    -2.75 | ChildKing, flying, gas, Marek, risk |
|           14 |     7489 | 2024-01-22 | -72C               | W   | 0.343      | 0.143        | 0.000 (0.000)    | 0.252 (0.012)    | 0 (0.000) |     6.38 | ChildKing, flying, gas, Marek, risk |
|           13 |     7616 | 2024-01-20 | Rare Atom          | L   | 0.328      | -            | -                | -                | -         |    -4.88 | ChildKing, flying, gas, Marek, risk |
|           12 |     7679 | 2024-01-19 | Lynn Vision Gaming | L   | 0.321      | -            | -                | -                | -         |    -0.89 | ChildKing, flying, gas, Marek, risk |
|           11 |     7683 | 2024-01-18 | Steel Helmet       | W   | 0.321      | 0.143        | 0.012 (0.001)    | 0.087 (0.004)    | 0 (0.000) |     5.05 | ChildKing, flying, gas, Marek, risk |
|           10 |     8468 | 2024-01-06 | TYLOO              | L   | 0.236      | -            | -                | -                | -         |    -2.56 | ChildKing, flying, gas, Marek, risk |
|            9 |     8472 | 2024-01-06 | ATOX Esports       | W   | 0.235      | 0.143        | 0.047 (0.002)    | 0.609 (0.020)    | 0 (0.000) |     7.12 | ChildKing, flying, gas, Marek, risk |
|            8 |     8483 | 2024-01-05 | TYLOO              | L   | 0.228      | -            | -                | -                | -         |    -2.46 | ChildKing, flying, gas, Marek, risk |
|            7 |     8489 | 2024-01-04 | NewHappy           | W   | 0.223      | 0.143        | 0.003 (0.000)    | 0.066 (0.002)    | 0 (0.000) |     3.58 | ChildKing, flying, gas, Marek, risk |
|            6 |     8495 | 2024-01-03 | Team NKT           | W   | 0.221      | 0.143        | 0.006 (0.000)    | 0.158 (0.005)    | 0 (0.000) |     3.93 | ChildKing, flying, gas, Marek, risk |
|            5 |     8524 | 2024-01-03 | ATOX Esports       | L   | 0.215      | -            | -                | -                | -         |    -0.24 | ChildKing, flying, gas, Marek, risk |
|            4 |     8551 | 2024-01-01 | The Huns Esports   | W   | 0.208      | 0.143        | 0.000 (0.000)    | 0.292 (0.009)    | 0 (0.000) |     5.05 | ChildKing, flying, gas, Marek, risk |
|            3 |     8591 | 2023-12-23 | Steel Helmet       | L   | 0.142      | -            | -                | -                | -         |    -2.23 | ChildKing, flying, gas, Marek, risk |
|            2 |     8599 | 2023-12-22 | TYLOO              | L   | 0.141      | -            | -                | -                | -         |    -1.50 | ChildKing, flying, gas, Marek, risk |
|            1 |     8601 | 2023-12-22 | MungYu Esports     | W   | 0.141      | -            | -                | -                | -         |     1.20 | ChildKing, flying, gas, Marek, risk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,659.07)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
