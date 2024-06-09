### Roster Details<br />
Team Name: SHPL<br />
Roster: Biuckmt, madness, NARONE, Roninbaby, twy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [112](../standings_global.md)<br />
Regional Rank: [10]( ../standings_asia.md)<br />
Final Rank Value:  853.4<br />
<br />
Final Rank Value (853.4) = Starting Rank Value (857.8) + Head To Head Adjustments (-4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.298[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 857.8
- 400 + ( ( 0.225 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 857.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2571 | 2024-04-21 | Nalakuvara        | W   | 0.942      | 0.143        | 0.013 (0.002)    | 0.051 (0.007)    | 1 (0.942) |    12.88 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            9 |     2586 | 2024-04-20 | Pressure Monsters | W   | 0.941      | 0.143        | 0.004 (0.001)    | 0.026 (0.003)    | 1 (0.941) |    10.06 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            8 |     2647 | 2024-04-20 | Team Remember     | W   | 0.936      | 0.143        | 0.010 (0.001)    | 0.044 (0.006)    | 1 (0.936) |     8.41 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            7 |     2710 | 2024-04-19 | Pressure Monsters | L   | 0.934      | -            | -                | -                | -         |   -19.09 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            6 |     7620 | 2024-01-19 | Rare Atom         | L   | 0.327      | -            | -                | -                | -         |    -7.12 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            5 |     7688 | 2024-01-18 | TYLOO             | L   | 0.321      | -            | -                | -                | -         |    -5.70 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            4 |     8124 | 2024-01-12 | Nirvana Esports   | W   | 0.276      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     0.66 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            3 |     8128 | 2024-01-12 | Rare Atom         | L   | 0.276      | -            | -                | -                | -         |    -6.07 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            2 |     8135 | 2024-01-11 | 小冰龙XBL            | W   | 0.274      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     0.95 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            1 |     8151 | 2024-01-11 | EzBoomFish        | W   | 0.274      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.62 | Biuckmt, madness, NARONE, S1kura, Xan    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,505.96)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
