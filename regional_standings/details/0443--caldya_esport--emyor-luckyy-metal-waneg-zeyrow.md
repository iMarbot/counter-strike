### Roster Details<br />
Team Name: Caldya Esport<br />
Roster: EMYOR, Luckyy, MetaL, waneG, ZeyRow<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [443](../standings_global.md)<br />
Regional Rank: [267]( ../standings_europe.md)<br />
Final Rank Value:  418.4<br />
<br />
Final Rank Value (418.4) = Starting Rank Value (400.4) + Head To Head Adjustments (18.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.4
- 400 + ( ( 0.000 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 400.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     2590 | 2024-04-20 | RushOnGrandpa   | L   | 0.936      | -            | -                | -                | -         |   -10.41 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|           10 |     2601 | 2024-04-20 | Assos           | W   | 0.936      | 0.143        | 0.000 (0.000)    | 0.052 (0.007)    | 0 (0.000) |    14.55 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            9 |     2614 | 2024-04-20 | Goashax Algeria | W   | 0.936      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    13.63 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            8 |     2628 | 2024-04-20 | Mirage Talents  | W   | 0.935      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.36 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            7 |     2634 | 2024-04-20 | 3K ESPORT       | L   | 0.935      | -            | -                | -                | -         |   -14.18 | EMYOR, Luckyy, MetaL, waneG, ZeyRow             |
|            6 |     8240 | 2024-01-03 | 3K ESPORT       | L   | 0.218      | -            | -                | -                | -         |    -3.44 | EMYOR, Fenkiiii, MetaL, polox, waneG            |
|            5 |     8250 | 2024-01-03 | FC GGedyh       | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     3.39 | Bruttas, fallS, fearz, Katkamee, mAYKA          |
|            4 |     8273 | 2024-01-02 | New Era         | L   | 0.212      | -            | -                | -                | -         |    -2.58 | GuiGui, Ministro, Shinji, Tyliix, Wapoh         |
|            3 |     8283 | 2024-01-02 | Goud guys       | W   | 0.211      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.30 | Charon, Pintypunky, Ragnarok4310, rikast, Wetek |
|            2 |     8289 | 2024-01-02 | ADEPTS          | L   | 0.211      | -            | -                | -                | -         |    -0.56 | Brooxsy, cHeuuuuk, Chuckyy, Tarkky, unshaark    |
|            1 |     9453 | 2023-12-02 | BRODA           | L   | 0.004      | -            | -                | -                | -         |    -0.07 | EMYOR, jarod, MetaL, N4MEKz, waneG              |

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
