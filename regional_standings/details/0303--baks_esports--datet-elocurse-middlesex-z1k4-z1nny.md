### Roster Details<br />
Team Name: BAKS Esports<br />
Roster: datet, elocurse, Middlesex, z1k4, z1Nny<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [303](../standings_global.md)<br />
Regional Rank: [185]( ../standings_europe.md)<br />
Final Rank Value:  608.9<br />
<br />
Final Rank Value (608.9) = Starting Rank Value (658.0) + Head To Head Adjustments (-49.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.279[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 658.0
- 400 + ( ( 0.130 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 658.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     1791 | 2024-03-26 | MANGANES                    | L   | 0.933      | -            | -                | -                | -             |   -19.41 | datet, elocurse, Middlesex, z1k4, z1Nny       |
|           21 |     2919 | 2024-03-01 | Kappa Bar                   | L   | 0.764      | -            | -                | -                | -             |   -11.13 | datet, elocurse, Middlesex, reyoz, twizell    |
|           20 |     2939 | 2024-02-29 | Lajtbitexe                  | W   | 0.759      | 0.371        | 0.000 (0.000)    | 0.033 (0.009)    | false (0.000) |     8.32 | datet, elocurse, Middlesex, reyoz, twizell    |
|           19 |     2999 | 2024-02-28 | ILIN                        | L   | 0.751      | -            | -                | -                | -             |   -12.99 | datet, elocurse, Middlesex, reyoz, twizell    |
|           18 |     3408 | 2024-02-19 | V1dar Gaming                | L   | 0.692      | -            | -                | -                | -             |   -11.52 | datet, elocurse, Middlesex, reyoz, twizell    |
|           17 |     3434 | 2024-02-18 | L1ZUN4IKI                   | W   | 0.686      | 0.284        | 0.001 (0.000)    | 0.024 (0.005)    | false (0.000) |    11.21 | datet, elocurse, Middlesex, reyoz, twizell    |
|           16 |     3580 | 2024-02-15 | GamerLegion Academy         | L   | 0.665      | -            | -                | -                | -             |    -6.20 | datet, elocurse, Middlesex, reyoz, twizell    |
|           15 |     3618 | 2024-02-14 | Zero Tenacity               | L   | 0.659      | -            | -                | -                | -             |    -3.51 | datet, elocurse, Middlesex, reyoz, twizell    |
|           14 |     3841 | 2024-02-07 | RoundsGG                    | L   | 0.612      | -            | -                | -                | -             |    -8.48 | datet, elocurse, Middlesex, reyoz, twizell    |
|           13 |     4925 | 2024-01-12 | UNiTY esports (Slovak team) | L   | 0.439      | -            | -                | -                | -             |    -2.11 | datet, elocurse, Middlesex, reyoz, twizell    |
|           12 |     4936 | 2024-01-12 | RUSH B (Russian team)       | W   | 0.439      | 0.143        | 0.006 (0.000)    | 0.471 (0.030)    | false (0.000) |     9.36 | datet, elocurse, Middlesex, reyoz, twizell    |
|           11 |     5398 | 2023-12-17 | VaselineWorms               | L   | 0.263      | -            | -                | -                | -             |    -4.21 | datet, elocurse, Middlesex, reyoz, twizell    |
|           10 |     5466 | 2023-12-16 | PrizyvaNet                  | W   | 0.259      | 0.294        | 0.000 (0.000)    | 0.015 (0.001)    | false (0.000) |     2.67 | datet, elocurse, Middlesex, reyoz, twizell    |
|            9 |     5501 | 2023-12-16 | Nemiga Gaming               | L   | 0.256      | -            | -                | -                | -             |    -0.20 | datet, elocurse, Middlesex, reyoz, twizell    |
|            8 |     6206 | 2023-11-30 | MOUZ NXT                    | L   | 0.152      | -            | -                | -                | -             |    -0.39 | datet, elocurse, Middlesex, reyoz, twizell    |
|            7 |     6261 | 2023-11-29 | V1dar Gaming                | W   | 0.145      | 0.371        | 0.000 (0.000)    | 0.345 (0.019)    | false (0.000) |     1.85 | 1mpala, 4X1s, Alv, lom1k, torox               |
|            6 |     6363 | 2023-11-27 | Zero Tenacity               | L   | 0.132      | -            | -                | -                | -             |    -0.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke      |
|            5 |     6517 | 2023-11-23 | ALTERNATE aTTaX             | W   | 0.105      | 0.371        | 0.110 (0.004)    | 0.723 (0.028)    | false (0.000) |     3.03 | awzek, FreeZe, PANIX, PerX, Spiidi            |
|            4 |     6561 | 2023-11-22 | The Chosen Few              | L   | 0.098      | -            | -                | -                | -             |    -0.91 | hybrid, Libido, shaiK, Skrimo, SPELLAN        |
|            3 |     6619 | 2023-11-20 | For The Win Esports         | L   | 0.086      | -            | -                | -                | -             |    -1.26 | Ag1l, NOPEEj, pr, shr, stadodo                |
|            2 |     6735 | 2023-11-18 | LF0                         | L   | 0.070      | -            | -                | -                | -             |    -1.14 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            1 |     6771 | 2023-11-17 | TEAM ZOO BAR                | L   | 0.065      | -            | -                | -                | -             |    -1.44 | AMANEK, devoduvek, drac, Kyojin, SIXER        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($411.75)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
