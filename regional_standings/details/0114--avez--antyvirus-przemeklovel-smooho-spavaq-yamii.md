### Roster Details<br />
Team Name: AVEZ<br />
Roster: AntyVirus, przemeklovel, smooho, SpavaQ, Yamii<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [114](../standings_global.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
Final Rank Value:  845.1<br />
<br />
Final Rank Value (845.1) = Starting Rank Value (843.8) + Head To Head Adjustments (1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.218<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 843.8
- 400 + ( ( 0.218 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 843.8


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
|           20 |       54 | 2024-05-29 | Cerberus eSports     | W   | 1.000      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.72 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           19 |     1416 | 2024-05-11 | Team LRP Poland      | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.056 (0.008)    | 1 (1.000) |    10.51 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           18 |     1462 | 2024-05-11 | akceptuj             | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.028 (0.004)    | 1 (1.000) |     8.66 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           17 |     1468 | 2024-05-11 | Team LRP Poland      | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.056 (0.008)    | 1 (1.000) |    10.79 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           16 |     2711 | 2024-04-19 | ThunderFlash         | L   | 0.929      | -            | -                | -                | -         |   -14.26 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           15 |     2954 | 2024-04-15 | M1 Gaming            | W   | 0.903      | 0.143        | 0.001 (0.000)    | 0.024 (0.003)    | 0 (0.000) |     6.65 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           14 |     3070 | 2024-04-12 | brazylijski luz      | W   | 0.884      | 0.143        | 0.013 (0.002)    | 0.490 (0.062)    | 0 (0.000) |    12.98 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           13 |     3116 | 2024-04-11 | 9INE                 | W   | 0.877      | 0.143        | 0.002 (0.000)    | 0.092 (0.012)    | 0 (0.000) |     8.80 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           12 |     3184 | 2024-04-10 | DEEZ NUTS            | W   | 0.870      | 0.143        | 0.002 (0.000)    | 0.077 (0.010)    | 0 (0.000) |     7.97 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           11 |     3230 | 2024-04-09 | Permitta Esports     | L   | 0.864      | -            | -                | -                | -         |    -8.58 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           10 |     4755 | 2024-03-08 | GamerLegion Academy  | L   | 0.650      | -            | -                | -                | -         |   -10.00 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|            9 |     4819 | 2024-03-07 | FAVBET Team          | L   | 0.643      | -            | -                | -                | -         |    -7.98 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|            8 |     5515 | 2024-02-24 | KOMNATA              | L   | 0.564      | -            | -                | -                | -         |   -12.89 | hotd0g, jcobbb, killkapi, misho, nawrot         |
|            7 |     6688 | 2024-02-01 | EXO Clan             | L   | 0.409      | -            | -                | -                | -         |    -3.91 | Adam9130, AwaykeN, bevve, dobbo, Duplicate      |
|            6 |     6766 | 2024-01-30 | Natus Vincere Junior | W   | 0.397      | 0.289        | 0.006 (0.001)    | 0.422 (0.048)    | 0 (0.000) |     5.10 | cmtry, dziugss, froz1k, qzr, UNBR0KEN           |
|            5 |     6834 | 2024-01-29 | Sashi Academy        | L   | 0.391      | -            | -                | -                | -         |    -9.01 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            4 |     7124 | 2024-01-24 | Begrip Gaming        | W   | 0.357      | 0.289        | 0.000 (0.000)    | 0.317 (0.033)    | 0 (0.000) |     2.51 | Ariant0, Karma, Reedz, shateri, titulus         |
|            3 |     7349 | 2024-01-20 | ex-KRC Genk Esports  | L   | 0.330      | -            | -                | -                | -         |    -7.81 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            2 |     7684 | 2024-01-16 | Young Gods           | W   | 0.304      | 0.289        | -                | 0.240 (0.021)    | -         |     1.43 | Cham, Focus, MaiL09, viz, Wonder                |
|            1 |     8352 | 2023-12-22 | monaco               | L   | 0.138      | -            | -                | -                | -         |    -3.43 | daph, darknesszz, diis6, redzy, xype            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,776.68)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-11 |      1.000 | $750.86        | $750.86         |
| 2024-04-21 |      0.943 | $739.38        | $697.48         |
| 2024-03-09 |      0.657 | $500.00        | $328.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
