### Roster Details<br />
Team Name: V1dar Gaming<br />
Roster: 1mpala, 4X1s, Alv, torox, xm1nd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [243](../standings_global.md)<br />
Regional Rank: [155]( ../standings_europe.md)<br />
Final Rank Value:  670.8<br />
<br />
Final Rank Value (670.8) = Starting Rank Value (580.2) + Head To Head Adjustments (90.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.069[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.091<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 580.2
- 400 + ( ( 0.091 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 580.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      115 | 2024-05-03 | RUBY            | L   | 1.000      | -            | -                | -                | -             |    -6.08 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           34 |      144 | 2024-05-02 | ThunderFlash    | W   | 1.000      | 0.371        | 0.023 (0.009)    | 0.274 (0.102)    | false (0.000) |    22.79 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           33 |      181 | 2024-05-01 | 1win            | L   | 1.000      | -            | -                | -                | -             |    -8.69 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           32 |      204 | 2024-05-01 | B8              | L   | 1.000      | -            | -                | -                | -             |    -4.04 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           31 |      247 | 2024-04-30 | MOUZ NXT        | L   | 1.000      | -            | -                | -                | -             |    -3.56 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           30 |      280 | 2024-04-29 | Los kogutos     | L   | 1.000      | -            | -                | -                | -             |   -20.22 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           29 |      432 | 2024-04-26 | VP.Prodigy      | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.762 (0.109)    | false (0.000) |    20.48 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           28 |      492 | 2024-04-25 | 9INE Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.171 (0.024)    | false (0.000) |    14.63 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           27 |      551 | 2024-04-24 | VP.Prodigy      | L   | 1.000      | -            | -                | -                | -             |    -9.79 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           26 |     2449 | 2024-03-10 | MOUZ NXT        | L   | 0.825      | -            | -                | -                | -             |    -2.52 | 1mpala, 4X1s, Alv, lom1k, torox |
|           25 |     2628 | 2024-03-06 | Endpoint        | L   | 0.798      | -            | -                | -                | -             |    -6.34 | 1mpala, 4X1s, Alv, lom1k, torox |
|           24 |     2946 | 2024-02-29 | Lilmix          | L   | 0.758      | -            | -                | -                | -             |   -13.06 | 1mpala, 4X1s, Alv, lom1k, torox |
|           23 |     3019 | 2024-02-27 | FORZE Esports   | L   | 0.745      | -            | -                | -                | -             |    -2.61 | 1mpala, 4X1s, Alv, lom1k, torox |
|           22 |     3030 | 2024-02-27 | Sashi Esport    | W   | 0.745      | 0.143        | 0.193 (0.021)    | 1.000 (0.106)    | false (0.000) |    20.96 | 1mpala, 4X1s, Alv, lom1k, torox |
|           21 |     3060 | 2024-02-26 | Rustec          | W   | 0.739      | 0.143        | 0.006 (0.001)    | -                | false (0.000) |    11.46 | 1mpala, 4X1s, Alv, lom1k, torox |
|           20 |     3213 | 2024-02-23 | GUN5 Esports    | W   | 0.718      | 0.371        | -                | 0.218 (0.058)    | false (0.000) |    10.57 | 1mpala, 4X1s, Alv, lom1k, torox |
|           19 |     3306 | 2024-02-21 | L&G             | W   | 0.705      | -            | -                | -                | false (0.000) |     8.08 | 1mpala, 4X1s, Alv, lom1k, torox |
|           18 |     3408 | 2024-02-19 | BAKS Esports    | W   | 0.692      | 0.371        | 0.003 (0.001)    | 0.084 (0.022)    | false (0.000) |    11.52 | 1mpala, 4X1s, Alv, lom1k, torox |
|           17 |     3627 | 2024-02-14 | GenOne          | W   | 0.658      | 0.371        | -                | 0.323 (0.079)    | false (0.000) |     9.82 | 1mpala, 4X1s, Alv, lom1k, torox |
|           16 |     3676 | 2024-02-13 | 1win            | L   | 0.652      | -            | -                | -                | -             |    -7.29 | 1mpala, 4X1s, Alv, lom1k, torox |
|           15 |     3746 | 2024-02-11 | Passion UA      | L   | 0.639      | -            | -                | -                | -             |    -3.05 | 1mpala, 4X1s, Alv, lom1k, torox |
|           14 |     3822 | 2024-02-08 | LODIS           | W   | 0.618      | 0.371        | 0.002 (0.001)    | 0.139 (0.032)    | false (0.000) |    10.39 | 1mpala, 4X1s, Alv, lom1k, torox |
|           13 |     3844 | 2024-02-07 | Nexus Gaming    | L   | 0.612      | -            | -                | -                | -             |    -3.21 | 1mpala, 4X1s, Alv, lom1k, torox |
|           12 |     3863 | 2024-02-06 | EsmagaB         | W   | 0.604      | 0.371        | 0.016 (0.004)    | 0.559 (0.125)    | -             |    15.43 | 1mpala, 4X1s, Alv, lom1k, torox |
|           11 |     4382 | 2024-01-24 | RoundsGG        | W   | 0.518      | 0.371        | -                | 0.170 (0.033)    | -             |    11.01 | 1mpala, 4X1s, Alv, lom1k, torox |
|           10 |     5004 | 2024-01-11 | SINNERS Esports | L   | 0.431      | -            | -                | -                | -             |    -1.30 | 1mpala, 4X1s, Alv, lom1k, torox |
|            9 |     5037 | 2024-01-10 | 1win            | W   | 0.426      | -            | -                | -                | -             |     9.31 | 1mpala, 4X1s, Alv, lom1k, torox |
|            8 |     6261 | 2023-11-29 | BAKS Esports    | L   | 0.145      | -            | -                | -                | -             |    -1.85 | 1mpala, 4X1s, Alv, lom1k, torox |
|            7 |     6362 | 2023-11-27 | Lilmix          | W   | 0.132      | -            | -                | -                | -             |     2.76 | 1mpala, 4X1s, Alv, lom1k, torox |
|            6 |     6518 | 2023-11-23 | Kappa Bar       | W   | 0.105      | -            | -                | -                | -             |     2.09 | 1mpala, 4X1s, Alv, lom1k, torox |
|            5 |     6635 | 2023-11-20 | K10             | W   | 0.085      | 0.371        | 0.015 (0.000)    | -                | -             |     2.28 | 1mpala, 4X1s, Alv, lom1k, torox |
|            4 |     6779 | 2023-11-17 | LF0             | W   | 0.064      | 0.371        | 0.006 (0.000)    | -                | -             |     1.21 | 1mpala, 4X1s, Alv, lom1k, torox |
|            3 |     6978 | 2023-11-13 | Underrated      | L   | 0.038      | -            | -                | -                | -             |    -0.76 | 1mpala, 4X1s, Alv, lom1k, torox |
|            2 |     7136 | 2023-11-09 | Los Alpacas     | W   | 0.012      | -            | -                | -                | -             |     0.21 | 1mpala, 4X1s, Alv, lom1k, torox |
|            1 |     7199 | 2023-11-08 | Insilio         | L   | 0.004      | -            | -                | -                | -             |    -0.02 | 1mpala, 4X1s, Alv, lom1k, torox |

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
