### Roster Details<br />
Team Name: SINNERS Academy<br />
Roster: BORO, DALIEN, dreez, majky, vANO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [245](../standings_global.md)<br />
Regional Rank: [157]( ../standings_europe.md)<br />
Final Rank Value:  670.3<br />
<br />
Final Rank Value (670.3) = Starting Rank Value (686.2) + Head To Head Adjustments (-16.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.001[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 686.2
- 400 + ( ( 0.144 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 686.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      198 | 2024-05-01 | L&G                    | L   | 1.000      | -            | -                | -                | -             |   -13.35 | BORO, DALIEN, dreez, majky, vANO |
|           29 |      244 | 2024-04-30 | Lazer Cats             | L   | 1.000      | -            | -                | -                | -             |   -16.84 | BORO, DALIEN, dreez, majky, vANO |
|           28 |      647 | 2024-04-21 | XI Esport              | W   | 1.000      | 0.289        | 0.002 (0.001)    | 0.313 (0.090)    | false (0.000) |    14.07 | BORO, DALIEN, dreez, majky, vANO |
|           27 |      938 | 2024-04-17 | DUSTY                  | W   | 1.000      | 0.289        | 0.015 (0.004)    | 0.233 (0.067)    | false (0.000) |    17.52 | BORO, DALIEN, dreez, majky, vANO |
|           26 |     1485 | 2024-04-04 | 777 Esports            | L   | 0.992      | -            | -                | -                | -             |   -10.54 | BORO, DALIEN, dreez, majky, vANO |
|           25 |     1538 | 2024-04-03 | Natus Vincere Youth    | L   | 0.984      | -            | -                | -                | -             |   -13.65 | BORO, DALIEN, dreez, majky, vANO |
|           24 |     1600 | 2024-04-01 | Apeks Rebels           | W   | 0.972      | 0.289        | 0.005 (0.002)    | 0.071 (0.020)    | false (0.000) |    16.03 | BORO, DALIEN, dreez, majky, vANO |
|           23 |     1634 | 2024-03-30 | 9INE Academy           | W   | 0.958      | 0.289        | 0.005 (0.001)    | 0.171 (0.047)    | false (0.000) |    14.29 | BORO, DALIEN, dreez, majky, vANO |
|           22 |     1743 | 2024-03-27 | Illuminar Junior       | W   | 0.939      | 0.289        | 0.000 (0.000)    | 0.031 (0.009)    | false (0.000) |     5.87 | BORO, DALIEN, dreez, majky, vANO |
|           21 |     1856 | 2024-03-24 | Dynamo Eclot Thunders  | W   | 0.919      | 0.289        | 0.000 (0.000)    | 0.035 (0.009)    | false (0.000) |     4.87 | BORO, DALIEN, dreez, majky, vANO |
|           20 |     2397 | 2024-03-11 | Oxuji Esports          | L   | 0.832      | -            | -                | -                | -             |   -18.07 | BORO, dreez, luke, majky, vANO   |
|           19 |     2481 | 2024-03-09 | Linx Legacy Madagaskar | W   | 0.819      | 0.333        | -                | 0.028 (0.008)    | false (0.000) |     6.94 | BORO, dreez, luke, majky, vANO   |
|           18 |     2631 | 2024-03-06 | GamerLegion Academy    | L   | 0.797      | -            | -                | -                | -             |    -7.66 | BORO, dreez, luke, majky, vANO   |
|           17 |     2793 | 2024-03-03 | BRUTE                  | W   | 0.779      | 0.289        | -                | 0.122 (0.028)    | false (0.000) |     8.22 | BORO, dreez, luke, majky, vANO   |
|           16 |     2960 | 2024-02-29 | Natus Vincere Youth    | W   | 0.758      | 0.289        | 0.013 (0.003)    | 0.306 (0.067)    | false (0.000) |    14.18 | BORO, dreez, luke, majky, vANO   |
|           15 |     3072 | 2024-02-26 | BRUTE                  | L   | 0.738      | -            | -                | -                | -             |   -15.59 | BORO, dreez, luke, majky, vANO   |
|           14 |     3097 | 2024-02-25 | Dynamo Eclot Thunders  | W   | 0.732      | -            | -                | -                | -             |     4.07 | BORO, dreez, luke, majky, vANO   |
|           13 |     3294 | 2024-02-21 | Natus Vincere Youth    | L   | 0.705      | -            | -                | -                | -             |    -8.96 | BORO, dreez, luke, majky, vANO   |
|           12 |     4948 | 2024-01-12 | ROSOMAHA               | L   | 0.437      | -            | -                | -                | -             |    -7.96 | BORO, dreez, luke, majky, vANO   |
|           11 |     5156 | 2024-01-08 | Lazer Cats             | L   | 0.409      | -            | -                | -                | -             |    -9.49 | BORO, dreez, luke, majky, vANO   |
|           10 |     5198 | 2024-01-04 | Dynamo Eclot           | L   | 0.383      | -            | -                | -                | -             |    -0.71 | BORO, dreez, luke, majky, vANO   |
|            9 |     5994 | 2023-12-05 | Monte Gen              | L   | 0.184      | -            | -                | -                | -             |    -2.05 | BORO, dreez, luke, majky, vANO   |
|            8 |     6032 | 2023-12-03 | Natus Vincere Youth    | W   | 0.172      | 0.289        | 0.013 (0.001)    | 0.306 (0.015)    | -             |     3.04 | BORO, dreez, luke, majky, vANO   |
|            7 |     6157 | 2023-12-01 | Monte Gen              | L   | 0.159      | -            | -                | -                | -             |    -1.74 | BORO, dreez, luke, majky, vANO   |
|            6 |     6211 | 2023-11-30 | Sampi NEXT             | W   | 0.151      | -            | -                | -                | -             |     1.22 | BORO, dreez, luke, majky, vANO   |
|            5 |     6376 | 2023-11-27 | Preasy Esport          | L   | 0.131      | -            | -                | -                | -             |    -1.32 | BORO, dreez, luke, majky, vANO   |
|            4 |     6522 | 2023-11-23 | Eternal Fire Academy   | W   | 0.104      | 0.289        | 0.013 (0.000)    | -                | -             |     1.79 | BORO, dreez, luke, majky, vANO   |
|            3 |     7097 | 2023-11-10 | Dynamo Eclot           | L   | 0.018      | -            | -                | -                | -             |    -0.29 | BORO, dreez, luke, majky, vANO   |
|            2 |     7123 | 2023-11-09 | Team Sampi             | L   | 0.012      | -            | -                | -                | -             |    -0.05 | BORO, dreez, luke, majky, vANO   |
|            1 |     7138 | 2023-11-09 | Dynamo Eclot           | W   | 0.012      | 0.143        | 0.013 (0.000)    | -                | true (0.012)  |     0.18 | BORO, dreez, luke, majky, vANO   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($499.14)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
