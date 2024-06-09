### Roster Details<br />
Team Name: Metizport<br />
Roster: abdi, adamb, Jackinho, nilo, Plopski<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [50](../standings_global.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
Final Rank Value:  1050.7<br />
<br />
Final Rank Value (1050.7) = Starting Rank Value (976.2) + Head To Head Adjustments (74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.487[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.191[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.283<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 976.2
- 400 + ( ( 0.283 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 976.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           87 |      428 | 2024-05-23 | Team Space             | L   | 1.000      | -            | -                | -                | -         |   -22.21 | abdi, adamb, Jackinho, nilo, Plopski |
|           86 |      674 | 2024-05-20 | Zero Tenacity          | L   | 1.000      | -            | -                | -                | -         |   -17.84 | adamb, Jackinho, nilo, Plopski, ztr  |
|           85 |      864 | 2024-05-18 | Ninjas in Pyjamas      | W   | 1.000      | 0.500        | 0.118 (0.059)    | 0.285 (0.142)    | 0 (0.000) |    16.86 | adamb, Jackinho, nilo, Plopski, ztr  |
|           84 |     1477 | 2024-05-11 | BetBoom Team           | L   | 1.000      | -            | -                | -                | -         |    -6.14 | adamb, Jackinho, nilo, Plopski, ztr  |
|           83 |     1525 | 2024-05-10 | EYEBALLERS             | W   | 1.000      | 0.435        | -                | 0.508 (0.221)    | 0 (0.000) |    10.57 | adamb, Jackinho, nilo, Plopski, ztr  |
|           82 |     1876 | 2024-05-04 | AMKAL ESPORTS          | L   | 1.000      | -            | -                | -                | -         |    -9.78 | adamb, Jackinho, nilo, susp, ztr     |
|           81 |     1920 | 2024-05-03 | Zero Tenacity          | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | 0 (0.000) |    14.21 | adamb, Jackinho, nilo, susp, ztr     |
|           80 |     1951 | 2024-05-02 | Sangal Esports         | W   | 1.000      | 0.435        | 0.166 (0.072)    | 0.658 (0.286)    | 0 (0.000) |    15.41 | adamb, Jackinho, nilo, susp, ztr     |
|           79 |     2348 | 2024-04-25 | Nexus Gaming           | L   | 0.970      | -            | -                | -                | -         |   -22.09 | adamb, Jackinho, nilo, susp, ztr     |
|           78 |     2475 | 2024-04-23 | Alliance               | W   | 0.956      | 0.384        | -                | 0.529 (0.195)    | 0 (0.000) |     8.20 | adamb, Jackinho, nilo, p1ke, susp    |
|           77 |     2769 | 2024-04-19 | FURIA Esports          | L   | 0.929      | -            | -                | -                | -         |    -4.18 | adamb, jackinho, Plopski, susp, ztr  |
|           76 |     2812 | 2024-04-18 | Imperial Esports       | L   | 0.924      | -            | -                | -                | -         |    -2.72 | adamb, jackinho, Plopski, susp, ztr  |
|           75 |     3334 | 2024-04-09 | ex-Guild Eagles        | L   | 0.863      | -            | -                | -                | -         |   -18.48 | adamb, Jackinho, nilo, susp, ztr     |
|           74 |     3358 | 2024-04-08 | Aurora Gaming          | L   | 0.858      | -            | -                | -                | -         |    -4.18 | adamb, jackinho, nilo, susp, ztr     |
|           73 |     3380 | 2024-04-08 | 9Pandas                | L   | 0.856      | -            | -                | -                | -         |   -11.01 | adamb, jackinho, nilo, susp, ztr     |
|           72 |     3412 | 2024-04-07 | EYEBALLERS             | W   | 0.850      | -            | -                | -                | 0 (0.000) |     7.13 | adamb, Jackinho, nilo, susp, ztr     |
|           71 |     3438 | 2024-04-07 | Johnny Speeds          | W   | 0.848      | -            | -                | -                | 0 (0.000) |     9.70 | adamb, Jackinho, nilo, susp, ztr     |
|           70 |     3493 | 2024-04-06 | Young Gods             | W   | 0.842      | -            | -                | -                | 0 (0.000) |     1.22 | adamb, Jackinho, nilo, susp, ztr     |
|           69 |     3594 | 2024-04-04 | Ninjas in Pyjamas      | L   | 0.829      | -            | -                | -                | -         |   -12.15 | adamb, jackinho, nilo, susp, ztr     |
|           68 |     3635 | 2024-04-03 | Monte                  | W   | 0.824      | 0.143        | 0.181 (0.021)    | -                | -         |    18.46 | adamb, jackinho, nilo, susp, ztr     |
|           67 |     3645 | 2024-04-03 | FAVBET Team            | W   | 0.823      | -            | -                | -                | -         |     8.77 | adamb, jackinho, nilo, susp, ztr     |
|           66 |     3684 | 2024-04-02 | B8                     | W   | 0.817      | 0.143        | 0.168 (0.020)    | 0.963 (0.112)    | -         |    16.10 | adamb, jackinho, nilo, susp, ztr     |
|           65 |     3695 | 2024-04-02 | Aurora Gaming          | L   | 0.816      | -            | -                | -                | -         |    -3.40 | adamb, jackinho, nilo, susp, ztr     |
|           64 |     3717 | 2024-04-01 | PARIVISION             | L   | 0.810      | -            | -                | -                | -         |   -17.42 | adamb, Jackinho, nilo, susp, ztr     |
|           63 |     3873 | 2024-03-27 | Aurora Gaming          | L   | 0.778      | -            | -                | -                | -         |    -3.26 | adamb, jackinho, nilo, susp, ztr     |
|           62 |     3881 | 2024-03-27 | Natus Vincere Junior   | W   | 0.778      | -            | -                | -                | -         |     5.76 | adamb, jackinho, nilo, susp, ztr     |
|           61 |     3894 | 2024-03-27 | TSM                    | W   | 0.777      | -            | -                | -                | -         |     4.05 | adamb, jackinho, nilo, susp, ztr     |
|           60 |     3975 | 2024-03-26 | Lausanne-Sport Esports | W   | 0.771      | -            | -                | -                | -         |     3.37 | adamb, jackinho, nilo, susp, ztr     |
|           59 |     4490 | 2024-03-15 | kONO.ECF               | L   | 0.697      | -            | -                | -                | -         |   -15.26 | adamb, Jackinho, nilo, susp, ztr     |
|           58 |     4552 | 2024-03-14 | ALTERNATE aTTaX        | L   | 0.690      | -            | -                | -                | -         |   -15.75 | adamb, Jackinho, nilo, susp, ztr     |
|           57 |     4614 | 2024-03-13 | HEROIC                 | L   | 0.683      | -            | -                | -                | -         |    -0.67 | adamb, Jackinho, nilo, susp, ztr     |
|           56 |     4668 | 2024-03-12 | B8                     | W   | 0.678      | 0.143        | 0.168 (0.016)    | -                | -         |    12.18 | adamb, Jackinho, nilo, susp, ztr     |
|           55 |     4682 | 2024-03-12 | Apeks                  | W   | 0.677      | -            | -                | -                | -         |    15.67 | adamb, Jackinho, nilo, susp, ztr     |
|           54 |     4722 | 2024-03-11 | ex-Preasy Esport       | W   | 0.671      | -            | -                | -                | -         |     8.91 | adamb, Jackinho, nilo, susp, ztr     |
|           53 |     4745 | 2024-03-11 | ENCE                   | L   | 0.670      | -            | -                | -                | -         |    -1.99 | adamb, Jackinho, nilo, susp, ztr     |
|           52 |     4770 | 2024-03-10 | Team Spirit            | L   | 0.665      | -            | -                | -                | -         |    -0.17 | adamb, Jackinho, nilo, susp, ztr     |
|           51 |     4837 | 2024-03-09 | Monte                  | W   | 0.657      | 0.535        | 0.181 (0.064)    | 0.387 (0.136)    | -         |    16.66 | adamb, Jackinho, nilo, susp, ztr     |
|           50 |     4844 | 2024-03-09 | EYEBALLERS             | L   | 0.656      | -            | -                | -                | -         |   -13.97 | adamb, Jackinho, nilo, susp, ztr     |
|           49 |     4850 | 2024-03-09 | Lemondogs              | W   | 0.656      | -            | -                | -                | -         |     1.64 | adamb, Jackinho, nilo, susp, ztr     |
|           48 |     4858 | 2024-03-09 | Skillz of Boras        | W   | 0.656      | -            | -                | -                | -         |     0.51 | adamb, Jackinho, nilo, susp, ztr     |
|           47 |     4885 | 2024-03-08 | Team Secret            | W   | 0.649      | -            | -                | -                | -         |     1.75 | adamb, Jackinho, nilo, susp, ztr     |
|           46 |     4982 | 2024-03-06 | Team Falcons           | W   | 0.638      | 0.535        | 0.355 (0.121)    | -                | -         |    18.51 | adamb, Jackinho, nilo, susp, ztr     |
|           45 |     5211 | 2024-03-03 | The Chosen Few         | W   | 0.618      | -            | -                | -                | -         |     4.26 | adamb, Jackinho, nilo, susp, ztr     |
|           44 |     5220 | 2024-03-03 | ILIN                   | W   | 0.618      | -            | -                | -                | -         |     1.90 | adamb, Jackinho, nilo, susp, ztr     |
|           43 |     5233 | 2024-03-03 | RUSH B                 | W   | 0.617      | -            | -                | -                | -         |     3.80 | adamb, Jackinho, nilo, susp, ztr     |
|           42 |     5254 | 2024-03-03 | Dynamo Eclot           | L   | 0.616      | -            | -                | -                | -         |    -7.81 | adamb, Jackinho, nilo, susp, ztr     |
|           41 |     5269 | 2024-03-02 | FORZE Esports          | W   | 0.612      | -            | -                | -                | -         |     9.70 | adamb, Jackinho, nilo, susp, ztr     |
|           40 |     5283 | 2024-03-02 | Dynamo Eclot           | W   | 0.611      | -            | -                | -                | -         |    12.07 | adamb, Jackinho, nilo, susp, ztr     |
|           39 |     5436 | 2024-02-29 | Endpoint               | W   | 0.596      | 0.384        | -                | 0.770 (0.176)    | -         |     7.04 | adamb, Jackinho, nilo, susp, ztr     |
|           38 |     5491 | 2024-02-28 | INGLORIOUS             | W   | 0.589      | -            | -                | -                | -         |     4.31 | adamb, Jackinho, nilo, susp, ztr     |
|           37 |     5517 | 2024-02-27 | ex-Guild Eagles        | L   | 0.584      | -            | -                | -                | -         |    -9.40 | adamb, Jackinho, nilo, susp, ztr     |
|           36 |     5551 | 2024-02-26 | Sashi Esport           | W   | 0.578      | -            | -                | -                | -         |     3.69 | adamb, Jackinho, nilo, susp, ztr     |
|           35 |     6416 | 2024-02-11 | Apeks                  | W   | 0.478      | -            | -                | -                | -         |    12.02 | adamb, Jackinho, nilo, susp, ztr     |
|           34 |     6452 | 2024-02-10 | FURIA Esports          | W   | 0.471      | -            | -                | -                | -         |    13.60 | adamb, Jackinho, nilo, susp, ztr     |
|           33 |     6462 | 2024-02-10 | Apeks                  | L   | 0.470      | -            | -                | -                | -         |    -2.82 | adamb, Jackinho, nilo, susp, ztr     |
|           32 |     6464 | 2024-02-10 | FURIA Esports          | W   | 0.470      | -            | -                | -                | -         |    13.72 | adamb, Jackinho, nilo, susp, ztr     |
|           31 |     6555 | 2024-02-07 | Sprout                 | W   | 0.450      | -            | -                | -                | -         |     2.16 | adamb, Jackinho, nilo, susp, ztr     |
|           30 |     6579 | 2024-02-06 | Into The Breach        | L   | 0.443      | -            | -                | -                | -         |   -10.49 | adamb, Jackinho, nilo, susp, ztr     |
|           29 |     6638 | 2024-02-05 | TSM                    | L   | 0.436      | -            | -                | -                | -         |   -10.58 | adamb, Jackinho, nilo, susp, ztr     |
|           28 |     6653 | 2024-02-04 | 500                    | L   | 0.431      | -            | -                | -                | -         |   -10.08 | adamb, Jackinho, nilo, susp, ztr     |
|           27 |     6658 | 2024-02-04 | TOOMUCHVIDEOGAMES      | W   | 0.431      | -            | -                | -                | -         |     0.97 | adamb, Jackinho, nilo, susp, ztr     |
|           26 |     6680 | 2024-02-04 | DUSTY                  | W   | 0.429      | -            | -                | -                | -         |     2.32 | adamb, Jackinho, nilo, susp, ztr     |
|           25 |     6777 | 2024-02-03 | Sangal Esports         | W   | 0.422      | 0.371        | 0.166 (0.026)    | -                | -         |     8.52 | adamb, Jackinho, nilo, susp, ztr     |
|           24 |     6790 | 2024-02-02 | EYEBALLERS             | W   | 0.418      | -            | -                | -                | -         |     5.43 | adamb, Jackinho, nilo, susp, ztr     |
|           23 |     6793 | 2024-02-02 | ex-Preasy Esport       | W   | 0.418      | -            | -                | -                | -         |     5.63 | adamb, Jackinho, nilo, susp, ztr     |
|           22 |     6798 | 2024-02-02 | Alliance               | W   | 0.417      | -            | -                | -                | -         |     4.24 | adamb, Jackinho, nilo, susp, ztr     |
|           21 |     6818 | 2024-02-02 | 777 Esports            | W   | 0.417      | -            | -                | -                | -         |     2.97 | adamb, Jackinho, nilo, susp, ztr     |
|           20 |     6892 | 2024-02-01 | Team Sampi             | W   | 0.409      | 0.384        | -                | 0.677 (0.106)    | -         |     6.06 | adamb, Jackinho, nilo, susp, ztr     |
|           19 |     7009 | 2024-01-29 | Dynamo Eclot           | L   | 0.392      | -            | -                | -                | -         |    -4.17 | adamb, Jackinho, nilo, susp, ztr     |
|           18 |     7029 | 2024-01-29 | premghouls             | W   | 0.392      | -            | -                | -                | -         |     0.50 | adamb, Jackinho, nilo, susp, ztr     |
|           17 |     7057 | 2024-01-29 | BLEED Esports          | W   | 0.389      | 0.371        | 0.248 (0.036)    | 0.714 (0.103)    | -         |    10.12 | adamb, Jackinho, nilo, susp, ztr     |
|           16 |     7316 | 2024-01-25 | BIG Academy            | W   | 0.362      | -            | -                | -                | -         |     2.62 | adamb, Jackinho, nilo, susp, ztr     |
|           15 |     7923 | 2024-01-16 | 9INE                   | L   | 0.304      | -            | -                | -                | -         |    -8.65 | adamb, Jackinho, nilo, susp, ztr     |
|           14 |     8341 | 2024-01-09 | IKLA                   | L   | 0.257      | -            | -                | -                | -         |    -7.36 | adamb, Jackinho, nilo, susp, ztr     |
|           13 |     8375 | 2024-01-09 | b52team                | W   | 0.257      | -            | -                | -                | -         |     0.32 | adamb, Jackinho, nilo, susp, ztr     |
|           12 |     8555 | 2023-12-30 | The Witchers           | L   | 0.190      | -            | -                | -                | -         |    -4.84 | adamb, Jackinho, nilo, susp, ztr     |
|           11 |     8557 | 2023-12-30 | VP.Prodigy             | W   | 0.189      | -            | -                | -                | -         |     2.04 | adamb, Jackinho, nilo, susp, ztr     |
|           10 |     8565 | 2023-12-29 | Aurora Young Blud      | W   | 0.184      | -            | -                | -                | -         |     1.58 | adamb, Jackinho, nilo, susp, ztr     |
|            9 |     8566 | 2023-12-29 | esmagaB                | W   | 0.183      | -            | -                | -                | -         |     1.98 | adamb, Jackinho, nilo, susp, ztr     |
|            8 |     8574 | 2023-12-27 | Aurora Young Blud      | L   | 0.170      | -            | -                | -                | -         |    -3.89 | adamb, Jackinho, nilo, susp, ztr     |
|            7 |     8638 | 2023-12-20 | Pera Esports           | L   | 0.124      | -            | -                | -                | -         |    -2.28 | adamb, Jackinho, nilo, susp, ztr     |
|            6 |     8641 | 2023-12-20 | ARCRED                 | W   | 0.123      | -            | -                | -                | -         |     0.95 | adamb, Jackinho, nilo, susp, ztr     |
|            5 |     8657 | 2023-12-19 | GUN5 Esports           | W   | 0.116      | -            | -                | -                | -         |     0.28 | adamb, Jackinho, nilo, susp, ztr     |
|            4 |     8660 | 2023-12-19 | Pera Esports           | W   | 0.116      | -            | -                | -                | -         |     1.52 | adamb, Jackinho, nilo, susp, ztr     |
|            3 |     8708 | 2023-12-17 | Lilmix                 | W   | 0.104      | -            | -                | -                | 1 (0.104) |     0.29 | adamb, Jackinho, nilo, susp, ztr     |
|            2 |     8732 | 2023-12-17 | angelnumbers           | L   | 0.103      | -            | -                | -                | -         |    -2.81 | adamb, Jackinho, nilo, susp, ztr     |
|            1 |     8746 | 2023-12-17 | latch gibb             | W   | 0.102      | -            | -                | -                | 1 (0.102) |     0.19 | adamb, Jackinho, nilo, susp, ztr     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,472.88)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-20 |      0.938 | $5,000.00      | $4,689.81       |
| 2024-04-07 |      0.850 | $6,087.86      | $5,176.37       |
| 2024-03-10 |      0.665 | $12,500.00     | $8,306.42       |
| 2023-12-30 |      0.190 | $5,000.00      | $950.00         |
| 2023-12-20 |      0.124 | $2,000.00      | $247.78         |
| 2023-12-17 |      0.104 | $981.34        | $102.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
