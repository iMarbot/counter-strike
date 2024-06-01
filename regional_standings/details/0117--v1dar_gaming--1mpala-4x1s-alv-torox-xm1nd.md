### Roster Details<br />
Team Name: V1dar Gaming<br />
Roster: 1mpala, 4X1s, Alv, torox, xm1nd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [117](../standings_global.md)<br />
Regional Rank: [81]( ../standings_europe.md)<br />
Final Rank Value:  840.8<br />
<br />
Final Rank Value (840.8) = Starting Rank Value (631.7) + Head To Head Adjustments (209.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.161[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 631.7
- 400 + ( ( 0.114 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 631.7


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
|           46 |       76 | 2024-05-29 | 1win Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.50 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           45 |      267 | 2024-05-25 | Rustec              | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.283 (0.105)    | 0 (0.000) |    14.78 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           44 |      344 | 2024-05-24 | ENRAGE              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.45 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           43 |      466 | 2024-05-22 | GamerLegion Academy | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    17.45 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           42 |      495 | 2024-05-22 | Soda Gaming         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.53 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           41 |      501 | 2024-05-22 | ENTERPRISE esports  | W   | 1.000      | 0.372        | 0.010 (0.004)    | 0.809 (0.301)    | 0 (0.000) |    19.93 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           40 |      675 | 2024-05-20 | Nemiga Gaming       | L   | 1.000      | -            | -                | -                | -         |    -4.48 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           39 |      711 | 2024-05-20 | Insilio             | L   | 1.000      | -            | -                | -                | -         |    -8.48 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           38 |      739 | 2024-05-19 | Team PeeP           | L   | 1.000      | -            | -                | -                | -         |   -23.16 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           37 |     1073 | 2024-05-16 | DASH                | W   | 1.000      | 0.372        | -                | 0.358 (0.133)    | 0 (0.000) |     9.54 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           36 |     1258 | 2024-05-14 | HOTU                | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.85 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           35 |     1272 | 2024-05-14 | 4epel7axuHuHd39     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.43 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           34 |     1373 | 2024-05-12 | Nexus Gaming        | W   | 1.000      | 0.372        | 0.014 (0.005)    | 0.825 (0.307)    | 0 (0.000) |    19.59 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           33 |     1422 | 2024-05-11 | Verdant             | L   | 1.000      | -            | -                | -                | -         |    -9.31 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           32 |     1578 | 2024-05-09 | Illuminar Gaming    | W   | 1.000      | -            | -                | -                | -         |    18.77 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           31 |     1622 | 2024-05-08 | ENCE Academy        | W   | 1.000      | 0.143        | 0.012 (0.002)    | -                | -         |    17.01 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           30 |     1887 | 2024-05-03 | RUBY                | L   | 1.000      | -            | -                | -                | -         |    -8.31 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           29 |     1917 | 2024-05-02 | ThunderFlash        | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.423 (0.158)    | -         |    22.04 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           28 |     1958 | 2024-05-01 | 1win                | L   | 1.000      | -            | -                | -                | -         |    -5.63 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           27 |     1985 | 2024-05-01 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -3.86 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           26 |     2035 | 2024-04-30 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |    -4.27 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           25 |     2071 | 2024-04-29 | los kogutos         | L   | 0.997      | -            | -                | -                | -         |   -10.00 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           24 |     2200 | 2024-04-27 | Viperio             | W   | 0.982      | -            | -                | -                | -         |    17.62 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           23 |     2265 | 2024-04-26 | VP.Prodigy          | W   | 0.976      | 0.143        | 0.008 (0.001)    | 0.752 (0.105)    | -         |    19.00 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           22 |     2330 | 2024-04-25 | 9INE                | W   | 0.968      | -            | -                | -                | -         |    12.48 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           21 |     2393 | 2024-04-24 | VP.Prodigy          | L   | 0.961      | -            | -                | -                | -         |   -10.74 | 1mpala, 4X1s, Alv, torox, xm1nd |
|           20 |     4649 | 2024-03-10 | MOUZ NXT            | L   | 0.664      | -            | -                | -                | -         |    -2.23 | 1mpala, 4X1s, Alv, lom1k, torox |
|           19 |     4883 | 2024-03-06 | Endpoint            | L   | 0.637      | -            | -                | -                | -         |    -4.60 | 1mpala, 4X1s, Alv, lom1k, torox |
|           18 |     5266 | 2024-02-29 | Lilmix              | L   | 0.597      | -            | -                | -                | -         |    -6.20 | 1mpala, 4X1s, Alv, lom1k, torox |
|           17 |     5355 | 2024-02-27 | FORZE Esports       | L   | 0.584      | -            | -                | -                | -         |    -3.02 | 1mpala, 4X1s, Alv, lom1k, torox |
|           16 |     5367 | 2024-02-27 | Sashi Esport        | W   | 0.584      | 0.143        | 0.172 (0.014)    | 1.000 (0.083)    | -         |    16.32 | 1mpala, 4X1s, Alv, lom1k, torox |
|           15 |     5398 | 2024-02-26 | Rustec              | W   | 0.578      | -            | -                | -                | -         |    11.71 | 1mpala, 4X1s, Alv, lom1k, torox |
|           14 |     5608 | 2024-02-23 | GUN5 Esports        | W   | 0.557      | -            | -                | -                | -         |     7.16 | 1mpala, 4X1s, Alv, lom1k, torox |
|           13 |     5712 | 2024-02-21 | L&G                 | W   | 0.544      | -            | -                | -                | -         |     4.72 | 1mpala, 4X1s, Alv, lom1k, torox |
|           12 |     5830 | 2024-02-19 | BAKS Esports        | W   | 0.531      | -            | -                | -                | -         |     7.34 | 1mpala, 4X1s, Alv, lom1k, torox |
|           11 |     6099 | 2024-02-14 | GenOne              | W   | 0.497      | 0.371        | -                | 0.442 (0.082)    | -         |     7.65 | 1mpala, 4X1s, Alv, lom1k, torox |
|           10 |     6154 | 2024-02-13 | 1win                | L   | 0.491      | -            | -                | -                | -         |    -2.35 | 1mpala, 4X1s, Alv, lom1k, torox |
|            9 |     6232 | 2024-02-11 | Passion UA          | L   | 0.477      | -            | -                | -                | -         |    -2.50 | 1mpala, 4X1s, Alv, lom1k, torox |
|            8 |     6331 | 2024-02-08 | LODIS               | W   | 0.457      | -            | -                | -                | -         |     6.63 | 1mpala, 4X1s, Alv, lom1k, torox |
|            7 |     6359 | 2024-02-07 | Nexus Gaming        | L   | 0.451      | -            | -                | -                | -         |    -2.79 | 1mpala, 4X1s, Alv, lom1k, torox |
|            6 |     6382 | 2024-02-06 | esmagaB             | W   | 0.443      | 0.371        | 0.008 (0.001)    | 0.460 (0.076)    | -         |    10.41 | 1mpala, 4X1s, Alv, lom1k, torox |
|            5 |     6466 | 2024-02-04 | ALTERNATE aTTaX     | W   | 0.430      | 0.371        | 0.004 (0.001)    | -                | -         |     8.20 | 1mpala, 4X1s, Alv, lom1k, torox |
|            4 |     7116 | 2024-01-24 | RoundsGG            | W   | 0.357      | -            | -                | -                | -         |     5.14 | 1mpala, 4X1s, Alv, lom1k, torox |
|            3 |     7945 | 2024-01-11 | SINNERS Esports     | L   | 0.270      | -            | -                | -                | -         |    -0.98 | 1mpala, 4X1s, Alv, lom1k, torox |
|            2 |     7994 | 2024-01-10 | 1win Academy        | W   | 0.265      | -            | -                | -                | -         |     3.97 | 1mpala, 4X1s, Alv, lom1k, torox |
|            1 |     8011 | 2024-01-10 | apa7hy              | W   | 0.265      | -            | -                | -                | -         |     1.78 | 1mpala, 4X1s, Alv, lom1k, torox |

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
