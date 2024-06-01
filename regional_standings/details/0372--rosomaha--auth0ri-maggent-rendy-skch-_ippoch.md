### Roster Details<br />
Team Name: ROSOMAHA<br />
Roster: auth0ri, Maggent, rendY, skcH, Зippoch<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [372](../standings_global.md)<br />
Regional Rank: [222]( ../standings_europe.md)<br />
Final Rank Value:  585.3<br />
<br />
Final Rank Value (585.3) = Starting Rank Value (606.4) + Head To Head Adjustments (-21.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.210[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 606.4
- 400 + ( ( 0.101 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 606.4


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
|           31 |       81 | 2024-05-29 | EPIC DUDES                | W   | 1.000      | 0.289        | 0.000 (0.000)    | 0.042 (0.012)    | 0 (0.000) |     8.51 | auth0ri, Maggent, rendY, skcH, Зippoch |
|           30 |      882 | 2024-05-18 | Quixal                    | L   | 1.000      | -            | -                | -                | -         |   -11.42 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           29 |      891 | 2024-05-18 | KOMNATA                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     8.62 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           28 |     3268 | 2024-04-09 | Verdant                   | L   | 0.862      | -            | -                | -                | -         |    -3.48 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           27 |     3423 | 2024-04-06 | ex-K10                    | L   | 0.841      | -            | -                | -                | -         |    -5.52 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           26 |     3611 | 2024-04-02 | BRUTE                     | W   | 0.815      | 0.333        | 0.000 (0.000)    | 0.157 (0.043)    | 0 (0.000) |    11.67 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           25 |     3635 | 2024-04-01 | ex-Turów Zgorzelec Esport | L   | 0.808      | -            | -                | -                | -         |    -6.46 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           24 |     3695 | 2024-03-30 | Permitta Esports          | L   | 0.795      | -            | -                | -                | -         |    -3.01 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           23 |     3753 | 2024-03-28 | NOM Esports               | W   | 0.782      | 0.333        | 0.000 (0.000)    | 0.360 (0.094)    | 0 (0.000) |    15.35 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           22 |     3829 | 2024-03-27 | Illuminar Gaming          | L   | 0.776      | -            | -                | -                | -         |    -5.00 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           21 |     3948 | 2024-03-24 | Passion UA                | L   | 0.756      | -            | -                | -                | -         |    -2.55 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           20 |     4182 | 2024-03-19 | Astralis Talent           | L   | 0.723      | -            | -                | -                | -         |    -3.47 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           19 |     4319 | 2024-03-16 | kONO.ECF                  | L   | 0.704      | -            | -                | -                | -         |    -3.02 | auth0ri, Maggent, rendY, skcH, Зippoch |
|           18 |     4388 | 2024-03-15 | GamerLegion Academy       | L   | 0.696      | -            | -                | -                | -         |    -4.85 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           17 |     5136 | 2024-03-02 | DASH                      | L   | 0.611      | -            | -                | -                | -         |    -6.66 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           16 |     6173 | 2024-02-13 | ex-K10                    | L   | 0.488      | -            | -                | -                | -         |    -3.52 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           15 |     7531 | 2024-01-17 | Sprout                    | L   | 0.311      | -            | -                | -                | -         |    -5.35 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           14 |     7540 | 2024-01-17 | ABT Esports               | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.153 (0.007)    | 0 (0.000) |     3.36 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           13 |     7718 | 2024-01-15 | Passion UA                | L   | 0.295      | -            | -                | -                | -         |    -0.92 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           12 |     7802 | 2024-01-13 | WOPA Esport               | L   | 0.282      | -            | -                | -                | -         |    -2.11 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           11 |     7872 | 2024-01-12 | SINNERS Academy           | W   | 0.276      | 0.303        | 0.001 (0.000)    | 0.227 (0.019)    | 0 (0.000) |     4.95 | D0nii, Maggent, rendY, skcH, Зippoch   |
|           10 |     8034 | 2024-01-10 | lajtbitexe                | L   | 0.262      | -            | -                | -                | -         |    -4.00 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            9 |     8211 | 2024-01-06 | Lilmix                    | W   | 0.236      | 0.303        | 0.000 (0.000)    | 0.045 (0.003)    | 0 (0.000) |     3.26 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            8 |     8336 | 2023-12-23 | aimclub                   | L   | 0.142      | -            | -                | -                | -         |    -3.01 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            7 |     8354 | 2023-12-22 | TY                        | L   | 0.136      | -            | -                | -                | -         |    -1.84 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            6 |     8913 | 2023-12-11 | BLUEJAYS Lite             | L   | 0.065      | -            | -                | -                | -         |    -1.39 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            5 |     9104 | 2023-12-08 | The Dice                  | W   | 0.044      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.33 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            4 |     9144 | 2023-12-07 | Preasy Esport             | W   | 0.038      | 0.333        | 0.008 (0.000)    | 0.642 (0.008)    | 0 (0.000) |     0.99 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            3 |     9296 | 2023-12-05 | showmakerz                | L   | 0.024      | -            | -                | -                | -         |    -0.45 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            2 |     9371 | 2023-12-03 | Preasy Esport             | L   | 0.010      | -            | -                | -                | -         |    -0.05 | D0nii, Maggent, rendY, skcH, Зippoch   |
|            1 |     9461 | 2023-12-02 | Team LRP Poland           | L   | 0.004      | -            | -                | -                | -         |    -0.04 | D0nii, Maggent, rendY, skcH, Зippoch   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($51.22)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
