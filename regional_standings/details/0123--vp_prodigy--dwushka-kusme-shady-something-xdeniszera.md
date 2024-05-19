### Roster Details<br />
Team Name: VP.Prodigy<br />
Roster: dwushka, KusMe, shady, Something, xdENiSZERA<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [123](../standings_global.md)<br />
Regional Rank: [87]( ../standings_europe.md)<br />
Final Rank Value:  812.6<br />
<br />
Final Rank Value (812.6) = Starting Rank Value (814.4) + Head To Head Adjustments (-1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.395[<sup>1</sup>](#table2)
- Bounty Collected: 0.292[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.046[<sup>2</sup>](#table1)

The average of these factors is 0.209<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 814.4
- 400 + ( ( 0.209 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 814.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |       12 | 2024-05-05 | Nemiga Gaming               | L   | 1.000      | -            | -                | -                | -             |    -2.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           54 |       16 | 2024-05-05 | Eternal Fire Academy        | W   | 1.000      | -            | -                | -                | false (0.000) |     5.57 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           53 |       82 | 2024-05-04 | XGOD                        | W   | 1.000      | -            | -                | -                | false (0.000) |     4.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           52 |      264 | 2024-04-29 | LOADING (French team)       | W   | 1.000      | -            | -                | -                | false (0.000) |     2.97 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           51 |      285 | 2024-04-29 | Nexus Gaming                | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.772 (0.110)    | false (0.000) |    21.37 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           50 |      319 | 2024-04-28 | LEON Esports                | W   | 1.000      | -            | -                | -                | false (0.000) |    13.30 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           49 |      364 | 2024-04-27 | RUSH B (Russian team)       | L   | 1.000      | -            | -                | -                | -             |   -12.95 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           48 |      432 | 2024-04-26 | V1dar Gaming                | L   | 1.000      | -            | -                | -                | -             |   -20.48 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           47 |      479 | 2024-04-25 | EXO Clan                    | L   | 1.000      | -            | -                | -                | -             |    -9.09 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           46 |      518 | 2024-04-24 | LOG Esports                 | W   | 1.000      | -            | -                | -                | false (0.000) |     2.58 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           45 |      551 | 2024-04-24 | V1dar Gaming                | W   | 1.000      | -            | -                | -                | false (0.000) |     9.79 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           44 |      826 | 2024-04-19 | HOTU                        | L   | 1.000      | -            | -                | -                | -             |   -16.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           43 |      889 | 2024-04-18 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -             |    -8.12 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           42 |     1037 | 2024-04-15 | JANO Esports                | L   | 1.000      | -            | -                | -                | -             |   -19.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           41 |     1072 | 2024-04-14 | Lemondogs                   | L   | 1.000      | -            | -                | -                | -             |   -26.34 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           40 |     1180 | 2024-04-11 | Aurora Young Blud           | W   | 1.000      | 0.333        | 0.017 (0.006)    | 0.422 (0.141)    | false (0.000) |    12.64 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           39 |     1323 | 2024-04-08 | Kappa Bar                   | W   | 1.000      | 0.371        | -                | 0.200 (0.074)    | -             |     4.89 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           38 |     1376 | 2024-04-07 | GUN5 Esports                | L   | 1.000      | -            | -                | -                | -             |   -22.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           37 |     1915 | 2024-03-23 | FORZE Esports               | L   | 0.911      | -            | -                | -                | -             |    -6.16 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           36 |     1952 | 2024-03-22 | Guild Eagles                | W   | 0.903      | 0.143        | 0.037 (0.005)    | 0.586 (0.076)    | -             |    19.97 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           35 |     2034 | 2024-03-20 | TSM                         | W   | 0.890      | 0.143        | 0.013 (0.002)    | -                | -             |     9.46 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           34 |     2463 | 2024-03-10 | 1win                        | L   | 0.824      | -            | -                | -                | -             |   -16.10 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           33 |     2573 | 2024-03-07 | Permitta Esports            | L   | 0.805      | -            | -                | -                | -             |    -8.15 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           32 |     2699 | 2024-03-05 | FORZE Youngsters            | W   | 0.792      | -            | -                | -                | -             |     6.76 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           31 |     2802 | 2024-03-03 | SHIPACHI                    | W   | 0.778      | -            | -                | -                | -             |     5.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           30 |     2808 | 2024-03-03 | W43                         | W   | 0.778      | -            | -                | -                | -             |     5.30 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           29 |     2812 | 2024-03-03 | BebraFPL1                   | W   | 0.777      | -            | -                | -                | -             |     3.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           28 |     2916 | 2024-03-01 | Entropiq                    | W   | 0.765      | 0.371        | -                | 0.436 (0.124)    | -             |    11.56 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           27 |     3036 | 2024-02-27 | The Chosen Few              | W   | 0.744      | 0.371        | 0.007 (0.002)    | 0.457 (0.126)    | -             |    10.42 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           26 |     3074 | 2024-02-26 | ARCRED                      | L   | 0.738      | -            | -                | -                | -             |   -11.88 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           25 |     3207 | 2024-02-23 | Sashi Esport                | L   | 0.719      | -            | -                | -                | -             |    -4.29 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           24 |     3242 | 2024-02-22 | Copenhagen Wolves           | W   | 0.712      | 0.371        | -                | 0.417 (0.110)    | -             |     4.80 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           23 |     3291 | 2024-02-21 | DASH                        | W   | 0.706      | -            | -                | -                | -             |     8.72 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           22 |     3435 | 2024-02-18 | L1ZUN4IKI                   | L   | 0.686      | -            | -                | -                | -             |   -16.06 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           21 |     3578 | 2024-02-15 | NOM Esports                 | W   | 0.665      | 0.371        | -                | 0.374 (0.092)    | -             |     5.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           20 |     3677 | 2024-02-13 | Rhyno Esports               | L   | 0.652      | -            | -                | -                | -             |    -8.14 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           19 |     3820 | 2024-02-08 | GenOne                      | L   | 0.618      | -            | -                | -                | -             |   -16.50 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           18 |     3881 | 2024-02-05 | Team Secret                 | W   | 0.599      | 0.371        | -                | 0.368 (0.082)    | -             |     4.93 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           17 |     4103 | 2024-01-31 | Ex-Anonymo Esports          | W   | 0.566      | 0.371        | 0.019 (0.004)    | -                | -             |     7.49 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           16 |     5248 | 2023-12-30 | Metizport                   | L   | 0.350      | -            | -                | -                | -             |    -3.31 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           15 |     5256 | 2023-12-28 | Illuminar Gaming            | W   | 0.336      | -            | -                | -                | -             |     4.27 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           14 |     5263 | 2023-12-26 | Alliance                    | W   | 0.324      | 0.371        | 0.017 (0.002)    | 0.729 (0.087)    | -             |     5.59 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           13 |     5322 | 2023-12-19 | ARCRED                      | W   | 0.276      | -            | -                | -                | -             |     4.25 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           12 |     5346 | 2023-12-17 | UNiTY esports (Slovak team) | W   | 0.266      | 0.333        | 0.055 (0.005)    | -                | -             |     5.67 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           11 |     5364 | 2023-12-17 | XGOD                        | W   | 0.264      | -            | -                | -                | -             |     1.11 | dwushka, KusMe, shady, Something, xdENiSZERA |
|           10 |     5377 | 2023-12-17 | 1win                        | W   | 0.264      | -            | -                | -                | -             |     3.02 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            9 |     5483 | 2023-12-16 | Nemiga Gaming               | L   | 0.257      | -            | -                | -                | -             |    -0.54 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            8 |     5500 | 2023-12-16 | VaselineWorms               | W   | 0.256      | -            | -                | -                | -             |     2.16 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            7 |     5578 | 2023-12-15 | UNiTY esports (Slovak team) | W   | 0.252      | 0.333        | 0.055 (0.005)    | -                | -             |     5.51 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            6 |     5643 | 2023-12-13 | Ex-KRC Genk Esports         | W   | 0.239      | -            | -                | -                | -             |     3.60 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            5 |     5675 | 2023-12-12 | Rhyno Esports               | W   | 0.231      | 0.333        | 0.047 (0.004)    | -                | -             |     4.84 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            4 |     5775 | 2023-12-09 | LF0                         | W   | 0.210      | -            | -                | -                | true (0.210)  |     1.83 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            3 |     5850 | 2023-12-08 | HOTU                        | W   | 0.203      | -            | -                | -                | true (0.203)  |     3.03 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            2 |     5873 | 2023-12-07 | Team OWL                    | W   | 0.199      | -            | -                | -                | -             |     0.88 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     5971 | 2023-12-05 | FALKE ESPORTS               | W   | 0.186      | -            | -                | -                | -             |     0.89 | dwushka, KusMe, shady, Something, xdENiSZERA |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,656.65)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-03 |      0.778 | $2,500.00      | $1,945.60       |
| 2024-02-18 |      0.686 | $100.00        | $68.63          |
| 2023-12-17 |      0.266 | $3,500.00      | $929.77         |
| 2023-12-09 |      0.210 | $8,138.46      | $1,712.66       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
