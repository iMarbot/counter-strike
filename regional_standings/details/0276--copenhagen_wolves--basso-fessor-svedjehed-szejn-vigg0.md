### Roster Details<br />
Team Name: Copenhagen Wolves<br />
Roster: Basso, Fessor, Svedjehed, szejn, vigg0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [276](../standings_global.md)<br />
Regional Rank: [172]( ../standings_europe.md)<br />
Final Rank Value:  637.4<br />
<br />
Final Rank Value (637.4) = Starting Rank Value (636.1) + Head To Head Adjustments (1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.283[<sup>2</sup>](#table1)
- Opponent Network: 0.082[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 636.1
- 400 + ( ( 0.119 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 636.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |       68 | 2024-05-04 | WOPA Esport                 | L   | 1.000      | -            | -                | -                | -             |   -11.06 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           42 |       88 | 2024-05-04 | Johnny Speeds               | L   | 1.000      | -            | -                | -                | -             |    -4.84 | Basso, Fessor, Logic, Svedjehed, vigg0    |
|           41 |      258 | 2024-04-30 | TBA.ECF                     | L   | 1.000      | -            | -                | -                | -             |    -9.07 | Basso, Fessor, smF, Svedjehed, szejn      |
|           40 |      266 | 2024-04-29 | Sashi Academy               | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.143 (0.020)    | false (0.000) |    14.39 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           39 |      269 | 2024-04-29 | AscendX Esports             | W   | 1.000      | 0.371        | 0.000 (0.000)    | -                | false (0.000) |     5.54 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           38 |      386 | 2024-04-27 | Johnny Speeds               | L   | 1.000      | -            | -                | -                | -             |    -4.47 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           37 |      468 | 2024-04-25 | BLESSED (Ukrainian team)    | W   | 1.000      | 0.371        | 0.018 (0.007)    | 0.781 (0.290)    | false (0.000) |    27.21 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           36 |      471 | 2024-04-25 | Young Gods                  | L   | 1.000      | -            | -                | -                | -             |   -20.83 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           35 |      511 | 2024-04-24 | Grindas                     | L   | 1.000      | -            | -                | -                | -             |   -12.80 | artie, Basso, Fessor, Svedjehed, vigg0    |
|           34 |      515 | 2024-04-24 | XI Esport                   | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.313 (0.045)    | false (0.000) |    16.29 | Altekz, Basso, Fessor, Svedjehed, vigg0   |
|           33 |      529 | 2024-04-24 | RUBY                        | L   | 1.000      | -            | -                | -                | -             |    -3.78 | artie, Basso, Fessor, Svedjehed, vigg0    |
|           32 |      670 | 2024-04-21 | MASONIC                     | L   | 1.000      | -            | -                | -                | -             |    -6.50 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           31 |      697 | 2024-04-20 | Floki Esport                | W   | 1.000      | -            | -                | -                | true (1.000)  |     6.30 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           30 |      925 | 2024-04-17 | GamerLegion                 | L   | 1.000      | -            | -                | -                | -             |    -0.32 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           29 |     1040 | 2024-04-15 | Preasy Esport               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.525 (0.075)    | false (0.000) |    19.22 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           28 |     1212 | 2024-04-10 | ARROW (German team)         | L   | 1.000      | -            | -                | -                | -             |   -11.41 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           27 |     2406 | 2024-03-11 | XI Esport                   | L   | 0.832      | -            | -                | -                | -             |   -12.04 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           26 |     2422 | 2024-03-11 | Preasy Esport               | L   | 0.832      | -            | -                | -                | -             |    -9.29 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           25 |     2601 | 2024-03-06 | IMMAPROBLEM                 | W   | 0.799      | -            | -                | -                | false (0.000) |     9.54 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           24 |     2608 | 2024-03-06 | Team Atlantic               | W   | 0.799      | -            | -                | -                | false (0.000) |     9.28 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           23 |     2620 | 2024-03-06 | WOPA Esport                 | L   | 0.799      | -            | -                | -                | -             |    -8.83 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           22 |     2954 | 2024-02-29 | UNiTY esports (Slovak team) | W   | 0.758      | 0.371        | 0.055 (0.016)    | 0.727 (0.205)    | false (0.000) |    18.54 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           21 |     2976 | 2024-02-28 | LODIS                       | W   | 0.752      | 0.371        | 0.002 (0.001)    | 0.139 (0.039)    | false (0.000) |    11.60 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           20 |     2986 | 2024-02-28 | Astralis Talent             | L   | 0.752      | -            | -                | -                | -             |    -3.56 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           19 |     2993 | 2024-02-28 | L&G                         | W   | 0.751      | 0.371        | -                | 0.064 (0.018)    | -             |     9.17 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           18 |     3242 | 2024-02-22 | VP.Prodigy                  | L   | 0.712      | -            | -                | -                | -             |    -4.80 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           17 |     3252 | 2024-02-22 | INGLORIOUS                  | L   | 0.712      | -            | -                | -                | -             |    -5.71 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           16 |     3573 | 2024-02-15 | 1win                        | L   | 0.666      | -            | -                | -                | -             |    -7.15 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           15 |     3577 | 2024-02-15 | HOTU                        | L   | 0.665      | -            | -                | -                | -             |    -6.22 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           14 |     3584 | 2024-02-15 | Team Spirit Academy         | L   | 0.665      | -            | -                | -                | -             |    -4.95 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           13 |     3593 | 2024-02-15 | Zero Tenacity               | L   | 0.664      | -            | -                | -                | -             |    -3.28 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           12 |     3834 | 2024-02-08 | WOPA Esport                 | L   | 0.616      | -            | -                | -                | -             |    -6.77 | Basso, mupzG, smF, Svedjehed, szejn       |
|           11 |     3877 | 2024-02-05 | IMMAPROBLEM                 | L   | 0.599      | -            | -                | -                | -             |   -12.37 | Basso, smF, Svedjehed, szejn, vigg0       |
|           10 |     3890 | 2024-02-05 | XI Esport                   | L   | 0.599      | -            | -                | -                | -             |    -8.94 | Basso, smF, Svedjehed, szejn, vigg0       |
|            9 |     3908 | 2024-02-05 | Illuminar Gaming            | L   | 0.597      | -            | -                | -                | -             |    -6.38 | Basso, mupzG, smF, Svedjehed, szejn       |
|            8 |     4066 | 2024-02-01 | Preasy Esport               | W   | 0.572      | 0.143        | 0.007 (0.001)    | 0.525 (0.043)    | -             |    11.41 | Basso, smF, Svedjehed, szejn, vigg0       |
|            7 |     4135 | 2024-01-30 | Astralis Talent             | L   | 0.559      | -            | -                | -                | -             |    -2.98 | Basso, smF, Svedjehed, szejn, vigg0       |
|            6 |     4379 | 2024-01-24 | GenOne                      | W   | 0.519      | 0.371        | -                | 0.323 (0.062)    | -             |     6.22 | fierre, Svedjehed, szejn, tooizera, vigg0 |
|            5 |     4424 | 2024-01-23 | Golden Sword                | W   | 0.512      | -            | -                | -                | -             |     3.06 | Basso, fierre, Svedjehed, szejn, tooizera |
|            4 |     4453 | 2024-01-22 | Sashi Esport                | W   | 0.506      | 0.143        | 0.055 (0.004)    | 0.256 (0.018)    | -             |    11.46 | Basso, smF, Svedjehed, szejn, vigg0       |
|            3 |     4472 | 2024-01-22 | Team Atlantic               | W   | 0.505      | -            | -                | -                | -             |     5.53 | Basso, smF, Svedjehed, szejn, vigg0       |
|            2 |     4714 | 2024-01-17 | Natus Vincere Junior        | L   | 0.472      | -            | -                | -                | -             |    -3.88 | Basso, mupzG, Svedjehed, szejn, vigg0     |
|            1 |     4743 | 2024-01-17 | Lilmix                      | W   | 0.472      | 0.143        | 0.000 (0.000)    | -                | -             |     8.79 | Basso, mupzG, Svedjehed, szejn, vigg0     |

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
