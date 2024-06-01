### Roster Details<br />
Team Name: Troublemakers<br />
Roster: aRon_dA-k1nG, arun, kenz1, Northwest, spok3nn<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [263](../standings_global.md)<br />
Regional Rank: [40]( ../standings_asia.md)<br />
Final Rank Value:  673.5<br />
<br />
Final Rank Value (673.5) = Starting Rank Value (666.0) + Head To Head Adjustments (7.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.221[<sup>1</sup>](#table2)
- Bounty Collected: 0.193[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.0
- 400 + ( ( 0.131 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 666.0


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
|           14 |      807 | 2024-05-19 | Revolution Gaming    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.014 (0.002)    | 1 (1.000) |     8.39 | aRon_dA-k1nG, arun, kenz1, Northwest, spok3nn     |
|           13 |     5721 | 2024-02-21 | RealGamers           | L   | 0.543      | -            | -                | -                | -         |    -9.35 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|           12 |     5764 | 2024-02-20 | CUBE BY SND          | L   | 0.537      | -            | -                | -                | -         |    -8.41 | adai, dosikzz, mag1k3Y, OxygeN, rinn              |
|           11 |     5878 | 2024-02-18 | Revolution Gaming    | W   | 0.523      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     4.34 | DiE, fitch, kamazbob, SNk, xztcu                  |
|           10 |     5992 | 2024-02-16 | MetroTeam            | W   | 0.510      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.81 | captoun, DcAky, multibr3nd, ossic0r, ryujintensei |
|            9 |     7273 | 2024-01-21 | Myth Avenue Gaming   | W   | 0.337      | 0.143        | 0.005 (0.000)    | 0.192 (0.009)    | 0 (0.000) |     5.66 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            8 |     7284 | 2024-01-21 | Gods Reign           | W   | 0.336      | 0.143        | 0.004 (0.000)    | 0.105 (0.005)    | 0 (0.000) |     5.90 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            7 |     7293 | 2024-01-20 | DEWA United          | W   | 0.334      | 0.143        | 0.002 (0.000)    | 0.185 (0.009)    | 0 (0.000) |     6.14 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            6 |     7370 | 2024-01-20 | Drippy Lab           | W   | 0.328      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.02 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            5 |     7425 | 2024-01-19 | DEWA United          | L   | 0.322      | -            | -                | -                | -         |    -4.25 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            4 |     7575 | 2024-01-17 | 2ez Gaming           | L   | 0.310      | -            | -                | -                | -         |    -5.47 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            3 |     7579 | 2024-01-17 | Drippy Lab           | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.83 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            2 |     7584 | 2024-01-17 | SR Nacague           | L   | 0.309      | -            | -                | -                | -         |    -7.12 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |
|            1 |     7599 | 2024-01-17 | Real Original Gaming | W   | 0.308      | 0.143        | 0.003 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     5.03 | aRon_dA-k1nG, arun, imyGDx, Northwest, nursSSS    |

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
