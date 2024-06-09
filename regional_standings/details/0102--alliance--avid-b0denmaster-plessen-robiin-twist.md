### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, robiin, twist<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [102](../standings_global.md)<br />
Regional Rank: [72]( ../standings_europe.md)<br />
Final Rank Value:  867.4<br />
<br />
Final Rank Value (867.4) = Starting Rank Value (871.9) + Head To Head Adjustments (-4.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.232<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 871.9
- 400 + ( ( 0.232 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 871.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           71 |      350 | 2024-05-24 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -4.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           70 |     1291 | 2024-05-14 | kONO.ECF            | L   | 1.000      | -            | -                | -                | -         |   -13.13 | avid, b0denmaster, PlesseN, robiin, twist |
|           69 |     2069 | 2024-04-30 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -9.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           68 |     2120 | 2024-04-29 | Endpoint            | W   | 0.995      | 0.384        | 0.012 (0.005)    | 0.770 (0.294)    | 0 (0.000) |    18.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           67 |     2159 | 2024-04-28 | DMS                 | W   | 0.989      | 0.500        | -                | 0.754 (0.373)    | 0 (0.000) |    14.60 | avid, b0denmaster, PlesseN, robiin, twist |
|           66 |     2396 | 2024-04-24 | Kappa Bar           | L   | 0.964      | -            | -                | -                | -         |   -25.88 | avid, b0denmaster, PlesseN, robiin, twist |
|           65 |     2475 | 2024-04-23 | Metizport           | L   | 0.956      | -            | -                | -                | -         |    -8.20 | avid, b0denmaster, PlesseN, robiin, twist |
|           64 |     2517 | 2024-04-22 | B8                  | W   | 0.949      | 0.384        | 0.168 (0.061)    | 0.963 (0.351)    | 0 (0.000) |    21.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           63 |     2578 | 2024-04-21 | Sangal Esports      | L   | 0.941      | -            | -                | -                | -         |    -8.19 | avid, b0denmaster, PlesseN, robiin, twist |
|           62 |     2787 | 2024-04-19 | 9Pandas             | W   | 0.928      | 0.500        | 0.110 (0.051)    | 0.710 (0.329)    | 0 (0.000) |    22.35 | avid, b0denmaster, PlesseN, robiin, twist |
|           61 |     2902 | 2024-04-17 | Nemiga Gaming       | L   | 0.916      | -            | -                | -                | -         |    -4.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           60 |     2921 | 2024-04-17 | Dynamo Eclot        | L   | 0.915      | -            | -                | -                | -         |    -9.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           59 |     3025 | 2024-04-15 | HAVU Gaming         | W   | 0.902      | 0.384        | 0.004 (0.001)    | -                | 0 (0.000) |     8.37 | avid, b0denmaster, PlesseN, robiin, twist |
|           58 |     3030 | 2024-04-15 | MOUZ NXT            | L   | 0.901      | -            | -                | -                | -         |    -6.45 | avid, b0denmaster, PlesseN, robiin, twist |
|           57 |     3116 | 2024-04-13 | ALTERNATE aTTaX     | L   | 0.888      | -            | -                | -                | -         |   -11.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           56 |     3199 | 2024-04-11 | Zero Tenacity       | W   | 0.876      | 0.384        | 0.147 (0.049)    | 1.000 (0.337)    | 0 (0.000) |    17.38 | avid, b0denmaster, PlesseN, robiin, twist |
|           55 |     3324 | 2024-04-09 | BLEED Esports       | L   | 0.863      | -            | -                | -                | -         |    -4.07 | avid, b0denmaster, PlesseN, robiin, twist |
|           54 |     3351 | 2024-04-09 | Astralis Talent     | W   | 0.861      | 0.371        | 0.012 (0.004)    | 0.452 (0.144)    | -         |    14.44 | avid, b0denmaster, PlesseN, robiin, twist |
|           53 |     3415 | 2024-04-07 | Johnny Speeds       | L   | 0.850      | -            | -                | -                | -         |    -8.77 | avid, b0denmaster, PlesseN, robiin, twist |
|           52 |     3429 | 2024-04-07 | EYEBALLERS          | L   | 0.849      | -            | -                | -                | -         |   -11.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           51 |     3451 | 2024-04-06 | Lilmix              | W   | 0.844      | 0.143        | -                | 0.593 (0.072)    | -         |    10.30 | avid, b0denmaster, PlesseN, robiin, twist |
|           50 |     3481 | 2024-04-06 | BetBoom Team        | L   | 0.843      | -            | -                | -                | -         |    -1.72 | avid, b0denmaster, PlesseN, robiin, twist |
|           49 |     3533 | 2024-04-05 | BLEED Esports       | L   | 0.836      | -            | -                | -                | -         |    -3.94 | avid, b0denmaster, PlesseN, robiin, twist |
|           48 |     3575 | 2024-04-04 | BetBoom Team        | L   | 0.831      | -            | -                | -                | -         |    -1.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           47 |     3591 | 2024-04-04 | BenchedHeroes       | W   | 0.829      | -            | -                | -                | -         |     1.72 | avid, b0denmaster, PlesseN, robiin, twist |
|           46 |     3656 | 2024-04-03 | AMKAL ESPORTS       | L   | 0.822      | -            | -                | -                | -         |    -5.15 | avid, b0denmaster, PlesseN, robiin, twist |
|           45 |     3837 | 2024-03-28 | plusW               | W   | 0.783      | -            | -                | -                | -         |     3.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |     4179 | 2024-03-21 | showmakerz          | W   | 0.738      | -            | -                | -                | -         |     3.91 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     4532 | 2024-03-14 | E-Town Gaming       | W   | 0.691      | -            | -                | -                | -         |     1.47 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     4626 | 2024-03-13 | MOUZ NXT            | L   | 0.682      | -            | -                | -                | -         |    -4.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     4693 | 2024-03-12 | Passion UA          | L   | 0.676      | -            | -                | -                | -         |    -8.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     4793 | 2024-03-10 | EYEBALLERS          | W   | 0.663      | -            | -                | -                | -         |    12.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     4830 | 2024-03-09 | Kappa Borr          | W   | 0.657      | -            | -                | -                | -         |     2.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     4848 | 2024-03-09 | Johnny Speeds       | W   | 0.656      | 0.143        | 0.056 (0.005)    | 0.683 (0.064)    | -         |    14.80 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     4851 | 2024-03-09 | Kappa Bar           | W   | 0.656      | -            | -                | -                | -         |     2.81 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     4864 | 2024-03-09 | Entropiq            | W   | 0.656      | -            | -                | -                | -         |     6.64 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     4956 | 2024-03-07 | Sprout              | W   | 0.642      | -            | -                | -                | -         |     5.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     5044 | 2024-03-06 | Sashi Esport        | L   | 0.636      | -            | -                | -                | -         |    -5.10 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     5125 | 2024-03-05 | Viperio             | W   | 0.628      | -            | -                | -                | -         |     5.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     5174 | 2024-03-04 | B8                  | L   | 0.625      | -            | -                | -                | -         |    -3.64 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     5392 | 2024-03-01 | 9INE                | L   | 0.602      | -            | -                | -                | -         |   -15.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     5489 | 2024-02-28 | Sangal Esports      | W   | 0.589      | 0.384        | 0.166 (0.038)    | 0.658 (0.149)    | -         |    13.91 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     5610 | 2024-02-25 | ALTERNATE aTTaX     | W   | 0.570      | 0.143        | 0.052 (0.004)    | 0.735 (0.060)    | -         |    11.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     6062 | 2024-02-18 | esmagaB             | W   | 0.522      | -            | -                | -                | -         |     8.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     6587 | 2024-02-06 | 9INE                | W   | 0.442      | -            | -                | -                | -         |     2.81 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     6665 | 2024-02-04 | Team Secret         | L   | 0.430      | -            | -                | -                | -         |   -10.05 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     6712 | 2024-02-03 | showmakerz          | L   | 0.424      | -            | -                | -                | -         |   -10.94 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     6724 | 2024-02-03 | Maknitude           | W   | 0.424      | -            | -                | -                | -         |     1.87 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     6798 | 2024-02-02 | Metizport           | L   | 0.417      | -            | -                | -                | -         |    -4.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     6808 | 2024-02-02 | venom               | W   | 0.417      | -            | -                | -                | -         |     1.02 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     7053 | 2024-01-29 | Passion UA          | L   | 0.390      | -            | -                | -                | -         |    -3.49 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     7107 | 2024-01-28 | Team Spirit Academy | L   | 0.382      | -            | -                | -                | -         |    -7.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     7378 | 2024-01-24 | Gaimin Gladiators   | L   | 0.355      | -            | -                | -                | -         |    -0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     7788 | 2024-01-17 | UNiTY esports       | L   | 0.311      | -            | -                | -                | -         |    -4.01 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     7900 | 2024-01-16 | Nexus Gaming        | L   | 0.304      | -            | -                | -                | -         |    -4.32 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     7902 | 2024-01-16 | naChille            | W   | 0.304      | -            | -                | -                | -         |     2.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     8100 | 2024-01-12 | ENRAGE              | L   | 0.278      | -            | -                | -                | -         |    -7.59 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     8202 | 2024-01-11 | Betera Esports      | L   | 0.270      | -            | -                | -                | -         |    -4.86 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     8205 | 2024-01-11 | Lazer Cats          | W   | 0.269      | -            | -                | -                | -         |     0.90 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     8556 | 2023-12-30 | The Witchers        | L   | 0.189      | -            | -                | -                | -         |    -4.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     8567 | 2023-12-29 | brazylijski luz     | W   | 0.182      | -            | -                | -                | -         |     2.43 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     8571 | 2023-12-28 | Rhyno Esports       | W   | 0.176      | 0.371        | 0.029 (0.002)    | -                | -         |     3.99 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     8579 | 2023-12-26 | VP.Prodigy          | L   | 0.163      | -            | -                | -                | -         |    -2.69 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     8704 | 2023-12-17 | angelnumbers        | W   | 0.104      | -            | -                | -                | 1 (0.104) |     0.72 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     8728 | 2023-12-17 | Lilmix              | W   | 0.103      | -            | -                | -                | 1 (0.103) |     0.47 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     8750 | 2023-12-17 | onliners5           | W   | 0.102      | -            | -                | -                | 1 (0.102) |     0.60 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     9197 | 2023-12-11 | ex-Sprout           | L   | 0.064      | -            | -                | -                | -         |    -1.59 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     9312 | 2023-12-09 | Kappa Bar           | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.17 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     9521 | 2023-12-06 | ex-Sprout           | W   | 0.029      | -            | -                | -                | -         |     0.19 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     9659 | 2023-12-03 | Ninjas in Pyjamas   | L   | 0.010      | -            | -                | -                | -         |    -0.20 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     9768 | 2023-12-02 | EYEBALLERS          | L   | 0.003      | -            | -                | -                | -         |    -0.04 | avid, b0denmaster, PlesseN, robiin, twist |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,296.19)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $500.00        | $500.00         |
| 2023-12-17 |      0.104 | $5,888.04      | $614.97         |
| 2023-12-13 |      0.078 | $500.00        | $38.76          |
| 2023-12-09 |      0.049 | $2,388.48      | $116.16         |
| 2023-12-03 |      0.011 | $2,396.52      | $26.30          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
