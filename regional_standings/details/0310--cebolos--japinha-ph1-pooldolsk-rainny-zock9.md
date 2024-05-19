### Roster Details<br />
Team Name: CEBOLOS<br />
Roster: japinha, ph1, pooldolsk, rainny, zock9<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [310](../standings_global.md)<br />
Regional Rank: [72]( ../standings_americas.md)<br />
Final Rank Value:  602.4<br />
<br />
Final Rank Value (602.4) = Starting Rank Value (599.3) + Head To Head Adjustments (3.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.237[<sup>1</sup>](#table2)
- Bounty Collected: 0.164[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 599.3
- 400 + ( ( 0.100 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 599.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     5293 | 2023-12-21 | 9z Academy                | L   | 0.294      | -            | -                | -                | -         |    -3.82 | japinha, ph1, pooldolsk, rainny, zock9   |
|           10 |     5434 | 2023-12-16 | TEAM ORUGA                | W   | 0.260      | 0.143        | 0.001 (0.000)    | 0.108 (0.004)    | 0 (0.000) |     4.09 | japinha, ph1, pooldolsk, rainny, zock9   |
|            9 |     5436 | 2023-12-16 | Vex Dragons               | W   | 0.260      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     4.01 | japinha, ph1, pooldolsk, rainny, zock9   |
|            8 |     5452 | 2023-12-16 | 9z Academy                | L   | 0.259      | -            | -                | -                | -         |    -3.36 | japinha, ph1, pooldolsk, rainny, zock9   |
|            7 |     5461 | 2023-12-16 | O Plano B                 | W   | 0.259      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     3.11 | japinha, ph1, pooldolsk, rainny, zock9   |
|            6 |     5472 | 2023-12-16 | 2Game Esports B           | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.03 | japinha, ph1, pooldolsk, rainny, zock9   |
|            5 |     5689 | 2023-12-11 | Case Esports              | L   | 0.226      | -            | -                | -                | -         |    -2.40 | guizin, ph1, pooldolsk, rainny, zock9    |
|            4 |     5830 | 2023-12-08 | Arena Jogue Fácil Esports | L   | 0.206      | -            | -                | -                | -         |    -2.63 | guizin, ph1, pooldolsk, rainny, zock9    |
|            3 |     6084 | 2023-12-02 | Patrulha Canina           | W   | 0.166      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.28 | dudinho, huffy, kln, lokyy, sanc         |
|            2 |     6184 | 2023-11-30 | 9z Academy                | L   | 0.154      | -            | -                | -                | -         |    -2.00 | heartless, ph1, pooldolsk, rainny, zock9 |
|            1 |     6187 | 2023-11-30 | TIMACETA                  | W   | 0.153      | 0.143        | 0.001 (0.000)    | 0.145 (0.003)    | 0 (0.000) |     2.77 | heartless, ph1, pooldolsk, rainny, zock9 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($95.57)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
