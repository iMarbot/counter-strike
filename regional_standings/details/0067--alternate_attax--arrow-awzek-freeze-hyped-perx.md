### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: ArroW, awzek, FreeZe, hyped, PerX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [67](../standings_global.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
Final Rank Value:  937.0<br />
<br />
Final Rank Value (937.0) = Starting Rank Value (1088.3) + Head To Head Adjustments (-151.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.511[<sup>1</sup>](#table2)
- Bounty Collected: 0.428[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.125[<sup>2</sup>](#table1)

The average of these factors is 0.347<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1088.3
- 400 + ( ( 0.347 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1088.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |      154 | 2024-05-02 | MOUZ NXT                 | L   | 1.000      | -            | -                | -                | -             |   -10.71 | ArroW, awzek, FreeZe, hyped, PerX   |
|           92 |      211 | 2024-05-01 | Team Sampi               | W   | 1.000      | 0.143        | 0.108 (0.015)    | -                | false (0.000) |    18.48 | ArroW, awzek, FreeZe, hyped, PerX   |
|           91 |      241 | 2024-04-30 | Endpoint                 | L   | 1.000      | -            | -                | -                | -             |   -16.48 | ArroW, awzek, FreeZe, hyped, PerX   |
|           90 |      254 | 2024-04-30 | Team Sampi               | W   | 1.000      | 0.143        | 0.108 (0.015)    | -                | false (0.000) |    18.58 | ArroW, awzek, FreeZe, hyped, PerX   |
|           89 |      312 | 2024-04-28 | Passion UA               | W   | 1.000      | 0.500        | 0.114 (0.057)    | 0.980 (0.490)    | false (0.000) |    15.74 | ArroW, awzek, FreeZe, hyped, PerX   |
|           88 |      419 | 2024-04-26 | Astralis Talent          | L   | 1.000      | -            | -                | -                | -             |   -18.51 | ArroW, awzek, FreeZe, hyped, skyye  |
|           87 |      446 | 2024-04-26 | Gaimin Gladiators        | W   | 1.000      | 0.500        | 0.194 (0.097)    | 0.989 (0.494)    | false (0.000) |    28.65 | ArroW, awzek, FreeZe, hyped, PerX   |
|           86 |      487 | 2024-04-25 | Team Space               | W   | 1.000      | -            | -                | -                | false (0.000) |     9.38 | ArroW, awzek, FreeZe, hyped, PerX   |
|           85 |      534 | 2024-04-24 | Astralis Talent          | L   | 1.000      | -            | -                | -                | -             |   -17.95 | ArroW, FreeZe, hyped, PerX, skyye   |
|           84 |      592 | 2024-04-23 | ENTERPRISE esports       | W   | 1.000      | 0.384        | -                | 0.476 (0.183)    | false (0.000) |    16.20 | ArroW, FreeZe, hyped, PerX, skyye   |
|           83 |      594 | 2024-04-23 | Permitta Esports         | L   | 1.000      | -            | -                | -                | -             |   -14.04 | ArroW, FreeZe, hyped, PerX, skyye   |
|           82 |      620 | 2024-04-22 | ENCE Academy             | W   | 1.000      | -            | -                | -                | false (0.000) |    12.92 | ArroW, FreeZe, hyped, PerX, skyye   |
|           81 |      644 | 2024-04-21 | MOUZ NXT                 | L   | 1.000      | -            | -                | -                | -             |    -9.41 | ArroW, awzek, FreeZe, hyped, skyye  |
|           80 |      672 | 2024-04-21 | Team Sampi               | L   | 1.000      | -            | -                | -                | -             |   -10.74 | ArroW, FreeZe, hyped, PerX, skyye   |
|           79 |      700 | 2024-04-20 | Team Space               | L   | 1.000      | -            | -                | -                | -             |   -23.19 | ArroW, awzek, FreeZe, hyped, skyye  |
|           78 |      775 | 2024-04-20 | ENTERPRISE esports       | W   | 1.000      | 0.500        | 0.039 (0.020)    | 0.476 (0.238)    | -             |    15.88 | ArroW, awzek, FreeZe, hyped, skyye  |
|           77 |      831 | 2024-04-19 | Passion UA               | W   | 1.000      | 0.371        | 0.114 (0.042)    | 0.980 (0.363)    | -             |    17.43 | ArroW, FreeZe, hyped, PerX, skyye   |
|           76 |      846 | 2024-04-19 | Zero Tenacity            | L   | 1.000      | -            | -                | -                | -             |   -15.72 | ArroW, awzek, FreeZe, hyped, skyye  |
|           75 |      895 | 2024-04-18 | HAVU Gaming              | L   | 1.000      | -            | -                | -                | -             |   -22.02 | ArroW, awzek, FreeZe, hyped, skyye  |
|           74 |      906 | 2024-04-18 | BLEED Esports            | L   | 1.000      | -            | -                | -                | -             |    -9.55 | ArroW, awzek, FreeZe, hyped, skyye  |
|           73 |      941 | 2024-04-17 | TeamOrangeGaming         | W   | 1.000      | -            | -                | -                | -             |     8.69 | awzek, FoG, FreeZe, hyped, w1dow    |
|           72 |     1020 | 2024-04-16 | Aurora Young Blud        | W   | 1.000      | -            | -                | -                | -             |     7.50 | ArroW, awzek, FreeZe, hyped, skyye  |
|           71 |     1042 | 2024-04-15 | Zero Tenacity            | L   | 1.000      | -            | -                | -                | -             |   -17.56 | ArroW, awzek, FreeZe, hyped, skyye  |
|           70 |     1121 | 2024-04-13 | Alliance                 | W   | 1.000      | 0.371        | -                | 0.729 (0.270)    | -             |    12.54 | ArroW, FreeZe, hyped, PerX, skyye   |
|           69 |     1306 | 2024-04-09 | Dynamo Eclot             | W   | 1.000      | 0.371        | 0.189 (0.070)    | 0.953 (0.353)    | -             |    19.53 | ArroW, FreeZe, hyped, PerX, skyye   |
|           68 |     1350 | 2024-04-08 | SINNERS Esports          | L   | 1.000      | -            | -                | -                | -             |   -11.41 | ArroW, awzek, FreeZe, hyped, skyye  |
|           67 |     1492 | 2024-04-04 | Rebels Gaming            | L   | 0.991      | -            | -                | -                | -             |    -7.10 | ArroW, awzek, FreeZe, hyped, skyye  |
|           66 |     1592 | 2024-04-02 | AMKAL ESPORTS            | L   | 0.976      | -            | -                | -                | -             |    -7.82 | ArroW, awzek, FreeZe, hyped, skyye  |
|           65 |     1730 | 2024-03-27 | BLESSED (Ukrainian team) | L   | 0.939      | -            | -                | -                | -             |   -15.87 | ArroW, awzek, FreeZe, hyped, skyye  |
|           64 |     1742 | 2024-03-27 | Guild Eagles             | W   | 0.939      | -            | -                | -                | -             |    16.82 | ArroW, awzek, FreeZe, hyped, skyye  |
|           63 |     1755 | 2024-03-27 | Heimo Esports            | W   | 0.938      | -            | -                | -                | -             |     7.21 | ArroW, awzek, FreeZe, hyped, skyye  |
|           62 |     1808 | 2024-03-26 | Ex-KRC Genk Esports      | W   | 0.932      | -            | -                | -                | -             |     7.30 | ArroW, awzek, FreeZe, hyped, skyye  |
|           61 |     1897 | 2024-03-23 | Aurora Gaming            | L   | 0.912      | -            | -                | -                | -             |    -1.10 | ArroW, awzek, FreeZe, hyped, skyye  |
|           60 |     2276 | 2024-03-14 | Metizport                | W   | 0.851      | 0.384        | 0.188 (0.062)    | 1.000 (0.327)    | -             |    21.19 | ArroW, awzek, FreeZe, hyped, skyye  |
|           59 |     2467 | 2024-03-10 | Entropiq                 | L   | 0.824      | -            | -                | -                | -             |   -17.38 | ArroW, awzek, FreeZe, hyped, skyye  |
|           58 |     2474 | 2024-03-10 | MOUZ NXT                 | L   | 0.823      | -            | -                | -                | -             |    -8.04 | ArroW, awzek, FreeZe, hyped, skyye  |
|           57 |     2545 | 2024-03-08 | Sashi Esport             | W   | 0.809      | 0.371        | 0.193 (0.058)    | 1.000 (0.300)    | -             |    15.92 | ArroW, awzek, FreeZe, hyped, skyye  |
|           56 |     2730 | 2024-03-04 | Passion UA               | L   | 0.786      | -            | -                | -                | -             |   -12.65 | ArroW, awzek, FreeZe, hyped, skyye  |
|           55 |     2770 | 2024-03-04 | Passion UA               | L   | 0.784      | -            | -                | -                | -             |   -13.52 | ArroW, awzek, FreeZe, hyped, skyye  |
|           54 |     2880 | 2024-03-02 | 500                      | L   | 0.771      | -            | -                | -                | -             |   -15.21 | ArroW, awzek, FreeZe, hyped, skyye  |
|           53 |     2924 | 2024-03-01 | Fnatic                   | L   | 0.764      | -            | -                | -                | -             |    -5.11 | ArroW, awzek, FreeZe, hyped, skyye  |
|           52 |     3000 | 2024-02-28 | BetBoom Team             | L   | 0.751      | -            | -                | -                | -             |    -1.63 | ArroW, awzek, FreeZe, hyped, skyye  |
|           51 |     3032 | 2024-02-27 | RUBY                     | L   | 0.745      | -            | -                | -                | -             |   -13.30 | ArroW, awzek, FreeZe, hyped, skyye  |
|           50 |     3058 | 2024-02-26 | Johnny Speeds            | W   | 0.739      | -            | -                | -                | -             |     7.39 | ArroW, awzek, FreeZe, hyped, skyye  |
|           49 |     3079 | 2024-02-26 | Endpoint                 | W   | 0.736      | 0.384        | -                | 0.785 (0.222)    | -             |     7.63 | ArroW, awzek, FreeZe, hyped, skyye  |
|           48 |     3101 | 2024-02-25 | Alliance                 | L   | 0.731      | -            | -                | -                | -             |   -15.12 | ArroW, awzek, FreeZe, hyped, skyye  |
|           47 |     3400 | 2024-02-19 | 1win                     | L   | 0.692      | -            | -                | -                | -             |   -17.33 | ArroW, awzek, FreeZe, PANIX, PerX   |
|           46 |     3591 | 2024-02-15 | Soda Gaming              | W   | 0.664      | -            | -                | -                | -             |     3.78 | ArroW, awzek, FreeZe, PANIX, PerX   |
|           45 |     3717 | 2024-02-12 | LODIS                    | W   | 0.645      | -            | -                | -                | -             |     2.41 | ArroW, awzek, FreeZe, PANIX, PerX   |
|           44 |     3938 | 2024-02-04 | Sangal Esports           | L   | 0.589      | -            | -                | -                | -             |   -15.63 | awzek, FreeZe, Goody, PANIX, PerX   |
|           43 |     4095 | 2024-02-01 | Sangal Esports           | L   | 0.570      | -            | -                | -                | -             |   -15.52 | awzek, FreeZe, Goody, PANIX, PerX   |
|           42 |     4179 | 2024-01-29 | TBA.ECF                  | L   | 0.553      | -            | -                | -                | -             |   -15.68 | awzek, FreeZe, Goody, PANIX, PerX   |
|           41 |     4336 | 2024-01-26 | Entropiq                 | W   | 0.530      | -            | -                | -                | -             |     3.66 | awzek, FreeZe, Goody, PANIX, PerX   |
|           40 |     4385 | 2024-01-24 | Guild Eagles             | L   | 0.518      | -            | -                | -                | -             |    -7.30 | awzek, FreeZe, Goody, PANIX, PerX   |
|           39 |     4428 | 2024-01-23 | Pera Esports             | L   | 0.512      | -            | -                | -                | -             |   -10.18 | awzek, FreeZe, Goody, PANIX, PerX   |
|           38 |     4433 | 2024-01-23 | Guild Eagles             | L   | 0.511      | -            | -                | -                | -             |    -7.94 | awzek, FreeZe, Goody, PANIX, PerX   |
|           37 |     4456 | 2024-01-22 | Viperio                  | W   | 0.506      | -            | -                | -                | -             |     1.04 | awzek, FreeZe, Goody, PANIX, PerX   |
|           36 |     4468 | 2024-01-22 | Rebels Gaming            | L   | 0.505      | -            | -                | -                | -             |    -6.24 | awzek, FreeZe, Goody, PANIX, PerX   |
|           35 |     4474 | 2024-01-22 | Team Sampi               | W   | 0.505      | -            | -                | -                | -             |     7.26 | awzek, FreeZe, Goody, PANIX, PerX   |
|           34 |     4987 | 2024-01-11 | Preasy Esport            | W   | 0.432      | -            | -                | -                | true (0.432)  |     2.68 | awzek, FreeZe, Goody, PANIX, PerX   |
|           33 |     4996 | 2024-01-11 | Lilmix                   | L   | 0.431      | -            | -                | -                | -             |   -12.04 | awzek, FreeZe, Goody, PANIX, PerX   |
|           32 |     4999 | 2024-01-11 | Preasy Esport            | W   | 0.431      | -            | -                | -                | true (0.431)  |     2.58 | awzek, FreeZe, Goody, PANIX, PerX   |
|           31 |     5479 | 2023-12-16 | BIG Academy              | W   | 0.258      | -            | -                | -                | true (0.258)  |     1.78 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           30 |     5676 | 2023-12-12 | Preasy Esport            | L   | 0.231      | -            | -                | -                | -             |    -4.67 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           29 |     5733 | 2023-12-10 | GODSENT                  | W   | 0.217      | -            | -                | -                | -             |     1.30 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           28 |     5831 | 2023-12-08 | Zero Tenacity            | W   | 0.206      | -            | -                | -                | -             |     2.35 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           27 |     5875 | 2023-12-07 | TUSTE CHOPAKI            | W   | 0.199      | -            | -                | -                | -             |     0.25 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           26 |     5892 | 2023-12-07 | Ex-Anonymo Esports       | L   | 0.198      | -            | -                | -                | -             |    -5.22 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           25 |     5927 | 2023-12-06 | The Witchers             | W   | 0.192      | -            | -                | -                | -             |     1.02 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           24 |     6020 | 2023-12-04 | Entropiq                 | W   | 0.177      | -            | -                | -                | -             |     0.96 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           23 |     6024 | 2023-12-04 | Guild Eagles             | L   | 0.176      | -            | -                | -                | -             |    -3.08 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           22 |     6122 | 2023-12-02 | Team Space               | W   | 0.164      | -            | -                | -                | -             |     0.69 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           21 |     6154 | 2023-12-01 | Aurora Gaming            | L   | 0.159      | -            | -                | -                | -             |    -0.22 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           20 |     6254 | 2023-11-29 | The Witchers             | L   | 0.145      | -            | -                | -                | -             |    -3.84 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           19 |     6269 | 2023-11-29 | Lajtbitexe               | W   | 0.145      | -            | -                | -                | -             |     0.23 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           18 |     6279 | 2023-11-29 | Sprout                   | L   | 0.144      | -            | -                | -                | -             |    -4.07 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           17 |     6301 | 2023-11-28 | EHawks                   | W   | 0.139      | -            | -                | -                | -             |     0.21 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           16 |     6329 | 2023-11-28 | Sangal Esports           | W   | 0.137      | -            | -                | -                | -             |     0.40 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           15 |     6360 | 2023-11-27 | ARROW (German team)      | W   | 0.132      | -            | -                | -                | -             |     0.44 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           14 |     6400 | 2023-11-26 | ARROW (German team)      | W   | 0.124      | -            | -                | -                | -             |     0.41 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           13 |     6427 | 2023-11-25 | BIG Academy              | L   | 0.118      | -            | -                | -                | -             |    -3.03 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           12 |     6503 | 2023-11-23 | Verdant                  | W   | 0.106      | -            | -                | -                | -             |     1.28 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           11 |     6517 | 2023-11-23 | BAKS Esports             | L   | 0.105      | -            | -                | -                | -             |    -3.03 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|           10 |     6573 | 2023-11-22 | 9Pandas                  | L   | 0.097      | -            | -                | -                | -             |    -1.29 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            9 |     6623 | 2023-11-20 | BIG Academy              | L   | 0.086      | -            | -                | -                | -             |    -2.22 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            8 |     6789 | 2023-11-17 | Into The Breach          | L   | 0.063      | -            | -                | -                | -             |    -1.65 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            7 |     6804 | 2023-11-16 | Guild Eagles             | W   | 0.059      | -            | -                | -                | -             |     0.77 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            6 |     6839 | 2023-11-16 | IKLA                     | W   | 0.057      | -            | -                | -                | -             |     0.18 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            5 |     6897 | 2023-11-15 | FORZE Esports            | L   | 0.050      | -            | -                | -                | -             |    -1.35 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            4 |     6934 | 2023-11-14 | Aurora Gaming            | W   | 0.044      | 0.589        | 1.000 (0.026)    | -                | -             |     1.32 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            3 |     6982 | 2023-11-13 | SINNERS Esports          | L   | 0.037      | -            | -                | -                | -             |    -0.75 | awzek, FreeZe, PANIX, PerX, Spiidi  |
|            2 |     7163 | 2023-11-08 | HOTU                     | W   | 0.006      | -            | -                | -                | -             |     0.03 | awzek, FreeZe, PerX, slaxz-, Spiidi |
|            1 |     7190 | 2023-11-08 | Insilio                  | W   | 0.005      | -            | -                | -                | -             |     0.04 | awzek, FreeZe, PerX, slaxz-, Spiidi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,422.81)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-03 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-25 |      1.000 | $1,000.00      | $1,000.00       |
| 2023-12-16 |      0.258 | $8,180.59      | $2,108.40       |
| 2023-12-13 |      0.238 | $1,250.00      | $297.51         |
| 2023-12-12 |      0.231 | $5,000.00      | $1,155.32       |
| 2023-11-18 |      0.072 | $5,000.00      | $361.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
