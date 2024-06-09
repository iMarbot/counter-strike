### Roster Details<br />
Team Name: V1dar Gaming<br />
Roster: 1mpala, 4X1s, Alv, torox, xm1nd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [103](../standings_global.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
Final Rank Value:  862.4<br />
<br />
Final Rank Value (862.4) = Starting Rank Value (645.3) + Head To Head Adjustments (217.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.3
- 400 + ( ( 0.121 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 645.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       71 | 2024-05-29 | Grannys Knockers    | W   | 1.000      | 0.372        | 0.006 (0.002)    | 0.517 (0.192)    | 0 (0.000) |    13.33 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           46 |       81 | 2024-05-29 | 1win Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.23 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           45 |      275 | 2024-05-25 | Rustec              | W   | 1.000      | 0.372        | -                | 0.328 (0.122)    | 0 (0.000) |    15.23 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           44 |      353 | 2024-05-24 | ENRAGE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.80 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           43 |      472 | 2024-05-22 | GamerLegion Academy | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    16.74 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           42 |      501 | 2024-05-22 | Soda Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.49 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           41 |      508 | 2024-05-22 | ENTERPRISE esports  | W   | 1.000      | 0.372        | 0.010 (0.004)    | 0.898 (0.334)    | 0 (0.000) |    20.13 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           40 |      686 | 2024-05-20 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |    -4.57 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           39 |      723 | 2024-05-20 | Insilio             | L   | 1.000      | -            | -                | -                | -         |    -8.74 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           38 |      751 | 2024-05-19 | Team PeeP           | L   | 1.000      | -            | -                | -                | -         |   -23.42 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           37 |     1083 | 2024-05-16 | DASH                | W   | 1.000      | 0.372        | -                | 0.385 (0.143)    | 0 (0.000) |    10.32 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           36 |     1268 | 2024-05-14 | HOTU                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    18.08 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           35 |     1283 | 2024-05-14 | 4epel7axuHuHd39     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.29 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           34 |     1386 | 2024-05-12 | Nexus Gaming        | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.857 (0.319)    | -         |    18.82 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           33 |     1435 | 2024-05-11 | Verdant             | L   | 1.000      | -            | -                | -                | -         |    -9.34 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           32 |     1594 | 2024-05-09 | Illuminar Gaming    | W   | 1.000      | -            | -                | -                | -         |    18.43 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           31 |     1639 | 2024-05-08 | ENCE Academy        | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | -         |    16.82 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           30 |     1912 | 2024-05-03 | RUBY                | L   | 1.000      | -            | -                | -                | -         |    -8.53 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           29 |     1944 | 2024-05-02 | ThunderFlash        | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.423 (0.158)    | -         |    21.22 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           28 |     1985 | 2024-05-01 | 1win                | L   | 1.000      | -            | -                | -                | -         |    -6.03 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           27 |     2014 | 2024-05-01 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -4.35 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           26 |     2068 | 2024-04-30 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |    -4.39 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           25 |     2106 | 2024-04-29 | los kogutos         | L   | 0.997      | -            | -                | -                | -         |   -10.89 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           24 |     2235 | 2024-04-27 | Viperio             | W   | 0.982      | -            | -                | -                | -         |    17.20 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           23 |     2301 | 2024-04-26 | VP.Prodigy          | W   | 0.976      | 0.143        | 0.008 (0.001)    | 0.829 (0.116)    | -         |    19.10 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           22 |     2371 | 2024-04-25 | 9INE                | W   | 0.968      | -            | -                | -                | -         |    12.06 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           21 |     2438 | 2024-04-24 | VP.Prodigy          | L   | 0.961      | -            | -                | -                | -         |   -10.63 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           20 |     4774 | 2024-03-10 | MOUZ NXT            | L   | 0.664      | -            | -                | -                | -         |    -2.22 | 1mpala, 4X1s, Alv, lom1k, torox |
|           19 |     5014 | 2024-03-06 | Endpoint            | L   | 0.637      | -            | -                | -                | -         |    -4.80 | 1mpala, 4X1s, Alv, lom1k, torox |
|           18 |     5416 | 2024-02-29 | Lilmix              | L   | 0.597      | -            | -                | -                | -         |    -6.93 | 1mpala, 4X1s, Alv, lom1k, torox |
|           17 |     5508 | 2024-02-27 | FORZE Esports       | L   | 0.584      | -            | -                | -                | -         |    -3.41 | 1mpala, 4X1s, Alv, lom1k, torox |
|           16 |     5520 | 2024-02-27 | Sashi Esport        | W   | 0.584      | 0.143        | 0.154 (0.013)    | -                | -         |    16.15 | 1mpala, 4X1s, Alv, lom1k, torox |
|           15 |     5555 | 2024-02-26 | Rustec              | W   | 0.578      | -            | -                | -                | -         |    11.56 | 1mpala, 4X1s, Alv, lom1k, torox |
|           14 |     5768 | 2024-02-23 | GUN5 Esports        | W   | 0.557      | -            | -                | -                | -         |     6.99 | 1mpala, 4X1s, Alv, lom1k, torox |
|           13 |     5875 | 2024-02-21 | L&G                 | W   | 0.544      | -            | -                | -                | -         |     4.66 | 1mpala, 4X1s, Alv, lom1k, torox |
|           12 |     6001 | 2024-02-19 | BAKS Esports        | W   | 0.531      | -            | -                | -                | -         |     6.87 | 1mpala, 4X1s, Alv, lom1k, torox |
|           11 |     6280 | 2024-02-14 | GenOne              | W   | 0.497      | -            | -                | -                | -         |     7.39 | 1mpala, 4X1s, Alv, lom1k, torox |
|           10 |     6339 | 2024-02-13 | 1win                | L   | 0.491      | -            | -                | -                | -         |    -2.69 | 1mpala, 4X1s, Alv, lom1k, torox |
|            9 |     6420 | 2024-02-11 | Passion UA          | L   | 0.477      | -            | -                | -                | -         |    -2.59 | 1mpala, 4X1s, Alv, lom1k, torox |
|            8 |     6519 | 2024-02-08 | LODIS               | W   | 0.457      | -            | -                | -                | -         |     6.51 | 1mpala, 4X1s, Alv, lom1k, torox |
|            7 |     6553 | 2024-02-07 | Nexus Gaming        | L   | 0.451      | -            | -                | -                | -         |    -3.25 | 1mpala, 4X1s, Alv, lom1k, torox |
|            6 |     6578 | 2024-02-06 | esmagaB             | W   | 0.443      | 0.371        | 0.008 (0.001)    | 0.564 (0.093)    | -         |    10.28 | 1mpala, 4X1s, Alv, lom1k, torox |
|            5 |     6669 | 2024-02-04 | ALTERNATE aTTaX     | W   | 0.430      | 0.371        | 0.052 (0.008)    | 0.735 (0.117)    | -         |    11.43 | 1mpala, 4X1s, Alv, lom1k, torox |
|            4 |     7349 | 2024-01-24 | RoundsGG            | W   | 0.357      | -            | -                | -                | -         |     5.17 | 1mpala, 4X1s, Alv, lom1k, torox |
|            3 |     8198 | 2024-01-11 | SINNERS Esports     | L   | 0.270      | -            | -                | -                | -         |    -0.92 | 1mpala, 4X1s, Alv, lom1k, torox |
|            2 |     8248 | 2024-01-10 | 1win Academy        | W   | 0.265      | -            | -                | -                | -         |     3.81 | 1mpala, 4X1s, Alv, lom1k, torox |
|            1 |     8265 | 2024-01-10 | apa7hy              | W   | 0.265      | -            | -                | -                | -         |     1.68 | 1mpala, 4X1s, Alv, lom1k, torox |

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
