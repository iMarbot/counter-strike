### Roster Details<br />
Team Name: Team Liquid<br />
Roster: cadiaN, NAF, skullz, Twistzz, YEKINDAR<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [10](../standings_global.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
Final Rank Value:  1616.7<br />
<br />
Final Rank Value (1616.7) = Starting Rank Value (1671.1) + Head To Head Adjustments (-54.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.775[<sup>1</sup>](#table2)
- Bounty Collected: 0.586[<sup>2</sup>](#table1)
- Opponent Network: 0.259[<sup>2</sup>](#table1)
- LAN Wins: 0.877[<sup>2</sup>](#table1)

The average of these factors is 0.624<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1671.1
- 400 + ( ( 0.624 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1671.1


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
|           57 |       33 | 2024-05-29 | G2 Esports        | L   | 1.000      | -            | -                | -                | -         |    -9.44 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           56 |      103 | 2024-05-28 | Team Falcons      | W   | 1.000      | 0.624        | 0.355 (0.221)    | -                | 1 (1.000) |     8.28 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           55 |      143 | 2024-05-27 | 9z Team           | L   | 1.000      | -            | -                | -                | -         |   -28.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           54 |      162 | 2024-05-27 | Complexity Gaming | W   | 1.000      | 0.624        | 0.260 (0.162)    | 0.219 (0.136)    | 1 (1.000) |    14.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           53 |      411 | 2024-05-23 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -9.85 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           52 |      516 | 2024-05-22 | Astralis          | W   | 1.000      | 0.769        | 0.395 (0.304)    | 0.286 (0.220)    | -         |    18.98 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           51 |      621 | 2024-05-21 | ENCE              | W   | 1.000      | 0.769        | 0.202 (0.155)    | 0.280 (0.215)    | -         |     4.64 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           50 |      780 | 2024-05-19 | AMKAL ESPORTS     | W   | 1.000      | 0.769        | -                | 0.565 (0.435)    | -         |     3.84 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           49 |      832 | 2024-05-18 | OG                | W   | 1.000      | 0.769        | 0.277 (0.213)    | 0.257 (0.197)    | -         |     3.34 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           48 |     1517 | 2024-05-10 | Astralis          | L   | 1.000      | -            | -                | -                | -         |   -11.80 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           47 |     1639 | 2024-05-08 | FlyQuest          | W   | 1.000      | 0.889        | -                | 0.419 (0.372)    | 1 (1.000) |     8.60 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           46 |     1805 | 2024-05-04 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -3.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           45 |     1975 | 2024-05-01 | Monte             | W   | 1.000      | 0.889        | 0.181 (0.161)    | 0.363 (0.322)    | 1 (1.000) |     3.29 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           44 |     2021 | 2024-04-30 | FURIA Esports     | W   | 1.000      | 0.889        | 0.138 (0.122)    | 0.267 (0.237)    | 1 (1.000) |     6.70 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           43 |     2662 | 2024-04-19 | M80               | L   | 0.933      | -            | -                | -                | -         |   -25.65 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           42 |     2739 | 2024-04-18 | M80               | W   | 0.926      | -            | -                | -                | -         |     3.23 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           41 |     2744 | 2024-04-18 | Legacy            | W   | 0.925      | -            | -                | -                | -         |     1.38 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           40 |     2802 | 2024-04-17 | G3                | W   | 0.919      | -            | -                | -                | -         |     0.29 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           39 |     2805 | 2024-04-17 | straykids         | W   | 0.918      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           38 |     2886 | 2024-04-16 | LAG Gaming        | W   | 0.912      | -            | -                | -                | -         |     0.49 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           37 |     3090 | 2024-04-12 | FaZe Clan         | L   | 0.882      | -            | -                | -                | -         |    -4.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           36 |     3208 | 2024-04-10 | MOUZ              | L   | 0.868      | -            | -                | -                | -         |    -3.69 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           35 |     3311 | 2024-04-08 | G2 Esports        | W   | 0.855      | 0.624        | 0.468 (0.250)    | 0.392 (0.209)    | 1 (0.855) |    19.55 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           34 |     3322 | 2024-04-07 | HEROIC            | W   | 0.853      | 0.624        | 0.322 (0.171)    | 0.463 (0.247)    | 1 (0.853) |    16.72 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           33 |     4820 | 2024-03-07 | SAW               | L   | 0.643      | -            | -                | -                | -         |   -16.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           32 |     4996 | 2024-03-04 | Complexity Gaming | L   | 0.625      | -            | -                | -                | -         |   -12.26 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           31 |     5091 | 2024-03-03 | BOSS              | W   | 0.617      | -            | -                | -                | 1 (0.617) |     0.28 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           30 |     5176 | 2024-03-02 | FURIA Esports     | L   | 0.611      | -            | -                | -                | -         |   -14.94 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           29 |     5217 | 2024-03-01 | BESTIA            | W   | 0.605      | -            | -                | -                | 1 (0.605) |     0.43 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           28 |     5389 | 2024-02-26 | Nouns Esports     | W   | 0.580      | -            | -                | -                | -         |     0.36 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           27 |     5392 | 2024-02-26 | BOSS              | W   | 0.579      | -            | -                | -                | -         |     0.22 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           26 |     5432 | 2024-02-25 | Wildcard Gaming   | W   | 0.573      | -            | -                | -                | -         |     0.33 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           25 |     5437 | 2024-02-25 | Nouns Esports     | L   | 0.572      | -            | -                | -                | -         |   -17.72 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           24 |     5625 | 2024-02-22 | Party Astronauts  | W   | 0.553      | -            | -                | -                | -         |     0.31 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           23 |     5626 | 2024-02-22 | MIGHT             | W   | 0.553      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           22 |     5630 | 2024-02-22 | ex-CatEvil        | W   | 0.552      | -            | -                | -                | -         |     0.05 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           21 |     5681 | 2024-02-21 | Lore Gaming       | W   | 0.546      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           20 |     6861 | 2024-01-28 | G2 Esports        | L   | 0.384      | -            | -                | -                | -         |    -3.89 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           19 |     6961 | 2024-01-27 | FaZe Clan         | L   | 0.377      | -            | -                | -                | -         |    -1.62 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           18 |     7089 | 2024-01-25 | GamerLegion       | W   | 0.362      | -            | -                | -                | 1 (0.362) |     0.91 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           17 |     7127 | 2024-01-24 | Team Spirit       | W   | 0.356      | 0.581        | 1.000 (0.207)    | -                | -         |     8.96 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           16 |     7301 | 2024-01-20 | M80               | L   | 0.333      | -            | -                | -                | -         |    -9.40 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           15 |     7380 | 2024-01-19 | Wildcard Gaming   | W   | 0.327      | -            | -                | -                | -         |     0.15 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           14 |     7391 | 2024-01-19 | BOSS              | W   | 0.325      | -            | -                | -                | -         |     0.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           13 |     7608 | 2024-01-16 | Elevate           | W   | 0.306      | -            | -                | -                | -         |     0.11 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           12 |     7609 | 2024-01-16 | huge sweaty       | W   | 0.306      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           11 |     7613 | 2024-01-16 | Wildcard Gaming   | W   | 0.306      | -            | -                | -                | -         |     0.12 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|           10 |     7692 | 2024-01-15 | LOS               | W   | 0.300      | -            | -                | -                | -         |     0.02 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            9 |     7743 | 2024-01-14 | Party Astronauts  | W   | 0.293      | -            | -                | -                | -         |     0.16 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            8 |     7766 | 2024-01-13 | Elevate           | W   | 0.286      | -            | -                | -                | -         |     0.09 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            7 |     7813 | 2024-01-12 | M80               | L   | 0.281      | -            | -                | -                | -         |    -7.93 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            6 |     7820 | 2024-01-12 | Nouns Esports     | W   | 0.280      | -            | -                | -                | -         |     0.13 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            5 |     8035 | 2024-01-09 | NRG               | W   | 0.261      | -            | -                | -                | -         |     0.08 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            4 |     8037 | 2024-01-09 | vagrants          | W   | 0.261      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            3 |     8040 | 2024-01-09 | LOS               | W   | 0.260      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            2 |     8045 | 2024-01-09 | bubibabu          | W   | 0.260      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |
|            1 |     8144 | 2024-01-08 | Maximum Ego       | W   | 0.254      | -            | -                | -                | -         |     0.01 | cadiaN, NAF, skullz, Twistzz, YEKINDAR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($154,306.48)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.51) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-05-23 |      1.000 | $100,000.00    | $100,000.00     |
| 2024-05-12 |      1.000 | $32,000.00     | $32,000.00      |
| 2024-04-14 |      0.895 | $10,000.00     | $8,951.62       |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-01-28 |      0.384 | $10,500.00     | $4,032.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
