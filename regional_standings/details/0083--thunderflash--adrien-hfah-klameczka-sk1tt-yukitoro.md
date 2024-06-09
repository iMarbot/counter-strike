### Roster Details<br />
Team Name: ThunderFlash<br />
Roster: AdrieN, hfah, Klameczka, sk1tt, yukitoro<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [83](../standings_global.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
Final Rank Value:  904.1<br />
<br />
Final Rank Value (904.1) = Starting Rank Value (836.4) + Head To Head Adjustments (67.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.299[<sup>2</sup>](#table1)
- Opponent Network: 0.218[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 836.4
- 400 + ( ( 0.215 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 836.4


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
|           29 |       89 | 2024-05-29 | GamerLegion Academy       | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.691 (0.099)    | 0 (0.000) |    11.93 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           28 |      408 | 2024-05-23 | ARCRED                    | L   | 1.000      | -            | -                | -                | -         |   -15.16 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           27 |      506 | 2024-05-22 | Insilio                   | W   | 1.000      | 0.372        | 0.007 (0.002)    | 0.717 (0.267)    | 0 (0.000) |    18.34 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           26 |      589 | 2024-05-21 | UNiTY esports             | L   | 1.000      | -            | -                | -                | -         |   -17.14 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           25 |      703 | 2024-05-20 | Team Spirit Academy       | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.38 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           24 |     1158 | 2024-05-15 | EXO Clan                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.579 (0.216)    | 0 (0.000) |    14.38 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           23 |     1273 | 2024-05-14 | Endpoint                  | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.770 (0.287)    | 0 (0.000) |    19.06 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           22 |     1447 | 2024-05-11 | ex-Turów Zgorzelec Esport | L   | 1.000      | -            | -                | -                | -         |   -19.81 | AdrieN, hfah, Klameczka, Melavi, sk1tt     |
|           21 |     1581 | 2024-05-09 | Entropiq                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.77 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           20 |     1637 | 2024-05-08 | CYBERSHOKE Esports        | W   | 1.000      | 0.372        | -                | 0.468 (0.174)    | 0 (0.000) |     9.15 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           19 |     1701 | 2024-05-07 | WOPA Esport               | W   | 1.000      | 0.372        | 0.003 (0.001)    | 0.594 (0.221)    | 0 (0.000) |    12.15 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           18 |     1944 | 2024-05-02 | V1dar Gaming              | L   | 1.000      | -            | -                | -                | -         |   -21.22 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           17 |     2001 | 2024-05-01 | kONO.ECF                  | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.853 (0.318)    | 0 (0.000) |    19.24 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           16 |     2350 | 2024-04-25 | Passion UA                | W   | 0.970      | 0.372        | 0.057 (0.020)    | 1.000 (0.361)    | 0 (0.000) |    18.83 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           15 |     2419 | 2024-04-24 | ex-Turów Zgorzelec Esport | L   | 0.963      | -            | -                | -                | -         |   -19.16 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           14 |     2548 | 2024-04-21 | ENTERPRISE esports        | W   | 0.943      | 0.143        | 0.010 (0.001)    | 0.898 (0.121)    | -         |    18.18 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           13 |     2650 | 2024-04-20 | Illuminar Gaming          | W   | 0.936      | -            | -                | -                | -         |    14.88 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           12 |     2671 | 2024-04-20 | Lazer Cats                | L   | 0.936      | -            | -                | -                | -         |   -19.29 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           11 |     2767 | 2024-04-19 | AVEZ                      | W   | 0.929      | -            | -                | -                | -         |    15.43 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|           10 |     3179 | 2024-04-11 | HyperSpirit               | W   | 0.877      | 0.372        | 0.004 (0.001)    | 0.356 (0.116)    | -         |    11.53 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            9 |     4128 | 2024-03-22 | ENTERPRISE esports        | W   | 0.744      | 0.143        | 0.010 (0.001)    | -                | -         |    15.19 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            8 |     4189 | 2024-03-21 | Mikstura1234              | W   | 0.737      | -            | -                | -                | -         |     6.94 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            7 |     4232 | 2024-03-20 | Illuminar Gaming          | L   | 0.731      | -            | -                | -                | -         |   -12.21 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            6 |     4259 | 2024-03-19 | ex-Turów Zgorzelec Esport | L   | 0.725      | -            | -                | -                | -         |   -12.79 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            5 |     4316 | 2024-03-18 | LODIS                     | W   | 0.717      | -            | -                | -                | -         |     5.29 | AdrieN, hfah, Klameczka, sk1tt, yukitoro   |
|            4 |     5153 | 2024-03-04 | Runners                   | L   | 0.625      | -            | -                | -                | -         |   -16.77 | AdrieN, hfah, Klameczka, sh3nanigan, sk1tt |
|            3 |     5563 | 2024-02-26 | RUBY                      | L   | 0.578      | -            | -                | -                | -         |    -6.47 | AdrieN, hfah, Klameczka, PeTeRoOo, sk1tt   |
|            2 |     8247 | 2024-01-10 | Team Space                | L   | 0.265      | -            | -                | -                | -         |    -4.05 | AdrieN, hfah, hypex, Klameczka, sk1tt      |
|            1 |     8270 | 2024-01-10 | naChille                  | W   | 0.265      | -            | -                | -                | -         |     2.16 | AdrieN, hfah, hypex, Klameczka, sk1tt      |

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
