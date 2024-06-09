### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [68](../standings_global.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
Final Rank Value:  960.6<br />
<br />
Final Rank Value (960.6) = Starting Rank Value (945.1) + Head To Head Adjustments (15.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.506[<sup>1</sup>](#table2)
- Bounty Collected: 0.397[<sup>2</sup>](#table1)
- Opponent Network: 0.116[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.268<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 945.1
- 400 + ( ( 0.268 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 945.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      324 | 2024-05-25 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -14.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           43 |      415 | 2024-05-23 | Zero Tenacity     | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | 0 (0.000) |    20.54 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           42 |     1016 | 2024-05-17 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.46 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           41 |     1196 | 2024-05-15 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -13.16 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           40 |     1656 | 2024-05-08 | G2 Esports        | L   | 1.000      | -            | -                | -                | -         |    -0.40 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           39 |     2031 | 2024-05-01 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -         |    -5.47 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           38 |     2075 | 2024-04-30 | BetBoom Team      | W   | 1.000      | 0.384        | 0.390 (0.150)    | 0.712 (0.273)    | 0 (0.000) |    28.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           37 |     2883 | 2024-04-17 | Ninjas in Pyjamas | L   | 0.918      | -            | -                | -                | -         |    -8.48 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           36 |     3051 | 2024-04-14 | BetBoom Team      | L   | 0.896      | -            | -                | -                | -         |    -3.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           35 |     3111 | 2024-04-13 | ex-Preasy Esport  | W   | 0.889      | 0.143        | 0.052 (0.007)    | 0.381 (0.048)    | 0 (0.000) |    15.81 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           34 |     3410 | 2024-04-07 | GenOne            | W   | 0.851      | 0.143        | -                | 0.442 (0.054)    | 0 (0.000) |     4.33 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           33 |     3430 | 2024-04-07 | Young Ninjas      | W   | 0.849      | 0.143        | 0.043 (0.005)    | 0.372 (0.045)    | 0 (0.000) |    13.60 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           32 |     3441 | 2024-04-07 | Kedusexdenuit     | W   | 0.848      | -            | -                | -                | 0 (0.000) |     1.30 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           31 |     3896 | 2024-03-27 | AURA              | L   | 0.777      | -            | -                | -                | -         |   -19.21 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           30 |     3976 | 2024-03-26 | ILLYRIANS         | W   | 0.771      | -            | -                | -                | 0 (0.000) |     5.68 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           29 |     4194 | 2024-03-21 | Fnatic            | L   | 0.736      | -            | -                | -                | -         |    -5.61 | Djoko, Ex3rcice, Lucky, Maka, NBK-    |
|           28 |     4281 | 2024-03-19 | GUN5 Esports      | W   | 0.723      | -            | -                | -                | 0 (0.000) |     4.11 | Djoko, Ex3rcice, Lucky, Maka, NBK-    |
|           27 |     4613 | 2024-03-13 | PARIVISION        | L   | 0.683      | -            | -                | -                | -         |   -11.56 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           26 |     5104 | 2024-03-05 | FORZE Esports     | L   | 0.631      | -            | -                | -                | -         |    -7.95 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           25 |     5137 | 2024-03-04 | FLuffy Gangsters  | W   | 0.625      | 0.143        | -                | 0.394 (0.035)    | 0 (0.000) |     2.46 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           24 |     5156 | 2024-03-04 | GenOne            | W   | 0.625      | -            | -                | -                | -         |     2.30 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           23 |     5195 | 2024-03-04 | Fnatic            | L   | 0.623      | -            | -                | -                | -         |    -5.72 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           22 |     5315 | 2024-03-02 | Monte             | W   | 0.611      | 0.500        | 0.181 (0.055)    | 0.387 (0.118)    | -         |    17.03 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           21 |     6166 | 2024-02-16 | 9Pandas           | L   | 0.510      | -            | -                | -                | -         |    -3.52 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           20 |     6227 | 2024-02-15 | Into The Breach   | W   | 0.504      | -            | -                | -                | 1 (0.504) |     4.47 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           19 |     6273 | 2024-02-14 | KOI               | L   | 0.497      | -            | -                | -                | -         |    -7.20 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           18 |     6289 | 2024-02-14 | Team Falcons      | L   | 0.496      | -            | -                | -                | -         |    -0.69 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           17 |     6430 | 2024-02-11 | Apeks             | L   | 0.477      | -            | -                | -                | -         |    -2.49 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           16 |     6484 | 2024-02-09 | Fnatic            | W   | 0.464      | 0.143        | 0.147 (0.010)    | -                | -         |    10.56 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           15 |     6487 | 2024-02-09 | Endpoint          | W   | 0.464      | 0.143        | 0.012 (0.001)    | 0.770 (0.051)    | -         |     7.47 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           14 |     6495 | 2024-02-09 | Sprout            | L   | 0.463      | -            | -                | -                | -         |   -12.13 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           13 |     6976 | 2024-01-30 | Permitta Esports  | L   | 0.397      | -            | -                | -                | -         |    -6.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           12 |     6996 | 2024-01-29 | Team Space        | W   | 0.392      | -            | -                | -                | -         |     4.31 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           11 |     7016 | 2024-01-29 | Passion UA        | W   | 0.392      | 0.143        | 0.057 (0.003)    | 1.000 (0.056)    | -         |     7.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           10 |     7507 | 2024-01-21 | ex-sYnck          | W   | 0.338      | -            | -                | -                | -         |     2.71 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            9 |     7523 | 2024-01-21 | ex-Preasy Esport  | L   | 0.336      | -            | -                | -                | -         |    -5.63 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            8 |     7569 | 2024-01-20 | 9Pandas           | L   | 0.331      | -            | -                | -                | -         |    -2.24 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            7 |     7604 | 2024-01-20 | Zero Tenacity     | W   | 0.329      | 0.143        | 0.147 (0.007)    | 1.000 (0.047)    | -         |     6.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            6 |     7661 | 2024-01-19 | OG                | L   | 0.323      | -            | -                | -                | -         |    -2.08 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            5 |     7715 | 2024-01-18 | Cloud9            | L   | 0.317      | -            | -                | -                | -         |    -0.45 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            4 |     7729 | 2024-01-18 | JANO Esports      | W   | 0.317      | -            | -                | -                | -         |     0.86 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            3 |     9223 | 2023-12-10 | FORZE Esports     | W   | 0.058      | -            | -                | -                | -         |     0.32 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            2 |     9439 | 2023-12-07 | SINNERS Esports   | W   | 0.037      | -            | -                | -                | -         |     0.72 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            1 |     9502 | 2023-12-06 | Apeks             | W   | 0.031      | 0.500        | 0.085 (0.001)    | -                | -         |     0.81 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($31,878.81)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-12 |      1.000 | $23,500.00     | $23,500.00      |
| 2024-05-02 |      1.000 | $1,500.00      | $1,500.00       |
| 2024-04-14 |      0.896 | $4,354.95      | $3,901.31       |
| 2023-12-10 |      0.058 | $17,000.00     | $977.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
