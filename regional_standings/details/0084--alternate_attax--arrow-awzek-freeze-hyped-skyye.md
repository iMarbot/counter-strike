### Roster Details<br />
Team Name: ALTERNATE aTTaX<br />
Roster: ArroW, awzek, FreeZe, hyped, skyye<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [84](../standings_global.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
Final Rank Value:  900.0<br />
<br />
Final Rank Value (900.0) = Starting Rank Value (984.8) + Head To Head Adjustments (-84.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.437[<sup>1</sup>](#table2)
- Bounty Collected: 0.393[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.287<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 984.8
- 400 + ( ( 0.287 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 984.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           78 |      263 | 2024-05-25 | TeamOrangeGaming    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.86 | ArroW, awzek, FreeZe, hyped, skyye   |
|           77 |      364 | 2024-05-24 | Endpoint            | L   | 1.000      | -            | -                | -                | -         |   -16.79 | ArroW, awzek, FreeZe, hyped, PerX    |
|           76 |      402 | 2024-05-23 | ARROW               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.97 | ArroW, awzek, FreeZe, hyped, skyye   |
|           75 |      417 | 2024-05-23 | Entropiq            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | ArroW, awzek, FreeZe, hyped, PerX    |
|           74 |      458 | 2024-05-22 | VP.Prodigy          | L   | 1.000      | -            | -                | -                | -         |   -17.55 | ArroW, awzek, FreeZe, hyped, PerX    |
|           73 |      804 | 2024-05-19 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |   -14.68 | ArroW, awzek, FreeZe, hyped, PerX    |
|           72 |      929 | 2024-05-18 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -4.57 | ArroW, awzek, FreeZe, hyped, PerX    |
|           71 |      964 | 2024-05-17 | EYEBALLERS          | L   | 1.000      | -            | -                | -                | -         |   -16.33 | ArroW, awzek, FreeZe, hyped, PerX    |
|           70 |     1082 | 2024-05-16 | 9Pandas             | L   | 1.000      | -            | -                | -                | -         |    -9.79 | ArroW, awzek, FreeZe, hyped, PerX    |
|           69 |     1106 | 2024-05-16 | SINNERS Esports     | L   | 1.000      | -            | -                | -                | -         |   -14.62 | ArroW, awzek, FreeZe, hyped, PerX    |
|           68 |     1251 | 2024-05-14 | Pera Esports        | L   | 1.000      | -            | -                | -                | -         |   -19.10 | ArroW, awzek, FreeZe, hyped, skyye   |
|           67 |     1291 | 2024-05-14 | Endpoint            | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.718 (0.312)    | 0 (0.000) |    14.32 | ArroW, awzek, FreeZe, hyped, PerX    |
|           66 |     1321 | 2024-05-13 | EVOPLAY             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.27 | ArroW, awzek, FreeZe, hyped, skyye   |
|           65 |     1346 | 2024-05-12 | SNOGARD Dragons     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.38 | ArroW, awzek, FreeZe, hyped, skyye   |
|           64 |     1351 | 2024-05-12 | Sissi State Punks   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.90 | ArroW, awzek, FreeZe, hyped, skyye   |
|           63 |     1726 | 2024-05-06 | Sashi Esport        | L   | 1.000      | -            | -                | -                | -         |    -4.86 | ArroW, awzek, FreeZe, hyped, PerX    |
|           62 |     1929 | 2024-05-02 | MOUZ NXT            | L   | 1.000      | -            | -                | -                | -         |   -10.76 | ArroW, awzek, FreeZe, hyped, PerX    |
|           61 |     1993 | 2024-05-01 | Team Sampi          | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    16.88 | ArroW, awzek, FreeZe, hyped, PerX    |
|           60 |     2004 | 2024-05-01 | Sangal Esports      | W   | 1.000      | 0.500        | 0.166 (0.083)    | 0.577 (0.288)    | 0 (0.000) |    19.90 | ArroW, awzek, FreeZe, hyped, PerX    |
|           59 |     2028 | 2024-04-30 | Endpoint            | L   | 1.000      | -            | -                | -                | -         |   -15.70 | ArroW, awzek, FreeZe, hyped, PerX    |
|           58 |     2042 | 2024-04-30 | Team Sampi          | W   | 1.000      | 0.143        | 0.039 (0.006)    | -                | 0 (0.000) |    17.81 | ArroW, awzek, FreeZe, hyped, PerX    |
|           57 |     2110 | 2024-04-28 | Passion UA          | W   | 0.990      | 0.500        | 0.057 (0.028)    | 1.000 (0.495)    | -         |    15.43 | ArroW, awzek, FreeZe, hyped, PerX    |
|           56 |     2253 | 2024-04-26 | Astralis Talent     | L   | 0.977      | -            | -                | -                | -         |   -17.96 | ArroW, awzek, FreeZe, hyped, skyye   |
|           55 |     2282 | 2024-04-26 | Gaimin Gladiators   | W   | 0.975      | 0.500        | 0.092 (0.045)    | 0.711 (0.347)    | -         |    26.27 | ArroW, awzek, FreeZe, hyped, PerX    |
|           54 |     2324 | 2024-04-25 | Team Space          | W   | 0.969      | -            | -                | -                | -         |    11.23 | ArroW, awzek, FreeZe, hyped, PerX    |
|           53 |     2377 | 2024-04-24 | Astralis Talent     | L   | 0.963      | -            | -                | -                | -         |   -17.21 | ArroW, FreeZe, hyped, PerX, skyye    |
|           52 |     2435 | 2024-04-23 | ENTERPRISE esports  | W   | 0.955      | 0.384        | -                | 0.809 (0.297)    | -         |    14.29 | ArroW, FreeZe, hyped, PerX, skyye    |
|           51 |     2438 | 2024-04-22 | Permitta Esports    | L   | 0.954      | -            | -                | -                | -         |   -12.67 | ArroW, FreeZe, hyped, PerX, skyye    |
|           50 |     2468 | 2024-04-22 | ENCE Academy        | W   | 0.948      | -            | -                | -                | -         |    12.08 | ArroW, FreeZe, hyped, PerX, skyye    |
|           49 |     2500 | 2024-04-21 | MOUZ NXT            | L   | 0.943      | -            | -                | -                | -         |    -8.36 | ArroW, awzek, FreeZe, hyped, skyye   |
|           48 |     2531 | 2024-04-21 | Team Sampi          | L   | 0.941      | -            | -                | -                | -         |   -10.97 | ArroW, FreeZe, hyped, PerX, skyye    |
|           47 |     2565 | 2024-04-20 | Team Space          | L   | 0.937      | -            | -                | -                | -         |   -19.61 | ArroW, awzek, FreeZe, hyped, skyye   |
|           46 |     2647 | 2024-04-20 | ENTERPRISE esports  | W   | 0.935      | 0.500        | -                | 0.809 (0.378)    | -         |    13.55 | ArroW, awzek, FreeZe, hyped, skyye   |
|           45 |     2710 | 2024-04-19 | Passion UA          | W   | 0.929      | 0.371        | 0.057 (0.019)    | 1.000 (0.344)    | -         |    15.76 | ArroW, FreeZe, hyped, PerX, skyye    |
|           44 |     2725 | 2024-04-19 | Zero Tenacity       | L   | 0.929      | -            | -                | -                | -         |   -12.72 | ArroW, awzek, FreeZe, hyped, skyye   |
|           43 |     2783 | 2024-04-18 | HAVU Gaming         | L   | 0.922      | -            | -                | -                | -         |   -22.57 | ArroW, awzek, FreeZe, hyped, skyye   |
|           42 |     2794 | 2024-04-18 | BLEED Esports       | L   | 0.921      | -            | -                | -                | -         |    -5.41 | ArroW, awzek, FreeZe, hyped, skyye   |
|           41 |     2841 | 2024-04-17 | TeamOrangeGaming    | W   | 0.917      | -            | -                | -                | -         |     7.26 | ArroW, awzek, FoG, FreeZe, hyped     |
|           40 |     2925 | 2024-04-16 | Aurora Young Blud   | W   | 0.909      | -            | -                | -                | -         |     6.75 | ArroW, awzek, FreeZe, hyped, skyye   |
|           39 |     2949 | 2024-04-15 | Zero Tenacity       | L   | 0.904      | -            | -                | -                | -         |   -13.48 | ArroW, awzek, FreeZe, hyped, skyye   |
|           38 |     3050 | 2024-04-13 | Alliance            | W   | 0.888      | -            | -                | -                | -         |    11.62 | ArroW, FreeZe, hyped, PerX, skyye    |
|           37 |     3076 | 2024-04-12 | Wave Esports        | W   | 0.883      | -            | -                | -                | -         |     3.27 | ArroW, devils, FreeZe, hyped, Rulz   |
|           36 |     3264 | 2024-04-09 | Dynamo Eclot        | W   | 0.862      | 0.371        | 0.097 (0.031)    | 0.936 (0.299)    | -         |    16.66 | ArroW, FreeZe, hyped, PerX, skyye    |
|           35 |     3312 | 2024-04-08 | SINNERS Esports     | L   | 0.855      | -            | -                | -                | -         |    -9.87 | ArroW, awzek, FreeZe, hyped, skyye   |
|           34 |     3504 | 2024-04-04 | Rebels Gaming       | L   | 0.830      | -            | -                | -                | -         |    -7.58 | ArroW, awzek, FreeZe, hyped, skyye   |
|           33 |     3614 | 2024-04-02 | AMKAL ESPORTS       | L   | 0.815      | -            | -                | -                | -         |    -6.56 | ArroW, awzek, FreeZe, hyped, skyye   |
|           32 |     3782 | 2024-03-27 | FAVBET Team         | L   | 0.778      | -            | -                | -                | -         |   -13.80 | ArroW, awzek, FreeZe, hyped, skyye   |
|           31 |     3797 | 2024-03-27 | ex-Guild Eagles     | W   | 0.777      | -            | -                | -                | -         |    12.15 | ArroW, awzek, FreeZe, hyped, skyye   |
|           30 |     3812 | 2024-03-27 | Heimo Esports       | W   | 0.777      | -            | -                | -                | -         |     5.87 | ArroW, awzek, FreeZe, hyped, skyye   |
|           29 |     3872 | 2024-03-26 | ex-KRC Genk Esports | W   | 0.771      | -            | -                | -                | -         |     3.78 | ArroW, awzek, FreeZe, hyped, skyye   |
|           28 |     3918 | 2024-03-25 | ex-Sprout           | W   | 0.764      | -            | -                | -                | -         |     4.45 | ArroW, awzek, FreeZe, hyped, skyye   |
|           27 |     3987 | 2024-03-23 | Aurora Gaming       | L   | 0.751      | -            | -                | -                | -         |    -1.43 | ArroW, awzek, FreeZe, hyped, skyye   |
|           26 |     4438 | 2024-03-14 | Metizport           | W   | 0.690      | 0.384        | 0.088 (0.023)    | 0.698 (0.185)    | -         |    15.68 | ArroW, awzek, FreeZe, hyped, skyye   |
|           25 |     4492 | 2024-03-13 | SINNERS Esports     | L   | 0.684      | -            | -                | -                | -         |    -8.81 | ArroW, awzek, FreeZe, hyped, skyye   |
|           24 |     4670 | 2024-03-10 | Entropiq            | L   | 0.663      | -            | -                | -                | -         |   -16.22 | ArroW, awzek, FreeZe, hyped, skyye   |
|           23 |     4677 | 2024-03-10 | MOUZ NXT            | L   | 0.662      | -            | -                | -                | -         |    -6.38 | ArroW, awzek, FreeZe, hyped, skyye   |
|           22 |     4768 | 2024-03-08 | Sashi Esport        | W   | 0.648      | 0.371        | 0.172 (0.041)    | 1.000 (0.240)    | -         |    13.11 | ArroW, awzek, FreeZe, hyped, skyye   |
|           21 |     4856 | 2024-03-06 | brazylijski luz     | W   | 0.638      | -            | -                | -                | -         |     5.95 | ArroW, awzek, FreeZe, hyped, skyye   |
|           20 |     4998 | 2024-03-04 | Passion UA          | L   | 0.625      | -            | -                | -                | -         |    -9.91 | ArroW, awzek, FreeZe, hyped, skyye   |
|           19 |     5051 | 2024-03-04 | Passion UA          | L   | 0.622      | -            | -                | -                | -         |   -10.43 | ArroW, awzek, FreeZe, hyped, skyye   |
|           18 |     5187 | 2024-03-02 | 500                 | L   | 0.610      | -            | -                | -                | -         |   -13.25 | ArroW, awzek, FreeZe, hyped, skyye   |
|           17 |     5242 | 2024-03-01 | Fnatic              | L   | 0.603      | -            | -                | -                | -         |    -6.00 | ArroW, awzek, FreeZe, hyped, skyye   |
|           16 |     5333 | 2024-02-28 | BetBoom Team        | L   | 0.589      | -            | -                | -                | -         |    -1.72 | ArroW, awzek, FreeZe, hyped, skyye   |
|           15 |     5370 | 2024-02-27 | RUBY                | L   | 0.584      | -            | -                | -                | -         |    -9.96 | ArroW, awzek, FreeZe, hyped, skyye   |
|           14 |     5395 | 2024-02-26 | Johnny Speeds       | W   | 0.578      | -            | -                | -                | -         |    10.31 | ArroW, awzek, FreeZe, hyped, skyye   |
|           13 |     5424 | 2024-02-26 | Endpoint            | W   | 0.575      | -            | -                | -                | -         |     7.94 | ArroW, awzek, FreeZe, hyped, skyye   |
|           12 |     5452 | 2024-02-25 | Alliance            | L   | 0.570      | -            | -                | -                | -         |   -12.25 | ArroW, awzek, FreeZe, hyped, skyye   |
|           11 |     5821 | 2024-02-19 | 1win                | L   | 0.531      | -            | -                | -                | -         |    -8.40 | ArroW, awzek, FreeZe, PANIX, PerX    |
|           10 |     5866 | 2024-02-18 | Young Ninjas        | L   | 0.524      | -            | -                | -                | -         |   -10.10 | ArroW, awzek, FreeZe, PANIX, PerX    |
|            9 |     6050 | 2024-02-15 | Soda Gaming         | W   | 0.503      | -            | -                | -                | -         |     1.87 | ArroW, awzek, FreeZe, PANIX, PerX    |
|            8 |     6199 | 2024-02-12 | LODIS               | W   | 0.484      | -            | -                | -                | -         |     1.78 | ArroW, awzek, FreeZe, PANIX, PerX    |
|            7 |     6229 | 2024-02-11 | Entropiq            | W   | 0.478      | -            | -                | -                | -         |     2.24 | ArroW, awzek, FreeZe, PANIX, PerX    |
|            6 |     8618 | 2023-12-16 | ALTERNATE aTTaX     | L   | 0.097      | -            | -                | -                | -         |    -2.48 | awzek, FreeZe, PANIX, PerX, Spiidi   |
|            5 |     8844 | 2023-12-13 | RUSH B              | W   | 0.077      | -            | -                | -                | -         |     0.54 | executoR, kinqie, Kiro, nota, tex1y  |
|            4 |     9094 | 2023-12-08 | TSM                 | W   | 0.045      | -            | -                | -                | -         |     0.18 | ArroW, hyped, MRC9, pr1metapz, skyye |
|            3 |     9167 | 2023-12-07 | Endpoint            | W   | 0.037      | -            | -                | -                | -         |     0.53 | ArroW, hyped, MRC9, pr1metapz, skyye |
|            2 |     9226 | 2023-12-06 | TUSTE CHOPAKI       | W   | 0.031      | -            | -                | -                | -         |     0.05 | ArroW, hyped, MRC9, pr1metapz, skyye |
|            1 |     9293 | 2023-12-05 | TY                  | W   | 0.024      | -            | -                | -                | -         |     0.10 | ArroW, hyped, MRC9, pr1metapz, skyye |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($15,501.95)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-05-03 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-25 |      0.968 | $1,000.00      | $967.78         |
| 2023-12-16 |      0.097 | $5,126.50      | $495.56         |
| 2023-12-13 |      0.077 | $7,000.00      | $538.61         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
