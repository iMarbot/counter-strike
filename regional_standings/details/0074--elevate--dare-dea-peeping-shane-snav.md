### Roster Details<br />
Team Name: Elevate<br />
Roster: dare, dea, Peeping, shane, snav<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [74](../standings_global.md)<br />
Regional Rank: [18]( ../standings_americas.md)<br />
Final Rank Value:  931.3<br />
<br />
Final Rank Value (931.3) = Starting Rank Value (846.7) + Head To Head Adjustments (84.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.333[<sup>2</sup>](#table1)
- Opponent Network: 0.201[<sup>2</sup>](#table1)
- LAN Wins: 0.003[<sup>2</sup>](#table1)

The average of these factors is 0.220<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 846.7
- 400 + ( ( 0.220 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 846.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           76 |       11 | 2024-05-29 | Revenge Nation     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.39 | dare, dea, Peeping, shane, snav                  |
|           75 |       25 | 2024-05-29 | HeadShotKings      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.60 | dare, dea, Peeping, shane, snav                  |
|           74 |      432 | 2024-05-22 | NRG                | W   | 1.000      | 0.477        | 0.010 (0.005)    | 0.555 (0.265)    | 0 (0.000) |    17.82 | dare, dea, Peeping, shane, snav                  |
|           73 |      437 | 2024-05-22 | NRG                | W   | 1.000      | 0.477        | -                | 0.555 (0.265)    | 0 (0.000) |    19.42 | dare, dea, Peeping, shane, snav                  |
|           72 |      538 | 2024-05-21 | One More Esports   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.99 | dare, dea, Peeping, shane, snav                  |
|           71 |      541 | 2024-05-21 | One More Esports   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.56 | dare, dea, Peeping, shane, snav                  |
|           70 |      558 | 2024-05-21 | FlyQuest RED       | L   | 1.000      | -            | -                | -                | -         |   -17.78 | dare, dea, Peeping, shane, snav                  |
|           69 |      564 | 2024-05-21 | FLUFFY AIMERS      | L   | 1.000      | -            | -                | -                | -         |   -18.91 | dare, dea, Peeping, shane, snav                  |
|           68 |      579 | 2024-05-21 | Rent Money         | L   | 1.000      | -            | -                | -                | -         |   -23.06 | dare, dea, Peeping, shane, snav                  |
|           67 |      649 | 2024-05-20 | Mythic             | L   | 1.000      | -            | -                | -                | -         |   -21.86 | dare, dea, Peeping, shane, snav                  |
|           66 |      951 | 2024-05-17 | FLUFFY AIMERS      | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | 0 (0.000) |    10.11 | dare, dea, Peeping, shane, snav                  |
|           65 |      953 | 2024-05-17 | FLUFFY AIMERS      | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | -         |    10.94 | dare, dea, Peeping, shane, snav                  |
|           64 |     1034 | 2024-05-16 | G3                 | L   | 1.000      | -            | -                | -                | -         |   -19.42 | dare, dea, Peeping, shane, snav                  |
|           63 |     1041 | 2024-05-16 | straykids          | W   | 1.000      | -            | -                | -                | -         |     2.33 | dare, dea, Peeping, shane, snav                  |
|           62 |     1126 | 2024-05-15 | Limitless          | W   | 1.000      | -            | -                | -                | -         |     5.38 | dare, dea, Peeping, shane, snav                  |
|           61 |     1132 | 2024-05-15 | Limitless          | W   | 1.000      | -            | -                | -                | -         |     5.66 | dare, dea, Peeping, shane, snav                  |
|           60 |     1223 | 2024-05-14 | M80                | L   | 1.000      | -            | -                | -                | -         |    -3.57 | dare, dea, Peeping, shane, snav                  |
|           59 |     1229 | 2024-05-14 | M80                | L   | 1.000      | -            | -                | -                | -         |    -3.70 | dare, dea, Peeping, shane, snav                  |
|           58 |     1237 | 2024-05-14 | Take Flyte         | W   | 1.000      | 0.477        | -                | 0.354 (0.169)    | -         |     9.51 | dare, dea, Peeping, shane, snav                  |
|           57 |     1239 | 2024-05-14 | Take Flyte         | W   | 1.000      | 0.477        | -                | 0.354 (0.169)    | -         |    10.26 | dare, dea, Peeping, shane, snav                  |
|           56 |     1352 | 2024-05-12 | NRG                | L   | 1.000      | -            | -                | -                | -         |   -15.36 | dare, dea, Peeping, shane, snav                  |
|           55 |     1411 | 2024-05-11 | Nouns Esports      | W   | 1.000      | 0.270        | 0.071 (0.019)    | 0.507 (0.137)    | -         |    17.92 | dare, dea, Peeping, shane, snav                  |
|           54 |     1413 | 2024-05-11 | Wildcard Gaming    | W   | 1.000      | 0.270        | -                | 0.525 (0.142)    | -         |    16.19 | dare, dea, Peeping, shane, snav                  |
|           53 |     1415 | 2024-05-11 | Nouns Esports      | L   | 1.000      | -            | -                | -                | -         |   -11.59 | dare, dea, Peeping, shane, snav                  |
|           52 |     1603 | 2024-05-08 | MIGHT              | W   | 1.000      | -            | -                | -                | -         |     6.08 | dare, dea, Peeping, shane, snav                  |
|           51 |     1607 | 2024-05-08 | MIGHT              | W   | 1.000      | -            | -                | -                | -         |     6.43 | dare, dea, Peeping, shane, snav                  |
|           50 |     1676 | 2024-05-07 | Party Astronauts   | W   | 1.000      | 0.477        | 0.031 (0.015)    | 0.545 (0.260)    | -         |    19.00 | dare, dea, Peeping, shane, snav                  |
|           49 |     1677 | 2024-05-07 | Party Astronauts   | L   | 1.000      | -            | -                | -                | -         |   -12.22 | dare, dea, Peeping, shane, snav                  |
|           48 |     2440 | 2024-04-23 | Wildcard Gaming    | L   | 0.960      | -            | -                | -                | -         |   -14.38 | dare, dea, Peeping, shane, snav                  |
|           47 |     2447 | 2024-04-23 | Wildcard Gaming    | W   | 0.959      | 0.477        | 0.012 (0.005)    | 0.525 (0.240)    | -         |    15.96 | dare, dea, Peeping, shane, snav                  |
|           46 |     2794 | 2024-04-18 | Legacy             | L   | 0.926      | -            | -                | -                | -         |    -7.25 | dare, dea, Peeping, shane, snav                  |
|           45 |     2799 | 2024-04-18 | M80                | L   | 0.925      | -            | -                | -                | -         |    -3.63 | dare, dea, Peeping, shane, snav                  |
|           44 |     2857 | 2024-04-17 | Nouns Esports      | W   | 0.919      | 0.143        | 0.071 (0.009)    | -                | -         |    18.31 | dare, dea, Peeping, shane, snav                  |
|           43 |     2863 | 2024-04-17 | Wildcard Gaming    | W   | 0.918      | -            | -                | -                | -         |    16.92 | dare, dea, Peeping, shane, snav                  |
|           42 |     2942 | 2024-04-16 | E-Xolos LAZER      | W   | 0.912      | -            | -                | -                | -         |     2.02 | dare, dea, Peeping, shane, snav                  |
|           41 |     3208 | 2024-04-10 | Nouns Esports      | L   | 0.873      | -            | -                | -                | -         |    -9.83 | dare, dea, Peeping, shane, snav                  |
|           40 |     3213 | 2024-04-10 | Nouns Esports      | L   | 0.873      | -            | -                | -                | -         |   -10.57 | dare, dea, Peeping, shane, snav                  |
|           39 |     3610 | 2024-04-03 | LAG Gaming         | W   | 0.826      | 0.477        | 0.013 (0.005)    | -                | -         |    14.70 | dare, dea, Peeping, shane, snav                  |
|           38 |     3612 | 2024-04-03 | LAG Gaming         | L   | 0.826      | -            | -                | -                | -         |   -11.37 | dare, dea, Peeping, shane, snav                  |
|           37 |     3932 | 2024-03-26 | BOSS               | W   | 0.773      | 0.477        | 0.016 (0.006)    | -                | -         |    10.85 | dare, dea, Peeping, shane, snav                  |
|           36 |     3937 | 2024-03-26 | BOSS               | W   | 0.773      | 0.477        | 0.016 (0.006)    | -                | -         |    11.62 | dare, dea, Peeping, shane, snav                  |
|           35 |     4455 | 2024-03-15 | Carpe Diem         | W   | 0.700      | -            | -                | -                | -         |     5.59 | dare, dea, Peeping, shane, snav                  |
|           34 |     4460 | 2024-03-15 | Carpe Diem         | W   | 0.700      | -            | -                | -                | -         |     5.87 | dare, dea, Peeping, shane, snav                  |
|           33 |     4645 | 2024-03-12 | Party Astronauts   | L   | 0.679      | -            | -                | -                | -         |    -7.96 | dare, dea, Peeping, shane, snav                  |
|           32 |     4648 | 2024-03-12 | Victorum           | W   | 0.679      | -            | -                | -                | -         |     1.53 | dare, dea, Peeping, shane, snav                  |
|           31 |     4883 | 2024-03-08 | Team Spirit        | L   | 0.650      | -            | -                | -                | -         |    -0.05 | dare, MRC9, Peeping, shane, snav                 |
|           30 |     5286 | 2024-03-02 | ODDIK              | L   | 0.611      | -            | -                | -                | -         |    -7.59 | dare, nbgee12, Peeping, shane, snav              |
|           29 |     5373 | 2024-03-01 | Complexity Gaming  | L   | 0.604      | -            | -                | -                | -         |    -0.42 | dare, nbgee12, Peeping, shane, snav              |
|           28 |     5738 | 2024-02-23 | LAG Gaming         | L   | 0.560      | -            | -                | -                | -         |    -7.61 | dare, dea, Peeping, shane, snav                  |
|           27 |     6187 | 2024-02-15 | G3                 | L   | 0.506      | -            | -                | -                | -         |    -9.36 | dare, dea, Peeping, shane, snav                  |
|           26 |     6316 | 2024-02-13 | Mythic             | L   | 0.493      | -            | -                | -                | -         |   -10.85 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           25 |     6318 | 2024-02-13 | Mythic             | W   | 0.493      | -            | -                | -                | -         |     4.72 | dare, dea, Peeping, shane, snav                  |
|           24 |     6648 | 2024-02-04 | Wildcard Gaming    | W   | 0.432      | -            | -                | -                | -         |     7.72 | Infinite, JBa, SLIGHT, Sonic, stanislaw          |
|           23 |     6696 | 2024-02-03 | NRG                | W   | 0.425      | -            | -                | -                | -         |     6.30 | Brehze, daps, FaNg, HexT, oSee                   |
|           22 |     6855 | 2024-02-01 | Nouns Esports      | W   | 0.412      | -            | -                | -                | -         |     7.61 | dare, dea, Peeping, shane, snav                  |
|           21 |     6857 | 2024-02-01 | BOSS               | W   | 0.412      | -            | -                | -                | -         |     6.40 | dare, dea, Peeping, shane, snav                  |
|           20 |     7698 | 2024-01-18 | NRG                | L   | 0.319      | -            | -                | -                | -         |    -5.44 | dare, dea, Peeping, shane, snav                  |
|           19 |     7753 | 2024-01-17 | regain             | W   | 0.313      | -            | -                | -                | -         |     2.05 | DYLAN, joshy, rayxts, sasha, Zucar               |
|           18 |     7857 | 2024-01-16 | Team Liquid        | L   | 0.306      | -            | -                | -                | -         |    -0.11 | dare, dea, Peeping, shane, snav                  |
|           17 |     7859 | 2024-01-16 | NRG                | W   | 0.306      | -            | -                | -                | -         |     4.52 | Brehze, daps, FaNg, HexT, oSee                   |
|           16 |     7864 | 2024-01-16 | Party Astronauts   | W   | 0.306      | -            | -                | -                | -         |     5.95 | dare, dea, Peeping, shane, snav                  |
|           15 |     7946 | 2024-01-15 | Mythic             | W   | 0.299      | -            | -                | -                | -         |     3.40 | Cooper, fl0m, freakazoid, hate, Trucklover86     |
|           14 |     7991 | 2024-01-14 | Party Astronauts   | W   | 0.293      | -            | -                | -                | -         |     5.88 | dare, dea, Peeping, shane, snav                  |
|           13 |     8006 | 2024-01-14 | For Fun            | W   | 0.292      | -            | -                | -                | -         |     3.59 | Momo, onter, Pluto, Tender, WOOHOO               |
|           12 |     8019 | 2024-01-13 | Team Liquid        | L   | 0.286      | -            | -                | -                | -         |    -0.09 | dare, dea, Peeping, shane, snav                  |
|           11 |     8060 | 2024-01-12 | LOS                | W   | 0.281      | -            | -                | -                | -         |     1.28 | history, JOTA, leo_drk, short, t9rnay            |
|           10 |     8074 | 2024-01-12 | NRG                | L   | 0.280      | -            | -                | -                | -         |    -4.46 | Brehze, daps, FaNg, HexT, oSee                   |
|            9 |     8797 | 2023-12-16 | Carpe Diem         | L   | 0.100      | -            | -                | -                | -         |    -2.40 | Cyrix, Lake, micro, Seb, Wolffe                  |
|            8 |     8805 | 2023-12-16 | Villainous         | W   | 0.099      | -            | -                | -                | -         |     0.82 | Beast, BiNoX, dopplahs, jsfeltner, TyRa          |
|            7 |     9207 | 2023-12-10 | Torqued            | L   | 0.060      | -            | -                | -                | -         |    -1.66 | Lake, micro, silas, steel, Wolffe                |
|            6 |     9211 | 2023-12-10 | Rugratz            | W   | 0.060      | -            | -                | -                | -         |     0.14 | Koalanoob, landmaz, Pol0, tender, tweiss         |
|            5 |     9474 | 2023-12-06 | Evil Geniuses      | L   | 0.033      | -            | -                | -                | -         |    -0.81 | consti, dare, Fr3nk1e, shane, snav               |
|            4 |     9538 | 2023-12-05 | Mythic             | W   | 0.026      | -            | -                | -                | -         |     0.31 | Cooper, fl0m, freakazoid, Stewie2K, Trucklover86 |
|            3 |     9630 | 2023-12-03 | Unjustified Gaming | W   | 0.013      | -            | -                | -                | 1 (0.013) |     0.09 | arcade, Cyrix, Lake, Seb, Wolffe                 |
|            2 |     9639 | 2023-12-03 | BOSS               | W   | 0.011      | -            | -                | -                | 1 (0.011) |     0.17 | dare, nbgee12, Peeping, shane, snav              |
|            1 |     9707 | 2023-12-02 | MIGHT              | W   | 0.006      | -            | -                | -                | 1 (0.006) |     0.05 | danss, djay, Nifty, scar, stamina                |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,571.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2023-12-10 |      0.059 | $3,000.00      | $178.33         |
| 2023-12-03 |      0.013 | $5,500.00      | $71.04          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
