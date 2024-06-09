### Roster Details<br />
Team Name: WICKED<br />
Roster: Andrew, Austin, Loagurt, mason, zeep<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [195](../standings_global.md)<br />
Regional Rank: [40]( ../standings_americas.md)<br />
Final Rank Value:  728.9<br />
<br />
Final Rank Value (728.9) = Starting Rank Value (721.9) + Head To Head Adjustments (7.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.075[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.9
- 400 + ( ( 0.158 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 721.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |     4061 | 2024-03-23 | ASCEND             | W   | 0.753      | 0.333        | 0.006 (0.001)    | 0.039 (0.010)    | 0 (0.000) |    10.39 | Andrew, Austin, Loagurt, mason, zeep   |
|           15 |     4149 | 2024-03-21 | Brahmas            | W   | 0.740      | 0.333        | 0.004 (0.001)    | 0.049 (0.012)    | 0 (0.000) |     9.80 | Andrew, Austin, Loagurt, mason, zeep   |
|           14 |     4254 | 2024-03-19 | VitaPLUR           | W   | 0.726      | 0.333        | 0.003 (0.001)    | 0.020 (0.005)    | 0 (0.000) |     9.27 | Andrew, Austin, Loagurt, mason, zeep   |
|           13 |     4293 | 2024-03-18 | 5Fellas            | W   | 0.720      | 0.333        | 0.002 (0.000)    | 0.019 (0.005)    | 0 (0.000) |     9.21 | Andrew, Austin, Loagurt, mason, zeep   |
|           12 |     4351 | 2024-03-17 | LAG Gaming         | L   | 0.711      | -            | -                | -                | -         |    -5.06 | Andrew, Austin, Loagurt, mason, zeep   |
|           11 |     4385 | 2024-03-17 | Atomic Gaming      | W   | 0.710      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.710) |     3.61 | Andrew, Austin, Loagurt, mason, zeep   |
|           10 |     4458 | 2024-03-15 | Brahmas            | L   | 0.700      | -            | -                | -                | -         |   -12.18 | Andrew, Austin, Loagurt, mason, zeep   |
|            9 |     7231 | 2024-01-26 | Rocket             | L   | 0.373      | -            | -                | -                | -         |    -7.85 | Andrew, Loagurt, mason, navy, zeep     |
|            8 |     7394 | 2024-01-23 | Akimbo Esports     | L   | 0.353      | -            | -                | -                | -         |    -4.84 | Andrew, Austin, Loagurt, mason, zeep   |
|            7 |     8153 | 2024-01-11 | LOS                | L   | 0.273      | -            | -                | -                | -         |    -6.48 | Andrew, Austin, Loagurt, mason, zeep   |
|            6 |     8156 | 2024-01-11 | Unjustified Gaming | W   | 0.273      | 0.143        | 0.000 (0.000)    | 0.053 (0.002)    | 0 (0.000) |     1.86 | Andrew, Austin, Loagurt, mason, zeep   |
|            5 |     8213 | 2024-01-10 | FlyQuest RED       | W   | 0.267      | 0.143        | 0.016 (0.001)    | 0.220 (0.008)    | 0 (0.000) |     4.68 | Andrew, Austin, Loagurt, mason, zeep   |
|            4 |     8295 | 2024-01-09 | vagrants           | L   | 0.260      | -            | -                | -                | -         |    -6.28 | Andrew, Austin, Loagurt, mason, tBonuh |
|            3 |     8301 | 2024-01-09 | CCG Esports        | W   | 0.260      | 0.143        | 0.000 (0.000)    | 0.043 (0.002)    | 0 (0.000) |     1.18 | Andrew, Austin, Loagurt, mason, tBonuh |
|            2 |     8400 | 2024-01-08 | Pantsu             | W   | 0.254      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.14 | Andrew, Austin, Loagurt, mason, tBonuh |
|            1 |     9214 | 2023-12-10 | Torqued            | L   | 0.059      | -            | -                | -                | -         |    -1.47 | Andrew, Austin, Loagurt, mason, navy   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,634.24)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
