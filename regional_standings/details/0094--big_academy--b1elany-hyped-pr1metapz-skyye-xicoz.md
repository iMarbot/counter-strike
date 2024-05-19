### Roster Details<br />
Team Name: BIG Academy<br />
Roster: b1elany, hyped, pr1metapz, skyye, xicoz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [94](../standings_global.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
Final Rank Value:  870.8<br />
<br />
Final Rank Value (870.8) = Starting Rank Value (809.4) + Head To Head Adjustments (61.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.340[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 809.4
- 400 + ( ( 0.206 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 809.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |     3264 | 2024-02-22 | Dynamo Eclot          | L   | 0.710      | -            | -                | -                | -             |    -4.07 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           30 |     3464 | 2024-02-18 | Team Sampi            | W   | 0.683      | 0.333        | 0.108 (0.025)    | 0.709 (0.161)    | false (0.000) |    14.93 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           29 |     3653 | 2024-02-14 | Sashi Esport          | W   | 0.657      | 0.333        | 0.055 (0.012)    | 0.256 (0.056)    | false (0.000) |     9.33 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           28 |     3803 | 2024-02-09 | Passion UA            | W   | 0.623      | 0.333        | 0.114 (0.024)    | 0.980 (0.203)    | false (0.000) |    12.84 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           27 |     3832 | 2024-02-08 | Betera Esports        | L   | 0.616      | -            | -                | -                | -             |   -10.07 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           26 |     3849 | 2024-02-07 | Sashi Esport          | W   | 0.610      | 0.333        | 0.193 (0.039)    | 1.000 (0.203)    | false (0.000) |    14.74 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           25 |     3928 | 2024-02-04 | Nexus Gaming          | W   | 0.591      | 0.333        | 0.031 (0.006)    | 0.772 (0.152)    | false (0.000) |    11.62 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           24 |     3996 | 2024-02-03 | Passion UA            | L   | 0.584      | -            | -                | -                | -             |    -5.36 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           23 |     4204 | 2024-01-29 | Into The Breach       | L   | 0.549      | -            | -                | -                | -             |    -8.68 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           22 |     4284 | 2024-01-27 | Royalty               | W   | 0.537      | -            | -                | -                | false (0.000) |     1.36 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           21 |     4303 | 2024-01-26 | Hazeschaden           | W   | 0.533      | -            | -                | -                | false (0.000) |     1.36 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           20 |     4360 | 2024-01-25 | Metizport             | L   | 0.523      | -            | -                | -                | -             |    -5.07 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           19 |     5479 | 2023-12-16 | ALTERNATE aTTaX       | L   | 0.258      | -            | -                | -                | -             |    -1.78 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           18 |     5650 | 2023-12-13 | RUSH B (Russian team) | W   | 0.238      | 0.371        | -                | 0.471 (0.042)    | false (0.000) |     3.31 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           17 |     5828 | 2023-12-08 | TSM                   | W   | 0.206      | -            | -                | -                | false (0.000) |     2.25 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           16 |     5884 | 2023-12-07 | Endpoint              | W   | 0.199      | 0.371        | -                | 0.785 (0.058)    | false (0.000) |     3.36 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           15 |     5934 | 2023-12-06 | TUSTE CHOPAKI         | W   | 0.192      | -            | -                | -                | -             |     0.81 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           14 |     5983 | 2023-12-05 | TY                    | W   | 0.185      | -            | -                | -                | -             |     1.83 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           13 |     6197 | 2023-11-30 | Verdant               | W   | 0.152      | 0.371        | 0.027 (0.002)    | 0.662 (0.037)    | -             |     3.49 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           12 |     6205 | 2023-11-30 | Nexus Gaming          | W   | 0.152      | 0.371        | 0.031 (0.002)    | 0.772 (0.043)    | -             |     3.19 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           11 |     6212 | 2023-11-30 | For The Win Esports   | W   | 0.151      | -            | -                | -                | -             |     1.51 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|           10 |     6427 | 2023-11-25 | ALTERNATE aTTaX       | W   | 0.118      | 0.143        | 0.110 (0.002)    | 0.723 (0.012)    | -             |     3.03 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            9 |     6552 | 2023-11-22 | The Witchers          | W   | 0.099      | 0.371        | 0.035 (0.001)    | -                | -             |     1.42 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            8 |     6568 | 2023-11-22 | Los Alpacas           | W   | 0.098      | -            | -                | -                | -             |     0.83 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            7 |     6623 | 2023-11-20 | ALTERNATE aTTaX       | W   | 0.086      | 0.143        | 0.110 (0.001)    | -                | -             |     2.22 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            6 |     6725 | 2023-11-18 | THE SUSPECT           | W   | 0.071      | -            | -                | -                | -             |     0.69 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            5 |     6730 | 2023-11-18 | AEX-1                 | W   | 0.071      | -            | -                | -                | -             |     0.55 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            4 |     6740 | 2023-11-18 | RED (German team)     | W   | 0.070      | -            | -                | -                | -             |     0.55 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            3 |     6760 | 2023-11-17 | BobRoss               | W   | 0.066      | -            | -                | -                | -             |     0.32 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            2 |     6887 | 2023-11-15 | CYBERSHOKE Esports    | W   | 0.051      | -            | -                | -                | -             |     0.66 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            1 |     7005 | 2023-11-12 | Lemondogs             | W   | 0.031      | -            | -                | -                | -             |     0.21 | ArroW, hyped, MRC9, pr1metapz, skyye    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,260.16)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.624 | $1,000.00      | $623.84         |
| 2024-01-26 |      0.533 | $1,084.11      | $577.57         |
| 2023-12-16 |      0.258 | $5,126.50      | $1,321.26       |
| 2023-12-13 |      0.238 | $7,000.00      | $1,666.06       |
| 2023-11-17 |      0.066 | $1,084.95      | $71.43          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
