### Roster Details<br />
Team Name: BIG Academy<br />
Roster: b1elany, hyped, pr1metapz, skyye, xicoz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [170](../standings_global.md)<br />
Regional Rank: [117]( ../standings_europe.md)<br />
Final Rank Value:  759.3<br />
<br />
Final Rank Value (759.3) = Starting Rank Value (723.1) + Head To Head Adjustments (36.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.159<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 723.1
- 400 + ( ( 0.159 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 723.1


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
|           12 |     5668 | 2024-02-22 | Dynamo Eclot    | L   | 0.549      | -            | -                | -                | -         |    -2.36 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           11 |     5892 | 2024-02-18 | Team Sampi      | W   | 0.522      | 0.333        | 0.039 (0.007)    | 0.665 (0.116)    | 0 (0.000) |    12.42 | b1elany, hyped, pr1metapz, skyye, xicoz |
|           10 |     6128 | 2024-02-14 | Sashi Esport    | W   | 0.496      | 0.333        | 0.000 (0.000)    | 0.091 (0.015)    | 0 (0.000) |     4.79 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            9 |     6312 | 2024-02-09 | Passion UA      | W   | 0.462      | 0.333        | 0.057 (0.009)    | 1.000 (0.154)    | 0 (0.000) |    11.51 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            8 |     6345 | 2024-02-08 | Betera Esports  | L   | 0.455      | -            | -                | -                | -         |    -5.35 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            7 |     6367 | 2024-02-07 | Sashi Esport    | W   | 0.449      | 0.333        | 0.172 (0.026)    | 1.000 (0.150)    | 0 (0.000) |    12.21 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            6 |     6469 | 2024-02-04 | Nexus Gaming    | W   | 0.429      | 0.333        | 0.014 (0.002)    | 0.825 (0.118)    | 0 (0.000) |    10.22 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            5 |     6565 | 2024-02-03 | Passion UA      | L   | 0.423      | -            | -                | -                | -         |    -2.30 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            4 |     6844 | 2024-01-29 | Into The Breach | L   | 0.388      | -            | -                | -                | -         |    -5.79 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            3 |     6985 | 2024-01-27 | Royalty         | W   | 0.376      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.67 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            2 |     7018 | 2024-01-26 | Hazeschaden     | W   | 0.372      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.66 | b1elany, hyped, pr1metapz, skyye, xicoz |
|            1 |     7087 | 2024-01-25 | Metizport       | L   | 0.362      | -            | -                | -                | -         |    -2.46 | b1elany, hyped, pr1metapz, skyye, xicoz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($865.73)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-09 |      0.463 | $1,000.00      | $462.78         |
| 2024-01-26 |      0.372 | $1,084.11      | $402.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
