### Roster Details<br />
Team Name: Preasy Esport<br />
Roster: Altekz, dupreeh, refrezh, roeJ, TMB<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [46](../standings_global.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
Final Rank Value:  1043.1<br />
<br />
Final Rank Value (1043.1) = Starting Rank Value (949.4) + Head To Head Adjustments (93.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.507[<sup>1</sup>](#table2)
- Bounty Collected: 0.408[<sup>2</sup>](#table1)
- Opponent Network: 0.115[<sup>2</sup>](#table1)
- LAN Wins: 0.078[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 949.4
- 400 + ( ( 0.277 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 949.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |     2407 | 2024-03-11 | Metizport              | L   | 0.832      | -            | -                | -                | -         |   -10.09 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           47 |     2426 | 2024-03-11 | HEROIC                 | L   | 0.831      | -            | -                | -                | -         |    -0.79 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           46 |     2782 | 2024-03-03 | Gaimin Gladiators      | W   | 0.779      | 0.143        | 0.194 (0.022)    | 0.989 (0.110)    | 0 (0.000) |    21.20 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           45 |     2790 | 2024-03-03 | BetBoom Team           | W   | 0.779      | 0.143        | 0.571 (0.064)    | 0.824 (0.092)    | 0 (0.000) |    22.30 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           44 |     2815 | 2024-03-03 | Fnatic                 | L   | 0.777      | -            | -                | -                | -         |    -6.07 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           43 |     2849 | 2024-03-02 | LEON Esports           | W   | 0.772      | -            | -                | -                | 0 (0.000) |     3.42 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           42 |     2910 | 2024-03-01 | BetBoom Team           | L   | 0.766      | -            | -                | -                | -         |    -2.08 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           41 |     2974 | 2024-02-28 | Fnatic                 | W   | 0.752      | 0.500        | 0.334 (0.126)    | 0.683 (0.257)    | 0 (0.000) |    18.00 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           40 |     3304 | 2024-02-21 | Guild Eagles           | L   | 0.705      | -            | -                | -                | -         |    -9.40 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           39 |     3352 | 2024-02-20 | Pera Esports           | W   | 0.698      | -            | -                | -                | 1 (0.698) |     9.81 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           38 |     3404 | 2024-02-19 | OG                     | L   | 0.692      | -            | -                | -                | -         |    -3.26 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           37 |     3418 | 2024-02-19 | HEROIC                 | L   | 0.691      | -            | -                | -                | -         |    -0.44 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           36 |     3806 | 2024-02-09 | Gaimin Gladiators      | W   | 0.623      | 0.371        | 0.194 (0.045)    | 0.989 (0.228)    | 0 (0.000) |    17.49 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           35 |     3850 | 2024-02-07 | Into The Breach        | W   | 0.609      | -            | -                | -                | 0 (0.000) |     6.99 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           34 |     3868 | 2024-02-06 | Sangal Esports         | W   | 0.603      | 0.371        | -                | 0.350 (0.078)    | 0 (0.000) |     3.65 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           33 |     3911 | 2024-02-05 | Gaimin Gladiators      | L   | 0.596      | -            | -                | -                | -         |    -1.88 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           32 |     3959 | 2024-02-03 | Sashi Esport           | L   | 0.585      | -            | -                | -                | -         |   -16.94 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           31 |     3972 | 2024-02-03 | Supermatch             | W   | 0.585      | -            | -                | -                | 0 (0.000) |     0.67 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           30 |     4014 | 2024-02-02 | Metizport              | L   | 0.579      | -            | -                | -                | -         |    -8.72 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           29 |     4020 | 2024-02-02 | Sashi Esport           | W   | 0.578      | -            | -                | -                | 0 (0.000) |     1.35 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           28 |     4034 | 2024-02-02 | Maknitude              | W   | 0.578      | -            | -                | -                | -         |     1.23 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           27 |     4056 | 2024-02-02 | SINNERS Esports        | W   | 0.576      | 0.371        | 0.038 (0.008)    | 0.534 (0.114)    | -         |     9.38 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           26 |     4124 | 2024-01-31 | Sprout                 | W   | 0.563      | -            | -                | -                | -         |     1.24 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           25 |     4155 | 2024-01-30 | Entropiq               | W   | 0.556      | 0.371        | -                | 0.436 (0.090)    | -         |     4.84 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           24 |     4163 | 2024-01-29 | FORZE Esports          | L   | 0.553      | -            | -                | -                | -         |   -12.39 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           23 |     4193 | 2024-01-29 | Turów Zgorzelec Esport | W   | 0.552      | -            | -                | -                | -         |     4.59 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           22 |     4507 | 2024-01-21 | 3DMAX                  | W   | 0.497      | -            | -                | -                | -         |     7.33 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           21 |     4540 | 2024-01-20 | MOUZ                   | L   | 0.492      | -            | -                | -                | -         |    -0.12 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           20 |     4565 | 2024-01-20 | FORZE Esports          | W   | 0.490      | -            | -                | -                | -         |     4.68 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           19 |     4610 | 2024-01-19 | Team Spirit            | L   | 0.484      | -            | -                | -                | -         |    -0.13 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           18 |     4658 | 2024-01-18 | Astralis               | L   | 0.478      | -            | -                | -                | -         |    -0.62 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           17 |     4663 | 2024-01-18 | Entropiq               | W   | 0.478      | -            | -                | -                | -         |     4.20 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           16 |     4707 | 2024-01-17 | PARIVISION             | L   | 0.473      | -            | -                | -                | -         |    -9.58 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           15 |     4740 | 2024-01-17 | Nemiga Gaming          | W   | 0.472      | 0.143        | 0.680 (0.046)    | 0.910 (0.061)    | -         |    12.87 | Altekz, dupreeh, refrezh, roeJ, TMB  |
|           14 |     5676 | 2023-12-12 | ALTERNATE aTTaX        | W   | 0.231      | 0.371        | 0.110 (0.009)    | 0.723 (0.062)    | -         |     4.67 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|           13 |     5694 | 2023-12-11 | 9Pandas                | W   | 0.225      | 0.384        | 0.085 (0.007)    | -                | -         |     5.17 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|           12 |     5707 | 2023-12-11 | GODSENT                | W   | 0.223      | -            | -                | -                | -         |     2.12 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|           11 |     5746 | 2023-12-10 | TSM                    | W   | 0.216      | -            | -                | -                | -         |     1.42 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|           10 |     5781 | 2023-12-09 | Endpoint               | W   | 0.210      | 0.371        | -                | 0.785 (0.061)    | -         |     2.40 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            9 |     5857 | 2023-12-08 | GODSENT                | L   | 0.203      | -            | -                | -                | -         |    -4.47 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            8 |     5992 | 2023-12-05 | FORZE Esports          | W   | 0.184      | -            | -                | -                | -         |     1.61 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            7 |     6327 | 2023-11-28 | EYEBALLERS             | W   | 0.138      | -            | -                | -                | -         |     2.09 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            6 |     6448 | 2023-11-25 | Sashi Esport           | W   | 0.116      | 0.371        | 0.193 (0.008)    | -                | -         |     2.50 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            5 |     6531 | 2023-11-23 | Gaimin Gladiators      | L   | 0.104      | -            | -                | -                | -         |    -0.19 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            4 |     6773 | 2023-11-17 | BIG                    | W   | 0.065      | 0.589        | 0.470 (0.018)    | -                | -         |     1.91 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            3 |     6886 | 2023-11-15 | Guild Eagles           | W   | 0.051      | -            | -                | -                | -         |     0.98 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            2 |     6898 | 2023-11-15 | Ex-Anonymo Esports     | W   | 0.050      | -            | -                | -                | -         |     0.43 | Altekz, nicoodoz, refrezh, roeJ, TMB |
|            1 |     6994 | 2023-11-12 | Endpoint               | W   | 0.032      | -            | -                | -                | -         |     0.37 | Altekz, nicoodoz, refrezh, roeJ, TMB |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,861.83)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.623 | $11,000.00     | $6,850.05       |
| 2023-12-13 |      0.239 | $1,000.00      | $238.59         |
| 2023-12-12 |      0.231 | $11,000.00     | $2,541.71       |
| 2023-11-18 |      0.072 | $100,000.00    | $7,231.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
