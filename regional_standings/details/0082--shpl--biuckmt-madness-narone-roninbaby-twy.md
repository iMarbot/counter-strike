### Roster Details<br />
Team Name: SHPL<br />
Roster: Biuckmt, madness, NARONE, Roninbaby, twy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [82](../standings_global.md)<br />
Regional Rank: [9]( ../standings_asia.md)<br />
Final Rank Value:  888.8<br />
<br />
Final Rank Value (888.8) = Starting Rank Value (898.8) + Head To Head Adjustments (-10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.424[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.334[<sup>2</sup>](#table1)

The average of these factors is 0.251<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 898.8
- 400 + ( ( 0.251 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 898.8


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
|           10 |      660 | 2024-04-21 | Nalakuvara        | W   | 1.000      | 0.143        | 0.027 (0.004)    | 0.070 (0.010)    | 1 (1.000) |    13.44 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            9 |      674 | 2024-04-20 | Pressure Monsters | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.035 (0.005)    | 1 (1.000) |    10.24 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            8 |      726 | 2024-04-20 | Team Remember     | W   | 1.000      | 0.143        | 0.022 (0.003)    | 0.067 (0.010)    | 1 (1.000) |     8.59 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            7 |      784 | 2024-04-19 | Pressure Monsters | L   | 1.000      | -            | -                | -                | -         |   -20.88 | Biuckmt, madness, NARONE, Roninbaby, twy |
|            6 |     4581 | 2024-01-19 | Rare Atom         | L   | 0.488      | -            | -                | -                | -         |   -10.47 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            5 |     4633 | 2024-01-18 | TYLOO             | L   | 0.482      | -            | -                | -                | -         |    -4.34 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            4 |     4946 | 2024-01-12 | Nirvana Esports   | W   | 0.437      | 0.143        | 0.000 (0.000)    | 0.031 (0.002)    | 0 (0.000) |     0.88 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            3 |     4951 | 2024-01-12 | Rare Atom         | L   | 0.437      | -            | -                | -                | -         |    -9.51 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            2 |     4958 | 2024-01-11 | 小冰龙XBL            | W   | 0.436      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | 0 (0.000) |     1.30 | Biuckmt, madness, NARONE, S1kura, Xan    |
|            1 |     4973 | 2024-01-11 | EzBoomFish        | W   | 0.435      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.79 | Biuckmt, madness, NARONE, S1kura, Xan    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,906.26)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
