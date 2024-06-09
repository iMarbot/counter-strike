### Roster Details<br />
Team Name: Sangal Esports<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [40](../standings_global.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
Final Rank Value:  1120.8<br />
<br />
Final Rank Value (1120.8) = Starting Rank Value (1111.3) + Head To Head Adjustments (9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.562[<sup>1</sup>](#table2)
- Bounty Collected: 0.454[<sup>2</sup>](#table1)
- Opponent Network: 0.383[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.350<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1111.3
- 400 + ( ( 0.350 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1111.3


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
|           70 |      498 | 2024-05-22 | Zero Tenacity       | W   | 1.000      | 0.500        | 0.147 (0.073)    | 1.000 (0.500)    | 0 (0.000) |    13.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           69 |      626 | 2024-05-21 | Monte               | W   | 1.000      | 0.500        | 0.181 (0.090)    | -                | 0 (0.000) |    22.65 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           68 |      720 | 2024-05-20 | PARIVISION          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.70 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           67 |      742 | 2024-05-19 | Ninjas in Pyjamas   | W   | 1.000      | 0.500        | 0.118 (0.059)    | -                | 0 (0.000) |    16.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           66 |      782 | 2024-05-19 | Endpoint            | W   | 1.000      | 0.435        | -                | 0.770 (0.335)    | 0 (0.000) |     9.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           65 |      917 | 2024-05-18 | Rare Atom           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           64 |     1028 | 2024-05-17 | Permitta Esports    | W   | 1.000      | 0.435        | -                | 1.000 (0.435)    | 0 (0.000) |     7.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           63 |     1069 | 2024-05-16 | Ninjas in Pyjamas   | L   | 1.000      | -            | -                | -                | -         |   -12.64 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           62 |     1206 | 2024-05-15 | Verdant             | L   | 1.000      | -            | -                | -                | -         |   -22.17 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           61 |     1305 | 2024-05-14 | DMS                 | L   | 1.000      | -            | -                | -                | -         |   -22.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           60 |     1512 | 2024-05-10 | 9Pandas             | W   | 1.000      | 0.143        | 0.110 (0.016)    | -                | 0 (0.000) |    16.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           59 |     1516 | 2024-05-10 | kONO.ECF            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.12 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           58 |     1528 | 2024-05-10 | Permitta Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           57 |     1537 | 2024-05-10 | PARIVISION          | W   | 1.000      | -            | -                | -                | -         |    10.89 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           56 |     1951 | 2024-05-02 | Metizport           | L   | 1.000      | -            | -                | -                | -         |   -15.41 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           55 |     2035 | 2024-05-01 | ALTERNATE aTTaX     | L   | 1.000      | -            | -                | -                | -         |   -21.07 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           54 |     2062 | 2024-04-30 | Zero Tenacity       | W   | 1.000      | 0.500        | 0.147 (0.073)    | 1.000 (0.500)    | -         |    13.29 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           53 |     2119 | 2024-04-29 | SINNERS Esports     | W   | 0.995      | 0.500        | -                | 0.582 (0.290)    | -         |    11.77 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           52 |     2143 | 2024-04-28 | 1win                | W   | 0.990      | 0.435        | 0.050 (0.022)    | 0.898 (0.386)    | -         |    13.86 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           51 |     2214 | 2024-04-27 | PARIVISION          | L   | 0.983      | -            | -                | -                | -         |   -19.67 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           50 |     2316 | 2024-04-26 | Nemiga Gaming       | W   | 0.975      | 0.435        | 0.358 (0.152)    | 0.895 (0.380)    | -         |    21.60 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           49 |     2485 | 2024-04-23 | Grannys Knockers    | W   | 0.954      | -            | -                | -                | -         |     6.90 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           48 |     2510 | 2024-04-22 | BLEED Esports       | L   | 0.950      | -            | -                | -                | -         |    -7.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           47 |     2525 | 2024-04-22 | ex-Guild Eagles     | L   | 0.948      | -            | -                | -                | -         |   -17.20 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           46 |     2578 | 2024-04-21 | Alliance            | W   | 0.941      | 0.500        | -                | 0.529 (0.249)    | -         |     8.19 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           45 |     2635 | 2024-04-20 | brazylijski luz     | W   | 0.937      | -            | -                | -                | -         |     7.90 | jottAAA, LNZ, sausol, xfl0ud, yxngstxr  |
|           44 |     2703 | 2024-04-20 | JANO Esports        | W   | 0.934      | -            | -                | -                | -         |     4.92 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           43 |     2740 | 2024-04-19 | TSM                 | W   | 0.931      | -            | -                | -                | -         |     5.75 | jottAAA, LNZ, sausol, xfl0ud, yxngstxr  |
|           42 |     2763 | 2024-04-19 | Nemiga Gaming       | L   | 0.930      | -            | -                | -                | -         |    -8.52 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           41 |     2932 | 2024-04-17 | 9Pandas             | W   | 0.915      | 0.500        | 0.110 (0.050)    | 0.710 (0.325)    | -         |    17.96 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           40 |     2962 | 2024-04-16 | Zero Tenacity       | W   | 0.910      | 0.143        | 0.147 (0.019)    | -                | -         |    12.00 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           39 |     3008 | 2024-04-15 | B8                  | W   | 0.904      | 0.500        | 0.168 (0.076)    | 0.963 (0.435)    | -         |    17.75 | jottAAA, LNZ, sausol, xfl0ud, yxngstxr  |
|           38 |     3023 | 2024-04-15 | Aurora Young Blud   | W   | 0.903      | -            | -                | -                | -         |     6.21 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           37 |     3145 | 2024-04-12 | Monte               | L   | 0.883      | -            | -                | -                | -         |    -5.41 | jottAAA, LNZ, sausol, xfl0ud, yxngstxr  |
|           36 |     3577 | 2024-04-04 | EYEBALLERS          | W   | 0.831      | -            | -                | -                | -         |    10.56 | jottAAA, LNZ, sausol, xfl0ud, yxngstxr  |
|           35 |     3688 | 2024-04-02 | 9Pandas             | L   | 0.817      | -            | -                | -                | -         |    -6.55 | jottAAA, LNZ, sausol, xfl0ud, yxngstxr  |
|           34 |     4593 | 2024-03-13 | KOI                 | L   | 0.684      | -            | -                | -                | -         |    -8.94 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           33 |     4847 | 2024-03-09 | Zero Tenacity       | L   | 0.656      | -            | -                | -                | -         |    -9.91 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           32 |     4950 | 2024-03-07 | 500                 | L   | 0.643      | -            | -                | -                | -         |   -14.52 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           31 |     4986 | 2024-03-06 | TSM                 | W   | 0.638      | -            | -                | -                | -         |     4.21 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           30 |     5161 | 2024-03-04 | Betera Esports      | L   | 0.625      | -            | -                | -                | -         |   -14.43 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           29 |     5198 | 2024-03-04 | Team Sampi          | W   | 0.622      | -            | -                | -                | -         |     7.29 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           28 |     5238 | 2024-03-03 | Rebels Gaming       | L   | 0.617      | -            | -                | -                | -         |    -7.66 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           27 |     5360 | 2024-03-02 | HAVU Gaming         | W   | 0.609      | -            | -                | -                | -         |     3.42 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           26 |     5425 | 2024-02-29 | Rebels Gaming       | L   | 0.597      | -            | -                | -                | -         |    -7.65 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           25 |     5489 | 2024-02-28 | Alliance            | L   | 0.589      | -            | -                | -                | -         |   -13.91 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           24 |     5505 | 2024-02-27 | 9INE                | W   | 0.584      | -            | -                | -                | -         |     1.92 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           23 |     5557 | 2024-02-26 | FORZE Esports       | L   | 0.578      | -            | -                | -                | -         |   -10.96 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           22 |     5601 | 2024-02-25 | Sashi Esport        | W   | 0.571      | -            | -                | -                | -         |     9.71 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           21 |     5956 | 2024-02-20 | Permitta Esports    | L   | 0.536      | -            | -                | -                | -         |   -10.30 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           20 |     6069 | 2024-02-18 | 500                 | W   | 0.522      | -            | -                | -                | -         |     3.20 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           19 |     6181 | 2024-02-16 | Astralis Talent     | W   | 0.508      | -            | -                | -                | -         |     5.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           18 |     6406 | 2024-02-12 | Permitta Esports    | L   | 0.482      | -            | -                | -                | -         |    -9.77 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           17 |     6527 | 2024-02-08 | AURA                | L   | 0.456      | -            | -                | -                | -         |   -13.32 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           16 |     6585 | 2024-02-06 | ex-Preasy Esport    | L   | 0.442      | -            | -                | -                | -         |    -9.99 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           15 |     6683 | 2024-02-04 | ALTERNATE aTTaX     | W   | 0.428      | -            | -                | -                | -         |     4.70 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           14 |     6758 | 2024-02-03 | Entropiq            | L   | 0.423      | -            | -                | -                | -         |   -12.14 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     6777 | 2024-02-03 | Metizport           | L   | 0.422      | -            | -                | -                | -         |    -8.52 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     6890 | 2024-02-01 | Team Spirit Academy | W   | 0.410      | -            | -                | -                | -         |     1.58 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     6904 | 2024-02-01 | ALTERNATE aTTaX     | W   | 0.408      | -            | -                | -                | -         |     4.49 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     7041 | 2024-01-29 | Sashi Esport        | L   | 0.392      | -            | -                | -                | -         |    -6.86 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     7103 | 2024-01-28 | Gaimin Gladiators   | L   | 0.382      | -            | -                | -                | -         |    -3.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     7369 | 2024-01-24 | Team Spirit Academy | W   | 0.356      | -            | -                | -                | -         |     1.31 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     8282 | 2024-01-10 | ex-sYnck            | L   | 0.265      | -            | -                | -                | -         |    -7.45 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     8338 | 2024-01-09 | BLEED Esports       | L   | 0.257      | -            | -                | -                | -         |    -2.36 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     8378 | 2024-01-09 | EC Kostroma         | W   | 0.257      | -            | -                | -                | -         |     0.15 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     8845 | 2023-12-16 | GenOne              | L   | 0.098      | -            | -                | -                | -         |    -2.97 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     8863 | 2023-12-16 | Insilio             | W   | 0.097      | -            | -                | -                | -         |     0.70 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     9666 | 2023-12-03 | IKLA                | L   | 0.009      | -            | -                | -                | -         |    -0.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     9796 | 2023-12-02 | Entropiq            | W   | 0.002      | -            | -                | -                | -         |     0.00 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

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
