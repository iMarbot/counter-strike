### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: awzek, FreeZe, Goody, PANIX, PerX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [193](../standings_global.md)<br />
Regional Rank: [130]( ../standings_europe.md)<br />
Final Rank Value:  730.4<br />
<br />
Final Rank Value (730.4) = Starting Rank Value (721.4) + Head To Head Adjustments (9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.067[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.4
- 400 + ( ( 0.158 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 721.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |     6384 | 2024-02-06 | 500                 | W   | 0.443      | 0.384        | 0.002 (0.000)    | 0.479 (0.082)    | 0 (0.000) |     8.72 | awzek, FreeZe, Goody, PANIX, PerX  |
|           37 |     6456 | 2024-02-04 | brazylijski luz     | W   | 0.431      | 0.143        | 0.013 (0.001)    | 0.490 (0.030)    | 0 (0.000) |     8.55 | awzek, FreeZe, Goody, PANIX, PerX  |
|           36 |     6466 | 2024-02-04 | V1dar Gaming        | L   | 0.430      | -            | -                | -                | -         |    -8.20 | awzek, FreeZe, Goody, PANIX, PerX  |
|           35 |     6480 | 2024-02-04 | Sangal Esports      | L   | 0.428      | -            | -                | -                | -         |    -1.82 | awzek, FreeZe, Goody, PANIX, PerX  |
|           34 |     6571 | 2024-02-03 | TSM                 | L   | 0.422      | -            | -                | -                | -         |    -6.34 | awzek, FreeZe, Goody, PANIX, PerX  |
|           33 |     6695 | 2024-02-01 | Sangal Esports      | L   | 0.408      | -            | -                | -                | -         |    -1.67 | awzek, FreeZe, Goody, PANIX, PerX  |
|           32 |     6706 | 2024-01-31 | GamerLegion Academy | L   | 0.404      | -            | -                | -                | -         |    -4.83 | awzek, FreeZe, Goody, PANIX, PerX  |
|           31 |     6718 | 2024-01-31 | Kappa Bar           | W   | 0.404      | 0.371        | -                | 0.062 (0.009)    | 0 (0.000) |     3.03 | awzek, FreeZe, Goody, PANIX, PerX  |
|           30 |     6726 | 2024-01-31 | Nexus Gaming        | L   | 0.403      | -            | -                | -                | -         |    -3.07 | awzek, FreeZe, Goody, PANIX, PerX  |
|           29 |     6772 | 2024-01-30 | Sprout              | W   | 0.396      | 0.371        | -                | 0.148 (0.022)    | 0 (0.000) |     4.69 | awzek, FreeZe, Goody, PANIX, PerX  |
|           28 |     6806 | 2024-01-29 | kONO.ECF            | L   | 0.392      | -            | -                | -                | -         |    -4.15 | awzek, FreeZe, Goody, PANIX, PerX  |
|           27 |     7057 | 2024-01-26 | Entropiq            | W   | 0.369      | 0.371        | -                | 0.241 (0.033)    | 0 (0.000) |     4.77 | awzek, FreeZe, Goody, PANIX, PerX  |
|           26 |     7121 | 2024-01-24 | ex-Guild Eagles     | L   | 0.357      | -            | -                | -                | -         |    -2.22 | awzek, FreeZe, Goody, PANIX, PerX  |
|           25 |     7178 | 2024-01-23 | Pera Esports        | L   | 0.351      | -            | -                | -                | -         |    -2.72 | awzek, FreeZe, Goody, PANIX, PerX  |
|           24 |     7183 | 2024-01-23 | ex-Guild Eagles     | L   | 0.350      | -            | -                | -                | -         |    -2.30 | awzek, FreeZe, Goody, PANIX, PerX  |
|           23 |     7211 | 2024-01-22 | Viperio             | W   | 0.344      | -            | -                | -                | 0 (0.000) |     3.17 | awzek, FreeZe, Goody, PANIX, PerX  |
|           22 |     7226 | 2024-01-22 | Rebels Gaming       | L   | 0.344      | -            | -                | -                | -         |    -1.26 | awzek, FreeZe, Goody, PANIX, PerX  |
|           21 |     7233 | 2024-01-22 | Team Sampi          | W   | 0.344      | 0.143        | 0.039 (0.002)    | 0.665 (0.033)    | 0 (0.000) |     8.46 | awzek, FreeZe, Goody, PANIX, PerX  |
|           20 |     7868 | 2024-01-12 | showmakerz          | L   | 0.278      | -            | -                | -                | -         |    -6.53 | awzek, FreeZe, Goody, PANIX, PerX  |
|           19 |     7922 | 2024-01-11 | Preasy Esport       | W   | 0.271      | 0.143        | 0.008 (0.000)    | 0.642 (0.025)    | 1 (0.271) |     6.04 | awzek, FreeZe, Goody, PANIX, PerX  |
|           18 |     7935 | 2024-01-11 | Lilmix              | L   | 0.270      | -            | -                | -                | -         |    -6.18 | awzek, FreeZe, Goody, PANIX, PerX  |
|           17 |     7939 | 2024-01-11 | Preasy Esport       | W   | 0.270      | 0.143        | 0.008 (0.000)    | 0.642 (0.025)    | 1 (0.270) |     6.06 | awzek, FreeZe, Goody, PANIX, PerX  |
|           16 |     8253 | 2024-01-03 | THE SUSPECT         | W   | 0.218      | 0.143        | 0.001 (0.000)    | -                | -         |     2.38 | awzek, FreeZe, Goody, PANIX, PerX  |
|           15 |     8257 | 2024-01-03 | Ovoshi              | W   | 0.218      | -            | -                | -                | -         |     0.95 | awzek, FreeZe, Goody, PANIX, PerX  |
|           14 |     8618 | 2023-12-16 | ALTERNATE aTTaX     | W   | 0.097      | 0.143        | 0.052 (0.001)    | 0.679 (0.009)    | 1 (0.097) |     2.48 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           13 |     8887 | 2023-12-12 | ex-Preasy Esport    | L   | 0.070      | -            | -                | -                | -         |    -0.56 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           12 |     8980 | 2023-12-10 | GODSENT             | W   | 0.056      | 0.371        | 0.001 (0.000)    | -                | -         |     0.74 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           11 |     9032 | 2023-12-09 | lajtbitexe          | L   | 0.050      | -            | -                | -                | -         |    -1.02 | awzek, FreeZe, PANIX, PerX, Spiidi |
|           10 |     9099 | 2023-12-08 | Zero Tenacity       | W   | 0.044      | 0.371        | 0.147 (0.002)    | 1.000 (0.017)    | -         |     1.25 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            9 |     9119 | 2023-12-08 | Sprout              | W   | 0.042      | -            | -                | -                | -         |     0.40 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            8 |     9152 | 2023-12-07 | TUSTE CHOPAKI       | W   | 0.038      | -            | -                | -                | -         |     0.23 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            7 |     9172 | 2023-12-07 | ex-Anonymo Esports  | L   | 0.037      | -            | -                | -                | -         |    -0.61 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            6 |     9222 | 2023-12-06 | The Witchers        | W   | 0.031      | 0.371        | 0.009 (0.000)    | -                | -         |     0.47 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            5 |     9241 | 2023-12-06 | ex-sYnck            | W   | 0.029      | -            | -                | -                | -         |     0.43 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            4 |     9292 | 2023-12-05 | lajtbitexe          | L   | 0.024      | -            | -                | -                | -         |    -0.49 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            3 |     9340 | 2023-12-04 | Entropiq            | W   | 0.016      | -            | -                | -                | -         |     0.20 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            2 |     9344 | 2023-12-04 | ex-Guild Eagles     | L   | 0.015      | -            | -                | -                | -         |    -0.10 | awzek, FreeZe, PANIX, PerX, Spiidi |
|            1 |     9491 | 2023-12-02 | Team Space          | W   | 0.003      | -            | -                | -                | -         |     0.06 | awzek, FreeZe, PANIX, PerX, Spiidi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,236.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-16 |      0.097 | $8,180.59      | $790.79         |
| 2023-12-13 |      0.077 | $1,250.00      | $96.18          |
| 2023-12-12 |      0.070 | $5,000.00      | $350.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
