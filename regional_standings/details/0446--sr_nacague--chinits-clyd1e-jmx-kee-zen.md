### Roster Details<br />
Team Name: SR Nacague<br />
Roster: Chinits, clyd1e, JMX, Kee, Zen<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [446](../standings_global.md)<br />
Regional Rank: [67]( ../standings_asia.md)<br />
Final Rank Value:  487.1<br />
<br />
Final Rank Value (487.1) = Starting Rank Value (485.0) + Head To Head Adjustments (2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.166[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.042<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 485.0
- 400 + ( ( 0.042 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 485.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     4750 | 2024-03-11 | TyPuCTbl           | L   | 0.669      | -            | -                | -                | -         |    -7.28 | Chinits, clyd1e, JMX, Kee, Zen |
|            9 |     4888 | 2024-03-08 | Moon Esports       | W   | 0.649      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.29 | Chinits, clyd1e, JMX, Kee, Zen |
|            8 |     5035 | 2024-03-06 | Myth Avenue Gaming | L   | 0.636      | -            | -                | -                | -         |    -3.96 | Chinits, clyd1e, JMX, Kee, Zen |
|            7 |     6308 | 2024-02-14 | ZEUSGG             | L   | 0.496      | -            | -                | -                | -         |    -6.31 | clyd1e, Kee, LU, xanzu, Zen    |
|            6 |     7667 | 2024-01-19 | Gods Reign         | L   | 0.322      | -            | -                | -                | -         |    -2.38 | clyd1e, Duane, Kee, Zen, Zumss |
|            5 |     7669 | 2024-01-19 | 2ez Gaming         | W   | 0.322      | 0.143        | 0.001 (0.000)    | 0.095 (0.004)    | 0 (0.000) |     6.85 | clyd1e, Duane, Kee, Zen, Zumss |
|            4 |     7823 | 2024-01-17 | DEWA United        | L   | 0.310      | -            | -                | -                | -         |    -2.24 | bryle, clyd1e, Kee, Zen, Zumss |
|            3 |     7827 | 2024-01-17 | Gods Reign         | L   | 0.310      | -            | -                | -                | -         |    -2.35 | bryle, clyd1e, Kee, Zen, Zumss |
|            2 |     7833 | 2024-01-17 | Troublemakers      | W   | 0.309      | 0.143        | 0.000 (0.000)    | 0.087 (0.004)    | 0 (0.000) |     7.12 | bryle, clyd1e, Kee, Zen, Zumss |
|            1 |     7936 | 2024-01-16 | LM68               | W   | 0.302      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.34 | bryle, clyd1e, Kee, Zen, Zumss |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
