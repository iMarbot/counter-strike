### Roster Details<br />
Team Name: Gods Reign<br />
Roster: 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [103](../standings_global.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
Final Rank Value:  864.1<br />
<br />
Final Rank Value (864.1) = Starting Rank Value (920.9) + Head To Head Adjustments (-56.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.484[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.084[<sup>2</sup>](#table1)
- LAN Wins: 0.147[<sup>2</sup>](#table1)

The average of these factors is 0.256<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 920.9
- 400 + ( ( 0.256 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 920.9


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
|           59 |      234 | 2024-05-26 | True Rippers        | W   | 1.000      | 0.262        | 0.025 (0.007)    | 0.241 (0.063)    | 0 (0.000) |    11.11 | 1nhuman, Bhavi, Ph1NNN, R2B2, reV3nnnn         |
|           58 |      237 | 2024-05-25 | Marcos Gaming       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.31 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           57 |      507 | 2024-05-22 | MIRAI Gaming        | W   | 1.000      | 0.417        | -                | 0.200 (0.083)    | 0 (0.000) |    10.98 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           56 |      513 | 2024-05-22 | MIRAI Gaming        | L   | 1.000      | -            | -                | -                | -         |   -20.93 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           55 |      623 | 2024-05-21 | NewHappy            | W   | 1.000      | 0.417        | 0.020 (0.008)    | 0.231 (0.096)    | 0 (0.000) |     9.00 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           54 |      625 | 2024-05-21 | NewHappy            | W   | 1.000      | 0.417        | 0.020 (0.008)    | 0.231 (0.096)    | 0 (0.000) |     9.69 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           53 |      706 | 2024-05-20 | DEWA United         | W   | 1.000      | 0.417        | -                | 0.185 (0.077)    | 0 (0.000) |    10.54 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           52 |      713 | 2024-05-20 | DEWA United         | L   | 1.000      | -            | -                | -                | -         |   -21.39 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           51 |      782 | 2024-05-19 | Clutch Gaming       | W   | 1.000      | 0.417        | -                | 0.167 (0.070)    | 0 (0.000) |    10.81 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           50 |      797 | 2024-05-19 | Clutch Gaming       | W   | 1.000      | 0.417        | -                | 0.167 (0.070)    | 0 (0.000) |    11.72 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           49 |     1179 | 2024-05-15 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -0.50 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           48 |     1191 | 2024-05-15 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -0.50 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           47 |     1281 | 2024-05-14 | TYLOO               | L   | 1.000      | -            | -                | -                | -         |   -10.67 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           46 |     1287 | 2024-05-14 | TYLOO               | L   | 1.000      | -            | -                | -                | -         |   -11.56 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           45 |     1330 | 2024-05-13 | GR Gaming           | L   | 1.000      | -            | -                | -                | -         |   -14.57 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           44 |     1645 | 2024-05-08 | Lynn Vision Gaming  | L   | 1.000      | -            | -                | -                | -         |    -8.58 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           43 |     2117 | 2024-04-28 | True Rippers        | W   | 0.989      | 0.143        | 0.025 (0.004)    | -                | -         |    10.19 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           42 |     2190 | 2024-04-27 | True Rippers        | W   | 0.983      | 0.143        | 0.025 (0.004)    | -                | -         |    10.95 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           41 |     2717 | 2024-04-19 | -72C                | L   | 0.929      | -            | -                | -                | -         |   -17.35 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           40 |     2722 | 2024-04-19 | -72C                | L   | 0.929      | -            | -                | -                | -         |   -18.75 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           39 |     2916 | 2024-04-16 | DEWA United         | L   | 0.909      | -            | -                | -                | -         |   -21.39 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           38 |     3176 | 2024-04-10 | BIG                 | L   | 0.870      | -            | -                | -                | -         |    -1.85 | Bhavi, f1redup, Ph1NNN, R2B2, yOOm             |
|           37 |     3241 | 2024-04-09 | Ninjas in Pyjamas   | L   | 0.864      | -            | -                | -                | -         |    -6.55 | Bhavi, f1redup, Ph1NNN, R2B2, yOOm             |
|           36 |     3563 | 2024-04-03 | Born In Far East    | L   | 0.823      | -            | -                | -                | -         |   -22.09 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           35 |     3567 | 2024-04-03 | Born In Far East    | W   | 0.822      | -            | -                | -                | -         |     3.58 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           34 |     3660 | 2024-03-31 | True Rippers        | W   | 0.801      | 0.143        | 0.025 (0.003)    | -                | -         |     6.75 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           33 |     3715 | 2024-03-29 | Marcos Gaming       | W   | 0.789      | -            | -                | -                | -         |     5.73 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           32 |     3748 | 2024-03-28 | Carnival Gaming     | W   | 0.783      | -            | -                | -                | -         |     3.80 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           31 |     3757 | 2024-03-28 | Crescent            | W   | 0.782      | -            | -                | -                | -         |     2.03 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           30 |     3908 | 2024-03-25 | love birds          | W   | 0.765      | -            | -                | -                | -         |     6.48 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           29 |     3919 | 2024-03-25 | st4rboys            | W   | 0.764      | 0.242        | 0.014 (0.003)    | -                | -         |     4.66 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           28 |     3956 | 2024-03-24 | Marcos Gaming       | W   | 0.755      | -            | -                | -                | -         |     5.57 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           27 |     3957 | 2024-03-23 | Grayfox Esports     | W   | 0.754      | -            | -                | -                | -         |     5.01 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           26 |     4334 | 2024-03-16 | Aurora Gaming       | L   | 0.703      | -            | -                | -                | -         |    -1.17 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           25 |     4342 | 2024-03-15 | Bad News Kangaroos  | W   | 0.701      | 0.435        | 0.031 (0.010)    | 0.241 (0.073)    | 1 (0.701) |    11.31 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           24 |     4391 | 2024-03-15 | Aurora Gaming       | L   | 0.695      | -            | -                | -                | -         |    -1.10 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           23 |     4445 | 2024-03-14 | Garuda Wisnu Voyage | W   | 0.689      | -            | -                | -                | 1 (0.689) |     2.80 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           22 |     4895 | 2024-03-06 | LYG Gaming          | L   | 0.636      | -            | -                | -                | -         |   -15.31 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           21 |     4903 | 2024-03-06 | LYG Gaming          | W   | 0.636      | 0.417        | -                | 0.275 (0.073)    | -         |     4.67 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           20 |     4974 | 2024-03-05 | Marcos Gaming       | W   | 0.629      | -            | -                | -                | -         |     4.97 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           19 |     5053 | 2024-03-04 | Grayfox Esports     | W   | 0.622      | -            | -                | -                | -         |     4.44 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           18 |     5104 | 2024-03-03 | True Rippers        | W   | 0.616      | 0.143        | 0.025 (0.002)    | -                | -         |     6.60 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           17 |     5109 | 2024-03-03 | Crescent            | W   | 0.615      | -            | -                | -                | -         |     1.26 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           16 |     5193 | 2024-03-02 | Marcos Gaming       | L   | 0.610      | -            | -                | -                | -         |   -14.67 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           15 |     5205 | 2024-03-02 | RETALIATION         | W   | 0.609      | -            | -                | -                | -         |     1.13 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           14 |     5469 | 2024-02-25 | Grayfox Esports     | W   | 0.568      | -            | -                | -                | -         |     3.99 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           13 |     5470 | 2024-02-24 | 2ez Gaming          | W   | 0.568      | -            | -                | -                | -         |     3.50 | Bhavi, f1redup, Ph1NNN, R2B2, reV3nnnn         |
|           12 |     5719 | 2024-02-21 | ATOX Esports        | L   | 0.543      | -            | -                | -                | -         |    -2.71 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           11 |     5728 | 2024-02-21 | ATOX Esports        | W   | 0.543      | 0.417        | 0.047 (0.011)    | 0.601 (0.136)    | -         |    14.63 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|           10 |     5781 | 2024-02-20 | The QUBE Esports    | L   | 0.536      | -            | -                | -                | -         |   -11.19 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|            9 |     5784 | 2024-02-20 | The QUBE Esports    | L   | 0.536      | -            | -                | -                | -         |   -11.66 | Bhavi, CycloneF, f1redup, Ph1NNN, R2B2         |
|            8 |     6641 | 2024-02-02 | Gods Reign          | L   | 0.415      | -            | -                | -                | -         |    -9.95 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|            7 |     6733 | 2024-01-31 | 2ez Gaming          | W   | 0.403      | -            | -                | -                | -         |     2.00 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn       |
|            6 |     6771 | 2024-01-30 | Firedup Gaming      | W   | 0.396      | -            | -                | -                | -         |     1.86 | ChAmP, LordGrim, lynX, N1kace, Robben          |
|            5 |     6842 | 2024-01-29 | Enigma Gaming       | W   | 0.389      | -            | -                | -                | -         |     2.74 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |
|            4 |     6992 | 2024-01-27 | True Rippers        | L   | 0.375      | -            | -                | -                | -         |    -8.15 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |
|            3 |     7361 | 2024-01-20 | Enigma Gaming       | L   | 0.329      | -            | -                | -                | -         |    -8.12 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |
|            2 |     8373 | 2023-12-21 | ROG Academy         | W   | 0.129      | -            | -                | -                | -         |     0.21 | arakyn, BrOCK, KillSwiTcH, SeeK, vrenyy        |
|            1 |     8382 | 2023-12-20 | Enigma Gaming       | L   | 0.123      | -            | -                | -                | -         |    -3.06 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn            |

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
