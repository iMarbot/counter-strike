### Roster Details<br />
Team Name: Gods Reign<br />
Roster: 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [111](../standings_global.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
Final Rank Value:  853.8<br />
<br />
Final Rank Value (853.8) = Starting Rank Value (920.0) + Head To Head Adjustments (-66.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.147[<sup>2</sup>](#table1)

The average of these factors is 0.256<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 920.0
- 400 + ( ( 0.256 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 920.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           61 |      242 | 2024-05-26 | True Rippers        | W   | 1.000      | 0.262        | 0.025 (0.007)    | 0.241 (0.063)    | 0 (0.000) |    11.42 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn         |
|           60 |      245 | 2024-05-25 | Marcos Gaming       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.44 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           59 |      514 | 2024-05-22 | MIRAI Gaming        | W   | 1.000      | 0.417        | -                | 0.200 (0.083)    | 0 (0.000) |    11.42 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           58 |      520 | 2024-05-22 | MIRAI Gaming        | L   | 1.000      | -            | -                | -                | -         |   -20.46 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           57 |      634 | 2024-05-21 | NewHappy            | W   | 1.000      | 0.417        | 0.020 (0.008)    | 0.231 (0.096)    | 0 (0.000) |     9.28 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           56 |      636 | 2024-05-21 | NewHappy            | W   | 1.000      | 0.417        | 0.020 (0.008)    | 0.231 (0.096)    | 0 (0.000) |    10.01 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           55 |      718 | 2024-05-20 | DEWA United         | W   | 1.000      | 0.417        | -                | 0.176 (0.073)    | 0 (0.000) |    10.90 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           54 |      725 | 2024-05-20 | DEWA United         | L   | 1.000      | -            | -                | -                | -         |   -21.02 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           53 |      794 | 2024-05-19 | Clutch Gaming       | W   | 1.000      | 0.417        | -                | 0.167 (0.070)    | 0 (0.000) |    11.38 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           52 |      809 | 2024-05-19 | Clutch Gaming       | W   | 1.000      | 0.417        | -                | 0.167 (0.070)    | 0 (0.000) |    12.37 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           51 |     1189 | 2024-05-15 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -0.46 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           50 |     1201 | 2024-05-15 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -0.46 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           49 |     1292 | 2024-05-14 | TYLOO               | L   | 1.000      | -            | -                | -                | -         |   -10.72 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           48 |     1298 | 2024-05-14 | TYLOO               | L   | 1.000      | -            | -                | -                | -         |   -11.62 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           47 |     1342 | 2024-05-13 | GR Gaming           | L   | 1.000      | -            | -                | -                | -         |   -14.03 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           46 |     1663 | 2024-05-08 | Lynn Vision Gaming  | L   | 1.000      | -            | -                | -                | -         |    -8.09 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           45 |     2152 | 2024-04-28 | True Rippers        | W   | 0.989      | 0.143        | 0.025 (0.004)    | -                | -         |    10.69 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           44 |     2225 | 2024-04-27 | True Rippers        | W   | 0.983      | 0.143        | 0.025 (0.004)    | -                | -         |    11.51 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           43 |     2773 | 2024-04-19 | -72C                | L   | 0.929      | -            | -                | -                | -         |   -16.62 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           42 |     2778 | 2024-04-19 | -72C                | L   | 0.929      | -            | -                | -                | -         |   -17.99 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           41 |     2977 | 2024-04-16 | DEWA United         | L   | 0.909      | -            | -                | -                | -         |   -20.91 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           40 |     3249 | 2024-04-10 | BIG                 | L   | 0.870      | -            | -                | -                | -         |    -1.76 | Bhavi, f1redup, Ph1NNN, R2B2, yOOm             |
|           39 |     3320 | 2024-04-09 | Ninjas in Pyjamas   | L   | 0.864      | -            | -                | -                | -         |    -6.05 | Bhavi, f1redup, Ph1NNN, R2B2, yOOm             |
|           38 |     3650 | 2024-04-03 | Born In Far East    | L   | 0.823      | -            | -                | -                | -         |   -21.55 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           37 |     3654 | 2024-04-03 | Born In Far East    | W   | 0.822      | -            | -                | -                | -         |     4.11 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           36 |     3753 | 2024-03-31 | True Rippers        | W   | 0.801      | 0.143        | 0.025 (0.003)    | -                | -         |     7.28 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           35 |     3809 | 2024-03-29 | Marcos Gaming       | W   | 0.789      | -            | -                | -                | -         |     6.19 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           34 |     3841 | 2024-03-28 | Carnival Gaming     | W   | 0.783      | -            | -                | -                | -         |     4.19 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           33 |     3850 | 2024-03-28 | Crescent            | W   | 0.782      | -            | -                | -                | -         |     2.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           32 |     4005 | 2024-03-25 | love birds          | W   | 0.765      | -            | -                | -                | -         |     7.05 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           31 |     4015 | 2024-03-25 | st4rboys            | W   | 0.764      | 0.242        | 0.014 (0.003)    | -                | -         |     5.13 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           30 |     4054 | 2024-03-24 | Marcos Gaming       | W   | 0.755      | -            | -                | -                | -         |     6.09 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           29 |     4055 | 2024-03-23 | Grayfox Esports     | W   | 0.754      | -            | -                | -                | -         |     5.51 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           28 |     4440 | 2024-03-16 | Aurora Gaming       | L   | 0.703      | -            | -                | -                | -         |    -1.08 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           27 |     4449 | 2024-03-15 | Bad News Kangaroos  | W   | 0.701      | 0.435        | 0.031 (0.010)    | 0.241 (0.073)    | 1 (0.701) |    12.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           26 |     4501 | 2024-03-15 | Aurora Gaming       | L   | 0.695      | -            | -                | -                | -         |    -1.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           25 |     4559 | 2024-03-14 | Garuda Wisnu Voyage | W   | 0.689      | -            | -                | -                | 1 (0.689) |     3.15 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           24 |     5029 | 2024-03-06 | LYG Gaming          | L   | 0.636      | -            | -                | -                | -         |   -14.79 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           23 |     5037 | 2024-03-06 | LYG Gaming          | W   | 0.636      | 0.417        | -                | 0.275 (0.073)    | -         |     5.20 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           22 |     5119 | 2024-03-05 | Marcos Gaming       | W   | 0.629      | -            | -                | -                | -         |     5.51 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           21 |     5199 | 2024-03-04 | Grayfox Esports     | W   | 0.622      | -            | -                | -                | -         |     4.95 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           20 |     5252 | 2024-03-03 | True Rippers        | W   | 0.616      | 0.143        | 0.025 (0.002)    | -                | -         |     7.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           19 |     5257 | 2024-03-03 | Crescent            | W   | 0.615      | -            | -                | -                | -         |     1.45 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           18 |     5341 | 2024-03-02 | Marcos Gaming       | L   | 0.610      | -            | -                | -                | -         |   -14.12 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           17 |     5354 | 2024-03-02 | RETALIATION         | W   | 0.609      | -            | -                | -                | -         |     1.30 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           16 |     5627 | 2024-02-25 | Grayfox Esports     | W   | 0.568      | -            | -                | -                | -         |     4.50 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           15 |     5628 | 2024-02-24 | 2ez Gaming          | W   | 0.568      | -            | -                | -                | -         |     3.98 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           14 |     5882 | 2024-02-21 | ATOX Esports        | L   | 0.543      | -            | -                | -                | -         |    -1.94 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           13 |     5893 | 2024-02-21 | ATOX Esports        | W   | 0.543      | 0.417        | 0.047 (0.011)    | 0.609 (0.138)    | -         |    15.36 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           12 |     5951 | 2024-02-20 | The QUBE Esports    | L   | 0.536      | -            | -                | -                | -         |   -12.62 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           11 |     5954 | 2024-02-20 | The QUBE Esports    | L   | 0.536      | -            | -                | -                | -         |   -13.05 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           10 |     6165 | 2024-02-16 | ZEUSGG              | L   | 0.510      | -            | -                | -                | -         |   -13.49 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|            9 |     6173 | 2024-02-16 | ZEUSGG              | L   | 0.509      | -            | -                | -                | -         |   -13.80 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|            8 |     6846 | 2024-02-02 | Gods Reign          | L   | 0.415      | -            | -                | -                | -         |    -9.94 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            7 |     6946 | 2024-01-31 | 2ez Gaming          | W   | 0.403      | -            | -                | -                | -         |     2.01 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn       |
|            6 |     6987 | 2024-01-30 | Firedup Gaming      | W   | 0.396      | -            | -                | -                | -         |     1.86 | ChAmP, LordGrim, lynX, N1kace, Robben          |
|            5 |     7059 | 2024-01-29 | Enigma Gaming       | W   | 0.389      | -            | -                | -                | -         |     2.75 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |
|            4 |     7212 | 2024-01-27 | True Rippers        | L   | 0.375      | -            | -                | -                | -         |    -8.15 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |
|            3 |     7605 | 2024-01-20 | Enigma Gaming       | L   | 0.329      | -            | -                | -                | -         |    -8.12 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |
|            2 |     8630 | 2023-12-21 | ROG Academy         | W   | 0.129      | -            | -                | -                | -         |     0.21 | arakyn, BrOCK, KillSwiTcH, SeeK, vrenyy        |
|            1 |     8639 | 2023-12-20 | Enigma Gaming       | L   | 0.123      | -            | -                | -                | -         |    -3.06 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,732.54)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-05-22 |      1.000 | $300.00        | $300.00         |
| 2024-04-14 |      0.896 | $15,000.00     | $13,443.75      |
| 2024-03-25 |      0.765 | $500.00        | $382.43         |
| 2024-03-24 |      0.755 | $1,000.00      | $754.68         |
| 2024-03-16 |      0.703 | $12,500.00     | $8,781.25       |
| 2024-02-25 |      0.568 | $1,000.00      | $568.06         |
| 2024-01-20 |      0.329 | $1,503.76      | $494.57         |
| 2023-12-21 |      0.130 | $60.12         | $7.81           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
