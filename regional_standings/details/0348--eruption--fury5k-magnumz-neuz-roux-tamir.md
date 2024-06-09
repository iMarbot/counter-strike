### Roster Details<br />
Team Name: Eruption<br />
Roster: fury5k, MagnumZ, NEUZ, ROUX, tamir<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [348](../standings_global.md)<br />
Regional Rank: [56]( ../standings_asia.md)<br />
Final Rank Value:  609.2<br />
<br />
Final Rank Value (609.2) = Starting Rank Value (595.7) + Head To Head Adjustments (13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.195[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.096<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 595.7
- 400 + ( ( 0.096 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 595.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     6956 | 2024-01-30 | Gods Reign         | W   | 0.401      | 0.143        | 0.004 (0.000)    | 0.105 (0.006)    | 0 (0.000) |     8.07 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           18 |     7327 | 2024-01-24 | The Huns Esports   | L   | 0.361      | -            | -                | -                | -         |    -1.82 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           17 |     7365 | 2024-01-24 | Rare Atom          | L   | 0.356      | -            | -                | -                | -         |    -3.89 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           16 |     7373 | 2024-01-24 | SR Nacague         | W   | 0.356      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     2.68 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           15 |     7429 | 2024-01-23 | Steel Helmet       | L   | 0.349      | -            | -                | -                | -         |    -4.20 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           14 |     7438 | 2024-01-22 | Myth Avenue Gaming | L   | 0.347      | -            | -                | -                | -         |    -4.30 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           13 |     7482 | 2024-01-22 | NewHappy           | W   | 0.343      | 0.143        | 0.003 (0.000)    | 0.066 (0.003)    | 0 (0.000) |     6.59 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           12 |     7492 | 2024-01-22 | LYG Gaming         | W   | 0.343      | 0.143        | 0.001 (0.000)    | 0.275 (0.013)    | 0 (0.000) |     7.24 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           11 |     7530 | 2024-01-21 | The Huns Esports   | L   | 0.335      | -            | -                | -                | -         |    -1.80 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           10 |     7606 | 2024-01-20 | MungYu Esports     | W   | 0.329      | 0.143        | 0.000 (0.000)    | 0.044 (0.002)    | 0 (0.000) |     4.20 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            9 |     7612 | 2024-01-20 | Fort Arena         | W   | 0.328      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     3.69 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            8 |     7671 | 2024-01-19 | GR Gaming          | L   | 0.322      | -            | -                | -                | -         |    -2.65 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            7 |     8744 | 2023-12-17 | The QUBE Esports   | L   | 0.102      | -            | -                | -                | -         |    -1.75 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            6 |     8891 | 2023-12-16 | ZEUSGG             | W   | 0.096      | 0.143        | 0.000 (0.000)    | 0.090 (0.001)    | 0 (0.000) |     1.38 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            5 |     9015 | 2023-12-15 | MIRAI Gaming       | L   | 0.089      | -            | -                | -                | -         |    -0.98 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            4 |     9112 | 2023-12-13 | DEWA United        | L   | 0.076      | -            | -                | -                | -         |    -1.15 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            3 |     9245 | 2023-12-10 | The QUBE Esports   | W   | 0.056      | 0.250        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.81 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            2 |     9303 | 2023-12-09 | DEWA United        | W   | 0.049      | 0.250        | 0.001 (0.000)    | 0.023 (0.000)    | 0 (0.000) |     0.81 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            1 |     9448 | 2023-12-07 | Hyper5             | W   | 0.036      | 0.250        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     0.60 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22.79)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
