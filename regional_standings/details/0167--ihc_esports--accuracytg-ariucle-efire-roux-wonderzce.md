### Roster Details<br />
Team Name: IHC Esports<br />
Roster: AccuracyTG, ariucle, efire, ROUX, wonderzce<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [167](../standings_global.md)<br />
Regional Rank: [18]( ../standings_asia.md)<br />
Final Rank Value:  761.5<br />
<br />
Final Rank Value (761.5) = Starting Rank Value (791.3) + Head To Head Adjustments (-29.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.162[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.302[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 791.3
- 400 + ( ( 0.192 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 791.3


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
|           10 |     1100 | 2024-05-16 | The Huns Esports  | L   | 1.000      | -            | -                | -                | -         |   -12.32 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            9 |     1108 | 2024-05-15 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |    -0.36 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            8 |     1890 | 2024-05-03 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |   -14.74 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            7 |     1898 | 2024-05-02 | The Huns Esports  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.292 (0.042)    | 1 (1.000) |    18.85 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            6 |     2001 | 2024-05-01 | Chinggis Warriors | L   | 1.000      | -            | -                | -                | -         |   -15.42 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            5 |     2008 | 2024-04-30 | Northwest         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     3.02 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            4 |     2922 | 2024-04-16 | Team NKT          | L   | 0.909      | -            | -                | -                | -         |   -23.80 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            3 |     2997 | 2024-04-13 | ATOX Esports      | L   | 0.894      | -            | -                | -                | -         |    -3.76 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            2 |     3301 | 2024-04-08 | The Huns Esports  | W   | 0.856      | 0.143        | 0.000 (0.000)    | 0.292 (0.036)    | 1 (0.856) |    16.29 | AccuracyTG, ariucle, efire, ROUX, wonderzce |
|            1 |     3719 | 2024-03-29 | Tseg Taslal       | W   | 0.789      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.47 | Bajify, blackyg4n, Ensury, lannde, SKITZOOO |

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
