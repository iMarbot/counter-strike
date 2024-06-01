### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: chawzyyy, draken, Lekr0, Ro1f, spooke<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [53](../standings_global.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
Final Rank Value:  1038.9<br />
<br />
Final Rank Value (1038.9) = Starting Rank Value (1039.3) + Head To Head Adjustments (-0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.331[<sup>2</sup>](#table1)
- Opponent Network: 0.269[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.314<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1039.3
- 400 + ( ( 0.314 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1039.3


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
|           56 |      228 | 2024-05-26 | Preasy Esport             | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.642 (0.238)    | 0 (0.000) |     4.64 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           55 |      392 | 2024-05-23 | Begrip Gaming             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.82 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           54 |      526 | 2024-05-22 | Permitta Esports          | W   | 1.000      | 0.371        | 0.029 (0.011)    | 1.000 (0.371)    | 0 (0.000) |     7.74 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           53 |     1295 | 2024-05-14 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -20.93 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           52 |     1328 | 2024-05-13 | UNiTY esports             | W   | 1.000      | 0.333        | 0.021 (0.007)    | 0.766 (0.255)    | 0 (0.000) |     9.28 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           51 |     1336 | 2024-05-13 | Dynamo Eclot              | W   | 1.000      | 0.333        | 0.097 (0.032)    | 0.936 (0.312)    | 0 (0.000) |    13.15 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           50 |     1348 | 2024-05-12 | Verdant                   | W   | 1.000      | 0.333        | 0.014 (0.005)    | 1.000 (0.333)    | 0 (0.000) |    10.81 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           49 |     1397 | 2024-05-12 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -24.18 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           48 |     1421 | 2024-05-11 | Lilmix                    | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.94 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           47 |     1479 | 2024-05-11 | Flying Angels             | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.53 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           46 |     1536 | 2024-05-10 | FAVBET Team               | W   | 1.000      | 0.333        | -                | 0.666 (0.222)    | 0 (0.000) |    13.03 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           45 |     1579 | 2024-05-09 | Viperio                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.71 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           44 |     1583 | 2024-05-09 | NOM Esports               | W   | 1.000      | -            | -                | -                | -         |     4.72 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           43 |     1657 | 2024-05-08 | Verdant                   | L   | 1.000      | -            | -                | -                | -         |   -21.30 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           42 |     1695 | 2024-05-07 | Entropiq                  | W   | 1.000      | -            | -                | -                | -         |     3.82 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           41 |     1740 | 2024-05-06 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |   -16.27 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           40 |     1770 | 2024-05-05 | NOM Esports               | W   | 1.000      | -            | -                | -                | -         |     4.47 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           39 |     1856 | 2024-05-04 | Copenhagen Wolves         | W   | 1.000      | -            | -                | -                | -         |     3.24 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           38 |     1936 | 2024-05-02 | Entropiq                  | W   | 1.000      | -            | -                | -                | -         |     3.49 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           37 |     2006 | 2024-05-01 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |   -19.48 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           36 |     2211 | 2024-04-27 | Copenhagen Wolves         | W   | 0.982      | -            | -                | -                | -         |     2.80 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           35 |     2348 | 2024-04-24 | Kappa Bar                 | W   | 0.965      | -            | -                | -                | -         |     2.25 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           34 |     2349 | 2024-04-24 | beaver                    | W   | 0.964      | -            | -                | -                | -         |     0.90 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           33 |     2352 | 2024-04-24 | Begrip Gaming             | W   | 0.964      | -            | -                | -                | -         |     1.94 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           32 |     2788 | 2024-04-18 | UNiTY esports             | W   | 0.922      | 0.333        | 0.021 (0.007)    | 0.766 (0.235)    | -         |     9.72 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |     2923 | 2024-04-16 | Viperio                   | W   | 0.909      | -            | -                | -                | -         |     5.38 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |     2990 | 2024-04-14 | Verdant                   | W   | 0.896      | 0.333        | 0.014 (0.004)    | 1.000 (0.299)    | -         |    10.20 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |     3087 | 2024-04-12 | UNiTY esports             | W   | 0.882      | 0.333        | 0.021 (0.006)    | 0.766 (0.225)    | -         |     8.23 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           28 |     3316 | 2024-04-08 | GamerLegion Academy       | W   | 0.854      | 0.333        | 0.018 (0.005)    | 0.691 (0.197)    | -         |     8.80 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     3334 | 2024-04-07 | Alliance                  | W   | 0.850      | -            | -                | -                | -         |     8.85 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           26 |     3355 | 2024-04-07 | Metizport                 | L   | 0.848      | -            | -                | -                | -         |    -9.33 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           25 |     3399 | 2024-04-06 | JANO Esports              | W   | 0.843      | -            | -                | -                | -         |     5.26 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           24 |     3516 | 2024-04-04 | Illuminar Gaming          | W   | 0.829      | -            | -                | -                | -         |     7.01 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     3539 | 2024-04-03 | Lilmix                    | L   | 0.824      | -            | -                | -                | -         |   -20.04 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     3541 | 2024-04-03 | Flying Angels             | W   | 0.824      | -            | -                | -                | -         |     2.85 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     3599 | 2024-04-02 | showmakerz                | W   | 0.817      | -            | -                | -                | -         |     2.18 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     3997 | 2024-03-23 | KUUSAMO.gg                | W   | 0.751      | -            | -                | -                | -         |     5.33 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     3999 | 2024-03-23 | Flying Angels             | W   | 0.750      | -            | -                | -                | -         |     0.92 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     4002 | 2024-03-23 | Rok paus vid 45           | W   | 0.750      | -            | -                | -                | -         |     0.84 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           17 |     4068 | 2024-03-21 | plusW                     | L   | 0.738      | -            | -                | -                | -         |   -21.57 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     4551 | 2024-03-12 | regelett                  | W   | 0.678      | -            | -                | -                | -         |     0.68 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     4723 | 2024-03-09 | Alliance                  | L   | 0.656      | -            | -                | -                | -         |   -14.72 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     4728 | 2024-03-09 | showmakerz                | W   | 0.656      | -            | -                | -                | -         |     1.56 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     4942 | 2024-03-05 | B8                        | L   | 0.631      | -            | -                | -                | -         |    -7.27 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     4951 | 2024-03-05 | Insilio                   | W   | 0.631      | -            | -                | -                | -         |     8.13 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     4955 | 2024-03-05 | Sashi Esport              | W   | 0.631      | 0.143        | 0.172 (0.015)    | -                | -         |    10.72 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     4992 | 2024-03-04 | Runners                   | W   | 0.625      | -            | -                | -                | -         |     1.19 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     5022 | 2024-03-04 | RUBY                      | W   | 0.625      | -            | -                | -                | -         |     7.67 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     5215 | 2024-03-02 | Astralis Talent           | L   | 0.608      | -            | -                | -                | -         |   -11.81 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     5382 | 2024-02-27 | Lilmix                    | W   | 0.583      | -            | -                | -                | -         |     5.21 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            6 |     5395 | 2024-02-26 | ALTERNATE aTTaX           | L   | 0.578      | -            | -                | -                | -         |   -10.31 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            5 |     5619 | 2024-02-23 | ex-Turów Zgorzelec Esport | L   | 0.556      | -            | -                | -                | -         |   -14.19 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            4 |     6524 | 2024-02-03 | Gaimin Gladiators         | L   | 0.424      | -            | -                | -                | -         |    -3.05 | chawzyyy, L00m1, Lekr0, spooke, truth     |
|            3 |     8077 | 2024-01-09 | ENTERPRISE esports        | L   | 0.258      | -            | -                | -                | -         |    -5.18 | Chawzyyy, draken, HugoXD, RuStY, spooke   |
|            2 |     8097 | 2024-01-09 | UNiTY esports             | W   | 0.257      | -            | -                | -                | -         |     2.77 | Chawzyyy, draken, HugoXD, RuStY, spooke   |
|            1 |     8112 | 2024-01-09 | B8                        | W   | 0.257      | -            | -                | -                | -         |     0.40 | Chawzyyy, draken, HugoXD, RuStY, spooke   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($16,968.53)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-16 |      1.000 | $500.00        | $500.00         |
| 2024-05-13 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-05-11 |      1.000 | $4,142.17      | $4,142.17       |
| 2024-04-18 |      0.922 | $6,000.00      | $5,530.00       |
| 2024-04-07 |      0.850 | $936.59        | $796.37         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
