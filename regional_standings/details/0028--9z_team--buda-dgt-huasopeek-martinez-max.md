### Roster Details<br />
Team Name: 9z Team<br />
Roster: buda, dgt, HUASOPEEK, Martinez, max<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [28](../standings_global.md)<br />
Regional Rank: [8]( ../standings_americas.md)<br />
Final Rank Value:  1286.7<br />
<br />
Final Rank Value (1286.7) = Starting Rank Value (1265.6) + Head To Head Adjustments (21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.507[<sup>1</sup>](#table2)
- Bounty Collected: 0.554[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.415[<sup>2</sup>](#table1)

The average of these factors is 0.425<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1265.6
- 400 + ( ( 0.425 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1265.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           66 |       38 | 2024-05-29 | Team Vitality        | W   | 1.000      | 0.624        | 0.696 (0.434)    | 0.320 (0.199)    | 1 (1.000) |    30.33 | buda, dgt, HUASOPEEK, Martinez, max   |
|           65 |      143 | 2024-05-27 | Team Liquid          | W   | 1.000      | 0.624        | 0.513 (0.320)    | 0.621 (0.388)    | 1 (1.000) |    28.34 | buda, dgt, HUASOPEEK, Martinez, max   |
|           64 |      158 | 2024-05-27 | MOUZ                 | W   | 1.000      | 0.624        | 1.000 (0.624)    | 0.434 (0.271)    | 1 (1.000) |    31.11 | buda, dgt, HUASOPEEK, Martinez, max   |
|           63 |      436 | 2024-05-22 | Imperial Esports     | L   | 1.000      | -            | -                | -                | -         |    -8.99 | buda, dgt, HUASOPEEK, Martinez, max   |
|           62 |      440 | 2024-05-22 | Imperial Esports     | L   | 1.000      | -            | -                | -                | -         |    -9.68 | buda, dgt, HUASOPEEK, Martinez, max   |
|           61 |      639 | 2024-05-20 | w7m esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.05 | buda, dgt, HUASOPEEK, Martinez, max   |
|           60 |      640 | 2024-05-20 | w7m esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.09 | buda, dgt, HUASOPEEK, Martinez, max   |
|           59 |      644 | 2024-05-20 | BESTIA               | L   | 1.000      | -            | -                | -                | -         |   -26.45 | buda, dgt, HUASOPEEK, Martinez, max   |
|           58 |      659 | 2024-05-20 | BESTIA               | W   | 1.000      | 0.450        | -                | 0.477 (0.215)    | 0 (0.000) |     4.58 | buda, dgt, HUASOPEEK, Martinez, max   |
|           57 |      735 | 2024-05-19 | RED Canids           | L   | 1.000      | -            | -                | -                | -         |   -21.10 | buda, HUASOPEEK, Luken, Martinez, max |
|           56 |      855 | 2024-05-18 | Fluxo                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | buda, HUASOPEEK, Luken, Martinez, max |
|           55 |     1037 | 2024-05-16 | ODDIK                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.05 | buda, dgt, HUASOPEEK, Martinez, max   |
|           54 |     1063 | 2024-05-16 | Imperial Esports     | L   | 1.000      | -            | -                | -                | -         |    -8.19 | buda, dgt, HUASOPEEK, Martinez, max   |
|           53 |     1124 | 2024-05-15 | RED Canids           | W   | 1.000      | 0.450        | 0.076 (0.034)    | 0.508 (0.229)    | 0 (0.000) |     9.21 | buda, dgt, HUASOPEEK, Martinez, max   |
|           52 |     1126 | 2024-05-15 | RED Canids           | L   | 1.000      | -            | -                | -                | -         |   -22.79 | buda, dgt, HUASOPEEK, Martinez, max   |
|           51 |     1134 | 2024-05-15 | Sharks Esports       | W   | 1.000      | -            | -                | -                | -         |     3.87 | buda, dgt, HUASOPEEK, Martinez, max   |
|           50 |     1231 | 2024-05-14 | 2Game Esports        | W   | 1.000      | -            | -                | -                | -         |     1.10 | buda, dgt, HUASOPEEK, Martinez, max   |
|           49 |     1233 | 2024-05-14 | 2Game Esports        | W   | 1.000      | -            | -                | -                | -         |     1.12 | buda, dgt, HUASOPEEK, Martinez, max   |
|           48 |     1246 | 2024-05-14 | Galorys              | W   | 1.000      | 0.384        | -                | 0.585 (0.225)    | -         |     3.20 | buda, dgt, HUASOPEEK, Martinez, max   |
|           47 |     1298 | 2024-05-13 | Galorys              | W   | 1.000      | -            | -                | -                | -         |     3.31 | buda, dgt, HUASOPEEK, Martinez, max   |
|           46 |     1337 | 2024-05-12 | inSanitY Sports      | W   | 1.000      | -            | -                | -                | -         |     1.80 | buda, dgt, HUASOPEEK, Martinez, max   |
|           45 |     1341 | 2024-05-12 | paiN Gaming          | L   | 1.000      | -            | -                | -                | -         |    -6.61 | buda, dgt, HUASOPEEK, Martinez, max   |
|           44 |     1408 | 2024-05-11 | KRÜ Esports          | W   | 1.000      | -            | -                | -                | -         |     3.44 | buda, dgt, HUASOPEEK, Martinez, max   |
|           43 |     1485 | 2024-05-10 | inSanitY Sports      | W   | 1.000      | -            | -                | -                | -         |     1.80 | buda, dgt, HUASOPEEK, Martinez, max   |
|           42 |     1597 | 2024-05-08 | Sharks Esports       | W   | 1.000      | 0.435        | 0.031 (0.013)    | 0.365 (0.159)    | -         |     4.04 | buda, dgt, HUASOPEEK, Martinez, max   |
|           41 |     1722 | 2024-05-06 | Vikings KR           | W   | 1.000      | -            | -                | -                | -         |     1.76 | buda, dgt, HUASOPEEK, Martinez, max   |
|           40 |     1951 | 2024-05-01 | Case Esports         | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.461 (0.208)    | -         |     3.08 | buda, dgt, HUASOPEEK, Martinez, max   |
|           39 |     1956 | 2024-05-01 | Case Esports         | W   | 1.000      | 0.450        | -                | 0.461 (0.208)    | -         |     3.17 | buda, dgt, HUASOPEEK, Martinez, max   |
|           38 |     2663 | 2024-04-19 | OG                   | L   | 0.933      | -            | -                | -                | -         |   -13.51 | buda, dgt, HUASOPEEK, Martinez, max   |
|           37 |     2740 | 2024-04-18 | Imperial Esports     | L   | 0.926      | -            | -                | -                | -         |    -6.33 | buda, dgt, HUASOPEEK, Martinez, max   |
|           36 |     2747 | 2024-04-18 | FURIA Esports        | W   | 0.924      | 0.589        | 0.138 (0.075)    | 0.267 (0.145)    | 1 (0.924) |    20.31 | buda, dgt, HUASOPEEK, Martinez, max   |
|           35 |     3310 | 2024-04-08 | HEROIC               | L   | 0.855      | -            | -                | -                | -         |    -2.01 | buda, dgt, HUASOPEEK, Martinez, max   |
|           34 |     3321 | 2024-04-07 | G2 Esports           | L   | 0.853      | -            | -                | -                | -         |    -1.08 | buda, dgt, HUASOPEEK, Martinez, max   |
|           33 |     3802 | 2024-03-27 | Natus Vincere Junior | L   | 0.777      | -            | -                | -                | -         |   -22.16 | buda, dgt, HUASOPEEK, Martinez, max   |
|           32 |     3864 | 2024-03-26 | INFURITY Gaming      | W   | 0.771      | -            | -                | -                | -         |     0.40 | buda, dgt, HUASOPEEK, Martinez, max   |
|           31 |     5587 | 2024-02-23 | FURIA Esports        | W   | 0.559      | -            | -                | -                | -         |    12.64 | buda, dgt, HUASOPEEK, Martinez, max   |
|           30 |     5599 | 2024-02-23 | BESTIA               | W   | 0.558      | -            | -                | -                | -         |     3.14 | buda, dgt, HUASOPEEK, Martinez, max   |
|           29 |     5629 | 2024-02-22 | FURIA Esports        | L   | 0.552      | -            | -                | -                | -         |    -4.85 | buda, dgt, HUASOPEEK, Martinez, max   |
|           28 |     5639 | 2024-02-22 | BESTIA               | W   | 0.551      | -            | -                | -                | -         |     2.89 | buda, dgt, HUASOPEEK, Martinez, max   |
|           27 |     5743 | 2024-02-20 | Team Solid           | W   | 0.539      | -            | -                | -                | -         |     1.88 | buda, dgt, HUASOPEEK, Martinez, max   |
|           26 |     5746 | 2024-02-20 | Case Esports         | W   | 0.539      | -            | -                | -                | -         |     2.00 | buda, dgt, HUASOPEEK, Martinez, max   |
|           25 |     5747 | 2024-02-20 | Salão do Corte       | W   | 0.538      | -            | -                | -                | -         |     0.52 | buda, dgt, HUASOPEEK, Martinez, max   |
|           24 |     5812 | 2024-02-19 | Hawks                | W   | 0.532      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, Martinez, max   |
|           23 |     5882 | 2024-02-18 | LA RUGONETA          | L   | 0.523      | -            | -                | -                | -         |   -16.12 | buda, dgt, HUASOPEEK, Martinez, max   |
|           22 |     5972 | 2024-02-16 | Fluxo                | L   | 0.511      | -            | -                | -                | -         |   -13.54 | buda, dgt, HUASOPEEK, Martinez, max   |
|           21 |     6019 | 2024-02-15 | Imperial Esports     | L   | 0.506      | -            | -                | -                | -         |    -3.23 | buda, dgt, HUASOPEEK, Martinez, max   |
|           20 |     6020 | 2024-02-15 | Case Esports         | W   | 0.505      | -            | -                | -                | -         |     1.61 | buda, dgt, HUASOPEEK, Martinez, max   |
|           19 |     6022 | 2024-02-15 | KRÜ Esports          | W   | 0.505      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, Martinez, max   |
|           18 |     6075 | 2024-02-14 | 2Game Esports        | W   | 0.499      | -            | -                | -                | -         |     0.59 | buda, dgt, HUASOPEEK, Martinez, max   |
|           17 |     6189 | 2024-02-12 | LA RUGONETA          | W   | 0.485      | -            | -                | -                | -         |     0.28 | buda, dgt, HUASOPEEK, Martinez, max   |
|           16 |     6449 | 2024-02-04 | Imperial Esports     | L   | 0.432      | -            | -                | -                | -         |    -2.63 | buda, dgt, HUASOPEEK, Martinez, max   |
|           15 |     6484 | 2024-02-03 | w7m esports          | W   | 0.426      | -            | -                | -                | -         |     0.98 | buda, dgt, HUASOPEEK, Martinez, max   |
|           14 |     6581 | 2024-02-02 | Imperial Esports     | W   | 0.419      | 0.143        | 0.372 (0.022)    | -                | -         |    10.74 | buda, dgt, HUASOPEEK, Martinez, max   |
|           13 |     6585 | 2024-02-02 | ODDIK                | W   | 0.418      | -            | -                | -                | -         |     1.94 | buda, dgt, HUASOPEEK, Martinez, max   |
|           12 |     7103 | 2024-01-24 | Imperial Esports     | L   | 0.359      | -            | -                | -                | -         |    -1.97 | buda, dgt, HUASOPEEK, Martinez, max   |
|           11 |     7169 | 2024-01-23 | Fluxo                | W   | 0.352      | -            | -                | -                | -         |     1.82 | buda, dgt, HUASOPEEK, Martinez, max   |
|           10 |     7201 | 2024-01-22 | Galorys              | W   | 0.346      | -            | -                | -                | -         |     0.88 | buda, dgt, HUASOPEEK, Martinez, max   |
|            9 |     7256 | 2024-01-21 | RED Canids           | L   | 0.340      | -            | -                | -                | -         |    -8.79 | buda, dgt, HUASOPEEK, Martinez, max   |
|            8 |     7259 | 2024-01-21 | w7m esports          | W   | 0.339      | -            | -                | -                | -         |     0.65 | buda, dgt, HUASOPEEK, Martinez, max   |
|            7 |     7269 | 2024-01-21 | Sharks Esports       | W   | 0.337      | -            | -                | -                | -         |     1.26 | buda, dgt, HUASOPEEK, Martinez, max   |
|            6 |     7317 | 2024-01-20 | ODDIK                | L   | 0.331      | -            | -                | -                | -         |    -9.09 | buda, dgt, HUASOPEEK, Martinez, max   |
|            5 |     7381 | 2024-01-19 | adalYamigos          | W   | 0.326      | -            | -                | -                | -         |     0.32 | buda, dgt, HUASOPEEK, Martinez, max   |
|            4 |     7397 | 2024-01-19 | Legacy               | L   | 0.324      | -            | -                | -                | -         |    -8.37 | buda, dgt, HUASOPEEK, Martinez, max   |
|            3 |     7447 | 2024-01-18 | MIBR                 | W   | 0.319      | 0.143        | 0.307 (0.014)    | -                | -         |     8.64 | buda, dgt, HUASOPEEK, Martinez, max   |
|            2 |     7508 | 2024-01-17 | MIBR                 | W   | 0.312      | 0.143        | 0.307 (0.014)    | -                | -         |     8.57 | buda, dgt, HUASOPEEK, Martinez, max   |
|            1 |     7542 | 2024-01-17 | RED Canids           | W   | 0.311      | -            | -                | -                | -         |     1.86 | buda, dgt, HUASOPEEK, Martinez, max   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($32,190.55)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $3,920.09      | $3,920.09       |
| 2024-05-16 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-12 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-04-20 |      0.938 | $5,000.00      | $4,689.81       |
| 2024-04-14 |      0.895 | $4,000.00      | $3,580.65       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
