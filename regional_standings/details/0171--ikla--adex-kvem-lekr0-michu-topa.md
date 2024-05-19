### Roster Details<br />
Team Name: IKLA<br />
Roster: adeX, Kvem, Lekr0, MICHU, Topa<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [171](../standings_global.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
Final Rank Value:  752.2<br />
<br />
Final Rank Value (752.2) = Starting Rank Value (692.7) + Head To Head Adjustments (59.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.7
- 400 + ( ( 0.148 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 692.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     4566 | 2024-01-20 | HEROIC                | L   | 0.490      | -            | -                | -                | -             |    -0.08 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           20 |     4611 | 2024-01-19 | Pera Esports          | L   | 0.484      | -            | -                | -                | -             |    -4.04 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           19 |     4656 | 2024-01-18 | Eternal Fire          | L   | 0.478      | -            | -                | -                | -             |    -0.05 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           18 |     4664 | 2024-01-18 | Aurora Gaming         | W   | 0.478      | 0.143        | 1.000 (0.068)    | 0.799 (0.055)    | false (0.000) |    14.94 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           17 |     4981 | 2024-01-11 | Pera Esports          | W   | 0.433      | 0.143        | 0.065 (0.004)    | 0.324 (0.020)    | false (0.000) |    10.34 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           16 |     4986 | 2024-01-11 | HEROIC                | L   | 0.432      | -            | -                | -                | -             |    -0.06 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           15 |     4994 | 2024-01-11 | Team Space            | W   | 0.432      | 0.143        | 0.008 (0.001)    | 0.201 (0.012)    | false (0.000) |     7.14 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           14 |     5002 | 2024-01-11 | 00 Nation             | W   | 0.431      | 0.143        | 0.000 (0.000)    | 0.048 (0.003)    | false (0.000) |     3.11 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           13 |     5041 | 2024-01-10 | GODSENT               | W   | 0.426      | 0.143        | 0.026 (0.002)    | 0.423 (0.026)    | false (0.000) |     8.39 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           12 |     5058 | 2024-01-10 | The Witchers          | W   | 0.426      | 0.143        | 0.035 (0.002)    | 0.158 (0.010)    | false (0.000) |     8.38 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           11 |     5083 | 2024-01-09 | BLEED Esports         | L   | 0.419      | -            | -                | -                | -             |    -1.16 | adeX, Kvem, Lekr0, MICHU, Topa           |
|           10 |     5092 | 2024-01-09 | Metizport             | W   | 0.418      | 0.143        | 0.188 (0.011)    | 1.000 (0.060)    | false (0.000) |    11.16 | adeX, Kvem, Lekr0, MICHU, Topa           |
|            9 |     5353 | 2023-12-17 | 9Pandas               | W   | 0.265      | 0.143        | 0.085 (0.003)    | 0.661 (0.025)    | false (0.000) |     7.69 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            8 |     5463 | 2023-12-16 | Pompa Team            | W   | 0.259      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | false (0.000) |     2.29 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            7 |     5583 | 2023-12-15 | RUSH B (Russian team) | L   | 0.252      | -            | -                | -                | -             |    -2.83 | kensizor, Kvem, MICHU, s4ltovsk1yy, Topa |
|            6 |     5904 | 2023-12-07 | TSM                   | L   | 0.196      | -            | -                | -                | -             |    -2.83 | forsyy, Kvem, Lekr0, MICHU, Topa         |
|            5 |     6377 | 2023-11-27 | Entropiq              | L   | 0.131      | -            | -                | -                | -             |    -1.50 | Kvem, MICHU, ROGA, Topa, VLDN            |
|            4 |     6646 | 2023-11-20 | Alliance              | L   | 0.084      | -            | -                | -                | -             |    -0.67 | Kvem, MICHU, ROGA, Topa, VLDN            |
|            3 |     6839 | 2023-11-16 | ALTERNATE aTTaX       | L   | 0.057      | -            | -                | -                | -             |    -0.18 | Kvem, MICHU, ROGA, Topa, VLDN            |
|            2 |     6872 | 2023-11-15 | Aurora Gaming         | L   | 0.052      | -            | -                | -                | -             |    -0.01 | draken, Kvem, MICHU, Topa, xicoz         |
|            1 |     6999 | 2023-11-12 | Sangal Esports        | L   | 0.032      | -            | -                | -                | -             |    -0.62 | draken, Kvem, MICHU, Topa, xicoz         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
