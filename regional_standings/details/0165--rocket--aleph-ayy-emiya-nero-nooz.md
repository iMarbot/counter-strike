### Roster Details<br />
Team Name: Rocket<br />
Roster: aleph, ayy, EMIYA, nero, nooz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [165](../standings_global.md)<br />
Regional Rank: [30]( ../standings_americas.md)<br />
Final Rank Value:  760.3<br />
<br />
Final Rank Value (760.3) = Starting Rank Value (668.5) + Head To Head Adjustments (91.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.135<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 668.5
- 400 + ( ( 0.135 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 668.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     3514 | 2024-02-16 | G3 (Asian team)            | W   | 0.674      | 0.143        | 0.014 (0.001)    | 0.173 (0.017)    | 0 (0.000) |    11.23 | aleph, ayy, EMIYA, nero, nooz   |
|           30 |     3515 | 2024-02-16 | MIGHT                      | W   | 0.673      | 0.143        | -                | 0.213 (0.020)    | 0 (0.000) |    10.50 | aleph, ayy, EMIYA, nero, nooz   |
|           29 |     3562 | 2024-02-15 | Revel                      | W   | 0.667      | 0.143        | 0.006 (0.001)    | -                | 0 (0.000) |     7.84 | aleph, ayy, EMIYA, nero, nooz   |
|           28 |     4059 | 2024-02-01 | BOSS                       | L   | 0.574      | -            | -                | -                | -         |    -5.09 | aleph, ayy, EMIYA, nero, nooz   |
|           27 |     4061 | 2024-02-01 | Nouns Esports              | L   | 0.573      | -            | -                | -                | -         |   -11.00 | aleph, ayy, EMIYA, nero, nooz   |
|           26 |     4235 | 2024-01-27 | LAG Gaming (American team) | W   | 0.541      | 0.143        | 0.033 (0.003)    | 0.405 (0.031)    | 0 (0.000) |    12.67 | aleph, ayy, EMIYA, nero, nooz   |
|           25 |     4297 | 2024-01-26 | Limitless                  | W   | 0.534      | 0.143        | -                | 0.177 (0.013)    | 0 (0.000) |     7.42 | aleph, ayy, EMIYA, nero, nooz   |
|           24 |     4300 | 2024-01-26 | WICKED (American team)     | W   | 0.534      | 0.143        | 0.020 (0.002)    | 0.157 (0.012)    | 0 (0.000) |     9.23 | aleph, ayy, EMIYA, nero, nooz   |
|           23 |     4635 | 2024-01-18 | Nouns Esports              | L   | 0.480      | -            | -                | -                | -         |    -8.96 | aleph, ayy, EMIYA, nero, nooz   |
|           22 |     4638 | 2024-01-18 | Carpe Diem                 | W   | 0.480      | 0.143        | 0.009 (0.001)    | 0.178 (0.012)    | 0 (0.000) |     7.21 | aleph, ayy, EMIYA, nero, nooz   |
|           21 |     4682 | 2024-01-17 | FLUFFY AIMERS              | W   | 0.474      | -            | -                | -                | 0 (0.000) |     6.67 | aleph, ayy, EMIYA, nero, nooz   |
|           20 |     4862 | 2024-01-14 | BOSS                       | L   | 0.454      | -            | -                | -                | -         |    -3.75 | aleph, ayy, droid, Elk, nero    |
|           19 |     4877 | 2024-01-13 | Carpe Diem                 | W   | 0.447      | 0.143        | 0.009 (0.001)    | 0.178 (0.011)    | 0 (0.000) |     7.29 | aleph, ayy, droid, Elk, nero    |
|           18 |     4906 | 2024-01-12 | For Fun                    | W   | 0.442      | 0.143        | 0.014 (0.001)    | 0.116 (0.007)    | 0 (0.000) |     8.27 | aleph, ayy, droid, Elk, nero    |
|           17 |     4916 | 2024-01-12 | M80                        | L   | 0.441      | -            | -                | -                | -         |    -0.48 | aleph, ayy, droid, Elk, nero    |
|           16 |     4954 | 2024-01-12 | For Fun                    | W   | 0.436      | 0.143        | 0.014 (0.001)    | -                | -         |     8.54 | aleph, ayy, droid, Elk, nero    |
|           15 |     4963 | 2024-01-11 | LOS                        | W   | 0.435      | -            | -                | -                | -         |     4.00 | aleph, ayy, droid, Elk, nero    |
|           14 |     4976 | 2024-01-11 | Villainous                 | W   | 0.434      | -            | -                | -                | -         |     4.90 | aleph, ayy, droid, Elk, nero    |
|           13 |     5019 | 2024-01-10 | Revenge Nation             | W   | 0.428      | 0.143        | 0.043 (0.003)    | 0.123 (0.008)    | -         |     7.79 | aleph, ayy, droid, Elk, nero    |
|           12 |     5138 | 2024-01-08 | Detonate                   | W   | 0.415      | -            | -                | -                | -         |     6.64 | aleph, ayy, droid, nero, nooz   |
|           11 |     5333 | 2023-12-17 | MIGHT                      | L   | 0.268      | -            | -                | -                | -         |    -3.62 | aleph, droid, nero, nooz, R2D2J |
|           10 |     5336 | 2023-12-17 | Bad News Bears             | W   | 0.267      | -            | -                | -                | -         |     2.20 | aleph, droid, nero, nooz, R2D2J |
|            9 |     5421 | 2023-12-16 | Revenge Nation             | W   | 0.261      | 0.143        | 0.043 (0.002)    | -                | -         |     4.87 | aleph, droid, nero, nooz, R2D2J |
|            8 |     5560 | 2023-12-15 | LAG Gaming (American team) | L   | 0.254      | -            | -                | -                | -         |    -1.30 | aleph, droid, nero, nooz, R2D2J |
|            7 |     6538 | 2023-11-22 | M80                        | L   | 0.101      | -            | -                | -                | -         |    -0.09 | aleph, droid, nero, nooz, R2D2J |
|            6 |     6541 | 2023-11-22 | FLUFFY AIMERS              | L   | 0.100      | -            | -                | -                | -         |    -1.55 | aleph, droid, nero, nooz, R2D2J |
|            5 |     6578 | 2023-11-21 | Limitless                  | W   | 0.094      | 0.500        | -                | 0.177 (0.008)    | -         |     1.54 | aleph, droid, nero, nooz, R2D2J |
|            4 |     6613 | 2023-11-20 | BOSS                       | L   | 0.087      | -            | -                | -                | -         |    -0.59 | aleph, droid, Elk, nero, R2D2J  |
|            3 |     6855 | 2023-11-15 | Carpe Diem                 | L   | 0.054      | -            | -                | -                | -         |    -0.71 | aleph, droid, Elk, nero, R2D2J  |
|            2 |     7155 | 2023-11-08 | Nouns Esports              | W   | 0.007      | -            | -                | -                | -         |     0.13 | aleph, droid, Elk, nero, R2D2J  |
|            1 |     7219 | 2023-11-07 | Evil Geniuses              | L   | 0.001      | -            | -                | -                | -         |    -0.01 | aleph, droid, Elk, nero, R2D2J  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($308.71)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
