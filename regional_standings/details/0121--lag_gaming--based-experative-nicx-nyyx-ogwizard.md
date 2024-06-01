### Roster Details<br />
Team Name: LAG Gaming<br />
Roster: based, Experative, nicx, Nyyx, ogwizard<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [121](../standings_global.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
Final Rank Value:  824.4<br />
<br />
Final Rank Value (824.4) = Starting Rank Value (956.6) + Head To Head Adjustments (-132.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.310[<sup>2</sup>](#table1)
- Opponent Network: 0.134[<sup>2</sup>](#table1)
- LAN Wins: 0.302[<sup>2</sup>](#table1)

The average of these factors is 0.273<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 956.6
- 400 + ( ( 0.273 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 956.6


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
|           57 |       31 | 2024-05-29 | Revenge Nation     | L   | 1.000      | -            | -                | -                | -         |   -19.79 | based, Experative, nicx, Nyyx, ogwizard |
|           56 |      425 | 2024-05-22 | Limitless          | W   | 1.000      | 0.477        | -                | 0.123 (0.059)    | 0 (0.000) |     7.49 | based, Experative, nicx, Nyyx, ogwizard |
|           55 |      431 | 2024-05-22 | Limitless          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | based, Experative, nicx, Nyyx, ogwizard |
|           54 |      434 | 2024-05-22 | Wildcard Gaming    | L   | 1.000      | -            | -                | -                | -         |   -10.14 | based, Experative, nicx, Nyyx, ogwizard |
|           53 |     1114 | 2024-05-15 | NRG                | L   | 1.000      | -            | -                | -                | -         |    -9.84 | based, Experative, nicx, Nyyx, ogwizard |
|           52 |     1120 | 2024-05-15 | NRG                | L   | 1.000      | -            | -                | -                | -         |   -10.64 | based, Experative, nicx, Nyyx, ogwizard |
|           51 |     1216 | 2024-05-14 | Carpe Diem         | W   | 1.000      | 0.477        | -                | 0.243 (0.116)    | 0 (0.000) |     7.80 | based, Experative, nicx, Nyyx, ogwizard |
|           50 |     1222 | 2024-05-14 | Carpe Diem         | L   | 1.000      | -            | -                | -                | -         |   -24.25 | based, Experative, nicx, Nyyx, ogwizard |
|           49 |     1539 | 2024-05-09 | M80                | L   | 1.000      | -            | -                | -                | -         |    -2.64 | based, Experative, nicx, Nyyx, ogwizard |
|           48 |     1542 | 2024-05-09 | M80                | L   | 1.000      | -            | -                | -                | -         |    -2.71 | based, Experative, nicx, Nyyx, ogwizard |
|           47 |     1585 | 2024-05-08 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |   -11.91 | based, Experative, nicx, Nyyx, ogwizard |
|           46 |     1589 | 2024-05-08 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | based, Experative, nicx, Nyyx, ogwizard |
|           45 |     2886 | 2024-04-16 | Team Liquid        | L   | 0.912      | -            | -                | -                | -         |    -0.49 | based, Experative, nicx, Nyyx, ogwizard |
|           44 |     3140 | 2024-04-10 | Mythic             | W   | 0.873      | 0.477        | -                | 0.339 (0.141)    | 0 (0.000) |     8.07 | based, Experative, nicx, Nyyx, ogwizard |
|           43 |     3145 | 2024-04-10 | Mythic             | W   | 0.873      | 0.477        | -                | 0.339 (0.141)    | 0 (0.000) |     8.61 | based, Experative, nicx, Nyyx, ogwizard |
|           42 |     3214 | 2024-04-09 | BOSS               | L   | 0.866      | -            | -                | -                | -         |   -14.60 | based, Experative, nicx, Nyyx, ogwizard |
|           41 |     3218 | 2024-04-09 | BOSS               | L   | 0.866      | -            | -                | -                | -         |   -15.74 | based, Experative, nicx, Nyyx, ogwizard |
|           40 |     3461 | 2024-04-04 | Nouns Esports      | W   | 0.833      | 0.477        | 0.071 (0.028)    | 0.507 (0.201)    | -         |    14.99 | based, Experative, nicx, Nyyx, ogwizard |
|           39 |     3465 | 2024-04-04 | Nouns Esports      | L   | 0.833      | -            | -                | -                | -         |   -11.27 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     3523 | 2024-04-03 | Elevate            | L   | 0.826      | -            | -                | -                | -         |   -14.53 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     3525 | 2024-04-03 | Elevate            | W   | 0.826      | 0.477        | 0.012 (0.005)    | 0.475 (0.187)    | -         |    11.54 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     3839 | 2024-03-26 | Wildcard Gaming    | L   | 0.773      | -            | -                | -                | -         |   -12.80 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     3844 | 2024-03-26 | Wildcard Gaming    | W   | 0.773      | 0.477        | 0.012 (0.004)    | 0.506 (0.187)    | -         |    11.70 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     4109 | 2024-03-20 | Take Flyte         | L   | 0.733      | -            | -                | -                | -         |   -16.50 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     4115 | 2024-03-20 | Take Flyte         | W   | 0.733      | 0.477        | 0.006 (0.002)    | 0.354 (0.124)    | -         |     6.49 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     4227 | 2024-03-17 | G3                 | W   | 0.713      | 0.333        | 0.006 (0.001)    | -                | 1 (0.713) |     6.77 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     4231 | 2024-03-17 | Akimbo Esports     | W   | 0.712      | 0.333        | 0.008 (0.002)    | -                | 1 (0.712) |     6.77 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     4246 | 2024-03-17 | WICKED             | W   | 0.711      | 0.333        | 0.009 (0.002)    | -                | 1 (0.711) |     5.06 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     4266 | 2024-03-17 | FlyQuest RED       | W   | 0.710      | 0.333        | 0.016 (0.004)    | -                | 1 (0.710) |     8.33 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     4534 | 2024-03-12 | Party Astronauts   | L   | 0.679      | -            | -                | -                | -         |    -9.82 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     4772 | 2024-03-07 | FLUFFY AIMERS      | W   | 0.647      | 0.477        | 0.030 (0.009)    | 0.384 (0.118)    | -         |    10.18 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     4780 | 2024-03-07 | FLUFFY AIMERS      | L   | 0.646      | -            | -                | -                | -         |   -10.40 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     4835 | 2024-03-06 | MIGHT              | W   | 0.640      | 0.477        | -                | 0.207 (0.063)    | -         |     5.29 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     4837 | 2024-03-06 | MIGHT              | L   | 0.640      | -            | -                | -                | -         |   -15.23 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     4918 | 2024-03-05 | One More Esports   | W   | 0.633      | -            | -                | -                | -         |     5.70 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     4928 | 2024-03-05 | One More Esports   | W   | 0.633      | -            | -                | -                | -         |     5.96 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     5484 | 2024-02-24 | Limitless          | L   | 0.566      | -            | -                | -                | -         |   -13.68 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     5578 | 2024-02-23 | Elevate            | W   | 0.560      | -            | -                | -                | -         |     7.72 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     5680 | 2024-02-21 | Party Astronauts   | L   | 0.546      | -            | -                | -                | -         |    -8.61 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     5968 | 2024-02-16 | FLUFFY AIMERS      | L   | 0.512      | -            | -                | -                | -         |    -8.11 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     6016 | 2024-02-15 | Strife Esports     | W   | 0.506      | -            | -                | -                | -         |     3.36 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     6893 | 2024-01-27 | Rocket             | L   | 0.379      | -            | -                | -                | -         |   -10.40 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     7006 | 2024-01-26 | FLUFFY AIMERS      | W   | 0.373      | 0.143        | 0.030 (0.002)    | -                | -         |     6.14 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     7012 | 2024-01-26 | Third Eye          | W   | 0.372      | -            | -                | -                | -         |     0.56 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     7160 | 2024-01-23 | Limitless          | L   | 0.353      | -            | -                | -                | -         |    -8.95 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     7740 | 2024-01-14 | Bad News Bears     | W   | 0.293      | -            | -                | -                | -         |     0.62 | based, Experative, Nyyx, ogwizard, X-23 |
|           11 |     8153 | 2024-01-08 | Zomblers           | L   | 0.254      | -            | -                | -                | -         |    -6.74 | based, Experative, Nyyx, ogwizard, X-23 |
|           10 |     8430 | 2023-12-17 | MIGHT              | L   | 0.106      | -            | -                | -                | -         |    -2.73 | based, Experative, Nyyx, ogwizard, X-23 |
|            9 |     8542 | 2023-12-16 | NRG                | L   | 0.099      | -            | -                | -                | -         |    -2.09 | based, Experative, Nyyx, ogwizard, X-23 |
|            8 |     8710 | 2023-12-15 | Rocket             | W   | 0.093      | -            | -                | -                | -         |     0.24 | based, Experative, Nyyx, ogwizard, X-23 |
|            7 |     8807 | 2023-12-13 | Villainous         | W   | 0.080      | -            | -                | -                | -         |     0.41 | based, Experative, Nyyx, ogwizard, X-23 |
|            6 |     9000 | 2023-12-09 | Revenge Nation     | L   | 0.053      | -            | -                | -                | -         |    -1.31 | based, Experative, Nyyx, ogwizard, X-23 |
|            5 |     9129 | 2023-12-07 | Pantsu             | L   | 0.040      | -            | -                | -                | -         |    -1.10 | based, Experative, Nyyx, ogwizard, X-23 |
|            4 |     9196 | 2023-12-06 | MIGHT              | W   | 0.033      | -            | -                | -                | -         |     0.19 | based, Experative, Nyyx, ogwizard, X-23 |
|            3 |     9249 | 2023-12-05 | Revenge Nation     | W   | 0.027      | -            | -                | -                | -         |     0.18 | based, Experative, Nyyx, ogwizard, X-23 |
|            2 |     9352 | 2023-12-03 | Unjustified Gaming | L   | 0.012      | -            | -                | -                | -         |    -0.33 | based, Experative, Nyyx, ogwizard, X-23 |
|            1 |     9427 | 2023-12-02 | kariESPORTS        | W   | 0.006      | -            | -                | -                | 1 (0.006) |     0.01 | based, Experative, Nyyx, ogwizard, X-23 |

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
