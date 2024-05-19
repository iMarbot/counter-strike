### Roster Details<br />
Team Name: Kitsune Esports<br />
Roster: .exe, aw3some, slash, tristanxa, uDEADSHOT<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [293](../standings_global.md)<br />
Regional Rank: [50]( ../standings_asia.md)<br />
Final Rank Value:  620.9<br />
<br />
Final Rank Value (620.9) = Starting Rank Value (634.7) + Head To Head Adjustments (-13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.268[<sup>1</sup>](#table2)
- Bounty Collected: 0.201[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 634.7
- 400 + ( ( 0.118 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 634.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1858 | 2024-03-24 | Nixuh          | L   | 0.919      | -            | -                | -                | -             |   -12.95 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            9 |     2129 | 2024-03-17 | Nixuh          | W   | 0.872      | 0.250        | 0.004 (0.001)    | 0.115 (0.025)    | false (0.000) |    14.87 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            8 |     2450 | 2024-03-10 | The Punishers  | W   | 0.825      | 0.250        | 0.001 (0.000)    | 0.058 (0.012)    | false (0.000) |     9.61 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            7 |     2568 | 2024-03-07 | Thpeed         | W   | 0.805      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.03 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            6 |     4274 | 2024-01-27 | Team Shush     | L   | 0.538      | -            | -                | -                | -             |   -11.45 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            5 |     4316 | 2024-01-26 | Bravado Gaming | L   | 0.531      | -            | -                | -                | -             |    -8.40 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            4 |     5126 | 2024-01-09 | Bravado Gaming | L   | 0.417      | -            | -                | -                | -             |    -7.03 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            3 |     5352 | 2023-12-17 | Nixuh          | L   | 0.265      | -            | -                | -                | -             |    -3.84 | .exe, aw3some, slash, tristanxa, uDEADSHOT |
|            2 |     5371 | 2023-12-17 | VYBN           | W   | 0.264      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     2.77 | dizzy, dyvo, Natural, Puppyy, TheM4N       |
|            1 |     5669 | 2023-12-12 | Nixuh          | L   | 0.232      | -            | -                | -                | -             |    -3.40 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($295.98)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-24 |      0.919 | $250.00        | $229.64         |
| 2023-12-17 |      0.265 | $250.00        | $66.34          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
