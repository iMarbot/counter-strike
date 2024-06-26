### Roster Details<br />
Team Name: ILLYRIANS<br />
Roster: BledarD, Caleyy, Dementor, HYPERI1, vAloN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [173](../standings_global.md)<br />
Regional Rank: [120]( ../standings_europe.md)<br />
Final Rank Value:  761.2<br />
<br />
Final Rank Value (761.2) = Starting Rank Value (740.3) + Head To Head Adjustments (21.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.182[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.190[<sup>2</sup>](#table1)

The average of these factors is 0.167<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 740.3
- 400 + ( ( 0.167 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 740.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      294 | 2024-05-25 | ex-Guild Eagles    | L   | 1.000      | -            | -                | -                | -         |    -7.58 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           30 |      359 | 2024-05-24 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |    -5.43 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           29 |      773 | 2024-05-19 | Jake Bube          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.048 (0.007)    | 0 (0.000) |     6.02 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           28 |      804 | 2024-05-19 | RUR Esports        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.049 (0.007)    | 0 (0.000) |     4.05 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           27 |     1374 | 2024-05-12 | CYBERSHOKE Esports | L   | 1.000      | -            | -                | -                | -         |   -18.52 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           26 |     1388 | 2024-05-12 | kONO.ECF           | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.853 (0.122)    | 0 (0.000) |    22.39 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           25 |     1523 | 2024-05-10 | kONO.ECF           | L   | 1.000      | -            | -                | -                | -         |    -8.78 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           24 |     1532 | 2024-05-10 | Grannys Knockers   | W   | 1.000      | 0.143        | 0.006 (0.001)    | 0.517 (0.074)    | 0 (0.000) |    17.89 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           23 |     1847 | 2024-05-04 | M1X                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.066 (0.009)    | 0 (0.000) |    10.11 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           22 |     1862 | 2024-05-04 | Cupava Veverica    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.43 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           21 |     2213 | 2024-04-27 | iNation            | L   | 0.983      | -            | -                | -                | -         |   -17.42 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           20 |     2234 | 2024-04-27 | Jake Bube          | W   | 0.982      | 0.143        | -                | 0.048 (0.007)    | 0 (0.000) |     6.11 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           19 |     2306 | 2024-04-26 | RUR Esports        | W   | 0.976      | 0.143        | -                | 0.049 (0.007)    | 0 (0.000) |     5.11 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           18 |     2308 | 2024-04-26 | M1X                | W   | 0.976      | -            | -                | -                | -         |     5.93 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           17 |     2607 | 2024-04-20 | ARCRED             | L   | 0.937      | -            | -                | -                | -         |   -12.33 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           16 |     2620 | 2024-04-20 | MIREA              | W   | 0.937      | -            | -                | -                | -         |     3.60 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           15 |     3044 | 2024-04-14 | HEROES             | W   | 0.897      | 0.143        | 0.001 (0.000)    | -                | 1 (0.897) |    11.23 | BledarD, Caleyy, deb0, Dementor, HYPERI1         |
|           14 |     3058 | 2024-04-14 | avoiD              | W   | 0.895      | -            | -                | -                | 1 (0.895) |     3.76 | BledarD, Caleyy, deb0, Dementor, HYPERI1         |
|           13 |     3976 | 2024-03-26 | 3DMAX              | L   | 0.771      | -            | -                | -                | -         |    -5.68 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           12 |     5151 | 2024-03-04 | KOI                | L   | 0.625      | -            | -                | -                | -         |    -3.41 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           11 |     5282 | 2024-03-02 | ILIN               | L   | 0.611      | -            | -                | -                | -         |   -13.01 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           10 |     5308 | 2024-03-02 | AMKAL ESPORTS      | W   | 0.611      | 0.143        | 0.146 (0.013)    | 0.565 (0.049)    | -         |    17.75 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|            9 |     6449 | 2024-02-10 | kONO.ECF           | L   | 0.471      | -            | -                | -                | -         |    -3.90 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy   |
|            8 |     6459 | 2024-02-10 | 9INE               | W   | 0.470      | 0.143        | -                | 0.131 (0.009)    | -         |     4.22 | Bambosh, KEi, mhL, mynio, tomiko                 |
|            7 |     6975 | 2024-01-30 | RUBY               | L   | 0.397      | -            | -                | -                | -         |    -3.36 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|            6 |     7006 | 2024-01-29 | FAVBET Team        | W   | 0.392      | 0.143        | 0.008 (0.000)    | 0.845 (0.047)    | -         |     8.03 | bondik, guthriee, j3kie, Smash, t3ns1on          |
|            5 |     7028 | 2024-01-29 | Bootcamp Aktau     | W   | 0.392      | 0.143        | 0.004 (0.000)    | -                | -         |     6.62 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|            4 |     7200 | 2024-01-27 | AIRLYA             | L   | 0.377      | -            | -                | -                | -         |    -9.26 | aidKiT, bibu, dan1, powerdy, stressarN           |
|            3 |     7272 | 2024-01-26 | HyperSpirit        | L   | 0.370      | -            | -                | -                | -         |    -5.63 | ADRON, GEOHYPE, kritik, smekk, swiiffter         |
|            2 |     7795 | 2024-01-17 | KOI                | L   | 0.311      | -            | -                | -                | -         |    -2.13 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|            1 |     9654 | 2023-12-03 | Heimo Esports      | W   | 0.010      | 0.294        | 0.011 (0.000)    | -                | -         |     0.15 | arvid, japE, oopee, ottob, Tumppis               |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9.81)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
