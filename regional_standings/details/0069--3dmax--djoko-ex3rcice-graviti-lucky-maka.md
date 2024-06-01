### Roster Details<br />
Team Name: 3DMAX<br />
Roster: Djoko, Ex3rcice, Graviti, Lucky, Maka<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [69](../standings_global.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
Final Rank Value:  948.5<br />
<br />
Final Rank Value (948.5) = Starting Rank Value (944.2) + Head To Head Adjustments (4.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.506[<sup>1</sup>](#table2)
- Bounty Collected: 0.396[<sup>2</sup>](#table1)
- Opponent Network: 0.114[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.267<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 944.2
- 400 + ( ( 0.267 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 944.2


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
|           43 |      316 | 2024-05-25 | MOUZ NXT          | L   | 1.000      | -            | -                | -                | -         |   -14.12 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           42 |      407 | 2024-05-23 | Zero Tenacity     | W   | 1.000      | 0.435        | 0.147 (0.064)    | 1.000 (0.435)    | 0 (0.000) |    20.86 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           41 |     1004 | 2024-05-17 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.83 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           40 |     1186 | 2024-05-15 | Zero Tenacity     | L   | 1.000      | -            | -                | -                | -         |   -12.72 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           39 |     1638 | 2024-05-08 | G2 Esports        | L   | 1.000      | -            | -                | -                | -         |    -0.36 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           38 |     2000 | 2024-05-01 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -         |    -5.11 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           37 |     2041 | 2024-04-30 | BetBoom Team      | W   | 1.000      | 0.384        | 0.390 (0.150)    | 0.712 (0.273)    | 0 (0.000) |    28.57 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           36 |     2826 | 2024-04-17 | Ninjas in Pyjamas | L   | 0.918      | -            | -                | -                | -         |    -8.00 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           35 |     2986 | 2024-04-14 | BetBoom Team      | L   | 0.896      | -            | -                | -                | -         |    -3.08 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           34 |     3045 | 2024-04-13 | ex-Preasy Esport  | W   | 0.889      | 0.143        | 0.052 (0.007)    | 0.381 (0.048)    | 0 (0.000) |    16.24 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           33 |     3329 | 2024-04-07 | GenOne            | W   | 0.851      | 0.143        | -                | 0.442 (0.054)    | 0 (0.000) |     4.58 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           32 |     3358 | 2024-04-07 | Kedusexdenuit     | W   | 0.848      | -            | -                | -                | 0 (0.000) |     1.31 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           31 |     3803 | 2024-03-27 | AURA              | L   | 0.777      | -            | -                | -                | -         |   -19.27 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           30 |     3879 | 2024-03-26 | ILLYRIANS         | W   | 0.771      | 0.143        | -                | 0.319 (0.035)    | 0 (0.000) |     5.67 | Djoko, Ex3rcice, Graviti, Lucky, Maka |
|           29 |     4095 | 2024-03-21 | Fnatic            | L   | 0.736      | -            | -                | -                | -         |    -5.59 | Djoko, Ex3rcice, Lucky, Maka, NBK-    |
|           28 |     4178 | 2024-03-19 | GUN5 Esports      | W   | 0.723      | -            | -                | -                | 0 (0.000) |     4.00 | Djoko, Ex3rcice, Lucky, Maka, NBK-    |
|           27 |     4498 | 2024-03-13 | PARIVISION        | L   | 0.683      | -            | -                | -                | -         |   -11.52 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           26 |     4961 | 2024-03-05 | FORZE Esports     | L   | 0.631      | -            | -                | -                | -         |    -7.62 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           25 |     4991 | 2024-03-04 | FLuffy Gangsters  | W   | 0.625      | -            | -                | -                | 0 (0.000) |     2.04 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           24 |     5010 | 2024-03-04 | GenOne            | W   | 0.625      | -            | -                | -                | 0 (0.000) |     2.26 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           23 |     5049 | 2024-03-04 | Fnatic            | L   | 0.623      | -            | -                | -                | -         |    -5.71 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           22 |     5167 | 2024-03-02 | Monte             | W   | 0.611      | 0.500        | 0.181 (0.055)    | 0.363 (0.111)    | -         |    17.01 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           21 |     5991 | 2024-02-16 | 9Pandas           | L   | 0.510      | -            | -                | -                | -         |    -3.65 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           20 |     6046 | 2024-02-15 | Into The Breach   | W   | 0.504      | -            | -                | -                | 1 (0.504) |     4.47 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           19 |     6092 | 2024-02-14 | KOI               | L   | 0.497      | -            | -                | -                | -         |    -7.27 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           18 |     6108 | 2024-02-14 | Team Falcons      | L   | 0.496      | -            | -                | -                | -         |    -0.68 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           17 |     6242 | 2024-02-11 | Apeks             | L   | 0.477      | -            | -                | -                | -         |    -2.44 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           16 |     6296 | 2024-02-09 | Fnatic            | W   | 0.464      | 0.143        | 0.147 (0.010)    | 0.480 (0.032)    | -         |    10.56 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           15 |     6299 | 2024-02-09 | Endpoint          | W   | 0.464      | 0.143        | 0.012 (0.001)    | 0.718 (0.048)    | -         |     7.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           14 |     6307 | 2024-02-09 | Sprout            | L   | 0.463      | -            | -                | -                | -         |   -12.27 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           13 |     6760 | 2024-01-30 | Permitta Esports  | L   | 0.397      | -            | -                | -                | -         |    -6.33 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           12 |     6780 | 2024-01-29 | Team Space        | W   | 0.392      | 0.143        | 0.009 (0.001)    | -                | -         |     4.33 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           11 |     6800 | 2024-01-29 | Passion UA        | W   | 0.392      | 0.143        | 0.057 (0.003)    | 1.000 (0.056)    | -         |     7.11 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|           10 |     7264 | 2024-01-21 | ex-sYnck          | W   | 0.338      | -            | -                | -                | -         |     2.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            9 |     7280 | 2024-01-21 | ex-Preasy Esport  | L   | 0.336      | -            | -                | -                | -         |    -5.67 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            8 |     7325 | 2024-01-20 | 9Pandas           | L   | 0.331      | -            | -                | -                | -         |    -2.35 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            7 |     7360 | 2024-01-20 | Zero Tenacity     | W   | 0.329      | 0.143        | 0.147 (0.007)    | 1.000 (0.047)    | -         |     6.84 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            6 |     7415 | 2024-01-19 | OG                | L   | 0.323      | -            | -                | -                | -         |    -2.06 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            5 |     7467 | 2024-01-18 | Cloud9            | L   | 0.317      | -            | -                | -                | -         |    -0.44 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            4 |     7480 | 2024-01-18 | JANO Esports      | W   | 0.317      | -            | -                | -                | -         |     0.87 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            3 |     8957 | 2023-12-10 | FORZE Esports     | W   | 0.058      | -            | -                | -                | -         |     0.36 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            2 |     9166 | 2023-12-07 | SINNERS Esports   | W   | 0.037      | -            | -                | -                | -         |     0.68 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |
|            1 |     9221 | 2023-12-06 | Apeks             | W   | 0.031      | 0.500        | 0.085 (0.001)    | -                | -         |     0.81 | Djoko, Ex3rcice, hAdji, Lucky, Maka   |

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
