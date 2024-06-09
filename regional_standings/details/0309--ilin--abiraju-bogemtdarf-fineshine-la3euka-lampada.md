### Roster Details<br />
Team Name: ILIN<br />
Roster: abiraju, bogemtdarf, fineshine, la3euka, lampada<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [309](../standings_global.md)<br />
Regional Rank: [193]( ../standings_europe.md)<br />
Final Rank Value:  639.3<br />
<br />
Final Rank Value (639.3) = Starting Rank Value (533.5) + Head To Head Adjustments (105.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.045[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 533.5
- 400 + ( ( 0.066 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 533.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |     5140 | 2024-03-04 | Fnatic                    | L   | 0.625      | -            | -                | -                | -         |    -1.18 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           28 |     5162 | 2024-03-04 | Linx Legacy Madagaskar    | W   | 0.625      | -            | -                | -                | 0 (0.000) |     6.42 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           27 |     5220 | 2024-03-03 | Metizport                 | L   | 0.618      | -            | -                | -                | -         |    -1.90 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           26 |     5232 | 2024-03-03 | 9INE                      | W   | 0.617      | -            | -                | -                | 0 (0.000) |     9.04 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           25 |     5282 | 2024-03-02 | ILLYRIANS                 | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.319 (0.028)    | 0 (0.000) |    13.01 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           24 |     5313 | 2024-03-02 | RUBY                      | W   | 0.611      | 0.143        | 0.007 (0.001)    | 0.738 (0.064)    | 0 (0.000) |    16.75 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           23 |     5390 | 2024-03-01 | Golden Sword              | W   | 0.603      | -            | -                | -                | 0 (0.000) |     4.28 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           22 |     5426 | 2024-02-29 | Eternal Fire Academy      | L   | 0.597      | -            | -                | -                | -         |    -8.24 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           21 |     5431 | 2024-02-29 | Soda Gaming               | W   | 0.597      | 0.371        | 0.000 (0.000)    | 0.119 (0.026)    | 0 (0.000) |    11.17 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           20 |     5484 | 2024-02-28 | BAKS Esports              | W   | 0.590      | 0.371        | 0.001 (0.000)    | 0.171 (0.038)    | 0 (0.000) |     9.85 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           19 |     5556 | 2024-02-26 | Croatia                   | L   | 0.578      | -            | -                | -                | -         |   -11.05 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           18 |     5889 | 2024-02-21 | VaselineWorms             | W   | 0.543      | 0.371        | 0.000 (0.000)    | 0.418 (0.084)    | 0 (0.000) |    11.35 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           17 |     6006 | 2024-02-19 | ex-sYnck                  | W   | 0.530      | 0.371        | 0.000 (0.000)    | 0.255 (0.050)    | 0 (0.000) |    12.43 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           16 |     6169 | 2024-02-16 | L&G                       | W   | 0.510      | -            | -                | -                | 0 (0.000) |     7.25 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           15 |     6224 | 2024-02-15 | FORZE Youngsters          | W   | 0.504      | 0.371        | 0.001 (0.000)    | 0.107 (0.020)    | -         |    10.81 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           14 |     6287 | 2024-02-14 | FLuffy Gangsters          | L   | 0.497      | -            | -                | -                | -         |    -6.74 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           13 |     6338 | 2024-02-13 | ex-K10                    | W   | 0.491      | 0.371        | 0.005 (0.001)    | 0.517 (0.094)    | -         |    12.79 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           12 |     6350 | 2024-02-13 | Insilio                   | L   | 0.490      | -            | -                | -                | -         |    -1.44 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           11 |     6400 | 2024-02-12 | Nemiga Gaming             | L   | 0.484      | -            | -                | -                | -         |    -0.27 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           10 |     7026 | 2024-01-29 | Aurora Gaming             | L   | 0.392      | -            | -                | -                | -         |    -0.08 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            9 |     7269 | 2024-01-26 | Rebels Gaming             | L   | 0.370      | -            | -                | -                | -         |    -0.56 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            8 |     7478 | 2024-01-22 | MOUZ NXT                  | L   | 0.344      | -            | -                | -                | -         |    -0.41 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            7 |     7817 | 2024-01-17 | ex-Turów Zgorzelec Esport | L   | 0.311      | -            | -                | -                | -         |    -2.10 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            6 |     8190 | 2024-01-11 | SINNERS Esports           | L   | 0.270      | -            | -                | -                | -         |    -0.54 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            5 |     8199 | 2024-01-11 | Endpoint                  | W   | 0.270      | 0.143        | 0.012 (0.000)    | 0.770 (0.030)    | -         |     7.72 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            4 |     8203 | 2024-01-11 | RUSH B                    | W   | 0.270      | 0.143        | 0.001 (0.000)    | 0.446 (0.017)    | -         |     6.68 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            3 |     8204 | 2024-01-11 | FullAliens                | W   | 0.269      | -            | -                | -                | -         |     2.74 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            2 |     8380 | 2024-01-09 | Zero Tenacity             | L   | 0.257      | -            | -                | -                | -         |    -0.34 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            1 |     8864 | 2023-12-16 | GenOne                    | L   | 0.097      | -            | -                | -                | -         |    -1.60 | abiraju, aviva, fineshine, KaRnez, lampada       |

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
