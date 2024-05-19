### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, Oxygen, tiziaN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [144](../standings_global.md)<br />
Regional Rank: [98]( ../standings_europe.md)<br />
Final Rank Value:  779.9<br />
<br />
Final Rank Value (779.9) = Starting Rank Value (790.8) + Head To Head Adjustments (-11.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.8
- 400 + ( ( 0.197 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 790.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |     1699 | 2024-03-28 | UNiTY esports (Slovak team) | L   | 0.944      | -            | -                | -                | -             |   -11.47 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           67 |     1993 | 2024-03-21 | Lilmix                      | L   | 0.897      | -            | -                | -                | -             |   -20.77 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           66 |     2224 | 2024-03-15 | MOUZ NXT                    | L   | 0.857      | -            | -                | -                | -             |    -5.43 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           65 |     2288 | 2024-03-14 | Grannys Knockers            | L   | 0.849      | -            | -                | -                | -             |   -11.14 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           64 |     2439 | 2024-03-11 | Dynamo Eclot                | W   | 0.829      | 0.371        | 0.189 (0.058)    | 0.953 (0.293)    | false (0.000) |    22.02 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           63 |     2467 | 2024-03-10 | ALTERNATE aTTaX             | W   | 0.824      | 0.371        | 0.110 (0.034)    | 0.723 (0.221)    | false (0.000) |    17.38 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           62 |     2519 | 2024-03-09 | Alliance                    | L   | 0.817      | -            | -                | -                | -             |   -10.41 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           61 |     2542 | 2024-03-08 | Passion UA                  | L   | 0.810      | -            | -                | -                | -             |    -7.73 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           60 |     2713 | 2024-03-05 | 500                         | L   | 0.790      | -            | -                | -                | -             |   -10.20 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           59 |     2774 | 2024-03-04 | Sashi Esport                | W   | 0.783      | 0.371        | 0.193 (0.056)    | 1.000 (0.290)    | false (0.000) |    19.50 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           58 |     2841 | 2024-03-02 | Team Secret                 | L   | 0.772      | -            | -                | -                | -             |   -16.13 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           57 |     2913 | 2024-03-01 | BLESSED (Ukrainian team)    | L   | 0.765      | -            | -                | -                | -             |   -10.44 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           56 |     2916 | 2024-03-01 | VP.Prodigy                  | L   | 0.765      | -            | -                | -                | -             |   -11.56 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           55 |     3002 | 2024-02-28 | Zero Tenacity               | W   | 0.751      | 0.371        | 0.095 (0.026)    | 1.000 (0.279)    | false (0.000) |    15.06 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           54 |     3076 | 2024-02-26 | 9INE                        | W   | 0.737      | 0.384        | -                | 0.230 (0.065)    | false (0.000) |     5.45 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           53 |     3108 | 2024-02-25 | Team Secret                 | W   | 0.731      | -            | -                | -                | false (0.000) |     7.87 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           52 |     3225 | 2024-02-23 | Team Sampi                  | L   | 0.716      | -            | -                | -                | -             |    -5.88 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           51 |     3259 | 2024-02-22 | Passion UA                  | L   | 0.711      | -            | -                | -                | -             |    -8.42 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           50 |     3329 | 2024-02-21 | MOUZ NXT                    | L   | 0.703      | -            | -                | -                | -             |    -3.77 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           49 |     3355 | 2024-02-20 | UNiTY esports (Slovak team) | W   | 0.698      | 0.371        | 0.055 (0.014)    | 0.727 (0.188)    | false (0.000) |    14.14 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           48 |     3417 | 2024-02-19 | Ex-Anonymo Esports          | W   | 0.691      | 0.371        | 0.019 (0.005)    | 0.295 (0.076)    | false (0.000) |    10.65 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           47 |     3430 | 2024-02-19 | Illuminar Gaming            | W   | 0.689      | 0.333        | 0.010 (0.002)    | 0.243 (0.056)    | false (0.000) |    10.75 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           46 |     3483 | 2024-02-17 | The Chosen Few              | W   | 0.679      | -            | -                | -                | false (0.000) |    11.02 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           45 |     3503 | 2024-02-17 | Turów Zgorzelec Esport      | L   | 0.677      | -            | -                | -                | -             |    -9.71 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           44 |     3534 | 2024-02-16 | Aurora Young Blud           | L   | 0.671      | -            | -                | -                | -             |    -9.83 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           43 |     3586 | 2024-02-15 | CYBERSHOKE Esports          | L   | 0.665      | -            | -                | -                | -             |   -13.05 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           42 |     3637 | 2024-02-14 | Illuminar Gaming            | W   | 0.658      | 0.333        | 0.010 (0.002)    | 0.243 (0.053)    | -             |    10.22 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           41 |     3682 | 2024-02-13 | GenOne                      | W   | 0.651      | 0.371        | -                | 0.323 (0.078)    | -             |     5.27 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           40 |     3723 | 2024-02-12 | Team Spirit Academy         | L   | 0.645      | -            | -                | -                | -             |    -9.55 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           39 |     3987 | 2024-02-03 | Sangal Esports              | W   | 0.584      | -            | -                | -                | -             |     6.84 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           38 |     4151 | 2024-01-30 | Endpoint                    | L   | 0.557      | -            | -                | -                | -             |    -7.88 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           37 |     4155 | 2024-01-30 | Preasy Esport               | L   | 0.556      | -            | -                | -                | -             |    -4.84 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           36 |     4320 | 2024-01-26 | FLuffy Gangsters            | W   | 0.531      | -            | -                | -                | -             |     3.28 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           35 |     4336 | 2024-01-26 | ALTERNATE aTTaX             | L   | 0.530      | -            | -                | -                | -             |    -3.66 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           34 |     4599 | 2024-01-19 | EYEBALLERS                  | W   | 0.486      | 0.143        | 0.051 (0.004)    | -                | -             |    10.60 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           33 |     4648 | 2024-01-18 | Team Spirit                 | L   | 0.479      | -            | -                | -                | -             |    -0.05 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           32 |     4663 | 2024-01-18 | Preasy Esport               | L   | 0.478      | -            | -                | -                | -             |    -4.20 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           31 |     4706 | 2024-01-17 | Into The Breach             | L   | 0.473      | -            | -                | -                | -             |    -7.27 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           30 |     4723 | 2024-01-17 | DMS                         | W   | 0.472      | -            | -                | -                | -             |     4.28 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           29 |     5067 | 2024-01-09 | Fnatic                      | L   | 0.420      | -            | -                | -                | -             |    -1.26 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           28 |     5068 | 2024-01-09 | KOI                         | L   | 0.420      | -            | -                | -                | -             |    -2.75 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           27 |     5076 | 2024-01-09 | BLEED Esports               | W   | 0.419      | 0.143        | 0.284 (0.017)    | -                | -             |    11.28 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           26 |     5085 | 2024-01-09 | TBA.ECF                     | W   | 0.419      | -            | -                | -                | -             |     3.93 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           25 |     5096 | 2024-01-09 | Come on now dawg            | W   | 0.418      | -            | -                | -                | -             |     2.33 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           24 |     5114 | 2024-01-09 | The Witchers                | W   | 0.418      | -            | -                | -                | -             |     6.85 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           23 |     6020 | 2023-12-04 | ALTERNATE aTTaX             | L   | 0.177      | -            | -                | -                | -             |    -0.96 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|           22 |     6140 | 2023-12-02 | Sangal Esports              | L   | 0.163      | -            | -                | -                | -             |    -3.41 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|           21 |     6276 | 2023-11-29 | Team Spirit Academy         | L   | 0.144      | -            | -                | -                | -             |    -2.25 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           20 |     6326 | 2023-11-28 | Insilio                     | W   | 0.138      | -            | -                | -                | -             |     2.91 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           19 |     6377 | 2023-11-27 | IKLA                        | W   | 0.131      | -            | -                | -                | -             |     1.50 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|           18 |     6486 | 2023-11-24 | LF0                         | W   | 0.111      | -            | -                | -                | -             |     1.09 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           17 |     6491 | 2023-11-24 | HOTU                        | L   | 0.111      | -            | -                | -                | -             |    -1.70 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           16 |     6648 | 2023-11-20 | Sprout                      | L   | 0.084      | -            | -                | -                | -             |    -1.71 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|           15 |     6829 | 2023-11-16 | SAW                         | L   | 0.058      | -            | -                | -                | -             |    -0.04 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|           14 |     6890 | 2023-11-15 | 9Pandas                     | L   | 0.051      | -            | -                | -                | -             |    -0.21 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           13 |     6927 | 2023-11-14 | Pompa Team                  | W   | 0.045      | -            | -                | -                | -             |     0.24 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           12 |     6963 | 2023-11-13 | K10                         | W   | 0.039      | -            | -                | -                | -             |     0.78 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           11 |     6989 | 2023-11-13 | Endpoint                    | L   | 0.036      | -            | -                | -                | -             |    -0.49 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|           10 |     7003 | 2023-11-12 | Aurora Young Blud           | W   | 0.032      | -            | -                | -                | -             |     0.55 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            9 |     7017 | 2023-11-12 | GUN5 Esports                | L   | 0.030      | -            | -                | -                | -             |    -0.65 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            8 |     7019 | 2023-11-12 | 9Pandas                     | W   | 0.030      | -            | -                | -                | -             |     0.81 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            7 |     7065 | 2023-11-11 | ODDIK                       | W   | 0.024      | -            | -                | -                | -             |     0.50 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            6 |     7103 | 2023-11-10 | Aurora Young Blud           | W   | 0.017      | -            | -                | -                | -             |     0.30 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            5 |     7108 | 2023-11-10 | ENCE Academy                | W   | 0.017      | -            | -                | -                | -             |     0.31 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            4 |     7131 | 2023-11-09 | TSM                         | W   | 0.012      | -            | -                | -                | -             |     0.14 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|            3 |     7167 | 2023-11-08 | The Witchers                | L   | 0.006      | -            | -                | -                | -             |    -0.09 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            2 |     7191 | 2023-11-08 | Viperio                     | W   | 0.005      | -            | -                | -                | -             |     0.04 | c0llins, forsyy, Marix, Oxygen, tiziaN |
|            1 |     7200 | 2023-11-08 | Los Alpacas                 | W   | 0.004      | -            | -                | -                | -             |     0.04 | c0llins, forsyy, Marix, Oxygen, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($172.77)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-11-21 |      0.092 | $1,500.00      | $138.47         |
| 2023-11-12 |      0.032 | $1,084.83      | $34.30          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
