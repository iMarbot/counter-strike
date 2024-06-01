### Roster Details<br />
Team Name: LaChampionsLiga<br />
Roster: castrz, dott1, Hezz, pavv+, rzk<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [381](../standings_global.md)<br />
Regional Rank: [97]( ../standings_americas.md)<br />
Final Rank Value:  574.7<br />
<br />
Final Rank Value (574.7) = Starting Rank Value (539.2) + Head To Head Adjustments (35.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.253[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 539.2
- 400 + ( ( 0.068 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 539.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       39 | 2024-05-29 | KRÜ Esports        | W   | 1.000      | 0.284        | 0.019 (0.005)    | 0.272 (0.077)    | 0 (0.000) |    24.76 | castrz, dott1, Hezz, pavv+, rzk     |
|            9 |      104 | 2024-05-28 | Hawks              | L   | 1.000      | -            | -                | -                | -         |   -10.74 | castrz, dott1, Hezz, pavv+, rzk     |
|            8 |      141 | 2024-05-27 | KRÜ Esports        | W   | 1.000      | 0.284        | 0.019 (0.005)    | 0.272 (0.077)    | 0 (0.000) |    25.67 | castrz, dott1, Hezz, pavv+, rzk     |
|            7 |     2095 | 2024-04-28 | Dusty Roots        | L   | 0.991      | -            | -                | -                | -         |    -9.68 | castrz, dott1, Hezz, ivanzinho, rzk |
|            6 |     2147 | 2024-04-27 | InFernales eSports | W   | 0.985      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.55 | castrz, dott1, Hezz, ivanzinho, rzk |
|            5 |     2232 | 2024-04-26 | MIBR Academy       | L   | 0.978      | -            | -                | -                | -         |    -7.92 | castrz, dott1, Hezz, ivanzinho, rzk |
|            4 |     2400 | 2024-04-23 | 9z Academy         | L   | 0.959      | -            | -                | -                | -         |   -12.04 | castrz, dott1, Hezz, ivanzinho, rzk |
|            3 |     2535 | 2024-04-20 | Galorys            | L   | 0.939      | -            | -                | -                | -         |    -4.04 | castrz, dott1, Hezz, ivanzinho, rzk |
|            2 |     2545 | 2024-04-20 | Intense Game       | W   | 0.938      | 0.143        | 0.003 (0.000)    | 0.362 (0.048)    | 0 (0.000) |    21.62 | castrz, dott1, Hezz, ivanzinho, rzk |
|            1 |     2894 | 2024-04-16 | RED Canids         | L   | 0.912      | -            | -                | -                | -         |    -1.66 | castrz, dott1, Hezz, ivanzinho, rzk |

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
