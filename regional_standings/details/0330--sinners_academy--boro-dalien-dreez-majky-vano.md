### Roster Details<br />
Team Name: SINNERS Academy<br />
Roster: BORO, DALIEN, dreez, majky, vANO<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [330](../standings_global.md)<br />
Regional Rank: [202]( ../standings_europe.md)<br />
Final Rank Value:  622.3<br />
<br />
Final Rank Value (622.3) = Starting Rank Value (661.8) + Head To Head Adjustments (-39.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.259[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 661.8
- 400 + ( ( 0.129 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 661.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     1397 | 2024-05-12 | BRUTE                  | L   | 1.000      | -            | -                | -                | -         |   -20.65 | BORO, DALIEN, dreez, majky, vANO |
|           31 |     1543 | 2024-05-10 | VENI VIDI VICI         | L   | 1.000      | -            | -                | -                | -         |   -17.05 | BORO, DALIEN, dreez, majky, vANO |
|           30 |     1586 | 2024-05-09 | BRUTE                  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.157 (0.022)    | 0 (0.000) |     9.39 | BORO, DALIEN, dreez, majky, vANO |
|           29 |     2005 | 2024-05-01 | L&G                    | L   | 1.000      | -            | -                | -                | -         |   -10.73 | BORO, DALIEN, dreez, majky, vANO |
|           28 |     2065 | 2024-04-30 | Lazer Cats             | L   | 1.000      | -            | -                | -                | -         |   -13.02 | BORO, DALIEN, dreez, majky, vANO |
|           27 |     2221 | 2024-04-27 | lajtbitexe             | W   | 0.983      | 0.289        | 0.001 (0.000)    | 0.082 (0.023)    | 0 (0.000) |    12.23 | BORO, DALIEN, dreez, majky, vANO |
|           26 |     2556 | 2024-04-21 | XI Esport              | W   | 0.943      | 0.289        | 0.001 (0.000)    | 0.277 (0.076)    | 0 (0.000) |    14.67 | BORO, DALIEN, dreez, majky, vANO |
|           25 |     2895 | 2024-04-17 | DUSTY                  | W   | 0.917      | 0.289        | 0.006 (0.002)    | 0.148 (0.039)    | 0 (0.000) |    16.13 | BORO, DALIEN, dreez, majky, vANO |
|           24 |     3582 | 2024-04-04 | 777 Esports            | L   | 0.830      | -            | -                | -                | -         |    -7.46 | BORO, DALIEN, dreez, majky, vANO |
|           23 |     3643 | 2024-04-03 | Natus Vincere Junior   | L   | 0.823      | -            | -                | -                | -         |    -8.89 | BORO, DALIEN, dreez, majky, vANO |
|           22 |     3715 | 2024-04-01 | Apeks Rebels           | W   | 0.810      | 0.289        | 0.000 (0.000)    | 0.043 (0.010)    | 0 (0.000) |     9.96 | BORO, DALIEN, dreez, majky, vANO |
|           21 |     3764 | 2024-03-30 | 9INE                   | W   | 0.797      | 0.289        | 0.002 (0.001)    | 0.092 (0.021)    | 0 (0.000) |    12.97 | BORO, DALIEN, dreez, majky, vANO |
|           20 |     3892 | 2024-03-27 | Illuminar Junior       | W   | 0.777      | 0.289        | 0.000 (0.000)    | 0.020 (0.005)    | 0 (0.000) |     5.66 | BORO, DALIEN, dreez, majky, vANO |
|           19 |     4035 | 2024-03-24 | Dynamo Eclot Thunders  | W   | 0.757      | 0.289        | 0.000 (0.000)    | 0.026 (0.006)    | 0 (0.000) |     4.87 | BORO, DALIEN, dreez, majky, vANO |
|           18 |     4238 | 2024-03-20 | Preasy Esport          | L   | 0.730      | -            | -                | -                | -         |    -6.28 | BORO, DALIEN, dreez, majky, vANO |
|           17 |     4708 | 2024-03-11 | Oxuji Esports          | L   | 0.671      | -            | -                | -                | -         |   -14.09 | BORO, dreez, luke, majky, vANO   |
|           16 |     4819 | 2024-03-09 | Linx Legacy Madagaskar | W   | 0.658      | -            | -                | -                | 0 (0.000) |     6.66 | BORO, dreez, luke, majky, vANO   |
|           15 |     4947 | 2024-03-07 | TeamOrangeGaming       | L   | 0.643      | -            | -                | -                | -         |    -5.82 | BORO, dreez, luke, majky, vANO   |
|           14 |     5017 | 2024-03-06 | GamerLegion Academy    | L   | 0.636      | -            | -                | -                | -         |    -5.85 | BORO, dreez, luke, majky, vANO   |
|           13 |     5092 | 2024-03-05 | AVEZ                   | L   | 0.631      | -            | -                | -                | -         |    -4.69 | BORO, dreez, luke, majky, vANO   |
|           12 |     5223 | 2024-03-03 | BRUTE                  | W   | 0.618      | 0.289        | -                | 0.157 (0.028)    | 0 (0.000) |     8.19 | BORO, dreez, luke, majky, vANO   |
|           11 |     5430 | 2024-02-29 | Natus Vincere Junior   | W   | 0.597      | 0.289        | 0.006 (0.001)    | 0.444 (0.077)    | -         |    12.56 | BORO, dreez, luke, majky, vANO   |
|           10 |     5468 | 2024-02-28 | VENI VIDI VICI         | L   | 0.591      | -            | -                | -                | -         |    -9.69 | BORO, dreez, luke, majky, vANO   |
|            9 |     5572 | 2024-02-26 | BRUTE                  | L   | 0.577      | -            | -                | -                | -         |   -11.10 | BORO, dreez, luke, majky, vANO   |
|            8 |     5605 | 2024-02-25 | Dynamo Eclot Thunders  | W   | 0.571      | -            | -                | -                | -         |     3.50 | BORO, dreez, luke, majky, vANO   |
|            7 |     5861 | 2024-02-21 | Natus Vincere Junior   | L   | 0.544      | -            | -                | -                | -         |    -5.81 | BORO, dreez, luke, majky, vANO   |
|            6 |     8125 | 2024-01-12 | ROSOMAHA               | L   | 0.276      | -            | -                | -                | -         |    -4.95 | BORO, dreez, luke, majky, vANO   |
|            5 |     8438 | 2024-01-08 | Lazer Cats             | L   | 0.248      | -            | -                | -                | -         |    -5.63 | BORO, dreez, luke, majky, vANO   |
|            4 |     8471 | 2024-01-06 | lajtbitexe             | L   | 0.235      | -            | -                | -                | -         |    -4.01 | BORO, dreez, luke, majky, vANO   |
|            3 |     8492 | 2024-01-04 | Dynamo Eclot           | L   | 0.222      | -            | -                | -                | -         |    -0.54 | BORO, dreez, luke, majky, vANO   |
|            2 |     9586 | 2023-12-05 | Monte Gen              | L   | 0.023      | -            | -                | -                | -         |    -0.26 | BORO, dreez, luke, majky, vANO   |
|            1 |     9640 | 2023-12-03 | Natus Vincere Junior   | W   | 0.011      | 0.289        | 0.006 (0.000)    | -                | -         |     0.22 | BORO, dreez, luke, majky, vANO   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($418.47)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
