### Roster Details<br />
Team Name: TeamOrangeGaming<br />
Roster: BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [137](../standings_global.md)<br />
Regional Rank: [96]( ../standings_europe.md)<br />
Final Rank Value:  798.2<br />
<br />
Final Rank Value (798.2) = Starting Rank Value (793.1) + Head To Head Adjustments (5.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.027[<sup>2</sup>](#table1)
- LAN Wins: 0.208[<sup>2</sup>](#table1)

The average of these factors is 0.193<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 793.1
- 400 + ( ( 0.193 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 793.1


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
|           28 |      263 | 2024-05-25 | ALTERNATE aTTaX     | L   | 1.000      | -            | -                | -                | -         |   -11.86 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           27 |      658 | 2024-05-20 | EVOPLAY             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.80 | BingBong, edox, kinQ, Pictrucz, Spidergum    |
|           26 |     1139 | 2024-05-15 | SNOGARD Dragons     | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.137 (0.020)    | 0 (0.000) |    13.25 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           25 |     2072 | 2024-04-29 | Sissi State Punks   | W   | 0.997      | 0.143        | 0.004 (0.001)    | 0.226 (0.032)    | 0 (0.000) |    10.45 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           24 |     2173 | 2024-04-27 | ALTERNATE aTTaX Evo | W   | 0.984      | 0.143        | 0.002 (0.000)    | 0.239 (0.034)    | 1 (0.984) |    12.10 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           23 |     2189 | 2024-04-27 | Sissi State Punks   | W   | 0.983      | 0.143        | 0.004 (0.001)    | 0.226 (0.032)    | 1 (0.983) |    11.67 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           22 |     2441 | 2024-04-22 | mYinsanity          | W   | 0.951      | 0.143        | 0.001 (0.000)    | 0.124 (0.017)    | 0 (0.000) |    10.28 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           21 |     2841 | 2024-04-17 | ALTERNATE aTTaX     | L   | 0.917      | -            | -                | -                | -         |    -7.26 | BingBong, edox, kinQ, Pictrucz, Spidergum    |
|           20 |     3290 | 2024-04-08 | ARROW               | L   | 0.857      | -            | -                | -                | -         |   -14.86 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           19 |     3377 | 2024-04-06 | eSports Cologne     | W   | 0.843      | -            | -                | -                | 0 (0.000) |     5.07 | Cl0uTz, edox, kinQ, Pictrucz, xTreMe         |
|           18 |     3430 | 2024-04-05 | Pandaric eSports    | W   | 0.839      | -            | -                | -                | 0 (0.000) |     5.25 | Cl0uTz, edox, kinQ, Pictrucz, xTreMe         |
|           17 |     3625 | 2024-04-01 | Wave Esports        | W   | 0.810      | -            | -                | -                | 0 (0.000) |     7.32 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|           16 |     4321 | 2024-03-16 | SNOGARD Dragons     | L   | 0.704      | -            | -                | -                | -         |   -11.81 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|           15 |     4430 | 2024-03-14 | ARROW               | L   | 0.691      | -            | -                | -                | -         |   -11.53 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|           14 |     4589 | 2024-03-11 | GameAgents          | L   | 0.671      | -            | -                | -                | -         |   -17.15 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|           13 |     4797 | 2024-03-07 | Donstu Esports      | L   | 0.645      | -            | -                | -                | -         |   -16.58 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|           12 |     4818 | 2024-03-07 | SINNERS Academy     | W   | 0.643      | 0.333        | 0.001 (0.000)    | 0.227 (0.049)    | 0 (0.000) |     5.71 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|           11 |     4845 | 2024-03-06 | ALTERNATE aTTaX Evo | W   | 0.638      | 0.143        | 0.002 (0.000)    | 0.239 (0.022)    | -         |     7.86 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|           10 |     4875 | 2024-03-06 | Sissi State Punks   | W   | 0.637      | 0.143        | 0.004 (0.000)    | 0.226 (0.021)    | -         |     6.38 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|            9 |     5025 | 2024-03-04 | SNOGARD Dragons     | L   | 0.625      | -            | -                | -                | -         |   -11.47 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|            8 |     5076 | 2024-03-03 | Sissi State Punks   | W   | 0.618      | 0.143        | 0.004 (0.000)    | 0.226 (0.020)    | -         |     6.21 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|            7 |     5298 | 2024-02-28 | ALTERNATE aTTaX Evo | W   | 0.591      | 0.143        | 0.002 (0.000)    | 0.239 (0.020)    | -         |     7.16 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|            6 |     6413 | 2024-02-05 | EPIC DUDES          | L   | 0.438      | -            | -                | -                | -         |   -11.69 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|            5 |     6833 | 2024-01-29 | Wave Esports        | W   | 0.391      | -            | -                | -                | -         |     3.48 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|            4 |     6934 | 2024-01-27 | OTHERSCANTBEAT      | W   | 0.378      | -            | -                | -                | -         |     1.19 | BingBong, Cl0uTz, kinQ, Pictrucz, Spidergum  |
|            3 |     8953 | 2023-12-10 | mYinsanity          | L   | 0.058      | -            | -                | -                | -         |    -1.30 | BingBong, bLESSED, kinQ, Pictrucz, Spidergum |
|            2 |     9027 | 2023-12-09 | Wave Esports        | W   | 0.050      | -            | -                | -                | -         |     0.25 | BingBong, bLESSED, kinQ, Pictrucz, Spidergum |
|            1 |     9093 | 2023-12-08 | EPIC DUDES          | W   | 0.045      | -            | -                | -                | -         |     0.14 | BingBong, bLESSED, kinQ, Pictrucz, Spidergum |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,874.26)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-25 |      1.000 | $271.41        | $271.41         |
| 2024-04-27 |      0.984 | $1,070.26      | $1,052.87       |
| 2024-03-17 |      0.710 | $544.93        | $386.69         |
| 2024-03-06 |      0.638 | $216.89        | $138.39         |
| 2023-12-10 |      0.058 | $430.94        | $24.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
