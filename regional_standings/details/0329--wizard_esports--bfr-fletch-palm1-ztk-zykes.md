### Roster Details<br />
Team Name: Wizard esports<br />
Roster: bfr, fletch, PALM1, ztk, zykes<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [329](../standings_global.md)<br />
Regional Rank: [201]( ../standings_europe.md)<br />
Final Rank Value:  622.4<br />
<br />
Final Rank Value (622.4) = Starting Rank Value (637.1) + Head To Head Adjustments (-14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.170[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.1
- 400 + ( ( 0.117 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 637.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1401 | 2024-05-12 | Metizport X     | L   | 1.000      | -            | -                | -                | -         |   -12.10 | bfr, fletch, PALM1, ztk, zykes |
|            9 |     1522 | 2024-05-10 | INFURITY Gaming | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.180 (0.026)    | 0 (0.000) |    12.46 | bfr, fletch, PALM1, ztk, zykes |
|            8 |     2138 | 2024-04-28 | Bitfix Gaming   | W   | 0.990      | 0.143        | 0.000 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     6.11 | bfr, fletch, PALM1, ztk, zykes |
|            7 |     2505 | 2024-04-22 | 777 Esports     | L   | 0.950      | -            | -                | -                | -         |    -9.60 | bfr, fletch, PALM1, ztk, zykes |
|            6 |     3368 | 2024-04-08 | Vanir           | W   | 0.857      | 0.143        | 0.000 (0.000)    | 0.052 (0.006)    | 0 (0.000) |     7.90 | bfr, fletch, PALM1, ztk, zykes |
|            5 |     4313 | 2024-03-18 | INFURITY Gaming | L   | 0.717      | -            | -                | -                | -         |   -14.49 | bfr, fletch, PALM1, ztk, zykes |
|            4 |     4737 | 2024-03-11 | Apeks Legends   | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.037 (0.004)    | 0 (0.000) |     4.51 | bfr, fletch, PALM1, ztk, zykes |
|            3 |     5187 | 2024-03-04 | Metizport X     | L   | 0.624      | -            | -                | -                | -         |    -7.96 | bfr, fletch, PALM1, ztk, zykes |
|            2 |     6390 | 2024-02-12 | Nordix Esport   | W   | 0.484      | 0.143        | 0.002 (0.000)    | 0.106 (0.007)    | 0 (0.000) |     7.95 | bfr, fletch, PALM1, ztk, zykes |
|            1 |     6610 | 2024-02-05 | Foxed Gaming    | L   | 0.438      | -            | -                | -                | -         |    -9.50 | bfr, fletch, PALM1, ztk, zykes |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,133.91)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
