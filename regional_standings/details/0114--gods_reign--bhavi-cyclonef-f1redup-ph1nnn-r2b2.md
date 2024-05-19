### Roster Details<br />
Team Name: Gods Reign<br />
Roster: Bhavi, CycloneF, f1redup, Ph1NNN, R2B2<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [114](../standings_global.md)<br />
Regional Rank: [14]( ../standings_asia.md)<br />
Final Rank Value:  829.4<br />
<br />
Final Rank Value (829.4) = Starting Rank Value (973.5) + Head To Head Adjustments (-144.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.568[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.191[<sup>2</sup>](#table1)

The average of these factors is 0.289<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.5
- 400 + ( ( 0.289 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 973.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |      838 | 2024-04-19 | -72C                        | L   | 1.000      | -            | -                | -                | -         |   -15.93 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           52 |      843 | 2024-04-19 | -72C                        | L   | 1.000      | -            | -                | -                | -         |   -17.40 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           51 |     1011 | 2024-04-16 | DEWA United                 | L   | 1.000      | -            | -                | -                | -         |   -26.64 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           50 |     1223 | 2024-04-10 | BIG                         | L   | 1.000      | -            | -                | -                | -         |    -1.57 | Bhavi, f1redup, Ph1NNN, R2B2, yOOm             |
|           49 |     1286 | 2024-04-09 | Ninjas in Pyjamas           | L   | 1.000      | -            | -                | -                | -         |    -5.71 | Bhavi, f1redup, Ph1NNN, R2B2, yOOm             |
|           48 |     1545 | 2024-04-03 | Born In Far East            | L   | 0.984      | -            | -                | -                | -         |   -25.38 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           47 |     1549 | 2024-04-03 | Born In Far East            | W   | 0.984      | 0.417        | 0.003 (0.001)    | 0.138 (0.056)    | 0 (0.000) |     5.15 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           46 |     1627 | 2024-03-31 | True Rippers                | W   | 0.963      | 0.143        | 0.059 (0.008)    | 0.272 (0.037)    | 0 (0.000) |    12.15 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           45 |     1674 | 2024-03-29 | Marcos Gaming               | W   | 0.950      | -            | -                | -                | 0 (0.000) |     9.36 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           44 |     1700 | 2024-03-28 | Carnival Gaming             | W   | 0.944      | 0.143        | 0.013 (0.002)    | -                | 0 (0.000) |     8.63 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           43 |     1709 | 2024-03-28 | Crescent (Indian team)      | W   | 0.943      | -            | -                | -                | 0 (0.000) |     1.97 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           42 |     1870 | 2024-03-24 | Marcos Gaming               | W   | 0.916      | 0.262        | -                | 0.118 (0.028)    | 0 (0.000) |     9.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           41 |     1871 | 2024-03-23 | Grayfox Esports             | W   | 0.915      | 0.262        | 0.010 (0.002)    | 0.264 (0.063)    | 0 (0.000) |     7.11 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           40 |     2181 | 2024-03-16 | Aurora Gaming               | L   | 0.864      | -            | -                | -                | -         |    -0.74 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           39 |     2188 | 2024-03-15 | Bad News Kangaroos          | W   | 0.862      | 0.435        | 0.071 (0.027)    | 0.238 (0.089)    | 1 (0.862) |    16.75 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           38 |     2230 | 2024-03-15 | Aurora Gaming               | L   | 0.856      | -            | -                | -                | -         |    -0.68 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           37 |     2283 | 2024-03-14 | Garuda Wisnu Voyage         | W   | 0.850      | 0.435        | 0.014 (0.005)    | -                | 1 (0.850) |     4.47 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           36 |     2640 | 2024-03-06 | LYG Gaming                  | L   | 0.797      | -            | -                | -                | -         |   -17.06 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           35 |     2648 | 2024-03-06 | LYG Gaming                  | W   | 0.797      | 0.417        | 0.004 (0.001)    | 0.380 (0.126)    | 0 (0.000) |     7.93 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           34 |     2710 | 2024-03-05 | Marcos Gaming               | W   | 0.790      | -            | -                | -                | -         |     8.30 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           33 |     2772 | 2024-03-04 | Grayfox Esports             | W   | 0.783      | 0.143        | 0.010 (0.001)    | 0.264 (0.030)    | -         |     7.00 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           32 |     2818 | 2024-03-03 | Crescent (Indian team)      | W   | 0.776      | -            | -                | -                | -         |     1.98 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           31 |     2885 | 2024-03-02 | Marcos Gaming               | L   | 0.771      | -            | -                | -                | -         |   -16.66 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           30 |     2895 | 2024-03-02 | RETALIATION                 | W   | 0.770      | -            | -                | -                | -         |     1.74 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           29 |     3115 | 2024-02-25 | Grayfox Esports             | W   | 0.729      | 0.262        | 0.010 (0.002)    | 0.264 (0.050)    | -         |     6.73 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           28 |     3313 | 2024-02-21 | ATOX Esports                | L   | 0.704      | -            | -                | -                | -         |    -5.12 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           27 |     3321 | 2024-02-21 | ATOX Esports                | W   | 0.704      | 0.417        | 0.112 (0.033)    | 0.769 (0.226)    | -         |    17.46 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           26 |     3369 | 2024-02-20 | The QUBE Esports            | L   | 0.697      | -            | -                | -                | -         |   -11.65 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           25 |     3372 | 2024-02-20 | The QUBE Esports            | L   | 0.697      | -            | -                | -                | -         |   -12.39 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           24 |     3909 | 2024-02-05 | GR Gaming                   | L   | 0.596      | -            | -                | -                | -         |   -10.22 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           23 |     4054 | 2024-02-02 | Marcos Gaming               | L   | 0.576      | -            | -                | -                | -         |   -10.98 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           22 |     4126 | 2024-01-31 | True Rippers                | L   | 0.563      | -            | -                | -                | -         |    -9.37 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           21 |     4130 | 2024-01-30 | Aravt                       | L   | 0.562      | -            | -                | -                | -         |   -15.19 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           20 |     4197 | 2024-01-29 | Firedup Gaming              | W   | 0.551      | -            | -                | -                | -         |     1.72 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           19 |     4285 | 2024-01-27 | Enigma Gaming               | L   | 0.537      | -            | -                | -                | -         |   -13.54 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           18 |     4398 | 2024-01-24 | LYG Gaming                  | L   | 0.517      | -            | -                | -                | -         |   -11.44 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           17 |     4510 | 2024-01-21 | Troublemakers (Kyrgyz team) | L   | 0.497      | -            | -                | -                | -         |   -12.96 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           16 |     4518 | 2024-01-20 | Myth Avenue Gaming          | L   | 0.495      | -            | -                | -                | -         |   -12.19 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           15 |     4615 | 2024-01-19 | SR Nacague                  | W   | 0.483      | -            | -                | -                | -         |     1.14 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           14 |     4622 | 2024-01-19 | RESILIENCE                  | W   | 0.482      | -            | -                | -                | -         |     0.65 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           13 |     4745 | 2024-01-17 | Myth Avenue Gaming          | W   | 0.471      | 0.143        | -                | 0.302 (0.020)    | -         |     3.23 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           12 |     4748 | 2024-01-17 | SR Nacague                  | W   | 0.471      | -            | -                | -                | -         |     1.15 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           11 |     4753 | 2024-01-17 | Drippy Lab                  | W   | 0.470      | -            | -                | -                | -         |     0.67 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           10 |     5378 | 2023-12-17 | MIRAI Gaming                | L   | 0.264      | -            | -                | -                | -         |    -6.66 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            9 |     5401 | 2023-12-17 | Marcos Gaming               | L   | 0.263      | -            | -                | -                | -         |    -5.62 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            8 |     5407 | 2023-12-16 | IKARI                       | W   | 0.262      | -            | -                | -                | -         |     0.34 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            7 |     5590 | 2023-12-15 | Born In Far East            | L   | 0.250      | -            | -                | -                | -         |    -6.14 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            6 |     5734 | 2023-12-10 | RAVENS (Japanese team)      | W   | 0.217      | -            | -                | -                | -         |     0.28 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            5 |     5776 | 2023-12-09 | MIRAI Gaming                | L   | 0.210      | -            | -                | -                | -         |    -5.43 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            4 |     5846 | 2023-12-08 | Guardian 5                  | W   | 0.204      | -            | -                | -                | -         |     0.25 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            3 |     6412 | 2023-11-25 | True Rippers                | L   | 0.122      | -            | -                | -                | -         |    -2.54 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            2 |     7109 | 2023-11-10 | Direct GharPe               | W   | 0.016      | -            | -                | -                | -         |     0.02 | Bhavi, Catastr0phE, Elvis, f1redup, R2B2       |
|            1 |     7205 | 2023-11-08 | Carnival Gaming             | L   | 0.004      | -            | -                | -                | -         |    -0.09 | Benzene, hattygOD, N1kace, Rider, SpawN        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,573.81)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.17) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-03-24 |      0.916 | $1,000.00      | $915.74         |
| 2024-03-16 |      0.864 | $12,500.00     | $10,794.56      |
| 2024-02-25 |      0.729 | $1,000.00      | $729.12         |
| 2023-12-17 |      0.263 | $500.00        | $131.47         |
| 2023-11-10 |      0.016 | $180.07        | $2.92           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
