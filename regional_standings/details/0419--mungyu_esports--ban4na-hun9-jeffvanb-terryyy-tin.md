### Roster Details<br />
Team Name: MungYu Esports<br />
Roster: BaN4na, Hun9, JeffVanB, Terryyy, Tin<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [419](../standings_global.md)<br />
Regional Rank: [60]( ../standings_asia.md)<br />
Final Rank Value:  522.2<br />
<br />
Final Rank Value (522.2) = Starting Rank Value (495.0) + Head To Head Adjustments (27.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.182[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.047<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 495.0
- 400 + ( ( 0.047 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 495.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     7362 | 2024-01-20 | Eruption         | L   | 0.329      | -            | -                | -                | -         |    -4.13 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           12 |     7418 | 2024-01-19 | The MongolZ      | L   | 0.322      | -            | -                | -                | -         |    -0.02 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           11 |     7423 | 2024-01-19 | The Huns Esports | W   | 0.322      | 0.143        | 0.000 (0.000)    | 0.292 (0.013)    | 0 (0.000) |     8.96 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|           10 |     7707 | 2024-01-15 | The Huns Esports | W   | 0.296      | 0.143        | 0.000 (0.000)    | 0.292 (0.012)    | 0 (0.000) |     8.35 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            9 |     7709 | 2024-01-15 | GR Gaming        | W   | 0.296      | 0.143        | 0.007 (0.000)    | 0.428 (0.018)    | 0 (0.000) |     7.74 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            8 |     7725 | 2024-01-15 | Clutch Gaming    | W   | 0.295      | 0.143        | 0.000 (0.000)    | 0.167 (0.007)    | 0 (0.000) |     6.87 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            7 |     8265 | 2024-01-03 | TYLOO            | L   | 0.216      | -            | -                | -                | -         |    -1.07 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            6 |     8269 | 2024-01-02 | NewHappy         | L   | 0.214      | -            | -                | -                | -         |    -1.72 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            5 |     8297 | 2024-01-01 | Jadeite          | W   | 0.202      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.35 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            4 |     8340 | 2023-12-23 | NewHappy         | L   | 0.141      | -            | -                | -                | -         |    -1.21 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            3 |     8344 | 2023-12-22 | Wings Up Gaming  | L   | 0.141      | -            | -                | -                | -         |    -1.19 | BaN4na, Hun9, JeffVanB, Terryyy, Tin |
|            2 |     8518 | 2023-12-16 | Talented Ynufe   | W   | 0.101      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.18 | h1mz, Hun9, sunshinez, Terryyy, Tin  |
|            1 |     8523 | 2023-12-16 | AP Gaming        | W   | 0.101      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.17 | h1mz, Hun9, sunshinez, Terryyy, Tin  |

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
