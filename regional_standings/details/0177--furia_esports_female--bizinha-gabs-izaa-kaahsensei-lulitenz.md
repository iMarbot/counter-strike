### Roster Details<br />
Team Name: FURIA Esports Female<br />
Roster: bizinha, gabs, izaa, kaahSENSEI, lulitenz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [177](../standings_global.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
Final Rank Value:  749.7<br />
<br />
Final Rank Value (749.7) = Starting Rank Value (818.9) + Head To Head Adjustments (-69.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.170[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 818.9
- 400 + ( ( 0.206 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 818.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       83 | 2024-05-29 | Intense Game           | L   | 1.000      | -            | -                | -                | -         |   -14.43 | bizinha, gabs, izaa, kaahSENSEI, lulitenz |
|           23 |     2140 | 2024-04-27 | Sensei Team            | L   | 0.985      | -            | -                | -                | -         |   -17.31 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           22 |     2151 | 2024-04-27 | Atrix Esports          | W   | 0.985      | 0.143        | 0.006 (0.001)    | 0.190 (0.027)    | 0 (0.000) |    11.42 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           21 |     2171 | 2024-04-27 | Sharks Youngsters      | L   | 0.984      | -            | -                | -                | -         |   -21.88 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           20 |     2229 | 2024-04-26 | Bounty Hunters Esports | L   | 0.978      | -            | -                | -                | -         |   -22.10 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           19 |     2476 | 2024-04-21 | Fluxo Demons           | L   | 0.945      | -            | -                | -                | -         |   -11.95 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           18 |     2482 | 2024-04-21 | w7m esports Female     | W   | 0.944      | 0.333        | 0.010 (0.003)    | 0.091 (0.029)    | 1 (0.944) |     8.44 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           17 |     2673 | 2024-04-19 | Fluxo Demons           | L   | 0.931      | -            | -                | -                | -         |   -12.78 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           16 |     3154 | 2024-04-10 | Illusion               | W   | 0.871      | 0.332        | 0.003 (0.001)    | 0.028 (0.008)    | 0 (0.000) |     5.64 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           15 |     3536 | 2024-04-03 | ex-DIVINA Female       | W   | 0.825      | 0.332        | 0.004 (0.001)    | 0.053 (0.014)    | 0 (0.000) |     7.13 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           14 |     3728 | 2024-03-28 | GENKID4M4              | W   | 0.785      | 0.332        | 0.004 (0.001)    | 0.032 (0.008)    | 0 (0.000) |     6.62 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           13 |     4055 | 2024-03-21 | Atrix Esports          | W   | 0.738      | 0.332        | 0.006 (0.001)    | 0.190 (0.047)    | 0 (0.000) |     7.65 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           12 |     4301 | 2024-03-16 | GENKID4M4              | W   | 0.706      | 0.250        | 0.004 (0.001)    | -                | 0 (0.000) |     6.79 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           11 |     4463 | 2024-03-13 | MIBR Female            | W   | 0.685      | 0.332        | 0.015 (0.003)    | 0.217 (0.049)    | 0 (0.000) |     7.95 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|           10 |     4844 | 2024-03-06 | w7m esports Female     | W   | 0.638      | 0.332        | 0.010 (0.002)    | 0.091 (0.019)    | -         |     7.41 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|            9 |     5061 | 2024-03-03 | Akave Esports Female   | W   | 0.618      | -            | -                | -                | 1 (0.618) |     2.07 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|            8 |     5492 | 2024-02-24 | MIBR Female            | W   | 0.565      | 0.250        | 0.015 (0.002)    | 0.217 (0.031)    | -         |     6.94 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|            7 |     5511 | 2024-02-24 | spotlight              | L   | 0.564      | -            | -                | -                | -         |   -14.74 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|            6 |     5524 | 2024-02-24 | Salão do Corte         | L   | 0.564      | -            | -                | -                | -         |   -12.76 | bizinha, GaBi, gabs, izaa, kaahSENSEI     |
|            5 |     6807 | 2024-01-29 | Bounty Hunters Esports | L   | 0.392      | -            | -                | -                | -         |   -10.34 | annaEX, GaBi, gabs, izaa, kaahSENSEI      |
|            4 |     7080 | 2024-01-25 | MIBR Academy           | L   | 0.364      | -            | -                | -                | -         |    -7.58 | annaEX, GaBi, gabs, izaa, kaahSENSEI      |
|            3 |     9040 | 2023-12-09 | NAVI Javelins          | L   | 0.049      | -            | -                | -                | -         |    -0.86 | annaEX, GaBi, gabs, izaa, kaahSENSEI      |
|            2 |     9096 | 2023-12-08 | TSM Shimmer            | W   | 0.044      | 0.524        | -                | 0.333 (0.008)    | 1 (0.044) |     0.52 | annaEX, GaBi, gabs, izaa, kaahSENSEI      |
|            1 |     9114 | 2023-12-08 | NOFEAR5                | L   | 0.043      | -            | -                | -                | -         |    -0.97 | annaEX, GaBi, gabs, izaa, kaahSENSEI      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,484.15)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.945 | $2,500.00      | $2,363.19       |
| 2024-04-19 |      0.931 | $1,900.00      | $1,769.38       |
| 2024-03-16 |      0.706 | $750.00        | $529.31         |
| 2024-02-24 |      0.566 | $750.00        | $424.15         |
| 2023-12-10 |      0.057 | $7,000.00      | $398.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
