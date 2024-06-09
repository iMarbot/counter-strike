### Roster Details<br />
Team Name: AMKAL ESPORTS<br />
Roster: Forester, ICY, Krad, Sdaim, TRAVIS<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [29](../standings_global.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
Final Rank Value:  1270.5<br />
<br />
Final Rank Value (1270.5) = Starting Rank Value (1199.8) + Head To Head Adjustments (70.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.545[<sup>1</sup>](#table2)
- Bounty Collected: 0.529[<sup>2</sup>](#table1)
- Opponent Network: 0.339[<sup>2</sup>](#table1)
- LAN Wins: 0.161[<sup>2</sup>](#table1)

The average of these factors is 0.394<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1199.8
- 400 + ( ( 0.394 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1199.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |      574 | 2024-05-21 | GamerLegion               | L   | 1.000      | -            | -                | -                | -         |   -15.62 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           55 |      762 | 2024-05-19 | paiN Gaming               | W   | 1.000      | 0.769        | 0.463 (0.356)    | 0.547 (0.420)    | 0 (0.000) |    23.29 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           54 |      792 | 2024-05-19 | Team Liquid               | L   | 1.000      | -            | -                | -                | -         |    -3.91 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           53 |      869 | 2024-05-18 | paiN Gaming               | W   | 1.000      | 0.769        | 0.463 (0.356)    | 0.547 (0.420)    | 0 (0.000) |    24.50 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           52 |     1834 | 2024-05-04 | BetBoom Team              | W   | 1.000      | 0.435        | 0.390 (0.169)    | 0.712 (0.309)    | 0 (0.000) |    20.59 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           51 |     1876 | 2024-05-04 | Metizport                 | W   | 1.000      | 0.435        | 0.088 (0.038)    | 0.698 (0.303)    | 0 (0.000) |     9.78 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           50 |     1909 | 2024-05-03 | Gaimin Gladiators         | W   | 1.000      | 0.435        | 0.092 (0.040)    | 0.727 (0.316)    | 0 (0.000) |    14.01 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           49 |     1933 | 2024-05-02 | BLEED Esports             | W   | 1.000      | 0.435        | 0.248 (0.108)    | 0.714 (0.310)    | 0 (0.000) |    16.84 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     2020 | 2024-05-01 | Fnatic                    | L   | 1.000      | -            | -                | -                | -         |   -16.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     2054 | 2024-04-30 | Gaimin Gladiators         | W   | 1.000      | 0.384        | 0.092 (0.035)    | 0.727 (0.279)    | 0 (0.000) |    14.87 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     2110 | 2024-04-29 | Permitta Esports          | W   | 0.996      | 0.384        | -                | 1.000 (0.383)    | -         |     6.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     2437 | 2024-04-24 | Nexus Gaming              | W   | 0.962      | 0.384        | -                | 0.857 (0.317)    | -         |     5.41 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     2558 | 2024-04-21 | Gaimin Gladiators         | L   | 0.943      | -            | -                | -                | -         |   -10.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     2768 | 2024-04-19 | ENCE                      | W   | 0.929      | 0.384        | 0.202 (0.072)    | -                | -         |    22.02 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     2818 | 2024-04-18 | Apeks                     | L   | 0.923      | -            | -                | -                | -         |   -12.67 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     2836 | 2024-04-18 | ex-Guild Eagles           | W   | 0.922      | -            | -                | -                | -         |     7.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     2878 | 2024-04-17 | 5x404                     | W   | 0.918      | -            | -                | -                | -         |     0.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2988 | 2024-04-16 | B8                        | W   | 0.908      | 0.384        | 0.168 (0.059)    | 0.963 (0.336)    | -         |    10.95 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     3137 | 2024-04-12 | Aurora Gaming             | L   | 0.884      | -            | -                | -                | -         |    -5.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     3200 | 2024-04-11 | BetBoom Team              | W   | 0.876      | 0.143        | 0.390 (0.049)    | -                | -         |    21.32 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     3237 | 2024-04-10 | Apeks                     | W   | 0.871      | -            | -                | -                | -         |    17.11 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     3279 | 2024-04-10 | ENTERPRISE esports        | L   | 0.868      | -            | -                | -                | -         |   -20.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     3629 | 2024-04-03 | Insilio                   | W   | 0.824      | -            | -                | -                | -         |     7.45 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     3642 | 2024-04-03 | ex-Guild Eagles           | W   | 0.823      | -            | -                | -                | -         |     6.73 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     3656 | 2024-04-03 | Alliance                  | W   | 0.822      | -            | -                | -                | -         |     5.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     3691 | 2024-04-02 | PARIVISION                | W   | 0.816      | -            | -                | -                | -         |     6.60 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     3692 | 2024-04-02 | ex-Guild Eagles           | L   | 0.816      | -            | -                | -                | -         |   -18.84 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     3704 | 2024-04-02 | ALTERNATE aTTaX           | W   | 0.815      | -            | -                | -                | -         |     6.58 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     3971 | 2024-03-26 | Verdant                   | L   | 0.771      | -            | -                | -                | -         |   -18.50 | Forester, ICY, Krad, TRAVIS, xdENiSZERA |
|           27 |     4322 | 2024-03-18 | The MongolZ               | L   | 0.716      | -            | -                | -                | -         |    -1.93 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           26 |     4350 | 2024-03-17 | Apeks                     | L   | 0.711      | -            | -                | -                | -         |    -8.33 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           25 |     4379 | 2024-03-17 | GamerLegion               | L   | 0.710      | -            | -                | -                | -         |    -8.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           24 |     5084 | 2024-03-05 | FORZE Esports             | L   | 0.631      | -            | -                | -                | -         |   -13.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           23 |     5103 | 2024-03-05 | Zero Tenacity             | W   | 0.631      | -            | -                | -                | -         |     5.72 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           22 |     5134 | 2024-03-04 | 500                       | W   | 0.625      | -            | -                | -                | -         |     2.65 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           21 |     5154 | 2024-03-04 | HyperSpirit               | W   | 0.625      | -            | -                | -                | -         |     1.40 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           20 |     5308 | 2024-03-02 | ILLYRIANS                 | L   | 0.611      | -            | -                | -                | -         |   -17.75 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           19 |     5393 | 2024-03-01 | BIG                       | L   | 0.602      | -            | -                | -                | -         |    -4.54 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           18 |     5472 | 2024-02-28 | Young Ninjas              | L   | 0.590      | -            | -                | -                | -         |   -15.45 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           17 |     6132 | 2024-02-17 | 9Pandas                   | W   | 0.516      | -            | -                | -                | 1 (0.516) |     7.64 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           16 |     6178 | 2024-02-16 | Team Falcons              | W   | 0.509      | -            | -                | -                | 1 (0.509) |    13.63 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     6241 | 2024-02-15 | Fnatic                    | L   | 0.502      | -            | -                | -                | -         |    -9.32 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     6285 | 2024-02-14 | Ninjas in Pyjamas         | W   | 0.497      | -            | -                | -                | 1 (0.497) |     1.28 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     6292 | 2024-02-14 | ENTERPRISE esports        | L   | 0.496      | -            | -                | -                | -         |   -12.12 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     6463 | 2024-02-10 | Sashi Esport              | L   | 0.470      | -            | -                | -                | -         |   -10.49 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     6481 | 2024-02-09 | Nemiga Gaming             | L   | 0.464      | -            | -                | -                | -         |    -6.67 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     6511 | 2024-02-08 | RUBY                      | W   | 0.458      | -            | -                | -                | -         |     2.53 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     6526 | 2024-02-08 | Insilio                   | W   | 0.457      | -            | -                | -                | -         |     2.63 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     7652 | 2024-01-19 | Astralis                  | W   | 0.324      | -            | -                | -                | -         |     9.47 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     7719 | 2024-01-18 | KOI                       | W   | 0.317      | -            | -                | -                | -         |     2.13 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     7734 | 2024-01-18 | ex-sYnck                  | W   | 0.317      | -            | -                | -                | -         |     0.74 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     7741 | 2024-01-18 | Insilio                   | W   | 0.316      | -            | -                | -                | -         |     1.66 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     7760 | 2024-01-17 | FreeESPI                  | W   | 0.312      | -            | -                | -                | -         |     0.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     7769 | 2024-01-17 | RUBY                      | W   | 0.312      | -            | -                | -                | -         |     1.52 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     7782 | 2024-01-17 | ex-Turów Zgorzelec Esport | W   | 0.311      | -            | -                | -                | -         |     0.86 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     7792 | 2024-01-17 | Looking4org               | W   | 0.311      | -            | -                | -                | -         |     0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($44,038.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.15) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-05-04 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-05-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
