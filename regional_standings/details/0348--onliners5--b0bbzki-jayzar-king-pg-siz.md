### Roster Details<br />
Team Name: onliners5<br />
Roster: b0bbzki, jayzaR, king, PG, siz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [348](../standings_global.md)<br />
Regional Rank: [208]( ../standings_europe.md)<br />
Final Rank Value:  605.8<br />
<br />
Final Rank Value (605.8) = Starting Rank Value (605.4) + Head To Head Adjustments (0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.256[<sup>1</sup>](#table2)
- Bounty Collected: 0.148[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.4
- 400 + ( ( 0.101 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 605.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     3383 | 2024-04-06 | EYEBALLERS      | L   | 0.843      | -            | -                | -                | -         |    -4.00 | b0bbzki, jayzaR, king, PG, siz   |
|           14 |     8259 | 2024-01-03 | showmakerz      | L   | 0.217      | -            | -                | -                | -         |    -4.13 | b0bbzki, king, PG, poiii, siz    |
|           13 |     8302 | 2023-12-29 | monaco          | W   | 0.185      | 0.143        | 0.001 (0.000)    | 0.018 (0.000)    | 0 (0.000) |     2.94 | b0bbzki, king, PG, poiii, siz    |
|           12 |     8304 | 2023-12-29 | detoks          | W   | 0.184      | 0.143        | 0.000 (0.000)    | 0.014 (0.000)    | 0 (0.000) |     2.10 | b0bbzki, king, PG, poiii, siz    |
|           11 |     8307 | 2023-12-29 | aimclub         | W   | 0.184      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.88 | b0bbzki, king, PG, poiii, siz    |
|           10 |     8347 | 2023-12-22 | Looking4org     | W   | 0.138      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.44 | b0bbzki, king666, PG, poiii, siz |
|            9 |     8349 | 2023-12-22 | Faceit4Contract | W   | 0.138      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.05 | b0bbzki, king666, PG, poiii, siz |
|            8 |     8361 | 2023-12-21 | plusW           | L   | 0.132      | -            | -                | -                | -         |    -2.53 | b0bbzki, king666, PG, poiii, siz |
|            7 |     8365 | 2023-12-21 | G-Units         | W   | 0.131      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.98 | b0bbzki, king666, PG, poiii, siz |
|            6 |     8490 | 2023-12-17 | Alliance        | L   | 0.102      | -            | -                | -                | -         |    -0.61 | b0bbzki, king666, PG, poiii, siz |
|            5 |     8865 | 2023-12-12 | ishjarnor       | W   | 0.072      | 0.143        | 0.000 (0.000)    | 0.059 (0.001)    | 0 (0.000) |     0.55 | b0bbzki, king666, PG, poiii, siz |
|            4 |     8867 | 2023-12-12 | HEYDERS         | W   | 0.071      | 0.143        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.04 | b0bbzki, king666, PG, poiii, siz |
|            3 |     8873 | 2023-12-12 | yeerrrkzi       | W   | 0.071      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.54 | b0bbzki, king666, PG, poiii, siz |
|            2 |     8905 | 2023-12-11 | LoaThE          | L   | 0.065      | -            | -                | -                | -         |    -1.38 | agoz, b0bbzki, PG, poiii, siz    |
|            1 |     8915 | 2023-12-11 | Curlews         | W   | 0.065      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.49 | agoz, b0bbzki, PG, poiii, siz    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($370.25)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
