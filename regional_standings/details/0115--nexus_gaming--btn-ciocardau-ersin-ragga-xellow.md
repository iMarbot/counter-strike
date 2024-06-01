### Roster Details<br />
Team Name: Nexus Gaming<br />
Roster: BTN, Ciocardau, ERSIN, ragga, XELLOW<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [115](../standings_global.md)<br />
Regional Rank: [80]( ../standings_europe.md)<br />
Final Rank Value:  841.4<br />
<br />
Final Rank Value (841.4) = Starting Rank Value (931.1) + Head To Head Adjustments (-89.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.295[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.261<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 931.1
- 400 + ( ( 0.261 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 931.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          106 |       88 | 2024-05-29 | VP.Prodigy           | L   | 1.000      | -            | -                | -                | -         |   -12.72 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|          105 |      211 | 2024-05-26 | Young Ninjas         | L   | 1.000      | -            | -                | -                | -         |   -13.73 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          104 |      220 | 2024-05-26 | Copenhagen Wolves    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|          103 |      227 | 2024-05-26 | Reason Gaming        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.48 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          102 |      412 | 2024-05-23 | Preasy Esport        | W   | 1.000      | 0.333        | -                | 0.642 (0.214)    | 0 (0.000) |    10.66 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|          101 |      496 | 2024-05-22 | GUN5 Esports         | L   | 1.000      | -            | -                | -                | -         |   -17.82 | BTN, ERSIN, fnl, ragga, XELLOW       |
|          100 |      587 | 2024-05-21 | Monte Gen            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.70 | BTN, Ed1m, ERSIN, ragga, XELLOW      |
|           99 |      597 | 2024-05-21 | Entropiq             | L   | 1.000      | -            | -                | -                | -         |   -21.73 | BTN, ERSIN, fnl, ragga, XELLOW       |
|           98 |      609 | 2024-05-21 | Endpoint             | W   | 1.000      | 0.372        | -                | 0.718 (0.267)    | 0 (0.000) |    14.66 | BTN, ERSIN, fnl, ragga, XELLOW       |
|           97 |      646 | 2024-05-20 | Lemoncats            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.31 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           96 |      746 | 2024-05-19 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |   -21.64 | BTN, ERSIN, fnl, ragga, XELLOW       |
|           95 |      752 | 2024-05-19 | Denial               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.47 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           94 |      963 | 2024-05-17 | varcolacu1996        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.79 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           93 |      982 | 2024-05-17 | HyperSpirit          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.66 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           92 |     1009 | 2024-05-17 | Passion UA           | L   | 1.000      | -            | -                | -                | -         |   -12.30 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           91 |     1163 | 2024-05-15 | kONO.ECF             | W   | 1.000      | 0.372        | -                | 0.778 (0.290)    | 0 (0.000) |    18.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           90 |     1209 | 2024-05-15 | Team Space           | L   | 1.000      | -            | -                | -                | -         |   -14.80 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           89 |     1278 | 2024-05-14 | Rhyno Esports        | W   | 1.000      | 0.372        | 0.029 (0.011)    | -                | -         |    20.92 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           88 |     1331 | 2024-05-13 | Team Sampi           | L   | 1.000      | -            | -                | -                | -         |    -9.19 | BTN, Ciocardau, ERSIN, ragga, XELLOW |
|           87 |     1373 | 2024-05-12 | V1dar Gaming         | L   | 1.000      | -            | -                | -                | -         |   -19.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           86 |     1495 | 2024-05-10 | LEON Esports         | W   | 1.000      | -            | -                | -                | -         |     9.85 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           85 |     1637 | 2024-05-08 | Passion UA           | W   | 1.000      | 0.372        | 0.057 (0.021)    | 1.000 (0.372)    | -         |    20.02 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           84 |     1680 | 2024-05-07 | ADEPTS               | W   | 1.000      | -            | -                | -                | -         |    11.16 | BTN, ERSIN, fnl, ragga, XELLOW       |
|           83 |     1896 | 2024-05-03 | ENCE Academy         | L   | 1.000      | -            | -                | -                | -         |   -18.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           82 |     1978 | 2024-05-01 | ARCRED               | L   | 1.000      | -            | -                | -                | -         |   -14.01 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           81 |     1994 | 2024-05-01 | Insilio              | L   | 1.000      | -            | -                | -                | -         |   -11.23 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           80 |     2048 | 2024-04-30 | Fnatic               | L   | 1.000      | -            | -                | -                | -         |    -5.08 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           79 |     2066 | 2024-04-29 | Endpoint             | L   | 0.997      | -            | -                | -                | -         |   -13.93 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           78 |     2077 | 2024-04-29 | VP.Prodigy           | L   | 0.996      | -            | -                | -                | -         |   -20.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           77 |     2082 | 2024-04-29 | LEON Esports         | W   | 0.995      | -            | -                | -                | -         |     8.47 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           76 |     2087 | 2024-04-29 | ENTERPRISE esports   | W   | 0.994      | 0.384        | -                | 0.809 (0.309)    | -         |    13.96 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           75 |     2129 | 2024-04-28 | brazylijski luz      | L   | 0.988      | -            | -                | -                | -         |   -16.70 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           74 |     2309 | 2024-04-25 | Metizport            | W   | 0.970      | 0.384        | 0.088 (0.033)    | 0.698 (0.260)    | -         |    22.53 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           73 |     2328 | 2024-04-25 | Grannys Knockers     | L   | 0.969      | -            | -                | -                | -         |   -18.50 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           72 |     2392 | 2024-04-24 | AMKAL ESPORTS        | L   | 0.962      | -            | -                | -                | -         |    -5.31 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           71 |     2432 | 2024-04-23 | Illuminar Gaming     | L   | 0.955      | -            | -                | -                | -         |   -18.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           70 |     2464 | 2024-04-22 | Zero Tenacity        | L   | 0.949      | -            | -                | -                | -         |   -11.83 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           69 |     2485 | 2024-04-21 | Young Ninjas         | W   | 0.944      | 0.500        | 0.043 (0.020)    | -                | -         |    15.43 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           68 |     2502 | 2024-04-21 | PARIVISION           | L   | 0.943      | -            | -                | -                | -         |   -16.68 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           67 |     2620 | 2024-04-20 | Permitta Esports     | W   | 0.936      | 0.500        | 0.029 (0.013)    | 1.000 (0.468)    | -         |    16.58 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           66 |     2750 | 2024-04-18 | Young Ninjas         | L   | 0.924      | -            | -                | -                | -         |   -13.39 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           65 |     2789 | 2024-04-18 | ENTERPRISE esports   | L   | 0.922      | -            | -                | -                | -         |   -15.90 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           64 |     3080 | 2024-04-12 | HyperSpirit          | L   | 0.883      | -            | -                | -                | -         |   -20.75 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           63 |     3191 | 2024-04-10 | B8                   | W   | 0.869      | 0.384        | 0.168 (0.056)    | 0.952 (0.318)    | -         |    19.36 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           62 |     3446 | 2024-04-05 | SINNERS Esports      | L   | 0.837      | -            | -                | -                | -         |   -11.04 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           61 |     3924 | 2024-03-25 | Sashi Esport         | L   | 0.764      | -            | -                | -                | -         |    -8.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           60 |     4557 | 2024-03-12 | Nemiga Gaming        | W   | 0.677      | 0.371        | 0.366 (0.092)    | -                | -         |    17.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           59 |     4616 | 2024-03-11 | RUBY                 | W   | 0.671      | -            | -                | -                | -         |    10.32 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           58 |     4710 | 2024-03-09 | INGLORIOUS           | W   | 0.657      | -            | -                | -                | -         |     6.63 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           57 |     4750 | 2024-03-08 | FAVBET Team          | W   | 0.651      | -            | -                | -                | -         |     9.39 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           56 |     4995 | 2024-03-04 | FORZE Esports        | L   | 0.625      | -            | -                | -                | -         |    -6.82 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           55 |     5014 | 2024-03-04 | KOMNATA              | W   | 0.625      | -            | -                | -                | -         |     3.96 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           54 |     5085 | 2024-03-03 | TSM                  | L   | 0.617      | -            | -                | -                | -         |   -14.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           53 |     5094 | 2024-03-03 | Zero Tenacity        | W   | 0.617      | 0.371        | 0.147 (0.034)    | 1.000 (0.229)    | -         |    12.45 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           52 |     5128 | 2024-03-02 | GUN5 Esports         | W   | 0.612      | -            | -                | -                | -         |     3.35 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           51 |     5155 | 2024-03-02 | Aurora Young Blud    | W   | 0.611      | -            | -                | -                | -         |     5.98 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           50 |     5239 | 2024-03-01 | Passion UA           | W   | 0.603      | 0.371        | 0.057 (0.013)    | 1.000 (0.224)    | -         |     9.76 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           49 |     5272 | 2024-02-29 | INGLORIOUS           | L   | 0.597      | -            | -                | -                | -         |   -12.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           48 |     5323 | 2024-02-28 | Aurora Young Blud    | W   | 0.590      | -            | -                | -                | -         |     5.72 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           47 |     5416 | 2024-02-26 | esmagaB              | W   | 0.577      | -            | -                | -                | -         |     6.21 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           46 |     5547 | 2024-02-24 | L&G                  | W   | 0.563      | -            | -                | -                | -         |     1.66 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           45 |     5776 | 2024-02-20 | ex-Guild Eagles      | L   | 0.536      | -            | -                | -                | -         |    -7.17 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           44 |     5827 | 2024-02-19 | Monte                | L   | 0.531      | -            | -                | -                | -         |    -1.48 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           43 |     5843 | 2024-02-19 | Astralis             | L   | 0.530      | -            | -                | -                | -         |    -0.25 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           42 |     6359 | 2024-02-07 | V1dar Gaming         | W   | 0.451      | -            | -                | -                | -         |     2.79 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           41 |     6427 | 2024-02-05 | Gaimin Gladiators    | L   | 0.437      | -            | -                | -                | -         |    -1.78 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           40 |     6469 | 2024-02-04 | BIG Academy          | L   | 0.429      | -            | -                | -                | -         |   -10.22 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           39 |     6505 | 2024-02-03 | 500                  | L   | 0.424      | -            | -                | -                | -         |    -9.18 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           38 |     6523 | 2024-02-03 | Jake Bube            | W   | 0.424      | -            | -                | -                | -         |     0.64 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           37 |     6564 | 2024-02-03 | AIRLYA               | L   | 0.423      | -            | -                | -                | -         |   -12.10 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           36 |     6632 | 2024-02-02 | Royalty              | W   | 0.416      | -            | -                | -                | -         |     0.59 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           35 |     6726 | 2024-01-31 | ALTERNATE aTTaX      | W   | 0.403      | -            | -                | -                | -         |     3.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           34 |     6888 | 2024-01-28 | Passion UA           | L   | 0.382      | -            | -                | -                | -         |    -5.14 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           33 |     7039 | 2024-01-26 | GamerLegion Academy  | W   | 0.370      | -            | -                | -                | -         |     4.08 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           32 |     7279 | 2024-01-21 | ex-sYnck             | W   | 0.336      | -            | -                | -                | -         |     2.52 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           31 |     7326 | 2024-01-20 | OG                   | L   | 0.331      | -            | -                | -                | -         |    -2.04 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           30 |     7359 | 2024-01-20 | BIG                  | W   | 0.329      | 0.143        | 0.235 (0.011)    | -                | -         |     9.74 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           29 |     7402 | 2024-01-19 | SINNERS Esports      | W   | 0.324      | -            | -                | -                | -         |     6.20 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           28 |     7457 | 2024-01-18 | Gaimin Gladiators    | L   | 0.318      | -            | -                | -                | -         |    -1.19 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           27 |     7473 | 2024-01-18 | 9Pandas              | L   | 0.317      | -            | -                | -                | -         |    -2.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           26 |     7622 | 2024-01-16 | Endpoint             | W   | 0.305      | -            | -                | -                | -         |     5.07 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           25 |     7631 | 2024-01-16 | FAVBET Team          | W   | 0.305      | -            | -                | -                | -         |     3.79 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           24 |     7651 | 2024-01-16 | Alliance             | W   | 0.304      | -            | -                | -                | -         |     4.05 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           23 |     7659 | 2024-01-16 | The Chosen Few       | W   | 0.304      | -            | -                | -                | -         |     2.94 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           22 |     7788 | 2024-01-13 | OG                   | L   | 0.283      | -            | -                | -                | -         |    -1.54 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           21 |     7832 | 2024-01-12 | Soda Gaming          | W   | 0.278      | -            | -                | -                | -         |     1.54 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           20 |     7846 | 2024-01-12 | JANO Esports         | W   | 0.278      | -            | -                | -                | -         |     0.79 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           19 |     7876 | 2024-01-12 | Astralis Talent      | L   | 0.275      | -            | -                | -                | -         |    -4.28 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           18 |     8033 | 2024-01-10 | WOPA Esport          | W   | 0.262      | -            | -                | -                | -         |     3.03 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           17 |     8101 | 2024-01-09 | ex-K10               | L   | 0.257      | -            | -                | -                | -         |    -4.71 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           16 |     8132 | 2024-01-09 | Team Space           | W   | 0.257      | -            | -                | -                | -         |     3.33 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           15 |     8181 | 2024-01-08 | Zero Tenacity        | L   | 0.249      | -            | -                | -                | -         |    -2.16 | BTN, CHANKY, ERSIN, ragga, XELLOW    |
|           14 |     8212 | 2024-01-06 | Astralis Talent      | L   | 0.236      | -            | -                | -                | -         |    -3.69 | BTN, ERSIN, ragga, s0und, XELLOW     |
|           13 |     8220 | 2024-01-05 | Monte Gen            | L   | 0.230      | -            | -                | -                | -         |    -5.06 | BTN, CHANKY, ERSIN, ragga, XELLOW    |
|           12 |     8394 | 2023-12-19 | MOUZ NXT             | L   | 0.117      | -            | -                | -                | -         |    -0.95 | BTN, ragga, s0und, smekk, XELLOW     |
|           11 |     8396 | 2023-12-19 | ex-Anonymo Esports   | L   | 0.117      | -            | -                | -                | -         |    -2.85 | BTN, ragga, s0und, smekk, XELLOW     |
|           10 |     8412 | 2023-12-18 | MOUZ NXT             | W   | 0.110      | -            | -                | -                | -         |     2.59 | BTN, ragga, s0und, smekk, XELLOW     |
|            9 |     8422 | 2023-12-18 | Astralis Talent      | L   | 0.109      | -            | -                | -                | -         |    -1.73 | BTN, ragga, s0und, smekk, XELLOW     |
|            8 |     8485 | 2023-12-17 | brazylijski luz      | L   | 0.102      | -            | -                | -                | -         |    -2.13 | BTN, ragga, s0und, smekk, XELLOW     |
|            7 |     8747 | 2023-12-15 | detoks               | W   | 0.090      | -            | -                | -                | -         |     0.24 | BTN, ragga, s0und, smekk, XELLOW     |
|            6 |     8761 | 2023-12-15 | Sashi Esport         | L   | 0.088      | -            | -                | -                | -         |    -2.48 | BTN, ragga, s0und, smekk, XELLOW     |
|            5 |     8891 | 2023-12-12 | WOPA Esport          | W   | 0.069      | -            | -                | -                | -         |     0.76 | BTN, ragga, s0und, smekk, XELLOW     |
|            4 |     8959 | 2023-12-10 | Natus Vincere Junior | L   | 0.057      | -            | -                | -                | -         |    -1.23 | BTN, ragga, s0und, smekk, XELLOW     |
|            3 |     9187 | 2023-12-07 | Pompa Team           | W   | 0.035      | -            | -                | -                | -         |     0.08 | BTN, ragga, s0und, smekk, XELLOW     |
|            2 |     9216 | 2023-12-06 | GamerLegion Academy  | W   | 0.031      | -            | -                | -                | -         |     0.36 | BTN, ragga, s0und, smekk, XELLOW     |
|            1 |     9383 | 2023-12-03 | Lazer Cats           | W   | 0.009      | -            | -                | -                | -         |     0.01 | BTN, ragga, s0und, smekk, XELLOW     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,283.53)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-03-25 |      0.764 | $4,300.00      | $3,283.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
