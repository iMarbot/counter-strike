### Roster Details<br />
Team Name: Sashi Esport<br />
Roster: b0RUP, nut nut, PR1mE, raalz, sL1m3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [143](../standings_global.md)<br />
Regional Rank: [97]( ../standings_europe.md)<br />
Final Rank Value:  782.1<br />
<br />
Final Rank Value (782.1) = Starting Rank Value (812.6) + Head To Head Adjustments (-30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.6
- 400 + ( ( 0.208 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 812.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     1507 | 2024-04-04 | GamerLegion Academy         | L   | 0.989      | -            | -                | -                | -         |   -10.55 | b0RUP, nut nut, PR1mE, raalz, sL1m3 |
|           26 |     1679 | 2024-03-29 | Natus Vincere Junior        | L   | 0.949      | -            | -                | -                | -         |   -10.86 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           25 |     1777 | 2024-03-27 | UNiTY esports (Slovak team) | W   | 0.936      | 0.333        | 0.055 (0.017)    | 0.727 (0.227)    | 0 (0.000) |    17.97 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           24 |     1832 | 2024-03-26 | GamerLegion Academy         | L   | 0.930      | -            | -                | -                | -         |   -11.86 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           23 |     1942 | 2024-03-22 | Sprout Academy              | W   | 0.904      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     5.55 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           22 |     2159 | 2024-03-17 | Natus Vincere Junior        | L   | 0.869      | -            | -                | -                | -         |   -11.52 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           21 |     2345 | 2024-03-13 | Sprout Academy              | W   | 0.843      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     4.63 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           20 |     2414 | 2024-03-11 | WOPA Esport                 | W   | 0.832      | 0.143        | 0.009 (0.001)    | 0.485 (0.058)    | 0 (0.000) |    12.12 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           19 |     2420 | 2024-03-11 | IMMAPROBLEM                 | W   | 0.832      | 0.143        | -                | 0.136 (0.016)    | 0 (0.000) |     5.66 | b0RUP, JUGi, niko, nut nut, PR1mE   |
|           18 |     2858 | 2024-03-02 | ENTERPRISE esports          | L   | 0.772      | -            | -                | -                | -         |    -7.10 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           17 |     2887 | 2024-03-02 | Passion UA                  | L   | 0.771      | -            | -                | -                | -         |    -8.69 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           16 |     3003 | 2024-02-28 | Verdant                     | W   | 0.750      | 0.303        | 0.027 (0.006)    | 0.662 (0.150)    | 0 (0.000) |    16.18 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           15 |     3057 | 2024-02-26 | Metizport                   | L   | 0.739      | -            | -                | -                | -         |    -3.79 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           14 |     3186 | 2024-02-24 | Passion UA                  | L   | 0.723      | -            | -                | -                | -         |    -7.45 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           13 |     3449 | 2024-02-18 | Viperio                     | L   | 0.685      | -            | -                | -                | -         |   -13.93 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           12 |     3460 | 2024-02-18 | Natus Vincere Junior        | L   | 0.684      | -            | -                | -                | -         |   -10.29 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           11 |     3547 | 2024-02-16 | Illuminar Gaming            | W   | 0.670      | 0.303        | 0.010 (0.002)    | 0.243 (0.049)    | 0 (0.000) |     9.58 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|           10 |     3599 | 2024-02-15 | Permitta Esports            | L   | 0.664      | -            | -                | -                | -         |    -5.79 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            9 |     3653 | 2024-02-14 | BIG Academy                 | L   | 0.657      | -            | -                | -                | -         |    -9.33 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            8 |     3759 | 2024-02-11 | Passion UA                  | W   | 0.636      | 0.303        | 0.114 (0.022)    | 0.980 (0.189)    | 0 (0.000) |    13.52 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            7 |     3847 | 2024-02-07 | EXO Clan                    | W   | 0.610      | 0.303        | 0.019 (0.003)    | 0.418 (0.077)    | 0 (0.000) |    12.11 | b0RUP, n1Xen, niko, nut nut, PR1mE  |
|            6 |     3876 | 2024-02-05 | Team Atlantic               | L   | 0.599      | -            | -                | -                | -         |   -15.47 | b0RUP, Fessor, niko, nut nut, PR1mE |
|            5 |     3883 | 2024-02-05 | Astralis Talent             | L   | 0.599      | -            | -                | -                | -         |    -5.90 | b0RUP, Fessor, niko, nut nut, PR1mE |
|            4 |     3889 | 2024-02-05 | Preasy Esport               | W   | 0.599      | 0.143        | 0.007 (0.001)    | 0.525 (0.045)    | 0 (0.000) |     8.12 | b0RUP, Fessor, niko, nut nut, PR1mE |
|            3 |     4453 | 2024-01-22 | Copenhagen Wolves           | L   | 0.506      | -            | -                | -                | -         |   -11.46 | b0RUP, Fessor, niko, nut nut, PR1mE |
|            2 |     4460 | 2024-01-22 | IMMAPROBLEM                 | W   | 0.506      | 0.143        | -                | 0.136 (0.010)    | -         |     2.64 | b0RUP, Fessor, niko, nut nut, PR1mE |
|            1 |     4464 | 2024-01-22 | XI Esport                   | W   | 0.505      | 0.143        | 0.002 (0.000)    | 0.313 (0.023)    | -         |     5.35 | b0RUP, Fessor, niko, nut nut, PR1mE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,707.29)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
