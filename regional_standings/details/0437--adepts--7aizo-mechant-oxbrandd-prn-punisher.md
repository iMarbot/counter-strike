### Roster Details<br />
Team Name: ADEPTS<br />
Roster: 7AIZO, MECHANT, Oxbrandd, prn, PunisheR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [437](../standings_global.md)<br />
Regional Rank: [263]( ../standings_europe.md)<br />
Final Rank Value:  483.4<br />
<br />
Final Rank Value (483.4) = Starting Rank Value (469.5) + Head To Head Adjustments (13.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.135[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.001[<sup>2</sup>](#table1)

The average of these factors is 0.034<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 469.5
- 400 + ( ( 0.034 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 469.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     8207 | 2024-01-06 | Team Aztec     | W   | 0.238      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.92 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|           10 |     8219 | 2024-01-05 | ADEPTS         | L   | 0.231      | -            | -                | -                | -         |    -0.90 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            9 |     8230 | 2024-01-04 | New Era        | W   | 0.224      | 0.143        | 0.000 (0.000)    | 0.069 (0.002)    | 0 (0.000) |     3.64 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            8 |     8248 | 2024-01-03 | RGW Esports    | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.025 (0.001)    | 0 (0.000) |     3.73 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            7 |     8270 | 2024-01-02 | FC GGedyh      | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     2.67 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            6 |     8281 | 2024-01-02 | ADEPTS         | L   | 0.211      | -            | -                | -                | -         |    -0.80 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            5 |     8286 | 2024-01-02 | Goud guys      | W   | 0.211      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.68 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            4 |     9404 | 2023-12-03 | RGW Esports    | L   | 0.008      | -            | -                | -                | -         |    -0.11 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            3 |     9438 | 2023-12-02 | BRODA          | W   | 0.005      | 0.143        | 0.000 (0.000)    | 0.018 (0.000)    | 1 (0.005) |     0.06 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            2 |     9459 | 2023-12-02 | Les Gaulois    | W   | 0.004      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.004) |     0.05 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |
|            1 |     9481 | 2023-12-02 | 11minutostarde | L   | 0.003      | -            | -                | -                | -         |    -0.02 | 7AIZO, MECHANT, Oxbrandd, prn, PunisheR |

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
