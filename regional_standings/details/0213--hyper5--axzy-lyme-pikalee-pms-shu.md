### Roster Details<br />
Team Name: Hyper5<br />
Roster: axZy, Lyme, Pikalee, pms, Shu<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [213](../standings_global.md)<br />
Regional Rank: [35]( ../standings_asia.md)<br />
Final Rank Value:  701.1<br />
<br />
Final Rank Value (701.1) = Starting Rank Value (695.6) + Head To Head Adjustments (5.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.153[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.173[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 695.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 695.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     5279 | 2023-12-23 | Những Chàng Trai Đeo Kính | L   | 0.303      | -            | -                | -                | -         |    -4.25 | axZy, Lyme, Pikalee, pms, Shu        |
|           13 |     5404 | 2023-12-16 | EZ Esport                 | W   | 0.262      | 0.143        | 0.000 (0.000)    | 0.045 (0.002)    | 1 (0.262) |     3.74 | Lyme, Pikalee, pms, Richard, Shu     |
|           12 |     5413 | 2023-12-16 | Cao Huyết Áp              | W   | 0.262      | 0.143        | 0.000 (0.000)    | 0.027 (0.001)    | 1 (0.262) |     3.42 | Lyme, Pikalee, pms, Richard, Shu     |
|           11 |     5419 | 2023-12-16 | BiuTiPhuCanTri            | W   | 0.261      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 1 (0.261) |     3.08 | Lyme, Pikalee, pms, Richard, Shu     |
|           10 |     5513 | 2023-12-16 | TUCNA                     | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 1 (0.256) |     2.23 | Lyme, Pikalee, pms, Richard, Shu     |
|            9 |     5531 | 2023-12-15 | TUCNA                     | W   | 0.255      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 1 (0.255) |     2.24 | Lyme, Pikalee, pms, Richard, Shu     |
|            8 |     5551 | 2023-12-15 | 1PinG                     | W   | 0.254      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 1 (0.254) |     1.41 | Lyme, Pikalee, pms, Richard, Shu     |
|            7 |     5591 | 2023-12-15 | The QUBE Esports          | L   | 0.250      | -            | -                | -                | -         |    -2.84 | Guckj, Lyme, Pikalee, pms, Shu       |
|            6 |     5777 | 2023-12-09 | RAVENS (Japanese team)    | W   | 0.210      | 0.250        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.10 | Guckj, Lyme, Pikalee, pms, Shu       |
|            5 |     5894 | 2023-12-07 | Aravt                     | L   | 0.197      | -            | -                | -                | -         |    -4.29 | Guckj, Lyme, Pikalee, pms, Shu       |
|            4 |     5997 | 2023-12-05 | Guardian 5                | W   | 0.184      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.93 | Guckj, Lyme, Pikalee, pms, Shu       |
|            3 |     6070 | 2023-12-02 | Những Chàng Trai Đeo Kính | L   | 0.169      | -            | -                | -                | -         |    -2.41 | Lyme, Pikalee, pms, Shu, Soncam-1603 |
|            2 |     6072 | 2023-12-02 | ONS                       | W   | 0.168      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.28 | Lyme, Pikalee, pms, Shu, Soncam-1603 |
|            1 |     6848 | 2023-11-16 | ATOX Esports              | L   | 0.056      | -            | -                | -                | -         |    -0.17 | Lyme, Pikalee, Pms, Shu, Soncam-1603 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($310.90)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.303 | $659.79        | $199.63         |
| 2023-12-16 |      0.262 | $288.36        | $75.66          |
| 2023-12-10 |      0.217 | $100.00        | $21.70          |
| 2023-12-02 |      0.169 | $82.34         | $13.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
