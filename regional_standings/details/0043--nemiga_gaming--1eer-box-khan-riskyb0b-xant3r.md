### Roster Details<br />
Team Name: Nemiga Gaming<br />
Roster: 1eeR, boX, khaN, riskyb0b, Xant3r<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [43](../standings_global.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
Final Rank Value:  1078.9<br />
<br />
Final Rank Value (1078.9) = Starting Rank Value (1254.8) + Head To Head Adjustments (-175.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.696[<sup>1</sup>](#table2)
- Bounty Collected: 0.464[<sup>2</sup>](#table1)
- Opponent Network: 0.429[<sup>2</sup>](#table1)
- LAN Wins: 0.091[<sup>2</sup>](#table1)

The average of these factors is 0.420<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1254.8
- 400 + ( ( 0.420 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1254.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           81 |      352 | 2024-05-24 | Endpoint               | L   | 1.000      | -            | -                | -                | -         |   -23.70 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           80 |      360 | 2024-05-24 | VP.Prodigy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.51 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           79 |      616 | 2024-05-21 | CYBERSHOKE Esports     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.72 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           78 |      675 | 2024-05-20 | V1dar Gaming           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.48 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           77 |      900 | 2024-05-18 | GUN5 Esports           | L   | 1.000      | -            | -                | -                | -         |   -27.21 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           76 |      925 | 2024-05-18 | naChille               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.86 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           75 |     1086 | 2024-05-16 | Entropiq               | L   | 1.000      | -            | -                | -                | -         |   -28.91 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           74 |     1327 | 2024-05-13 | RUSH B                 | L   | 1.000      | -            | -                | -                | -         |   -27.08 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           73 |     1332 | 2024-05-13 | VP.Prodigy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.56 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           72 |     1533 | 2024-05-10 | RUBY                   | L   | 1.000      | -            | -                | -                | -         |   -24.06 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           71 |     1625 | 2024-05-08 | ARCRED                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.03 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           70 |     1636 | 2024-05-08 | Rhyno Esports          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.29 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           69 |     1652 | 2024-05-08 | 1win                   | L   | 1.000      | -            | -                | -                | -         |   -21.71 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           68 |     1694 | 2024-05-07 | SINNERS Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.76 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           67 |     1719 | 2024-05-06 | LODIS                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.04 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           66 |     1725 | 2024-05-06 | MOUZ NXT               | L   | 1.000      | -            | -                | -                | -         |   -22.09 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           65 |     1731 | 2024-05-06 | Team Spirit Academy    | W   | 1.000      | -            | -                | -                | -         |     1.84 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           64 |     1763 | 2024-05-05 | VP.Prodigy             | W   | 1.000      | -            | -                | -                | -         |     2.82 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           63 |     1881 | 2024-05-03 | MOUZ NXT               | W   | 1.000      | 0.500        | 0.157 (0.079)    | 0.950 (0.475)    | -         |     9.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           62 |     1921 | 2024-05-02 | Passion UA             | W   | 1.000      | 0.500        | 0.057 (0.028)    | 1.000 (0.500)    | -         |     5.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           61 |     1965 | 2024-05-01 | B8                     | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.952 (0.476)    | -         |    10.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           60 |     2055 | 2024-04-29 | MOUZ NXT               | W   | 0.997      | 0.500        | 0.157 (0.078)    | 0.950 (0.473)    | -         |    10.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           59 |     2130 | 2024-04-28 | Grannys Knockers       | L   | 0.988      | -            | -                | -                | -         |   -27.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           58 |     2193 | 2024-04-27 | 1win                   | W   | 0.982      | 0.500        | -                | 0.887 (0.436)    | -         |     8.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           57 |     2279 | 2024-04-26 | Sangal Esports         | L   | 0.975      | -            | -                | -                | -         |   -22.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           56 |     2366 | 2024-04-24 | kONO.ECF               | W   | 0.964      | -            | -                | -                | -         |     4.76 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           55 |     2378 | 2024-04-24 | BLEED Esports          | W   | 0.963      | 0.500        | 0.248 (0.119)    | 0.677 (0.326)    | -         |    16.69 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           54 |     2407 | 2024-04-23 | EXO Clan               | L   | 0.957      | -            | -                | -                | -         |   -22.37 | 1eeR, boX, khaN, riskyb0b, Xant3r     |
|           53 |     2430 | 2024-04-23 | Zero Tenacity          | W   | 0.956      | 0.500        | 0.147 (0.070)    | 1.000 (0.478)    | -         |     7.33 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           52 |     2471 | 2024-04-22 | MOUZ NXT               | W   | 0.948      | 0.500        | 0.157 (0.074)    | 0.950 (0.450)    | -         |     9.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           51 |     2504 | 2024-04-21 | Team PeeP              | W   | 0.943      | -            | -                | -                | -         |     0.94 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           50 |     2519 | 2024-04-21 | 1win                   | W   | 0.942      | 0.435        | -                | 0.887 (0.363)    | -         |     8.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           49 |     2642 | 2024-04-20 | Gaimin Gladiators      | L   | 0.935      | -            | -                | -                | -         |   -11.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           48 |     2707 | 2024-04-19 | Sangal Esports         | W   | 0.930      | 0.500        | 0.166 (0.077)    | -                | -         |     7.38 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           47 |     2769 | 2024-04-18 | Team Secret            | W   | 0.923      | -            | -                | -                | -         |     1.59 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           46 |     2846 | 2024-04-17 | Alliance               | W   | 0.916      | -            | -                | -                | -         |     4.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           45 |     3211 | 2024-04-09 | FlyQuest               | L   | 0.867      | -            | -                | -                | -         |    -5.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           44 |     3270 | 2024-04-09 | Steel Helmet           | W   | 0.861      | -            | -                | -                | 1 (0.861) |     1.39 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           43 |     3313 | 2024-04-08 | FaZe Clan              | L   | 0.855      | -            | -                | -                | -         |    -0.36 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           42 |     3632 | 2024-04-01 | Zero Tenacity          | W   | 0.808      | 0.384        | 0.147 (0.046)    | 1.000 (0.311)    | -         |     6.99 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           41 |     3866 | 2024-03-26 | AURA                   | L   | 0.771      | -            | -                | -                | -         |   -23.01 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           40 |     4032 | 2024-03-22 | Sashi Esport           | L   | 0.744      | -            | -                | -                | -         |   -16.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           39 |     4557 | 2024-03-12 | Nexus Gaming           | L   | 0.677      | -            | -                | -                | -         |   -17.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           38 |     4625 | 2024-03-11 | Sashi Esport           | W   | 0.670      | 0.371        | 0.172 (0.043)    | -                | -         |     4.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           37 |     4664 | 2024-03-10 | Endpoint               | W   | 0.664      | -            | -                | -                | -         |     3.23 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           36 |     4946 | 2024-03-05 | KOI                    | L   | 0.631      | -            | -                | -                | -         |   -15.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           35 |     4959 | 2024-03-05 | GUN5 Esports           | W   | 0.631      | -            | -                | -                | -         |     0.75 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           34 |     5000 | 2024-03-04 | ENTERPRISE esports     | W   | 0.625      | -            | -                | -                | -         |     3.06 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           33 |     5030 | 2024-03-04 | Aurora Young Blud      | W   | 0.625      | -            | -                | -                | -         |     1.28 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           32 |     5158 | 2024-03-02 | kONO.ECF               | L   | 0.611      | -            | -                | -                | -         |   -16.64 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           31 |     5730 | 2024-02-21 | Insilio                | W   | 0.543      | -            | -                | -                | -         |     2.59 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           30 |     5774 | 2024-02-20 | NOM Esports            | W   | 0.536      | -            | -                | -                | -         |     0.47 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           29 |     5829 | 2024-02-19 | FORZE Youngsters       | W   | 0.531      | -            | -                | -                | -         |     0.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           28 |     5835 | 2024-02-19 | Endpoint               | W   | 0.530      | -            | -                | -                | -         |     2.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           27 |     5879 | 2024-02-18 | GUN5 Esports           | L   | 0.523      | -            | -                | -                | -         |   -16.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           26 |     6158 | 2024-02-13 | 1win                   | W   | 0.490      | -            | -                | -                | -         |     2.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           25 |     6209 | 2024-02-12 | Team Secret            | W   | 0.484      | -            | -                | -                | -         |     0.48 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           24 |     6212 | 2024-02-12 | ILIN                   | W   | 0.484      | -            | -                | -                | -         |     0.26 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           23 |     6253 | 2024-02-10 | Sashi Esport           | W   | 0.471      | -            | -                | -                | -         |     3.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           22 |     6293 | 2024-02-09 | AMKAL ESPORTS          | W   | 0.464      | -            | -                | -                | -         |     6.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           21 |     6322 | 2024-02-08 | Sashi Esport           | W   | 0.458      | -            | -                | -                | -         |     3.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           20 |     6335 | 2024-02-08 | BetBoom Team           | W   | 0.457      | -            | -                | -                | -         |    10.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           19 |     6424 | 2024-02-05 | Kappa Bar              | W   | 0.437      | -            | -                | -                | -         |     0.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           18 |     6677 | 2024-02-01 | Lausanne-Sport Esports | L   | 0.410      | -            | -                | -                | -         |   -12.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           17 |     6749 | 2024-01-30 | RUBY                   | W   | 0.398      | -            | -                | -                | -         |     1.73 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           16 |     6752 | 2024-01-30 | Sprout                 | W   | 0.398      | -            | -                | -                | -         |     0.41 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           15 |     6758 | 2024-01-30 | 9Pandas                | W   | 0.397      | -            | -                | -                | -         |     5.07 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           14 |     6784 | 2024-01-29 | Aurora Gaming          | W   | 0.392      | -            | -                | -                | -         |     9.58 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           13 |     6805 | 2024-01-29 | Endpoint               | W   | 0.392      | -            | -                | -                | -         |     1.89 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           12 |     7120 | 2024-01-24 | ex-Hot Headed Gaming   | W   | 0.357      | -            | -                | -                | -         |     0.19 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           11 |     7123 | 2024-01-24 | GODSENT                | W   | 0.357      | -            | -                | -                | -         |     0.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           10 |     7567 | 2024-01-17 | ex-Preasy Esport       | L   | 0.311      | -            | -                | -                | -         |    -8.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            9 |     7641 | 2024-01-16 | samaloyod              | L   | 0.305      | -            | -                | -                | -         |    -9.42 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            8 |     7683 | 2024-01-16 | Betera Esports         | W   | 0.304      | -            | -                | -                | -         |     0.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            7 |     8090 | 2024-01-09 | brazylijski luz        | L   | 0.257      | -            | -                | -                | -         |    -7.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            6 |     8105 | 2024-01-09 | HEROIC                 | W   | 0.257      | -            | -                | -                | -         |     7.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            5 |     8508 | 2023-12-17 | LF0                    | W   | 0.102      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            4 |     8623 | 2023-12-16 | VP.Prodigy             | W   | 0.096      | -            | -                | -                | -         |     0.27 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            3 |     8645 | 2023-12-16 | BAKS Esports           | W   | 0.095      | -            | -                | -                | -         |     0.09 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|            2 |     9214 | 2023-12-06 | ENTERPRISE esports     | L   | 0.031      | -            | -                | -                | -         |    -0.84 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            1 |     9234 | 2023-12-06 | MOUZ NXT               | L   | 0.029      | -            | -                | -                | -         |    -0.63 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($109,983.53)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.37) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-09 |      1.000 | $5,064.11      | $5,064.11       |
| 2024-05-03 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-04-24 |      0.963 | $50,000.00     | $48,152.78      |
| 2024-04-14 |      0.895 | $5,000.00      | $4,475.81       |
| 2024-03-25 |      0.764 | $3,000.00      | $2,290.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
