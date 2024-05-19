### Roster Details<br />
Team Name: L&G<br />
Roster: crickey, jackast, kr1vda, OneUn1que, somnium<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [337](../standings_global.md)<br />
Regional Rank: [207]( ../standings_europe.md)<br />
Final Rank Value:  522.4<br />
<br />
Final Rank Value (522.4) = Starting Rank Value (542.4) + Head To Head Adjustments (-20.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.072<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 542.4
- 400 + ( ( 0.072 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 542.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |     2953 | 2024-02-29 | Passion UA             | L   | 0.758      | -            | -                | -                | -         |    -2.54 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           24 |     2993 | 2024-02-28 | Copenhagen Wolves      | L   | 0.751      | -            | -                | -                | -         |    -9.17 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           23 |     3164 | 2024-02-24 | Nexus Gaming           | L   | 0.724      | -            | -                | -                | -         |    -2.60 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           22 |     3306 | 2024-02-21 | V1dar Gaming           | L   | 0.705      | -            | -                | -                | -         |    -8.08 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           21 |     3398 | 2024-02-19 | RoundsGG               | L   | 0.692      | -            | -                | -                | -         |    -6.73 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           20 |     3541 | 2024-02-16 | ILIN                   | L   | 0.671      | -            | -                | -                | -         |    -9.51 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           19 |     3823 | 2024-02-08 | Grindas                | W   | 0.618      | 0.371        | 0.002 (0.000)    | 0.332 (0.076)    | 0 (0.000) |    13.16 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           18 |     3842 | 2024-02-07 | DMS                    | L   | 0.612      | -            | -                | -                | -         |    -7.16 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           17 |     3879 | 2024-02-05 | Gaimin Gladiators      | L   | 0.599      | -            | -                | -                | -         |    -0.20 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           16 |     3898 | 2024-02-05 | Sashi Esport           | L   | 0.598      | -            | -                | -                | -         |    -1.09 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           15 |     3980 | 2024-02-03 | HyperSpirit            | W   | 0.584      | 0.143        | 0.009 (0.001)    | 0.293 (0.024)    | 0 (0.000) |    13.19 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           14 |     4055 | 2024-02-02 | Team Secret            | L   | 0.576      | -            | -                | -                | -         |    -6.62 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           13 |     4152 | 2024-01-30 | MOUZ NXT               | L   | 0.557      | -            | -                | -                | -         |    -0.79 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           12 |     4806 | 2024-01-16 | The Witchers           | L   | 0.465      | -            | -                | -                | -         |    -3.01 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           11 |     5186 | 2024-01-05 | Natus Vincere Junior   | L   | 0.391      | -            | -                | -                | -         |    -2.19 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           10 |     5254 | 2023-12-28 | Passion UA             | W   | 0.337      | 0.354        | 0.114 (0.014)    | 0.980 (0.117)    | 0 (0.000) |     9.82 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            9 |     6432 | 2023-11-25 | SHIPACHI               | W   | 0.118      | 0.371        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     1.47 | Brilliance, F1n3tw, kenhy, Remill, z1k4      |
|            8 |     6484 | 2023-11-24 | The Chosen Few         | W   | 0.111      | 0.371        | 0.007 (0.000)    | 0.457 (0.019)    | 0 (0.000) |     2.87 | hybrid, Libido, shaiK, Skrimo, SPELLAN       |
|            7 |     6524 | 2023-11-23 | GODSENT                | L   | 0.104      | -            | -                | -                | -         |    -0.63 | bobeksde, eraa, Golden, Plopski, Ro1f        |
|            6 |     6600 | 2023-11-21 | Gaimin Gladiators      | L   | 0.091      | -            | -                | -                | -         |    -0.02 | kraghen, Nodios, Patti, Queenix, salazar     |
|            5 |     6637 | 2023-11-20 | Endpoint               | L   | 0.085      | -            | -                | -                | -         |    -0.41 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal   |
|            4 |     6645 | 2023-11-20 | DMS                    | L   | 0.084      | -            | -                | -                | -         |    -0.94 | AW, H1te, kAlash, sFade8, sm3t               |
|            3 |     6931 | 2023-11-14 | Turów Zgorzelec Esport | W   | 0.044      | 0.371        | 0.019 (0.000)    | 0.640 (0.011)    | 0 (0.000) |     1.17 | b1elany, darko, gRuChA, kadziu, Markoś       |
|            2 |     7101 | 2023-11-10 | TSM                    | L   | 0.017      | -            | -                | -                | -         |    -0.16 | CYPHER, interz, JACKZ, MoDo, valde           |
|            1 |     7143 | 2023-11-09 | Ex-sYnck               | W   | 0.011      | 0.371        | 0.000 (0.000)    | 0.099 (0.000)    | 0 (0.000) |     0.18 | eku, fejtZ, Jyo, Wahtzz, xezr                |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
