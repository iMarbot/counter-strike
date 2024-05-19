### Roster Details<br />
Team Name: Lilmix<br />
Roster: bobeksde, dex, poiii, quix, zyyx<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [220](../standings_global.md)<br />
Regional Rank: [145]( ../standings_europe.md)<br />
Final Rank Value:  695.8<br />
<br />
Final Rank Value (695.8) = Starting Rank Value (609.5) + Head To Head Adjustments (86.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.138[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.106<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 609.5
- 400 + ( ( 0.106 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 609.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      271 | 2024-04-29 | DMS                         | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.504 (0.187)    | false (0.000) |    19.85 | bobeksde, dex, poiii, quix, zyyx |
|           44 |      520 | 2024-04-24 | Team PeeP                   | L   | 1.000      | -            | -                | -                | -             |   -25.87 | bobeksde, dex, poiii, quix, zyyx |
|           43 |      531 | 2024-04-24 | RoundsGG                    | L   | 1.000      | -            | -                | -                | -             |   -17.10 | bobeksde, dex, poiii, quix, zyyx |
|           42 |     1024 | 2024-04-16 | UNiTY esports (Slovak team) | L   | 1.000      | -            | -                | -                | -             |    -9.00 | Brillo, dex, poiii, quix, zyyx   |
|           41 |     1060 | 2024-04-15 | Illuminar Gaming            | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.433 (0.144)    | false (0.000) |    20.61 | Brillo, dex, poiii, quix, zyyx   |
|           40 |     1063 | 2024-04-14 | LOADING (French team)       | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | false (0.000) |     4.87 | bobeksde, dex, poiii, quix, zyyx |
|           39 |     1124 | 2024-04-13 | Astralis Talent             | W   | 1.000      | 0.333        | 0.030 (0.010)    | 0.613 (0.204)    | false (0.000) |    22.28 | Brillo, dex, poiii, quix, zyyx   |
|           38 |     1155 | 2024-04-12 | Verdant                     | L   | 1.000      | -            | -                | -                | -             |    -6.40 | Brillo, dex, eraa, poiii, quix   |
|           37 |     1379 | 2024-04-07 | NOM Esports                 | W   | 1.000      | 0.333        | -                | 0.374 (0.125)    | false (0.000) |    16.50 | Brillo, dex, poiii, quix, zyyx   |
|           36 |     1389 | 2024-04-06 | Alliance                    | L   | 1.000      | -            | -                | -                | -             |    -7.69 | Brillo, dex, poiii, quix, zyyx   |
|           35 |     1488 | 2024-04-04 | Lemondogs                   | W   | 0.991      | -            | -                | -                | false (0.000) |    11.13 | Brillo, dex, poiii, quix, zyyx   |
|           34 |     1520 | 2024-04-03 | Podwars                     | W   | 0.986      | -            | -                | -                | false (0.000) |     8.96 | Brillo, dex, poiii, quix, zyyx   |
|           33 |     1524 | 2024-04-03 | Johnny Speeds               | W   | 0.986      | 0.143        | 0.044 (0.006)    | 0.718 (0.101)    | false (0.000) |    24.23 | Brillo, dex, poiii, quix, zyyx   |
|           32 |     1562 | 2024-04-03 | Turów Zgorzelec Esport      | W   | 0.982      | 0.333        | 0.019 (0.006)    | 0.640 (0.210)    | false (0.000) |    22.71 | Brillo, dex, poiii, quix, zyyx   |
|           31 |     1659 | 2024-03-29 | Young Gods                  | W   | 0.952      | -            | -                | -                | false (0.000) |     8.95 | Brillo, dex, poiii, quix, zyyx   |
|           30 |     1671 | 2024-03-29 | UNiTY esports (Slovak team) | L   | 0.950      | -            | -                | -                | -             |    -5.33 | Brillo, dex, poiii, quix, zyyx   |
|           29 |     1849 | 2024-03-25 | Turów Zgorzelec Esport      | L   | 0.923      | -            | -                | -                | -             |    -7.22 | Brillo, dex, poiii, quix, zyyx   |
|           28 |     1932 | 2024-03-22 | Kappa Bar                   | L   | 0.906      | -            | -                | -                | -             |   -18.03 | Brillo, dex, poiii, quix, zyyx   |
|           27 |     1993 | 2024-03-21 | Entropiq                    | W   | 0.897      | 0.333        | 0.001 (0.000)    | 0.436 (0.130)    | -             |    20.77 | Brillo, dex, poiii, quix, zyyx   |
|           26 |     2250 | 2024-03-14 | Curlews                     | W   | 0.853      | -            | -                | -                | -             |     6.29 | Brillo, dex, poiii, quix, zyyx   |
|           25 |     2512 | 2024-03-09 | Lemondogs                   | L   | 0.817      | -            | -                | -                | -             |   -13.66 | Brillo, dex, poiii, quix, zyyx   |
|           24 |     2747 | 2024-03-04 | 9INE                        | L   | 0.786      | -            | -                | -                | -             |   -11.62 | Brillo, dex, poiii, quix, zyyx   |
|           23 |     2786 | 2024-03-03 | Zero Tenacity               | L   | 0.779      | -            | -                | -                | -             |    -3.79 | Brillo, dex, poiii, quix, zyyx   |
|           22 |     2794 | 2024-03-03 | RoundsGG                    | L   | 0.778      | -            | -                | -                | -             |   -10.01 | Brillo, dex, poiii, quix, zyyx   |
|           21 |     2825 | 2024-03-02 | The Chosen Few              | L   | 0.773      | -            | -                | -                | -             |    -6.83 | Brillo, dex, poiii, quix, zyyx   |
|           20 |     2835 | 2024-03-02 | IMMAPROBLEM                 | W   | 0.773      | -            | -                | -                | -             |     8.85 | Brillo, dex, poiii, quix, zyyx   |
|           19 |     2940 | 2024-02-29 | Lemondogs                   | L   | 0.759      | -            | -                | -                | -             |   -14.41 | Brillo, dex, poiii, quix, zyyx   |
|           18 |     2946 | 2024-02-29 | V1dar Gaming                | W   | 0.758      | 0.371        | -                | 0.345 (0.097)    | -             |    13.06 | Brillo, dex, poiii, quix, zyyx   |
|           17 |     2989 | 2024-02-28 | BLESSED (Ukrainian team)    | L   | 0.752      | -            | -                | -                | -             |    -6.38 | Brillo, dex, poiii, quix, zyyx   |
|           16 |     3017 | 2024-02-27 | Golden Sword                | W   | 0.746      | -            | -                | -                | -             |     4.17 | Brillo, dex, poiii, quix, zyyx   |
|           15 |     3043 | 2024-02-27 | Johnny Speeds               | L   | 0.744      | -            | -                | -                | -             |    -6.02 | Brillo, dex, poiii, quix, zyyx   |
|           14 |     3224 | 2024-02-23 | Astralis Talent             | L   | 0.716      | -            | -                | -                | -             |    -3.84 | Brillo, dex, poiii, quix, zyyx   |
|           13 |     3249 | 2024-02-22 | GenOne                      | W   | 0.712      | 0.371        | -                | 0.323 (0.085)    | -             |     9.41 | Brillo, dex, poiii, quix, zyyx   |
|           12 |     3379 | 2024-02-20 | Dynamo Eclot                | L   | 0.696      | -            | -                | -                | -             |    -1.39 | Brillo, dex, poiii, quix, zyyx   |
|           11 |     3607 | 2024-02-15 | K10                         | W   | 0.663      | 0.333        | 0.015 (0.003)    | 0.418 (0.092)    | -             |    15.85 | Brillo, dex, poiii, quix, zyyx   |
|           10 |     3709 | 2024-02-12 | Ex-KRC Genk Esports         | W   | 0.646      | 0.371        | 0.008 (0.002)    | -                | -             |    14.07 | Brillo, dex, poiii, quix, zyyx   |
|            9 |     3738 | 2024-02-12 | Permitta Esports            | L   | 0.643      | -            | -                | -                | -             |    -2.44 | Brillo, dex, poiii, quix, zyyx   |
|            8 |     3742 | 2024-02-11 | INGLORIOUS                  | L   | 0.639      | -            | -                | -                | -             |    -5.17 | Brillo, dex, poiii, quix, zyyx   |
|            7 |     3748 | 2024-02-11 | 9INE                        | W   | 0.639      | -            | -                | -                | -             |     9.97 | Brillo, dex, poiii, quix, zyyx   |
|            6 |     3760 | 2024-02-11 | Dynamo Eclot                | L   | 0.636      | -            | -                | -                | -             |    -0.97 | Brillo, dex, poiii, quix, zyyx   |
|            5 |     3773 | 2024-02-10 | NOM Esports                 | W   | 0.631      | -            | -                | -                | -             |    10.67 | Brillo, dex, poiii, quix, zyyx   |
|            4 |     3801 | 2024-02-09 | Natus Vincere Junior        | L   | 0.624      | -            | -                | -                | -             |    -4.32 | Brillo, dex, poiii, quix, zyyx   |
|            3 |     3957 | 2024-02-03 | Gaimin Gladiators           | L   | 0.585      | -            | -                | -                | -             |    -0.24 | Brillo, dex, poiii, quix, zyyx   |
|            2 |     3973 | 2024-02-03 | XI Esport                   | W   | 0.585      | 0.143        | 0.002 (0.000)    | -                | -             |    11.63 | Brillo, dex, poiii, quix, zyyx   |
|            1 |     4028 | 2024-02-02 | Sashi Esport                | L   | 0.578      | -            | -                | -                | -             |   -10.78 | Brillo, dex, poiii, quix, zyyx   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
