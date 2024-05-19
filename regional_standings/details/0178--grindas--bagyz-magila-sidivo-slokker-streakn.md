### Roster Details<br />
Team Name: Grindas<br />
Roster: BaGyZ, MAGILA, Sidivo, slokker, StreakN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [178](../standings_global.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
Final Rank Value:  748.1<br />
<br />
Final Rank Value (748.1) = Starting Rank Value (701.7) + Head To Head Adjustments (46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.271[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.7
- 400 + ( ( 0.152 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 701.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |       72 | 2024-05-04 | Team Flow             | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     7.63 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           32 |      469 | 2024-04-25 | EsmagaB               | W   | 1.000      | 0.371        | 0.016 (0.006)    | 0.559 (0.207)    | false (0.000) |    19.50 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           31 |      511 | 2024-04-24 | Copenhagen Wolves     | W   | 1.000      | 0.371        | -                | 0.417 (0.155)    | false (0.000) |    12.80 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           30 |      563 | 2024-04-23 | LOADING (French team) | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | false (0.000) |     5.06 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           29 |      638 | 2024-04-21 | Soda Gaming           | L   | 1.000      | -            | -                | -                | -             |   -23.00 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           28 |      686 | 2024-04-20 | RUSH B (Russian team) | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.471 (0.067)    | false (0.000) |    21.13 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           27 |      703 | 2024-04-20 | TopTab Club           | W   | 1.000      | -            | -                | -                | false (0.000) |     8.13 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           26 |     1225 | 2024-04-10 | Lemondogs             | W   | 1.000      | 0.371        | -                | 0.252 (0.094)    | false (0.000) |     9.78 | BaGyZ, MAGILA, Sidivo, slokker, StreakN |
|           25 |     3034 | 2024-02-27 | Rhyno Esports         | L   | 0.745      | -            | -                | -                | -             |    -6.07 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           24 |     3240 | 2024-02-22 | LODIS                 | W   | 0.712      | 0.371        | 0.002 (0.001)    | 0.139 (0.037)    | false (0.000) |     9.35 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           23 |     3251 | 2024-02-22 | GUN5 Esports          | W   | 0.712      | 0.371        | -                | 0.218 (0.058)    | false (0.000) |     9.96 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           22 |     3823 | 2024-02-08 | L&G                   | L   | 0.618      | -            | -                | -                | -             |   -13.16 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           21 |     3901 | 2024-02-05 | Insilio               | L   | 0.598      | -            | -                | -                | -             |    -3.28 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           20 |     4257 | 2024-01-27 | FORZE Youngsters      | L   | 0.539      | -            | -                | -                | -             |    -8.64 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           19 |     4378 | 2024-01-24 | Rebels Gaming         | L   | 0.519      | -            | -                | -                | -             |    -1.48 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           18 |     4458 | 2024-01-22 | MOUZ NXT              | L   | 0.506      | -            | -                | -                | -             |    -1.50 | AwwEzz, BaGyZ, prochas, Sidivo, slokker |
|           17 |     5772 | 2023-12-09 | Wolves eSports        | L   | 0.211      | -            | -                | -                | -             |    -3.94 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|           16 |     6095 | 2023-12-02 | FreeESPI              | L   | 0.165      | -            | -                | -                | -             |    -2.99 | AwwEzz, BaGyZ, MAGILA, Prochas, Sidivo  |
|           15 |     6125 | 2023-12-02 | Daugava               | W   | 0.163      | 0.143        | 0.001 (0.000)    | -                | true (0.163)  |     1.32 | AwwEzz, BaGyZ, MAGILA, Prochas, Sidivo  |
|           14 |     6268 | 2023-11-29 | TY                    | W   | 0.145      | 0.143        | 0.011 (0.000)    | -                | -             |     2.22 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|           13 |     6275 | 2023-11-29 | K10                   | W   | 0.144      | 0.371        | 0.015 (0.001)    | 0.418 (0.022)    | -             |     3.38 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|           12 |     6309 | 2023-11-28 | XGOD                  | W   | 0.139      | -            | -                | -                | -             |     1.08 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|           11 |     6314 | 2023-11-28 | TEAM ZOO BAR          | L   | 0.138      | -            | -                | -                | -             |    -3.28 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|           10 |     6350 | 2023-11-27 | Viperio               | W   | 0.132      | 0.371        | -                | 0.321 (0.016)    | -             |     1.54 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            9 |     6368 | 2023-11-27 | Galaxy Gaming         | W   | 0.132      | 0.143        | 0.000 (0.000)    | -                | -             |     1.50 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            8 |     6618 | 2023-11-20 | Wu-Tang Clan          | L   | 0.086      | -            | -                | -                | -             |    -2.06 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            7 |     6631 | 2023-11-20 | Aurora Young Blud     | W   | 0.085      | 0.371        | 0.017 (0.001)    | -                | -             |     1.79 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            6 |     6672 | 2023-11-19 | GenOne                | L   | 0.078      | -            | -                | -                | -             |    -1.49 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            5 |     6703 | 2023-11-18 | XGOD                  | W   | 0.072      | -            | -                | -                | -             |     0.56 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            4 |     6713 | 2023-11-18 | Insilio               | W   | 0.072      | 0.294        | 0.020 (0.000)    | 0.875 (0.018)    | -             |     1.76 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            3 |     6815 | 2023-11-16 | GenOne                | L   | 0.059      | -            | -                | -                | -             |    -1.12 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            2 |     7137 | 2023-11-09 | MOUZ NXT              | L   | 0.012      | -            | -                | -                | -             |    -0.04 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |
|            1 |     7173 | 2023-11-08 | Bazar mix             | L   | 0.006      | -            | -                | -                | -             |    -0.14 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($327.82)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-17 |      0.264 | $218.15        | $57.62          |
| 2023-12-02 |      0.165 | $1,633.90      | $270.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
