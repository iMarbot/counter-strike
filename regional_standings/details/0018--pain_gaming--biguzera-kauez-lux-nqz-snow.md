### Roster Details<br />
Team Name: paiN Gaming<br />
Roster: biguzera, kauez, lux, nqz, snow<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [18](../standings_global.md)<br />
Regional Rank: [4]( ../standings_americas.md)<br />
Final Rank Value:  1424.3<br />
<br />
Final Rank Value (1424.3) = Starting Rank Value (1643.6) + Head To Head Adjustments (-219.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.750[<sup>1</sup>](#table2)
- Bounty Collected: 0.550[<sup>2</sup>](#table1)
- Opponent Network: 0.302[<sup>2</sup>](#table1)
- LAN Wins: 0.846[<sup>2</sup>](#table1)

The average of these factors is 0.612<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1643.6
- 400 + ( ( 0.612 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1643.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           75 |      462 | 2024-05-22 | MIBR              | L   | 1.000      | -            | -                | -                | -         |   -11.50 | biguzera, kauez, lux, nqz, snow   |
|           74 |      478 | 2024-05-22 | MIBR              | L   | 1.000      | -            | -                | -                | -         |   -12.50 | biguzera, kauez, lux, nqz, snow   |
|           73 |      762 | 2024-05-19 | AMKAL ESPORTS     | L   | 1.000      | -            | -                | -                | -         |   -23.29 | biguzera, kauez, lux, nqz, snow   |
|           72 |      817 | 2024-05-19 | OG                | W   | 1.000      | 0.769        | 0.277 (0.213)    | -                | -         |     6.43 | biguzera, kauez, lux, nqz, snow   |
|           71 |      869 | 2024-05-18 | AMKAL ESPORTS     | L   | 1.000      | -            | -                | -                | -         |   -24.50 | biguzera, kauez, lux, nqz, snow   |
|           70 |     1353 | 2024-05-12 | 9z Team           | W   | 1.000      | -            | -                | -                | -         |     6.69 | biguzera, kauez, lux, nqz, snow   |
|           69 |     1436 | 2024-05-11 | BESTIA            | W   | 1.000      | -            | -                | -                | -         |     1.26 | biguzera, kauez, lux, nqz, snow   |
|           68 |     1535 | 2024-05-10 | RED Canids        | W   | 1.000      | -            | -                | -                | -         |     2.79 | biguzera, kauez, lux, nqz, snow   |
|           67 |     1555 | 2024-05-09 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |   -28.62 | biguzera, kauez, lux, nqz, snow   |
|           66 |     1561 | 2024-05-09 | Fluxo             | W   | 1.000      | -            | -                | -                | -         |     2.54 | biguzera, kauez, lux, nqz, snow   |
|           65 |     1611 | 2024-05-08 | RED Canids        | W   | 1.000      | 0.450        | -                | 0.536 (0.241)    | -         |     2.44 | biguzera, kauez, lux, nqz, snow   |
|           64 |     1613 | 2024-05-08 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -29.40 | biguzera, kauez, lux, nqz, snow   |
|           63 |     1622 | 2024-05-08 | Galorys           | W   | 1.000      | 0.450        | -                | 0.600 (0.270)    | -         |     0.70 | biguzera, kauez, lux, nqz, snow   |
|           62 |     1638 | 2024-05-08 | Galorys           | W   | 1.000      | 0.450        | -                | 0.600 (0.270)    | -         |     0.70 | biguzera, kauez, lux, nqz, snow   |
|           61 |     1680 | 2024-05-07 | w7m esports       | W   | 1.000      | -            | -                | -                | -         |     0.49 | biguzera, kauez, lux, nqz, snow   |
|           60 |     1729 | 2024-05-06 | w7m esports       | W   | 1.000      | -            | -                | -                | -         |     0.50 | biguzera, kauez, lux, nqz, snow   |
|           59 |     1742 | 2024-05-06 | w7m esports       | W   | 1.000      | -            | -                | -                | -         |     0.50 | biguzera, kauez, lux, nqz, snow   |
|           58 |     1774 | 2024-05-05 | KRÜ Esports       | W   | 1.000      | -            | -                | -                | -         |     0.63 | biguzera, kauez, lux, nqz, snow   |
|           57 |     2380 | 2024-04-24 | ODDIK             | W   | 0.965      | -            | -                | -                | -         |     0.97 | biguzera, kauez, lux, nqz, nyezin |
|           56 |     2385 | 2024-04-24 | ODDIK             | L   | 0.965      | -            | -                | -                | -         |   -29.58 | biguzera, kauez, lux, nqz, nyezin |
|           55 |     2601 | 2024-04-20 | Imperial Esports  | W   | 0.938      | 0.589        | 0.372 (0.205)    | 0.582 (0.321)    | 1 (0.938) |    11.72 | biguzera, kauez, lux, nqz, nyezin |
|           54 |     2624 | 2024-04-20 | MIBR              | W   | 0.937      | 0.589        | 0.307 (0.170)    | 0.531 (0.293)    | 1 (0.937) |    17.21 | biguzera, kauez, lux, nqz, nyezin |
|           53 |     2714 | 2024-04-19 | Imperial Esports  | L   | 0.933      | -            | -                | -                | -         |   -17.36 | biguzera, kauez, lux, nqz, nyezin |
|           52 |     2715 | 2024-04-19 | MIBR              | L   | 0.933      | -            | -                | -                | -         |   -13.03 | biguzera, kauez, lux, nqz, nyezin |
|           51 |     2733 | 2024-04-19 | Imperial Esports  | W   | 0.931      | -            | -                | -                | -         |    11.34 | biguzera, kauez, lux, nqz, nyezin |
|           50 |     2758 | 2024-04-19 | MIBR              | W   | 0.930      | 0.589        | 0.307 (0.168)    | 0.531 (0.291)    | 1 (0.930) |    16.71 | biguzera, kauez, lux, nqz, nyezin |
|           49 |     2793 | 2024-04-18 | Fluxo             | W   | 0.926      | -            | -                | -                | -         |     2.12 | biguzera, kauez, lux, nqz, nyezin |
|           48 |     2797 | 2024-04-18 | MIBR              | L   | 0.925      | -            | -                | -                | -         |   -12.78 | biguzera, kauez, lux, nqz, nyezin |
|           47 |     2826 | 2024-04-18 | Monte             | W   | 0.923      | 0.589        | 0.181 (0.098)    | -                | 1 (0.923) |     4.81 | biguzera, kauez, lux, nqz, nyezin |
|           46 |     3039 | 2024-04-14 | Imperial Esports  | L   | 0.897      | -            | -                | -                | -         |   -16.87 | biguzera, kauez, lux, nqz, nyezin |
|           45 |     3077 | 2024-04-13 | ODDIK             | W   | 0.891      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, nqz, nyezin |
|           44 |     3165 | 2024-04-11 | MIBR              | L   | 0.879      | -            | -                | -                | -         |   -14.37 | biguzera, kauez, lux, nqz, nyezin |
|           43 |     3172 | 2024-04-11 | Sharks Esports    | W   | 0.878      | -            | -                | -                | -         |     0.28 | biguzera, kauez, lux, nqz, nyezin |
|           42 |     3186 | 2024-04-11 | Imperial Esports  | W   | 0.877      | -            | -                | -                | -         |    10.41 | biguzera, kauez, lux, nqz, nyezin |
|           41 |     3231 | 2024-04-10 | RED Canids        | W   | 0.871      | -            | -                | -                | -         |     1.37 | biguzera, kauez, lux, nqz, nyezin |
|           40 |     3300 | 2024-04-09 | Case Esports      | W   | 0.865      | -            | -                | -                | -         |     0.43 | biguzera, kauez, lux, nqz, nyezin |
|           39 |     3305 | 2024-04-09 | Case Esports      | W   | 0.865      | -            | -                | -                | -         |     0.43 | biguzera, kauez, lux, nqz, nyezin |
|           38 |     3325 | 2024-04-09 | Imperial Esports  | L   | 0.863      | -            | -                | -                | -         |   -15.89 | biguzera, kauez, lux, nqz, nyezin |
|           37 |     3361 | 2024-04-08 | Sharks Esports    | W   | 0.857      | -            | -                | -                | -         |     0.27 | biguzera, kauez, lux, nqz, nyezin |
|           36 |     3404 | 2024-04-07 | MIBR              | L   | 0.852      | -            | -                | -                | -         |   -15.80 | biguzera, kauez, lux, nqz, nyezin |
|           35 |     3408 | 2024-04-07 | Galorys           | W   | 0.851      | -            | -                | -                | -         |     0.41 | biguzera, kauez, lux, nqz, nyezin |
|           34 |     3529 | 2024-04-05 | Sharks Esports    | W   | 0.837      | -            | -                | -                | -         |     0.19 | biguzera, kauez, lux, nqz, nyezin |
|           33 |     3558 | 2024-04-04 | Sharks Esports    | W   | 0.832      | -            | -                | -                | -         |     0.73 | biguzera, kauez, lux, nqz, nyezin |
|           32 |     3561 | 2024-04-04 | Sharks Esports    | W   | 0.832      | -            | -                | -                | -         |     0.74 | biguzera, kauez, lux, nqz, nyezin |
|           31 |     4036 | 2024-03-24 | Natus Vincere     | L   | 0.757      | -            | -                | -                | -         |    -4.66 | biguzera, kauez, lux, n1ssim, nqz |
|           30 |     4085 | 2024-03-23 | HEROIC            | W   | 0.751      | 1.000        | 0.322 (0.242)    | 0.463 (0.348)    | 1 (0.751) |    16.12 | biguzera, kauez, lux, n1ssim, nqz |
|           29 |     4136 | 2024-03-22 | The MongolZ       | W   | 0.743      | 1.000        | 0.192 (0.143)    | 0.619 (0.460)    | 1 (0.743) |    11.62 | biguzera, kauez, lux, n1ssim, nqz |
|           28 |     4184 | 2024-03-21 | Virtus.pro        | L   | 0.738      | -            | -                | -                | -         |    -7.60 | biguzera, kauez, lux, n1ssim, nqz |
|           27 |     4195 | 2024-03-21 | Complexity Gaming | L   | 0.736      | -            | -                | -                | -         |   -13.14 | biguzera, kauez, lux, n1ssim, nqz |
|           26 |     4279 | 2024-03-19 | SAW               | W   | 0.723      | 1.000        | 0.112 (0.081)    | 0.388 (0.281)    | 1 (0.723) |     5.87 | biguzera, kauez, lux, n1ssim, nqz |
|           25 |     4326 | 2024-03-18 | ENCE              | W   | 0.716      | 1.000        | 0.202 (0.144)    | -                | 1 (0.716) |     7.17 | biguzera, kauez, lux, n1ssim, nqz |
|           24 |     4358 | 2024-03-17 | Eternal Fire      | L   | 0.711      | -            | -                | -                | -         |    -4.08 | biguzera, kauez, lux, n1ssim, nqz |
|           23 |     4391 | 2024-03-17 | Apeks             | W   | 0.709      | 1.000        | 0.085 (0.061)    | 0.345 (0.245)    | 1 (0.709) |     3.13 | biguzera, kauez, lux, n1ssim, nqz |
|           22 |     5188 | 2024-03-04 | ODDIK             | W   | 0.624      | -            | -                | -                | 1 (0.624) |     0.61 | biguzera, kauez, lux, n1ssim, nqz |
|           21 |     5224 | 2024-03-03 | Imperial Esports  | L   | 0.617      | -            | -                | -                | -         |   -12.11 | biguzera, kauez, lux, n1ssim, nqz |
|           20 |     5333 | 2024-03-02 | RED Canids        | W   | 0.610      | -            | -                | -                | -         |     0.76 | biguzera, kauez, lux, n1ssim, nqz |
|           19 |     5368 | 2024-03-01 | Legacy            | W   | 0.605      | -            | -                | -                | -         |     0.83 | biguzera, kauez, lux, n1ssim, nqz |
|           18 |     6851 | 2024-02-01 | w7m esports       | L   | 0.413      | -            | -                | -                | -         |   -12.85 | biguzera, kauez, lux, n1ssim, nqz |
|           17 |     6854 | 2024-02-01 | MIBR              | L   | 0.412      | -            | -                | -                | -         |    -6.77 | biguzera, kauez, lux, n1ssim, nqz |
|           16 |     6856 | 2024-02-01 | RED Canids        | W   | 0.412      | -            | -                | -                | -         |     0.44 | biguzera, kauez, lux, n1ssim, nqz |
|           15 |     7331 | 2024-01-24 | Sharks Esports    | L   | 0.359      | -            | -                | -                | -         |   -11.06 | biguzera, kauez, lux, n1ssim, nqz |
|           14 |     7404 | 2024-01-23 | w7m esports       | W   | 0.352      | -            | -                | -                | -         |     0.11 | biguzera, kauez, lux, n1ssim, nqz |
|           13 |     7446 | 2024-01-22 | inSanitY Sports   | W   | 0.346      | -            | -                | -                | -         |     0.02 | biguzera, kauez, lux, n1ssim, nqz |
|           12 |     7500 | 2024-01-21 | Case Esports      | W   | 0.339      | -            | -                | -                | -         |     0.07 | biguzera, kauez, lux, n1ssim, nqz |
|           11 |     7504 | 2024-01-21 | Imperial Esports  | L   | 0.338      | -            | -                | -                | -         |    -6.51 | biguzera, kauez, lux, n1ssim, nqz |
|           10 |     7561 | 2024-01-20 | Sharks Esports    | W   | 0.331      | -            | -                | -                | -         |     0.20 | biguzera, kauez, lux, n1ssim, nqz |
|            9 |     7630 | 2024-01-19 | Legacy            | L   | 0.326      | -            | -                | -                | -         |    -9.92 | biguzera, kauez, lux, n1ssim, nqz |
|            8 |     7642 | 2024-01-19 | w7m esports       | W   | 0.324      | -            | -                | -                | -         |     0.09 | biguzera, kauez, lux, n1ssim, nqz |
|            7 |     7875 | 2024-01-16 | Case Esports      | L   | 0.305      | -            | -                | -                | -         |    -9.56 | biguzera, kauez, lux, n1ssim, nqz |
|            6 |     7951 | 2024-01-15 | Dusty Roots       | W   | 0.299      | -            | -                | -                | -         |     0.04 | biguzera, kauez, lux, n1ssim, nqz |
|            5 |     7997 | 2024-01-14 | Sharks Esports    | L   | 0.292      | -            | -                | -                | -         |    -9.07 | biguzera, kauez, lux, n1ssim, nqz |
|            4 |     7999 | 2024-01-14 | RED Canids        | W   | 0.292      | -            | -                | -                | -         |     0.24 | biguzera, kauez, lux, n1ssim, nqz |
|            3 |     8002 | 2024-01-14 | ODDIK             | W   | 0.292      | -            | -                | -                | -         |     0.17 | biguzera, kauez, lux, n1ssim, nqz |
|            2 |     8018 | 2024-01-13 | Looking4Org       | W   | 0.286      | -            | -                | -                | -         |     0.01 | biguzera, kauez, lux, n1ssim, nqz |
|            1 |     9628 | 2023-12-04 | ex-sYnck          | L   | 0.015      | -            | -                | -                | -         |    -0.47 | biguzera, kauez, lux, n1ssim, nqz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($139,396.30)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.46) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $25,000.00     | $25,000.00      |
| 2024-04-20 |      0.938 | $100,000.00    | $93,796.30      |
| 2024-04-15 |      0.904 | $5,000.00      | $4,522.22       |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
