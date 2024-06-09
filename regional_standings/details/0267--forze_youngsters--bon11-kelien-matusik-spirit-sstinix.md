### Roster Details<br />
Team Name: FORZE Youngsters<br />
Roster: boN11, kelieN, matusik, spirit, sstiNiX<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [267](../standings_global.md)<br />
Regional Rank: [171]( ../standings_europe.md)<br />
Final Rank Value:  672.6<br />
<br />
Final Rank Value (672.6) = Starting Rank Value (656.2) + Head To Head Adjustments (16.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.223[<sup>2</sup>](#table1)
- Opponent Network: 0.040[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.2
- 400 + ( ( 0.126 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 656.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     4833 | 2024-03-09 | ARCRED               | L   | 0.657      | -            | -                | -                | -         |    -7.03 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           22 |     5105 | 2024-03-05 | VP.Prodigy           | L   | 0.631      | -            | -                | -                | -         |    -5.19 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           21 |     5400 | 2024-02-29 | NOM Esports          | L   | 0.598      | -            | -                | -                | -         |   -10.20 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           20 |     5773 | 2024-02-23 | Insilio              | L   | 0.557      | -            | -                | -                | -         |    -3.47 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           19 |     5993 | 2024-02-19 | Aurora Young Blud    | W   | 0.531      | 0.371        | 0.008 (0.002)    | 0.506 (0.100)    | 0 (0.000) |    10.63 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           18 |     6000 | 2024-02-19 | Nemiga Gaming        | L   | 0.531      | -            | -                | -                | -         |    -0.69 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           17 |     6161 | 2024-02-16 | VaselineWorms        | W   | 0.510      | 0.371        | 0.000 (0.000)    | 0.418 (0.079)    | 0 (0.000) |     8.72 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           16 |     6224 | 2024-02-15 | ILIN                 | L   | 0.504      | -            | -                | -                | -         |   -10.81 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           15 |     6333 | 2024-02-13 | ex-Hot Headed Gaming | W   | 0.491      | 0.371        | 0.000 (0.000)    | 0.086 (0.016)    | 0 (0.000) |     4.04 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           14 |     6378 | 2024-02-12 | AURA                 | W   | 0.484      | 0.371        | 0.000 (0.000)    | 0.274 (0.049)    | 0 (0.000) |     6.66 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           13 |     6543 | 2024-02-07 | 0to100               | W   | 0.451      | 0.371        | 0.000 (0.000)    | 0.012 (0.002)    | 0 (0.000) |     3.50 | kelieN, matusik, spirit, sstiNiX, yoshi   |
|           12 |     7160 | 2024-01-27 | Grannys Knockers     | W   | 0.378      | 0.371        | 0.006 (0.001)    | 0.517 (0.073)    | 0 (0.000) |     8.06 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           11 |     7175 | 2024-01-27 | 1win                 | L   | 0.377      | -            | -                | -                | -         |    -1.82 | boN11, kelieN, matusik, spirit, sstiNiX   |
|           10 |     7355 | 2024-01-24 | GUN5 Esports         | W   | 0.357      | 0.371        | -                | 0.058 (0.008)    | 0 (0.000) |     3.80 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            9 |     7455 | 2024-01-22 | Lilmix               | W   | 0.344      | 0.371        | 0.006 (0.001)    | 0.593 (0.076)    | 0 (0.000) |     8.40 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            8 |     7472 | 2024-01-22 | Sashi Esport         | L   | 0.344      | -            | -                | -                | -         |    -1.13 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            7 |     8707 | 2023-12-17 | Kova Gaming          | W   | 0.104      | 0.310        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     1.38 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            6 |     8739 | 2023-12-17 | TOR                  | L   | 0.103      | -            | -                | -                | -         |    -0.96 | boN11, gooddeph, matusik, spirit, sstiNiX |
|            5 |     8888 | 2023-12-16 | Insilio              | L   | 0.096      | -            | -                | -                | -         |    -0.64 | boN11, gooddeph, matusik, spirit, sstiNiX |
|            4 |     8910 | 2023-12-16 | Griefers             | W   | 0.095      | -            | -                | -                | 0 (0.000) |     0.57 | boN11, gooddeph, matusik, spirit, sstiNiX |
|            3 |     8993 | 2023-12-15 | Kova Gaming          | W   | 0.091      | 0.310        | 0.000 (0.000)    | -                | -         |     1.20 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            2 |     9141 | 2023-12-12 | AKA HERO             | W   | 0.071      | 0.310        | 0.001 (0.000)    | 0.100 (0.002)    | -         |     0.99 | boN11, kelieN, matusik, spirit, sstiNiX   |
|            1 |     9220 | 2023-12-10 | Desperados           | W   | 0.058      | -            | -                | -                | -         |     0.35 | boN11, kelieN, matusik, spirit, sstiNiX   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($208.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
