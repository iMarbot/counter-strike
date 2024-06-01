### Roster Details<br />
Team Name: Copenhagen Wolves<br />
Roster: Basso, Fessor, Svedjehed, szejn, vigg0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [305](../standings_global.md)<br />
Regional Rank: [187]( ../standings_europe.md)<br />
Final Rank Value:  640.6<br />
<br />
Final Rank Value (640.6) = Starting Rank Value (630.6) + Head To Head Adjustments (10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.289[<sup>2</sup>](#table1)
- Opponent Network: 0.065[<sup>2</sup>](#table1)
- LAN Wins: 0.099[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.6
- 400 + ( ( 0.113 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 630.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |     1629 | 2024-05-08 | Sashi Esport         | W   | 1.000      | 0.143        | 0.172 (0.025)    | 1.000 (0.143)    | 0 (0.000) |    30.63 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           46 |     1708 | 2024-05-06 | Kappa Bar            | L   | 1.000      | -            | -                | -                | -         |   -18.14 | artie, Basso, Fessor, Svedjehed, szejn    |
|           45 |     1712 | 2024-05-06 | Astralis Talent      | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.452 (0.065)    | 0 (0.000) |    22.59 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           44 |     1723 | 2024-05-06 | IMMAPROBLEM          | L   | 1.000      | -            | -                | -                | -         |   -17.53 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           43 |     1735 | 2024-05-06 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |    -7.57 | Altekz, Fessor, Svedjehed, szejn, vigg0   |
|           42 |     1829 | 2024-05-04 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -10.37 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           41 |     1856 | 2024-05-04 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -3.24 | Basso, Fessor, Logic, Svedjehed, vigg0    |
|           40 |     2046 | 2024-04-30 | kONO.ECF             | L   | 1.000      | -            | -                | -                | -         |    -5.03 | Basso, Fessor, smF, Svedjehed, szejn      |
|           39 |     2056 | 2024-04-29 | Sashi Academy        | W   | 0.997      | 0.143        | 0.001 (0.000)    | 0.088 (0.013)    | 0 (0.000) |    14.65 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           38 |     2059 | 2024-04-29 | AscendX Esports      | W   | 0.997      | 0.372        | 0.000 (0.000)    | -                | 0 (0.000) |     5.89 | artie, Basso, Fessor, Svedjehed, szejn    |
|           37 |     2211 | 2024-04-27 | Johnny Speeds        | L   | 0.982      | -            | -                | -                | -         |    -2.80 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           36 |     2310 | 2024-04-25 | Young Gods           | L   | 0.970      | -            | -                | -                | -         |   -17.91 | artie, Basso, Fessor, Svedjehed, szejn    |
|           35 |     2358 | 2024-04-24 | XI Esport            | W   | 0.964      | 0.143        | 0.001 (0.000)    | 0.277 (0.038)    | 0 (0.000) |    15.61 | Altekz, Basso, Fessor, Svedjehed, vigg0   |
|           34 |     2529 | 2024-04-21 | MASONIC              | L   | 0.941      | -            | -                | -                | -         |    -6.64 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           33 |     2561 | 2024-04-20 | Floki Esport         | W   | 0.937      | -            | -                | -                | 1 (0.937) |     6.11 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           32 |     2818 | 2024-04-17 | GamerLegion          | L   | 0.918      | -            | -                | -                | -         |    -1.02 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           31 |     2947 | 2024-04-15 | Preasy Esport        | W   | 0.904      | 0.143        | 0.008 (0.001)    | 0.642 (0.083)    | 0 (0.000) |    19.47 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           30 |     3162 | 2024-04-10 | ARROW                | L   | 0.871      | -            | -                | -                | -         |    -9.62 | artie, Basso, Fessor, Svedjehed, szejn    |
|           29 |     4599 | 2024-03-11 | XI Esport            | L   | 0.671      | -            | -                | -                | -         |    -9.84 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           28 |     4618 | 2024-03-11 | Preasy Esport        | L   | 0.671      | -            | -                | -                | -         |    -5.90 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           27 |     4849 | 2024-03-06 | IMMAPROBLEM          | W   | 0.638      | 0.143        | -                | 0.160 (0.015)    | 0 (0.000) |     7.70 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           26 |     4860 | 2024-03-06 | Team Atlantic        | W   | 0.638      | -            | -                | -                | 0 (0.000) |     7.20 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           25 |     4872 | 2024-03-06 | WOPA Esport          | L   | 0.637      | -            | -                | -                | -         |    -5.93 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           24 |     5274 | 2024-02-29 | UNiTY esports        | W   | 0.597      | 0.371        | 0.021 (0.005)    | 0.766 (0.170)    | 0 (0.000) |    14.75 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           23 |     5302 | 2024-02-28 | LODIS                | W   | 0.591      | 0.371        | 0.001 (0.000)    | 0.140 (0.031)    | -         |     9.08 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           22 |     5316 | 2024-02-28 | Astralis Talent      | L   | 0.591      | -            | -                | -                | -         |    -2.85 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           21 |     5324 | 2024-02-28 | L&G                  | W   | 0.590      | -            | -                | -                | -         |     6.50 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           20 |     5644 | 2024-02-22 | VP.Prodigy           | L   | 0.551      | -            | -                | -                | -         |    -3.76 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           19 |     5655 | 2024-02-22 | INGLORIOUS           | L   | 0.551      | -            | -                | -                | -         |    -5.29 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           18 |     5825 | 2024-02-19 | Sashi Esport         | L   | 0.531      | -            | -                | -                | -         |    -5.13 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           17 |     6032 | 2024-02-15 | 1win                 | L   | 0.504      | -            | -                | -                | -         |    -1.95 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           16 |     6035 | 2024-02-15 | HOTU                 | L   | 0.504      | -            | -                | -                | -         |    -3.68 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           15 |     6042 | 2024-02-15 | Team Spirit Academy  | L   | 0.504      | -            | -                | -                | -         |    -4.83 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           14 |     6052 | 2024-02-15 | Zero Tenacity        | L   | 0.503      | -            | -                | -                | -         |    -1.38 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           13 |     6347 | 2024-02-08 | WOPA Esport          | L   | 0.455      | -            | -                | -                | -         |    -4.19 | Basso, mupzG, smF, Svedjehed, szejn       |
|           12 |     6401 | 2024-02-05 | IMMAPROBLEM          | L   | 0.438      | -            | -                | -                | -         |    -8.96 | Basso, smF, Svedjehed, szejn, vigg0       |
|           11 |     6416 | 2024-02-05 | XI Esport            | L   | 0.438      | -            | -                | -                | -         |    -6.44 | Basso, smF, Svedjehed, szejn, vigg0       |
|           10 |     6438 | 2024-02-05 | brazylijski luz      | L   | 0.436      | -            | -                | -                | -         |    -4.13 | Basso, mupzG, smF, Svedjehed, szejn       |
|            9 |     6662 | 2024-02-01 | Preasy Esport        | W   | 0.411      | 0.143        | 0.008 (0.000)    | 0.642 (0.038)    | -         |     9.71 | Basso, smF, Svedjehed, szejn, vigg0       |
|            8 |     6748 | 2024-01-30 | Astralis Talent      | L   | 0.398      | -            | -                | -                | -         |    -2.24 | Basso, smF, Svedjehed, szejn, vigg0       |
|            7 |     6756 | 2024-01-30 | WOPA Esport          | L   | 0.398      | -            | -                | -                | -         |    -3.61 | Basso, smF, Svedjehed, szejn, vigg0       |
|            6 |     7111 | 2024-01-24 | GenOne               | W   | 0.358      | 0.371        | -                | 0.442 (0.059)    | -         |     5.55 | fierre, Svedjehed, szejn, tooizera, vigg0 |
|            5 |     7173 | 2024-01-23 | Golden Sword         | W   | 0.351      | -            | -                | -                | -         |     2.25 | Basso, fierre, Svedjehed, szejn, tooizera |
|            4 |     7208 | 2024-01-22 | Sashi Esport         | W   | 0.345      | 0.143        | 0.024 (0.001)    | -                | -         |     7.47 | Basso, smF, Svedjehed, szejn, vigg0       |
|            3 |     7231 | 2024-01-22 | Team Atlantic        | W   | 0.344      | -            | -                | -                | -         |     3.75 | Basso, smF, Svedjehed, szejn, vigg0       |
|            2 |     7537 | 2024-01-17 | Natus Vincere Junior | L   | 0.311      | -            | -                | -                | -         |    -2.90 | Basso, mupzG, Svedjehed, szejn, vigg0     |
|            1 |     7571 | 2024-01-17 | Lilmix               | W   | 0.311      | -            | -                | -                | -         |     3.97 | Basso, mupzG, Svedjehed, szejn, vigg0     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
