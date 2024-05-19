### Roster Details<br />
Team Name: Bad News Kangaroos<br />
Roster: ADDICT, BRACE, damyo, HaZR, pz<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [65](../standings_global.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
Final Rank Value:  941.4<br />
<br />
Final Rank Value (941.4) = Starting Rank Value (953.3) + Head To Head Adjustments (-11.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.465[<sup>1</sup>](#table2)
- Bounty Collected: 0.285[<sup>2</sup>](#table1)
- Opponent Network: 0.067[<sup>2</sup>](#table1)
- LAN Wins: 0.298[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 953.3
- 400 + ( ( 0.279 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 953.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      110 | 2024-05-03 | FURIA Esports               | L   | 1.000      | -            | -                | -                | -             |    -1.70 | ADDICT, BRACE, damyo, HaZR, pz              |
|           33 |      206 | 2024-05-01 | ENCE                        | L   | 1.000      | -            | -                | -                | -             |    -2.26 | ADDICT, BRACE, damyo, HaZR, pz              |
|           32 |      251 | 2024-04-30 | MOUZ                        | L   | 1.000      | -            | -                | -                | -             |    -0.17 | ADDICT, BRACE, damyo, HaZR, pz              |
|           31 |      769 | 2024-04-20 | FlyQuest                    | L   | 1.000      | -            | -                | -                | -             |    -2.17 | ADDICT, BRACE, damyo, HaZR, pz              |
|           30 |      783 | 2024-04-19 | Rooster                     | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.312 (0.045)    | false (0.000) |    12.54 | ADDICT, BRACE, damyo, HaZR, pz              |
|           29 |      847 | 2024-04-19 | Mindfreak (Australian team) | W   | 1.000      | 0.143        | -                | 0.299 (0.043)    | false (0.000) |     9.49 | ADDICT, BRACE, damyo, HaZR, pz              |
|           28 |      856 | 2024-04-18 | Rooster                     | L   | 1.000      | -            | -                | -                | -             |   -17.50 | ADDICT, BRACE, damyo, HaZR, pz              |
|           27 |     1248 | 2024-04-10 | Rooster                     | W   | 1.000      | 0.333        | 0.031 (0.010)    | 0.312 (0.104)    | false (0.000) |    14.15 | ADDICT, BRACE, damyo, HaZR, pz              |
|           26 |     1254 | 2024-04-10 | Rooster                     | L   | 1.000      | -            | -                | -                | -             |   -17.50 | ADDICT, BRACE, damyo, HaZR, pz              |
|           25 |     1554 | 2024-04-03 | DXA Esports                 | W   | 0.983      | 0.333        | 0.010 (0.003)    | 0.266 (0.087)    | false (0.000) |     6.15 | ADDICT, BRACE, damyo, HaZR, pz              |
|           24 |     1558 | 2024-04-03 | DXA Esports                 | W   | 0.983      | 0.333        | 0.010 (0.003)    | 0.266 (0.087)    | false (0.000) |     6.50 | ADDICT, BRACE, damyo, HaZR, pz              |
|           23 |     1773 | 2024-03-27 | Mindfreak (Australian team) | L   | 0.937      | -            | -                | -                | -             |   -23.29 | ADDICT, BRACE, damyo, HaZR, pz              |
|           22 |     1774 | 2024-03-27 | Mindfreak (Australian team) | W   | 0.936      | 0.333        | 0.001 (0.000)    | 0.299 (0.093)    | false (0.000) |     5.81 | ADDICT, BRACE, damyo, HaZR, pz              |
|           21 |     1922 | 2024-03-23 | DXA Esports                 | W   | 0.909      | 0.143        | 0.010 (0.001)    | -                | true (0.909)  |     5.90 | ADDICT, BRACE, damyo, HaZR, pz              |
|           20 |     1925 | 2024-03-23 | VexX Gaming                 | W   | 0.909      | 0.143        | 0.010 (0.001)    | 0.390 (0.051)    | true (0.909)  |     7.80 | ADDICT, BRACE, damyo, HaZR, pz              |
|           19 |     2036 | 2024-03-20 | Canon Event                 | W   | 0.889      | -            | -                | -                | false (0.000) |     1.24 | ADDICT, BRACE, damyo, HaZR, pz              |
|           18 |     2037 | 2024-03-20 | Canon Event                 | W   | 0.889      | -            | -                | -                | -             |     1.26 | ADDICT, BRACE, damyo, HaZR, pz              |
|           17 |     2188 | 2024-03-15 | Gods Reign                  | L   | 0.862      | -            | -                | -                | -             |   -16.75 | ADDICT, HaZR, pz, Valiance, yourwombat      |
|           16 |     2237 | 2024-03-14 | Garuda Wisnu Voyage         | W   | 0.855      | 0.435        | 0.014 (0.005)    | -                | true (0.855)  |     2.72 | ADDICT, HaZR, pz, Valiance, yourwombat      |
|           15 |     2289 | 2024-03-14 | Aurora Gaming               | L   | 0.849      | -            | -                | -                | -             |    -1.14 | ADDICT, HaZR, pz, Valiance, yourwombat      |
|           14 |     2651 | 2024-03-06 | Vantage Esports             | W   | 0.797      | 0.333        | -                | 0.236 (0.063)    | -             |     3.13 | ADDICT, BRACE, damyo, HaZR, pz              |
|           13 |     2654 | 2024-03-06 | Vantage Esports             | W   | 0.796      | 0.333        | -                | 0.236 (0.063)    | -             |     3.22 | ADDICT, BRACE, damyo, HaZR, pz              |
|           12 |     3226 | 2024-02-22 | Rooster                     | L   | 0.715      | -            | -                | -                | -             |   -14.04 | ADDICT, BRACE, Hatz, HaZR, pz               |
|           11 |     3266 | 2024-02-22 | Vantage Esports             | W   | 0.710      | -            | -                | -                | -             |     2.76 | ADDICT, BRACE, Hatz, HaZR, pz               |
|           10 |     3270 | 2024-02-21 | FlyQuest                    | L   | 0.708      | -            | -                | -                | -             |    -1.84 | ADDICT, BRACE, Hatz, HaZR, pz               |
|            9 |     3740 | 2024-02-11 | Mindfreak (Australian team) | W   | 0.642      | -            | -                | -                | -             |     4.05 | ADDICT, Hatz, HaZR, pz, Valiance            |
|            8 |     3762 | 2024-02-11 | VexX Gaming                 | W   | 0.636      | 0.143        | 0.010 (0.001)    | 0.390 (0.035)    | -             |     3.93 | ADDICT, Hatz, HaZR, pz, Valiance            |
|            7 |     5515 | 2023-12-16 | The Art of War              | W   | 0.256      | -            | -                | -                | -             |     0.65 | AnGod, rekonz, SkulL, sunshinez, viridian   |
|            6 |     6087 | 2023-12-02 | Zero Tenacity               | L   | 0.166      | -            | -                | -                | -             |    -2.48 | ADDICT, BRACE, HaZR, pz, Valiance           |
|            5 |     6170 | 2023-12-01 | Guild Eagles                | L   | 0.156      | -            | -                | -                | -             |    -1.93 | ADDICT, BRACE, HaZR, pz, Valiance           |
|            4 |     6608 | 2023-11-21 | FlyQuest                    | L   | 0.090      | -            | -                | -                | -             |    -0.24 | ADDICT, BRACE, HaZR, pz, Valiance           |
|            3 |     6612 | 2023-11-20 | Rooster                     | W   | 0.089      | 0.143        | 0.031 (0.000)    | -                | -             |     1.00 | ADDICT, BRACE, HaZR, pz, Valiance           |
|            2 |     6652 | 2023-11-20 | Vantage Esports             | W   | 0.083      | -            | -                | -                | -             |     0.32 | Kobe, KRAXYT, Mingovi, N1ghtraid, Omichella |
|            1 |     6687 | 2023-11-18 | Rooster                     | L   | 0.075      | -            | -                | -                | -             |    -1.52 | ADDICT, BRACE, HaZR, pz, Valiance           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,236.98)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $3,500.00      | $3,500.00       |
| 2024-03-23 |      0.909 | $3,257.96      | $2,963.01       |
| 2024-03-16 |      0.864 | $5,000.00      | $4,317.82       |
| 2023-12-16 |      0.256 | $750.00        | $191.86         |
| 2023-11-21 |      0.090 | $1,313.66      | $118.11         |
| 2023-11-18 |      0.075 | $1,953.90      | $146.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
