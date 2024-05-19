### Roster Details<br />
Team Name: Young Ninjas<br />
Roster: bobeksde, jocab, MisteM, Silence, sprayxd<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [79](../standings_global.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
Final Rank Value:  895.7<br />
<br />
Final Rank Value (895.7) = Starting Rank Value (937.6) + Head To Head Adjustments (-41.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.469[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.271<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 937.6
- 400 + ( ( 0.271 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 937.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |       15 | 2024-05-05 | Team Spirit Academy | L   | 1.000      | -            | -                | -                | -         |   -25.29 | bobeksde, jocab, MisteM, Silence, sprayxd    |
|           20 |       49 | 2024-05-04 | CYBERSHOKE Esports  | L   | 1.000      | -            | -                | -                | -         |   -27.82 | bobeksde, jocab, MisteM, Silence, sprayxd    |
|           19 |      143 | 2024-05-02 | ARCRED              | W   | 1.000      | 0.371        | 0.004 (0.002)    | 0.825 (0.306)    | 0 (0.000) |    13.87 | bobeksde, jocab, MisteM, Silence, sprayxd    |
|           18 |      631 | 2024-04-21 | Nexus Gaming        | L   | 1.000      | -            | -                | -                | -         |   -16.79 | bobeksde, jocab, MisteM, Silence, xKacpersky |
|           17 |      699 | 2024-04-20 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |   -16.12 | bobeksde, jocab, MisteM, Silence, xKacpersky |
|           16 |      869 | 2024-04-18 | Nexus Gaming        | W   | 1.000      | 0.500        | 0.031 (0.016)    | 0.772 (0.386)    | 0 (0.000) |    14.00 | bobeksde, jocab, MisteM, Silence, xKacpersky |
|           15 |     1005 | 2024-04-16 | TBA.ECF             | L   | 1.000      | -            | -                | -                | -         |   -24.12 | bobeksde, jocab, MisteM, Silence, xKacpersky |
|           14 |     1038 | 2024-04-15 | LEON Esports        | W   | 1.000      | 0.371        | 0.003 (0.001)    | 0.357 (0.133)    | 0 (0.000) |     5.55 | bobeksde, jocab, MisteM, Silence, xKacpersky |
|           13 |     1064 | 2024-04-14 | LODIS               | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.139 (0.052)    | 0 (0.000) |     3.23 | bobeksde, jocab, MisteM, Silence, xKacpersky |
|           12 |     1905 | 2024-03-23 | Falcons Esport      | W   | 0.912      | 0.310        | 0.007 (0.002)    | 0.092 (0.026)    | 0 (0.000) |     5.16 | BluePho3nix, jocab, maxster, MisteM, Silence |
|           11 |     2132 | 2024-03-17 | Falcons Esport      | W   | 0.872      | 0.310        | 0.007 (0.002)    | -                | 0 (0.000) |     4.86 | BluePho3nix, jocab, maxster, MisteM, Silence |
|           10 |     2206 | 2024-03-15 | RED (German team)   | W   | 0.859      | -            | -                | -                | 0 (0.000) |     3.85 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            9 |     2284 | 2024-03-14 | Ex-sYnck            | L   | 0.850      | -            | -                | -                | -         |   -23.72 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            8 |     2464 | 2024-03-10 | 500                 | W   | 0.824      | 0.143        | -                | 0.660 (0.078)    | 0 (0.000) |     9.96 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            7 |     2510 | 2024-03-09 | GODSENT             | W   | 0.817      | 0.384        | 0.026 (0.008)    | 0.423 (0.133)    | 0 (0.000) |     6.93 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            6 |     2701 | 2024-03-05 | Fnatic              | L   | 0.791      | -            | -                | -                | -         |    -4.76 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            5 |     2706 | 2024-03-05 | Permitta Esports    | L   | 0.791      | -            | -                | -                | -         |   -12.54 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            4 |     2762 | 2024-03-04 | Aurora Gaming       | W   | 0.785      | 0.500        | 1.000 (0.392)    | 0.799 (0.313)    | 0 (0.000) |    23.66 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            3 |     2784 | 2024-03-03 | BIG                 | W   | 0.779      | 0.500        | 0.470 (0.183)    | 0.400 (0.156)    | -         |    23.04 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            2 |     2968 | 2024-02-29 | Zero Tenacity       | L   | 0.757      | -            | -                | -                | -         |   -12.52 | BluePho3nix, jocab, maxster, MisteM, Silence |
|            1 |     3756 | 2024-02-11 | EsmagaB             | W   | 0.638      | 0.143        | 0.016 (0.001)    | 0.559 (0.051)    | -         |     7.69 | BluePho3nix, jocab, maxster, MisteM, Silence |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,715.58)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.912 | $2,000.00      | $1,823.80       |
| 2024-03-05 |      0.791 | $12,500.00     | $9,891.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
