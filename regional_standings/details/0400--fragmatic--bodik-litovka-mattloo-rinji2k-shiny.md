### Roster Details<br />
Team Name: fragmatic<br />
Roster: bodik, Litovka, mattloo, rinji2k, shiny<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [400](../standings_global.md)<br />
Regional Rank: [240]( ../standings_europe.md)<br />
Final Rank Value:  562.4<br />
<br />
Final Rank Value (562.4) = Starting Rank Value (526.4) + Head To Head Adjustments (36.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.4
- 400 + ( ( 0.062 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 526.4


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
|           15 |     1393 | 2024-05-12 | CourageG                  | L   | 1.000      | -            | -                | -                | -         |   -22.45 | bodik, Litovka, mattloo, rinji2k, shiny |
|           14 |     1853 | 2024-05-04 | Grannys Knockers          | L   | 1.000      | -            | -                | -                | -         |    -7.09 | bodik, Litovka, mattloo, rinji2k, shiny |
|           13 |     1860 | 2024-05-04 | Wolves eSports            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.109 (0.016)    | 0 (0.000) |    16.73 | bodik, Litovka, mattloo, rinji2k, shiny |
|           12 |     1869 | 2024-05-04 | SHIFT                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.58 | bodik, Litovka, mattloo, rinji2k, shiny |
|           11 |     2820 | 2024-04-18 | ex-Guild Eagles           | L   | 0.923      | -            | -                | -                | -         |    -2.70 | bodik, Litovka, mattloo, rinji2k, shiny |
|           10 |     2884 | 2024-04-17 | 500                       | W   | 0.918      | 0.143        | 0.002 (0.000)    | 0.479 (0.063)    | 0 (0.000) |    25.19 | bodik, Litovka, mattloo, rinji2k, shiny |
|            9 |     4376 | 2024-03-17 | HyperSpirit               | L   | 0.710      | -            | -                | -                | -         |    -5.89 | bodik, Litovka, mattloo, shiny, smouf   |
|            8 |     4477 | 2024-03-15 | Raptors Esports Club      | L   | 0.698      | -            | -                | -                | -         |    -4.05 | bodik, Litovka, mattloo, shiny, smouf   |
|            7 |     4726 | 2024-03-11 | ex-Turów Zgorzelec Esport | W   | 0.671      | 0.333        | 0.006 (0.001)    | 0.491 (0.110)    | 0 (0.000) |    16.67 | bodik, Litovka, mattloo, shiny, smouf   |
|            6 |     4936 | 2024-03-07 | Natus Vincere Junior      | W   | 0.644      | 0.333        | 0.006 (0.001)    | 0.444 (0.095)    | 0 (0.000) |    15.60 | bodik, Litovka, mattloo, shiny, smouf   |
|            5 |     5304 | 2024-03-02 | RUSH B                    | L   | 0.611      | -            | -                | -                | -         |    -4.07 | bodik, Litovka, mattloo, shiny, smouf   |
|            4 |     8107 | 2024-01-12 | Gaimin Gladiators         | L   | 0.278      | -            | -                | -                | -         |    -0.13 | bodik, mattloo, Pikor, shiny, tuscan4ik |
|            3 |     9279 | 2023-12-09 | XI Esport                 | L   | 0.051      | -            | -                | -                | -         |    -0.46 | bodik, Kemply, mattloo, Pikor, shiny    |
|            2 |     9414 | 2023-12-07 | BebraFPL1                 | W   | 0.038      | 0.333        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.57 | bodik, Kemply, mattloo, Pikor, shiny    |
|            1 |     9556 | 2023-12-05 | The Dice                  | L   | 0.025      | -            | -                | -                | -         |    -0.52 | bodik, Kemply, mattloo, Pikor, shiny    |

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
