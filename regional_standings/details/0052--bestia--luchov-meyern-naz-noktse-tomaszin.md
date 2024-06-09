### Roster Details<br />
Team Name: BESTIA<br />
Roster: luchov, meyern, naz, Noktse, tomaszin<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [52](../standings_global.md)<br />
Regional Rank: [12]( ../standings_americas.md)<br />
Final Rank Value:  1042.9<br />
<br />
Final Rank Value (1042.9) = Starting Rank Value (949.7) + Head To Head Adjustments (93.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.461[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.270<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 949.7
- 400 + ( ( 0.270 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 949.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           70 |       29 | 2024-05-29 | inSanitY Sports           | L   | 1.000      | -            | -                | -                | -         |   -26.81 | luchov, meyern, naz, Noktse, tomaszin  |
|           69 |       36 | 2024-05-29 | w7m esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           68 |      444 | 2024-05-22 | Case Esports              | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.470 (0.212)    | 0 (0.000) |     9.27 | luchov, meyern, naz, Noktse, tomaszin  |
|           67 |      448 | 2024-05-22 | Case Esports              | W   | 1.000      | 0.450        | 0.028 (0.013)    | -                | 0 (0.000) |     9.99 | luchov, meyern, naz, Noktse, tomaszin  |
|           66 |      453 | 2024-05-22 | Fluxo                     | W   | 1.000      | 0.450        | 0.065 (0.029)    | 0.474 (0.213)    | 0 (0.000) |    17.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           65 |      463 | 2024-05-22 | Fluxo                     | W   | 1.000      | 0.450        | 0.065 (0.029)    | 0.474 (0.213)    | 0 (0.000) |    19.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           64 |      547 | 2024-05-21 | 2Game Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           63 |      552 | 2024-05-21 | 2Game Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.85 | luchov, meyern, naz, Noktse, tomaszin  |
|           62 |      555 | 2024-05-21 | Imperial Esports          | W   | 1.000      | 0.450        | 0.372 (0.167)    | 0.582 (0.262)    | 0 (0.000) |    28.54 | luchov, meyern, naz, Noktse, tomaszin  |
|           61 |      573 | 2024-05-21 | Imperial Esports          | W   | 1.000      | 0.450        | 0.372 (0.167)    | 0.582 (0.262)    | 0 (0.000) |    29.30 | luchov, meyern, naz, Noktse, tomaszin  |
|           60 |      653 | 2024-05-20 | Corinthians Esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.08 | luchov, meyern, naz, Noktse, tomaszin  |
|           59 |      655 | 2024-05-20 | 9z Team                   | W   | 1.000      | 0.450        | 0.107 (0.048)    | 0.547 (0.246)    | -         |    26.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           58 |      670 | 2024-05-20 | 9z Team                   | L   | 1.000      | -            | -                | -                | -         |    -4.44 | luchov, meyern, naz, Noktse, tomaszin  |
|           57 |     1138 | 2024-05-15 | ODDIK                     | W   | 1.000      | 0.450        | -                | 0.494 (0.222)    | -         |    16.38 | luchov, meyern, naz, Noktse, tomaszin  |
|           56 |     1141 | 2024-05-15 | ODDIK                     | W   | 1.000      | 0.450        | -                | 0.494 (0.222)    | -         |    17.88 | luchov, meyern, naz, Noktse, tomaszin  |
|           55 |     1163 | 2024-05-15 | Hype Esports              | L   | 1.000      | -            | -                | -                | -         |   -24.47 | luchov, meyern, naz, Noktse, tomaszin  |
|           54 |     1247 | 2024-05-14 | Imperial Esports          | L   | 1.000      | -            | -                | -                | -         |    -1.70 | luchov, meyern, naz, Noktse, tomaszin  |
|           53 |     1265 | 2024-05-14 | RED Canids                | L   | 1.000      | -            | -                | -                | -         |    -9.86 | luchov, meyern, naz, Noktse, tomaszin  |
|           52 |     1365 | 2024-05-12 | O Plano                   | W   | 1.000      | -            | -                | -                | -         |     3.51 | luchov, meyern, naz, Noktse, tomaszin  |
|           51 |     1436 | 2024-05-11 | paiN Gaming               | L   | 1.000      | -            | -                | -                | -         |    -1.26 | luchov, meyern, naz, Noktse, tomaszin  |
|           50 |     1510 | 2024-05-10 | Imperial Esports          | W   | 1.000      | 0.435        | 0.372 (0.162)    | 0.582 (0.253)    | -         |    29.98 | luchov, meyern, naz, Noktse, tomaszin  |
|           49 |     1562 | 2024-05-09 | Sharks Esports            | W   | 1.000      | -            | -                | -                | -         |    18.71 | luchov, meyern, naz, Noktse, tomaszin  |
|           48 |     1640 | 2024-05-08 | Vikings KR                | W   | 1.000      | -            | -                | -                | -         |    10.23 | luchov, meyern, naz, Noktse, tomaszin  |
|           47 |     1723 | 2024-05-06 | Sharks Esports            | L   | 1.000      | -            | -                | -                | -         |   -11.87 | luchov, meyern, naz, Noktse, tomaszin  |
|           46 |     1882 | 2024-05-03 | KRÜ Esports               | L   | 1.000      | -            | -                | -                | -         |   -18.13 | luchov, meyern, naz, Noktse, tomaszin  |
|           45 |     1929 | 2024-05-02 | KRÜ Esports               | W   | 1.000      | -            | -                | -                | -         |    12.68 | luchov, meyern, naz, Noktse, tomaszin  |
|           44 |     1935 | 2024-05-02 | Dusty Roots               | W   | 1.000      | -            | -                | -                | -         |     8.39 | luchov, meyern, naz, Noktse, tomaszin  |
|           43 |     1969 | 2024-05-01 | w7m esports               | W   | 1.000      | -            | -                | -                | -         |    12.22 | luchov, meyern, naz, Noktse, tomaszin  |
|           42 |     1975 | 2024-05-01 | inSanitY Sports           | W   | 1.000      | -            | -                | -                | -         |     8.66 | luchov, meyern, naz, Noktse, tomaszin  |
|           41 |     2333 | 2024-04-25 | RED Canids                | L   | 0.972      | -            | -                | -                | -         |    -7.60 | luchov, meyern, naz, Noktse, tomaszin  |
|           40 |     2334 | 2024-04-25 | RED Canids                | L   | 0.972      | -            | -                | -                | -         |    -8.11 | luchov, meyern, naz, Noktse, tomaszin  |
|           39 |     2949 | 2024-04-16 | O Plano                   | L   | 0.912      | -            | -                | -                | -         |   -25.01 | luchov, meyern, naz, Noktse, tomaszin  |
|           38 |     3183 | 2024-04-11 | Galorys                   | L   | 0.877      | -            | -                | -                | -         |   -15.24 | luchov, meyern, naz, Noktse, tomaszin  |
|           37 |     3301 | 2024-04-09 | Galorys                   | L   | 0.865      | -            | -                | -                | -         |   -16.18 | luchov, meyern, naz, Noktse, tomaszin  |
|           36 |     3303 | 2024-04-09 | Galorys                   | W   | 0.865      | 0.450        | -                | 0.600 (0.233)    | -         |    11.02 | luchov, meyern, naz, Noktse, tomaszin  |
|           35 |     3356 | 2024-04-08 | RED Canids                | L   | 0.858      | -            | -                | -                | -         |    -9.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           34 |     3425 | 2024-04-07 | Sharks Esports            | L   | 0.849      | -            | -                | -                | -         |   -19.89 | luchov, meyern, naz, Noktse, tomaszin  |
|           33 |     3447 | 2024-04-06 | Fluxo                     | W   | 0.845      | -            | -                | -                | -         |    17.59 | luchov, meyern, naz, Noktse, tomaszin  |
|           32 |     3554 | 2024-04-04 | adalYamigos               | L   | 0.832      | -            | -                | -                | -         |   -19.41 | luchov, meyern, naz, Noktse, tomaszin  |
|           31 |     3564 | 2024-04-04 | adalYamigos               | W   | 0.832      | -            | -                | -                | -         |     6.58 | luchov, meyern, naz, Noktse, tomaszin  |
|           30 |     3573 | 2024-04-04 | Imperial Esports          | L   | 0.831      | -            | -                | -                | -         |    -1.09 | luchov, meyern, naz, Noktse, tomaszin  |
|           29 |     3625 | 2024-04-03 | Fluxo                     | L   | 0.824      | -            | -                | -                | -         |    -9.95 | luchov, meyern, naz, Noktse, tomaszin  |
|           28 |     3672 | 2024-04-02 | Sharks Esports            | W   | 0.819      | -            | -                | -                | -         |     5.67 | luchov, meyern, naz, Noktse, tomaszin  |
|           27 |     3678 | 2024-04-02 | Fluxo                     | L   | 0.818      | -            | -                | -                | -         |   -10.32 | luchov, meyern, naz, Noktse, tomaszin  |
|           26 |     4703 | 2024-03-11 | FURIA Academy             | W   | 0.672      | -            | -                | -                | -         |     2.44 | deco, luchov, meyern, Noktse, tomaszin |
|           25 |     4764 | 2024-03-10 | adalYamigos               | L   | 0.666      | -            | -                | -                | -         |   -16.17 | deco, luchov, meyern, Noktse, tomaszin |
|           24 |     4870 | 2024-03-08 | FURIA Academy             | W   | 0.652      | -            | -                | -                | -         |     2.17 | deco, luchov, meyern, Noktse, tomaszin |
|           23 |     5321 | 2024-03-02 | Wildcard Gaming           | L   | 0.611      | -            | -                | -                | -         |   -10.69 | deco, luchov, meyern, Noktse, tomaszin |
|           22 |     5366 | 2024-03-01 | Team Liquid               | L   | 0.605      | -            | -                | -                | -         |    -0.44 | deco, luchov, meyern, Noktse, tomaszin |
|           21 |     5691 | 2024-02-24 | Imperial Esports          | L   | 0.564      | -            | -                | -                | -         |    -0.89 | deco, luchov, meyern, Noktse, tomaszin |
|           20 |     5759 | 2024-02-23 | 9z Team                   | L   | 0.558      | -            | -                | -                | -         |    -3.10 | deco, luchov, meyern, Noktse, tomaszin |
|           19 |     5788 | 2024-02-22 | Imperial Esports          | W   | 0.552      | 0.143        | 0.372 (0.029)    | -                | -         |    16.62 | deco, luchov, meyern, Noktse, tomaszin |
|           18 |     5799 | 2024-02-22 | 9z Team                   | L   | 0.551      | -            | -                | -                | -         |    -2.85 | deco, luchov, meyern, Noktse, tomaszin |
|           17 |     5866 | 2024-02-21 | w7m esports               | W   | 0.544      | -            | -                | -                | -         |     5.60 | deco, luchov, meyern, Noktse, tomaszin |
|           16 |     6044 | 2024-02-18 | FURIA Academy             | W   | 0.524      | -            | -                | -                | -         |     1.81 | deco, luchov, meyern, Noktse, tomaszin |
|           15 |     6143 | 2024-02-16 | Case Esports              | L   | 0.512      | -            | -                | -                | -         |    -9.72 | deco, luchov, meyern, Noktse, tomaszin |
|           14 |     6372 | 2024-02-12 | FURIA Academy             | W   | 0.486      | -            | -                | -                | -         |     1.55 | deco, luchov, meyern, Noktse, tomaszin |
|           13 |     6780 | 2024-02-02 | Imperial Esports          | L   | 0.420      | -            | -                | -                | -         |    -0.55 | deco, luchov, meyern, Noktse, tomaszin |
|           12 |     6782 | 2024-02-02 | ODDIK                     | W   | 0.419      | -            | -                | -                | -         |     6.40 | deco, luchov, meyern, Noktse, tomaszin |
|           11 |     6786 | 2024-02-02 | Imperial Esports          | L   | 0.419      | -            | -                | -                | -         |    -0.51 | deco, luchov, meyern, Noktse, tomaszin |
|           10 |     7406 | 2024-01-23 | Imperial Esports          | L   | 0.352      | -            | -                | -                | -         |    -0.41 | deco, luchov, meyern, Noktse, tomaszin |
|            9 |     7441 | 2024-01-22 | Arena Jogue Fácil Esports | W   | 0.346      | -            | -                | -                | -         |     1.40 | deco, luchov, meyern, Noktse, tomaszin |
|            8 |     7505 | 2024-01-21 | w7m esports               | W   | 0.338      | -            | -                | -                | -         |     2.94 | deco, luchov, meyern, Noktse, tomaszin |
|            7 |     7555 | 2024-01-20 | MIBR                      | L   | 0.331      | -            | -                | -                | -         |    -0.28 | deco, luchov, meyern, Noktse, tomaszin |
|            6 |     7632 | 2024-01-19 | Imperial Esports          | W   | 0.326      | 0.143        | 0.372 (0.017)    | -                | -         |     9.91 | deco, luchov, meyern, Noktse, tomaszin |
|            5 |     7636 | 2024-01-19 | Flamengo Esports          | W   | 0.325      | -            | -                | -                | -         |     1.01 | deco, luchov, meyern, Noktse, tomaszin |
|            4 |     7952 | 2024-01-15 | TIMACETA                  | L   | 0.299      | -            | -                | -                | -         |    -8.01 | deco, luchov, meyern, Noktse, tomaszin |
|            3 |     7998 | 2024-01-14 | Sharks Esports            | L   | 0.292      | -            | -                | -                | -         |    -5.32 | deco, luchov, meyern, Noktse, tomaszin |
|            2 |     8000 | 2024-01-14 | w7m esports               | W   | 0.292      | -            | -                | -                | -         |     2.46 | deco, luchov, meyern, Noktse, tomaszin |
|            1 |     8027 | 2024-01-13 | Intense Game              | W   | 0.286      | -            | -                | -                | -         |     1.12 | deco, luchov, meyern, Noktse, tomaszin |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,856.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-02-25 |      0.571 | $5,000.00      | $2,856.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
