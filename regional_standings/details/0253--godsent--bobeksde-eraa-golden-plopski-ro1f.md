### Roster Details<br />
Team Name: GODSENT<br />
Roster: bobeksde, eraa, Golden, Plopski, Ro1f<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [253](../standings_global.md)<br />
Regional Rank: [166]( ../standings_europe.md)<br />
Final Rank Value:  683.8<br />
<br />
Final Rank Value (683.8) = Starting Rank Value (664.7) + Head To Head Adjustments (19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.253[<sup>1</sup>](#table2)
- Bounty Collected: 0.244[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.130<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 664.7
- 400 + ( ( 0.130 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 664.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     6541 | 2024-02-07 | Rhyno Esports             | W   | 0.451      | 0.371        | 0.029 (0.005)    | 0.567 (0.095)    | 0 (0.000) |    12.35 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           23 |     6599 | 2024-02-05 | Golden Sword              | W   | 0.438      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.42 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           22 |     6954 | 2024-01-31 | TSM                       | L   | 0.402      | -            | -                | -                | -         |    -4.89 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           21 |     6989 | 2024-01-30 | 500                       | W   | 0.396      | 0.384        | 0.002 (0.000)    | 0.479 (0.073)    | 0 (0.000) |     8.53 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           20 |     6999 | 2024-01-29 | Permitta Esports          | L   | 0.392      | -            | -                | -                | -         |    -2.05 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           19 |     7013 | 2024-01-29 | DUSTY                     | W   | 0.392      | 0.143        | 0.006 (0.000)    | 0.148 (0.008)    | 0 (0.000) |     7.40 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           18 |     7209 | 2024-01-27 | SINNERS Esports           | L   | 0.376      | -            | -                | -                | -         |    -1.34 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           17 |     7304 | 2024-01-25 | BAKS Esports              | W   | 0.364      | 0.371        | 0.001 (0.000)    | 0.171 (0.023)    | 0 (0.000) |     5.38 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           16 |     7350 | 2024-01-24 | ex-K10                    | L   | 0.357      | -            | -                | -                | -         |    -2.68 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           15 |     7358 | 2024-01-24 | Nemiga Gaming             | L   | 0.357      | -            | -                | -                | -         |    -0.42 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           14 |     7432 | 2024-01-23 | TSM                       | W   | 0.348      | 0.371        | 0.011 (0.001)    | 0.170 (0.022)    | 0 (0.000) |     7.04 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           13 |     7774 | 2024-01-17 | FreeESPI                  | L   | 0.312      | -            | -                | -                | -         |    -5.60 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           12 |     7787 | 2024-01-17 | LODIS                     | W   | 0.311      | 0.143        | 0.001 (0.000)    | 0.140 (0.006)    | 0 (0.000) |     4.82 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           11 |     8115 | 2024-01-12 | ex-Turów Zgorzelec Esport | L   | 0.278      | -            | -                | -                | -         |    -2.83 | bobeksde, eraa, Golden, Plopski, Ro1f |
|           10 |     8253 | 2024-01-10 | IKLA                      | L   | 0.265      | -            | -                | -                | -         |    -5.17 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            9 |     8281 | 2024-01-10 | klivervi                  | W   | 0.265      | -            | -                | -                | 0 (0.000) |     1.58 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            8 |     8363 | 2024-01-09 | underrated                | L   | 0.257      | -            | -                | -                | -         |    -5.96 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            7 |     9206 | 2023-12-11 | ex-Preasy Esport          | L   | 0.062      | -            | -                | -                | -         |    -0.39 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            6 |     9246 | 2023-12-10 | ALTERNATE aTTaX           | L   | 0.056      | -            | -                | -                | -         |    -0.20 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            5 |     9398 | 2023-12-08 | ex-Preasy Esport          | W   | 0.042      | 0.371        | 0.052 (0.001)    | 0.381 (0.006)    | 0 (0.000) |     1.05 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            4 |     9576 | 2023-12-05 | ex-Anonymo Esports        | L   | 0.024      | -            | -                | -                | -         |    -0.34 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            3 |     9599 | 2023-12-05 | TSM                       | W   | 0.022      | 0.371        | 0.001 (0.000)    | 0.010 (0.000)    | -         |     0.33 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            2 |     9638 | 2023-12-03 | EYEBALLERS                | L   | 0.011      | -            | -                | -                | -         |    -0.07 | bobeksde, eraa, Golden, Plopski, Ro1f |
|            1 |     9746 | 2023-12-02 | Ninjas in Pyjamas         | W   | 0.004      | 0.143        | 0.011 (0.000)    | 0.027 (0.000)    | 1 (0.004) |     0.08 | bobeksde, eraa, Golden, Plopski, Ro1f |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($341.48)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-12 |      0.070 | $3,000.00      | $210.00         |
| 2023-12-03 |      0.011 | $11,982.61     | $131.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
