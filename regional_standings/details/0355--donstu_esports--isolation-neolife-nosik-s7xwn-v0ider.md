### Roster Details<br />
Team Name: Donstu Esports<br />
Roster: isolatioN, NeoLife, Nosik, s7xWn, V0ider<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [355](../standings_global.md)<br />
Regional Rank: [212]( ../standings_europe.md)<br />
Final Rank Value:  604.4<br />
<br />
Final Rank Value (604.4) = Starting Rank Value (527.3) + Head To Head Adjustments (77.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 527.3
- 400 + ( ( 0.063 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 527.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |      142 | 2024-05-28 | DOSKI             | L   | 1.000      | -            | -                | -                | -         |   -21.61 | isolatioN, NeoLife, Nosik, s7xWn, V0ider     |
|           18 |      182 | 2024-05-27 | Team PeeP         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.247 (0.035)    | 0 (0.000) |    17.56 | isolatioN, NeoLife, Nosik, s7xWn, V0ider     |
|           17 |      198 | 2024-05-27 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |    -8.96 | isolatioN, NeoLife, Nosik, s7xWn, V0ider     |
|           16 |      325 | 2024-05-24 | FLuffy Gangsters  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.394 (0.056)    | 0 (0.000) |    20.37 | isolatioN, NeoLife, Nosik, s7xWn, V0ider     |
|           15 |      495 | 2024-05-22 | TOR               | W   | 1.000      | 0.143        | 0.014 (0.002)    | 0.196 (0.028)    | 0 (0.000) |    25.00 | isolatioN, NeoLife, Nosik, s7xWn, V0ider     |
|           14 |      590 | 2024-05-21 | polizej           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.70 | isolatioN, NeoLife, Nosik, s7xWn, V0ider     |
|           13 |     4347 | 2024-03-17 | ADEPTS            | L   | 0.711      | -            | -                | -                | -         |    -3.94 | aNsavage, NeoLife, Nosik, s7xWn, Snoob       |
|           12 |     4413 | 2024-03-16 | Gorillas          | W   | 0.704      | 0.333        | 0.000 (0.000)    | 0.037 (0.009)    | 0 (0.000) |    11.80 | aNsavage, NeoLife, Nosik, s7xWn, Snoob       |
|           11 |     4543 | 2024-03-14 | CUBE BY SND       | W   | 0.691      | 0.333        | 0.003 (0.001)    | 0.205 (0.047)    | 0 (0.000) |    15.45 | adai, dosikzz, mag1k3Y, OxygeN, syph0        |
|           10 |     4715 | 2024-03-11 | ARROW             | L   | 0.671      | -            | -                | -                | -         |    -5.88 | j1NZO, Kre1N, Orbit, Tionix, Twiksar         |
|            9 |     4926 | 2024-03-07 | TeamOrangeGaming  | W   | 0.645      | 0.333        | 0.006 (0.001)    | 0.235 (0.051)    | 0 (0.000) |    16.43 | Cl0uTz, edox, kinQ, Pictrucz, Spidergum      |
|            8 |     7892 | 2024-01-16 | FAVBET Team       | L   | 0.304      | -            | -                | -                | -         |    -1.41 | bondik, guthriee, j3kie, Smash, t3ns1on      |
|            7 |     7909 | 2024-01-16 | aimclub           | W   | 0.304      | 0.143        | 0.000 (0.000)    | 0.009 (0.000)    | 0 (0.000) |     4.08 | aNsavage, NeoLife, Nosik, s7xWn, Snoob       |
|            6 |     8741 | 2023-12-17 | VaselineWorms     | L   | 0.103      | -            | -                | -                | -         |    -0.82 | aliot, kashl1d, Muk0s, relaxxie, zweih       |
|            5 |     8889 | 2023-12-16 | ARCRED            | L   | 0.096      | -            | -                | -                | -         |    -0.60 | aNsavage, NeoLife, Nosik, s7xWn, Snoob       |
|            4 |     8908 | 2023-12-16 | FLuffy Gangsters  | W   | 0.095      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.99 | 7tetsu, b1st, h1ghnesS, mo5kow, takanashi    |
|            3 |     9278 | 2023-12-09 | HyperSpirit       | L   | 0.051      | -            | -                | -                | -         |    -0.35 | ADRON, awks, GEOHYPE, kritik, swiiffter      |
|            2 |     9422 | 2023-12-07 | VP.Prodigy        | L   | 0.038      | -            | -                | -                | -         |    -0.18 | dwushka, KusMe, shady, Something, xdENiSZERA |
|            1 |     9557 | 2023-12-05 | NOM Esports       | W   | 0.025      | 0.333        | 0.000 (0.000)    | 0.019 (0.000)    | 0 (0.000) |     0.51 | aNsavage, NeoLife, Nosik, s7xWn, Snoob       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
