### Roster Details<br />
Team Name: RGW Esports<br />
Roster: Dodal, Empera, Myzunic, sOSEIRy, ViTaaa<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [428](../standings_global.md)<br />
Regional Rank: [61]( ../standings_asia.md)<br />
Final Rank Value:  508.9<br />
<br />
Final Rank Value (508.9) = Starting Rank Value (504.9) + Head To Head Adjustments (4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.205[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.001[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 504.9
- 400 + ( ( 0.052 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 504.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     8208 | 2024-01-06 | ADEPTS      | L   | 0.238      | -            | -                | -                | -         |    -1.06 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|           11 |     8218 | 2024-01-05 | Team Aztec  | W   | 0.231      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.61 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|           10 |     8231 | 2024-01-04 | BRODA       | W   | 0.224      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.60 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            9 |     8242 | 2024-01-03 | BEAT200     | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     2.47 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            8 |     8248 | 2024-01-03 | ADEPTS      | L   | 0.218      | -            | -                | -                | -         |    -3.73 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            7 |     8271 | 2024-01-02 | Never Named | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     2.40 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            6 |     8279 | 2024-01-02 | Bulldozer   | L   | 0.211      | -            | -                | -                | -         |    -3.65 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            5 |     8292 | 2024-01-02 | Team Aztec  | W   | 0.211      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.36 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            4 |     9396 | 2023-12-03 | Soda Gaming | L   | 0.008      | -            | -                | -                | -         |    -0.09 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            3 |     9404 | 2023-12-03 | ADEPTS      | W   | 0.008      | 0.143        | 0.000 (0.000)    | 0.031 (0.000)    | 1 (0.008) |     0.11 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            2 |     9455 | 2023-12-02 | SSX         | L   | 0.004      | -            | -                | -                | -         |    -0.06 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            1 |     9479 | 2023-12-02 | Prodigy     | W   | 0.003      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.003) |     0.04 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($39.12)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
