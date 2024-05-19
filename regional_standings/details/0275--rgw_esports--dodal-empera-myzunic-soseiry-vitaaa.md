### Roster Details<br />
Team Name: RGW Esports<br />
Roster: Dodal, Empera, Myzunic, sOSEIRy, ViTaaa<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [275](../standings_global.md)<br />
Regional Rank: [48]( ../standings_asia.md)<br />
Final Rank Value:  638.0<br />
<br />
Final Rank Value (638.0) = Starting Rank Value (635.9) + Head To Head Adjustments (2.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.207[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 635.9
- 400 + ( ( 0.119 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 635.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     5184 | 2024-01-05 | Team Aztec              | W   | 0.392      | 0.143        | 0.000 (0.000)    | 0.040 (0.002)    | 0 (0.000) |     2.68 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|           11 |     5194 | 2024-01-04 | BRODA                   | W   | 0.386      | 0.143        | 0.000 (0.000)    | 0.045 (0.002)    | 0 (0.000) |     2.88 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|           10 |     5204 | 2024-01-03 | BEAT200                 | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     2.58 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            9 |     5222 | 2024-01-02 | Never Named             | W   | 0.373      | 0.143        | 0.000 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     2.57 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            8 |     5229 | 2024-01-02 | Bulldozer (French team) | L   | 0.372      | -            | -                | -                | -         |    -8.18 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            7 |     5239 | 2024-01-02 | Team Aztec              | W   | 0.372      | 0.143        | 0.000 (0.000)    | 0.040 (0.002)    | 0 (0.000) |     2.46 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            6 |     6062 | 2023-12-03 | Soda Gaming             | L   | 0.169      | -            | -                | -                | -         |    -1.73 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            5 |     6100 | 2023-12-02 | SSX                     | L   | 0.165      | -            | -                | -                | -         |    -2.64 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            4 |     6112 | 2023-12-02 | Prodigy (Agency)        | W   | 0.165      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 1 (0.165) |     1.18 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa |
|            3 |     6669 | 2023-11-19 | Divine Vendetta         | L   | 0.078      | -            | -                | -                | -         |    -1.75 | 0SAMAS, Dodal, Myzunic, sOSEIRy, ViTaaa |
|            2 |     6722 | 2023-11-18 | Marcos Gaming           | W   | 0.071      | 0.242        | 0.086 (0.001)    | 0.087 (0.002)    | 0 (0.000) |     1.66 | 0SAMAS, Dodal, Myzunic, sOSEIRy, ViTaaa |
|            1 |     6929 | 2023-11-14 | FG Metarix              | W   | 0.045      | 0.249        | 0.000 (0.000)    | 0.070 (0.001)    | 0 (0.000) |     0.44 | 0SAMAS, Dodz, Myzunic, sOSEIRy, ViTaaa  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($151.89)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-05 |      0.392 | $164.32        | $64.49          |
| 2023-11-19 |      0.078 | $750.00        | $58.40          |
| 2023-11-14 |      0.045 | $650.00        | $28.99          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
