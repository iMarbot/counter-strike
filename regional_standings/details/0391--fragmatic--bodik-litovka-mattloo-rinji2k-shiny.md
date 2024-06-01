### Roster Details<br />
Team Name: fragmatic<br />
Roster: bodik, Litovka, mattloo, rinji2k, shiny<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [391](../standings_global.md)<br />
Regional Rank: [233]( ../standings_europe.md)<br />
Final Rank Value:  560.2<br />
<br />
Final Rank Value (560.2) = Starting Rank Value (525.1) + Head To Head Adjustments (35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.1
- 400 + ( ( 0.061 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 525.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1380 | 2024-05-12 | CourageG                  | L   | 1.000      | -            | -                | -                | -         |   -22.37 | bodik, Litovka, mattloo, rinji2k, shiny |
|           14 |     1830 | 2024-05-04 | Grannys Knockers          | L   | 1.000      | -            | -                | -                | -         |    -7.86 | bodik, Litovka, mattloo, rinji2k, shiny |
|           13 |     1837 | 2024-05-04 | Wolves eSports            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.109 (0.016)    | 0 (0.000) |    16.81 | bodik, Litovka, mattloo, rinji2k, shiny |
|           12 |     1846 | 2024-05-04 | SHIFT                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.64 | bodik, Litovka, mattloo, rinji2k, shiny |
|           11 |     2764 | 2024-04-18 | ex-Guild Eagles           | L   | 0.923      | -            | -                | -                | -         |    -2.74 | bodik, Litovka, mattloo, rinji2k, shiny |
|           10 |     2827 | 2024-04-17 | 500                       | W   | 0.918      | 0.143        | 0.002 (0.000)    | 0.479 (0.063)    | 0 (0.000) |    25.11 | bodik, Litovka, mattloo, rinji2k, shiny |
|            9 |     4271 | 2024-03-17 | HyperSpirit               | L   | 0.710      | -            | -                | -                | -         |    -5.85 | bodik, Litovka, mattloo, shiny, smouf   |
|            8 |     4369 | 2024-03-15 | Raptors Esports Club      | L   | 0.698      | -            | -                | -                | -         |    -3.91 | bodik, Litovka, mattloo, shiny, smouf   |
|            7 |     4604 | 2024-03-11 | ex-Turów Zgorzelec Esport | W   | 0.671      | 0.333        | 0.006 (0.001)    | 0.375 (0.084)    | 0 (0.000) |    16.36 | bodik, Litovka, mattloo, shiny, smouf   |
|            6 |     4807 | 2024-03-07 | Natus Vincere Junior      | W   | 0.644      | 0.333        | 0.006 (0.001)    | 0.422 (0.091)    | 0 (0.000) |    15.54 | bodik, Litovka, mattloo, shiny, smouf   |
|            5 |     5156 | 2024-03-02 | RUSH B                    | L   | 0.611      | -            | -                | -                | -         |    -4.05 | bodik, Litovka, mattloo, shiny, smouf   |
|            4 |     7854 | 2024-01-12 | Gaimin Gladiators         | L   | 0.278      | -            | -                | -                | -         |    -0.13 | bodik, mattloo, Pikor, shiny, tuscan4ik |
|            3 |     9013 | 2023-12-09 | XI Esport                 | L   | 0.051      | -            | -                | -                | -         |    -0.46 | bodik, Kemply, mattloo, Pikor, shiny    |
|            2 |     9141 | 2023-12-07 | BebraFPL1                 | W   | 0.038      | 0.333        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.57 | bodik, Kemply, mattloo, Pikor, shiny    |
|            1 |     9274 | 2023-12-05 | The Dice                  | L   | 0.025      | -            | -                | -                | -         |    -0.52 | bodik, Kemply, mattloo, Pikor, shiny    |

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
