### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [21](../standings_global.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
Final Rank Value:  1413.4<br />
<br />
Final Rank Value (1413.4) = Starting Rank Value (1379.5) + Head To Head Adjustments (33.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.436[<sup>1</sup>](#table2)
- Bounty Collected: 0.510[<sup>2</sup>](#table1)
- Opponent Network: 0.224[<sup>2</sup>](#table1)
- LAN Wins: 0.805[<sup>2</sup>](#table1)

The average of these factors is 0.494<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1379.5
- 400 + ( ( 0.494 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1379.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       25 | 2024-05-05 | Ninjas in Pyjamas           | W   | 1.000      | 0.889        | 0.241 (0.215)    | 0.376 (0.334)    | 1 (1.000) |     6.34 | aliStair, dexter, INS, Liazz, Vexite         |
|           40 |       77 | 2024-05-04 | Pera Esports                | W   | 1.000      | 0.889        | 0.065 (0.058)    | 0.324 (0.288)    | 1 (1.000) |     1.76 | aliStair, dexter, INS, Liazz, Vexite         |
|           39 |      120 | 2024-05-03 | HEROIC                      | L   | 1.000      | -            | -                | -                | -         |    -7.25 | aliStair, dexter, INS, Liazz, Vexite         |
|           38 |      156 | 2024-05-02 | BOSS                        | W   | 1.000      | 0.889        | 0.051 (0.045)    | 0.293 (0.260)    | 1 (1.000) |     1.54 | aliStair, dexter, INS, Liazz, Vexite         |
|           37 |      215 | 2024-05-01 | Natus Vincere               | L   | 1.000      | -            | -                | -                | -         |    -1.49 | aliStair, dexter, INS, Liazz, Vexite         |
|           36 |      769 | 2024-04-20 | Bad News Kangaroos          | W   | 1.000      | 0.143        | 0.071 (0.010)    | -                | 0 (0.000) |     2.17 | aliStair, dexter, INS, Liazz, Vexite         |
|           35 |      848 | 2024-04-19 | Rooster                     | W   | 1.000      | 0.143        | 0.031 (0.004)    | -                | 0 (0.000) |     1.50 | aliStair, dexter, INS, Liazz, Vexite         |
|           34 |      855 | 2024-04-18 | Mindfreak (Australian team) | W   | 1.000      | -            | -                | -                | -         |     0.93 | aliStair, dexter, INS, Liazz, Vexite         |
|           33 |     1243 | 2024-04-10 | FaZe Clan                   | L   | 1.000      | -            | -                | -                | -         |    -1.63 | aliStair, dexter, INS, Liazz, Vexite         |
|           32 |     1260 | 2024-04-09 | Nemiga Gaming               | W   | 1.000      | 0.624        | 0.680 (0.425)    | 0.910 (0.568)    | 1 (1.000) |     8.78 | aliStair, dexter, INS, Liazz, Vexite         |
|           31 |     1316 | 2024-04-08 | Virtus.pro                  | L   | 1.000      | -            | -                | -                | -         |    -4.60 | aliStair, dexter, INS, Liazz, Vexite         |
|           30 |     1356 | 2024-04-08 | Cloud9                      | W   | 1.000      | 0.624        | 0.487 (0.304)    | 0.419 (0.262)    | 1 (1.000) |    27.86 | aliStair, dexter, INS, Liazz, Vexite         |
|           29 |     1555 | 2024-04-03 | VexX Gaming                 | W   | 0.983      | 0.333        | -                | 0.390 (0.128)    | -         |     0.79 | aliStair, dexter, INS, Liazz, Vexite         |
|           28 |     1560 | 2024-04-03 | VexX Gaming                 | W   | 0.983      | 0.333        | -                | 0.390 (0.128)    | -         |     0.80 | aliStair, dexter, INS, Liazz, Vexite         |
|           27 |     3008 | 2024-02-27 | Lynn Vision Gaming          | L   | 0.749      | -            | -                | -                | -         |   -16.16 | aliStair, dexter, INS, Liazz, Vexite         |
|           26 |     3009 | 2024-02-27 | ATOX Esports                | W   | 0.748      | 0.143        | 0.112 (0.012)    | 0.769 (0.082)    | 1 (0.748) |     3.49 | aliStair, dexter, INS, Liazz, Vexite         |
|           25 |     3047 | 2024-02-27 | JiJieHao                    | W   | 0.743      | -            | -                | -                | 1 (0.743) |     0.27 | DavCost, El1an, ISSAA, m1N1, ViTaL           |
|           24 |     3083 | 2024-02-25 | The MongolZ                 | L   | 0.735      | -            | -                | -                | -         |    -5.01 | aliStair, dexter, INS, Liazz, Vexite         |
|           23 |     3086 | 2024-02-25 | ATOX Esports                | W   | 0.734      | 0.143        | 0.112 (0.012)    | -                | 1 (0.734) |     3.27 | aliStair, dexter, INS, Liazz, Vexite         |
|           22 |     3223 | 2024-02-23 | Rooster                     | W   | 0.716      | -            | -                | -                | -         |     1.18 | asap, chelleos, dangeR, nettik, TjP          |
|           21 |     3267 | 2024-02-22 | Rooster                     | W   | 0.710      | -            | -                | -                | -         |     1.10 | aliStair, dexter, INS, Liazz, Vexite         |
|           20 |     3270 | 2024-02-21 | Bad News Kangaroos          | W   | 0.708      | 0.143        | 0.071 (0.007)    | -                | -         |     1.84 | ADDICT, BRACE, Hatz, HaZR, pz                |
|           19 |     3432 | 2024-02-18 | Mindfreak (Australian team) | W   | 0.689      | -            | -                | -                | -         |     0.46 | gump, Rickeh, Sliimey, supar, tucks          |
|           18 |     3466 | 2024-02-18 | VexX Gaming                 | W   | 0.683      | -            | -                | -                | -         |     0.54 | apocdud, damyo, foggers, Kobe, void          |
|           17 |     3469 | 2024-02-18 | MANTRA                      | W   | 0.683      | -            | -                | -                | -         |     0.40 | cheeseball, cookie, Reapz, rekonz, w0mbat    |
|           16 |     3471 | 2024-02-17 | Altered Edge                | W   | 0.682      | -            | -                | -                | -         |     0.34 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee  |
|           15 |     3476 | 2024-02-17 | VexX Gaming                 | W   | 0.681      | 0.310        | -                | 0.390 (0.082)    | -         |     0.50 | apocdud, damyo, foggers, Kobe, void          |
|           14 |     3511 | 2024-02-16 | GR Gaming                   | W   | 0.675      | 0.310        | -                | 0.495 (0.104)    | -         |     0.93 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           13 |     3851 | 2024-02-07 | Canon Event                 | W   | 0.609      | -            | -                | -                | -         |     0.08 | aliStair, dexter, INS, Liazz, Vexite         |
|           12 |     4441 | 2024-01-23 | Mindfreak (Australian team) | W   | 0.510      | -            | -                | -                | -         |     0.41 | dangeR, dpr, Forleks, supar, tucks           |
|           11 |     4491 | 2024-01-22 | Mindfreak (Australian team) | W   | 0.503      | -            | -                | -                | -         |     0.39 | aliStair, dexter, INS, Liazz, Vexite         |
|           10 |     4519 | 2024-01-20 | Rooster                     | W   | 0.495      | -            | -                | -                | -         |     0.77 | aliStair, dexter, INS, Liazz, Vexite         |
|            9 |     4523 | 2024-01-20 | Mindfreak (Australian team) | W   | 0.494      | -            | -                | -                | -         |     0.36 | dangeR, dpr, Forleks, supar, tucks           |
|            8 |     4571 | 2024-01-20 | Vantage Esports             | W   | 0.489      | -            | -                | -                | -         |     0.17 | KRAXYT, N1ghtraid, Omichella, SkulL, vision  |
|            7 |     4631 | 2024-01-18 | TEAM RKON                   | W   | 0.482      | -            | -                | -                | -         |     0.12 | aliStair, dexter, INS, Liazz, Vexite         |
|            6 |     4820 | 2024-01-15 | Mindfreak (Australian team) | W   | 0.462      | -            | -                | -                | -         |     0.31 | dangeR, dpr, Forleks, supar, tucks           |
|            5 |     4845 | 2024-01-15 | Jehovah witness             | W   | 0.456      | -            | -                | -                | -         |     0.11 | badger, DickStacy, mswag, sync, Texta        |
|            4 |     4853 | 2024-01-15 | 500x                        | W   | 0.456      | -            | -                | -                | -         |     0.11 | atooomic, iLuu, pixie, Teee, V1per           |
|            3 |     6608 | 2023-11-21 | Bad News Kangaroos          | W   | 0.090      | -            | -                | -                | -         |     0.24 | ADDICT, BRACE, HaZR, pz, Valiance            |
|            2 |     6656 | 2023-11-19 | Rooster                     | W   | 0.082      | -            | -                | -                | -         |     0.13 | asap, chelleos, nettik, Rackem, TjP          |
|            1 |     6992 | 2023-11-12 | DXA Esports                 | W   | 0.036      | -            | -                | -                | -         |     0.01 | bebest, helix, Kiyo, lucas222, Roflko        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,078.09)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-02-17 |      0.681 | $2,750.00      | $1,871.40       |
| 2023-11-21 |      0.090 | $2,298.91      | $206.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
