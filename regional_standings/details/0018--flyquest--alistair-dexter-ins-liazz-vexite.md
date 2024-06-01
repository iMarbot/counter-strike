### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [18](../standings_global.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
Final Rank Value:  1420.9<br />
<br />
Final Rank Value (1420.9) = Starting Rank Value (1438.0) + Head To Head Adjustments (-17.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.515[<sup>1</sup>](#table2)
- Bounty Collected: 0.477[<sup>2</sup>](#table1)
- Opponent Network: 0.258[<sup>2</sup>](#table1)
- LAN Wins: 0.789[<sup>2</sup>](#table1)

The average of these factors is 0.510<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1438.0
- 400 + ( ( 0.510 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1438.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |      109 | 2024-05-28 | BIG                | L   | 1.000      | -            | -                | -                | -         |   -18.74 | aliStair, dexter, INS, Liazz, Vexite         |
|           48 |      153 | 2024-05-27 | Team Spirit        | L   | 1.000      | -            | -                | -                | -         |    -2.00 | aliStair, dexter, INS, Liazz, Vexite         |
|           47 |      519 | 2024-05-22 | Mindfreak          | W   | 1.000      | 0.333        | -                | 0.306 (0.102)    | 0 (0.000) |     0.94 | aliStair, dexter, INS, Liazz, Vexite         |
|           46 |      522 | 2024-05-22 | Mindfreak          | W   | 1.000      | 0.333        | -                | 0.306 (0.102)    | -         |     0.95 | aliStair, dexter, INS, Liazz, Vexite         |
|           45 |      714 | 2024-05-20 | Canon Event        | W   | 1.000      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite         |
|           44 |      717 | 2024-05-20 | Canon Event        | W   | 1.000      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite         |
|           43 |     1639 | 2024-05-08 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |    -8.60 | aliStair, dexter, INS, Liazz, Vexite         |
|           42 |     1684 | 2024-05-07 | BetBoom Team       | W   | 1.000      | 0.889        | 0.390 (0.346)    | 0.712 (0.633)    | 1 (1.000) |    10.95 | aliStair, dexter, INS, Liazz, Vexite         |
|           41 |     1778 | 2024-05-05 | Ninjas in Pyjamas  | W   | 1.000      | 0.889        | 0.118 (0.105)    | 0.285 (0.253)    | 1 (1.000) |     4.29 | aliStair, dexter, INS, Liazz, Vexite         |
|           40 |     1842 | 2024-05-04 | Pera Esports       | W   | 1.000      | 0.889        | 0.028 (0.025)    | 0.574 (0.510)    | 1 (1.000) |     1.42 | aliStair, dexter, INS, Liazz, Vexite         |
|           39 |     1892 | 2024-05-03 | HEROIC             | L   | 1.000      | -            | -                | -                | -         |    -7.59 | aliStair, dexter, INS, Liazz, Vexite         |
|           38 |     1931 | 2024-05-02 | BOSS               | W   | 1.000      | 0.889        | 0.016 (0.014)    | 0.315 (0.280)    | 1 (1.000) |     1.31 | aliStair, dexter, INS, Liazz, Vexite         |
|           37 |     1997 | 2024-05-01 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -2.42 | aliStair, dexter, INS, Liazz, Vexite         |
|           36 |     2641 | 2024-04-20 | Bad News Kangaroos | W   | 0.935      | 0.143        | 0.031 (0.004)    | -                | -         |     1.45 | aliStair, dexter, INS, Liazz, Vexite         |
|           35 |     2727 | 2024-04-19 | Rooster            | W   | 0.928      | -            | -                | -                | -         |     0.96 | aliStair, dexter, INS, Liazz, Vexite         |
|           34 |     2734 | 2024-04-18 | Mindfreak          | W   | 0.927      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite         |
|           33 |     3196 | 2024-04-10 | FaZe Clan          | L   | 0.869      | -            | -                | -                | -         |    -1.55 | aliStair, dexter, INS, Liazz, Vexite         |
|           32 |     3211 | 2024-04-09 | Nemiga Gaming      | W   | 0.867      | 0.624        | 0.366 (0.198)    | 0.830 (0.449)    | 1 (0.867) |     5.53 | aliStair, dexter, INS, Liazz, Vexite         |
|           31 |     3274 | 2024-04-08 | Virtus.pro         | L   | 0.860      | -            | -                | -                | -         |    -5.10 | aliStair, dexter, INS, Liazz, Vexite         |
|           30 |     3318 | 2024-04-07 | Cloud9             | W   | 0.854      | 0.624        | 0.187 (0.100)    | 0.253 (0.135)    | 1 (0.854) |    17.57 | aliStair, dexter, INS, Liazz, Vexite         |
|           29 |     5342 | 2024-02-27 | Lynn Vision Gaming | L   | 0.588      | -            | -                | -                | -         |   -16.04 | aliStair, dexter, INS, Liazz, Vexite         |
|           28 |     5343 | 2024-02-27 | ATOX Esports       | W   | 0.587      | 0.143        | 0.047 (0.004)    | 0.601 (0.050)    | 1 (0.587) |     3.71 | aliStair, dexter, INS, Liazz, Vexite         |
|           27 |     5385 | 2024-02-27 | JiJieHao           | W   | 0.582      | -            | -                | -                | 1 (0.582) |     0.13 | DavCost, El1an, ISSAA, m1N1, ViTaL           |
|           26 |     5428 | 2024-02-25 | The MongolZ        | L   | 0.574      | -            | -                | -                | -         |    -5.38 | aliStair, dexter, INS, Liazz, Vexite         |
|           25 |     5431 | 2024-02-25 | ATOX Esports       | W   | 0.573      | 0.143        | 0.047 (0.004)    | -                | 1 (0.573) |     3.62 | aliStair, dexter, INS, Liazz, Vexite         |
|           24 |     5621 | 2024-02-23 | Rooster            | W   | 0.555      | -            | -                | -                | -         |     0.57 | asap, chelleos, dangeR, nettik, TjP          |
|           23 |     5671 | 2024-02-22 | Rooster            | W   | 0.548      | -            | -                | -                | -         |     0.54 | aliStair, dexter, INS, Liazz, Vexite         |
|           22 |     5674 | 2024-02-21 | Bad News Kangaroos | W   | 0.547      | 0.143        | 0.031 (0.002)    | -                | -         |     0.85 | ADDICT, BRACE, Hatz, HaZR, pz                |
|           21 |     5855 | 2024-02-18 | Mindfreak          | W   | 0.528      | -            | -                | -                | -         |     0.27 | gump, Rickeh, Sliimey, supar, tucks          |
|           20 |     5897 | 2024-02-18 | Arcade Esports     | W   | 0.522      | -            | -                | -                | -         |     0.28 | apocdud, damyo, foggers, Kobe, void          |
|           19 |     5901 | 2024-02-18 | MANTRA             | W   | 0.522      | -            | -                | -                | -         |     0.21 | cheeseball, cookie, Reapz, rekonz, w0mbat    |
|           18 |     5904 | 2024-02-17 | Altered Edge       | W   | 0.521      | -            | -                | -                | -         |     0.18 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee  |
|           17 |     5916 | 2024-02-17 | Arcade Esports     | W   | 0.519      | -            | -                | -                | -         |     0.26 | apocdud, damyo, foggers, Kobe, void          |
|           16 |     5963 | 2024-02-16 | GR Gaming          | W   | 0.514      | 0.310        | -                | 0.428 (0.068)    | -         |     0.45 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           15 |     6219 | 2024-02-12 | fuelist            | W   | 0.482      | -            | -                | -                | -         |     0.09 | aliStair, dexter, INS, Liazz, Vexite         |
|           14 |     6369 | 2024-02-07 | Canon Event        | W   | 0.448      | -            | -                | -                | -         |     0.08 | aliStair, dexter, INS, Liazz, Vexite         |
|           13 |     7191 | 2024-01-23 | Mindfreak          | W   | 0.349      | -            | -                | -                | -         |     0.17 | dangeR, dpr, Forleks, supar, tucks           |
|           12 |     7252 | 2024-01-22 | Mindfreak          | W   | 0.342      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite         |
|           11 |     7255 | 2024-01-21 | Bad News Kangaroos | W   | 0.341      | -            | -                | -                | -         |     0.56 | ADDICT, BRACE, Hatz, HaZR, pz                |
|           10 |     7288 | 2024-01-21 | Bad News Kangaroos | W   | 0.335      | -            | -                | -                | -         |     0.55 | aliStair, dexter, INS, Liazz, Vexite         |
|            9 |     7295 | 2024-01-20 | Rooster            | W   | 0.334      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite         |
|            8 |     7299 | 2024-01-20 | Mindfreak          | W   | 0.333      | -            | -                | -                | -         |     0.15 | dangeR, dpr, Forleks, supar, tucks           |
|            7 |     7366 | 2024-01-20 | Vantage Esports    | W   | 0.328      | -            | -                | -                | -         |     0.13 | KRAXYT, N1ghtraid, Omichella, SkulL, vision  |
|            6 |     7435 | 2024-01-19 | Bad News Kangaroos | L   | 0.321      | -            | -                | -                | -         |    -9.64 | aliStair, dexter, INS, Liazz, Vexite         |
|            5 |     7443 | 2024-01-18 | TEAM RKON          | W   | 0.321      | -            | -                | -                | -         |     0.05 | aliStair, dexter, INS, Liazz, Vexite         |
|            4 |     7689 | 2024-01-16 | sunday school      | W   | 0.302      | -            | -                | -                | -         |     0.05 | gump, HUGHMUNGUS, nexar, rekonz, versa       |
|            3 |     7690 | 2024-01-15 | Mindfreak          | W   | 0.301      | -            | -                | -                | -         |     0.12 | dangeR, dpr, Forleks, supar, tucks           |
|            2 |     7723 | 2024-01-15 | Jehovah witness    | W   | 0.295      | -            | -                | -                | -         |     0.05 | badger, DickStacy, mswag, sync, Texta        |
|            1 |     7731 | 2024-01-15 | 500x               | W   | 0.295      | -            | -                | -                | -         |     0.05 | atooomic, iLuu, pixie, Teee, V1per           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,299.44)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-05-12 |      1.000 | $23,500.00     | $23,500.00      |
| 2024-04-14 |      0.895 | $6,000.00      | $5,370.97       |
| 2024-02-17 |      0.519 | $2,750.00      | $1,428.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
