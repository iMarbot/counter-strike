### Roster Details<br />
Team Name: Team Liquid<br />
Roster: cadiaN, NAF, skullz, Twistzz, YEKINDAR<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [10](../standings_global.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
Final Rank Value:  1614.1<br />
<br />
Final Rank Value (1614.1) = Starting Rank Value (1667.1) + Head To Head Adjustments (-53.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.765[<sup>1</sup>](#table2)
- Bounty Collected: 0.586[<sup>2</sup>](#table1)
- Opponent Network: 0.265[<sup>2</sup>](#table1)
- LAN Wins: 0.877[<sup>2</sup>](#table1)

The average of these factors is 0.623<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1667.1
- 400 + ( ( 0.623 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1667.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |       33 | 2024-05-29 | G2 Esports        | L   | 1.000      | -            | -                | -                | -         |    -9.41 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           56 |      110 | 2024-05-28 | Team Falcons      | W   | 1.000      | 0.624        | 0.355 (0.221)    | -                | 1 (1.000) |     8.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           55 |      150 | 2024-05-27 | 9z Team           | L   | 1.000      | -            | -                | -                | -         |   -28.28 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           54 |      169 | 2024-05-27 | Complexity Gaming | W   | 1.000      | 0.624        | 0.260 (0.162)    | 0.219 (0.136)    | 1 (1.000) |    14.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           53 |      419 | 2024-05-23 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -9.81 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           52 |      523 | 2024-05-22 | Astralis          | W   | 1.000      | 0.769        | 0.395 (0.304)    | 0.286 (0.220)    | -         |    18.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           51 |      632 | 2024-05-21 | ENCE              | W   | 1.000      | 0.769        | 0.202 (0.155)    | 0.280 (0.215)    | -         |     4.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           50 |      792 | 2024-05-19 | AMKAL ESPORTS     | W   | 1.000      | 0.769        | -                | 0.565 (0.435)    | -         |     3.91 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           49 |      844 | 2024-05-18 | OG                | W   | 1.000      | 0.769        | 0.277 (0.213)    | 0.257 (0.197)    | -         |     3.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           48 |     1531 | 2024-05-10 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -11.83 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           47 |     1657 | 2024-05-08 | FlyQuest          | W   | 1.000      | 0.889        | -                | 0.466 (0.414)    | 1 (1.000) |     8.90 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           46 |     1828 | 2024-05-04 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -3.91 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           45 |     2003 | 2024-05-01 | Monte             | W   | 1.000      | 0.889        | 0.181 (0.161)    | 0.387 (0.344)    | 1 (1.000) |     3.47 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           44 |     2052 | 2024-04-30 | FURIA Esports     | W   | 1.000      | 0.889        | 0.138 (0.122)    | 0.267 (0.237)    | 1 (1.000) |     6.79 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           43 |     2716 | 2024-04-19 | M80               | L   | 0.933      | -            | -                | -                | -         |   -25.74 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           42 |     2795 | 2024-04-18 | M80               | W   | 0.926      | -            | -                | -                | -         |     3.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           41 |     2800 | 2024-04-18 | Legacy            | W   | 0.925      | -            | -                | -                | -         |     1.39 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           40 |     2858 | 2024-04-17 | G3                | W   | 0.919      | -            | -                | -                | -         |     0.35 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           39 |     2861 | 2024-04-17 | straykids         | W   | 0.918      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           38 |     2944 | 2024-04-16 | LAG Gaming        | W   | 0.912      | -            | -                | -                | -         |     0.51 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           37 |     3156 | 2024-04-12 | FaZe Clan         | L   | 0.882      | -            | -                | -                | -         |    -4.06 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           36 |     3286 | 2024-04-10 | MOUZ              | L   | 0.868      | -            | -                | -                | -         |    -3.67 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           35 |     3392 | 2024-04-08 | G2 Esports        | W   | 0.855      | 0.624        | 0.468 (0.250)    | 0.392 (0.209)    | 1 (0.855) |    19.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     3403 | 2024-04-07 | HEROIC            | W   | 0.853      | 0.624        | 0.322 (0.171)    | 0.463 (0.247)    | 1 (0.853) |    16.87 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     4949 | 2024-03-07 | SAW               | L   | 0.643      | -            | -                | -                | -         |   -16.26 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     5142 | 2024-03-04 | Complexity Gaming | L   | 0.625      | -            | -                | -                | -         |   -12.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     5237 | 2024-03-03 | BOSS              | W   | 0.617      | -            | -                | -                | 1 (0.617) |     0.28 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     5324 | 2024-03-02 | FURIA Esports     | L   | 0.611      | -            | -                | -                | -         |   -14.88 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     5366 | 2024-03-01 | BESTIA            | W   | 0.605      | -            | -                | -                | 1 (0.605) |     0.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     5546 | 2024-02-26 | Nouns Esports     | W   | 0.580      | -            | -                | -                | -         |     0.37 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     5549 | 2024-02-26 | BOSS              | W   | 0.579      | -            | -                | -                | -         |     0.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     5590 | 2024-02-25 | Wildcard Gaming   | W   | 0.573      | -            | -                | -                | -         |     0.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     5595 | 2024-02-25 | Nouns Esports     | L   | 0.572      | -            | -                | -                | -         |   -17.71 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     5785 | 2024-02-22 | Party Astronauts  | W   | 0.553      | -            | -                | -                | -         |     0.32 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     5786 | 2024-02-22 | MIGHT             | W   | 0.553      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     5790 | 2024-02-22 | ex-CatEvil        | W   | 0.552      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     5842 | 2024-02-21 | Lore Gaming       | W   | 0.546      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     7079 | 2024-01-28 | G2 Esports        | L   | 0.384      | -            | -                | -                | -         |    -3.85 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     7181 | 2024-01-27 | FaZe Clan         | L   | 0.377      | -            | -                | -                | -         |    -1.59 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     7318 | 2024-01-25 | GamerLegion       | W   | 0.362      | -            | -                | -                | 1 (0.362) |     0.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     7362 | 2024-01-24 | Team Spirit       | W   | 0.356      | 0.581        | 1.000 (0.207)    | -                | -         |     8.97 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     7544 | 2024-01-20 | M80               | L   | 0.333      | -            | -                | -                | -         |    -9.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     7624 | 2024-01-19 | Wildcard Gaming   | W   | 0.327      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     7635 | 2024-01-19 | BOSS              | W   | 0.325      | -            | -                | -                | -         |     0.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     7857 | 2024-01-16 | Elevate           | W   | 0.306      | -            | -                | -                | -         |     0.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     7858 | 2024-01-16 | huge sweaty       | W   | 0.306      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     7862 | 2024-01-16 | Wildcard Gaming   | W   | 0.306      | -            | -                | -                | -         |     0.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     7941 | 2024-01-15 | LOS               | W   | 0.300      | -            | -                | -                | -         |     0.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     7996 | 2024-01-14 | Party Astronauts  | W   | 0.293      | -            | -                | -                | -         |     0.17 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     8019 | 2024-01-13 | Elevate           | W   | 0.286      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     8066 | 2024-01-12 | M80               | L   | 0.281      | -            | -                | -                | -         |    -7.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     8073 | 2024-01-12 | Nouns Esports     | W   | 0.280      | -            | -                | -                | -         |     0.14 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     8289 | 2024-01-09 | NRG               | W   | 0.261      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     8291 | 2024-01-09 | vagrants          | W   | 0.261      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     8294 | 2024-01-09 | LOS               | W   | 0.260      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     8299 | 2024-01-09 | bubibabu          | W   | 0.260      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     8398 | 2024-01-08 | Maximum Ego       | W   | 0.254      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($148,306.48)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.49) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $100,000.00    | $100,000.00     |
| 2024-05-12 |      1.000 | $32,000.00     | $32,000.00      |
| 2024-04-14 |      0.895 | $10,000.00     | $8,951.62       |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-01-28 |      0.384 | $10,500.00     | $4,032.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
