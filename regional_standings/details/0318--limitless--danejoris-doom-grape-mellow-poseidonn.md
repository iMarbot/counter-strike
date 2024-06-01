### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, DooM, grape, Mellow, PoseidoNN<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [318](../standings_global.md)<br />
Regional Rank: [74]( ../standings_americas.md)<br />
Final Rank Value:  628.8<br />
<br />
Final Rank Value (628.8) = Starting Rank Value (701.2) + Head To Head Adjustments (-72.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.062[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.2
- 400 + ( ( 0.148 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 701.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |      425 | 2024-05-22 | LAG Gaming       | L   | 1.000      | -            | -                | -                | -         |    -7.49 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           40 |      431 | 2024-05-22 | LAG Gaming       | L   | 1.000      | -            | -                | -                | -         |    -7.99 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           39 |      528 | 2024-05-21 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -4.00 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           38 |      530 | 2024-05-21 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -4.16 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           37 |      722 | 2024-05-19 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -5.19 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE |
|           36 |     1116 | 2024-05-15 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.33 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           35 |     1122 | 2024-05-15 | Elevate          | L   | 1.000      | -            | -                | -                | -         |    -5.61 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           34 |     1483 | 2024-05-10 | M80              | L   | 1.000      | -            | -                | -                | -         |    -0.86 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           33 |     1484 | 2024-05-10 | M80              | L   | 1.000      | -            | -                | -                | -         |    -0.87 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           32 |     1537 | 2024-05-09 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |    -8.38 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           31 |     1543 | 2024-05-09 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.030 (0.014)    | 0.384 (0.183)    | 0 (0.000) |    23.65 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           30 |     1586 | 2024-05-08 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -5.58 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           29 |     1590 | 2024-05-08 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -5.88 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           28 |     2932 | 2024-04-15 | Nouns Esports    | L   | 0.906      | -            | -                | -                | -         |    -4.06 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           27 |     2933 | 2024-04-15 | Nouns Esports    | L   | 0.906      | -            | -                | -                | -         |    -4.23 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           26 |     3094 | 2024-04-11 | BOSS             | L   | 0.879      | -            | -                | -                | -         |    -6.45 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           25 |     3097 | 2024-04-11 | BOSS             | L   | 0.879      | -            | -                | -                | -         |    -6.83 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           24 |     3460 | 2024-04-04 | One More Esports | L   | 0.833      | -            | -                | -                | -         |   -11.94 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           23 |     3464 | 2024-04-04 | One More Esports | W   | 0.833      | 0.477        | 0.005 (0.002)    | 0.166 (0.066)    | 0 (0.000) |    14.54 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           22 |     3522 | 2024-04-03 | Take Flyte       | L   | 0.826      | -            | -                | -                | -         |   -10.11 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           21 |     3524 | 2024-04-03 | Take Flyte       | L   | 0.826      | -            | -                | -                | -         |   -10.85 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           20 |     3761 | 2024-03-27 | MIGHT            | W   | 0.780      | 0.477        | 0.001 (0.000)    | 0.207 (0.077)    | 0 (0.000) |    11.59 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           19 |     3765 | 2024-03-27 | MIGHT            | W   | 0.780      | 0.477        | 0.001 (0.000)    | 0.207 (0.077)    | 0 (0.000) |    12.42 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           18 |     3838 | 2024-03-26 | Mythic           | L   | 0.773      | -            | -                | -                | -         |    -9.58 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           17 |     3843 | 2024-03-26 | Mythic           | W   | 0.773      | 0.477        | 0.000 (0.000)    | 0.339 (0.125)    | 0 (0.000) |    15.14 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           16 |     4399 | 2024-03-14 | NRG              | L   | 0.693      | -            | -                | -                | -         |    -5.82 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           15 |     4401 | 2024-03-14 | NRG              | L   | 0.693      | -            | -                | -                | -         |    -6.11 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           14 |     4834 | 2024-03-06 | Carpe Diem       | L   | 0.640      | -            | -                | -                | -         |   -11.65 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           13 |     4836 | 2024-03-06 | Carpe Diem       | L   | 0.640      | -            | -                | -                | -         |   -12.30 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           12 |     5477 | 2024-02-24 | NRG              | L   | 0.566      | -            | -                | -                | -         |    -5.25 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           11 |     5484 | 2024-02-24 | LAG Gaming       | W   | 0.566      | 0.143        | 0.013 (0.001)    | 0.335 (0.027)    | 0 (0.000) |    13.68 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|           10 |     5581 | 2024-02-23 | FLUFFY AIMERS    | W   | 0.560      | 0.143        | 0.030 (0.002)    | 0.384 (0.031)    | 0 (0.000) |    13.55 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            9 |     6010 | 2024-02-15 | G3               | L   | 0.506      | -            | -                | -                | -         |    -5.94 | Danejoris, DooM, grape, Mellow, RiFT       |
|            8 |     6013 | 2024-02-15 | Zomblers         | W   | 0.506      | 0.143        | 0.003 (0.000)    | 0.108 (0.008)    | 0 (0.000) |     6.83 | Danejoris, DooM, grape, Mellow, RiFT       |
|            7 |     7004 | 2024-01-26 | Rocket           | L   | 0.373      | -            | -                | -                | -         |    -7.53 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            6 |     7009 | 2024-01-26 | Zomblers         | W   | 0.373      | 0.143        | 0.003 (0.000)    | 0.108 (0.006)    | 0 (0.000) |     5.10 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            5 |     7157 | 2024-01-23 | NRG              | L   | 0.353      | -            | -                | -                | -         |    -3.44 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            4 |     7160 | 2024-01-23 | LAG Gaming       | W   | 0.353      | 0.143        | 0.013 (0.001)    | 0.335 (0.017)    | 0 (0.000) |     8.95 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            3 |     7693 | 2024-01-15 | huge sweaty      | L   | 0.300      | -            | -                | -                | -         |    -7.23 | Danejoris, DooM, grape, Mellow, PoseidoNN  |
|            2 |     8185 | 2024-01-07 | LOS              | L   | 0.247      | -            | -                | -                | -         |    -5.80 | Danejoris, DooM, grape, PoseidoNN, Reason  |
|            1 |     8946 | 2023-12-10 | Akimbo Esports   | L   | 0.060      | -            | -                | -                | -         |    -1.45 | flixxy, Florence, Keiti, niise, Noxio      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($400.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
