### Roster Details<br />
Team Name: AL-QATRAO<br />
Roster: drext, hdstr, Icarus, nesto, shr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [193](../standings_global.md)<br />
Regional Rank: [128]( ../standings_europe.md)<br />
Final Rank Value:  734.7<br />
<br />
Final Rank Value (734.7) = Starting Rank Value (687.2) + Head To Head Adjustments (47.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.273[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 687.2
- 400 + ( ( 0.145 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 687.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       51 | 2024-05-04 | GTZ.ESPORTS                      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.095 (0.014)    | false (0.000) |     4.10 | drext, hdstr, Icarus, nesto, shr       |
|           16 |       84 | 2024-05-04 | SAW Youngsters                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.27 | drext, hdstr, Icarus, nesto, shr       |
|           15 |      106 | 2024-05-03 | NeverPlay (Portuguese team)      | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     4.36 | drext, hdstr, Icarus, nesto, shr       |
|           14 |      712 | 2024-04-20 | Strike Force                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |     4.78 | drext, hdstr, Icarus, nesto, shr       |
|           13 |      719 | 2024-04-20 | ABT Esports                      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.137 (0.020)    | false (0.000) |     7.26 | drext, hdstr, Icarus, nesto, shr       |
|           12 |      731 | 2024-04-20 | Lx Soldiers                      | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     4.58 | drext, hdstr, Icarus, nesto, shr       |
|           11 |     2877 | 2024-03-02 | Rhyno Esports                    | L   | 0.771      | -            | -                | -                | -             |    -6.52 | drext, hdstr, Icarus, nesto, shr       |
|           10 |     3247 | 2024-02-22 | OVERFRAG                         | W   | 0.712      | 0.143        | 0.004 (0.000)    | 0.050 (0.005)    | false (0.000) |     6.56 | drext, hdstr, Icarus, nesto, shr       |
|            9 |     3344 | 2024-02-20 | The Agency Clan                  | W   | 0.699      | 0.143        | 0.000 (0.000)    | 0.038 (0.004)    | false (0.000) |     5.51 | drext, hdstr, Icarus, nesto, shr       |
|            8 |     3346 | 2024-02-20 | GTZ.ESPORTS                      | W   | 0.698      | 0.143        | 0.000 (0.000)    | 0.095 (0.009)    | false (0.000) |     3.31 | drext, hdstr, Icarus, nesto, shr       |
|            7 |     3488 | 2024-02-17 | Enigma Esports (Portuguese team) | W   | 0.679      | 0.143        | -                | 0.050 (0.005)    | false (0.000) |     3.44 | drext, frozzen, hdstr, shr, snowiee    |
|            6 |     4069 | 2024-02-01 | SAW                              | L   | 0.572      | -            | -                | -                | -             |    -0.24 | drext, frozzen, hdstr, nesto, shr      |
|            5 |     4073 | 2024-02-01 | EsmagaB                          | L   | 0.571      | -            | -                | -                | -             |    -4.94 | drext, frozzen, hdstr, nesto, shr      |
|            4 |     4077 | 2024-02-01 | SAW                              | W   | 0.571      | 0.143        | 0.263 (0.021)    | 0.590 (0.048)    | -             |    17.77 | drext, frozzen, hdstr, nesto, shr      |
|            3 |     4223 | 2024-01-28 | ARMARIOS                         | W   | 0.544      | -            | -                | -                | -             |     2.97 | drext, frozzen, Icarus, nesto, snowiee |
|            2 |     4272 | 2024-01-27 | The Agency Clan                  | L   | 0.538      | -            | -                | -                | -             |   -12.52 | frozzen, hdstr, nesto, shr, snowiee    |
|            1 |     4277 | 2024-01-27 | GTZ.ESPORTS                      | W   | 0.538      | 0.143        | -                | 0.095 (0.007)    | -             |     2.82 | frozzen, hdstr, nesto, shr, snowiee    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($632.69)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
