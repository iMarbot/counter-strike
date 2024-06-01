### Roster Details<br />
Team Name: Natus Vincere Junior<br />
Roster: dem0n, dezt, Krabeni, Magic, makazze<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [98](../standings_global.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
Final Rank Value:  872.2<br />
<br />
Final Rank Value (872.2) = Starting Rank Value (797.7) + Head To Head Adjustments (74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.118[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.195<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 797.7
- 400 + ( ( 0.195 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 797.7


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
|           58 |     3681 | 2024-03-30 | GamerLegion Academy       | L   | 0.796      | -            | -                | -                | -         |   -12.83 | dem0n, dezt, Krabeni, Magic, makazze     |
|           57 |     3710 | 2024-03-29 | Passion UA                | W   | 0.789      | 0.333        | 0.057 (0.015)    | 1.000 (0.263)    | 0 (0.000) |    14.98 | dem0n, dezt, Krabeni, Magic, makazze     |
|           56 |     3721 | 2024-03-29 | Sashi Esport              | W   | 0.788      | 0.333        | 0.024 (0.006)    | -                | 0 (0.000) |    10.54 | dem0n, dezt, Krabeni, Magic, makazze     |
|           55 |     3788 | 2024-03-27 | Metizport                 | L   | 0.778      | -            | -                | -                | -         |    -5.43 | dem0n, dezt, Krabeni, Magic, makazze     |
|           54 |     3802 | 2024-03-27 | 9z Team                   | W   | 0.777      | 0.143        | 0.107 (0.012)    | 0.547 (0.061)    | 0 (0.000) |    22.16 | dem0n, dezt, Krabeni, Magic, makazze     |
|           53 |     3827 | 2024-03-27 | Astralis Talent           | W   | 0.776      | 0.333        | 0.012 (0.003)    | 0.452 (0.117)    | 0 (0.000) |    13.73 | dem0n, dezt, Krabeni, Magic, makazze     |
|           52 |     3865 | 2024-03-26 | EYEBALLERS                | W   | 0.771      | 0.143        | -                | 0.508 (0.056)    | 0 (0.000) |    15.32 | dem0n, dezt, Krabeni, Magic, makazze     |
|           51 |     3904 | 2024-03-26 | Passion UA                | L   | 0.768      | -            | -                | -                | -         |    -7.52 | dem0n, dezt, Krabeni, Magic, makazze     |
|           50 |     4137 | 2024-03-20 | FORZE Esports             | L   | 0.730      | -            | -                | -                | -         |    -4.97 | dem0n, froz1k, Krabeni, Magic, makazze   |
|           49 |     4296 | 2024-03-17 | Sashi Esport              | W   | 0.708      | 0.333        | 0.024 (0.006)    | -                | 0 (0.000) |     9.86 | dem0n, dezt, Krabeni, Magic, makazze     |
|           48 |     4509 | 2024-03-13 | ENCE Academy              | W   | 0.682      | 0.333        | -                | 0.337 (0.077)    | 0 (0.000) |    11.26 | dem0n, dezt, Krabeni, Magic, makazze     |
|           47 |     4769 | 2024-03-08 | NOM Esports               | L   | 0.648      | -            | -                | -                | -         |   -14.48 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           46 |     4914 | 2024-03-06 | ex-Turów Zgorzelec Esport | W   | 0.635      | 0.303        | -                | 0.375 (0.072)    | 0 (0.000) |     8.86 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           45 |     4971 | 2024-03-05 | Passion UA                | L   | 0.629      | -            | -                | -                | -         |    -6.54 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           44 |     5246 | 2024-03-01 | MOUZ NXT                  | W   | 0.602      | 0.303        | 0.157 (0.029)    | 0.950 (0.173)    | 0 (0.000) |    15.88 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           43 |     5407 | 2024-02-26 | ARCRED                    | L   | 0.578      | -            | -                | -                | -         |    -9.44 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           42 |     5462 | 2024-02-25 | Viperio                   | W   | 0.569      | -            | -                | -                | 0 (0.000) |     5.33 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           41 |     5785 | 2024-02-20 | Dynamo Eclot              | L   | 0.536      | -            | -                | -                | -         |    -2.99 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           40 |     5854 | 2024-02-19 | Viperio                   | W   | 0.528      | -            | -                | -                | -         |     5.16 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           39 |     5888 | 2024-02-18 | Sashi Esport              | W   | 0.522      | 0.303        | 0.024 (0.004)    | -                | -         |     7.79 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           38 |     5944 | 2024-02-17 | Dynamo Eclot              | L   | 0.517      | -            | -                | -                | -         |    -2.69 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           37 |     5961 | 2024-02-17 | brazylijski luz           | L   | 0.515      | -            | -                | -                | -         |    -8.57 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           36 |     6049 | 2024-02-15 | Passion UA                | W   | 0.503      | 0.303        | 0.057 (0.009)    | 1.000 (0.152)    | -         |    11.29 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           35 |     6169 | 2024-02-13 | ex-Turów Zgorzelec Esport | L   | 0.489      | -            | -                | -                | -         |    -8.64 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           34 |     6310 | 2024-02-09 | Lilmix                    | W   | 0.463      | 0.303        | -                | 0.581 (0.081)    | -         |     8.59 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           33 |     6473 | 2024-02-04 | Permitta Esports          | W   | 0.429      | 0.303        | 0.029 (0.004)    | 1.000 (0.130)    | -         |     9.63 | alkarenn, dem0n, Krabeni, Magic, makazze |
|           32 |     6548 | 2024-02-03 | 9Pandas                   | L   | 0.423      | -            | -                | -                | -         |    -1.35 | dem0n, fnl, Krabeni, Magic, makazze      |
|           31 |     6599 | 2024-02-02 | The Chosen Few            | L   | 0.417      | -            | -                | -                | -         |    -7.14 | dem0n, fnl, Krabeni, Magic, makazze      |
|           30 |     6622 | 2024-02-02 | Zero Tenacity             | L   | 0.417      | -            | -                | -                | -         |    -2.40 | dem0n, fnl, Krabeni, Magic, makazze      |
|           29 |     6634 | 2024-02-02 | The Chosen Few            | W   | 0.416      | -            | -                | -                | -         |     6.02 | dem0n, fnl, Krabeni, Magic, makazze      |
|           28 |     7041 | 2024-01-26 | U Cluj Esports            | W   | 0.370      | -            | -                | -                | -         |     1.21 | dem0n, fnl, Krabeni, Magic, makazze      |
|           27 |     7051 | 2024-01-26 | Jake Bube                 | W   | 0.370      | -            | -                | -                | -         |     1.86 | dem0n, fnl, Krabeni, Magic, makazze      |
|           26 |     7524 | 2024-01-17 | esmagaB                   | L   | 0.312      | -            | -                | -                | -         |    -4.03 | dem0n, fnl, Krabeni, Magic, makazze      |
|           25 |     7537 | 2024-01-17 | Copenhagen Wolves         | W   | 0.311      | -            | -                | -                | -         |     2.90 | dem0n, fnl, Krabeni, Magic, makazze      |
|           24 |     7572 | 2024-01-17 | Sashi Esport              | W   | 0.311      | 0.143        | 0.172 (0.008)    | -                | -         |     8.01 | dem0n, fnl, Krabeni, Magic, makazze      |
|           23 |     7581 | 2024-01-17 | MOUZ NXT                  | L   | 0.309      | -            | -                | -                | -         |    -1.36 | dem0n, fnl, Krabeni, Magic, makazze      |
|           22 |     7686 | 2024-01-16 | Monte Gen                 | L   | 0.302      | -            | -                | -                | -         |    -4.76 | dem0n, fnl, Krabeni, Magic, makazze      |
|           21 |     7757 | 2024-01-14 | lajtbitexe                | W   | 0.289      | -            | -                | -                | -         |     2.56 | dem0n, fnl, Krabeni, Magic, makazze      |
|           20 |     7796 | 2024-01-13 | The Prodigies             | L   | 0.282      | -            | -                | -                | -         |    -6.76 | dem0n, fnl, Krabeni, Magic, makazze      |
|           19 |     7956 | 2024-01-11 | Lazer Cats                | W   | 0.268      | -            | -                | -                | -         |     1.35 | dem0n, Krabeni, Magic, makazze, qzr      |
|           18 |     8141 | 2024-01-09 | ex-Turów Zgorzelec Esport | W   | 0.255      | -            | -                | -                | -         |     3.86 | dem0n, fnl, Krabeni, Magic, makazze      |
|           17 |     8194 | 2024-01-07 | Viperio                   | W   | 0.242      | -            | -                | -                | -         |     1.86 | dem0n, fnl, Krabeni, Magic, makazze      |
|           16 |     8209 | 2024-01-06 | ex-Anonymo Esports        | W   | 0.237      | -            | -                | -                | -         |     2.98 | dem0n, fnl, Krabeni, Magic, makazze      |
|           15 |     8210 | 2024-01-06 | TY                        | L   | 0.236      | -            | -                | -                | -         |    -4.96 | dem0n, fnl, Krabeni, Magic, makazze      |
|           14 |     8221 | 2024-01-05 | L&G                       | W   | 0.230      | -            | -                | -                | -         |     1.37 | dem0n, fnl, Krabeni, Magic, makazze      |
|           13 |     8223 | 2024-01-05 | The Prodigies             | L   | 0.229      | -            | -                | -                | -         |    -5.64 | dem0n, fnl, Krabeni, Magic, makazze      |
|           12 |     8266 | 2024-01-03 | WOPA Esport               | L   | 0.216      | -            | -                | -                | -         |    -3.19 | dem0n, fnl, Krabeni, Magic, makazze      |
|           11 |     8330 | 2023-12-23 | aimclub                   | W   | 0.144      | -            | -                | -                | -         |     0.66 | dem0n, fnl, Krabeni, Magic, makazze      |
|           10 |     8333 | 2023-12-23 | TY                        | L   | 0.143      | -            | -                | -                | -         |    -3.08 | dem0n, fnl, Krabeni, Magic, makazze      |
|            9 |     8353 | 2023-12-22 | aimclub                   | W   | 0.136      | -            | -                | -                | -         |     0.61 | dem0n, fnl, Krabeni, Magic, makazze      |
|            8 |     8356 | 2023-12-22 | ex-Anonymo Esports        | L   | 0.135      | -            | -                | -                | -         |    -2.66 | dem0n, fnl, Krabeni, Magic, makazze      |
|            7 |     8376 | 2023-12-21 | NOM Esports               | W   | 0.128      | -            | -                | -                | -         |     1.22 | dem0n, fnl, Krabeni, Magic, makazze      |
|            6 |     8383 | 2023-12-20 | Sashi Esport              | W   | 0.123      | -            | -                | -                | -         |     0.80 | dem0n, fnl, Krabeni, Magic, makazze      |
|            5 |     8408 | 2023-12-19 | Team Spirit Academy       | L   | 0.115      | -            | -                | -                | -         |    -2.13 | dem0n, fnl, Krabeni, Magic, makazze      |
|            4 |     8653 | 2023-12-16 | NOM Esports               | W   | 0.095      | -            | -                | -                | -         |     0.90 | dem0n, fnl, Krabeni, Magic, makazze      |
|            3 |     8819 | 2023-12-13 | cs2Ctonjeu                | L   | 0.078      | -            | -                | -                | -         |    -1.85 | dem0n, fnl, Krabeni, Magic, makazze      |
|            2 |     8959 | 2023-12-10 | Nexus Gaming              | W   | 0.057      | -            | -                | -                | -         |     1.23 | dem0n, fnl, Krabeni, Magic, makazze      |
|            1 |     9230 | 2023-12-06 | Sashi Esport              | W   | 0.030      | -            | -                | -                | -         |     0.19 | dem0n, fnl, Krabeni, Magic, makazze      |

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
