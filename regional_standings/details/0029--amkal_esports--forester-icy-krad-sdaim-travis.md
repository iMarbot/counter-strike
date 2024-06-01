### Roster Details<br />
Team Name: AMKAL ESPORTS<br />
Roster: Forester, ICY, Krad, Sdaim, TRAVIS<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [29](../standings_global.md)<br />
Regional Rank: [19]( ../standings_europe.md)<br />
Final Rank Value:  1269.8<br />
<br />
Final Rank Value (1269.8) = Starting Rank Value (1197.0) + Head To Head Adjustments (72.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.545[<sup>1</sup>](#table2)
- Bounty Collected: 0.529[<sup>2</sup>](#table1)
- Opponent Network: 0.331[<sup>2</sup>](#table1)
- LAN Wins: 0.161[<sup>2</sup>](#table1)

The average of these factors is 0.392<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1197.0
- 400 + ( ( 0.392 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1197.0


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
|           56 |      563 | 2024-05-21 | GamerLegion               | L   | 1.000      | -            | -                | -                | -         |   -15.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           55 |      750 | 2024-05-19 | paiN Gaming               | W   | 1.000      | 0.769        | 0.463 (0.356)    | 0.524 (0.403)    | 0 (0.000) |    23.37 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           54 |      780 | 2024-05-19 | Team Liquid               | L   | 1.000      | -            | -                | -                | -         |    -3.84 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           53 |      857 | 2024-05-18 | paiN Gaming               | W   | 1.000      | 0.769        | 0.463 (0.356)    | 0.524 (0.403)    | 0 (0.000) |    24.58 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           52 |     1811 | 2024-05-04 | BetBoom Team              | W   | 1.000      | 0.435        | 0.390 (0.169)    | 0.712 (0.309)    | 0 (0.000) |    20.68 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           51 |     1853 | 2024-05-04 | Metizport                 | W   | 1.000      | 0.435        | 0.088 (0.038)    | 0.698 (0.303)    | 0 (0.000) |    10.04 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           50 |     1884 | 2024-05-03 | Gaimin Gladiators         | W   | 1.000      | 0.435        | 0.092 (0.040)    | 0.711 (0.309)    | 0 (0.000) |    13.91 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           49 |     1907 | 2024-05-02 | BLEED Esports             | W   | 1.000      | 0.435        | 0.248 (0.108)    | 0.677 (0.294)    | 0 (0.000) |    16.98 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |     1990 | 2024-05-01 | Fnatic                    | L   | 1.000      | -            | -                | -                | -         |   -16.14 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |     2023 | 2024-04-30 | Gaimin Gladiators         | W   | 1.000      | 0.384        | 0.092 (0.035)    | 0.711 (0.273)    | 0 (0.000) |    14.77 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |     2075 | 2024-04-29 | Permitta Esports          | W   | 0.996      | 0.384        | -                | 1.000 (0.383)    | -         |     6.13 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |     2392 | 2024-04-24 | Nexus Gaming              | W   | 0.962      | 0.384        | -                | 0.825 (0.305)    | -         |     5.31 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |     2505 | 2024-04-21 | Gaimin Gladiators         | L   | 0.943      | -            | -                | -                | -         |   -10.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |     2712 | 2024-04-19 | ENCE                      | W   | 0.929      | 0.384        | 0.202 (0.072)    | -                | -         |    21.99 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |     2762 | 2024-04-18 | Apeks                     | L   | 0.923      | -            | -                | -                | -         |   -12.53 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |     2780 | 2024-04-18 | ex-Guild Eagles           | W   | 0.922      | -            | -                | -                | -         |     7.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |     2821 | 2024-04-17 | 5x404                     | W   | 0.918      | -            | -                | -                | -         |     0.64 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |     2927 | 2024-04-16 | B8                        | W   | 0.908      | 0.384        | 0.168 (0.059)    | 0.952 (0.332)    | -         |    11.79 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |     3071 | 2024-04-12 | Aurora Gaming             | L   | 0.884      | -            | -                | -                | -         |    -5.05 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     3130 | 2024-04-11 | BetBoom Team              | W   | 0.876      | 0.143        | 0.390 (0.049)    | -                | -         |    21.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     3165 | 2024-04-10 | Apeks                     | W   | 0.871      | -            | -                | -                | -         |    17.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     3202 | 2024-04-10 | ENTERPRISE esports        | L   | 0.868      | -            | -                | -                | -         |   -21.88 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     3542 | 2024-04-03 | Insilio                   | W   | 0.824      | -            | -                | -                | -         |     7.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     3555 | 2024-04-03 | ex-Guild Eagles           | W   | 0.823      | -            | -                | -                | -         |     6.61 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     3569 | 2024-04-03 | Alliance                  | W   | 0.822      | -            | -                | -                | -         |     5.21 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     3601 | 2024-04-02 | PARIVISION                | W   | 0.816      | -            | -                | -                | -         |     6.87 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     3602 | 2024-04-02 | ex-Guild Eagles           | L   | 0.816      | -            | -                | -                | -         |   -18.96 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     3614 | 2024-04-02 | ALTERNATE aTTaX           | W   | 0.815      | -            | -                | -                | -         |     6.56 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     3874 | 2024-03-26 | Verdant                   | L   | 0.771      | -            | -                | -                | -         |   -18.56 | Forester, ICY, Krad, TRAVIS, xdENiSZERA |
|           27 |     4217 | 2024-03-18 | The MongolZ               | L   | 0.716      | -            | -                | -                | -         |    -1.90 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           26 |     4245 | 2024-03-17 | Apeks                     | L   | 0.711      | -            | -                | -                | -         |    -8.22 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           25 |     4274 | 2024-03-17 | GamerLegion               | L   | 0.710      | -            | -                | -                | -         |    -8.39 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           24 |     4944 | 2024-03-05 | FORZE Esports             | L   | 0.631      | -            | -                | -                | -         |   -13.10 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           23 |     4960 | 2024-03-05 | Zero Tenacity             | W   | 0.631      | -            | -                | -                | -         |     6.08 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           22 |     4988 | 2024-03-04 | 500                       | W   | 0.625      | -            | -                | -                | -         |     2.61 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           21 |     5008 | 2024-03-04 | HyperSpirit               | W   | 0.625      | -            | -                | -                | -         |     1.43 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           20 |     5160 | 2024-03-02 | ILLYRIANS                 | L   | 0.611      | -            | -                | -                | -         |   -17.74 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           19 |     5244 | 2024-03-01 | BIG                       | L   | 0.602      | -            | -                | -                | -         |    -4.30 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           18 |     5321 | 2024-02-28 | Young Ninjas              | L   | 0.590      | -            | -                | -                | -         |   -15.40 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           17 |     5959 | 2024-02-17 | 9Pandas                   | W   | 0.516      | -            | -                | -                | 1 (0.516) |     7.47 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           16 |     6002 | 2024-02-16 | Team Falcons              | W   | 0.509      | -            | -                | -                | 1 (0.509) |    13.67 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     6060 | 2024-02-15 | Fnatic                    | L   | 0.502      | -            | -                | -                | -         |    -9.29 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     6104 | 2024-02-14 | Ninjas in Pyjamas         | W   | 0.497      | -            | -                | -                | 1 (0.497) |     1.32 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     6111 | 2024-02-14 | ENTERPRISE esports        | L   | 0.496      | -            | -                | -                | -         |   -12.47 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     6275 | 2024-02-10 | Sashi Esport              | L   | 0.470      | -            | -                | -                | -         |   -10.37 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     6293 | 2024-02-09 | Nemiga Gaming             | L   | 0.464      | -            | -                | -                | -         |    -6.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     6323 | 2024-02-08 | RUBY                      | W   | 0.458      | -            | -                | -                | -         |     2.54 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     6338 | 2024-02-08 | Insilio                   | W   | 0.457      | -            | -                | -                | -         |     2.69 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     7406 | 2024-01-19 | Astralis                  | W   | 0.324      | -            | -                | -                | -         |     9.50 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     7471 | 2024-01-18 | KOI                       | W   | 0.317      | -            | -                | -                | -         |     2.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     7485 | 2024-01-18 | ex-sYnck                  | W   | 0.317      | -            | -                | -                | -         |     0.64 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     7492 | 2024-01-18 | Insilio                   | W   | 0.316      | -            | -                | -                | -         |     1.73 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     7511 | 2024-01-17 | FreeESPI                  | W   | 0.312      | -            | -                | -                | -         |     0.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     7520 | 2024-01-17 | RUBY                      | W   | 0.312      | -            | -                | -                | -         |     1.61 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     7533 | 2024-01-17 | ex-Turów Zgorzelec Esport | W   | 0.311      | -            | -                | -                | -         |     0.78 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     7543 | 2024-01-17 | Looking4org               | W   | 0.311      | -            | -                | -                | -         |     0.17 | Forester, ICY, Krad, NickelBack, TRAVIS |

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
