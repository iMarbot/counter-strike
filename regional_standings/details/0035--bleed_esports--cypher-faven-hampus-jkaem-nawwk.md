### Roster Details<br />
Team Name: BLEED Esports<br />
Roster: CYPHER, faveN, hampus, jkaem, nawwk<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [35](../standings_global.md)<br />
Regional Rank: [25]( ../standings_europe.md)<br />
Final Rank Value:  1178.3<br />
<br />
Final Rank Value (1178.3) = Starting Rank Value (1262.6) + Head To Head Adjustments (-84.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.623[<sup>1</sup>](#table2)
- Bounty Collected: 0.463[<sup>2</sup>](#table1)
- Opponent Network: 0.398[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.424<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1262.6
- 400 + ( ( 0.424 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1262.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           60 |        0 | 2024-05-29 | ATOX Esports      | W   | 1.000      | -            | -                | -                | 1 (1.000) |    11.89 | CYPHER, faveN, hampus, jkaem, nawwk |
|           59 |       97 | 2024-05-28 | Chinggis Warriors | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.78 | CYPHER, faveN, hampus, jkaem, nawwk |
|           58 |      596 | 2024-05-21 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -20.52 | CYPHER, faveN, hampus, jkaem, nawwk |
|           57 |      698 | 2024-05-20 | 9Pandas           | W   | 1.000      | 0.500        | 0.110 (0.055)    | 0.660 (0.330)    | 0 (0.000) |    12.14 | CYPHER, faveN, hampus, jkaem, nawwk |
|           56 |      806 | 2024-05-19 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.157 (0.079)    | 0.950 (0.475)    | 0 (0.000) |    10.19 | CYPHER, faveN, hampus, jkaem, nawwk |
|           55 |      979 | 2024-05-17 | Monte             | L   | 1.000      | -            | -                | -                | -         |   -11.54 | CYPHER, faveN, hampus, jkaem, nawwk |
|           54 |     1177 | 2024-05-15 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |   -16.58 | CYPHER, faveN, hampus, jkaem, nawwk |
|           53 |     1204 | 2024-05-15 | MOUZ NXT          | W   | 1.000      | 0.500        | 0.157 (0.079)    | 0.950 (0.475)    | 0 (0.000) |     9.48 | CYPHER, faveN, hampus, jkaem, nawwk |
|           52 |     1480 | 2024-05-11 | B8                | L   | 1.000      | -            | -                | -                | -         |   -19.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           51 |     1552 | 2024-05-09 | Team Sampi        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.71 | CYPHER, draken, faveN, hampus, VLDN |
|           50 |     1677 | 2024-05-07 | 1win              | L   | 1.000      | -            | -                | -                | -         |   -23.07 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           49 |     1741 | 2024-05-06 | Insilio           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           48 |     1907 | 2024-05-02 | AMKAL ESPORTS     | L   | 1.000      | -            | -                | -                | -         |   -16.98 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           47 |     1995 | 2024-05-01 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -22.19 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           46 |     2045 | 2024-04-30 | Permitta Esports  | W   | 1.000      | 0.384        | -                | 1.000 (0.384)    | 0 (0.000) |     4.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           45 |     2254 | 2024-04-26 | ex-Guild Eagles   | W   | 0.977      | -            | -                | -                | 0 (0.000) |     6.08 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           44 |     2275 | 2024-04-26 | DMS               | W   | 0.976      | 0.500        | -                | 0.751 (0.366)    | 0 (0.000) |     3.15 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           43 |     2371 | 2024-04-24 | Permitta Esports  | W   | 0.964      | 0.435        | -                | 1.000 (0.419)    | -         |     5.61 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           42 |     2378 | 2024-04-24 | Nemiga Gaming     | L   | 0.963      | -            | -                | -                | -         |   -16.69 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           41 |     2420 | 2024-04-23 | B8                | W   | 0.956      | 0.500        | 0.168 (0.080)    | 0.952 (0.455)    | -         |     8.46 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           40 |     2433 | 2024-04-23 | Sashi Esport      | L   | 0.955      | -            | -                | -                | -         |   -17.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           39 |     2459 | 2024-04-22 | Sangal Esports    | W   | 0.950      | 0.500        | 0.166 (0.079)    | -                | -         |     5.79 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           38 |     2462 | 2024-04-22 | Gaimin Gladiators | W   | 0.949      | 0.384        | 0.092 (0.034)    | -                | -         |    16.40 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           37 |     2488 | 2024-04-21 | Illuminar Gaming  | W   | 0.944      | -            | -                | -                | -         |     2.74 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           36 |     2583 | 2024-04-20 | MOUZ NXT          | W   | 0.936      | 0.500        | 0.157 (0.074)    | 0.950 (0.445)    | -         |     9.44 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           35 |     2728 | 2024-04-19 | Team Sampi        | W   | 0.928      | -            | -                | -                | -         |     6.91 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           34 |     2794 | 2024-04-18 | ALTERNATE aTTaX   | W   | 0.921      | 0.500        | 0.052 (0.024)    | 0.679 (0.313)    | -         |     5.41 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           33 |     2906 | 2024-04-16 | KOI               | W   | 0.910      | -            | -                | -                | -         |     8.57 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           32 |     2928 | 2024-04-16 | SINNERS Esports   | W   | 0.908      | -            | -                | -                | -         |     9.05 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           31 |     3245 | 2024-04-09 | Alliance          | W   | 0.863      | -            | -                | -                | -         |     3.95 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           30 |     3260 | 2024-04-09 | HAVU Gaming       | W   | 0.862      | -            | -                | -                | -         |     2.02 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           29 |     3442 | 2024-04-05 | BetBoom Team      | L   | 0.837      | -            | -                | -                | -         |    -7.97 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           28 |     3449 | 2024-04-05 | Alliance          | W   | 0.836      | -            | -                | -                | -         |     3.81 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           27 |     3502 | 2024-04-04 | BenchedHeroes     | W   | 0.830      | -            | -                | -                | -         |     0.31 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           26 |     3509 | 2024-04-04 | BetBoom Team      | L   | 0.829      | -            | -                | -                | -         |    -8.34 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           25 |     3600 | 2024-04-02 | Passion UA        | W   | 0.817      | 0.384        | -                | 1.000 (0.314)    | -         |     4.84 | CeRq, CYPHER, faveN, hampus, RuStY  |
|           24 |     3816 | 2024-03-27 | Team Sampi        | L   | 0.777      | -            | -                | -                | -         |   -19.04 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           23 |     3855 | 2024-03-26 | MIREA             | W   | 0.771      | -            | -                | -                | -         |     0.25 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           22 |     4880 | 2024-03-06 | Fnatic            | L   | 0.637      | -            | -                | -                | -         |   -12.17 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           21 |     4969 | 2024-03-05 | BetBoom Team      | W   | 0.629      | 0.500        | 0.390 (0.123)    | -                | -         |    13.89 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           20 |     5031 | 2024-03-04 | Rebels Gaming     | W   | 0.624      | -            | -                | -                | -         |     7.09 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           19 |     5055 | 2024-03-04 | AURA              | W   | 0.622      | -            | -                | -                | -         |     1.09 | CeRq, CYPHER, faveN, hampus, lauNX  |
|           18 |     5118 | 2024-03-02 | KOI               | L   | 0.612      | -            | -                | -                | -         |   -14.35 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           17 |     5166 | 2024-03-02 | L&G               | W   | 0.611      | -            | -                | -                | -         |     0.33 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           16 |     5233 | 2024-03-01 | Young Ninjas      | W   | 0.604      | -            | -                | -                | -         |     3.13 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           15 |     5292 | 2024-02-29 | AURA              | W   | 0.596      | -            | -                | -                | -         |     0.80 | CeRq, CYPHER, faveN, hampus, lauNX  |
|           14 |     5338 | 2024-02-28 | BIG               | W   | 0.589      | 0.500        | 0.235 (0.069)    | -                | -         |    14.27 | CeRq, CYPHER, faveN, hampus, VLDN   |
|           13 |     5420 | 2024-02-26 | MOUZ NXT          | L   | 0.576      | -            | -                | -                | -         |   -11.23 | CeRq, CYPHER, faveN, hampus, lauNX  |
|           12 |     6342 | 2024-02-08 | Passion UA        | W   | 0.456      | -            | -                | -                | -         |     3.31 | CeRq, CYPHER, faveN, hampus, lauNX  |
|           11 |     6694 | 2024-02-01 | Into The Breach   | L   | 0.409      | -            | -                | -                | -         |   -11.94 | CeRq, CYPHER, faveN, hampus, lauNX  |
|           10 |     6737 | 2024-01-31 | 9INE              | W   | 0.402      | -            | -                | -                | -         |     0.34 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            9 |     6822 | 2024-01-29 | RUBY              | L   | 0.392      | -            | -                | -                | -         |   -10.55 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            8 |     6841 | 2024-01-29 | Metizport         | L   | 0.389      | -            | -                | -                | -         |   -10.10 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            7 |     6869 | 2024-01-28 | Into The Breach   | L   | 0.383      | -            | -                | -                | -         |   -11.42 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            6 |     6969 | 2024-01-27 | Sprout            | L   | 0.377      | -            | -                | -                | -         |   -11.57 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            5 |     7093 | 2024-01-25 | Into The Breach   | W   | 0.362      | -            | -                | -                | -         |     0.58 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            4 |     8065 | 2024-01-09 | Entropiq          | L   | 0.258      | -            | -                | -                | -         |    -7.86 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            3 |     8078 | 2024-01-09 | IKLA              | W   | 0.258      | -            | -                | -                | -         |     0.16 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            2 |     8084 | 2024-01-09 | Sangal Esports    | W   | 0.257      | -            | -                | -                | -         |     2.21 | CeRq, CYPHER, faveN, hampus, lauNX  |
|            1 |     8123 | 2024-01-09 | NextUp            | W   | 0.257      | -            | -                | -                | -         |     0.06 | CeRq, CYPHER, faveN, hampus, lauNX  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($74,512.61)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.25) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-05-18 |      1.000 | $500.00        | $500.00         |
| 2024-05-12 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-09 |      1.000 | $532.06        | $532.06         |
| 2024-04-24 |      0.963 | $25,000.00     | $24,076.39      |
| 2024-04-22 |      0.949 | $20,000.00     | $18,980.56      |
| 2024-03-06 |      0.637 | $25,000.00     | $15,923.61      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
