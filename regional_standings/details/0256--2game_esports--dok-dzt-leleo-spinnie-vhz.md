### Roster Details<br />
Team Name: 2Game Esports<br />
Roster: dok, dzt, leleo, spinnie, vhz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [256](../standings_global.md)<br />
Regional Rank: [54]( ../standings_americas.md)<br />
Final Rank Value:  680.7<br />
<br />
Final Rank Value (680.7) = Starting Rank Value (699.7) + Head To Head Adjustments (-19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.284[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.055[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.7
- 400 + ( ( 0.147 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 699.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      152 | 2024-05-27 | Vikings KR          | W   | 1.000      | 0.384        | 0.004 (0.002)    | 0.313 (0.120)    | 0 (0.000) |    18.25 | dok, dzt, leleo, spinnie, vhz |
|           37 |      201 | 2024-05-26 | MIBR Academy        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.220 (0.031)    | 0 (0.000) |    16.08 | beg0d, dok, dzt, spinnie, vhz |
|           36 |      547 | 2024-05-21 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |    -3.70 | beg0d, dok, dzt, spinnie, vhz |
|           35 |      552 | 2024-05-21 | BESTIA              | L   | 1.000      | -            | -                | -                | -         |    -3.85 | beg0d, dok, dzt, spinnie, vhz |
|           34 |     1057 | 2024-05-16 | ex-Martians         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.064 (0.009)    | 0 (0.000) |    12.19 | beg0d, dok, dzt, spinnie, vhz |
|           33 |     1068 | 2024-05-16 | Sharks Youngsters   | L   | 1.000      | -            | -                | -                | -         |   -16.67 | beg0d, dok, dzt, spinnie, vhz |
|           32 |     1137 | 2024-05-15 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -2.21 | beg0d, dok, dzt, spinnie, vhz |
|           31 |     1139 | 2024-05-15 | Fluxo               | L   | 1.000      | -            | -                | -                | -         |    -2.26 | beg0d, dok, dzt, spinnie, vhz |
|           30 |     1241 | 2024-05-14 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -1.08 | beg0d, dok, dzt, spinnie, vhz |
|           29 |     1243 | 2024-05-14 | 9z Team             | L   | 1.000      | -            | -                | -                | -         |    -1.10 | beg0d, dok, dzt, spinnie, vhz |
|           28 |     2259 | 2024-04-26 | Corinthians Esports | L   | 0.979      | -            | -                | -                | -         |   -15.47 | Alisson, beg0d, dok, dzt, vhz |
|           27 |     2264 | 2024-04-26 | pugdesonesto        | W   | 0.979      | 0.143        | 0.001 (0.000)    | 0.146 (0.020)    | 0 (0.000) |    11.34 | Alisson, beg0d, dok, dzt, vhz |
|           26 |     2591 | 2024-04-20 | MIBR Academy        | L   | 0.939      | -            | -                | -                | -         |   -12.70 | beg0d, dok, dzt, jz, vhz      |
|           25 |     2599 | 2024-04-20 | bebidarosa          | W   | 0.938      | 0.143        | 0.001 (0.000)    | 0.100 (0.013)    | 0 (0.000) |    13.04 | beg0d, dok, dzt, jz, vhz      |
|           24 |     3517 | 2024-04-05 | adalYamigos         | W   | 0.838      | 0.450        | -                | 0.177 (0.067)    | 0 (0.000) |    16.71 | beg0d, dok, dzt, santos, vhz  |
|           23 |     3519 | 2024-04-05 | adalYamigos         | L   | 0.838      | -            | -                | -                | -         |    -9.60 | beg0d, dok, dzt, santos, vhz  |
|           22 |     3617 | 2024-04-03 | Sharks Esports      | L   | 0.825      | -            | -                | -                | -         |    -4.39 | beg0d, dok, dzt, santos, vhz  |
|           21 |     3618 | 2024-04-03 | Sharks Esports      | L   | 0.825      | -            | -                | -                | -         |    -4.57 | beg0d, dok, dzt, santos, vhz  |
|           20 |     3867 | 2024-03-27 | Corinthians Esports | W   | 0.779      | 0.450        | 0.002 (0.001)    | 0.458 (0.161)    | 0 (0.000) |    13.87 | beg0d, dok, dzt, santos, vhz  |
|           19 |     3870 | 2024-03-27 | Corinthians Esports | L   | 0.779      | -            | -                | -                | -         |   -10.74 | beg0d, dok, dzt, santos, vhz  |
|           18 |     3942 | 2024-03-26 | Galorys             | L   | 0.773      | -            | -                | -                | -         |    -7.86 | beg0d, dok, dzt, santos, vhz  |
|           17 |     3947 | 2024-03-26 | Galorys             | L   | 0.772      | -            | -                | -                | -         |    -8.35 | beg0d, dok, dzt, santos, vhz  |
|           16 |     4467 | 2024-03-15 | ODDIK               | L   | 0.699      | -            | -                | -                | -         |    -4.23 | beg0d, dok, dzt, santos, vhz  |
|           15 |     4468 | 2024-03-15 | ODDIK               | L   | 0.699      | -            | -                | -                | -         |    -4.40 | beg0d, dok, dzt, santos, vhz  |
|           14 |     4660 | 2024-03-12 | Sharks Esports      | L   | 0.679      | -            | -                | -                | -         |    -4.62 | beg0d, dok, dzt, santos, vhz  |
|           13 |     5638 | 2024-02-24 | Case Esports        | L   | 0.566      | -            | -                | -                | -         |    -5.11 | beg0d, dok, dzt, santos, vhz  |
|           12 |     5647 | 2024-02-24 | Case Esports        | W   | 0.566      | 0.450        | 0.028 (0.007)    | 0.470 (0.120)    | 0 (0.000) |    13.03 | beg0d, dok, dzt, santos, vhz  |
|           11 |     5846 | 2024-02-21 | Imperial Esports    | L   | 0.546      | -            | -                | -                | -         |    -0.16 | beg0d, dok, dzt, santos, vhz  |
|           10 |     5849 | 2024-02-21 | Imperial Esports    | L   | 0.546      | -            | -                | -                | -         |    -0.16 | beg0d, dok, dzt, santos, vhz  |
|            9 |     6256 | 2024-02-14 | 9z Team             | L   | 0.499      | -            | -                | -                | -         |    -0.58 | beg0d, dok, dzt, santos, vhz  |
|            8 |     7299 | 2024-01-25 | w7m esports         | L   | 0.366      | -            | -                | -                | -         |    -4.32 | beg0d, dok, dzt, santos, vhz  |
|            7 |     8172 | 2024-01-11 | adalYamigos         | L   | 0.271      | -            | -                | -                | -         |    -4.97 | Brnz1k, dok, dzt, santos, vhz |
|            6 |     8182 | 2024-01-11 | Corinthians Esports | W   | 0.271      | 0.143        | 0.000 (0.000)    | 0.117 (0.005)    | 0 (0.000) |     3.44 | Brnz1k, dok, dzt, santos, vhz |
|            5 |     8236 | 2024-01-10 | Myth e-Sports       | W   | 0.266      | 0.143        | 0.000 (0.000)    | 0.041 (0.002)    | 0 (0.000) |     3.25 | Brnz1k, dok, dzt, santos, vhz |
|            4 |     8425 | 2024-01-08 | caradecachorro      | L   | 0.252      | -            | -                | -                | -         |    -5.95 | Brnz1k, dok, dzt, santos, vhz |
|            3 |     9097 | 2023-12-13 | Case Esports        | L   | 0.077      | -            | -                | -                | -         |    -1.29 | Brnz1k, dok, dzt, santos, vhz |
|            2 |     9177 | 2023-12-11 | Vex Dragons         | W   | 0.065      | 0.262        | 0.000 (0.000)    | -                | -         |     0.67 | Brnz1k, dok, dzt, santos, vhz |
|            1 |     9541 | 2023-12-05 | Meta Gaming         | L   | 0.026      | -            | -                | -                | -         |    -0.63 | Brnz1k, dok, dzt, santos, vhz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($900.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
