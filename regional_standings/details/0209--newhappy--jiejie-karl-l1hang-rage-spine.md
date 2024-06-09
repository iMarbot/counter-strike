### Roster Details<br />
Team Name: NewHappy<br />
Roster: jiejie, karl, L1haNg, rage, SPine<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [209](../standings_global.md)<br />
Regional Rank: [25]( ../standings_asia.md)<br />
Final Rank Value:  716.4<br />
<br />
Final Rank Value (716.4) = Starting Rank Value (765.7) + Head To Head Adjustments (-49.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.370[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 765.7
- 400 + ( ( 0.180 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 765.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      513 | 2024-05-22 | Clutch Gaming      | W   | 1.000      | 0.417        | -                | 0.167 (0.070)    | 0 (0.000) |    15.47 | jiejie, karl, L1haNg, rage, SPine      |
|           34 |      519 | 2024-05-22 | Clutch Gaming      | W   | 1.000      | 0.417        | -                | 0.167 (0.070)    | 0 (0.000) |    16.89 | jiejie, karl, L1haNg, rage, SPine      |
|           33 |      634 | 2024-05-21 | Gods Reign         | L   | 1.000      | -            | -                | -                | -         |    -9.28 | jiejie, karl, L1haNg, rage, SPine      |
|           32 |      636 | 2024-05-21 | Gods Reign         | L   | 1.000      | -            | -                | -                | -         |   -10.01 | jiejie, karl, L1haNg, rage, SPine      |
|           31 |     2587 | 2024-04-20 | Rare Atom          | L   | 0.940      | -            | -                | -                | -         |    -8.48 | jiejie, rage, SPine, TiGeR, zy88       |
|           30 |     2664 | 2024-04-20 | LYG Gaming         | L   | 0.936      | -            | -                | -                | -         |   -13.16 | jiejie, karl, rage, SPine, TiGeR       |
|           29 |     2679 | 2024-04-20 | LYG Gaming         | L   | 0.936      | -            | -                | -                | -         |   -14.29 | jiejie, karl, rage, SPine, TiGeR       |
|           28 |     2690 | 2024-04-20 | Bigetron Fury      | W   | 0.935      | -            | -                | -                | 0 (0.000) |     7.09 | jiejie, rage, SPine, TiGeR, zy88       |
|           27 |     2780 | 2024-04-19 | Steel Helmet       | W   | 0.929      | 0.143        | 0.012 (0.002)    | -                | 0 (0.000) |    12.08 | 18yM, AE, captainMo, DD, XiaosaGe      |
|           26 |     2849 | 2024-04-18 | Bigetron Fury      | L   | 0.921      | -            | -                | -                | -         |   -22.18 | aleph, BnTeT, Derek, nero, WasteOfAmmo |
|           25 |     3265 | 2024-04-10 | Born In Far East   | L   | 0.869      | -            | -                | -                | -         |   -15.94 | jiejie, karl, rage, SPine, TiGeR       |
|           24 |     3270 | 2024-04-10 | Born In Far East   | L   | 0.869      | -            | -                | -                | -         |   -17.15 | jiejie, karl, rage, SPine, TiGeR       |
|           23 |     3336 | 2024-04-09 | ATOX Esports       | W   | 0.862      | 0.417        | 0.047 (0.017)    | 0.609 (0.219)    | 0 (0.000) |    24.95 | jiejie, karl, rage, SPine, TiGeR       |
|           22 |     3341 | 2024-04-09 | ATOX Esports       | L   | 0.862      | -            | -                | -                | -         |    -2.02 | jiejie, karl, rage, SPine, TiGeR       |
|           21 |     3649 | 2024-04-03 | The QUBE Esports   | L   | 0.823      | -            | -                | -                | -         |   -16.93 | jiejie, karl, rage, SPine, TiGeR       |
|           20 |     3653 | 2024-04-03 | The QUBE Esports   | W   | 0.822      | 0.417        | -                | 0.138 (0.047)    | 0 (0.000) |     8.86 | jiejie, karl, rage, SPine, TiGeR       |
|           19 |     3772 | 2024-03-30 | TYLOO              | L   | 0.796      | -            | -                | -                | -         |    -8.48 | jiejie, karl, rage, SPine, TiGeR       |
|           18 |     3773 | 2024-03-30 | TYLOO              | L   | 0.796      | -            | -                | -                | -         |    -9.04 | jiejie, karl, rage, SPine, TiGeR       |
|           17 |     3801 | 2024-03-29 | -72C               | L   | 0.790      | -            | -                | -                | -         |   -12.42 | jiejie, karl, rage, SPine, TiGeR       |
|           16 |     3803 | 2024-03-29 | -72C               | L   | 0.789      | -            | -                | -                | -         |   -13.32 | jiejie, karl, rage, SPine, TiGeR       |
|           15 |     4551 | 2024-03-14 | GR Gaming          | W   | 0.690      | 0.417        | 0.007 (0.002)    | 0.428 (0.123)    | 0 (0.000) |    11.89 | jiejie, karl, rage, SPine, TiGeR       |
|           14 |     4556 | 2024-03-14 | GR Gaming          | L   | 0.689      | -            | -                | -                | -         |    -9.98 | jiejie, karl, rage, SPine, TiGeR       |
|           13 |     4615 | 2024-03-13 | MIRAI Gaming       | L   | 0.683      | -            | -                | -                | -         |   -14.82 | jiejie, karl, rage, SPine, TiGeR       |
|           12 |     4620 | 2024-03-13 | MIRAI Gaming       | W   | 0.683      | 0.417        | -                | 0.200 (0.057)    | 0 (0.000) |     6.67 | jiejie, karl, rage, SPine, TiGeR       |
|           11 |     4755 | 2024-03-11 | ATOX Esports       | L   | 0.669      | -            | -                | -                | -         |    -1.86 | jiejie, L1haNg, rage, SPine, zy88      |
|           10 |     4761 | 2024-03-11 | E9 esports         | W   | 0.668      | 0.143        | 0.008 (0.001)    | -                | 0 (0.000) |     8.75 | jiejie, L1haNg, rage, SPine, zy88      |
|            9 |     4798 | 2024-03-10 | Myth Avenue Gaming | W   | 0.662      | 0.143        | 0.005 (0.000)    | 0.192 (0.018)    | 0 (0.000) |     8.75 | jiejie, L1haNg, rage, SPine, zy88      |
|            8 |     4868 | 2024-03-09 | E9 esports         | L   | 0.655      | -            | -                | -                | -         |   -12.05 | jiejie, L1haNg, rage, SPine, zy88      |
|            7 |     4899 | 2024-03-07 | Myth Avenue Gaming | W   | 0.647      | 0.143        | 0.005 (0.000)    | 0.192 (0.018)    | -         |     8.48 | jiejie, L1haNg, rage, SPine, zy88      |
|            6 |     5056 | 2024-03-05 | DEWA United        | W   | 0.634      | 0.143        | 0.002 (0.000)    | -                | -         |     7.73 | jiejie, L1haNg, rage, SPine, zy88      |
|            5 |     5940 | 2024-02-20 | Lynn Vision Gaming | L   | 0.536      | -            | -                | -                | -         |    -2.75 | jiejie, karl, rage, SPine, TiGeR       |
|            4 |     5948 | 2024-02-20 | Lynn Vision Gaming | L   | 0.536      | -            | -                | -                | -         |    -2.83 | jiejie, karl, rage, SPine, TiGeR       |
|            3 |     6126 | 2024-02-17 | Lynn Vision Gaming | W   | 0.516      | 0.143        | 0.063 (0.005)    | 0.431 (0.032)    | -         |    13.77 | jiejie, L1haNg, rage, SPine, TiGeR     |
|            2 |     6135 | 2024-02-17 | Myth Avenue Gaming | W   | 0.515      | 0.143        | 0.005 (0.000)    | -                | -         |     7.32 | jiejie, L1haNg, rage, SPine, TiGeR     |
|            1 |     6184 | 2024-02-16 | GR Gaming          | W   | 0.508      | 0.143        | 0.007 (0.000)    | 0.428 (0.031)    | -         |     8.99 | jiejie, karl, L1haNg, rage, SPine      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,955.62)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.942 | $1,381.25      | $1,301.45       |
| 2024-03-11 |      0.669 | $6,958.07      | $4,654.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
