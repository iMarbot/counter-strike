### Roster Details<br />
Team Name: ROYALS<br />
Roster: jeyN, joeyyy, oskvr, Ping, Swaggy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [245](../standings_global.md)<br />
Regional Rank: [162]( ../standings_europe.md)<br />
Final Rank Value:  691.9<br />
<br />
Final Rank Value (691.9) = Starting Rank Value (718.9) + Head To Head Adjustments (-27.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.119[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 718.9
- 400 + ( ( 0.157 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 718.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      568 | 2024-05-21 | FearFerox               | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    13.05 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           20 |      698 | 2024-05-20 | EXO Clan                | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.579 (0.083)    | 0 (0.000) |    22.48 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           19 |     1251 | 2024-05-14 | The Last Resort         | L   | 1.000      | -            | -                | -                | -         |   -14.80 | jeyN, joeyyy, oskvr, Swaggy, urk3  |
|           18 |     1575 | 2024-05-09 | Verdant                 | L   | 1.000      | -            | -                | -                | -         |    -6.77 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           17 |     1621 | 2024-05-08 | Halal5                  | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.110 (0.016)    | 0 (0.000) |    14.47 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           16 |     1689 | 2024-05-07 | Raptors Esports Club    | L   | 1.000      | -            | -                | -                | -         |    -9.74 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           15 |     1981 | 2024-05-01 | Part Timers             | L   | 1.000      | -            | -                | -                | -         |   -14.66 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           14 |     2055 | 2024-04-30 | ex-K10                  | L   | 1.000      | -            | -                | -                | -         |   -11.53 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           13 |     2131 | 2024-04-28 | Team Invictum           | L   | 0.991      | -            | -                | -                | -         |   -17.44 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           12 |     4307 | 2024-03-18 | FearFerox               | W   | 0.718      | 0.143        | 0.001 (0.000)    | 0.101 (0.010)    | 0 (0.000) |     8.84 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           11 |     4590 | 2024-03-13 | NeedMoreBullets         | W   | 0.684      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     3.46 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|           10 |     4846 | 2024-03-09 | Verdant                 | L   | 0.656      | -            | -                | -                | -         |    -4.73 | entz, jeyN, joeyyy, oskvr, Ping    |
|            9 |     5689 | 2024-02-24 | Raptors Esports Club    | L   | 0.564      | -            | -                | -                | -         |    -6.30 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|            8 |     5713 | 2024-02-24 | Anita Max Wynn          | W   | 0.563      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 1 (0.563) |     4.92 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|            7 |     5734 | 2024-02-24 | ex-Raptors Esports Club | W   | 0.562      | 0.143        | 0.000 (0.000)    | 0.110 (0.009)    | 1 (0.562) |     7.82 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|            6 |     5754 | 2024-02-23 | EXO Clan                | L   | 0.558      | -            | -                | -                | -         |    -2.97 | jeyN, joeyyy, oskvr, Ping, Swaggy  |
|            5 |     7072 | 2024-01-28 | Part Timers             | L   | 0.385      | -            | -                | -                | -         |    -9.14 | entz, jeyN, oskvr, Ping, Swaggy    |
|            4 |     7074 | 2024-01-28 | ex-Raptors Esports Club | W   | 0.385      | 0.143        | 0.000 (0.000)    | 0.110 (0.006)    | 0 (0.000) |     4.99 | entz, jeyN, oskvr, Ping, Swaggy    |
|            3 |     7142 | 2024-01-27 | Part Timers             | L   | 0.378      | -            | -                | -                | -         |    -9.15 | entz, jeyN, oskvr, Ping, Swaggy    |
|            2 |     7150 | 2024-01-27 | Shaman Esports          | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     1.98 | entz, jeyN, oskvr, Ping, Swaggy    |
|            1 |     8667 | 2023-12-18 | ex-Anonymo Esports      | L   | 0.111      | -            | -                | -                | -         |    -1.83 | devraNN, Joey, oskvr, Ping, Swaggy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($757.83)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-18 |      0.718 | $954.79        | $685.59         |
| 2024-02-25 |      0.570 | $126.79        | $72.24          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
