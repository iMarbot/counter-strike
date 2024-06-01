### Roster Details<br />
Team Name: Carpe Diem<br />
Roster: Lake, micro, Seb, Tender, wiz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [205](../standings_global.md)<br />
Regional Rank: [44]( ../standings_americas.md)<br />
Final Rank Value:  720.7<br />
<br />
Final Rank Value (720.7) = Starting Rank Value (635.1) + Head To Head Adjustments (85.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.328[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 635.1
- 400 + ( ( 0.116 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 635.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       13 | 2024-05-29 | Lore Gaming      | L   | 1.000      | -            | -                | -                | -         |   -27.01 | Lake, micro, Seb, Tender, wiz        |
|           46 |      427 | 2024-05-22 | MIGHT            | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | 0 (0.000) |    10.81 | Lake, micro, Seb, Tender, wiz        |
|           45 |      430 | 2024-05-22 | MIGHT            | W   | 1.000      | 0.477        | -                | 0.207 (0.099)    | 0 (0.000) |    11.72 | Lake, micro, Seb, Tender, wiz        |
|           44 |      537 | 2024-05-21 | Legacy           | L   | 1.000      | -            | -                | -                | -         |    -3.90 | Lake, micro, Seb, Tender, wiz        |
|           43 |      541 | 2024-05-21 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -6.94 | Lake, micro, Seb, Tender, wiz        |
|           42 |      543 | 2024-05-21 | Wildcard Gaming  | L   | 1.000      | -            | -                | -                | -         |    -7.38 | Lake, micro, Seb, Tender, wiz        |
|           41 |      630 | 2024-05-20 | BOSS             | W   | 1.000      | 0.477        | 0.016 (0.007)    | 0.315 (0.150)    | 0 (0.000) |    19.49 | Lake, micro, Seb, Tender, wiz        |
|           40 |      635 | 2024-05-20 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -11.70 | Lake, micro, Seb, Tender, wiz        |
|           39 |     1020 | 2024-05-16 | One More Esports | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.166 (0.079)    | 0 (0.000) |    15.03 | Lake, micro, Seb, Tender, wiz        |
|           38 |     1025 | 2024-05-16 | One More Esports | W   | 1.000      | 0.477        | 0.005 (0.002)    | 0.166 (0.079)    | 0 (0.000) |    16.42 | Lake, micro, Seb, Tender, wiz        |
|           37 |     1113 | 2024-05-15 | Nouns Esports    | W   | 1.000      | 0.477        | 0.071 (0.034)    | 0.507 (0.242)    | 0 (0.000) |    24.80 | Lake, micro, Seb, Tender, wiz        |
|           36 |     1119 | 2024-05-15 | Nouns Esports    | W   | 1.000      | 0.477        | 0.071 (0.034)    | 0.507 (0.242)    | 0 (0.000) |    26.19 | Lake, micro, Seb, Tender, wiz        |
|           35 |     1216 | 2024-05-14 | LAG Gaming       | L   | 1.000      | -            | -                | -                | -         |    -7.80 | arcade, Lake, micro, Seb, wiz        |
|           34 |     1222 | 2024-05-14 | LAG Gaming       | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.335 (0.160)    | 0 (0.000) |    24.25 | arcade, Lake, micro, Seb, wiz        |
|           33 |     3095 | 2024-04-11 | Mythic           | W   | 0.879      | 0.477        | -                | 0.339 (0.142)    | 0 (0.000) |    18.18 | arcade, Lake, micro, Seb, wiz        |
|           32 |     3098 | 2024-04-11 | Mythic           | L   | 0.879      | -            | -                | -                | -         |    -9.33 | arcade, Lake, micro, Seb, wiz        |
|           31 |     3216 | 2024-04-09 | NRG              | L   | 0.866      | -            | -                | -                | -         |    -5.08 | arcade, Lake, micro, Seb, wiz        |
|           30 |     3220 | 2024-04-09 | NRG              | L   | 0.866      | -            | -                | -                | -         |    -5.32 | arcade, Lake, micro, Seb, wiz        |
|           29 |     3463 | 2024-04-04 | Take Flyte       | L   | 0.833      | -            | -                | -                | -         |    -8.00 | arcade, Lake, micro, Seb, wiz        |
|           28 |     3467 | 2024-04-04 | Take Flyte       | L   | 0.833      | -            | -                | -                | -         |    -8.52 | arcade, Lake, micro, Seb, wiz        |
|           27 |     3760 | 2024-03-27 | Party Astronauts | L   | 0.780      | -            | -                | -                | -         |    -3.73 | arcade, Lake, micro, Seb, wiz        |
|           26 |     3764 | 2024-03-27 | Party Astronauts | L   | 0.780      | -            | -                | -                | -         |    -3.87 | arcade, Lake, micro, Seb, wiz        |
|           25 |     4348 | 2024-03-15 | Elevate          | L   | 0.700      | -            | -                | -                | -         |    -5.49 | arcade, Lake, micro, Seb, wiz        |
|           24 |     4353 | 2024-03-15 | Elevate          | L   | 0.700      | -            | -                | -                | -         |    -5.76 | arcade, Lake, micro, Seb, wiz        |
|           23 |     4462 | 2024-03-13 | Party Astronauts | L   | 0.685      | -            | -                | -                | -         |    -3.74 | arcade, Lake, micro, Seb, wiz        |
|           22 |     4525 | 2024-03-12 | NRG              | W   | 0.680      | 0.143        | 0.010 (0.001)    | 0.555 (0.054)    | 0 (0.000) |    16.08 | arcade, Lake, micro, Seb, wiz        |
|           21 |     4532 | 2024-03-12 | MIGHT            | W   | 0.679      | -            | -                | -                | -         |    12.62 | arcade, Lake, micro, Seb, wiz        |
|           20 |     4834 | 2024-03-06 | Limitless        | W   | 0.640      | 0.477        | 0.001 (0.000)    | -                | -         |    11.65 | arcade, Lake, micro, Seb, wiz        |
|           19 |     4836 | 2024-03-06 | Limitless        | W   | 0.640      | 0.477        | 0.001 (0.000)    | -                | -         |    12.30 | arcade, Lake, micro, Seb, wiz        |
|           18 |     5678 | 2024-02-21 | MIGHT            | L   | 0.546      | -            | -                | -                | -         |    -7.48 | arcade, DJF, Lake, micro, wiz        |
|           17 |     6580 | 2024-02-02 | Party Astronauts | L   | 0.419      | -            | -                | -                | -         |    -2.22 | arcade, Lake, Seb, Walco, wiz        |
|           16 |     6586 | 2024-02-02 | Wildcard Gaming  | L   | 0.418      | -            | -                | -                | -         |    -2.25 | arcade, Lake, Seb, Walco, wiz        |
|           15 |     6907 | 2024-01-27 | ex-CatEvil       | W   | 0.379      | -            | -                | -                | -         |     5.66 | arcade, Lake, Seb, Walco, wiz        |
|           14 |     7002 | 2024-01-26 | LOS              | W   | 0.373      | -            | -                | -                | -         |     4.26 | arcade, Lake, Seb, Walco, wiz        |
|           13 |     7008 | 2024-01-26 | huge sweaty      | W   | 0.373      | -            | -                | -                | -         |     3.34 | arcade, Lake, Seb, Walco, wiz        |
|           12 |     7164 | 2024-01-23 | Team Lampa       | L   | 0.353      | -            | -                | -                | -         |    -7.66 | arcade, Lake, Seb, Walco, wiz        |
|           11 |     7449 | 2024-01-18 | Rocket           | L   | 0.319      | -            | -                | -                | -         |    -5.81 | Lake, Seb, Walco, wiz, Wolffe        |
|           10 |     7506 | 2024-01-17 | LOS              | W   | 0.313      | -            | -                | -                | -         |     3.46 | Lake, Seb, Walco, wiz, Wolffe        |
|            9 |     7699 | 2024-01-15 | MIGHT            | L   | 0.299      | -            | -                | -                | -         |    -4.09 | Lake, Seb, Walco, wiz, Wolffe        |
|            8 |     7737 | 2024-01-14 | Nouns Esports    | L   | 0.294      | -            | -                | -                | -         |    -1.51 | Lake, Seb, Walco, wiz, Wolffe        |
|            7 |     7752 | 2024-01-14 | Akimbo Esports   | W   | 0.292      | -            | -                | -                | -         |     6.23 | Lake, Seb, Walco, wiz, Wolffe        |
|            6 |     7769 | 2024-01-13 | Rocket           | L   | 0.286      | -            | -                | -                | -         |    -5.43 | Lake, Seb, Walco, wiz, Wolffe        |
|            5 |     7815 | 2024-01-12 | Party Astronauts | L   | 0.281      | -            | -                | -                | -         |    -1.36 | Lake, Seb, Walco, wiz, Wolffe        |
|            4 |     7819 | 2024-01-12 | LOS              | W   | 0.280      | -            | -                | -                | -         |     3.07 | Lake, Seb, Walco, wiz, Wolffe        |
|            3 |     8433 | 2023-12-17 | Nouns Esports    | L   | 0.106      | -            | -                | -                | -         |    -1.68 | Cyrix, Lake, micro, Seb, Wolffe      |
|            2 |     8537 | 2023-12-16 | Elevate          | W   | 0.100      | 0.294        | 0.012 (0.000)    | -                | -         |     2.40 | Cyrix, Lake, micro, Seb, Wolffe      |
|            1 |     8548 | 2023-12-16 | We Go Hard       | W   | 0.099      | -            | -                | -                | -         |     0.66 | Dodge, goro, myth, Oczarka, Scorchyy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
