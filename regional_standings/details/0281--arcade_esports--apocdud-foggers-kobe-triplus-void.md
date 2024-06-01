### Roster Details<br />
Team Name: Arcade Esports<br />
Roster: apocdud, foggers, Kobe, TRIPLUS, void<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [281](../standings_global.md)<br />
Regional Rank: [45]( ../standings_asia.md)<br />
Final Rank Value:  654.2<br />
<br />
Final Rank Value (654.2) = Starting Rank Value (689.3) + Head To Head Adjustments (-35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.312[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.142<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.3
- 400 + ( ( 0.142 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 689.3


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
|           37 |      935 | 2024-05-17 | Vantage Esports          | L   | 1.000      | -            | -                | -                | -         |   -15.52 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           36 |     1201 | 2024-05-15 | Bad News Kangaroos       | L   | 1.000      | -            | -                | -                | -         |    -6.47 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           35 |     1206 | 2024-05-15 | Bad News Kangaroos       | L   | 1.000      | -            | -                | -                | -         |    -6.86 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           34 |     1651 | 2024-05-08 | Mindfreak                | L   | 1.000      | -            | -                | -                | -         |   -10.77 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           33 |     1653 | 2024-05-08 | Mindfreak                | L   | 1.000      | -            | -                | -                | -         |   -11.68 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           32 |     1691 | 2024-05-07 | DXA Esports              | L   | 1.000      | -            | -                | -                | -         |   -18.43 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           31 |     1697 | 2024-05-07 | DXA Esports              | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.196 (0.065)    | 0 (0.000) |    12.84 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           30 |     2858 | 2024-04-17 | Rooster                  | L   | 0.915      | -            | -                | -                | -         |    -9.06 | apocdud, foggers, Kobe, TRIPLUS, void          |
|           29 |     2863 | 2024-04-17 | Vantage Esports          | W   | 0.915      | 0.143        | 0.000 (0.000)    | 0.226 (0.030)    | 0 (0.000) |    13.84 | Drox, N1ghtraid, Omichella, SkulL, vision      |
|           28 |     2874 | 2024-04-17 | The Bardolphs            | W   | 0.915      | -            | -                | -                | 0 (0.000) |     4.40 | AppleJuice, HappyDuckss, Italy, RYME, sad_fish |
|           27 |     4014 | 2024-03-23 | KZG                      | L   | 0.748      | -            | -                | -                | -         |   -11.93 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs        |
|           26 |     4017 | 2024-03-23 | Bad News Kangaroos       | L   | 0.748      | -            | -                | -                | -         |    -6.18 | apocdud, foggers, Kobe, void, yourwombat       |
|           25 |     4226 | 2024-03-18 | KZG                      | L   | 0.715      | -            | -                | -                | -         |   -11.96 | apocdud, foggers, Kobe, rekonz, void           |
|           24 |     4389 | 2024-03-15 | LE-LUX Esports           | W   | 0.696      | 0.143        | 0.000 (0.000)    | 0.072 (0.007)    | 0 (0.000) |     7.25 | apocdud, foggers, Kobe, rekonz, void           |
|           23 |     4397 | 2024-03-15 | KZG                      | W   | 0.694      | 0.143        | 0.011 (0.001)    | 0.223 (0.022)    | 0 (0.000) |    10.64 | Hassie, KRAXYT, KZXL, Mingovi, Samuukxs        |
|           22 |     4447 | 2024-03-14 | Underground Esports Club | W   | 0.688      | 0.143        | 0.000 (0.000)    | 0.070 (0.007)    | 0 (0.000) |     6.25 | beep, cl0ver, coops, Mechanical, Prime7        |
|           21 |     5741 | 2024-02-20 | Vantage Esports          | L   | 0.541      | -            | -                | -                | -         |    -9.60 | Drox, Omichella, SkulL, viridian, vision       |
|           20 |     5790 | 2024-02-20 | Altered Edge             | W   | 0.535      | 0.143        | 0.002 (0.000)    | 0.086 (0.007)    | 0 (0.000) |     6.81 | BROJVHS, Havoc, luffy, Mr Shark, Winnieeeee    |
|           19 |     5792 | 2024-02-20 | gjdpdffileljhkj          | W   | 0.535      | -            | -                | -                | 0 (0.000) |     2.76 | BaN4na, dcey, NeoAgricola, nub, sunshinez      |
|           18 |     5797 | 2024-02-20 | Golf Club                | W   | 0.535      | -            | -                | -                | 0 (0.000) |     3.48 | Bones, kaylyn, nauh, supa, swede               |
|           17 |     5897 | 2024-02-18 | FlyQuest                 | L   | 0.522      | -            | -                | -                | -         |    -0.28 | apocdud, damyo, foggers, Kobe, void            |
|           16 |     5900 | 2024-02-18 | KZG                      | W   | 0.522      | 0.143        | 0.011 (0.001)    | 0.223 (0.017)    | 0 (0.000) |     9.05 | dpr, Hassie, Lexon, Mingovi, Samuukxs          |
|           15 |     5911 | 2024-02-17 | StevosFirstCS2           | W   | 0.521      | -            | -                | -                | -         |     3.89 | deStiny, ferg, gazR, NikkeZ, stvnsn            |
|           14 |     5916 | 2024-02-17 | FlyQuest                 | L   | 0.519      | -            | -                | -                | -         |    -0.26 | apocdud, damyo, foggers, Kobe, void            |
|           13 |     5964 | 2024-02-16 | LYG Gaming               | W   | 0.513      | 0.310        | 0.001 (0.000)    | 0.275 (0.044)    | -         |     8.66 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           12 |     6171 | 2024-02-13 | DXA Esports              | L   | 0.489      | -            | -                | -                | -         |    -7.11 | apocdud, damyo, foggers, Kobe, SaVage          |
|           11 |     6174 | 2024-02-13 | Jehovah witness          | W   | 0.488      | 0.143        | -                | 0.047 (0.003)    | -         |     4.24 | badge, DickStacy, mswag, stevie, Texta         |
|           10 |     6184 | 2024-02-12 | FAREWELL TOUR            | W   | 0.488      | -            | -                | -                | -         |     2.59 | 7ambo, cud, minidooba, p00chy, widep           |
|            9 |     6222 | 2024-02-12 | DXA Esports              | W   | 0.481      | 0.310        | 0.005 (0.001)    | 0.196 (0.029)    | -         |     8.34 | Falcon, helix, Kiyo, lucas, Roflko             |
|            8 |     6251 | 2024-02-11 | Bad News Kangaroos       | L   | 0.475      | -            | -                | -                | -         |    -8.18 | apocdud, damyo, foggers, Kobe, SaVage          |
|            7 |     6343 | 2024-02-08 | Moon Esports             | W   | 0.455      | -            | -                | -                | -         |     2.43 | Estelle, kenoith, naksu, Naofu, TonyPOPONY     |
|            6 |     7496 | 2024-01-18 | Mindfreak                | L   | 0.315      | -            | -                | -                | -         |    -5.24 | dangeR, dpr, Forleks, supar, tucks             |
|            5 |     7497 | 2024-01-17 | sunday school            | W   | 0.314      | 0.143        | 0.007 (0.000)    | -                | -         |     4.89 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            4 |     7589 | 2024-01-17 | Jehovah witness          | W   | 0.308      | -            | -                | -                | -         |     2.71 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            3 |     7596 | 2024-01-17 | TEAM RKON                | W   | 0.308      | -            | -                | -                | -         |     2.60 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            2 |     7734 | 2024-01-14 | Jehovah witness          | L   | 0.295      | -            | -                | -                | -         |    -6.81 | apocdud, damyo, foggers, Kobe, yourwombat      |
|            1 |     7889 | 2024-01-11 | StevosFirstCS2           | L   | 0.274      | -            | -                | -                | -         |    -6.48 | deStiny, ferg, gazR, GENESIS, InfrequeNt       |

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
