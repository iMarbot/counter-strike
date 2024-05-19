### Roster Details<br />
Team Name: For Fun<br />
Roster: Cyrix, Lake, Momo, Pluto, Tender<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [153](../standings_global.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
Final Rank Value:  773.7<br />
<br />
Final Rank Value (773.7) = Starting Rank Value (783.2) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.349[<sup>1</sup>](#table2)
- Bounty Collected: 0.197[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 783.2
- 400 + ( ( 0.193 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 783.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      624 | 2024-04-21 | Walmart Door Greeters | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.035 (0.005)    | true (1.000)  |    12.53 | Cyrix, Lake, Momo, Pluto, Tender   |
|            9 |      628 | 2024-04-21 | Strife Esports        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | true (1.000)  |     3.58 | Cyrix, Lake, Momo, Pluto, Tender   |
|            8 |     4867 | 2024-01-14 | Elevate               | L   | 0.453      | -            | -                | -                | -             |    -6.62 | Momo, onter, Pluto, Tender, WOOHOO |
|            7 |     4906 | 2024-01-12 | Rocket                | L   | 0.442      | -            | -                | -                | -             |    -8.27 | Calix, Momo, onter, Pluto, Tender  |
|            6 |     4912 | 2024-01-12 | BOSS                  | L   | 0.441      | -            | -                | -                | -             |    -4.57 | Calix, Momo, onter, Pluto, Tender  |
|            5 |     4954 | 2024-01-12 | Rocket                | L   | 0.436      | -            | -                | -                | -             |    -8.54 | Calix, Momo, onter, Pluto, Tender  |
|            4 |     4959 | 2024-01-11 | FLUFFY AIMERS         | W   | 0.436      | 0.143        | 0.004 (0.000)    | 0.103 (0.006)    | false (0.000) |     5.17 | Calix, Momo, onter, Pluto, Tender  |
|            3 |     4979 | 2024-01-11 | Take Flyte            | W   | 0.434      | 0.143        | 0.004 (0.000)    | 0.279 (0.017)    | false (0.000) |     5.68 | Calix, Momo, onter, Pluto, Tender  |
|            2 |     5023 | 2024-01-10 | Team Lampa            | W   | 0.428      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | false (0.000) |     2.36 | Calix, Momo, onter, Pluto, Tender  |
|            1 |     5131 | 2024-01-08 | MOLEGAN               | L   | 0.415      | -            | -                | -                | -             |   -10.83 | Calix, Momo, onter, Pluto, Tender  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,173.99)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
