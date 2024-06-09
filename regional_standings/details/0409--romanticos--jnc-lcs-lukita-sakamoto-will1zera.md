### Roster Details<br />
Team Name: Romanticos<br />
Roster: JNC, lcs, Lukita, Sakamoto, will1ZERA<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [409](../standings_global.md)<br />
Regional Rank: [104]( ../standings_americas.md)<br />
Final Rank Value:  552.5<br />
<br />
Final Rank Value (552.5) = Starting Rank Value (511.5) + Head To Head Adjustments (41.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.5
- 400 + ( ( 0.055 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 511.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       44 | 2024-05-29 | Sensei Team         | L   | 1.000      | -            | -                | -                | -         |    -8.83 | JNC, lcs, Lukita, Sakamoto, will1ZERA    |
|           10 |      166 | 2024-05-27 | 9z Academy          | L   | 1.000      | -            | -                | -                | -         |   -12.86 | JNC, lcs, Lukita, Sakamoto, will1ZERA    |
|            9 |      338 | 2024-05-24 | Corinthians Esports | L   | 1.000      | -            | -                | -                | -         |    -9.53 | JNC, lcs, Lukita, Sakamoto, will1ZERA    |
|            8 |      388 | 2024-05-23 | bebidarosa          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.100 (0.014)    | 0 (0.000) |    14.35 | JNC, lcs, Lukita, Sakamoto, will1ZERA    |
|            7 |      391 | 2024-05-23 | Full House Gaming   | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.205 (0.029)    | 0 (0.000) |    20.32 | JNC, lcs, Lukita, Sakamoto, will1ZERA    |
|            6 |      455 | 2024-05-22 | MIBR Academy        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    23.00 | JNC, lcs, Lukita, Sakamoto, will1ZERA    |
|            5 |     1615 | 2024-05-08 | Sharks Youngsters   | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.407 (0.058)    | 0 (0.000) |    20.69 | Brnz1k, lcs, Lukita, Sakamoto, Skr       |
|            4 |     1973 | 2024-05-01 | MIBR Academy        | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Lukita, Sakamoto, santos, Skr, will1ZERA |
|            3 |     1989 | 2024-05-01 | paiN Gaming Academy | L   | 1.000      | -            | -                | -                | -         |    -8.54 | Lukita, Sakamoto, santos, Skr, will1ZERA |
|            2 |     2043 | 2024-04-30 | Corinthians Esports | L   | 1.000      | -            | -                | -                | -         |    -9.85 | Lukita, Sakamoto, santos, Skr, will1ZERA |
|            1 |     2046 | 2024-04-30 | ex-Martians         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.064 (0.009)    | 0 (0.000) |    20.23 | Lukita, Sakamoto, santos, Skr, will1ZERA |

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
