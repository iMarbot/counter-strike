### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, nettik, TjP<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [100](../standings_global.md)<br />
Regional Rank: [11]( ../standings_asia.md)<br />
Final Rank Value:  864.0<br />
<br />
Final Rank Value (864.0) = Starting Rank Value (844.3) + Head To Head Adjustments (19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.399[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.071[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 844.3
- 400 + ( ( 0.224 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 844.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      394 | 2024-04-26 | MIBR                        | L   | 1.000      | -            | -                | -                | -             |    -0.58 | asap, chelleos, dangeR, nettik, TjP |
|           39 |      447 | 2024-04-26 | KZG                         | W   | 1.000      | 0.500        | 0.020 (0.010)    | 0.249 (0.124)    | true (1.000)  |     8.63 | asap, chelleos, dangeR, nettik, TjP |
|           38 |      453 | 2024-04-25 | Rebels Gaming               | L   | 1.000      | -            | -                | -                | -             |    -5.47 | asap, chelleos, dangeR, nettik, TjP |
|           37 |      783 | 2024-04-19 | Bad News Kangaroos          | L   | 1.000      | -            | -                | -                | -             |   -12.54 | asap, chelleos, dangeR, nettik, TjP |
|           36 |      848 | 2024-04-19 | FlyQuest                    | L   | 1.000      | -            | -                | -                | -             |    -1.50 | asap, chelleos, dangeR, nettik, TjP |
|           35 |      851 | 2024-04-19 | Gen.G Esports               | L   | 1.000      | -            | -                | -                | -             |   -27.82 | asap, chelleos, dangeR, nettik, TjP |
|           34 |      856 | 2024-04-18 | Bad News Kangaroos          | W   | 1.000      | 0.143        | 0.071 (0.010)    | 0.238 (0.034)    | false (0.000) |    17.50 | asap, chelleos, dangeR, nettik, TjP |
|           33 |      910 | 2024-04-17 | Rare Atom                   | L   | 1.000      | -            | -                | -                | -             |   -18.29 | asap, chelleos, dangeR, nettik, TjP |
|           32 |      957 | 2024-04-17 | VexX Gaming                 | W   | 1.000      | 0.143        | 0.010 (0.001)    | 0.390 (0.056)    | false (0.000) |     7.97 | asap, chelleos, dangeR, nettik, TjP |
|           31 |      960 | 2024-04-17 | Canon Event                 | W   | 1.000      | -            | -                | -                | false (0.000) |     1.61 | asap, chelleos, dangeR, nettik, TjP |
|           30 |      978 | 2024-04-17 | Double-Down                 | W   | 1.000      | -            | -                | -                | false (0.000) |     1.86 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1248 | 2024-04-10 | Bad News Kangaroos          | L   | 1.000      | -            | -                | -                | -             |   -14.15 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1254 | 2024-04-10 | Bad News Kangaroos          | W   | 1.000      | 0.333        | 0.071 (0.024)    | 0.238 (0.079)    | false (0.000) |    17.50 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1772 | 2024-03-27 | VexX Gaming                 | W   | 0.937      | 0.333        | 0.010 (0.003)    | 0.390 (0.122)    | false (0.000) |     8.80 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     1776 | 2024-03-27 | VexX Gaming                 | W   | 0.936      | 0.333        | 0.010 (0.003)    | 0.390 (0.122)    | false (0.000) |     9.45 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     3223 | 2024-02-23 | FlyQuest                    | L   | 0.716      | -            | -                | -                | -             |    -1.18 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     3226 | 2024-02-22 | Bad News Kangaroos          | W   | 0.715      | 0.143        | 0.071 (0.007)    | 0.238 (0.024)    | false (0.000) |    14.04 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     3267 | 2024-02-22 | FlyQuest                    | L   | 0.710      | -            | -                | -                | -             |    -1.10 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     3269 | 2024-02-21 | Vantage Esports             | W   | 0.708      | 0.143        | -                | 0.236 (0.024)    | false (0.000) |     4.49 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     3325 | 2024-02-21 | DXA Esports                 | W   | 0.703      | 0.333        | 0.010 (0.002)    | 0.266 (0.062)    | -             |     6.82 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     3328 | 2024-02-21 | DXA Esports                 | W   | 0.703      | 0.333        | 0.010 (0.002)    | 0.266 (0.062)    | -             |     7.19 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     4074 | 2024-02-01 | M80                         | L   | 0.571      | -            | -                | -                | -             |    -1.37 | asap, chelleos, nettik, Rackem, TjP |
|           18 |     4104 | 2024-01-31 | Virtus.pro                  | L   | 0.565      | -            | -                | -                | -             |    -0.12 | asap, chelleos, nettik, Rackem, TjP |
|           17 |     4366 | 2024-01-25 | Mindfreak (Australian team) | W   | 0.522      | -            | -                | -                | -             |     6.09 | asap, chelleos, nettik, Rackem, TjP |
|           16 |     4403 | 2024-01-24 | Blitz (Australian team)     | W   | 0.516      | -            | -                | -                | -             |     2.09 | asap, chelleos, nettik, Rackem, TjP |
|           15 |     4412 | 2024-01-23 | 500x                        | W   | 0.516      | -            | -                | -                | -             |     2.27 | asap, chelleos, nettik, Rackem, TjP |
|           14 |     4447 | 2024-01-22 | Mindfreak (Australian team) | L   | 0.508      | -            | -                | -                | -             |   -10.46 | asap, chelleos, nettik, Rackem, TjP |
|           13 |     4493 | 2024-01-21 | Mindfreak (Australian team) | L   | 0.502      | -            | -                | -                | -             |   -10.74 | asap, chelleos, nettik, Rackem, TjP |
|           12 |     4519 | 2024-01-20 | FlyQuest                    | L   | 0.495      | -            | -                | -                | -             |    -0.77 | asap, chelleos, nettik, Rackem, TjP |
|           11 |     4624 | 2024-01-19 | Mindfreak (Australian team) | W   | 0.482      | -            | -                | -                | -             |     4.86 | asap, chelleos, nettik, Rackem, TjP |
|           10 |     4630 | 2024-01-18 | StevosFirstCS2              | W   | 0.482      | -            | -                | -                | -             |     1.88 | asap, chelleos, nettik, Rackem, TjP |
|            9 |     6283 | 2023-11-28 | MANTRA                      | W   | 0.142      | -            | -                | -                | -             |     0.54 | asap, chelleos, nettik, Rackem, TjP |
|            8 |     6335 | 2023-11-28 | Blingus                     | W   | 0.136      | -            | -                | -                | -             |     0.45 | asap, chelleos, nettik, Rackem, TjP |
|            7 |     6339 | 2023-11-28 | Dracula Flow                | W   | 0.136      | -            | -                | -                | -             |     0.33 | asap, chelleos, nettik, Rackem, TjP |
|            6 |     6612 | 2023-11-20 | Bad News Kangaroos          | L   | 0.089      | -            | -                | -                | -             |    -1.00 | asap, chelleos, nettik, Rackem, TjP |
|            5 |     6656 | 2023-11-19 | FlyQuest                    | L   | 0.082      | -            | -                | -                | -             |    -0.13 | asap, chelleos, nettik, Rackem, TjP |
|            4 |     6687 | 2023-11-18 | Bad News Kangaroos          | W   | 0.075      | 0.314        | 0.071 (0.002)    | -                | -             |     1.52 | asap, chelleos, nettik, Rackem, TjP |
|            3 |     6755 | 2023-11-17 | KZG                         | W   | 0.069      | -            | -                | -                | -             |     0.82 | asap, chelleos, nettik, Rackem, TjP |
|            2 |     7025 | 2023-11-11 | Mindfreak (Australian team) | W   | 0.029      | -            | -                | -                | -             |     0.24 | asap, chelleos, nettik, Rackem, TjP |
|            1 |     7078 | 2023-11-10 | Cobro's Cobros              | W   | 0.021      | -            | -                | -                | -             |     0.05 | asap, chelleos, nettik, Rackem, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,964.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-02-11 |      0.638 | $2,500.00      | $1,595.02       |
| 2023-11-21 |      0.090 | $821.04        | $73.82          |
| 2023-11-18 |      0.075 | $3,256.50      | $243.63         |
| 2023-11-17 |      0.069 | $750.00        | $51.53          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
