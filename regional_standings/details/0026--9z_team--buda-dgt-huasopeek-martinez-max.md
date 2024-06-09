### Roster Details<br />
Team Name: 9z Team<br />
Roster: buda, dgt, HUASOPEEK, Martinez, max<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [26](../standings_global.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
Final Rank Value:  1287.2<br />
<br />
Final Rank Value (1287.2) = Starting Rank Value (1265.9) + Head To Head Adjustments (21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.507[<sup>1</sup>](#table2)
- Bounty Collected: 0.553[<sup>2</sup>](#table1)
- Opponent Network: 0.229[<sup>2</sup>](#table1)
- LAN Wins: 0.415[<sup>2</sup>](#table1)

The average of these factors is 0.426<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1265.9
- 400 + ( ( 0.426 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1265.9


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
|           66 |       38 | 2024-05-29 | Team Vitality        | W   | 1.000      | 0.624        | 0.696 (0.434)    | 0.320 (0.199)    | 1 (1.000) |    30.28 | buda, dgt, HUASOPEEK, Martinez, max   |
|           65 |      150 | 2024-05-27 | Team Liquid          | W   | 1.000      | 0.624        | 0.493 (0.308)    | 0.621 (0.388)    | 1 (1.000) |    28.28 | buda, dgt, HUASOPEEK, Martinez, max   |
|           64 |      165 | 2024-05-27 | MOUZ                 | W   | 1.000      | 0.624        | 1.000 (0.624)    | 0.434 (0.271)    | 1 (1.000) |    31.10 | buda, dgt, HUASOPEEK, Martinez, max   |
|           63 |      443 | 2024-05-22 | Imperial Esports     | L   | 1.000      | -            | -                | -                | -         |    -9.01 | buda, dgt, HUASOPEEK, Martinez, max   |
|           62 |      447 | 2024-05-22 | Imperial Esports     | L   | 1.000      | -            | -                | -                | -         |    -9.70 | buda, dgt, HUASOPEEK, Martinez, max   |
|           61 |      650 | 2024-05-20 | w7m esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.98 | buda, dgt, HUASOPEEK, Martinez, max   |
|           60 |      651 | 2024-05-20 | w7m esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.03 | buda, dgt, HUASOPEEK, Martinez, max   |
|           59 |      655 | 2024-05-20 | BESTIA               | L   | 1.000      | -            | -                | -                | -         |   -26.59 | buda, dgt, HUASOPEEK, Martinez, max   |
|           58 |      670 | 2024-05-20 | BESTIA               | W   | 1.000      | 0.450        | -                | 0.500 (0.225)    | 0 (0.000) |     4.44 | buda, dgt, HUASOPEEK, Martinez, max   |
|           57 |      747 | 2024-05-19 | RED Canids           | L   | 1.000      | -            | -                | -                | -         |   -21.26 | buda, HUASOPEEK, Luken, Martinez, max |
|           56 |      867 | 2024-05-18 | Fluxo                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.73 | buda, HUASOPEEK, Luken, Martinez, max |
|           55 |     1049 | 2024-05-16 | ODDIK                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.90 | buda, dgt, HUASOPEEK, Martinez, max   |
|           54 |     1073 | 2024-05-16 | Imperial Esports     | L   | 1.000      | -            | -                | -                | -         |    -8.28 | buda, dgt, HUASOPEEK, Martinez, max   |
|           53 |     1134 | 2024-05-15 | RED Canids           | W   | 1.000      | 0.450        | 0.076 (0.034)    | 0.536 (0.241)    | 0 (0.000) |     9.04 | buda, dgt, HUASOPEEK, Martinez, max   |
|           52 |     1136 | 2024-05-15 | RED Canids           | L   | 1.000      | -            | -                | -                | -         |   -22.98 | buda, dgt, HUASOPEEK, Martinez, max   |
|           51 |     1143 | 2024-05-15 | Sharks Esports       | W   | 1.000      | 0.384        | -                | 0.381 (0.147)    | -         |     4.72 | buda, dgt, HUASOPEEK, Martinez, max   |
|           50 |     1241 | 2024-05-14 | 2Game Esports        | W   | 1.000      | -            | -                | -                | -         |     1.08 | buda, dgt, HUASOPEEK, Martinez, max   |
|           49 |     1243 | 2024-05-14 | 2Game Esports        | W   | 1.000      | -            | -                | -                | -         |     1.10 | buda, dgt, HUASOPEEK, Martinez, max   |
|           48 |     1256 | 2024-05-14 | Galorys              | W   | 1.000      | 0.384        | -                | 0.600 (0.230)    | -         |     3.28 | buda, dgt, HUASOPEEK, Martinez, max   |
|           47 |     1309 | 2024-05-13 | Galorys              | W   | 1.000      | -            | -                | -                | -         |     3.39 | buda, dgt, HUASOPEEK, Martinez, max   |
|           46 |     1349 | 2024-05-12 | inSanitY Sports      | W   | 1.000      | -            | -                | -                | -         |     1.78 | buda, dgt, HUASOPEEK, Martinez, max   |
|           45 |     1353 | 2024-05-12 | paiN Gaming          | L   | 1.000      | -            | -                | -                | -         |    -6.69 | buda, dgt, HUASOPEEK, Martinez, max   |
|           44 |     1421 | 2024-05-11 | KRÜ Esports          | W   | 1.000      | -            | -                | -                | -         |     3.38 | buda, dgt, HUASOPEEK, Martinez, max   |
|           43 |     1498 | 2024-05-10 | inSanitY Sports      | W   | 1.000      | -            | -                | -                | -         |     1.79 | buda, dgt, HUASOPEEK, Martinez, max   |
|           42 |     1612 | 2024-05-08 | Sharks Esports       | W   | 1.000      | 0.435        | -                | 0.381 (0.166)    | -         |     5.14 | buda, dgt, HUASOPEEK, Martinez, max   |
|           41 |     1744 | 2024-05-06 | Vikings KR           | W   | 1.000      | -            | -                | -                | -         |     1.74 | buda, dgt, HUASOPEEK, Martinez, max   |
|           40 |     1978 | 2024-05-01 | Case Esports         | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.470 (0.212)    | -         |     3.06 | buda, dgt, HUASOPEEK, Martinez, max   |
|           39 |     1983 | 2024-05-01 | Case Esports         | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.470 (0.212)    | -         |     3.15 | buda, dgt, HUASOPEEK, Martinez, max   |
|           38 |     2717 | 2024-04-19 | OG                   | L   | 0.933      | -            | -                | -                | -         |   -13.60 | buda, dgt, HUASOPEEK, Martinez, max   |
|           37 |     2796 | 2024-04-18 | Imperial Esports     | L   | 0.926      | -            | -                | -                | -         |    -6.36 | buda, dgt, HUASOPEEK, Martinez, max   |
|           36 |     2803 | 2024-04-18 | FURIA Esports        | W   | 0.924      | 0.589        | 0.138 (0.075)    | -                | 1 (0.924) |    20.30 | buda, dgt, HUASOPEEK, Martinez, max   |
|           35 |     3391 | 2024-04-08 | HEROIC               | L   | 0.855      | -            | -                | -                | -         |    -2.01 | buda, dgt, HUASOPEEK, Martinez, max   |
|           34 |     3402 | 2024-04-07 | G2 Esports           | L   | 0.853      | -            | -                | -                | -         |    -1.09 | buda, dgt, HUASOPEEK, Martinez, max   |
|           33 |     3895 | 2024-03-27 | Natus Vincere Junior | L   | 0.777      | -            | -                | -                | -         |   -22.14 | buda, dgt, HUASOPEEK, Martinez, max   |
|           32 |     3961 | 2024-03-26 | INFURITY Gaming      | W   | 0.771      | -            | -                | -                | -         |     0.40 | buda, dgt, HUASOPEEK, Martinez, max   |
|           31 |     5747 | 2024-02-23 | FURIA Esports        | W   | 0.559      | -            | -                | -                | -         |    12.63 | buda, dgt, HUASOPEEK, Martinez, max   |
|           30 |     5759 | 2024-02-23 | BESTIA               | W   | 0.558      | -            | -                | -                | -         |     3.10 | buda, dgt, HUASOPEEK, Martinez, max   |
|           29 |     5789 | 2024-02-22 | FURIA Esports        | L   | 0.552      | -            | -                | -                | -         |    -4.86 | buda, dgt, HUASOPEEK, Martinez, max   |
|           28 |     5799 | 2024-02-22 | BESTIA               | W   | 0.551      | -            | -                | -                | -         |     2.85 | buda, dgt, HUASOPEEK, Martinez, max   |
|           27 |     5910 | 2024-02-20 | Team Solid           | W   | 0.539      | -            | -                | -                | -         |     1.89 | buda, dgt, HUASOPEEK, Martinez, max   |
|           26 |     5913 | 2024-02-20 | Case Esports         | W   | 0.539      | -            | -                | -                | -         |     1.99 | buda, dgt, HUASOPEEK, Martinez, max   |
|           25 |     5914 | 2024-02-20 | Salão do Corte       | W   | 0.538      | -            | -                | -                | -         |     0.52 | buda, dgt, HUASOPEEK, Martinez, max   |
|           24 |     5982 | 2024-02-19 | Hawks                | W   | 0.532      | -            | -                | -                | -         |     0.54 | buda, dgt, HUASOPEEK, Martinez, max   |
|           23 |     6055 | 2024-02-18 | LA RUGONETA          | L   | 0.523      | -            | -                | -                | -         |   -16.12 | buda, dgt, HUASOPEEK, Martinez, max   |
|           22 |     6145 | 2024-02-16 | Fluxo                | L   | 0.511      | -            | -                | -                | -         |   -13.40 | buda, dgt, HUASOPEEK, Martinez, max   |
|           21 |     6195 | 2024-02-15 | Imperial Esports     | L   | 0.506      | -            | -                | -                | -         |    -3.24 | buda, dgt, HUASOPEEK, Martinez, max   |
|           20 |     6196 | 2024-02-15 | Case Esports         | W   | 0.505      | -            | -                | -                | -         |     1.60 | buda, dgt, HUASOPEEK, Martinez, max   |
|           19 |     6198 | 2024-02-15 | KRÜ Esports          | W   | 0.505      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, Martinez, max   |
|           18 |     6256 | 2024-02-14 | 2Game Esports        | W   | 0.499      | -            | -                | -                | -         |     0.58 | buda, dgt, HUASOPEEK, Martinez, max   |
|           17 |     6374 | 2024-02-12 | LA RUGONETA          | W   | 0.485      | -            | -                | -                | -         |     0.28 | buda, dgt, HUASOPEEK, Martinez, max   |
|           16 |     6651 | 2024-02-04 | Imperial Esports     | L   | 0.432      | -            | -                | -                | -         |    -2.64 | buda, dgt, HUASOPEEK, Martinez, max   |
|           15 |     6687 | 2024-02-03 | w7m esports          | W   | 0.426      | -            | -                | -                | -         |     0.96 | buda, dgt, HUASOPEEK, Martinez, max   |
|           14 |     6784 | 2024-02-02 | Imperial Esports     | W   | 0.419      | 0.143        | 0.372 (0.022)    | -                | -         |    10.73 | buda, dgt, HUASOPEEK, Martinez, max   |
|           13 |     6788 | 2024-02-02 | ODDIK                | W   | 0.418      | -            | -                | -                | -         |     1.93 | buda, dgt, HUASOPEEK, Martinez, max   |
|           12 |     7332 | 2024-01-24 | Imperial Esports     | L   | 0.359      | -            | -                | -                | -         |    -1.98 | buda, dgt, HUASOPEEK, Martinez, max   |
|           11 |     7405 | 2024-01-23 | Fluxo                | W   | 0.352      | -            | -                | -                | -         |     1.80 | buda, dgt, HUASOPEEK, Martinez, max   |
|           10 |     7442 | 2024-01-22 | Galorys              | W   | 0.346      | -            | -                | -                | -         |     0.86 | buda, dgt, HUASOPEEK, Martinez, max   |
|            9 |     7499 | 2024-01-21 | RED Canids           | L   | 0.340      | -            | -                | -                | -         |    -8.82 | buda, dgt, HUASOPEEK, Martinez, max   |
|            8 |     7502 | 2024-01-21 | w7m esports          | W   | 0.339      | -            | -                | -                | -         |     0.64 | buda, dgt, HUASOPEEK, Martinez, max   |
|            7 |     7512 | 2024-01-21 | Sharks Esports       | W   | 0.337      | -            | -                | -                | -         |     1.27 | buda, dgt, HUASOPEEK, Martinez, max   |
|            6 |     7560 | 2024-01-20 | ODDIK                | L   | 0.331      | -            | -                | -                | -         |    -9.10 | buda, dgt, HUASOPEEK, Martinez, max   |
|            5 |     7625 | 2024-01-19 | adalYamigos          | W   | 0.326      | -            | -                | -                | -         |     0.32 | buda, dgt, HUASOPEEK, Martinez, max   |
|            4 |     7641 | 2024-01-19 | Legacy               | L   | 0.324      | -            | -                | -                | -         |    -8.38 | buda, dgt, HUASOPEEK, Martinez, max   |
|            3 |     7694 | 2024-01-18 | MIBR                 | W   | 0.319      | 0.143        | 0.307 (0.014)    | -                | -         |     8.61 | buda, dgt, HUASOPEEK, Martinez, max   |
|            2 |     7757 | 2024-01-17 | MIBR                 | W   | 0.312      | 0.143        | 0.307 (0.014)    | -                | -         |     8.54 | buda, dgt, HUASOPEEK, Martinez, max   |
|            1 |     7791 | 2024-01-17 | RED Canids           | W   | 0.311      | -            | -                | -                | -         |     1.83 | buda, dgt, HUASOPEEK, Martinez, max   |

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
