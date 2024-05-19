### Roster Details<br />
Team Name: Verdant<br />
Roster: arTisT, Diviiii, Ducky, Girafffe, Vacancy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [84](../standings_global.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
Final Rank Value:  885.5<br />
<br />
Final Rank Value (885.5) = Starting Rank Value (1002.0) + Head To Head Adjustments (-116.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.131[<sup>2</sup>](#table1)
- LAN Wins: 0.370[<sup>2</sup>](#table1)

The average of these factors is 0.303<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1002.0
- 400 + ( ( 0.303 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1002.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |       26 | 2024-05-05 | Preasy Esport               | W   | 1.000      | 0.333        | 0.007 (0.002)    | 0.525 (0.175)    | false (0.000) |    10.69 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           55 |       36 | 2024-05-05 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | false (0.000) |    16.54 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           54 |       79 | 2024-05-04 | Team Flow                   | L   | 1.000      | -            | -                | -                | -             |   -27.47 | AdamJC, arTisT, Ducky, Girafffe, Vacancy  |
|           53 |       99 | 2024-05-03 | Part Timers                 | W   | 1.000      | -            | -                | -                | false (0.000) |     3.81 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           52 |      189 | 2024-05-01 | LOG Esports                 | W   | 1.000      | -            | -                | -                | false (0.000) |     1.66 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           51 |      279 | 2024-04-29 | Aurora Young Blud           | W   | 1.000      | 0.371        | 0.017 (0.006)    | 0.422 (0.157)    | false (0.000) |    12.32 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           50 |      464 | 2024-04-25 | Lemondogs                   | L   | 1.000      | -            | -                | -                | -             |   -26.43 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           49 |      494 | 2024-04-25 | Turów Zgorzelec Esport      | W   | 1.000      | 0.333        | 0.019 (0.006)    | 0.640 (0.213)    | -             |    11.02 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           48 |      564 | 2024-04-23 | Zero Tenacity               | L   | 1.000      | -            | -                | -                | -             |   -12.44 | arTisT, Diviiii, Ducky, Girafffe, Vacancy |
|           47 |      927 | 2024-04-17 | BetBoom Team                | L   | 1.000      | -            | -                | -                | -             |    -1.98 | arTisT, Ducky, Girafffe, J3nsyy, Vacancy  |
|           46 |     1057 | 2024-04-15 | UNiTY esports (Slovak team) | L   | 1.000      | -            | -                | -                | -             |   -17.18 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           45 |     1077 | 2024-04-14 | Johnny Speeds               | L   | 1.000      | -            | -                | -                | -             |   -15.53 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           44 |     1155 | 2024-04-12 | Lilmix                      | W   | 1.000      | 0.333        | -                | 0.604 (0.201)    | -             |     6.40 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           43 |     1310 | 2024-04-09 | ROSOMAHA                    | W   | 1.000      | 0.333        | -                | 0.136 (0.045)    | -             |     4.21 | aidKiT, Ducky, Girafffe, Vacancy, Zax1e   |
|           42 |     1415 | 2024-04-06 | BRUTE                       | W   | 1.000      | -            | -                | -                | -             |     2.88 | Diviiii, Ducky, Girafffe, Vacancy, Zax1e  |
|           41 |     1494 | 2024-04-04 | K10                         | L   | 0.991      | -            | -                | -                | -             |   -20.13 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           40 |     1606 | 2024-04-01 | Reason Gaming               | W   | 0.970      | -            | -                | -                | true (0.970)  |     8.93 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           39 |     1626 | 2024-03-31 | Ahoka                       | W   | 0.964      | -            | -                | -                | true (0.964)  |     9.28 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           38 |     1648 | 2024-03-30 | MAMMOTHS2                   | W   | 0.957      | -            | -                | -                | true (0.957)  |     2.07 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           37 |     1738 | 2024-03-27 | Ninjas in Pyjamas           | L   | 0.939      | -            | -                | -                | -             |    -6.91 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           36 |     1751 | 2024-03-27 | Betera Esports              | W   | 0.938      | 0.143        | 0.036 (0.005)    | 0.315 (0.042)    | -             |    12.89 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           35 |     1810 | 2024-03-26 | AMKAL ESPORTS               | W   | 0.932      | 0.143        | 0.209 (0.028)    | 0.756 (0.101)    | -             |    23.48 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           34 |     2050 | 2024-03-19 | EXO Clan                    | L   | 0.886      | -            | -                | -                | -             |   -13.38 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           33 |     2363 | 2024-03-12 | Part Timers                 | W   | 0.839      | -            | -                | -                | -             |     2.74 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           32 |     2505 | 2024-03-09 | ROYALS                      | W   | 0.817      | -            | -                | -                | -             |     4.98 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           31 |     2690 | 2024-03-05 | Dreams To Legends           | W   | 0.792      | -            | -                | -                | -             |     1.40 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           30 |     2930 | 2024-02-29 | Viperio                     | W   | 0.759      | -            | -                | -                | -             |     5.96 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           29 |     2932 | 2024-02-29 | K10                         | L   | 0.759      | -            | -                | -                | -             |   -13.39 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           28 |     2951 | 2024-02-29 | The Chosen Few              | L   | 0.758      | -            | -                | -                | -             |   -15.64 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           27 |     3003 | 2024-02-28 | Sashi Esport                | L   | 0.750      | -            | -                | -                | -             |   -16.18 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           26 |     3100 | 2024-02-25 | Permitta Esports            | L   | 0.731      | -            | -                | -                | -             |    -9.49 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           25 |     3144 | 2024-02-24 | INGLORIOUS                  | L   | 0.726      | -            | -                | -                | -             |   -15.32 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           24 |     3173 | 2024-02-24 | NOM Esports                 | L   | 0.724      | -            | -                | -                | -             |   -19.55 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           23 |     3256 | 2024-02-22 | Ex-Anonymo Esports          | W   | 0.711      | 0.371        | 0.019 (0.005)    | 0.295 (0.078)    | -             |     5.58 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           22 |     3331 | 2024-02-21 | Sashi Esport                | L   | 0.703      | -            | -                | -                | -             |    -7.70 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           21 |     3341 | 2024-02-20 | The Last Resort             | L   | 0.699      | -            | -                | -                | -             |   -18.53 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           20 |     3351 | 2024-02-20 | MOUZ NXT                    | L   | 0.698      | -            | -                | -                | -             |    -8.00 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           19 |     3569 | 2024-02-15 | Team Invictum               | W   | 0.666      | -            | -                | -                | -             |     0.65 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           18 |     3668 | 2024-02-13 | Raptors Esports Club        | W   | 0.652      | 0.143        | 0.017 (0.002)    | -                | -             |     6.38 | arTisT, Ducky, Girafffe, Vacancy, Zax1e   |
|           17 |     5714 | 2023-12-10 | K10                         | L   | 0.219      | -            | -                | -                | -             |    -4.47 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           16 |     5739 | 2023-12-10 | K10                         | W   | 0.217      | -            | -                | -                | true (0.217)  |     2.39 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           15 |     5782 | 2023-12-09 | Raptors Esports Club        | W   | 0.210      | -            | -                | -                | true (0.210)  |     2.17 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           14 |     6197 | 2023-11-30 | BIG Academy                 | L   | 0.152      | -            | -                | -                | -             |    -3.49 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           13 |     6248 | 2023-11-29 | Zero Tenacity               | W   | 0.146      | 0.371        | 0.095 (0.005)    | 1.000 (0.054)    | -             |     2.11 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           12 |     6354 | 2023-11-27 | 9Pandas                     | W   | 0.132      | 0.371        | 0.085 (0.004)    | -                | -             |     2.89 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           11 |     6503 | 2023-11-23 | ALTERNATE aTTaX             | L   | 0.106      | -            | -                | -                | -             |    -1.28 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|           10 |     6553 | 2023-11-22 | For The Win Esports         | L   | 0.099      | -            | -                | -                | -             |    -2.67 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            9 |     6581 | 2023-11-21 | AURORA (Icelandic team)     | W   | 0.092      | -            | -                | -                | -             |     0.10 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            8 |     6720 | 2023-11-18 | Endpoint                    | L   | 0.071      | -            | -                | -                | -             |    -1.57 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            7 |     6923 | 2023-11-14 | Souls-Land                  | W   | 0.045      | -            | -                | -                | -             |     0.06 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            6 |     6939 | 2023-11-14 | For The Win Esports         | L   | 0.043      | -            | -                | -                | -             |    -1.18 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            5 |     6960 | 2023-11-13 | MOUZ NXT                    | L   | 0.039      | -            | -                | -                | -             |    -0.46 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            4 |     7105 | 2023-11-10 | Rhyno Esports               | W   | 0.017      | -            | -                | -                | -             |     0.23 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            3 |     7122 | 2023-11-09 | Insilio                     | W   | 0.013      | -            | -                | -                | -             |     0.16 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            2 |     7128 | 2023-11-09 | GUN5 Esports                | W   | 0.012      | -            | -                | -                | -             |     0.04 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |
|            1 |     7165 | 2023-11-08 | TEAM ZOO BAR                | L   | 0.006      | -            | -                | -                | -             |    -0.16 | arTisT, Ducky, Extinct, Girafffe, Wolfie  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,273.63)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-01 |      0.970 | $3,160.28      | $3,065.10       |
| 2024-03-29 |      0.952 | $315.48        | $300.48         |
| 2024-03-09 |      0.817 | $642.90        | $525.54         |
| 2023-12-10 |      0.219 | $1,505.76      | $329.11         |
| 2023-11-18 |      0.071 | $750.00        | $53.40          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
