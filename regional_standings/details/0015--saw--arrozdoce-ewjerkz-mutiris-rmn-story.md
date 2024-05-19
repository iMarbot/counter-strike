### Roster Details<br />
Team Name: SAW<br />
Roster: arrozdoce, ewjerkz, MUTiRiS, rmn, story<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [15](../standings_global.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
Final Rank Value:  1469.0<br />
<br />
Final Rank Value (1469.0) = Starting Rank Value (1489.2) + Head To Head Adjustments (-20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.633[<sup>1</sup>](#table2)
- Bounty Collected: 0.575[<sup>2</sup>](#table1)
- Opponent Network: 0.307[<sup>2</sup>](#table1)
- LAN Wins: 0.681[<sup>2</sup>](#table1)

The average of these factors is 0.549<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1489.2
- 400 + ( ( 0.549 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1489.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      315 | 2024-04-28 | Virtus.pro             | L   | 1.000      | -            | -                | -                | -         |    -7.94 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           49 |      358 | 2024-04-27 | Eternal Fire           | W   | 1.000      | 0.889        | 0.409 (0.364)    | 0.462 (0.411)    | 1 (1.000) |    26.04 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           48 |      433 | 2024-04-26 | Imperial Esports       | W   | 1.000      | 0.889        | 0.674 (0.599)    | 0.549 (0.488)    | 1 (1.000) |    16.05 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           47 |      538 | 2024-04-24 | Virtus.pro             | L   | 1.000      | -            | -                | -                | -         |    -6.96 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           46 |     1021 | 2024-04-16 | Team Sampi             | L   | 1.000      | -            | -                | -                | -         |   -28.81 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           45 |     1217 | 2024-04-10 | 9Pandas                | W   | 1.000      | 0.500        | 0.085 (0.043)    | 0.661 (0.330)    | -         |     3.80 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           44 |     1454 | 2024-04-05 | Turów Zgorzelec Esport | W   | 0.996      | 0.384        | -                | 0.640 (0.245)    | -         |     0.74 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           43 |     1486 | 2024-04-04 | Betera Esports         | W   | 0.992      | -            | -                | -                | -         |     1.23 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           42 |     1539 | 2024-04-03 | Pera Esports           | W   | 0.984      | 0.500        | 0.065 (0.032)    | -                | -         |     1.23 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           41 |     2025 | 2024-03-20 | FURIA Esports          | L   | 0.892      | -            | -                | -                | -         |   -10.14 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           40 |     2064 | 2024-03-19 | PaiN Gaming            | L   | 0.884      | -            | -                | -                | -         |   -25.26 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           39 |     2093 | 2024-03-18 | Cloud9                 | L   | 0.878      | -            | -                | -                | -         |    -5.73 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           38 |     2114 | 2024-03-17 | GamerLegion            | W   | 0.873      | 1.000        | 0.194 (0.169)    | 0.419 (0.366)    | 1 (0.873) |    15.09 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           37 |     2142 | 2024-03-17 | KOI                    | W   | 0.871      | 1.000        | 0.066 (0.058)    | 0.537 (0.468)    | 1 (0.871) |     2.96 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           36 |     2308 | 2024-03-13 | System5                | W   | 0.846      | -            | -                | -                | -         |     0.16 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           35 |     2457 | 2024-03-10 | OG                     | W   | 0.825      | 0.535        | 0.594 (0.262)    | 0.390 (0.172)    | -         |     7.98 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           34 |     2525 | 2024-03-08 | Cloud9                 | W   | 0.812      | 0.535        | 0.487 (0.212)    | 0.419 (0.182)    | -         |    21.23 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           33 |     2578 | 2024-03-07 | Team Liquid            | W   | 0.804      | 0.535        | 0.125 (0.054)    | 0.546 (0.235)    | -         |     9.76 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           32 |     3068 | 2024-02-26 | RUSH B (Russian team)  | W   | 0.739      | 0.500        | -                | 0.471 (0.174)    | -         |     0.51 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           31 |     3499 | 2024-02-17 | Fnatic                 | W   | 0.678      | 0.143        | 0.334 (0.032)    | -                | 1 (0.678) |     4.78 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           30 |     3525 | 2024-02-16 | ENTERPRISE esports     | W   | 0.672      | -            | -                | -                | 1 (0.672) |     1.24 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           29 |     3596 | 2024-02-15 | Ninjas in Pyjamas      | W   | 0.664      | -            | -                | -                | 1 (0.664) |     0.62 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           28 |     3633 | 2024-02-14 | 9Pandas                | L   | 0.658      | -            | -                | -                | -         |   -17.69 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           27 |     3655 | 2024-02-14 | Virtus.pro             | L   | 0.657      | -            | -                | -                | -         |    -4.14 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           26 |     3925 | 2024-02-04 | Rhyno Esports          | W   | 0.591      | -            | -                | -                | -         |     0.84 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           25 |     3994 | 2024-02-03 | KOI                    | W   | 0.584      | -            | -                | -                | -         |     1.92 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           24 |     4069 | 2024-02-01 | AL-QATRAO              | W   | 0.572      | -            | -                | -                | -         |     0.24 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           23 |     4071 | 2024-02-01 | The Agency Clan        | W   | 0.572      | -            | -                | -                | -         |     0.09 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           22 |     4077 | 2024-02-01 | AL-QATRAO              | L   | 0.571      | -            | -                | -                | -         |   -17.77 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           21 |     4556 | 2024-01-20 | 9Pandas                | W   | 0.491      | -            | -                | -                | -         |     1.99 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           20 |     4605 | 2024-01-19 | Zero Tenacity          | W   | 0.484      | -            | -                | -                | -         |     0.73 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           19 |     4651 | 2024-01-18 | Virtus.pro             | L   | 0.478      | -            | -                | -                | -         |    -3.19 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           18 |     4660 | 2024-01-18 | Fnatic                 | W   | 0.478      | -            | -                | -                | -         |     2.82 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           17 |     5703 | 2023-12-11 | FORZE Esports          | L   | 0.224      | -            | -                | -                | -         |    -6.88 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           16 |     5949 | 2023-12-06 | 9Pandas                | L   | 0.190      | -            | -                | -                | -         |    -5.25 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           15 |     6007 | 2023-12-05 | RED Canids             | W   | 0.183      | -            | -                | -                | -         |     0.23 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           14 |     6019 | 2023-12-04 | Zero Tenacity          | W   | 0.177      | -            | -                | -                | -         |     0.29 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           13 |     6046 | 2023-12-03 | Aurora Gaming          | L   | 0.171      | -            | -                | -                | -         |    -1.73 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           12 |     6162 | 2023-12-01 | Team Space             | W   | 0.158      | -            | -                | -                | -         |     0.07 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           11 |     6218 | 2023-11-30 | 9Pandas                | W   | 0.150      | -            | -                | -                | -         |     0.57 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           10 |     6396 | 2023-11-26 | Legacy                 | W   | 0.124      | -            | -                | -                | 1 (0.124) |     0.47 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            9 |     6434 | 2023-11-25 | Rhyno Esports          | W   | 0.118      | -            | -                | -                | 1 (0.118) |     0.17 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            8 |     6476 | 2023-11-24 | Los Alpacas            | W   | 0.111      | -            | -                | -                | 1 (0.111) |     0.03 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            7 |     6527 | 2023-11-23 | Sashi Esport           | W   | 0.104      | -            | -                | -                | -         |     0.33 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            6 |     6793 | 2023-11-17 | Metizport              | L   | 0.063      | -            | -                | -                | -         |    -1.85 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            5 |     6829 | 2023-11-16 | Entropiq               | W   | 0.058      | -            | -                | -                | -         |     0.04 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            4 |     6889 | 2023-11-15 | Pompa Team             | W   | 0.051      | -            | -                | -                | -         |     0.01 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            3 |     6997 | 2023-11-12 | KOI                    | L   | 0.032      | -            | -                | -                | -         |    -0.93 | aragornN, arrozdoce, ewjerkz, rmn, story  |
|            2 |     7050 | 2023-11-11 | Fantazeri              | W   | 0.025      | -            | -                | -                | -         |     0.01 | aragornN, arrozdoce, ewjerkz, rmn, story  |
|            1 |     7181 | 2023-11-08 | FORZE Esports          | L   | 0.005      | -            | -                | -                | -         |    -0.16 | aragornN, arrozdoce, ewjerkz, rmn, story  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($41,635.17)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.26) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-03-31 |      0.965 | $10,000.00     | $9,652.31       |
| 2024-03-10 |      0.826 | $20,000.00     | $16,511.57      |
| 2023-12-13 |      0.239 | $500.00        | $119.29         |
| 2023-12-10 |      0.219 | $3,500.00      | $764.98         |
| 2023-12-07 |      0.199 | $5,000.00      | $994.10         |
| 2023-11-26 |      0.124 | $5,474.63      | $681.03         |
| 2023-11-25 |      0.118 | $6,569.55      | $772.53         |
| 2023-11-18 |      0.070 | $2,000.00      | $139.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
