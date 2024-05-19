### Roster Details<br />
Team Name: ILIN<br />
Roster: abiraju, bogemtdarf, fineshine, la3euka, lampada<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [239](../standings_global.md)<br />
Regional Rank: [153]( ../standings_europe.md)<br />
Final Rank Value:  673.4<br />
<br />
Final Rank Value (673.4) = Starting Rank Value (548.9) + Head To Head Adjustments (124.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.252[<sup>2</sup>](#table1)
- Opponent Network: 0.048[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.075<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 548.9
- 400 + ( ( 0.075 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 548.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     2726 | 2024-03-04 | Fnatic                  | L   | 0.786      | -            | -                | -                | -         |    -1.11 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           34 |     2743 | 2024-03-04 | Linx Legacy Madagaskar  | W   | 0.786      | -            | -                | -                | 0 (0.000) |     6.32 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           33 |     2791 | 2024-03-03 | Metizport               | L   | 0.779      | -            | -                | -                | -         |    -2.04 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           32 |     2799 | 2024-03-03 | 9INE                    | W   | 0.778      | 0.143        | -                | 0.230 (0.026)    | 0 (0.000) |    11.83 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           31 |     2838 | 2024-03-02 | ILLYRIANS               | W   | 0.773      | 0.143        | 0.001 (0.000)    | 0.308 (0.034)    | 0 (0.000) |    15.52 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           30 |     2864 | 2024-03-02 | RUBY                    | W   | 0.772      | 0.143        | 0.012 (0.001)    | 0.882 (0.097)    | 0 (0.000) |    20.46 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           29 |     2923 | 2024-03-01 | Golden Sword            | W   | 0.764      | -            | -                | -                | 0 (0.000) |     4.67 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           28 |     2956 | 2024-02-29 | Eternal Fire Academy    | L   | 0.758      | -            | -                | -                | -         |    -9.54 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           27 |     2961 | 2024-02-29 | Soda Gaming             | W   | 0.758      | 0.371        | 0.009 (0.003)    | 0.182 (0.051)    | 0 (0.000) |    15.25 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           26 |     2999 | 2024-02-28 | BAKS Esports            | W   | 0.751      | 0.371        | 0.003 (0.001)    | 0.084 (0.023)    | 0 (0.000) |    12.99 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           25 |     3061 | 2024-02-26 | Croatia (Croatian team) | L   | 0.739      | -            | -                | -                | -         |   -14.11 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           24 |     3319 | 2024-02-21 | VaselineWorms           | W   | 0.704      | 0.371        | 0.001 (0.000)    | 0.164 (0.043)    | 0 (0.000) |    13.21 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           23 |     3541 | 2024-02-16 | L&G                     | W   | 0.671      | -            | -                | -                | 0 (0.000) |     9.51 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           22 |     3585 | 2024-02-15 | FORZE Youngsters        | W   | 0.665      | 0.371        | 0.003 (0.001)    | 0.123 (0.030)    | 0 (0.000) |    14.08 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           21 |     3634 | 2024-02-14 | FLuffy Gangsters        | L   | 0.658      | -            | -                | -                | -         |   -10.05 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           20 |     3675 | 2024-02-13 | K10                     | W   | 0.652      | 0.371        | 0.015 (0.004)    | 0.418 (0.101)    | -         |    17.10 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           19 |     3686 | 2024-02-13 | Insilio                 | L   | 0.651      | -            | -                | -                | -         |    -1.87 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           18 |     3730 | 2024-02-12 | Nemiga Gaming           | L   | 0.645      | -            | -                | -                | -         |    -0.28 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           17 |     4182 | 2024-01-29 | Aurora Gaming           | L   | 0.553      | -            | -                | -                | -         |    -0.06 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           16 |     4325 | 2024-01-26 | Rebels Gaming           | L   | 0.531      | -            | -                | -                | -         |    -0.77 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           15 |     4476 | 2024-01-22 | MOUZ NXT                | L   | 0.505      | -            | -                | -                | -         |    -0.77 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           14 |     4741 | 2024-01-17 | Turów Zgorzelec Esport  | L   | 0.472      | -            | -                | -                | -         |    -3.19 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           13 |     4997 | 2024-01-11 | SINNERS Esports         | L   | 0.431      | -            | -                | -                | -         |    -1.18 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           12 |     5005 | 2024-01-11 | Endpoint                | W   | 0.431      | 0.143        | 0.005 (0.000)    | 0.785 (0.048)    | -         |    11.23 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           11 |     5007 | 2024-01-11 | RUSH B (Russian team)   | W   | 0.431      | 0.143        | 0.006 (0.000)    | 0.471 (0.029)    | -         |    10.79 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|           10 |     5008 | 2024-01-11 | FullAliens              | W   | 0.430      | -            | -                | -                | -         |     4.04 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            9 |     5120 | 2024-01-09 | Zero Tenacity           | L   | 0.418      | -            | -                | -                | -         |    -1.23 | abiraju, aviva, bogemtdarf, fineshine, lampada   |
|            8 |     5469 | 2023-12-16 | GenOne                  | L   | 0.258      | -            | -                | -                | -         |    -3.24 | abiraju, aviva, fineshine, KaRnez, lampada       |
|            7 |     6260 | 2023-11-29 | JESTE                   | W   | 0.145      | -            | -                | -                | -         |     1.35 | abiraju, aviva, fineshine, lampada, meteiru      |
|            6 |     6356 | 2023-11-27 | MASONIC Academy         | W   | 0.132      | -            | -                | -                | -         |     1.23 | abiraju, aviva, fineshine, lampada, meteiru      |
|            5 |     6371 | 2023-11-27 | Viperio                 | W   | 0.132      | -            | -                | -                | -         |     2.41 | abiraju, aviva, fineshine, lampada, meteiru      |
|            4 |     6490 | 2023-11-24 | Sashi Esport            | W   | 0.111      | 0.371        | 0.013 (0.001)    | -                | -         |     2.53 | abiraju, aviva, fineshine, lampada, meteiru      |
|            3 |     6777 | 2023-11-17 | Team Spirit Academy     | L   | 0.064      | -            | -                | -                | -         |    -0.40 | abiraju, aviva, fineshine, lampada, meteiru      |
|            2 |     7100 | 2023-11-10 | ENCE Academy            | L   | 0.018      | -            | -                | -                | -         |    -0.09 | abiraju, aviva, fineshine, lampada, redzed       |
|            1 |     7106 | 2023-11-10 | Aurora Young Blud       | L   | 0.017      | -            | -                | -                | -         |    -0.09 | abiraju, aviva, fineshine, lampada, redzed       |

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
