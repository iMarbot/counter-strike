### Roster Details<br />
Team Name: Johnny Speeds<br />
Roster: chawzyyy, draken, Lekr0, Ro1f, spooke<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [54](../standings_global.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
Final Rank Value:  1040.4<br />
<br />
Final Rank Value (1040.4) = Starting Rank Value (1041.9) + Head To Head Adjustments (-1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.445[<sup>1</sup>](#table2)
- Bounty Collected: 0.330[<sup>2</sup>](#table1)
- Opponent Network: 0.277[<sup>2</sup>](#table1)
- LAN Wins: 0.212[<sup>2</sup>](#table1)

The average of these factors is 0.316<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1041.9
- 400 + ( ( 0.316 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1041.9


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
|           56 |      236 | 2024-05-26 | Preasy Esport             | W   | 1.000      | 0.371        | 0.008 (0.003)    | 0.705 (0.261)    | 0 (0.000) |     4.65 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           55 |      400 | 2024-05-23 | Begrip Gaming             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.82 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           54 |      533 | 2024-05-22 | Permitta Esports          | W   | 1.000      | 0.371        | 0.025 (0.009)    | 1.000 (0.371)    | 0 (0.000) |     8.23 | chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           53 |     1306 | 2024-05-14 | kONO.ECF                  | L   | 1.000      | -            | -                | -                | -         |   -20.64 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           52 |     1340 | 2024-05-13 | UNiTY esports             | W   | 1.000      | 0.333        | 0.021 (0.007)    | 0.766 (0.255)    | 0 (0.000) |     9.02 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           51 |     1348 | 2024-05-13 | Dynamo Eclot              | W   | 1.000      | 0.333        | 0.097 (0.032)    | 0.940 (0.313)    | 0 (0.000) |    12.48 | bobeksde, draken, Lekr0, Ro1f, spooke     |
|           50 |     1360 | 2024-05-12 | Verdant                   | W   | 1.000      | 0.333        | 0.014 (0.005)    | 1.000 (0.333)    | 0 (0.000) |    11.06 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           49 |     1410 | 2024-05-12 | Preasy Esport             | L   | 1.000      | -            | -                | -                | -         |   -24.13 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           48 |     1434 | 2024-05-11 | Lilmix                    | W   | 1.000      | -            | -                | -                | 1 (1.000) |     7.10 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           47 |     1492 | 2024-05-11 | Flying Angels             | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           46 |     1551 | 2024-05-10 | FAVBET Team               | W   | 1.000      | 0.333        | -                | 0.845 (0.282)    | 0 (0.000) |    12.20 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           45 |     1595 | 2024-05-09 | Viperio                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.72 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           44 |     1599 | 2024-05-09 | NOM Esports               | W   | 1.000      | -            | -                | -                | -         |     4.70 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           43 |     1675 | 2024-05-08 | Verdant                   | L   | 1.000      | -            | -                | -                | -         |   -20.95 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           42 |     1715 | 2024-05-07 | Entropiq                  | W   | 1.000      | -            | -                | -                | -         |     3.85 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           41 |     1763 | 2024-05-06 | Zero Tenacity             | L   | 1.000      | -            | -                | -                | -         |   -16.17 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           40 |     1793 | 2024-05-05 | NOM Esports               | W   | 1.000      | -            | -                | -                | -         |     4.47 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           39 |     1879 | 2024-05-04 | Copenhagen Wolves         | W   | 1.000      | -            | -                | -                | -         |     4.52 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           38 |     1963 | 2024-05-02 | Entropiq                  | W   | 1.000      | -            | -                | -                | -         |     3.53 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           37 |     2037 | 2024-05-01 | FAVBET Team               | L   | 1.000      | -            | -                | -                | -         |   -20.77 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           36 |     2246 | 2024-04-27 | Copenhagen Wolves         | W   | 0.982      | -            | -                | -                | -         |     3.66 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           35 |     2389 | 2024-04-24 | Kappa Bar                 | W   | 0.965      | -            | -                | -                | -         |     2.24 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           34 |     2390 | 2024-04-24 | beaver                    | W   | 0.964      | -            | -                | -                | -         |     0.89 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           33 |     2393 | 2024-04-24 | Begrip Gaming             | W   | 0.964      | -            | -                | -                | -         |     1.94 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           32 |     2844 | 2024-04-18 | UNiTY esports             | W   | 0.922      | 0.333        | 0.021 (0.007)    | 0.766 (0.235)    | -         |     9.22 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           31 |     2984 | 2024-04-16 | Viperio                   | W   | 0.909      | -            | -                | -                | -         |     5.42 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           30 |     3055 | 2024-04-14 | Verdant                   | W   | 0.896      | 0.333        | 0.014 (0.004)    | 1.000 (0.299)    | -         |    10.69 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           29 |     3153 | 2024-04-12 | UNiTY esports             | W   | 0.882      | 0.333        | 0.021 (0.006)    | 0.766 (0.225)    | -         |     8.23 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           28 |     3397 | 2024-04-08 | GamerLegion Academy       | W   | 0.854      | 0.333        | 0.018 (0.005)    | 0.691 (0.197)    | -         |     8.73 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           27 |     3415 | 2024-04-07 | Alliance                  | W   | 0.850      | -            | -                | -                | -         |     8.77 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           26 |     3438 | 2024-04-07 | Metizport                 | L   | 0.848      | -            | -                | -                | -         |    -9.70 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           25 |     3482 | 2024-04-06 | JANO Esports              | W   | 0.843      | -            | -                | -                | -         |     5.22 | bobeksde, Chawzyyy, draken, Lekr0, spooke |
|           24 |     3602 | 2024-04-04 | Illuminar Gaming          | W   | 0.829      | -            | -                | -                | -         |     7.00 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           23 |     3626 | 2024-04-03 | Lilmix                    | L   | 0.824      | -            | -                | -                | -         |   -20.34 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           22 |     3628 | 2024-04-03 | Flying Angels             | W   | 0.824      | -            | -                | -                | -         |     2.82 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           21 |     3689 | 2024-04-02 | showmakerz                | W   | 0.817      | -            | -                | -                | -         |     2.22 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           20 |     4094 | 2024-03-23 | KUUSAMO.gg                | W   | 0.751      | -            | -                | -                | -         |     5.30 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           19 |     4096 | 2024-03-23 | Flying Angels             | W   | 0.750      | -            | -                | -                | -         |     0.91 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           18 |     4099 | 2024-03-23 | Rok paus vid 45           | W   | 0.750      | -            | -                | -                | -         |     0.83 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           17 |     4166 | 2024-03-21 | plusW                     | L   | 0.738      | -            | -                | -                | -         |   -21.61 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           16 |     4671 | 2024-03-12 | regelett                  | W   | 0.678      | -            | -                | -                | -         |     0.67 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           15 |     4848 | 2024-03-09 | Alliance                  | L   | 0.656      | -            | -                | -                | -         |   -14.80 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           14 |     4853 | 2024-03-09 | showmakerz                | W   | 0.656      | -            | -                | -                | -         |     1.59 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           13 |     5081 | 2024-03-05 | B8                        | L   | 0.631      | -            | -                | -                | -         |    -7.27 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           12 |     5091 | 2024-03-05 | Insilio                   | W   | 0.631      | -            | -                | -                | -         |     8.07 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           11 |     5098 | 2024-03-05 | Sashi Esport              | W   | 0.631      | 0.143        | 0.154 (0.014)    | -                | -         |    10.50 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|           10 |     5138 | 2024-03-04 | Runners                   | W   | 0.625      | -            | -                | -                | -         |     1.18 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            9 |     5168 | 2024-03-04 | RUBY                      | W   | 0.625      | -            | -                | -                | -         |     7.68 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            8 |     5364 | 2024-03-02 | Astralis Talent           | L   | 0.608      | -            | -                | -                | -         |   -11.80 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            7 |     5536 | 2024-02-27 | Lilmix                    | W   | 0.583      | -            | -                | -                | -         |     4.79 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            6 |     5552 | 2024-02-26 | ALTERNATE aTTaX           | L   | 0.578      | -            | -                | -                | -         |   -10.84 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            5 |     5779 | 2024-02-23 | ex-Turów Zgorzelec Esport | L   | 0.556      | -            | -                | -                | -         |   -13.94 | Chawzyyy, draken, Lekr0, Ro1f, spooke     |
|            4 |     6727 | 2024-02-03 | Gaimin Gladiators         | L   | 0.424      | -            | -                | -                | -         |    -3.05 | chawzyyy, L00m1, Lekr0, spooke, truth     |
|            3 |     8331 | 2024-01-09 | ENTERPRISE esports        | L   | 0.258      | -            | -                | -                | -         |    -5.02 | Chawzyyy, draken, HugoXD, RuStY, spooke   |
|            2 |     8351 | 2024-01-09 | UNiTY esports             | W   | 0.257      | -            | -                | -                | -         |     2.75 | Chawzyyy, draken, HugoXD, RuStY, spooke   |
|            1 |     8366 | 2024-01-09 | B8                        | W   | 0.257      | -            | -                | -                | -         |     0.39 | Chawzyyy, draken, HugoXD, RuStY, spooke   |

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
