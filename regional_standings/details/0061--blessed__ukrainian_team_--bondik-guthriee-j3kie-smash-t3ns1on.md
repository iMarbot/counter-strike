### Roster Details<br />
Team Name: BLESSED (Ukrainian team)<br />
Roster: bondik, guthriee, j3kie, Smash, t3ns1on<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [61](../standings_global.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
Final Rank Value:  948.9<br />
<br />
Final Rank Value (948.9) = Starting Rank Value (840.1) + Head To Head Adjustments (108.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.365[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 840.1
- 400 + ( ( 0.222 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 840.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |      105 | 2024-05-03 | AscendX Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.26 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           49 |      223 | 2024-05-01 | Johnny Speeds               | W   | 1.000      | 0.333        | 0.044 (0.015)    | 0.718 (0.239)    | 0 (0.000) |    16.67 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           48 |      238 | 2024-04-30 | Permitta Esports            | L   | 1.000      | -            | -                | -                | -         |   -17.27 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           47 |      468 | 2024-04-25 | Copenhagen Wolves           | L   | 1.000      | -            | -                | -                | -         |   -27.21 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           46 |      600 | 2024-04-22 | LOADING (French team)       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.30 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           45 |     1211 | 2024-04-10 | Lemondogs                   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.61 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           44 |     1540 | 2024-04-03 | Metizport                   | L   | 0.984      | -            | -                | -                | -         |    -9.19 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           43 |     1574 | 2024-04-02 | Ninjas in Pyjamas           | L   | 0.978      | -            | -                | -                | -         |    -8.10 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           42 |     1584 | 2024-04-02 | GamerLegion                 | W   | 0.977      | 0.143        | 0.194 (0.027)    | -                | 0 (0.000) |    29.20 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           41 |     1624 | 2024-03-31 | Passion UA                  | W   | 0.964      | 0.143        | 0.114 (0.016)    | 0.980 (0.135)    | 0 (0.000) |    14.62 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           40 |     1640 | 2024-03-30 | L&G                         | W   | 0.957      | -            | -                | -                | 0 (0.000) |     6.57 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           39 |     1730 | 2024-03-27 | ALTERNATE aTTaX             | W   | 0.939      | 0.143        | 0.110 (0.015)    | -                | 0 (0.000) |    15.87 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           38 |     1740 | 2024-03-27 | BetBoom Team                | W   | 0.939      | 0.143        | 0.571 (0.077)    | -                | 0 (0.000) |    27.80 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           37 |     1753 | 2024-03-27 | L&G                         | W   | 0.938      | -            | -                | -                | 0 (0.000) |     8.24 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           36 |     1859 | 2024-03-24 | Chroma                      | W   | 0.918      | -            | -                | -                | -         |     3.17 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           35 |     2460 | 2024-03-10 | GODSENT                     | L   | 0.825      | -            | -                | -                | -         |   -17.35 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           34 |     2500 | 2024-03-09 | GamerLegion Academy         | W   | 0.818      | 0.289        | 0.043 (0.010)    | 0.567 (0.134)    | -         |    10.47 | Darber, Goody, leaf, nestee, rud               |
|           33 |     2529 | 2024-03-08 | Nexus Gaming                | L   | 0.812      | -            | -                | -                | -         |   -11.87 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           32 |     2577 | 2024-03-07 | AVEZ                        | W   | 0.804      | -            | -                | -                | -         |     5.53 | AntyVirus, przemeklovel, smooho, SpavaQ, Yamii |
|           31 |     2624 | 2024-03-06 | CYBERSHOKE Esports          | W   | 0.798      | -            | -                | -                | -         |     7.54 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz      |
|           30 |     2702 | 2024-03-05 | Preasy Esport               | W   | 0.791      | -            | -                | -                | -         |     7.75 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           29 |     2870 | 2024-03-02 | Sashi Academy               | W   | 0.772      | -            | -                | -                | -         |     6.00 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           28 |     2913 | 2024-03-01 | Entropiq                    | W   | 0.765      | 0.371        | -                | 0.436 (0.124)    | -         |    10.44 | c0llins, Marix, mwlky, Oxygen, tiziaN          |
|           27 |     2917 | 2024-03-01 | The Chosen Few              | W   | 0.765      | 0.371        | 0.007 (0.002)    | 0.457 (0.130)    | -         |    10.10 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN        |
|           26 |     2945 | 2024-02-29 | 1win                        | W   | 0.759      | -            | -                | -                | -         |     9.85 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           25 |     2979 | 2024-02-28 | ENTERPRISE esports          | W   | 0.752      | 0.371        | 0.039 (0.011)    | 0.476 (0.133)    | -         |    15.11 | bajmi, Demho, Ex1st, fr3nd, TOAO               |
|           24 |     2989 | 2024-02-28 | Lilmix                      | W   | 0.752      | 0.371        | -                | 0.604 (0.168)    | -         |     6.38 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           23 |     3039 | 2024-02-27 | Rhyno Esports               | W   | 0.744      | 0.371        | 0.047 (0.013)    | 0.446 (0.123)    | -         |    14.01 | DDias, krazy, renatoohaxx, snapy, TMKj         |
|           22 |     3042 | 2024-02-27 | UNiTY esports (Slovak team) | W   | 0.744      | 0.371        | 0.055 (0.015)    | 0.727 (0.201)    | -         |    14.81 | Levi, luko, M1key, NIO, Pechyn                 |
|           21 |     3212 | 2024-02-23 | Sashi Esport                | L   | 0.718      | -            | -                | -                | -         |    -3.48 | Cabbi, IceBerg, kwezz, Lucky, MistR            |
|           20 |     3217 | 2024-02-23 | DMS                         | W   | 0.718      | 0.371        | -                | 0.504 (0.134)    | -         |     7.42 | AW, H1te, kAlash, sFade8, sm3t                 |
|           19 |     3244 | 2024-02-22 | Kappa Bar                   | W   | 0.712      | -            | -                | -                | -         |     7.09 | dezt, jayzaR, pupcake, TIM, upE                |
|           18 |     3714 | 2024-02-12 | NOM Esports                 | L   | 0.646      | -            | -                | -                | -         |   -14.46 | dan1, Libido, meztal, MOREE, ultimate          |
|           17 |     3838 | 2024-02-07 | EsmagaB                     | L   | 0.612      | -            | -                | -                | -         |    -8.10 | Ag1l, aragornN, NOPEEj, pr, rafaxF             |
|           16 |     4030 | 2024-02-02 | 9Pandas                     | L   | 0.578      | -            | -                | -                | -         |    -2.34 | clax, d1Ledez, glowiing, iDISBALANCE, seized   |
|           15 |     4043 | 2024-02-02 | M1X                         | W   | 0.578      | -            | -                | -                | -         |     1.68 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           14 |     4102 | 2024-01-31 | Lajtbitexe                  | W   | 0.566      | -            | -                | -                | -         |     3.58 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           13 |     4166 | 2024-01-29 | ILLYRIANS                   | L   | 0.553      | -            | -                | -                | -         |   -10.79 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           12 |     4783 | 2024-01-16 | Nexus Gaming                | L   | 0.466      | -            | -                | -                | -         |    -5.29 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           11 |     4792 | 2024-01-16 | Team OWL                    | W   | 0.466      | -            | -                | -                | -         |     1.98 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|           10 |     4891 | 2024-01-13 | Ex-Anonymo Esports          | L   | 0.444      | -            | -                | -                | -         |    -7.42 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            9 |     5061 | 2024-01-10 | GUN5 Esports                | L   | 0.426      | -            | -                | -                | -         |    -9.84 | bondik, guthriee, j3kie, Smash, t3ns1on        |
|            8 |     6159 | 2023-12-01 | Nexus Gaming                | W   | 0.159      | -            | -                | -                | -         |     3.26 | BTN, ragga, s0und, smekk, XELLOW               |
|            7 |     6244 | 2023-11-29 | The Witchers                | L   | 0.146      | -            | -                | -                | -         |    -2.61 | bondik, Edward, MUV, Smash, t3ns1on            |
|            6 |     6468 | 2023-11-24 | Insilio                     | L   | 0.112      | -            | -                | -                | -         |    -1.35 | bondik, Edward, MUV, Smash, t3ns1on            |
|            5 |     6505 | 2023-11-23 | Kappa Bar                   | L   | 0.106      | -            | -                | -                | -         |    -2.35 | bondik, Edward, MUV, Smash, t3ns1on            |
|            4 |     6551 | 2023-11-22 | EHawks                      | L   | 0.099      | -            | -                | -                | -         |    -2.62 | arbnorz, Diviiii, Razzmo, Wonderful_Y, xReal   |
|            3 |     6617 | 2023-11-20 | MOUZ NXT                    | L   | 0.086      | -            | -                | -                | -         |    -0.53 | Chr1zN, Neityu, Nexius, PR, sirah              |
|            2 |     6769 | 2023-11-17 | GenOne                      | W   | 0.065      | -            | -                | -                | -         |     0.47 | bondik, Edward, MUV, Smash, t3ns1on            |
|            1 |     6953 | 2023-11-13 | Lemondogs                   | W   | 0.039      | -            | -                | -                | -         |     0.23 | bondik, Edward, MUV, Smash, t3ns1on            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,865.86)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.964 | $1,276.37      | $1,230.40       |
| 2024-03-09 |      0.818 | $2,000.00      | $1,635.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
