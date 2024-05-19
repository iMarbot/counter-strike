### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [39](../standings_global.md)<br />
Regional Rank: [30]( ../standings_europe.md)<br />
Final Rank Value:  1145.2<br />
<br />
Final Rank Value (1145.2) = Starting Rank Value (1053.6) + Head To Head Adjustments (91.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.596[<sup>1</sup>](#table2)
- Bounty Collected: 0.483[<sup>2</sup>](#table1)
- Opponent Network: 0.128[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.329<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1053.6
- 400 + ( ( 0.329 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1053.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |       78 | 2024-05-04 | Monte                | L   | 1.000      | -            | -                | -                | -         |    -9.33 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |      135 | 2024-05-02 | GamerLegion          | L   | 1.000      | -            | -                | -                | -         |    -5.23 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           27 |      195 | 2024-05-01 | FURIA Esports        | W   | 1.000      | 0.889        | 0.384 (0.341)    | 0.361 (0.321)    | 1 (1.000) |    27.03 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           26 |      235 | 2024-04-30 | Monte                | L   | 1.000      | -            | -                | -                | -         |    -8.39 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           25 |     1138 | 2024-04-12 | BIG                  | L   | 1.000      | -            | -                | -                | -         |    -5.54 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           24 |     1183 | 2024-04-11 | Aurora Gaming        | L   | 1.000      | -            | -                | -                | -         |    -4.36 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           23 |     1215 | 2024-04-10 | TSM                  | W   | 1.000      | 0.500        | -                | 0.183 (0.091)    | 0 (0.000) |     3.28 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           22 |     1339 | 2024-04-08 | ENCE                 | W   | 1.000      | 0.687        | 0.377 (0.259)    | 0.352 (0.242)    | 0 (0.000) |    27.41 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           21 |     1737 | 2024-03-27 | 500                  | L   | 0.939      | -            | -                | -                | -         |   -22.55 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     1750 | 2024-03-27 | Team Secret          | W   | 0.938      | -            | -                | -                | 0 (0.000) |     1.97 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     1815 | 2024-03-26 | GUN5 Esports         | W   | 0.932      | -            | -                | -                | 0 (0.000) |     2.20 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     1828 | 2024-03-26 | En av de lette       | W   | 0.931      | 0.500        | 0.020 (0.009)    | -                | 0 (0.000) |     2.76 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           17 |     1867 | 2024-03-24 | BetBoom Team         | W   | 0.917      | 0.143        | 0.571 (0.075)    | 0.824 (0.108)    | 0 (0.000) |    24.39 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     1915 | 2024-03-23 | VP.Prodigy           | W   | 0.911      | 0.143        | -                | 0.762 (0.099)    | 0 (0.000) |     6.16 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     1945 | 2024-03-22 | Grannys Knockers     | W   | 0.904      | 0.143        | 0.061 (0.008)    | -                | 0 (0.000) |     7.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     1987 | 2024-03-21 | PARIVISION           | L   | 0.898      | -            | -                | -                | -         |   -21.96 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           13 |     2029 | 2024-03-20 | Natus Vincere Junior | W   | 0.891      | -            | -                | -                | 0 (0.000) |     5.37 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     2672 | 2024-03-05 | KOI                  | L   | 0.792      | -            | -                | -                | -         |   -12.85 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     2681 | 2024-03-05 | AMKAL ESPORTS        | W   | 0.792      | 0.143        | 0.209 (0.024)    | 0.756 (0.086)    | -         |    14.46 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     2698 | 2024-03-05 | 3DMAX                | W   | 0.792      | 0.143        | 0.062 (0.007)    | -                | -         |     7.85 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     2727 | 2024-03-04 | Nexus Gaming         | W   | 0.786      | 0.143        | -                | 0.772 (0.087)    | -         |     6.65 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     2827 | 2024-03-02 | Metizport            | L   | 0.773      | -            | -                | -                | -         |   -12.49 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     2861 | 2024-03-02 | RoundsGG             | W   | 0.772      | -            | -                | -                | -         |     2.43 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     2912 | 2024-03-01 | Aurora Gaming        | L   | 0.765      | -            | -                | -                | -         |    -2.15 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     2942 | 2024-02-29 | 9Pandas              | W   | 0.759      | 0.143        | 0.085 (0.009)    | 0.661 (0.072)    | -         |    14.35 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     2982 | 2024-02-28 | KOI                  | W   | 0.752      | 0.143        | 0.066 (0.007)    | -                | -         |    12.36 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     2996 | 2024-02-28 | Aurora Gaming        | W   | 0.751      | 0.143        | 1.000 (0.107)    | 0.799 (0.086)    | -         |    22.00 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     3019 | 2024-02-27 | V1dar Gaming         | W   | 0.745      | -            | -                | -                | -         |     2.61 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     3029 | 2024-02-27 | ARCRED               | W   | 0.745      | 0.143        | -                | 0.825 (0.088)    | -         |     5.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,250.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.21) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      1.000 | $26,250.00     | $26,250.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
