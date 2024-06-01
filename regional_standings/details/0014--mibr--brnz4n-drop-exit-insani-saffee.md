### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [14](../standings_global.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
Final Rank Value:  1537.0<br />
<br />
Final Rank Value (1537.0) = Starting Rank Value (1610.1) + Head To Head Adjustments (-73.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.661[<sup>1</sup>](#table2)
- Bounty Collected: 0.574[<sup>2</sup>](#table1)
- Opponent Network: 0.258[<sup>2</sup>](#table1)
- LAN Wins: 0.885[<sup>2</sup>](#table1)

The average of these factors is 0.594<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1610.1
- 400 + ( ( 0.594 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1610.1


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
|           66 |      456 | 2024-05-22 | paiN Gaming            | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.524 (0.236)    | -         |    11.46 | brnz4n, drop, exit, insani, saffee |
|           65 |      472 | 2024-05-22 | paiN Gaming            | W   | 1.000      | 0.450        | 0.463 (0.209)    | 0.524 (0.236)    | -         |    12.45 | brnz4n, drop, exit, insani, saffee |
|           64 |      648 | 2024-05-20 | BetBoom Team           | L   | 1.000      | -            | -                | -                | -         |   -23.38 | brnz4n, drop, exit, insani, saffee |
|           63 |      707 | 2024-05-20 | BIG                    | W   | 1.000      | 0.769        | 0.235 (0.181)    | 0.304 (0.233)    | -         |     8.64 | brnz4n, drop, exit, insani, saffee |
|           62 |      720 | 2024-05-20 | BetBoom Team           | L   | 1.000      | -            | -                | -                | -         |   -24.54 | brnz4n, drop, exit, insani, saffee |
|           61 |      976 | 2024-05-17 | HEROIC                 | L   | 1.000      | -            | -                | -                | -         |   -13.74 | brnz4n, drop, exit, insani, saffee |
|           60 |     1067 | 2024-05-16 | Aurora Gaming          | W   | 1.000      | 0.769        | 0.492 (0.378)    | 0.616 (0.473)    | 1 (1.000) |     7.32 | brnz4n, drop, exit, insani, saffee |
|           59 |     1180 | 2024-05-15 | HEROIC                 | L   | 1.000      | -            | -                | -                | -         |   -14.46 | brnz4n, drop, exit, insani, saffee |
|           58 |     2132 | 2024-04-28 | Aurora Gaming          | W   | 0.988      | 0.500        | 0.492 (0.243)    | 0.616 (0.304)    | 1 (0.988) |     8.71 | brnz4n, drop, exit, insani, saffee |
|           57 |     2136 | 2024-04-27 | Apeks                  | W   | 0.986      | -            | -                | -                | 1 (0.986) |     4.32 | brnz4n, drop, exit, insani, saffee |
|           56 |     2220 | 2024-04-26 | Rooster                | W   | 0.980      | -            | -                | -                | 1 (0.980) |     0.50 | brnz4n, drop, exit, insani, saffee |
|           55 |     2288 | 2024-04-25 | Rebels Gaming          | L   | 0.974      | -            | -                | -                | -         |   -28.93 | brnz4n, drop, exit, insani, saffee |
|           54 |     2291 | 2024-04-25 | KZG                    | W   | 0.973      | -            | -                | -                | 1 (0.973) |     0.21 | brnz4n, drop, exit, insani, saffee |
|           53 |     2571 | 2024-04-20 | paiN Gaming            | L   | 0.937      | -            | -                | -                | -         |   -17.22 | brnz4n, drop, exit, insani, saffee |
|           52 |     2606 | 2024-04-20 | OG                     | W   | 0.936      | 0.589        | 0.277 (0.153)    | -                | 1 (0.936) |     4.11 | brnz4n, drop, exit, insani, saffee |
|           51 |     2661 | 2024-04-19 | paiN Gaming            | W   | 0.933      | 0.143        | 0.463 (0.062)    | -                | -         |    13.02 | brnz4n, drop, exit, insani, saffee |
|           50 |     2668 | 2024-04-19 | FURIA Esports          | W   | 0.932      | 0.589        | 0.138 (0.076)    | -                | 1 (0.932) |     7.23 | brnz4n, drop, exit, insani, saffee |
|           49 |     2702 | 2024-04-19 | paiN Gaming            | L   | 0.930      | -            | -                | -                | -         |   -16.72 | brnz4n, drop, exit, insani, saffee |
|           48 |     2736 | 2024-04-18 | Imperial Esports       | W   | 0.926      | -            | -                | -                | -         |    10.20 | brnz4n, drop, exit, insani, saffee |
|           47 |     2741 | 2024-04-18 | paiN Gaming            | W   | 0.925      | -            | -                | -                | -         |    12.77 | brnz4n, drop, exit, insani, saffee |
|           46 |     2746 | 2024-04-18 | OG                     | W   | 0.925      | 0.589        | 0.277 (0.151)    | -                | 1 (0.925) |     4.22 | brnz4n, drop, exit, insani, saffee |
|           45 |     2803 | 2024-04-17 | RED Canids             | W   | 0.918      | -            | -                | -                | -         |     1.40 | brnz4n, drop, exit, insani, saffee |
|           44 |     2812 | 2024-04-17 | Case Esports           | W   | 0.918      | -            | -                | -                | -         |     0.51 | brnz4n, drop, exit, insani, saffee |
|           43 |     2898 | 2024-04-16 | Bounty Hunters Esports | W   | 0.912      | -            | -                | -                | -         |     0.11 | brnz4n, drop, exit, insani, saffee |
|           42 |     2937 | 2024-04-15 | Imperial Esports       | W   | 0.904      | 0.435        | 0.372 (0.146)    | 0.582 (0.229)    | -         |    11.03 | brnz4n, drop, exit, insani, saffee |
|           41 |     2970 | 2024-04-14 | Galorys                | W   | 0.898      | 0.435        | -                | 0.585 (0.228)    | -         |     0.68 | brnz4n, drop, exit, insani, saffee |
|           40 |     3019 | 2024-04-13 | Case Esports           | W   | 0.890      | -            | -                | -                | -         |     0.48 | brnz4n, drop, exit, insani, saffee |
|           39 |     3099 | 2024-04-11 | paiN Gaming            | W   | 0.879      | -            | -                | -                | -         |    14.37 | brnz4n, drop, exit, insani, saffee |
|           38 |     3149 | 2024-04-10 | Galorys                | W   | 0.872      | 0.450        | -                | 0.585 (0.230)    | -         |     0.60 | brnz4n, drop, exit, insani, saffee |
|           37 |     3153 | 2024-04-10 | Galorys                | W   | 0.872      | 0.450        | -                | 0.585 (0.230)    | -         |     0.60 | brnz4n, drop, exit, insani, saffee |
|           36 |     3181 | 2024-04-10 | Imperial Esports       | W   | 0.870      | -            | -                | -                | -         |    12.65 | brnz4n, drop, exit, insani, saffee |
|           35 |     3221 | 2024-04-09 | adalYamigos            | W   | 0.865      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|           34 |     3228 | 2024-04-09 | adalYamigos            | W   | 0.865      | -            | -                | -                | -         |     0.37 | brnz4n, drop, exit, insani, saffee |
|           33 |     3231 | 2024-04-09 | RED Canids             | W   | 0.864      | -            | -                | -                | -         |     1.62 | brnz4n, drop, exit, insani, saffee |
|           32 |     3275 | 2024-04-08 | w7m esports            | W   | 0.859      | -            | -                | -                | -         |     0.53 | brnz4n, drop, exit, insani, saffee |
|           31 |     3323 | 2024-04-07 | paiN Gaming            | W   | 0.852      | -            | -                | -                | -         |    15.76 | brnz4n, drop, exit, insani, saffee |
|           30 |     3431 | 2024-04-05 | Fluxo                  | W   | 0.839      | 0.450        | -                | 0.474 (0.179)    | -         |     1.79 | brnz4n, drop, exit, insani, saffee |
|           29 |     3432 | 2024-04-05 | Fluxo                  | L   | 0.838      | -            | -                | -                | -         |   -24.87 | brnz4n, drop, exit, insani, saffee |
|           28 |     3437 | 2024-04-05 | ODDIK                  | W   | 0.837      | -            | -                | -                | -         |     0.89 | brnz4n, drop, exit, insani, saffee |
|           27 |     3526 | 2024-04-03 | Fluxo                  | W   | 0.825      | -            | -                | -                | -         |     1.42 | brnz4n, drop, exit, insani, saffee |
|           26 |     3584 | 2024-04-02 | Fluxo                  | W   | 0.819      | -            | -                | -                | -         |     1.35 | brnz4n, drop, exit, insani, saffee |
|           25 |     3588 | 2024-04-02 | Sharks Esports         | W   | 0.818      | -            | -                | -                | -         |     0.85 | brnz4n, drop, exit, insani, saffee |
|           24 |     3771 | 2024-03-27 | Case Esports           | W   | 0.779      | -            | -                | -                | -         |     0.49 | brnz4n, drop, exit, insani, saffee |
|           23 |     3775 | 2024-03-27 | Case Esports           | W   | 0.779      | -            | -                | -                | -         |     0.50 | brnz4n, drop, exit, insani, saffee |
|           22 |     3847 | 2024-03-26 | ODDIK                  | W   | 0.772      | -            | -                | -                | -         |     0.86 | brnz4n, drop, exit, insani, saffee |
|           21 |     3849 | 2024-03-26 | ODDIK                  | W   | 0.772      | -            | -                | -                | -         |     0.87 | brnz4n, drop, exit, insani, saffee |
|           20 |     4546 | 2024-03-12 | Fluxo                  | L   | 0.678      | -            | -                | -                | -         |   -20.30 | brnz4n, drop, exit, insani, saffee |
|           19 |     4642 | 2024-03-10 | Galorys                | W   | 0.665      | -            | -                | -                | -         |     0.34 | brnz4n, drop, exit, insani, saffee |
|           18 |     4744 | 2024-03-08 | LA RUGONETA            | W   | 0.651      | -            | -                | -                | -         |     0.09 | brnz4n, drop, exit, insani, saffee |
|           17 |     5060 | 2024-03-03 | Legacy                 | L   | 0.618      | -            | -                | -                | -         |   -18.47 | brnz4n, drop, exit, insani, saffee |
|           16 |     5171 | 2024-03-02 | NRG                    | W   | 0.611      | -            | -                | -                | 1 (0.611) |     0.38 | brnz4n, drop, exit, insani, saffee |
|           15 |     5221 | 2024-03-01 | BOSS                   | L   | 0.605      | -            | -                | -                | -         |   -18.72 | brnz4n, drop, exit, insani, saffee |
|           14 |     6492 | 2024-02-03 | Imperial Esports       | L   | 0.425      | -            | -                | -                | -         |    -7.92 | brnz4n, drop, exit, insani, saffee |
|           13 |     6649 | 2024-02-01 | paiN Gaming            | W   | 0.412      | -            | -                | -                | -         |     6.72 | brnz4n, drop, exit, insani, saffee |
|           12 |     6654 | 2024-02-01 | w7m esports            | W   | 0.412      | -            | -                | -                | -         |     0.16 | brnz4n, drop, exit, insani, saffee |
|           11 |     7206 | 2024-01-22 | adalYamigos            | L   | 0.346      | -            | -                | -                | -         |   -10.83 | brnz4n, drop, exit, insani, saffee |
|           10 |     7312 | 2024-01-20 | BESTIA                 | W   | 0.331      | -            | -                | -                | -         |     0.28 | brnz4n, drop, exit, insani, saffee |
|            9 |     7385 | 2024-01-19 | TIMACETA               | W   | 0.326      | -            | -                | -                | -         |     0.05 | brnz4n, drop, exit, insani, saffee |
|            8 |     7396 | 2024-01-19 | ODDIK                  | W   | 0.324      | -            | -                | -                | -         |     0.24 | brnz4n, drop, exit, insani, saffee |
|            7 |     7447 | 2024-01-18 | 9z Team                | L   | 0.319      | -            | -                | -                | -         |    -8.64 | brnz4n, drop, exit, insani, saffee |
|            6 |     7454 | 2024-01-18 | Sharks Esports         | W   | 0.318      | -            | -                | -                | -         |     0.21 | brnz4n, drop, exit, insani, saffee |
|            5 |     7508 | 2024-01-17 | 9z Team                | L   | 0.312      | -            | -                | -                | -         |    -8.57 | brnz4n, drop, exit, insani, saffee |
|            4 |     7541 | 2024-01-17 | Sharks Esports         | W   | 0.311      | -            | -                | -                | -         |     0.19 | brnz4n, drop, exit, insani, saffee |
|            3 |     9033 | 2023-12-09 | Team Spirit            | L   | 0.049      | -            | -                | -                | -         |    -0.25 | brnz4n, drop, exit, insani, saffee |
|            2 |     9174 | 2023-12-07 | Cloud9                 | W   | 0.036      | -            | -                | -                | 1 (0.036) |     0.39 | brnz4n, drop, exit, insani, saffee |
|            1 |     9305 | 2023-12-05 | BetBoom Team           | W   | 0.023      | -            | -                | -                | -         |     0.20 | brnz4n, drop, exit, insani, saffee |

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
