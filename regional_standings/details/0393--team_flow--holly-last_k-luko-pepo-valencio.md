### Roster Details<br />
Team Name: Team Flow<br />
Roster: HoLLy, Lastík, luko, Pepo, Valencio<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [393](../standings_global.md)<br />
Regional Rank: [235]( ../standings_europe.md)<br />
Final Rank Value:  559.2<br />
<br />
Final Rank Value (559.2) = Starting Rank Value (521.5) + Head To Head Adjustments (37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.060<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.5
- 400 + ( ( 0.060 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 521.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |       49 | 2024-05-29 | KUUSAMO.gg       | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.116 (0.039)    | 0 (0.000) |    23.24 | HoLLy, Lastík, luko, Pepo, Valencio |
|           11 |      768 | 2024-05-19 | WinX             | L   | 1.000      | -            | -                | -                | -         |   -21.00 | HoLLy, Lastík, luko, Pepo, Valencio |
|           10 |      788 | 2024-05-19 | ANIMEDODGERS     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.05 | HoLLy, Lastík, luko, Pepo, Valencio |
|            9 |      899 | 2024-05-18 | Dynamo Eclot     | L   | 1.000      | -            | -                | -                | -         |    -3.27 | HoLLy, Lastík, luko, Pepo, Valencio |
|            8 |     1084 | 2024-05-16 | UNiTY esports    | L   | 1.000      | -            | -                | -                | -         |    -4.30 | HoLLy, Lastík, luko, Pepo, Valencio |
|            7 |     1376 | 2024-05-12 | DMS              | L   | 1.000      | -            | -                | -                | -         |    -4.68 | HoLLy, Lastík, luko, Pepo, Valencio |
|            6 |     1465 | 2024-05-11 | SACRAMENTO       | L   | 1.000      | -            | -                | -                | -         |   -12.13 | HoLLy, Lastík, luko, Pepo, Valencio |
|            5 |     1470 | 2024-05-11 | IceFox           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.69 | HoLLy, Lastík, luko, Pepo, Valencio |
|            4 |     1515 | 2024-05-10 | Sampi NEXT       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |    12.14 | HoLLy, Lastík, luko, Pepo, Valencio |
|            3 |     1564 | 2024-05-09 | Lan Party Hotel  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.016 (0.002)    | 0 (0.000) |     9.59 | HoLLy, Lastík, luko, Pepo, Valencio |
|            2 |     1835 | 2024-05-04 | Grannys Knockers | L   | 1.000      | -            | -                | -                | -         |    -6.80 | HoLLy, Lastík, luko, Pepo, Valencio |
|            1 |     1844 | 2024-05-04 | Verdant          | W   | 1.000      | 0.143        | 0.014 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    27.22 | HoLLy, Lastík, luko, Pepo, Valencio |

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
