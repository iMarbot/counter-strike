### Roster Details<br />
Team Name: VexX Gaming<br />
Roster: apocdud, foggers, Kobe, TRIPLUS, void<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [210](../standings_global.md)<br />
Regional Rank: [34]( ../standings_asia.md)<br />
Final Rank Value:  703.1<br />
<br />
Final Rank Value (703.1) = Starting Rank Value (717.9) + Head To Head Adjustments (-14.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.268[<sup>2</sup>](#table1)
- Opponent Network: 0.039[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.160<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 717.9
- 400 + ( ( 0.160 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 717.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      957 | 2024-04-17 | Rooster                         | L   | 1.000      | -            | -                | -                | -         |    -7.97 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           37 |      962 | 2024-04-17 | Vantage Esports                 | W   | 1.000      | 0.143        | -                | 0.236 (0.034)    | 0 (0.000) |    14.97 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           36 |      974 | 2024-04-17 | The Bardolphs (Australian team) | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.04 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           35 |     1249 | 2024-04-10 | Vantage Esports                 | L   | 1.000      | -            | -                | -                | -         |   -16.60 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           34 |     1255 | 2024-04-10 | Vantage Esports                 | L   | 1.000      | -            | -                | -                | -         |   -18.12 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           33 |     1555 | 2024-04-03 | FlyQuest                        | L   | 0.983      | -            | -                | -                | -         |    -0.79 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           32 |     1560 | 2024-04-03 | FlyQuest                        | L   | 0.983      | -            | -                | -                | -         |    -0.80 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           31 |     1772 | 2024-03-27 | Rooster                         | L   | 0.937      | -            | -                | -                | -         |    -8.80 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           30 |     1776 | 2024-03-27 | Rooster                         | L   | 0.936      | -            | -                | -                | -         |    -9.45 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           29 |     1921 | 2024-03-23 | KZG                             | L   | 0.909      | -            | -                | -                | -         |   -16.15 | apocdud, foggers, Kobe, void, yourwombat    |
|           28 |     1925 | 2024-03-23 | Bad News Kangaroos              | L   | 0.909      | -            | -                | -                | -         |    -7.80 | apocdud, foggers, Kobe, void, yourwombat    |
|           27 |     2109 | 2024-03-18 | KZG                             | L   | 0.876      | -            | -                | -                | -         |   -16.55 | apocdud, foggers, Kobe, rekonz, void        |
|           26 |     2228 | 2024-03-15 | LE-LUX Esports                  | W   | 0.857      | 0.143        | 0.001 (0.000)    | 0.114 (0.014)    | 0 (0.000) |     7.79 | apocdud, foggers, Kobe, rekonz, void        |
|           25 |     2236 | 2024-03-15 | KZG                             | W   | 0.856      | 0.143        | 0.020 (0.002)    | 0.249 (0.030)    | 0 (0.000) |    11.00 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs     |
|           24 |     2285 | 2024-03-14 | Underground Esports Club        | W   | 0.849      | 0.143        | 0.000 (0.000)    | 0.112 (0.014)    | 0 (0.000) |     6.27 | beep, cl0ver, coops, Mechanical, Prime7     |
|           23 |     2650 | 2024-03-06 | KZG                             | W   | 0.797      | 0.333        | 0.020 (0.005)    | 0.249 (0.066)    | 0 (0.000) |    10.89 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           22 |     2653 | 2024-03-06 | KZG                             | W   | 0.796      | 0.333        | 0.020 (0.005)    | 0.249 (0.066)    | 0 (0.000) |    11.68 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           21 |     3046 | 2024-02-27 | Canon Event                     | W   | 0.743      | -            | -                | -                | 0 (0.000) |     2.98 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           20 |     3049 | 2024-02-27 | Canon Event                     | W   | 0.743      | -            | -                | -                | 0 (0.000) |     3.06 | apocdud, foggers, Kobe, TRIPLUS, void       |
|           19 |     3332 | 2024-02-20 | Vantage Esports                 | L   | 0.702      | -            | -                | -                | -         |   -15.19 | Drox, Omichella, SkulL, viridian, vision    |
|           18 |     3377 | 2024-02-20 | Altered Edge                    | W   | 0.696      | 0.143        | 0.003 (0.000)    | 0.138 (0.014)    | 0 (0.000) |     8.78 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee |
|           17 |     3381 | 2024-02-20 | Golf Club                       | W   | 0.696      | 0.143        | 0.000 (0.000)    | -                | -         |     6.36 | Bones, kaylyn, nauh, supa, swede            |
|           16 |     3466 | 2024-02-18 | FlyQuest                        | L   | 0.683      | -            | -                | -                | -         |    -0.54 | apocdud, damyo, foggers, Kobe, void         |
|           15 |     3468 | 2024-02-18 | KZG                             | W   | 0.683      | 0.143        | 0.020 (0.002)    | 0.249 (0.024)    | -         |    11.10 | dpr, Hassie, Lexon, Mingovi, Samuukxs       |
|           14 |     3474 | 2024-02-17 | StevosFirstCS2                  | W   | 0.682      | -            | -                | -                | -         |     4.64 | deStiny, ferg, gazR, NikkeZ, stvnsn         |
|           13 |     3476 | 2024-02-17 | FlyQuest                        | L   | 0.681      | -            | -                | -                | -         |    -0.50 | apocdud, damyo, foggers, Kobe, void         |
|           12 |     3512 | 2024-02-16 | LYG Gaming                      | W   | 0.674      | 0.310        | 0.004 (0.001)    | 0.380 (0.080)    | -         |    12.04 | AceX, Haski4, Sange, Soundwave, ZinGY       |
|           11 |     3692 | 2024-02-13 | DXA Esports                     | L   | 0.650      | -            | -                | -                | -         |    -9.53 | apocdud, damyo, foggers, Kobe, SaVage       |
|           10 |     3695 | 2024-02-13 | Jehovah witness                 | W   | 0.649      | -            | -                | -                | -         |     5.33 | badge, DickStacy, mswag, stevie, Texta      |
|            9 |     3704 | 2024-02-12 | FAREWELL TOUR                   | W   | 0.649      | -            | -                | -                | -         |     3.08 | 7ambo, cud, minidooba, p00chy, widep        |
|            8 |     3739 | 2024-02-12 | DXA Esports                     | W   | 0.642      | 0.310        | 0.010 (0.002)    | 0.266 (0.053)    | -         |    11.04 | Falcon, helix, Kiyo, lucas, Roflko          |
|            7 |     3762 | 2024-02-11 | Bad News Kangaroos              | L   | 0.636      | -            | -                | -                | -         |    -3.93 | apocdud, damyo, foggers, Kobe, SaVage       |
|            6 |     3831 | 2024-02-08 | Moon Esports                    | W   | 0.616      | -            | -                | -                | -         |     3.07 | Estelle, kenoith, naksu, Naofu, TonyPOPONY  |
|            5 |     4680 | 2024-01-18 | Mindfreak (Australian team)     | L   | 0.476      | -            | -                | -                | -         |    -7.42 | dangeR, dpr, Forleks, supar, tucks          |
|            4 |     4755 | 2024-01-17 | Jehovah witness                 | W   | 0.469      | -            | -                | -                | -         |     3.82 | apocdud, damyo, foggers, Kobe, yourwombat   |
|            3 |     4760 | 2024-01-17 | TEAM RKON                       | W   | 0.469      | -            | -                | -                | -         |     3.88 | apocdud, damyo, foggers, Kobe, yourwombat   |
|            2 |     4856 | 2024-01-14 | Jehovah witness                 | L   | 0.456      | -            | -                | -                | -         |   -10.89 | apocdud, damyo, foggers, Kobe, yourwombat   |
|            1 |     4964 | 2024-01-11 | StevosFirstCS2                  | L   | 0.435      | -            | -                | -                | -         |   -10.57 | deStiny, ferg, gazR, GENESIS, InfrequeNt    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,598.29)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.909 | $651.59        | $592.60         |
| 2024-03-18 |      0.876 | $177.04        | $155.05         |
| 2024-02-17 |      0.681 | $1,250.00      | $850.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
