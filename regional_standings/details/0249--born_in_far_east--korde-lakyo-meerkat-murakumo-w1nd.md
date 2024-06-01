### Roster Details<br />
Team Name: Born In Far East<br />
Roster: korde, lakyo, meerkat, murakumo, W1nd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [249](../standings_global.md)<br />
Regional Rank: [164]( ../standings_europe.md)<br />
Final Rank Value:  684.4<br />
<br />
Final Rank Value (684.4) = Starting Rank Value (708.0) + Head To Head Adjustments (-23.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.0
- 400 + ( ( 0.151 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 708.0


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
|           32 |     1282 | 2024-05-14 | DEWA United        | L   | 1.000      | -            | -                | -                | -         |   -15.30 | korde, lakyo, meerkat, murakumo, W1nd              |
|           31 |     1288 | 2024-05-14 | DEWA United        | W   | 1.000      | 0.417        | 0.002 (0.001)    | 0.185 (0.077)    | 0 (0.000) |    16.24 | korde, lakyo, meerkat, murakumo, W1nd              |
|           30 |     2718 | 2024-04-19 | ATOX Esports       | L   | 0.929      | -            | -                | -                | -         |    -2.33 | korde, lakyo, meerkat, murakumo, W1nd              |
|           29 |     2723 | 2024-04-19 | ATOX Esports       | L   | 0.929      | -            | -                | -                | -         |    -2.39 | korde, lakyo, meerkat, murakumo, W1nd              |
|           28 |     2918 | 2024-04-16 | Rare Atom          | L   | 0.909      | -            | -                | -                | -         |   -11.61 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           27 |     3190 | 2024-04-10 | NewHappy           | W   | 0.869      | 0.417        | 0.020 (0.007)    | 0.231 (0.084)    | 0 (0.000) |    16.15 | korde, lakyo, meerkat, murakumo, W1nd              |
|           26 |     3195 | 2024-04-10 | NewHappy           | W   | 0.869      | 0.417        | 0.020 (0.007)    | 0.231 (0.084)    | 0 (0.000) |    17.37 | korde, lakyo, meerkat, murakumo, W1nd              |
|           25 |     3258 | 2024-04-09 | The QUBE Esports   | W   | 0.862      | 0.417        | 0.001 (0.000)    | 0.120 (0.043)    | 0 (0.000) |    15.34 | korde, lakyo, meerkat, murakumo, W1nd              |
|           24 |     3263 | 2024-04-09 | The QUBE Esports   | W   | 0.862      | 0.417        | 0.001 (0.000)    | 0.120 (0.043)    | 0 (0.000) |    16.52 | korde, lakyo, meerkat, murakumo, W1nd              |
|           23 |     3563 | 2024-04-03 | Gods Reign         | W   | 0.823      | 0.417        | 0.086 (0.029)    | 0.461 (0.158)    | 0 (0.000) |    22.09 | korde, lakyo, meerkat, murakumo, W1nd              |
|           22 |     3567 | 2024-04-03 | Gods Reign         | L   | 0.822      | -            | -                | -                | -         |    -3.58 | korde, lakyo, meerkat, murakumo, W1nd              |
|           21 |     3903 | 2024-03-26 | Depresure          | W   | 0.769      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.60 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           20 |     4436 | 2024-03-14 | MIRAI Gaming       | L   | 0.690      | -            | -                | -                | -         |    -8.47 | korde, lakyo, meerkat, murakumo, W1nd              |
|           19 |     4441 | 2024-03-14 | MIRAI Gaming       | L   | 0.689      | -            | -                | -                | -         |    -8.98 | korde, lakyo, meerkat, murakumo, W1nd              |
|           18 |     4502 | 2024-03-13 | The MongolZ        | L   | 0.683      | -            | -                | -                | -         |    -0.10 | korde, lakyo, meerkat, murakumo, W1nd              |
|           17 |     4504 | 2024-03-13 | The MongolZ        | L   | 0.683      | -            | -                | -                | -         |    -0.10 | korde, lakyo, meerkat, murakumo, W1nd              |
|           16 |     4565 | 2024-03-12 | ROUX from hell     | L   | 0.676      | -            | -                | -                | -         |   -14.78 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           15 |     4888 | 2024-03-06 | TYLOO              | L   | 0.636      | -            | -                | -                | -         |    -3.55 | korde, lakyo, meerkat, murakumo, W1nd              |
|           14 |     4893 | 2024-03-06 | TYLOO              | L   | 0.636      | -            | -                | -                | -         |    -3.67 | korde, lakyo, meerkat, murakumo, W1nd              |
|           13 |     4967 | 2024-03-05 | -72C               | L   | 0.630      | -            | -                | -                | -         |    -6.95 | korde, lakyo, meerkat, murakumo, W1nd              |
|           12 |     4972 | 2024-03-05 | -72C               | L   | 0.629      | -            | -                | -                | -         |    -7.31 | korde, lakyo, meerkat, murakumo, W1nd              |
|           11 |     5546 | 2024-02-24 | GR Gaming          | L   | 0.563      | -            | -                | -                | -         |    -5.75 | korde, lakyo, meerkat, murakumo, W1nd              |
|           10 |     5556 | 2024-02-24 | GR Gaming          | L   | 0.563      | -            | -                | -                | -         |    -6.01 | korde, lakyo, meerkat, murakumo, W1nd              |
|            9 |     5722 | 2024-02-21 | Lynn Vision Gaming | L   | 0.543      | -            | -                | -                | -         |    -1.54 | korde, lakyo, meerkat, murakumo, W1nd              |
|            8 |     5727 | 2024-02-21 | Lynn Vision Gaming | L   | 0.543      | -            | -                | -                | -         |    -1.57 | korde, lakyo, meerkat, murakumo, W1nd              |
|            7 |     5844 | 2024-02-19 | LYG Gaming         | L   | 0.529      | -            | -                | -                | -         |    -7.64 | korde, lakyo, meerkat, murakumo, W1nd              |
|            6 |     5847 | 2024-02-19 | LYG Gaming         | L   | 0.529      | -            | -                | -                | -         |    -8.00 | korde, lakyo, meerkat, murakumo, W1nd              |
|            5 |     6162 | 2024-02-13 | Clutch Gaming      | L   | 0.490      | -            | -                | -                | -         |    -8.01 | korde, lakyo, meerkat, murakumo, W1nd              |
|            4 |     6166 | 2024-02-13 | Clutch Gaming      | L   | 0.489      | -            | -                | -                | -         |    -8.37 | korde, lakyo, meerkat, murakumo, W1nd              |
|            3 |     8631 | 2023-12-16 | The QUBE Esports   | W   | 0.096      | 0.143        | 0.001 (0.000)    | 0.120 (0.002)    | 0 (0.000) |     1.63 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            2 |     8751 | 2023-12-15 | Gods Reign         | W   | 0.089      | 0.143        | 0.004 (0.000)    | 0.105 (0.001)    | 0 (0.000) |     1.39 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN     |
|            1 |     9518 | 2023-12-02 | GR Gaming          | L   | 0.001      | -            | -                | -                | -         |    -0.02 | edGe, korde, lakyo, meerkat, W1nd                  |

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
