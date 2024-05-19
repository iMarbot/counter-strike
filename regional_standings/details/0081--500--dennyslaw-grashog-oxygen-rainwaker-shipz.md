### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, Oxygen, Rainwaker, SHiPZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [81](../standings_global.md)<br />
Regional Rank: [60]( ../standings_europe.md)<br />
Final Rank Value:  891.4<br />
<br />
Final Rank Value (891.4) = Starting Rank Value (790.6) + Head To Head Adjustments (100.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.357[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 790.6
- 400 + ( ( 0.197 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 790.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      117 | 2024-05-03 | Soda Gaming       | W   | 1.000      | -            | -                | -                | false (0.000) |     3.93 | dennyslaw, Grashog, Oxygen, Rainwaker, SHiPZ  |
|           43 |      289 | 2024-04-29 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -             |    -3.58 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           42 |      351 | 2024-04-27 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -             |   -11.69 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           41 |      449 | 2024-04-26 | GenOne            | W   | 1.000      | -            | -                | -                | false (0.000) |     5.14 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           40 |      593 | 2024-04-23 | GUN5 Esports      | W   | 1.000      | -            | -                | -                | false (0.000) |     7.06 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           39 |      616 | 2024-04-22 | GenOne            | L   | 1.000      | -            | -                | -                | -             |   -26.43 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           38 |      897 | 2024-04-18 | Team Secret       | L   | 1.000      | -            | -                | -                | -             |   -24.57 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           37 |      946 | 2024-04-17 | EsmagaB           | L   | 1.000      | -            | -                | -                | -             |   -20.85 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           36 |     1002 | 2024-04-16 | Passion UA        | W   | 1.000      | 0.384        | 0.114 (0.044)    | 0.980 (0.376)    | false (0.000) |    14.71 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           35 |     1176 | 2024-04-11 | PARIVISION        | W   | 1.000      | 0.384        | -                | 0.374 (0.144)    | false (0.000) |    12.07 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           34 |     1591 | 2024-04-02 | Guild Eagles      | W   | 0.976      | 0.384        | 0.037 (0.014)    | 0.586 (0.220)    | false (0.000) |    18.44 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           33 |     1599 | 2024-04-01 | Guild Eagles      | L   | 0.972      | -            | -                | -                | -             |   -12.03 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           32 |     1729 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.939      | -            | -                | -                | -             |    -7.08 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           31 |     1737 | 2024-03-27 | FORZE Esports     | W   | 0.939      | 0.143        | 0.210 (0.028)    | -                | false (0.000) |    22.55 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           30 |     1749 | 2024-03-27 | EsmagaB           | W   | 0.938      | -            | -                | -                | false (0.000) |    11.31 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           29 |     1804 | 2024-03-26 | Insilio           | W   | 0.932      | 0.143        | 0.020 (0.003)    | 0.875 (0.117)    | false (0.000) |    18.09 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           28 |     2156 | 2024-03-17 | REALMADRID        | W   | 0.870      | -            | -                | -                | false (0.000) |     1.71 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           27 |     2464 | 2024-03-10 | Young Ninjas      | L   | 0.824      | -            | -                | -                | -             |    -9.96 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           26 |     2579 | 2024-03-07 | Sangal Esports    | W   | 0.804      | 0.384        | -                | 0.350 (0.108)    | -             |     7.91 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           25 |     2713 | 2024-03-05 | Entropiq          | W   | 0.790      | 0.384        | -                | 0.436 (0.132)    | -             |    10.20 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           24 |     2880 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.771      | 0.143        | 0.110 (0.012)    | 0.723 (0.080)    | -             |    15.21 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           23 |     3078 | 2024-02-26 | Team Pigeons      | W   | 0.737      | 0.384        | 0.094 (0.027)    | 0.402 (0.114)    | -             |    12.37 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           22 |     3157 | 2024-02-24 | EsmagaB           | W   | 0.725      | -            | -                | -                | -             |    10.51 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           21 |     3522 | 2024-02-16 | SINNERS Esports   | L   | 0.672      | -            | -                | -                | -             |    -6.63 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           20 |     3533 | 2024-02-16 | B8                | L   | 0.671      | -            | -                | -                | -             |    -7.19 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           19 |     3537 | 2024-02-16 | SINNERS Esports   | W   | 0.671      | 0.143        | 0.038 (0.004)    | -                | -             |    14.44 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           18 |     3744 | 2024-02-11 | DASH              | L   | 0.639      | -            | -                | -                | -             |   -12.42 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           17 |     3749 | 2024-02-11 | M1X               | W   | 0.638      | -            | -                | -                | -             |     1.52 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           16 |     3927 | 2024-02-04 | Zero Tenacity     | W   | 0.591      | 0.143        | 0.095 (0.008)    | 1.000 (0.084)    | -             |    12.16 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           15 |     3951 | 2024-02-03 | Nexus Gaming      | W   | 0.585      | 0.143        | 0.031 (0.003)    | -                | -             |    11.76 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           14 |     3981 | 2024-02-03 | AIRLYA            | L   | 0.584      | -            | -                | -                | -             |   -15.04 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           13 |     3988 | 2024-02-03 | Jake Bube         | W   | 0.584      | -            | -                | -                | -             |     1.45 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           12 |     4147 | 2024-01-30 | Fnatic            | L   | 0.558      | -            | -                | -                | -             |    -1.67 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           11 |     4159 | 2024-01-29 | Gaimin Gladiators | W   | 0.553      | 0.143        | 0.194 (0.015)    | 0.989 (0.078)    | -             |    16.71 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           10 |     4175 | 2024-01-29 | EsmagaB           | W   | 0.553      | -            | -                | -                | -             |    10.08 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            9 |     4326 | 2024-01-26 | HyperSpirit       | W   | 0.531      | -            | -                | -                | -             |     6.69 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            8 |     4690 | 2024-01-17 | Sprout            | L   | 0.473      | -            | -                | -                | -             |   -12.56 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            7 |     4694 | 2024-01-17 | Ninjas in Pyjamas | W   | 0.473      | -            | -                | -                | -             |     7.45 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            6 |     4709 | 2024-01-17 | Team Space        | W   | 0.473      | -            | -                | -                | -             |     6.26 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     4736 | 2024-01-17 | WOPA Esport       | W   | 0.472      | -            | -                | -                | -             |     6.82 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     4808 | 2024-01-16 | Aurora Young Blud | L   | 0.465      | -            | -                | -                | -             |    -6.79 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     4885 | 2024-01-13 | Gaimin Gladiators | L   | 0.445      | -            | -                | -                | -             |    -0.46 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     4892 | 2024-01-13 | Team Space        | W   | 0.444      | -            | -                | -                | -             |     6.08 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     4943 | 2024-01-12 | The Chosen Few    | W   | 0.439      | -            | -                | -                | -             |     7.17 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($500.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
