### Roster Details<br />
Team Name: WOPA Esport<br />
Roster: brzer, Gnøffe, Leakz, LUMSEN, Vster<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [166](../standings_global.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
Final Rank Value:  758.0<br />
<br />
Final Rank Value (758.0) = Starting Rank Value (779.5) + Head To Head Adjustments (-21.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.330[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 779.5
- 400 + ( ( 0.191 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 779.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |       68 | 2024-05-04 | Copenhagen Wolves            | W   | 1.000      | 0.143        | -                | 0.417 (0.060)    | 0 (0.000) |    11.06 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           53 |       81 | 2024-05-04 | UNiTY esports (Slovak team)  | L   | 1.000      | -            | -                | -                | -         |   -10.04 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           52 |      159 | 2024-05-02 | Astralis Talent              | W   | 1.000      | 0.333        | 0.030 (0.010)    | 0.613 (0.204)    | 0 (0.000) |    20.74 | brzer, Gnøffe, Kragh, LUMSEN, Vster            |
|           51 |      216 | 2024-05-01 | Preasy Esport                | L   | 1.000      | -            | -                | -                | -         |   -16.07 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           50 |      278 | 2024-04-29 | Sashi Esport                 | L   | 1.000      | -            | -                | -                | -         |    -1.75 | Boye, brzer, Gnøffe, LUMSEN, Vster             |
|           49 |      323 | 2024-04-28 | UNiTY esports (Slovak team)  | L   | 1.000      | -            | -                | -                | -         |   -10.22 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           48 |      997 | 2024-04-16 | XI Esport                    | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.313 (0.045)    | 0 (0.000) |    11.29 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           47 |     1004 | 2024-04-16 | Sashi Academy                | W   | 1.000      | 0.143        | 0.004 (0.001)    | -                | 0 (0.000) |    10.80 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           46 |     1105 | 2024-04-13 | Esport Harte                 | L   | 1.000      | -            | -                | -                | -         |   -24.02 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           45 |     1110 | 2024-04-13 | Vendetta gaming              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.59 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           44 |     1314 | 2024-04-09 | UNiTY esports (Slovak team)  | L   | 1.000      | -            | -                | -                | -         |   -10.35 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           43 |     1451 | 2024-04-05 | Dynamo Eclot                 | W   | 0.997      | 0.333        | 0.189 (0.063)    | 0.953 (0.317)    | 0 (0.000) |    26.04 | brzer, Gnøffe, Leakz, LUMSEN, Vster            |
|           42 |     1605 | 2024-04-01 | UNiTY esports (Slovak team)  | L   | 0.970      | -            | -                | -                | -         |    -9.03 | K1-FiDa, Levi, M1key, NIO, Pechyn              |
|           41 |     1678 | 2024-03-29 | Astralis Talent              | L   | 0.949      | -            | -                | -                | -         |   -10.43 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           40 |     1916 | 2024-03-23 | En av de lette               | W   | 0.910      | 0.333        | 0.020 (0.006)    | 0.129 (0.039)    | 0 (0.000) |    13.65 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           39 |     2028 | 2024-03-20 | HyperSpirit                  | L   | 0.891      | -            | -                | -                | -         |   -15.26 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           38 |     2033 | 2024-03-20 | Astralis Talent              | L   | 0.890      | -            | -                | -                | -         |    -9.67 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           37 |     2061 | 2024-03-19 | Turów Zgorzelec Esport       | W   | 0.885      | 0.333        | 0.019 (0.006)    | 0.640 (0.189)    | 0 (0.000) |    15.51 | AxEcHo, darko, kadziu, Markoś, xKacpersky      |
|           36 |     2080 | 2024-03-18 | Raptors Esports Club         | L   | 0.879      | -            | -                | -                | -         |   -11.34 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           35 |     2164 | 2024-03-16 | ADEPTS                       | W   | 0.866      | 0.333        | 0.002 (0.000)    | -                | 0 (0.000) |    10.08 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky       |
|           34 |     2401 | 2024-03-11 | TEAM MAX (European mix-team) | W   | 0.832      | -            | -                | -                | 0 (0.000) |     5.71 | kL1o, Malkiss, tAk, tooizera, zecco            |
|           33 |     2414 | 2024-03-11 | Sashi Esport                 | L   | 0.832      | -            | -                | -                | -         |   -12.12 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           32 |     2421 | 2024-03-11 | Team Atlantic                | W   | 0.832      | -            | -                | -                | -         |     6.23 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           31 |     2571 | 2024-03-07 | Linx Legacy Madagaskar       | W   | 0.805      | -            | -                | -                | -         |     4.63 | dancer, fiction, kemi, masthead, Rezkiyy       |
|           30 |     2602 | 2024-03-06 | XI Esport                    | W   | 0.799      | 0.143        | 0.002 (0.000)    | 0.313 (0.036)    | -         |     9.77 | anber, Dengzoe, fez, foam, Scr0b               |
|           29 |     2606 | 2024-03-06 | Astralis Talent              | L   | 0.799      | -            | -                | -                | -         |    -7.05 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           28 |     2620 | 2024-03-06 | Copenhagen Wolves            | W   | 0.799      | 0.143        | -                | 0.417 (0.048)    | -         |     8.83 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           27 |     2700 | 2024-03-05 | IMMAPROBLEM                  | W   | 0.792      | -            | -                | -                | -         |     5.92 | Damkilde, daxy, NoProblemGuy, notaN, vester    |
|           26 |     3026 | 2024-02-27 | Preasy Esport                | L   | 0.745      | -            | -                | -                | -         |   -11.32 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           25 |     3735 | 2024-02-12 | Illuminar Gaming             | L   | 0.644      | -            | -                | -                | -         |    -9.05 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy           |
|           24 |     3834 | 2024-02-08 | Copenhagen Wolves            | W   | 0.616      | 0.303        | -                | 0.417 (0.078)    | -         |     6.77 | Basso, mupzG, smF, Svedjehed, szejn            |
|           23 |     4619 | 2024-01-19 | MOUZ NXT                     | L   | 0.483      | -            | -                | -                | -         |    -2.04 | Chr1zN, kristou, Neityu, PR, sirah             |
|           22 |     4675 | 2024-01-18 | Monte Gen                    | L   | 0.477      | -            | -                | -                | -         |    -6.06 | Gizmy, leen, n0te, ryu, shield                 |
|           21 |     4736 | 2024-01-17 | 500                          | L   | 0.472      | -            | -                | -                | -         |    -6.82 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           20 |     4901 | 2024-01-13 | ROSOMAHA                     | W   | 0.443      | -            | -                | -                | -         |     4.32 | D0nii, Maggent, rendY, skcH, Зippoch           |
|           19 |     5063 | 2024-01-10 | Nexus Gaming                 | L   | 0.423      | -            | -                | -                | -         |    -4.28 | BTN, ERSIN, ragga, s0und, XELLOW               |
|           18 |     5105 | 2024-01-09 | Team Sampi                   | L   | 0.418      | -            | -                | -                | -         |    -2.38 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           17 |     5172 | 2024-01-07 | Lazer Cats                   | W   | 0.403      | -            | -                | -                | -         |     2.30 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           16 |     5182 | 2024-01-06 | MOUZ NXT                     | L   | 0.396      | -            | -                | -                | -         |    -1.81 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           15 |     5218 | 2024-01-03 | Natus Vincere Junior         | W   | 0.377      | 0.303        | 0.025 (0.003)    | 0.492 (0.056)    | -         |     7.21 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           14 |     5615 | 2023-12-14 | NOM Esports                  | L   | 0.244      | -            | -                | -                | -         |    -4.67 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e    |
|           13 |     5679 | 2023-12-12 | Nexus Gaming                 | L   | 0.230      | -            | -                | -                | -         |    -2.03 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|           12 |     5699 | 2023-12-11 | XI Esport                    | L   | 0.225      | -            | -                | -                | -         |    -4.36 | anber, Dengzoe, foam, Pellyy, Scr0b            |
|           11 |     5706 | 2023-12-11 | AGO esports                  | W   | 0.223      | 0.303        | 0.004 (0.000)    | -                | -         |     2.35 | Dementor, DEPRESHN, sh3nanigan, Svedjehed, tAk |
|           10 |     5765 | 2023-12-09 | WHYKICK Team                 | W   | 0.212      | -            | -                | -                | -         |     0.75 | CYXXX, Frothe, HEADBANGER, olymp1c, t3nzy      |
|            9 |     5856 | 2023-12-08 | Astralis Talent              | L   | 0.203      | -            | -                | -                | -         |    -1.63 | ANSG1, JBOEN, kiR, kroK, tOPZ                  |
|            8 |     5882 | 2023-12-07 | Ex-KRC Genk Esports          | L   | 0.199      | -            | -                | -                | -         |    -2.86 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            7 |     5990 | 2023-12-05 | ENTERPRISE esports           | W   | 0.185      | -            | -                | -                | -         |     1.22 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            6 |     6025 | 2023-12-04 | AGO esports                  | W   | 0.176      | -            | -                | -                | -         |     1.87 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            5 |     6093 | 2023-12-02 | Sashi Esport                 | L   | 0.165      | -            | -                | -                | -         |    -2.98 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            4 |     6679 | 2023-11-19 | Team Universe                | L   | 0.077      | -            | -                | -                | -         |    -1.75 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            3 |     6896 | 2023-11-15 | Lazer Cats                   | L   | 0.050      | -            | -                | -                | -         |    -1.12 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            2 |     6956 | 2023-11-13 | Exzentriq United             | W   | 0.039      | -            | -                | -                | -         |     0.18 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |
|            1 |     6965 | 2023-11-13 | IMMAPROBLEM                  | W   | 0.039      | -            | -                | -                | -         |     0.24 | brzer, buNNy, Gnøffe, Leakz, LUMSEN            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,488.74)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-25 |      0.925 | $362.12        | $334.90         |
| 2024-03-23 |      0.912 | $1,000.00      | $912.31         |
| 2023-12-02 |      0.165 | $1,459.92      | $241.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
