### Roster Details<br />
Team Name: GenOne<br />
Roster: Brooxsy, devoduvek, drac, Kursy, unshaark<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [252](../standings_global.md)<br />
Regional Rank: [160]( ../standings_europe.md)<br />
Final Rank Value:  662.5<br />
<br />
Final Rank Value (662.5) = Starting Rank Value (577.3) + Head To Head Adjustments (85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.089<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 577.3
- 400 + ( ( 0.089 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 577.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      104 | 2024-05-03 | Ex-KRC Genk Esports    | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.181 (0.067)    | 0 (0.000) |    19.98 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           24 |      151 | 2024-05-02 | HyperSpirit            | W   | 1.000      | 0.371        | 0.009 (0.003)    | 0.293 (0.109)    | 0 (0.000) |    19.59 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           23 |      239 | 2024-04-30 | ADEPTS                 | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.116 (0.043)    | 0 (0.000) |    17.02 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           22 |      449 | 2024-04-26 | 500                    | L   | 1.000      | -            | -                | -                | -         |    -5.14 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           21 |      485 | 2024-04-25 | Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |    -9.06 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           20 |      575 | 2024-04-23 | RUBY                   | L   | 1.000      | -            | -                | -                | -         |    -3.54 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           19 |      616 | 2024-04-22 | 500                    | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.660 (0.094)    | 0 (0.000) |    26.43 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           18 |      825 | 2024-04-19 | ARROW (German team)    | L   | 1.000      | -            | -                | -                | -         |    -9.98 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           17 |     1179 | 2024-04-11 | LEON Esports           | L   | 1.000      | -            | -                | -                | -         |   -11.89 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           16 |     1232 | 2024-04-10 | VaselineWorms          | W   | 1.000      | 0.371        | 0.001 (0.000)    | 0.164 (0.061)    | 0 (0.000) |    17.10 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           15 |     1366 | 2024-04-07 | TEAM ZOO BAR           | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |    12.46 | Brooxsy, devoduvek, drac, Kursy, unshaark |
|           14 |     2958 | 2024-02-29 | EsmagaB                | W   | 0.758      | 0.371        | 0.016 (0.004)    | 0.559 (0.157)    | 0 (0.000) |    18.52 | devoduvek, drac, Revol, SIXER, unshaark   |
|           13 |     2994 | 2024-02-28 | GUN5 Esports           | L   | 0.751      | -            | -                | -                | -         |    -9.78 | FinigaN, lov1kus, supra, tried, xiELO     |
|           12 |     3241 | 2024-02-22 | GODSENT                | L   | 0.712      | -            | -                | -                | -         |    -5.04 | devoduvek, drac, Revol, SIXER, unshaark   |
|           11 |     3249 | 2024-02-22 | Lilmix                 | L   | 0.712      | -            | -                | -                | -         |    -9.41 | Brillo, dex, poiii, quix, zyyx            |
|           10 |     3627 | 2024-02-14 | V1dar Gaming           | L   | 0.658      | -            | -                | -                | -         |    -9.82 | 1mpala, 4X1s, Alv, lom1k, torox           |
|            9 |     3682 | 2024-02-13 | Entropiq               | L   | 0.651      | -            | -                | -                | -         |    -5.27 | c0llins, Marix, mwlky, Oxygen, tiziaN     |
|            8 |     3792 | 2024-02-09 | DMS                    | W   | 0.625      | 0.371        | -                | 0.504 (0.117)    | 0 (0.000) |    11.31 | AW, H1te, kAlash, sFade8, sm3t            |
|            7 |     3796 | 2024-02-09 | Lausanne-Sport Esports | W   | 0.624      | 0.371        | 0.004 (0.001)    | 0.241 (0.056)    | 0 (0.000) |    13.99 | Diviiii, msn2k, SBT, SeBreeZe, xReal      |
|            6 |     3818 | 2024-02-08 | TBA.ECF                | L   | 0.618      | -            | -                | -                | -         |    -7.08 | devoduvek, drac, Revol, SIXER, unshaark   |
|            5 |     3840 | 2024-02-07 | Endpoint               | W   | 0.612      | 0.371        | 0.005 (0.001)    | 0.785 (0.179)    | 0 (0.000) |    16.17 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3892 | 2024-02-05 | Ex-Anonymo Esports     | L   | 0.598      | -            | -                | -                | -         |    -4.28 | lunAtic, reiko, SaMey, Sobol, virtuoso    |
|            3 |     4025 | 2024-02-02 | Eternal Fire Academy   | W   | 0.578      | 0.371        | 0.013 (0.003)    | 0.179 (0.038)    | -         |    12.99 | cyber, Depact, hey, jottAAA, scolleN      |
|            2 |     4176 | 2024-01-29 | Illuminar Gaming       | L   | 0.553      | -            | -                | -                | -         |    -3.91 | Furlan, phr, POLO, Prism, Qlocuu          |
|            1 |     4379 | 2024-01-24 | Copenhagen Wolves      | L   | 0.519      | -            | -                | -                | -         |    -6.22 | fierre, Svedjehed, szejn, tooizera, vigg0 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
