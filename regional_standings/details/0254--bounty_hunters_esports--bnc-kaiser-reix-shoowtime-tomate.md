### Roster Details<br />
Team Name: Bounty Hunters Esports<br />
Roster: bnc, KAISER, Reix, SHOOWTiME, Tomate<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [254](../standings_global.md)<br />
Regional Rank: [49]( ../standings_americas.md)<br />
Final Rank Value:  660.6<br />
<br />
Final Rank Value (660.6) = Starting Rank Value (543.7) + Head To Head Adjustments (117.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 543.7
- 400 + ( ( 0.072 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 543.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      398 | 2024-04-26 | FURIA Esports Female     | W   | 1.000      | 0.143        | 0.048 (0.007)    | 0.205 (0.029)    | 0 (0.000) |    22.32 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|           13 |      500 | 2024-04-24 | Vikings KR               | L   | 1.000      | -            | -                | -                | -         |   -10.54 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|           12 |      504 | 2024-04-24 | Corinthians Esports      | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    16.13 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|           11 |      507 | 2024-04-24 | Hawks (Argentinian team) | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | 0 (0.000) |     6.73 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|           10 |      677 | 2024-04-20 | ODDIK                    | W   | 1.000      | 0.143        | 0.015 (0.002)    | 0.402 (0.057)    | 0 (0.000) |    25.27 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            9 |      679 | 2024-04-20 | Bombril 1001 Utilidades  | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.157 (0.022)    | 0 (0.000) |    22.15 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            8 |      994 | 2024-04-16 | MIBR                     | L   | 1.000      | -            | -                | -                | -         |    -0.13 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            7 |     1276 | 2024-04-09 | Vikings KR               | L   | 1.000      | -            | -                | -                | -         |   -10.06 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            6 |     1324 | 2024-04-08 | RED Canids               | L   | 1.000      | -            | -                | -                | -         |    -2.78 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            5 |     1384 | 2024-04-06 | MIBR                     | L   | 1.000      | -            | -                | -                | -         |    -0.16 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            4 |     1476 | 2024-04-04 | Sensei Team              | W   | 0.992      | 0.143        | 0.006 (0.001)    | 0.409 (0.058)    | 0 (0.000) |    21.18 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            3 |     1688 | 2024-03-28 | Dusty Roots              | W   | 0.945      | 0.143        | 0.005 (0.001)    | 0.352 (0.048)    | 0 (0.000) |    18.37 | bnc, KAISER, Reix, SHOOWTiME, Tomate |
|            2 |     1962 | 2024-03-21 | FURIA Academy            | L   | 0.899      | -            | -                | -                | -         |   -12.45 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |
|            1 |     1972 | 2024-03-21 | Intense Game             | W   | 0.899      | 0.143        | 0.008 (0.001)    | 0.372 (0.048)    | 0 (0.000) |    20.93 | MTGG, Reix, SHOOWTiME, Tomate, zmb   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
