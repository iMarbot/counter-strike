### Roster Details<br />
Team Name: LODIS<br />
Roster: aimy, asran, fugor, Mride, pawkoem<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [388](../standings_global.md)<br />
Regional Rank: [231]( ../standings_europe.md)<br />
Final Rank Value:  562.8<br />
<br />
Final Rank Value (562.8) = Starting Rank Value (645.8) + Head To Head Adjustments (-83.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.195[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.121<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 645.8
- 400 + ( ( 0.121 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 645.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      336 | 2024-05-24 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -12.04 | aimy, asran, fugor, Mride, pawkoem          |
|           30 |      728 | 2024-05-19 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |    -3.11 | aimy, asran, fugor, Mride, pawkoem          |
|           29 |      995 | 2024-05-17 | Dynamo Eclot              | L   | 1.000      | -            | -                | -                | -         |    -3.56 | aimy, asran, fugor, Mride, pawkoem          |
|           28 |     1071 | 2024-05-16 | JANO Esports              | L   | 1.000      | -            | -                | -                | -         |    -9.45 | aimy, asran, fugor, Mride, pawkoem          |
|           27 |     1308 | 2024-05-13 | Eternal Fire Academy      | L   | 1.000      | -            | -                | -                | -         |   -17.20 | aimy, asran, fugor, Mride, pawkoem          |
|           26 |     1675 | 2024-05-07 | GenOne                    | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.442 (0.165)    | 0 (0.000) |    19.89 | aimy, asran, fugor, Mride, pawkoem          |
|           25 |     1719 | 2024-05-06 | Nemiga Gaming             | L   | 1.000      | -            | -                | -                | -         |    -1.04 | aimy, asran, fugor, Mride, pawkoem          |
|           24 |     1757 | 2024-05-05 | Lemondogs                 | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.274 (0.102)    | 0 (0.000) |    16.85 | aimy, asran, fugor, Mride, pawkoem          |
|           23 |     1765 | 2024-05-05 | Kappa Bar                 | L   | 1.000      | -            | -                | -                | -         |   -17.26 | aimy, asran, fugor, Mride, pawkoem          |
|           22 |     2704 | 2024-04-19 | Lausanne-Sport Esports    | L   | 0.930      | -            | -                | -                | -         |   -10.13 | aimy, asran, fugor, Mride, pawkoem          |
|           21 |     2972 | 2024-04-14 | Young Ninjas              | L   | 0.897      | -            | -                | -                | -         |    -3.51 | aimy, asran, fugor, Mride, pawkoem          |
|           20 |     4035 | 2024-03-22 | Illuminar Gaming          | L   | 0.744      | -            | -                | -                | -         |    -5.85 | aimy, asran, fugor, Mride, pawkoem          |
|           19 |     4087 | 2024-03-21 | ex-Turów Zgorzelec Esport | W   | 0.738      | 0.143        | 0.006 (0.001)    | 0.375 (0.040)    | 0 (0.000) |    16.70 | aimy, asran, fugor, Mride, pawkoem          |
|           18 |     4122 | 2024-03-20 | Mikstura1234              | W   | 0.731      | 0.143        | 0.001 (0.000)    | 0.081 (0.008)    | 0 (0.000) |    13.71 | aimy, asran, fugor, Mride, pawkoem          |
|           17 |     4172 | 2024-03-19 | ENTERPRISE esports        | L   | 0.724      | -            | -                | -                | -         |    -3.18 | aimy, asran, fugor, Mride, pawkoem          |
|           16 |     4211 | 2024-03-18 | ThunderFlash              | L   | 0.717      | -            | -                | -                | -         |    -4.99 | aimy, asran, fugor, Mride, pawkoem          |
|           15 |     4658 | 2024-03-10 | DEEZ NUTS                 | L   | 0.664      | -            | -                | -                | -         |    -8.77 | avis, b1elany, ewrzyn, sh3nanigan, zaNNN    |
|           14 |     5302 | 2024-02-28 | Copenhagen Wolves         | L   | 0.591      | -            | -                | -                | -         |    -9.08 | Basso, Fessor, Svedjehed, szejn, vigg0      |
|           13 |     5360 | 2024-02-27 | ex-Hot Headed Gaming      | L   | 0.584      | -            | -                | -                | -         |   -11.40 | asran, fugor, GruBy, Mride, pawkoem         |
|           12 |     5412 | 2024-02-26 | 0to100                    | W   | 0.578      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.14 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|           11 |     5442 | 2024-02-25 | Golden Sword              | W   | 0.571      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.93 | asran, fugor, GruBy, Mride, pawkoem         |
|           10 |     5642 | 2024-02-22 | Grindas                   | L   | 0.551      | -            | -                | -                | -         |   -11.49 | AwwEzz, BaGyZ, prochas, Sidivo, slokker     |
|            9 |     6193 | 2024-02-12 | ex-K10                    | L   | 0.484      | -            | -                | -                | -         |    -3.92 | Rezst, shyyne, SLY, Tree, yz0               |
|            8 |     6199 | 2024-02-12 | ALTERNATE aTTaX           | L   | 0.484      | -            | -                | -                | -         |    -1.78 | asran, fugor, GruBy, Mride, pawkoem         |
|            7 |     6331 | 2024-02-08 | V1dar Gaming              | L   | 0.457      | -            | -                | -                | -         |    -6.63 | asran, fugor, GruBy, Mride, pawkoem         |
|            6 |     6358 | 2024-02-07 | ex-KRC Genk Esports       | W   | 0.451      | 0.371        | 0.000 (0.000)    | 0.120 (0.020)    | 0 (0.000) |     7.48 | asran, fugor, GruBy, Mride, pawkoem         |
|            5 |     6405 | 2024-02-05 | MOUZ NXT                  | L   | 0.438      | -            | -                | -                | -         |    -1.00 | Burmylov, Chr1zN, Neityu, PR, sirah         |
|            4 |     6603 | 2024-02-02 | DASH                      | L   | 0.417      | -            | -                | -                | -         |    -5.57 | asran, fugor, GruBy, Mride, pawkoem         |
|            3 |     6751 | 2024-01-30 | Kappa Bar                 | L   | 0.398      | -            | -                | -                | -         |    -8.26 | asran, fugor, GruBy, Mride, pawkoem         |
|            2 |     7538 | 2024-01-17 | GODSENT                   | L   | 0.311      | -            | -                | -                | -         |    -4.79 | asran, fugor, GruBy, Mride, pawkoem         |
|            1 |     7663 | 2024-01-16 | PARIVISION                | L   | 0.304      | -            | -                | -                | -         |    -1.65 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($348.74)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
