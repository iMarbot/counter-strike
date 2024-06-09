### Roster Details<br />
Team Name: IKLA<br />
Roster: adeX, Kvem, Lekr0, MICHU, Topa<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [357](../standings_global.md)<br />
Regional Rank: [213]( ../standings_europe.md)<br />
Final Rank Value:  603.7<br />
<br />
Final Rank Value (603.7) = Starting Rank Value (550.0) + Head To Head Adjustments (53.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.074<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 550.0
- 400 + ( ( 0.074 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 550.0


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
|           19 |     7601 | 2024-01-20 | HEROIC           | L   | 0.329      | -            | -                | -                | -         |    -0.02 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           18 |     7657 | 2024-01-19 | Pera Esports     | L   | 0.323      | -            | -                | -                | -         |    -1.48 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           17 |     7718 | 2024-01-18 | Eternal Fire     | L   | 0.317      | -            | -                | -                | -         |    -0.01 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           16 |     7726 | 2024-01-18 | Aurora Gaming    | W   | 0.317      | 0.143        | 0.492 (0.022)    | 0.573 (0.026)    | 0 (0.000) |     9.91 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           15 |     8168 | 2024-01-11 | Pera Esports     | W   | 0.272      | 0.143        | 0.028 (0.001)    | 0.542 (0.021)    | 0 (0.000) |     7.42 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           14 |     8174 | 2024-01-11 | HEROIC           | L   | 0.271      | -            | -                | -                | -         |    -0.01 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           13 |     8186 | 2024-01-11 | Team Space       | W   | 0.270      | 0.143        | 0.009 (0.000)    | 0.457 (0.018)    | 0 (0.000) |     6.99 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           12 |     8196 | 2024-01-11 | 00 Nation        | W   | 0.270      | 0.143        | 0.000 (0.000)    | 0.031 (0.001)    | 0 (0.000) |     3.30 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           11 |     8253 | 2024-01-10 | GODSENT          | W   | 0.265      | 0.143        | 0.001 (0.000)    | 0.084 (0.003)    | 0 (0.000) |     5.17 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           10 |     8279 | 2024-01-10 | The Witchers     | W   | 0.265      | 0.143        | 0.009 (0.000)    | 0.060 (0.002)    | 0 (0.000) |     5.82 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            9 |     8332 | 2024-01-09 | BLEED Esports    | L   | 0.258      | -            | -                | -                | -         |    -0.16 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            8 |     8341 | 2024-01-09 | Metizport        | W   | 0.257      | 0.143        | 0.088 (0.003)    | 0.698 (0.026)    | 0 (0.000) |     7.36 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            7 |     8376 | 2024-01-09 | ex-sYnck         | W   | 0.257      | 0.143        | 0.000 (0.000)    | 0.255 (0.009)    | 0 (0.000) |     5.88 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            6 |     8712 | 2023-12-17 | 9Pandas          | W   | 0.104      | 0.143        | 0.110 (0.002)    | 0.710 (0.011)    | 0 (0.000) |     3.19 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            5 |     8855 | 2023-12-16 | Pompa Team       | W   | 0.098      | -            | -                | -                | 0 (0.000) |     1.25 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            4 |     9004 | 2023-12-15 | RUSH B           | L   | 0.091      | -            | -                | -                | -         |    -0.67 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            3 |     9461 | 2023-12-07 | TSM              | L   | 0.035      | -            | -                | -                | -         |    -0.41 | forsyy, Kvem, Lekr0, MICHU, Topa         |
|            2 |     9605 | 2023-12-05 | ex-Preasy Esport | L   | 0.022      | -            | -                | -                | -         |    -0.08 | forsyy, Kvem, MICHU, Topa, VLDN          |
|            1 |     9666 | 2023-12-03 | Sangal Esports   | W   | 0.009      | 0.371        | 0.166 (0.001)    | 0.658 (0.002)    | -         |     0.27 | forsyy, Kvem, MICHU, Topa, VLDN          |

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
