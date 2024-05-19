### Roster Details<br />
Team Name: Metizport<br />
Roster: adamb, Jackinho, nilo, susp, ztr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [41](../standings_global.md)<br />
Regional Rank: [31]( ../standings_europe.md)<br />
Final Rank Value:  1093.7<br />
<br />
Final Rank Value (1093.7) = Starting Rank Value (1013.3) + Head To Head Adjustments (80.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.580[<sup>1</sup>](#table2)
- Bounty Collected: 0.442[<sup>2</sup>](#table1)
- Opponent Network: 0.183[<sup>2</sup>](#table1)
- LAN Wins: 0.032[<sup>2</sup>](#table1)

The average of these factors is 0.309<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1013.3
- 400 + ( ( 0.309 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1013.3


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
|           82 |       85 | 2024-05-04 | AMKAL ESPORTS            | L   | 1.000      | -            | -                | -                | -             |    -9.75 | adamb, Jackinho, nilo, susp, ztr    |
|           81 |      123 | 2024-05-03 | Zero Tenacity            | W   | 1.000      | 0.435        | 0.095 (0.041)    | 1.000 (0.435)    | false (0.000) |    12.20 | adamb, Jackinho, nilo, susp, ztr    |
|           80 |      470 | 2024-04-25 | Nexus Gaming             | L   | 1.000      | -            | -                | -                | -             |   -23.79 | adamb, Jackinho, nilo, susp, ztr    |
|           79 |      584 | 2024-04-23 | Alliance                 | W   | 1.000      | 0.384        | -                | 0.729 (0.280)    | false (0.000) |     6.17 | adamb, Jackinho, nilo, p1ke, susp   |
|           78 |      834 | 2024-04-19 | FURIA Esports            | L   | 1.000      | -            | -                | -                | -             |    -3.05 | adamb, jackinho, Plopski, susp, ztr |
|           77 |      873 | 2024-04-18 | Imperial Esports         | L   | 1.000      | -            | -                | -                | -             |    -3.80 | adamb, jackinho, Plopski, susp, ztr |
|           76 |     1297 | 2024-04-09 | Guild Eagles             | L   | 1.000      | -            | -                | -                | -             |   -21.33 | adamb, Jackinho, nilo, susp, ztr    |
|           75 |     1319 | 2024-04-08 | Aurora Gaming            | L   | 1.000      | -            | -                | -                | -             |    -3.43 | adamb, jackinho, nilo, susp, ztr    |
|           74 |     1338 | 2024-04-08 | 9Pandas                  | L   | 1.000      | -            | -                | -                | -             |   -16.15 | adamb, jackinho, nilo, susp, ztr    |
|           73 |     1364 | 2024-04-07 | EYEBALLERS               | W   | 1.000      | -            | -                | -                | false (0.000) |     7.58 | adamb, Jackinho, nilo, susp, ztr    |
|           72 |     1377 | 2024-04-07 | Johnny Speeds            | W   | 1.000      | -            | -                | -                | false (0.000) |     5.79 | adamb, Jackinho, nilo, susp, ztr    |
|           71 |     1416 | 2024-04-06 | Young Gods               | W   | 1.000      | -            | -                | -                | false (0.000) |     0.69 | adamb, Jackinho, nilo, susp, ztr    |
|           70 |     1496 | 2024-04-04 | Ninjas in Pyjamas        | L   | 0.991      | -            | -                | -                | -             |   -15.36 | adamb, jackinho, nilo, susp, ztr    |
|           69 |     1530 | 2024-04-03 | Monte                    | W   | 0.985      | 0.143        | 0.199 (0.028)    | -                | false (0.000) |    22.85 | adamb, jackinho, nilo, susp, ztr    |
|           68 |     1540 | 2024-04-03 | BLESSED (Ukrainian team) | W   | 0.984      | 0.143        | -                | 0.781 (0.110)    | false (0.000) |     9.19 | adamb, jackinho, nilo, susp, ztr    |
|           67 |     1582 | 2024-04-02 | Aurora Gaming            | L   | 0.977      | -            | -                | -                | -             |    -3.10 | adamb, jackinho, nilo, susp, ztr    |
|           66 |     1603 | 2024-04-01 | PARIVISION               | L   | 0.971      | -            | -                | -                | -             |   -24.44 | adamb, Jackinho, nilo, susp, ztr    |
|           65 |     1728 | 2024-03-27 | Aurora Gaming            | L   | 0.939      | -            | -                | -                | -             |    -3.48 | adamb, jackinho, nilo, susp, ztr    |
|           64 |     1733 | 2024-03-27 | Natus Vincere Junior     | W   | 0.939      | -            | -                | -                | false (0.000) |     5.66 | adamb, jackinho, nilo, susp, ztr    |
|           63 |     1745 | 2024-03-27 | TSM                      | W   | 0.938      | -            | -                | -                | -             |     2.74 | adamb, jackinho, nilo, susp, ztr    |
|           62 |     1813 | 2024-03-26 | Lausanne-Sport Esports   | W   | 0.932      | -            | -                | -                | -             |     2.51 | adamb, jackinho, nilo, susp, ztr    |
|           61 |     2276 | 2024-03-14 | ALTERNATE aTTaX          | L   | 0.851      | -            | -                | -                | -             |   -21.19 | adamb, Jackinho, nilo, susp, ztr    |
|           60 |     2325 | 2024-03-13 | HEROIC                   | L   | 0.844      | -            | -                | -                | -             |    -1.49 | adamb, Jackinho, nilo, susp, ztr    |
|           59 |     2365 | 2024-03-12 | B8                       | W   | 0.839      | -            | -                | -                | -             |     8.76 | adamb, Jackinho, nilo, susp, ztr    |
|           58 |     2377 | 2024-03-12 | Apeks                    | W   | 0.838      | 0.143        | 0.253 (0.030)    | -                | -             |    21.54 | adamb, Jackinho, nilo, susp, ztr    |
|           57 |     2407 | 2024-03-11 | Preasy Esport            | W   | 0.832      | -            | -                | -                | -             |    10.09 | adamb, Jackinho, nilo, susp, ztr    |
|           56 |     2427 | 2024-03-11 | ENCE                     | L   | 0.831      | -            | -                | -                | -             |    -2.07 | adamb, Jackinho, nilo, susp, ztr    |
|           55 |     2447 | 2024-03-10 | Team Spirit              | L   | 0.826      | -            | -                | -                | -             |    -0.41 | adamb, Jackinho, nilo, susp, ztr    |
|           54 |     2498 | 2024-03-09 | Monte                    | W   | 0.818      | 0.535        | 0.199 (0.087)    | 0.378 (0.166)    | -             |    21.25 | adamb, Jackinho, nilo, susp, ztr    |
|           53 |     2503 | 2024-03-09 | EYEBALLERS               | L   | 0.818      | -            | -                | -                | -             |   -18.64 | adamb, Jackinho, nilo, susp, ztr    |
|           52 |     2508 | 2024-03-09 | Lemondogs                | W   | 0.817      | -            | -                | -                | -             |     1.27 | adamb, Jackinho, nilo, susp, ztr    |
|           51 |     2514 | 2024-03-09 | Skillz of Boras          | W   | 0.817      | -            | -                | -                | -             |     0.43 | adamb, Jackinho, nilo, susp, ztr    |
|           50 |     2536 | 2024-03-08 | Team Secret              | W   | 0.811      | 0.384        | -                | 0.368 (0.115)    | -             |     1.73 | adamb, Jackinho, nilo, susp, ztr    |
|           49 |     2603 | 2024-03-06 | Team Falcons             | W   | 0.799      | 0.535        | 0.431 (0.184)    | -                | -             |    20.64 | adamb, Jackinho, nilo, susp, ztr    |
|           48 |     2783 | 2024-03-03 | The Chosen Few           | W   | 0.779      | -            | -                | -                | -             |     4.78 | adamb, Jackinho, nilo, susp, ztr    |
|           47 |     2791 | 2024-03-03 | ILIN                     | W   | 0.779      | -            | -                | -                | -             |     2.04 | adamb, Jackinho, nilo, susp, ztr    |
|           46 |     2800 | 2024-03-03 | RUSH B (Russian team)    | W   | 0.778      | -            | -                | -                | -             |     3.74 | adamb, Jackinho, nilo, susp, ztr    |
|           45 |     2816 | 2024-03-03 | Dynamo Eclot             | L   | 0.777      | -            | -                | -                | -             |   -10.58 | adamb, Jackinho, nilo, susp, ztr    |
|           44 |     2827 | 2024-03-02 | FORZE Esports            | W   | 0.773      | 0.143        | 0.210 (0.023)    | -                | -             |    12.49 | adamb, Jackinho, nilo, susp, ztr    |
|           43 |     2839 | 2024-03-02 | Dynamo Eclot             | W   | 0.772      | 0.143        | -                | 0.953 (0.105)    | -             |    14.55 | adamb, Jackinho, nilo, susp, ztr    |
|           42 |     2965 | 2024-02-29 | Endpoint                 | W   | 0.757      | 0.384        | -                | 0.785 (0.229)    | -             |     5.26 | adamb, Jackinho, nilo, susp, ztr    |
|           41 |     3005 | 2024-02-28 | INGLORIOUS               | W   | 0.750      | 0.384        | -                | 0.358 (0.103)    | -             |     5.14 | adamb, Jackinho, nilo, susp, ztr    |
|           40 |     3027 | 2024-02-27 | Guild Eagles             | L   | 0.745      | -            | -                | -                | -             |   -11.29 | adamb, Jackinho, nilo, susp, ztr    |
|           39 |     3057 | 2024-02-26 | Sashi Esport             | W   | 0.739      | -            | -                | -                | -             |     3.79 | adamb, Jackinho, nilo, susp, ztr    |
|           38 |     3743 | 2024-02-11 | Apeks                    | W   | 0.639      | -            | -                | -                | -             |    17.60 | adamb, Jackinho, nilo, susp, ztr    |
|           37 |     3769 | 2024-02-10 | FURIA Esports            | W   | 0.632      | 0.143        | 0.384 (0.035)    | -                | -             |    19.10 | adamb, Jackinho, nilo, susp, ztr    |
|           36 |     3776 | 2024-02-10 | Apeks                    | L   | 0.631      | -            | -                | -                | -             |    -2.21 | adamb, Jackinho, nilo, susp, ztr    |
|           35 |     3778 | 2024-02-10 | FURIA Esports            | W   | 0.631      | 0.143        | 0.384 (0.035)    | -                | -             |    19.22 | adamb, Jackinho, nilo, susp, ztr    |
|           34 |     3846 | 2024-02-07 | Sprout                   | W   | 0.611      | -            | -                | -                | -             |     1.12 | adamb, Jackinho, nilo, susp, ztr    |
|           33 |     3864 | 2024-02-06 | Into The Breach          | L   | 0.604      | -            | -                | -                | -             |   -13.46 | adamb, Jackinho, nilo, susp, ztr    |
|           32 |     3918 | 2024-02-04 | TOOMUCHVIDEOGAMES        | W   | 0.592      | -            | -                | -                | -             |     1.19 | adamb, Jackinho, nilo, susp, ztr    |
|           31 |     3936 | 2024-02-04 | DUSTY                    | W   | 0.590      | -            | -                | -                | -             |     3.20 | adamb, Jackinho, nilo, susp, ztr    |
|           30 |     4003 | 2024-02-03 | Sangal Esports           | W   | 0.583      | -            | -                | -                | -             |     2.68 | adamb, Jackinho, nilo, susp, ztr    |
|           29 |     4011 | 2024-02-02 | EYEBALLERS               | W   | 0.579      | -            | -                | -                | -             |     7.40 | adamb, Jackinho, nilo, susp, ztr    |
|           28 |     4014 | 2024-02-02 | Preasy Esport            | W   | 0.579      | -            | -                | -                | -             |     8.72 | adamb, Jackinho, nilo, susp, ztr    |
|           27 |     4019 | 2024-02-02 | Alliance                 | W   | 0.578      | -            | -                | -                | -             |     5.52 | adamb, Jackinho, nilo, susp, ztr    |
|           26 |     4032 | 2024-02-02 | 777 Esports              | W   | 0.578      | -            | -                | -                | -             |     3.44 | adamb, Jackinho, nilo, susp, ztr    |
|           25 |     4085 | 2024-02-01 | Team Sampi               | W   | 0.571      | 0.384        | 0.108 (0.024)    | 0.709 (0.155)    | -             |     9.33 | adamb, Jackinho, nilo, susp, ztr    |
|           24 |     4169 | 2024-01-29 | Dynamo Eclot             | L   | 0.553      | -            | -                | -                | -             |    -5.23 | adamb, Jackinho, nilo, susp, ztr    |
|           23 |     4201 | 2024-01-29 | BLEED Esports            | W   | 0.550      | 0.371        | 0.284 (0.058)    | 0.644 (0.131)    | -             |    11.22 | adamb, Jackinho, nilo, susp, ztr    |
|           22 |     4360 | 2024-01-25 | BIG Academy              | W   | 0.523      | -            | -                | -                | -             |     5.07 | adamb, Jackinho, nilo, susp, ztr    |
|           21 |     4809 | 2024-01-16 | 9INE                     | L   | 0.465      | -            | -                | -                | -             |   -13.23 | adamb, Jackinho, nilo, susp, ztr    |
|           20 |     5092 | 2024-01-09 | IKLA                     | L   | 0.418      | -            | -                | -                | -             |   -11.16 | adamb, Jackinho, nilo, susp, ztr    |
|           19 |     5246 | 2023-12-30 | The Witchers             | L   | 0.351      | -            | -                | -                | -             |    -8.48 | adamb, Jackinho, nilo, susp, ztr    |
|           18 |     5248 | 2023-12-30 | VP.Prodigy               | W   | 0.350      | -            | -                | -                | -             |     3.31 | adamb, Jackinho, nilo, susp, ztr    |
|           17 |     5249 | 2023-12-29 | Aurora Young Blud        | W   | 0.345      | -            | -                | -                | -             |     2.88 | adamb, Jackinho, nilo, susp, ztr    |
|           16 |     5250 | 2023-12-29 | EsmagaB                  | W   | 0.344      | -            | -                | -                | -             |     3.44 | adamb, Jackinho, nilo, susp, ztr    |
|           15 |     5258 | 2023-12-27 | Aurora Young Blud        | L   | 0.331      | -            | -                | -                | -             |    -7.68 | adamb, Jackinho, nilo, susp, ztr    |
|           14 |     5304 | 2023-12-20 | Pera Esports             | L   | 0.285      | -            | -                | -                | -             |    -5.59 | adamb, Jackinho, nilo, susp, ztr    |
|           13 |     5306 | 2023-12-20 | ARCRED                   | W   | 0.284      | -            | -                | -                | -             |     2.39 | adamb, Jackinho, nilo, susp, ztr    |
|           12 |     5316 | 2023-12-19 | GUN5 Esports             | W   | 0.277      | -            | -                | -                | -             |     1.01 | adamb, Jackinho, nilo, susp, ztr    |
|           11 |     5319 | 2023-12-19 | Pera Esports             | W   | 0.277      | -            | -                | -                | -             |     3.33 | adamb, Jackinho, nilo, susp, ztr    |
|           10 |     5351 | 2023-12-17 | Lilmix                   | W   | 0.265      | -            | -                | -                | true (0.265)  |     1.24 | adamb, Jackinho, nilo, susp, ztr    |
|            9 |     6164 | 2023-12-01 | GODSENT                  | L   | 0.158      | -            | -                | -                | -             |    -3.78 | adamb, hns, Jackinho, nilo, RuStY   |
|            8 |     6433 | 2023-11-25 | Soda Gaming              | L   | 0.118      | -            | -                | -                | -             |    -3.00 | adamb, hns, Jackinho, nilo, RuStY   |
|            7 |     6793 | 2023-11-17 | SAW                      | W   | 0.063      | -            | -                | -                | -             |     1.85 | adamb, hns, Jackinho, nilo, RuStY   |
|            6 |     6902 | 2023-11-15 | ODDIK                    | W   | 0.049      | -            | -                | -                | -             |     0.54 | adamb, hns, Jackinho, nilo, RuStY   |
|            5 |     7000 | 2023-11-12 | Ex-Anonymo Esports       | W   | 0.032      | -            | -                | -                | -             |     0.20 | adamb, hns, Jackinho, nilo, RuStY   |
|            4 |     7047 | 2023-11-11 | Lilmix                   | L   | 0.026      | -            | -                | -                | -             |    -0.69 | adamb, hns, Jackinho, nilo, RuStY   |
|            3 |     7055 | 2023-11-11 | Pungrottorna             | W   | 0.025      | -            | -                | -                | true (0.025)  |     0.04 | adamb, hns, Jackinho, nilo, RuStY   |
|            2 |     7095 | 2023-11-10 | MOUZ NXT                 | W   | 0.018      | -            | -                | -                | -             |     0.35 | adamb, hns, Jackinho, nilo, RuStY   |
|            1 |     7195 | 2023-11-08 | Team Space               | W   | 0.005      | -            | -                | -                | -             |     0.03 | adamb, hns, Jackinho, nilo, RuStY   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($29,831.92)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-07 |      1.000 | $6,087.86      | $6,087.86       |
| 2024-03-10 |      0.826 | $12,500.00     | $10,319.73      |
| 2023-12-30 |      0.351 | $5,000.00      | $1,755.32       |
| 2023-12-20 |      0.285 | $2,000.00      | $569.91         |
| 2023-12-17 |      0.265 | $981.34        | $260.42         |
| 2023-12-03 |      0.172 | $1,437.91      | $247.37         |
| 2023-11-26 |      0.124 | $1,957.16      | $242.92         |
| 2023-11-18 |      0.070 | $5,000.00      | $348.38         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
