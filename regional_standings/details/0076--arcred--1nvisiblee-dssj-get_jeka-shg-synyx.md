### Roster Details<br />
Team Name: ARCRED<br />
Roster: 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [76](../standings_global.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
Final Rank Value:  920.6<br />
<br />
Final Rank Value (920.6) = Starting Rank Value (776.9) + Head To Head Adjustments (143.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.201[<sup>1</sup>](#table2)
- Bounty Collected: 0.322[<sup>2</sup>](#table1)
- Opponent Network: 0.218[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.9
- 400 + ( ( 0.185 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 776.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |      408 | 2024-05-23 | ThunderFlash         | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.423 (0.158)    | 0 (0.000) |    15.16 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           63 |      417 | 2024-05-23 | WOPA Esport          | W   | 1.000      | 0.372        | -                | 0.594 (0.221)    | 0 (0.000) |     8.09 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           62 |      489 | 2024-05-22 | Soda Gaming          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.17 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           61 |      689 | 2024-05-20 | 5goblinz             | L   | 1.000      | -            | -                | -                | -         |   -28.90 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           60 |      776 | 2024-05-19 | Insilio              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    17.89 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           59 |     1178 | 2024-05-15 | HOTU                 | W   | 1.000      | 0.372        | 0.004 (0.002)    | 0.580 (0.216)    | 0 (0.000) |    13.00 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           58 |     1642 | 2024-05-08 | Nemiga Gaming        | L   | 1.000      | -            | -                | -                | -         |    -4.97 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           57 |     1812 | 2024-05-05 | 9Pandas              | L   | 1.000      | -            | -                | -                | -         |    -8.25 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           56 |     1904 | 2024-05-03 | ARROW                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.52 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           55 |     2006 | 2024-05-01 | Nexus Gaming         | W   | 1.000      | 0.372        | -                | 0.857 (0.319)    | 0 (0.000) |    14.24 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           54 |     2156 | 2024-04-28 | FORZE Youngsters     | W   | 0.989      | -            | -                | -                | 0 (0.000) |     1.91 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           53 |     2299 | 2024-04-26 | Insilio              | W   | 0.976      | -            | -                | -                | 0 (0.000) |    19.46 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           52 |     2318 | 2024-04-26 | Permitta Esports     | W   | 0.975      | 0.143        | 0.025 (0.004)    | 1.000 (0.139)    | 0 (0.000) |    19.93 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           51 |     2428 | 2024-04-24 | Dynamo Eclot         | W   | 0.963      | 0.372        | 0.097 (0.035)    | 0.940 (0.337)    | -         |    22.23 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           50 |     2545 | 2024-04-21 | MANGANES             | W   | 0.943      | -            | -                | -                | -         |     5.64 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           49 |     2607 | 2024-04-20 | ILLYRIANS            | W   | 0.937      | -            | -                | -                | -         |    12.33 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           48 |     2628 | 2024-04-20 | M1X                  | W   | 0.937      | -            | -                | -                | -         |     4.53 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           47 |     2885 | 2024-04-17 | iNation              | L   | 0.918      | -            | -                | -                | -         |   -19.38 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           46 |     3024 | 2024-04-15 | 1win                 | L   | 0.902      | -            | -                | -                | -         |    -7.77 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           45 |     3110 | 2024-04-13 | RUBY                 | W   | 0.889      | -            | -                | -                | -         |    18.27 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           44 |     3180 | 2024-04-11 | TopTab Club          | W   | 0.877      | -            | -                | -                | -         |     5.14 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           43 |     3478 | 2024-04-06 | Team Space           | W   | 0.843      | -            | -                | -                | -         |    13.91 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           42 |     3956 | 2024-03-26 | Team Secret          | L   | 0.771      | -            | -                | -                | -         |   -17.19 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           41 |     4679 | 2024-03-12 | The Chosen Few       | L   | 0.677      | -            | -                | -                | -         |   -10.37 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           40 |     4748 | 2024-03-11 | LEON Esports         | W   | 0.669      | -            | -                | -                | -         |     9.18 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           39 |     4833 | 2024-03-09 | FORZE Youngsters     | W   | 0.657      | -            | -                | -                | -         |     7.03 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           38 |     4876 | 2024-03-08 | RUBY                 | L   | 0.651      | -            | -                | -                | -         |    -6.76 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           37 |     5078 | 2024-03-05 | 1win                 | W   | 0.631      | 0.371        | 0.050 (0.012)    | 0.898 (0.210)    | -         |    14.13 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           36 |     5277 | 2024-03-02 | 9INE                 | L   | 0.612      | -            | -                | -                | -         |   -14.51 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           35 |     5301 | 2024-03-02 | GamerLegion Academy  | W   | 0.611      | 0.143        | 0.018 (0.002)    | -                | -         |     9.89 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           34 |     5457 | 2024-02-28 | Endpoint             | L   | 0.591      | -            | -                | -                | -         |    -6.30 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           33 |     5519 | 2024-02-27 | FORZE Esports        | L   | 0.584      | -            | -                | -                | -         |    -4.78 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           32 |     5564 | 2024-02-26 | Natus Vincere Junior | W   | 0.578      | -            | -                | -                | -         |     9.47 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           31 |     5576 | 2024-02-26 | VP.Prodigy           | W   | 0.577      | 0.371        | 0.008 (0.002)    | 0.829 (0.177)    | -         |    10.73 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           30 |     5813 | 2024-02-22 | Permitta Esports     | W   | 0.551      | 0.371        | 0.025 (0.005)    | 1.000 (0.204)    | -         |    13.12 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           29 |     5859 | 2024-02-21 | ex-Anonymo Esports   | L   | 0.544      | -            | -                | -                | -         |   -10.04 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           28 |     5925 | 2024-02-20 | Passion UA           | W   | 0.537      | 0.371        | 0.057 (0.011)    | 1.000 (0.200)    | -         |    12.26 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           27 |     6050 | 2024-02-18 | brazylijski luz      | L   | 0.523      | -            | -                | -                | -         |    -7.58 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           26 |     6112 | 2024-02-17 | CYBERSHOKE Esports   | L   | 0.517      | -            | -                | -                | -         |   -11.85 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           25 |     6146 | 2024-02-16 | Golden Sword         | W   | 0.511      | -            | -                | -                | -         |     1.59 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           24 |     6381 | 2024-02-12 | INGLORIOUS           | W   | 0.484      | -            | -                | -                | -         |     7.39 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           23 |     6434 | 2024-02-11 | Sashi Esport         | L   | 0.476      | -            | -                | -                | -         |    -2.59 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           22 |     6521 | 2024-02-08 | Aurora Young Blud    | W   | 0.457      | -            | -                | -                | -         |     7.90 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           21 |     6677 | 2024-02-04 | esmagaB              | L   | 0.429      | -            | -                | -                | -         |    -5.29 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           20 |     6887 | 2024-02-01 | FLuffy Gangsters     | L   | 0.410      | -            | -                | -                | -         |    -9.84 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           19 |     6937 | 2024-01-31 | UNiTY esports        | W   | 0.403      | 0.371        | 0.021 (0.003)    | -                | -         |     8.62 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           18 |     7004 | 2024-01-29 | Fnatic               | L   | 0.392      | -            | -                | -                | -         |    -1.45 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           17 |     7042 | 2024-01-29 | ZEROvariant          | W   | 0.392      | -            | -                | -                | -         |     2.26 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx   |
|           16 |     7896 | 2024-01-16 | Sashi Esport         | L   | 0.304      | -            | -                | -                | -         |    -1.67 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|           15 |     7913 | 2024-01-16 | manageYself          | W   | 0.304      | -            | -                | -                | -         |     1.70 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|           14 |     8077 | 2024-01-12 | Team Space           | L   | 0.279      | -            | -                | -                | -         |    -3.53 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|           13 |     8101 | 2024-01-12 | EXO Clan             | W   | 0.278      | -            | -                | -                | -         |     6.76 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|           12 |     8641 | 2023-12-20 | Metizport            | L   | 0.123      | -            | -                | -                | -         |    -0.95 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|           11 |     8663 | 2023-12-19 | VP.Prodigy           | L   | 0.115      | -            | -                | -                | -         |    -1.44 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|           10 |     8670 | 2023-12-18 | showmakerz           | W   | 0.110      | -            | -                | -                | -         |     0.75 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            9 |     8673 | 2023-12-18 | Sprout               | L   | 0.109      | -            | -                | -                | -         |    -2.61 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            8 |     8677 | 2023-12-18 | Sashi Esport         | W   | 0.109      | -            | -                | -                | -         |     0.76 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            7 |     8769 | 2023-12-17 | Insilio              | L   | 0.102      | -            | -                | -                | -         |    -1.11 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            6 |     8889 | 2023-12-16 | Donstu Esports       | W   | 0.096      | -            | -                | -                | -         |     0.60 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            5 |     8907 | 2023-12-16 | 1win Academy         | W   | 0.095      | -            | -                | -                | -         |     0.85 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            4 |     9642 | 2023-12-03 | Team Spirit Academy  | W   | 0.011      | -            | -                | -                | -         |     0.15 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            3 |     9649 | 2023-12-03 | Betera Esports       | W   | 0.010      | -            | -                | -                | -         |     0.17 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            2 |     9730 | 2023-12-02 | JANO Esports         | W   | 0.004      | -            | -                | -                | -         |     0.07 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |
|            1 |     9747 | 2023-12-02 | TUSTE CHOPAKI        | W   | 0.004      | -            | -                | -                | -         |     0.02 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($32.29)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
