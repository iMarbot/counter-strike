### Roster Details<br />
Team Name: BetBoom Team<br />
Roster: KaiR0N-, Magnojez, nafany, s1ren, zorte<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [24](../standings_global.md)<br />
Regional Rank: [17]( ../standings_europe.md)<br />
Final Rank Value:  1378.6<br />
<br />
Final Rank Value (1378.6) = Starting Rank Value (1483.3) + Head To Head Adjustments (-104.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.804[<sup>1</sup>](#table2)
- Bounty Collected: 0.550[<sup>2</sup>](#table1)
- Opponent Network: 0.297[<sup>2</sup>](#table1)
- LAN Wins: 0.533[<sup>2</sup>](#table1)

The average of these factors is 0.546<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1483.3
- 400 + ( ( 0.546 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1483.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           62 |       52 | 2024-05-04 | AMKAL ESPORTS            | L   | 1.000      | -            | -                | -                | -         |   -21.34 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           61 |       70 | 2024-05-04 | 9Pandas                  | W   | 1.000      | 0.435        | -                | 0.661 (0.287)    | 0 (0.000) |     4.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           60 |      125 | 2024-05-03 | Insilio                  | W   | 1.000      | 0.435        | -                | 0.875 (0.380)    | 0 (0.000) |     3.01 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           59 |      209 | 2024-05-01 | EYEBALLERS               | W   | 1.000      | 0.435        | -                | 0.533 (0.232)    | -         |     2.37 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           58 |      253 | 2024-04-30 | 3DMAX                    | L   | 1.000      | -            | -                | -                | -         |   -28.75 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           57 |      408 | 2024-04-26 | M80                      | W   | 1.000      | 0.889        | 0.155 (0.138)    | 0.405 (0.360)    | 1 (1.000) |    11.12 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           56 |      443 | 2024-04-26 | Team Falcons             | W   | 1.000      | 0.889        | 0.431 (0.383)    | -                | 1 (1.000) |    12.75 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           55 |      483 | 2024-04-25 | Team Vitality            | L   | 1.000      | -            | -                | -                | -         |    -2.07 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           54 |      566 | 2024-04-23 | M80                      | W   | 1.000      | 0.889        | 0.155 (0.138)    | 0.405 (0.360)    | 1 (1.000) |    11.09 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           53 |      811 | 2024-04-19 | Cloud9                   | L   | 1.000      | -            | -                | -                | -         |    -4.61 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           52 |      836 | 2024-04-19 | Eternal Fire             | L   | 1.000      | -            | -                | -                | -         |    -2.78 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           51 |      867 | 2024-04-18 | Apeks                    | W   | 1.000      | -            | -                | -                | -         |    12.25 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           50 |      877 | 2024-04-18 | Aloha                    | W   | 1.000      | -            | -                | -                | -         |     0.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           49 |      927 | 2024-04-17 | Verdant                  | W   | 1.000      | -            | -                | -                | -         |     1.98 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           48 |     1073 | 2024-04-14 | 3DMAX                    | W   | 1.000      | -            | -                | -                | -         |     2.52 | kaiR0N-, Magnojez, nafany, s1ren, zorte |
|           47 |     1096 | 2024-04-13 | OG                       | L   | 1.000      | -            | -                | -                | -         |   -16.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           46 |     1107 | 2024-04-13 | Aurora Gaming            | L   | 1.000      | -            | -                | -                | -         |   -11.05 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           45 |     1122 | 2024-04-13 | Team Sampi               | W   | 1.000      | -            | -                | -                | -         |     3.69 | kaiR0N-, Magnojez, nafany, s1ren, zorte |
|           44 |     1166 | 2024-04-11 | Aurora Gaming            | L   | 1.000      | -            | -                | -                | -         |   -12.02 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           43 |     1177 | 2024-04-11 | Ninjas in Pyjamas        | W   | 1.000      | 0.687        | 0.241 (0.166)    | 0.376 (0.258)    | -         |     6.35 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           42 |     1186 | 2024-04-11 | AMKAL ESPORTS            | L   | 1.000      | -            | -                | -                | -         |   -25.46 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           41 |     1230 | 2024-04-10 | Aurora Gaming            | W   | 1.000      | 0.143        | 1.000 (0.143)    | -                | -         |    18.36 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           40 |     1295 | 2024-04-09 | BIG                      | W   | 1.000      | 0.687        | 0.470 (0.323)    | 0.400 (0.275)    | -         |    16.60 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           39 |     1406 | 2024-04-06 | Alliance                 | W   | 1.000      | -            | -                | -                | -         |     1.60 | kaiR0N-, Magnojez, nafany, s1ren, zorte |
|           38 |     1441 | 2024-04-05 | BLEED Esports            | W   | 0.998      | -            | -                | -                | -         |     4.51 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           37 |     1479 | 2024-04-04 | Alliance                 | W   | 0.992      | -            | -                | -                | -         |     1.73 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           36 |     1497 | 2024-04-04 | BLEED Esports            | W   | 0.991      | -            | -                | -                | -         |     4.52 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           35 |     1740 | 2024-03-27 | BLESSED (Ukrainian team) | L   | 0.939      | -            | -                | -                | -         |   -27.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           34 |     1867 | 2024-03-24 | FORZE Esports            | L   | 0.917      | -            | -                | -                | -         |   -24.39 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           33 |     1920 | 2024-03-23 | Fnatic                   | W   | 0.910      | 0.143        | 0.334 (0.043)    | -                | -         |     6.92 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           32 |     1997 | 2024-03-21 | B8                       | W   | 0.897      | -            | -                | -                | -         |     2.80 | KaiR0N-, Magnojez, nafany, s1ren, zorte |
|           31 |     2773 | 2024-03-04 | Gaimin Gladiators        | W   | 0.783      | 0.500        | 0.194 (0.076)    | 0.989 (0.387)    | -         |    10.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           30 |     2790 | 2024-03-03 | Preasy Esport            | L   | 0.779      | -            | -                | -                | -         |   -22.30 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           29 |     2828 | 2024-03-02 | DASH                     | W   | 0.773      | -            | -                | -                | -         |     0.50 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           28 |     2846 | 2024-03-02 | GenOne                   | W   | 0.772      | -            | -                | -                | -         |     0.27 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           27 |     2910 | 2024-03-01 | Preasy Esport            | W   | 0.766      | 0.500        | -                | 0.421 (0.161)    | -         |     2.08 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           26 |     3000 | 2024-02-28 | ALTERNATE aTTaX          | W   | 0.751      | 0.500        | -                | 0.723 (0.271)    | -         |     1.63 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           25 |     3220 | 2024-02-23 | Guild Eagles             | L   | 0.717      | -            | -                | -                | -         |   -20.18 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           24 |     3492 | 2024-02-17 | Eternal Fire             | L   | 0.678      | -            | -                | -                | -         |    -2.94 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           23 |     3532 | 2024-02-16 | Natus Vincere            | L   | 0.671      | -            | -                | -                | -         |    -1.43 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           22 |     3598 | 2024-02-15 | ENTERPRISE esports       | W   | 0.664      | -            | -                | -                | 1 (0.664) |     1.13 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           21 |     3630 | 2024-02-14 | Into The Breach          | W   | 0.658      | -            | -                | -                | 1 (0.658) |     0.76 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           20 |     3635 | 2024-02-14 | Fnatic                   | L   | 0.658      | -            | -                | -                | -         |   -16.60 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           19 |     3826 | 2024-02-08 | Nemiga Gaming            | L   | 0.618      | -            | -                | -                | -         |   -14.18 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           18 |     4076 | 2024-02-01 | Cloud9                   | L   | 0.571      | -            | -                | -                | -         |    -3.36 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           17 |     4118 | 2024-01-31 | Eternal Fire             | L   | 0.564      | -            | -                | -                | -         |    -2.69 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           16 |     4555 | 2024-01-20 | OG                       | W   | 0.491      | 0.143        | 0.594 (0.042)    | -                | -         |     4.41 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           15 |     4602 | 2024-01-19 | Cloud9                   | L   | 0.485      | -            | -                | -                | -         |    -2.46 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           14 |     4654 | 2024-01-18 | BIG                      | W   | 0.478      | -            | -                | -                | -         |     6.79 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           13 |     4661 | 2024-01-18 | Zero Tenacity            | W   | 0.478      | -            | -                | -                | -         |     0.66 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           12 |     5787 | 2023-12-09 | Virtus.pro               | L   | 0.210      | -            | -                | -                | -         |    -1.49 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           11 |     5854 | 2023-12-08 | Cloud9                   | W   | 0.203      | 0.657        | 0.487 (0.065)    | -                | 1 (0.203) |     5.44 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|           10 |     5932 | 2023-12-06 | GamerLegion              | W   | 0.192      | -            | -                | -                | 1 (0.192) |     3.88 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            9 |     5995 | 2023-12-05 | MIBR                     | L   | 0.184      | -            | -                | -                | -         |    -1.54 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            8 |     6399 | 2023-11-26 | Soda Gaming              | L   | 0.124      | -            | -                | -                | -         |    -3.84 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            7 |     6443 | 2023-11-25 | Into The Breach          | W   | 0.117      | -            | -                | -                | -         |     0.09 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            6 |     6712 | 2023-11-18 | MIBR                     | L   | 0.072      | -            | -                | -                | -         |    -0.62 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            5 |     6788 | 2023-11-17 | KOI                      | W   | 0.063      | -            | -                | -                | 1 (0.063) |     0.16 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            4 |     6833 | 2023-11-16 | 9Pandas                  | L   | 0.058      | -            | -                | -                | -         |    -1.59 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            3 |     7132 | 2023-11-09 | SINNERS Esports          | W   | 0.012      | -            | -                | -                | -         |     0.02 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            2 |     7140 | 2023-11-09 | ARCRED                   | W   | 0.011      | -            | -                | -                | -         |     0.01 | danistzz, KaiR0N-, nafany, s1ren, zorte |
|            1 |     7196 | 2023-11-08 | B8                       | W   | 0.005      | -            | -                | -                | -         |     0.00 | danistzz, KaiR0N-, nafany, s1ren, zorte |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($90,465.24)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.57) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-14 |      1.000 | $52,500.00     | $52,500.00      |
| 2024-04-14 |      1.000 | $8,165.54      | $8,165.54       |
| 2024-03-05 |      0.791 | $12,500.00     | $9,891.78       |
| 2024-02-11 |      0.638 | $2,500.00      | $1,595.02       |
| 2023-12-10 |      0.217 | $30,000.00     | $6,497.92       |
| 2023-11-26 |      0.124 | $4,473.51      | $555.25         |
| 2023-11-09 |      0.012 | $22,000.00     | $259.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
