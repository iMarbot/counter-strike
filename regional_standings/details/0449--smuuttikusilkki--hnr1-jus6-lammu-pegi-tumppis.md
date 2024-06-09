### Roster Details<br />
Team Name: smuuttikusilkki<br />
Roster: hNR1, JUS6, lammu, Pegi, Tumppis<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [449](../standings_global.md)<br />
Regional Rank: [270]( ../standings_europe.md)<br />
Final Rank Value:  481.5<br />
<br />
Final Rank Value (481.5) = Starting Rank Value (488.8) + Head To Head Adjustments (-7.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 488.8
- 400 + ( ( 0.044 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 488.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     2675 | 2024-04-20 | RoundsGG              | L   | 0.936      | -            | -                | -                | -         |    -9.76 | hNR1, JUS6, lammu, Pegi, Tumppis |
|            9 |     3096 | 2024-04-13 | ENCE Academy          | L   | 0.890      | -            | -                | -                | -         |    -4.03 | hNR1, JUS6, lammu, Pegi, Tumppis |
|            8 |     3414 | 2024-04-07 | nonnih                | W   | 0.850      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.95 | hNR1, JUS6, lammu, Pegi, Tumppis |
|            7 |     4423 | 2024-03-16 | Young Gods            | L   | 0.704      | -            | -                | -                | -         |    -9.93 | hNR1, JUS6, Pegi, Tumppis, yolt  |
|            6 |     4432 | 2024-03-16 | Flying Angels         | W   | 0.704      | 0.143        | 0.002 (0.000)    | 0.213 (0.021)    | 0 (0.000) |    15.53 | hNR1, JUS6, Pegi, Tumppis, yolt  |
|            5 |     4542 | 2024-03-14 | Gorillas              | L   | 0.691      | -            | -                | -                | -         |    -8.02 | hNR1, JUS6, Late, Pegi, robson   |
|            4 |     4732 | 2024-03-11 | Academy Cybersport XP | W   | 0.671      | 0.333        | 0.000 (0.000)    | 0.028 (0.006)    | 0 (0.000) |     7.90 | hNR1, JUS6, Late, Pegi, robson   |
|            3 |     4816 | 2024-03-09 | Griefers              | W   | 0.658      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.93 | hNR1, JUS6, Late, Pegi, robson   |
|            2 |     4946 | 2024-03-07 | TopTab Club           | L   | 0.644      | -            | -                | -                | -         |    -8.68 | hNR1, JUS6, Late, Pegi, robson   |
|            1 |     6732 | 2024-02-03 | Split                 | L   | 0.424      | -            | -                | -                | -         |    -8.23 | hNR1, JUS6, Late, Pegi, robson   |

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