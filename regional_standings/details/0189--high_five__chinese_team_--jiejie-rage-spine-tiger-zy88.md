### Roster Details<br />
Team Name: High Five (Chinese team)<br />
Roster: jiejie, rage, SPine, TiGeR, zy88<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [189](../standings_global.md)<br />
Regional Rank: [31]( ../standings_asia.md)<br />
Final Rank Value:  737.2<br />
<br />
Final Rank Value (737.2) = Starting Rank Value (814.1) + Head To Head Adjustments (-76.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.426[<sup>1</sup>](#table2)
- Bounty Collected: 0.321[<sup>2</sup>](#table1)
- Opponent Network: 0.088[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.209<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 814.1
- 400 + ( ( 0.209 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 814.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      675 | 2024-04-20 | Rare Atom          | L   | 1.000      | -            | -                | -                | -         |    -8.33 | jiejie, rage, SPine, TiGeR, zy88                 |
|           29 |      742 | 2024-04-20 | LYG Gaming         | L   | 1.000      | -            | -                | -                | -         |   -13.51 | deffen, Haski4, Sange, Soundwave, ZinGY          |
|           28 |      755 | 2024-04-20 | LYG Gaming         | L   | 1.000      | -            | -                | -                | -         |   -14.75 | jiejie, karl, rage, SPine, TiGeR                 |
|           27 |      766 | 2024-04-20 | Bigetron Fury      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.80 | jiejie, rage, SPine, TiGeR, zy88                 |
|           26 |      845 | 2024-04-19 | Steel Helmet       | W   | 1.000      | 0.143        | 0.025 (0.004)    | 0.174 (0.025)    | 0 (0.000) |    12.44 | jiejie, rage, SPine, TiGeR, zy88                 |
|           25 |      905 | 2024-04-18 | Bigetron Fury      | L   | 1.000      | -            | -                | -                | -         |   -24.84 | jiejie, rage, SPine, TiGeR, zy88                 |
|           24 |     1237 | 2024-04-10 | Born In Far East   | L   | 1.000      | -            | -                | -                | -         |   -18.67 | korde, lakyo, meerkat, murakumo, W1nd            |
|           23 |     1242 | 2024-04-10 | Born In Far East   | L   | 1.000      | -            | -                | -                | -         |   -20.30 | jiejie, karl, rage, SPine, TiGeR                 |
|           22 |     1299 | 2024-04-09 | ATOX Esports       | W   | 1.000      | 0.417        | 0.112 (0.047)    | 0.769 (0.321)    | 0 (0.000) |    26.04 | ANNIHILATION, dobu, kabal, MiQ, Zesta            |
|           21 |     1304 | 2024-04-09 | ATOX Esports       | L   | 1.000      | -            | -                | -                | -         |    -4.98 | jiejie, karl, rage, SPine, TiGeR                 |
|           20 |     1544 | 2024-04-03 | The QUBE Esports   | L   | 0.984      | -            | -                | -                | -         |   -17.49 | jiejie, karl, rage, SPine, TiGeR                 |
|           19 |     1548 | 2024-04-03 | The QUBE Esports   | W   | 0.984      | 0.417        | 0.004 (0.002)    | 0.168 (0.069)    | 0 (0.000) |    13.34 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, Randy |
|           18 |     1641 | 2024-03-30 | TYLOO              | L   | 0.957      | -            | -                | -                | -         |    -7.45 | jiejie, karl, rage, SPine, TiGeR                 |
|           17 |     1642 | 2024-03-30 | TYLOO              | L   | 0.957      | -            | -                | -                | -         |    -7.94 | advent, JamYoung, kaze, Mercury, zdr             |
|           16 |     1666 | 2024-03-29 | -72C               | L   | 0.951      | -            | -                | -                | -         |   -15.12 | 1nhuman, borosto, forzetsky, m3wsu, shandarez    |
|           15 |     1668 | 2024-03-29 | -72C               | L   | 0.951      | -            | -                | -                | -         |   -16.44 | jiejie, karl, rage, SPine, TiGeR                 |
|           14 |     2275 | 2024-03-14 | GR Gaming          | W   | 0.851      | 0.417        | 0.006 (0.002)    | 0.495 (0.176)    | 0 (0.000) |    14.67 | mediocrity, qqGOD, Runnin, SALO_MUX, weqt2       |
|           13 |     2280 | 2024-03-14 | GR Gaming          | L   | 0.851      | -            | -                | -                | -         |   -12.19 | jiejie, karl, rage, SPine, TiGeR                 |
|           12 |     2326 | 2024-03-13 | MIRAI Gaming       | L   | 0.844      | -            | -                | -                | -         |   -19.55 | jiejie, karl, rage, SPine, TiGeR                 |
|           11 |     2331 | 2024-03-13 | MIRAI Gaming       | W   | 0.844      | 0.417        | -                | 0.246 (0.087)    | 0 (0.000) |     6.80 | 7nation, aisu, ameno, Geneka, WallneR            |
|           10 |     2436 | 2024-03-11 | ATOX Esports       | L   | 0.830      | -            | -                | -                | -         |    -5.64 | jiejie, L1haNg, rage, SPine, zy88                |
|            9 |     2441 | 2024-03-11 | E9 esports         | W   | 0.829      | 0.143        | 0.021 (0.002)    | -                | 0 (0.000) |    10.65 | jiejie, L1haNg, rage, SPine, zy88                |
|            8 |     2470 | 2024-03-10 | Myth Avenue Gaming | W   | 0.823      | 0.143        | 0.012 (0.001)    | 0.302 (0.036)    | 0 (0.000) |     9.69 | Derek, Jaytzy, Kayje, SiameseCv, WasteOfAmmo     |
|            7 |     2521 | 2024-03-09 | E9 esports         | L   | 0.816      | -            | -                | -                | -         |   -15.05 | Balzo, neverland, salmon, skrrrr, T3rrymeister   |
|            6 |     2548 | 2024-03-07 | Myth Avenue Gaming | W   | 0.808      | 0.143        | 0.012 (0.001)    | 0.302 (0.035)    | 0 (0.000) |     9.79 | Derek, Jaytzy, Kayje, SiameseCv, WasteOfAmmo     |
|            5 |     3359 | 2024-02-20 | Lynn Vision Gaming | L   | 0.697      | -            | -                | -                | -         |    -2.31 | jiejie, karl, rage, SPine, TiGeR                 |
|            4 |     3366 | 2024-02-20 | Lynn Vision Gaming | L   | 0.697      | -            | -                | -                | -         |    -2.37 | EmiliaQAQ, Jee, Starry, westmelon, z4kr          |
|            3 |     3501 | 2024-02-17 | Lynn Vision Gaming | W   | 0.677      | 0.143        | 0.155 (0.015)    | 0.554 (0.054)    | 0 (0.000) |    19.29 | jiejie, L1haNg, rage, SPine, TiGeR               |
|            2 |     3510 | 2024-02-17 | Myth Avenue Gaming | W   | 0.676      | 0.143        | 0.012 (0.001)    | 0.302 (0.029)    | -         |     8.97 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            1 |     3554 | 2024-02-16 | GR Gaming          | W   | 0.669      | 0.143        | 0.006 (0.001)    | 0.495 (0.047)    | -         |    11.59 | jiejie, karl, L1haNg, rage, SPine                |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,156.13)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $1,381.25      | $1,381.25       |
| 2024-03-11 |      0.830 | $6,958.07      | $5,774.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
