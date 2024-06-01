### Roster Details<br />
Team Name: Arena Jogue Fácil Esports<br />
Roster: mxa, n9xtz, pigo, r1see, urban0<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [353](../standings_global.md)<br />
Regional Rank: [88]( ../standings_americas.md)<br />
Final Rank Value:  600.7<br />
<br />
Final Rank Value (600.7) = Starting Rank Value (600.0) + Head To Head Adjustments (0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.218[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.098<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.0
- 400 + ( ( 0.098 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 600.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     7029 | 2024-01-26 | 9z Academy              | L   | 0.371      | -            | -                | -                | -         |    -4.78 | mxa, n9xtz, pigo, r1see, urban0    |
|           23 |     7171 | 2024-01-23 | paiN Gaming Academy     | L   | 0.351      | -            | -                | -                | -         |    -5.52 | mxa, n9xtz, pigo, r1see, urban0    |
|           22 |     7200 | 2024-01-22 | BESTIA                  | L   | 0.346      | -            | -                | -                | -         |    -1.39 | mxa, n9xtz, pigo, r1see, urban0    |
|           21 |     7565 | 2024-01-17 | Intense Game            | W   | 0.311      | 0.143        | 0.001 (0.000)    | 0.028 (0.001)    | 0 (0.000) |     4.83 | mxa, n9xtz, pigo, r1see, urban0    |
|           20 |     7705 | 2024-01-15 | RED Canids              | L   | 0.299      | -            | -                | -                | -         |    -0.96 | mxa, n9xtz, pigo, r1see, urban0    |
|           19 |     7918 | 2024-01-11 | Case Esports            | L   | 0.272      | -            | -                | -                | -         |    -3.35 | mxa, n9xtz, pigo, r1see, urban0    |
|           18 |     7926 | 2024-01-11 | Astral Aces Esports     | W   | 0.271      | 0.143        | 0.001 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     4.30 | mxa, n9xtz, pigo, r1see, urban0    |
|           17 |     7974 | 2024-01-10 | Opala SS                | W   | 0.266      | -            | -                | -                | 0 (0.000) |     2.01 | mxa, n9xtz, pigo, r1see, urban0    |
|           16 |     8436 | 2023-12-17 | TIMACETA                | L   | 0.105      | -            | -                | -                | -         |    -1.55 | Lineko, n9xtz, pigo, r1see, urban0 |
|           15 |     8722 | 2023-12-15 | WINDINGO                | L   | 0.092      | -            | -                | -                | -         |    -1.38 | Lineko, n9xtz, pigo, r1see, urban0 |
|           14 |     8771 | 2023-12-14 | MIBR Academy            | W   | 0.085      | 0.143        | 0.005 (0.000)    | 0.439 (0.005)    | 0 (0.000) |     1.66 | Lineko, n9xtz, pigo, r1see, urban0 |
|           13 |     8789 | 2023-12-14 | Yawara E-Sports         | W   | 0.084      | 0.143        | 0.002 (0.000)    | 0.319 (0.004)    | 0 (0.000) |     1.67 | Lineko, n9xtz, pigo, r1see, urban0 |
|           12 |     8810 | 2023-12-13 | Case Esports            | W   | 0.079      | 0.143        | 0.001 (0.000)    | 0.087 (0.001)    | 0 (0.000) |     1.50 | Lineko, n9xtz, pigo, r1see, urban0 |
|           11 |     8813 | 2023-12-13 | Corinthians Esports     | L   | 0.079      | -            | -                | -                | -         |    -1.20 | Lineko, n9xtz, pigo, r1see, urban0 |
|           10 |     8864 | 2023-12-12 | SOLOVE                  | W   | 0.072      | 0.143        | -                | 0.035 (0.000)    | 0 (0.000) |     1.16 | Lineko, n9xtz, pigo, r1see, urban0 |
|            9 |     8878 | 2023-12-12 | Team Solid              | L   | 0.071      | -            | -                | -                | -         |    -0.40 | mxa, n9xtz, pigo, r1see, urban0    |
|            8 |     8902 | 2023-12-11 | Bombril 1001 Utilidades | W   | 0.065      | 0.143        | 0.001 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     1.08 | Lineko, n9xtz, pigo, r1see, urban0 |
|            7 |     8919 | 2023-12-11 | SOLOVE                  | W   | 0.064      | 0.262        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     1.04 | mxa, n9xtz, pigo, r1see, urban0    |
|            6 |     9097 | 2023-12-08 | CEBOLOS                 | W   | 0.044      | 0.262        | 0.000 (0.000)    | -                | 0 (0.000) |     0.66 | mxa, n9xtz, pigo, r1see, urban0    |
|            5 |     9160 | 2023-12-07 | Martians                | W   | 0.037      | -            | -                | -                | -         |     0.29 | mxa, n9xtz, pigo, r1see, urban0    |
|            4 |     9204 | 2023-12-06 | Team Solid              | L   | 0.033      | -            | -                | -                | -         |    -0.18 | Lineko, n9xtz, pigo, r1see, urban0 |
|            3 |     9209 | 2023-12-06 | w7m esports             | W   | 0.031      | 0.143        | 0.003 (0.000)    | 0.259 (0.001)    | -         |     0.71 | Lineko, n9xtz, pigo, r1see, urban0 |
|            2 |     9284 | 2023-12-05 | WINDINGO                | W   | 0.024      | 0.143        | 0.001 (0.000)    | -                | -         |     0.41 | Lineko, n9xtz, pigo, r1see, urban0 |
|            1 |     9460 | 2023-12-02 | 9z Academy              | W   | 0.004      | 0.143        | -                | 0.311 (0.000)    | -         |     0.08 | mxa, n9xtz, pigo, r1see, urban0    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($76.54)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-20 |      0.125 | $133.52        | $16.75          |
| 2023-12-18 |      0.110 | $544.93        | $59.79          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
