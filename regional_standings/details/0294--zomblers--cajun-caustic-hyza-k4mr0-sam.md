### Roster Details<br />
Team Name: Zomblers<br />
Roster: CAJUN, caustic, hyza, K4mr0, sam<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [294](../standings_global.md)<br />
Regional Rank: [65]( ../standings_americas.md)<br />
Final Rank Value:  649.0<br />
<br />
Final Rank Value (649.0) = Starting Rank Value (649.4) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 649.4
- 400 + ( ( 0.123 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 649.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     2941 | 2024-04-16 | NRG               | L   | 0.913      | -            | -                | -                | -         |    -5.36 | CAJUN, caustic, hyza, K4mr0, sam   |
|           16 |     4334 | 2024-03-17 | Akimbo Esports    | L   | 0.713      | -            | -                | -                | -         |    -7.93 | CAJUN, caustic, K4mr0, Marro, sam  |
|           15 |     4466 | 2024-03-15 | Snakes Den Gaming | W   | 0.700      | 0.371        | 0.002 (0.000)    | 0.054 (0.014)    | 0 (0.000) |    10.38 | CAJUN, caustic, K4mr0, Marro, sam  |
|           14 |     4570 | 2024-03-13 | eefsports         | W   | 0.686      | 0.371        | 0.000 (0.000)    | 0.035 (0.009)    | 0 (0.000) |     9.12 | CAJUN, caustic, K4mr0, Marro, sam  |
|           13 |     4696 | 2024-03-11 | Pryde             | W   | 0.673      | 0.371        | 0.000 (0.000)    | 0.043 (0.011)    | 0 (0.000) |     6.53 | CAJUN, caustic, K4mr0, Marro, sam  |
|           12 |     4762 | 2024-03-10 | KingsOfTheNorth   | W   | 0.666      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.37 | CAJUN, caustic, K4mr0, Marro, sam  |
|           11 |     4903 | 2024-03-07 | Akimbo Esports    | L   | 0.647      | -            | -                | -                | -         |    -6.91 | CAJUN, caustic, K4mr0, Marro, sam  |
|           10 |     5061 | 2024-03-05 | Lore Gaming       | W   | 0.633      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.18 | CAJUN, caustic, K4mr0, Marro, sam  |
|            9 |     6189 | 2024-02-15 | Limitless         | L   | 0.506      | -            | -                | -                | -         |    -6.83 | CAJUN, K4mr0, Marro, sam, seziwana |
|            8 |     7229 | 2024-01-26 | Limitless         | L   | 0.373      | -            | -                | -                | -         |    -5.10 | CAJUN, K4mr0, Marro, sam, X-23     |
|            7 |     7695 | 2024-01-18 | Nouns Esports     | L   | 0.319      | -            | -                | -                | -         |    -1.70 | CAJUN, K4mr0, Marro, sam, seziwana |
|            6 |     7750 | 2024-01-17 | FPL Friends       | W   | 0.313      | 0.143        | 0.001 (0.000)    | 0.011 (0.001)    | 0 (0.000) |     4.79 | CAJUN, K4mr0, Marro, sam, seziwana |
|            5 |     7945 | 2024-01-15 | Party Astronauts  | L   | 0.299      | -            | -                | -                | -         |    -1.52 | CAJUN, K4mr0, Marro, sam, seziwana |
|            4 |     8222 | 2024-01-10 | MIGHT             | L   | 0.267      | -            | -                | -                | -         |    -3.75 | CAJUN, K4mr0, Marro, sam, seziwana |
|            3 |     8300 | 2024-01-09 | vagrants          | L   | 0.260      | -            | -                | -                | -         |    -5.72 | CAJUN, K4mr0, Marro, sam, seziwana |
|            2 |     8407 | 2024-01-08 | LAG Gaming        | W   | 0.254      | 0.143        | 0.013 (0.000)    | 0.335 (0.012)    | 0 (0.000) |     6.74 | CAJUN, K4mr0, Marro, sam, seziwana |
|            1 |     8804 | 2023-12-16 | FLUFFY AIMERS     | L   | 0.099      | -            | -                | -                | -         |    -1.72 | CAJUN, DJF, K4mr0, LittleBEER, sam |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($940.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
