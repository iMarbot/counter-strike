### Roster Details<br />
Team Name: Những Chàng Trai Đeo Kính<br />
Roster: Differ3nt, MrRaiJin, Pixie, Pr0digy, Tal3nt<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [186](../standings_global.md)<br />
Regional Rank: [29]( ../standings_asia.md)<br />
Final Rank Value:  738.4<br />
<br />
Final Rank Value (738.4) = Starting Rank Value (728.7) + Head To Head Adjustments (9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.175[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 728.7
- 400 + ( ( 0.166 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 728.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     4293 | 2024-01-26 | E9 esports                 | L   | 0.536      | -            | -                | -                | -         |    -8.17 | Differ3nt, MrRaiJin, Pixie, Pr0digy, Tal3nt |
|           10 |     4341 | 2024-01-26 | Lynn Vision Gaming         | L   | 0.529      | -            | -                | -                | -         |    -0.82 | Differ3nt, MrRaiJin, Pixie, Pr0digy, Tal3nt |
|            9 |     5279 | 2023-12-23 | Hyper5                     | W   | 0.303      | 0.143        | 0.002 (0.000)    | 0.065 (0.003)    | 1 (0.303) |     4.25 | Differ3nt, Foxy2k, Pr0digy, Ramel, Tal3nt   |
|            8 |     5747 | 2023-12-09 | Deadly Stare               | W   | 0.216      | 0.143        | 0.000 (0.000)    | 0.030 (0.001)    | 1 (0.216) |     2.54 | Asterex, Ex-President, Fuyu, Hozumi, Nico   |
|            7 |     5749 | 2023-12-09 | Run and Choke              | W   | 0.215      | 0.143        | 0.000 (0.000)    | 0.015 (0.000)    | 1 (0.215) |     2.25 | bi, dlr, dmh, nice, so                      |
|            6 |     5752 | 2023-12-09 | Serenity (Vietnamese team) | W   | 0.214      | 0.143        | 0.000 (0.000)    | 0.015 (0.000)    | 1 (0.214) |     2.18 | Al1an, Ariki, FeedKingz, IRO, Peo           |
|            5 |     5802 | 2023-12-08 | Let Shiro Cook             | W   | 0.209      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 1 (0.209) |     1.40 | HwAnG-, Levi, mintttt, Shiro, ThanhChoww    |
|            4 |     5813 | 2023-12-08 | Elite Crew                 | W   | 0.208      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.208) |     0.87 | Differ3nt, Foxy2k, Pr0digy, Ramel, Tal3nt   |
|            3 |     5817 | 2023-12-08 | Let Shiro Cook             | W   | 0.207      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 1 (0.207) |     1.40 | HwAnG-, Levi, mintttt, Shiro, ThanhChoww    |
|            2 |     6070 | 2023-12-02 | Hyper5                     | W   | 0.169      | 0.143        | 0.002 (0.000)    | 0.065 (0.002)    | 0 (0.000) |     2.41 | Differ3nt, Foxy2k, Pr0digy, Ramel, Tal3nt   |
|            1 |     6073 | 2023-12-02 | PowR                       | W   | 0.168      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.28 | Differ3nt, Foxy2k, Pr0digy, Ramel, Tal3nt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,061.67)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-28 |      0.543 | $1,250.00      | $679.11         |
| 2023-12-23 |      0.303 | $989.69        | $299.45         |
| 2023-12-09 |      0.216 | $288.90        | $62.26          |
| 2023-12-02 |      0.169 | $123.51        | $20.85          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
