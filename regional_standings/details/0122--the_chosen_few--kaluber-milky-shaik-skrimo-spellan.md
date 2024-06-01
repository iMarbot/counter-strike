### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: KalubeR, milky, shaiK, Skrimo, SPELLAN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [122](../standings_global.md)<br />
Regional Rank: [85]( ../standings_europe.md)<br />
Final Rank Value:  820.1<br />
<br />
Final Rank Value (820.1) = Starting Rank Value (769.6) + Head To Head Adjustments (50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.148[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.182<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 769.6
- 400 + ( ( 0.182 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 769.6


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
|           41 |     4288 | 2024-03-17 | ENRAGE               | L   | 0.709      | -            | -                | -                | -         |   -18.79 | KalubeR, milky, shaiK, Skrimo, SPELLAN  |
|           40 |     4383 | 2024-03-15 | Permitta Esports     | L   | 0.696      | -            | -                | -                | -         |    -6.97 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           39 |     4431 | 2024-03-14 | Endpoint             | W   | 0.691      | 0.371        | 0.012 (0.003)    | 0.718 (0.184)    | 0 (0.000) |    13.61 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           38 |     4559 | 2024-03-12 | ARCRED               | W   | 0.677      | 0.371        | -                | 0.630 (0.158)    | 0 (0.000) |    10.07 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           37 |     4713 | 2024-03-09 | Passion UA           | W   | 0.657      | 0.371        | 0.057 (0.014)    | 1.000 (0.244)    | 0 (0.000) |    13.80 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           36 |     4871 | 2024-03-06 | Insilio              | L   | 0.637      | -            | -                | -                | -         |    -6.21 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           35 |     5065 | 2024-03-03 | Metizport            | L   | 0.618      | -            | -                | -                | -         |    -4.51 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           34 |     5072 | 2024-03-03 | TSM                  | W   | 0.618      | 0.143        | 0.011 (0.001)    | -                | 0 (0.000) |     8.51 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           33 |     5084 | 2024-03-03 | KOI                  | W   | 0.617      | 0.143        | 0.027 (0.002)    | -                | 0 (0.000) |    15.11 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           32 |     5117 | 2024-03-02 | Lilmix               | W   | 0.612      | 0.143        | -                | 0.581 (0.051)    | 0 (0.000) |    10.63 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           31 |     5152 | 2024-03-02 | Sashi Esport         | W   | 0.611      | 0.143        | 0.172 (0.015)    | 1.000 (0.087)    | 0 (0.000) |    16.25 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           30 |     5235 | 2024-03-01 | FAVBET Team          | L   | 0.604      | -            | -                | -                | -         |    -7.01 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           29 |     5271 | 2024-02-29 | Verdant              | W   | 0.597      | 0.371        | 0.014 (0.003)    | 1.000 (0.222)    | 0 (0.000) |    13.57 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           28 |     5375 | 2024-02-27 | VP.Prodigy           | L   | 0.583      | -            | -                | -                | -         |    -7.64 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           27 |     5557 | 2024-02-24 | brazylijski luz      | L   | 0.563      | -            | -                | -                | -         |    -8.52 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           26 |     5604 | 2024-02-23 | DASH                 | L   | 0.557      | -            | -                | -                | -         |   -10.63 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           25 |     5609 | 2024-02-23 | Aurora Young Blud    | W   | 0.557      | 0.371        | 0.008 (0.002)    | 0.506 (0.105)    | 0 (0.000) |     8.63 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           24 |     5648 | 2024-02-22 | ex-Anonymo Esports   | W   | 0.551      | -            | -                | -                | 0 (0.000) |     7.31 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           23 |     5661 | 2024-02-22 | Permitta Esports     | W   | 0.550      | 0.371        | 0.029 (0.006)    | 1.000 (0.204)    | -         |    13.34 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           22 |     5927 | 2024-02-17 | Entropiq             | L   | 0.518      | -            | -                | -                | -         |   -10.37 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           21 |     5940 | 2024-02-17 | kONO.ECF             | L   | 0.517      | -            | -                | -                | -         |    -5.34 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           20 |     5951 | 2024-02-17 | Monte                | L   | 0.516      | -            | -                | -                | -         |    -0.76 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           19 |     5989 | 2024-02-16 | GenOne               | L   | 0.510      | -            | -                | -                | -         |   -12.49 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           18 |     6101 | 2024-02-14 | HOTU                 | W   | 0.497      | 0.371        | 0.004 (0.001)    | 0.524 (0.097)    | -         |     9.18 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           17 |     6207 | 2024-02-12 | Endpoint             | W   | 0.484      | 0.371        | 0.012 (0.002)    | 0.718 (0.129)    | -         |    10.93 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           16 |     6254 | 2024-02-10 | ex-Anonymo Esports   | W   | 0.471      | -            | -                | -                | -         |     7.01 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           15 |     6326 | 2024-02-08 | Team Spirit Academy  | L   | 0.458      | -            | -                | -                | -         |    -7.34 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           14 |     6460 | 2024-02-04 | AIRLYA               | W   | 0.430      | -            | -                | -                | -         |     3.11 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           13 |     6495 | 2024-02-03 | Zero Tenacity        | L   | 0.425      | -            | -                | -                | -         |    -2.11 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           12 |     6599 | 2024-02-02 | Natus Vincere Junior | W   | 0.417      | -            | -                | -                | -         |     7.14 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           11 |     6615 | 2024-02-02 | Jake Bube            | W   | 0.417      | -            | -                | -                | -         |     2.56 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           10 |     6634 | 2024-02-02 | Natus Vincere Junior | L   | 0.416      | -            | -                | -                | -         |    -6.02 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            9 |     6703 | 2024-01-31 | Soda Gaming          | W   | 0.404      | -            | -                | -                | -         |     4.34 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            8 |     6781 | 2024-01-29 | RUBY                 | L   | 0.392      | -            | -                | -                | -         |    -3.69 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            7 |     6799 | 2024-01-29 | HAVU Gaming          | W   | 0.392      | -            | -                | -                | -         |     6.42 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|            6 |     7544 | 2024-01-17 | Soda Gaming          | L   | 0.311      | -            | -                | -                | -         |    -6.57 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            5 |     7659 | 2024-01-16 | Nexus Gaming         | L   | 0.304      | -            | -                | -                | -         |    -2.94 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            4 |     7866 | 2024-01-12 | 500                  | L   | 0.278      | -            | -                | -                | -         |    -4.43 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            3 |     8457 | 2023-12-17 | WinX                 | W   | 0.104      | -            | -                | -                | -         |     0.83 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            2 |     8471 | 2023-12-17 | Gr Infractional      | W   | 0.103      | -            | -                | -                | -         |     0.59 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            1 |     9451 | 2023-12-02 | Gorillas             | L   | 0.004      | -            | -                | -                | -         |    -0.10 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($717.58)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-25 |      0.764 | $750.00        | $572.71         |
| 2023-12-17 |      0.104 | $1,394.51      | $144.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
