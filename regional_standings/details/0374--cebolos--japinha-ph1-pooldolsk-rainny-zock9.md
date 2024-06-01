### Roster Details<br />
Team Name: CEBOLOS<br />
Roster: japinha, ph1, pooldolsk, rainny, zock9<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [374](../standings_global.md)<br />
Regional Rank: [94]( ../standings_americas.md)<br />
Final Rank Value:  584.8<br />
<br />
Final Rank Value (584.8) = Starting Rank Value (582.3) + Head To Head Adjustments (2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.151[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.090<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 582.3
- 400 + ( ( 0.090 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 582.3


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
|           11 |     8357 | 2023-12-21 | 9z Academy                | L   | 0.133      | -            | -                | -                | -         |    -1.58 | japinha, ph1, pooldolsk, rainny, zock9   |
|           10 |     8435 | 2023-12-17 | pugdesonesto              | W   | 0.105      | 0.143        | 0.001 (0.000)    | 0.146 (0.002)    | 0 (0.000) |     1.95 | japinha, ph1, pooldolsk, rainny, zock9   |
|            9 |     8556 | 2023-12-16 | TEAM ORUGA                | W   | 0.099      | 0.143        | 0.000 (0.000)    | 0.094 (0.001)    | 0 (0.000) |     1.65 | japinha, ph1, pooldolsk, rainny, zock9   |
|            8 |     8560 | 2023-12-16 | Vex Dragons               | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     1.50 | japinha, ph1, pooldolsk, rainny, zock9   |
|            7 |     8580 | 2023-12-16 | 9z Academy                | L   | 0.098      | -            | -                | -                | -         |    -1.16 | japinha, ph1, pooldolsk, rainny, zock9   |
|            6 |     8592 | 2023-12-16 | O Plano B                 | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.81 | japinha, ph1, pooldolsk, rainny, zock9   |
|            5 |     8607 | 2023-12-16 | 2Game Esports B           | W   | 0.097      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.82 | japinha, ph1, pooldolsk, rainny, zock9   |
|            4 |     8918 | 2023-12-11 | Case Esports              | L   | 0.064      | -            | -                | -                | -         |    -0.75 | guizin, ph1, pooldolsk, rainny, zock9    |
|            3 |     9097 | 2023-12-08 | Arena Jogue Fácil Esports | L   | 0.044      | -            | -                | -                | -         |    -0.66 | guizin, ph1, pooldolsk, rainny, zock9    |
|            2 |     9431 | 2023-12-02 | w7m esports               | L   | 0.005      | -            | -                | -                | -         |    -0.09 | Alisson, koala, pooldolsk, rainny, zock9 |
|            1 |     9434 | 2023-12-02 | Patrulha Canina           | W   | 0.005      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.04 | dudinho, huffy, kln, lokyy, sanc         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43.15)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
