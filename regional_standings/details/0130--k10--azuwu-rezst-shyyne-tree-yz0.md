### Roster Details<br />
Team Name: K10<br />
Roster: AZUWU, Rezst, shyyne, Tree, yz0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [130](../standings_global.md)<br />
Regional Rank: [92]( ../standings_europe.md)<br />
Final Rank Value:  805.2<br />
<br />
Final Rank Value (805.2) = Starting Rank Value (895.9) + Head To Head Adjustments (-90.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.355[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.233[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 895.9
- 400 + ( ( 0.250 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 895.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |     1119 | 2024-04-13 | UNiTY esports (Slovak team) | L   | 1.000      | -            | -                | -                | -         |   -13.71 | AZUWU, Rezst, shyyne, Tree, yz0              |
|           52 |     1189 | 2024-04-11 | Viperio                     | L   | 1.000      | -            | -                | -                | -         |   -18.70 | Rezst, shyyne, SLY, Tree, yz0                |
|           51 |     1426 | 2024-04-06 | ROSOMAHA                    | W   | 1.000      | 0.333        | -                | 0.136 (0.045)    | 0 (0.000) |     6.49 | Rezst, shyyne, SLY, Tree, yz0                |
|           50 |     1494 | 2024-04-04 | Verdant                     | W   | 0.991      | 0.333        | 0.027 (0.009)    | 0.662 (0.219)    | 0 (0.000) |    20.13 | Rezst, shyyne, SLY, Tree, yz0                |
|           49 |     1657 | 2024-03-29 | EXO Clan                    | L   | 0.952      | -            | -                | -                | -         |   -10.69 | Kisynergy, Rezst, shyyne, Tree, yz0          |
|           48 |     1996 | 2024-03-21 | Permitta Esports            | L   | 0.897      | -            | -                | -                | -         |    -7.83 | Rezst, shyyne, SLY, Tree, yz0                |
|           47 |     2047 | 2024-03-19 | Part Timers                 | W   | 0.886      | -            | -                | -                | 0 (0.000) |     4.18 | Kisynergy, Rezst, shyyne, Tree, yz0          |
|           46 |     2152 | 2024-03-17 | Passion UA                  | L   | 0.870      | -            | -                | -                | -         |    -9.61 | Rezst, shyyne, SLY, Tree, yz0                |
|           45 |     2282 | 2024-03-14 | Permitta Esports            | W   | 0.850      | 0.333        | 0.063 (0.018)    | 1.000 (0.283)    | 0 (0.000) |    20.09 | Rezst, shyyne, SLY, Tree, yz0                |
|           44 |     2501 | 2024-03-09 | Insilio                     | L   | 0.818      | -            | -                | -                | -         |    -7.62 | Rezst, shyyne, SLY, Tree, yz0                |
|           43 |     2520 | 2024-03-09 | Grannys Knockers            | L   | 0.816      | -            | -                | -                | -         |   -11.94 | Rezst, shyyne, SLY, Tree, yz0                |
|           42 |     2532 | 2024-03-08 | MOUZ NXT                    | L   | 0.811      | -            | -                | -                | -         |    -5.45 | Rezst, shyyne, SLY, Tree, yz0                |
|           41 |     2652 | 2024-03-06 | Passion UA                  | L   | 0.797      | -            | -                | -                | -         |    -9.44 | Rezst, shyyne, SLY, Tree, yz0                |
|           40 |     2766 | 2024-03-04 | Team Secret                 | W   | 0.784      | 0.371        | -                | 0.368 (0.107)    | 0 (0.000) |     7.29 | Rezst, shyyne, SLY, Tree, yz0                |
|           39 |     2817 | 2024-03-03 | ENCE Academy                | L   | 0.777      | -            | -                | -                | -         |   -11.52 | Rezst, shyyne, SLY, Tree, yz0                |
|           38 |     2915 | 2024-03-01 | HOTU                        | W   | 0.765      | 0.371        | 0.011 (0.003)    | 0.323 (0.092)    | -         |     9.94 | Rezst, shyyne, SLY, Tree, yz0                |
|           37 |     2918 | 2024-03-01 | CYBERSHOKE Esports          | L   | 0.765      | -            | -                | -                | -         |   -15.58 | Rezst, shyyne, SLY, Tree, yz0                |
|           36 |     2932 | 2024-02-29 | Verdant                     | W   | 0.759      | 0.143        | 0.027 (0.003)    | 0.662 (0.072)    | -         |    13.39 | Kisynergy, Rezst, shyyne, Tree, yz0          |
|           35 |     2967 | 2024-02-29 | Aurora Young Blud           | L   | 0.757      | -            | -                | -                | -         |   -14.00 | Rezst, shyyne, SLY, Tree, yz0                |
|           34 |     3013 | 2024-02-27 | The Last Resort             | W   | 0.746      | -            | -                | -                | -         |     6.85 | Kisynergy, Rezst, shyyne, Tree, yz0          |
|           33 |     3035 | 2024-02-27 | ENCE Academy                | L   | 0.745      | -            | -                | -                | -         |   -11.53 | Rezst, shyyne, SLY, Tree, yz0                |
|           32 |     3170 | 2024-02-24 | Raptors Esports Club        | W   | 0.724      | 0.143        | 0.017 (0.002)    | 0.384 (0.040)    | 1 (0.724) |    11.14 | Rezst, shyyne, SLY, Tree, yz0                |
|           31 |     3202 | 2024-02-23 | Rum Bumpers                 | W   | 0.720      | -            | -                | -                | 1 (0.720) |     6.74 | Rezst, shyyne, SLY, Tree, yz0                |
|           30 |     3342 | 2024-02-20 | Raptors Esports Club        | W   | 0.699      | 0.143        | 0.017 (0.002)    | -                | -         |    11.46 | Kisynergy, Rezst, shyyne, Tree, yz0          |
|           29 |     3552 | 2024-02-16 | Passion UA                  | L   | 0.669      | -            | -                | -                | -         |    -7.70 | Rezst, shyyne, SLY, Tree, yz0                |
|           28 |     3571 | 2024-02-15 | Souls-Land                  | W   | 0.666      | -            | -                | -                | -         |     1.92 | Kisynergy, Rezst, shyyne, Tree, yz0          |
|           27 |     3592 | 2024-02-15 | GamerLegion Academy         | W   | 0.664      | 0.371        | 0.043 (0.011)    | 0.567 (0.140)    | -         |     9.68 | Rezst, shyyne, SLY, Tree, yz0                |
|           26 |     3607 | 2024-02-15 | Lilmix                      | L   | 0.663      | -            | -                | -                | -         |   -15.85 | Rezst, shyyne, SLY, Tree, yz0                |
|           25 |     3646 | 2024-02-14 | Dynamo Eclot                | L   | 0.657      | -            | -                | -                | -         |    -3.23 | Rezst, shyyne, SLY, Tree, yz0                |
|           24 |     3675 | 2024-02-13 | ILIN                        | L   | 0.652      | -            | -                | -                | -         |   -17.10 | Rezst, shyyne, SLY, Tree, yz0                |
|           23 |     3681 | 2024-02-13 | Lajtbitexe                  | W   | 0.651      | -            | -                | -                | -         |     2.88 | Rezst, shyyne, SLY, Tree, yz0                |
|           22 |     3694 | 2024-02-13 | ROSOMAHA                    | W   | 0.649      | -            | -                | -                | -         |     4.06 | Rezst, shyyne, SLY, Tree, yz0                |
|           21 |     3712 | 2024-02-12 | LODIS                       | W   | 0.646      | 0.371        | 0.002 (0.001)    | -                | -         |     4.52 | Rezst, shyyne, SLY, Tree, yz0                |
|           20 |     3726 | 2024-02-12 | RoundsGG                    | W   | 0.645      | 0.371        | -                | 0.170 (0.041)    | -         |     6.25 | Rezst, shyyne, SLY, Tree, yz0                |
|           19 |     3758 | 2024-02-11 | MOUZ NXT                    | L   | 0.637      | -            | -                | -                | -         |    -4.61 | Rezst, shyyne, SLY, Tree, yz0                |
|           18 |     3780 | 2024-02-10 | Viperio                     | L   | 0.629      | -            | -                | -                | -         |   -15.15 | Rezst, shyyne, SLY, Tree, yz0                |
|           17 |     3979 | 2024-02-03 | Viperio                     | L   | 0.584      | -            | -                | -                | -         |   -14.76 | dox, Rezst, shyyne, Tree, yz0                |
|           16 |     3986 | 2024-02-03 | The Last Resort             | W   | 0.584      | -            | -                | -                | -         |     4.40 | dox, Rezst, shyyne, Tree, yz0                |
|           15 |     4268 | 2024-01-27 | 9INE                        | L   | 0.538      | -            | -                | -                | -         |   -14.13 | dox, Rezst, shyyne, Tree, yz0                |
|           14 |     5052 | 2024-01-10 | Permitta Esports            | L   | 0.426      | -            | -                | -                | -         |    -4.91 | dox, Rezst, shyyne, Tree, yz0                |
|           13 |     5084 | 2024-01-09 | KOI                         | L   | 0.419      | -            | -                | -                | -         |    -4.06 | dox, Rezst, shyyne, Tree, yz0                |
|           12 |     5102 | 2024-01-09 | Nexus Gaming                | W   | 0.418      | 0.143        | 0.031 (0.002)    | 0.772 (0.046)    | -         |     6.75 | dox, Rezst, shyyne, Tree, yz0                |
|           11 |     5122 | 2024-01-09 | Sashi Esport                | W   | 0.418      | -            | -                | -                | -         |     1.50 | dox, Rezst, shyyne, Tree, yz0                |
|           10 |     5714 | 2023-12-10 | Verdant                     | W   | 0.219      | 0.143        | 0.027 (0.001)    | -                | 1 (0.219) |     4.47 | dox, Rezst, shyyne, Tree, yz0                |
|            9 |     5727 | 2023-12-10 | Raptors Esports Club        | W   | 0.217      | -            | -                | -                | 1 (0.217) |     3.24 | dox, Rezst, shyyne, Tree, yz0                |
|            8 |     5739 | 2023-12-10 | Verdant                     | L   | 0.217      | -            | -                | -                | -         |    -2.39 | dox, Rezst, shyyne, Tree, yz0                |
|            7 |     5773 | 2023-12-09 | Viperio                     | W   | 0.211      | -            | -                | -                | 1 (0.211) |     1.13 | dox, Rezst, shyyne, Tree, yz0                |
|            6 |     6275 | 2023-11-29 | Grindas                     | L   | 0.144      | -            | -                | -                | -         |    -3.38 | dox, Rezst, shyyne, Tree, yz0                |
|            5 |     6555 | 2023-11-22 | BALLISTIC                   | W   | 0.099      | -            | -                | -                | -         |     0.18 | dox, Rezst, shyyne, Tree, yz0                |
|            4 |     6635 | 2023-11-20 | V1dar Gaming                | L   | 0.085      | -            | -                | -                | -         |    -2.28 | 1mpala, 4X1s, Alv, lom1k, torox              |
|            3 |     6765 | 2023-11-17 | The Chosen Few              | L   | 0.066      | -            | -                | -                | -         |    -1.26 | hybrid, Libido, shaiK, Skrimo, SPELLAN       |
|            2 |     6963 | 2023-11-13 | Entropiq                    | L   | 0.039      | -            | -                | -                | -         |    -0.78 | c0llins, forsyy, Marix, Oxygen, tiziaN       |
|            1 |     7090 | 2023-11-10 | 9Pandas                     | L   | 0.019      | -            | -                | -                | -         |    -0.12 | clax, d1Ledez, glowiing, iDISBALANCE, seized |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,434.19)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-29 |      0.952 | $946.43        | $901.43         |
| 2024-02-24 |      0.726 | $1,204.50      | $874.55         |
| 2023-12-10 |      0.219 | $3,011.52      | $658.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
