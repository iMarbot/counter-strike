### Roster Details<br />
Team Name: Regnum<br />
Roster: LAZA, LeO, miksozzz, miwo, showcrazy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [384](../standings_global.md)<br />
Regional Rank: [230]( ../standings_europe.md)<br />
Final Rank Value:  580.6<br />
<br />
Final Rank Value (580.6) = Starting Rank Value (635.5) + Head To Head Adjustments (-54.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.012[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 635.5
- 400 + ( ( 0.116 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 635.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      805 | 2024-05-19 | Jake Bube        | L   | 1.000      | -            | -                | -                | -         |   -19.36 | LAZA, LeO, miksozzz, miwo, showcrazy     |
|            9 |     1383 | 2024-05-12 | iNation          | L   | 1.000      | -            | -                | -                | -         |   -10.84 | LAZA, miksozzz, miwo, showcrazy, VENO    |
|            8 |     1400 | 2024-05-12 | Superior Esports | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.40 | LAZA, miksozzz, miwo, showcrazy, VENO    |
|            7 |     1861 | 2024-05-04 | M1X              | L   | 1.000      | -            | -                | -                | -         |   -15.83 | LAZA, miksozzz, miwo, showcrazy, VENO    |
|            6 |     3769 | 2024-03-30 | Sangrija         | L   | 0.796      | -            | -                | -                | -         |   -15.76 | LAZA, LeO, miksozzz, showcrazy, VENO     |
|            5 |     4298 | 2024-03-18 | GYROCOPTER_UA    | L   | 0.718      | -            | -                | -                | -         |   -10.75 | LAZA, miksozzz, miwo, showcrazy, VENO    |
|            4 |     4487 | 2024-03-15 | JANO Esports     | W   | 0.697      | 0.284        | 0.003 (0.001)    | 0.419 (0.083)    | 0 (0.000) |    14.97 | LAZA, miksozzz, miwo, showcrazy, VENO    |
|            3 |     7196 | 2024-01-27 | Soda Gaming      | L   | 0.377      | -            | -                | -                | -         |    -5.41 | LAZA, miksozzz, miwo, showcrazy, VENO    |
|            2 |     9227 | 2023-12-10 | Plitak Potok     | W   | 0.057      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.057) |     0.39 | davinho, illya, Salted, superflik, zecco |
|            1 |     9237 | 2023-12-10 | BUDI2            | W   | 0.056      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.056) |     0.38 | FoXy, ha0s, LeO, Mangulito, RiiL3        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($317.39)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-20 |      0.731 | $350.00        | $255.74         |
| 2023-12-10 |      0.057 | $1,077.35      | $61.65          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
