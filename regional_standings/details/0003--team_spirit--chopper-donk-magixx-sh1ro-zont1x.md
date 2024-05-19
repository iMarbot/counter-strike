### Roster Details<br />
Team Name: Team Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [3](../standings_global.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
Final Rank Value:  1884.9<br />
<br />
Final Rank Value (1884.9) = Starting Rank Value (1837.8) + Head To Head Adjustments (47.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.747[<sup>2</sup>](#table1)
- Opponent Network: 0.343[<sup>2</sup>](#table1)
- LAN Wins: 0.809[<sup>2</sup>](#table1)

The average of these factors is 0.725<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1837.8
- 400 + ( ( 0.725 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1837.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     1691 | 2024-03-28 | FaZe Clan         | L   | 0.945      | -            | -                | -                | -         |   -12.71 | chopper, donk, magixx, sh1ro, zont1x    |
|           29 |     1939 | 2024-03-22 | Natus Vincere     | W   | 0.905      | 1.000        | 1.000 (0.905)    | 0.406 (0.368)    | 1 (0.905) |    16.14 | chopper, donk, magixx, sh1ro, zont1x    |
|           28 |     1959 | 2024-03-21 | Imperial Esports  | W   | 0.899      | 1.000        | 0.674 (0.606)    | 0.549 (0.493)    | 1 (0.899) |     3.35 | chopper, donk, magixx, sh1ro, zont1x    |
|           27 |     1985 | 2024-03-21 | Cloud9            | W   | 0.898      | 1.000        | 0.487 (0.438)    | 0.419 (0.377)    | 1 (0.898) |     9.13 | chopper, donk, magixx, sh1ro, zont1x    |
|           26 |     2447 | 2024-03-10 | Metizport         | W   | 0.826      | 0.535        | -                | 1.000 (0.442)    | -         |     0.41 | chopper, donk, magixx, sh1ro, zont1x    |
|           25 |     2486 | 2024-03-09 | BIG               | W   | 0.819      | 0.535        | 0.470 (0.206)    | 0.400 (0.175)    | -         |     2.06 | chopper, donk, magixx, sh1ro, zont1x    |
|           24 |     2534 | 2024-03-08 | Elevate           | W   | 0.811      | -            | -                | -                | -         |     0.06 | chopper, donk, magixx, sh1ro, zont1x    |
|           23 |     3302 | 2024-02-21 | HEROIC            | W   | 0.705      | -            | -                | -                | 1 (0.705) |     6.17 | chopper, donk, magixx, sh1ro, zont1x    |
|           22 |     3354 | 2024-02-20 | MOUZ              | L   | 0.698      | -            | -                | -                | -         |   -11.13 | chopper, donk, magixx, sh1ro, zont1x    |
|           21 |     3395 | 2024-02-19 | Astralis          | W   | 0.692      | -            | -                | -                | 1 (0.692) |     2.90 | chopper, donk, magixx, sh1ro, zont1x    |
|           20 |     3426 | 2024-02-19 | ENCE              | W   | 0.690      | -            | -                | -                | 1 (0.690) |     3.14 | chopper, donk, magixx, sh1ro, zont1x    |
|           19 |     3755 | 2024-02-11 | FaZe Clan         | W   | 0.638      | 1.000        | 1.000 (0.638)    | 0.566 (0.361)    | 1 (0.638) |    13.63 | chopper, donk, magixx, sh1ro, zont1x    |
|           18 |     3764 | 2024-02-10 | Team Falcons      | W   | 0.632      | 1.000        | 0.431 (0.273)    | -                | 1 (0.632) |     1.55 | chopper, donk, magixx, sh1ro, zont1x    |
|           17 |     3861 | 2024-02-06 | FaZe Clan         | W   | 0.605      | 1.000        | 1.000 (0.605)    | 0.566 (0.342)    | 1 (0.605) |    13.27 | chopper, donk, magixx, sh1ro, zont1x    |
|           16 |     3923 | 2024-02-04 | Complexity Gaming | W   | 0.591      | 1.000        | 0.271 (0.160)    | -                | 1 (0.591) |     2.70 | chopper, donk, magixx, sh1ro, zont1x    |
|           15 |     3968 | 2024-02-03 | Natus Vincere     | W   | 0.585      | 1.000        | 1.000 (0.585)    | 0.406 (0.238)    | -         |    12.60 | chopper, donk, magixx, sh1ro, zont1x    |
|           14 |     4086 | 2024-02-01 | The MongolZ       | W   | 0.570      | 1.000        | 0.292 (0.167)    | 0.663 (0.378)    | -         |     4.73 | chopper, donk, magixx, sh1ro, zont1x    |
|           13 |     4111 | 2024-01-31 | Apeks             | W   | 0.565      | 1.000        | -                | 0.459 (0.260)    | -         |     1.53 | chopper, donk, magixx, sh1ro, zont1x    |
|           12 |     4358 | 2024-01-25 | FaZe Clan         | L   | 0.524      | -            | -                | -                | -         |    -4.71 | baz, chopper, hally, sh1ro, zont1x      |
|           11 |     4389 | 2024-01-24 | Team Liquid       | L   | 0.517      | -            | -                | -                | -         |   -15.10 | baz, chopper, hally, sh1ro, zont1x      |
|           10 |     4558 | 2024-01-20 | MOUZ              | W   | 0.491      | -            | -                | -                | -         |     8.34 | chopper, donk, magixx, sh1ro, zont1x    |
|            9 |     4610 | 2024-01-19 | Preasy Esport     | W   | 0.484      | -            | -                | -                | -         |     0.13 | chopper, donk, magixx, sh1ro, zont1x    |
|            8 |     4648 | 2024-01-18 | Entropiq          | W   | 0.479      | -            | -                | -                | -         |     0.05 | chopper, donk, magixx, sh1ro, zont1x    |
|            7 |     4671 | 2024-01-18 | KOI               | L   | 0.478      | -            | -                | -                | -         |   -14.86 | chopper, donk, magixx, sh1ro, zont1x    |
|            6 |     5740 | 2023-12-10 | Virtus.pro        | W   | 0.217      | -            | -                | -                | -         |     2.19 | ArtFr0st, chopper, donk, magixx, zont1x |
|            5 |     5774 | 2023-12-09 | MIBR              | W   | 0.210      | -            | -                | -                | -         |     1.83 | ArtFr0st, chopper, donk, magixx, zont1x |
|            4 |     5844 | 2023-12-08 | FURIA Esports     | W   | 0.204      | -            | -                | -                | -         |     1.76 | ArtFr0st, chopper, donk, magixx, zont1x |
|            3 |     5905 | 2023-12-07 | Virtus.pro        | L   | 0.196      | -            | -                | -                | -         |    -4.23 | ArtFr0st, chopper, donk, magixx, zont1x |
|            2 |     5940 | 2023-12-06 | FURIA Esports     | W   | 0.191      | -            | -                | -                | -         |     1.63 | ArtFr0st, chopper, donk, magixx, zont1x |
|            1 |     6780 | 2023-11-17 | MIBR              | W   | 0.064      | -            | -                | -                | -         |     0.54 | ArtFr0st, chopper, donk, magixx, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($356,863.66)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.965 | $45,000.00     | $43,435.42      |
| 2024-03-10 |      0.826 | $20,000.00     | $16,511.57      |
| 2024-02-11 |      0.638 | $400,000.00    | $255,203.70     |
| 2024-01-28 |      0.545 | $5,000.00      | $2,725.46       |
| 2023-12-10 |      0.217 | $180,000.00    | $38,987.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
