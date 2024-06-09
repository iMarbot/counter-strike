### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [14](../standings_global.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
Final Rank Value:  1534.5<br />
<br />
Final Rank Value (1534.5) = Starting Rank Value (1606.9) + Head To Head Adjustments (-72.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.661[<sup>1</sup>](#table2)
- Bounty Collected: 0.572[<sup>2</sup>](#table1)
- Opponent Network: 0.256[<sup>2</sup>](#table1)
- LAN Wins: 0.885[<sup>2</sup>](#table1)

The average of these factors is 0.594<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1606.9
- 400 + ( ( 0.594 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1606.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           68 |      462 | 2024-05-22 | paiN Gaming            | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.547 (0.246)    | -         |    11.50 | brnz4n, drop, exit, insani, saffee |
|           67 |      478 | 2024-05-22 | paiN Gaming            | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.547 (0.246)    | -         |    12.50 | brnz4n, drop, exit, insani, saffee |
|           66 |      659 | 2024-05-20 | BetBoom Team           | L   | 1.000      | -            | -                | -                | -         |   -23.31 | brnz4n, drop, exit, insani, saffee |
|           65 |      719 | 2024-05-20 | BIG                    | W   | 1.000      | 0.769        | 0.215 (0.166)    | 0.304 (0.233)    | -         |     8.47 | brnz4n, drop, exit, insani, saffee |
|           64 |      732 | 2024-05-20 | BetBoom Team           | L   | 1.000      | -            | -                | -                | -         |   -24.48 | brnz4n, drop, exit, insani, saffee |
|           63 |      988 | 2024-05-17 | HEROIC                 | L   | 1.000      | -            | -                | -                | -         |   -13.63 | brnz4n, drop, exit, insani, saffee |
|           62 |     1077 | 2024-05-16 | Aurora Gaming          | W   | 1.000      | 0.769        | 0.492 (0.378)    | 0.573 (0.441)    | 1 (1.000) |     6.78 | brnz4n, drop, exit, insani, saffee |
|           61 |     1190 | 2024-05-15 | HEROIC                 | L   | 1.000      | -            | -                | -                | -         |   -14.36 | brnz4n, drop, exit, insani, saffee |
|           60 |     2167 | 2024-04-28 | Aurora Gaming          | W   | 0.988      | 0.500        | 0.492 (0.243)    | 0.573 (0.283)    | 1 (0.988) |     8.02 | brnz4n, drop, exit, insani, saffee |
|           59 |     2171 | 2024-04-27 | Apeks                  | W   | 0.986      | -            | -                | -                | 1 (0.986) |     4.28 | brnz4n, drop, exit, insani, saffee |
|           58 |     2256 | 2024-04-26 | Rooster                | W   | 0.980      | -            | -                | -                | 1 (0.980) |     0.54 | brnz4n, drop, exit, insani, saffee |
|           57 |     2325 | 2024-04-25 | Rebels Gaming          | L   | 0.974      | -            | -                | -                | -         |   -28.84 | brnz4n, drop, exit, insani, saffee |
|           56 |     2328 | 2024-04-25 | KZG                    | W   | 0.973      | -            | -                | -                | 1 (0.973) |     0.20 | brnz4n, drop, exit, insani, saffee |
|           55 |     2624 | 2024-04-20 | paiN Gaming            | L   | 0.937      | -            | -                | -                | -         |   -17.21 | brnz4n, drop, exit, insani, saffee |
|           54 |     2660 | 2024-04-20 | OG                     | W   | 0.936      | 0.589        | 0.277 (0.153)    | -                | 1 (0.936) |     4.10 | brnz4n, drop, exit, insani, saffee |
|           53 |     2715 | 2024-04-19 | paiN Gaming            | W   | 0.933      | 0.143        | 0.463 (0.062)    | -                | -         |    13.03 | brnz4n, drop, exit, insani, saffee |
|           52 |     2722 | 2024-04-19 | FURIA Esports          | W   | 0.932      | 0.589        | 0.138 (0.076)    | -                | 1 (0.932) |     7.27 | brnz4n, drop, exit, insani, saffee |
|           51 |     2758 | 2024-04-19 | paiN Gaming            | L   | 0.930      | -            | -                | -                | -         |   -16.71 | brnz4n, drop, exit, insani, saffee |
|           50 |     2792 | 2024-04-18 | Imperial Esports       | W   | 0.926      | -            | -                | -                | -         |    10.23 | brnz4n, drop, exit, insani, saffee |
|           49 |     2797 | 2024-04-18 | paiN Gaming            | W   | 0.925      | -            | -                | -                | -         |    12.78 | brnz4n, drop, exit, insani, saffee |
|           48 |     2802 | 2024-04-18 | OG                     | W   | 0.925      | 0.589        | 0.277 (0.151)    | -                | 1 (0.925) |     4.20 | brnz4n, drop, exit, insani, saffee |
|           47 |     2859 | 2024-04-17 | RED Canids             | W   | 0.918      | -            | -                | -                | -         |     1.39 | brnz4n, drop, exit, insani, saffee |
|           46 |     2869 | 2024-04-17 | Case Esports           | W   | 0.918      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           45 |     2956 | 2024-04-16 | Bounty Hunters Esports | W   | 0.912      | -            | -                | -                | -         |     0.11 | brnz4n, drop, exit, insani, saffee |
|           44 |     2998 | 2024-04-15 | Imperial Esports       | W   | 0.904      | 0.435        | 0.372 (0.146)    | 0.582 (0.229)    | -         |    11.06 | brnz4n, drop, exit, insani, saffee |
|           43 |     3035 | 2024-04-14 | Galorys                | W   | 0.898      | 0.435        | -                | 0.600 (0.234)    | -         |     0.62 | brnz4n, drop, exit, insani, saffee |
|           42 |     3085 | 2024-04-13 | Case Esports           | W   | 0.890      | 0.435        | -                | 0.470 (0.182)    | -         |     0.48 | brnz4n, drop, exit, insani, saffee |
|           41 |     3165 | 2024-04-11 | paiN Gaming            | W   | 0.879      | -            | -                | -                | -         |    14.37 | brnz4n, drop, exit, insani, saffee |
|           40 |     3220 | 2024-04-10 | Galorys                | W   | 0.872      | 0.450        | -                | 0.600 (0.235)    | -         |     0.57 | brnz4n, drop, exit, insani, saffee |
|           39 |     3224 | 2024-04-10 | Galorys                | W   | 0.872      | 0.450        | -                | 0.600 (0.235)    | -         |     0.57 | brnz4n, drop, exit, insani, saffee |
|           38 |     3255 | 2024-04-10 | Imperial Esports       | W   | 0.870      | -            | -                | -                | -         |    12.69 | brnz4n, drop, exit, insani, saffee |
|           37 |     3299 | 2024-04-09 | adalYamigos            | W   | 0.865      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|           36 |     3306 | 2024-04-09 | adalYamigos            | W   | 0.865      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|           35 |     3309 | 2024-04-09 | RED Canids             | W   | 0.864      | -            | -                | -                | -         |     1.61 | brnz4n, drop, exit, insani, saffee |
|           34 |     3355 | 2024-04-08 | w7m esports            | W   | 0.859      | -            | -                | -                | -         |     0.52 | brnz4n, drop, exit, insani, saffee |
|           33 |     3404 | 2024-04-07 | paiN Gaming            | W   | 0.852      | -            | -                | -                | -         |    15.80 | brnz4n, drop, exit, insani, saffee |
|           32 |     3515 | 2024-04-05 | Fluxo                  | W   | 0.839      | -            | -                | -                | -         |     1.85 | brnz4n, drop, exit, insani, saffee |
|           31 |     3516 | 2024-04-05 | Fluxo                  | L   | 0.838      | -            | -                | -                | -         |   -24.82 | brnz4n, drop, exit, insani, saffee |
|           30 |     3521 | 2024-04-05 | ODDIK                  | W   | 0.837      | -            | -                | -                | -         |     0.89 | brnz4n, drop, exit, insani, saffee |
|           29 |     3613 | 2024-04-03 | Fluxo                  | W   | 0.825      | -            | -                | -                | -         |     1.48 | brnz4n, drop, exit, insani, saffee |
|           28 |     3673 | 2024-04-02 | Fluxo                  | W   | 0.819      | -            | -                | -                | -         |     1.41 | brnz4n, drop, exit, insani, saffee |
|           27 |     3677 | 2024-04-02 | Sharks Esports         | W   | 0.818      | -            | -                | -                | -         |     0.27 | brnz4n, drop, exit, insani, saffee |
|           26 |     3864 | 2024-03-27 | Case Esports           | W   | 0.779      | -            | -                | -                | -         |     0.50 | brnz4n, drop, exit, insani, saffee |
|           25 |     3868 | 2024-03-27 | Case Esports           | W   | 0.779      | -            | -                | -                | -         |     0.50 | brnz4n, drop, exit, insani, saffee |
|           24 |     3944 | 2024-03-26 | ODDIK                  | W   | 0.772      | -            | -                | -                | -         |     0.86 | brnz4n, drop, exit, insani, saffee |
|           23 |     3946 | 2024-03-26 | ODDIK                  | W   | 0.772      | -            | -                | -                | -         |     0.87 | brnz4n, drop, exit, insani, saffee |
|           22 |     4518 | 2024-03-14 | Sharks Esports         | W   | 0.693      | -            | -                | -                | -         |     0.81 | brnz4n, drop, exit, insani, saffee |
|           21 |     4519 | 2024-03-14 | Sharks Esports         | W   | 0.692      | -            | -                | -                | -         |     0.82 | brnz4n, drop, exit, insani, saffee |
|           20 |     4665 | 2024-03-12 | Fluxo                  | L   | 0.678      | -            | -                | -                | -         |   -20.24 | brnz4n, drop, exit, insani, saffee |
|           19 |     4765 | 2024-03-10 | Galorys                | W   | 0.665      | -            | -                | -                | -         |     0.32 | brnz4n, drop, exit, insani, saffee |
|           18 |     4871 | 2024-03-08 | LA RUGONETA            | W   | 0.651      | -            | -                | -                | -         |     0.10 | brnz4n, drop, exit, insani, saffee |
|           17 |     5206 | 2024-03-03 | Legacy                 | L   | 0.618      | -            | -                | -                | -         |   -18.45 | brnz4n, drop, exit, insani, saffee |
|           16 |     5319 | 2024-03-02 | NRG                    | W   | 0.611      | -            | -                | -                | 1 (0.611) |     0.39 | brnz4n, drop, exit, insani, saffee |
|           15 |     5370 | 2024-03-01 | BOSS                   | L   | 0.605      | -            | -                | -                | -         |   -18.71 | brnz4n, drop, exit, insani, saffee |
|           14 |     6695 | 2024-02-03 | Imperial Esports       | L   | 0.425      | -            | -                | -                | -         |    -7.87 | brnz4n, drop, exit, insani, saffee |
|           13 |     6854 | 2024-02-01 | paiN Gaming            | W   | 0.412      | -            | -                | -                | -         |     6.77 | brnz4n, drop, exit, insani, saffee |
|           12 |     6859 | 2024-02-01 | w7m esports            | W   | 0.412      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           11 |     7447 | 2024-01-22 | adalYamigos            | L   | 0.346      | -            | -                | -                | -         |   -10.83 | brnz4n, drop, exit, insani, saffee |
|           10 |     7555 | 2024-01-20 | BESTIA                 | W   | 0.331      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|            9 |     7629 | 2024-01-19 | TIMACETA               | W   | 0.326      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            8 |     7640 | 2024-01-19 | ODDIK                  | W   | 0.324      | -            | -                | -                | -         |     0.25 | brnz4n, drop, exit, insani, saffee |
|            7 |     7694 | 2024-01-18 | 9z Team                | L   | 0.319      | -            | -                | -                | -         |    -8.61 | brnz4n, drop, exit, insani, saffee |
|            6 |     7702 | 2024-01-18 | Sharks Esports         | W   | 0.318      | -            | -                | -                | -         |     0.21 | brnz4n, drop, exit, insani, saffee |
|            5 |     7757 | 2024-01-17 | 9z Team                | L   | 0.312      | -            | -                | -                | -         |    -8.54 | brnz4n, drop, exit, insani, saffee |
|            4 |     7790 | 2024-01-17 | Sharks Esports         | W   | 0.311      | -            | -                | -                | -         |     0.19 | brnz4n, drop, exit, insani, saffee |
|            3 |     9299 | 2023-12-09 | Team Spirit            | L   | 0.049      | -            | -                | -                | -         |    -0.25 | brnz4n, drop, exit, insani, saffee |
|            2 |     9447 | 2023-12-07 | Cloud9                 | W   | 0.036      | -            | -                | -                | 1 (0.036) |     0.40 | brnz4n, drop, exit, insani, saffee |
|            1 |     9587 | 2023-12-05 | BetBoom Team           | W   | 0.023      | -            | -                | -                | -         |     0.20 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92,441.44)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.31) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      0.988 | $50,000.00     | $49,405.09      |
| 2024-04-20 |      0.938 | $20,000.00     | $18,759.26      |
| 2024-04-15 |      0.904 | $25,000.00     | $22,611.11      |
| 2023-12-10 |      0.056 | $30,000.00     | $1,665.97       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
