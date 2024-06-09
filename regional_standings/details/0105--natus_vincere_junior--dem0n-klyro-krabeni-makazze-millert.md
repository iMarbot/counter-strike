### Roster Details<br />
Team Name: Natus Vincere Junior<br />
Roster: dem0n, klyrO, Krabeni, makazze, millert<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [105](../standings_global.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
Final Rank Value:  861.9<br />
<br />
Final Rank Value (861.9) = Starting Rank Value (798.2) + Head To Head Adjustments (63.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.121[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.196<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 798.2
- 400 + ( ( 0.196 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 798.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |     3175 | 2024-04-11 | Verdant                   | L   | 0.877      | -            | -                | -                | -         |   -11.97 | dem0n, klyrO, Krabeni, makazze, millert  |
|           58 |     3774 | 2024-03-30 | GamerLegion Academy       | L   | 0.796      | -            | -                | -                | -         |   -12.97 | dem0n, dezt, Krabeni, Magic, makazze     |
|           57 |     3804 | 2024-03-29 | Passion UA                | W   | 0.789      | 0.333        | 0.057 (0.015)    | 1.000 (0.263)    | 0 (0.000) |    15.08 | dem0n, dezt, Krabeni, Magic, makazze     |
|           56 |     3815 | 2024-03-29 | Sashi Esport              | W   | 0.788      | 0.333        | 0.024 (0.006)    | -                | 0 (0.000) |    10.61 | dem0n, dezt, Krabeni, Magic, makazze     |
|           55 |     3881 | 2024-03-27 | Metizport                 | L   | 0.778      | -            | -                | -                | -         |    -5.76 | dem0n, dezt, Krabeni, Magic, makazze     |
|           54 |     3895 | 2024-03-27 | 9z Team                   | W   | 0.777      | 0.143        | 0.107 (0.012)    | 0.547 (0.061)    | 0 (0.000) |    22.14 | dem0n, dezt, Krabeni, Magic, makazze     |
|           53 |     3920 | 2024-03-27 | Astralis Talent           | W   | 0.776      | 0.333        | 0.012 (0.003)    | 0.452 (0.117)    | 0 (0.000) |    13.79 | dem0n, dezt, Krabeni, Magic, makazze     |
|           52 |     3962 | 2024-03-26 | EYEBALLERS                | W   | 0.771      | 0.143        | -                | 0.508 (0.056)    | 0 (0.000) |    15.29 | dem0n, dezt, Krabeni, Magic, makazze     |
|           51 |     4001 | 2024-03-26 | Passion UA                | L   | 0.768      | -            | -                | -                | -         |    -7.42 | dem0n, dezt, Krabeni, Magic, makazze     |
|           50 |     4239 | 2024-03-20 | FORZE Esports             | L   | 0.730      | -            | -                | -                | -         |    -5.22 | dem0n, froz1k, Krabeni, Magic, makazze   |
|           49 |     4402 | 2024-03-17 | Sashi Esport              | W   | 0.708      | 0.333        | 0.024 (0.006)    | -                | 0 (0.000) |     9.92 | dem0n, dezt, Krabeni, Magic, makazze     |
|           48 |     4625 | 2024-03-13 | ENCE Academy              | W   | 0.682      | 0.333        | -                | 0.337 (0.077)    | 0 (0.000) |    11.26 | dem0n, dezt, Krabeni, Magic, makazze     |
|           47 |     4897 | 2024-03-08 | NOM Esports               | L   | 0.648      | -            | -                | -                | -         |   -14.50 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           46 |     5053 | 2024-03-06 | ex-Turów Zgorzelec Esport | W   | 0.635      | 0.303        | -                | 0.491 (0.094)    | 0 (0.000) |     9.29 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           45 |     5115 | 2024-03-05 | Passion UA                | L   | 0.629      | -            | -                | -                | -         |    -6.43 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           44 |     5395 | 2024-03-01 | MOUZ NXT                  | W   | 0.602      | 0.303        | 0.157 (0.029)    | 0.977 (0.178)    | 0 (0.000) |    16.00 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           43 |     5564 | 2024-02-26 | ARCRED                    | L   | 0.578      | -            | -                | -                | -         |    -9.47 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           42 |     5620 | 2024-02-25 | Viperio                   | W   | 0.569      | -            | -                | -                | 0 (0.000) |     5.54 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           41 |     5955 | 2024-02-20 | Dynamo Eclot              | L   | 0.536      | -            | -                | -                | -         |    -2.96 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           40 |     6026 | 2024-02-19 | Viperio                   | W   | 0.528      | -            | -                | -                | -         |     5.36 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           39 |     6061 | 2024-02-18 | Sashi Esport              | W   | 0.522      | 0.303        | 0.024 (0.004)    | -                | -         |     7.84 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           38 |     6117 | 2024-02-17 | Dynamo Eclot              | L   | 0.517      | -            | -                | -                | -         |    -2.65 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           37 |     6134 | 2024-02-17 | brazylijski luz           | L   | 0.515      | -            | -                | -                | -         |    -8.39 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           36 |     6230 | 2024-02-15 | Passion UA                | W   | 0.503      | 0.303        | 0.057 (0.009)    | 1.000 (0.152)    | -         |    11.43 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           35 |     6354 | 2024-02-13 | ex-Turów Zgorzelec Esport | L   | 0.489      | -            | -                | -                | -         |    -8.22 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           34 |     6498 | 2024-02-09 | Lilmix                    | W   | 0.463      | 0.303        | -                | 0.593 (0.083)    | -         |     8.28 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           33 |     6676 | 2024-02-04 | Permitta Esports          | W   | 0.429      | 0.303        | 0.025 (0.003)    | 1.000 (0.130)    | -         |     9.72 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           32 |     6751 | 2024-02-03 | 9Pandas                   | L   | 0.423      | -            | -                | -                | -         |    -1.28 | dem0n, fnl, Krabeni, Magic, makazze      |
|           31 |     6802 | 2024-02-02 | The Chosen Few            | L   | 0.417      | -            | -                | -                | -         |    -7.50 | dem0n, fnl, Krabeni, Magic, makazze      |
|           30 |     6827 | 2024-02-02 | Zero Tenacity             | L   | 0.417      | -            | -                | -                | -         |    -2.59 | dem0n, fnl, Krabeni, Magic, makazze      |
|           29 |     6839 | 2024-02-02 | The Chosen Few            | W   | 0.416      | -            | -                | -                | -         |     5.64 | dem0n, fnl, Krabeni, Magic, makazze      |
|           28 |     7265 | 2024-01-26 | U Cluj Esports            | W   | 0.370      | -            | -                | -                | -         |     1.21 | dem0n, fnl, Krabeni, Magic, makazze      |
|           27 |     7277 | 2024-01-26 | Jake Bube                 | W   | 0.370      | -            | -                | -                | -         |     1.85 | dem0n, fnl, Krabeni, Magic, makazze      |
|           26 |     7773 | 2024-01-17 | esmagaB                   | L   | 0.312      | -            | -                | -                | -         |    -4.00 | dem0n, fnl, Krabeni, Magic, makazze      |
|           25 |     7786 | 2024-01-17 | Copenhagen Wolves         | W   | 0.311      | -            | -                | -                | -         |     3.21 | dem0n, fnl, Krabeni, Magic, makazze      |
|           24 |     7821 | 2024-01-17 | Sashi Esport              | W   | 0.311      | 0.143        | 0.154 (0.007)    | -                | -         |     8.00 | dem0n, fnl, Krabeni, Magic, makazze      |
|           23 |     7830 | 2024-01-17 | MOUZ NXT                  | L   | 0.309      | -            | -                | -                | -         |    -1.33 | dem0n, fnl, Krabeni, Magic, makazze      |
|           22 |     7935 | 2024-01-16 | Monte Gen                 | L   | 0.302      | -            | -                | -                | -         |    -4.75 | dem0n, fnl, Krabeni, Magic, makazze      |
|           21 |     8010 | 2024-01-14 | lajtbitexe                | W   | 0.289      | -            | -                | -                | -         |     2.75 | dem0n, fnl, Krabeni, Magic, makazze      |
|           20 |     8049 | 2024-01-13 | The Prodigies             | L   | 0.282      | -            | -                | -                | -         |    -6.76 | dem0n, fnl, Krabeni, Magic, makazze      |
|           19 |     8209 | 2024-01-11 | Lazer Cats                | W   | 0.268      | -            | -                | -                | -         |     1.34 | dem0n, Krabeni, Magic, makazze, qzr      |
|           18 |     8395 | 2024-01-09 | ex-Turów Zgorzelec Esport | W   | 0.255      | -            | -                | -                | -         |     4.10 | dem0n, fnl, Krabeni, Magic, makazze      |
|           17 |     8449 | 2024-01-07 | Viperio                   | W   | 0.242      | -            | -                | -                | -         |     1.87 | dem0n, fnl, Krabeni, Magic, makazze      |
|           16 |     8464 | 2024-01-06 | ex-Anonymo Esports        | W   | 0.237      | -            | -                | -                | -         |     2.98 | dem0n, fnl, Krabeni, Magic, makazze      |
|           15 |     8465 | 2024-01-06 | TY                        | L   | 0.236      | -            | -                | -                | -         |    -4.96 | dem0n, fnl, Krabeni, Magic, makazze      |
|           14 |     8476 | 2024-01-05 | L&G                       | W   | 0.230      | -            | -                | -                | -         |     1.41 | dem0n, fnl, Krabeni, Magic, makazze      |
|           13 |     8478 | 2024-01-05 | The Prodigies             | L   | 0.229      | -            | -                | -                | -         |    -5.64 | dem0n, fnl, Krabeni, Magic, makazze      |
|           12 |     8522 | 2024-01-03 | WOPA Esport               | L   | 0.216      | -            | -                | -                | -         |    -3.19 | dem0n, fnl, Krabeni, Magic, makazze      |
|           11 |     8587 | 2023-12-23 | aimclub                   | W   | 0.144      | -            | -                | -                | -         |     0.66 | dem0n, fnl, Krabeni, Magic, makazze      |
|           10 |     8590 | 2023-12-23 | TY                        | L   | 0.143      | -            | -                | -                | -         |    -3.09 | dem0n, fnl, Krabeni, Magic, makazze      |
|            9 |     8610 | 2023-12-22 | aimclub                   | W   | 0.136      | -            | -                | -                | -         |     0.61 | dem0n, fnl, Krabeni, Magic, makazze      |
|            8 |     8613 | 2023-12-22 | ex-Anonymo Esports        | L   | 0.135      | -            | -                | -                | -         |    -2.66 | dem0n, fnl, Krabeni, Magic, makazze      |
|            7 |     8633 | 2023-12-21 | NOM Esports               | W   | 0.128      | -            | -                | -                | -         |     1.21 | dem0n, fnl, Krabeni, Magic, makazze      |
|            6 |     8640 | 2023-12-20 | Sashi Esport              | W   | 0.123      | -            | -                | -                | -         |     0.80 | dem0n, fnl, Krabeni, Magic, makazze      |
|            5 |     8665 | 2023-12-19 | Team Spirit Academy       | L   | 0.115      | -            | -                | -                | -         |    -2.13 | dem0n, fnl, Krabeni, Magic, makazze      |
|            4 |     8914 | 2023-12-16 | NOM Esports               | W   | 0.095      | -            | -                | -                | -         |     0.89 | dem0n, fnl, Krabeni, Magic, makazze      |
|            3 |     9083 | 2023-12-13 | cs2Ctonjeu                | L   | 0.078      | -            | -                | -                | -         |    -1.85 | dem0n, fnl, Krabeni, Magic, makazze      |
|            2 |     9225 | 2023-12-10 | Nexus Gaming              | W   | 0.057      | -            | -                | -                | -         |     1.18 | dem0n, fnl, Krabeni, Magic, makazze      |
|            1 |     9511 | 2023-12-06 | Sashi Esport              | W   | 0.030      | -            | -                | -                | -         |     0.19 | dem0n, fnl, Krabeni, Magic, makazze      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,964.58)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-30 |      0.796 | $3,000.00      | $2,387.50       |
| 2024-01-07 |      0.243 | $1,500.00      | $364.58         |
| 2023-12-23 |      0.142 | $1,500.00      | $212.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
