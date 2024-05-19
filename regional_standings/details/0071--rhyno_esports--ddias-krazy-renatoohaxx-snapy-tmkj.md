### Roster Details<br />
Team Name: Rhyno Esports<br />
Roster: DDias, krazy, renatoohaxx, snapy, TMKj<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [71](../standings_global.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
Final Rank Value:  914.4<br />
<br />
Final Rank Value (914.4) = Starting Rank Value (946.5) + Head To Head Adjustments (-32.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.430[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.188[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 946.5
- 400 + ( ( 0.275 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 946.5


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
|           48 |      639 | 2024-04-21 | Aurora Young Blud           | W   | 1.000      | 0.333        | 0.017 (0.006)    | 0.422 (0.141)    | false (0.000) |     9.88 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           47 |      652 | 2024-04-21 | Dynamo Eclot                | W   | 1.000      | 0.333        | 0.189 (0.063)    | 0.953 (0.318)    | false (0.000) |    20.79 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           46 |      768 | 2024-04-20 | HOTU                        | W   | 1.000      | 0.333        | 0.011 (0.004)    | 0.323 (0.108)    | false (0.000) |    11.97 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           45 |      842 | 2024-04-19 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | false (0.000) |    17.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           44 |      899 | 2024-04-18 | Aurora Young Blud           | L   | 1.000      | -            | -                | -                | -             |   -21.12 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           43 |     1006 | 2024-04-16 | Los kogutos                 | L   | 1.000      | -            | -                | -                | -             |   -27.23 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           42 |     1187 | 2024-04-11 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | false (0.000) |    14.72 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           41 |     1239 | 2024-04-10 | Dynamo Eclot                | W   | 1.000      | 0.333        | 0.189 (0.063)    | 0.953 (0.318)    | false (0.000) |    20.87 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           40 |     1288 | 2024-04-09 | ARROW (German team)         | W   | 1.000      | 0.371        | 0.009 (0.003)    | 0.273 (0.102)    | -             |    10.09 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           39 |     1344 | 2024-04-08 | DMS                         | L   | 1.000      | -            | -                | -                | -             |   -19.62 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           38 |     2814 | 2024-03-03 | EsmagaB                     | L   | 0.777      | -            | -                | -                | -             |   -15.42 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           37 |     2877 | 2024-03-02 | AL-QATRAO                   | W   | 0.771      | -            | -                | -                | true (0.771)  |     6.52 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           36 |     3022 | 2024-02-27 | Lemondogs                   | W   | 0.745      | -            | -                | -                | -             |     3.45 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           35 |     3034 | 2024-02-27 | Grindas                     | W   | 0.745      | 0.371        | -                | 0.332 (0.092)    | -             |     6.07 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           34 |     3039 | 2024-02-27 | BLESSED (Ukrainian team)    | L   | 0.744      | -            | -                | -                | -             |   -14.01 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           33 |     3261 | 2024-02-22 | Insilio                     | L   | 0.711      | -            | -                | -                | -             |    -9.24 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           32 |     3348 | 2024-02-20 | Lausanne-Sport Esports      | W   | 0.698      | -            | -                | -                | -             |     6.08 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           31 |     3496 | 2024-02-17 | UNiTY esports (Slovak team) | L   | 0.678      | -            | -                | -                | -             |   -10.31 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           30 |     3535 | 2024-02-16 | HOTU                        | L   | 0.671      | -            | -                | -                | -             |   -13.98 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           29 |     3595 | 2024-02-15 | Team Spirit Academy         | L   | 0.664      | -            | -                | -                | -             |   -13.08 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           28 |     3677 | 2024-02-13 | VP.Prodigy                  | W   | 0.652      | 0.371        | 0.029 (0.007)    | 0.762 (0.184)    | -             |     8.14 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           27 |     3825 | 2024-02-08 | GamerLegion Academy         | W   | 0.618      | 0.371        | 0.043 (0.010)    | 0.567 (0.130)    | -             |     7.38 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           26 |     3925 | 2024-02-04 | SAW                         | L   | 0.591      | -            | -                | -                | -             |    -0.84 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           25 |     3952 | 2024-02-03 | EsmagaB                     | W   | 0.585      | 0.143        | 0.016 (0.001)    | -                | -             |     8.22 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           24 |     4015 | 2024-02-02 | ABT Esports                 | W   | 0.579      | -            | -                | -                | -             |     1.77 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           23 |     4027 | 2024-02-02 | KOI                         | L   | 0.578      | -            | -                | -                | -             |    -5.22 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           22 |     4039 | 2024-02-02 | OVERFRAG                    | W   | 0.578      | -            | -                | -                | -             |     2.19 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           21 |     4324 | 2024-01-26 | INGLORIOUS                  | L   | 0.531      | -            | -                | -                | -             |   -11.26 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           20 |     4425 | 2024-01-23 | Zero Tenacity               | L   | 0.512      | -            | -                | -                | -             |    -7.86 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           19 |     5100 | 2024-01-09 | Dynamo Eclot                | L   | 0.418      | -            | -                | -                | -             |    -2.57 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           18 |     5111 | 2024-01-09 | Soda Gaming                 | W   | 0.418      | -            | -                | -                | -             |     3.71 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           17 |     5255 | 2023-12-28 | Alliance                    | L   | 0.337      | -            | -                | -                | -             |    -6.04 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           16 |     5261 | 2023-12-27 | Illuminar Gaming            | L   | 0.330      | -            | -                | -                | -             |    -7.36 | DDias, krazy, renatoohaxx, snapy, TMKj |
|           15 |     5449 | 2023-12-16 | UNiTY esports (Slovak team) | L   | 0.259      | -            | -                | -                | -             |    -3.77 | DDias, Icarus, krazy, snapy, TMKj      |
|           14 |     5573 | 2023-12-15 | Ex-KRC Genk Esports         | W   | 0.252      | -            | -                | -                | -             |     2.60 | DDias, Icarus, krazy, snapy, TMKj      |
|           13 |     5634 | 2023-12-13 | NOM Esports                 | W   | 0.239      | -            | -                | -                | -             |     1.50 | DDias, Icarus, krazy, snapy, TMKj      |
|           12 |     5666 | 2023-12-12 | BLUEJAYS Lite               | W   | 0.232      | -            | -                | -                | -             |     1.00 | DDias, Icarus, krazy, snapy, TMKj      |
|           11 |     5675 | 2023-12-12 | VP.Prodigy                  | L   | 0.231      | -            | -                | -                | -             |    -4.84 | DDias, Icarus, krazy, snapy, TMKj      |
|           10 |     5840 | 2023-12-08 | TOOMUCHVIDEOGAMES           | W   | 0.205      | -            | -                | -                | -             |     0.52 | DDias, Icarus, krazy, snapy, TMKj      |
|            9 |     5972 | 2023-12-05 | Family                      | W   | 0.186      | -            | -                | -                | -             |     0.27 | DDias, Icarus, krazy, snapy, TMKj      |
|            8 |     6434 | 2023-11-25 | SAW                         | L   | 0.118      | -            | -                | -                | -             |    -0.17 | DDias, Icarus, krazy, snapy, TMKj      |
|            7 |     6494 | 2023-11-24 | For The Win Esports         | W   | 0.110      | -            | -                | -                | true (0.110)  |     0.66 | DDias, Icarus, krazy, snapy, TMKj      |
|            6 |     6528 | 2023-11-23 | For The Win Esports         | L   | 0.104      | -            | -                | -                | -             |    -2.68 | DDias, Icarus, krazy, snapy, TMKj      |
|            5 |     6545 | 2023-11-22 | OVERFRAG                    | W   | 0.099      | -            | -                | -                | -             |     0.30 | DDias, Icarus, krazy, snapy, TMKj      |
|            4 |     6668 | 2023-11-19 | For The Win Esports         | W   | 0.078      | -            | -                | -                | true (0.078)  |     0.45 | DDias, Icarus, krazy, snapy, TMKj      |
|            3 |     6682 | 2023-11-19 | Los Alpacas                 | W   | 0.077      | -            | -                | -                | true (0.077)  |     0.37 | DDias, Icarus, krazy, snapy, TMKj      |
|            2 |     6704 | 2023-11-18 | For The Win Esports         | L   | 0.072      | -            | -                | -                | -             |    -1.86 | DDias, Icarus, krazy, snapy, TMKj      |
|            1 |     7105 | 2023-11-10 | Verdant                     | L   | 0.017      | -            | -                | -                | -             |    -0.23 | DDias, Icarus, krazy, snapy, TMKj      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,496.40)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-03 |      0.777 | $1,627.60      | $1,265.38       |
| 2023-12-17 |      0.266 | $1,500.00      | $398.47         |
| 2023-11-25 |      0.118 | $3,284.78      | $386.27         |
| 2023-11-19 |      0.078 | $5,731.13      | $446.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
