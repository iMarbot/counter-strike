### Roster Details<br />
Team Name: Team Liquid<br />
Roster: cadiaN, NAF, skullz, Twistzz, YEKINDAR<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [20](../standings_global.md)<br />
Regional Rank: [5]( ../standings_americas.md)<br />
Final Rank Value:  1436.5<br />
<br />
Final Rank Value (1436.5) = Starting Rank Value (1389.0) + Head To Head Adjustments (47.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.526[<sup>1</sup>](#table2)
- Bounty Collected: 0.558[<sup>2</sup>](#table1)
- Opponent Network: 0.177[<sup>2</sup>](#table1)
- LAN Wins: 0.734[<sup>2</sup>](#table1)

The average of these factors is 0.499<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1389.0
- 400 + ( ( 0.499 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1389.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |       45 | 2024-05-04 | MOUZ                       | L   | 1.000      | -            | -                | -                | -             |    -2.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           39 |      196 | 2024-05-01 | Monte                      | W   | 1.000      | 0.889        | 0.199 (0.177)    | 0.378 (0.336)    | true (1.000)  |    10.76 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           38 |      234 | 2024-04-30 | FURIA Esports              | W   | 1.000      | 0.889        | 0.384 (0.341)    | 0.361 (0.321)    | true (1.000)  |    18.82 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           37 |      788 | 2024-04-19 | M80                        | L   | 1.000      | -            | -                | -                | -             |   -21.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           36 |      859 | 2024-04-18 | M80                        | W   | 1.000      | 0.143        | 0.155 (0.022)    | 0.405 (0.058)    | false (0.000) |     8.87 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           35 |      863 | 2024-04-18 | Legacy                     | W   | 1.000      | 0.143        | 0.061 (0.009)    | -                | false (0.000) |     6.43 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |      913 | 2024-04-17 | G3 (Asian team)            | W   | 1.000      | -            | -                | -                | -             |     0.85 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |      986 | 2024-04-16 | LAG Gaming (American team) | W   | 1.000      | 0.143        | -                | 0.405 (0.058)    | -             |     1.42 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     1153 | 2024-04-12 | FaZe Clan                  | L   | 1.000      | -            | -                | -                | -             |    -1.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     1257 | 2024-04-10 | MOUZ                       | L   | 1.000      | -            | -                | -                | -             |    -2.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     1349 | 2024-04-08 | G2 Esports                 | W   | 1.000      | 0.624        | 0.866 (0.540)    | 0.477 (0.298)    | true (1.000)  |    29.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     1360 | 2024-04-07 | HEROIC                     | W   | 1.000      | 0.624        | 0.243 (0.152)    | 0.537 (0.335)    | true (1.000)  |    25.92 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     2578 | 2024-03-07 | SAW                        | L   | 0.804      | -            | -                | -                | -             |    -9.76 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     2728 | 2024-03-04 | Complexity Gaming          | L   | 0.786      | -            | -                | -                | -             |    -8.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     2804 | 2024-03-03 | BOSS                       | W   | 0.778      | 0.143        | 0.051 (0.006)    | -                | true (0.778)  |     1.63 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     2871 | 2024-03-02 | FURIA Esports              | L   | 0.772      | -            | -                | -                | -             |    -5.81 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     2904 | 2024-03-01 | BESTIA                     | W   | 0.766      | -            | -                | -                | true (0.766)  |     1.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     3052 | 2024-02-26 | Nouns Esports              | W   | 0.741      | 0.143        | -                | 0.475 (0.050)    | -             |     0.56 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     3055 | 2024-02-26 | BOSS                       | W   | 0.740      | 0.143        | 0.051 (0.005)    | -                | -             |     1.37 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     3087 | 2024-02-25 | Wildcard Gaming            | W   | 0.734      | 0.143        | -                | 0.483 (0.051)    | -             |     1.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     3091 | 2024-02-25 | Nouns Esports              | L   | 0.733      | -            | -                | -                | -             |   -22.66 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     3227 | 2024-02-22 | Party Astronauts           | W   | 0.714      | -            | -                | -                | -             |     0.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     3228 | 2024-02-22 | MIGHT                      | W   | 0.714      | -            | -                | -                | -             |     0.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     3276 | 2024-02-21 | Slava Ukraine              | W   | 0.707      | -            | -                | -                | -             |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     4212 | 2024-01-28 | G2 Esports                 | L   | 0.545      | -            | -                | -                | -             |    -1.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     4267 | 2024-01-27 | FaZe Clan                  | L   | 0.538      | -            | -                | -                | -             |    -0.61 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     4362 | 2024-01-25 | GamerLegion                | W   | 0.523      | 0.581        | 0.194 (0.059)    | 0.419 (0.127)    | true (0.523)  |    12.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     4389 | 2024-01-24 | Team Spirit                | W   | 0.517      | 0.581        | 1.000 (0.301)    | 0.433 (0.130)    | true (0.517)  |    15.10 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     4524 | 2024-01-20 | M80                        | L   | 0.494      | -            | -                | -                | -             |    -9.92 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     4583 | 2024-01-19 | Wildcard Gaming            | W   | 0.488      | -            | -                | -                | -             |     0.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     4591 | 2024-01-19 | BOSS                       | W   | 0.486      | -            | -                | -                | -             |     0.97 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     4769 | 2024-01-16 | Elevate                    | W   | 0.467      | -            | -                | -                | -             |     0.58 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     4772 | 2024-01-16 | Wildcard Gaming            | W   | 0.467      | -            | -                | -                | -             |     0.79 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     4821 | 2024-01-15 | LOS                        | W   | 0.461      | -            | -                | -                | -             |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     4863 | 2024-01-14 | Party Astronauts           | W   | 0.454      | -            | -                | -                | -             |     0.57 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     4876 | 2024-01-13 | Elevate                    | W   | 0.447      | -            | -                | -                | -             |     0.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     4909 | 2024-01-12 | M80                        | L   | 0.442      | -            | -                | -                | -             |    -8.70 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     4914 | 2024-01-12 | Nouns Esports              | W   | 0.441      | -            | -                | -                | -             |     0.20 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     5064 | 2024-01-09 | LOS                        | W   | 0.421      | -            | -                | -                | -             |     0.10 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     5132 | 2024-01-08 | Maximum Ego                | W   | 0.415      | -            | -                | -                | -             |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,851.37)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.13) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-03-10 |      0.826 | $5,000.00      | $4,127.89       |
| 2024-01-28 |      0.545 | $10,500.00     | $5,723.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
