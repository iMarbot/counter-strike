### Roster Details<br />
Team Name: Lazer Cats<br />
Roster: 7oX1C, Burmylov, m1she4ka, neiter, t0kk<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [292](../standings_global.md)<br />
Regional Rank: [181]( ../standings_europe.md)<br />
Final Rank Value:  622.0<br />
<br />
Final Rank Value (622.0) = Starting Rank Value (621.6) + Head To Head Adjustments (0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.249[<sup>1</sup>](#table2)
- Bounty Collected: 0.195[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 621.6
- 400 + ( ( 0.112 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 621.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     5896 | 2023-12-07 | Illuminar Gaming | L   | 0.197      | -            | -                | -                | -         |    -2.01 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|           13 |     6051 | 2023-12-03 | Nexus Gaming     | L   | 0.170      | -            | -                | -                | -         |    -0.78 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|           12 |     6450 | 2023-11-25 | Astralis Talent  | L   | 0.116      | -            | -                | -                | -         |    -0.46 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|           11 |     6514 | 2023-11-23 | POLET            | W   | 0.105      | 0.371        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     1.06 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|           10 |     6533 | 2023-11-23 | Zero Tenacity    | L   | 0.103      | -            | -                | -                | -         |    -0.41 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            9 |     6570 | 2023-11-22 | Kappa Bar        | L   | 0.098      | -            | -                | -                | -         |    -1.31 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            8 |     6602 | 2023-11-21 | Team Universe    | W   | 0.091      | 0.303        | 0.000 (0.000)    | 0.086 (0.002)    | 0 (0.000) |     1.36 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            7 |     6666 | 2023-11-19 | Sashi Esport     | L   | 0.078      | -            | -                | -                | -         |    -0.92 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            6 |     6753 | 2023-11-18 | Pompa Team       | W   | 0.069      | 0.333        | 0.000 (0.000)    | 0.014 (0.000)    | 0 (0.000) |     0.77 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            5 |     6840 | 2023-11-16 | Astralis Talent  | W   | 0.057      | 0.333        | 0.030 (0.001)    | 0.613 (0.012)    | 0 (0.000) |     1.57 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            4 |     6896 | 2023-11-15 | WOPA Esport      | W   | 0.050      | 0.303        | 0.009 (0.000)    | 0.485 (0.007)    | 0 (0.000) |     1.12 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            3 |     7022 | 2023-11-12 | AGO esports      | W   | 0.029      | 0.333        | 0.004 (0.000)    | 0.016 (0.000)    | 0 (0.000) |     0.50 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            2 |     7171 | 2023-11-08 | Bleiz            | L   | 0.006      | -            | -                | -                | -         |    -0.12 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |
|            1 |     7213 | 2023-11-08 | Zero Tenacity    | L   | 0.003      | -            | -                | -                | -         |    -0.01 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($154.27)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
