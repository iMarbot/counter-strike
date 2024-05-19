### Roster Details<br />
Team Name: LAG Gaming (American team)<br />
Roster: based, Experative, nicx, Nyyx, ogwizard<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [96](../standings_global.md)<br />
Regional Rank: [71]( ../standings_europe.md)<br />
Final Rank Value:  868.6<br />
<br />
Final Rank Value (868.6) = Starting Rank Value (970.2) + Head To Head Adjustments (-101.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.404[<sup>1</sup>](#table2)
- Bounty Collected: 0.307[<sup>2</sup>](#table1)
- Opponent Network: 0.130[<sup>2</sup>](#table1)
- LAN Wins: 0.309[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 970.2
- 400 + ( ( 0.287 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 970.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           39 |      986 | 2024-04-16 | Team Liquid            | L   | 1.000      | -            | -                | -                | -             |    -1.42 | based, Experative, nicx, Nyyx, ogwizard |
|           38 |     1195 | 2024-04-10 | Mythic                 | W   | 1.000      | 0.477        | -                | 0.380 (0.181)    | false (0.000) |     9.13 | based, Experative, nicx, Nyyx, ogwizard |
|           37 |     1199 | 2024-04-10 | Mythic                 | W   | 1.000      | 0.477        | -                | 0.380 (0.181)    | false (0.000) |     9.84 | based, Experative, nicx, Nyyx, ogwizard |
|           36 |     1263 | 2024-04-09 | BOSS                   | L   | 1.000      | -            | -                | -                | -             |   -14.00 | based, Experative, nicx, Nyyx, ogwizard |
|           35 |     1267 | 2024-04-09 | BOSS                   | L   | 1.000      | -            | -                | -                | -             |   -15.28 | based, Experative, nicx, Nyyx, ogwizard |
|           34 |     1456 | 2024-04-04 | Nouns Esports          | W   | 0.994      | 0.477        | -                | 0.475 (0.225)    | false (0.000) |    11.99 | based, Experative, nicx, Nyyx, ogwizard |
|           33 |     1460 | 2024-04-04 | Nouns Esports          | L   | 0.994      | -            | -                | -                | -             |   -19.65 | based, Experative, nicx, Nyyx, ogwizard |
|           32 |     1511 | 2024-04-03 | Elevate                | L   | 0.987      | -            | -                | -                | -             |   -19.47 | based, Experative, nicx, Nyyx, ogwizard |
|           31 |     1513 | 2024-04-03 | Elevate                | W   | 0.987      | 0.477        | 0.030 (0.014)    | 0.268 (0.126)    | false (0.000) |    11.32 | based, Experative, nicx, Nyyx, ogwizard |
|           30 |     1781 | 2024-03-26 | Wildcard Gaming        | L   | 0.934      | -            | -                | -                | -             |   -15.30 | based, Experative, nicx, Nyyx, ogwizard |
|           29 |     1785 | 2024-03-26 | Wildcard Gaming        | W   | 0.934      | 0.477        | 0.025 (0.011)    | 0.483 (0.215)    | false (0.000) |    14.17 | based, Experative, nicx, Nyyx, ogwizard |
|           28 |     2001 | 2024-03-20 | Take Flyte             | L   | 0.894      | -            | -                | -                | -             |   -21.38 | based, Experative, nicx, Nyyx, ogwizard |
|           27 |     2007 | 2024-03-20 | Take Flyte             | W   | 0.894      | 0.477        | 0.004 (0.002)    | 0.279 (0.119)    | false (0.000) |     6.45 | based, Experative, nicx, Nyyx, ogwizard |
|           26 |     2110 | 2024-03-17 | G3 (Asian team)        | W   | 0.874      | 0.333        | 0.014 (0.004)    | -                | true (0.874)  |     7.84 | based, Experative, nicx, Nyyx, ogwizard |
|           25 |     2124 | 2024-03-17 | WICKED (American team) | W   | 0.872      | 0.333        | 0.020 (0.006)    | -                | true (0.872)  |     7.74 | based, Experative, nicx, Nyyx, ogwizard |
|           24 |     2138 | 2024-03-17 | FlyQuest RED           | W   | 0.871      | 0.333        | 0.014 (0.004)    | 0.203 (0.059)    | true (0.871)  |     9.37 | based, Experative, nicx, Nyyx, ogwizard |
|           23 |     2592 | 2024-03-06 | MIGHT                  | W   | 0.801      | 0.477        | -                | 0.213 (0.081)    | -             |     9.11 | based, Experative, nicx, Nyyx, ogwizard |
|           22 |     2594 | 2024-03-06 | MIGHT                  | L   | 0.801      | -            | -                | -                | -             |   -16.53 | based, Experative, nicx, Nyyx, ogwizard |
|           21 |     2660 | 2024-03-05 | One More Esports       | W   | 0.794      | 0.477        | 0.011 (0.004)    | 0.147 (0.056)    | -             |     6.49 | based, Experative, nicx, Nyyx, ogwizard |
|           20 |     2665 | 2024-03-05 | One More Esports       | W   | 0.794      | 0.477        | 0.011 (0.004)    | 0.147 (0.056)    | -             |     6.85 | based, Experative, nicx, Nyyx, ogwizard |
|           19 |     3123 | 2024-02-24 | Limitless              | L   | 0.727      | -            | -                | -                | -             |   -17.07 | based, Experative, nicx, Nyyx, ogwizard |
|           18 |     3188 | 2024-02-23 | Elevate                | W   | 0.721      | 0.143        | 0.030 (0.003)    | -                | -             |     8.41 | based, Experative, nicx, Nyyx, ogwizard |
|           17 |     3275 | 2024-02-21 | Party Astronauts       | L   | 0.707      | -            | -                | -                | -             |   -13.45 | based, Experative, nicx, Nyyx, ogwizard |
|           16 |     3516 | 2024-02-16 | FLUFFY AIMERS          | L   | 0.673      | -            | -                | -                | -             |   -16.56 | based, Experative, nicx, Nyyx, ogwizard |
|           15 |     3560 | 2024-02-15 | Strife Esports         | W   | 0.667      | -            | -                | -                | -             |     1.08 | based, Experative, nicx, Nyyx, ogwizard |
|           14 |     4235 | 2024-01-27 | Rocket                 | L   | 0.541      | -            | -                | -                | -             |   -12.67 | based, Experative, nicx, Nyyx, ogwizard |
|           13 |     4301 | 2024-01-26 | Third Eye              | W   | 0.534      | -            | -                | -                | -             |     0.82 | based, Experative, nicx, Nyyx, ogwizard |
|           12 |     4416 | 2024-01-23 | Limitless              | L   | 0.514      | -            | -                | -                | -             |   -13.27 | based, Experative, nicx, Nyyx, ogwizard |
|           11 |     4860 | 2024-01-14 | Bad News Bears         | W   | 0.454      | -            | -                | -                | -             |     1.05 | based, Experative, Nyyx, ogwizard, X-23 |
|           10 |     5137 | 2024-01-08 | Zomblers               | L   | 0.415      | -            | -                | -                | -             |   -10.81 | based, Experative, Nyyx, ogwizard, X-23 |
|            9 |     5337 | 2023-12-17 | MIGHT                  | L   | 0.267      | -            | -                | -                | -             |    -6.68 | based, Experative, Nyyx, ogwizard, X-23 |
|            8 |     5560 | 2023-12-15 | Rocket                 | W   | 0.254      | -            | -                | -                | -             |     1.30 | based, Experative, Nyyx, ogwizard, X-23 |
|            7 |     5626 | 2023-12-13 | Villainous             | W   | 0.241      | -            | -                | -                | -             |     0.81 | based, Experative, Nyyx, ogwizard, X-23 |
|            6 |     5750 | 2023-12-09 | Revenge Nation         | L   | 0.214      | -            | -                | -                | -             |    -5.33 | based, Experative, Nyyx, ogwizard, X-23 |
|            5 |     5858 | 2023-12-07 | Pantsu                 | L   | 0.201      | -            | -                | -                | -             |    -5.38 | based, Experative, Nyyx, ogwizard, X-23 |
|            4 |     5910 | 2023-12-06 | MIGHT                  | W   | 0.194      | -            | -                | -                | -             |     1.23 | based, Experative, Nyyx, ogwizard, X-23 |
|            3 |     5954 | 2023-12-05 | Revenge Nation         | W   | 0.188      | 0.371        | 0.043 (0.003)    | -                | -             |     1.22 | based, Experative, Nyyx, ogwizard, X-23 |
|            2 |     6028 | 2023-12-03 | Carpe Diem             | L   | 0.173      | -            | -                | -                | -             |    -4.33 | based, Experative, Nyyx, ogwizard, X-23 |
|            1 |     6183 | 2023-11-30 | Peeker's Advantage     | W   | 0.154      | -            | -                | -                | true (0.154)  |     0.82 | based, Experative, Nyyx, ogwizard, X-23 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,283.36)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-17 |      0.874 | $5,500.00      | $4,809.19       |
| 2023-12-13 |      0.241 | $1,250.00      | $301.16         |
| 2023-12-03 |      0.173 | $1,000.00      | $173.01         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
