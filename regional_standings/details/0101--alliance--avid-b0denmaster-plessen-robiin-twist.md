### Roster Details<br />
Team Name: Alliance<br />
Roster: avid, b0denmaster, PlesseN, robiin, twist<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [101](../standings_global.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
Final Rank Value:  866.5<br />
<br />
Final Rank Value (866.5) = Starting Rank Value (868.9) + Head To Head Adjustments (-2.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.297[<sup>1</sup>](#table2)
- Bounty Collected: 0.376[<sup>2</sup>](#table1)
- Opponent Network: 0.210[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.9
- 400 + ( ( 0.230 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 868.9


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
|           70 |      341 | 2024-05-24 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -4.74 | avid, b0denmaster, PlesseN, robiin, twist |
|           69 |     1280 | 2024-05-14 | kONO.ECF            | L   | 1.000      | -            | -                | -                | -         |   -13.44 | avid, b0denmaster, PlesseN, robiin, twist |
|           68 |     2036 | 2024-04-30 | B8                  | L   | 1.000      | -            | -                | -                | -         |    -8.95 | avid, b0denmaster, PlesseN, robiin, twist |
|           67 |     2085 | 2024-04-29 | Endpoint            | W   | 0.995      | 0.384        | 0.012 (0.005)    | 0.718 (0.275)    | 0 (0.000) |    17.09 | avid, b0denmaster, PlesseN, robiin, twist |
|           66 |     2124 | 2024-04-28 | DMS                 | W   | 0.989      | 0.500        | -                | 0.751 (0.371)    | 0 (0.000) |    14.22 | avid, b0denmaster, PlesseN, robiin, twist |
|           65 |     2355 | 2024-04-24 | Kappa Bar           | L   | 0.964      | -            | -                | -                | -         |   -25.88 | avid, b0denmaster, PlesseN, robiin, twist |
|           64 |     2427 | 2024-04-23 | Metizport           | L   | 0.956      | -            | -                | -                | -         |    -7.94 | avid, b0denmaster, PlesseN, robiin, twist |
|           63 |     2465 | 2024-04-22 | B8                  | W   | 0.949      | 0.384        | 0.168 (0.061)    | 0.952 (0.347)    | 0 (0.000) |    22.35 | avid, b0denmaster, PlesseN, robiin, twist |
|           62 |     2525 | 2024-04-21 | Sangal Esports      | L   | 0.941      | -            | -                | -                | -         |    -9.66 | avid, b0denmaster, PlesseN, robiin, twist |
|           61 |     2731 | 2024-04-19 | 9Pandas             | W   | 0.928      | 0.500        | 0.110 (0.051)    | 0.660 (0.306)    | 0 (0.000) |    21.93 | avid, b0denmaster, PlesseN, robiin, twist |
|           60 |     2846 | 2024-04-17 | Nemiga Gaming       | L   | 0.916      | -            | -                | -                | -         |    -4.01 | avid, b0denmaster, PlesseN, robiin, twist |
|           59 |     2864 | 2024-04-17 | Dynamo Eclot        | L   | 0.915      | -            | -                | -                | -         |    -9.73 | avid, b0denmaster, PlesseN, robiin, twist |
|           58 |     2961 | 2024-04-15 | HAVU Gaming         | W   | 0.902      | 0.384        | 0.004 (0.001)    | -                | 0 (0.000) |     8.29 | avid, b0denmaster, PlesseN, robiin, twist |
|           57 |     2965 | 2024-04-15 | MOUZ NXT            | L   | 0.901      | -            | -                | -                | -         |    -6.79 | avid, b0denmaster, PlesseN, robiin, twist |
|           56 |     3050 | 2024-04-13 | ALTERNATE aTTaX     | L   | 0.888      | -            | -                | -                | -         |   -11.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           55 |     3129 | 2024-04-11 | Zero Tenacity       | W   | 0.876      | 0.384        | 0.147 (0.049)    | 1.000 (0.337)    | 0 (0.000) |    17.68 | avid, b0denmaster, PlesseN, robiin, twist |
|           54 |     3245 | 2024-04-09 | BLEED Esports       | L   | 0.863      | -            | -                | -                | -         |    -3.95 | avid, b0denmaster, PlesseN, robiin, twist |
|           53 |     3271 | 2024-04-09 | Astralis Talent     | W   | 0.861      | 0.371        | 0.012 (0.004)    | 0.452 (0.144)    | -         |    14.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           52 |     3334 | 2024-04-07 | Johnny Speeds       | L   | 0.850      | -            | -                | -                | -         |    -8.85 | avid, b0denmaster, PlesseN, robiin, twist |
|           51 |     3348 | 2024-04-07 | EYEBALLERS          | L   | 0.849      | -            | -                | -                | -         |   -11.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           50 |     3368 | 2024-04-06 | Lilmix              | W   | 0.844      | 0.143        | -                | 0.581 (0.070)    | -         |    10.61 | avid, b0denmaster, PlesseN, robiin, twist |
|           49 |     3398 | 2024-04-06 | BetBoom Team        | L   | 0.843      | -            | -                | -                | -         |    -1.75 | avid, b0denmaster, PlesseN, robiin, twist |
|           48 |     3449 | 2024-04-05 | BLEED Esports       | L   | 0.836      | -            | -                | -                | -         |    -3.81 | avid, b0denmaster, PlesseN, robiin, twist |
|           47 |     3490 | 2024-04-04 | BetBoom Team        | L   | 0.831      | -            | -                | -                | -         |    -1.86 | avid, b0denmaster, PlesseN, robiin, twist |
|           46 |     3505 | 2024-04-04 | BenchedHeroes       | W   | 0.829      | -            | -                | -                | -         |     1.72 | avid, b0denmaster, PlesseN, robiin, twist |
|           45 |     3569 | 2024-04-03 | AMKAL ESPORTS       | L   | 0.822      | -            | -                | -                | -         |    -5.21 | avid, b0denmaster, PlesseN, robiin, twist |
|           44 |     3744 | 2024-03-28 | plusW               | W   | 0.783      | -            | -                | -                | -         |     3.61 | avid, b0denmaster, PlesseN, robiin, twist |
|           43 |     4081 | 2024-03-21 | showmakerz          | W   | 0.738      | -            | -                | -                | -         |     3.80 | avid, b0denmaster, PlesseN, robiin, twist |
|           42 |     4418 | 2024-03-14 | E-Town Gaming       | W   | 0.691      | -            | -                | -                | -         |     1.46 | avid, b0denmaster, PlesseN, robiin, twist |
|           41 |     4510 | 2024-03-13 | MOUZ NXT            | L   | 0.682      | -            | -                | -                | -         |    -5.15 | avid, b0denmaster, PlesseN, robiin, twist |
|           40 |     4572 | 2024-03-12 | Passion UA          | L   | 0.676      | -            | -                | -                | -         |    -8.91 | avid, b0denmaster, PlesseN, robiin, twist |
|           39 |     4668 | 2024-03-10 | EYEBALLERS          | W   | 0.663      | -            | -                | -                | -         |    12.01 | avid, b0denmaster, PlesseN, robiin, twist |
|           38 |     4705 | 2024-03-09 | Kappa Borr          | W   | 0.657      | -            | -                | -                | -         |     2.27 | avid, b0denmaster, PlesseN, robiin, twist |
|           37 |     4723 | 2024-03-09 | Johnny Speeds       | W   | 0.656      | 0.143        | 0.056 (0.005)    | 0.683 (0.064)    | -         |    14.72 | avid, b0denmaster, PlesseN, robiin, twist |
|           36 |     4726 | 2024-03-09 | Kappa Bar           | W   | 0.656      | -            | -                | -                | -         |     2.77 | avid, b0denmaster, PlesseN, robiin, twist |
|           35 |     4738 | 2024-03-09 | Entropiq            | W   | 0.656      | -            | -                | -                | -         |     6.54 | avid, b0denmaster, PlesseN, robiin, twist |
|           34 |     4826 | 2024-03-07 | Sprout              | W   | 0.642      | -            | -                | -                | -         |     5.55 | avid, b0denmaster, PlesseN, robiin, twist |
|           33 |     4979 | 2024-03-05 | Viperio             | W   | 0.628      | -            | -                | -                | -         |     5.16 | avid, b0denmaster, PlesseN, robiin, twist |
|           32 |     5028 | 2024-03-04 | B8                  | L   | 0.625      | -            | -                | -                | -         |    -3.62 | avid, b0denmaster, PlesseN, robiin, twist |
|           31 |     5243 | 2024-03-01 | 9INE                | L   | 0.602      | -            | -                | -                | -         |   -15.71 | avid, b0denmaster, PlesseN, robiin, twist |
|           30 |     5337 | 2024-02-28 | Sangal Esports      | W   | 0.589      | 0.384        | 0.166 (0.038)    | 0.577 (0.131)    | -         |    13.53 | avid, b0denmaster, PlesseN, robiin, twist |
|           29 |     5452 | 2024-02-25 | ALTERNATE aTTaX     | W   | 0.570      | 0.143        | 0.052 (0.004)    | 0.679 (0.055)    | -         |    12.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           28 |     5889 | 2024-02-18 | esmagaB             | W   | 0.522      | -            | -                | -                | -         |     8.12 | avid, b0denmaster, PlesseN, robiin, twist |
|           27 |     6391 | 2024-02-06 | 9INE                | W   | 0.442      | -            | -                | -                | -         |     2.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           26 |     6462 | 2024-02-04 | Team Secret         | L   | 0.430      | -            | -                | -                | -         |   -10.06 | avid, b0denmaster, PlesseN, robiin, twist |
|           25 |     6509 | 2024-02-03 | showmakerz          | L   | 0.424      | -            | -                | -                | -         |   -10.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           24 |     6521 | 2024-02-03 | Maknitude           | W   | 0.424      | -            | -                | -                | -         |     1.89 | avid, b0denmaster, PlesseN, robiin, twist |
|           23 |     6595 | 2024-02-02 | Metizport           | L   | 0.417      | -            | -                | -                | -         |    -4.24 | avid, b0denmaster, PlesseN, robiin, twist |
|           22 |     6605 | 2024-02-02 | venom               | W   | 0.417      | -            | -                | -                | -         |     1.03 | avid, b0denmaster, PlesseN, robiin, twist |
|           21 |     6837 | 2024-01-29 | Passion UA          | L   | 0.390      | -            | -                | -                | -         |    -3.58 | avid, b0denmaster, PlesseN, robiin, twist |
|           20 |     6889 | 2024-01-28 | Team Spirit Academy | L   | 0.382      | -            | -                | -                | -         |    -7.83 | avid, b0denmaster, PlesseN, robiin, twist |
|           19 |     7143 | 2024-01-24 | Gaimin Gladiators   | L   | 0.355      | -            | -                | -                | -         |    -0.97 | avid, b0denmaster, PlesseN, robiin, twist |
|           18 |     7539 | 2024-01-17 | UNiTY esports       | L   | 0.311      | -            | -                | -                | -         |    -3.99 | avid, b0denmaster, PlesseN, robiin, twist |
|           17 |     7651 | 2024-01-16 | Nexus Gaming        | L   | 0.304      | -            | -                | -                | -         |    -4.05 | avid, b0denmaster, PlesseN, robiin, twist |
|           16 |     7653 | 2024-01-16 | naChille            | W   | 0.304      | -            | -                | -                | -         |     2.25 | avid, b0denmaster, PlesseN, robiin, twist |
|           15 |     7847 | 2024-01-12 | ENRAGE              | L   | 0.278      | -            | -                | -                | -         |    -7.57 | avid, b0denmaster, PlesseN, robiin, twist |
|           14 |     7949 | 2024-01-11 | Betera Esports      | L   | 0.270      | -            | -                | -                | -         |    -4.84 | avid, b0denmaster, PlesseN, robiin, twist |
|           13 |     7952 | 2024-01-11 | Lazer Cats          | W   | 0.269      | -            | -                | -                | -         |     0.92 | avid, b0denmaster, PlesseN, robiin, twist |
|           12 |     8300 | 2023-12-30 | The Witchers        | L   | 0.189      | -            | -                | -                | -         |    -4.23 | avid, b0denmaster, PlesseN, robiin, twist |
|           11 |     8310 | 2023-12-29 | brazylijski luz     | W   | 0.182      | -            | -                | -                | -         |     2.42 | avid, b0denmaster, PlesseN, robiin, twist |
|           10 |     8314 | 2023-12-28 | Rhyno Esports       | W   | 0.176      | 0.371        | 0.029 (0.002)    | -                | -         |     3.99 | avid, b0denmaster, PlesseN, robiin, twist |
|            9 |     8322 | 2023-12-26 | VP.Prodigy          | L   | 0.163      | -            | -                | -                | -         |    -2.73 | avid, b0denmaster, PlesseN, robiin, twist |
|            8 |     8446 | 2023-12-17 | angelnumbers        | W   | 0.104      | -            | -                | -                | 1 (0.104) |     0.73 | avid, b0denmaster, PlesseN, robiin, twist |
|            7 |     8468 | 2023-12-17 | Lilmix              | W   | 0.103      | -            | -                | -                | 1 (0.103) |     0.47 | avid, b0denmaster, PlesseN, robiin, twist |
|            6 |     8490 | 2023-12-17 | onliners5           | W   | 0.102      | -            | -                | -                | 1 (0.102) |     0.61 | avid, b0denmaster, PlesseN, robiin, twist |
|            5 |     8931 | 2023-12-11 | ex-Sprout           | L   | 0.064      | -            | -                | -                | -         |    -1.59 | avid, b0denmaster, PlesseN, robiin, twist |
|            4 |     9045 | 2023-12-09 | Kappa Bar           | W   | 0.049      | -            | -                | -                | 1 (0.049) |     0.18 | avid, b0denmaster, PlesseN, robiin, twist |
|            3 |     9240 | 2023-12-06 | ex-Sprout           | W   | 0.029      | -            | -                | -                | -         |     0.19 | avid, b0denmaster, PlesseN, robiin, twist |
|            2 |     9377 | 2023-12-03 | Ninjas in Pyjamas   | L   | 0.010      | -            | -                | -                | -         |    -0.20 | avid, b0denmaster, PlesseN, robiin, twist |
|            1 |     9486 | 2023-12-02 | EYEBALLERS          | L   | 0.003      | -            | -                | -                | -         |    -0.04 | avid, b0denmaster, PlesseN, robiin, twist |

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
