### Roster Details<br />
Team Name: IHC Esports<br />
Roster: AccuracyTG, ariucle, efire, ROUX, wonderzce<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [122](../standings_global.md)<br />
Regional Rank: [14]( ../standings_asia.md)<br />
Final Rank Value:  828.8<br />
<br />
Final Rank Value (828.8) = Starting Rank Value (882.0) + Head To Head Adjustments (-53.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.162[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.481[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 882.0
- 400 + ( ( 0.237 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 882.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     1110 | 2024-05-16 | The Huns Esports  | L   | 1.000      | -            | -                | -                | -         |   -16.11 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|           12 |     1118 | 2024-05-15 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -0.54 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|           11 |     1915 | 2024-05-03 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |   -17.72 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|           10 |     1923 | 2024-05-02 | The Huns Esports  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.292 (0.042)    | 1 (1.000) |    14.54 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            9 |     2032 | 2024-05-01 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |   -18.85 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            8 |     2039 | 2024-04-30 | Northwest         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     1.98 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            7 |     2983 | 2024-04-16 | Team NKT          | L   | 0.909      | -            | -                | -                | -         |   -25.40 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            6 |     3063 | 2024-04-13 | ATOX Esports      | L   | 0.894      | -            | -                | -                | -         |    -4.84 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            5 |     3382 | 2024-04-08 | The Huns Esports  | W   | 0.856      | 0.143        | 0.000 (0.000)    | 0.292 (0.036)    | 1 (0.856) |    11.96 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            4 |     3433 | 2024-04-07 | Born to Win       | W   | 0.849      | 0.143        | 0.000 (0.000)    | 0.023 (0.003)    | 1 (0.849) |     2.34 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            3 |     3506 | 2024-04-06 | KnowHow           | W   | 0.841      | 0.143        | 0.000 (0.000)    | 0.022 (0.003)    | 1 (0.841) |     1.77 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            2 |     3541 | 2024-04-05 | ATOX Esports      | L   | 0.835      | -            | -                | -                | -         |    -3.86 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            1 |     3813 | 2024-03-29 | Tseg Taslal       | W   | 0.789      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.56 | Bajify, blackyg4n, Ensury, lannde, SKITZOOO |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,298.04)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
