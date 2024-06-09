### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [17](../standings_global.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
Final Rank Value:  1425.6<br />
<br />
Final Rank Value (1425.6) = Starting Rank Value (1438.5) + Head To Head Adjustments (-13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.515[<sup>1</sup>](#table2)
- Bounty Collected: 0.477[<sup>2</sup>](#table1)
- Opponent Network: 0.262[<sup>2</sup>](#table1)
- LAN Wins: 0.789[<sup>2</sup>](#table1)

The average of these factors is 0.511<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1438.5
- 400 + ( ( 0.511 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1438.5


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
|           59 |      116 | 2024-05-28 | BIG                | L   | 1.000      | -            | -                | -                | -         |   -19.25 | aliStair, dexter, INS, Liazz, Vexite         |
|           58 |      160 | 2024-05-27 | Team Spirit        | L   | 1.000      | -            | -                | -                | -         |    -2.08 | aliStair, dexter, INS, Liazz, Vexite         |
|           57 |      526 | 2024-05-22 | Mindfreak          | W   | 1.000      | 0.333        | -                | 0.306 (0.102)    | 0 (0.000) |     0.92 | aliStair, dexter, INS, Liazz, Vexite         |
|           56 |      529 | 2024-05-22 | Mindfreak          | W   | 1.000      | 0.333        | -                | 0.306 (0.102)    | -         |     0.93 | aliStair, dexter, INS, Liazz, Vexite         |
|           55 |      726 | 2024-05-20 | Canon Event        | W   | 1.000      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite         |
|           54 |      729 | 2024-05-20 | Canon Event        | W   | 1.000      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite         |
|           53 |     1657 | 2024-05-08 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |    -8.90 | aliStair, dexter, INS, Liazz, Vexite         |
|           52 |     1703 | 2024-05-07 | BetBoom Team       | W   | 1.000      | 0.889        | 0.390 (0.346)    | 0.712 (0.633)    | 1 (1.000) |    10.69 | aliStair, dexter, INS, Liazz, Vexite         |
|           51 |     1801 | 2024-05-05 | Ninjas in Pyjamas  | W   | 1.000      | 0.889        | 0.118 (0.105)    | 0.285 (0.253)    | 1 (1.000) |     4.17 | aliStair, dexter, INS, Liazz, Vexite         |
|           50 |     1865 | 2024-05-04 | Pera Esports       | W   | 1.000      | 0.889        | 0.028 (0.025)    | 0.542 (0.482)    | 1 (1.000) |     1.31 | aliStair, dexter, INS, Liazz, Vexite         |
|           49 |     1917 | 2024-05-03 | HEROIC             | L   | 1.000      | -            | -                | -                | -         |    -7.79 | aliStair, dexter, INS, Liazz, Vexite         |
|           48 |     1958 | 2024-05-02 | BOSS               | W   | 1.000      | 0.889        | 0.016 (0.014)    | 0.315 (0.280)    | 1 (1.000) |     1.26 | aliStair, dexter, INS, Liazz, Vexite         |
|           47 |     2027 | 2024-05-01 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |    -2.50 | aliStair, dexter, INS, Liazz, Vexite         |
|           46 |     2695 | 2024-04-20 | Bad News Kangaroos | W   | 0.935      | 0.143        | 0.031 (0.004)    | -                | -         |     1.41 | aliStair, dexter, INS, Liazz, Vexite         |
|           45 |     2783 | 2024-04-19 | Rooster            | W   | 0.928      | -            | -                | -                | -         |     1.00 | aliStair, dexter, INS, Liazz, Vexite         |
|           44 |     2790 | 2024-04-18 | Mindfreak          | W   | 0.927      | -            | -                | -                | -         |     0.68 | aliStair, dexter, INS, Liazz, Vexite         |
|           43 |     3271 | 2024-04-10 | FaZe Clan          | L   | 0.869      | -            | -                | -                | -         |    -1.61 | aliStair, dexter, INS, Liazz, Vexite         |
|           42 |     3289 | 2024-04-09 | Nemiga Gaming      | W   | 0.867      | 0.624        | 0.358 (0.194)    | 0.895 (0.485)    | 1 (0.867) |     5.23 | aliStair, dexter, INS, Liazz, Vexite         |
|           41 |     3354 | 2024-04-08 | Virtus.pro         | L   | 0.860      | -            | -                | -                | -         |    -5.25 | aliStair, dexter, INS, Liazz, Vexite         |
|           40 |     3399 | 2024-04-07 | Cloud9             | W   | 0.854      | 0.624        | 0.187 (0.100)    | 0.253 (0.135)    | 1 (0.854) |    17.32 | aliStair, dexter, INS, Liazz, Vexite         |
|           39 |     3662 | 2024-04-03 | Arcade Esports     | W   | 0.822      | 0.333        | -                | 0.280 (0.077)    | -         |     0.47 | aliStair, dexter, INS, Liazz, Vexite         |
|           38 |     3667 | 2024-04-03 | Arcade Esports     | W   | 0.821      | 0.333        | -                | 0.280 (0.077)    | -         |     0.47 | aliStair, dexter, INS, Liazz, Vexite         |
|           37 |     3926 | 2024-03-27 | KZG                | W   | 0.775      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite         |
|           36 |     3929 | 2024-03-27 | KZG                | W   | 0.775      | -            | -                | -                | -         |     0.41 | Estate, Hassie, Mingovi, pain, Samuukxs      |
|           35 |     4630 | 2024-03-13 | Rooster            | W   | 0.682      | -            | -                | -                | -         |     0.80 | asap, chelleos, dangeR, nettik, TjP          |
|           34 |     4636 | 2024-03-13 | Rooster            | W   | 0.682      | -            | -                | -                | -         |     0.80 | aliStair, dexter, INS, Liazz, Vexite         |
|           33 |     5042 | 2024-03-06 | DXA Esports        | W   | 0.636      | -            | -                | -                | -         |     0.30 | aliStair, dexter, INS, Liazz, Vexite         |
|           32 |     5048 | 2024-03-06 | DXA Esports        | W   | 0.635      | -            | -                | -                | -         |     0.30 | Kiyo, lucas, motion, rocky, Roflko           |
|           31 |     5494 | 2024-02-27 | Lynn Vision Gaming | L   | 0.588      | -            | -                | -                | -         |   -16.09 | aliStair, dexter, INS, Liazz, Vexite         |
|           30 |     5495 | 2024-02-27 | ATOX Esports       | W   | 0.587      | 0.143        | 0.047 (0.004)    | -                | 1 (0.587) |     4.32 | aliStair, dexter, INS, Liazz, Vexite         |
|           29 |     5541 | 2024-02-27 | JiJieHao           | W   | 0.582      | -            | -                | -                | 1 (0.582) |     0.13 | DavCost, El1an, ISSAA, m1N1, ViTaL           |
|           28 |     5586 | 2024-02-25 | The MongolZ        | L   | 0.574      | -            | -                | -                | -         |    -5.47 | aliStair, dexter, INS, Liazz, Vexite         |
|           27 |     5589 | 2024-02-25 | ATOX Esports       | W   | 0.573      | -            | -                | -                | 1 (0.573) |     4.24 | aliStair, dexter, INS, Liazz, Vexite         |
|           26 |     5781 | 2024-02-23 | Rooster            | W   | 0.555      | -            | -                | -                | -         |     0.57 | asap, chelleos, dangeR, nettik, TjP          |
|           25 |     5832 | 2024-02-22 | Rooster            | W   | 0.548      | -            | -                | -                | -         |     0.54 | aliStair, dexter, INS, Liazz, Vexite         |
|           24 |     5835 | 2024-02-21 | Bad News Kangaroos | W   | 0.547      | -            | -                | -                | -         |     0.83 | ADDICT, BRACE, Hatz, HaZR, pz                |
|           23 |     5897 | 2024-02-21 | Bad News Kangaroos | W   | 0.542      | 0.333        | 0.031 (0.006)    | -                | -         |     0.83 | ADDICT, BRACE, HaZR, pz, yourwombat          |
|           22 |     5902 | 2024-02-21 | Bad News Kangaroos | W   | 0.542      | 0.333        | 0.031 (0.006)    | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite         |
|           21 |     6027 | 2024-02-18 | Mindfreak          | W   | 0.528      | -            | -                | -                | -         |     0.27 | gump, Rickeh, Sliimey, supar, tucks          |
|           20 |     6070 | 2024-02-18 | Arcade Esports     | W   | 0.522      | -            | -                | -                | -         |     0.29 | apocdud, damyo, foggers, Kobe, void          |
|           19 |     6074 | 2024-02-18 | MANTRA             | W   | 0.522      | -            | -                | -                | -         |     0.21 | cheeseball, cookie, Reapz, rekonz, w0mbat    |
|           18 |     6077 | 2024-02-17 | Altered Edge       | W   | 0.521      | -            | -                | -                | -         |     0.18 | Havoc, Mr Shark, Rahley, Scr1pt, Winnieeeee  |
|           17 |     6089 | 2024-02-17 | Arcade Esports     | W   | 0.519      | -            | -                | -                | -         |     0.27 | apocdud, damyo, foggers, Kobe, void          |
|           16 |     6136 | 2024-02-16 | GR Gaming          | W   | 0.514      | -            | -                | -                | -         |     0.45 | mediocrity, qqGOD, Reminder, SALO_MUX, weqt2 |
|           15 |     6407 | 2024-02-12 | fuelist            | W   | 0.482      | -            | -                | -                | -         |     0.09 | aliStair, dexter, INS, Liazz, Vexite         |
|           14 |     6563 | 2024-02-07 | Canon Event        | W   | 0.448      | -            | -                | -                | -         |     0.08 | aliStair, dexter, INS, Liazz, Vexite         |
|           13 |     7431 | 2024-01-23 | Mindfreak          | W   | 0.349      | -            | -                | -                | -         |     0.17 | dangeR, dpr, Forleks, supar, tucks           |
|           12 |     7495 | 2024-01-22 | Mindfreak          | W   | 0.342      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite         |
|           11 |     7498 | 2024-01-21 | Bad News Kangaroos | W   | 0.341      | -            | -                | -                | -         |     0.56 | ADDICT, BRACE, Hatz, HaZR, pz                |
|           10 |     7531 | 2024-01-21 | Bad News Kangaroos | W   | 0.335      | -            | -                | -                | -         |     0.55 | aliStair, dexter, INS, Liazz, Vexite         |
|            9 |     7538 | 2024-01-20 | Rooster            | W   | 0.334      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite         |
|            8 |     7542 | 2024-01-20 | Mindfreak          | W   | 0.333      | -            | -                | -                | -         |     0.15 | dangeR, dpr, Forleks, supar, tucks           |
|            7 |     7610 | 2024-01-20 | Vantage Esports    | W   | 0.328      | -            | -                | -                | -         |     0.14 | KRAXYT, N1ghtraid, Omichella, SkulL, vision  |
|            6 |     7682 | 2024-01-19 | Bad News Kangaroos | L   | 0.321      | -            | -                | -                | -         |    -9.65 | aliStair, dexter, INS, Liazz, Vexite         |
|            5 |     7690 | 2024-01-18 | TEAM RKON          | W   | 0.321      | -            | -                | -                | -         |     0.05 | aliStair, dexter, INS, Liazz, Vexite         |
|            4 |     7938 | 2024-01-16 | sunday school      | W   | 0.302      | -            | -                | -                | -         |     0.05 | gump, HUGHMUNGUS, nexar, rekonz, versa       |
|            3 |     7939 | 2024-01-15 | Mindfreak          | W   | 0.301      | -            | -                | -                | -         |     0.12 | dangeR, dpr, Forleks, supar, tucks           |
|            2 |     7975 | 2024-01-15 | Jehovah witness    | W   | 0.295      | -            | -                | -                | -         |     0.05 | badger, DickStacy, mswag, sync, Texta        |
|            1 |     7984 | 2024-01-15 | 500x               | W   | 0.295      | -            | -                | -                | -         |     0.05 | atooomic, iLuu, pixie, Teee, V1per           |

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
