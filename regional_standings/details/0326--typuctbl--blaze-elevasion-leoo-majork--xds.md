### Roster Details<br />
Team Name: TyPuCTbl<br />
Roster: blaze, elevasion, Leoo, majorK-, xds<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [326](../standings_global.md)<br />
Regional Rank: [200]( ../standings_europe.md)<br />
Final Rank Value:  625.4<br />
<br />
Final Rank Value (625.4) = Starting Rank Value (607.3) + Head To Head Adjustments (18.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.217[<sup>1</sup>](#table2)
- Bounty Collected: 0.187[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.102<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 607.3
- 400 + ( ( 0.102 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 607.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     4282 | 2024-03-19 | The Huns Esports | L   | 0.723      | -            | -                | -                | -         |    -4.82 | blaze, elevasion, Leoo, majorK-, xds   |
|           10 |     4496 | 2024-03-15 | MOLEGAN          | W   | 0.696      | 0.250        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     4.86 | blaze, elevasion, Leoo, majorK-, xds   |
|            9 |     4623 | 2024-03-13 | OneTwoThree      | W   | 0.683      | 0.250        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     4.93 | blaze, elevasion, Leoo, majorK-, xds   |
|            8 |     4631 | 2024-03-13 | TYLOO            | L   | 0.682      | -            | -                | -                | -         |    -3.52 | AceQx, Forceboy, Leoo, majorK-, xds    |
|            7 |     4688 | 2024-03-12 | Marcos Gaming    | W   | 0.676      | 0.143        | 0.001 (0.000)    | 0.091 (0.009)    | 0 (0.000) |    12.85 | AceQx, Forceboy, Leoo, majorK-, xds    |
|            6 |     4750 | 2024-03-11 | SR Nacague       | W   | 0.669      | 0.250        | 0.000 (0.000)    | 0.044 (0.007)    | 0 (0.000) |     7.28 | blaze, elevasion, Leoo, majorK-, xds   |
|            5 |     4889 | 2024-03-08 | Memo_team        | L   | 0.649      | -            | -                | -                | -         |   -10.12 | blaze, elevasion, Leoo, majorK-, xds   |
|            4 |     5032 | 2024-03-06 | BrodyyygiNR      | W   | 0.636      | 0.250        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     4.68 | blaze, elevasion, Leoo, majorK-, xds   |
|            3 |     6294 | 2024-02-14 | The Huns Esports | L   | 0.496      | -            | -                | -                | -         |    -2.70 | blaze, elevasion, Leoo, majorK-, xds   |
|            2 |     6301 | 2024-02-14 | Grayfox Esports  | W   | 0.496      | 0.143        | 0.004 (0.000)    | 0.204 (0.014)    | 0 (0.000) |     9.19 | blaze, elevasion, Leoo, majorK-, xds   |
|            1 |     7981 | 2024-01-15 | Memo_team        | L   | 0.295      | -            | -                | -                | -         |    -4.47 | elevasion, killing, Leoo, majorK-, xds |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($75.01)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
