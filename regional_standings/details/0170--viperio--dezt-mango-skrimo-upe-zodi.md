### Roster Details<br />
Team Name: Viperio<br />
Roster: dezt, mAnGo, Skrimo, upE, zodi<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [170](../standings_global.md)<br />
Regional Rank: [118]( ../standings_europe.md)<br />
Final Rank Value:  763.2<br />
<br />
Final Rank Value (763.2) = Starting Rank Value (726.5) + Head To Head Adjustments (36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.285[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.102[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 726.5
- 400 + ( ( 0.161 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 726.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      874 | 2024-05-18 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |    -9.33 | dezt, mAnGo, Skrimo, upE, zodi       |
|           23 |      890 | 2024-05-18 | Raptors Esports Club      | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.406 (0.058)    | 0 (0.000) |    17.18 | dezt, mAnGo, Skrimo, upE, zodi       |
|           22 |     1197 | 2024-05-15 | Tropic                    | L   | 1.000      | -            | -                | -                | -         |   -24.85 | dezt, mAnGo, Skrimo, upE, zodi       |
|           21 |     1486 | 2024-05-11 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -14.26 | dezt, mAnGo, Skrimo, upE, zodi       |
|           20 |     1588 | 2024-05-09 | DMS                       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.754 (0.108)    | 0 (0.000) |    19.16 | dezt, mAnGo, Skrimo, upE, zodi       |
|           19 |     1595 | 2024-05-09 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |    -6.72 | dezt, mAnGo, Skrimo, upE, zodi       |
|           18 |     1673 | 2024-05-08 | MASONIC                   | W   | 1.000      | 0.143        | 0.018 (0.003)    | -                | 0 (0.000) |    19.76 | dezt, mAnGo, Skrimo, upE, zodi       |
|           17 |     1713 | 2024-05-07 | NOM Esports               | W   | 1.000      | 0.333        | -                | 0.360 (0.120)    | 0 (0.000) |    13.50 | dezt, mAnGo, Skrimo, upE, zodi       |
|           16 |     1719 | 2024-05-07 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -14.80 | dezt, mAnGo, Skrimo, upE, zodi       |
|           15 |     1762 | 2024-05-06 | Dynamo Eclot              | L   | 1.000      | -            | -                | -                | -         |    -7.65 | dezt, mAnGo, Skrimo, upE, zodi       |
|           14 |     2235 | 2024-04-27 | V1dar Gaming              | L   | 0.982      | -            | -                | -                | -         |   -17.20 | dezt, mAnGo, Skrimo, upE, zodi       |
|           13 |     2452 | 2024-04-23 | GamerLegion Academy       | W   | 0.957      | 0.143        | 0.018 (0.002)    | 0.691 (0.095)    | 0 (0.000) |    17.12 | dezt, mAnGo, Skrimo, upE, zodi       |
|           12 |     2509 | 2024-04-22 | LEON Esports              | W   | 0.950      | 0.143        | 0.001 (0.000)    | 0.564 (0.076)    | 0 (0.000) |    13.32 | dezt, mAnGo, Skrimo, upE, zodi       |
|           11 |     2692 | 2024-04-20 | Illuminar Gaming          | L   | 0.935      | -            | -                | -                | -         |   -11.96 | dezt, mAnGo, Skrimo, upE, zodi       |
|           10 |     2788 | 2024-04-19 | ENCE Academy              | W   | 0.928      | 0.143        | 0.012 (0.002)    | 0.337 (0.045)    | 0 (0.000) |    17.21 | mAnGo, pandi7o, Skrimo, upE, zodi    |
|            9 |     2939 | 2024-04-17 | UNiTY esports             | L   | 0.914      | -            | -                | -                | -         |    -8.99 | mAnGo, pandi7o, ReegaN, Skrimo, zodi |
|            8 |     2984 | 2024-04-16 | Johnny Speeds             | L   | 0.909      | -            | -                | -                | -         |    -5.42 | mAnGo, pandi7o, ReegaN, Skrimo, zodi |
|            7 |     2991 | 2024-04-16 | Lazer Cats                | W   | 0.908      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |    12.05 | dezt, mAnGo, pandi7o, Skrimo, zodi   |
|            6 |     3027 | 2024-04-15 | ENCE Academy              | L   | 0.902      | -            | -                | -                | -         |   -11.91 | dezt, mAnGo, pandi7o, Skrimo, zodi   |
|            5 |     3061 | 2024-04-14 | Illuminar Gaming          | W   | 0.894      | 0.333        | 0.004 (0.001)    | 0.403 (0.120)    | 0 (0.000) |    16.72 | mAnGo, pandi7o, Skrimo, upE, zodi    |
|            4 |     3203 | 2024-04-11 | ex-K10                    | W   | 0.875      | 0.333        | 0.005 (0.002)    | 0.517 (0.151)    | 0 (0.000) |    17.13 | mAnGo, pandi7o, Skrimo, upE, zodi    |
|            3 |     3288 | 2024-04-10 | NOM Esports               | W   | 0.868      | 0.333        | -                | 0.360 (0.104)    | -         |    10.91 | mAnGo, ReegaN, Skrimo, upE, zodi     |
|            2 |     3436 | 2024-04-07 | ex-Turów Zgorzelec Esport | W   | 0.849      | 0.333        | 0.006 (0.002)    | 0.491 (0.139)    | -         |    15.54 | mAnGo, pandi7o, ReegaN, Skrimo, zodi |
|            1 |     3655 | 2024-04-03 | NOM Esports               | L   | 0.822      | -            | -                | -                | -         |   -19.78 | mAnGo, pandi7o, ReegaN, upE, zodi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($921.67)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
