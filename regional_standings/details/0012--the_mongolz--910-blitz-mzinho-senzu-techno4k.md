### Roster Details<br />
Team Name: The MongolZ<br />
Roster: 910, bLitz, mzinho, Senzu, Techno4K<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [12](../standings_global.md)<br />
Regional Rank: [1]( ../standings_asia.md)<br />
Final Rank Value:  1586.5<br />
<br />
Final Rank Value (1586.5) = Starting Rank Value (1662.3) + Head To Head Adjustments (-75.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.652[<sup>1</sup>](#table2)
- Bounty Collected: 0.582[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.636<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1662.3
- 400 + ( ( 0.636 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1662.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           69 |      322 | 2024-04-28 | Team Vitality                | L   | 1.000      | -            | -                | -                | -            |    -5.31 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           68 |      490 | 2024-04-25 | G2 Esports                   | W   | 1.000      | 0.889        | 0.866 (0.769)    | 0.477 (0.424)    | true (1.000) |    25.35 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           67 |      546 | 2024-04-24 | Team Falcons                 | W   | 1.000      | 0.889        | 0.431 (0.383)    | 0.161 (0.143)    | true (1.000) |     6.96 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           66 |      837 | 2024-04-19 | Rare Atom                    | W   | 1.000      | -            | -                | -                | -            |     0.86 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           65 |      888 | 2024-04-18 | TYLOO                        | W   | 1.000      | -            | -                | -                | -            |     1.74 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           64 |      902 | 2024-04-18 | Rare Atom                    | W   | 1.000      | -            | -                | -                | -            |     0.67 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           63 |      951 | 2024-04-17 | DEWA United                  | W   | 1.000      | -            | -                | -                | -            |     0.13 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           62 |      955 | 2024-04-17 | DEWA United                  | W   | 1.000      | -            | -                | -                | -            |     0.13 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           61 |     1075 | 2024-04-14 | ATOX Esports                 | W   | 1.000      | -            | -                | -                | true (1.000) |     1.98 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           60 |     1149 | 2024-04-12 | ZEUSGG                       | W   | 1.000      | -            | -                | -                | -            |     0.12 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           59 |     1151 | 2024-04-12 | ZEUSGG                       | W   | 1.000      | -            | -                | -                | -            |     0.12 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           58 |     1235 | 2024-04-10 | ATOX Esports                 | W   | 1.000      | 0.417        | 0.112 (0.047)    | 0.769 (0.321)    | -            |     1.95 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           57 |     1240 | 2024-04-10 | ATOX Esports                 | W   | 1.000      | 0.417        | 0.112 (0.047)    | 0.769 (0.321)    | -            |     1.99 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           56 |     1298 | 2024-04-09 | LYG Gaming                   | W   | 1.000      | 0.417        | -                | 0.380 (0.159)    | -            |     0.58 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           55 |     1301 | 2024-04-09 | LYG Gaming                   | W   | 1.000      | 0.417        | -                | 0.380 (0.159)    | -            |     0.58 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           54 |     1347 | 2024-04-08 | ATOX Esports                 | W   | 1.000      | -            | -                | -                | true (1.000) |     2.28 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           53 |     1431 | 2024-04-05 | Born to Win (Mongolian team) | W   | 1.000      | -            | -                | -                | true (1.000) |     0.08 | 910, kaz, mzinho, Senzu, Techno4K     |
|           52 |     1506 | 2024-04-04 | Nitromethane                 | W   | 0.990      | -            | -                | -                | true (0.990) |     0.05 | 910, kaz, mzinho, Senzu, Techno4K     |
|           51 |     1546 | 2024-04-03 | Lynn Vision Gaming           | W   | 0.984      | -            | -                | -                | -            |     4.59 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           50 |     1561 | 2024-04-03 | LYG Gaming                   | W   | 0.983      | -            | -                | -                | -            |     0.60 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           49 |     1587 | 2024-04-02 | ATOX Esports                 | W   | 0.977      | -            | -                | -                | -            |     2.21 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           48 |     1593 | 2024-04-02 | LYG Gaming                   | L   | 0.976      | -            | -                | -                | -            |   -30.23 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           47 |     1943 | 2024-03-22 | PaiN Gaming                  | L   | 0.904      | -            | -                | -                | -            |   -26.66 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           46 |     1983 | 2024-03-21 | Team Vitality                | L   | 0.898      | -            | -                | -                | -            |    -5.31 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           45 |     1995 | 2024-03-21 | Natus Vincere                | L   | 0.897      | -            | -                | -                | -            |    -3.91 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           44 |     2032 | 2024-03-20 | Legacy                       | W   | 0.890      | 1.000        | 0.061 (0.054)    | 0.262 (0.233)    | true (0.890) |     2.40 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           43 |     2068 | 2024-03-19 | Lynn Vision Gaming           | W   | 0.884      | 1.000        | 0.155 (0.137)    | 0.554 (0.490)    | true (0.884) |     3.76 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           42 |     2100 | 2024-03-18 | AMKAL ESPORTS                | W   | 0.877      | 1.000        | 0.209 (0.184)    | 0.756 (0.663)    | true (0.877) |     2.16 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           41 |     2131 | 2024-03-17 | Gaimin Gladiators            | L   | 0.872      | -            | -                | -                | -            |   -22.65 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           40 |     2151 | 2024-03-17 | Eternal Fire                 | L   | 0.870      | -            | -                | -                | -            |    -7.79 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           39 |     2328 | 2024-03-13 | Born In Far East             | W   | 0.844      | -            | -                | -                | -            |     0.11 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           38 |     2330 | 2024-03-13 | Born In Far East             | W   | 0.844      | -            | -                | -                | -            |     0.11 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           37 |     3010 | 2024-02-27 | Lynn Vision Gaming           | W   | 0.747      | -            | -                | -                | true (0.747) |     2.48 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           36 |     3083 | 2024-02-25 | FlyQuest                     | W   | 0.735      | -            | -                | -                | -            |     5.01 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           35 |     3089 | 2024-02-25 | Myth Avenue Gaming           | W   | 0.734      | -            | -                | -                | -            |     0.03 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           34 |     4036 | 2024-02-02 | ENCE                         | L   | 0.578      | -            | -                | -                | -            |   -11.62 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           33 |     4086 | 2024-02-01 | Team Spirit                  | L   | 0.570      | -            | -                | -                | -            |    -4.73 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           32 |     4107 | 2024-01-31 | FURIA Esports                | W   | 0.565      | 1.000        | 0.384 (0.217)    | 0.361 (0.204)    | -            |     9.63 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           31 |     4229 | 2024-01-28 | Lynn Vision Gaming           | W   | 0.543      | 0.435        | 0.155 (0.037)    | -                | -            |     2.20 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           30 |     4232 | 2024-01-27 | Team NKT                     | W   | 0.542      | -            | -                | -                | -            |     0.17 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           29 |     4283 | 2024-01-27 | TYLOO                        | L   | 0.537      | -            | -                | -                | -            |   -16.23 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           28 |     4332 | 2024-01-26 | TYLOO                        | W   | 0.531      | -            | -                | -                | -            |     0.64 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           27 |     4339 | 2024-01-26 | The Huns Esports             | W   | 0.530      | -            | -                | -                | -            |     0.29 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           26 |     4342 | 2024-01-25 | TYLOO                        | W   | 0.529      | -            | -                | -                | -            |     0.63 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           25 |     4343 | 2024-01-25 | ACME                         | W   | 0.528      | -            | -                | -                | -            |     0.08 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           24 |     4517 | 2024-01-20 | ATOX Esports                 | W   | 0.495      | -            | -                | -                | -            |     0.67 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           23 |     4613 | 2024-01-19 | MungYu Esports               | W   | 0.483      | -            | -                | -                | -            |     0.04 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           22 |     4620 | 2024-01-19 | Team NKT                     | W   | 0.483      | -            | -                | -                | -            |     0.12 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           21 |     5169 | 2024-01-07 | The QUBE Esports             | L   | 0.403      | -            | -                | -                | -            |   -12.59 | 910, bLitz, darkis, hasteka, Techno4K |
|           20 |     5173 | 2024-01-06 | Team mzinho                  | W   | 0.402      | -            | -                | -                | -            |     0.03 | 910, bLitz, darkis, hasteka, Techno4K |
|           19 |     5369 | 2023-12-17 | Virtus.pro                   | L   | 0.264      | -            | -                | -                | -            |    -3.55 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           18 |     5467 | 2023-12-16 | Complexity Gaming            | W   | 0.258      | 0.500        | 0.271 (0.035)    | -                | -            |     2.76 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           17 |     5565 | 2023-12-15 | Apeks                        | L   | 0.253      | -            | -                | -                | -            |    -6.44 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           16 |     5572 | 2023-12-15 | Complexity Gaming            | W   | 0.252      | -            | -                | -                | -            |     2.68 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           15 |     5737 | 2023-12-10 | TYLOO                        | W   | 0.217      | -            | -                | -                | -            |     0.23 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           14 |     5780 | 2023-12-09 | Lynn Vision Gaming           | W   | 0.210      | -            | -                | -                | -            |     0.73 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           13 |     5849 | 2023-12-08 | NewHappy                     | W   | 0.204      | -            | -                | -                | -            |     0.04 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           12 |     5899 | 2023-12-07 | GR Gaming                    | W   | 0.197      | -            | -                | -                | -            |     0.06 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           11 |     5946 | 2023-12-06 | LYG Gaming                   | W   | 0.190      | -            | -                | -                | -            |     0.05 | 910, bLitz, mzinho, Senzu, Techno4K   |
|           10 |     6004 | 2023-12-05 | NewHappy                     | L   | 0.184      | -            | -                | -                | -            |    -5.75 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            9 |     6404 | 2023-11-26 | ATOX Esports                 | W   | 0.123      | -            | -                | -                | -            |     0.16 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            8 |     6409 | 2023-11-26 | The Huns Esports             | W   | 0.123      | -            | -                | -                | -            |     0.06 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            7 |     6453 | 2023-11-24 | ATOX Esports                 | L   | 0.116      | -            | -                | -                | -            |    -3.50 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            6 |     6456 | 2023-11-24 | The Huns Esports             | W   | 0.115      | -            | -                | -                | -            |     0.06 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            5 |     6650 | 2023-11-20 | Octagonal Disposition Gaming | W   | 0.084      | -            | -                | -                | -            |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            4 |     6737 | 2023-11-18 | TYLOO                        | W   | 0.070      | -            | -                | -                | -            |     0.07 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            3 |     6787 | 2023-11-17 | TYLOO                        | W   | 0.064      | -            | -                | -                | -            |     0.06 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            2 |     6794 | 2023-11-16 | NewHappy                     | W   | 0.062      | -            | -                | -                | -            |     0.01 | 910, bLitz, mzinho, Senzu, Techno4K   |
|            1 |     7209 | 2023-11-08 | GR Gaming                    | W   | 0.004      | -            | -                | -                | -            |     0.00 | 910, bLitz, mzinho, Senzu, Techno4K   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($46,256.69)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.29) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $4,347.83      | $4,347.83       |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-02-11 |      0.638 | $4,500.00      | $2,871.04       |
| 2024-01-28 |      0.543 | $25,000.00     | $13,582.18      |
| 2024-01-07 |      0.403 | $584.86        | $235.74         |
| 2023-12-17 |      0.266 | $10,000.00     | $2,661.81       |
| 2023-12-10 |      0.217 | $15,000.00     | $3,253.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
