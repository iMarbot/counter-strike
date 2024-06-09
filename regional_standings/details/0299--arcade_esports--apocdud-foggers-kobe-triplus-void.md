### Roster Details<br />
Team Name: Arcade Esports<br />
Roster: apocdud, foggers, Kobe, TRIPLUS, void<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [299](../standings_global.md)<br />
Regional Rank: [47]( ../standings_asia.md)<br />
Final Rank Value:  646.5<br />
<br />
Final Rank Value (646.5) = Starting Rank Value (701.4) + Head To Head Adjustments (-54.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 701.4
- 400 + ( ( 0.148 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 701.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |      947 | 2024-05-17 | Vantage Esports          | L   | 1.000      | -            | -                | -                | -         |   -13.96 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           46 |     1211 | 2024-05-15 | Bad News Kangaroos       | L   | 1.000      | -            | -                | -                | -         |    -6.18 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           45 |     1216 | 2024-05-15 | Bad News Kangaroos       | L   | 1.000      | -            | -                | -                | -         |    -6.54 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           44 |     1669 | 2024-05-08 | Mindfreak                | L   | 1.000      | -            | -                | -                | -         |   -10.34 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           43 |     1671 | 2024-05-08 | Mindfreak                | L   | 1.000      | -            | -                | -                | -         |   -11.19 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           42 |     1711 | 2024-05-07 | DXA Esports              | L   | 1.000      | -            | -                | -                | -         |   -18.07 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           41 |     1717 | 2024-05-07 | DXA Esports              | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.196 (0.065)    | 0 (0.000) |    13.23 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           40 |     2915 | 2024-04-17 | Rooster                  | L   | 0.915      | -            | -                | -                | -         |    -8.14 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           39 |     2920 | 2024-04-17 | Vantage Esports          | W   | 0.915      | 0.143        | -                | 0.226 (0.030)    | 0 (0.000) |    15.67 | Drox, N1ghtraid, Omichella, SkulL, vision      |
|           38 |     2931 | 2024-04-17 | The Bardolphs            | W   | 0.915      | -            | -                | -                | 0 (0.000) |     4.71 | AppleJuice, HappyDuckss, Italy, RYME, sad_fish |
|           37 |     3278 | 2024-04-10 | Vantage Esports          | L   | 0.868      | -            | -                | -                | -         |   -12.44 | Drox, Jynx, N1ghtraid, Omichella, vision       |
|           36 |     3284 | 2024-04-10 | Vantage Esports          | L   | 0.868      | -            | -                | -                | -         |   -13.42 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           35 |     3662 | 2024-04-03 | FlyQuest                 | L   | 0.822      | -            | -                | -                | -         |    -0.47 | aliStair, dexter, INS, Liazz, Vexite           |
|           34 |     3667 | 2024-04-03 | FlyQuest                 | L   | 0.821      | -            | -                | -                | -         |    -0.47 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           33 |     3924 | 2024-03-27 | Rooster                  | L   | 0.775      | -            | -                | -                | -         |    -7.79 | asap, chelleos, dangeR, nettik, TjP            |
|           32 |     3930 | 2024-03-27 | Rooster                  | L   | 0.775      | -            | -                | -                | -         |    -8.27 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           31 |     4112 | 2024-03-23 | KZG                      | L   | 0.748      | -            | -                | -                | -         |   -13.41 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs        |
|           30 |     4115 | 2024-03-23 | Bad News Kangaroos       | L   | 0.748      | -            | -                | -                | -         |    -7.03 | apocdud, foggers, Kobe, void, yourwombat       |
|           29 |     4331 | 2024-03-18 | KZG                      | L   | 0.715      | -            | -                | -                | -         |   -13.49 | apocdud, foggers, Kobe, rekonz, void           |
|           28 |     4498 | 2024-03-15 | LE-LUX Esports           | W   | 0.696      | 0.143        | -                | 0.072 (0.007)    | 0 (0.000) |     6.38 | apocdud, foggers, Kobe, rekonz, void           |
|           27 |     4507 | 2024-03-15 | KZG                      | W   | 0.694      | 0.143        | 0.011 (0.001)    | 0.223 (0.022)    | 0 (0.000) |     9.02 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs        |
|           26 |     4561 | 2024-03-14 | Underground Esports Club | W   | 0.688      | 0.143        | -                | 0.070 (0.007)    | 0 (0.000) |     5.41 | beep, cl0ver, coops, Mechanical, Prime7        |
|           25 |     5041 | 2024-03-06 | KZG                      | W   | 0.636      | 0.333        | 0.011 (0.002)    | 0.223 (0.047)    | 0 (0.000) |     8.68 | Estate, Hassie, Mingovi, pain, Samuukxs        |
|           24 |     5047 | 2024-03-06 | KZG                      | W   | 0.635      | 0.333        | 0.011 (0.002)    | 0.223 (0.047)    | 0 (0.000) |     9.17 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           23 |     5540 | 2024-02-27 | Canon Event              | W   | 0.582      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     4.22 | Blizz, BoBo, Coppo, Kras, mitzy                |
|           22 |     5543 | 2024-02-27 | Canon Event              | W   | 0.582      | -            | -                | -                | 0 (0.000) |     4.38 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           21 |     5908 | 2024-02-20 | Vantage Esports          | L   | 0.541      | -            | -                | -                | -         |    -9.53 | Drox, Omichella, SkulL, viridian, vision       |
|           20 |     5960 | 2024-02-20 | Altered Edge             | W   | 0.535      | 0.143        | 0.002 (0.000)    | -                | -         |     6.59 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee    |
|           19 |     5962 | 2024-02-20 | gjdpdffileljhkj          | W   | 0.535      | -            | -                | -                | -         |     2.64 | BaN4na, dcey, NeoAgricola, nub, sunshinez      |
|           18 |     5967 | 2024-02-20 | Golf Club                | W   | 0.535      | -            | -                | -                | -         |     3.34 | Bones, kaylyn, nauh, supa, swede               |
|           17 |     6070 | 2024-02-18 | FlyQuest                 | L   | 0.522      | -            | -                | -                | -         |    -0.29 | apocdud, damyo, foggers, Kobe, void            |
|           16 |     6073 | 2024-02-18 | KZG                      | W   | 0.522      | 0.143        | 0.011 (0.001)    | 0.223 (0.017)    | -         |     8.75 | dpr, Hassie, Lexon, Mingovi, Samuukxs          |
|           15 |     6084 | 2024-02-17 | StevosFirstCS2           | W   | 0.521      | -            | -                | -                | -         |     3.73 | deStiny, ferg, gazR, NikkeZ, stvnsn            |
|           14 |     6089 | 2024-02-17 | FlyQuest                 | L   | 0.519      | -            | -                | -                | -         |    -0.27 | apocdud, damyo, foggers, Kobe, void            |
|           13 |     6137 | 2024-02-16 | LYG Gaming               | W   | 0.513      | 0.310        | 0.001 (0.000)    | 0.275 (0.044)    | -         |     8.44 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           12 |     6356 | 2024-02-13 | DXA Esports              | L   | 0.489      | -            | -                | -                | -         |    -7.33 | apocdud, damyo, foggers, Kobe, SaVage          |
|           11 |     6359 | 2024-02-13 | Jehovah witness          | W   | 0.488      | -            | -                | -                | -         |     4.06 | badge, DickStacy, mswag, stevie, Texta         |
|           10 |     6369 | 2024-02-12 | FAREWELL TOUR            | W   | 0.488      | -            | -                | -                | -         |     2.47 | 7ambo, cud, minidooba, p00chy, widep           |
|            9 |     6410 | 2024-02-12 | DXA Esports              | W   | 0.481      | 0.310        | 0.005 (0.001)    | 0.196 (0.029)    | -         |     8.11 | Falcon, helix, Kiyo, lucas, Roflko             |
|            8 |     6439 | 2024-02-11 | Bad News Kangaroos       | L   | 0.475      | -            | -                | -                | -         |    -8.41 | apocdud, damyo, foggers, Kobe, SaVage          |
|            7 |     6531 | 2024-02-08 | Moon Esports             | W   | 0.455      | -            | -                | -                | -         |     2.31 | Estelle, kenoith, naksu, Naofu, TonyPOPONY     |
|            6 |     7745 | 2024-01-18 | Mindfreak                | L   | 0.315      | -            | -                | -                | -         |    -5.40 | dangeR, dpr, Forleks, supar, tucks             |
|            5 |     7746 | 2024-01-17 | sunday school            | W   | 0.314      | 0.143        | 0.007 (0.000)    | -                | -         |     4.71 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            4 |     7838 | 2024-01-17 | Jehovah witness          | W   | 0.308      | -            | -                | -                | -         |     2.58 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            3 |     7845 | 2024-01-17 | TEAM RKON                | W   | 0.308      | -            | -                | -                | -         |     2.47 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            2 |     7987 | 2024-01-14 | Jehovah witness          | L   | 0.295      | -            | -                | -                | -         |    -6.93 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            1 |     8142 | 2024-01-11 | StevosFirstCS2           | L   | 0.274      | -            | -                | -                | -         |    -6.59 | deStiny, ferg, gazR, GENESIS, InfrequeNt       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,863.50)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $600.00        | $600.00         |
| 2024-03-23 |      0.748 | $651.59        | $487.65         |
| 2024-03-18 |      0.715 | $177.04        | $126.54         |
| 2024-02-17 |      0.519 | $1,250.00      | $649.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
