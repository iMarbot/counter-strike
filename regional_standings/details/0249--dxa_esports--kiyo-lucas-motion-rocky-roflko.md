### Roster Details<br />
Team Name: DXA Esports<br />
Roster: Kiyo, lucas, motion, rocky, Roflko<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [249](../standings_global.md)<br />
Regional Rank: [44]( ../standings_asia.md)<br />
Final Rank Value:  668.4<br />
<br />
Final Rank Value (668.4) = Starting Rank Value (738.1) + Head To Head Adjustments (-69.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.101[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 738.1
- 400 + ( ( 0.170 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 738.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      908 | 2024-04-18 | Mindfreak (Australian team) | L   | 1.000      | -            | -                | -                | -             |   -11.19 | Kiyo, lucas, motion, rocky, Roflko      |
|           32 |      969 | 2024-04-17 | Blitz (Australian team)     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.109 (0.016)    | false (0.000) |     8.46 | Kiyo, lucas, motion, rocky, Roflko      |
|           31 |      976 | 2024-04-17 | Nine Lives                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     5.66 | Kiyo, lucas, motion, rocky, Roflko      |
|           30 |     1246 | 2024-04-10 | Mindfreak (Australian team) | L   | 1.000      | -            | -                | -                | -             |   -12.33 | Kiyo, lucas, motion, rocky, Roflko      |
|           29 |     1252 | 2024-04-10 | Mindfreak (Australian team) | L   | 1.000      | -            | -                | -                | -             |   -13.43 | Kiyo, lucas, motion, rocky, Roflko      |
|           28 |     1554 | 2024-04-03 | Bad News Kangaroos          | L   | 0.983      | -            | -                | -                | -             |    -6.15 | Kiyo, lucas, motion, rocky, Roflko      |
|           27 |     1558 | 2024-04-03 | Bad News Kangaroos          | L   | 0.983      | -            | -                | -                | -             |    -6.50 | Kiyo, lucas, motion, rocky, Roflko      |
|           26 |     1922 | 2024-03-23 | Bad News Kangaroos          | L   | 0.909      | -            | -                | -                | -             |    -5.90 | gump, Kiyo, lucas, motion, Roflko       |
|           25 |     1924 | 2024-03-23 | KZG                         | W   | 0.909      | 0.143        | 0.020 (0.003)    | 0.249 (0.032)    | true (0.909)  |    14.62 | gump, Kiyo, lucas, motion, Roflko       |
|           24 |     2339 | 2024-03-13 | Vantage Esports             | W   | 0.843      | 0.333        | 0.000 (0.000)    | 0.236 (0.066)    | false (0.000) |    10.40 | Kiyo, lucas, motion, rocky, Roflko      |
|           23 |     2343 | 2024-03-13 | Vantage Esports             | L   | 0.843      | -            | -                | -                | -             |   -16.52 | Kiyo, lucas, motion, rocky, Roflko      |
|           22 |     3325 | 2024-02-21 | Rooster                     | L   | 0.703      | -            | -                | -                | -             |    -6.82 | Kiyo, lucas, motion, rocky, Roflko      |
|           21 |     3328 | 2024-02-21 | Rooster                     | L   | 0.703      | -            | -                | -                | -             |    -7.19 | Kiyo, lucas, motion, rocky, Roflko      |
|           20 |     3382 | 2024-02-20 | Altered Edge                | L   | 0.696      | -            | -                | -                | -             |   -13.16 | Falcon, Kiyo, motion, Roflko, Valiance  |
|           19 |     3606 | 2024-02-15 | Vantage Esports             | L   | 0.663      | -            | -                | -                | -             |   -14.62 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           18 |     3692 | 2024-02-13 | VexX Gaming                 | W   | 0.650      | 0.143        | 0.010 (0.001)    | 0.390 (0.036)    | false (0.000) |     9.53 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           17 |     3697 | 2024-02-13 | Underground Esports Club    | W   | 0.649      | 0.143        | 0.000 (0.000)    | 0.112 (0.010)    | false (0.000) |     6.20 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           16 |     3705 | 2024-02-12 | Team RPG                    | W   | 0.649      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     2.83 | HUGHMUNGUS, Kiyo, lucas, motion, Roflko |
|           15 |     3739 | 2024-02-12 | VexX Gaming                 | L   | 0.642      | -            | -                | -                | -             |   -11.04 | Falcon, helix, Kiyo, lucas, Roflko      |
|           14 |     4406 | 2024-01-24 | Mindfreak (Australian team) | L   | 0.516      | -            | -                | -                | -             |    -8.20 | Falcon, helix, Kiyo, lucas, Roflko      |
|           13 |     4408 | 2024-01-24 | Underground Esports Club    | W   | 0.516      | 0.143        | 0.000 (0.000)    | 0.112 (0.008)    | false (0.000) |     4.72 | Falcon, helix, Kiyo, lucas, Roflko      |
|           12 |     4840 | 2024-01-15 | Vantage Esports             | W   | 0.456      | 0.143        | -                | 0.236 (0.015)    | false (0.000) |     4.09 | Falcon, helix, Kiyo, lucas, Roflko      |
|           11 |     4850 | 2024-01-15 | TEAM RKON                   | W   | 0.456      | 0.143        | -                | 0.092 (0.006)    | false (0.000) |     3.29 | Falcon, helix, Kiyo, lucas, Roflko      |
|           10 |     4898 | 2024-01-13 | StevosFirstCS2              | W   | 0.443      | -            | -                | -                | -             |     3.06 | Falcon, helix, Kiyo, lucas, Roflko      |
|            9 |     4902 | 2024-01-13 | TEAM RKON                   | L   | 0.443      | -            | -                | -                | -             |   -10.86 | Falcon, helix, Kiyo, lucas, Roflko      |
|            8 |     4908 | 2024-01-12 | Blitz (Australian team)     | W   | 0.442      | 0.143        | -                | 0.109 (0.007)    | -             |     2.75 | Falcon, helix, Kiyo, lucas, Roflko      |
|            7 |     4961 | 2024-01-11 | Abyss (Australian team)     | W   | 0.435      | -            | -                | -                | -             |     1.82 | Falcon, helix, Kiyo, lucas, Roflko      |
|            6 |     5704 | 2023-12-11 | Mindfreak (Australian team) | L   | 0.223      | -            | -                | -                | -             |    -4.24 | Falcon, helix, Kiyo, lucas, Roflko      |
|            5 |     5902 | 2023-12-07 | Canon Event                 | W   | 0.196      | -            | -                | -                | -             |     0.81 | Falcon, helix, Kiyo, lucas, Roflko      |
|            4 |     6008 | 2023-12-05 | Dracula Flow                | W   | 0.183      | -            | -                | -                | -             |     0.75 | Falcon, helix, Kiyo, lucas, Roflko      |
|            3 |     6173 | 2023-11-30 | Vantage Esports             | L   | 0.156      | -            | -                | -                | -             |    -3.38 | Falcon, helix, Kiyo, lucas, Roflko      |
|            2 |     6223 | 2023-11-30 | Antic Esports               | W   | 0.149      | 0.143        | 0.000 (0.000)    | -                | -             |     1.42 | Falcon, helix, Kiyo, lucas, Roflko      |
|            1 |     6229 | 2023-11-29 | Underground Esports Club    | W   | 0.149      | 0.143        | 0.000 (0.000)    | 0.112 (0.002)    | -             |     1.42 | Falcon, helix, Kiyo, lucas, Roflko      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,651.63)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.909 | $1,628.98      | $1,481.50       |
| 2024-02-17 |      0.681 | $250.00        | $170.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
