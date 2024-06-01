### Roster Details<br />
Team Name: Wolves eSports<br />
Roster: Berzius, Darkas, ErUu, PoKe, tooizera<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [414](../standings_global.md)<br />
Regional Rank: [249]( ../standings_europe.md)<br />
Final Rank Value:  534.0<br />
<br />
Final Rank Value (534.0) = Starting Rank Value (625.6) + Head To Head Adjustments (-91.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.268[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.6
- 400 + ( ( 0.111 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 625.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      229 | 2024-05-26 | 9INE               | L   | 1.000      | -            | -                | -                | -         |   -18.42 | Berzius, Darkas, ErUu, PoKe, tooizera     |
|           21 |      287 | 2024-05-25 | Illuminar Gaming   | L   | 1.000      | -            | -                | -                | -         |    -8.49 | Berzius, Darkas, ErUu, PoKe, tooizera     |
|           20 |      911 | 2024-05-18 | ROYALS             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.09 | Berzius, Darkas, ErUu, PoKe, tooizera     |
|           19 |     1193 | 2024-05-15 | ghoulsW            | L   | 1.000      | -            | -                | -                | -         |   -17.13 | Berzius, Darkas, ErUu, PoKe, tooizera     |
|           18 |     1389 | 2024-05-12 | L&G                | L   | 1.000      | -            | -                | -                | -         |    -7.45 | Berzius, bond1e, Darkas, PoKe, tooizera   |
|           17 |     1450 | 2024-05-11 | Chroma             | L   | 1.000      | -            | -                | -                | -         |   -15.93 | Berzius, bond1e, Darkas, PoKe, tooizera   |
|           16 |     1463 | 2024-05-11 | L&G                | L   | 1.000      | -            | -                | -                | -         |    -7.78 | Berzius, bond1e, Darkas, PoKe, tooizera   |
|           15 |     1466 | 2024-05-11 | Smalsiai           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.74 | Berzius, bond1e, Darkas, PoKe, tooizera   |
|           14 |     1526 | 2024-05-10 | Permitta Esports   | L   | 1.000      | -            | -                | -                | -         |    -5.26 | Berzius, Darkas, OniX, PoKe, tooizera     |
|           13 |     1837 | 2024-05-04 | fragmatic          | L   | 1.000      | -            | -                | -                | -         |   -16.81 | Berzius, bond1e, Darkas, PoKe, tooizera   |
|           12 |     1845 | 2024-05-04 | Back2TheGame       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |    15.14 | Berzius, bond1e, Darkas, PoKe, tooizera   |
|           11 |     2161 | 2024-04-27 | EZ4ENCE            | L   | 0.984      | -            | -                | -                | -         |   -11.23 | Berzius, Darkas, Misterio, PoKe, tooizera |
|           10 |     4698 | 2024-03-09 | nomatter           | L   | 0.658      | -            | -                | -                | -         |   -13.91 | Berzius, Darkas, PoKe, REL, Uzman         |
|            9 |     4795 | 2024-03-07 | Dynamo Eclot       | L   | 0.645      | -            | -                | -                | -         |    -1.38 | Berzius, Darkas, PoKe, REL, Uzman         |
|            8 |     4934 | 2024-03-05 | Cerberus eSports   | W   | 0.631      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.72 | Berzius, Darkas, PoKe, REL, Uzman         |
|            7 |     5570 | 2024-02-24 | hypewrld           | L   | 0.562      | -            | -                | -                | -         |    -6.75 | Berzius, Darkas, OniX, PoKe, Uzman        |
|            6 |     7827 | 2024-01-12 | FAVBET Team        | L   | 0.279      | -            | -                | -                | -         |    -2.00 | bondik, guthriee, j3kie, Smash, t3ns1on   |
|            5 |     7853 | 2024-01-12 | Come on now dawg   | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     3.01 | Boye, Folke, notaN, Sukker, zEden         |
|            4 |     8476 | 2023-12-17 | Winter             | L   | 0.103      | -            | -                | -                | -         |    -1.76 | CagXD, Frip, krea6on, LeeN, m1kketye      |
|            3 |     9030 | 2023-12-09 | Grannys Knockers   | W   | 0.050      | 0.143        | 0.006 (0.000)    | 0.355 (0.003)    | 0 (0.000) |     1.10 | Berzius, Darkas, Misterio, OniX, PoKe     |
|            2 |     9361 | 2023-12-03 | 7 Reasons e-sports | W   | 0.011      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.10 | Berzius, Darkas, Misterio, OniX, PoKe     |
|            1 |     9395 | 2023-12-03 | 7 Reasons e-sports | L   | 0.009      | -            | -                | -                | -         |    -0.19 | Berzius, Darkas, Misterio, OniX, PoKe     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($557.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      0.984 | $428.11        | $421.33         |
| 2024-02-24 |      0.564 | $162.50        | $91.68          |
| 2023-12-17 |      0.103 | $436.30        | $44.96          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
