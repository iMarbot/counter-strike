### Roster Details<br />
Team Name: LAG Gaming<br />
Roster: based, Experative, nicx, Nyyx, ogwizard<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [124](../standings_global.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
Final Rank Value:  824.8<br />
<br />
Final Rank Value (824.8) = Starting Rank Value (956.2) + Head To Head Adjustments (-131.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.302[<sup>2</sup>](#table1)

The average of these factors is 0.274<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.2
- 400 + ( ( 0.274 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 956.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |       31 | 2024-05-29 | Revenge Nation     | L   | 1.000      | -            | -                | -                | -         |   -19.82 | based, Experative, nicx, Nyyx, ogwizard |
|           56 |      433 | 2024-05-22 | Limitless          | W   | 1.000      | 0.477        | -                | 0.123 (0.059)    | 0 (0.000) |     7.48 | based, Experative, nicx, Nyyx, ogwizard |
|           55 |      439 | 2024-05-22 | Limitless          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | based, Experative, nicx, Nyyx, ogwizard |
|           54 |      441 | 2024-05-22 | Wildcard Gaming    | L   | 1.000      | -            | -                | -                | -         |    -9.97 | based, Experative, nicx, Nyyx, ogwizard |
|           53 |     1124 | 2024-05-15 | NRG                | L   | 1.000      | -            | -                | -                | -         |    -9.82 | based, Experative, nicx, Nyyx, ogwizard |
|           52 |     1130 | 2024-05-15 | NRG                | L   | 1.000      | -            | -                | -                | -         |   -10.61 | based, Experative, nicx, Nyyx, ogwizard |
|           51 |     1226 | 2024-05-14 | Carpe Diem         | W   | 1.000      | 0.477        | -                | 0.243 (0.116)    | 0 (0.000) |     7.78 | based, Experative, nicx, Nyyx, ogwizard |
|           50 |     1232 | 2024-05-14 | Carpe Diem         | L   | 1.000      | -            | -                | -                | -         |   -24.28 | based, Experative, nicx, Nyyx, ogwizard |
|           49 |     1554 | 2024-05-09 | M80                | L   | 1.000      | -            | -                | -                | -         |    -2.77 | based, Experative, nicx, Nyyx, ogwizard |
|           48 |     1557 | 2024-05-09 | M80                | L   | 1.000      | -            | -                | -                | -         |    -2.85 | based, Experative, nicx, Nyyx, ogwizard |
|           47 |     1601 | 2024-05-08 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |   -11.91 | based, Experative, nicx, Nyyx, ogwizard |
|           46 |     1605 | 2024-05-08 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |   -12.96 | based, Experative, nicx, Nyyx, ogwizard |
|           45 |     2944 | 2024-04-16 | Team Liquid        | L   | 0.912      | -            | -                | -                | -         |    -0.51 | based, Experative, nicx, Nyyx, ogwizard |
|           44 |     3211 | 2024-04-10 | Mythic             | W   | 0.873      | 0.477        | -                | 0.339 (0.141)    | 0 (0.000) |     8.21 | based, Experative, nicx, Nyyx, ogwizard |
|           43 |     3216 | 2024-04-10 | Mythic             | W   | 0.873      | 0.477        | -                | 0.339 (0.141)    | 0 (0.000) |     8.77 | based, Experative, nicx, Nyyx, ogwizard |
|           42 |     3292 | 2024-04-09 | BOSS               | L   | 0.866      | -            | -                | -                | -         |   -14.65 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     3296 | 2024-04-09 | BOSS               | L   | 0.866      | -            | -                | -                | -         |   -15.80 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     3546 | 2024-04-04 | Nouns Esports      | W   | 0.833      | 0.477        | 0.071 (0.028)    | 0.507 (0.201)    | -         |    14.97 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     3550 | 2024-04-04 | Nouns Esports      | L   | 0.833      | -            | -                | -                | -         |   -11.29 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     3610 | 2024-04-03 | Elevate            | L   | 0.826      | -            | -                | -                | -         |   -14.70 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     3612 | 2024-04-03 | Elevate            | W   | 0.826      | 0.477        | 0.012 (0.005)    | 0.480 (0.189)    | -         |    11.37 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     3936 | 2024-03-26 | Wildcard Gaming    | L   | 0.773      | -            | -                | -                | -         |   -12.39 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     3941 | 2024-03-26 | Wildcard Gaming    | W   | 0.773      | 0.477        | 0.012 (0.004)    | 0.525 (0.194)    | -         |    12.15 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     4209 | 2024-03-20 | Take Flyte         | L   | 0.733      | -            | -                | -                | -         |   -16.80 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     4215 | 2024-03-20 | Take Flyte         | W   | 0.733      | 0.477        | 0.006 (0.002)    | 0.354 (0.124)    | -         |     6.18 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     4332 | 2024-03-17 | G3                 | W   | 0.713      | 0.333        | 0.006 (0.001)    | -                | 1 (0.713) |     7.65 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     4336 | 2024-03-17 | Akimbo Esports     | W   | 0.712      | 0.333        | 0.008 (0.002)    | -                | 1 (0.712) |     6.77 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     4351 | 2024-03-17 | WICKED             | W   | 0.711      | 0.333        | 0.009 (0.002)    | -                | 1 (0.711) |     5.06 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     4371 | 2024-03-17 | FlyQuest RED       | W   | 0.710      | 0.333        | 0.016 (0.004)    | -                | 1 (0.710) |     8.33 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     4653 | 2024-03-12 | Party Astronauts   | L   | 0.679      | -            | -                | -                | -         |    -9.79 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     4900 | 2024-03-07 | FLUFFY AIMERS      | W   | 0.647      | 0.477        | 0.030 (0.009)    | 0.384 (0.118)    | -         |    10.19 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     4908 | 2024-03-07 | FLUFFY AIMERS      | L   | 0.646      | -            | -                | -                | -         |   -10.40 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     4966 | 2024-03-06 | MIGHT              | W   | 0.640      | 0.477        | -                | 0.207 (0.063)    | -         |     5.30 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     4968 | 2024-03-06 | MIGHT              | L   | 0.640      | -            | -                | -                | -         |   -15.22 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     5057 | 2024-03-05 | One More Esports   | W   | 0.633      | -            | -                | -                | -         |     5.70 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     5067 | 2024-03-05 | One More Esports   | W   | 0.633      | -            | -                | -                | -         |     5.96 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     5643 | 2024-02-24 | Limitless          | L   | 0.566      | -            | -                | -                | -         |   -13.67 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     5738 | 2024-02-23 | Elevate            | W   | 0.560      | -            | -                | -                | -         |     7.61 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     5841 | 2024-02-21 | Party Astronauts   | L   | 0.546      | -            | -                | -                | -         |    -8.58 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     6141 | 2024-02-16 | FLUFFY AIMERS      | L   | 0.512      | -            | -                | -                | -         |    -8.12 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     6192 | 2024-02-15 | Strife Esports     | W   | 0.506      | -            | -                | -                | -         |     3.36 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     7111 | 2024-01-27 | Rocket             | L   | 0.379      | -            | -                | -                | -         |   -10.39 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     7226 | 2024-01-26 | FLUFFY AIMERS      | W   | 0.373      | 0.143        | 0.030 (0.002)    | -                | -         |     6.14 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     7232 | 2024-01-26 | Third Eye          | W   | 0.372      | -            | -                | -                | -         |     0.56 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     7395 | 2024-01-23 | Limitless          | L   | 0.353      | -            | -                | -                | -         |    -8.96 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     7993 | 2024-01-14 | Bad News Bears     | W   | 0.293      | -            | -                | -                | -         |     0.63 | based, Experative, Nyyx, ogwizard, X-23 |
|           11 |     8407 | 2024-01-08 | Zomblers           | L   | 0.254      | -            | -                | -                | -         |    -6.74 | based, Experative, Nyyx, ogwizard, X-23 |
|           10 |     8687 | 2023-12-17 | MIGHT              | L   | 0.106      | -            | -                | -                | -         |    -2.73 | based, Experative, Nyyx, ogwizard, X-23 |
|            9 |     8802 | 2023-12-16 | NRG                | L   | 0.099      | -            | -                | -                | -         |    -2.09 | based, Experative, Nyyx, ogwizard, X-23 |
|            8 |     8971 | 2023-12-15 | Rocket             | W   | 0.093      | -            | -                | -                | -         |     0.24 | based, Experative, Nyyx, ogwizard, X-23 |
|            7 |     9070 | 2023-12-13 | Villainous         | W   | 0.080      | -            | -                | -                | -         |     0.41 | based, Experative, Nyyx, ogwizard, X-23 |
|            6 |     9266 | 2023-12-09 | Revenge Nation     | L   | 0.053      | -            | -                | -                | -         |    -1.32 | based, Experative, Nyyx, ogwizard, X-23 |
|            5 |     9399 | 2023-12-07 | Pantsu             | L   | 0.040      | -            | -                | -                | -         |    -1.10 | based, Experative, Nyyx, ogwizard, X-23 |
|            4 |     9469 | 2023-12-06 | MIGHT              | W   | 0.033      | -            | -                | -                | -         |     0.19 | based, Experative, Nyyx, ogwizard, X-23 |
|            3 |     9530 | 2023-12-05 | Revenge Nation     | W   | 0.027      | -            | -                | -                | -         |     0.18 | based, Experative, Nyyx, ogwizard, X-23 |
|            2 |     9634 | 2023-12-03 | Unjustified Gaming | L   | 0.012      | -            | -                | -                | -         |    -0.33 | based, Experative, Nyyx, ogwizard, X-23 |
|            1 |     9709 | 2023-12-02 | kariESPORTS        | W   | 0.006      | -            | -                | -                | 1 (0.006) |     0.01 | based, Experative, Nyyx, ogwizard, X-23 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,036.08)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-17 |      0.713 | $5,500.00      | $3,923.33       |
| 2023-12-13 |      0.080 | $1,250.00      | $99.83          |
| 2023-12-03 |      0.013 | $1,000.00      | $12.92          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
