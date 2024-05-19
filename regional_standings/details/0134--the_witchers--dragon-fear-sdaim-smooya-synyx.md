### Roster Details<br />
Team Name: The Witchers<br />
Roster: Dragon, fear, Sdaim, smooya, synyx<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [134](../standings_global.md)<br />
Regional Rank: [93]( ../standings_europe.md)<br />
Final Rank Value:  794.7<br />
<br />
Final Rank Value (794.7) = Starting Rank Value (780.6) + Head To Head Adjustments (14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.407[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 780.6
- 400 + ( ( 0.192 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 780.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |     4776 | 2024-01-16 | EYEBALLERS               | L   | 0.466      | -            | -                | -                | -         |    -4.27 | Dragon, fear, Sdaim, smooya, synyx  |
|           40 |     4782 | 2024-01-16 | Linx Legacy Madagaskar   | W   | 0.466      | -            | -                | -                | 0 (0.000) |     2.20 | Dragon, fear, Sdaim, smooya, synyx  |
|           39 |     4806 | 2024-01-16 | L&G                      | W   | 0.465      | -            | -                | -                | 0 (0.000) |     3.01 | Dragon, fear, Sdaim, smooya, synyx  |
|           38 |     4924 | 2024-01-12 | Gaimin Gladiators        | L   | 0.439      | -            | -                | -                | -         |    -0.43 | Dragon, fear, Sdaim, smooya, synyx  |
|           37 |     4935 | 2024-01-12 | Viperio                  | W   | 0.439      | 0.143        | -                | 0.321 (0.020)    | 0 (0.000) |     3.44 | Dragon, fear, Sdaim, smooya, synyx  |
|           36 |     5058 | 2024-01-10 | IKLA                     | L   | 0.426      | -            | -                | -                | -         |    -8.38 | Dragon, fear, Sdaim, smooya, synyx  |
|           35 |     5114 | 2024-01-09 | Entropiq                 | L   | 0.418      | -            | -                | -                | -         |    -6.85 | Dragon, fear, Sdaim, smooya, synyx  |
|           34 |     5246 | 2023-12-30 | Metizport                | W   | 0.351      | 0.371        | 0.188 (0.024)    | 1.000 (0.130)    | 0 (0.000) |     8.48 | Dragon, fear, Sdaim, smooya, synyx  |
|           33 |     5247 | 2023-12-30 | Alliance                 | W   | 0.350      | 0.371        | 0.017 (0.002)    | 0.729 (0.095)    | 0 (0.000) |     7.01 | Dragon, fear, Sdaim, smooya, synyx  |
|           32 |     5253 | 2023-12-28 | Aurora Young Blud        | W   | 0.338      | 0.371        | 0.017 (0.002)    | 0.422 (0.053)    | 0 (0.000) |     5.99 | Dragon, fear, Sdaim, smooya, synyx  |
|           31 |     5257 | 2023-12-27 | EsmagaB                  | W   | 0.332      | 0.371        | 0.016 (0.002)    | 0.559 (0.069)    | 0 (0.000) |     6.58 | Dragon, fear, Sdaim, smooya, synyx  |
|           30 |     5332 | 2023-12-18 | NOM Esports              | L   | 0.269      | -            | -                | -                | -         |    -5.24 | Dragon, fear, Sdaim, smooya, synyx  |
|           29 |     5451 | 2023-12-16 | INGLORIOUS               | L   | 0.259      | -            | -                | -                | -         |    -4.02 | bevve, fear, Sdaim, smooya, synyx   |
|           28 |     5491 | 2023-12-16 | Team Spirit Academy      | L   | 0.257      | -            | -                | -                | -         |    -3.88 | Dragon, fear, Sdaim, smooya, synyx  |
|           27 |     5618 | 2023-12-14 | Zero Tenacity            | W   | 0.243      | 0.333        | 0.095 (0.008)    | 1.000 (0.081)    | 0 (0.000) |     5.57 | Dragon, fear, Sdaim, smooya, synyx  |
|           26 |     5678 | 2023-12-12 | Illuminar Gaming         | W   | 0.231      | -            | -                | -                | 0 (0.000) |     3.37 | Dragon, fear, Sdaim, smooya, synyx  |
|           25 |     5735 | 2023-12-10 | Passion UA               | L   | 0.217      | -            | -                | -                | -         |    -1.49 | fear, Sdaim, smooya, soulfly, synyx |
|           24 |     5835 | 2023-12-08 | Sashi Esport             | L   | 0.205      | -            | -                | -                | -         |    -1.03 | Dragon, fear, Sdaim, smooya, synyx  |
|           23 |     5927 | 2023-12-06 | ALTERNATE aTTaX          | L   | 0.192      | -            | -                | -                | -         |    -1.02 | fear, Sdaim, smooya, soulfly, synyx |
|           22 |     5991 | 2023-12-05 | RUSH B (Russian team)    | L   | 0.185      | -            | -                | -                | -         |    -2.95 | fear, Sdaim, smooya, soulfly, synyx |
|           21 |     6023 | 2023-12-04 | Endpoint                 | L   | 0.177      | -            | -                | -                | -         |    -2.35 | fear, Sdaim, smooya, soulfly, synyx |
|           20 |     6139 | 2023-12-02 | M1X                      | W   | 0.163      | -            | -                | -                | 0 (0.000) |     1.58 | fear, Sdaim, smooya, soulfly, synyx |
|           19 |     6163 | 2023-12-01 | ARCRED                   | L   | 0.158      | -            | -                | -                | -         |    -2.20 | fear, Sdaim, smooya, soulfly, synyx |
|           18 |     6201 | 2023-11-30 | ENTERPRISE esports       | W   | 0.152      | 0.371        | 0.039 (0.002)    | 0.476 (0.027)    | -         |     3.44 | fear, Sdaim, smooya, soulfly, synyx |
|           17 |     6224 | 2023-11-30 | Into The Breach          | W   | 0.149      | 0.371        | 0.022 (0.001)    | -                | -         |     2.51 | fear, Sdaim, smooya, soulfly, synyx |
|           16 |     6244 | 2023-11-29 | BLESSED (Ukrainian team) | W   | 0.146      | 0.371        | 0.018 (0.001)    | 0.781 (0.042)    | -         |     2.61 | fear, Sdaim, smooya, soulfly, synyx |
|           15 |     6254 | 2023-11-29 | ALTERNATE aTTaX          | W   | 0.145      | 0.371        | 0.110 (0.006)    | 0.723 (0.039)    | -         |     3.84 | fear, Sdaim, smooya, soulfly, synyx |
|           14 |     6328 | 2023-11-28 | GODSENT                  | L   | 0.138      | -            | -                | -                | -         |    -2.07 | fear, Sdaim, smooya, soulfly, synyx |
|           13 |     6366 | 2023-11-27 | For The Win Esports      | L   | 0.132      | -            | -                | -                | -         |    -2.65 | fear, Sdaim, smooya, soulfly, synyx |
|           12 |     6375 | 2023-11-27 | DMS                      | W   | 0.131      | 0.371        | -                | 0.504 (0.025)    | -         |     1.31 | fear, Sdaim, smooya, soulfly, synyx |
|           11 |     6552 | 2023-11-22 | BIG Academy              | L   | 0.099      | -            | -                | -                | -         |    -1.42 | fear, Sdaim, smooya, soulfly, synyx |
|           10 |     6661 | 2023-11-19 | GenOne                   | W   | 0.079      | -            | -                | -                | -         |     0.72 | fear, Sdaim, smooya, soulfly, synyx |
|            9 |     6671 | 2023-11-19 | Team Spirit Academy      | W   | 0.078      | -            | -                | -                | -         |     1.29 | fear, Sdaim, smooya, soulfly, synyx |
|            8 |     6702 | 2023-11-18 | TUSTE CHOPAKI            | W   | 0.072      | -            | -                | -                | -         |     0.37 | fear, Sdaim, smooya, soulfly, synyx |
|            7 |     6711 | 2023-11-18 | Heimo Esports            | W   | 0.072      | -            | -                | -                | -         |     0.98 | fear, Sdaim, smooya, soulfly, synyx |
|            6 |     6778 | 2023-11-17 | Turów Zgorzelec Esport   | W   | 0.064      | -            | -                | -                | -         |     1.15 | fear, Sdaim, smooya, soulfly, synyx |
|            5 |     6987 | 2023-11-13 | Team Space               | L   | 0.037      | -            | -                | -                | -         |    -0.64 | fear, Sdaim, smooya, soulfly, synyx |
|            4 |     7009 | 2023-11-12 | FORZE Esports            | L   | 0.031      | -            | -                | -                | -         |    -0.49 | fear, Sdaim, smooya, soulfly, synyx |
|            3 |     7096 | 2023-11-10 | Ex-sYnck                 | L   | 0.018      | -            | -                | -                | -         |    -0.44 | fear, Sdaim, smooya, soulfly, synyx |
|            2 |     7139 | 2023-11-09 | Gaimin Gladiators        | W   | 0.011      | 0.435        | 0.194 (0.001)    | -                | -         |     0.35 | fear, Sdaim, smooya, soulfly, synyx |
|            1 |     7167 | 2023-11-08 | Entropiq                 | W   | 0.006      | -            | -                | -                | -         |     0.09 | fear, Sdaim, smooya, soulfly, synyx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,501.88)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-30 |      0.351 | $15,000.00     | $5,265.97       |
| 2023-11-19 |      0.079 | $3,000.00      | $235.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
