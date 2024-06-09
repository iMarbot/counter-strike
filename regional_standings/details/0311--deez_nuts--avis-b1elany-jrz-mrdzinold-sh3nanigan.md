### Roster Details<br />
Team Name: DEEZ NUTS<br />
Roster: avis, b1elany, jrz, MrDzinold, sh3nanigan<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [311](../standings_global.md)<br />
Regional Rank: [194]( ../standings_europe.md)<br />
Final Rank Value:  636.9<br />
<br />
Final Rank Value (636.9) = Starting Rank Value (644.0) + Head To Head Adjustments (-7.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 644.0
- 400 + ( ( 0.120 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 644.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3144 | 2024-04-12 | M1 Gaming        | W   | 0.883      | 0.143        | 0.001 (0.000)    | 0.024 (0.003)    | 0 (0.000) |    13.58 | avis, b1elany, jrz, MrDzinold, sh3nanigan |
|            9 |     3173 | 2024-04-11 | brazylijski luz  | L   | 0.878      | -            | -                | -                | -         |    -7.59 | avis, b1elany, jrz, MrDzinold, sh3nanigan |
|            8 |     3258 | 2024-04-10 | AVEZ             | L   | 0.870      | -            | -                | -                | -         |    -6.90 | avis, b1elany, jrz, MrDzinold, sh3nanigan |
|            7 |     3318 | 2024-04-09 | 9INE             | L   | 0.864      | -            | -                | -                | -         |   -12.32 | avis, b1elany, jrz, MrDzinold, sh3nanigan |
|            6 |     3376 | 2024-04-08 | Permitta Esports | L   | 0.856      | -            | -                | -                | -         |    -4.55 | avis, b1elany, jrz, MrDzinold, sh3nanigan |
|            5 |     4537 | 2024-03-14 | KU AZS UZ        | W   | 0.691      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     4.36 | avis, b1elany, ewrzyn, sh3nanigan, zaNNN  |
|            4 |     4769 | 2024-03-10 | brazylijski luz  | L   | 0.665      | -            | -                | -                | -         |    -6.93 | avis, b1elany, ewrzyn, sh3nanigan, zaNNN  |
|            3 |     4783 | 2024-03-10 | LODIS            | W   | 0.664      | 0.143        | 0.001 (0.000)    | 0.140 (0.013)    | 0 (0.000) |     9.25 | avis, b1elany, ewrzyn, sh3nanigan, zaNNN  |
|            2 |     5615 | 2024-02-25 | KOMNATA          | L   | 0.570      | -            | -                | -                | -         |    -8.50 | avis, b1elany, kRaSnaL, sh3nanigan, zaNNN |
|            1 |     5677 | 2024-02-24 | brazylijski luz  | W   | 0.564      | 0.143        | 0.013 (0.001)    | 0.514 (0.041)    | 0 (0.000) |    12.47 | avis, b1elany, kRaSnaL, sh3nanigan, zaNNN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($590.56)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.943 | $246.46        | $232.49         |
| 2024-02-25 |      0.570 | $628.26        | $358.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
