### Roster Details<br />
Team Name: 500<br />
Roster: dennyslaw, Grashog, Oxygen, Rainwaker, SHiPZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [118](../standings_global.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
Final Rank Value:  839.8<br />
<br />
Final Rank Value (839.8) = Starting Rank Value (764.9) + Head To Head Adjustments (74.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.265[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.115[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 764.9
- 400 + ( ( 0.179 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 764.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |     1736 | 2024-05-06 | Gaimin Gladiators | L   | 1.000      | -            | -                | -                | -         |    -4.16 | dennyslaw, Grashog, Oxygen, Rainwaker, SHiPZ  |
|           55 |     1889 | 2024-05-03 | Soda Gaming       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.75 | dennyslaw, Grashog, Oxygen, Rainwaker, SHiPZ  |
|           54 |     2081 | 2024-04-29 | Sashi Esport      | L   | 0.995      | -            | -                | -                | -         |    -3.10 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           53 |     2164 | 2024-04-27 | Zero Tenacity     | L   | 0.984      | -            | -                | -                | -         |    -8.28 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           52 |     2286 | 2024-04-26 | GenOne            | W   | 0.975      | 0.143        | -                | 0.442 (0.062)    | 0 (0.000) |     7.86 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           51 |     2436 | 2024-04-23 | GUN5 Esports      | W   | 0.955      | -            | -                | -                | 0 (0.000) |     7.85 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           50 |     2463 | 2024-04-22 | GenOne            | L   | 0.949      | -            | -                | -                | -         |   -22.37 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           49 |     2785 | 2024-04-18 | Team Secret       | L   | 0.922      | -            | -                | -                | -         |   -21.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           48 |     2827 | 2024-04-17 | fragmatic         | L   | 0.918      | -            | -                | -                | -         |   -25.11 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           47 |     2847 | 2024-04-17 | esmagaB           | L   | 0.916      | -            | -                | -                | -         |   -18.50 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           46 |     2907 | 2024-04-16 | Passion UA        | W   | 0.910      | 0.384        | 0.057 (0.020)    | 1.000 (0.350)    | 0 (0.000) |    14.73 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           45 |     3120 | 2024-04-11 | PARIVISION        | W   | 0.877      | 0.384        | -                | 0.329 (0.111)    | 0 (0.000) |    13.82 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           44 |     3613 | 2024-04-02 | ex-Guild Eagles   | W   | 0.815      | 0.384        | 0.015 (0.005)    | 0.475 (0.149)    | 0 (0.000) |    14.90 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           43 |     3623 | 2024-04-01 | ex-Guild Eagles   | L   | 0.811      | -            | -                | -                | -         |   -10.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           42 |     3781 | 2024-03-27 | Ninjas in Pyjamas | L   | 0.778      | -            | -                | -                | -         |    -5.67 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           41 |     3792 | 2024-03-27 | FORZE Esports     | W   | 0.778      | 0.143        | 0.111 (0.012)    | -                | 0 (0.000) |    18.10 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           40 |     3805 | 2024-03-27 | esmagaB           | W   | 0.777      | -            | -                | -                | 0 (0.000) |    10.26 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           39 |     3867 | 2024-03-26 | Insilio           | W   | 0.771      | 0.143        | 0.010 (0.001)    | 0.717 (0.079)    | 0 (0.000) |    15.74 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           38 |     4272 | 2024-03-17 | ENRAGE            | W   | 0.710      | -            | -                | -                | 0 (0.000) |     3.50 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           37 |     4293 | 2024-03-17 | REALMADRID        | W   | 0.709      | -            | -                | -                | -         |     1.70 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           36 |     4667 | 2024-03-10 | Young Ninjas      | L   | 0.663      | -            | -                | -                | -         |    -7.67 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           35 |     4821 | 2024-03-07 | Sangal Esports    | W   | 0.643      | 0.384        | 0.166 (0.041)    | 0.577 (0.143)    | -         |    14.19 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           34 |     4977 | 2024-03-05 | Entropiq          | W   | 0.629      | -            | -                | -                | -         |     6.89 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           33 |     4988 | 2024-03-04 | AMKAL ESPORTS     | L   | 0.625      | -            | -                | -                | -         |    -2.61 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           32 |     5021 | 2024-03-04 | FAVBET Team       | W   | 0.625      | 0.143        | -                | 0.666 (0.059)    | -         |    11.35 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           31 |     5187 | 2024-03-02 | ALTERNATE aTTaX   | W   | 0.610      | 0.143        | 0.052 (0.004)    | 0.679 (0.059)    | -         |    13.25 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           30 |     5423 | 2024-02-26 | Team Pigeons      | W   | 0.576      | 0.384        | 0.024 (0.005)    | 0.350 (0.077)    | -         |     8.37 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           29 |     5538 | 2024-02-24 | esmagaB           | W   | 0.563      | -            | -                | -                | -         |     8.99 | dennyslaw, Grashog, Rainwaker, REDSTAR, SHiPZ |
|           28 |     5896 | 2024-02-18 | Sangal Esports    | L   | 0.522      | -            | -                | -                | -         |    -3.46 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           27 |     5974 | 2024-02-16 | SINNERS Esports   | L   | 0.511      | -            | -                | -                | -         |    -4.39 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           26 |     5985 | 2024-02-16 | B8                | L   | 0.510      | -            | -                | -                | -         |    -2.24 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           25 |     5990 | 2024-02-16 | SINNERS Esports   | W   | 0.510      | -            | -                | -                | -         |    11.77 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           24 |     6230 | 2024-02-11 | DASH              | L   | 0.478      | -            | -                | -                | -         |    -9.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           23 |     6235 | 2024-02-11 | M1X               | W   | 0.477      | -            | -                | -                | -         |     1.46 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           22 |     6278 | 2024-02-10 | Team Secret       | L   | 0.469      | -            | -                | -                | -         |   -10.61 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           21 |     6384 | 2024-02-06 | ALTERNATE aTTaX   | L   | 0.443      | -            | -                | -                | -         |    -8.72 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           20 |     6451 | 2024-02-04 | Metizport         | W   | 0.431      | 0.143        | 0.088 (0.005)    | -                | -         |    10.05 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           19 |     6468 | 2024-02-04 | Zero Tenacity     | W   | 0.429      | 0.143        | 0.147 (0.009)    | 1.000 (0.061)    | -         |    11.06 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           18 |     6505 | 2024-02-03 | Nexus Gaming      | W   | 0.424      | -            | -                | -                | -         |     9.18 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           17 |     6546 | 2024-02-03 | AIRLYA            | L   | 0.423      | -            | -                | -                | -         |   -10.73 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           16 |     6556 | 2024-02-03 | Jake Bube         | W   | 0.423      | -            | -                | -                | -         |     1.29 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           15 |     6764 | 2024-01-30 | Fnatic            | L   | 0.397      | -            | -                | -                | -         |    -1.60 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           14 |     6773 | 2024-01-30 | GODSENT           | L   | 0.396      | -            | -                | -                | -         |    -8.64 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           13 |     6782 | 2024-01-29 | Gaimin Gladiators | W   | 0.392      | 0.143        | 0.092 (0.005)    | -                | -         |    11.55 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           12 |     6802 | 2024-01-29 | esmagaB           | W   | 0.392      | -            | -                | -                | -         |     7.23 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           11 |     7046 | 2024-01-26 | HyperSpirit       | W   | 0.370      | -            | -                | -                | -         |     5.37 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           10 |     7053 | 2024-01-26 | M1X               | W   | 0.370      | -            | -                | -                | -         |     2.06 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            9 |     7509 | 2024-01-17 | Sprout            | L   | 0.312      | -            | -                | -                | -         |    -7.46 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            8 |     7513 | 2024-01-17 | Ninjas in Pyjamas | W   | 0.312      | -            | -                | -                | -         |     4.58 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            7 |     7530 | 2024-01-17 | Team Space        | W   | 0.311      | -            | -                | -                | -         |     5.86 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            6 |     7563 | 2024-01-17 | WOPA Esport       | W   | 0.311      | -            | -                | -                | -         |     5.46 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            5 |     7671 | 2024-01-16 | Aurora Young Blud | L   | 0.304      | -            | -                | -                | -         |    -4.54 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            4 |     7782 | 2024-01-13 | Gaimin Gladiators | L   | 0.284      | -            | -                | -                | -         |    -0.51 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            3 |     7790 | 2024-01-13 | Team Space        | W   | 0.283      | -            | -                | -                | -         |     5.46 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            2 |     7829 | 2024-01-12 | ENRAGE            | W   | 0.278      | -            | -                | -                | -         |     1.89 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|            1 |     7866 | 2024-01-12 | The Chosen Few    | W   | 0.278      | -            | -                | -                | -         |     4.43 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($500.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
