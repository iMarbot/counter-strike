### Roster Details<br />
Team Name: AVEZ<br />
Roster: AntyVirus, przemeklovel, smooho, SpavaQ, Yamii<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [98](../standings_global.md)<br />
Regional Rank: [69]( ../standings_europe.md)<br />
Final Rank Value:  873.2<br />
<br />
Final Rank Value (873.2) = Starting Rank Value (866.6) + Head To Head Adjustments (6.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.310[<sup>1</sup>](#table2)
- Bounty Collected: 0.246[<sup>2</sup>](#table1)
- Opponent Network: 0.046[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 866.6
- 400 + ( ( 0.230 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 866.6


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
|           26 |       56 | 2024-05-29 | Cerberus eSports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.23 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           25 |     1429 | 2024-05-11 | Team LRP Poland      | W   | 1.000      | 0.143        | 0.001 (0.000)    | -                | 1 (1.000) |     9.45 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           24 |     1475 | 2024-05-11 | akceptuj             | W   | 1.000      | -            | -                | -                | 1 (1.000) |     7.64 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           23 |     1481 | 2024-05-11 | Team LRP Poland      | W   | 1.000      | 0.143        | 0.001 (0.000)    | -                | 1 (1.000) |     9.59 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           22 |     2767 | 2024-04-19 | ThunderFlash         | L   | 0.929      | -            | -                | -                | -         |   -15.43 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           21 |     3018 | 2024-04-15 | M1 Gaming            | W   | 0.903      | -            | -                | -                | 0 (0.000) |     5.76 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           20 |     3136 | 2024-04-12 | brazylijski luz      | W   | 0.884      | 0.143        | 0.013 (0.002)    | 0.514 (0.065)    | 0 (0.000) |    12.13 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           19 |     3184 | 2024-04-11 | 9INE                 | W   | 0.877      | 0.143        | 0.002 (0.000)    | 0.092 (0.012)    | 0 (0.000) |     7.68 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           18 |     3258 | 2024-04-10 | DEEZ NUTS            | W   | 0.870      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     6.90 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           17 |     3308 | 2024-04-09 | Permitta Esports     | L   | 0.864      | -            | -                | -                | -         |    -9.45 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           16 |     4882 | 2024-03-08 | GamerLegion Academy  | L   | 0.650      | -            | -                | -                | -         |   -11.25 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           15 |     4948 | 2024-03-07 | FAVBET Team          | L   | 0.643      | -            | -                | -                | -         |    -8.83 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           14 |     5092 | 2024-03-05 | SINNERS Academy      | W   | 0.631      | 0.289        | 0.001 (0.000)    | 0.227 (0.041)    | 0 (0.000) |     4.69 | BORO, dreez, luke, majky, vANO                  |
|           13 |     5246 | 2024-03-03 | GamerLegion Academy  | W   | 0.617      | 0.289        | 0.018 (0.003)    | 0.691 (0.123)    | 0 (0.000) |     8.34 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii  |
|           12 |     5412 | 2024-02-29 | Kappa Bar            | W   | 0.598      | 0.289        | -                | 0.062 (0.011)    | -         |     2.80 | dezt, jayzaR, pupcake, TIM, upE                 |
|           11 |     5575 | 2024-02-26 | FAVBET Team          | L   | 0.577      | -            | -                | -                | -         |    -9.83 | bondik, guthriee, j3kie, Smash, t3ns1on         |
|           10 |     5675 | 2024-02-24 | KOMNATA              | L   | 0.564      | -            | -                | -                | -         |   -13.54 | hotd0g, jcobbb, killkapi, misho, nawrot         |
|            9 |     5822 | 2024-02-22 | ALTERNATE aTTaX Evo  | W   | 0.550      | 0.289        | 0.002 (0.000)    | 0.239 (0.038)    | -         |     5.02 | devils, FoG, HuNt3rz, Miku, Rulz                |
|            8 |     6897 | 2024-02-01 | EXO Clan             | L   | 0.409      | -            | -                | -                | -         |    -4.18 | Adam9130, AwaykeN, bevve, dobbo, Duplicate      |
|            7 |     6982 | 2024-01-30 | Natus Vincere Junior | W   | 0.397      | 0.289        | 0.006 (0.001)    | 0.444 (0.051)    | -         |     4.67 | cmtry, dziugss, froz1k, qzr, UNBR0KEN           |
|            6 |     7050 | 2024-01-29 | Sashi Academy        | L   | 0.391      | -            | -                | -                | -         |    -9.38 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            5 |     7270 | 2024-01-26 | EXO Clan             | W   | 0.370      | 0.289        | 0.013 (0.001)    | 0.579 (0.062)    | -         |     7.88 | Adam9130, AwaykeN, bevve, dobbo, Duplicate      |
|            4 |     7359 | 2024-01-24 | Begrip Gaming        | W   | 0.357      | 0.289        | -                | 0.317 (0.033)    | -         |     2.28 | Ariant0, Karma, Reedz, shateri, titulus         |
|            3 |     7593 | 2024-01-20 | ex-KRC Genk Esports  | L   | 0.330      | -            | -                | -                | -         |    -7.32 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            2 |     7933 | 2024-01-16 | Young Gods           | W   | 0.304      | 0.289        | -                | 0.240 (0.021)    | -         |     1.29 | Cham, Focus, MaiL09, viz, Wonder                |
|            1 |     8609 | 2023-12-22 | monaco               | L   | 0.138      | -            | -                | -                | -         |    -3.52 | daph, darknesszz, diis6, redzy, xype            |

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
