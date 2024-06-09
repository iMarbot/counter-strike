### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Ducky, Girafffe, Vacancy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [80](../standings_global.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
Final Rank Value:  913.0<br />
<br />
Final Rank Value (913.0) = Starting Rank Value (1048.2) + Head To Head Adjustments (-135.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.354[<sup>2</sup>](#table1)
- Opponent Network: 0.220[<sup>2</sup>](#table1)
- LAN Wins: 0.350[<sup>2</sup>](#table1)

The average of these factors is 0.319<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1048.2
- 400 + ( ( 0.319 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1048.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |       63 | 2024-05-29 | DMS                       | L   | 1.000      | -            | -                | -                | -         |   -16.45 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           92 |      346 | 2024-05-24 | VaselineWorms             | W   | 1.000      | 0.372        | -                | 0.418 (0.156)    | 0 (0.000) |     8.89 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           91 |      362 | 2024-05-24 | NOM Esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           90 |      474 | 2024-05-22 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -18.26 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           89 |      571 | 2024-05-21 | ex-K10                    | L   | 1.000      | -            | -                | -                | -         |   -23.15 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           88 |      633 | 2024-05-21 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |   -11.97 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           87 |      730 | 2024-05-20 | Team Sampi                | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.677 (0.294)    | 0 (0.000) |    16.27 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           86 |      870 | 2024-05-18 | Endpoint                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.67 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           85 |      875 | 2024-05-18 | EXO Clan                  | W   | 1.000      | -            | -                | -                | -         |    12.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           84 |      884 | 2024-05-18 | Team Cookie               | W   | 1.000      | -            | -                | -                | -         |     1.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           83 |      945 | 2024-05-18 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -19.32 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           82 |      962 | 2024-05-17 | FearFerox                 | W   | 1.000      | -            | -                | -                | -         |     5.24 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           81 |      971 | 2024-05-17 | EXO Clan                  | W   | 1.000      | -            | -                | -                | -         |    12.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           80 |      992 | 2024-05-17 | Pera Esports              | L   | 1.000      | -            | -                | -                | -         |   -15.58 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           79 |     1001 | 2024-05-17 | DASH                      | W   | 1.000      | -            | -                | -                | -         |     5.92 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           78 |     1013 | 2024-05-17 | VOLT                      | W   | 1.000      | -            | -                | -                | -         |     1.50 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           77 |     1062 | 2024-05-16 | The Last Resort           | W   | 1.000      | -            | -                | -                | -         |     6.51 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           76 |     1152 | 2024-05-15 | TopTab Club               | W   | 1.000      | -            | -                | -                | -         |     2.93 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           75 |     1168 | 2024-05-15 | Raptors Esports Club      | W   | 1.000      | -            | -                | -                | -         |    10.81 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           74 |     1206 | 2024-05-15 | Sangal Esports            | W   | 1.000      | 0.435        | 0.166 (0.072)    | 0.658 (0.286)    | -         |    22.17 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           73 |     1253 | 2024-05-14 | Team Invictum             | W   | 1.000      | -            | -                | -                | -         |     7.02 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           72 |     1285 | 2024-05-14 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -6.23 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           71 |     1345 | 2024-05-13 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -14.40 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           70 |     1360 | 2024-05-12 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |   -11.06 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           69 |     1403 | 2024-05-12 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -9.96 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           68 |     1435 | 2024-05-11 | V1dar Gaming              | W   | 1.000      | -            | -                | -                | -         |     9.34 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           67 |     1534 | 2024-05-10 | LEON Esports              | W   | 1.000      | -            | -                | -                | -         |     8.38 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           66 |     1546 | 2024-05-10 | Dynamo Eclot              | L   | 1.000      | -            | -                | -                | -         |   -13.96 | Diviiii, Ducky, Extinct, Girafffe, Vacancy  |
|           65 |     1550 | 2024-05-10 | GamerLegion Academy       | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    12.12 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           64 |     1575 | 2024-05-09 | ROYALS                    | W   | 1.000      | -            | -                | -                | -         |     6.77 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           63 |     1675 | 2024-05-08 | Johnny Speeds             | W   | 1.000      | 0.333        | 0.056 (0.019)    | 0.683 (0.228)    | -         |    20.95 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           62 |     1683 | 2024-05-07 | Halal5                    | W   | 1.000      | -            | -                | -                | -         |     6.94 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           61 |     1718 | 2024-05-07 | RoundsGG                  | W   | 1.000      | -            | -                | -                | -         |     5.91 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           60 |     1761 | 2024-05-06 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -21.55 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           59 |     1802 | 2024-05-05 | Preasy Esport             | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.705 (0.235)    | -         |    11.79 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           58 |     1813 | 2024-05-05 | UNiTY esports             | W   | 1.000      | 0.333        | 0.021 (0.007)    | 0.766 (0.255)    | -         |    16.10 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           57 |     1867 | 2024-05-04 | Team Flow                 | L   | 1.000      | -            | -                | -                | -         |   -27.47 | AdamJC, arTisT, Ducky, Girafffe, Vacancy    |
|           56 |     1896 | 2024-05-03 | Part Timers               | W   | 1.000      | -            | -                | -                | -         |     8.52 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           55 |     1995 | 2024-05-01 | LOG Esports               | W   | 1.000      | -            | -                | -                | -         |     3.32 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           54 |     2105 | 2024-04-29 | Aurora Young Blud         | W   | 0.997      | 0.372        | 0.008 (0.003)    | 0.506 (0.188)    | -         |    12.71 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           53 |     2340 | 2024-04-25 | Lemondogs                 | L   | 0.971      | -            | -                | -                | -         |   -24.76 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           52 |     2373 | 2024-04-25 | ex-Turów Zgorzelec Esport | W   | 0.968      | 0.333        | -                | 0.491 (0.158)    | -         |    10.59 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           51 |     2455 | 2024-04-23 | Zero Tenacity             | L   | 0.957      | -            | -                | -                | -         |   -10.24 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           50 |     2487 | 2024-04-22 | Kappa Bar                 | W   | 0.951      | -            | -                | -                | -         |     3.06 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           49 |     2877 | 2024-04-17 | BetBoom Team              | L   | 0.918      | -            | -                | -                | -         |    -2.29 | arTisT, Ducky, Girafffe, J3nsyy, Vacancy    |
|           48 |     3002 | 2024-04-15 | DMS                       | L   | 0.904      | -            | -                | -                | -         |   -16.60 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           47 |     3029 | 2024-04-15 | UNiTY esports             | L   | 0.902      | -            | -                | -                | -         |   -16.34 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           46 |     3055 | 2024-04-14 | Johnny Speeds             | L   | 0.896      | -            | -                | -                | -         |   -10.69 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           45 |     3158 | 2024-04-12 | Lilmix                    | W   | 0.881      | 0.333        | -                | 0.593 (0.174)    | -         |     9.20 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           44 |     3175 | 2024-04-11 | Natus Vincere Junior      | W   | 0.877      | 0.372        | 0.010 (0.003)    | -                | -         |    11.97 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           43 |     3187 | 2024-04-11 | Lilmix                    | L   | 0.877      | -            | -                | -                | -         |   -18.50 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           42 |     3347 | 2024-04-09 | ROSOMAHA                  | W   | 0.862      | -            | -                | -                | -         |     3.58 | aidKiT, Ducky, Girafffe, Vacancy, Zax1e     |
|           41 |     3428 | 2024-04-07 | Lazer Cats                | L   | 0.849      | -            | -                | -                | -         |   -21.26 | Diviiii, Ducky, Girafffe, Vacancy, Zax1e    |
|           40 |     3492 | 2024-04-06 | BRUTE                     | W   | 0.842      | -            | -                | -                | -         |     2.51 | Diviiii, Ducky, Girafffe, Vacancy, Zax1e    |
|           39 |     3592 | 2024-04-04 | ex-K10                    | L   | 0.829      | -            | -                | -                | -         |   -17.79 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           38 |     3722 | 2024-04-01 | Reason Gaming             | W   | 0.809      | -            | -                | -                | 1 (0.809) |     7.00 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           37 |     3751 | 2024-03-31 | Ahoka                     | W   | 0.802      | -            | -                | -                | 1 (0.802) |     5.88 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           36 |     3767 | 2024-03-30 | p0dbots                   | W   | 0.797      | -            | -                | -                | 1 (0.797) |     3.53 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           35 |     3781 | 2024-03-30 | MAMMOTHS2                 | W   | 0.796      | -            | -                | -                | 1 (0.796) |     1.41 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           34 |     3886 | 2024-03-27 | Ninjas in Pyjamas         | L   | 0.778      | -            | -                | -                | -         |    -7.36 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           33 |     3900 | 2024-03-27 | Betera Esports            | W   | 0.777      | 0.143        | 0.023 (0.003)    | -                | -         |     9.43 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           32 |     3971 | 2024-03-26 | AMKAL ESPORTS             | W   | 0.771      | 0.143        | 0.146 (0.016)    | -                | -         |    18.50 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           31 |     4264 | 2024-03-19 | EXO Clan                  | L   | 0.725      | -            | -                | -                | -         |    -9.14 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           30 |     4666 | 2024-03-12 | Part Timers               | W   | 0.678      | -            | -                | -                | -         |     5.67 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           29 |     4846 | 2024-03-09 | ROYALS                    | W   | 0.656      | -            | -                | -                | -         |     4.73 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           28 |     5094 | 2024-03-05 | Dreams To Legends         | W   | 0.631      | -            | -                | -                | -         |     1.52 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           27 |     5397 | 2024-02-29 | Viperio                   | W   | 0.598      | -            | -                | -                | -         |     3.86 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           26 |     5399 | 2024-02-29 | ex-K10                    | L   | 0.598      | -            | -                | -                | -         |   -11.88 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           25 |     5421 | 2024-02-29 | The Chosen Few            | L   | 0.597      | -            | -                | -                | -         |   -13.90 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           24 |     5488 | 2024-02-28 | Sashi Esport              | L   | 0.589      | -            | -                | -                | -         |   -13.75 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           23 |     5609 | 2024-02-25 | Permitta Esports          | L   | 0.570      | -            | -                | -                | -         |    -8.58 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           22 |     5674 | 2024-02-24 | INGLORIOUS                | L   | 0.564      | -            | -                | -                | -         |   -13.37 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           21 |     5718 | 2024-02-24 | NOM Esports               | L   | 0.563      | -            | -                | -                | -         |   -15.62 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           20 |     5820 | 2024-02-22 | ex-Anonymo Esports        | W   | 0.550      | -            | -                | -                | -         |     3.11 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           19 |     5907 | 2024-02-21 | Sashi Esport              | L   | 0.542      | -            | -                | -                | -         |    -6.43 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           18 |     5930 | 2024-02-20 | MOUZ NXT                  | L   | 0.537      | -            | -                | -                | -         |    -5.91 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           17 |     6205 | 2024-02-15 | Team Invictum             | W   | 0.505      | -            | -                | -                | -         |     0.50 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           16 |     6328 | 2024-02-13 | Raptors Esports Club      | W   | 0.491      | -            | -                | -                | -         |     4.50 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           15 |     6444 | 2024-02-10 | Dynamo Eclot              | L   | 0.471      | -            | -                | -                | -         |    -5.70 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           14 |     6448 | 2024-02-10 | Lilmix                    | W   | 0.471      | -            | -                | -                | -         |     4.33 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           13 |     6455 | 2024-02-10 | esmagaB                   | W   | 0.470      | -            | -                | -                | -         |     4.47 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           12 |     6746 | 2024-02-03 | Endpoint                  | L   | 0.423      | -            | -                | -                | -         |    -7.78 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           11 |     6766 | 2024-02-03 | SRK                       | W   | 0.423      | -            | -                | -                | -         |     0.44 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           10 |     6893 | 2024-02-01 | ROYALS                    | L   | 0.409      | -            | -                | -                | -         |   -12.10 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            9 |     7183 | 2024-01-27 | Sprout                    | L   | 0.377      | -            | -                | -                | -         |   -10.79 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            8 |     7195 | 2024-01-27 | Back2TheGame              | W   | 0.377      | -            | -                | -                | -         |     0.35 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            7 |     7213 | 2024-01-27 | Sashi Esport              | L   | 0.375      | -            | -                | -                | -         |    -5.59 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            6 |     7818 | 2024-01-17 | ghoulsW                   | L   | 0.311      | -            | -                | -                | -         |    -9.34 | Ducky, Extinct, Girafffe, tvs, Vacancy      |
|            5 |     7888 | 2024-01-16 | Linx Legacy Madagaskar    | L   | 0.305      | -            | -                | -                | -         |    -9.15 | Ducky, Extinct, Girafffe, tvs, Vacancy      |
|            4 |     7916 | 2024-01-16 | kONO.ECF                  | W   | 0.304      | -            | -                | -                | -         |     2.63 | Ducky, Extinct, Girafffe, tvs, Vacancy      |
|            3 |     9221 | 2023-12-10 | ex-K10                    | L   | 0.058      | -            | -                | -                | -         |    -1.32 | arTisT, Ducky, Extinct, Girafffe, Wolfie    |
|            2 |     9253 | 2023-12-10 | ex-K10                    | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.48 | arTisT, Ducky, Extinct, Girafffe, Wolfie    |
|            1 |     9310 | 2023-12-09 | DuckDuckGOOSE             | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.07 | arTisT, Ducky, Extinct, Girafffe, Wolfie    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,313.45)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-13 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-01 |      0.809 | $3,160.28      | $2,555.22       |
| 2024-03-29 |      0.791 | $315.48        | $249.67         |
| 2024-03-09 |      0.656 | $642.90        | $421.99         |
| 2023-12-10 |      0.058 | $1,505.76      | $86.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
