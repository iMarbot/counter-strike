### Roster Details<br />
Team Name: ENCE Academy<br />
Roster: 2high, HENU, myltsi, podi, teme<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [145](../standings_global.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
Final Rank Value:  778.4<br />
<br />
Final Rank Value (778.4) = Starting Rank Value (854.2) + Head To Head Adjustments (-75.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.391[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.122[<sup>2</sup>](#table1)
- LAN Wins: 0.081[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.2
- 400 + ( ( 0.229 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 854.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |       13 | 2024-05-05 | Heimo Esports               | L   | 1.000      | -            | -                | -                | -         |   -15.87 | 2high, HENU, myltsi, podi, teme    |
|           32 |       76 | 2024-05-04 | TOOMUCHVIDEOGAMES           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.161 (0.023)    | 0 (0.000) |     7.01 | 2high, HENU, myltsi, podi, teme    |
|           31 |      124 | 2024-05-03 | Nexus Gaming                | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.772 (0.335)    | 0 (0.000) |    19.18 | 2high, HENU, myltsi, podi, teme    |
|           30 |      185 | 2024-05-01 | ENTERPRISE esports          | L   | 1.000      | -            | -                | -                | -         |   -12.16 | 2high, HENU, myltsi, podi, teme    |
|           29 |      220 | 2024-05-01 | Team Sampi                  | L   | 1.000      | -            | -                | -                | -         |    -7.02 | HENU, myltsi, podi, S1rva, teme    |
|           28 |      246 | 2024-04-30 | Endpoint                    | L   | 1.000      | -            | -                | -                | -         |   -10.86 | HENU, myltsi, podi, S1rva, teme    |
|           27 |      262 | 2024-04-29 | RUSH B (Russian team)       | L   | 1.000      | -            | -                | -                | -         |   -13.71 | 2high, HENU, myltsi, podi, teme    |
|           26 |      321 | 2024-04-28 | Heimo Esports               | L   | 1.000      | -            | -                | -                | -         |   -18.13 | 2high, HENU, myltsi, podi, teme    |
|           25 |      620 | 2024-04-22 | ALTERNATE aTTaX             | L   | 1.000      | -            | -                | -                | -         |   -12.92 | HENU, myltsi, podi, S1rva, teme    |
|           24 |      645 | 2024-04-21 | TOOMUCHVIDEOGAMES           | W   | 1.000      | 0.143        | -                | 0.161 (0.023)    | 0 (0.000) |     5.25 | 2high, HENU, myltsi, podi, teme    |
|           23 |      752 | 2024-04-20 | SINNERS Esports             | W   | 1.000      | 0.371        | 0.038 (0.014)    | 0.534 (0.198)    | 0 (0.000) |    23.21 | HENU, myltsi, podi, S1rva, teme    |
|           22 |      853 | 2024-04-19 | Viperio                     | L   | 1.000      | -            | -                | -                | -         |   -18.27 | HENU, myltsi, podi, S1rva, teme    |
|           21 |      898 | 2024-04-18 | MOUZ NXT                    | L   | 1.000      | -            | -                | -                | -         |    -6.85 | HENU, myltsi, podi, S1rva, teme    |
|           20 |     1007 | 2024-04-16 | 1win                        | L   | 1.000      | -            | -                | -                | -         |   -19.20 | HENU, myltsi, podi, S1rva, teme    |
|           19 |     1051 | 2024-04-15 | Team Sampi                  | W   | 1.000      | 0.371        | 0.108 (0.040)    | 0.709 (0.263)    | 0 (0.000) |    23.11 | HENU, myltsi, podi, S1rva, teme    |
|           18 |     1055 | 2024-04-15 | Viperio                     | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.176 (0.025)    | 0 (0.000) |    13.70 | HENU, myltsi, podi, S1rva, teme    |
|           17 |     1188 | 2024-04-11 | Team Secret                 | W   | 1.000      | 0.371        | -                | 0.368 (0.136)    | 0 (0.000) |    10.52 | HENU, myltsi, podi, S1rva, teme    |
|           16 |     2106 | 2024-03-18 | Sprout Academy              | L   | 0.876      | -            | -                | -                | -         |   -23.16 | Diviiii, HENU, myltsi, S1rva, teme |
|           15 |     2335 | 2024-03-13 | Natus Vincere Junior        | L   | 0.844      | -            | -                | -                | -         |   -13.27 | Diviiii, HENU, myltsi, S1rva, teme |
|           14 |     2541 | 2024-03-08 | Astralis Talent             | L   | 0.810      | -            | -                | -                | -         |   -11.25 | HENU, myltsi, podi, S1rva, teme    |
|           13 |     2769 | 2024-03-04 | NOM Esports                 | L   | 0.784      | -            | -                | -                | -         |   -18.03 | HENU, myltsi, podi, S1rva, teme    |
|           12 |     2817 | 2024-03-03 | K10                         | W   | 0.777      | 0.303        | 0.015 (0.004)    | 0.418 (0.098)    | 0 (0.000) |    11.52 | HENU, myltsi, podi, S1rva, teme    |
|           11 |     2971 | 2024-02-29 | Permitta Esports            | L   | 0.756      | -            | -                | -                | -         |    -7.81 | HENU, myltsi, podi, S1rva, teme    |
|           10 |     3035 | 2024-02-27 | K10                         | W   | 0.745      | 0.303        | 0.015 (0.003)    | 0.418 (0.094)    | 0 (0.000) |    11.53 | HENU, myltsi, podi, S1rva, teme    |
|            9 |     3137 | 2024-02-24 | HAVU Gaming                 | W   | 0.726      | 0.143        | 0.024 (0.002)    | 0.213 (0.022)    | 1 (0.726) |    11.89 | HENU, myltsi, podi, S1rva, teme    |
|            8 |     4093 | 2024-02-01 | Sashi Esport                | L   | 0.570      | -            | -                | -                | -         |    -4.16 | HENU, myltsi, podi, S1rva, teme    |
|            7 |     6782 | 2023-11-17 | Zero Tenacity               | L   | 0.064      | -            | -                | -                | -         |    -0.70 | HENU, juissi, myltsi, podi, S1rva  |
|            6 |     6899 | 2023-11-15 | UNiTY esports (Slovak team) | W   | 0.050      | 0.333        | 0.055 (0.001)    | -                | -         |     1.06 | HENU, juissi, myltsi, podi, S1rva  |
|            5 |     6991 | 2023-11-13 | Sashi Esport                | W   | 0.036      | 0.333        | 0.013 (0.000)    | -                | -         |     0.37 | HENU, juissi, myltsi, podi, S1rva  |
|            4 |     7094 | 2023-11-10 | Aurora Young Blud           | L   | 0.018      | -            | -                | -                | -         |    -0.31 | HENU, juissi, myltsi, podi, S1rva  |
|            3 |     7100 | 2023-11-10 | ILIN                        | W   | 0.018      | -            | -                | -                | -         |     0.09 | HENU, juissi, myltsi, podi, S1rva  |
|            2 |     7108 | 2023-11-10 | Entropiq                    | L   | 0.017      | -            | -                | -                | -         |    -0.31 | HENU, juissi, myltsi, podi, S1rva  |
|            1 |     7152 | 2023-11-09 | Pompa Team                  | L   | 0.009      | -            | -                | -                | -         |    -0.26 | HENU, juissi, myltsi, podi, S1rva  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,367.88)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $1,615.77      | $1,615.77       |
| 2024-02-24 |      0.726 | $3,791.78      | $2,752.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
