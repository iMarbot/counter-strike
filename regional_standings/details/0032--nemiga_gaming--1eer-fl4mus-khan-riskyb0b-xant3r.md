### Roster Details<br />
Team Name: Nemiga Gaming<br />
Roster: 1eeR, FL4MUS, khaN, riskyb0b, Xant3r<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [32](../standings_global.md)<br />
Regional Rank: [24]( ../standings_europe.md)<br />
Final Rank Value:  1265.4<br />
<br />
Final Rank Value (1265.4) = Starting Rank Value (1322.8) + Head To Head Adjustments (-57.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.857[<sup>1</sup>](#table2)
- Bounty Collected: 0.477[<sup>2</sup>](#table1)
- Opponent Network: 0.415[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.465<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1322.8
- 400 + ( ( 0.465 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1322.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           66 |       12 | 2024-05-05 | VP.Prodigy             | W   | 1.000      | -            | -                | -                | false (0.000) |     2.34 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           65 |      109 | 2024-05-03 | MOUZ NXT               | W   | 1.000      | 0.500        | 0.215 (0.108)    | 1.000 (0.500)    | false (0.000) |     7.19 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           64 |      148 | 2024-05-02 | Passion UA             | W   | 1.000      | 0.500        | 0.114 (0.057)    | 0.980 (0.490)    | false (0.000) |     4.35 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           63 |      186 | 2024-05-01 | B8                     | W   | 1.000      | 0.500        | 0.088 (0.044)    | 0.589 (0.294)    | false (0.000) |     6.44 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           62 |      265 | 2024-04-29 | MOUZ NXT               | W   | 1.000      | 0.500        | 0.215 (0.108)    | 1.000 (0.500)    | false (0.000) |     7.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           61 |      373 | 2024-04-27 | 1win                   | W   | 1.000      | -            | -                | -                | false (0.000) |     2.90 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           60 |      522 | 2024-04-24 | TBA.ECF                | W   | 1.000      | -            | -                | -                | false (0.000) |     2.21 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           59 |      535 | 2024-04-24 | BLEED Esports          | W   | 1.000      | 0.500        | 0.284 (0.142)    | 0.644 (0.322)    | false (0.000) |    13.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           58 |      562 | 2024-04-23 | EXO Clan               | L   | 1.000      | -            | -                | -                | -             |   -26.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           57 |      587 | 2024-04-23 | Zero Tenacity          | W   | 1.000      | 0.500        | 0.095 (0.047)    | 1.000 (0.500)    | false (0.000) |     5.43 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           56 |      623 | 2024-04-22 | MOUZ NXT               | W   | 1.000      | 0.500        | 0.215 (0.108)    | 1.000 (0.500)    | -             |     8.30 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           55 |      648 | 2024-04-21 | Team PeeP              | W   | 1.000      | -            | -                | -                | -             |     0.31 | 1eeR, khaN, riskyb0b, Xant3r, zweih   |
|           54 |      661 | 2024-04-21 | 1win                   | W   | 1.000      | -            | -                | -                | -             |     2.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           53 |      770 | 2024-04-20 | Gaimin Gladiators      | L   | 1.000      | -            | -                | -                | -             |    -9.95 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           52 |      827 | 2024-04-19 | Sangal Esports         | W   | 1.000      | -            | -                | -                | -             |     2.50 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           51 |      884 | 2024-04-18 | Team Secret            | W   | 1.000      | -            | -                | -                | -             |     1.63 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           50 |      945 | 2024-04-17 | Alliance               | W   | 1.000      | 0.500        | -                | 0.729 (0.364)    | -             |     3.46 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           49 |     1260 | 2024-04-09 | FlyQuest               | L   | 1.000      | -            | -                | -                | -             |    -8.78 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           48 |     1312 | 2024-04-09 | Steel Helmet           | W   | 1.000      | -            | -                | -                | true (1.000)  |     1.43 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           47 |     1351 | 2024-04-08 | FaZe Clan              | L   | 1.000      | -            | -                | -                | -             |    -0.58 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           46 |     1608 | 2024-04-01 | Zero Tenacity          | W   | 0.970      | 0.384        | -                | 1.000 (0.373)    | -             |     4.79 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           45 |     1803 | 2024-03-26 | AURA (Swedish team)    | L   | 0.932      | -            | -                | -                | -             |   -28.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           44 |     1938 | 2024-03-22 | Sashi Esport           | L   | 0.905      | -            | -                | -                | -             |   -22.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           43 |     2372 | 2024-03-12 | Nexus Gaming           | L   | 0.839      | -            | -                | -                | -             |   -22.96 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           42 |     2429 | 2024-03-11 | Sashi Esport           | W   | 0.831      | 0.371        | 0.193 (0.059)    | 1.000 (0.309)    | -             |     4.12 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           41 |     2461 | 2024-03-10 | Endpoint               | W   | 0.825      | -            | -                | -                | -             |     2.10 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           40 |     2683 | 2024-03-05 | KOI                    | L   | 0.792      | -            | -                | -                | -             |   -19.29 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           39 |     2696 | 2024-03-05 | GUN5 Esports           | W   | 0.792      | -            | -                | -                | -             |     0.74 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           38 |     2732 | 2024-03-04 | ENTERPRISE esports     | W   | 0.786      | -            | -                | -                | -             |     2.85 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           37 |     2751 | 2024-03-04 | Aurora Young Blud      | W   | 0.786      | -            | -                | -                | -             |     1.24 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           36 |     3323 | 2024-02-21 | Insilio                | W   | 0.704      | -            | -                | -                | -             |     2.91 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           35 |     3362 | 2024-02-20 | NOM Esports            | W   | 0.697      | -            | -                | -                | -             |     0.49 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           34 |     3407 | 2024-02-19 | FORZE Youngsters       | W   | 0.692      | -            | -                | -                | -             |     0.68 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           33 |     3413 | 2024-02-19 | Endpoint               | W   | 0.691      | -            | -                | -                | -             |     1.61 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           32 |     3452 | 2024-02-18 | GUN5 Esports           | L   | 0.684      | -            | -                | -                | -             |   -21.14 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           31 |     3680 | 2024-02-13 | 1win                   | W   | 0.651      | -            | -                | -                | -             |     0.67 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           30 |     3727 | 2024-02-12 | Team Secret            | W   | 0.645      | -            | -                | -                | -             |     0.53 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           29 |     3730 | 2024-02-12 | ILIN                   | W   | 0.645      | -            | -                | -                | -             |     0.28 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           28 |     3763 | 2024-02-10 | Sashi Esport           | W   | 0.632      | -            | -                | -                | -             |     3.51 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           27 |     3788 | 2024-02-09 | AMKAL ESPORTS          | W   | 0.625      | -            | -                | -                | -             |     7.77 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           26 |     3813 | 2024-02-08 | Sashi Esport           | W   | 0.619      | -            | -                | -                | -             |     3.29 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           25 |     3826 | 2024-02-08 | BetBoom Team           | W   | 0.618      | 0.143        | 0.571 (0.050)    | -                | -             |    14.18 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           24 |     3897 | 2024-02-05 | Kappa Bar              | W   | 0.598      | -            | -                | -                | -             |     0.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           23 |     4080 | 2024-02-01 | Lausanne-Sport Esports | L   | 0.571      | -            | -                | -                | -             |   -17.22 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           22 |     4136 | 2024-01-30 | RUBY                   | W   | 0.559      | -            | -                | -                | -             |     1.52 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           21 |     4142 | 2024-01-30 | 9Pandas                | W   | 0.558      | -            | -                | -                | -             |     5.04 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           20 |     4161 | 2024-01-29 | Aurora Gaming          | W   | 0.553      | 0.143        | 1.000 (0.079)    | -                | -             |    14.40 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           19 |     4178 | 2024-01-29 | Endpoint               | W   | 0.553      | -            | -                | -                | -             |     1.25 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           18 |     4384 | 2024-01-24 | Ex-Hot Headed Gaming   | W   | 0.518      | -            | -                | -                | -             |     0.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           17 |     4740 | 2024-01-17 | Preasy Esport          | L   | 0.472      | -            | -                | -                | -             |   -12.87 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           16 |     5094 | 2024-01-09 | Illuminar Gaming       | L   | 0.418      | -            | -                | -                | -             |   -12.55 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           15 |     5106 | 2024-01-09 | HEROIC                 | W   | 0.418      | -            | -                | -                | -             |    11.94 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           14 |     5399 | 2023-12-17 | LF0                    | W   | 0.263      | -            | -                | -                | -             |     0.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           13 |     5483 | 2023-12-16 | VP.Prodigy             | W   | 0.257      | -            | -                | -                | -             |     0.54 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           12 |     5501 | 2023-12-16 | BAKS Esports           | W   | 0.256      | -            | -                | -                | -             |     0.20 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r  |
|           11 |     5924 | 2023-12-06 | ENTERPRISE esports     | L   | 0.192      | -            | -                | -                | -             |    -5.35 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|           10 |     5942 | 2023-12-06 | MOUZ NXT               | L   | 0.191      | -            | -                | -                | -             |    -4.68 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            9 |     6247 | 2023-11-29 | Ex-sYnck               | W   | 0.146      | -            | -                | -                | -             |     0.07 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            8 |     6310 | 2023-11-28 | Gaimin Gladiators      | W   | 0.139      | -            | -                | -                | -             |     2.98 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            7 |     6323 | 2023-11-28 | Ex-Anonymo Esports     | W   | 0.138      | -            | -                | -                | -             |     0.19 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            6 |     6372 | 2023-11-27 | ESCAPIST               | L   | 0.132      | -            | -                | -                | -             |    -4.09 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            5 |     6620 | 2023-11-20 | INGLORIOUS             | W   | 0.086      | -            | -                | -                | -             |     0.13 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            4 |     6638 | 2023-11-20 | Lajtbitexe             | L   | 0.085      | -            | -                | -                | -             |    -2.64 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            3 |     7120 | 2023-11-09 | GUN5 Esports           | L   | 0.013      | -            | -                | -                | -             |    -0.39 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            2 |     7133 | 2023-11-09 | Insilio                | L   | 0.012      | -            | -                | -                | -             |    -0.33 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |
|            1 |     7188 | 2023-11-08 | EHawks                 | L   | 0.005      | -            | -                | -                | -             |    -0.15 | 1eeR, almazer, FL4MUS, khaN, riskyb0b |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($107,774.03)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.68) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-03 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-04-24 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-04-14 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-25 |      0.925 | $3,000.00      | $2,774.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
