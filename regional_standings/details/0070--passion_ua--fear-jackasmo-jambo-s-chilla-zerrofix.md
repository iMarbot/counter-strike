### Roster Details<br />
Team Name: Passion UA<br />
Roster: fear, jackasmo, jambo, s-chilla, zeRRoFIX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [70](../standings_global.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
Final Rank Value:  924.5<br />
<br />
Final Rank Value (924.5) = Starting Rank Value (1009.6) + Head To Head Adjustments (-85.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.515[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.307<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1009.6
- 400 + ( ( 0.307 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1009.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          100 |      148 | 2024-05-02 | Nemiga Gaming               | L   | 1.000      | -            | -                | -                | -             |    -4.35 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           99 |      205 | 2024-05-01 | PARIVISION                  | W   | 1.000      | -            | -                | -                | false (0.000) |    15.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           98 |      256 | 2024-04-30 | 9Pandas                     | W   | 1.000      | 0.500        | 0.085 (0.043)    | 0.661 (0.330)    | false (0.000) |    21.53 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           97 |      272 | 2024-04-29 | 1win                        | L   | 1.000      | -            | -                | -                | -             |   -19.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           96 |      312 | 2024-04-28 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -             |   -15.74 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           95 |      431 | 2024-04-26 | 9Pandas                     | W   | 1.000      | 0.500        | 0.085 (0.043)    | 0.661 (0.330)    | false (0.000) |    20.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           94 |      472 | 2024-04-25 | ThunderFlash                | L   | 1.000      | -            | -                | -                | -             |   -19.75 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           93 |      491 | 2024-04-25 | Sashi Esport                | L   | 1.000      | -            | -                | -                | -             |    -4.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           92 |      542 | 2024-04-24 | Permitta Esports            | L   | 1.000      | -            | -                | -                | -             |   -15.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           91 |      597 | 2024-04-22 | B8                          | L   | 1.000      | -            | -                | -                | -             |   -13.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           90 |      699 | 2024-04-20 | Young Ninjas                | W   | 1.000      | 0.500        | 0.074 (0.037)    | -                | false (0.000) |    16.12 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           89 |      728 | 2024-04-20 | Insilio                     | W   | 1.000      | 0.371        | -                | 0.875 (0.325)    | false (0.000) |    16.05 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           88 |      778 | 2024-04-20 | Permitta Esports            | L   | 1.000      | -            | -                | -                | -             |   -15.51 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           87 |      831 | 2024-04-19 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -             |   -17.43 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           86 |      894 | 2024-04-18 | Permitta Esports            | W   | 1.000      | 0.500        | 0.063 (0.031)    | 1.000 (0.500)    | false (0.000) |    15.21 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           85 |      950 | 2024-04-17 | Sashi Esport                | W   | 1.000      | 0.371        | 0.193 (0.071)    | 1.000 (0.371)    | false (0.000) |    20.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           84 |     1002 | 2024-04-16 | 500                         | L   | 1.000      | -            | -                | -                | -             |   -14.71 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           83 |     1078 | 2024-04-14 | SINNERS Esports             | L   | 1.000      | -            | -                | -                | -             |   -11.27 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           82 |     1141 | 2024-04-12 | Team PeeP                   | W   | 1.000      | -            | -                | -                | false (0.000) |     1.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           81 |     1184 | 2024-04-11 | 3DMAX                       | W   | 1.000      | -            | -                | -                | false (0.000) |    16.22 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           80 |     1500 | 2024-04-04 | HAVU Gaming                 | W   | 0.991      | -            | -                | -                | false (0.000) |    10.98 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           79 |     1578 | 2024-04-02 | BLEED Esports               | L   | 0.978      | -            | -                | -                | -             |    -9.66 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           78 |     1624 | 2024-03-31 | BLESSED (Ukrainian team)    | L   | 0.964      | -            | -                | -                | -             |   -14.62 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           77 |     1669 | 2024-03-29 | Natus Vincere Junior        | L   | 0.950      | -            | -                | -                | -             |   -16.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           76 |     1704 | 2024-03-28 | GamerLegion Academy         | L   | 0.944      | -            | -                | -                | -             |   -18.80 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           75 |     1756 | 2024-03-27 | Rebels Gaming               | L   | 0.938      | -            | -                | -                | -             |    -8.94 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           74 |     1818 | 2024-03-26 | Dynamo Eclot                | W   | 0.932      | 0.143        | 0.189 (0.025)    | -                | -             |    18.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           73 |     1835 | 2024-03-26 | Natus Vincere Junior        | W   | 0.929      | -            | -                | -                | -             |    10.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           72 |     1864 | 2024-03-24 | ROSOMAHA                    | W   | 0.917      | -            | -                | -                | -             |     3.11 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           71 |     1919 | 2024-03-23 | Astralis Talent             | W   | 0.910      | -            | -                | -                | -             |    12.04 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           70 |     2152 | 2024-03-17 | K10                         | W   | 0.870      | -            | -                | -                | -             |     9.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           69 |     2160 | 2024-03-17 | Team Sampi                  | L   | 0.869      | -            | -                | -                | -             |   -11.14 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           68 |     2180 | 2024-03-16 | Grannys Knockers            | L   | 0.864      | -            | -                | -                | -             |   -15.84 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           67 |     2281 | 2024-03-14 | Team Sampi                  | W   | 0.850      | 0.371        | 0.108 (0.034)    | 0.709 (0.223)    | -             |    15.47 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           66 |     2287 | 2024-03-14 | NOM Esports                 | W   | 0.849      | -            | -                | -                | -             |     1.19 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           65 |     2386 | 2024-03-12 | Alliance                    | W   | 0.837      | 0.371        | -                | 0.729 (0.226)    | -             |    11.70 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           64 |     2434 | 2024-03-11 | MOUZ NXT                    | L   | 0.830      | -            | -                | -                | -             |    -8.41 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           63 |     2469 | 2024-03-10 | MOUZ NXT                    | W   | 0.824      | 0.303        | 0.215 (0.054)    | 1.000 (0.250)    | -             |    17.87 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           62 |     2499 | 2024-03-09 | The Chosen Few              | L   | 0.818      | -            | -                | -                | -             |   -16.13 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           61 |     2531 | 2024-03-08 | Team Spirit Academy         | L   | 0.811      | -            | -                | -                | -             |   -15.81 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           60 |     2542 | 2024-03-08 | Entropiq                    | W   | 0.810      | -            | -                | -                | -             |     7.73 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           59 |     2575 | 2024-03-07 | GODSENT                     | W   | 0.805      | -            | -                | -                | -             |     7.61 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           58 |     2582 | 2024-03-07 | Astralis Talent             | W   | 0.804      | -            | -                | -                | -             |    11.38 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           57 |     2635 | 2024-03-06 | Permitta Esports            | L   | 0.797      | -            | -                | -                | -             |   -10.55 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           56 |     2652 | 2024-03-06 | K10                         | W   | 0.797      | -            | -                | -                | -             |     9.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           55 |     2684 | 2024-03-05 | B8                          | L   | 0.792      | -            | -                | -                | -             |   -10.86 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           54 |     2707 | 2024-03-05 | Natus Vincere Junior        | W   | 0.791      | -            | -                | -                | -             |     9.44 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           53 |     2720 | 2024-03-04 | 9INE                        | W   | 0.786      | -            | -                | -                | -             |     4.32 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           52 |     2730 | 2024-03-04 | ALTERNATE aTTaX             | W   | 0.786      | -            | -                | -                | -             |    12.65 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           51 |     2770 | 2024-03-04 | ALTERNATE aTTaX             | W   | 0.784      | 0.371        | 0.110 (0.032)    | 0.723 (0.210)    | -             |    13.52 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           50 |     2887 | 2024-03-02 | Sashi Esport                | W   | 0.771      | -            | -                | -                | -             |     8.69 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           49 |     2921 | 2024-03-01 | Nexus Gaming                | L   | 0.764      | -            | -                | -                | -             |   -11.77 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           48 |     2953 | 2024-02-29 | L&G                         | W   | 0.758      | -            | -                | -                | -             |     2.54 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           47 |     3006 | 2024-02-28 | NOM Esports                 | L   | 0.749      | -            | -                | -                | -             |   -18.89 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           46 |     3186 | 2024-02-24 | Sashi Esport                | W   | 0.723      | -            | -                | -                | -             |     7.45 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           45 |     3259 | 2024-02-22 | Entropiq                    | W   | 0.711      | -            | -                | -                | -             |     8.42 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           44 |     3347 | 2024-02-20 | ARCRED                      | L   | 0.698      | -            | -                | -                | -             |   -14.06 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           43 |     3447 | 2024-02-18 | MOUZ NXT                    | L   | 0.685      | -            | -                | -                | -             |    -6.01 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           42 |     3467 | 2024-02-18 | Viperio                     | L   | 0.683      | -            | -                | -                | -             |   -17.46 | fear, jackasmo, jambo, s-chilla, zeRRoFIX      |
|           41 |     3552 | 2024-02-16 | K10                         | W   | 0.669      | -            | -                | -                | -             |     7.70 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           40 |     3590 | 2024-02-15 | Natus Vincere Junior        | L   | 0.664      | -            | -                | -                | -             |   -13.71 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           39 |     3678 | 2024-02-13 | Insilio                     | W   | 0.651      | 0.371        | -                | 0.875 (0.212)    | -             |    11.30 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           38 |     3715 | 2024-02-12 | Lemondogs                   | W   | 0.645      | -            | -                | -                | -             |     2.41 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           37 |     3746 | 2024-02-11 | V1dar Gaming                | W   | 0.639      | -            | -                | -                | -             |     3.05 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           36 |     3759 | 2024-02-11 | Sashi Esport                | L   | 0.636      | -            | -                | -                | -             |   -13.52 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           35 |     3803 | 2024-02-09 | BIG Academy                 | L   | 0.623      | -            | -                | -                | -             |   -12.84 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           34 |     3830 | 2024-02-08 | Monte Gen                   | L   | 0.617      | -            | -                | -                | -             |   -12.69 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           33 |     3920 | 2024-02-04 | DASH                        | L   | 0.592      | -            | -                | -                | -             |   -15.09 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           32 |     3996 | 2024-02-03 | BIG Academy                 | W   | 0.584      | -            | -                | -                | -             |     5.36 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           31 |     4100 | 2024-01-31 | Kappa Bar                   | W   | 0.566      | -            | -                | -                | -             |     2.68 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           30 |     4173 | 2024-01-29 | 3DMAX                       | L   | 0.553      | -            | -                | -                | -             |    -9.40 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           29 |     4198 | 2024-01-29 | Alliance                    | W   | 0.551      | -            | -                | -                | -             |     5.82 | jackasmo, jambo, s-chilla, zeRRoFIX, Zinchenko |
|           28 |     4230 | 2024-01-28 | Nexus Gaming                | W   | 0.543      | -            | -                | -                | -             |     7.94 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           27 |     4498 | 2024-01-21 | Ex-KRC Genk Esports         | W   | 0.499      | -            | -                | -                | -             |     4.33 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           26 |     4679 | 2024-01-18 | MOUZ NXT                    | L   | 0.476      | -            | -                | -                | -             |    -5.26 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           25 |     4729 | 2024-01-17 | Into The Breach             | L   | 0.472      | -            | -                | -                | -             |   -10.81 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           24 |     4771 | 2024-01-16 | Zero Tenacity               | L   | 0.467      | -            | -                | -                | -             |    -8.51 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           23 |     4780 | 2024-01-16 | Rebels Gaming               | W   | 0.466      | -            | -                | -                | -             |    10.79 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           22 |     4790 | 2024-01-16 | RUBY                        | W   | 0.466      | -            | -                | -                | -             |     5.06 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           21 |     4841 | 2024-01-15 | ROSOMAHA                    | W   | 0.456      | -            | -                | -                | -             |     1.71 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           20 |     4870 | 2024-01-14 | Monte Gen                   | L   | 0.450      | -            | -                | -                | -             |   -10.23 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           19 |     4934 | 2024-01-12 | OG                          | L   | 0.439      | -            | -                | -                | -             |    -1.82 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           18 |     4942 | 2024-01-12 | HAVU Gaming                 | W   | 0.439      | -            | -                | -                | -             |     4.92 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           17 |     5054 | 2024-01-10 | SINNERS Esports             | L   | 0.426      | -            | -                | -                | -             |    -6.74 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           16 |     5130 | 2024-01-09 | MOUZ NXT                    | W   | 0.416      | 0.303        | 0.215 (0.027)    | -                | -             |     8.39 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           15 |     5187 | 2024-01-05 | Permitta Esports            | W   | 0.390      | -            | -                | -                | -             |     6.60 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           14 |     5252 | 2023-12-28 | PSYCHOACTiVE                | L   | 0.339      | -            | -                | -                | -             |    -9.87 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           13 |     5254 | 2023-12-28 | L&G                         | L   | 0.337      | -            | -                | -                | -             |    -9.82 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           12 |     5259 | 2023-12-27 | PSYCHOACTiVE                | W   | 0.331      | -            | -                | -                | -             |     0.73 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           11 |     5509 | 2023-12-16 | Astralis Talent             | L   | 0.256      | -            | -                | -                | -             |    -4.44 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|           10 |     5593 | 2023-12-15 | Illuminar Gaming            | L   | 0.250      | -            | -                | -                | -             |    -6.30 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            9 |     5611 | 2023-12-14 | Ex-KRC Genk Esports         | L   | 0.245      | -            | -                | -                | -             |    -5.86 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            8 |     5645 | 2023-12-13 | Eternal Fire Academy        | W   | 0.239      | -            | -                | -                | -             |     1.25 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            7 |     5652 | 2023-12-13 | NOM Esports                 | W   | 0.237      | -            | -                | -                | -             |     1.08 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            6 |     5674 | 2023-12-12 | HyperSpirit                 | W   | 0.231      | -            | -                | -                | -             |     1.32 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            5 |     5692 | 2023-12-11 | UNiTY esports (Slovak team) | L   | 0.225      | -            | -                | -                | -             |    -3.94 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            4 |     5735 | 2023-12-10 | The Witchers                | W   | 0.217      | -            | -                | -                | -             |     1.49 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            3 |     5879 | 2023-12-07 | BLUEJAYS Lite               | W   | 0.199      | -            | -                | -                | -             |     0.58 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            2 |     5943 | 2023-12-06 | M1X                         | W   | 0.190      | -            | -                | -                | -             |     0.69 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |
|            1 |     5987 | 2023-12-05 | WHYKICK Team                | W   | 0.185      | -            | -                | -                | -             |     0.19 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,105.03)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-03 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-03-31 |      0.964 | $638.18        | $615.20         |
| 2024-03-30 |      0.957 | $1,000.00      | $956.90         |
| 2024-03-18 |      0.876 | $3,000.00      | $2,628.19       |
| 2024-03-11 |      0.830 | $1,500.00      | $1,245.35       |
| 2023-12-17 |      0.266 | $600.00        | $159.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
