### Roster Details<br />
Team Name: Entropiq<br />
Roster: c0llins, Marix, mwlky, Oxygen, tiziaN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [213](../standings_global.md)<br />
Regional Rank: [143]( ../standings_europe.md)<br />
Final Rank Value:  714.6<br />
<br />
Final Rank Value (714.6) = Starting Rank Value (645.0) + Head To Head Adjustments (69.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.349[<sup>2</sup>](#table1)
- Opponent Network: 0.132[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.0
- 400 + ( ( 0.120 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 645.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |     3747 | 2024-03-28 | UNiTY esports             | L   | 0.783      | -            | -                | -                | -         |    -8.07 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           48 |     4099 | 2024-03-21 | Lilmix                    | L   | 0.736      | -            | -                | -                | -         |   -10.10 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           47 |     4385 | 2024-03-15 | MOUZ NXT                  | L   | 0.696      | -            | -                | -                | -         |    -2.91 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           46 |     4450 | 2024-03-14 | ex-Preasy Esport          | L   | 0.688      | -            | -                | -                | -         |    -4.11 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           45 |     4635 | 2024-03-11 | Dynamo Eclot              | W   | 0.668      | 0.371        | 0.097 (0.024)    | 0.936 (0.232)    | 0 (0.000) |    18.44 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           44 |     4670 | 2024-03-10 | ALTERNATE aTTaX           | W   | 0.663      | 0.371        | 0.052 (0.013)    | 0.679 (0.167)    | 0 (0.000) |    16.22 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           43 |     4738 | 2024-03-09 | Alliance                  | L   | 0.656      | -            | -                | -                | -         |    -6.54 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           42 |     4764 | 2024-03-08 | Passion UA                | L   | 0.649      | -            | -                | -                | -         |    -4.27 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           41 |     4977 | 2024-03-05 | 500                       | L   | 0.629      | -            | -                | -                | -         |    -6.89 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           40 |     5056 | 2024-03-04 | Sashi Esport              | W   | 0.622      | 0.371        | 0.172 (0.040)    | 1.000 (0.230)    | 0 (0.000) |    17.14 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           39 |     5137 | 2024-03-02 | Team Secret               | L   | 0.611      | -            | -                | -                | -         |   -11.05 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           38 |     5230 | 2024-03-01 | FAVBET Team               | L   | 0.604      | -            | -                | -                | -         |    -5.62 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           37 |     5234 | 2024-03-01 | VP.Prodigy                | L   | 0.604      | -            | -                | -                | -         |    -6.70 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           36 |     5335 | 2024-02-28 | Zero Tenacity             | W   | 0.589      | 0.371        | 0.147 (0.032)    | 1.000 (0.219)    | 0 (0.000) |    15.83 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           35 |     5421 | 2024-02-26 | 9INE                      | W   | 0.576      | -            | -                | -                | 0 (0.000) |     5.65 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           34 |     5461 | 2024-02-25 | Team Secret               | W   | 0.569      | -            | -                | -                | 0 (0.000) |     7.96 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           33 |     5623 | 2024-02-23 | Team Sampi                | L   | 0.555      | -            | -                | -                | -         |    -3.61 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           32 |     5663 | 2024-02-22 | Passion UA                | L   | 0.550      | -            | -                | -                | -         |    -3.91 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           31 |     5738 | 2024-02-21 | MOUZ NXT                  | L   | 0.542      | -            | -                | -                | -         |    -1.65 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           30 |     5766 | 2024-02-20 | UNiTY esports             | W   | 0.537      | 0.371        | 0.021 (0.004)    | 0.766 (0.153)    | 0 (0.000) |    12.74 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           29 |     5839 | 2024-02-19 | ex-Anonymo Esports        | W   | 0.530      | 0.371        | -                | 0.204 (0.040)    | 0 (0.000) |     9.42 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           28 |     5853 | 2024-02-19 | brazylijski luz           | W   | 0.528      | 0.333        | 0.013 (0.002)    | 0.490 (0.086)    | 0 (0.000) |    10.95 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           27 |     5927 | 2024-02-17 | The Chosen Few            | W   | 0.518      | -            | -                | -                | 0 (0.000) |    10.37 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           26 |     5955 | 2024-02-17 | ex-Turów Zgorzelec Esport | L   | 0.516      | -            | -                | -                | -         |    -5.97 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           25 |     5987 | 2024-02-16 | Aurora Young Blud         | L   | 0.510      | -            | -                | -                | -         |    -5.60 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           24 |     6045 | 2024-02-15 | CYBERSHOKE Esports        | L   | 0.504      | -            | -                | -                | -         |    -7.07 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           23 |     6109 | 2024-02-14 | brazylijski luz           | W   | 0.496      | 0.333        | 0.013 (0.002)    | 0.490 (0.081)    | -         |    10.62 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           22 |     6160 | 2024-02-13 | GenOne                    | W   | 0.490      | 0.371        | -                | 0.442 (0.080)    | -         |     7.56 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           21 |     6205 | 2024-02-12 | Team Spirit Academy       | L   | 0.484      | -            | -                | -                | -         |    -5.79 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           20 |     6229 | 2024-02-11 | ALTERNATE aTTaX           | L   | 0.478      | -            | -                | -                | -         |    -2.24 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           19 |     6555 | 2024-02-03 | Sangal Esports            | W   | 0.423      | 0.143        | 0.166 (0.010)    | 0.577 (0.035)    | -         |    12.04 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           18 |     6768 | 2024-01-30 | Endpoint                  | L   | 0.396      | -            | -                | -                | -         |    -2.27 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           17 |     6776 | 2024-01-30 | ex-Preasy Esport          | L   | 0.395      | -            | -                | -                | -         |    -2.51 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           16 |     7040 | 2024-01-26 | ex-FLuffy Gangsters       | W   | 0.370      | -            | -                | -                | -         |     3.42 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           15 |     7057 | 2024-01-26 | ALTERNATE aTTaX           | L   | 0.369      | -            | -                | -                | -         |    -4.77 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           14 |     7355 | 2024-01-20 | ex-sYnck                  | L   | 0.329      | -            | -                | -                | -         |    -4.39 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           13 |     7400 | 2024-01-19 | EYEBALLERS                | W   | 0.324      | 0.143        | 0.012 (0.001)    | -                | -         |     8.20 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           12 |     7460 | 2024-01-18 | Team Spirit               | L   | 0.318      | -            | -                | -                | -         |    -0.01 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           11 |     7476 | 2024-01-18 | ex-Preasy Esport          | L   | 0.317      | -            | -                | -                | -         |    -1.96 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|           10 |     7526 | 2024-01-17 | Into The Breach           | L   | 0.312      | -            | -                | -                | -         |    -4.08 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            9 |     7548 | 2024-01-17 | DMS                       | W   | 0.311      | -            | -                | -                | -         |     5.66 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            8 |     8051 | 2024-01-09 | Fnatic                    | L   | 0.259      | -            | -                | -                | -         |    -0.59 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            7 |     8053 | 2024-01-09 | KOI                       | L   | 0.259      | -            | -                | -                | -         |    -1.28 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            6 |     8065 | 2024-01-09 | BLEED Esports             | W   | 0.258      | 0.143        | 0.248 (0.009)    | -                | -         |     7.86 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            5 |     8080 | 2024-01-09 | kONO.ECF                  | W   | 0.258      | -            | -                | -                | -         |     6.23 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            4 |     8093 | 2024-01-09 | Come on now dawg          | W   | 0.257      | -            | -                | -                | -         |     2.56 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            3 |     8118 | 2024-01-09 | The Witchers              | W   | 0.257      | -            | -                | -                | -         |     4.89 | c0llins, Marix, mwlky, Oxygen, tiziaN  |
|            2 |     9340 | 2023-12-04 | ALTERNATE aTTaX           | L   | 0.016      | -            | -                | -                | -         |    -0.20 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |
|            1 |     9514 | 2023-12-02 | Sangal Esports            | L   | 0.002      | -            | -                | -                | -         |    -0.00 | c0llins, Marix, Oxygen, S3NSEY, tiziaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
