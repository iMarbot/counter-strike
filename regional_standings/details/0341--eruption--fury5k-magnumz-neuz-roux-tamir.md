### Roster Details<br />
Team Name: Eruption<br />
Roster: fury5k, MagnumZ, NEUZ, ROUX, tamir<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [341](../standings_global.md)<br />
Regional Rank: [55]( ../standings_asia.md)<br />
Final Rank Value:  611.3<br />
<br />
Final Rank Value (611.3) = Starting Rank Value (596.7) + Head To Head Adjustments (14.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.195[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.097<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 596.7
- 400 + ( ( 0.097 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 596.7


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
|           19 |     6743 | 2024-01-30 | Gods Reign         | W   | 0.401      | 0.143        | 0.004 (0.000)    | 0.105 (0.006)    | 0 (0.000) |     8.04 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           18 |     7098 | 2024-01-24 | The Huns Esports   | L   | 0.361      | -            | -                | -                | -         |    -1.84 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           17 |     7130 | 2024-01-24 | Rare Atom          | L   | 0.356      | -            | -                | -                | -         |    -3.92 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           16 |     7138 | 2024-01-24 | SR Nacague         | W   | 0.356      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     2.65 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           15 |     7189 | 2024-01-23 | Steel Helmet       | L   | 0.349      | -            | -                | -                | -         |    -4.23 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           14 |     7197 | 2024-01-22 | Myth Avenue Gaming | L   | 0.347      | -            | -                | -                | -         |    -4.32 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           13 |     7239 | 2024-01-22 | NewHappy           | W   | 0.343      | 0.143        | 0.003 (0.000)    | 0.066 (0.003)    | 0 (0.000) |     6.56 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           12 |     7249 | 2024-01-22 | LYG Gaming         | W   | 0.343      | 0.143        | 0.001 (0.000)    | 0.275 (0.013)    | 0 (0.000) |     7.21 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           11 |     7287 | 2024-01-21 | The Huns Esports   | L   | 0.335      | -            | -                | -                | -         |    -1.83 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|           10 |     7362 | 2024-01-20 | MungYu Esports     | W   | 0.329      | 0.143        | 0.000 (0.000)    | 0.036 (0.002)    | 0 (0.000) |     4.13 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            9 |     7368 | 2024-01-20 | Fort Arena         | W   | 0.328      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     3.67 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            8 |     7424 | 2024-01-19 | GR Gaming          | L   | 0.322      | -            | -                | -                | -         |    -2.67 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            7 |     8484 | 2023-12-17 | The QUBE Esports   | L   | 0.102      | -            | -                | -                | -         |    -1.02 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            6 |     8630 | 2023-12-16 | ZEUSGG             | W   | 0.096      | 0.143        | 0.000 (0.000)    | 0.076 (0.001)    | 0 (0.000) |     1.12 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            5 |     8753 | 2023-12-15 | MIRAI Gaming       | L   | 0.089      | -            | -                | -                | -         |    -0.99 | fury5k, MagnumZ, NEUZ, ROUX, tamir   |
|            4 |     8848 | 2023-12-13 | DEWA United        | L   | 0.076      | -            | -                | -                | -         |    -0.82 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            3 |     8979 | 2023-12-10 | The QUBE Esports   | W   | 0.056      | 0.250        | 0.001 (0.000)    | 0.120 (0.002)    | 0 (0.000) |     1.21 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            2 |     9037 | 2023-12-09 | DEWA United        | W   | 0.049      | 0.250        | 0.002 (0.000)    | 0.185 (0.002)    | 0 (0.000) |     1.02 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |
|            1 |     9175 | 2023-12-07 | Hyper5             | W   | 0.036      | 0.250        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     0.59 | ariucle, fury5k, MagnumZ, NEUZ, ROUX |

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
