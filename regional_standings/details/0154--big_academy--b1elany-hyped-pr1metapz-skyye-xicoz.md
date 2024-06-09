### Roster Details<br />
Team Name: BIG Academy<br />
Roster: b1elany, hyped, pr1metapz, skyye, xicoz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [154](../standings_global.md)<br />
Regional Rank: [107]( ../standings_europe.md)<br />
Final Rank Value:  776.6<br />
<br />
Final Rank Value (776.6) = Starting Rank Value (737.6) + Head To Head Adjustments (39.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.313[<sup>1</sup>](#table2)
- Bounty Collected: 0.294[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 737.6
- 400 + ( ( 0.166 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 737.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     5829 | 2024-02-22 | Dynamo Eclot    | L   | 0.549      | -            | -                | -                | -         |    -2.52 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           18 |     6065 | 2024-02-18 | Team Sampi      | W   | 0.522      | 0.333        | 0.039 (0.007)    | 0.677 (0.118)    | 0 (0.000) |    12.24 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           17 |     6309 | 2024-02-14 | Sashi Esport    | W   | 0.496      | 0.333        | 0.000 (0.000)    | 0.091 (0.015)    | 0 (0.000) |     4.48 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           16 |     6500 | 2024-02-09 | Passion UA      | W   | 0.462      | 0.333        | 0.057 (0.009)    | 1.000 (0.154)    | 0 (0.000) |    11.37 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           15 |     6533 | 2024-02-08 | Betera Esports  | L   | 0.455      | -            | -                | -                | -         |    -5.67 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           14 |     6561 | 2024-02-07 | Sashi Esport    | W   | 0.449      | 0.333        | 0.154 (0.023)    | 1.000 (0.150)    | 0 (0.000) |    11.98 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           13 |     6672 | 2024-02-04 | Nexus Gaming    | W   | 0.429      | 0.333        | 0.003 (0.000)    | 0.857 (0.123)    | 0 (0.000) |     9.85 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           12 |     6768 | 2024-02-03 | Passion UA      | L   | 0.423      | -            | -                | -                | -         |    -2.41 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           11 |     7061 | 2024-01-29 | Into The Breach | L   | 0.388      | -            | -                | -                | -         |    -6.11 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           10 |     7205 | 2024-01-27 | Royalty         | W   | 0.376      | -            | -                | -                | 0 (0.000) |     1.52 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            9 |     7236 | 2024-01-26 | DAVIDHESCOBAR   | W   | 0.372      | 0.143        | 0.001 (0.000)    | 0.010 (0.001)    | 0 (0.000) |     2.71 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            8 |     7240 | 2024-01-26 | Hazeschaden     | W   | 0.372      | -            | -                | -                | 0 (0.000) |     1.53 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            7 |     7316 | 2024-01-25 | Metizport       | L   | 0.362      | -            | -                | -                | -         |    -2.62 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            6 |     8879 | 2023-12-16 | ALTERNATE aTTaX | L   | 0.097      | -            | -                | -                | -         |    -0.51 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            5 |     9108 | 2023-12-13 | RUSH B          | W   | 0.077      | 0.371        | 0.001 (0.000)    | 0.446 (0.013)    | 0 (0.000) |     1.29 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            4 |     9362 | 2023-12-08 | TSM             | W   | 0.045      | 0.371        | 0.001 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     0.52 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            3 |     9440 | 2023-12-07 | Endpoint        | W   | 0.037      | 0.371        | 0.012 (0.000)    | 0.770 (0.011)    | -         |     0.91 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            2 |     9507 | 2023-12-06 | TUSTE CHOPAKI   | W   | 0.031      | -            | -                | -                | -         |     0.17 | ArroW, hyped, MRC9, pr1metapz, skyye    |
|            1 |     9575 | 2023-12-05 | TY              | W   | 0.024      | 0.371        | 0.004 (0.000)    | 0.017 (0.000)    | -         |     0.29 | ArroW, hyped, MRC9, pr1metapz, skyye    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,900.23)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.463 | $1,000.00      | $462.78         |
| 2024-01-26 |      0.372 | $1,084.11      | $403.28         |
| 2023-12-16 |      0.097 | $5,126.50      | $495.56         |
| 2023-12-13 |      0.077 | $7,000.00      | $538.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
