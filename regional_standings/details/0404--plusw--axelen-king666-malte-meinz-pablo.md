### Roster Details<br />
Team Name: plusW<br />
Roster: Axelen, king666, Malte, meinz, pAblo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [404](../standings_global.md)<br />
Regional Rank: [243]( ../standings_europe.md)<br />
Final Rank Value:  559.0<br />
<br />
Final Rank Value (559.0) = Starting Rank Value (526.0) + Head To Head Adjustments (33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.0
- 400 + ( ( 0.062 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 526.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3229 | 2024-04-10 | Begrip Gaming | L   | 0.871      | -            | -                | -                | -         |   -13.11 | Axelen, king666, Malte, meinz, pAblo |
|            9 |     3243 | 2024-04-10 | Kappa Bar     | W   | 0.871      | 0.143        | 0.000 (0.000)    | 0.110 (0.014)    | 0 (0.000) |    11.58 | Axelen, king666, Malte, meinz, pAblo |
|            8 |     3465 | 2024-04-06 | Kappa Borr    | W   | 0.843      | 0.143        | 0.000 (0.000)    | 0.127 (0.015)    | 0 (0.000) |    11.54 | Axelen, king666, Malte, meinz, pAblo |
|            7 |     3631 | 2024-04-03 | Lilmix        | L   | 0.824      | -            | -                | -                | -         |    -6.37 | Axelen, king666, Malte, meinz, pAblo |
|            6 |     3837 | 2024-03-28 | Alliance      | L   | 0.783      | -            | -                | -                | -         |    -3.57 | Axelen, king666, Malte, meinz, pAblo |
|            5 |     4166 | 2024-03-21 | Johnny Speeds | W   | 0.738      | 0.143        | 0.056 (0.006)    | 0.683 (0.072)    | 0 (0.000) |    21.61 | Axelen, king666, Malte, meinz, pAblo |
|            4 |     4598 | 2024-03-13 | Lemoncats     | W   | 0.684      | 0.143        | 0.000 (0.000)    | 0.101 (0.010)    | 0 (0.000) |    10.55 | Axelen, king666, Malte, meinz, pAblo |
|            3 |     8563 | 2023-12-29 | detoks        | L   | 0.184      | -            | -                | -                | -         |    -3.06 | Axelen, khobra, Malte, meinz, viz    |
|            2 |     8618 | 2023-12-21 | onliners5     | W   | 0.132      | 0.143        | 0.001 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     2.52 | Axelen, khobra, Malte, meinz, viz    |
|            1 |     8623 | 2023-12-21 | yengi         | W   | 0.131      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.37 | Axelen, khobra, Malte, meinz, viz    |

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
