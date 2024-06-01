### Roster Details<br />
Team Name: M80<br />
Roster: malbsMd, reck, s1n, slaxz-, Swisher<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [26](../standings_global.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
Final Rank Value:  1288.6<br />
<br />
Final Rank Value (1288.6) = Starting Rank Value (1285.1) + Head To Head Adjustments (3.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.535[<sup>1</sup>](#table2)
- Bounty Collected: 0.455[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.482[<sup>2</sup>](#table1)

The average of these factors is 0.435<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1285.1
- 400 + ( ( 0.435 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1285.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      118 | 2024-05-28 | HEROIC           | L   | 1.000      | -            | -                | -                | -         |    -4.81 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           60 |      155 | 2024-05-27 | FaZe Clan        | L   | 1.000      | -            | -                | -                | -         |    -0.79 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           59 |      319 | 2024-05-24 | Nouns Esports    | W   | 1.000      | 0.384        | 0.071 (0.027)    | 0.507 (0.195)    | 0 (0.000) |     6.19 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           58 |      378 | 2024-05-23 | Wildcard Gaming  | W   | 1.000      | 0.384        | -                | 0.506 (0.195)    | 0 (0.000) |     4.80 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           57 |      433 | 2024-05-22 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -26.47 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           56 |      435 | 2024-05-22 | Party Astronauts | W   | 1.000      | 0.477        | 0.031 (0.015)    | 0.545 (0.260)    | 0 (0.000) |     4.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           55 |      445 | 2024-05-22 | Mythic           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.77 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           54 |      628 | 2024-05-20 | NRG              | W   | 1.000      | 0.477        | -                | 0.555 (0.265)    | -         |     4.64 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           53 |      632 | 2024-05-20 | NRG              | W   | 1.000      | 0.477        | -                | 0.555 (0.265)    | -         |     4.86 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           52 |      645 | 2024-05-20 | E-Xolos LAZER    | W   | 1.000      | -            | -                | -                | -         |     0.22 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           51 |      723 | 2024-05-19 | BOSS             | W   | 1.000      | 0.477        | 0.016 (0.007)    | -                | -         |     2.07 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           50 |      724 | 2024-05-19 | BOSS             | W   | 1.000      | 0.477        | 0.016 (0.007)    | -                | -         |     2.12 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           49 |      817 | 2024-05-18 | Nouns Esports    | L   | 1.000      | -            | -                | -                | -         |   -27.83 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           48 |      943 | 2024-05-17 | regain           | W   | 1.000      | -            | -                | -                | -         |     0.67 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           47 |     1111 | 2024-05-15 | One More Esports | W   | 1.000      | -            | -                | -                | -         |     1.18 | malbsMd, reck, slaxz-, stamina, Swisher |
|           46 |     1117 | 2024-05-15 | One More Esports | W   | 1.000      | -            | -                | -                | -         |     1.20 | malbsMd, reck, slaxz-, stamina, Swisher |
|           45 |     1213 | 2024-05-14 | Elevate          | W   | 1.000      | 0.477        | -                | 0.475 (0.226)    | -         |     3.44 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           44 |     1219 | 2024-05-14 | Elevate          | W   | 1.000      | 0.477        | -                | 0.475 (0.226)    | -         |     3.56 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           43 |     1483 | 2024-05-10 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     0.86 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           42 |     1484 | 2024-05-10 | Limitless        | W   | 1.000      | -            | -                | -                | -         |     0.87 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           41 |     1539 | 2024-05-09 | LAG Gaming       | W   | 1.000      | -            | -                | -                | -         |     2.64 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           40 |     1542 | 2024-05-09 | LAG Gaming       | W   | 1.000      | -            | -                | -                | -         |     2.71 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           39 |     2098 | 2024-04-28 | G2 Esports       | L   | 0.990      | -            | -                | -                | -         |    -2.30 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           38 |     2184 | 2024-04-27 | TYLOO            | W   | 0.983      | 0.889        | 0.035 (0.031)    | 0.433 (0.378)    | 1 (0.983) |     3.65 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           37 |     2242 | 2024-04-26 | BetBoom Team     | L   | 0.978      | -            | -                | -                | -         |   -12.79 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           36 |     2277 | 2024-04-26 | G2 Esports       | W   | 0.975      | 0.889        | 0.468 (0.406)    | 0.392 (0.340)    | 1 (0.975) |    28.63 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           35 |     2316 | 2024-04-25 | Sharks Esports   | W   | 0.970      | 0.889        | 0.031 (0.027)    | 0.365 (0.315)    | 1 (0.970) |     3.37 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           34 |     2410 | 2024-04-23 | BetBoom Team     | L   | 0.957      | -            | -                | -                | -         |   -12.96 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           33 |     2662 | 2024-04-19 | Team Liquid      | W   | 0.933      | 0.143        | 0.513 (0.068)    | -                | -         |    25.65 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           32 |     2670 | 2024-04-19 | Legacy           | W   | 0.932      | -            | -                | -                | -         |     8.29 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           31 |     2739 | 2024-04-18 | Team Liquid      | L   | 0.926      | -            | -                | -                | -         |    -3.23 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           30 |     2743 | 2024-04-18 | Elevate          | W   | 0.925      | -            | -                | -                | -         |     3.53 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           29 |     3767 | 2024-03-27 | Take Flyte       | W   | 0.779      | -            | -                | -                | -         |     1.55 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           28 |     3773 | 2024-03-27 | Take Flyte       | W   | 0.779      | -            | -                | -                | -         |     1.57 | malbsMd, reck, s1n, slaxz-, Swisher     |
|           27 |     5037 | 2024-03-04 | Legacy           | L   | 0.624      | -            | -                | -                | -         |   -14.98 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           26 |     5090 | 2024-03-03 | Wildcard Gaming  | W   | 0.617      | -            | -                | -                | 1 (0.617) |     2.57 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           25 |     5177 | 2024-03-02 | Imperial Esports | L   | 0.611      | -            | -                | -                | -         |    -4.52 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           24 |     5222 | 2024-03-01 | ODDIK            | W   | 0.605      | -            | -                | -                | 1 (0.605) |     2.58 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           23 |     6589 | 2024-02-02 | Rebels Gaming    | L   | 0.418      | -            | -                | -                | -         |    -9.83 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           22 |     6671 | 2024-02-01 | Rooster          | W   | 0.410      | -            | -                | -                | 1 (0.410) |     0.84 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           21 |     6715 | 2024-01-31 | GamerLegion      | L   | 0.404      | -            | -                | -                | -         |    -7.35 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           20 |     7301 | 2024-01-20 | Team Liquid      | W   | 0.333      | 0.143        | 0.513 (0.024)    | -                | -         |     9.40 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           19 |     7308 | 2024-01-20 | Wildcard Gaming  | W   | 0.332      | -            | -                | -                | -         |     1.21 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           18 |     7379 | 2024-01-19 | BOSS             | W   | 0.327      | -            | -                | -                | -         |     0.92 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           17 |     7390 | 2024-01-19 | Wildcard Gaming  | L   | 0.325      | -            | -                | -                | -         |    -9.14 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           16 |     7741 | 2024-01-14 | Nouns Esports    | W   | 0.293      | -            | -                | -                | -         |     1.13 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           15 |     7762 | 2024-01-13 | Wildcard Gaming  | L   | 0.286      | -            | -                | -                | -         |    -8.19 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           14 |     7813 | 2024-01-12 | Team Liquid      | W   | 0.281      | 0.143        | 0.513 (0.021)    | -                | -         |     7.93 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           13 |     7823 | 2024-01-12 | Rocket           | W   | 0.280      | -            | -                | -                | -         |     0.15 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|           12 |     8616 | 2023-12-16 | BESTIA           | L   | 0.097      | -            | -                | -                | -         |    -2.96 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           11 |     8743 | 2023-12-15 | Virtus.pro       | L   | 0.091      | -            | -                | -                | -         |    -0.26 | dephh, malbsMd, reck, slaxz-, Swisher   |
|           10 |     8808 | 2023-12-13 | Nouns Esports    | W   | 0.079      | -            | -                | -                | -         |     0.06 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            9 |     8858 | 2023-12-12 | BOSS             | W   | 0.073      | -            | -                | -                | -         |     0.19 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            8 |     8898 | 2023-12-11 | Torqued          | W   | 0.066      | -            | -                | -                | -         |     0.02 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            7 |     8949 | 2023-12-10 | BOSS             | W   | 0.059      | -            | -                | -                | -         |     0.15 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            6 |     9137 | 2023-12-07 | BOSS             | W   | 0.039      | -            | -                | -                | -         |     0.10 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            5 |     9202 | 2023-12-06 | Party Astronauts | W   | 0.033      | -            | -                | -                | -         |     0.03 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            4 |     9347 | 2023-12-03 | Take Flyte       | W   | 0.013      | -            | -                | -                | -         |     0.02 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            3 |     9351 | 2023-12-03 | NRG              | W   | 0.012      | -            | -                | -                | -         |     0.03 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            2 |     9412 | 2023-12-02 | Wildcard Gaming  | W   | 0.006      | -            | -                | -                | -         |     0.02 | malbsMd, maNkz, reck, slaxz-, Swisher   |
|            1 |     9415 | 2023-12-02 | CCG Esports      | W   | 0.006      | -            | -                | -                | -         |     0.00 | malbsMd, maNkz, reck, slaxz-, Swisher   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($40,793.98)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-05-24 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-05-12 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-02-11 |      0.477 | $4,500.00      | $2,146.25       |
| 2023-12-17 |      0.105 | $2,000.00      | $210.23         |
| 2023-12-13 |      0.079 | $4,000.00      | $317.78         |
| 2023-12-10 |      0.059 | $35,000.00     | $2,080.56       |
| 2023-12-03 |      0.013 | $3,000.00      | $39.17          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
