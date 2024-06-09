### Roster Details<br />
Team Name: Nixuh<br />
Roster: Fadey, FROZ3N, kanii, RustyYG, SloWye<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [281](../standings_global.md)<br />
Regional Rank: [43]( ../standings_asia.md)<br />
Final Rank Value:  659.0<br />
<br />
Final Rank Value (659.0) = Starting Rank Value (632.0) + Head To Head Adjustments (26.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.260[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.0
- 400 + ( ( 0.114 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 632.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       48 | 2024-05-29 | Kitsune Esports    | W   | 1.000      | 0.250        | 0.001 (0.000)    | 0.072 (0.018)    | 0 (0.000) |    13.63 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           14 |     4037 | 2024-03-24 | Kitsune Esports    | W   | 0.757      | 0.250        | 0.001 (0.000)    | 0.072 (0.014)    | 0 (0.000) |    11.24 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           13 |     4183 | 2024-03-21 | Exceed             | W   | 0.738      | 0.250        | 0.000 (0.000)    | 0.084 (0.016)    | 0 (0.000) |    10.64 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           12 |     4357 | 2024-03-17 | Kitsune Esports    | L   | 0.711      | -            | -                | -                | -         |   -11.71 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           11 |     4724 | 2024-03-11 | Exceed             | W   | 0.671      | 0.250        | 0.000 (0.000)    | 0.084 (0.014)    | 0 (0.000) |     9.51 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           10 |     5085 | 2024-03-05 | ex-Adaptive Gaming | W   | 0.631      | 0.250        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     4.38 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|            9 |     7192 | 2024-01-27 | Twisted Minds      | L   | 0.377      | -            | -                | -                | -         |    -6.63 | flexeeee, FROZ3N, kanii, RustyYG, zox     |
|            8 |     7267 | 2024-01-26 | Onyx Ravens        | L   | 0.370      | -            | -                | -                | -         |    -5.89 | flexeeee, FROZ3N, kanii, RustyYG, zox     |
|            7 |     8340 | 2024-01-09 | Bravado Gaming     | L   | 0.257      | -            | -                | -                | -         |    -5.57 | Fadey, flexeeee, FROZ3N, kanii, RustyYG   |
|            6 |     8389 | 2024-01-09 | Elder Titans       | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.71 | Fadey, flexeeee, FROZ3N, kanii, RustyYG   |
|            5 |     8432 | 2024-01-08 | The Punishers      | W   | 0.251      | 0.143        | 0.000 (0.000)    | 0.064 (0.002)    | 0 (0.000) |     2.62 | Fadey, flexeeee, FROZ3N, kanii, RustyYG   |
|            4 |     8709 | 2023-12-17 | Kitsune Esports    | W   | 0.104      | 0.250        | 0.001 (0.000)    | 0.072 (0.002)    | 0 (0.000) |     1.56 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |
|            3 |     9143 | 2023-12-12 | Kitsune Esports    | W   | 0.071      | 0.250        | 0.001 (0.000)    | 0.072 (0.001)    | 0 (0.000) |     1.06 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |
|            2 |     9568 | 2023-12-05 | ATK Female         | W   | 0.024      | 0.250        | 0.005 (0.000)    | 0.138 (0.001)    | 0 (0.000) |     0.42 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |
|            1 |     9770 | 2023-12-02 | Exceed             | L   | 0.003      | -            | -                | -                | -         |    -0.05 | Fadey, flexeeee, FROZ3N, Natural, RustyYG |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($431.67)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-24 |      0.757 | $500.00        | $378.75         |
| 2023-12-17 |      0.104 | $500.00        | $52.15          |
| 2023-12-02 |      0.003 | $250.00        | $0.76           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
