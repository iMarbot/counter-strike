### Roster Details<br />
Team Name: AMKAL ESPORTS<br />
Roster: Forester, ICY, Krad, Sdaim, TRAVIS<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [31](../standings_global.md)<br />
Regional Rank: [23]( ../standings_europe.md)<br />
Final Rank Value:  1268.0<br />
<br />
Final Rank Value (1268.0) = Starting Rank Value (1217.3) + Head To Head Adjustments (50.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.595[<sup>1</sup>](#table2)
- Bounty Collected: 0.495[<sup>2</sup>](#table1)
- Opponent Network: 0.334[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.412<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1217.3
- 400 + ( ( 0.412 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1217.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |       52 | 2024-05-04 | BetBoom Team                  | W   | 1.000      | 0.435        | 0.571 (0.248)    | 0.824 (0.358)    | false (0.000) |    21.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           49 |       85 | 2024-05-04 | Metizport                     | W   | 1.000      | 0.435        | 0.188 (0.082)    | 1.000 (0.435)    | false (0.000) |     9.75 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           48 |      112 | 2024-05-03 | Gaimin Gladiators             | W   | 1.000      | 0.435        | 0.194 (0.084)    | 0.989 (0.430)    | false (0.000) |    16.15 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           47 |      134 | 2024-05-02 | BLEED Esports                 | W   | 1.000      | 0.435        | 0.284 (0.123)    | 0.644 (0.280)    | false (0.000) |    13.47 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           46 |      208 | 2024-05-01 | Fnatic                        | L   | 1.000      | -            | -                | -                | -             |   -14.51 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           45 |      236 | 2024-04-30 | Gaimin Gladiators             | W   | 1.000      | 0.384        | 0.194 (0.075)    | 0.989 (0.380)    | false (0.000) |    17.27 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           44 |      283 | 2024-04-29 | Permitta Esports              | W   | 1.000      | 0.384        | -                | 1.000 (0.384)    | false (0.000) |     5.00 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           43 |      550 | 2024-04-24 | Nexus Gaming                  | W   | 1.000      | 0.384        | -                | 0.772 (0.297)    | false (0.000) |     4.86 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           42 |      649 | 2024-04-21 | Gaimin Gladiators             | L   | 1.000      | -            | -                | -                | -             |    -8.36 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           41 |      833 | 2024-04-19 | ENCE                          | W   | 1.000      | 0.384        | 0.377 (0.145)    | -                | -             |    24.92 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           40 |      878 | 2024-04-18 | Apeks                         | L   | 1.000      | -            | -                | -                | -             |   -10.54 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           39 |      892 | 2024-04-18 | Guild Eagles                  | W   | 1.000      | -            | -                | -                | -             |     9.16 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           38 |      928 | 2024-04-17 | 5x404                         | W   | 1.000      | -            | -                | -                | -             |     0.40 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           37 |     1022 | 2024-04-16 | B8                            | W   | 1.000      | 0.384        | -                | 0.589 (0.226)    | -             |     8.57 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           36 |     1135 | 2024-04-12 | Aurora Gaming                 | L   | 1.000      | -            | -                | -                | -             |    -4.34 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           35 |     1186 | 2024-04-11 | BetBoom Team                  | W   | 1.000      | 0.143        | 0.571 (0.082)    | -                | -             |    25.46 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           34 |     1214 | 2024-04-10 | Apeks                         | W   | 1.000      | 0.143        | 0.253 (0.036)    | -                | -             |    23.04 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           33 |     1250 | 2024-04-10 | ENTERPRISE esports            | L   | 1.000      | -            | -                | -                | -             |   -24.39 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           32 |     1526 | 2024-04-03 | Insilio                       | W   | 0.985      | -            | -                | -                | -             |     9.18 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           31 |     1537 | 2024-04-03 | Guild Eagles                  | W   | 0.984      | -            | -                | -                | -             |     9.42 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           30 |     1550 | 2024-04-03 | Alliance                      | W   | 0.983      | 0.384        | -                | 0.729 (0.275)    | -             |     6.28 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           29 |     1579 | 2024-04-02 | PARIVISION                    | W   | 0.978      | -            | -                | -                | -             |     6.68 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           28 |     1580 | 2024-04-02 | Guild Eagles                  | L   | 0.977      | -            | -                | -                | -             |   -20.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           27 |     1592 | 2024-04-02 | ALTERNATE aTTaX               | W   | 0.976      | 0.384        | 0.110 (0.041)    | 0.723 (0.271)    | -             |     7.82 | Forester, ICY, Krad, Sdaim, TRAVIS      |
|           26 |     1810 | 2024-03-26 | Verdant                       | L   | 0.932      | -            | -                | -                | -             |   -23.48 | Forester, ICY, Krad, TRAVIS, xdENiSZERA |
|           25 |     2100 | 2024-03-18 | The MongolZ                   | L   | 0.877      | -            | -                | -                | -             |    -2.16 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           24 |     2123 | 2024-03-17 | Apeks                         | L   | 0.872      | -            | -                | -                | -             |    -6.25 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           23 |     2141 | 2024-03-17 | GamerLegion                   | L   | 0.871      | -            | -                | -                | -             |    -3.06 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           22 |     2681 | 2024-03-05 | FORZE Esports                 | L   | 0.792      | -            | -                | -                | -             |   -14.46 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           21 |     2697 | 2024-03-05 | Zero Tenacity                 | W   | 0.792      | -            | -                | -                | -             |     5.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           20 |     2739 | 2024-03-04 | HyperSpirit                   | W   | 0.786      | -            | -                | -                | -             |     1.45 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           19 |     2860 | 2024-03-02 | ILLYRIANS                     | L   | 0.772      | -            | -                | -                | -             |   -22.49 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           18 |     2926 | 2024-03-01 | BIG                           | L   | 0.763      | -            | -                | -                | -             |    -5.11 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           17 |     2990 | 2024-02-28 | Young Ninjas                  | L   | 0.751      | -            | -                | -                | -             |   -21.65 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           16 |     3507 | 2024-02-17 | 9Pandas                       | W   | 0.677      | -            | -                | -                | true (0.677)  |     8.36 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           15 |     3549 | 2024-02-16 | Team Falcons                  | W   | 0.670      | 0.143        | 0.431 (0.041)    | -                | true (0.670)  |    15.82 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           14 |     3600 | 2024-02-15 | Fnatic                        | L   | 0.664      | -            | -                | -                | -             |    -9.72 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           13 |     3632 | 2024-02-14 | Ninjas in Pyjamas             | W   | 0.658      | -            | -                | -                | true (0.658)  |     2.09 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           12 |     3639 | 2024-02-14 | ENTERPRISE esports            | L   | 0.657      | -            | -                | -                | -             |   -17.20 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           11 |     3777 | 2024-02-10 | Sashi Esport                  | L   | 0.631      | -            | -                | -                | -             |   -14.81 | Forester, ICY, Krad, NickelBack, TRAVIS |
|           10 |     3788 | 2024-02-09 | Nemiga Gaming                 | L   | 0.625      | -            | -                | -                | -             |    -7.77 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            9 |     3814 | 2024-02-08 | RUBY                          | W   | 0.619      | -            | -                | -                | -             |     2.71 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            8 |     3828 | 2024-02-08 | Insilio                       | W   | 0.618      | -            | -                | -                | -             |     3.64 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            7 |     4604 | 2024-01-19 | Astralis                      | W   | 0.485      | -            | -                | -                | -             |    12.93 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            6 |     4657 | 2024-01-18 | KOI                           | W   | 0.478      | -            | -                | -                | -             |     4.42 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            5 |     4676 | 2024-01-18 | Insilio                       | W   | 0.477      | -            | -                | -                | -             |     2.59 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            4 |     4692 | 2024-01-17 | FreeESPI                      | W   | 0.473      | -            | -                | -                | -             |     0.65 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            3 |     4700 | 2024-01-17 | RUBY                          | W   | 0.473      | -            | -                | -                | -             |     1.80 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            2 |     4712 | 2024-01-17 | Turów Zgorzelec Esport        | W   | 0.472      | -            | -                | -                | -             |     1.37 | Forester, ICY, Krad, NickelBack, TRAVIS |
|            1 |     4720 | 2024-01-17 | Looking4org (Belarusian team) | W   | 0.472      | -            | -                | -                | -             |     0.15 | Forester, ICY, Krad, NickelBack, TRAVIS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,152.31)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $22,000.00     | $22,000.00      |
| 2024-05-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-03-31 |      0.965 | $10,000.00     | $9,652.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
