### Roster Details<br />
Team Name: SINNERS Esports<br />
Roster: AJTT, beastik, NEOFRAG, oskar, SHOCK<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [64](../standings_global.md)<br />
Regional Rank: [48]( ../standings_europe.md)<br />
Final Rank Value:  946.3<br />
<br />
Final Rank Value (946.3) = Starting Rank Value (989.6) + Head To Head Adjustments (-43.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.383[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.193[<sup>2</sup>](#table1)

The average of these factors is 0.297<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 989.6
- 400 + ( ( 0.297 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 989.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |       23 | 2024-05-05 | Endpoint                    | W   | 1.000      | 0.143        | -                | 0.785 (0.112)    | false (0.000) |    16.50 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           57 |      160 | 2024-05-02 | Gaimin Gladiators           | L   | 1.000      | -            | -                | -                | -             |    -4.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           56 |      222 | 2024-05-01 | B8                          | L   | 1.000      | -            | -                | -                | -             |   -13.25 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           55 |      284 | 2024-04-29 | 1win                        | W   | 1.000      | 0.435        | -                | 0.422 (0.183)    | false (0.000) |    10.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           54 |      317 | 2024-04-28 | Zero Tenacity               | L   | 1.000      | -            | -                | -                | -             |   -13.14 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           53 |      391 | 2024-04-27 | Zero Tenacity               | L   | 1.000      | -            | -                | -                | -             |   -14.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           52 |      434 | 2024-04-26 | PARIVISION                  | L   | 1.000      | -            | -                | -                | -             |   -18.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           51 |      544 | 2024-04-24 | Endpoint                    | L   | 1.000      | -            | -                | -                | -             |   -20.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           50 |      618 | 2024-04-22 | HAVU Gaming                 | W   | 1.000      | 0.435        | 0.024 (0.010)    | 0.213 (0.093)    | false (0.000) |     6.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           49 |      752 | 2024-04-20 | ENCE Academy                | L   | 1.000      | -            | -                | -                | -             |   -23.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           48 |      854 | 2024-04-19 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -             |   -16.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           47 |      971 | 2024-04-17 | Gaimin Gladiators           | L   | 1.000      | -            | -                | -                | -             |    -3.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           46 |     1023 | 2024-04-16 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -             |   -13.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           45 |     1078 | 2024-04-14 | Passion UA                  | W   | 1.000      | 0.371        | 0.114 (0.042)    | 0.980 (0.363)    | false (0.000) |    11.27 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           44 |     1258 | 2024-04-10 | UNiTY esports (Slovak team) | W   | 1.000      | 0.371        | 0.055 (0.021)    | 0.727 (0.269)    | false (0.000) |     9.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           43 |     1350 | 2024-04-08 | ALTERNATE aTTaX             | W   | 1.000      | 0.384        | 0.110 (0.042)    | 0.723 (0.278)    | false (0.000) |    11.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           42 |     1443 | 2024-04-05 | Nexus Gaming                | W   | 0.998      | 0.384        | 0.031 (0.012)    | 0.772 (0.296)    | false (0.000) |    13.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           41 |     2135 | 2024-03-17 | Dynamo Eclot                | L   | 0.872      | -            | -                | -                | -             |   -11.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           40 |     2144 | 2024-03-17 | UNiTY esports (Slovak team) | W   | 0.871      | -            | -                | -                | true (0.871)  |     8.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           39 |     2179 | 2024-03-16 | Team Sampi                  | W   | 0.864      | 0.143        | 0.108 (0.013)    | -                | true (0.864)  |    13.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           38 |     2213 | 2024-03-15 | UNiTY esports (Slovak team) | L   | 0.859      | -            | -                | -                | -             |   -19.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           37 |     2692 | 2024-03-05 | Dynamo Eclot                | W   | 0.792      | 0.143        | 0.189 (0.021)    | 0.953 (0.108)    | false (0.000) |    17.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           36 |     2753 | 2024-03-04 | Team Universe               | W   | 0.785      | -            | -                | -                | -             |     2.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           35 |     2796 | 2024-03-03 | Gaimin Gladiators           | L   | 0.778      | -            | -                | -                | -             |    -2.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           34 |     2834 | 2024-03-02 | Permitta Esports            | W   | 0.773      | 0.143        | -                | 1.000 (0.110)    | -             |    12.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           33 |     2856 | 2024-03-02 | DUSTY                       | W   | 0.772      | -            | -                | -                | -             |     4.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           32 |     3448 | 2024-02-18 | Monte                       | L   | 0.685      | -            | -                | -                | -             |    -1.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           31 |     3522 | 2024-02-16 | 500                         | W   | 0.672      | -            | -                | -                | -             |     6.63 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           30 |     3527 | 2024-02-16 | Pera Esports                | W   | 0.672      | -            | -                | -                | -             |    10.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           29 |     3537 | 2024-02-16 | 500                         | L   | 0.671      | -            | -                | -                | -             |   -14.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           28 |     3935 | 2024-02-04 | Into The Breach             | L   | 0.590      | -            | -                | -                | -             |   -12.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           27 |     4056 | 2024-02-02 | Preasy Esport               | L   | 0.576      | -            | -                | -                | -             |    -9.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           26 |     4287 | 2024-01-27 | GODSENT                     | W   | 0.537      | -            | -                | -                | -             |     3.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           25 |     4436 | 2024-01-23 | MOUZ NXT                    | W   | 0.510      | 0.371        | 0.215 (0.041)    | 1.000 (0.189)    | -             |    10.46 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           24 |     4597 | 2024-01-19 | Nexus Gaming                | L   | 0.486      | -            | -                | -                | -             |    -9.11 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           23 |     4644 | 2024-01-18 | Fnatic                      | L   | 0.479      | -            | -                | -                | -             |    -3.56 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           22 |     4667 | 2024-01-18 | Virtus.pro                  | L   | 0.478      | -            | -                | -                | -             |    -0.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           21 |     4982 | 2024-01-11 | HEROIC                      | L   | 0.433      | -            | -                | -                | -             |    -0.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           20 |     4988 | 2024-01-11 | Pera Esports                | W   | 0.432      | -            | -                | -                | -             |     5.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           19 |     4997 | 2024-01-11 | ILIN                        | W   | 0.431      | -            | -                | -                | -             |     1.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           18 |     5004 | 2024-01-11 | V1dar Gaming                | W   | 0.431      | -            | -                | -                | -             |     1.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           17 |     5039 | 2024-01-10 | The Prodigies               | W   | 0.426      | -            | -                | -                | -             |     1.48 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           16 |     5054 | 2024-01-10 | Passion UA                  | W   | 0.426      | 0.143        | 0.114 (0.007)    | -                | -             |     6.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           15 |     5764 | 2023-12-09 | FORZE Esports               | L   | 0.212      | -            | -                | -                | -             |    -4.93 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|           14 |     5888 | 2023-12-07 | 3DMAX                       | L   | 0.199      | -            | -                | -                | -             |    -3.50 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|           13 |     5930 | 2023-12-06 | Team Spirit Academy         | W   | 0.192      | -            | -                | -                | -             |     1.56 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|           12 |     5985 | 2023-12-05 | ENCE                        | W   | 0.185      | 0.500        | 0.377 (0.035)    | -                | -             |     5.60 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|           11 |     6442 | 2023-11-25 | UNiTY esports (Slovak team) | L   | 0.117      | -            | -                | -                | -             |    -1.92 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|           10 |     6489 | 2023-11-24 | Team Sampi                  | L   | 0.111      | -            | -                | -                | -             |    -1.51 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            9 |     6747 | 2023-11-18 | BIG                         | L   | 0.070      | -            | -                | -                | -             |    -0.17 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            8 |     6784 | 2023-11-17 | TSM                         | W   | 0.064      | -            | -                | -                | -             |     0.34 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            7 |     6845 | 2023-11-16 | Legacy                      | W   | 0.056      | -            | -                | -                | -             |     1.23 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            6 |     6982 | 2023-11-13 | ALTERNATE aTTaX             | W   | 0.037      | -            | -                | -                | -             |     0.75 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            5 |     7048 | 2023-11-11 | UNiTY esports (Slovak team) | L   | 0.026      | -            | -                | -                | -             |    -0.41 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            4 |     7132 | 2023-11-09 | BetBoom Team                | L   | 0.012      | -            | -                | -                | -             |    -0.02 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            3 |     7149 | 2023-11-09 | 9Pandas                     | W   | 0.010      | -            | -                | -                | -             |     0.22 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            2 |     7182 | 2023-11-08 | Monte                       | W   | 0.005      | -            | -                | -                | -             |     0.15 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            1 |     7211 | 2023-11-08 | Gaimin Gladiators           | W   | 0.003      | -            | -                | -                | -             |     0.08 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,942.79)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-17 |      0.872 | $3,030.54      | $2,641.90       |
| 2023-12-10 |      0.219 | $10,000.00     | $2,185.65       |
| 2023-11-25 |      0.118 | $5,381.91      | $635.61         |
| 2023-11-18 |      0.072 | $5,000.00      | $361.57         |
| 2023-11-09 |      0.012 | $10,000.00     | $118.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
