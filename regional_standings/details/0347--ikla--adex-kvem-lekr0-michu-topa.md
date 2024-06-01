### Roster Details<br />
Team Name: IKLA<br />
Roster: adeX, Kvem, Lekr0, MICHU, Topa<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [347](../standings_global.md)<br />
Regional Rank: [207]( ../standings_europe.md)<br />
Final Rank Value:  605.9<br />
<br />
Final Rank Value (605.9) = Starting Rank Value (551.1) + Head To Head Adjustments (54.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.284[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.074<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 551.1
- 400 + ( ( 0.074 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 551.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     7357 | 2024-01-20 | HEROIC           | L   | 0.329      | -            | -                | -                | -         |    -0.02 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           18 |     7411 | 2024-01-19 | Pera Esports     | L   | 0.323      | -            | -                | -                | -         |    -1.46 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           17 |     7470 | 2024-01-18 | Eternal Fire     | L   | 0.317      | -            | -                | -                | -         |    -0.01 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           16 |     7477 | 2024-01-18 | Aurora Gaming    | W   | 0.317      | 0.143        | 0.492 (0.022)    | 0.616 (0.028)    | 0 (0.000) |     9.92 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           15 |     7915 | 2024-01-11 | Pera Esports     | W   | 0.272      | 0.143        | 0.028 (0.001)    | 0.574 (0.022)    | 0 (0.000) |     7.43 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           14 |     7921 | 2024-01-11 | HEROIC           | L   | 0.271      | -            | -                | -                | -         |    -0.01 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           13 |     7933 | 2024-01-11 | Team Space       | W   | 0.270      | 0.143        | 0.009 (0.000)    | 0.457 (0.018)    | 0 (0.000) |     6.97 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           12 |     7943 | 2024-01-11 | 00 Nation        | W   | 0.270      | -            | -                | -                | 0 (0.000) |     3.27 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           11 |     7999 | 2024-01-10 | GODSENT          | W   | 0.265      | 0.143        | 0.001 (0.000)    | 0.073 (0.003)    | 0 (0.000) |     5.12 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           10 |     8025 | 2024-01-10 | The Witchers     | W   | 0.265      | 0.143        | 0.009 (0.000)    | 0.060 (0.002)    | 0 (0.000) |     5.79 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            9 |     8078 | 2024-01-09 | BLEED Esports    | L   | 0.258      | -            | -                | -                | -         |    -0.16 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            8 |     8087 | 2024-01-09 | Metizport        | W   | 0.257      | 0.143        | 0.088 (0.003)    | 0.698 (0.026)    | 0 (0.000) |     7.34 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            7 |     8122 | 2024-01-09 | ex-sYnck         | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.206 (0.008)    | 0 (0.000) |     5.54 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            6 |     8453 | 2023-12-17 | 9Pandas          | W   | 0.104      | 0.143        | 0.110 (0.002)    | 0.660 (0.010)    | 0 (0.000) |     3.18 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            5 |     8594 | 2023-12-16 | Permitta Esports | W   | 0.098      | 0.143        | 0.029 (0.000)    | 1.000 (0.014)    | 0 (0.000) |     2.79 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            4 |     8742 | 2023-12-15 | RUSH B           | L   | 0.091      | -            | -                | -                | -         |    -0.67 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            3 |     9188 | 2023-12-07 | TSM              | L   | 0.035      | -            | -                | -                | -         |    -0.42 | forsyy, Kvem, Lekr0, MICHU, Topa         |
|            2 |     9323 | 2023-12-05 | ex-Preasy Esport | L   | 0.022      | -            | -                | -                | -         |    -0.08 | forsyy, Kvem, MICHU, Topa, VLDN          |
|            1 |     9384 | 2023-12-03 | Sangal Esports   | W   | 0.009      | 0.371        | 0.166 (0.001)    | 0.577 (0.002)    | -         |     0.27 | forsyy, Kvem, MICHU, Topa, VLDN          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
