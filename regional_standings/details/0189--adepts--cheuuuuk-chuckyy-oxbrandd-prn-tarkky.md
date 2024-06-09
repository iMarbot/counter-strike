### Roster Details<br />
Team Name: ADEPTS<br />
Roster: cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [189](../standings_global.md)<br />
Regional Rank: [128]( ../standings_europe.md)<br />
Final Rank Value:  733.5<br />
<br />
Final Rank Value (733.5) = Starting Rank Value (826.8) + Head To Head Adjustments (-93.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.270[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.210<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 826.8
- 400 + ( ( 0.210 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 826.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      467 | 2024-05-22 | Eternal Fire Academy | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.136 (0.051)    | 0 (0.000) |     9.29 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           29 |      593 | 2024-05-21 | ARROW                | L   | 1.000      | -            | -                | -                | -         |   -15.63 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           28 |      811 | 2024-05-19 | 11minutostarde       | L   | 1.000      | -            | -                | -                | -         |   -14.28 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           27 |      820 | 2024-05-19 | Over30               | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.055 (0.008)    | 1 (1.000) |    10.87 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           26 |      822 | 2024-05-18 | CLEAR                | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 1 (1.000) |     4.02 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           25 |     1153 | 2024-05-15 | Young Ninjas         | W   | 1.000      | 0.372        | 0.043 (0.016)    | 0.372 (0.138)    | 0 (0.000) |    21.74 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           24 |     1458 | 2024-05-11 | B8                   | L   | 1.000      | -            | -                | -                | -         |    -3.37 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           23 |     1471 | 2024-05-11 | Dragon esports       | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.48 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           22 |     1520 | 2024-05-10 | NOM Esports          | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.360 (0.134)    | 0 (0.000) |    15.11 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           21 |     1629 | 2024-05-08 | Team PeeP            | W   | 1.000      | 0.372        | -                | 0.247 (0.092)    | 0 (0.000) |    10.89 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           20 |     1699 | 2024-05-07 | Nexus Gaming         | L   | 1.000      | -            | -                | -                | -         |   -10.71 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           19 |     1734 | 2024-05-06 | Lemondogs            | L   | 1.000      | -            | -                | -                | -         |   -19.24 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           18 |     1997 | 2024-05-01 | Kappa Bar            | L   | 1.000      | -            | -                | -                | -         |   -23.95 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           17 |     2009 | 2024-05-01 | Denial               | L   | 1.000      | -            | -                | -                | -         |   -22.52 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           16 |     2059 | 2024-04-30 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -21.00 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           15 |     2400 | 2024-04-24 | Aurora Young Blud    | L   | 0.964      | -            | -                | -                | -         |   -14.93 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|           14 |     3194 | 2024-04-11 | Rhyno Esports        | L   | 0.876      | -            | -                | -                | -         |    -7.83 | DDias, krazy, renatoohaxx, snapy, TMKj       |
|           13 |     3365 | 2024-04-08 | Copenhagen Wolves    | L   | 0.857      | -            | -                | -                | -         |   -19.48 | artie, Basso, Fessor, Svedjehed, szejn       |
|           12 |     4318 | 2024-03-18 | HyperSpirit          | L   | 0.717      | -            | -                | -                | -         |   -14.33 | ADRON, GEOHYPE, kritik, smekk, swiiffter     |
|           11 |     4347 | 2024-03-17 | Donstu Esports       | W   | 0.711      | 0.333        | -                | 0.178 (0.042)    | 0 (0.000) |     3.94 | aNsavage, NeoLife, Nosik, s7xWn, Snoob       |
|           10 |     4410 | 2024-03-16 | WOPA Esport          | L   | 0.705      | -            | -                | -                | -         |   -12.36 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|            9 |     4717 | 2024-03-11 | TOR                  | W   | 0.671      | 0.333        | 0.014 (0.003)    | 0.196 (0.044)    | 0 (0.000) |     9.19 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|            8 |     4929 | 2024-03-07 | XI Esport            | W   | 0.645      | 0.333        | 0.001 (0.000)    | 0.277 (0.060)    | 0 (0.000) |     5.21 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|            7 |     5077 | 2024-03-05 | Team LRP Poland      | W   | 0.631      | 0.333        | 0.001 (0.000)    | 0.056 (0.012)    | -         |     7.01 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky     |
|            6 |     8463 | 2024-01-06 | RGW Esports          | W   | 0.238      | 0.143        | 0.000 (0.000)    | -                | -         |     1.07 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa      |
|            5 |     8474 | 2024-01-05 | ADEPTS               | W   | 0.231      | -            | -                | -                | -         |     0.91 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR      |
|            4 |     8485 | 2024-01-04 | 3K ESPORT            | W   | 0.224      | -            | -                | -                | -         |     0.61 | 0riion, Calicerime, LaKra, Nidoria, P0MP0M   |
|            3 |     8531 | 2024-01-02 | 3K ESPORT            | W   | 0.212      | -            | -                | -                | -         |     0.57 | 0riion, Calicerime, LaKra, Nidoria, P0MP0M   |
|            2 |     8537 | 2024-01-02 | ADEPTS               | W   | 0.211      | -            | -                | -                | -         |     0.80 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR      |
|            1 |     8545 | 2024-01-02 | Caldya Esport        | W   | 0.211      | 0.143        | -                | 0.089 (0.003)    | -         |     0.56 | Brooxsy, cHeuuuuk, Chuckyy, Tarkky, unshaark |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,406.09)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $1,089.44      | $1,089.44       |
| 2024-03-23 |      0.751 | $300.00        | $225.38         |
| 2024-01-06 |      0.238 | $383.41        | $91.27          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
