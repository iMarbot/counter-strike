### Roster Details<br />
Team Name: Born In Far East<br />
Roster: korde, lakyo, meerkat, murakumo, W1nd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [251](../standings_global.md)<br />
Regional Rank: [165]( ../standings_europe.md)<br />
Final Rank Value:  686.0<br />
<br />
Final Rank Value (686.0) = Starting Rank Value (709.6) + Head To Head Adjustments (-23.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.054[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.6
- 400 + ( ( 0.152 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 709.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |     1293 | 2024-05-14 | DEWA United        | L   | 1.000      | -            | -                | -                | -         |   -15.49 | korde, lakyo, meerkat, murakumo, W1nd              |
|           33 |     1299 | 2024-05-14 | DEWA United        | W   | 1.000      | 0.417        | 0.002 (0.001)    | 0.176 (0.073)    | 0 (0.000) |    16.04 | korde, lakyo, meerkat, murakumo, W1nd              |
|           32 |     2774 | 2024-04-19 | ATOX Esports       | L   | 0.929      | -            | -                | -                | -         |    -2.00 | korde, lakyo, meerkat, murakumo, W1nd              |
|           31 |     2779 | 2024-04-19 | ATOX Esports       | L   | 0.929      | -            | -                | -                | -         |    -2.04 | korde, lakyo, meerkat, murakumo, W1nd              |
|           30 |     2979 | 2024-04-16 | Rare Atom          | L   | 0.909      | -            | -                | -                | -         |   -11.67 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           29 |     3265 | 2024-04-10 | NewHappy           | W   | 0.869      | 0.417        | 0.020 (0.007)    | 0.231 (0.084)    | 0 (0.000) |    15.94 | korde, lakyo, meerkat, murakumo, W1nd              |
|           28 |     3270 | 2024-04-10 | NewHappy           | W   | 0.869      | 0.417        | 0.020 (0.007)    | 0.231 (0.084)    | 0 (0.000) |    17.15 | korde, lakyo, meerkat, murakumo, W1nd              |
|           27 |     3337 | 2024-04-09 | The QUBE Esports   | W   | 0.862      | 0.417        | 0.000 (0.000)    | 0.138 (0.050)    | 0 (0.000) |    12.03 | korde, lakyo, meerkat, murakumo, W1nd              |
|           26 |     3342 | 2024-04-09 | The QUBE Esports   | W   | 0.862      | 0.417        | 0.000 (0.000)    | 0.138 (0.050)    | 0 (0.000) |    12.98 | korde, lakyo, meerkat, murakumo, W1nd              |
|           25 |     3650 | 2024-04-03 | Gods Reign         | W   | 0.823      | 0.417        | 0.086 (0.029)    | 0.461 (0.158)    | 0 (0.000) |    21.55 | korde, lakyo, meerkat, murakumo, W1nd              |
|           24 |     3654 | 2024-04-03 | Gods Reign         | L   | 0.822      | -            | -                | -                | -         |    -4.11 | korde, lakyo, meerkat, murakumo, W1nd              |
|           23 |     4000 | 2024-03-26 | Depresure          | W   | 0.769      | 0.262        | 0.000 (0.000)    | -                | 0 (0.000) |     5.37 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           22 |     4550 | 2024-03-14 | MIRAI Gaming       | L   | 0.690      | -            | -                | -                | -         |    -8.87 | korde, lakyo, meerkat, murakumo, W1nd              |
|           21 |     4555 | 2024-03-14 | MIRAI Gaming       | L   | 0.689      | -            | -                | -                | -         |    -9.42 | korde, lakyo, meerkat, murakumo, W1nd              |
|           20 |     4617 | 2024-03-13 | The MongolZ        | L   | 0.683      | -            | -                | -                | -         |    -0.10 | korde, lakyo, meerkat, murakumo, W1nd              |
|           19 |     4619 | 2024-03-13 | The MongolZ        | L   | 0.683      | -            | -                | -                | -         |    -0.10 | korde, lakyo, meerkat, murakumo, W1nd              |
|           18 |     4686 | 2024-03-12 | ROUX from hell     | L   | 0.676      | -            | -                | -                | -         |   -15.05 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           17 |     5020 | 2024-03-06 | TYLOO              | L   | 0.636      | -            | -                | -                | -         |    -4.02 | korde, lakyo, meerkat, murakumo, W1nd              |
|           16 |     5027 | 2024-03-06 | TYLOO              | L   | 0.636      | -            | -                | -                | -         |    -4.17 | korde, lakyo, meerkat, murakumo, W1nd              |
|           15 |     5111 | 2024-03-05 | -72C               | L   | 0.630      | -            | -                | -                | -         |    -7.24 | korde, lakyo, meerkat, murakumo, W1nd              |
|           14 |     5117 | 2024-03-05 | -72C               | L   | 0.629      | -            | -                | -                | -         |    -7.63 | korde, lakyo, meerkat, murakumo, W1nd              |
|           13 |     5706 | 2024-02-24 | GR Gaming          | L   | 0.563      | -            | -                | -                | -         |    -6.00 | korde, lakyo, meerkat, murakumo, W1nd              |
|           12 |     5716 | 2024-02-24 | GR Gaming          | L   | 0.563      | -            | -                | -                | -         |    -6.28 | korde, lakyo, meerkat, murakumo, W1nd              |
|           11 |     5886 | 2024-02-21 | Lynn Vision Gaming | L   | 0.543      | -            | -                | -                | -         |    -1.66 | korde, lakyo, meerkat, murakumo, W1nd              |
|           10 |     5892 | 2024-02-21 | Lynn Vision Gaming | L   | 0.543      | -            | -                | -                | -         |    -1.69 | korde, lakyo, meerkat, murakumo, W1nd              |
|            9 |     5939 | 2024-02-20 | ZEUSGG             | W   | 0.536      | 0.417        | 0.000 (0.000)    | 0.090 (0.020)    | 0 (0.000) |     6.10 | korde, lakyo, meerkat, murakumo, W1nd              |
|            8 |     5947 | 2024-02-20 | ZEUSGG             | W   | 0.536      | 0.417        | -                | 0.090 (0.020)    | 0 (0.000) |     6.37 | korde, lakyo, meerkat, murakumo, W1nd              |
|            7 |     6016 | 2024-02-19 | LYG Gaming         | L   | 0.529      | -            | -                | -                | -         |    -7.66 | korde, lakyo, meerkat, murakumo, W1nd              |
|            6 |     6019 | 2024-02-19 | LYG Gaming         | L   | 0.529      | -            | -                | -                | -         |    -8.02 | korde, lakyo, meerkat, murakumo, W1nd              |
|            5 |     6347 | 2024-02-13 | Clutch Gaming      | L   | 0.490      | -            | -                | -                | -         |    -7.88 | korde, lakyo, meerkat, murakumo, W1nd              |
|            4 |     6351 | 2024-02-13 | Clutch Gaming      | L   | 0.489      | -            | -                | -                | -         |    -8.23 | korde, lakyo, meerkat, murakumo, W1nd              |
|            3 |     8892 | 2023-12-16 | The QUBE Esports   | W   | 0.096      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.93 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            2 |     9013 | 2023-12-15 | Gods Reign         | W   | 0.089      | 0.143        | 0.004 (0.000)    | 0.105 (0.001)    | -         |     1.38 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN     |
|            1 |     9800 | 2023-12-02 | GR Gaming          | L   | 0.001      | -            | -                | -                | -         |    -0.02 | edGe, korde, lakyo, meerkat, W1nd                  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($384.44)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
