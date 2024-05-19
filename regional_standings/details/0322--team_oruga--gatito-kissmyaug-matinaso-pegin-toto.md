### Roster Details<br />
Team Name: TEAM ORUGA<br />
Roster: gAtito, kissmyaug, matinaso, pegin, toto<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [322](../standings_global.md)<br />
Regional Rank: [75]( ../standings_americas.md)<br />
Final Rank Value:  577.8<br />
<br />
Final Rank Value (577.8) = Starting Rank Value (597.8) + Head To Head Adjustments (-20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.241[<sup>1</sup>](#table2)
- Bounty Collected: 0.157[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 597.8
- 400 + ( ( 0.100 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 597.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      131 | 2024-05-02 | RJT                      | L   | 1.000      | -            | -                | -                | -             |   -18.87 | gAtito, kissmyaug, matinaso, pegin, toto |
|           10 |      137 | 2024-05-02 | KRÜ Esports              | L   | 1.000      | -            | -                | -                | -             |    -9.80 | gAtito, kissmyaug, matinaso, pegin, toto |
|            9 |      336 | 2024-04-27 | Hawks (Argentinian team) | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |     7.82 | gAtito, kissmyaug, matinaso, pegin, toto |
|            8 |      342 | 2024-04-27 | FAZ O L                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     7.79 | gAtito, kissmyaug, matinaso, pegin, toto |
|            7 |      681 | 2024-04-20 | Galorys                  | L   | 1.000      | -            | -                | -                | -             |    -5.22 | gAtito, kissmyaug, matinaso, pegin, toto |
|            6 |     4236 | 2024-01-27 | Romanticos               | L   | 0.540      | -            | -                | -                | -             |    -6.70 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            5 |     4242 | 2024-01-27 | SOLOVE                   | W   | 0.540      | 0.143        | 0.000 (0.000)    | 0.054 (0.004)    | false (0.000) |     9.46 | brokeN, doiz, farias, legy, mid1         |
|            4 |     4252 | 2024-01-27 | Yawara E-Sports          | L   | 0.539      | -            | -                | -                | -             |    -5.52 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            3 |     5434 | 2023-12-16 | CEBOLOS                  | L   | 0.260      | -            | -                | -                | -             |    -4.09 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            2 |     5444 | 2023-12-16 | Astral Aces Esports      | W   | 0.259      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | false (0.000) |     2.00 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            1 |     5455 | 2023-12-16 | O Plano B                | W   | 0.259      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | false (0.000) |     3.09 | gAtito, kissmyaug, pegin, rushardo, zLN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($112.29)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-30 |      0.560 | $131.27        | $73.47          |
| 2023-12-21 |      0.294 | $132.22        | $38.82          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
