### Roster Details<br />
Team Name: Insilio<br />
Roster: faydett, FpSSS, Pipw, Polt, sugaR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [53](../standings_global.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
Final Rank Value:  1002.1<br />
<br />
Final Rank Value (1002.1) = Starting Rank Value (925.1) + Head To Head Adjustments (77.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.438[<sup>2</sup>](#table1)
- Opponent Network: 0.250[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.265<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 925.1
- 400 + ( ( 0.265 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 925.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           77 |      108 | 2024-05-03 | Permitta Esports         | W   | 1.000      | 0.435        | 0.063 (0.027)    | 1.000 (0.435)    | false (0.000) |    11.00 | faydett, FpSSS, Pipw, Polt, sugaR |
|           76 |      125 | 2024-05-03 | BetBoom Team             | L   | 1.000      | -            | -                | -                | -             |    -3.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           75 |      197 | 2024-05-01 | OG                       | W   | 1.000      | 0.435        | 0.594 (0.258)    | 0.390 (0.170)    | false (0.000) |    27.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           74 |      212 | 2024-05-01 | Nexus Gaming             | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.772 (0.335)    | false (0.000) |    12.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           73 |      286 | 2024-04-29 | HAVU Gaming              | L   | 1.000      | -            | -                | -                | -             |   -24.68 | faydett, FpSSS, Pipw, Polt, sugaR |
|           72 |      361 | 2024-04-27 | Guild Eagles             | W   | 1.000      | 0.435        | 0.037 (0.016)    | 0.586 (0.255)    | false (0.000) |    16.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|           71 |      372 | 2024-04-27 | Permitta Esports         | W   | 1.000      | 0.143        | 0.063 (0.009)    | 1.000 (0.143)    | false (0.000) |    13.94 | faydett, FpSSS, Pipw, Polt, sugaR |
|           70 |      430 | 2024-04-26 | ARCRED                   | L   | 1.000      | -            | -                | -                | -             |   -19.13 | faydett, FpSSS, Pipw, Polt, sugaR |
|           69 |      439 | 2024-04-26 | ENTERPRISE esports       | W   | 1.000      | -            | -                | -                | false (0.000) |    12.99 | faydett, FpSSS, Pipw, Polt, sugaR |
|           68 |      495 | 2024-04-25 | MOUZ NXT                 | W   | 1.000      | 0.435        | 0.215 (0.094)    | 1.000 (0.435)    | false (0.000) |    19.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           67 |      568 | 2024-04-23 | EYEBALLERS               | W   | 1.000      | 0.435        | 0.051 (0.022)    | 0.533 (0.232)    | false (0.000) |    14.96 | faydett, FpSSS, Pipw, Polt, sugaR |
|           66 |      664 | 2024-04-21 | FORZE Youngsters         | W   | 1.000      | -            | -                | -                | false (0.000) |     1.58 | faydett, FpSSS, Pipw, Polt, sugaR |
|           65 |      668 | 2024-04-21 | Permitta Esports         | L   | 1.000      | -            | -                | -                | -             |   -15.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           64 |      728 | 2024-04-20 | Passion UA               | L   | 1.000      | -            | -                | -                | -             |   -16.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           63 |      830 | 2024-04-19 | GamerLegion Academy      | L   | 1.000      | -            | -                | -                | -             |   -19.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           62 |      924 | 2024-04-17 | Apeks                    | L   | 1.000      | -            | -                | -                | -             |    -4.36 | faydett, FpSSS, Pipw, Polt, sugaR |
|           61 |     1071 | 2024-04-14 | LEON Esports             | W   | 1.000      | -            | -                | -                | false (0.000) |     5.80 | faydett, FpSSS, Pipw, Polt, sugaR |
|           60 |     1369 | 2024-04-07 | RUBY                     | L   | 1.000      | -            | -                | -                | -             |   -18.06 | faydett, FpSSS, Pipw, Polt, sugaR |
|           59 |     1526 | 2024-04-03 | AMKAL ESPORTS            | L   | 0.985      | -            | -                | -                | -             |    -9.18 | faydett, FpSSS, Pipw, Polt, sugaR |
|           58 |     1571 | 2024-04-02 | Guild Eagles             | W   | 0.979      | -            | -                | -                | -             |    16.02 | faydett, FpSSS, Pipw, Polt, sugaR |
|           57 |     1585 | 2024-04-02 | PARIVISION               | W   | 0.977      | -            | -                | -                | -             |    12.39 | faydett, FpSSS, Pipw, Polt, sugaR |
|           56 |     1804 | 2024-03-26 | 500                      | L   | 0.932      | -            | -                | -                | -             |   -18.09 | faydett, FpSSS, Pipw, Polt, sugaR |
|           55 |     2098 | 2024-03-18 | Sashi Esport             | L   | 0.877      | -            | -                | -                | -             |   -13.17 | faydett, FpSSS, Pipw, Polt, sugaR |
|           54 |     2215 | 2024-03-15 | CYBERSHOKE Esports       | W   | 0.859      | -            | -                | -                | -             |     5.55 | faydett, FpSSS, Pipw, Polt, sugaR |
|           53 |     2323 | 2024-03-13 | INGLORIOUS               | W   | 0.845      | -            | -                | -                | -             |     7.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           52 |     2423 | 2024-03-11 | 1win                     | W   | 0.831      | -            | -                | -                | -             |     6.38 | faydett, FpSSS, Pipw, Polt, sugaR |
|           51 |     2501 | 2024-03-09 | K10                      | W   | 0.818      | -            | -                | -                | -             |     7.62 | faydett, FpSSS, Pipw, Polt, sugaR |
|           50 |     2565 | 2024-03-07 | Sashi Esport             | L   | 0.806      | -            | -                | -                | -             |   -11.26 | faydett, FpSSS, Pipw, Polt, sugaR |
|           49 |     2619 | 2024-03-06 | The Chosen Few           | W   | 0.799      | 0.371        | -                | 0.457 (0.135)    | -             |     8.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           48 |     2688 | 2024-03-05 | Johnny Speeds            | L   | 0.792      | -            | -                | -                | -             |   -16.18 | faydett, FpSSS, Pipw, Polt, sugaR |
|           47 |     2694 | 2024-03-05 | Betera Esports           | W   | 0.792      | -            | -                | -                | -             |     8.47 | faydett, FpSSS, Pipw, Polt, sugaR |
|           46 |     2722 | 2024-03-04 | Pera Esports             | W   | 0.786      | -            | -                | -                | -             |    10.15 | faydett, FpSSS, Pipw, Polt, sugaR |
|           45 |     3216 | 2024-02-23 | FORZE Youngsters         | W   | 0.718      | -            | -                | -                | -             |     4.33 | faydett, FpSSS, Pipw, Polt, sugaR |
|           44 |     3254 | 2024-02-22 | GenOne                   | W   | 0.711      | -            | -                | -                | -             |     2.42 | faydett, FpSSS, Pipw, Polt, sugaR |
|           43 |     3261 | 2024-02-22 | Rhyno Esports            | W   | 0.711      | 0.371        | 0.047 (0.012)    | -                | -             |     9.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|           42 |     3311 | 2024-02-21 | DMS                      | L   | 0.704      | -            | -                | -                | -             |   -19.05 | faydett, FpSSS, Pipw, Polt, sugaR |
|           41 |     3323 | 2024-02-21 | Nemiga Gaming            | L   | 0.704      | -            | -                | -                | -             |    -2.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           40 |     3619 | 2024-02-14 | EsmagaB                  | W   | 0.659      | 0.371        | -                | 0.559 (0.137)    | -             |     6.74 | faydett, FpSSS, Pipw, Polt, sugaR |
|           39 |     3678 | 2024-02-13 | Passion UA               | L   | 0.651      | -            | -                | -                | -             |   -11.30 | faydett, FpSSS, Pipw, Polt, sugaR |
|           38 |     3686 | 2024-02-13 | ILIN                     | W   | 0.651      | -            | -                | -                | -             |     1.87 | faydett, FpSSS, Pipw, Polt, sugaR |
|           37 |     3798 | 2024-02-09 | Sashi Esport             | L   | 0.624      | -            | -                | -                | -             |    -8.57 | faydett, FpSSS, Pipw, Polt, sugaR |
|           36 |     3812 | 2024-02-08 | Guild Eagles             | W   | 0.619      | -            | -                | -                | -             |    11.81 | faydett, FpSSS, Pipw, Polt, sugaR |
|           35 |     3828 | 2024-02-08 | AMKAL ESPORTS            | L   | 0.618      | -            | -                | -                | -             |    -3.64 | faydett, FpSSS, Pipw, Polt, sugaR |
|           34 |     3845 | 2024-02-07 | Sashi Esport             | W   | 0.612      | 0.371        | 0.193 (0.044)    | 1.000 (0.227)    | -             |    11.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           33 |     3901 | 2024-02-05 | Grindas                  | W   | 0.598      | -            | -                | -                | -             |     3.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           32 |     3905 | 2024-02-05 | Gaimin Gladiators        | L   | 0.598      | -            | -                | -                | -             |    -1.82 | faydett, FpSSS, Pipw, Polt, sugaR |
|           31 |     4132 | 2024-01-30 | Sashi Esport             | L   | 0.559      | -            | -                | -                | -             |    -6.69 | faydett, FpSSS, Pipw, Polt, sugaR |
|           30 |     4139 | 2024-01-30 | Fnatic                   | W   | 0.559      | 0.143        | 0.334 (0.027)    | -                | -             |    14.45 | faydett, FpSSS, Pipw, Polt, sugaR |
|           29 |     4146 | 2024-01-30 | EXO Clan                 | W   | 0.558      | -            | -                | -                | -             |     7.16 | faydett, FpSSS, Pipw, Polt, sugaR |
|           28 |     4165 | 2024-01-29 | Team Sampi               | W   | 0.553      | -            | -                | -                | -             |    10.44 | faydett, FpSSS, Pipw, Polt, sugaR |
|           27 |     4167 | 2024-01-29 | TBA.ECF                  | W   | 0.553      | -            | -                | -                | -             |     2.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|           26 |     4676 | 2024-01-18 | AMKAL ESPORTS            | L   | 0.477      | -            | -                | -                | -             |    -2.59 | faydett, FpSSS, Pipw, Polt, sugaR |
|           25 |     4693 | 2024-01-17 | EsmagaB                  | W   | 0.473      | -            | -                | -                | -             |     6.27 | faydett, FpSSS, Pipw, Polt, sugaR |
|           24 |     4699 | 2024-01-17 | PARIVISION               | W   | 0.473      | -            | -                | -                | -             |     6.41 | faydett, FpSSS, Pipw, Polt, sugaR |
|           23 |     4708 | 2024-01-17 | Endpoint                 | W   | 0.473      | -            | -                | -                | -             |     5.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           22 |     4800 | 2024-01-16 | Rebels Gaming            | L   | 0.465      | -            | -                | -                | -             |    -3.01 | faydett, FpSSS, Pipw, Polt, sugaR |
|           21 |     4887 | 2024-01-13 | Permitta Esports         | L   | 0.445      | -            | -                | -                | -             |    -5.79 | faydett, FpSSS, Pipw, Polt, sugaR |
|           20 |     4888 | 2024-01-13 | B8                       | W   | 0.444      | -            | -                | -                | -             |     2.49 | faydett, FpSSS, Pipw, Polt, sugaR |
|           19 |     4920 | 2024-01-12 | EYEBALLERS               | W   | 0.440      | -            | -                | -                | -             |     7.32 | faydett, FpSSS, Pipw, Polt, sugaR |
|           18 |     4940 | 2024-01-12 | Kappa Bar                | W   | 0.439      | -            | -                | -                | -             |     2.71 | faydett, FpSSS, Pipw, Polt, sugaR |
|           17 |     5400 | 2023-12-17 | ARCRED                   | W   | 0.263      | -            | -                | -                | -             |     3.28 | faydett, FpSSS, Pipw, Polt, sugaR |
|           16 |     5468 | 2023-12-16 | Sangal Esports           | L   | 0.258      | -            | -                | -                | -             |    -6.53 | faydett, FpSSS, Pipw, Polt, sugaR |
|           15 |     5486 | 2023-12-16 | FORZE Youngsters         | W   | 0.257      | -            | -                | -                | -             |     1.75 | faydett, FpSSS, Pipw, Polt, sugaR |
|           14 |     5503 | 2023-12-16 | BebraFPL1                | W   | 0.256      | -            | -                | -                | -             |     0.77 | faydett, FpSSS, Pipw, Polt, sugaR |
|           13 |     6168 | 2023-12-01 | 9Pandas                  | W   | 0.157      | -            | -                | -                | -             |     3.83 | faydett, FpSSS, Pipw, Polt, sugaR |
|           12 |     6265 | 2023-11-29 | Ex-sYnck                 | W   | 0.145      | -            | -                | -                | -             |     0.56 | faydett, FpSSS, Pipw, Polt, sugaR |
|           11 |     6277 | 2023-11-29 | Gaimin Gladiators        | L   | 0.144      | -            | -                | -                | -             |    -0.22 | faydett, FpSSS, Pipw, Polt, sugaR |
|           10 |     6326 | 2023-11-28 | Entropiq                 | L   | 0.138      | -            | -                | -                | -             |    -2.91 | faydett, FpSSS, Pipw, Polt, sugaR |
|            9 |     6426 | 2023-11-25 | ARCRED                   | L   | 0.118      | -            | -                | -                | -             |    -2.34 | faydett, FpSSS, Pipw, Polt, sugaR |
|            8 |     6468 | 2023-11-24 | BLESSED (Ukrainian team) | W   | 0.112      | -            | -                | -                | -             |     1.35 | faydett, FpSSS, Pipw, Polt, sugaR |
|            7 |     6644 | 2023-11-20 | GenOne                   | L   | 0.084      | -            | -                | -                | -             |    -2.24 | faydett, FpSSS, Pipw, Polt, sugaR |
|            6 |     6713 | 2023-11-18 | Grindas                  | L   | 0.072      | -            | -                | -                | -             |    -1.76 | faydett, FpSSS, Pipw, Polt, sugaR |
|            5 |     7118 | 2023-11-09 | GUN5 Esports             | L   | 0.013      | -            | -                | -                | -             |    -0.34 | FpSSS, k4sl, Pipw, Polt, Xant3r   |
|            4 |     7122 | 2023-11-09 | Verdant                  | L   | 0.013      | -            | -                | -                | -             |    -0.16 | FpSSS, k4sl, Pipw, Polt, Xant3r   |
|            3 |     7133 | 2023-11-09 | Nemiga Gaming            | W   | 0.012      | -            | -                | -                | -             |     0.33 | FpSSS, k4sl, Pipw, Polt, Xant3r   |
|            2 |     7190 | 2023-11-08 | ALTERNATE aTTaX          | L   | 0.005      | -            | -                | -                | -             |    -0.04 | FpSSS, k4sl, Pipw, Polt, Xant3r   |
|            1 |     7199 | 2023-11-08 | V1dar Gaming             | W   | 0.004      | -            | -                | -                | -             |     0.02 | FpSSS, k4sl, Pipw, Polt, Xant3r   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,155.84)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-03-25 |      0.925 | $1,250.00      | $1,155.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
