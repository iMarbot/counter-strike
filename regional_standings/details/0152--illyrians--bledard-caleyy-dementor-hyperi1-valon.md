### Roster Details<br />
Team Name: ILLYRIANS<br />
Roster: BledarD, Caleyy, Dementor, HYPERI1, vAloN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [152](../standings_global.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
Final Rank Value:  774.1<br />
<br />
Final Rank Value (774.1) = Starting Rank Value (731.2) + Head To Head Adjustments (42.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.167<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 731.2
- 400 + ( ( 0.167 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 731.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |       64 | 2024-05-04 | M1X                      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.097 (0.014)    | false (0.000) |     9.91 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           21 |       75 | 2024-05-04 | Cupava Veverica          | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     3.97 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           20 |      378 | 2024-04-27 | Jake Bube                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.038 (0.005)    | false (0.000) |     6.45 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           19 |      436 | 2024-04-26 | RUR Esports              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.069 (0.010)    | false (0.000) |     5.31 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           18 |      437 | 2024-04-26 | M1X                      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.097 (0.014)    | false (0.000) |    10.37 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           17 |      690 | 2024-04-20 | ARCRED                   | L   | 1.000      | -            | -                | -                | -             |   -12.65 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           16 |      702 | 2024-04-20 | MIREA                    | W   | 1.000      | -            | -                | -                | false (0.000) |     3.80 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           15 |     1067 | 2024-04-14 | HEROES (Kosovar team)    | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.063 (0.009)    | true (1.000)  |    15.99 | BledarD, Caleyy, deb0, Dementor, HYPERI1         |
|           14 |     1814 | 2024-03-26 | 3DMAX                    | L   | 0.932      | -            | -                | -                | -             |    -6.27 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           13 |     2737 | 2024-03-04 | KOI                      | L   | 0.786      | -            | -                | -                | -             |    -3.11 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           12 |     2838 | 2024-03-02 | ILIN                     | L   | 0.773      | -            | -                | -                | -             |   -15.52 | abiraju, bogemtdarf, fineshine, la3euka, lampada |
|           11 |     2860 | 2024-03-02 | AMKAL ESPORTS            | W   | 0.772      | 0.143        | 0.209 (0.023)    | 0.756 (0.083)    | false (0.000) |    22.49 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|           10 |     3774 | 2024-02-10 | 9INE                     | W   | 0.631      | 0.143        | -                | 0.230 (0.021)    | false (0.000) |     6.98 | Bambosh, KEi, mhL, mynio, tomiko                 |
|            9 |     4143 | 2024-01-30 | RUBY                     | L   | 0.558      | -            | -                | -                | -             |    -5.28 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|            8 |     4166 | 2024-01-29 | BLESSED (Ukrainian team) | W   | 0.553      | 0.143        | 0.018 (0.001)    | 0.781 (0.062)    | false (0.000) |    10.79 | bondik, guthriee, j3kie, Smash, t3ns1on          |
|            7 |     4183 | 2024-01-29 | Bootcamp Aktau           | W   | 0.553      | 0.143        | 0.009 (0.001)    | 0.094 (0.007)    | -             |     9.98 | BledarD, Caleyy, Dementor, HYPERI1, vAloN        |
|            6 |     4279 | 2024-01-27 | AIRLYA                   | L   | 0.538      | -            | -                | -                | -             |   -12.71 | aidKiT, bibu, dan1, powerdy, stressarN           |
|            5 |     4327 | 2024-01-26 | HyperSpirit              | L   | 0.531      | -            | -                | -                | -             |    -8.36 | ADRON, GEOHYPE, kritik, smekk, swiiffter         |
|            4 |     6043 | 2023-12-03 | Heimo Esports            | W   | 0.171      | 0.294        | 0.020 (0.001)    | 0.229 (0.012)    | -             |     2.71 | arvid, japE, oopee, ottob, Tumppis               |
|            3 |     6478 | 2023-11-24 | M1X                      | L   | 0.111      | -            | -                | -                | -             |    -2.18 | ammar, cerber, deb0, gejmzilla, v1w              |
|            2 |     6502 | 2023-11-23 | Guild Eagles             | L   | 0.106      | -            | -                | -                | -             |    -0.54 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy      |
|            1 |     6594 | 2023-11-21 | PSYCHOACTiVE             | W   | 0.091      | -            | -                | -                | -             |     0.72 | BledarD, Caleyy, HYPERI1, Rand, vAloN            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($170.88)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
