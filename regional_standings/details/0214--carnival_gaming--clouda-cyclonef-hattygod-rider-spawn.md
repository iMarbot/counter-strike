### Roster Details<br />
Team Name: Carnival Gaming<br />
Roster: clouda, CycloneF, hattygOD, Rider, SpawN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [214](../standings_global.md)<br />
Regional Rank: [36]( ../standings_asia.md)<br />
Final Rank Value:  699.7<br />
<br />
Final Rank Value (699.7) = Starting Rank Value (719.1) + Head To Head Adjustments (-19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.346[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.055[<sup>2</sup>](#table1)

The average of these factors is 0.161<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 719.1
- 400 + ( ( 0.161 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 719.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      294 | 2024-04-29 | True Rippers     | L   | 1.000      | -            | -                | -                | -         |   -10.14 | clouda, CycloneF, hattygOD, Rider, SpawN              |
|            9 |     1680 | 2024-03-29 | Grayfox Esports  | L   | 0.949      | -            | -                | -                | -         |   -16.94 | clouda, EmbeR, hattygOD, Rider, SpawN                 |
|            8 |     1700 | 2024-03-28 | Gods Reign       | L   | 0.944      | -            | -                | -                | -         |    -8.63 | clouda, EmbeR, hattygOD, Rider, SpawN                 |
|            7 |     1706 | 2024-03-28 | 2ez Gaming       | W   | 0.943      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.94 | clouda, EmbeR, hattygOD, Rider, SpawN                 |
|            6 |     4567 | 2024-01-20 | Marcos Gaming    | W   | 0.490      | 0.143        | 0.086 (0.006)    | 0.087 (0.006)    | 1 (0.490) |     9.80 | Bhavi, ELV1S, EmbeR, R2B2, reV3nnnn                   |
|            5 |     6535 | 2023-11-22 | Marcos Gaming    | W   | 0.102      | 0.143        | 0.086 (0.001)    | 0.087 (0.001)    | 0 (0.000) |     2.07 | Bhavi, Elvis, EmbeR, R2B2, reV3nnnn                   |
|            4 |     6609 | 2023-11-21 | Marcos Gaming    | L   | 0.090      | -            | -                | -                | -         |    -1.01 | Benzene, Catastr0phE, hattygOD, Rider, SpawN          |
|            3 |     6654 | 2023-11-20 | Wasted Potential | W   | 0.083      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     0.81 | 3vilpr1nc3, HeadshotSpeciaL, lynX, Owned, YellowFlash |
|            2 |     6683 | 2023-11-19 | ROG Academy      | W   | 0.076      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.55 | arakyn, BrOCK, SeeK, Smoakkk, vrenyy                  |
|            1 |     7205 | 2023-11-08 | Gods Reign       | W   | 0.004      | 0.143        | 0.174 (0.000)    | 0.479 (0.000)    | 0 (0.000) |     0.09 | Benzene, hattygOD, N1kace, Rider, SpawN               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,040.80)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-29 |      1.000 | $500.00        | $500.00         |
| 2024-01-20 |      0.490 | $3,007.52      | $1,473.55       |
| 2023-11-22 |      0.102 | $600.32        | $61.42          |
| 2023-11-10 |      0.016 | $360.13        | $5.84           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
