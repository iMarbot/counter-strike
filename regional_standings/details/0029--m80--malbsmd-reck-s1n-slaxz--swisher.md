### Roster Details<br />
Team Name: M80<br />
Roster: malbsMd, reck, s1n, slaxz-, Swisher<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [29](../standings_global.md)<br />
Regional Rank: [6]( ../standings_americas.md)<br />
Final Rank Value:  1303.6<br />
<br />
Final Rank Value (1303.6) = Starting Rank Value (1299.9) + Head To Head Adjustments (3.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.553[<sup>1</sup>](#table2)
- Bounty Collected: 0.502[<sup>2</sup>](#table1)
- Opponent Network: 0.190[<sup>2</sup>](#table1)
- LAN Wins: 0.570[<sup>2</sup>](#table1)

The average of these factors is 0.454<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1299.9
- 400 + ( ( 0.454 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1299.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |      302 | 2024-04-28 | G2 Esports       | L   | 1.000      | -            | -                | -                | -             |    -1.93 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           47 |      366 | 2024-04-27 | TYLOO            | W   | 1.000      | 0.889        | 0.131 (0.117)    | 0.592 (0.526)    | true (1.000)  |     5.67 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           46 |      408 | 2024-04-26 | BetBoom Team     | L   | 1.000      | -            | -                | -                | -             |   -11.12 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           45 |      442 | 2024-04-26 | G2 Esports       | W   | 1.000      | 0.889        | 0.866 (0.769)    | 0.477 (0.424)    | true (1.000)  |    29.78 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           44 |      478 | 2024-04-25 | Sharks Esports   | W   | 1.000      | 0.889        | 0.063 (0.056)    | 0.343 (0.305)    | true (1.000)  |     3.83 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           43 |      566 | 2024-04-23 | BetBoom Team     | L   | 1.000      | -            | -                | -                | -             |   -11.09 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           42 |      788 | 2024-04-19 | Team Liquid      | W   | 1.000      | 0.143        | 0.125 (0.018)    | 0.546 (0.078)    | false (0.000) |    21.74 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           41 |      795 | 2024-04-19 | Legacy           | W   | 1.000      | 0.143        | 0.061 (0.009)    | -                | false (0.000) |    11.85 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           40 |      859 | 2024-04-18 | Team Liquid      | L   | 1.000      | -            | -                | -                | -             |    -8.87 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           39 |      862 | 2024-04-18 | Elevate          | W   | 1.000      | -            | -                | -                | false (0.000) |     2.51 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           38 |     1717 | 2024-03-27 | Take Flyte       | W   | 0.941      | 0.477        | -                | 0.279 (0.125)    | false (0.000) |     1.33 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           37 |     1721 | 2024-03-27 | Take Flyte       | W   | 0.940      | 0.477        | -                | 0.279 (0.125)    | -             |     1.35 | malbsMd, reck, s1n, slaxz-, Swisher   |
|           36 |     2757 | 2024-03-04 | Legacy           | L   | 0.785      | -            | -                | -                | -             |   -16.97 | dephh, malbsMd, reck, slaxz-, Swisher |
|           35 |     2803 | 2024-03-03 | Wildcard Gaming  | W   | 0.778      | 0.143        | -                | 0.483 (0.054)    | true (0.778)  |     2.93 | dephh, malbsMd, reck, slaxz-, Swisher |
|           34 |     2872 | 2024-03-02 | Imperial Esports | L   | 0.772      | -            | -                | -                | -             |    -5.39 | dephh, malbsMd, reck, slaxz-, Swisher |
|           33 |     2907 | 2024-03-01 | ODDIK            | W   | 0.766      | 0.143        | -                | 0.402 (0.044)    | true (0.766)  |     2.71 | dephh, malbsMd, reck, slaxz-, Swisher |
|           32 |     4013 | 2024-02-02 | Rebels Gaming    | L   | 0.579      | -            | -                | -                | -             |   -12.90 | dephh, malbsMd, reck, slaxz-, Swisher |
|           31 |     4074 | 2024-02-01 | Rooster          | W   | 0.571      | 1.000        | 0.031 (0.018)    | 0.312 (0.178)    | true (0.571)  |     1.37 | dephh, malbsMd, reck, slaxz-, Swisher |
|           30 |     4108 | 2024-01-31 | GamerLegion      | L   | 0.565      | -            | -                | -                | -             |    -2.94 | dephh, malbsMd, reck, slaxz-, Swisher |
|           29 |     4524 | 2024-01-20 | Team Liquid      | W   | 0.494      | 0.143        | 0.125 (0.009)    | 0.546 (0.039)    | -             |     9.92 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           28 |     4529 | 2024-01-20 | Wildcard Gaming  | W   | 0.493      | -            | -                | -                | -             |     1.61 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           27 |     4582 | 2024-01-19 | BOSS             | W   | 0.488      | -            | -                | -                | -             |     1.67 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           26 |     4590 | 2024-01-19 | Wildcard Gaming  | L   | 0.486      | -            | -                | -                | -             |   -13.87 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           25 |     4861 | 2024-01-14 | Nouns Esports    | W   | 0.454      | -            | -                | -                | -             |     0.36 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           24 |     4873 | 2024-01-13 | Wildcard Gaming  | L   | 0.447      | -            | -                | -                | -             |   -13.01 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           23 |     4909 | 2024-01-12 | Team Liquid      | W   | 0.442      | 0.143        | 0.125 (0.008)    | -                | -             |     8.70 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           22 |     4916 | 2024-01-12 | Rocket           | W   | 0.441      | -            | -                | -                | -             |     0.48 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           21 |     5478 | 2023-12-16 | BESTIA           | L   | 0.258      | -            | -                | -                | -             |    -7.84 | dephh, malbsMd, reck, slaxz-, Swisher |
|           20 |     5584 | 2023-12-15 | Virtus.pro       | L   | 0.252      | -            | -                | -                | -             |    -0.76 | dephh, malbsMd, reck, slaxz-, Swisher |
|           19 |     5627 | 2023-12-13 | Nouns Esports    | W   | 0.241      | -            | -                | -                | -             |     0.29 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           18 |     5659 | 2023-12-12 | BOSS             | W   | 0.234      | -            | -                | -                | -             |     0.72 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           17 |     5683 | 2023-12-11 | Torqued          | W   | 0.227      | -            | -                | -                | -             |     0.05 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           16 |     5711 | 2023-12-10 | BOSS             | W   | 0.221      | 0.500        | 0.051 (0.006)    | -                | -             |     0.67 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           15 |     5864 | 2023-12-07 | BOSS             | W   | 0.201      | 0.500        | 0.051 (0.005)    | -                | -             |     0.60 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           14 |     5915 | 2023-12-06 | Party Astronauts | W   | 0.194      | -            | -                | -                | -             |     0.37 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           13 |     6026 | 2023-12-03 | Take Flyte       | W   | 0.174      | -            | -                | -                | -             |     0.20 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           12 |     6074 | 2023-12-02 | Wildcard Gaming  | W   | 0.167      | -            | -                | -                | -             |     0.40 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           11 |     6076 | 2023-12-02 | CCG Esports      | W   | 0.167      | -            | -                | -                | -             |     0.03 | malbsMd, maNkz, reck, slaxz-, Swisher |
|           10 |     6538 | 2023-11-22 | Rocket           | W   | 0.101      | -            | -                | -                | -             |     0.09 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            9 |     6658 | 2023-11-19 | BOSS             | W   | 0.081      | -            | -                | -                | -             |     0.24 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            8 |     6757 | 2023-11-17 | Evil Geniuses    | W   | 0.067      | -            | -                | -                | -             |     0.06 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            7 |     6796 | 2023-11-16 | NRG              | W   | 0.061      | -            | -                | -                | -             |     0.04 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            6 |     6800 | 2023-11-16 | Party Astronauts | W   | 0.059      | -            | -                | -                | -             |     0.11 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            5 |     6853 | 2023-11-15 | BOSS             | W   | 0.054      | -            | -                | -                | -             |     0.16 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            4 |     6859 | 2023-11-15 | Party Astronauts | L   | 0.053      | -            | -                | -                | -             |    -1.56 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            3 |     6905 | 2023-11-14 | MIGHT            | W   | 0.047      | -            | -                | -                | -             |     0.06 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            2 |     6907 | 2023-11-14 | 5Fellas          | W   | 0.047      | -            | -                | -                | -             |     0.04 | malbsMd, maNkz, reck, slaxz-, Swisher |
|            1 |     6946 | 2023-11-13 | Xiaoma Gaming    | W   | 0.041      | -            | -                | -                | -             |     0.03 | malbsMd, maNkz, reck, slaxz-, Swisher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,605.62)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.16) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-02-11 |      0.638 | $4,500.00      | $2,871.04       |
| 2023-12-17 |      0.266 | $2,000.00      | $532.36         |
| 2023-12-13 |      0.241 | $4,000.00      | $962.04         |
| 2023-12-10 |      0.221 | $35,000.00     | $7,717.82       |
| 2023-12-03 |      0.174 | $3,000.00      | $522.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
