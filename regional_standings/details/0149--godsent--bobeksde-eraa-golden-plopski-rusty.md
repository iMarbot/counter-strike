### Roster Details<br />
Team Name: GODSENT<br />
Roster: bobeksde, eraa, Golden, Plopski, RuStY<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [149](../standings_global.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
Final Rank Value:  775.1<br />
<br />
Final Rank Value (775.1) = Starting Rank Value (800.7) + Head To Head Adjustments (-25.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.388[<sup>1</sup>](#table2)
- Bounty Collected: 0.287[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.044[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 800.7
- 400 + ( ( 0.202 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 800.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |     2375 | 2024-03-12 | MOUZ NXT                    | L   | 0.838      | -            | -                | -                | -             |    -4.40 | bobeksde, eraa, Golden, Plopski, RuStY |
|           58 |     2460 | 2024-03-10 | BLESSED (Ukrainian team)    | W   | 0.825      | 0.371        | 0.018 (0.006)    | 0.781 (0.239)    | false (0.000) |    17.35 | bobeksde, eraa, Golden, Plopski, RuStY |
|           57 |     2497 | 2024-03-09 | Kappa Borr                  | L   | 0.818      | -            | -                | -                | -             |   -20.49 | bobeksde, eraa, Golden, Plopski, RuStY |
|           56 |     2510 | 2024-03-09 | Young Ninjas                | L   | 0.817      | -            | -                | -                | -             |    -6.93 | bobeksde, eraa, Golden, Plopski, RuStY |
|           55 |     2575 | 2024-03-07 | Passion UA                  | L   | 0.805      | -            | -                | -                | -             |    -7.61 | bobeksde, eraa, Golden, Plopski, RuStY |
|           54 |     2636 | 2024-03-06 | Zero Tenacity               | L   | 0.797      | -            | -                | -                | -             |    -8.04 | bobeksde, eraa, Golden, Plopski, RuStY |
|           53 |     2656 | 2024-03-06 | Team Sampi                  | L   | 0.796      | -            | -                | -                | -             |    -7.17 | bobeksde, eraa, Golden, Plopski, RuStY |
|           52 |     2705 | 2024-03-05 | Endpoint                    | L   | 0.791      | -            | -                | -                | -             |   -11.16 | bobeksde, eraa, Golden, Plopski, RuStY |
|           51 |     2795 | 2024-03-03 | Fnatic                      | L   | 0.778      | -            | -                | -                | -             |    -2.46 | bobeksde, eraa, Golden, Plopski, RuStY |
|           50 |     2830 | 2024-03-02 | UNiTY esports (Slovak team) | W   | 0.773      | 0.143        | 0.055 (0.006)    | 0.727 (0.080)    | false (0.000) |    13.16 | bobeksde, eraa, Golden, Plopski, RuStY |
|           49 |     2852 | 2024-03-02 | Turów Zgorzelec Esport      | W   | 0.772      | 0.143        | 0.019 (0.002)    | 0.640 (0.071)    | false (0.000) |    13.31 | bobeksde, eraa, Golden, Plopski, RuStY |
|           48 |     2893 | 2024-03-02 | Permitta Esports            | L   | 0.770      | -            | -                | -                | -             |    -6.17 | bobeksde, eraa, Golden, Plopski, RuStY |
|           47 |     2934 | 2024-02-29 | FLuffy Gangsters            | W   | 0.759      | 0.371        | -                | 0.264 (0.074)    | false (0.000) |     6.19 | bobeksde, eraa, Golden, Plopski, RuStY |
|           46 |     2948 | 2024-02-29 | Ex-sYnck                    | W   | 0.758      | -            | -                | -                | false (0.000) |     5.42 | bobeksde, eraa, Golden, Plopski, RuStY |
|           45 |     3028 | 2024-02-27 | Croatia (Croatian team)     | L   | 0.745      | -            | -                | -                | -             |   -19.01 | bobeksde, eraa, Golden, Plopski, RuStY |
|           44 |     3064 | 2024-02-26 | IMMAPROBLEM                 | W   | 0.739      | -            | -                | -                | false (0.000) |     4.44 | bobeksde, eraa, Golden, Plopski, RuStY |
|           43 |     3241 | 2024-02-22 | GenOne                      | W   | 0.712      | 0.371        | -                | 0.323 (0.086)    | false (0.000) |     5.04 | bobeksde, eraa, Golden, Plopski, RuStY |
|           42 |     3258 | 2024-02-22 | HOTU                        | W   | 0.711      | 0.371        | 0.011 (0.003)    | 0.323 (0.085)    | -             |    11.74 | bobeksde, eraa, Golden, Plopski, RuStY |
|           41 |     3416 | 2024-02-19 | Team Secret                 | W   | 0.691      | 0.371        | -                | 0.368 (0.095)    | -             |     8.19 | bobeksde, eraa, Golden, Plopski, RuStY |
|           40 |     3711 | 2024-02-12 | FORZE Youngsters            | L   | 0.646      | -            | -                | -                | -             |   -12.73 | bobeksde, eraa, Golden, Plopski, RuStY |
|           39 |     3729 | 2024-02-12 | MOUZ NXT                    | L   | 0.645      | -            | -                | -                | -             |    -3.60 | bobeksde, eraa, Golden, Plopski, RuStY |
|           38 |     3741 | 2024-02-11 | DASH                        | W   | 0.639      | -            | -                | -                | -             |     9.24 | bobeksde, eraa, Golden, Plopski, RuStY |
|           37 |     3745 | 2024-02-11 | Sashi Esport                | W   | 0.639      | -            | -                | -                | -             |     4.43 | bobeksde, eraa, Golden, Plopski, RuStY |
|           36 |     3750 | 2024-02-11 | XI Esport                   | W   | 0.638      | -            | -                | -                | -             |     7.82 | bobeksde, eraa, Golden, Plopski, RuStY |
|           35 |     3772 | 2024-02-10 | 0to100                      | L   | 0.631      | -            | -                | -                | -             |   -16.39 | bobeksde, eraa, Golden, Plopski, RuStY |
|           34 |     3829 | 2024-02-08 | Sangal Esports              | W   | 0.617      | 0.384        | -                | 0.350 (0.083)    | -             |     7.64 | bobeksde, eraa, Golden, Plopski, RuStY |
|           33 |     4160 | 2024-01-29 | Permitta Esports            | L   | 0.553      | -            | -                | -                | -             |    -4.15 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           32 |     4170 | 2024-01-29 | DUSTY                       | W   | 0.553      | 0.143        | 0.015 (0.001)    | -                | -             |     8.35 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           31 |     4287 | 2024-01-27 | SINNERS Esports             | L   | 0.537      | -            | -                | -                | -             |    -3.89 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           30 |     4705 | 2024-01-17 | FreeESPI                    | L   | 0.473      | -            | -                | -                | -             |   -10.11 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           29 |     4715 | 2024-01-17 | LODIS                       | W   | 0.472      | -            | -                | -                | -             |     4.70 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           28 |     4941 | 2024-01-12 | Turów Zgorzelec Esport      | L   | 0.439      | -            | -                | -                | -             |    -6.63 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           27 |     5041 | 2024-01-10 | IKLA                        | L   | 0.426      | -            | -                | -                | -             |    -8.39 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           26 |     5707 | 2023-12-11 | Preasy Esport               | L   | 0.223      | -            | -                | -                | -             |    -2.12 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           25 |     5733 | 2023-12-10 | ALTERNATE aTTaX             | L   | 0.217      | -            | -                | -                | -             |    -1.30 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           24 |     5857 | 2023-12-08 | Preasy Esport               | W   | 0.203      | 0.371        | 0.106 (0.008)    | 0.421 (0.032)    | -             |     4.47 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           23 |     5984 | 2023-12-05 | Ex-Anonymo Esports          | L   | 0.185      | -            | -                | -                | -             |    -3.21 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           22 |     6005 | 2023-12-05 | TSM                         | W   | 0.183      | 0.371        | 0.008 (0.001)    | -                | -             |     2.17 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           21 |     6031 | 2023-12-03 | EYEBALLERS                  | L   | 0.172      | -            | -                | -                | -             |    -1.74 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           20 |     6164 | 2023-12-01 | Metizport                   | W   | 0.158      | 0.143        | 0.188 (0.004)    | -                | true (0.158)  |     3.78 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           19 |     6219 | 2023-11-30 | Endpoint                    | W   | 0.150      | 0.371        | -                | 0.785 (0.044)    | -             |     2.67 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           18 |     6242 | 2023-11-29 | INGLORIOUS                  | W   | 0.146      | -            | -                | -                | -             |     2.23 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           17 |     6263 | 2023-11-29 | Kappa Bar                   | W   | 0.145      | -            | -                | -                | -             |     1.54 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           16 |     6328 | 2023-11-28 | The Witchers                | W   | 0.138      | 0.371        | 0.035 (0.002)    | -                | -             |     2.07 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           15 |     6331 | 2023-11-28 | FORZE Esports               | L   | 0.137      | -            | -                | -                | -             |    -2.24 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           14 |     6355 | 2023-11-27 | Aurora Young Blud           | L   | 0.132      | -            | -                | -                | -             |    -1.97 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           13 |     6373 | 2023-11-27 | ARCRED                      | L   | 0.132      | -            | -                | -                | -             |    -1.91 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           12 |     6405 | 2023-11-26 | Apeks Rebels                | W   | 0.123      | -            | -                | -                | true (0.123)  |     1.37 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           11 |     6428 | 2023-11-25 | Outcasts                    | W   | 0.118      | -            | -                | -                | true (0.118)  |     0.35 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|           10 |     6524 | 2023-11-23 | L&G                         | W   | 0.104      | -            | -                | -                | -             |     0.63 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            9 |     6569 | 2023-11-22 | Guild Eagles                | L   | 0.098      | -            | -                | -                | -             |    -0.69 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            8 |     6603 | 2023-11-21 | Pera Esports                | L   | 0.091      | -            | -                | -                | -             |    -0.96 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            7 |     6791 | 2023-11-17 | Alliance                    | W   | 0.063      | 0.384        | 0.017 (0.000)    | -                | -             |     1.23 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            6 |     6819 | 2023-11-16 | RoundsGG                    | W   | 0.058      | -            | -                | -                | -             |     0.74 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            5 |     6828 | 2023-11-16 | Inferus eSports             | W   | 0.058      | -            | -                | -                | -             |     0.29 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            4 |     6850 | 2023-11-16 | GenOne                      | W   | 0.056      | -            | -                | -                | -             |     0.48 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            3 |     6874 | 2023-11-15 | ARCRED                      | L   | 0.052      | -            | -                | -                | -             |    -0.76 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            2 |     6969 | 2023-11-13 | JESTE                       | W   | 0.038      | -            | -                | -                | -             |     0.12 | bobeksde, eraa, Golden, Plopski, Ro1f  |
|            1 |     7056 | 2023-11-11 | Lilmix                      | L   | 0.025      | -            | -                | -                | -             |    -0.49 | bobeksde, eraa, Golden, Plopski, Ro1f  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,166.28)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-12 |      0.231 | $3,000.00      | $693.19         |
| 2023-12-03 |      0.172 | $11,982.61     | $2,061.45       |
| 2023-11-26 |      0.123 | $9,577.99      | $1,180.84       |
| 2023-11-21 |      0.092 | $2,500.00      | $230.79         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
