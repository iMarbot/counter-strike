### Roster Details<br />
Team Name: Team Spirit Academy<br />
Roster: alpha, baz, keegaN, Magnojez, notineki<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [128](../standings_global.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
Final Rank Value:  814.7<br />
<br />
Final Rank Value (814.7) = Starting Rank Value (733.9) + Head To Head Adjustments (80.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.293[<sup>1</sup>](#table2)
- Bounty Collected: 0.277[<sup>2</sup>](#table1)
- Opponent Network: 0.088[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 733.9
- 400 + ( ( 0.164 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 733.9


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
|           41 |     4834 | 2024-03-09 | RUBY                      | L   | 0.657      | -            | -                | -                | -         |    -7.20 | alpha, baz, keegaN, Magnojez, notineki    |
|           40 |     4880 | 2024-03-08 | Passion UA                | W   | 0.650      | 0.371        | 0.057 (0.014)    | 1.000 (0.242)    | 0 (0.000) |    14.16 | alpha, baz, keegaN, Magnojez, notineki    |
|           39 |     5433 | 2024-02-29 | Aurora Gaming             | L   | 0.597      | -            | -                | -                | -         |    -0.62 | alpha, baz, keegaN, Magnojez, notineki    |
|           38 |     5462 | 2024-02-28 | 9Pandas                   | L   | 0.591      | -            | -                | -                | -         |    -1.88 | alpha, baz, keegaN, Magnojez, notineki    |
|           37 |     5480 | 2024-02-28 | HAVU Gaming               | W   | 0.590      | -            | -                | -                | 0 (0.000) |     8.24 | alpha, baz, keegaN, Magnojez, notineki    |
|           36 |     5511 | 2024-02-27 | RUBY                      | W   | 0.584      | 0.143        | 0.007 (0.001)    | 0.738 (0.062)    | 0 (0.000) |    12.99 | alpha, baz, keegaN, Magnojez, notineki    |
|           35 |     5524 | 2024-02-27 | brazylijski luz           | W   | 0.584      | 0.143        | 0.013 (0.001)    | 0.514 (0.043)    | 0 (0.000) |     9.54 | alpha, baz, keegaN, Magnojez, notineki    |
|           34 |     5550 | 2024-02-26 | KamKom                    | W   | 0.578      | -            | -                | -                | 0 (0.000) |     1.97 | alpha, baz, keegaN, Magnojez, notineki    |
|           33 |     6154 | 2024-02-16 | kONO.ECF                  | L   | 0.511      | -            | -                | -                | -         |    -5.05 | alpha, baz, keegaN, Magnojez, notineki    |
|           32 |     6223 | 2024-02-15 | Copenhagen Wolves         | W   | 0.504      | 0.371        | -                | 0.387 (0.072)    | 0 (0.000) |     5.22 | alpha, baz, keegaN, Magnojez, notineki    |
|           31 |     6236 | 2024-02-15 | Rhyno Esports             | W   | 0.503      | 0.371        | 0.029 (0.005)    | 0.567 (0.106)    | 0 (0.000) |    12.55 | alpha, baz, keegaN, Magnojez, notineki    |
|           30 |     6392 | 2024-02-12 | Entropiq                  | W   | 0.484      | 0.371        | -                | 0.241 (0.043)    | 0 (0.000) |     5.82 | alpha, baz, keegaN, Magnojez, notineki    |
|           29 |     6401 | 2024-02-12 | Team Secret               | L   | 0.484      | -            | -                | -                | -         |    -9.97 | alpha, baz, keegaN, Magnojez, notineki    |
|           28 |     6514 | 2024-02-08 | The Chosen Few            | W   | 0.458      | 0.371        | -                | 0.262 (0.044)    | 0 (0.000) |     6.90 | alpha, baz, keegaN, Magnojez, notineki    |
|           27 |     6518 | 2024-02-08 | lajtbitexe                | W   | 0.457      | -            | -                | -                | 0 (0.000) |     4.82 | alpha, baz, keegaN, Magnojez, notineki    |
|           26 |     6546 | 2024-02-07 | Sashi Esport              | L   | 0.451      | -            | -                | -                | -         |    -2.49 | alpha, baz, keegaN, Magnojez, notineki    |
|           25 |     6660 | 2024-02-04 | ENTERPRISE esports        | W   | 0.431      | 0.371        | 0.010 (0.002)    | 0.898 (0.144)    | -         |    10.82 | alpha, baz, keegaN, Magnojez, notineki    |
|           24 |     6817 | 2024-02-02 | Lausanne-Sport Esports    | W   | 0.417      | 0.371        | 0.002 (0.000)    | 0.306 (0.047)    | -         |     7.25 | alpha, baz, keegaN, Magnojez, notineki    |
|           23 |     6890 | 2024-02-01 | Sangal Esports            | L   | 0.410      | -            | -                | -                | -         |    -1.58 | alpha, baz, keegaN, Magnojez, notineki    |
|           22 |     6995 | 2024-01-29 | Sprout                    | L   | 0.392      | -            | -                | -                | -         |    -7.88 | alpha, baz, keegaN, Magnojez, notineki    |
|           21 |     7037 | 2024-01-29 | VaselineWorms             | W   | 0.392      | -            | -                | -                | -         |     5.74 | alpha, baz, keegaN, Magnojez, notineki    |
|           20 |     7107 | 2024-01-28 | Alliance                  | W   | 0.382      | 0.371        | 0.004 (0.001)    | 0.529 (0.075)    | -         |     7.84 | alpha, baz, keegaN, Magnojez, notineki    |
|           19 |     7369 | 2024-01-24 | Sangal Esports            | L   | 0.356      | -            | -                | -                | -         |    -1.31 | alpha, keegaN, Magnojez, notineki, S0tF1k |
|           18 |     7739 | 2024-01-18 | Permitta Esports          | L   | 0.316      | -            | -                | -                | -         |    -2.21 | alpha, baz, keegaN, Magnojez, notineki    |
|           17 |     7767 | 2024-01-17 | Ninjas in Pyjamas         | L   | 0.312      | -            | -                | -                | -         |    -4.80 | alpha, baz, keegaN, Magnojez, notineki    |
|           16 |     7807 | 2024-01-17 | Heimo Esports             | W   | 0.311      | 0.143        | 0.011 (0.000)    | -                | -         |     4.63 | alpha, baz, keegaN, Magnojez, notineki    |
|           15 |     7964 | 2024-01-15 | Aurora Young Blud         | L   | 0.296      | -            | -                | -                | -         |    -4.01 | alpha, baz, keegaN, Magnojez, notineki    |
|           14 |     8206 | 2024-01-11 | Lilmix                    | W   | 0.269      | -            | -                | -                | -         |     2.27 | alpha, baz, keegaN, Magnojez, notineki    |
|           13 |     8454 | 2024-01-07 | Verdant                   | W   | 0.242      | -            | -                | -                | -         |     0.98 | alpha, baz, keegaN, Magnojez, notineki    |
|           12 |     8594 | 2023-12-23 | ex-Anonymo Esports        | W   | 0.142      | -            | -                | -                | -         |     2.04 | alpha, baz, keegaN, Magnojez, notineki    |
|           11 |     8632 | 2023-12-21 | ex-Anonymo Esports        | W   | 0.129      | -            | -                | -                | -         |     1.86 | alpha, baz, keegaN, Magnojez, notineki    |
|           10 |     8665 | 2023-12-19 | Natus Vincere Junior      | W   | 0.115      | 0.333        | 0.010 (0.000)    | -                | -         |     2.13 | alpha, baz, keegaN, Magnojez, notineki    |
|            9 |     8894 | 2023-12-16 | The Witchers              | W   | 0.096      | 0.333        | 0.009 (0.000)    | -                | -         |     1.41 | alpha, baz, keegaN, Magnojez, notineki    |
|            8 |     9198 | 2023-12-11 | ex-Turów Zgorzelec Esport | W   | 0.063      | -            | -                | -                | -         |     1.18 | alpha, baz, keegaN, Magnojez, notineki    |
|            7 |     9282 | 2023-12-09 | detoks                    | W   | 0.051      | -            | -                | -                | -         |     0.34 | alpha, baz, keegaN, Magnojez, notineki    |
|            6 |     9438 | 2023-12-07 | FORZE Esports             | L   | 0.037      | -            | -                | -                | -         |    -0.70 | gokushima, Krad, r3salt, shalfey, tN1R    |
|            5 |     9501 | 2023-12-06 | SINNERS Esports           | L   | 0.031      | -            | -                | -                | -         |    -0.16 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO     |
|            4 |     9642 | 2023-12-03 | ARCRED                    | L   | 0.011      | -            | -                | -                | -         |    -0.15 | alpha, baz, keegaN, Magnojez, notineki    |
|            3 |     9648 | 2023-12-03 | Gorillas                  | W   | 0.010      | -            | -                | -                | -         |     0.09 | alpha, baz, keegaN, Magnojez, notineki    |
|            2 |     9725 | 2023-12-02 | Fantazeri                 | W   | 0.004      | -            | -                | -                | -         |     0.02 | alpha, baz, keegaN, Magnojez, notineki    |
|            1 |     9750 | 2023-12-02 | NOM Esports               | W   | 0.004      | -            | -                | -                | -         |     0.05 | alpha, baz, keegaN, Magnojez, notineki    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,150.35)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.142 | $5,000.00      | $708.33         |
| 2023-12-10 |      0.058 | $7,500.00      | $431.25         |
| 2023-12-03 |      0.011 | $1,000.00      | $10.76          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
