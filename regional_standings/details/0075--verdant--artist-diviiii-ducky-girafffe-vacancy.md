### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Ducky, Girafffe, Vacancy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [75](../standings_global.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
Final Rank Value:  923.9<br />
<br />
Final Rank Value (923.9) = Starting Rank Value (1044.5) + Head To Head Adjustments (-120.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.352[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.350[<sup>2</sup>](#table1)

The average of these factors is 0.317<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1044.5
- 400 + ( ( 0.317 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1044.5


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
|           91 |      337 | 2024-05-24 | VaselineWorms             | W   | 1.000      | 0.372        | -                | 0.424 (0.158)    | 0 (0.000) |     9.16 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           90 |      353 | 2024-05-24 | NOM Esports               | W   | 1.000      | 0.372        | -                | 0.360 (0.134)    | 0 (0.000) |     6.17 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           89 |      468 | 2024-05-22 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -18.52 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           88 |      560 | 2024-05-21 | ex-K10                    | L   | 1.000      | -            | -                | -                | -         |   -22.78 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           87 |      622 | 2024-05-21 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |   -11.88 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           86 |      718 | 2024-05-20 | Team Sampi                | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.665 (0.289)    | 0 (0.000) |    16.42 | arTisT, Diviiii, Extinct, Girafffe, Vacancy |
|           85 |      858 | 2024-05-18 | Endpoint                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    14.17 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           84 |      863 | 2024-05-18 | EXO Clan                  | W   | 1.000      | 0.143        | 0.013 (0.002)    | -                | -         |    11.90 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           83 |      872 | 2024-05-18 | Team Cookie               | W   | 1.000      | -            | -                | -                | -         |     1.63 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           82 |      933 | 2024-05-18 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -19.14 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           81 |      950 | 2024-05-17 | FearFerox                 | W   | 1.000      | -            | -                | -                | -         |     5.38 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           80 |      959 | 2024-05-17 | EXO Clan                  | W   | 1.000      | -            | -                | -                | -         |    12.31 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           79 |      980 | 2024-05-17 | Pera Esports              | L   | 1.000      | -            | -                | -                | -         |   -14.95 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           78 |      989 | 2024-05-17 | DASH                      | W   | 1.000      | -            | -                | -                | -         |     5.37 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           77 |     1001 | 2024-05-17 | VOLT                      | W   | 1.000      | -            | -                | -                | -         |     1.55 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           76 |     1052 | 2024-05-16 | The Last Resort           | W   | 1.000      | -            | -                | -                | -         |     6.67 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           75 |     1143 | 2024-05-15 | TopTab Club               | W   | 1.000      | -            | -                | -                | -         |     2.98 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           74 |     1159 | 2024-05-15 | Raptors Esports Club      | W   | 1.000      | -            | -                | -                | -         |    12.41 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           73 |     1196 | 2024-05-15 | Sangal Esports            | W   | 1.000      | 0.435        | 0.166 (0.072)    | 0.577 (0.251)    | -         |    21.52 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           72 |     1243 | 2024-05-14 | Team Invictum             | W   | 1.000      | -            | -                | -                | -         |     7.18 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           71 |     1274 | 2024-05-14 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -5.83 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           70 |     1333 | 2024-05-13 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -14.44 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           69 |     1348 | 2024-05-12 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |   -10.81 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           68 |     1390 | 2024-05-12 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |    -9.79 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           67 |     1422 | 2024-05-11 | V1dar Gaming              | W   | 1.000      | -            | -                | -                | -         |     9.31 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           66 |     1520 | 2024-05-10 | LEON Esports              | W   | 1.000      | -            | -                | -                | -         |     8.46 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           65 |     1531 | 2024-05-10 | Dynamo Eclot              | L   | 1.000      | -            | -                | -                | -         |   -12.94 | Diviiii, Ducky, Extinct, Girafffe, Vacancy  |
|           64 |     1535 | 2024-05-10 | GamerLegion Academy       | W   | 1.000      | 0.333        | 0.018 (0.006)    | 0.691 (0.230)    | -         |    12.99 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           63 |     1560 | 2024-05-09 | ROYALS                    | W   | 1.000      | -            | -                | -                | -         |     7.40 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           62 |     1657 | 2024-05-08 | Johnny Speeds             | W   | 1.000      | 0.333        | 0.056 (0.019)    | 0.683 (0.228)    | -         |    21.30 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           61 |     1665 | 2024-05-07 | Halal5                    | W   | 1.000      | -            | -                | -                | -         |     7.26 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           60 |     1698 | 2024-05-07 | RoundsGG                  | W   | 1.000      | -            | -                | -                | -         |     5.29 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           59 |     1738 | 2024-05-06 | LEON Esports              | L   | 1.000      | -            | -                | -                | -         |   -21.36 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           58 |     1779 | 2024-05-05 | Preasy Esport             | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.642 (0.214)    | -         |    12.08 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           57 |     1790 | 2024-05-05 | UNiTY esports             | W   | 1.000      | 0.333        | 0.021 (0.007)    | 0.766 (0.255)    | -         |    16.97 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           56 |     1844 | 2024-05-04 | Team Flow                 | L   | 1.000      | -            | -                | -                | -         |   -27.22 | AdamJC, arTisT, Ducky, Girafffe, Vacancy    |
|           55 |     1872 | 2024-05-03 | Part Timers               | W   | 1.000      | -            | -                | -                | -         |     8.34 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           54 |     1968 | 2024-05-01 | LOG Esports               | W   | 1.000      | -            | -                | -                | -         |     3.73 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           53 |     2070 | 2024-04-29 | Aurora Young Blud         | W   | 0.997      | 0.372        | 0.008 (0.003)    | 0.506 (0.188)    | -         |    13.06 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           52 |     2303 | 2024-04-25 | Lemondogs                 | L   | 0.971      | -            | -                | -                | -         |   -24.25 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           51 |     2332 | 2024-04-25 | ex-Turów Zgorzelec Esport | W   | 0.968      | -            | -                | -                | -         |     9.48 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           50 |     2408 | 2024-04-23 | Zero Tenacity             | L   | 0.957      | -            | -                | -                | -         |    -9.56 | arTisT, Diviiii, Ducky, Girafffe, Vacancy   |
|           49 |     2439 | 2024-04-22 | Kappa Bar                 | W   | 0.951      | -            | -                | -                | -         |     3.24 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           48 |     2820 | 2024-04-17 | BetBoom Team              | L   | 0.918      | -            | -                | -                | -         |    -2.13 | arTisT, Ducky, Girafffe, J3nsyy, Vacancy    |
|           47 |     2941 | 2024-04-15 | DMS                       | L   | 0.904      | -            | -                | -                | -         |   -16.47 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           46 |     2964 | 2024-04-15 | UNiTY esports             | L   | 0.902      | -            | -                | -                | -         |   -15.59 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           45 |     2990 | 2024-04-14 | Johnny Speeds             | L   | 0.896      | -            | -                | -                | -         |   -10.20 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           44 |     3092 | 2024-04-12 | Lilmix                    | W   | 0.881      | 0.333        | -                | 0.581 (0.171)    | -         |    10.02 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           43 |     3119 | 2024-04-11 | Lilmix                    | L   | 0.877      | -            | -                | -                | -         |   -18.05 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           42 |     3268 | 2024-04-09 | ROSOMAHA                  | W   | 0.862      | -            | -                | -                | -         |     3.48 | aidKiT, Ducky, Girafffe, Vacancy, Zax1e     |
|           41 |     3347 | 2024-04-07 | Lazer Cats                | L   | 0.849      | -            | -                | -                | -         |   -21.16 | Diviiii, Ducky, Girafffe, Vacancy, Zax1e    |
|           40 |     3409 | 2024-04-06 | BRUTE                     | W   | 0.842      | -            | -                | -                | -         |     2.54 | Diviiii, Ducky, Girafffe, Vacancy, Zax1e    |
|           39 |     3506 | 2024-04-04 | ex-K10                    | L   | 0.829      | -            | -                | -                | -         |   -17.94 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           38 |     3630 | 2024-04-01 | Reason Gaming             | W   | 0.809      | -            | -                | -                | 1 (0.809) |     7.12 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           37 |     3658 | 2024-03-31 | Ahoka                     | W   | 0.802      | -            | -                | -                | 1 (0.802) |     6.00 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           36 |     3674 | 2024-03-30 | p0dbots                   | W   | 0.797      | -            | -                | -                | 1 (0.797) |     3.60 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           35 |     3688 | 2024-03-30 | MAMMOTHS2                 | W   | 0.796      | -            | -                | -                | 1 (0.796) |     1.44 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           34 |     3793 | 2024-03-27 | Ninjas in Pyjamas         | L   | 0.778      | -            | -                | -                | -         |    -7.29 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           33 |     3807 | 2024-03-27 | Betera Esports            | W   | 0.777      | 0.143        | 0.023 (0.003)    | -                | -         |     9.49 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           32 |     3874 | 2024-03-26 | AMKAL ESPORTS             | W   | 0.771      | 0.143        | 0.146 (0.016)    | -                | -         |    18.56 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           31 |     4162 | 2024-03-19 | EXO Clan                  | L   | 0.725      | -            | -                | -                | -         |    -9.36 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           30 |     4547 | 2024-03-12 | Part Timers               | W   | 0.678      | -            | -                | -                | -         |     4.99 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           29 |     4721 | 2024-03-09 | ROYALS                    | W   | 0.656      | -            | -                | -                | -         |     4.80 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           28 |     4952 | 2024-03-05 | Dreams To Legends         | W   | 0.631      | -            | -                | -                | -         |     1.58 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           27 |     5248 | 2024-02-29 | Viperio                   | W   | 0.598      | -            | -                | -                | -         |     3.74 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           26 |     5250 | 2024-02-29 | ex-K10                    | L   | 0.598      | -            | -                | -                | -         |   -12.06 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           25 |     5271 | 2024-02-29 | The Chosen Few            | L   | 0.597      | -            | -                | -                | -         |   -13.57 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           24 |     5336 | 2024-02-28 | Sashi Esport              | L   | 0.589      | -            | -                | -                | -         |   -13.75 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           23 |     5451 | 2024-02-25 | Permitta Esports          | L   | 0.570      | -            | -                | -                | -         |    -8.72 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           22 |     5514 | 2024-02-24 | INGLORIOUS                | L   | 0.564      | -            | -                | -                | -         |   -13.39 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           21 |     5558 | 2024-02-24 | NOM Esports               | L   | 0.563      | -            | -                | -                | -         |   -15.58 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           20 |     5660 | 2024-02-22 | ex-Anonymo Esports        | W   | 0.550      | -            | -                | -                | -         |     3.18 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           19 |     5740 | 2024-02-21 | Sashi Esport              | L   | 0.542      | -            | -                | -                | -         |    -6.26 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           18 |     5762 | 2024-02-20 | MOUZ NXT                  | L   | 0.537      | -            | -                | -                | -         |    -6.08 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           17 |     6029 | 2024-02-15 | Team Invictum             | W   | 0.505      | -            | -                | -                | -         |     0.51 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           16 |     6145 | 2024-02-13 | Raptors Esports Club      | W   | 0.491      | -            | -                | -                | -         |     4.54 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           15 |     6256 | 2024-02-10 | Dynamo Eclot              | L   | 0.471      | -            | -                | -                | -         |    -5.71 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           14 |     6260 | 2024-02-10 | Lilmix                    | W   | 0.471      | -            | -                | -                | -         |     4.64 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           13 |     6267 | 2024-02-10 | esmagaB                   | W   | 0.470      | -            | -                | -                | -         |     4.36 | ArTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           12 |     6543 | 2024-02-03 | Endpoint                  | L   | 0.423      | -            | -                | -                | -         |    -7.80 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           11 |     6563 | 2024-02-03 | SRK                       | W   | 0.423      | -            | -                | -                | -         |     0.45 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|           10 |     6684 | 2024-02-01 | ROYALS                    | L   | 0.409      | -            | -                | -                | -         |   -12.09 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            9 |     6963 | 2024-01-27 | Sprout                    | L   | 0.377      | -            | -                | -                | -         |   -10.78 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            8 |     6975 | 2024-01-27 | Back2TheGame              | W   | 0.377      | -            | -                | -                | -         |     0.35 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            7 |     6993 | 2024-01-27 | Sashi Esport              | L   | 0.375      | -            | -                | -                | -         |    -5.55 | arTisT, Ducky, Girafffe, Vacancy, Zax1e     |
|            6 |     7569 | 2024-01-17 | ghoulsW                   | L   | 0.311      | -            | -                | -                | -         |    -9.33 | Ducky, Extinct, Girafffe, tvs, Vacancy      |
|            5 |     7639 | 2024-01-16 | Linx Legacy Madagaskar    | L   | 0.305      | -            | -                | -                | -         |    -9.14 | Ducky, Extinct, Girafffe, tvs, Vacancy      |
|            4 |     7667 | 2024-01-16 | kONO.ECF                  | W   | 0.304      | -            | -                | -                | -         |     2.54 | Ducky, Extinct, Girafffe, tvs, Vacancy      |
|            3 |     8955 | 2023-12-10 | ex-K10                    | L   | 0.058      | -            | -                | -                | -         |    -1.35 | arTisT, Ducky, Extinct, Girafffe, Wolfie    |
|            2 |     8987 | 2023-12-10 | ex-K10                    | W   | 0.056      | -            | -                | -                | 1 (0.056) |     0.45 | arTisT, Ducky, Extinct, Girafffe, Wolfie    |
|            1 |     9043 | 2023-12-09 | DuckDuckGOOSE             | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.07 | arTisT, Ducky, Extinct, Girafffe, Wolfie    |

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
