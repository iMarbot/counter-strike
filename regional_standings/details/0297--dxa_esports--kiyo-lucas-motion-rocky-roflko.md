### Roster Details<br />
Team Name: DXA Esports<br />
Roster: Kiyo, lucas, motion, rocky, Roflko<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [297](../standings_global.md)<br />
Regional Rank: [46]( ../standings_asia.md)<br />
Final Rank Value:  647.6<br />
<br />
Final Rank Value (647.6) = Starting Rank Value (723.4) + Head To Head Adjustments (-75.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.4
- 400 + ( ( 0.159 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 723.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      524 | 2024-05-22 | Canon Event              | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.025 (0.008)    | 0 (0.000) |     8.01 | Kiyo, lucas, motion, rocky, Roflko      |
|           40 |      532 | 2024-05-22 | Canon Event              | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.025 (0.008)    | 0 (0.000) |     8.58 | Kiyo, lucas, motion, rocky, Roflko      |
|           39 |     1213 | 2024-05-15 | KZG                      | L   | 1.000      | -            | -                | -                | -         |   -13.88 | Kiyo, lucas, motion, rocky, Roflko      |
|           38 |     1218 | 2024-05-15 | KZG                      | L   | 1.000      | -            | -                | -                | -         |   -15.15 | Kiyo, lucas, motion, rocky, Roflko      |
|           37 |     1711 | 2024-05-07 | Arcade Esports           | W   | 1.000      | 0.333        | 0.006 (0.002)    | 0.280 (0.093)    | 0 (0.000) |    18.07 | Kiyo, lucas, motion, rocky, Roflko      |
|           36 |     1717 | 2024-05-07 | Arcade Esports           | L   | 1.000      | -            | -                | -                | -         |   -13.23 | Kiyo, lucas, motion, rocky, Roflko      |
|           35 |     2853 | 2024-04-18 | Mindfreak                | L   | 0.921      | -            | -                | -                | -         |   -10.18 | Kiyo, lucas, motion, rocky, Roflko      |
|           34 |     2926 | 2024-04-17 | Blitz                    | W   | 0.915      | 0.143        | -                | 0.089 (0.012)    | 0 (0.000) |     8.00 | Kiyo, lucas, motion, rocky, Roflko      |
|           33 |     2933 | 2024-04-17 | Nine Lives               | W   | 0.915      | -            | -                | -                | 0 (0.000) |     5.52 | Kiyo, lucas, motion, rocky, Roflko      |
|           32 |     3275 | 2024-04-10 | Mindfreak                | L   | 0.868      | -            | -                | -                | -         |   -10.47 | Kiyo, lucas, motion, rocky, Roflko      |
|           31 |     3281 | 2024-04-10 | Mindfreak                | L   | 0.868      | -            | -                | -                | -         |   -11.27 | Kiyo, lucas, motion, rocky, Roflko      |
|           30 |     3661 | 2024-04-03 | Bad News Kangaroos       | L   | 0.822      | -            | -                | -                | -         |    -5.62 | Kiyo, lucas, motion, rocky, Roflko      |
|           29 |     3665 | 2024-04-03 | Bad News Kangaroos       | L   | 0.821      | -            | -                | -                | -         |    -5.91 | Kiyo, lucas, motion, rocky, Roflko      |
|           28 |     4111 | 2024-03-23 | Bad News Kangaroos       | L   | 0.748      | -            | -                | -                | -         |    -5.36 | gump, Kiyo, lucas, motion, Roflko       |
|           27 |     4114 | 2024-03-23 | KZG                      | W   | 0.748      | 0.143        | 0.011 (0.001)    | 0.223 (0.024)    | 1 (0.748) |    12.07 | gump, Kiyo, lucas, motion, Roflko       |
|           26 |     4629 | 2024-03-13 | Vantage Esports          | W   | 0.682      | 0.333        | 0.000 (0.000)    | 0.226 (0.051)    | 0 (0.000) |    10.92 | Kiyo, lucas, motion, rocky, Roflko      |
|           25 |     4637 | 2024-03-13 | Vantage Esports          | L   | 0.682      | -            | -                | -                | -         |   -10.77 | Kiyo, lucas, motion, rocky, Roflko      |
|           24 |     5042 | 2024-03-06 | FlyQuest                 | L   | 0.636      | -            | -                | -                | -         |    -0.30 | Kiyo, lucas, motion, rocky, Roflko      |
|           23 |     5048 | 2024-03-06 | FlyQuest                 | L   | 0.635      | -            | -                | -                | -         |    -0.30 | Kiyo, lucas, motion, rocky, Roflko      |
|           22 |     5898 | 2024-02-21 | Rooster                  | L   | 0.542      | -            | -                | -                | -         |    -5.57 | Kiyo, lucas, motion, rocky, Roflko      |
|           21 |     5903 | 2024-02-21 | Rooster                  | L   | 0.542      | -            | -                | -                | -         |    -5.81 | Kiyo, lucas, motion, rocky, Roflko      |
|           20 |     5968 | 2024-02-20 | Altered Edge             | L   | 0.535      | -            | -                | -                | -         |   -10.08 | Falcon, Kiyo, motion, Roflko, Valiance  |
|           19 |     6247 | 2024-02-15 | Vantage Esports          | L   | 0.502      | -            | -                | -                | -         |   -12.16 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           18 |     6251 | 2024-02-14 | sunday school            | L   | 0.501      | -            | -                | -                | -         |    -9.01 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           17 |     6356 | 2024-02-13 | Arcade Esports           | W   | 0.489      | 0.143        | 0.006 (0.000)    | 0.280 (0.020)    | 0 (0.000) |     7.33 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           16 |     6361 | 2024-02-13 | Underground Esports Club | W   | 0.488      | 0.143        | 0.000 (0.000)    | 0.070 (0.005)    | 0 (0.000) |     4.91 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           15 |     6370 | 2024-02-12 | Team RPG                 | W   | 0.488      | -            | -                | -                | 0 (0.000) |     2.32 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           14 |     6410 | 2024-02-12 | Arcade Esports           | L   | 0.481      | -            | -                | -                | -         |    -8.11 | Falcon, helix, Kiyo, lucas, Roflko      |
|           13 |     7379 | 2024-01-24 | Mindfreak                | L   | 0.355      | -            | -                | -                | -         |    -6.06 | Falcon, helix, Kiyo, lucas, Roflko      |
|           12 |     7383 | 2024-01-24 | Underground Esports Club | W   | 0.355      | 0.143        | 0.000 (0.000)    | -                | -         |     3.46 | Falcon, helix, Kiyo, lucas, Roflko      |
|           11 |     7940 | 2024-01-15 | sunday school            | L   | 0.301      | -            | -                | -                | -         |    -7.42 | Falcon, helix, Kiyo, lucas, Roflko      |
|           10 |     7969 | 2024-01-15 | Vantage Esports          | W   | 0.295      | 0.143        | 0.000 (0.000)    | 0.226 (0.010)    | -         |     3.90 | Falcon, helix, Kiyo, lucas, Roflko      |
|            9 |     7980 | 2024-01-15 | TEAM RKON                | W   | 0.295      | -            | -                | -                | -         |     2.09 | Falcon, helix, Kiyo, lucas, Roflko      |
|            8 |     8053 | 2024-01-13 | StevosFirstCS2           | W   | 0.282      | -            | -                | -                | -         |     1.98 | Falcon, helix, Kiyo, lucas, Roflko      |
|            7 |     8056 | 2024-01-13 | TEAM RKON                | L   | 0.282      | -            | -                | -                | -         |    -6.93 | Falcon, helix, Kiyo, lucas, Roflko      |
|            6 |     8064 | 2024-01-12 | Blitz                    | W   | 0.281      | 0.143        | -                | 0.089 (0.004)    | -         |     1.82 | Falcon, helix, Kiyo, lucas, Roflko      |
|            5 |     8138 | 2024-01-11 | Abyss                    | W   | 0.274      | -            | -                | -                | -         |     1.23 | Falcon, helix, Kiyo, lucas, Roflko      |
|            4 |     9024 | 2023-12-15 | Vantage Esports          | L   | 0.088      | -            | -                | -                | -         |    -1.62 | Falcon, helix, Kiyo, lucas, Roflko      |
|            3 |     9203 | 2023-12-11 | Mindfreak                | L   | 0.062      | -            | -                | -                | -         |    -1.22 | Falcon, helix, Kiyo, lucas, Roflko      |
|            2 |     9458 | 2023-12-07 | Canon Event              | W   | 0.035      | 0.270        | 0.000 (0.000)    | -                | -         |     0.26 | Falcon, helix, Kiyo, lucas, Roflko      |
|            1 |     9602 | 2023-12-05 | Dracula Flow             | W   | 0.022      | -            | -                | -                | -         |     0.10 | Falcon, helix, Kiyo, lucas, Roflko      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,648.99)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $300.00        | $300.00         |
| 2024-03-23 |      0.748 | $1,628.98      | $1,219.13       |
| 2024-02-17 |      0.519 | $250.00        | $129.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
