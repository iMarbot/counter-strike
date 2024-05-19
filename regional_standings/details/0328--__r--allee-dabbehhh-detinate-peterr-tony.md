### Roster Details<br />
Team Name: Þór<br />
Roster: allee, Dabbehhh, detinate, peterr, Tony<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [328](../standings_global.md)<br />
Regional Rank: [200]( ../standings_europe.md)<br />
Final Rank Value:  559.7<br />
<br />
Final Rank Value (559.7) = Starting Rank Value (508.2) + Head To Head Adjustments (51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 508.2
- 400 + ( ( 0.055 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 508.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     1937 | 2024-03-22 | SAGA Esports            | L   | 0.905      | -            | -                | -                | -         |   -12.60 | allee, Dabbehhh, detinate, peterr, Tony |
|           14 |     2248 | 2024-03-14 | VALLEA                  | W   | 0.853      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.44 | allee, Dabbehhh, detinate, peterr, Tony |
|           13 |     3479 | 2024-02-17 | DUSTY                   | W   | 0.679      | 0.143        | 0.015 (0.001)    | 0.233 (0.023)    | 0 (0.000) |    15.91 | allee, Dabbehhh, detinate, peterr, Tony |
|           12 |     3567 | 2024-02-15 | ÍA Akranes              | W   | 0.666      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     5.88 | allee, Dabbehhh, detinate, peterr, Tony |
|           11 |     3809 | 2024-02-08 | SAGA Esports            | W   | 0.619      | 0.143        | 0.006 (0.001)    | 0.133 (0.012)    | 0 (0.000) |    11.83 | allee, Dabbehhh, detinate, peterr, Tony |
|           10 |     4063 | 2024-02-01 | ÍBV Esports             | W   | 0.573      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     5.57 | allee, Dabbehhh, detinate, peterr, Tony |
|            9 |     4541 | 2024-01-20 | Breiðablik              | W   | 0.492      | 0.143        | 0.000 (0.000)    | 0.115 (0.008)    | 0 (0.000) |     7.53 | allee, Dabbehhh, detinate, peterr, Tony |
|            8 |     4643 | 2024-01-18 | FH                      | W   | 0.479      | 0.143        | 0.000 (0.000)    | 0.040 (0.003)    | 0 (0.000) |     5.22 | allee, Dabbehhh, detinate, peterr, Tony |
|            7 |     5866 | 2023-12-07 | Young Prodigies         | W   | 0.199      | 0.143        | 0.000 (0.000)    | 0.065 (0.002)    | 0 (0.000) |     2.22 | allee, Dabbehhh, detinate, peterr, Tony |
|            6 |     6193 | 2023-11-30 | Ármann                  | W   | 0.153      | 0.143        | 0.000 (0.000)    | 0.097 (0.002)    | 0 (0.000) |     2.36 | allee, Dabbehhh, detinate, peterr, Tony |
|            5 |     6663 | 2023-11-19 | DUSTY                   | L   | 0.079      | -            | -                | -                | -         |    -0.44 | allee, Dabbehhh, peterr, Rean, Tony     |
|            4 |     6801 | 2023-11-16 | Ármann                  | W   | 0.059      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.66 | allee, Dabbehhh, peterr, Rean, Tony     |
|            3 |     6911 | 2023-11-14 | AURORA (Icelandic team) | W   | 0.046      | 0.143        | -                | 0.037 (0.000)    | -         |     0.51 | allee, Dabbehhh, peterr, Rean, Tony     |
|            2 |     6915 | 2023-11-14 | SAGA Esports            | L   | 0.046      | -            | -                | -                | -         |    -0.52 | allee, Dabbehhh, peterr, Rean, Tony     |
|            1 |     7121 | 2023-11-09 | DUSTY                   | L   | 0.013      | -            | -                | -                | -         |    -0.07 | allee, Dabbehhh, detinate, peterr, Tony |

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
