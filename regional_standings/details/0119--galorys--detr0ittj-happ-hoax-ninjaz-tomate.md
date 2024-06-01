### Roster Details<br />
Team Name: Galorys<br />
Roster: detr0ittJ, happ, hoax, ninjaZ, Tomate<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [119](../standings_global.md)<br />
Regional Rank: [24]( ../standings_americas.md)<br />
Final Rank Value:  836.5<br />
<br />
Final Rank Value (836.5) = Starting Rank Value (854.1) + Head To Head Adjustments (-17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.376[<sup>1</sup>](#table2)
- Bounty Collected: 0.347[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.223<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 854.1
- 400 + ( ( 0.223 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 854.1


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
|           85 |       23 | 2024-05-29 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -13.41 | detr0ittJ, happ, hoax, ninjaZ, Tomate    |
|           84 |      183 | 2024-05-27 | Dusty Roots         | W   | 1.000      | 0.384        | -                | 0.425 (0.163)    | 0 (0.000) |     8.71 | detr0ittJ, happ, hoax, ninjaZ, Tomate    |
|           83 |      664 | 2024-05-20 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -14.19 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           82 |      734 | 2024-05-19 | Team Solid          | W   | 1.000      | 0.303        | 0.062 (0.019)    | -                | 0 (0.000) |    16.16 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           81 |      853 | 2024-05-18 | ODDIK               | L   | 1.000      | -            | -                | -                | -         |   -12.19 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           80 |     1133 | 2024-05-15 | Hype Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.00 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           79 |     1153 | 2024-05-15 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -16.62 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           78 |     1228 | 2024-05-14 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -18.14 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           77 |     1235 | 2024-05-14 | Case Esports        | W   | 1.000      | 0.450        | 0.028 (0.013)    | 0.461 (0.208)    | 0 (0.000) |    13.15 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           76 |     1246 | 2024-05-14 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.20 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           75 |     1298 | 2024-05-13 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -3.31 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           74 |     1306 | 2024-05-13 | Yawara E-Sports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.13 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           73 |     1342 | 2024-05-12 | KRÜ Esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.32 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           72 |     1442 | 2024-05-11 | Case Esports        | W   | 1.000      | 0.384        | 0.028 (0.011)    | 0.461 (0.177)    | 0 (0.000) |    15.62 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           71 |     1596 | 2024-05-08 | Corinthians Esports | L   | 1.000      | -            | -                | -                | -         |   -20.84 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           70 |     1602 | 2024-05-08 | Case Esports        | L   | 1.000      | -            | -                | -                | -         |   -16.85 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           69 |     1608 | 2024-05-08 | paiN Gaming         | L   | 1.000      | -            | -                | -                | -         |    -0.75 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           68 |     1621 | 2024-05-08 | paiN Gaming         | L   | 1.000      | -            | -                | -                | -         |    -0.75 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           67 |     1686 | 2024-05-07 | KRÜ Esports         | L   | 1.000      | -            | -                | -                | -         |   -17.40 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           66 |     1768 | 2024-05-05 | w7m esports         | L   | 1.000      | -            | -                | -                | -         |   -20.26 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           65 |     1947 | 2024-05-01 | w7m esports         | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.39 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           64 |     2481 | 2024-04-21 | MIBR Academy        | W   | 0.944      | -            | -                | -                | 0 (0.000) |     8.56 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           63 |     2535 | 2024-04-20 | LaChampionsLiga     | W   | 0.939      | -            | -                | -                | 0 (0.000) |     4.04 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           62 |     2544 | 2024-04-20 | TEAM ORUGA          | W   | 0.938      | -            | -                | -                | -         |     5.16 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           61 |     2895 | 2024-04-16 | Case Esports        | L   | 0.912      | -            | -                | -                | -         |   -16.23 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           60 |     2970 | 2024-04-14 | MIBR                | L   | 0.898      | -            | -                | -                | -         |    -0.68 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           59 |     3043 | 2024-04-13 | Fluxo               | W   | 0.889      | 0.435        | 0.065 (0.025)    | 0.474 (0.183)    | -         |    20.71 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           58 |     3069 | 2024-04-12 | Sharks Esports      | W   | 0.885      | 0.435        | 0.031 (0.012)    | 0.365 (0.140)    | -         |    16.68 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           57 |     3103 | 2024-04-11 | Vikings KR          | L   | 0.878      | -            | -                | -                | -         |   -18.73 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           56 |     3115 | 2024-04-11 | BESTIA              | W   | 0.877      | 0.435        | 0.026 (0.010)    | 0.477 (0.182)    | -         |    15.31 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           55 |     3149 | 2024-04-10 | MIBR                | L   | 0.872      | -            | -                | -                | -         |    -0.60 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           54 |     3153 | 2024-04-10 | MIBR                | L   | 0.872      | -            | -                | -                | -         |    -0.60 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           53 |     3223 | 2024-04-09 | BESTIA              | W   | 0.865      | 0.450        | 0.026 (0.010)    | 0.477 (0.186)    | -         |    16.25 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           52 |     3225 | 2024-04-09 | BESTIA              | L   | 0.865      | -            | -                | -                | -         |   -10.95 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           51 |     3280 | 2024-04-08 | FURIA Academy       | W   | 0.858      | -            | -                | -                | -         |     6.32 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           50 |     3327 | 2024-04-07 | paiN Gaming         | L   | 0.851      | -            | -                | -                | -         |    -0.43 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           49 |     3485 | 2024-04-04 | Intense Game        | W   | 0.831      | -            | -                | -                | -         |     9.35 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           48 |     3733 | 2024-03-28 | Corinthians Esports | W   | 0.784      | -            | -                | -                | -         |     8.10 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           47 |     3770 | 2024-03-27 | Fluxo               | W   | 0.779      | 0.450        | 0.065 (0.023)    | 0.474 (0.166)    | -         |    18.27 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           46 |     3776 | 2024-03-27 | Fluxo               | L   | 0.779      | -            | -                | -                | -         |    -6.11 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           45 |     3845 | 2024-03-26 | 2Game Esports       | W   | 0.773      | -            | -                | -                | -         |     7.54 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           44 |     3850 | 2024-03-26 | 2Game Esports       | W   | 0.772      | -            | -                | -                | -         |     8.00 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           43 |     3857 | 2024-03-26 | MIBR Academy        | W   | 0.771      | -            | -                | -                | -         |     9.33 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           42 |     4064 | 2024-03-21 | Sensei Team         | L   | 0.738      | -            | -                | -                | -         |   -14.65 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           41 |     4079 | 2024-03-21 | 20/70               | W   | 0.738      | -            | -                | -                | -         |     3.34 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           40 |     4485 | 2024-03-13 | RED Canids          | L   | 0.684      | -            | -                | -                | -         |    -5.21 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           39 |     4543 | 2024-03-12 | Hype Esports        | W   | 0.679      | -            | -                | -                | -         |     3.17 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           38 |     4642 | 2024-03-10 | MIBR                | L   | 0.665      | -            | -                | -                | -         |    -0.34 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           37 |     4757 | 2024-03-08 | ODDIK               | W   | 0.650      | 0.435        | 0.017 (0.005)    | 0.494 (0.139)    | -         |    14.30 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           36 |     5588 | 2024-02-23 | Corinthians Esports | L   | 0.559      | -            | -                | -                | -         |   -11.89 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           35 |     5593 | 2024-02-23 | Corinthians Esports | W   | 0.559      | 0.450        | -                | 0.553 (0.139)    | -         |     5.75 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           34 |     5634 | 2024-02-22 | MIBR Academy        | W   | 0.552      | -            | -                | -                | -         |     6.89 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           33 |     5686 | 2024-02-21 | adalYamigos         | L   | 0.546      | -            | -                | -                | -         |   -11.18 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           32 |     5688 | 2024-02-21 | adalYamigos         | L   | 0.546      | -            | -                | -                | -         |   -11.67 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           31 |     5711 | 2024-02-21 | Sharks Esports      | L   | 0.544      | -            | -                | -                | -         |    -6.38 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           30 |     5809 | 2024-02-19 | Flamengo Esports    | L   | 0.533      | -            | -                | -                | -         |   -14.21 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           29 |     5856 | 2024-02-18 | Sharks Esports      | L   | 0.526      | -            | -                | -                | -         |    -6.85 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           28 |     5863 | 2024-02-18 | Case Esports        | W   | 0.525      | -            | -                | -                | -         |     9.43 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           27 |     5926 | 2024-02-17 | Sharks Esports      | W   | 0.518      | 0.303        | 0.031 (0.005)    | -                | -         |    10.24 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           26 |     5938 | 2024-02-17 | Corinthians Esports | W   | 0.517      | -            | -                | -                | -         |     5.07 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           25 |     5971 | 2024-02-16 | Flamengo Esports    | W   | 0.512      | -            | -                | -                | -         |     2.64 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           24 |     5975 | 2024-02-16 | Imperial Esports    | L   | 0.511      | -            | -                | -                | -         |    -0.31 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           23 |     5980 | 2024-02-16 | Imperial Esports    | L   | 0.511      | -            | -                | -                | -         |    -0.31 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           22 |     6034 | 2024-02-15 | 9z Academy          | W   | 0.504      | -            | -                | -                | -         |     4.60 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           21 |     6080 | 2024-02-14 | Team Solid          | L   | 0.499      | -            | -                | -                | -         |    -7.08 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           20 |     6098 | 2024-02-14 | Sharks Esports      | L   | 0.497      | -            | -                | -                | -         |    -5.77 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           19 |     6148 | 2024-02-13 | Case Esports        | L   | 0.491      | -            | -                | -                | -         |    -7.00 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           18 |     6188 | 2024-02-12 | inSanitY Sports     | W   | 0.485      | -            | -                | -                | -         |     2.09 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           17 |     6659 | 2024-02-01 | Projeto KinGui      | W   | 0.411      | -            | -                | -                | -         |     1.76 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           16 |     6830 | 2024-01-29 | Formiguinhas        | W   | 0.391      | -            | -                | -                | -         |     1.01 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           15 |     7022 | 2024-01-26 | ODDIK               | L   | 0.371      | -            | -                | -                | -         |    -4.09 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           14 |     7069 | 2024-01-25 | Sharks Esports      | W   | 0.366      | -            | -                | -                | -         |     7.33 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           13 |     7079 | 2024-01-25 | 2024                | W   | 0.364      | -            | -                | -                | -         |     0.96 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           12 |     7201 | 2024-01-22 | 9z Team             | L   | 0.346      | -            | -                | -                | -         |    -0.88 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           11 |     7306 | 2024-01-20 | Flamengo Esports    | L   | 0.332      | -            | -                | -                | -         |    -8.74 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|           10 |     7382 | 2024-01-19 | Sharks Esports      | L   | 0.326      | -            | -                | -                | -         |    -4.17 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            9 |     7394 | 2024-01-19 | Imperial Esports    | L   | 0.325      | -            | -                | -                | -         |    -0.20 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            8 |     7700 | 2024-01-15 | Legacy              | L   | 0.299      | -            | -                | -                | -         |    -2.72 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            7 |     7773 | 2024-01-13 | Sharks Esports      | L   | 0.286      | -            | -                | -                | -         |    -3.96 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            6 |     7911 | 2024-01-11 | adalYamigos         | L   | 0.273      | -            | -                | -                | -         |    -6.49 | delboNi, f4stzin, piria, shz, zqk        |
|            5 |     7912 | 2024-01-11 | Case Esports        | W   | 0.272      | -            | -                | -                | -         |     2.50 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            4 |     7916 | 2024-01-11 | inSanitY Sports     | W   | 0.272      | -            | -                | -                | -         |     1.07 | detr0ittJ, happ, hoax, koala, ninjaZ     |
|            3 |     7928 | 2024-01-11 | Vex Dragons         | W   | 0.271      | -            | -                | -                | -         |     0.65 | duzzy, marcin, pac, spider, Tineu        |
|            2 |     7981 | 2024-01-10 | Rocket.GG           | W   | 0.266      | -            | -                | -                | -         |     1.86 | arthur, gbr1, MrD, patu, Tatuujey        |
|            1 |     8071 | 2024-01-09 | caradecachorro      | L   | 0.258      | -            | -                | -                | -         |    -7.09 | Demonos, Drummond, fREQ, proSHOW, suNday |

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
