### Roster Details<br />
Team Name: Betera Esports<br />
Roster: alex666, lollipop21k, MaSvAl, nifee, sad<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [94](../standings_global.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
Final Rank Value:  882.2<br />
<br />
Final Rank Value (882.2) = Starting Rank Value (801.3) + Head To Head Adjustments (80.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.339[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 801.3
- 400 + ( ( 0.197 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 801.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |     3497 | 2024-04-04 | SAW                       | L   | 0.830      | -            | -                | -                | -         |    -1.56 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           40 |     3546 | 2024-04-03 | System5                   | W   | 0.824      | 0.500        | 0.002 (0.001)    | 0.069 (0.029)    | 0 (0.000) |     6.26 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           39 |     3740 | 2024-03-28 | Monte                     | W   | 0.784      | 0.500        | 0.181 (0.071)    | 0.363 (0.142)    | 0 (0.000) |    22.54 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           38 |     3807 | 2024-03-27 | Verdant                   | L   | 0.777      | -            | -                | -                | -         |    -9.49 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           37 |     3854 | 2024-03-26 | PARIVISION                | W   | 0.771      | 0.143        | -                | 0.329 (0.036)    | 0 (0.000) |    15.07 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           36 |     4381 | 2024-03-15 | Pera Esports              | W   | 0.697      | 0.500        | 0.028 (0.010)    | 0.574 (0.200)    | 0 (0.000) |    12.28 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           35 |     4478 | 2024-03-13 | RUSH B                    | L   | 0.684      | -            | -                | -                | -         |   -12.86 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           34 |     4956 | 2024-03-05 | Insilio                   | L   | 0.631      | -            | -                | -                | -         |    -7.16 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           33 |     4984 | 2024-03-04 | HAVU Gaming               | W   | 0.625      | -            | -                | -                | 0 (0.000) |     7.19 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           32 |     5015 | 2024-03-04 | Sangal Esports            | W   | 0.625      | 0.143        | 0.166 (0.015)    | 0.577 (0.051)    | 0 (0.000) |    14.06 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           31 |     5401 | 2024-02-26 | Sashi Esport              | L   | 0.578      | -            | -                | -                | -         |    -3.86 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           30 |     6255 | 2024-02-10 | kONO.ECF                  | L   | 0.471      | -            | -                | -                | -         |    -6.46 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           29 |     6258 | 2024-02-10 | Viperio                   | W   | 0.471      | -            | -                | -                | 0 (0.000) |     3.61 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           28 |     6265 | 2024-02-10 | Team Rayvenclaw           | W   | 0.470      | -            | -                | -                | 0 (0.000) |     1.82 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           27 |     6309 | 2024-02-09 | Monte Gen                 | W   | 0.463      | 0.333        | 0.007 (0.001)    | 0.301 (0.046)    | 0 (0.000) |     7.03 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           26 |     6345 | 2024-02-08 | BIG Academy               | W   | 0.455      | 0.333        | 0.003 (0.000)    | -                | 0 (0.000) |     5.35 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           25 |     6385 | 2024-02-06 | Team Secret               | W   | 0.443      | 0.333        | -                | 0.230 (0.034)    | -         |     3.63 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           24 |     6572 | 2024-02-03 | ex-Anonymo Esports        | W   | 0.422      | 0.333        | 0.002 (0.000)    | 0.204 (0.029)    | -         |     5.27 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           23 |     6839 | 2024-01-29 | esmagaB                   | W   | 0.389      | 0.333        | 0.008 (0.001)    | 0.460 (0.060)    | -         |     6.89 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           22 |     7536 | 2024-01-17 | FreeESPI                  | L   | 0.311      | -            | -                | -                | -         |    -7.59 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           21 |     7683 | 2024-01-16 | Nemiga Gaming             | L   | 0.304      | -            | -                | -                | -         |    -0.78 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           20 |     7785 | 2024-01-13 | ex-sYnck                  | L   | 0.284      | -            | -                | -                | -         |    -5.83 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           19 |     7792 | 2024-01-13 | esmagaB                   | W   | 0.283      | -            | -                | -                | -         |     4.82 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           18 |     7836 | 2024-01-12 | ex-Turów Zgorzelec Esport | W   | 0.278      | -            | -                | -                | -         |     3.77 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           17 |     7859 | 2024-01-12 | premghouls                | W   | 0.278      | -            | -                | -                | -         |     0.77 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           16 |     7947 | 2024-01-11 | ex-Anonymo Esports        | L   | 0.270      | -            | -                | -                | -         |    -5.52 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           15 |     7949 | 2024-01-11 | Alliance                  | W   | 0.270      | -            | -                | -                | -         |     4.84 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           14 |     8005 | 2024-01-10 | ex-Turów Zgorzelec Esport | W   | 0.265      | -            | -                | -                | -         |     3.63 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           13 |     8100 | 2024-01-09 | KOI                       | L   | 0.257      | -            | -                | -                | -         |    -2.50 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           12 |     8130 | 2024-01-09 | lajtbitexe                | W   | 0.257      | -            | -                | -                | -         |     1.99 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           11 |     8193 | 2024-01-07 | TY                        | W   | 0.243      | -            | -                | -                | -         |     2.34 | alex666, lollipop21k, MaSvAl, nifee, sad |
|           10 |     8214 | 2024-01-06 | ex-Anonymo Esports        | W   | 0.236      | -            | -                | -                | -         |     2.71 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            9 |     8232 | 2024-01-04 | MOUZ NXT                  | W   | 0.223      | 0.354        | 0.157 (0.012)    | 0.950 (0.075)    | -         |     5.98 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            8 |     8372 | 2023-12-21 | brazylijski luz           | W   | 0.129      | 0.354        | 0.013 (0.001)    | -                | -         |     2.11 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            7 |     8387 | 2023-12-20 | Viperio                   | W   | 0.122      | -            | -                | -                | -         |     0.90 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            6 |     8464 | 2023-12-17 | INGLORIOUS                | L   | 0.103      | -            | -                | -                | -         |    -1.88 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            5 |     8583 | 2023-12-16 | BAKS Esports              | W   | 0.098      | -            | -                | -                | -         |     0.85 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            4 |     8604 | 2023-12-16 | FreeESPI                  | W   | 0.097      | -            | -                | -                | -         |     0.74 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            3 |     9367 | 2023-12-03 | ARCRED                    | L   | 0.010      | -            | -                | -                | -         |    -0.17 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            2 |     9446 | 2023-12-02 | Lausanne-Sport Esports    | W   | 0.004      | -            | -                | -                | -         |     0.03 | alex666, lollipop21k, MaSvAl, nifee, sad |
|            1 |     9469 | 2023-12-02 | showmakerz                | W   | 0.004      | -            | -                | -                | -         |     0.02 | alex666, lollipop21k, MaSvAl, nifee, sad |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,964.17)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-02-09 |      0.463 | $6,000.00      | $2,776.67       |
| 2024-01-07 |      0.243 | $9,000.00      | $2,187.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
