### Roster Details<br />
Team Name: Team Atlantic<br />
Roster: Folke, Inspire, Logic, logz, mupzG<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [325](../standings_global.md)<br />
Regional Rank: [197]( ../standings_europe.md)<br />
Final Rank Value:  567.1<br />
<br />
Final Rank Value (567.1) = Starting Rank Value (531.2) + Head To Head Adjustments (35.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 531.2
- 400 + ( ( 0.066 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 531.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     2412 | 2024-03-11 | IMMAPROBLEM       | W   | 0.832      | 0.143        | 0.000 (0.000)    | 0.136 (0.016)    | 0 (0.000) |    12.54 | Folke, Inspire, Logic, logz, mupzG |
|           11 |     2421 | 2024-03-11 | WOPA Esport       | L   | 0.832      | -            | -                | -                | -         |    -6.23 | Folke, Inspire, Logic, logz, mupzG |
|           10 |     2600 | 2024-03-06 | Astralis Talent   | W   | 0.799      | 0.143        | 0.030 (0.003)    | 0.613 (0.070)    | 0 (0.000) |    22.36 | Folke, Inspire, Logic, logz, mupzG |
|            9 |     2608 | 2024-03-06 | Copenhagen Wolves | L   | 0.799      | -            | -                | -                | -         |    -9.28 | Folke, Inspire, Logic, logz, mupzG |
|            8 |     2621 | 2024-03-06 | Preasy Esport     | L   | 0.799      | -            | -                | -                | -         |    -6.49 | Folke, Inspire, Logic, logz, mupzG |
|            7 |     3025 | 2024-02-27 | XI Esport         | W   | 0.745      | 0.143        | 0.002 (0.000)    | 0.313 (0.033)    | 0 (0.000) |    16.26 | Folke, Inspire, Logic, logz, mupzG |
|            6 |     3859 | 2024-02-06 | IMMAPROBLEM       | L   | 0.605      | -            | -                | -                | -         |    -9.29 | Folke, Inspire, logz, mupzG, zEden |
|            5 |     3876 | 2024-02-05 | Sashi Esport      | W   | 0.599      | 0.143        | 0.055 (0.005)    | 0.256 (0.022)    | 0 (0.000) |    15.47 | Folke, Inspire, logz, mupzG, zEden |
|            4 |     3882 | 2024-02-05 | XI Esport         | L   | 0.599      | -            | -                | -                | -         |    -5.52 | Folke, Inspire, logz, mupzG, zEden |
|            3 |     4106 | 2024-01-31 | Astralis Talent   | L   | 0.565      | -            | -                | -                | -         |    -1.59 | Folke, Inspire, logz, mupzG, zEden |
|            2 |     4465 | 2024-01-22 | Preasy Esport     | W   | 0.505      | 0.143        | 0.007 (0.000)    | 0.525 (0.038)    | 0 (0.000) |    13.12 | Folke, Inspire, logz, mupzG, zEden |
|            1 |     4472 | 2024-01-22 | Copenhagen Wolves | L   | 0.505      | -            | -                | -                | -         |    -5.53 | Folke, Inspire, logz, mupzG, zEden |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
