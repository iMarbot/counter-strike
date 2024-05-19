### Roster Details<br />
Team Name: MIBR<br />
Roster: brnz4n, drop, exit, insani, saffee<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [11](../standings_global.md)<br />
Regional Rank: [1]( ../standings_americas.md)<br />
Final Rank Value:  1592.3<br />
<br />
Final Rank Value (1592.3) = Starting Rank Value (1658.1) + Head To Head Adjustments (-65.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.844[<sup>1</sup>](#table2)
- Bounty Collected: 0.601[<sup>2</sup>](#table1)
- Opponent Network: 0.256[<sup>2</sup>](#table1)
- LAN Wins: 0.835[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1658.1
- 400 + ( ( 0.634 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1658.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           58 |      326 | 2024-04-28 | Aurora Gaming          | W   | 1.000      | 0.500        | 1.000 (0.500)    | 0.799 (0.399)    | true (1.000) |    10.85 | brnz4n, drop, exit, insani, saffee |
|           57 |      330 | 2024-04-27 | Apeks                  | W   | 1.000      | 0.500        | 0.253 (0.126)    | 0.459 (0.230)    | true (1.000) |     6.01 | brnz4n, drop, exit, insani, saffee |
|           56 |      394 | 2024-04-26 | Rooster                | W   | 1.000      | -            | -                | -                | true (1.000) |     0.58 | brnz4n, drop, exit, insani, saffee |
|           55 |      451 | 2024-04-26 | Rebels Gaming          | L   | 1.000      | -            | -                | -                | -            |   -28.99 | brnz4n, drop, exit, insani, saffee |
|           54 |      454 | 2024-04-25 | KZG                    | W   | 1.000      | -            | -                | -                | true (1.000) |     0.19 | brnz4n, drop, exit, insani, saffee |
|           53 |      738 | 2024-04-20 | OG                     | W   | 1.000      | 0.589        | 0.594 (0.349)    | 0.390 (0.230)    | true (1.000) |     7.17 | brnz4n, drop, exit, insani, saffee |
|           52 |      793 | 2024-04-19 | FURIA Esports          | W   | 1.000      | 0.589        | 0.384 (0.226)    | -                | true (1.000) |    12.03 | brnz4n, drop, exit, insani, saffee |
|           51 |      857 | 2024-04-18 | Imperial Esports       | W   | 1.000      | 0.143        | 0.674 (0.096)    | -                | -            |    11.09 | brnz4n, drop, exit, insani, saffee |
|           50 |      865 | 2024-04-18 | OG                     | W   | 1.000      | 0.589        | 0.594 (0.349)    | 0.390 (0.230)    | true (1.000) |     7.84 | brnz4n, drop, exit, insani, saffee |
|           49 |      914 | 2024-04-17 | RED Canids             | W   | 1.000      | -            | -                | -                | -            |     1.39 | brnz4n, drop, exit, insani, saffee |
|           48 |      920 | 2024-04-17 | Case Esports           | W   | 1.000      | -            | -                | -                | -            |     0.48 | brnz4n, drop, exit, insani, saffee |
|           47 |      994 | 2024-04-16 | Bounty Hunters Esports | W   | 1.000      | -            | -                | -                | -            |     0.13 | brnz4n, drop, exit, insani, saffee |
|           46 |     1031 | 2024-04-15 | Imperial Esports       | W   | 1.000      | 0.435        | 0.674 (0.293)    | 0.549 (0.238)    | -            |    12.07 | brnz4n, drop, exit, insani, saffee |
|           45 |     1062 | 2024-04-14 | Galorys                | W   | 1.000      | 0.435        | -                | 0.598 (0.260)    | -            |     0.80 | brnz4n, drop, exit, insani, saffee |
|           44 |     1099 | 2024-04-13 | Case Esports           | W   | 1.000      | -            | -                | -                | -            |     0.47 | brnz4n, drop, exit, insani, saffee |
|           43 |     1202 | 2024-04-10 | Galorys                | W   | 1.000      | 0.450        | -                | 0.598 (0.269)    | -            |     0.67 | brnz4n, drop, exit, insani, saffee |
|           42 |     1206 | 2024-04-10 | Galorys                | W   | 1.000      | 0.450        | -                | 0.598 (0.269)    | -            |     0.67 | brnz4n, drop, exit, insani, saffee |
|           41 |     1228 | 2024-04-10 | Imperial Esports       | W   | 1.000      | 0.143        | 0.674 (0.096)    | -                | -            |    14.36 | brnz4n, drop, exit, insani, saffee |
|           40 |     1270 | 2024-04-09 | AdalYamigos            | W   | 1.000      | -            | -                | -                | -            |     0.55 | brnz4n, drop, exit, insani, saffee |
|           39 |     1275 | 2024-04-09 | AdalYamigos            | W   | 1.000      | -            | -                | -                | -            |     0.55 | brnz4n, drop, exit, insani, saffee |
|           38 |     1278 | 2024-04-09 | RED Canids             | W   | 1.000      | -            | -                | -                | -            |     1.66 | brnz4n, drop, exit, insani, saffee |
|           37 |     1384 | 2024-04-06 | Bounty Hunters Esports | W   | 1.000      | -            | -                | -                | -            |     0.16 | brnz4n, drop, exit, insani, saffee |
|           36 |     1433 | 2024-04-05 | Fluxo                  | W   | 1.000      | 0.450        | 0.153 (0.069)    | 0.484 (0.218)    | -            |     1.89 | brnz4n, drop, exit, insani, saffee |
|           35 |     1434 | 2024-04-05 | Fluxo                  | L   | 1.000      | -            | -                | -                | -            |   -29.88 | brnz4n, drop, exit, insani, saffee |
|           34 |     1438 | 2024-04-05 | ODDIK                  | W   | 0.999      | -            | -                | -                | -            |     0.77 | brnz4n, drop, exit, insani, saffee |
|           33 |     1514 | 2024-04-03 | Fluxo                  | W   | 0.987      | -            | -                | -                | -            |     1.45 | brnz4n, drop, exit, insani, saffee |
|           32 |     1566 | 2024-04-02 | Fluxo                  | W   | 0.980      | -            | -                | -                | -            |     1.40 | brnz4n, drop, exit, insani, saffee |
|           31 |     1569 | 2024-04-02 | Sharks Esports         | W   | 0.979      | -            | -                | -                | -            |     0.94 | brnz4n, drop, exit, insani, saffee |
|           30 |     1788 | 2024-03-26 | ODDIK                  | W   | 0.934      | -            | -                | -                | -            |     0.75 | brnz4n, drop, exit, insani, saffee |
|           29 |     1789 | 2024-03-26 | ODDIK                  | W   | 0.933      | -            | -                | -                | -            |     0.76 | brnz4n, drop, exit, insani, saffee |
|           28 |     2243 | 2024-03-14 | Sharks Esports         | W   | 0.854      | -            | -                | -                | -            |     0.84 | brnz4n, drop, exit, insani, saffee |
|           27 |     2245 | 2024-03-14 | Sharks Esports         | W   | 0.853      | -            | -                | -                | -            |     0.84 | brnz4n, drop, exit, insani, saffee |
|           26 |     2362 | 2024-03-12 | Fluxo                  | L   | 0.839      | -            | -                | -                | -            |   -25.25 | brnz4n, drop, exit, insani, saffee |
|           25 |     2444 | 2024-03-10 | Galorys                | W   | 0.826      | 0.435        | -                | 0.598 (0.215)    | -            |     0.35 | brnz4n, drop, exit, insani, saffee |
|           24 |     2524 | 2024-03-08 | LA RUGONETA            | W   | 0.812      | -            | -                | -                | -            |     0.10 | brnz4n, drop, exit, insani, saffee |
|           23 |     2778 | 2024-03-03 | Legacy                 | L   | 0.779      | -            | -                | -                | -            |   -23.01 | brnz4n, drop, exit, insani, saffee |
|           22 |     2906 | 2024-03-01 | BOSS                   | L   | 0.766      | -            | -                | -                | -            |   -23.71 | brnz4n, drop, exit, insani, saffee |
|           21 |     3942 | 2024-02-03 | Imperial Esports       | L   | 0.586      | -            | -                | -                | -            |   -11.58 | brnz4n, drop, exit, insani, saffee |
|           20 |     4533 | 2024-01-20 | BESTIA                 | W   | 0.492      | -            | -                | -                | -            |     0.16 | brnz4n, drop, exit, insani, saffee |
|           19 |     4586 | 2024-01-19 | TIMACETA               | W   | 0.487      | -            | -                | -                | -            |     0.08 | brnz4n, drop, exit, insani, saffee |
|           18 |     4594 | 2024-01-19 | ODDIK                  | W   | 0.486      | -            | -                | -                | -            |     0.25 | brnz4n, drop, exit, insani, saffee |
|           17 |     4636 | 2024-01-18 | 9z Team                | L   | 0.480      | -            | -                | -                | -            |   -14.81 | brnz4n, drop, exit, insani, saffee |
|           16 |     4642 | 2024-01-18 | Sharks Esports         | W   | 0.479      | -            | -                | -                | -            |     0.23 | brnz4n, drop, exit, insani, saffee |
|           15 |     4689 | 2024-01-17 | 9z Team                | L   | 0.473      | -            | -                | -                | -            |   -14.65 | brnz4n, drop, exit, insani, saffee |
|           14 |     4718 | 2024-01-17 | Sharks Esports         | W   | 0.472      | -            | -                | -                | -            |     0.20 | brnz4n, drop, exit, insani, saffee |
|           13 |     5774 | 2023-12-09 | Team Spirit            | L   | 0.210      | -            | -                | -                | -            |    -1.83 | brnz4n, drop, exit, insani, saffee |
|           12 |     5893 | 2023-12-07 | Cloud9                 | W   | 0.197      | -            | -                | -                | true (0.197) |     4.22 | brnz4n, drop, exit, insani, saffee |
|           11 |     5995 | 2023-12-05 | BetBoom Team           | W   | 0.184      | 0.657        | 0.571 (0.069)    | -                | true (0.184) |     1.54 | brnz4n, drop, exit, insani, saffee |
|           10 |     6403 | 2023-11-26 | Eternal Fire           | L   | 0.123      | -            | -                | -                | -            |    -1.26 | brnz4n, drop, exit, insani, saffee |
|            9 |     6474 | 2023-11-24 | Virtus.pro             | W   | 0.112      | -            | -                | -                | true (0.112) |     1.97 | brnz4n, drop, exit, insani, saffee |
|            8 |     6488 | 2023-11-24 | GamerLegion            | W   | 0.111      | -            | -                | -                | -            |     1.44 | brnz4n, drop, exit, insani, saffee |
|            7 |     6632 | 2023-11-20 | Aurora Gaming          | W   | 0.085      | -            | -                | -                | -            |     1.22 | brnz4n, drop, exit, insani, saffee |
|            6 |     6651 | 2023-11-20 | BIG                    | W   | 0.084      | -            | -                | -                | -            |     0.58 | brnz4n, drop, exit, insani, saffee |
|            5 |     6664 | 2023-11-19 | Eternal Fire           | L   | 0.078      | -            | -                | -                | -            |    -0.77 | brnz4n, drop, exit, insani, saffee |
|            4 |     6712 | 2023-11-18 | BetBoom Team           | W   | 0.072      | -            | -                | -                | -            |     0.62 | brnz4n, drop, exit, insani, saffee |
|            3 |     6780 | 2023-11-17 | Team Spirit            | L   | 0.064      | -            | -                | -                | -            |    -0.54 | brnz4n, drop, exit, insani, saffee |
|            2 |     6790 | 2023-11-17 | 9Pandas                | L   | 0.063      | -            | -                | -                | -            |    -1.89 | brnz4n, drop, exit, insani, saffee |
|            1 |     6844 | 2023-11-16 | KOI                    | W   | 0.056      | -            | -                | -                | -            |     0.06 | brnz4n, drop, exit, insani, saffee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($103,594.91)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.65) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-28 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-04-20 |      1.000 | $20,000.00     | $20,000.00      |
| 2024-04-15 |      1.000 | $25,000.00     | $25,000.00      |
| 2023-12-10 |      0.217 | $30,000.00     | $6,497.92       |
| 2023-11-26 |      0.125 | $10,000.00     | $1,250.23       |
| 2023-11-20 |      0.085 | $10,000.00     | $846.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
