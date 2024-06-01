### Roster Details<br />
Team Name: Sangal Esports<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [41](../standings_global.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
Final Rank Value:  1101.5<br />
<br />
Final Rank Value (1101.5) = Starting Rank Value (1090.6) + Head To Head Adjustments (10.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.562[<sup>1</sup>](#table2)
- Bounty Collected: 0.446[<sup>2</sup>](#table1)
- Opponent Network: 0.349[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.339<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1090.6
- 400 + ( ( 0.339 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1090.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      492 | 2024-05-22 | Zero Tenacity       | W   | 1.000      | 0.500        | 0.147 (0.073)    | 1.000 (0.500)    | 0 (0.000) |    14.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |      615 | 2024-05-21 | Monte               | W   | 1.000      | 0.500        | 0.181 (0.090)    | 0.363 (0.181)    | 0 (0.000) |    23.15 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |      708 | 2024-05-20 | PARIVISION          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.48 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |      730 | 2024-05-19 | Ninjas in Pyjamas   | W   | 1.000      | 0.500        | 0.118 (0.059)    | -                | 0 (0.000) |    17.73 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |      770 | 2024-05-19 | Endpoint            | W   | 1.000      | 0.435        | -                | 0.718 (0.312)    | 0 (0.000) |     9.87 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |      905 | 2024-05-18 | Rare Atom           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.27 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |     1016 | 2024-05-17 | Permitta Esports    | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     7.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |     1059 | 2024-05-16 | Ninjas in Pyjamas   | L   | 1.000      | -            | -                | -                | -         |   -11.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |     1196 | 2024-05-15 | Verdant             | L   | 1.000      | -            | -                | -                | -         |   -21.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     1294 | 2024-05-14 | DMS                 | L   | 1.000      | -            | -                | -                | -         |   -21.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     1499 | 2024-05-10 | 9Pandas             | W   | 1.000      | 0.143        | 0.110 (0.016)    | -                | 0 (0.000) |    17.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     1503 | 2024-05-10 | kONO.ECF            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     1514 | 2024-05-10 | Permitta Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.47 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     1523 | 2024-05-10 | PARIVISION          | W   | 1.000      | -            | -                | -                | -         |    12.03 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     1924 | 2024-05-02 | Metizport           | L   | 1.000      | -            | -                | -                | -         |   -13.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     2004 | 2024-05-01 | ALTERNATE aTTaX     | L   | 1.000      | -            | -                | -                | -         |   -19.90 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     2029 | 2024-04-30 | Zero Tenacity       | W   | 1.000      | 0.500        | 0.147 (0.073)    | 1.000 (0.500)    | -         |    14.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     2084 | 2024-04-29 | SINNERS Esports     | W   | 0.995      | 0.500        | -                | 0.560 (0.279)    | -         |    12.75 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     2108 | 2024-04-28 | 1win                | W   | 0.990      | 0.435        | 0.050 (0.022)    | 0.887 (0.382)    | -         |    15.63 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     2179 | 2024-04-27 | PARIVISION          | L   | 0.983      | -            | -                | -                | -         |   -18.05 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           44 |     2279 | 2024-04-26 | Nemiga Gaming       | W   | 0.975      | 0.435        | 0.366 (0.155)    | 0.830 (0.352)    | -         |    22.91 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     2437 | 2024-04-23 | Grannys Knockers    | W   | 0.954      | -            | -                | -                | -         |     7.59 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           42 |     2459 | 2024-04-22 | BLEED Esports       | L   | 0.950      | -            | -                | -                | -         |    -5.79 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     2472 | 2024-04-22 | ex-Guild Eagles     | L   | 0.948      | -            | -                | -                | -         |   -15.74 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2525 | 2024-04-21 | Alliance            | W   | 0.941      | 0.500        | -                | 0.529 (0.249)    | -         |     9.66 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     2649 | 2024-04-20 | JANO Esports        | W   | 0.934      | -            | -                | -                | -         |     5.76 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           38 |     2707 | 2024-04-19 | Nemiga Gaming       | L   | 0.930      | -            | -                | -                | -         |    -7.38 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     2875 | 2024-04-17 | 9Pandas             | W   | 0.915      | 0.500        | 0.110 (0.050)    | 0.660 (0.302)    | -         |    18.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           36 |     2903 | 2024-04-16 | Zero Tenacity       | W   | 0.910      | 0.143        | 0.147 (0.019)    | -                | -         |    13.62 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           35 |     2959 | 2024-04-15 | Aurora Young Blud   | W   | 0.903      | -            | -                | -                | -         |     6.54 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |     4479 | 2024-03-13 | KOI                 | L   | 0.684      | -            | -                | -                | -         |    -8.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           33 |     4722 | 2024-03-09 | Zero Tenacity       | L   | 0.656      | -            | -                | -                | -         |    -9.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           32 |     4821 | 2024-03-07 | 500                 | L   | 0.643      | -            | -                | -                | -         |   -14.19 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           31 |     4855 | 2024-03-06 | TSM                 | W   | 0.638      | -            | -                | -                | -         |     4.25 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           30 |     5015 | 2024-03-04 | Betera Esports      | L   | 0.625      | -            | -                | -                | -         |   -14.06 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           29 |     5052 | 2024-03-04 | Team Sampi          | W   | 0.622      | -            | -                | -                | -         |     7.76 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           28 |     5092 | 2024-03-03 | Rebels Gaming       | L   | 0.617      | -            | -                | -                | -         |    -7.29 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           27 |     5211 | 2024-03-02 | HAVU Gaming         | W   | 0.609      | -            | -                | -                | -         |     3.74 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           26 |     5275 | 2024-02-29 | Rebels Gaming       | L   | 0.597      | -            | -                | -                | -         |    -7.26 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           25 |     5337 | 2024-02-28 | Alliance            | L   | 0.589      | -            | -                | -                | -         |   -13.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           24 |     5352 | 2024-02-27 | 9INE                | W   | 0.584      | -            | -                | -                | -         |     2.13 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           23 |     5400 | 2024-02-26 | FORZE Esports       | L   | 0.578      | -            | -                | -                | -         |   -10.08 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           22 |     5443 | 2024-02-25 | Sashi Esport        | W   | 0.571      | 0.143        | 0.172 (0.014)    | -                | -         |    10.34 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           21 |     5786 | 2024-02-20 | Permitta Esports    | L   | 0.536      | -            | -                | -                | -         |    -9.99 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           20 |     5896 | 2024-02-18 | 500                 | W   | 0.522      | -            | -                | -                | -         |     3.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           19 |     6005 | 2024-02-16 | Astralis Talent     | W   | 0.508      | -            | -                | -                | -         |     5.82 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           18 |     6218 | 2024-02-12 | Permitta Esports    | L   | 0.482      | -            | -                | -                | -         |    -9.41 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           17 |     6339 | 2024-02-08 | AURA                | L   | 0.456      | -            | -                | -                | -         |   -13.22 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           16 |     6389 | 2024-02-06 | ex-Preasy Esport    | L   | 0.442      | -            | -                | -                | -         |    -9.65 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           15 |     6480 | 2024-02-04 | ALTERNATE aTTaX     | W   | 0.428      | -            | -                | -                | -         |     1.82 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           14 |     6555 | 2024-02-03 | Entropiq            | L   | 0.423      | -            | -                | -                | -         |   -12.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     6574 | 2024-02-03 | Metizport           | L   | 0.422      | -            | -                | -                | -         |    -8.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     6681 | 2024-02-01 | Team Spirit Academy | W   | 0.410      | -            | -                | -                | -         |     1.74 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     6695 | 2024-02-01 | ALTERNATE aTTaX     | W   | 0.408      | -            | -                | -                | -         |     1.67 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     6825 | 2024-01-29 | Sashi Esport        | L   | 0.392      | -            | -                | -                | -         |    -6.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     6885 | 2024-01-28 | Gaimin Gladiators   | L   | 0.382      | -            | -                | -                | -         |    -3.03 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     7134 | 2024-01-24 | Team Spirit Academy | W   | 0.356      | -            | -                | -                | -         |     1.44 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     8028 | 2024-01-10 | ex-sYnck            | L   | 0.265      | -            | -                | -                | -         |    -7.50 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     8084 | 2024-01-09 | BLEED Esports       | L   | 0.257      | -            | -                | -                | -         |    -2.21 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     8124 | 2024-01-09 | EC Kostroma         | W   | 0.257      | -            | -                | -                | -         |     0.17 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     8585 | 2023-12-16 | GenOne              | L   | 0.098      | -            | -                | -                | -         |    -2.96 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     8602 | 2023-12-16 | Insilio             | W   | 0.097      | -            | -                | -                | -         |     0.79 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     9384 | 2023-12-03 | IKLA                | L   | 0.009      | -            | -                | -                | -         |    -0.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     9514 | 2023-12-02 | Entropiq            | W   | 0.002      | -            | -                | -                | -         |     0.00 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($50,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
