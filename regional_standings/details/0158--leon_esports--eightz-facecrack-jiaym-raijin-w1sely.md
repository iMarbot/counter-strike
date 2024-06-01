### Roster Details<br />
Team Name: LEON Esports<br />
Roster: eightz, facecrack, JIaYm, Raijin, w1sely<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [158](../standings_global.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
Final Rank Value:  768.2<br />
<br />
Final Rank Value (768.2) = Starting Rank Value (753.4) + Head To Head Adjustments (14.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.261[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.136[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 753.4
- 400 + ( ( 0.174 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 753.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           54 |       62 | 2024-05-29 | Smart Walrus           | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.86 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           53 |       95 | 2024-05-29 | NOM Esports            | W   | 1.000      | 0.143        | -                | 0.360 (0.051)    | 0 (0.000) |    10.48 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           52 |      347 | 2024-05-24 | Rustec                 | W   | 1.000      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |    20.22 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           51 |      355 | 2024-05-24 | FORZE Youngsters       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.75 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           50 |      362 | 2024-05-24 | Permitta Esports       | L   | 1.000      | -            | -                | -                | -         |   -11.82 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           49 |      606 | 2024-05-21 | Entropiq               | W   | 1.000      | 0.372        | -                | 0.220 (0.082)    | 0 (0.000) |    14.65 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           48 |      672 | 2024-05-20 | RUBY                   | L   | 1.000      | -            | -                | -                | -         |    -6.29 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           47 |      694 | 2024-05-20 | Dynamo Eclot           | W   | 1.000      | 0.372        | 0.097 (0.036)    | 0.936 (0.348)    | 0 (0.000) |    24.03 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           46 |      803 | 2024-05-19 | Team Space             | L   | 1.000      | -            | -                | -                | -         |    -9.43 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           45 |      930 | 2024-05-18 | Rhyno Esports          | L   | 1.000      | -            | -                | -                | -         |    -6.78 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           44 |     1007 | 2024-05-17 | WOPA Esport            | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.594 (0.085)    | 0 (0.000) |    17.49 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           43 |     1245 | 2024-05-14 | VP.Prodigy             | L   | 1.000      | -            | -                | -                | -         |   -11.26 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           42 |     1301 | 2024-05-13 | Team Secret            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.81 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           41 |     1352 | 2024-05-12 | eternal premium        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.03 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           40 |     1362 | 2024-05-12 | VaselineWorms          | L   | 1.000      | -            | -                | -                | -         |   -16.89 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           39 |     1420 | 2024-05-11 | DOSKI                  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.72 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           38 |     1495 | 2024-05-10 | Nexus Gaming           | L   | 1.000      | -            | -                | -                | -         |    -9.85 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           37 |     1520 | 2024-05-10 | Verdant                | L   | 1.000      | -            | -                | -                | -         |    -8.46 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           36 |     1617 | 2024-05-08 | DMS                    | L   | 1.000      | -            | -                | -                | -         |   -10.42 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           35 |     1685 | 2024-05-07 | Passion UA             | L   | 1.000      | -            | -                | -                | -         |    -7.64 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           34 |     1738 | 2024-05-06 | Verdant                | W   | 1.000      | 0.143        | 0.014 (0.002)    | 1.000 (0.143)    | -         |    21.36 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           33 |     1760 | 2024-05-05 | RUBY                   | L   | 1.000      | -            | -                | -                | -         |    -7.71 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           32 |     2060 | 2024-04-29 | Lausanne-Sport Esports | W   | 0.997      | 0.372        | 0.002 (0.001)    | 0.257 (0.096)    | -         |    16.54 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           31 |     2082 | 2024-04-29 | Nexus Gaming           | L   | 0.995      | -            | -                | -                | -         |    -8.47 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           30 |     2122 | 2024-04-28 | VP.Prodigy             | L   | 0.989      | -            | -                | -                | -         |   -13.60 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           29 |     2314 | 2024-04-25 | HOTU                   | W   | 0.970      | 0.372        | 0.004 (0.002)    | 0.524 (0.189)    | -         |    20.07 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           28 |     2362 | 2024-04-24 | JANO Esports           | W   | 0.964      | 0.372        | 0.003 (0.001)    | 0.392 (0.141)    | -         |    16.96 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           27 |     2429 | 2024-04-23 | JANO Esports           | L   | 0.956      | -            | -                | -                | -         |   -13.19 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           26 |     2458 | 2024-04-22 | Viperio                | L   | 0.950      | -            | -                | -                | -         |   -13.30 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           25 |     2597 | 2024-04-20 | FORZE Youngsters       | W   | 0.936      | -            | -                | -                | -         |     4.05 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           24 |     2792 | 2024-04-18 | BIG                    | L   | 0.922      | -            | -                | -                | -         |    -0.77 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           23 |     2945 | 2024-04-15 | Young Ninjas           | L   | 0.904      | -            | -                | -                | -         |    -6.23 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           22 |     2984 | 2024-04-14 | Insilio                | L   | 0.896      | -            | -                | -                | -         |    -6.26 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           21 |     3123 | 2024-04-11 | GenOne                 | W   | 0.876      | 0.372        | -                | 0.442 (0.144)    | -         |    10.96 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           20 |     3341 | 2024-04-07 | Lazer Cats             | L   | 0.849      | -            | -                | -                | -         |   -14.09 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           19 |     3350 | 2024-04-07 | CyberMAN               | W   | 0.849      | -            | -                | -                | -         |     3.88 | ASTR, Dabok, H1kari, makaroff, vladick1234   |
|           18 |     3396 | 2024-04-06 | DMS                    | L   | 0.843      | -            | -                | -                | -         |   -11.53 | AW, H1te, kAlash, sFade8, sm3t               |
|           17 |     3401 | 2024-04-06 | REDPack Esports        | W   | 0.842      | -            | -                | -                | -         |     5.23 | bitu, BRK, H4rder, KaroL, Yoghi              |
|           16 |     4161 | 2024-03-19 | HyperSpirit            | L   | 0.725      | -            | -                | -                | -         |   -11.29 | ADRON, GEOHYPE, kritik, smekk, swiiffter     |
|           15 |     4174 | 2024-03-19 | Dynamo Eclot           | L   | 0.723      | -            | -                | -                | -         |    -3.68 | Blytz, Dytor, forsyy, kreaz, nbqq            |
|           14 |     4367 | 2024-03-15 | Viperio                | W   | 0.698      | -            | -                | -                | -         |     8.65 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|           13 |     4626 | 2024-03-11 | ARCRED                 | L   | 0.669      | -            | -                | -                | -         |    -9.14 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           12 |     4665 | 2024-03-10 | HyperSpirit            | W   | 0.663      | 0.333        | 0.004 (0.001)    | 0.356 (0.079)    | -         |     9.44 | ADRON, GEOHYPE, kritik, smekk, swiiffter     |
|           11 |     4793 | 2024-03-07 | Pingu E-Sports         | W   | 0.645      | -            | -                | -                | -         |     2.53 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|           10 |     4868 | 2024-03-06 | PCIFIC Espor           | W   | 0.637      | -            | -                | -                | -         |     2.53 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            9 |     5004 | 2024-03-04 | Gaimin Gladiators      | L   | 0.625      | -            | -                | -                | -         |    -1.07 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            8 |     5147 | 2024-03-02 | ex-Preasy Esport       | L   | 0.611      | -            | -                | -                | -         |    -4.75 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            7 |     7635 | 2024-01-16 | ex-Anonymo Esports     | L   | 0.305      | -            | -                | -                | -         |    -5.08 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            6 |     7677 | 2024-01-16 | RUSH B                 | W   | 0.304      | 0.143        | 0.001 (0.000)    | -                | -         |     4.85 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            5 |     8605 | 2023-12-16 | INGLORIOUS             | L   | 0.097      | -            | -                | -                | -         |    -1.56 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1        |
|            4 |     8928 | 2023-12-11 | NOM Esports            | L   | 0.064      | -            | -                | -                | -         |    -1.31 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            3 |     8960 | 2023-12-10 | Team Raised            | W   | 0.057      | -            | -                | -                | -         |     0.22 | ferrariri, maaak, msle, ruddaenami, ssspring |
|            2 |     9146 | 2023-12-07 | Eternal Fire Academy   | L   | 0.038      | -            | -                | -                | -         |    -0.76 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            1 |     9271 | 2023-12-05 | Kolon 3                | W   | 0.025      | -            | -                | -                | -         |     0.09 | Ayoh, fippe, looky, mogv, simpan             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($450.75)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
