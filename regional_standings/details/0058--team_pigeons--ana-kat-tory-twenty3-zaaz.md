### Roster Details<br />
Team Name: Team Pigeons<br />
Roster: ANa, Kat, tory, twenty3, zAAz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [58](../standings_global.md)<br />
Regional Rank: [43]( ../standings_europe.md)<br />
Final Rank Value:  969.8<br />
<br />
Final Rank Value (969.8) = Starting Rank Value (881.5) + Head To Head Adjustments (88.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.494[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.095[<sup>2</sup>](#table1)

The average of these factors is 0.243<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 881.5
- 400 + ( ( 0.243 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 881.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |       18 | 2024-05-05 | Crescent (Female team)      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.14 | ANa, Kat, tory, twenty3, zAAz          |
|           25 |       56 | 2024-05-04 | Nemesis (Female team)       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.29 | ANa, Kat, tory, twenty3, zAAz          |
|           24 |       61 | 2024-05-04 | YUME                        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.29 | ANa, Kat, tory, twenty3, zAAz          |
|           23 |      365 | 2024-04-27 | NIP Impact                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.88 | ANa, Kat, tory, twenty3, zAAz          |
|           22 |      368 | 2024-04-27 | Team Spirit Female          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.19 | ANa, Kat, tory, twenty3, zAAz          |
|           21 |      374 | 2024-04-27 | VIOLET                      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.63 | ANa, Kat, tory, twenty3, zAAz          |
|           20 |      815 | 2024-04-19 | Guild Esports               | W   | 1.000      | 0.331        | 0.010 (0.003)    | 0.194 (0.064)    | -         |     7.96 | ANa, Kat, tory, twenty3, zAAz          |
|           19 |      999 | 2024-04-16 | NAVI Javelins               | L   | 1.000      | -            | -                | -                | -         |   -18.93 | ANa, Kat, tory, twenty3, zAAz          |
|           18 |     1066 | 2024-04-14 | NIP Impact                  | W   | 1.000      | 0.303        | 0.011 (0.003)    | 0.344 (0.104)    | -         |     8.50 | ANa, Kat, tory, twenty3, zAAz          |
|           17 |     1115 | 2024-04-13 | NAVI Javelins               | W   | 1.000      | 0.303        | 0.062 (0.019)    | 0.328 (0.099)    | -         |    11.87 | ANa, Kat, tory, twenty3, zAAz          |
|           16 |     1167 | 2024-04-11 | Astralis Women              | W   | 1.000      | 0.331        | 0.007 (0.002)    | -                | -         |     4.54 | ANa, Kat, tory, twenty3, zAAz          |
|           15 |     1224 | 2024-04-10 | Astralis Women              | W   | 1.000      | -            | -                | -                | -         |     4.74 | ANa, Kat, tory, twenty3, zAAz          |
|           14 |     1336 | 2024-04-08 | Crescent (Female team)      | W   | 1.000      | 0.303        | 0.008 (0.002)    | 0.187 (0.057)    | -         |     7.07 | ANa, Kat, tory, twenty3, zAAz          |
|           13 |     1367 | 2024-04-07 | NIP Impact                  | W   | 1.000      | 0.262        | 0.011 (0.003)    | 0.344 (0.090)    | -         |     9.41 | ANa, Kat, tory, twenty3, zAAz          |
|           12 |     1373 | 2024-04-07 | BIG EQUIPA                  | W   | 1.000      | 0.262        | -                | 0.300 (0.078)    | -         |     9.39 | ANa, Kat, tory, twenty3, zAAz          |
|           11 |     1410 | 2024-04-06 | ENCE Athena                 | W   | 1.000      | 0.262        | 0.009 (0.002)    | 0.244 (0.064)    | -         |     7.77 | ANa, Kat, tory, twenty3, zAAz          |
|           10 |     1734 | 2024-03-27 | ENCE Athena                 | W   | 0.939      | 0.331        | 0.009 (0.003)    | 0.244 (0.076)    | -         |     7.85 | ANa, Kat, tory, twenty3, zAAz          |
|            9 |     2260 | 2024-03-14 | BIG EQUIPA                  | W   | 0.852      | 0.331        | -                | 0.300 (0.084)    | -         |     8.75 | ANa, Kat, tory, twenty3, zAAz          |
|            8 |     2566 | 2024-03-07 | NIP Impact                  | W   | 0.805      | 0.331        | 0.011 (0.003)    | 0.344 (0.092)    | -         |     7.22 | ANa, Kat, tory, twenty3, zAAz          |
|            7 |     3078 | 2024-02-26 | 500                         | L   | 0.737      | -            | -                | -                | -         |   -12.37 | ANa, Kat, tory, twenty3, zAAz          |
|            6 |     3974 | 2024-02-03 | UNiTY esports (Slovak team) | L   | 0.585      | -            | -                | -                | -         |    -7.65 | Levi, luko, M1key, NIO, Pechyn         |
|            5 |     5724 | 2023-12-10 | NAVI Javelins               | W   | 0.218      | 0.524        | 0.062 (0.007)    | -                | 1 (0.218) |     3.10 | ANa, Kat, tory, twenty3, vilga         |
|            4 |     5743 | 2023-12-10 | NOFEAR5                     | W   | 0.216      | -            | -                | -                | 1 (0.216) |     2.13 | Elizabeth, f6tal, Ksu, t4tty, victoria |
|            3 |     5771 | 2023-12-09 | HSG                         | W   | 0.211      | -            | -                | -                | 1 (0.211) |     1.65 | Argent, GFi, Hazel, olga, XiaoWu       |
|            2 |     5838 | 2023-12-08 | Fluxo Demons                | L   | 0.205      | -            | -                | -                | -         |    -2.73 | goddess, julih, nani, poppins, yungher |
|            1 |     5855 | 2023-12-08 | HSG                         | W   | 0.203      | -            | -                | -                | 1 (0.203) |     1.56 | Argent, GFi, Hazel, olga, XiaoWu       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,932.12)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $750.00        | $750.00         |
| 2024-04-27 |      1.000 | $535.13        | $535.13         |
| 2024-04-16 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-04-07 |      1.000 | $1,250.00      | $1,250.00       |
| 2023-12-10 |      0.218 | $50,000.00     | $10,896.99      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
