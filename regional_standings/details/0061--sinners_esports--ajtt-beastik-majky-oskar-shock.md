### Roster Details<br />
Team Name: SINNERS Esports<br />
Roster: AJTT, beastik, majky, oskar, SHOCK<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [61](../standings_global.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
Final Rank Value:  996.2<br />
<br />
Final Rank Value (996.2) = Starting Rank Value (998.2) + Head To Head Adjustments (-1.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.380[<sup>2</sup>](#table1)
- Opponent Network: 0.309[<sup>2</sup>](#table1)
- LAN Wins: 0.149[<sup>2</sup>](#table1)

The average of these factors is 0.294<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 998.2
- 400 + ( ( 0.294 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 998.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           66 |       77 | 2024-05-29 | brazylijski luz     | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.27 | AJTT, beastik, majky, oskar, SHOCK    |
|           65 |      216 | 2024-05-26 | Team Sampi          | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.665 (0.289)    | 0 (0.000) |    14.82 | AJTT, beastik, majky, oskar, SHOCK    |
|           64 |      333 | 2024-05-24 | GUN5 Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.77 | AJTT, beastik, majky, oskar, SHOCK    |
|           63 |      365 | 2024-05-24 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |   -10.44 | AJTT, beastik, majky, oskar, SHOCK    |
|           62 |      403 | 2024-05-23 | UNiTY esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.29 | AJTT, beastik, majky, oskar, SHOCK    |
|           61 |      418 | 2024-05-23 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |   -16.92 | AJTT, beastik, majky, oskar, SHOCK    |
|           60 |      709 | 2024-05-20 | VP.Prodigy          | W   | 1.000      | 0.435        | -                | 0.752 (0.327)    | 0 (0.000) |     9.85 | AJTT, beastik, majky, MoriiSko, oskar |
|           59 |      741 | 2024-05-19 | EP Genesis          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.15 | AJTT, beastik, oskar, SHOCK, tomkeejs |
|           58 |      860 | 2024-05-18 | VENI VIDI VICI      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.14 | AJTT, beastik, oskar, SHOCK, tomkeejs |
|           57 |     1079 | 2024-05-16 | EP Genesis          | L   | 1.000      | -            | -                | -                | -         |   -28.66 | AJTT, beastik, oskar, SHOCK, tomkeejs |
|           56 |     1106 | 2024-05-16 | ALTERNATE aTTaX     | W   | 1.000      | 0.435        | 0.052 (0.022)    | 0.679 (0.295)    | 0 (0.000) |    14.62 | AJTT, beastik, majky, oskar, SHOCK    |
|           55 |     1254 | 2024-05-14 | Passion UA          | W   | 1.000      | 0.435        | 0.057 (0.025)    | 1.000 (0.435)    | -         |    13.60 | AJTT, beastik, majky, oskar, SHOCK    |
|           54 |     1694 | 2024-05-07 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |    -6.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           53 |     1775 | 2024-05-05 | Endpoint            | W   | 1.000      | -            | -                | -                | -         |    16.27 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           52 |     1935 | 2024-05-02 | Gaimin Gladiators   | L   | 1.000      | -            | -                | -                | -         |    -7.50 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           51 |     2005 | 2024-05-01 | B8                  | L   | 1.000      | -            | -                | -                | -         |   -11.46 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           50 |     2076 | 2024-04-29 | 1win                | W   | 0.996      | 0.435        | 0.050 (0.022)    | 0.887 (0.384)    | -         |    17.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           49 |     2084 | 2024-04-29 | Sangal Esports      | L   | 0.995      | -            | -                | -                | -         |   -12.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           48 |     2120 | 2024-04-28 | Zero Tenacity       | L   | 0.989      | -            | -                | -                | -         |   -12.86 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           47 |     2217 | 2024-04-27 | Zero Tenacity       | L   | 0.981      | -            | -                | -                | -         |   -14.27 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           46 |     2268 | 2024-04-26 | PARIVISION          | L   | 0.976      | -            | -                | -                | -         |   -18.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           45 |     2466 | 2024-04-22 | HAVU Gaming         | W   | 0.949      | -            | -                | -                | -         |     4.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           44 |     2622 | 2024-04-20 | ENCE Academy        | L   | 0.936      | -            | -                | -                | -         |   -22.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           43 |     2733 | 2024-04-19 | Dynamo Eclot        | L   | 0.928      | -            | -                | -                | -         |   -15.67 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           42 |     2871 | 2024-04-17 | Gaimin Gladiators   | L   | 0.915      | -            | -                | -                | -         |    -6.11 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           41 |     2928 | 2024-04-16 | BLEED Esports       | L   | 0.908      | -            | -                | -                | -         |    -9.05 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           40 |     2991 | 2024-04-14 | Passion UA          | W   | 0.895      | 0.371        | 0.057 (0.019)    | 1.000 (0.332)    | -         |     9.54 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           39 |     3209 | 2024-04-10 | UNiTY esports       | W   | 0.868      | 0.371        | -                | 0.766 (0.246)    | -         |     7.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           38 |     3238 | 2024-04-09 | 9Pandas             | W   | 0.864      | 0.500        | 0.110 (0.048)    | 0.660 (0.285)    | -         |    17.14 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           37 |     3312 | 2024-04-08 | ALTERNATE aTTaX     | W   | 0.855      | 0.384        | 0.052 (0.017)    | -                | -         |     9.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           36 |     3446 | 2024-04-05 | Nexus Gaming        | W   | 0.837      | 0.384        | -                | 0.825 (0.265)    | -         |    11.04 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           35 |     3572 | 2024-04-03 | Rebels Gaming       | W   | 0.822      | 0.500        | 0.062 (0.025)    | -                | -         |    16.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           34 |     3703 | 2024-03-29 | ex-Sprout           | W   | 0.791      | -            | -                | -                | -         |     3.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           33 |     4260 | 2024-03-17 | Dynamo Eclot        | L   | 0.711      | -            | -                | -                | -         |    -9.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           32 |     4278 | 2024-03-17 | UNiTY esports       | W   | 0.710      | -            | -                | -                | 1 (0.710) |     7.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           31 |     4332 | 2024-03-16 | Team Sampi          | W   | 0.703      | -            | -                | -                | 1 (0.703) |    10.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           30 |     4374 | 2024-03-15 | UNiTY esports       | L   | 0.698      | -            | -                | -                | -         |   -15.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           29 |     4492 | 2024-03-13 | ALTERNATE aTTaX     | W   | 0.684      | 0.500        | 0.052 (0.018)    | 0.679 (0.232)    | -         |     8.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           28 |     4611 | 2024-03-11 | brazylijski luz     | L   | 0.671      | -            | -                | -                | -         |   -16.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           27 |     4954 | 2024-03-05 | Dynamo Eclot        | W   | 0.631      | -            | -                | -                | -         |    12.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           26 |     5033 | 2024-03-04 | Team Universe       | W   | 0.624      | -            | -                | -                | -         |     1.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           25 |     5083 | 2024-03-03 | Gaimin Gladiators   | L   | 0.617      | -            | -                | -                | -         |    -3.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           24 |     5130 | 2024-03-02 | Permitta Esports    | W   | 0.612      | -            | -                | -                | -         |     9.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           23 |     5154 | 2024-03-02 | DUSTY               | W   | 0.611      | -            | -                | -                | -         |     3.46 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           22 |     5875 | 2024-02-18 | Monte               | L   | 0.524      | -            | -                | -                | -         |    -2.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           21 |     5974 | 2024-02-16 | 500                 | W   | 0.511      | -            | -                | -                | -         |     4.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           20 |     5979 | 2024-02-16 | Pera Esports        | W   | 0.511      | -            | -                | -                | -         |     7.52 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           19 |     5990 | 2024-02-16 | 500                 | L   | 0.510      | -            | -                | -                | -         |   -11.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           18 |     6476 | 2024-02-04 | Into The Breach     | L   | 0.429      | -            | -                | -                | -         |   -10.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           17 |     6643 | 2024-02-02 | ex-Preasy Esport    | L   | 0.415      | -            | -                | -                | -         |    -7.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           16 |     6827 | 2024-01-29 | GUN5 Esports        | L   | 0.391      | -            | -                | -                | -         |   -11.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           15 |     6989 | 2024-01-27 | GODSENT             | W   | 0.376      | -            | -                | -                | -         |     1.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           14 |     7186 | 2024-01-23 | MOUZ NXT            | W   | 0.349      | 0.371        | 0.157 (0.020)    | -                | -         |     7.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           13 |     7402 | 2024-01-19 | Nexus Gaming        | L   | 0.324      | -            | -                | -                | -         |    -6.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           12 |     7456 | 2024-01-18 | Fnatic              | L   | 0.318      | -            | -                | -                | -         |    -3.48 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           11 |     7486 | 2024-01-18 | Virtus.pro          | L   | 0.317      | -            | -                | -                | -         |    -0.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|           10 |     7914 | 2024-01-11 | HEROIC              | L   | 0.272      | -            | -                | -                | -         |    -0.12 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|            9 |     7923 | 2024-01-11 | Pera Esports        | W   | 0.271      | -            | -                | -                | -         |     3.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|            8 |     7937 | 2024-01-11 | ILIN                | W   | 0.270      | -            | -                | -                | -         |     0.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|            7 |     7945 | 2024-01-11 | V1dar Gaming        | W   | 0.270      | -            | -                | -                | -         |     0.98 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|            6 |     7996 | 2024-01-10 | The Prodigies       | W   | 0.265      | -            | -                | -                | -         |     0.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|            5 |     8018 | 2024-01-10 | Passion UA          | W   | 0.265      | -            | -                | -                | -         |     4.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK  |
|            4 |     9019 | 2023-12-09 | FORZE Esports       | L   | 0.051      | -            | -                | -                | -         |    -1.35 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            3 |     9166 | 2023-12-07 | 3DMAX               | L   | 0.037      | -            | -                | -                | -         |    -0.68 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            2 |     9220 | 2023-12-06 | Team Spirit Academy | W   | 0.031      | -            | -                | -                | -         |     0.18 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |
|            1 |     9289 | 2023-12-05 | ENCE                | W   | 0.024      | -            | -                | -                | -         |     0.70 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,260.84)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-09 |      1.000 | $532.06        | $532.06         |
| 2024-03-17 |      0.711 | $3,030.54      | $2,153.79       |
| 2023-12-10 |      0.058 | $10,000.00     | $575.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
