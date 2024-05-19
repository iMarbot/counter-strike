### Roster Details<br />
Team Name: E9 esports<br />
Roster: Balzo, neverland, salmon, skrrrr, T3rrymeister<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [141](../standings_global.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
Final Rank Value:  785.2<br />
<br />
Final Rank Value (785.2) = Starting Rank Value (757.7) + Head To Head Adjustments (27.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.373[<sup>1</sup>](#table2)
- Bounty Collected: 0.280[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.060[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 757.7
- 400 + ( ( 0.180 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 757.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     2441 | 2024-03-11 | High Five (Chinese team)  | L   | 0.829      | -            | -                | -                | -         |   -10.65 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           13 |     2475 | 2024-03-10 | ATOX Esports              | L   | 0.822      | -            | -                | -                | -         |    -4.28 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           12 |     2521 | 2024-03-09 | High Five (Chinese team)  | W   | 0.816      | 0.143        | 0.045 (0.005)    | 0.282 (0.033)    | 0 (0.000) |    15.05 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           11 |     2522 | 2024-03-08 | AP Gaming                 | W   | 0.815      | 0.143        | 0.082 (0.010)    | 0.152 (0.018)    | 0 (0.000) |    17.17 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|           10 |     2547 | 2024-03-08 | ATOX Esports              | L   | 0.809      | -            | -                | -                | -         |    -3.83 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|            9 |     2589 | 2024-03-07 | AP Gaming                 | W   | 0.803      | 0.143        | 0.082 (0.009)    | 0.152 (0.017)    | 0 (0.000) |    17.68 | Balzo, neverland, salmon, skrrrr, T3rrymeister |
|            8 |     4290 | 2024-01-27 | Team NKT                  | L   | 0.536      | -            | -                | -                | -         |    -7.57 | N1nE, neverland, salmon, T3rrymeister, Tikkkk  |
|            7 |     4293 | 2024-01-26 | Những Chàng Trai Đeo Kính | W   | 0.536      | 0.435        | 0.007 (0.002)    | 0.054 (0.013)    | 1 (0.536) |     8.17 | N1nE, neverland, salmon, T3rrymeister, Tikkkk  |
|            6 |     4338 | 2024-01-26 | Team NKT                  | L   | 0.530      | -            | -                | -                | -         |    -7.62 | N1nE, neverland, salmon, T3rrymeister, Tikkkk  |
|            5 |     4896 | 2024-01-13 | Change The Game           | L   | 0.443      | -            | -                | -                | -         |    -9.13 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            4 |     4903 | 2024-01-13 | TigerMan Esports          | W   | 0.442      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.80 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            3 |     5153 | 2024-01-08 | PA Esports                | W   | 0.410      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.61 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            2 |     5480 | 2023-12-16 | 川渝一棵松                     | W   | 0.258      | 0.143        | 0.001 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     2.45 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |
|            1 |     5494 | 2023-12-16 | Nalakuvara                | W   | 0.257      | 0.143        | 0.027 (0.001)    | 0.070 (0.003)    | 0 (0.000) |     4.71 | kylin, N1nE, salmon, T3rrymeister, Tikkkk      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,300.77)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-11 |      0.830 | $2,783.23      | $2,309.95       |
| 2024-01-28 |      0.543 | $1,250.00      | $679.11         |
| 2024-01-13 |      0.443 | $703.18        | $311.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
