### Roster Details<br />
Team Name: ThunderFlash<br />
Roster: AdrieN, hfah, Klameczka, sk1tt, yukitoro<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [79](../standings_global.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
Final Rank Value:  908.1<br />
<br />
Final Rank Value (908.1) = Starting Rank Value (833.3) + Head To Head Adjustments (74.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.213<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 833.3
- 400 + ( ( 0.213 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 833.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       82 | 2024-05-29 | GamerLegion Academy       | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.691 (0.099)    | 0 (0.000) |    11.99 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           27 |      400 | 2024-05-23 | ARCRED                    | L   | 1.000      | -            | -                | -                | -         |   -15.43 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           26 |      499 | 2024-05-22 | Insilio                   | W   | 1.000      | 0.372        | 0.010 (0.004)    | 0.717 (0.267)    | 0 (0.000) |    18.09 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           25 |      578 | 2024-05-21 | UNiTY esports             | L   | 1.000      | -            | -                | -                | -         |   -17.11 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           24 |      692 | 2024-05-20 | Team Spirit Academy       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.04 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           23 |     1149 | 2024-05-15 | EXO Clan                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.510 (0.190)    | 0 (0.000) |    13.55 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           22 |     1262 | 2024-05-14 | Endpoint                  | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.718 (0.267)    | 0 (0.000) |    17.89 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           21 |     1434 | 2024-05-11 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -21.67 | AdrieN, hfah, Klameczka, Melavi, sk1tt     |
|           20 |     1565 | 2024-05-09 | Entropiq                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.35 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           19 |     1620 | 2024-05-08 | CYBERSHOKE Esports        | W   | 1.000      | 0.372        | -                | 0.468 (0.174)    | 0 (0.000) |     8.62 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           18 |     1682 | 2024-05-07 | WOPA Esport               | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.594 (0.221)    | 0 (0.000) |    11.57 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           17 |     1917 | 2024-05-02 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -22.04 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           16 |     1973 | 2024-05-01 | kONO.ECF                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.778 (0.290)    | 0 (0.000) |    18.40 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           15 |     2311 | 2024-04-25 | Passion UA                | W   | 0.970      | 0.372        | 0.057 (0.020)    | 1.000 (0.361)    | 0 (0.000) |    17.66 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           14 |     2495 | 2024-04-21 | ENTERPRISE esports        | W   | 0.943      | 0.143        | 0.010 (0.001)    | 0.809 (0.109)    | -         |    17.44 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           13 |     2596 | 2024-04-20 | Illuminar Gaming          | W   | 0.936      | -            | -                | -                | -         |    15.00 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           12 |     2617 | 2024-04-20 | Lazer Cats                | L   | 0.936      | -            | -                | -                | -         |   -19.12 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           11 |     2711 | 2024-04-19 | AVEZ                      | W   | 0.929      | -            | -                | -                | -         |    14.26 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           10 |     3112 | 2024-04-11 | HyperSpirit               | W   | 0.877      | 0.372        | 0.004 (0.001)    | 0.356 (0.116)    | -         |    11.67 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            9 |     4030 | 2024-03-22 | ENTERPRISE esports        | W   | 0.744      | 0.143        | 0.010 (0.001)    | -                | -         |    14.72 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            8 |     4090 | 2024-03-21 | Mikstura1234              | W   | 0.737      | -            | -                | -                | -         |     7.01 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            7 |     4132 | 2024-03-20 | Illuminar Gaming          | L   | 0.731      | -            | -                | -                | -         |   -12.08 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            6 |     4157 | 2024-03-19 | ex-Turów Zgorzelec Esport | L   | 0.725      | -            | -                | -                | -         |   -12.93 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            5 |     4211 | 2024-03-18 | LODIS                     | W   | 0.717      | -            | -                | -                | -         |     4.99 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            4 |     5007 | 2024-03-04 | Runners                   | L   | 0.625      | -            | -                | -                | -         |   -16.73 | AdrieN, hfah, Klameczka, sh3nanigan, sk1tt |
|            3 |     5406 | 2024-02-26 | RUBY                      | L   | 0.578      | -            | -                | -                | -         |    -6.45 | AdrieN, hfah, Klameczka, PeTeRoOo, sk1tt   |
|            2 |     7993 | 2024-01-10 | Team Space                | L   | 0.265      | -            | -                | -                | -         |    -4.02 | AdrieN, hfah, hypex, Klameczka, sk1tt      |
|            1 |     8016 | 2024-01-10 | naChille                  | W   | 0.265      | -            | -                | -                | -         |     2.19 | AdrieN, hfah, hypex, Klameczka, sk1tt      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,605.10)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.943 | $3,696.91      | $3,487.41       |
| 2024-04-20 |      0.937 | $125.57        | $117.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
