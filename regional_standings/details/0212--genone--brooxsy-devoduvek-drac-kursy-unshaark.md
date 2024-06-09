### Roster Details<br />
Team Name: GenOne<br />
Roster: Brooxsy, devoduvek, drac, Kursy, unshaark<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [212](../standings_global.md)<br />
Regional Rank: [142]( ../standings_europe.md)<br />
Final Rank Value:  713.3<br />
<br />
Final Rank Value (713.3) = Starting Rank Value (644.2) + Head To Head Adjustments (69.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.266[<sup>2</sup>](#table1)
- Opponent Network: 0.109[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 644.2
- 400 + ( ( 0.120 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 644.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      468 | 2024-05-22 | TopTab Club               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.86 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           39 |      812 | 2024-05-19 | Over30                    | L   | 1.000      | -            | -                | -                | -         |   -19.12 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           38 |      836 | 2024-05-18 | 3K ESPORT                 | W   | 1.000      | -            | -                | -                | 1 (1.000) |     4.38 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           37 |     1170 | 2024-05-15 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |    -5.68 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           36 |     1286 | 2024-05-14 | DASH                      | W   | 1.000      | 0.372        | -                | 0.385 (0.143)    | 0 (0.000) |    14.50 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           35 |     1368 | 2024-05-12 | CYBERSHOKE Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.43 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           34 |     1381 | 2024-05-12 | M1X                       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.18 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           33 |     1395 | 2024-05-12 | VOLT                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.49 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           32 |     1450 | 2024-05-11 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -3.29 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           31 |     1457 | 2024-05-11 | Chroma                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.21 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           30 |     1470 | 2024-05-11 | Rebels Gaming             | W   | 1.000      | 0.143        | 0.062 (0.009)    | 0.411 (0.059)    | 0 (0.000) |    28.26 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           29 |     1647 | 2024-05-08 | AscendX Esports           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.89 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           28 |     1661 | 2024-05-08 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |    -5.47 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           27 |     1693 | 2024-05-07 | LODIS                     | L   | 1.000      | -            | -                | -                | -         |   -19.16 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           26 |     1901 | 2024-05-03 | ex-KRC Genk Esports       | W   | 1.000      | 0.372        | -                | 0.173 (0.064)    | 0 (0.000) |    16.68 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           25 |     1953 | 2024-05-02 | HyperSpirit               | W   | 1.000      | 0.372        | 0.004 (0.001)    | 0.356 (0.133)    | 0 (0.000) |    19.41 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           24 |     2059 | 2024-04-30 | ADEPTS                    | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.291 (0.108)    | -         |    21.00 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           23 |     2323 | 2024-04-26 | 500                       | L   | 0.975      | -            | -                | -                | -         |    -7.47 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           22 |     2363 | 2024-04-25 | ex-Turów Zgorzelec Esport | L   | 0.969      | -            | -                | -                | -         |   -10.51 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           21 |     2466 | 2024-04-23 | RUBY                      | L   | 0.956      | -            | -                | -                | -         |    -4.45 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           20 |     2515 | 2024-04-22 | 500                       | W   | 0.949      | 0.143        | 0.002 (0.000)    | 0.479 (0.065)    | -         |    22.43 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           19 |     2761 | 2024-04-19 | ARROW                     | L   | 0.930      | -            | -                | -                | -         |   -10.82 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           18 |     3192 | 2024-04-11 | LEON Esports              | L   | 0.876      | -            | -                | -                | -         |   -10.96 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           17 |     3260 | 2024-04-10 | VaselineWorms             | W   | 0.869      | 0.372        | 0.000 (0.000)    | 0.418 (0.135)    | -         |    14.54 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           16 |     3410 | 2024-04-07 | 3DMAX                     | L   | 0.851      | -            | -                | -                | -         |    -4.33 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           15 |     3418 | 2024-04-07 | Over30                    | W   | 0.850      | 0.143        | 0.002 (0.000)    | -                | -         |    13.13 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           14 |     5428 | 2024-02-29 | esmagaB                   | W   | 0.597      | 0.371        | 0.008 (0.002)    | 0.564 (0.125)    | -         |    13.43 | devoduvek, drac, Revol, SIXER, unshaark   |
|           13 |     5476 | 2024-02-28 | GUN5 Esports              | L   | 0.590      | -            | -                | -                | -         |    -9.42 | FinigaN, lov1kus, supra, tried, xiELO     |
|           12 |     5803 | 2024-02-22 | AURA                      | L   | 0.551      | -            | -                | -                | -         |    -8.25 | devoduvek, drac, Revol, SIXER, unshaark   |
|           11 |     5812 | 2024-02-22 | Lilmix                    | L   | 0.551      | -            | -                | -                | -         |    -4.59 | Brillo, dex, poiii, quix, zyyx            |
|           10 |     6280 | 2024-02-14 | V1dar Gaming              | L   | 0.497      | -            | -                | -                | -         |    -7.39 | 1mpala, 4X1s, Alv, lom1k, torox           |
|            9 |     6345 | 2024-02-13 | Entropiq                  | L   | 0.490      | -            | -                | -                | -         |    -7.55 | c0llins, Marix, mwlky, Oxygen, tiziaN     |
|            8 |     6485 | 2024-02-09 | DMS                       | W   | 0.464      | 0.371        | -                | 0.754 (0.130)    | -         |     8.88 | AW, H1te, kAlash, sFade8, sm3t            |
|            7 |     6491 | 2024-02-09 | Lausanne-Sport Esports    | W   | 0.463      | 0.371        | 0.002 (0.000)    | -                | -         |     9.57 | Diviiii, msn2k, SBT, SeBreeZe, xReal      |
|            6 |     6515 | 2024-02-08 | kONO.ECF                  | L   | 0.457      | -            | -                | -                | -         |    -2.67 | devoduvek, drac, Revol, SIXER, unshaark   |
|            5 |     6547 | 2024-02-07 | Endpoint                  | W   | 0.451      | 0.371        | 0.012 (0.002)    | 0.770 (0.129)    | -         |    12.18 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     6618 | 2024-02-05 | ex-Anonymo Esports        | L   | 0.437      | -            | -                | -                | -         |    -4.93 | lunAtic, reiko, SaMey, Sobol, virtuoso    |
|            3 |     6805 | 2024-02-02 | Eternal Fire Academy      | W   | 0.417      | 0.371        | 0.003 (0.000)    | -                | -         |     7.05 | cyber, Depact, hey, jottAAA, scolleN      |
|            2 |     7019 | 2024-01-29 | brazylijski luz           | L   | 0.392      | -            | -                | -                | -         |    -3.33 | Furlan, phr, POLO, Prism, Qlocuu          |
|            1 |     7342 | 2024-01-24 | Copenhagen Wolves         | L   | 0.358      | -            | -                | -                | -         |    -5.17 | fierre, Svedjehed, szejn, tooizera, vigg0 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
