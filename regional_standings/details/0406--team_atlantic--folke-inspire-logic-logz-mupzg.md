### Roster Details<br />
Team Name: Team Atlantic<br />
Roster: Folke, Inspire, Logic, logz, mupzG<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [406](../standings_global.md)<br />
Regional Rank: [243]( ../standings_europe.md)<br />
Final Rank Value:  544.7<br />
<br />
Final Rank Value (544.7) = Starting Rank Value (519.1) + Head To Head Adjustments (25.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 519.1
- 400 + ( ( 0.059 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 519.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     4607 | 2024-03-11 | IMMAPROBLEM       | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.160 (0.015)    | 0 (0.000) |    10.70 | Folke, Inspire, Logic, logz, mupzG  |
|           13 |     4617 | 2024-03-11 | WOPA Esport       | L   | 0.671      | -            | -                | -                | -         |    -4.04 | Folke, Inspire, Logic, logz, mupzG  |
|           12 |     4848 | 2024-03-06 | Astralis Talent   | W   | 0.638      | 0.143        | 0.012 (0.001)    | 0.452 (0.041)    | 0 (0.000) |    18.11 | Folke, Inspire, Logic, logz, mupzG  |
|           11 |     4860 | 2024-03-06 | Copenhagen Wolves | L   | 0.638      | -            | -                | -                | -         |    -7.20 | Folke, Inspire, Logic, logz, mupzG  |
|           10 |     4873 | 2024-03-06 | Preasy Esport     | L   | 0.637      | -            | -                | -                | -         |    -3.48 | Folke, Inspire, Logic, logz, mupzG  |
|            9 |     5315 | 2024-02-28 | Sashi Esport      | L   | 0.591      | -            | -                | -                | -         |    -3.85 | Folke, Inspire, Logic, logz, mupzG  |
|            8 |     5362 | 2024-02-27 | XI Esport         | W   | 0.584      | 0.143        | 0.001 (0.000)    | 0.277 (0.023)    | 0 (0.000) |    12.80 | Folke, Inspire, Logic, logz, mupzG  |
|            7 |     6378 | 2024-02-06 | IMMAPROBLEM       | L   | 0.444      | -            | -                | -                | -         |    -6.73 | Folke, Inspire, logz, mupzG, Pellyy |
|            6 |     6400 | 2024-02-05 | Sashi Esport      | W   | 0.438      | 0.143        | 0.024 (0.001)    | 0.210 (0.013)    | 0 (0.000) |    11.11 | Folke, Inspire, logz, mupzG, Pellyy |
|            5 |     6407 | 2024-02-05 | XI Esport         | L   | 0.438      | -            | -                | -                | -         |    -4.03 | Folke, Inspire, logz, mupzG, Pellyy |
|            4 |     6417 | 2024-02-05 | WOPA Esport       | L   | 0.438      | -            | -                | -                | -         |    -2.45 | Folke, Inspire, logz, mupzG, Pellyy |
|            3 |     6713 | 2024-01-31 | Astralis Talent   | L   | 0.404      | -            | -                | -                | -         |    -1.25 | Folke, Inspire, logz, mupzG, Pellyy |
|            2 |     7223 | 2024-01-22 | Preasy Esport     | W   | 0.344      | 0.143        | 0.008 (0.000)    | 0.642 (0.032)    | 0 (0.000) |     9.58 | Folke, Inspire, logz, mupzG, Pellyy |
|            1 |     7231 | 2024-01-22 | Copenhagen Wolves | L   | 0.344      | -            | -                | -                | -         |    -3.75 | Folke, Inspire, logz, mupzG, Pellyy |

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
