### Roster Details<br />
Team Name: Lilmix<br />
Roster: Brillo, dex, L00m1, quix, SeBreeZe<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [397](../standings_global.md)<br />
Regional Rank: [237]( ../standings_europe.md)<br />
Final Rank Value:  566.8<br />
<br />
Final Rank Value (566.8) = Starting Rank Value (556.4) + Head To Head Adjustments (10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.077<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 556.4
- 400 + ( ( 0.077 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 556.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     7820 | 2024-01-17 | Copenhagen Wolves   | L   | 0.311      | -            | -                | -                | -         |    -3.70 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           18 |     8110 | 2024-01-12 | Permitta Esports    | L   | 0.278      | -            | -                | -                | -         |    -0.90 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           17 |     8126 | 2024-01-12 | Permitta Esports    | L   | 0.276      | -            | -                | -                | -         |    -0.91 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           16 |     8188 | 2024-01-11 | ALTERNATE aTTaX     | W   | 0.270      | 0.143        | 0.052 (0.002)    | 0.735 (0.028)    | 1 (0.270) |     7.93 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           15 |     8193 | 2024-01-11 | Momenta             | W   | 0.270      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.270) |     2.46 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           14 |     8206 | 2024-01-11 | Team Spirit Academy | L   | 0.269      | -            | -                | -                | -         |    -2.27 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           13 |     8373 | 2024-01-09 | ex-Anonymo Esports  | L   | 0.257      | -            | -                | -                | -         |    -2.53 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           12 |     8450 | 2024-01-07 | Permitta Esports    | W   | 0.242      | 0.333        | 0.025 (0.002)    | 1.000 (0.081)    | 0 (0.000) |     6.91 | Brillo, dex, L00m1, quix, SeBreeZe    |
|           11 |     8466 | 2024-01-06 | ROSOMAHA            | L   | 0.236      | -            | -                | -                | -         |    -3.32 | Brillo, dex, L00m1, quix, treckiz     |
|           10 |     8500 | 2024-01-03 | Begrip Gaming       | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.317 (0.010)    | 0 (0.000) |     3.97 | Brillo, Chawzyyy, dex, L00m1, quix    |
|            9 |     8511 | 2024-01-03 | RawkAndRawl         | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     2.05 | Brillo, Chawzyyy, dex, L00m1, quix    |
|            8 |     8519 | 2024-01-03 | stcity              | W   | 0.217      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.02 | Brillo, Chawzyyy, dex, L00m1, quix    |
|            7 |     8708 | 2023-12-17 | Metizport           | L   | 0.104      | -            | -                | -                | -         |    -0.29 | Brillo, dex, L00m1, quix, SeBreeZe    |
|            6 |     8728 | 2023-12-17 | Alliance            | L   | 0.103      | -            | -                | -                | -         |    -0.47 | Brillo, dex, L00m1, quix, SeBreeZe    |
|            5 |     8751 | 2023-12-17 | Uruguay3            | W   | 0.102      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.102) |     1.23 | Brillo, dex, L00m1, quix, SeBreeZe    |
|            4 |     9091 | 2023-12-13 | Kappa Bar           | L   | 0.078      | -            | -                | -                | -         |    -1.32 | Brillo, dex, L00m1, quix, SeBreeZe    |
|            3 |     9100 | 2023-12-13 | G-Units             | W   | 0.077      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.72 | Brillo, dex, L00m1, quix, SeBreeZe    |
|            2 |     9307 | 2023-12-09 | Kappa Bar           | L   | 0.049      | -            | -                | -                | -         |    -0.84 | dex, L00m1, melonhead, quix, SeBreeZe |
|            1 |     9604 | 2023-12-05 | NOM Esports         | L   | 0.022      | -            | -                | -                | -         |    -0.26 | dex, L00m1, melonhead, quix, SeBreeZe |

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
