### Roster Details<br />
Team Name: OVERFRAG<br />
Roster: Devine, HS, Louro, P3R3IIRA, SeabraEZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [336](../standings_global.md)<br />
Regional Rank: [202]( ../standings_europe.md)<br />
Final Rank Value:  616.7<br />
<br />
Final Rank Value (616.7) = Starting Rank Value (617.4) + Head To Head Adjustments (-0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.133[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.022[<sup>2</sup>](#table1)

The average of these factors is 0.107<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 617.4
- 400 + ( ( 0.107 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 617.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     5202 | 2024-03-02 | esmagaB        | L   | 0.609      | -            | -                | -                | -         |    -5.67 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            9 |     5600 | 2024-02-23 | Enigma Esports | W   | 0.558      | 0.143        | 0.000 (0.000)    | 0.045 (0.004)    | 0 (0.000) |     5.59 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            8 |     5650 | 2024-02-22 | AL-QATRAO      | L   | 0.551      | -            | -                | -                | -         |    -5.47 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            7 |     5751 | 2024-02-20 | ABT Esports    | W   | 0.538      | 0.143        | 0.000 (0.000)    | 0.153 (0.012)    | 0 (0.000) |     6.05 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            6 |     6594 | 2024-02-02 | ABT Esports    | L   | 0.417      | -            | -                | -                | -         |    -8.84 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            5 |     6623 | 2024-02-02 | Rhyno Esports  | L   | 0.417      | -            | -                | -                | -         |    -1.34 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            4 |     6966 | 2024-01-27 | ABT Esports    | W   | 0.377      | 0.143        | 0.000 (0.000)    | 0.153 (0.008)    | 0 (0.000) |     3.78 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            3 |     6977 | 2024-01-27 | despatiro      | W   | 0.377      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.67 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            2 |     8462 | 2023-12-17 | Leao Foca      | W   | 0.104      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.104) |     1.43 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |
|            1 |     8478 | 2023-12-17 | despatiros     | W   | 0.103      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.103) |     1.09 | Devine, HS, Louro, P3R3IIRA, SeabraEZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($591.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-03 |      0.616 | $813.80        | $501.62         |
| 2023-12-17 |      0.104 | $872.60        | $90.35          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
