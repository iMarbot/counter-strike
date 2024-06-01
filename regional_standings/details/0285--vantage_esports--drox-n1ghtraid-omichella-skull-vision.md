### Roster Details<br />
Team Name: Vantage Esports<br />
Roster: Drox, N1ghtraid, Omichella, SkulL, vision<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [285](../standings_global.md)<br />
Regional Rank: [47]( ../standings_asia.md)<br />
Final Rank Value:  652.3<br />
<br />
Final Rank Value (652.3) = Starting Rank Value (650.3) + Head To Head Adjustments (2.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.213[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 650.3
- 400 + ( ( 0.123 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 650.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      520 | 2024-05-22 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -7.54 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           44 |      523 | 2024-05-22 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -8.05 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           43 |      934 | 2024-05-17 | Bad News Kangaroos | L   | 1.000      | -            | -                | -                | -         |    -7.00 | Drox, Jynx, Omichella, SkulL, vision        |
|           42 |      935 | 2024-05-17 | Arcade Esports     | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.264 (0.038)    | 0 (0.000) |    15.52 | Drox, Jynx, Omichella, SkulL, vision        |
|           41 |      938 | 2024-05-17 | Mindfreak          | L   | 1.000      | -            | -                | -                | -         |    -9.45 | Drox, Jynx, Omichella, SkulL, vision        |
|           40 |     2467 | 2024-04-22 | Mindfreak          | L   | 0.949      | -            | -                | -                | -         |   -10.55 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           39 |     2469 | 2024-04-22 | Mindfreak          | L   | 0.948      | -            | -                | -                | -         |   -11.40 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           38 |     2863 | 2024-04-17 | Arcade Esports     | L   | 0.915      | -            | -                | -                | -         |   -13.84 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           37 |     2879 | 2024-04-17 | Imports            | W   | 0.915      | -            | -                | -                | 0 (0.000) |     4.30 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           36 |     3570 | 2024-04-03 | KZG                | W   | 0.822      | 0.333        | 0.011 (0.003)    | 0.223 (0.061)    | 0 (0.000) |    12.97 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           35 |     3578 | 2024-04-03 | KZG                | W   | 0.821      | 0.333        | 0.011 (0.003)    | 0.223 (0.061)    | 0 (0.000) |    13.94 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           34 |     3830 | 2024-03-27 | Canon Event        | W   | 0.776      | 0.333        | 0.000 (0.000)    | 0.025 (0.007)    | 0 (0.000) |     6.77 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           33 |     3833 | 2024-03-27 | Canon Event        | W   | 0.775      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     7.16 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           32 |     4513 | 2024-03-13 | DXA Esports        | L   | 0.682      | -            | -                | -                | -         |   -10.54 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           31 |     4518 | 2024-03-13 | DXA Esports        | W   | 0.682      | 0.333        | 0.005 (0.001)    | 0.196 (0.044)    | 0 (0.000) |    11.18 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           30 |     4907 | 2024-03-06 | Bad News Kangaroos | L   | 0.636      | -            | -                | -                | -         |    -4.13 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           29 |     4910 | 2024-03-06 | Bad News Kangaroos | L   | 0.635      | -            | -                | -                | -         |    -4.29 | Drox, N1ghtraid, Omichella, SkulL, vision   |
|           28 |     5670 | 2024-02-22 | Bad News Kangaroos | L   | 0.548      | -            | -                | -                | -         |    -3.66 | Drox, Omichella, SkulL, viridian, vision    |
|           27 |     5673 | 2024-02-21 | Rooster            | L   | 0.547      | -            | -                | -                | -         |    -5.41 | Drox, Omichella, SkulL, viridian, vision    |
|           26 |     5741 | 2024-02-20 | Arcade Esports     | W   | 0.541      | 0.143        | 0.006 (0.000)    | 0.264 (0.020)    | 0 (0.000) |     9.60 | Drox, Omichella, SkulL, viridian, vision    |
|           25 |     5789 | 2024-02-20 | Mindfreak          | W   | 0.535      | 0.143        | -                | 0.306 (0.023)    | 0 (0.000) |     9.52 | Drox, Omichella, SkulL, viridian, vision    |
|           24 |     5791 | 2024-02-20 | Blitz              | W   | 0.535      | 0.143        | -                | 0.089 (0.007)    | 0 (0.000) |     4.38 | Drox, Omichella, SkulL, viridian, vision    |
|           23 |     5801 | 2024-02-19 | Team RPG           | W   | 0.535      | -            | -                | -                | -         |     3.28 | Drox, Omichella, SkulL, viridian, vision    |
|           22 |     5894 | 2024-02-18 | Mindfreak          | L   | 0.522      | -            | -                | -                | -         |    -7.26 | Drox, Omichella, SkulL, viridian, vision    |
|           21 |     5898 | 2024-02-18 | LE-LUX Esports     | W   | 0.522      | -            | -                | -                | -         |     6.83 | Drox, Omichella, SkulL, viridian, vision    |
|           20 |     5905 | 2024-02-17 | Golf Club          | W   | 0.521      | -            | -                | -                | -         |     4.44 | Drox, Omichella, SkulL, viridian, vision    |
|           19 |     6009 | 2024-02-15 | sunday school      | L   | 0.507      | -            | -                | -                | -         |    -7.54 | damyo, Omichella, SkulL, viridian, vision   |
|           18 |     6066 | 2024-02-15 | DXA Esports        | W   | 0.502      | 0.143        | 0.005 (0.000)    | 0.196 (0.014)    | -         |     9.30 | damyo, Omichella, SkulL, viridian, vision   |
|           17 |     6071 | 2024-02-14 | KZG                | L   | 0.501      | -            | -                | -                | -         |    -6.05 | damyo, Omichella, SkulL, viridian, vision   |
|           16 |     7092 | 2024-01-25 | Bad News Kangaroos | L   | 0.362      | -            | -                | -                | -         |    -6.05 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           15 |     7142 | 2024-01-24 | KZG                | W   | 0.355      | 0.143        | 0.011 (0.001)    | 0.223 (0.011)    | -         |     6.84 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           14 |     7150 | 2024-01-24 | WIDERALLY          | W   | 0.355      | -            | -                | -                | -         |     2.23 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           13 |     7366 | 2024-01-20 | FlyQuest           | L   | 0.328      | -            | -                | -                | -         |    -0.13 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           12 |     7377 | 2024-01-19 | StevosFirstCS2     | W   | 0.327      | -            | -                | -                | -         |     3.02 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           11 |     7438 | 2024-01-18 | Mindfreak          | L   | 0.321      | -            | -                | -                | -         |    -4.74 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|           10 |     7498 | 2024-01-17 | Mindfreak          | L   | 0.314      | -            | -                | -                | -         |    -4.85 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            9 |     7592 | 2024-01-17 | FARMsim            | W   | 0.308      | -            | -                | -                | -         |     1.94 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            8 |     7597 | 2024-01-17 | Dracula Flow       | W   | 0.308      | -            | -                | -                | -         |     1.90 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            7 |     7717 | 2024-01-15 | DXA Esports        | L   | 0.295      | -            | -                | -                | -         |    -3.76 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            6 |     7727 | 2024-01-15 | Dracula Flow       | W   | 0.295      | -            | -                | -                | -         |     1.82 | KRAXYT, N1ghtraid, Omichella, SkulL, vision |
|            5 |     8512 | 2023-12-17 | Mindfreak          | L   | 0.102      | -            | -                | -                | -         |    -1.69 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            4 |     8762 | 2023-12-15 | DXA Esports        | W   | 0.088      | 0.270        | 0.005 (0.000)    | -                | -         |     1.66 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            3 |     8893 | 2023-12-12 | TEAM RKON          | W   | 0.068      | -            | -                | -                | -         |     0.63 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            2 |     8994 | 2023-12-10 | Golf Club          | W   | 0.055      | -            | -                | -                | -         |     0.47 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |
|            1 |     9186 | 2023-12-07 | Dracula Flow       | W   | 0.035      | -            | -                | -                | -         |     0.22 | Kobe, KRAXYT, N1ghtraid, Omichella, vision  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
