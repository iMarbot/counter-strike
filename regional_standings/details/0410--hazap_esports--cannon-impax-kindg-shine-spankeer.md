### Roster Details<br />
Team Name: Hazap Esports<br />
Roster: cAnnon, impax, kindg, shine, spankeer<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [410](../standings_global.md)<br />
Regional Rank: [105]( ../standings_americas.md)<br />
Final Rank Value:  551.5<br />
<br />
Final Rank Value (551.5) = Starting Rank Value (571.5) + Head To Head Adjustments (-19.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.184[<sup>1</sup>](#table2)
- Bounty Collected: 0.153[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.084<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 571.5
- 400 + ( ( 0.084 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 571.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     4527 | 2024-03-14 | Bounty Hunters Esports | L   | 0.691      | -            | -                | -                | -         |   -12.01 | cAnnon, impax, kindg, shine, spankeer |
|            9 |     5656 | 2024-02-24 | phantom troupe         | L   | 0.565      | -            | -                | -                | -         |    -7.85 | cAnnon, impax, kindg, shine, spankeer |
|            8 |     5659 | 2024-02-24 | CSGONET                | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.084 (0.007)    | 0 (0.000) |     6.81 | cAnnon, impax, kindg, shine, spankeer |
|            7 |     5670 | 2024-02-24 | podmaldito             | W   | 0.564      | 0.143        | 0.000 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     9.57 | cAnnon, impax, kindg, shine, spankeer |
|            6 |     5679 | 2024-02-24 | Myth e-Sports          | L   | 0.564      | -            | -                | -                | -         |    -7.88 | cAnnon, impax, kindg, shine, spankeer |
|            5 |     7122 | 2024-01-27 | LA RUGONETA            | L   | 0.379      | -            | -                | -                | -         |    -6.11 | cAnnon, impax, kindg, shine, spankeer |
|            4 |     8234 | 2024-01-10 | adalYamigos            | L   | 0.266      | -            | -                | -                | -         |    -3.46 | cAnnon, impax, kindg, shine, spankeer |
|            3 |     8699 | 2023-12-17 | Dusty Roots            | L   | 0.105      | -            | -                | -                | -         |    -1.66 | cAnnon, impax, kindg, shine, spankeer |
|            2 |     8807 | 2023-12-16 | Rocket.GG              | W   | 0.099      | 0.143        | 0.001 (0.000)    | 0.062 (0.001)    | 0 (0.000) |     1.79 | cAnnon, impax, kindg, shine, spankeer |
|            1 |     8814 | 2023-12-16 | Bulls 95               | W   | 0.099      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.86 | cAnnon, impax, kindg, shine, spankeer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10.71)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
