### Roster Details<br />
Team Name: GTZ.ESPORTS<br />
Roster: brA, c0mplex, Jayy2s, M1KA, MattyMyimb<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [360](../standings_global.md)<br />
Regional Rank: [226]( ../standings_europe.md)<br />
Final Rank Value:  391.6<br />
<br />
Final Rank Value (391.6) = Starting Rank Value (400.9) + Head To Head Adjustments (-9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.9
- 400 + ( ( 0.000 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 400.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       51 | 2024-05-04 | AL-QATRAO                        | L   | 1.000      | -            | -                | -                | -             |    -4.10 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            9 |       69 | 2024-05-04 | The Agency Clan                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |    16.08 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            8 |       95 | 2024-05-03 | Strike Force                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |    16.65 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            7 |      733 | 2024-04-20 | Strike Force                     | L   | 1.000      | -            | -                | -                | -             |   -14.09 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            6 |     2119 | 2024-03-17 | Coolermaster                     | L   | 0.872      | -            | -                | -                | -             |   -12.87 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            5 |     3235 | 2024-02-22 | Enigma Esports (Portuguese team) | L   | 0.712      | -            | -                | -                | -             |   -10.88 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            4 |     3297 | 2024-02-21 | ABT Esports                      | W   | 0.705      | 0.143        | 0.000 (0.000)    | 0.137 (0.014)    | false (0.000) |    14.36 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            3 |     3346 | 2024-02-20 | AL-QATRAO                        | L   | 0.698      | -            | -                | -                | -             |    -3.31 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            2 |     4220 | 2024-01-28 | Qlimax                           | L   | 0.544      | -            | -                | -                | -             |    -8.41 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |
|            1 |     4277 | 2024-01-27 | AL-QATRAO                        | L   | 0.538      | -            | -                | -                | -             |    -2.82 | brA, c0mplex, Jayy2s, M1KA, MattyMyimb |

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
