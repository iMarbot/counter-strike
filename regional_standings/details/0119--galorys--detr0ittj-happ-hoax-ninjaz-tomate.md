### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [119](../standings_global.md)<br />
Regional Rank: [24]( ../standings_americas.md)<br />
Final Rank Value:  839.7<br />
<br />
Final Rank Value (839.7) = Starting Rank Value (850.0) + Head To Head Adjustments (-10.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.344[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.0
- 400 + ( ( 0.221 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 850.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           86 |       23 | 2024-05-29 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -13.83 | detr0ittJ, happ, hoax, ninjaZ, Tomate    |
|           85 |      191 | 2024-05-27 | Dusty Roots         | W   | 1.000      | 0.384        | -                | 0.425 (0.163)    | 0 (0.000) |     9.01 | detr0ittJ, happ, hoax, ninjaZ, Tomate    |
|           84 |      675 | 2024-05-20 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -14.51 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           83 |      746 | 2024-05-19 | Team Solid          | W   | 1.000      | 0.303        | 0.062 (0.019)    | -                | 0 (0.000) |    15.63 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           82 |      865 | 2024-05-18 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -12.55 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           81 |     1142 | 2024-05-15 | Hype Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.73 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           80 |     1162 | 2024-05-15 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -16.89 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           79 |     1238 | 2024-05-14 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -18.43 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           78 |     1245 | 2024-05-14 | Case Esports        | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.470 (0.212)    | 0 (0.000) |    12.84 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           77 |     1256 | 2024-05-14 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.28 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           76 |     1309 | 2024-05-13 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.39 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           75 |     1317 | 2024-05-13 | Yawara E-Sports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.91 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           74 |     1354 | 2024-05-12 | KRÜ Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.94 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           73 |     1455 | 2024-05-11 | Case Esports        | W   | 1.000      | 0.384        | 0.028 (0.011)    | 0.470 (0.181)    | 0 (0.000) |    15.24 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           72 |     1616 | 2024-05-08 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -16.31 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           71 |     1622 | 2024-05-08 | paiN Gaming         | L   | 1.000      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           70 |     1638 | 2024-05-08 | paiN Gaming         | L   | 1.000      | -            | -                | -                | -         |    -0.70 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           69 |     1705 | 2024-05-07 | KRÜ Esports         | L   | 1.000      | -            | -                | -                | -         |   -16.81 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           68 |     1791 | 2024-05-05 | w7m esports         | L   | 1.000      | -            | -                | -                | -         |   -20.09 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           67 |     1974 | 2024-05-01 | w7m esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.57 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           66 |     2534 | 2024-04-21 | MIBR Academy        | W   | 0.944      | -            | -                | -                | 0 (0.000) |     9.05 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           65 |     2588 | 2024-04-20 | LaChampionsLiga     | W   | 0.939      | -            | -                | -                | 0 (0.000) |     4.36 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           64 |     2597 | 2024-04-20 | TEAM ORUGA          | W   | 0.938      | -            | -                | -                | -         |     5.56 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           63 |     2953 | 2024-04-16 | Case Esports        | L   | 0.912      | -            | -                | -                | -         |   -15.59 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           62 |     3035 | 2024-04-14 | MIBR                | L   | 0.898      | -            | -                | -                | -         |    -0.62 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           61 |     3109 | 2024-04-13 | Fluxo               | W   | 0.889      | 0.435        | 0.065 (0.025)    | 0.474 (0.183)    | -         |    21.30 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           60 |     3135 | 2024-04-12 | Sharks Esports      | W   | 0.885      | 0.435        | 0.012 (0.004)    | -                | -         |     9.84 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           59 |     3169 | 2024-04-11 | Vikings KR          | L   | 0.878      | -            | -                | -                | -         |   -18.40 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           58 |     3183 | 2024-04-11 | BESTIA              | W   | 0.877      | 0.435        | 0.026 (0.010)    | 0.500 (0.190)    | -         |    15.24 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           57 |     3220 | 2024-04-10 | MIBR                | L   | 0.872      | -            | -                | -                | -         |    -0.57 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           56 |     3224 | 2024-04-10 | MIBR                | L   | 0.872      | -            | -                | -                | -         |    -0.57 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           55 |     3301 | 2024-04-09 | BESTIA              | W   | 0.865      | 0.450        | 0.026 (0.010)    | 0.500 (0.195)    | -         |    16.18 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           54 |     3303 | 2024-04-09 | BESTIA              | L   | 0.865      | -            | -                | -                | -         |   -11.02 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           53 |     3360 | 2024-04-08 | FURIA Academy       | W   | 0.858      | -            | -                | -                | -         |     6.59 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           52 |     3408 | 2024-04-07 | paiN Gaming         | L   | 0.851      | -            | -                | -                | -         |    -0.41 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           51 |     3570 | 2024-04-04 | Intense Game        | W   | 0.831      | -            | -                | -                | -         |     9.71 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           50 |     3827 | 2024-03-28 | Corinthians Esports | W   | 0.784      | -            | -                | -                | -         |     8.09 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           49 |     3863 | 2024-03-27 | Fluxo               | W   | 0.779      | 0.450        | 0.065 (0.023)    | 0.474 (0.166)    | -         |    18.76 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           48 |     3869 | 2024-03-27 | Fluxo               | L   | 0.779      | -            | -                | -                | -         |    -5.60 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           47 |     3942 | 2024-03-26 | 2Game Esports       | W   | 0.773      | -            | -                | -                | -         |     7.86 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           46 |     3947 | 2024-03-26 | 2Game Esports       | W   | 0.772      | -            | -                | -                | -         |     8.35 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           45 |     3954 | 2024-03-26 | MIBR Academy        | W   | 0.771      | -            | -                | -                | -         |     9.75 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           44 |     4162 | 2024-03-21 | Sensei Team         | L   | 0.738      | -            | -                | -                | -         |   -14.24 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           43 |     4177 | 2024-03-21 | 20/70               | W   | 0.738      | -            | -                | -                | -         |     3.58 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           42 |     4600 | 2024-03-13 | RED Canids          | L   | 0.684      | -            | -                | -                | -         |    -4.96 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           41 |     4662 | 2024-03-12 | Hype Esports        | W   | 0.679      | -            | -                | -                | -         |     3.40 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           40 |     4765 | 2024-03-10 | MIBR                | L   | 0.665      | -            | -                | -                | -         |    -0.32 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           39 |     4884 | 2024-03-08 | ODDIK               | W   | 0.650      | 0.435        | 0.017 (0.005)    | 0.494 (0.139)    | -         |    14.63 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           38 |     5637 | 2024-02-24 | Sharks Esports      | L   | 0.566      | -            | -                | -                | -         |    -5.66 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           37 |     5646 | 2024-02-24 | Sharks Esports      | L   | 0.566      | -            | -                | -                | -         |    -5.92 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           36 |     5748 | 2024-02-23 | Corinthians Esports | L   | 0.559      | -            | -                | -                | -         |   -12.20 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           35 |     5753 | 2024-02-23 | Corinthians Esports | W   | 0.559      | 0.450        | -                | 0.458 (0.115)    | -         |     5.43 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           34 |     5794 | 2024-02-22 | MIBR Academy        | W   | 0.552      | -            | -                | -                | -         |     6.99 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           33 |     5848 | 2024-02-21 | adalYamigos         | L   | 0.546      | -            | -                | -                | -         |   -11.14 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           32 |     5850 | 2024-02-21 | adalYamigos         | L   | 0.546      | -            | -                | -                | -         |   -11.63 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           31 |     5874 | 2024-02-21 | Sharks Esports      | L   | 0.544      | -            | -                | -                | -         |    -6.55 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           30 |     5979 | 2024-02-19 | Flamengo Esports    | L   | 0.533      | -            | -                | -                | -         |   -14.19 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           29 |     6028 | 2024-02-18 | Sharks Esports      | L   | 0.526      | -            | -                | -                | -         |    -7.06 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           28 |     6035 | 2024-02-18 | Case Esports        | W   | 0.525      | 0.303        | 0.028 (0.005)    | -                | -         |     9.49 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           27 |     6099 | 2024-02-17 | Sharks Esports      | W   | 0.518      | -            | -                | -                | -         |    10.03 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           26 |     6111 | 2024-02-17 | Corinthians Esports | W   | 0.517      | 0.435        | -                | 0.458 (0.103)    | -         |     4.82 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           25 |     6144 | 2024-02-16 | Flamengo Esports    | W   | 0.512      | -            | -                | -                | -         |     2.65 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           24 |     6148 | 2024-02-16 | Imperial Esports    | L   | 0.511      | -            | -                | -                | -         |    -0.30 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           23 |     6153 | 2024-02-16 | Imperial Esports    | L   | 0.511      | -            | -                | -                | -         |    -0.30 | detr0ittJ, happ, hoax, ninjaZ, piria     |
|           22 |     6211 | 2024-02-15 | 9z Academy          | W   | 0.504      | -            | -                | -                | -         |     4.62 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           21 |     6261 | 2024-02-14 | Team Solid          | L   | 0.499      | -            | -                | -                | -         |    -6.99 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           20 |     6279 | 2024-02-14 | Sharks Esports      | L   | 0.497      | -            | -                | -                | -         |    -5.70 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           19 |     6332 | 2024-02-13 | Case Esports        | L   | 0.491      | -            | -                | -                | -         |    -6.94 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           18 |     6373 | 2024-02-12 | inSanitY Sports     | W   | 0.485      | -            | -                | -                | -         |     2.12 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           17 |     6864 | 2024-02-01 | Projeto KinGui      | W   | 0.411      | -            | -                | -                | -         |     1.78 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           16 |     7046 | 2024-01-29 | Formiguinhas        | W   | 0.391      | -            | -                | -                | -         |     1.52 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           15 |     7244 | 2024-01-26 | ODDIK               | L   | 0.371      | -            | -                | -                | -         |    -4.05 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           14 |     7295 | 2024-01-25 | Sharks Esports      | W   | 0.366      | -            | -                | -                | -         |     7.40 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           13 |     7307 | 2024-01-25 | 2024                | W   | 0.364      | -            | -                | -                | -         |     0.98 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           12 |     7442 | 2024-01-22 | 9z Team             | L   | 0.346      | -            | -                | -                | -         |    -0.86 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           11 |     7549 | 2024-01-20 | Flamengo Esports    | L   | 0.332      | -            | -                | -                | -         |    -8.71 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           10 |     7626 | 2024-01-19 | Sharks Esports      | L   | 0.326      | -            | -                | -                | -         |    -4.10 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            9 |     7638 | 2024-01-19 | Imperial Esports    | L   | 0.325      | -            | -                | -                | -         |    -0.19 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            8 |     7949 | 2024-01-15 | Legacy              | L   | 0.299      | -            | -                | -                | -         |    -2.69 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            7 |     8026 | 2024-01-13 | Sharks Esports      | L   | 0.286      | -            | -                | -                | -         |    -3.89 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            6 |     8164 | 2024-01-11 | adalYamigos         | L   | 0.273      | -            | -                | -                | -         |    -6.47 | delboNi, f4stzin, piria, shz, zqk        |
|            5 |     8165 | 2024-01-11 | Case Esports        | W   | 0.272      | -            | -                | -                | -         |     2.54 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            4 |     8169 | 2024-01-11 | inSanitY Sports     | W   | 0.272      | -            | -                | -                | -         |     1.09 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            3 |     8181 | 2024-01-11 | Vex Dragons         | W   | 0.271      | -            | -                | -                | -         |     0.67 | duzzy, marcin, pac, spider, Tineu        |
|            2 |     8235 | 2024-01-10 | Rocket.GG           | W   | 0.266      | -            | -                | -                | -         |     1.89 | arthur, gbr1, MrD, patu, Tatuujey        |
|            1 |     8325 | 2024-01-09 | caradecachorro      | L   | 0.258      | -            | -                | -                | -         |    -7.07 | Demonos, Drummond, fREQ, proSHOW, suNday |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,639.87)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-15 |      0.904 | $5,000.00      | $4,522.22       |
| 2024-04-11 |      0.878 | $591.98        | $519.96         |
| 2024-02-22 |      0.552 | $1,418.01      | $782.27         |
| 2024-02-21 |      0.544 | $1,500.00      | $815.42         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
