### Roster Details<br />
Team Name: BOSS<br />
Roster: Cryptic, d4rty, FaNg, freshie, PwnAlone<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [90](../standings_global.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
Final Rank Value:  875.3<br />
<br />
Final Rank Value (875.3) = Starting Rank Value (899.0) + Head To Head Adjustments (-23.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.436[<sup>1</sup>](#table2)
- Bounty Collected: 0.341[<sup>2</sup>](#table1)
- Opponent Network: 0.108[<sup>2</sup>](#table1)
- LAN Wins: 0.121[<sup>2</sup>](#table1)

The average of these factors is 0.252<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 899.0
- 400 + ( ( 0.252 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 899.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |      101 | 2024-05-03 | Ninjas in Pyjamas          | L   | 1.000      | -            | -                | -                | -             |    -6.04 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           41 |      156 | 2024-05-02 | FlyQuest                   | L   | 1.000      | -            | -                | -                | -             |    -1.54 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           40 |      214 | 2024-05-01 | BIG                        | L   | 1.000      | -            | -                | -                | -             |    -1.84 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           39 |      497 | 2024-04-24 | Mythic                     | L   | 1.000      | -            | -                | -                | -             |   -24.50 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           38 |      498 | 2024-04-24 | Mythic                     | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.380 (0.181)    | false (0.000) |     6.49 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           37 |     1157 | 2024-04-11 | Limitless                  | W   | 1.000      | 0.477        | 0.001 (0.001)    | 0.177 (0.084)    | false (0.000) |     6.35 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           36 |     1160 | 2024-04-11 | Limitless                  | W   | 1.000      | 0.477        | -                | 0.177 (0.084)    | false (0.000) |     6.73 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           35 |     1192 | 2024-04-10 | NRG                        | L   | 1.000      | -            | -                | -                | -             |   -23.15 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           34 |     1196 | 2024-04-10 | NRG                        | W   | 1.000      | 0.477        | -                | 0.303 (0.145)    | false (0.000) |     7.86 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           33 |     1263 | 2024-04-09 | LAG Gaming (American team) | W   | 1.000      | 0.477        | 0.033 (0.016)    | 0.405 (0.193)    | false (0.000) |    14.00 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           32 |     1267 | 2024-04-09 | LAG Gaming (American team) | W   | 1.000      | 0.477        | 0.033 (0.016)    | 0.405 (0.193)    | false (0.000) |    15.28 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           31 |     1519 | 2024-04-03 | Party Astronauts           | L   | 0.986      | -            | -                | -                | -             |   -17.74 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           30 |     1564 | 2024-04-02 | Nouns Esports              | L   | 0.981      | -            | -                | -                | -             |   -20.71 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           29 |     1567 | 2024-04-02 | Take Flyte                 | W   | 0.980      | 0.143        | -                | 0.279 (0.039)    | false (0.000) |     7.58 | Cryptic, d4rty, FaNg, freshie, PwnAlone  |
|           28 |     2804 | 2024-03-03 | Team Liquid                | L   | 0.778      | -            | -                | -                | -             |    -1.63 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           27 |     2878 | 2024-03-02 | Complexity Gaming          | L   | 0.771      | -            | -                | -                | -             |    -0.84 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           26 |     2906 | 2024-03-01 | MIBR                       | W   | 0.766      | 0.143        | 0.654 (0.072)    | 0.616 (0.067)    | true (0.766)  |    23.71 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           25 |     3055 | 2024-02-26 | Team Liquid                | L   | 0.740      | -            | -                | -                | -             |    -1.37 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           24 |     3088 | 2024-02-25 | Nouns Esports              | L   | 0.734      | -            | -                | -                | -             |   -17.12 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           23 |     3090 | 2024-02-25 | Wildcard Gaming            | W   | 0.733      | 0.143        | 0.025 (0.003)    | 0.483 (0.051)    | -             |    12.62 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           22 |     4058 | 2024-02-01 | Nouns Esports              | L   | 0.574      | -            | -                | -                | -             |   -14.10 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           21 |     4059 | 2024-02-01 | Rocket                     | W   | 0.574      | -            | -                | -                | -             |     5.09 | brett, Cryptic, d4rty, freshie, PwnAlone |
|           20 |     4582 | 2024-01-19 | M80                        | L   | 0.488      | -            | -                | -                | -             |    -1.67 | brett, Cryptic, cynic, d4rty, freshie    |
|           19 |     4591 | 2024-01-19 | Team Liquid                | L   | 0.486      | -            | -                | -                | -             |    -0.97 | brett, Cryptic, cynic, d4rty, freshie    |
|           18 |     4862 | 2024-01-14 | Rocket                     | W   | 0.454      | -            | -                | -                | -             |     3.75 | brett, Cryptic, cynic, d4rty, freshie    |
|           17 |     4910 | 2024-01-12 | Wildcard Gaming            | L   | 0.442      | -            | -                | -                | -             |    -8.08 | brett, Cryptic, cynic, d4rty, freshie    |
|           16 |     4912 | 2024-01-12 | For Fun                    | W   | 0.441      | 0.143        | 0.014 (0.001)    | -                | -             |     4.57 | brett, Cryptic, cynic, d4rty, freshie    |
|           15 |     5659 | 2023-12-12 | M80                        | L   | 0.234      | -            | -                | -                | -             |    -0.72 | brett, Cryptic, d4rty, freshie, WolfY    |
|           14 |     5681 | 2023-12-11 | Party Astronauts           | W   | 0.228      | 0.303        | 0.036 (0.003)    | -                | -             |     2.70 | brett, Cryptic, d4rty, freshie, WolfY    |
|           13 |     5711 | 2023-12-10 | M80                        | L   | 0.221      | -            | -                | -                | -             |    -0.67 | brett, Cryptic, d4rty, freshie, WolfY    |
|           12 |     5756 | 2023-12-09 | Party Astronauts           | W   | 0.214      | 0.500        | 0.036 (0.004)    | 0.374 (0.040)    | -             |     2.58 | brett, Cryptic, d4rty, freshie, WolfY    |
|           11 |     5864 | 2023-12-07 | M80                        | L   | 0.201      | -            | -                | -                | -             |    -0.60 | brett, Cryptic, d4rty, freshie, WolfY    |
|           10 |     5916 | 2023-12-06 | Nouns Esports              | W   | 0.194      | 0.500        | 0.016 (0.002)    | -                | -             |     1.68 | brett, Cryptic, d4rty, freshie, WolfY    |
|            9 |     6079 | 2023-12-02 | Supernova (American team)  | W   | 0.167      | -            | -                | -                | true (0.167)  |     0.32 | brett, Cryptic, d4rty, dea, freshie      |
|            8 |     6178 | 2023-11-30 | Tsunami Esports            | W   | 0.154      | -            | -                | -                | true (0.154)  |     0.28 | brett, Cryptic, d4rty, dea, freshie      |
|            7 |     6536 | 2023-11-22 | Party Astronauts           | L   | 0.101      | -            | -                | -                | -             |    -2.00 | brett, Cryptic, d4rty, freshie, WolfY    |
|            6 |     6579 | 2023-11-21 | Evil Geniuses              | W   | 0.094      | -            | -                | -                | -             |     0.64 | brett, Cryptic, d4rty, freshie, WolfY    |
|            5 |     6613 | 2023-11-20 | Rocket                     | W   | 0.087      | -            | -                | -                | -             |     0.59 | brett, Cryptic, d4rty, freshie, WolfY    |
|            4 |     6658 | 2023-11-19 | M80                        | L   | 0.081      | -            | -                | -                | -             |    -0.24 | brett, Cryptic, d4rty, freshie, WolfY    |
|            3 |     6756 | 2023-11-17 | Take Flyte                 | W   | 0.067      | -            | -                | -                | -             |     0.58 | brett, Cryptic, d4rty, freshie, WolfY    |
|            2 |     6853 | 2023-11-15 | M80                        | L   | 0.054      | -            | -                | -                | -             |    -0.16 | brett, Cryptic, d4rty, freshie, SLIGHT   |
|            1 |     6860 | 2023-11-15 | NRG                        | L   | 0.053      | -            | -                | -                | -             |    -1.37 | autimatic, HexT, Jeorge, junior, Walco   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,083.19)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $3,500.00      | $3,500.00       |
| 2023-12-10 |      0.221 | $20,000.00     | $4,410.19       |
| 2023-12-03 |      0.173 | $1,000.00      | $173.01         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
