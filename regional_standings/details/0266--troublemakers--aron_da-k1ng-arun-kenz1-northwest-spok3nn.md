### Roster Details<br />
Team Name: Troublemakers<br />
Roster: aRon_dA-k1nG, arun, kenz1, Northwest, spok3nn<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [266](../standings_global.md)<br />
Regional Rank: [39]( ../standings_asia.md)<br />
Final Rank Value:  672.9<br />
<br />
Final Rank Value (672.9) = Starting Rank Value (665.5) + Head To Head Adjustments (7.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.221[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 665.5
- 400 + ( ( 0.131 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 665.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      819 | 2024-05-19 | Revolution Gaming    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.014 (0.002)    | 1 (1.000) |     8.41 | aRon_dA-k1nG, arun, kenz1, Northwest, spok3nn     |
|           13 |     5884 | 2024-02-21 | RealGamers           | L   | 0.543      | -            | -                | -                | -         |    -9.35 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|           12 |     5932 | 2024-02-20 | CUBE BY SND          | L   | 0.537      | -            | -                | -                | -         |    -8.39 | adai, dosikzz, mag1k3Y, OxygeN, rinn              |
|           11 |     6051 | 2024-02-18 | Revolution Gaming    | W   | 0.523      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     4.35 | DiE, fitch, kamazbob, SNk, xztcu                  |
|           10 |     6167 | 2024-02-16 | MetroTeam            | W   | 0.510      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.81 | captoun, DcAky, multibr3nd, ossic0r, ryujintensei |
|            9 |     7516 | 2024-01-21 | Myth Avenue Gaming   | W   | 0.337      | 0.143        | 0.005 (0.000)    | 0.192 (0.009)    | 0 (0.000) |     5.65 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            8 |     7527 | 2024-01-21 | Gods Reign           | W   | 0.336      | 0.143        | 0.004 (0.000)    | 0.105 (0.005)    | 0 (0.000) |     5.90 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            7 |     7536 | 2024-01-20 | DEWA United          | W   | 0.334      | 0.143        | 0.002 (0.000)    | 0.176 (0.008)    | 0 (0.000) |     6.09 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            6 |     7614 | 2024-01-20 | Drippy Lab           | W   | 0.328      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.02 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            5 |     7672 | 2024-01-19 | DEWA United          | L   | 0.322      | -            | -                | -                | -         |    -4.29 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            4 |     7824 | 2024-01-17 | 2ez Gaming           | L   | 0.310      | -            | -                | -                | -         |    -5.46 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            3 |     7828 | 2024-01-17 | Drippy Lab           | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.83 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            2 |     7833 | 2024-01-17 | SR Nacague           | L   | 0.309      | -            | -                | -                | -         |    -7.12 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            1 |     7848 | 2024-01-17 | Real Original Gaming | W   | 0.308      | 0.143        | 0.003 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     5.03 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($91.20)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
