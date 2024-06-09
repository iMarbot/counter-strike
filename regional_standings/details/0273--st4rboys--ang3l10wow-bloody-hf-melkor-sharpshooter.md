### Roster Details<br />
Team Name: st4rboys<br />
Roster: Ang3l10wow, Bloody, hf, MELKOR, Sharpshooter<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [273](../standings_global.md)<br />
Regional Rank: [41]( ../standings_asia.md)<br />
Final Rank Value:  666.0<br />
<br />
Final Rank Value (666.0) = Starting Rank Value (683.0) + Head To Head Adjustments (-17.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.202[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.0
- 400 + ( ( 0.139 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 683.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     3540 | 2024-04-05 | love birds      | L   | 0.835      | -            | -                | -                | -         |   -10.74 | Ang3l10wow, Bloody, hf, MELKOR, Sharpshooter        |
|           11 |     3730 | 2024-03-31 | Grayfox Esports | W   | 0.805      | 0.242        | 0.004 (0.001)    | 0.204 (0.040)    | 0 (0.000) |    12.31 | Ang3l10wow, Bloody, hf, MELKOR, Sharpshooter        |
|           10 |     3737 | 2024-03-31 | Carnival Gaming | W   | 0.804      | 0.242        | 0.002 (0.000)    | 0.022 (0.004)    | 0 (0.000) |    10.72 | Ang3l10wow, Bloody, hf, MELKOR, Sharpshooter        |
|            9 |     4015 | 2024-03-25 | Gods Reign      | L   | 0.764      | -            | -                | -                | -         |    -5.13 | Ang3l10wow, Bloody, hf, MELKOR, Sharpshooter        |
|            8 |     4367 | 2024-03-17 | True Rippers    | L   | 0.711      | -            | -                | -                | -         |    -8.16 | Ang3l10wow, Bloody, hf, MELKOR, Sharpshooter        |
|            7 |     5580 | 2024-02-26 | Come Mid        | L   | 0.576      | -            | -                | -                | -         |   -12.58 | Ang3l10wow, Bloody, Dynamite, Scoffic, Sharpshooter |
|            6 |     6467 | 2024-02-10 | Marcos Gaming   | L   | 0.469      | -            | -                | -                | -         |    -6.26 | Ang3l10wow, Bloody, Dynamite, friberg, Sharpshooter |
|            5 |     6760 | 2024-02-03 | Made In 4No     | L   | 0.423      | -            | -                | -                | -         |    -6.69 | Ang3l10wow, Bloody, Dynamite, Scoffic, Sharpshooter |
|            4 |     6896 | 2024-02-01 | Team Paradox    | W   | 0.409      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.98 | Ang3l10wow, Bloody, Dynamite, Scoffic, Sharpshooter |
|            3 |     6948 | 2024-01-31 | vRn             | W   | 0.403      | 0.143        | 0.000 (0.000)    | 0.011 (0.001)    | 0 (0.000) |     2.14 | Ang3l10wow, Bloody, Dynamite, Scoffic, Sharpshooter |
|            2 |     6986 | 2024-01-30 | Team Mystic     | W   | 0.396      | 0.143        | 0.000 (0.000)    | 0.011 (0.001)    | 0 (0.000) |     2.14 | Ang3l10wow, Bloody, Dynamite, Scoffic, Sharpshooter |
|            1 |     7097 | 2024-01-28 | Come Mid        | W   | 0.383      | 0.143        | 0.000 (0.000)    | 0.061 (0.003)    | 0 (0.000) |     3.27 | BoNo, HSB, Rocky, sadbutrue, SOULM8                 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,151.38)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.805 | $500.00        | $402.30         |
| 2024-02-10 |      0.469 | $8,000.00      | $3,749.07       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
