### Roster Details<br />
Team Name: Born In Far East<br />
Roster: korde, lakyo, meerkat, murakumo, W1nd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [203](../standings_global.md)<br />
Regional Rank: [135]( ../standings_europe.md)<br />
Final Rank Value:  710.7<br />
<br />
Final Rank Value (710.7) = Starting Rank Value (741.7) + Head To Head Adjustments (-31.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.288[<sup>1</sup>](#table2)
- Bounty Collected: 0.342[<sup>2</sup>](#table1)
- Opponent Network: 0.059[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 741.7
- 400 + ( ( 0.172 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 741.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      839 | 2024-04-19 | ATOX Esports             | L   | 1.000      | -            | -                | -                | -             |    -4.03 | korde, lakyo, meerkat, murakumo, W1nd              |
|           31 |      844 | 2024-04-19 | ATOX Esports             | L   | 1.000      | -            | -                | -                | -             |    -4.20 | korde, lakyo, meerkat, murakumo, W1nd              |
|           30 |     1013 | 2024-04-16 | Rare Atom                | L   | 1.000      | -            | -                | -                | -             |   -12.31 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           29 |     1237 | 2024-04-10 | High Five (Chinese team) | W   | 1.000      | 0.417        | 0.045 (0.019)    | 0.282 (0.117)    | false (0.000) |    18.67 | korde, lakyo, meerkat, murakumo, W1nd              |
|           28 |     1242 | 2024-04-10 | High Five (Chinese team) | W   | 1.000      | 0.417        | 0.045 (0.019)    | 0.282 (0.117)    | false (0.000) |    20.30 | korde, lakyo, meerkat, murakumo, W1nd              |
|           27 |     1300 | 2024-04-09 | The QUBE Esports         | W   | 1.000      | 0.417        | 0.004 (0.002)    | 0.168 (0.070)    | false (0.000) |    18.24 | korde, lakyo, meerkat, murakumo, W1nd              |
|           26 |     1305 | 2024-04-09 | The QUBE Esports         | W   | 1.000      | 0.417        | 0.004 (0.002)    | 0.168 (0.070)    | false (0.000) |    19.85 | korde, lakyo, meerkat, murakumo, W1nd              |
|           25 |     1545 | 2024-04-03 | Gods Reign               | W   | 0.984      | 0.417        | 0.174 (0.071)    | 0.479 (0.196)    | false (0.000) |    25.38 | korde, lakyo, meerkat, murakumo, W1nd              |
|           24 |     1549 | 2024-04-03 | Gods Reign               | L   | 0.984      | -            | -                | -                | -             |    -5.15 | korde, lakyo, meerkat, murakumo, W1nd              |
|           23 |     1834 | 2024-03-26 | Depresure                | W   | 0.930      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.23 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           22 |     2274 | 2024-03-14 | MIRAI Gaming             | L   | 0.851      | -            | -                | -                | -             |   -10.85 | korde, lakyo, meerkat, murakumo, W1nd              |
|           21 |     2279 | 2024-03-14 | MIRAI Gaming             | L   | 0.851      | -            | -                | -                | -             |   -11.68 | korde, lakyo, meerkat, murakumo, W1nd              |
|           20 |     2328 | 2024-03-13 | The MongolZ              | L   | 0.844      | -            | -                | -                | -             |    -0.11 | korde, lakyo, meerkat, murakumo, W1nd              |
|           19 |     2330 | 2024-03-13 | The MongolZ              | L   | 0.844      | -            | -                | -                | -             |    -0.11 | korde, lakyo, meerkat, murakumo, W1nd              |
|           18 |     2380 | 2024-03-12 | ROUX from hell           | L   | 0.837      | -            | -                | -                | -             |   -18.76 | kaito, lakyo, meerkat, murakumo, W1nd              |
|           17 |     2633 | 2024-03-06 | TYLOO                    | L   | 0.797      | -            | -                | -                | -             |    -2.56 | korde, lakyo, meerkat, murakumo, W1nd              |
|           16 |     2638 | 2024-03-06 | TYLOO                    | L   | 0.797      | -            | -                | -                | -             |    -2.63 | korde, lakyo, meerkat, murakumo, W1nd              |
|           15 |     2704 | 2024-03-05 | -72C                     | L   | 0.791      | -            | -                | -                | -             |    -8.50 | korde, lakyo, meerkat, murakumo, W1nd              |
|           14 |     2708 | 2024-03-05 | -72C                     | L   | 0.791      | -            | -                | -                | -             |    -9.06 | korde, lakyo, meerkat, murakumo, W1nd              |
|           13 |     3163 | 2024-02-24 | GR Gaming                | L   | 0.724      | -            | -                | -                | -             |    -7.23 | korde, lakyo, meerkat, murakumo, W1nd              |
|           12 |     3171 | 2024-02-24 | GR Gaming                | L   | 0.724      | -            | -                | -                | -             |    -7.64 | korde, lakyo, meerkat, murakumo, W1nd              |
|           11 |     3316 | 2024-02-21 | Lynn Vision Gaming       | L   | 0.704      | -            | -                | -                | -             |    -1.09 | korde, lakyo, meerkat, murakumo, W1nd              |
|           10 |     3320 | 2024-02-21 | Lynn Vision Gaming       | L   | 0.704      | -            | -                | -                | -             |    -1.11 | korde, lakyo, meerkat, murakumo, W1nd              |
|            9 |     3421 | 2024-02-19 | LYG Gaming               | L   | 0.690      | -            | -                | -                | -             |    -9.43 | korde, lakyo, meerkat, murakumo, W1nd              |
|            8 |     3424 | 2024-02-19 | LYG Gaming               | L   | 0.690      | -            | -                | -                | -             |   -10.02 | korde, lakyo, meerkat, murakumo, W1nd              |
|            7 |     3684 | 2024-02-13 | Clutch Gaming            | L   | 0.651      | -            | -                | -                | -             |   -10.38 | korde, lakyo, meerkat, murakumo, W1nd              |
|            6 |     3687 | 2024-02-13 | Clutch Gaming            | L   | 0.651      | -            | -                | -                | -             |   -10.99 | korde, lakyo, meerkat, murakumo, W1nd              |
|            5 |     5489 | 2023-12-16 | The QUBE Esports         | W   | 0.257      | 0.143        | 0.004 (0.000)    | 0.168 (0.006)    | false (0.000) |     4.61 | aNSeLMO, deadsh9t, Holy-_-Sanaa, hoolig4n, soloooS |
|            4 |     5590 | 2023-12-15 | Gods Reign               | W   | 0.250      | 0.143        | 0.174 (0.006)    | 0.479 (0.017)    | false (0.000) |     6.14 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN     |
|            3 |     6143 | 2023-12-02 | GR Gaming                | L   | 0.162      | -            | -                | -                | -             |    -2.04 | edGe, korde, lakyo, meerkat, W1nd                  |
|            2 |     6985 | 2023-11-13 | -72C                     | L   | 0.037      | -            | -                | -                | -             |    -0.50 | 1nhuman, borosto, forzetsky, m3wsu, shandarez      |
|            1 |     7210 | 2023-11-08 | Clutch Gaming            | L   | 0.004      | -            | -                | -                | -             |    -0.06 | clouden, flame, hasteka, IMAGINE, IZR              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($530.05)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-26 |      0.930 | $500.00        | $464.98         |
| 2023-12-10 |      0.217 | $300.00        | $65.07          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
