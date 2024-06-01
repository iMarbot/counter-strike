### Roster Details<br />
Team Name: GTZ.ESPORTS<br />
Roster: brA, c0mplex, Jayy2s, M1KA, MattyMyimb<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [445](../standings_global.md)<br />
Regional Rank: [269]( ../standings_europe.md)<br />
Final Rank Value:  399.1<br />
<br />
Final Rank Value (399.1) = Starting Rank Value (401.0) + Head To Head Adjustments (-1.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 401.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 401.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      924 | 2024-05-18 | ABT Esports     | L   | 1.000      | -            | -                | -                | -         |   -10.68 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|           10 |     1810 | 2024-05-04 | AL-QATRAO       | L   | 1.000      | -            | -                | -                | -         |    -3.51 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            9 |     1832 | 2024-05-04 | The Agency Clan | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.051 (0.007)    | 0 (0.000) |    20.75 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            8 |     1868 | 2024-05-03 | Strike Force    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    16.08 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            7 |     2600 | 2024-04-20 | ALL-IN          | L   | 0.936      | -            | -                | -                | -         |    -8.57 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            6 |     4240 | 2024-03-17 | Coolermaster    | L   | 0.711      | -            | -                | -                | -         |   -10.81 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            5 |     5636 | 2024-02-22 | Enigma Esports  | L   | 0.551      | -            | -                | -                | -         |    -6.81 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            4 |     5701 | 2024-02-21 | ABT Esports     | W   | 0.544      | 0.143        | 0.000 (0.000)    | 0.153 (0.012)    | 0 (0.000) |    11.14 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            3 |     5756 | 2024-02-20 | AL-QATRAO       | L   | 0.537      | -            | -                | -                | -         |    -1.99 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            2 |     6877 | 2024-01-28 | Qlimax          | L   | 0.383      | -            | -                | -                | -         |    -5.99 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            1 |     6978 | 2024-01-27 | AL-QATRAO       | L   | 0.377      | -            | -                | -                | -         |    -1.49 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |

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
