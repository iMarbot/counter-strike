### Roster Details<br />
Team Name: ROSOMAHA<br />
Roster: D0nii, Maggent, rendY, skcH, Зippoch<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [319](../standings_global.md)<br />
Regional Rank: [194]( ../standings_europe.md)<br />
Final Rank Value:  586.1<br />
<br />
Final Rank Value (586.1) = Starting Rank Value (624.3) + Head To Head Adjustments (-38.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.227[<sup>1</sup>](#table2)
- Bounty Collected: 0.200[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 624.3
- 400 + ( ( 0.113 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 624.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     1310 | 2024-04-09 | Verdant                | L   | 1.000      | -            | -                | -                | -             |    -4.21 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           31 |     1426 | 2024-04-06 | K10                    | L   | 1.000      | -            | -                | -                | -             |    -6.49 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           30 |     1589 | 2024-04-02 | BRUTE                  | W   | 0.977      | 0.333        | 0.000 (0.000)    | 0.122 (0.040)    | false (0.000) |    12.22 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           29 |     1611 | 2024-04-01 | Turów Zgorzelec Esport | L   | 0.969      | -            | -                | -                | -             |    -6.83 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           28 |     1655 | 2024-03-30 | Permitta Esports       | L   | 0.956      | -            | -                | -                | -             |    -3.57 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           27 |     1705 | 2024-03-28 | NOM Esports            | W   | 0.943      | 0.333        | 0.000 (0.000)    | 0.374 (0.118)    | false (0.000) |    20.04 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           26 |     1770 | 2024-03-27 | Illuminar Gaming       | L   | 0.937      | -            | -                | -                | -             |    -5.19 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           25 |     1864 | 2024-03-24 | Passion UA             | L   | 0.917      | -            | -                | -                | -             |    -3.11 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           24 |     2070 | 2024-03-19 | Astralis Talent        | L   | 0.884      | -            | -                | -                | -             |    -4.47 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           23 |     2173 | 2024-03-16 | TBA.ECF                | L   | 0.865      | -            | -                | -                | -             |    -8.28 | auth0ri, Maggent, rendY, skcH, Зippoch |
|           22 |     2227 | 2024-03-15 | GamerLegion Academy    | L   | 0.857      | -            | -                | -                | -             |    -5.99 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           21 |     2840 | 2024-03-02 | DASH                   | L   | 0.772      | -            | -                | -                | -             |    -7.73 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           20 |     3694 | 2024-02-13 | K10                    | L   | 0.649      | -            | -                | -                | -             |    -4.06 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           19 |     4710 | 2024-01-17 | Sprout                 | L   | 0.473      | -            | -                | -                | -             |    -9.99 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           18 |     4717 | 2024-01-17 | ABT Esports            | W   | 0.472      | 0.143        | 0.000 (0.000)    | 0.137 (0.009)    | false (0.000) |     4.85 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           17 |     4841 | 2024-01-15 | Passion UA             | L   | 0.456      | -            | -                | -                | -             |    -1.71 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           16 |     4901 | 2024-01-13 | WOPA Esport            | L   | 0.443      | -            | -                | -                | -             |    -4.32 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           15 |     4948 | 2024-01-12 | SINNERS Academy        | W   | 0.437      | 0.303        | 0.003 (0.000)    | 0.296 (0.039)    | false (0.000) |     7.96 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           14 |     5179 | 2024-01-06 | Lilmix                 | W   | 0.397      | 0.303        | 0.000 (0.000)    | 0.098 (0.012)    | false (0.000) |     7.81 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           13 |     5277 | 2023-12-23 | DOXA Gaming            | L   | 0.303      | -            | -                | -                | -             |    -6.47 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           12 |     5290 | 2023-12-22 | TY                     | L   | 0.297      | -            | -                | -                | -             |    -3.82 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           11 |     5688 | 2023-12-11 | BLUEJAYS Lite          | L   | 0.226      | -            | -                | -                | -             |    -3.71 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           10 |     5836 | 2023-12-08 | The Dice               | W   | 0.205      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.44 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            9 |     5870 | 2023-12-07 | Preasy Esport          | W   | 0.199      | 0.333        | 0.007 (0.000)    | 0.525 (0.035)    | false (0.000) |     4.70 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            8 |     5988 | 2023-12-05 | Pungrottorna           | L   | 0.185      | -            | -                | -                | -             |    -3.96 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            7 |     6042 | 2023-12-03 | Preasy Esport          | L   | 0.171      | -            | -                | -                | -             |    -1.33 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            6 |     6102 | 2023-12-02 | FALKE ESPORTS          | L   | 0.165      | -            | -                | -                | -             |    -3.48 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            5 |     6274 | 2023-11-29 | BRUTE                  | W   | 0.144      | 0.289        | 0.000 (0.000)    | 0.005 (0.000)    | false (0.000) |     1.44 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            4 |     6417 | 2023-11-25 | Natus Vincere Youth    | L   | 0.119      | -            | -                | -                | -             |    -1.33 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            3 |     6598 | 2023-11-21 | Sashi Academy          | W   | 0.091      | 0.289        | 0.004 (0.000)    | 0.143 (0.004)    | false (0.000) |     1.58 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            2 |     7098 | 2023-11-10 | Team Universe          | L   | 0.018      | -            | -                | -                | -             |    -0.29 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            1 |     7197 | 2023-11-08 | Dynamo Eclot Thunders  | W   | 0.004      | 0.289        | 0.001 (0.000)    | 0.008 (0.000)    | false (0.000) |     0.06 | D0nii, Maggent, rendY, skcH, Зippoch   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($61.52)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
