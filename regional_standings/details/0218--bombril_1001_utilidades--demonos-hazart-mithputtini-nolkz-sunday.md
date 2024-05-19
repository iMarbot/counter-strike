### Roster Details<br />
Team Name: Bombril 1001 Utilidades<br />
Roster: Demonos, hazart, MITHPUTTINI, nolkz, suNday<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [218](../standings_global.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
Final Rank Value:  697.2<br />
<br />
Final Rank Value (697.2) = Starting Rank Value (683.0) + Head To Head Adjustments (14.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.0
- 400 + ( ( 0.143 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 683.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      227 | 2024-04-30 | Looking4Org (Brazilian team) | L   | 1.000      | -            | -                | -                | -         |   -18.38 | Demonos, hazart, MITHPUTTINI, nolkz, suNday |
|            9 |      229 | 2024-04-30 | Yawara E-Sports              | L   | 1.000      | -            | -                | -                | -         |   -16.47 | Demonos, hazart, MITHPUTTINI, nolkz, suNday |
|            8 |      679 | 2024-04-20 | Bounty Hunters Esports       | L   | 1.000      | -            | -                | -                | -         |   -22.15 | hazart, MITHPUTTINI, nolkz, spinnie, suNday |
|            7 |     1612 | 2024-03-31 | MIBR Academy                 | W   | 0.967      | 0.143        | 0.011 (0.002)    | 0.455 (0.063)    | 0 (0.000) |    14.32 | hazart, MITHPUTTINI, nolkz, spinnie, Tomate |
|            6 |     1684 | 2024-03-28 | Yawara E-Sports              | W   | 0.946      | 0.143        | 0.005 (0.001)    | 0.361 (0.049)    | 0 (0.000) |    15.33 | hazart, MITHPUTTINI, nolkz, spinnie, Tomate |
|            5 |     1929 | 2024-03-22 | Hawks (Argentinian team)     | W   | 0.906      | 0.143        | 0.003 (0.000)    | 0.134 (0.017)    | 0 (0.000) |    13.20 | hazart, MITHPUTTINI, nolkz, spinnie, Tomate |
|            4 |     2013 | 2024-03-20 | MIBR Academy                 | W   | 0.893      | 0.143        | 0.011 (0.001)    | 0.455 (0.058)    | 0 (0.000) |    15.36 | hazart, MITHPUTTINI, nolkz, spinnie, Tomate |
|            3 |     2051 | 2024-03-19 | Sharks Youngsters            | W   | 0.886      | 0.143        | 0.004 (0.000)    | 0.211 (0.027)    | 0 (0.000) |    12.85 | hazart, MITHPUTTINI, nolkz, spinnie, Tomate |
|            2 |     2752 | 2024-03-04 | Yawara E-Sports              | L   | 0.786      | -            | -                | -                | -         |   -11.76 | hazart, Ltz, MITHPUTTINI, nolkz, spinnie    |
|            1 |     2865 | 2024-03-02 | Romanticos                   | W   | 0.772      | 0.143        | 0.003 (0.000)    | 0.185 (0.020)    | 0 (0.000) |    11.91 | hazart, Ltz, MITHPUTTINI, nolkz, spinnie    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,074.34)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.967 | $1,002.96      | $969.62         |
| 2024-03-06 |      0.799 | $131.09        | $104.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
