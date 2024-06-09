### Roster Details<br />
Team Name: NRG<br />
Roster: autimatic, Brehze, HexT, oSee, Walco<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [70](../standings_global.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
Final Rank Value:  950.9<br />
<br />
Final Rank Value (950.9) = Starting Rank Value (828.7) + Head To Head Adjustments (122.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.333[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.177[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 828.7
- 400 + ( ( 0.211 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 828.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           86 |        9 | 2024-05-29 | G3                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.63 | autimatic, Brehze, HexT, oSee, Walco |
|           85 |       26 | 2024-05-29 | Perseverance Gaming | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.40 | autimatic, Brehze, HexT, oSee, Walco |
|           84 |      379 | 2024-05-23 | Nouns Esports       | L   | 1.000      | -            | -                | -                | -         |   -11.78 | autimatic, Brehze, HexT, oSee, Walco |
|           83 |      432 | 2024-05-22 | Elevate             | L   | 1.000      | -            | -                | -                | -         |   -17.82 | autimatic, Brehze, HexT, oSee, Walco |
|           82 |      437 | 2024-05-22 | Elevate             | L   | 1.000      | -            | -                | -                | -         |   -19.42 | autimatic, Brehze, HexT, oSee, Walco |
|           81 |      482 | 2024-05-22 | Legacy              | W   | 1.000      | 0.384        | 0.027 (0.010)    | -                | 0 (0.000) |    19.61 | autimatic, Brehze, HexT, oSee, Walco |
|           80 |      539 | 2024-05-21 | Take Flyte          | L   | 1.000      | -            | -                | -                | -         |   -24.17 | autimatic, Brehze, HexT, oSee, Walco |
|           79 |      540 | 2024-05-21 | Take Flyte          | W   | 1.000      | 0.477        | -                | 0.354 (0.169)    | 0 (0.000) |     6.82 | autimatic, Brehze, HexT, oSee, Walco |
|           78 |      639 | 2024-05-20 | M80                 | L   | 1.000      | -            | -                | -                | -         |    -4.84 | autimatic, Brehze, HexT, oSee, Walco |
|           77 |      643 | 2024-05-20 | M80                 | L   | 1.000      | -            | -                | -                | -         |    -5.07 | autimatic, Brehze, HexT, oSee, Walco |
|           76 |      824 | 2024-05-18 | Nouns Esports       | L   | 1.000      | -            | -                | -                | -         |   -17.46 | autimatic, Brehze, HexT, oSee, Walco |
|           75 |      854 | 2024-05-18 | Party Astronauts    | W   | 1.000      | 0.303        | 0.031 (0.009)    | 0.545 (0.165)    | 0 (0.000) |    13.88 | autimatic, Brehze, HexT, oSee, Walco |
|           74 |      956 | 2024-05-17 | BOSS                | W   | 1.000      | 0.303        | 0.016 (0.005)    | -                | 0 (0.000) |     8.82 | autimatic, Brehze, HexT, oSee, Walco |
|           73 |     1124 | 2024-05-15 | LAG Gaming          | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | 0 (0.000) |     9.82 | autimatic, Brehze, HexT, oSee, Walco |
|           72 |     1130 | 2024-05-15 | LAG Gaming          | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | 0 (0.000) |    10.61 | autimatic, Brehze, HexT, oSee, Walco |
|           71 |     1225 | 2024-05-14 | One More Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.96 | autimatic, Brehze, HexT, oSee, Walco |
|           70 |     1231 | 2024-05-14 | One More Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.41 | autimatic, Brehze, HexT, oSee, Walco |
|           69 |     1350 | 2024-05-12 | Take Flyte          | W   | 1.000      | -            | -                | -                | -         |     9.73 | autimatic, Brehze, HexT, oSee, Walco |
|           68 |     1352 | 2024-05-12 | Elevate             | W   | 1.000      | -            | -                | -                | -         |    15.36 | autimatic, Brehze, HexT, oSee, Walco |
|           67 |     1419 | 2024-05-11 | Take Flyte          | W   | 1.000      | -            | -                | -                | -         |     9.81 | autimatic, Brehze, HexT, oSee, Walco |
|           66 |     1424 | 2024-05-11 | BOSS                | W   | 1.000      | -            | -                | -                | -         |    12.60 | autimatic, Brehze, HexT, oSee, Walco |
|           65 |     1721 | 2024-05-06 | Party Astronauts    | W   | 1.000      | 0.477        | 0.031 (0.015)    | 0.545 (0.260)    | -         |    19.03 | autimatic, Brehze, HexT, oSee, Walco |
|           64 |     1722 | 2024-05-06 | Party Astronauts    | L   | 1.000      | -            | -                | -                | -         |   -12.19 | autimatic, Brehze, HexT, oSee, Walco |
|           63 |     2329 | 2024-04-25 | Wildcard Gaming     | L   | 0.973      | -            | -                | -                | -         |   -14.89 | autimatic, Brehze, HexT, oSee, Walco |
|           62 |     2331 | 2024-04-25 | Wildcard Gaming     | W   | 0.973      | 0.477        | 0.012 (0.006)    | 0.525 (0.244)    | -         |    15.82 | autimatic, Brehze, HexT, oSee, Walco |
|           61 |     2862 | 2024-04-17 | G3                  | L   | 0.918      | -            | -                | -                | -         |   -17.57 | autimatic, Brehze, HexT, oSee, Walco |
|           60 |     2941 | 2024-04-16 | Zomblers            | W   | 0.913      | -            | -                | -                | -         |     5.36 | autimatic, Brehze, HexT, oSee, Walco |
|           59 |     2995 | 2024-04-15 | Mythic              | W   | 0.906      | 0.477        | -                | 0.339 (0.147)    | -         |     7.52 | autimatic, Brehze, HexT, oSee, Walco |
|           58 |     2996 | 2024-04-15 | Mythic              | W   | 0.906      | 0.477        | -                | 0.339 (0.147)    | -         |     8.01 | autimatic, Brehze, HexT, oSee, Walco |
|           57 |     3207 | 2024-04-10 | BOSS                | W   | 0.873      | 0.477        | 0.016 (0.007)    | 0.315 (0.131)    | -         |    13.71 | autimatic, Brehze, HexT, oSee, Walco |
|           56 |     3212 | 2024-04-10 | BOSS                | L   | 0.873      | -            | -                | -                | -         |   -13.92 | autimatic, Brehze, HexT, oSee, Walco |
|           55 |     3294 | 2024-04-09 | Carpe Diem          | W   | 0.866      | -            | -                | -                | -         |     5.05 | autimatic, Brehze, HexT, oSee, Walco |
|           54 |     3298 | 2024-04-09 | Carpe Diem          | W   | 0.866      | -            | -                | -                | -         |     5.29 | autimatic, Brehze, HexT, oSee, Walco |
|           53 |     3852 | 2024-03-27 | Nouns Esports       | W   | 0.780      | 0.477        | 0.071 (0.027)    | 0.507 (0.188)    | -         |    15.00 | autimatic, Brehze, HexT, oSee, Walco |
|           52 |     3856 | 2024-03-27 | Nouns Esports       | L   | 0.780      | -            | -                | -                | -         |    -9.56 | autimatic, Brehze, HexT, oSee, Walco |
|           51 |     3934 | 2024-03-26 | MIGHT               | W   | 0.773      | -            | -                | -                | -         |     6.58 | autimatic, Brehze, HexT, oSee, Walco |
|           50 |     3939 | 2024-03-26 | MIGHT               | W   | 0.773      | -            | -                | -                | -         |     6.95 | autimatic, Brehze, HexT, oSee, Walco |
|           49 |     4456 | 2024-03-15 | FLUFFY AIMERS       | W   | 0.700      | 0.477        | 0.030 (0.010)    | -                | -         |    12.40 | autimatic, Brehze, HexT, oSee, Walco |
|           48 |     4459 | 2024-03-15 | FLUFFY AIMERS       | L   | 0.700      | -            | -                | -                | -         |    -9.77 | autimatic, Brehze, HexT, oSee, Walco |
|           47 |     4509 | 2024-03-14 | Limitless           | W   | 0.693      | -            | -                | -                | -         |     5.83 | autimatic, Brehze, HexT, oSee, Walco |
|           46 |     4511 | 2024-03-14 | Limitless           | W   | 0.693      | -            | -                | -                | -         |     6.12 | autimatic, Brehze, HexT, oSee, Walco |
|           45 |     4644 | 2024-03-12 | Carpe Diem          | L   | 0.680      | -            | -                | -                | -         |   -16.09 | autimatic, Brehze, HexT, oSee, Walco |
|           44 |     4650 | 2024-03-12 | Synergy Esports     | W   | 0.679      | -            | -                | -                | -         |     1.45 | autimatic, Brehze, HexT, oSee, Walco |
|           43 |     5319 | 2024-03-02 | MIBR                | L   | 0.611      | -            | -                | -                | -         |    -0.39 | Brehze, daps, FaNg, HexT, oSee       |
|           42 |     5367 | 2024-03-01 | Imperial Esports    | L   | 0.605      | -            | -                | -                | -         |    -0.61 | Brehze, daps, FaNg, HexT, oSee       |
|           41 |     5631 | 2024-02-24 | Wildcard Gaming     | L   | 0.566      | -            | -                | -                | -         |    -7.39 | Brehze, daps, FaNg, HexT, oSee       |
|           40 |     5635 | 2024-02-24 | Limitless           | W   | 0.566      | -            | -                | -                | -         |     5.25 | Brehze, daps, FaNg, HexT, oSee       |
|           39 |     5642 | 2024-02-24 | Mythic              | W   | 0.566      | -            | -                | -                | -         |     6.59 | Brehze, daps, FaNg, HexT, oSee       |
|           38 |     5742 | 2024-02-23 | Danny Devito        | W   | 0.560      | -            | -                | -                | -         |     1.22 | Brehze, daps, FaNg, HexT, oSee       |
|           37 |     5787 | 2024-02-22 | Party Astronauts    | L   | 0.553      | -            | -                | -                | -         |    -7.03 | Brehze, daps, FaNg, HexT, oSee       |
|           36 |     5792 | 2024-02-22 | Wildcard Gaming     | W   | 0.552      | -            | -                | -                | -         |    10.12 | Brehze, daps, FaNg, HexT, oSee       |
|           35 |     5843 | 2024-02-21 | Artemis Esports     | W   | 0.546      | -            | -                | -                | -         |     1.22 | Brehze, daps, FaNg, HexT, oSee       |
|           34 |     5909 | 2024-02-20 | Party Astronauts    | L   | 0.540      | -            | -                | -                | -         |    -7.25 | Brehze, daps, FaNg, HexT, oSee       |
|           33 |     5975 | 2024-02-19 | Party Astronauts    | W   | 0.533      | -            | -                | -                | -         |     9.74 | Brehze, daps, FaNg, HexT, oSee       |
|           32 |     5985 | 2024-02-19 | Mythic              | W   | 0.532      | -            | -                | -                | -         |     6.85 | Brehze, daps, FaNg, HexT, oSee       |
|           31 |     6696 | 2024-02-03 | Elevate             | L   | 0.425      | -            | -                | -                | -         |    -6.30 | Brehze, daps, FaNg, HexT, oSee       |
|           30 |     6781 | 2024-02-02 | Party Astronauts    | W   | 0.420      | -            | -                | -                | -         |     7.88 | Brehze, daps, FaNg, HexT, oSee       |
|           29 |     6785 | 2024-02-02 | Wildcard Gaming     | L   | 0.419      | -            | -                | -                | -         |    -5.35 | Brehze, daps, FaNg, HexT, oSee       |
|           28 |     6787 | 2024-02-02 | Party Astronauts    | W   | 0.419      | -            | -                | -                | -         |     8.01 | Brehze, daps, FaNg, HexT, oSee       |
|           27 |     7330 | 2024-01-24 | Mythic              | W   | 0.359      | -            | -                | -                | -         |     4.16 | Brehze, daps, FaNg, HexT, oSee       |
|           26 |     7392 | 2024-01-23 | Limitless           | W   | 0.353      | -            | -                | -                | -         |     3.44 | Brehze, daps, FaNg, HexT, oSee       |
|           25 |     7397 | 2024-01-23 | ex-CatEvil          | W   | 0.353      | -            | -                | -                | -         |     2.35 | Brehze, daps, FaNg, HexT, oSee       |
|           24 |     7693 | 2024-01-18 | Wildcard Gaming     | L   | 0.319      | -            | -                | -                | -         |    -4.26 | Brehze, daps, FaNg, HexT, oSee       |
|           23 |     7698 | 2024-01-18 | Elevate             | W   | 0.319      | -            | -                | -                | -         |     5.44 | Brehze, daps, FaNg, HexT, oSee       |
|           22 |     7748 | 2024-01-17 | orbital vsat online | W   | 0.313      | -            | -                | -                | -         |     0.80 | Brehze, daps, FaNg, HexT, oSee       |
|           21 |     7859 | 2024-01-16 | Elevate             | L   | 0.306      | -            | -                | -                | -         |    -4.52 | Brehze, daps, FaNg, HexT, oSee       |
|           20 |     7865 | 2024-01-16 | regain              | W   | 0.306      | -            | -                | -                | -         |     2.28 | Brehze, daps, FaNg, HexT, oSee       |
|           19 |     7943 | 2024-01-15 | TSM Shimmer         | W   | 0.300      | -            | -                | -                | -         |     3.27 | Brehze, daps, FaNg, HexT, oSee       |
|           18 |     7992 | 2024-01-14 | Rocket              | L   | 0.293      | -            | -                | -                | -         |    -7.59 | Brehze, daps, FaNg, HexT, oSee       |
|           17 |     8004 | 2024-01-14 | LOS                 | W   | 0.292      | -            | -                | -                | -         |     1.36 | Brehze, daps, FaNg, HexT, oSee       |
|           16 |     8020 | 2024-01-13 | Nouns Esports       | L   | 0.286      | -            | -                | -                | -         |    -3.44 | Brehze, daps, FaNg, HexT, oSee       |
|           15 |     8065 | 2024-01-12 | Complexity Gaming   | L   | 0.281      | -            | -                | -                | -         |    -0.15 | Brehze, daps, FaNg, HexT, oSee       |
|           14 |     8074 | 2024-01-12 | Elevate             | W   | 0.280      | -            | -                | -                | -         |     4.46 | Brehze, daps, FaNg, HexT, oSee       |
|           13 |     8289 | 2024-01-09 | Team Liquid         | L   | 0.261      | -            | -                | -                | -         |    -0.08 | Brehze, daps, FaNg, HexT, oSee       |
|           12 |     8290 | 2024-01-09 | Akimbo Esports      | W   | 0.261      | -            | -                | -                | -         |     3.41 | Brehze, daps, FaNg, HexT, oSee       |
|           11 |     8293 | 2024-01-09 | Team Lampa          | W   | 0.260      | -            | -                | -                | -         |     1.04 | Brehze, daps, FaNg, HexT, oSee       |
|           10 |     8298 | 2024-01-09 | MOLEGAN             | W   | 0.260      | -            | -                | -                | -         |     1.09 | Brehze, daps, FaNg, HexT, oSee       |
|            9 |     8404 | 2024-01-08 | gamin4fun           | W   | 0.254      | -            | -                | -                | -         |     0.66 | Brehze, daps, FaNg, HexT, oSee       |
|            8 |     8802 | 2023-12-16 | LAG Gaming          | W   | 0.099      | -            | -                | -                | -         |     2.09 | Brehze, daps, FaNg, HexT, oSee       |
|            7 |     8972 | 2023-12-15 | Revenge Nation      | W   | 0.093      | -            | -                | -                | -         |     1.05 | Brehze, daps, FaNg, HexT, oSee       |
|            6 |     9125 | 2023-12-12 | Nouns Esports       | L   | 0.072      | -            | -                | -                | -         |    -1.72 | Brehze, daps, FaNg, HexT, oSee       |
|            5 |     9165 | 2023-12-11 | Wildcard Gaming     | W   | 0.066      | -            | -                | -                | -         |     1.17 | Brehze, daps, FaNg, HexT, oSee       |
|            4 |     9216 | 2023-12-10 | huge sweaty         | W   | 0.059      | -            | -                | -                | -         |     0.21 | Brehze, daps, FaNg, HexT, oSee       |
|            3 |     9633 | 2023-12-03 | M80                 | L   | 0.012      | -            | -                | -                | -         |    -0.03 | Brehze, daps, FaNg, HexT, oSee       |
|            2 |     9696 | 2023-12-02 | Party Astronauts    | W   | 0.006      | -            | -                | -                | -         |     0.05 | Brehze, daps, FaNg, HexT, oSee       |
|            1 |     9702 | 2023-12-02 | Wanted Goons        | W   | 0.006      | -            | -                | -                | -         |     0.02 | Brehze, daps, FaNg, HexT, oSee       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,000.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-05-12 |      1.000 | $2,000.00      | $2,000.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
