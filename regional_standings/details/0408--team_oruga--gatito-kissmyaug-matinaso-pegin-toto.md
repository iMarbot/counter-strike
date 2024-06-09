### Roster Details<br />
Team Name: TEAM ORUGA<br />
Roster: gAtito, kissmyaug, matinaso, pegin, toto<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [408](../standings_global.md)<br />
Regional Rank: [103]( ../standings_americas.md)<br />
Final Rank Value:  553.4<br />
<br />
Final Rank Value (553.4) = Starting Rank Value (603.4) + Head To Head Adjustments (-50.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.232[<sup>1</sup>](#table2)
- Bounty Collected: 0.164[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 603.4
- 400 + ( ( 0.100 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 603.4


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
|           19 |      108 | 2024-05-28 | LA RUGONETA         | L   | 1.000      | -            | -                | -                | -         |   -18.90 | gAtito, kissmyaug, matinaso, pegin, toto |
|           18 |      156 | 2024-05-27 | VELOX Argentina     | L   | 1.000      | -            | -                | -                | -         |   -16.01 | gAtito, kissmyaug, matinaso, pegin, toto |
|           17 |      744 | 2024-05-19 | DJAMBA MAGAZINE     | L   | 1.000      | -            | -                | -                | -         |   -15.30 | gAtito, kissmyaug, matinaso, pegin, toto |
|           16 |     1928 | 2024-05-02 | Dusty Roots         | L   | 1.000      | -            | -                | -                | -         |   -12.22 | gAtito, kissmyaug, matinaso, pegin, toto |
|           15 |     1936 | 2024-05-02 | KRÜ Esports         | L   | 1.000      | -            | -                | -                | -         |    -7.99 | gAtito, kissmyaug, matinaso, pegin, toto |
|           14 |     2178 | 2024-04-27 | Hawks               | W   | 0.985      | 0.143        | 0.000 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    15.56 | gAtito, kissmyaug, matinaso, pegin, toto |
|           13 |     2184 | 2024-04-27 | FAZ O L             | W   | 0.985      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.37 | gAtito, kissmyaug, matinaso, pegin, toto |
|           12 |     2597 | 2024-04-20 | Galorys             | L   | 0.938      | -            | -                | -                | -         |    -5.56 | gAtito, kissmyaug, matinaso, pegin, toto |
|           11 |     7115 | 2024-01-27 | Romanticos          | L   | 0.379      | -            | -                | -                | -         |    -5.14 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|           10 |     7124 | 2024-01-27 | SOLOVE              | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     6.20 | brokeN, doiz, farias, legy, mid1         |
|            9 |     7146 | 2024-01-27 | Yawara E-Sports     | L   | 0.378      | -            | -                | -                | -         |    -4.50 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            8 |     7159 | 2024-01-27 | phantom troupe      | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.111 (0.006)    | 0 (0.000) |     5.95 | edv, FasteR, gtw, n0page, redi           |
|            7 |     7168 | 2024-01-27 | Looking4Org         | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.90 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            6 |     8615 | 2023-12-21 | paiN Gaming Academy | L   | 0.133      | -            | -                | -                | -         |    -2.07 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            5 |     8816 | 2023-12-16 | Corinthians Esports | L   | 0.099      | -            | -                | -                | -         |    -1.58 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            4 |     8824 | 2023-12-16 | phantom troupe      | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.032 (0.000)    | 0 (0.000) |     1.45 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            3 |     8831 | 2023-12-16 | Astral Aces Esports | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.75 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            2 |     8844 | 2023-12-16 | O Plano B           | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.75 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            1 |     8871 | 2023-12-16 | phantom troupe      | L   | 0.097      | -            | -                | -                | -         |    -1.63 | FasteR, n0page, nth, redi, Riider        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($148.26)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-20 |      1.000 | $78.40         | $78.40          |
| 2024-01-30 |      0.399 | $131.27        | $52.33          |
| 2023-12-21 |      0.133 | $132.22        | $17.53          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
