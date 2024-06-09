### Roster Details<br />
Team Name: LODIS<br />
Roster: aimy, asran, fugor, Mride, pawkoem<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [386](../standings_global.md)<br />
Regional Rank: [232]( ../standings_europe.md)<br />
Final Rank Value:  576.5<br />
<br />
Final Rank Value (576.5) = Starting Rank Value (649.7) + Head To Head Adjustments (-73.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.195[<sup>2</sup>](#table1)
- Opponent Network: 0.042[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 649.7
- 400 + ( ( 0.123 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 649.7


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
|           32 |      345 | 2024-05-24 | Copenhagen Wolves         | L   | 1.000      | -            | -                | -                | -         |   -10.92 | aimy, asran, fugor, Mride, pawkoem          |
|           31 |      740 | 2024-05-19 | RUBY                      | L   | 1.000      | -            | -                | -                | -         |    -3.25 | aimy, asran, fugor, Mride, pawkoem          |
|           30 |     1007 | 2024-05-17 | Dynamo Eclot              | L   | 1.000      | -            | -                | -                | -         |    -4.04 | aimy, asran, fugor, Mride, pawkoem          |
|           29 |     1081 | 2024-05-16 | JANO Esports              | L   | 1.000      | -            | -                | -                | -         |    -9.59 | aimy, asran, fugor, Mride, pawkoem          |
|           28 |     1319 | 2024-05-13 | Eternal Fire Academy      | L   | 1.000      | -            | -                | -                | -         |   -17.93 | aimy, asran, fugor, Mride, pawkoem          |
|           27 |     1693 | 2024-05-07 | GenOne                    | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.442 (0.165)    | 0 (0.000) |    19.16 | aimy, asran, fugor, Mride, pawkoem          |
|           26 |     1741 | 2024-05-06 | Nemiga Gaming             | L   | 1.000      | -            | -                | -                | -         |    -1.12 | aimy, asran, fugor, Mride, pawkoem          |
|           25 |     1780 | 2024-05-05 | Lemondogs                 | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.314 (0.117)    | 0 (0.000) |    16.45 | aimy, asran, fugor, Mride, pawkoem          |
|           24 |     1788 | 2024-05-05 | Kappa Bar                 | L   | 1.000      | -            | -                | -                | -         |   -17.89 | aimy, asran, fugor, Mride, pawkoem          |
|           23 |     2760 | 2024-04-19 | Lausanne-Sport Esports    | L   | 0.930      | -            | -                | -                | -         |    -8.78 | aimy, asran, fugor, Mride, pawkoem          |
|           22 |     3037 | 2024-04-14 | Young Ninjas              | L   | 0.897      | -            | -                | -                | -         |    -4.02 | aimy, asran, fugor, Mride, pawkoem          |
|           21 |     4133 | 2024-03-22 | Illuminar Gaming          | L   | 0.744      | -            | -                | -                | -         |    -6.23 | aimy, asran, fugor, Mride, pawkoem          |
|           20 |     4186 | 2024-03-21 | ex-Turów Zgorzelec Esport | W   | 0.738      | 0.143        | 0.006 (0.001)    | 0.491 (0.052)    | 0 (0.000) |    16.49 | aimy, asran, fugor, Mride, pawkoem          |
|           19 |     4222 | 2024-03-20 | Mikstura1234              | W   | 0.731      | 0.143        | 0.001 (0.000)    | 0.081 (0.008)    | 0 (0.000) |    13.22 | aimy, asran, fugor, Mride, pawkoem          |
|           18 |     4275 | 2024-03-19 | ENTERPRISE esports        | L   | 0.724      | -            | -                | -                | -         |    -3.12 | aimy, asran, fugor, Mride, pawkoem          |
|           17 |     4316 | 2024-03-18 | ThunderFlash              | L   | 0.717      | -            | -                | -                | -         |    -5.29 | aimy, asran, fugor, Mride, pawkoem          |
|           16 |     4783 | 2024-03-10 | DEEZ NUTS                 | L   | 0.664      | -            | -                | -                | -         |    -9.25 | avis, b1elany, ewrzyn, sh3nanigan, zaNNN    |
|           15 |     5453 | 2024-02-28 | Copenhagen Wolves         | L   | 0.591      | -            | -                | -                | -         |    -8.97 | Basso, Fessor, Svedjehed, szejn, vigg0      |
|           14 |     5513 | 2024-02-27 | ex-Hot Headed Gaming      | L   | 0.584      | -            | -                | -                | -         |   -11.82 | asran, fugor, GruBy, Mride, pawkoem         |
|           13 |     5569 | 2024-02-26 | 0to100                    | W   | 0.578      | 0.371        | 0.000 (0.000)    | 0.012 (0.003)    | 0 (0.000) |     5.27 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|           12 |     5600 | 2024-02-25 | Golden Sword              | W   | 0.571      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.66 | asran, fugor, GruBy, Mride, pawkoem         |
|           11 |     5802 | 2024-02-22 | Grannys Knockers          | L   | 0.551      | -            | -                | -                | -         |    -5.18 | AwwEzz, BaGyZ, prochas, Sidivo, slokker     |
|           10 |     6379 | 2024-02-12 | ex-K10                    | L   | 0.484      | -            | -                | -                | -         |    -3.97 | Rezst, shyyne, SLY, Tree, yz0               |
|            9 |     6386 | 2024-02-12 | ALTERNATE aTTaX           | L   | 0.484      | -            | -                | -                | -         |    -2.11 | asran, fugor, GruBy, Mride, pawkoem         |
|            8 |     6519 | 2024-02-08 | V1dar Gaming              | L   | 0.457      | -            | -                | -                | -         |    -6.51 | asran, fugor, GruBy, Mride, pawkoem         |
|            7 |     6551 | 2024-02-07 | ex-KRC Genk Esports       | W   | 0.451      | 0.371        | 0.000 (0.000)    | 0.173 (0.029)    | 0 (0.000) |     8.45 | asran, fugor, GruBy, Mride, pawkoem         |
|            6 |     6603 | 2024-02-05 | MOUZ NXT                  | L   | 0.438      | -            | -                | -                | -         |    -0.99 | Burmylov, Chr1zN, Neityu, PR, sirah         |
|            5 |     6806 | 2024-02-02 | DASH                      | L   | 0.417      | -            | -                | -                | -         |    -5.54 | asran, fugor, GruBy, Mride, pawkoem         |
|            4 |     6964 | 2024-01-30 | Kappa Bar                 | L   | 0.398      | -            | -                | -                | -         |    -8.39 | asran, fugor, GruBy, Mride, pawkoem         |
|            3 |     6969 | 2024-01-30 | Lemondogs                 | W   | 0.398      | 0.371        | 0.000 (0.000)    | 0.314 (0.046)    | 0 (0.000) |     5.52 | dZ, hechtikal, hemzk9, xelos, zeak          |
|            2 |     7787 | 2024-01-17 | GODSENT                   | L   | 0.311      | -            | -                | -                | -         |    -4.82 | asran, fugor, GruBy, Mride, pawkoem         |
|            1 |     7912 | 2024-01-16 | PARIVISION                | L   | 0.304      | -            | -                | -                | -         |    -1.67 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V       |

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
