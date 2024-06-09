### Roster Details<br />
Team Name: Memo_team<br />
Roster: 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [307](../standings_global.md)<br />
Regional Rank: [192]( ../standings_europe.md)<br />
Final Rank Value:  641.0<br />
<br />
Final Rank Value (641.0) = Starting Rank Value (620.3) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.250[<sup>1</sup>](#table2)
- Bounty Collected: 0.171[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 620.3
- 400 + ( ( 0.108 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 620.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     4103 | 2024-03-23 | Noobs But Diligent | L   | 0.750      | -            | -                | -                | -         |    -7.91 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |
|           11 |     4198 | 2024-03-21 | The Huns Esports   | W   | 0.736      | 0.250        | 0.000 (0.000)    | 0.292 (0.054)    | 0 (0.000) |    18.00 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |
|           10 |     4624 | 2024-03-13 | Noobs But Diligent | L   | 0.683      | -            | -                | -                | -         |    -7.13 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |
|            9 |     4751 | 2024-03-11 | The Huns Esports   | W   | 0.669      | 0.250        | 0.000 (0.000)    | 0.292 (0.049)    | 0 (0.000) |    16.96 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |
|            8 |     4889 | 2024-03-08 | TyPuCTbl           | W   | 0.649      | 0.250        | 0.000 (0.000)    | 0.106 (0.017)    | 0 (0.000) |    10.12 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |
|            7 |     5024 | 2024-03-06 | Jadeite            | W   | 0.636      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.27 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |
|            6 |     5247 | 2024-03-03 | Shadow Garden      | L   | 0.616      | -            | -                | -                | -         |    -9.54 | DrammaGod, GREATEST, kenhy, mds, XeeDo              |
|            5 |     7956 | 2024-01-15 | Team NKT           | L   | 0.297      | -            | -                | -                | -         |    -3.36 | 1nki666, ayeprince, dan4ck, PsychoDoctor, S0uthS1d3 |
|            4 |     7961 | 2024-01-15 | Chinggis Warriors  | W   | 0.296      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.16 | 1nki666, ayeprince, dan4ck, PsychoDoctor, S0uthS1d3 |
|            3 |     7966 | 2024-01-15 | MungYu Esports     | L   | 0.295      | -            | -                | -                | -         |    -6.19 | 1nki666, ayeprince, dan4ck, PsychoDoctor, S0uthS1d3 |
|            2 |     7981 | 2024-01-15 | TyPuCTbl           | W   | 0.295      | 0.143        | 0.000 (0.000)    | 0.106 (0.004)    | 0 (0.000) |     4.47 | 1nki666, ayeprince, dan4ck, PsychoDoctor, S0uthS1d3 |
|            1 |     9082 | 2023-12-13 | Sashi Academy      | L   | 0.078      | -            | -                | -                | -         |    -1.13 | 1nki666, 7AM, dan4ck, PsychoDoctor, S0uthS1d3       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($302.19)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.750 | $300.00        | $225.04         |
| 2024-03-03 |      0.617 | $125.00        | $77.15          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
