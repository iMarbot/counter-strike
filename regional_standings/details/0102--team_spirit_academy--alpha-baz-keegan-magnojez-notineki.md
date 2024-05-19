### Roster Details<br />
Team Name: Team Spirit Academy<br />
Roster: alpha, baz, keegaN, Magnojez, notineki<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [102](../standings_global.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
Final Rank Value:  863.2<br />
<br />
Final Rank Value (863.2) = Starting Rank Value (800.4) + Head To Head Adjustments (62.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.373[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.116[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 800.4
- 400 + ( ( 0.202 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 800.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           53 |     2495 | 2024-03-09 | RUBY                   | L   | 0.818      | -            | -                | -                | -         |   -11.27 | alpha, baz, keegaN, Magnojez, notineki    |
|           52 |     2531 | 2024-03-08 | Passion UA             | W   | 0.811      | 0.371        | 0.114 (0.034)    | 0.980 (0.295)    | 0 (0.000) |    15.81 | alpha, baz, keegaN, Magnojez, notineki    |
|           51 |     2963 | 2024-02-29 | Aurora Gaming          | L   | 0.758      | -            | -                | -                | -         |    -0.58 | alpha, baz, keegaN, Magnojez, notineki    |
|           50 |     2983 | 2024-02-28 | 9Pandas                | L   | 0.752      | -            | -                | -                | -         |    -3.45 | alpha, baz, keegaN, Magnojez, notineki    |
|           49 |     2997 | 2024-02-28 | HAVU Gaming            | W   | 0.751      | 0.143        | 0.024 (0.003)    | -                | 0 (0.000) |    11.87 | alpha, baz, keegaN, Magnojez, notineki    |
|           48 |     3021 | 2024-02-27 | RUBY                   | W   | 0.745      | 0.143        | -                | 0.882 (0.094)    | 0 (0.000) |    14.68 | alpha, baz, keegaN, Magnojez, notineki    |
|           47 |     3056 | 2024-02-26 | KamKom                 | W   | 0.739      | -            | -                | -                | 0 (0.000) |     1.87 | alpha, baz, keegaN, Magnojez, notineki    |
|           46 |     3529 | 2024-02-16 | TBA.ECF                | L   | 0.672      | -            | -                | -                | -         |   -14.63 | alpha, baz, keegaN, Magnojez, notineki    |
|           45 |     3584 | 2024-02-15 | Copenhagen Wolves      | W   | 0.665      | 0.371        | -                | 0.417 (0.103)    | 0 (0.000) |     4.95 | alpha, baz, keegaN, Magnojez, notineki    |
|           44 |     3595 | 2024-02-15 | Rhyno Esports          | W   | 0.664      | 0.371        | 0.047 (0.012)    | 0.446 (0.110)    | 0 (0.000) |    13.08 | alpha, baz, keegaN, Magnojez, notineki    |
|           43 |     3723 | 2024-02-12 | Entropiq               | W   | 0.645      | 0.371        | -                | 0.436 (0.104)    | 0 (0.000) |     9.55 | alpha, baz, keegaN, Magnojez, notineki    |
|           42 |     3731 | 2024-02-12 | Team Secret            | L   | 0.645      | -            | -                | -                | -         |   -14.30 | alpha, baz, keegaN, Magnojez, notineki    |
|           41 |     3817 | 2024-02-08 | The Chosen Few         | W   | 0.619      | 0.371        | 0.007 (0.002)    | 0.457 (0.105)    | 0 (0.000) |     8.92 | alpha, baz, keegaN, Magnojez, notineki    |
|           40 |     3821 | 2024-02-08 | Lajtbitexe             | W   | 0.618      | -            | -                | -                | 0 (0.000) |     3.60 | alpha, baz, keegaN, Magnojez, notineki    |
|           39 |     3839 | 2024-02-07 | Sashi Esport           | L   | 0.612      | -            | -                | -                | -         |    -4.67 | alpha, baz, keegaN, Magnojez, notineki    |
|           38 |     3919 | 2024-02-04 | ENTERPRISE esports     | W   | 0.592      | 0.371        | 0.039 (0.009)    | 0.476 (0.105)    | 0 (0.000) |    12.65 | alpha, baz, keegaN, Magnojez, notineki    |
|           37 |     4031 | 2024-02-02 | Lausanne-Sport Esports | W   | 0.578      | 0.371        | -                | 0.241 (0.052)    | -         |     8.09 | alpha, baz, keegaN, Magnojez, notineki    |
|           36 |     4083 | 2024-02-01 | Sangal Esports         | L   | 0.571      | -            | -                | -                | -         |   -11.71 | alpha, baz, keegaN, Magnojez, notineki    |
|           35 |     4188 | 2024-01-29 | VaselineWorms          | W   | 0.553      | -            | -                | -                | -         |     5.23 | alpha, baz, keegaN, Magnojez, notineki    |
|           34 |     4231 | 2024-01-28 | Alliance               | W   | 0.543      | 0.371        | 0.017 (0.003)    | 0.729 (0.147)    | -         |    10.10 | alpha, baz, keegaN, Magnojez, notineki    |
|           33 |     4396 | 2024-01-24 | Sangal Esports         | L   | 0.517      | -            | -                | -                | -         |   -11.04 | alpha, keegaN, Magnojez, notineki, S0tF1k |
|           32 |     4674 | 2024-01-18 | Permitta Esports       | L   | 0.477      | -            | -                | -                | -         |    -3.98 | alpha, baz, keegaN, Magnojez, notineki    |
|           31 |     4698 | 2024-01-17 | Ninjas in Pyjamas      | L   | 0.473      | -            | -                | -                | -         |    -7.81 | alpha, baz, keegaN, Magnojez, notineki    |
|           30 |     4732 | 2024-01-17 | Heimo Esports          | W   | 0.472      | -            | -                | -                | -         |     5.51 | alpha, baz, keegaN, Magnojez, notineki    |
|           29 |     4836 | 2024-01-15 | Aurora Young Blud      | L   | 0.457      | -            | -                | -                | -         |    -7.30 | alpha, baz, keegaN, Magnojez, notineki    |
|           28 |     5010 | 2024-01-11 | Lilmix                 | W   | 0.430      | -            | -                | -                | -         |     4.51 | alpha, baz, keegaN, Magnojez, notineki    |
|           27 |     5171 | 2024-01-07 | Verdant                | W   | 0.403      | -            | -                | -                | -         |     1.09 | alpha, baz, keegaN, Magnojez, notineki    |
|           26 |     5278 | 2023-12-23 | Ex-Anonymo Esports     | W   | 0.303      | 0.333        | 0.019 (0.002)    | -                | -         |     4.51 | alpha, baz, keegaN, Magnojez, notineki    |
|           25 |     5299 | 2023-12-21 | Ex-Anonymo Esports     | W   | 0.290      | 0.333        | 0.019 (0.002)    | -                | -         |     4.37 | alpha, baz, keegaN, Magnojez, notineki    |
|           24 |     5324 | 2023-12-19 | Natus Vincere Junior   | W   | 0.276      | 0.333        | 0.025 (0.002)    | -                | -         |     4.92 | alpha, baz, keegaN, Magnojez, notineki    |
|           23 |     5491 | 2023-12-16 | The Witchers           | W   | 0.257      | 0.333        | 0.035 (0.003)    | -                | -         |     3.88 | alpha, baz, keegaN, Magnojez, notineki    |
|           22 |     5701 | 2023-12-11 | Turów Zgorzelec Esport | W   | 0.224      | 0.333        | -                | 0.640 (0.048)    | -         |     3.78 | alpha, baz, keegaN, Magnojez, notineki    |
|           21 |     5887 | 2023-12-07 | FORZE Esports          | L   | 0.199      | -            | -                | -                | -         |    -3.19 | gokushima, Krad, r3salt, shalfey, tN1R    |
|           20 |     5930 | 2023-12-06 | SINNERS Esports        | L   | 0.192      | -            | -                | -                | -         |    -1.56 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO     |
|           19 |     6034 | 2023-12-03 | ARCRED                 | L   | 0.172      | -            | -                | -                | -         |    -2.49 | alpha, baz, keegaN, Magnojez, notineki    |
|           18 |     6039 | 2023-12-03 | 4ERNOTA                | W   | 0.171      | -            | -                | -                | -         |     0.81 | alpha, baz, keegaN, Magnojez, notineki    |
|           17 |     6091 | 2023-12-02 | Fantazeri              | W   | 0.166      | -            | -                | -                | -         |     1.53 | alpha, baz, keegaN, Magnojez, notineki    |
|           16 |     6106 | 2023-12-02 | NOM Esports            | W   | 0.165      | -            | -                | -                | -         |     1.81 | alpha, baz, keegaN, Magnojez, notineki    |
|           15 |     6266 | 2023-11-29 | ARCRED                 | W   | 0.145      | -            | -                | -                | -         |     2.49 | alpha, baz, keegaN, Magnojez, notineki    |
|           14 |     6276 | 2023-11-29 | Entropiq               | W   | 0.144      | -            | -                | -                | -         |     2.25 | alpha, baz, keegaN, Magnojez, notineki    |
|           13 |     6299 | 2023-11-28 | RoundsGG               | L   | 0.139      | -            | -                | -                | -         |    -2.62 | alpha, baz, keegaN, Magnojez, notineki    |
|           12 |     6319 | 2023-11-28 | Wu-Tang Clan           | W   | 0.138      | -            | -                | -                | -         |     0.67 | alpha, baz, keegaN, Magnojez, notineki    |
|           11 |     6671 | 2023-11-19 | The Witchers           | L   | 0.078      | -            | -                | -                | -         |    -1.29 | alpha, baz, keegaN, Magnojez, notineki    |
|           10 |     6701 | 2023-11-18 | FORZE Youngsters       | W   | 0.072      | -            | -                | -                | -         |     0.77 | alpha, baz, keegaN, Magnojez, notineki    |
|            9 |     6710 | 2023-11-18 | GUN5 Esports           | W   | 0.072      | -            | -                | -                | -         |     0.67 | alpha, baz, keegaN, Magnojez, notineki    |
|            8 |     6777 | 2023-11-17 | ILIN                   | W   | 0.064      | -            | -                | -                | -         |     0.40 | alpha, baz, keegaN, Magnojez, notineki    |
|            7 |     6817 | 2023-11-16 | Inferus eSports        | W   | 0.058      | -            | -                | -                | -         |     0.29 | alpha, baz, keegaN, Magnojez, notineki    |
|            6 |     6873 | 2023-11-15 | Gaimin Gladiators      | L   | 0.052      | -            | -                | -                | -         |    -0.04 | alpha, baz, keegaN, Magnojez, notineki    |
|            5 |     6933 | 2023-11-14 | MOUZ NXT               | L   | 0.044      | -            | -                | -                | -         |    -0.22 | alpha, baz, keegaN, Magnojez, notineki    |
|            4 |     6958 | 2023-11-13 | JESTE                  | W   | 0.039      | -            | -                | -                | -         |     0.12 | alpha, baz, keegaN, Magnojez, notineki    |
|            3 |     7141 | 2023-11-09 | CYBERSHOKE Esports     | W   | 0.011      | -            | -                | -                | -         |     0.15 | alpha, baz, keegaN, Magnojez, notineki    |
|            2 |     7153 | 2023-11-09 | Aurora Young Blud      | L   | 0.009      | -            | -                | -                | -         |    -0.14 | alpha, baz, keegaN, Magnojez, notineki    |
|            1 |     7183 | 2023-11-08 | Apeks                  | W   | 0.005      | -            | -                | -                | -         |     0.16 | CacaNito, jkaem, kyxsan, nawwk, sense     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,324.72)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.303 | $5,000.00      | $1,513.66       |
| 2023-12-10 |      0.219 | $7,500.00      | $1,639.24       |
| 2023-12-03 |      0.172 | $1,000.00      | $171.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
