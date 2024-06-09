### Roster Details<br />
Team Name: SINNERS Esports<br />
Roster: AJTT, beastik, majky, oskar, SHOCK<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [59](../standings_global.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
Final Rank Value:  1004.3<br />
<br />
Final Rank Value (1004.3) = Starting Rank Value (1023.7) + Head To Head Adjustments (-19.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.420[<sup>2</sup>](#table1)
- Opponent Network: 0.321[<sup>2</sup>](#table1)
- LAN Wins: 0.149[<sup>2</sup>](#table1)

The average of these factors is 0.307<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1023.7
- 400 + ( ( 0.307 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1023.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |       82 | 2024-05-29 | brazylijski luz     | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.12 | AJTT, beastik, majky, oskar, SHOCK     |
|           67 |      224 | 2024-05-26 | Team Sampi          | W   | 1.000      | 0.435        | -                | 0.677 (0.294)    | 0 (0.000) |    14.62 | AJTT, beastik, majky, oskar, SHOCK     |
|           66 |      342 | 2024-05-24 | GUN5 Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.19 | AJTT, beastik, majky, oskar, SHOCK     |
|           65 |      374 | 2024-05-24 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |   -10.36 | AJTT, beastik, majky, oskar, SHOCK     |
|           64 |      411 | 2024-05-23 | UNiTY esports       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.74 | AJTT, beastik, majky, oskar, SHOCK     |
|           63 |      426 | 2024-05-23 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |   -16.91 | AJTT, beastik, majky, oskar, SHOCK     |
|           62 |      721 | 2024-05-20 | VP.Prodigy          | W   | 1.000      | 0.435        | -                | 0.829 (0.360)    | 0 (0.000) |    10.44 | AJTT, beastik, majky, MoriiSko, oskar  |
|           61 |      753 | 2024-05-19 | EP Genesis          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.03 | AJTT, beastik, oskar, SHOCK, tomkeejs  |
|           60 |      872 | 2024-05-18 | VENI VIDI VICI      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.98 | AJTT, beastik, oskar, SHOCK, tomkeejs  |
|           59 |     1089 | 2024-05-16 | EP Genesis          | L   | 1.000      | -            | -                | -                | -         |   -28.78 | AJTT, beastik, oskar, SHOCK, tomkeejs  |
|           58 |     1116 | 2024-05-16 | ALTERNATE aTTaX     | W   | 1.000      | 0.435        | 0.052 (0.023)    | 0.735 (0.319)    | 0 (0.000) |    14.36 | AJTT, beastik, majky, oskar, SHOCK     |
|           57 |     1264 | 2024-05-14 | Passion UA          | W   | 1.000      | 0.435        | 0.057 (0.025)    | 1.000 (0.435)    | -         |    13.65 | AJTT, beastik, majky, oskar, SHOCK     |
|           56 |     1714 | 2024-05-07 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |    -7.00 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           55 |     1798 | 2024-05-05 | Endpoint            | W   | 1.000      | -            | -                | -                | -         |    17.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           54 |     1962 | 2024-05-02 | Gaimin Gladiators   | L   | 1.000      | -            | -                | -                | -         |    -7.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           53 |     2036 | 2024-05-01 | B8                  | L   | 1.000      | -            | -                | -                | -         |   -12.42 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           52 |     2111 | 2024-04-29 | 1win                | W   | 0.996      | 0.435        | 0.050 (0.022)    | 0.898 (0.389)    | -         |    16.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           51 |     2119 | 2024-04-29 | Sangal Esports      | L   | 0.995      | -            | -                | -                | -         |   -11.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           50 |     2155 | 2024-04-28 | Zero Tenacity       | L   | 0.989      | -            | -                | -                | -         |   -13.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           49 |     2252 | 2024-04-27 | Zero Tenacity       | L   | 0.981      | -            | -                | -                | -         |   -14.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           48 |     2304 | 2024-04-26 | PARIVISION          | L   | 0.976      | -            | -                | -                | -         |   -18.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           47 |     2431 | 2024-04-24 | Endpoint            | L   | 0.963      | -            | -                | -                | -         |   -18.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           46 |     2518 | 2024-04-22 | HAVU Gaming         | W   | 0.949      | -            | -                | -                | -         |     3.99 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           45 |     2676 | 2024-04-20 | ENCE Academy        | L   | 0.936      | -            | -                | -                | -         |   -22.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           44 |     2789 | 2024-04-19 | Dynamo Eclot        | L   | 0.928      | -            | -                | -                | -         |   -16.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           43 |     2928 | 2024-04-17 | Gaimin Gladiators   | L   | 0.915      | -            | -                | -                | -         |    -6.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           42 |     2989 | 2024-04-16 | BLEED Esports       | L   | 0.908      | -            | -                | -                | -         |   -10.50 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           41 |     3056 | 2024-04-14 | Passion UA          | W   | 0.895      | 0.371        | 0.057 (0.019)    | 1.000 (0.332)    | -         |     9.12 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           40 |     3287 | 2024-04-10 | UNiTY esports       | W   | 0.868      | 0.371        | -                | 0.766 (0.246)    | -         |     6.68 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           39 |     3317 | 2024-04-09 | 9Pandas             | W   | 0.864      | 0.500        | 0.110 (0.048)    | 0.710 (0.307)    | -         |    16.28 | beastik, majky, MoriiSko, oskar, SHOCK |
|           38 |     3393 | 2024-04-08 | ALTERNATE aTTaX     | W   | 0.855      | 0.384        | 0.052 (0.017)    | -                | -         |     8.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           37 |     3530 | 2024-04-05 | Nexus Gaming        | W   | 0.837      | 0.384        | -                | 0.857 (0.276)    | -         |     9.91 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           36 |     3659 | 2024-04-03 | Rebels Gaming       | W   | 0.822      | 0.500        | 0.062 (0.025)    | -                | -         |    15.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           35 |     3714 | 2024-04-01 | Aurora Gaming       | W   | 0.811      | 0.500        | 0.492 (0.199)    | -                | -         |    22.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           34 |     3797 | 2024-03-29 | ex-Sprout           | W   | 0.791      | -            | -                | -                | -         |     3.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           33 |     4365 | 2024-03-17 | Dynamo Eclot        | L   | 0.711      | -            | -                | -                | -         |   -10.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     4383 | 2024-03-17 | UNiTY esports       | W   | 0.710      | -            | -                | -                | 1 (0.710) |     6.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     4438 | 2024-03-16 | Team Sampi          | W   | 0.703      | -            | -                | -                | 1 (0.703) |    10.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     4482 | 2024-03-15 | UNiTY esports       | L   | 0.698      | -            | -                | -                | -         |   -15.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     4607 | 2024-03-13 | ALTERNATE aTTaX     | W   | 0.684      | 0.500        | 0.052 (0.018)    | 0.735 (0.251)    | -         |     8.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           28 |     4733 | 2024-03-11 | brazylijski luz     | L   | 0.671      | -            | -                | -                | -         |   -16.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           27 |     5096 | 2024-03-05 | Dynamo Eclot        | W   | 0.631      | -            | -                | -                | -         |    12.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     5179 | 2024-03-04 | Phantom Troupe      | W   | 0.624      | -            | -                | -                | -         |     1.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     5229 | 2024-03-03 | Gaimin Gladiators   | L   | 0.617      | -            | -                | -                | -         |    -3.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     5278 | 2024-03-02 | Permitta Esports    | W   | 0.612      | -            | -                | -                | -         |     9.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     5302 | 2024-03-02 | DUSTY               | W   | 0.611      | -            | -                | -                | -         |     3.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     6048 | 2024-02-18 | Monte               | L   | 0.524      | -            | -                | -                | -         |    -2.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     6147 | 2024-02-16 | 500                 | W   | 0.511      | -            | -                | -                | -         |     4.11 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     6152 | 2024-02-16 | Pera Esports        | W   | 0.511      | -            | -                | -                | -         |     7.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     6164 | 2024-02-16 | 500                 | L   | 0.510      | -            | -                | -                | -         |   -12.07 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     6679 | 2024-02-04 | Into The Breach     | L   | 0.429      | -            | -                | -                | -         |   -10.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     6848 | 2024-02-02 | ex-Preasy Esport    | L   | 0.415      | -            | -                | -                | -         |    -8.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     7043 | 2024-01-29 | GUN5 Esports        | L   | 0.391      | -            | -                | -                | -         |   -11.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     7209 | 2024-01-27 | GODSENT             | W   | 0.376      | -            | -                | -                | -         |     1.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     7426 | 2024-01-23 | MOUZ NXT            | W   | 0.349      | 0.371        | 0.157 (0.020)    | -                | -         |     7.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     7646 | 2024-01-19 | Nexus Gaming        | L   | 0.324      | -            | -                | -                | -         |    -6.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     7704 | 2024-01-18 | Fnatic              | L   | 0.318      | -            | -                | -                | -         |    -3.79 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     7735 | 2024-01-18 | Virtus.pro          | L   | 0.317      | -            | -                | -                | -         |    -0.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     8167 | 2024-01-11 | HEROIC              | L   | 0.272      | -            | -                | -                | -         |    -0.14 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     8176 | 2024-01-11 | Pera Esports        | W   | 0.271      | -            | -                | -                | -         |     3.07 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     8190 | 2024-01-11 | ILIN                | W   | 0.270      | -            | -                | -                | -         |     0.54 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     8198 | 2024-01-11 | V1dar Gaming        | W   | 0.270      | -            | -                | -                | -         |     0.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     8250 | 2024-01-10 | The Prodigies       | W   | 0.265      | -            | -                | -                | -         |     0.65 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     8272 | 2024-01-10 | Passion UA          | W   | 0.265      | -            | -                | -                | -         |     4.12 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     9285 | 2023-12-09 | FORZE Esports       | L   | 0.051      | -            | -                | -                | -         |    -1.41 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO  |
|            3 |     9439 | 2023-12-07 | 3DMAX               | L   | 0.037      | -            | -                | -                | -         |    -0.72 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO  |
|            2 |     9501 | 2023-12-06 | Team Spirit Academy | W   | 0.031      | -            | -                | -                | -         |     0.16 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO  |
|            1 |     9571 | 2023-12-05 | ENCE                | W   | 0.024      | -            | -                | -                | -         |     0.69 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO  |

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
