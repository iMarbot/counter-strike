### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, DooM, grape, Mellow, PoseidoNN<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [277](../standings_global.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
Final Rank Value:  635.2<br />
<br />
Final Rank Value (635.2) = Starting Rank Value (683.6) + Head To Head Adjustments (-48.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.255[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.6
- 400 + ( ( 0.143 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 683.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |     1026 | 2024-04-15 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -             |    -7.53 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           28 |     1027 | 2024-04-15 | Nouns Esports              | L   | 1.000      | -            | -                | -                | -             |    -8.04 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           27 |     1157 | 2024-04-11 | BOSS                       | L   | 1.000      | -            | -                | -                | -             |    -6.35 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           26 |     1160 | 2024-04-11 | BOSS                       | L   | 1.000      | -            | -                | -                | -             |    -6.73 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           25 |     1455 | 2024-04-04 | One More Esports           | L   | 0.994      | -            | -                | -                | -             |   -15.82 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           24 |     1459 | 2024-04-04 | One More Esports           | W   | 0.994      | 0.477        | 0.011 (0.005)    | 0.147 (0.070)    | false (0.000) |    15.48 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           23 |     1510 | 2024-04-03 | Take Flyte                 | L   | 0.987      | -            | -                | -                | -             |   -13.56 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           22 |     1512 | 2024-04-03 | Take Flyte                 | L   | 0.987      | -            | -                | -                | -             |   -14.78 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           21 |     1712 | 2024-03-27 | MIGHT                      | W   | 0.941      | 0.477        | 0.003 (0.001)    | 0.213 (0.095)    | false (0.000) |    15.44 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           20 |     1715 | 2024-03-27 | MIGHT                      | W   | 0.941      | 0.477        | 0.003 (0.001)    | 0.213 (0.095)    | false (0.000) |    16.77 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           19 |     1780 | 2024-03-26 | Mythic                     | L   | 0.934      | -            | -                | -                | -             |   -12.15 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           18 |     1784 | 2024-03-26 | Mythic                     | W   | 0.934      | 0.477        | 0.003 (0.001)    | 0.380 (0.169)    | false (0.000) |    17.57 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           17 |     2238 | 2024-03-14 | NRG                        | L   | 0.854      | -            | -                | -                | -             |   -14.35 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           16 |     2240 | 2024-03-14 | NRG                        | L   | 0.854      | -            | -                | -                | -             |   -15.46 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           15 |     2591 | 2024-03-06 | Carpe Diem                 | L   | 0.801      | -            | -                | -                | -             |   -12.68 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           14 |     2593 | 2024-03-06 | Carpe Diem                 | L   | 0.801      | -            | -                | -                | -             |   -13.61 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           13 |     3123 | 2024-02-24 | LAG Gaming (American team) | W   | 0.727      | 0.143        | 0.033 (0.003)    | 0.405 (0.042)    | false (0.000) |    17.07 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           12 |     3191 | 2024-02-23 | FLUFFY AIMERS              | W   | 0.721      | 0.143        | 0.004 (0.000)    | 0.103 (0.011)    | false (0.000) |    11.29 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|           11 |     3555 | 2024-02-15 | G3 (Asian team)            | L   | 0.667      | -            | -                | -                | -             |    -8.08 | Danejoris, DooM, grape, Mellow, RiFT      |
|           10 |     3558 | 2024-02-15 | Zomblers                   | W   | 0.667      | 0.143        | 0.007 (0.001)    | 0.090 (0.009)    | false (0.000) |     9.73 | Danejoris, DooM, grape, Mellow, RiFT      |
|            9 |     4297 | 2024-01-26 | Rocket                     | L   | 0.534      | -            | -                | -                | -             |    -7.42 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|            8 |     4299 | 2024-01-26 | Zomblers                   | W   | 0.534      | 0.143        | 0.007 (0.001)    | 0.090 (0.007)    | false (0.000) |     8.04 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|            7 |     4416 | 2024-01-23 | LAG Gaming (American team) | W   | 0.514      | 0.143        | 0.033 (0.002)    | 0.405 (0.030)    | false (0.000) |    13.27 | Danejoris, DooM, grape, Mellow, PoseidoNN |
|            6 |     5158 | 2024-01-07 | LOS                        | L   | 0.408      | -            | -                | -                | -             |    -9.10 | Danejoris, DooM, grape, PoseidoNN, Reason |
|            5 |     5710 | 2023-12-10 | Akimbo Esports             | L   | 0.221      | -            | -                | -                | -             |    -5.27 | flixxy, Florence, Keiti, niise, Noxio     |
|            4 |     6578 | 2023-11-21 | Rocket                     | L   | 0.094      | -            | -                | -                | -             |    -1.54 | AJaxz, BeaKie, Danejoris, grape, Mellow   |
|            3 |     6904 | 2023-11-14 | Evil Geniuses              | L   | 0.048      | -            | -                | -                | -             |    -0.79 | AJaxz, BeaKie, Danejoris, grape, Mellow   |
|            2 |     6906 | 2023-11-14 | Wildcard Gaming            | L   | 0.047      | -            | -                | -                | -             |    -0.42 | AJaxz, BeaKie, Danejoris, grape, Mellow   |
|            1 |     6948 | 2023-11-13 | Pantsu                     | W   | 0.041      | 0.143        | 0.005 (0.000)    | 0.020 (0.000)    | false (0.000) |     0.59 | Hibou, N2oAmZ, obi1337, tmk, Zamgaa       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($187.43)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
