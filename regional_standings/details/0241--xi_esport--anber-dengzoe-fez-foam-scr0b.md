### Roster Details<br />
Team Name: XI Esport<br />
Roster: anber, Dengzoe, fez, foam, Scr0b<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [241](../standings_global.md)<br />
Regional Rank: [158]( ../standings_europe.md)<br />
Final Rank Value:  694.1<br />
<br />
Final Rank Value (694.1) = Starting Rank Value (690.3) + Head To Head Adjustments (3.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.248[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.077[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 690.3
- 400 + ( ( 0.143 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 690.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |      173 | 2024-05-27 | Sashi Academy        | W   | 1.000      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     9.87 | anber, Dengzoe, fez, foam, Scr0b    |
|           55 |      181 | 2024-05-27 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -13.89 | anber, Dengzoe, fez, foam, Scr0b    |
|           54 |      185 | 2024-05-27 | IMMAPROBLEM          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.78 | anber, Dengzoe, fez, foam, Scr0b    |
|           53 |      592 | 2024-05-21 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -1.45 | anber, Dengzoe, fez, foam, Scr0b    |
|           52 |      665 | 2024-05-20 | WOPA Esport          | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.594 (0.085)    | 0 (0.000) |    20.14 | anber, Dengzoe, fez, foam, Scr0b    |
|           51 |      677 | 2024-05-20 | Preasy Esport        | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.705 (0.101)    | 0 (0.000) |    19.31 | anber, Dengzoe, fez, foam, Scr0b    |
|           50 |     1690 | 2024-05-07 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -0.95 | anber, Dengzoe, fez, foam, Scr0b    |
|           49 |     1750 | 2024-05-06 | Sashi Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.90 | anber, Dengzoe, fez, foam, Scr0b    |
|           48 |     1807 | 2024-05-05 | Kronjyllands Esport  | L   | 1.000      | -            | -                | -                | -         |   -22.56 | anber, Dengzoe, fez, foam, Scr0b    |
|           47 |     1940 | 2024-05-02 | L&G                  | L   | 1.000      | -            | -                | -                | -         |   -10.64 | anber, Dengzoe, fez, foam, Scr0b    |
|           46 |     2022 | 2024-05-01 | Natus Vincere Junior | W   | 1.000      | 0.289        | 0.006 (0.002)    | 0.444 (0.129)    | 0 (0.000) |    20.39 | anber, Dengzoe, fez, foam, Scr0b    |
|           45 |     2056 | 2024-04-30 | los kogutos          | L   | 1.000      | -            | -                | -                | -         |    -7.34 | anber, Dengzoe, fez, foam, Scr0b    |
|           44 |     2092 | 2024-04-29 | IMMAPROBLEM          | L   | 0.997      | -            | -                | -                | -         |   -21.39 | anber, Dengzoe, fez, foam, Scr0b    |
|           43 |     2100 | 2024-04-29 | Astralis Talent      | L   | 0.997      | -            | -                | -                | -         |    -7.89 | anber, Dengzoe, fez, foam, Scr0b    |
|           42 |     2135 | 2024-04-28 | L&G                  | W   | 0.990      | 0.289        | 0.006 (0.002)    | 0.442 (0.127)    | 0 (0.000) |    19.67 | anber, Dengzoe, fez, foam, Scr0b    |
|           41 |     2362 | 2024-04-25 | KUUSAMO.gg           | W   | 0.969      | 0.289        | 0.002 (0.001)    | 0.116 (0.033)    | 0 (0.000) |    19.33 | anber, Dengzoe, fez, foam, Scr0b    |
|           40 |     2399 | 2024-04-24 | Copenhagen Wolves    | L   | 0.964      | -            | -                | -                | -         |   -14.34 | anber, Dengzoe, fez, foam, Scr0b    |
|           39 |     2499 | 2024-04-22 | Preasy Esport        | W   | 0.950      | 0.143        | 0.008 (0.001)    | 0.705 (0.096)    | 0 (0.000) |    18.84 | anber, Dengzoe, fez, foam, Scr0b    |
|           38 |     2556 | 2024-04-21 | SINNERS Academy      | L   | 0.943      | -            | -                | -                | -         |   -14.67 | anber, Dengzoe, fez, foam, Scr0b    |
|           37 |     2613 | 2024-04-20 | MASONIC              | L   | 0.937      | -            | -                | -                | -         |    -7.54 | anber, Dengzoe, fez, foam, Scr0b    |
|           36 |     2905 | 2024-04-17 | KUUSAMO.gg           | W   | 0.916      | 0.289        | 0.002 (0.001)    | -                | 0 (0.000) |    18.64 | anber, Dengzoe, fez, foam, Scr0b    |
|           35 |     2961 | 2024-04-16 | WOPA Esport          | L   | 0.910      | -            | -                | -                | -         |    -9.67 | anber, Dengzoe, fez, foam, Scr0b    |
|           34 |     4017 | 2024-03-25 | Astralis Talent      | L   | 0.764      | -            | -                | -                | -         |    -4.93 | anber, Dengzoe, fez, foam, Scr0b    |
|           33 |     4541 | 2024-03-14 | Preasy Esport        | L   | 0.691      | -            | -                | -                | -         |    -6.97 | anber, Dengzoe, fez, foam, Scr0b    |
|           32 |     4676 | 2024-03-12 | Clownfiesta          | W   | 0.677      | -            | -                | -                | -         |     5.99 | anber, Dengzoe, fez, foam, Scr0b    |
|           31 |     4707 | 2024-03-11 | Astralis Talent      | L   | 0.671      | -            | -                | -                | -         |    -4.40 | anber, Dengzoe, fez, foam, Scr0b    |
|           30 |     4721 | 2024-03-11 | Copenhagen Wolves    | W   | 0.671      | 0.143        | -                | 0.387 (0.037)    | -         |    10.32 | anber, Dengzoe, fez, foam, Scr0b    |
|           29 |     4818 | 2024-03-09 | Begrip Gaming        | W   | 0.658      | 0.333        | -                | 0.317 (0.070)    | -         |     9.00 | anber, Dengzoe, fez, foam, Scr0b    |
|           28 |     4929 | 2024-03-07 | ADEPTS               | L   | 0.645      | -            | -                | -                | -         |    -5.21 | anber, Dengzoe, fez, foam, Scr0b    |
|           27 |     4981 | 2024-03-06 | WOPA Esport          | L   | 0.638      | -            | -                | -                | -         |    -6.51 | anber, Dengzoe, fez, foam, Scr0b    |
|           26 |     4989 | 2024-03-06 | Sashi Esport         | L   | 0.638      | -            | -                | -                | -         |    -7.24 | anber, Dengzoe, fez, foam, Scr0b    |
|           25 |     5095 | 2024-03-05 | IMMAPROBLEM          | L   | 0.631      | -            | -                | -                | -         |   -13.74 | anber, Dengzoe, fez, foam, Scr0b    |
|           24 |     5507 | 2024-02-27 | Preasy Esport        | W   | 0.584      | 0.143        | 0.008 (0.001)    | 0.705 (0.059)    | -         |    13.31 | anber, Dengzoe, fez, foam, Scr0b    |
|           23 |     5515 | 2024-02-27 | Team Atlantic        | L   | 0.584      | -            | -                | -                | -         |   -12.84 | anber, Dengzoe, fez, foam, Scr0b    |
|           22 |     6425 | 2024-02-11 | AURA                 | L   | 0.477      | -            | -                | -                | -         |    -8.98 | anber, Dengzoe, fez, foam, Scr0b    |
|           21 |     6571 | 2024-02-06 | IMMAPROBLEM          | W   | 0.444      | -            | -                | -                | -         |     4.41 | anber, Dengzoe, fez, foam, Scr0b    |
|           20 |     6605 | 2024-02-05 | Team Atlantic        | W   | 0.438      | -            | -                | -                | -         |     4.01 | anber, Dengzoe, fez, foam, Scr0b    |
|           19 |     6614 | 2024-02-05 | Copenhagen Wolves    | W   | 0.438      | -            | -                | -                | -         |     6.89 | anber, Dengzoe, fez, foam, Scr0b    |
|           18 |     6630 | 2024-02-05 | Preasy Esport        | L   | 0.437      | -            | -                | -                | -         |    -3.86 | anber, Dengzoe, fez, foam, Scr0b    |
|           17 |     6738 | 2024-02-03 | Lilmix               | L   | 0.424      | -            | -                | -                | -         |    -3.74 | anber, Dengzoe, fez, foam, Scr0b    |
|           16 |     6815 | 2024-02-02 | AURA                 | L   | 0.417      | -            | -                | -                | -         |    -7.87 | anber, Dengzoe, fez, foam, Scr0b    |
|           15 |     6920 | 2024-01-31 | WOPA Esport          | W   | 0.404      | 0.143        | -                | 0.594 (0.034)    | -         |     8.63 | anber, Dengzoe, fez, foam, Scr0b    |
|           14 |     7031 | 2024-01-29 | ex-Anonymo Esports   | L   | 0.392      | -            | -                | -                | -         |    -5.26 | anber, Dengzoe, fez, foam, Scr0b    |
|           13 |     7458 | 2024-01-22 | Astralis Talent      | W   | 0.344      | 0.143        | 0.012 (0.001)    | -                | -         |     8.80 | anber, Dengzoe, fez, foam, Scr0b    |
|           12 |     7465 | 2024-01-22 | Sashi Esport         | L   | 0.344      | -            | -                | -                | -         |    -3.98 | anber, Dengzoe, fez, foam, Scr0b    |
|           11 |     7927 | 2024-01-16 | Endpoint             | L   | 0.304      | -            | -                | -                | -         |    -1.79 | anber, Dengzoe, fez, foam, Scr0b    |
|           10 |     8251 | 2024-01-10 | ex-sYnck             | L   | 0.265      | -            | -                | -                | -         |    -3.62 | anber, Dengzoe, fez, foam, Scr0b    |
|            9 |     8260 | 2024-01-10 | Kappa Bar            | W   | 0.265      | -            | -                | -                | -         |     2.42 | anber, Dengzoe, fez, foam, Scr0b    |
|            8 |     8520 | 2024-01-03 | Preasy Esport        | L   | 0.217      | -            | -                | -                | -         |    -1.63 | Dengzoe, fez, foam, logz, Scr0b     |
|            7 |     8607 | 2023-12-22 | Looking4org          | L   | 0.138      | -            | -                | -                | -         |    -3.33 | anber, Dengzoe, fez, foam, Scr0b    |
|            6 |     8624 | 2023-12-21 | detoks               | L   | 0.131      | -            | -                | -                | -         |    -3.06 | anber, Dengzoe, fez, foam, Scr0b    |
|            5 |     9144 | 2023-12-12 | Eternal Fire Academy | L   | 0.071      | -            | -                | -                | -         |    -1.24 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            4 |     9196 | 2023-12-11 | WOPA Esport          | W   | 0.064      | -            | -                | -                | -         |     1.36 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            3 |     9279 | 2023-12-09 | fragmatic            | W   | 0.051      | -            | -                | -                | -         |     0.46 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            2 |     9494 | 2023-12-06 | showmakerz           | L   | 0.031      | -            | -                | -                | -         |    -0.68 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            1 |     9585 | 2023-12-05 | Preasy Esport        | W   | 0.023      | -            | -                | -                | -         |     0.56 | anber, Dengzoe, foam, Pellyy, Scr0b |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($276.88)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
