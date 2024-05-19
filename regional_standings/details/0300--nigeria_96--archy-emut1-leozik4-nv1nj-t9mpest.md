### Roster Details<br />
Team Name: NIGERIA 96<br />
Roster: archy, emut1, leozik4, nv1nJ, t9mpest<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [300](../standings_global.md)<br />
Regional Rank: [68]( ../standings_americas.md)<br />
Final Rank Value:  612.2<br />
<br />
Final Rank Value (612.2) = Starting Rank Value (631.3) + Head To Head Adjustments (-19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.269[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 631.3
- 400 + ( ( 0.117 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 631.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      337 | 2024-04-27 | Sharks Youngsters           | L   | 1.000      | -            | -                | -                | -         |   -16.43 | archy, emut1, leozik4, nv1nJ, t9mpest   |
|           11 |      354 | 2024-04-27 | Floripa Stars               | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.181 (0.026)    | 0 (0.000) |    17.99 | archy, emut1, leozik4, nv1nJ, t9mpest   |
|           10 |     1851 | 2024-03-24 | Yawara E-Sports             | L   | 0.919      | -            | -                | -                | -         |   -10.43 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            9 |     2006 | 2024-03-20 | Romanticos                  | L   | 0.894      | -            | -                | -                | -         |   -12.72 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            8 |     2045 | 2024-03-19 | 9z Academy                  | L   | 0.886      | -            | -                | -                | -         |   -14.12 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            7 |     3011 | 2024-02-27 | Hawks (Argentinian team)    | L   | 0.746      | -            | -                | -                | -         |   -10.57 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            6 |     3132 | 2024-02-24 | Hawks (Argentinian team)    | W   | 0.726      | 0.143        | 0.003 (0.000)    | 0.134 (0.014)    | 0 (0.000) |    12.50 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            5 |     3135 | 2024-02-24 | Floripa Stars               | W   | 0.726      | 0.143        | 0.001 (0.000)    | 0.181 (0.019)    | 0 (0.000) |    12.67 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            4 |     3392 | 2024-02-19 | Fluxo                       | L   | 0.694      | -            | -                | -                | -         |    -2.34 | leozik4, nv1nJ, predict, rN, t9mpest    |
|            3 |     4209 | 2024-01-28 | New Legacy (Brazilian team) | W   | 0.546      | 0.143        | 0.000 (0.000)    | 0.038 (0.003)    | 0 (0.000) |     7.66 | archy, deemO, dudinho, leozik4, t9mpest |
|            2 |     4993 | 2024-01-11 | TIMACETA                    | L   | 0.432      | -            | -                | -                | -         |    -6.20 | archy, dudinho, nv1nJ, sigma, t9mpest   |
|            1 |     5031 | 2024-01-10 | EMC2 ESPORTS                | W   | 0.426      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.84 | archy, dudinho, nv1nJ, sigma, t9mpest   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($306.37)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-27 |      0.746 | $321.25        | $239.76         |
| 2024-01-28 |      0.546 | $122.07        | $66.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
