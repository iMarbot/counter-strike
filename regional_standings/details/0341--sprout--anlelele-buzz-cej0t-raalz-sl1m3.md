### Roster Details<br />
Team Name: Sprout<br />
Roster: Anlelele, Buzz, cej0t, raalz, sL1m3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [341](../standings_global.md)<br />
Regional Rank: [210]( ../standings_europe.md)<br />
Final Rank Value:  515.3<br />
<br />
Final Rank Value (515.3) = Starting Rank Value (492.7) + Head To Head Adjustments (22.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.181[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.047<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 492.7
- 400 + ( ( 0.047 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 492.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     2584 | 2024-03-07 | Alliance                     | L   | 0.803      | -            | -                | -                | -         |    -3.27 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           10 |     3045 | 2024-02-27 | Permitta Esports             | L   | 0.743      | -            | -                | -                | -         |    -1.40 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|            9 |     3066 | 2024-02-26 | B8                           | L   | 0.739      | -            | -                | -                | -         |    -1.74 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|            8 |     3846 | 2024-02-07 | Metizport                    | L   | 0.611      | -            | -                | -                | -         |    -1.12 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|            7 |     4124 | 2024-01-31 | Preasy Esport                | L   | 0.563      | -            | -                | -                | -         |    -1.24 | Anlelele, BERRY, cej0t, raalz, sL1m3  |
|            6 |     4677 | 2024-01-18 | Guild Eagles                 | L   | 0.477      | -            | -                | -                | -         |    -0.70 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            5 |     4690 | 2024-01-17 | 500                          | W   | 0.473      | 0.143        | 0.003 (0.000)    | 0.660 (0.045)    | 0 (0.000) |    12.56 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            4 |     4697 | 2024-01-17 | GUN5 Esports                 | W   | 0.473      | 0.143        | 0.001 (0.000)    | 0.077 (0.005)    | 0 (0.000) |    10.83 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            3 |     4710 | 2024-01-17 | ROSOMAHA                     | W   | 0.473      | 0.143        | 0.000 (0.000)    | 0.136 (0.009)    | 0 (0.000) |     9.99 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            2 |     4927 | 2024-01-12 | TEAM ZOO BAR                 | L   | 0.439      | -            | -                | -                | -         |    -6.43 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            1 |     4939 | 2024-01-12 | Balkan Bears (Romanian team) | W   | 0.439      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.12 | Anlelele, cej0t, raalz, sL1m3, Zyphon |

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
