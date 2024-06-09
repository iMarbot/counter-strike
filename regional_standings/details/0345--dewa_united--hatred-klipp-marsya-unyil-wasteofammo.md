### Roster Details<br />
Team Name: DEWA United<br />
Roster: Hatred, klipp, marsyA, unyil, WasteOfAmmo<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [345](../standings_global.md)<br />
Regional Rank: [55]( ../standings_asia.md)<br />
Final Rank Value:  615.2<br />
<br />
Final Rank Value (615.2) = Starting Rank Value (610.1) + Head To Head Adjustments (5.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.173[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.103<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 610.1
- 400 + ( ( 0.103 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 610.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     6532 | 2024-02-08 | GR Gaming        | L   | 0.455      | -            | -                | -                | -         |    -3.85 | Hatred, klipp, marsyA, unyil, WasteOfAmmo |
|           10 |     6640 | 2024-02-05 | Jadeite          | W   | 0.436      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.00 | Hatred, klipp, marsyA, unyil, WasteOfAmmo |
|            9 |     8774 | 2023-12-17 | ATOX Esports     | L   | 0.101      | -            | -                | -                | -         |    -0.08 | klipp, marsyA, WasteOfAmmo, xerolte, XigN |
|            8 |     8912 | 2023-12-16 | GR Gaming        | W   | 0.095      | 0.250        | 0.007 (0.000)    | 0.428 (0.010)    | 0 (0.000) |     2.16 | klipp, marsyA, WasteOfAmmo, xerolte, XigN |
|            7 |     9112 | 2023-12-13 | Eruption         | W   | 0.076      | 0.250        | 0.000 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.15 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |
|            6 |     9154 | 2023-12-12 | The QUBE Esports | W   | 0.069      | 0.250        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.95 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |
|            5 |     9199 | 2023-12-11 | Hyper5           | W   | 0.063      | 0.250        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     1.00 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |
|            4 |     9243 | 2023-12-10 | MIRAI Gaming     | W   | 0.056      | 0.250        | 0.000 (0.000)    | 0.200 (0.003)    | 0 (0.000) |     1.12 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |
|            3 |     9303 | 2023-12-09 | Eruption         | L   | 0.049      | -            | -                | -                | -         |    -0.81 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |
|            2 |     9446 | 2023-12-07 | Drippy Lab       | W   | 0.036      | 0.250        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     0.27 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |
|            1 |     9590 | 2023-12-05 | Jadeite          | W   | 0.023      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | Jaytzyy, klipp, marsyA, WasteOfAmmo, Whis |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($193.19)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-17 |      0.519 | $250.00        | $129.86         |
| 2023-12-17 |      0.101 | $250.00        | $25.35          |
| 2023-12-13 |      0.076 | $500.00        | $37.99          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
