### Roster Details<br />
Team Name: Nixuh<br />
Roster: Fadey, FROZ3N, kanii, RustyYG, SloWye<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [241](../standings_global.md)<br />
Regional Rank: [43]( ../standings_asia.md)<br />
Final Rank Value:  672.5<br />
<br />
Final Rank Value (672.5) = Starting Rank Value (657.0) + Head To Head Adjustments (15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 657.0
- 400 + ( ( 0.130 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 657.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     1858 | 2024-03-24 | Kitsune Esports | W   | 0.919      | 0.250        | 0.002 (0.000)    | 0.097 (0.022)    | 0 (0.000) |    12.95 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           13 |     1978 | 2024-03-21 | Monarch Realm   | W   | 0.899      | 0.250        | 0.002 (0.000)    | 0.095 (0.021)    | 0 (0.000) |    12.96 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           12 |     2129 | 2024-03-17 | Kitsune Esports | L   | 0.872      | -            | -                | -                | -         |   -14.87 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           11 |     2409 | 2024-03-11 | Monarch Realm   | W   | 0.832      | 0.250        | 0.002 (0.000)    | 0.095 (0.020)    | 0 (0.000) |    11.80 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|           10 |     2682 | 2024-03-05 | Adaptive Gaming | W   | 0.792      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.94 | Fadey, FROZ3N, kanii, RustyYG, SloWye     |
|            9 |     4273 | 2024-01-27 | Twisted Minds   | L   | 0.538      | -            | -                | -                | -         |    -9.49 | flexeeee, FROZ3N, kanii, RustyYG, zox     |
|            8 |     4323 | 2024-01-26 | Onyx Ravens     | L   | 0.531      | -            | -                | -                | -         |    -7.76 | flexeeee, FROZ3N, kanii, RustyYG, zox     |
|            7 |     5091 | 2024-01-09 | Bravado Gaming  | L   | 0.418      | -            | -                | -                | -         |    -7.62 | Fadey, flexeeee, FROZ3N, kanii, RustyYG   |
|            6 |     5151 | 2024-01-08 | The Punishers   | W   | 0.412      | 0.143        | 0.001 (0.000)    | 0.058 (0.003)    | 0 (0.000) |     3.92 | Fadey, flexeeee, FROZ3N, kanii, RustyYG   |
|            5 |     5352 | 2023-12-17 | Kitsune Esports | W   | 0.265      | 0.250        | 0.002 (0.000)    | 0.097 (0.006)    | 0 (0.000) |     3.84 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |
|            4 |     5669 | 2023-12-12 | Kitsune Esports | W   | 0.232      | 0.250        | 0.002 (0.000)    | 0.097 (0.006)    | 0 (0.000) |     3.40 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |
|            3 |     5981 | 2023-12-05 | ATK Female      | W   | 0.185      | 0.250        | 0.011 (0.001)    | 0.201 (0.009)    | 0 (0.000) |     3.25 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |
|            2 |     6120 | 2023-12-02 | Monarch Realm   | L   | 0.164      | -            | -                | -                | -         |    -2.84 | Fadey, flexeeee, FROZ3N, Natural, RustyYG |
|            1 |     6721 | 2023-11-18 | Bravado Gaming  | W   | 0.071      | 0.250        | 0.000 (0.000)    | 0.048 (0.001)    | 0 (0.000) |     0.93 | bLazE, Fadey, flexeeee, FROZ3N, RustyYG   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($686.35)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-24 |      0.919 | $500.00        | $459.28         |
| 2023-12-17 |      0.265 | $500.00        | $132.69         |
| 2023-12-02 |      0.164 | $250.00        | $41.03          |
| 2023-11-18 |      0.071 | $750.00        | $53.35          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
