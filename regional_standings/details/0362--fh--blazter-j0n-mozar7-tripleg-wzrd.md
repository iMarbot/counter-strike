### Roster Details<br />
Team Name: FH<br />
Roster: blazter, j0n, mozar7, TripleG, WZRD<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [362](../standings_global.md)<br />
Regional Rank: [227]( ../standings_europe.md)<br />
Final Rank Value:  382.1<br />
<br />
Final Rank Value (382.1) = Starting Rank Value (400.0) + Head To Head Adjustments (-17.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     3489 | 2024-02-17 | Young Prodigies         | L   | 0.679      | -            | -                | -                | -             |   -10.29 | blazter, j0n, mozar7, TripleG, WZRD |
|           11 |     3666 | 2024-02-13 | ÍBV Esports             | W   | 0.653      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     9.82 | blazter, j0n, mozar7, TripleG, WZRD |
|           10 |     3852 | 2024-02-06 | Ármann                  | L   | 0.606      | -            | -                | -                | -             |    -6.17 | blazter, j0n, mozar7, TripleG, WZRD |
|            9 |     4137 | 2024-01-30 | Breiðablik              | L   | 0.559      | -            | -                | -                | -             |    -6.12 | blazter, j0n, mozar7, TripleG, WZRD |
|            8 |     4549 | 2024-01-20 | DUSTY                   | L   | 0.492      | -            | -                | -                | -             |    -1.59 | blazter, j0n, mozar7, TripleG, WZRD |
|            7 |     4643 | 2024-01-18 | Þór                     | L   | 0.479      | -            | -                | -                | -             |    -5.22 | blazter, j0n, mozar7, TripleG, WZRD |
|            6 |     4983 | 2024-01-11 | ÍA Akranes              | W   | 0.433      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | false (0.000) |     6.87 | blazter, j0n, mozar7, TripleG, WZRD |
|            5 |     5877 | 2023-12-07 | AURORA (Icelandic team) | L   | 0.199      | -            | -                | -                | -             |    -3.14 | blazter, j0n, mozar7, TripleG, WZRD |
|            4 |     6192 | 2023-11-30 | SAGA Esports            | L   | 0.153      | -            | -                | -                | -             |    -1.14 | blazter, j0n, mozar7, TripleG, WZRD |
|            3 |     6802 | 2023-11-16 | Young Prodigies         | L   | 0.059      | -            | -                | -                | -             |    -0.93 | blazter, mozar7, pabo, VCTR, WZRD   |
|            2 |     6913 | 2023-11-14 | ÍA Akranes              | W   | 0.046      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     0.72 | blazter, mozar7, pabo, VCTR, WZRD   |
|            1 |     6917 | 2023-11-14 | Young Prodigies         | L   | 0.046      | -            | -                | -                | -             |    -0.72 | blazter, mozar7, pabo, VCTR, WZRD   |

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
