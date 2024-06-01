### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: BluePho3nix, jocab, MisteM, Silence, xKacpersky<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [93](../standings_global.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
Final Rank Value:  884.9<br />
<br />
Final Rank Value (884.9) = Starting Rank Value (905.1) + Head To Head Adjustments (-20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.422[<sup>1</sup>](#table2)
- Bounty Collected: 0.394[<sup>2</sup>](#table1)
- Opponent Network: 0.176[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.248<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 905.1
- 400 + ( ( 0.248 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 905.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |       85 | 2024-05-29 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -19.05 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           34 |      124 | 2024-05-28 | Preasy Esport        | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.642 (0.214)    | 0 (0.000) |     8.17 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           33 |      175 | 2024-05-27 | Monte Gen            | L   | 1.000      | -            | -                | -                | -         |   -18.18 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           32 |      211 | 2024-05-26 | Nexus Gaming         | W   | 1.000      | 0.333        | 0.014 (0.005)    | 0.825 (0.275)    | 0 (0.000) |    13.73 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           31 |      293 | 2024-05-25 | Reason Gaming        | W   | 1.000      | 0.333        | 0.004 (0.001)    | -                | 0 (0.000) |     9.99 | BluePho3nix, jocab, MisteM, Silence, xKacpersky |
|           30 |      669 | 2024-05-20 | AscendX Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.60 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           29 |     1144 | 2024-05-15 | ADEPTS               | L   | 1.000      | -            | -                | -                | -         |   -22.07 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           28 |     1248 | 2024-05-14 | Insilio              | L   | 1.000      | -            | -                | -                | -         |   -14.33 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           27 |     1277 | 2024-05-14 | HyperSpirit          | W   | 1.000      | 0.372        | 0.004 (0.001)    | 0.356 (0.133)    | 0 (0.000) |     9.94 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           26 |     1635 | 2024-05-08 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -10.55 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           25 |     2485 | 2024-04-21 | Nexus Gaming         | L   | 0.944      | -            | -                | -                | -         |   -15.43 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           24 |     2564 | 2024-04-20 | Passion UA           | L   | 0.937      | -            | -                | -                | -         |   -15.00 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           23 |     2750 | 2024-04-18 | Nexus Gaming         | W   | 0.924      | 0.500        | 0.014 (0.007)    | 0.825 (0.381)    | 0 (0.000) |    13.39 | bobeksde, jocab, MisteM, Silence, xKacpersky    |
|           22 |     2910 | 2024-04-16 | kONO.ECF             | L   | 0.910      | -            | -                | -                | -         |   -16.35 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           21 |     2945 | 2024-04-15 | LEON Esports         | W   | 0.904      | 0.372        | -                | 0.564 (0.190)    | 0 (0.000) |     6.23 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           20 |     2972 | 2024-04-14 | LODIS                | W   | 0.897      | -            | -                | -                | 0 (0.000) |     3.51 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           19 |     3996 | 2024-03-23 | Falcons Esport       | W   | 0.751      | 0.310        | 0.003 (0.001)    | -                | 0 (0.000) |     4.21 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           18 |     4255 | 2024-03-17 | Falcons Esport       | W   | 0.711      | -            | -                | -                | 0 (0.000) |     3.92 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           17 |     4365 | 2024-03-15 | ex-RED               | W   | 0.698      | -            | -                | -                | -         |     3.23 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           16 |     4446 | 2024-03-14 | ex-sYnck             | L   | 0.689      | -            | -                | -                | -         |   -16.41 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           15 |     4470 | 2024-03-13 | VENI VIDI VICI       | W   | 0.685      | -            | -                | -                | -         |     2.78 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           14 |     4667 | 2024-03-10 | 500                  | W   | 0.663      | -            | -                | -                | -         |     7.67 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           13 |     4727 | 2024-03-09 | AURA                 | W   | 0.656      | 0.384        | -                | 0.274 (0.069)    | -         |     3.82 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           12 |     4879 | 2024-03-06 | HEROIC               | L   | 0.637      | -            | -                | -                | -         |    -0.23 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           11 |     4964 | 2024-03-05 | Fnatic               | L   | 0.630      | -            | -                | -                | -         |    -5.13 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|           10 |     4970 | 2024-03-05 | Permitta Esports     | L   | 0.629      | -            | -                | -                | -         |    -9.91 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            9 |     5043 | 2024-03-04 | Aurora Gaming        | W   | 0.624      | 0.500        | 0.492 (0.153)    | 0.616 (0.192)    | -         |    18.42 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            8 |     5066 | 2024-03-03 | BIG                  | W   | 0.618      | 0.500        | 0.235 (0.073)    | 0.304 (0.094)    | -         |    18.21 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            7 |     5233 | 2024-03-01 | BLEED Esports        | L   | 0.604      | -            | -                | -                | -         |    -3.13 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            6 |     5290 | 2024-02-29 | Zero Tenacity        | L   | 0.596      | -            | -                | -                | -         |    -6.95 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            5 |     5321 | 2024-02-28 | AMKAL ESPORTS        | W   | 0.590      | 0.500        | 0.146 (0.043)    | 0.565 (0.167)    | -         |    15.40 | BluePho3nix, maxster, MisteM, REZ, Silence      |
|            4 |     5866 | 2024-02-18 | ALTERNATE aTTaX      | W   | 0.524      | 0.143        | 0.052 (0.004)    | 0.679 (0.051)    | -         |    10.10 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            3 |     6245 | 2024-02-11 | esmagaB              | W   | 0.477      | -            | -                | -                | -         |     6.13 | BluePho3nix, jocab, maxster, MisteM, Silence    |
|            2 |     6395 | 2024-02-06 | Viperio              | L   | 0.442      | -            | -                | -                | -         |   -11.69 | BluePho3nix, maxster, MisteM, Silence, spooke   |
|            1 |     6506 | 2024-02-03 | ex-Anonymo Esports   | W   | 0.424      | -            | -                | -                | -         |     3.79 | BluePho3nix, jocab, maxster, MisteM, Silence    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,786.04)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.751 | $2,000.00      | $1,501.67       |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-03-06 |      0.637 | $12,500.00     | $7,961.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
