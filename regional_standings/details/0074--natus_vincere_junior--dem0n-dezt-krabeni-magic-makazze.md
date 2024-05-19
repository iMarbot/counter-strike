### Roster Details<br />
Team Name: Natus Vincere Junior<br />
Roster: dem0n, dezt, Krabeni, Magic, makazze<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [74](../standings_global.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
Final Rank Value:  905.2<br />
<br />
Final Rank Value (905.2) = Starting Rank Value (853.7) + Head To Head Adjustments (51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.384[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.162[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 853.7
- 400 + ( ( 0.229 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 853.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |     1643 | 2024-03-30 | GamerLegion Academy    | L   | 0.957      | -            | -                | -                | -         |   -15.92 | dem0n, dezt, Krabeni, Magic, makazze     |
|           59 |     1669 | 2024-03-29 | Passion UA             | W   | 0.950      | 0.333        | 0.114 (0.036)    | 0.980 (0.310)    | 0 (0.000) |    16.73 | dem0n, dezt, Krabeni, Magic, makazze     |
|           58 |     1679 | 2024-03-29 | Sashi Esport           | W   | 0.949      | 0.333        | 0.055 (0.017)    | 0.256 (0.081)    | 0 (0.000) |    10.86 | dem0n, dezt, Krabeni, Magic, makazze     |
|           57 |     1733 | 2024-03-27 | Metizport              | L   | 0.939      | -            | -                | -                | -         |    -5.66 | dem0n, dezt, Krabeni, Magic, makazze     |
|           56 |     1746 | 2024-03-27 | 9z Team                | W   | 0.938      | -            | -                | -                | 0 (0.000) |    19.84 | dem0n, dezt, Krabeni, Magic, makazze     |
|           55 |     1768 | 2024-03-27 | Astralis Talent        | W   | 0.937      | 0.333        | 0.030 (0.009)    | 0.613 (0.191)    | 0 (0.000) |    14.95 | dem0n, dezt, Krabeni, Magic, makazze     |
|           54 |     1802 | 2024-03-26 | EYEBALLERS             | W   | 0.932      | -            | -                | -                | 0 (0.000) |    17.99 | dem0n, dezt, Krabeni, Magic, makazze     |
|           53 |     1835 | 2024-03-26 | Passion UA             | L   | 0.929      | -            | -                | -                | -         |   -10.11 | dem0n, dezt, Krabeni, Magic, makazze     |
|           52 |     2029 | 2024-03-20 | FORZE Esports          | L   | 0.891      | -            | -                | -                | -         |    -5.37 | dem0n, froz1k, Krabeni, Magic, makazze   |
|           51 |     2159 | 2024-03-17 | Sashi Esport           | W   | 0.869      | 0.333        | 0.055 (0.016)    | -                | 0 (0.000) |    11.52 | dem0n, dezt, Krabeni, Magic, makazze     |
|           50 |     2335 | 2024-03-13 | ENCE Academy           | W   | 0.844      | 0.333        | 0.028 (0.008)    | 0.267 (0.075)    | 0 (0.000) |    13.27 | dem0n, dezt, Krabeni, Magic, makazze     |
|           49 |     2546 | 2024-03-08 | NOM Esports            | L   | 0.809      | -            | -                | -                | -         |   -17.50 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           48 |     2657 | 2024-03-06 | Turów Zgorzelec Esport | W   | 0.796      | 0.303        | -                | 0.640 (0.154)    | 0 (0.000) |    11.31 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           47 |     2707 | 2024-03-05 | Passion UA             | L   | 0.791      | -            | -                | -                | -         |    -9.44 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           46 |     2928 | 2024-03-01 | MOUZ NXT               | W   | 0.763      | 0.303        | 0.215 (0.050)    | 1.000 (0.231)    | 0 (0.000) |    19.16 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           45 |     3067 | 2024-02-26 | ARCRED                 | L   | 0.739      | -            | -                | -                | -         |   -11.59 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           44 |     3109 | 2024-02-25 | Viperio                | W   | 0.730      | -            | -                | -                | 0 (0.000) |     6.91 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           43 |     3373 | 2024-02-20 | Dynamo Eclot           | L   | 0.697      | -            | -                | -                | -         |    -3.61 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           42 |     3431 | 2024-02-19 | Viperio                | W   | 0.689      | -            | -                | -                | -         |     6.88 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           41 |     3460 | 2024-02-18 | Sashi Esport           | W   | 0.684      | 0.303        | 0.055 (0.011)    | -                | -         |    10.29 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           40 |     3494 | 2024-02-17 | Dynamo Eclot           | L   | 0.678      | -            | -                | -                | -         |    -3.13 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           39 |     3509 | 2024-02-17 | Illuminar Gaming       | L   | 0.676      | -            | -                | -                | -         |   -12.47 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           38 |     3590 | 2024-02-15 | Passion UA             | W   | 0.664      | 0.303        | 0.114 (0.023)    | 0.980 (0.197)    | -         |    13.71 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           37 |     3690 | 2024-02-13 | Turów Zgorzelec Esport | L   | 0.650      | -            | -                | -                | -         |   -11.01 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           36 |     3801 | 2024-02-09 | Lilmix                 | W   | 0.624      | 0.303        | -                | 0.604 (0.114)    | -         |     4.32 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           35 |     3932 | 2024-02-04 | Permitta Esports       | W   | 0.590      | 0.303        | 0.063 (0.011)    | 1.000 (0.179)    | -         |    13.45 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           34 |     3982 | 2024-02-03 | 9Pandas                | L   | 0.584      | -            | -                | -                | -         |    -2.56 | dem0n, fnl, Krabeni, Magic, makazze      |
|           33 |     4022 | 2024-02-02 | The Chosen Few         | L   | 0.578      | -            | -                | -                | -         |    -9.95 | dem0n, fnl, Krabeni, Magic, makazze      |
|           32 |     4038 | 2024-02-02 | Zero Tenacity          | L   | 0.578      | -            | -                | -                | -         |    -6.43 | dem0n, fnl, Krabeni, Magic, makazze      |
|           31 |     4048 | 2024-02-02 | The Chosen Few         | W   | 0.577      | -            | -                | -                | -         |     8.16 | dem0n, fnl, Krabeni, Magic, makazze      |
|           30 |     4321 | 2024-01-26 | U Cluj Esports         | W   | 0.531      | -            | -                | -                | -         |     1.44 | dem0n, fnl, Krabeni, Magic, makazze      |
|           29 |     4331 | 2024-01-26 | Jake Bube              | W   | 0.531      | -            | -                | -                | -         |     2.30 | dem0n, fnl, Krabeni, Magic, makazze      |
|           28 |     4704 | 2024-01-17 | EsmagaB                | L   | 0.473      | -            | -                | -                | -         |    -6.50 | dem0n, fnl, Krabeni, Magic, makazze      |
|           27 |     4714 | 2024-01-17 | Copenhagen Wolves      | W   | 0.472      | -            | -                | -                | -         |     3.88 | dem0n, fnl, Krabeni, Magic, makazze      |
|           26 |     4744 | 2024-01-17 | Sashi Esport           | W   | 0.472      | 0.143        | 0.193 (0.013)    | -                | -         |    11.64 | dem0n, fnl, Krabeni, Magic, makazze      |
|           25 |     4750 | 2024-01-17 | MOUZ NXT               | L   | 0.471      | -            | -                | -                | -         |    -2.78 | dem0n, fnl, Krabeni, Magic, makazze      |
|           24 |     4817 | 2024-01-16 | Monte Gen              | L   | 0.464      | -            | -                | -                | -         |    -7.34 | dem0n, fnl, Krabeni, Magic, makazze      |
|           23 |     4895 | 2024-01-13 | The Prodigies          | L   | 0.443      | -            | -                | -                | -         |   -10.73 | dem0n, fnl, Krabeni, Magic, makazze      |
|           22 |     5013 | 2024-01-11 | Lazer Cats             | W   | 0.429      | -            | -                | -                | -         |     1.85 | dem0n, Krabeni, Magic, makazze, qzr      |
|           21 |     5129 | 2024-01-09 | Turów Zgorzelec Esport | W   | 0.416      | 0.333        | -                | 0.640 (0.089)    | -         |     6.26 | dem0n, fnl, Krabeni, Magic, makazze      |
|           20 |     5166 | 2024-01-07 | Viperio                | W   | 0.404      | -            | -                | -                | -         |     2.68 | dem0n, fnl, Krabeni, Magic, makazze      |
|           19 |     5177 | 2024-01-06 | Ex-Anonymo Esports     | W   | 0.398      | -            | -                | -                | -         |     5.87 | dem0n, fnl, Krabeni, Magic, makazze      |
|           18 |     5178 | 2024-01-06 | TY                     | L   | 0.397      | -            | -                | -                | -         |    -8.42 | dem0n, fnl, Krabeni, Magic, makazze      |
|           17 |     5186 | 2024-01-05 | L&G                    | W   | 0.391      | -            | -                | -                | -         |     2.19 | dem0n, fnl, Krabeni, Magic, makazze      |
|           16 |     5188 | 2024-01-05 | The Prodigies          | L   | 0.390      | -            | -                | -                | -         |    -9.85 | dem0n, fnl, Krabeni, Magic, makazze      |
|           15 |     5218 | 2024-01-03 | WOPA Esport            | L   | 0.377      | -            | -                | -                | -         |    -7.21 | dem0n, fnl, Krabeni, Magic, makazze      |
|           14 |     5271 | 2023-12-23 | DOXA Gaming            | W   | 0.305      | -            | -                | -                | -         |     1.14 | dem0n, fnl, Krabeni, Magic, makazze      |
|           13 |     5274 | 2023-12-23 | TY                     | L   | 0.304      | -            | -                | -                | -         |    -6.80 | dem0n, fnl, Krabeni, Magic, makazze      |
|           12 |     5289 | 2023-12-22 | DOXA Gaming            | W   | 0.297      | -            | -                | -                | -         |     1.05 | dem0n, fnl, Krabeni, Magic, makazze      |
|           11 |     5292 | 2023-12-22 | Ex-Anonymo Esports     | L   | 0.296      | -            | -                | -                | -         |    -5.43 | dem0n, fnl, Krabeni, Magic, makazze      |
|           10 |     5300 | 2023-12-21 | NOM Esports            | W   | 0.289      | -            | -                | -                | -         |     2.81 | dem0n, fnl, Krabeni, Magic, makazze      |
|            9 |     5324 | 2023-12-19 | Team Spirit Academy    | L   | 0.276      | -            | -                | -                | -         |    -4.92 | dem0n, fnl, Krabeni, Magic, makazze      |
|            8 |     5508 | 2023-12-16 | NOM Esports            | W   | 0.256      | -            | -                | -                | -         |     2.36 | dem0n, fnl, Krabeni, Magic, makazze      |
|            7 |     5717 | 2023-12-10 | Nexus Gaming           | W   | 0.218      | -            | -                | -                | -         |     4.31 | dem0n, fnl, Krabeni, Magic, makazze      |
|            6 |     5938 | 2023-12-06 | Sashi Esport           | W   | 0.191      | -            | -                | -                | -         |     2.05 | dem0n, fnl, Krabeni, Magic, makazze      |
|            5 |     6493 | 2023-11-24 | AGO esports            | L   | 0.110      | -            | -                | -                | -         |    -2.61 | dem0n, fnl, Krabeni, Magic, makazze      |
|            4 |     6572 | 2023-11-22 | Sashi Esport           | L   | 0.097      | -            | -                | -                | -         |    -2.07 | dem0n, fnl, Krabeni, Magic, makazze      |
|            3 |     6655 | 2023-11-20 | Sprout Academy         | W   | 0.083      | -            | -                | -                | -         |     0.30 | dem0n, fnl, Krabeni, Magic, makazze      |
|            2 |     6838 | 2023-11-16 | L&G                    | W   | 0.057      | -            | -                | -                | -         |     0.21 | dem0n, fnl, Krabeni, Magic, makazze      |
|            1 |     7020 | 2023-11-12 | Sprout Academy         | L   | 0.029      | -            | -                | -                | -         |    -0.82 | dem0n, fnl, Krabeni, Magic, makazze      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,922.22)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-30 |      0.957 | $3,000.00      | $2,870.69       |
| 2024-01-06 |      0.398 | $1,500.00      | $597.43         |
| 2023-12-23 |      0.303 | $1,500.00      | $454.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
