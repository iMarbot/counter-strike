### Roster Details<br />
Team Name: Caldya Esport<br />
Roster: EMYOR, Luckyy, MetaL, waneG, ZeyRow<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [358](../standings_global.md)<br />
Regional Rank: [224]( ../standings_europe.md)<br />
Final Rank Value:  418.9<br />
<br />
Final Rank Value (418.9) = Starting Rank Value (400.5) + Head To Head Adjustments (18.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.5
- 400 + ( ( 0.000 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 400.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      723 | 2024-04-20 | RushOnGrandpa         | L   | 1.000      | -            | -                | -                | -         |   -10.83 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            9 |      734 | 2024-04-20 | Assos                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |    15.53 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            8 |      746 | 2024-04-20 | Goashax Algeria       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.48 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            7 |      758 | 2024-04-20 | Mirage Talents        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.33 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            6 |      764 | 2024-04-20 | 3K ESPORT             | L   | 1.000      | -            | -                | -                | -         |   -15.02 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            5 |     5202 | 2024-01-03 | 3K ESPORT             | L   | 0.379      | -            | -                | -                | -         |    -5.90 | EMYOR, Fenkiiii, MetaL, polox, waneG            |
|            4 |     5209 | 2024-01-03 | FC GGedyh             | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     5.94 | Bruttas, fallS, fearz, Katkamee, mAYKA          |
|            3 |     5224 | 2024-01-02 | New Era (French team) | L   | 0.373      | -            | -                | -                | -         |    -4.50 | GuiGui, Ministro, Shinji, Tyliix, Wapoh         |
|            2 |     5232 | 2024-01-02 | Goud guys             | W   | 0.372      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.86 | Charon, Pintypunky, Ragnarok4310, rikast, Wetek |
|            1 |     6098 | 2023-12-02 | BRODA                 | L   | 0.165      | -            | -                | -                | -         |    -2.54 | EMYOR, jarod, MetaL, N4MEKz, waneG              |

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
