### Roster Details<br />
Team Name: Sangal Esports<br />
Roster: jottAAA, LNZ, SaMey, xfl0ud, yxngstxr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [117](../standings_global.md)<br />
Regional Rank: [84]( ../standings_europe.md)<br />
Final Rank Value:  825.6<br />
<br />
Final Rank Value (825.6) = Starting Rank Value (669.8) + Head To Head Adjustments (155.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.178[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.8
- 400 + ( ( 0.136 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 669.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      612 | 2024-04-22 | BLEED Esports       | L   | 1.000      | -            | -                | -                | -         |    -3.80 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           34 |      666 | 2024-04-21 | Alliance            | W   | 1.000      | 0.500        | 0.017 (0.008)    | 0.729 (0.364)    | 0 (0.000) |    18.02 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           33 |      777 | 2024-04-20 | JANO Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.98 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           32 |      827 | 2024-04-19 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |    -2.50 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           31 |      975 | 2024-04-17 | 9Pandas             | W   | 1.000      | 0.500        | 0.085 (0.043)    | 0.661 (0.330)    | 0 (0.000) |    26.84 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           30 |      998 | 2024-04-16 | Zero Tenacity       | W   | 1.000      | 0.143        | 0.095 (0.014)    | 1.000 (0.143)    | 0 (0.000) |    21.58 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           29 |     1052 | 2024-04-15 | Aurora Young Blud   | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.68 | jottAAA, LNZ, SaMey, xfl0ud, yxngstxr   |
|           28 |     2506 | 2024-03-09 | Zero Tenacity       | L   | 0.817      | -            | -                | -                | -         |    -6.21 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           27 |     2579 | 2024-03-07 | 500                 | L   | 0.804      | -            | -                | -                | -         |    -7.91 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           26 |     2742 | 2024-03-04 | Betera Esports      | L   | 0.786      | -            | -                | -                | -         |    -9.05 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           25 |     2771 | 2024-03-04 | Team Sampi          | W   | 0.783      | 0.384        | 0.108 (0.033)    | 0.709 (0.213)    | 0 (0.000) |    19.24 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           24 |     2805 | 2024-03-03 | Rebels Gaming       | L   | 0.778      | -            | -                | -                | -         |    -2.46 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           23 |     2899 | 2024-03-02 | HAVU Gaming         | W   | 0.770      | 0.500        | 0.024 (0.009)    | 0.213 (0.082)    | 0 (0.000) |    15.60 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           22 |     2955 | 2024-02-29 | Rebels Gaming       | L   | 0.758      | -            | -                | -                | -         |    -2.25 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           21 |     3004 | 2024-02-28 | Alliance            | L   | 0.750      | -            | -                | -                | -         |    -7.38 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           20 |     3094 | 2024-02-25 | Sashi Esport        | W   | 0.732      | 0.143        | 0.193 (0.020)    | 1.000 (0.105)    | 0 (0.000) |    20.18 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           19 |     3374 | 2024-02-20 | Permitta Esports    | L   | 0.697      | -            | -                | -                | -         |    -3.81 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           18 |     3551 | 2024-02-16 | Astralis Talent     | W   | 0.669      | 0.333        | 0.030 (0.007)    | 0.613 (0.137)    | 0 (0.000) |    16.70 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           17 |     3736 | 2024-02-12 | Permitta Esports    | L   | 0.643      | -            | -                | -                | -         |    -3.64 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           16 |     3829 | 2024-02-08 | GODSENT             | L   | 0.617      | -            | -                | -                | -         |    -7.64 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           15 |     3868 | 2024-02-06 | Preasy Esport       | L   | 0.603      | -            | -                | -                | -         |    -3.65 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           14 |     3938 | 2024-02-04 | ALTERNATE aTTaX     | W   | 0.589      | 0.371        | 0.110 (0.024)    | 0.723 (0.158)    | 0 (0.000) |    15.63 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           13 |     3987 | 2024-02-03 | Entropiq            | L   | 0.584      | -            | -                | -                | -         |    -6.84 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           12 |     4003 | 2024-02-03 | Metizport           | L   | 0.583      | -            | -                | -                | -         |    -2.68 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           11 |     4083 | 2024-02-01 | Team Spirit Academy | W   | 0.571      | 0.371        | 0.021 (0.004)    | 0.422 (0.089)    | -         |    11.71 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|           10 |     4095 | 2024-02-01 | ALTERNATE aTTaX     | W   | 0.570      | 0.384        | 0.110 (0.024)    | 0.723 (0.158)    | -         |    15.52 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            9 |     4191 | 2024-01-29 | Sashi Esport        | L   | 0.553      | -            | -                | -                | -         |    -2.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            8 |     4228 | 2024-01-28 | Gaimin Gladiators   | L   | 0.543      | -            | -                | -                | -         |    -0.32 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            7 |     4396 | 2024-01-24 | Team Spirit Academy | W   | 0.517      | -            | -                | -                | -         |    11.04 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            6 |     5089 | 2024-01-09 | BLEED Esports       | L   | 0.418      | -            | -                | -                | -         |    -1.01 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            5 |     5118 | 2024-01-09 | EC Kostroma         | W   | 0.418      | -            | -                | -                | -         |     2.31 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            4 |     5456 | 2023-12-16 | GenOne              | L   | 0.259      | -            | -                | -                | -         |    -4.60 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            3 |     5468 | 2023-12-16 | Insilio             | W   | 0.258      | -            | -                | -                | -         |     6.53 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            2 |     6140 | 2023-12-02 | Entropiq            | W   | 0.163      | -            | -                | -                | -         |     3.41 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |
|            1 |     6329 | 2023-11-28 | ALTERNATE aTTaX     | L   | 0.137      | -            | -                | -                | -         |    -0.40 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
