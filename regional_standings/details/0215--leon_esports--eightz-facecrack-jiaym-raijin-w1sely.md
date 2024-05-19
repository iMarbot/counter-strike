### Roster Details<br />
Team Name: LEON Esports<br />
Roster: eightz, facecrack, JIaYm, Raijin, w1sely<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [215](../standings_global.md)<br />
Regional Rank: [142]( ../standings_europe.md)<br />
Final Rank Value:  698.1<br />
<br />
Final Rank Value (698.1) = Starting Rank Value (696.8) + Head To Head Adjustments (1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.289[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 696.8
- 400 + ( ( 0.150 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 696.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |        9 | 2024-05-05 | RUBY                  | L   | 1.000      | -            | -                | -                | -         |    -6.41 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           30 |      290 | 2024-04-29 | Nexus Gaming          | L   | 1.000      | -            | -                | -                | -         |    -7.00 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           29 |      319 | 2024-04-28 | VP.Prodigy            | L   | 1.000      | -            | -                | -                | -         |   -13.30 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           28 |      475 | 2024-04-25 | HOTU                  | W   | 1.000      | 0.371        | 0.011 (0.004)    | 0.323 (0.120)    | 0 (0.000) |    18.91 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           27 |      519 | 2024-04-24 | JANO Esports          | W   | 1.000      | 0.371        | 0.006 (0.002)    | 0.407 (0.151)    | 0 (0.000) |    17.92 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           26 |      586 | 2024-04-23 | JANO Esports          | L   | 1.000      | -            | -                | -                | -         |   -13.39 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           25 |      730 | 2024-04-20 | FORZE Youngsters      | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.92 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           24 |      904 | 2024-04-18 | BIG                   | L   | 1.000      | -            | -                | -                | -         |    -0.59 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           23 |     1038 | 2024-04-15 | Young Ninjas          | L   | 1.000      | -            | -                | -                | -         |    -5.55 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           22 |     1071 | 2024-04-14 | Insilio               | L   | 1.000      | -            | -                | -                | -         |    -5.80 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           21 |     1179 | 2024-04-11 | GenOne                | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.323 (0.120)    | 0 (0.000) |    11.89 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           20 |     1372 | 2024-04-07 | CyberMAN              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.033 (0.005)    | 0 (0.000) |     5.44 | ASTR, Dabok, H1kari, makaroff, vladick1234   |
|           19 |     1404 | 2024-04-06 | DMS                   | L   | 1.000      | -            | -                | -                | -         |   -12.95 | AW, H1te, kAlash, sFade8, sm3t               |
|           18 |     1409 | 2024-04-06 | REDPack Esports       | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     4.85 | bitu, BRK, H4rder, KaroL, Yoghi              |
|           17 |     2049 | 2024-03-19 | HyperSpirit           | L   | 0.886      | -            | -                | -                | -         |   -13.60 | ADRON, GEOHYPE, kritik, smekk, swiiffter     |
|           16 |     2062 | 2024-03-19 | Dynamo Eclot          | L   | 0.885      | -            | -                | -                | -         |    -3.16 | Blytz, Dytor, forsyy, kreaz, nbqq            |
|           15 |     2208 | 2024-03-15 | Viperio               | W   | 0.859      | 0.333        | 0.000 (0.000)    | 0.321 (0.092)    | 0 (0.000) |    13.05 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|           14 |     2430 | 2024-03-11 | ARCRED                | L   | 0.831      | -            | -                | -                | -         |    -8.53 | eightz, facecrack, JIaYm, Raijin, w1sely     |
|           13 |     2462 | 2024-03-10 | HyperSpirit           | W   | 0.824      | 0.333        | 0.009 (0.002)    | 0.293 (0.080)    | 0 (0.000) |    12.13 | ADRON, GEOHYPE, kritik, smekk, swiiffter     |
|           12 |     2559 | 2024-03-07 | Pingu E-Sports        | W   | 0.806      | -            | -                | -                | 0 (0.000) |     4.01 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|           11 |     2616 | 2024-03-06 | PCIFIC Espor          | W   | 0.799      | 0.333        | 0.001 (0.000)    | 0.028 (0.007)    | 0 (0.000) |     7.15 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|           10 |     2736 | 2024-03-04 | Gaimin Gladiators     | L   | 0.786      | -            | -                | -                | -         |    -0.60 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            9 |     2849 | 2024-03-02 | Preasy Esport         | L   | 0.772      | -            | -                | -                | -         |    -3.42 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            8 |     4787 | 2024-01-16 | Ex-Anonymo Esports    | L   | 0.466      | -            | -                | -                | -         |    -5.03 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            7 |     4812 | 2024-01-16 | RUSH B (Russian team) | W   | 0.465      | 0.143        | 0.006 (0.000)    | 0.471 (0.031)    | -         |     9.13 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            6 |     5470 | 2023-12-16 | INGLORIOUS            | L   | 0.258      | -            | -                | -                | -         |    -2.98 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1        |
|            5 |     5697 | 2023-12-11 | NOM Esports           | L   | 0.225      | -            | -                | -                | -         |    -3.57 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            4 |     5718 | 2023-12-10 | Team Raised           | W   | 0.218      | 0.333        | -                | 0.007 (0.001)    | -         |     1.12 | ferrariri, maaak, msle, ruddaenami, ssspring |
|            3 |     5871 | 2023-12-07 | Eternal Fire Academy  | L   | 0.199      | -            | -                | -                | -         |    -2.95 | eightz, facecrack, JIaYm, k0s, z1w0w         |
|            2 |     5967 | 2023-12-05 | Lemoncats             | W   | 0.186      | 0.333        | -                | 0.076 (0.005)    | -         |     1.26 | Ayoh, fippe, looky, mogv, simpan             |
|            1 |     6731 | 2023-11-18 | TopTab Club           | L   | 0.071      | -            | -                | -                | -         |    -1.62 | ADntZ, keembo, maQuein, rezn9, SKYLLLER      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($547.39)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
