### Roster Details<br />
Team Name: TIMACETA<br />
Roster: beg0d, bnc, cerolzin, farias, leleo<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [224](../standings_global.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
Final Rank Value:  688.5<br />
<br />
Final Rank Value (688.5) = Starting Rank Value (655.1) + Head To Head Adjustments (33.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.1
- 400 + ( ( 0.129 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 655.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     4500 | 2024-01-21 | Flamengo Esports               | L   | 0.498      | -            | -                | -                | -             |   -10.30 | beg0d, bnc, cerolzin, farias, leleo          |
|           26 |     4586 | 2024-01-19 | MIBR                           | L   | 0.487      | -            | -                | -                | -             |    -0.08 | beg0d, bnc, cerolzin, farias, leleo          |
|           25 |     4589 | 2024-01-19 | Sharks Esports                 | W   | 0.487      | 0.143        | 0.063 (0.004)    | 0.343 (0.024)    | false (0.000) |    11.79 | beg0d, bnc, cerolzin, farias, leleo          |
|           24 |     4828 | 2024-01-15 | BESTIA                         | W   | 0.460      | 0.143        | 0.026 (0.002)    | 0.423 (0.028)    | false (0.000) |     9.84 | beg0d, bnc, cerolzin, farias, leleo          |
|           23 |     4985 | 2024-01-11 | KRÜ Esports                    | W   | 0.433      | 0.143        | 0.006 (0.000)    | 0.182 (0.011)    | false (0.000) |     7.49 | beg0d, bnc, cerolzin, farias, leleo          |
|           22 |     4993 | 2024-01-11 | NIGERIA 96                     | W   | 0.432      | 0.143        | 0.002 (0.000)    | 0.095 (0.006)    | false (0.000) |     6.20 | beg0d, bnc, cerolzin, farias, leleo          |
|           21 |     5030 | 2024-01-10 | VISH!                          | W   | 0.427      | -            | -                | -                | false (0.000) |     2.52 | beg0d, bnc, cerolzin, farias, leleo          |
|           20 |     5077 | 2024-01-09 | Patins da Ferrari              | L   | 0.419      | -            | -                | -                | -             |    -7.48 | beg0d, bnc, cerolzin, farias, leleo          |
|           19 |     5145 | 2024-01-08 | VELOX Argentina                | W   | 0.414      | 0.143        | 0.002 (0.000)    | 0.030 (0.002)    | false (0.000) |     6.01 | beg0d, bnc, cerolzin, farias, leleo          |
|           18 |     5301 | 2023-12-20 | Sharks Youngsters              | L   | 0.286      | -            | -                | -                | -             |    -4.18 | beg0d, bnc, cerolzin, farias, leleo          |
|           17 |     5311 | 2023-12-19 | Intense Game                   | W   | 0.279      | 0.143        | 0.008 (0.000)    | 0.372 (0.015)    | false (0.000) |     5.05 | beg0d, bnc, cerolzin, farias, leleo          |
|           16 |     5340 | 2023-12-17 | Arena Jogue Fácil Esports      | W   | 0.266      | 0.143        | 0.002 (0.000)    | 0.125 (0.005)    | false (0.000) |     4.42 | beg0d, bnc, cerolzin, farias, leleo          |
|           15 |     5581 | 2023-12-15 | Myth e-Sports                  | W   | 0.252      | 0.143        | 0.000 (0.000)    | 0.070 (0.003)    | false (0.000) |     3.69 | beg0d, bnc, cerolzin, farias, leleo          |
|           14 |     5605 | 2023-12-14 | Case Esports                   | L   | 0.246      | -            | -                | -                | -             |    -3.16 | beg0d, bnc, cerolzin, farias, leleo          |
|           13 |     5614 | 2023-12-14 | Intense Game                   | W   | 0.245      | 0.143        | 0.008 (0.000)    | 0.372 (0.013)    | false (0.000) |     4.49 | beg0d, bnc, cerolzin, farias, leleo          |
|           12 |     5631 | 2023-12-13 | SOLOVE                         | W   | 0.240      | 0.262        | 0.000 (0.000)    | 0.054 (0.003)    | -             |     3.51 | beg0d, bnc, cerolzin, farias, leleo          |
|           11 |     5648 | 2023-12-13 | Sharks Youngsters              | L   | 0.238      | -            | -                | -                | -             |    -3.45 | beg0d, bnc, cerolzin, farias, leleo          |
|           10 |     6010 | 2023-12-04 | Intense Game                   | W   | 0.180      | -            | -                | -                | -             |     2.30 | beg0d, bnc, cerolzin, farias, leleo          |
|            9 |     6187 | 2023-11-30 | CEBOLOS                        | L   | 0.153      | -            | -                | -                | -             |    -2.77 | heartless, ph1, pooldolsk, rainny, zock9     |
|            8 |     6199 | 2023-11-30 | Hype E-Sports (Brazilian team) | W   | 0.152      | -            | -                | -                | -             |     1.95 | hazart, mid1, MITHPUTTINI, neozix, spinnie   |
|            7 |     6257 | 2023-11-29 | Intense Game                   | L   | 0.145      | -            | -                | -                | -             |    -2.74 | bsd, ckzao, lealziNho, Roz, suNday           |
|            6 |     6688 | 2023-11-18 | AdalYamigos                    | L   | 0.074      | -            | -                | -                | -             |    -0.89 | bnc, farias, leleo, nyezin, will1ZERA        |
|            5 |     6692 | 2023-11-18 | Sharks Youngsters              | L   | 0.073      | -            | -                | -                | -             |    -1.09 | kenznk, ksloks, lukiz, pepe, yangue          |
|            4 |     6693 | 2023-11-18 | PROJEL INCLUSIVA               | W   | 0.073      | -            | -                | -                | -             |     0.65 | dist, dokka, hemp, rph, sing                 |
|            3 |     7028 | 2023-11-11 | 9z Academy                     | L   | 0.027      | -            | -                | -                | -             |    -0.42 | divine, MaxOff, perez, slashzz, Tomate       |
|            2 |     7039 | 2023-11-11 | Galorys                        | L   | 0.027      | -            | -                | -                | -             |    -0.19 | detr0ittJ, koala, ninjaZ, voltera, xns       |
|            1 |     7043 | 2023-11-11 | Storm Gaming                   | W   | 0.027      | -            | -                | -                | -             |     0.23 | cyrexx, eldre, jvz, Kauazinhow, torvi killua |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($236.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-20 |      0.286 | $513.53        | $147.12         |
| 2023-12-04 |      0.180 | $404.47        | $72.67          |
| 2023-11-18 |      0.074 | $163.75        | $12.12          |
| 2023-11-11 |      0.027 | $160.72        | $4.38           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
