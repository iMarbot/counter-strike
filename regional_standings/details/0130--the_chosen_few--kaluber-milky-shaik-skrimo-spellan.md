### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: KalubeR, milky, shaiK, Skrimo, SPELLAN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [130](../standings_global.md)<br />
Regional Rank: [90]( ../standings_europe.md)<br />
Final Rank Value:  812.0<br />
<br />
Final Rank Value (812.0) = Starting Rank Value (747.2) + Head To Head Adjustments (64.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.232[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.171<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 747.2
- 400 + ( ( 0.171 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 747.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |     4394 | 2024-03-17 | ENRAGE               | L   | 0.709      | -            | -                | -                | -         |   -18.64 | KalubeR, milky, shaiK, Skrimo, SPELLAN  |
|           40 |     4492 | 2024-03-15 | Permitta Esports     | L   | 0.696      | -            | -                | -                | -         |    -6.37 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           39 |     4545 | 2024-03-14 | Endpoint             | W   | 0.691      | 0.371        | 0.012 (0.003)    | 0.770 (0.197)    | 0 (0.000) |    13.85 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           38 |     4679 | 2024-03-12 | ARCRED               | W   | 0.677      | 0.371        | -                | 0.630 (0.158)    | 0 (0.000) |    10.37 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           37 |     4838 | 2024-03-09 | Passion UA           | W   | 0.657      | 0.371        | 0.057 (0.014)    | 1.000 (0.244)    | 0 (0.000) |    14.18 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           36 |     5002 | 2024-03-06 | Insilio              | L   | 0.637      | -            | -                | -                | -         |    -5.99 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           35 |     5211 | 2024-03-03 | Metizport            | L   | 0.618      | -            | -                | -                | -         |    -4.26 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           34 |     5218 | 2024-03-03 | TSM                  | W   | 0.618      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |     9.26 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           33 |     5230 | 2024-03-03 | KOI                  | W   | 0.617      | 0.143        | 0.027 (0.002)    | -                | 0 (0.000) |    15.39 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           32 |     5265 | 2024-03-02 | Lilmix               | W   | 0.612      | 0.143        | -                | 0.593 (0.052)    | 0 (0.000) |    10.51 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           31 |     5300 | 2024-03-02 | Sashi Esport         | W   | 0.611      | 0.143        | 0.154 (0.013)    | 1.000 (0.087)    | 0 (0.000) |    16.52 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           30 |     5384 | 2024-03-01 | FAVBET Team          | L   | 0.604      | -            | -                | -                | -         |    -6.43 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           29 |     5421 | 2024-02-29 | Verdant              | W   | 0.597      | 0.371        | 0.014 (0.003)    | 1.000 (0.222)    | 0 (0.000) |    13.90 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           28 |     5528 | 2024-02-27 | VP.Prodigy           | L   | 0.583      | -            | -                | -                | -         |    -6.91 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           27 |     5717 | 2024-02-24 | brazylijski luz      | L   | 0.563      | -            | -                | -                | -         |    -7.99 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           26 |     5764 | 2024-02-23 | DASH                 | L   | 0.557      | -            | -                | -                | -         |   -10.01 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           25 |     5769 | 2024-02-23 | Aurora Young Blud    | W   | 0.557      | 0.371        | 0.008 (0.002)    | 0.506 (0.105)    | 0 (0.000) |     9.09 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           24 |     5808 | 2024-02-22 | ex-Anonymo Esports   | W   | 0.551      | -            | -                | -                | 0 (0.000) |     7.63 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           23 |     5821 | 2024-02-22 | Permitta Esports     | W   | 0.550      | 0.371        | 0.025 (0.005)    | 1.000 (0.204)    | -         |    13.76 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           22 |     6100 | 2024-02-17 | Entropiq             | L   | 0.518      | -            | -                | -                | -         |    -9.99 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           21 |     6113 | 2024-02-17 | kONO.ECF             | L   | 0.517      | -            | -                | -                | -         |    -4.58 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           20 |     6124 | 2024-02-17 | Monte                | L   | 0.516      | -            | -                | -                | -         |    -0.68 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           19 |     6163 | 2024-02-16 | GenOne               | L   | 0.510      | -            | -                | -                | -         |   -12.16 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           18 |     6282 | 2024-02-14 | HOTU                 | W   | 0.497      | 0.371        | 0.004 (0.001)    | 0.580 (0.107)    | -         |     9.76 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           17 |     6394 | 2024-02-12 | Endpoint             | W   | 0.484      | 0.371        | 0.012 (0.002)    | 0.770 (0.138)    | -         |    11.31 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           16 |     6442 | 2024-02-10 | ex-Anonymo Esports   | W   | 0.471      | -            | -                | -                | -         |     7.34 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           15 |     6514 | 2024-02-08 | Team Spirit Academy  | L   | 0.458      | -            | -                | -                | -         |    -6.90 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           14 |     6663 | 2024-02-04 | AIRLYA               | W   | 0.430      | -            | -                | -                | -         |     3.27 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           13 |     6698 | 2024-02-03 | Zero Tenacity        | L   | 0.425      | -            | -                | -                | -         |    -2.08 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     6802 | 2024-02-02 | Natus Vincere Junior | W   | 0.417      | -            | -                | -                | -         |     7.50 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     6819 | 2024-02-02 | Jake Bube            | W   | 0.417      | -            | -                | -                | -         |     2.80 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     6839 | 2024-02-02 | Natus Vincere Junior | L   | 0.416      | -            | -                | -                | -         |    -5.64 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     6912 | 2024-01-31 | Soda Gaming          | W   | 0.404      | -            | -                | -                | -         |     5.15 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     6997 | 2024-01-29 | RUBY                 | L   | 0.392      | -            | -                | -                | -         |    -3.42 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     7015 | 2024-01-29 | HAVU Gaming          | W   | 0.392      | -            | -                | -                | -         |     6.79 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     7793 | 2024-01-17 | Soda Gaming          | L   | 0.311      | -            | -                | -                | -         |    -6.01 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            5 |     7908 | 2024-01-16 | Nexus Gaming         | L   | 0.304      | -            | -                | -                | -         |    -2.88 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            4 |     8119 | 2024-01-12 | 500                  | L   | 0.278      | -            | -                | -                | -         |    -4.15 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            3 |     8716 | 2023-12-17 | WinX                 | W   | 0.104      | -            | -                | -                | -         |     0.91 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            2 |     8731 | 2023-12-17 | Gr Infractional      | W   | 0.103      | -            | -                | -                | -         |     0.65 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            1 |     9733 | 2023-12-02 | Gorillas             | L   | 0.004      | -            | -                | -                | -         |    -0.10 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($144.87)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
