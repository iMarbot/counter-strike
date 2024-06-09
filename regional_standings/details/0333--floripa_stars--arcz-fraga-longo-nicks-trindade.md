### Roster Details<br />
Team Name: Floripa Stars<br />
Roster: arcz, fraga, Longo, Nicks, trindade<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [333](../standings_global.md)<br />
Regional Rank: [79]( ../standings_americas.md)<br />
Final Rank Value:  620.6<br />
<br />
Final Rank Value (620.6) = Starting Rank Value (629.6) + Head To Head Adjustments (-9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 629.6
- 400 + ( ( 0.113 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 629.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      827 | 2024-05-18 | Hawks               | L   | 1.000      | -            | -                | -                | -         |   -15.45 | arcz, fraga, Longo, Nicks, trindade |
|           10 |      839 | 2024-05-18 | Peak Academy        | L   | 1.000      | -            | -                | -                | -         |   -15.65 | arcz, fraga, Longo, Nicks, trindade |
|            9 |      848 | 2024-05-18 | Angels              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |    10.30 | arcz, fraga, Longo, Nicks, trindade |
|            8 |      857 | 2024-05-18 | CULTO JOVEM         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.47 | arcz, fraga, Longo, Nicks, trindade |
|            7 |     2180 | 2024-04-27 | Sensei Team         | L   | 0.985      | -            | -                | -                | -         |   -12.32 | Longo, Nicks, nog, nth, trindade    |
|            6 |     2193 | 2024-04-27 | CSGONET             | W   | 0.984      | 0.143        | 0.000 (0.000)    | 0.084 (0.012)    | 0 (0.000) |     8.99 | Longo, Nicks, nog, nth, trindade    |
|            5 |     2205 | 2024-04-27 | NIGERIA 96          | L   | 0.984      | -            | -                | -                | -         |   -17.21 | Longo, Nicks, nog, nth, trindade    |
|            4 |     4070 | 2024-03-23 | MIBR Female         | W   | 0.752      | 0.143        | 0.015 (0.002)    | 0.227 (0.024)    | 0 (0.000) |    13.00 | Longo, Nicks, nog, nth, trindade    |
|            3 |     4073 | 2024-03-23 | SoJoga              | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.138 (0.015)    | 0 (0.000) |    12.00 | Longo, Nicks, nog, nth, trindade    |
|            2 |     4082 | 2024-03-23 | Corinthians Esports | L   | 0.751      | -            | -                | -                | -         |   -10.38 | Longo, Nicks, nog, nth, trindade    |
|            1 |     4087 | 2024-03-23 | Formula 1           | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.042 (0.004)    | 0 (0.000) |    11.23 | Longo, Nicks, nog, nth, trindade    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($175.61)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $97.95         | $97.95          |
| 2024-03-26 |      0.772 | $100.52        | $77.66          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
