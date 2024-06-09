### Roster Details<br />
Team Name: DMS<br />
Roster: AW, H1te, kAlash, sFade8, sm3t<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [79](../standings_global.md)<br />
Regional Rank: [55]( ../standings_europe.md)<br />
Final Rank Value:  913.5<br />
<br />
Final Rank Value (913.5) = Starting Rank Value (736.7) + Head To Head Adjustments (176.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.289[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.166<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.7
- 400 + ( ( 0.166 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 736.7


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
|           65 |       63 | 2024-05-29 | Verdant                   | W   | 1.000      | 0.372        | 0.014 (0.005)    | 1.000 (0.372)    | 0 (0.000) |    16.45 | AW, H1te, kAlash, sFade8, sm3t              |
|           64 |      241 | 2024-05-26 | GUN5 Esports              | L   | 1.000      | -            | -                | -                | -         |   -19.99 | AW, H1te, kAlash, sFade8, sm3t              |
|           63 |      360 | 2024-05-24 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -17.52 | AW, H1te, kAlash, sFade8, sm3t              |
|           62 |      378 | 2024-05-24 | BetBoom Team              | L   | 1.000      | -            | -                | -                | -         |    -2.87 | AW, H1te, kAlash, sFade8, sm3t              |
|           61 |      422 | 2024-05-23 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -6.88 | AW, H1te, kAlash, sFade8, sm3t              |
|           60 |      473 | 2024-05-22 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -20.06 | AW, H1te, kAlash, sFade8, sm3t              |
|           59 |      490 | 2024-05-22 | Insilio                   | W   | 1.000      | 0.372        | -                | 0.717 (0.267)    | 0 (0.000) |    15.03 | AW, H1te, kAlash, sFade8, sm3t              |
|           58 |      599 | 2024-05-21 | EYEBALLERS                | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.508 (0.221)    | 0 (0.000) |    14.14 | AW, H1te, kAlash, sFade8, sm3t              |
|           57 |      624 | 2024-05-21 | MOUZ NXT                  | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.977 (0.424)    | 0 (0.000) |    19.18 | AW, H1te, kAlash, sFade8, sm3t              |
|           56 |      755 | 2024-05-19 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -17.77 | AW, H1te, kAlash, sFade8, sm3t              |
|           55 |      882 | 2024-05-18 | 777 Esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.81 | AW, H1te, kAlash, sFade8, sm3t              |
|           54 |      934 | 2024-05-18 | Team Sampi                | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.677 (0.294)    | 0 (0.000) |    19.00 | AW, H1te, kAlash, sFade8, sm3t              |
|           53 |     1025 | 2024-05-17 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -10.15 | AW, H1te, kAlash, sFade8, sm3t              |
|           52 |     1078 | 2024-05-16 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -7.40 | AW, H1te, kAlash, sFade8, sm3t              |
|           51 |     1154 | 2024-05-15 | FLuffy Gangsters          | L   | 1.000      | -            | -                | -                | -         |   -25.68 | AW, H1te, kAlash, sFade8, sm3t              |
|           50 |     1176 | 2024-05-15 | Monte                     | L   | 1.000      | -            | -                | -                | -         |    -4.75 | AW, H1te, kAlash, sFade8, sm3t              |
|           49 |     1278 | 2024-05-14 | Rare Atom                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.71 | AW, H1te, kAlash, sFade8, sm3t              |
|           48 |     1305 | 2024-05-14 | Sangal Esports            | W   | 1.000      | 0.435        | 0.166 (0.072)    | 0.658 (0.286)    | 0 (0.000) |    22.00 | AW, H1te, kAlash, sFade8, sm3t              |
|           47 |     1320 | 2024-05-13 | ENRAGE                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.83 | AW, H1te, kAlash, sFade8, sm3t              |
|           46 |     1341 | 2024-05-13 | Heimo Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.25 | AW, H1te, kAlash, sFade8, sm3t              |
|           45 |     1366 | 2024-05-12 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     8.76 | AW, H1te, kAlash, sFade8, sm3t              |
|           44 |     1373 | 2024-05-12 | brazylijski luz           | W   | 1.000      | -            | -                | -                | -         |    15.18 | AW, H1te, kAlash, sFade8, sm3t              |
|           43 |     1379 | 2024-05-12 | CourageG                  | W   | 1.000      | -            | -                | -                | -         |     2.25 | AW, H1te, kAlash, sFade8, sm3t              |
|           42 |     1389 | 2024-05-12 | Team Flow                 | W   | 1.000      | -            | -                | -                | -         |     4.54 | AW, H1te, kAlash, sFade8, sm3t              |
|           41 |     1462 | 2024-05-11 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     8.78 | AW, H1te, kAlash, sFade8, sm3t              |
|           40 |     1549 | 2024-05-10 | Astralis Talent           | W   | 1.000      | -            | -                | -                | -         |    12.07 | AW, H1te, kAlash, sFade8, sm3t              |
|           39 |     1588 | 2024-05-09 | Viperio                   | L   | 1.000      | -            | -                | -                | -         |   -19.16 | AW, H1te, kAlash, sFade8, sm3t              |
|           38 |     1632 | 2024-05-08 | LEON Esports              | W   | 1.000      | 0.372        | -                | 0.564 (0.210)    | -         |    10.35 | AW, H1te, kAlash, sFade8, sm3t              |
|           37 |     1666 | 2024-05-08 | Astralis Talent           | W   | 1.000      | -            | -                | -                | -         |    11.91 | AW, H1te, kAlash, sFade8, sm3t              |
|           36 |     1738 | 2024-05-06 | Entropiq                  | W   | 1.000      | -            | -                | -                | -         |     8.80 | AW, H1te, kAlash, sFade8, sm3t              |
|           35 |     1999 | 2024-05-01 | RUBY                      | W   | 1.000      | 0.372        | -                | 0.738 (0.275)    | -         |    19.66 | AW, H1te, kAlash, sFade8, sm3t              |
|           34 |     2096 | 2024-04-29 | Lilmix                    | L   | 0.997      | -            | -                | -                | -         |   -17.21 | AW, H1te, kAlash, sFade8, sm3t              |
|           33 |     2159 | 2024-04-28 | Alliance                  | L   | 0.989      | -            | -                | -                | -         |   -14.60 | AW, H1te, kAlash, sFade8, sm3t              |
|           32 |     2312 | 2024-04-26 | BLEED Esports             | L   | 0.976      | -            | -                | -                | -         |    -3.33 | AW, H1te, kAlash, sFade8, sm3t              |
|           31 |     2423 | 2024-04-24 | DASH                      | W   | 0.963      | -            | -                | -                | -         |     9.16 | AW, H1te, kAlash, sFade8, sm3t              |
|           30 |     2435 | 2024-04-24 | Permitta Esports          | L   | 0.962      | -            | -                | -                | -         |   -10.51 | AW, H1te, kAlash, sFade8, sm3t              |
|           29 |     2463 | 2024-04-23 | esmagaB                   | W   | 0.957      | 0.372        | -                | 0.564 (0.201)    | -         |    13.55 | AW, H1te, kAlash, sFade8, sm3t              |
|           28 |     2615 | 2024-04-20 | RUSH B                    | L   | 0.937      | -            | -                | -                | -         |   -15.95 | AW, H1te, kAlash, sFade8, sm3t              |
|           27 |     2808 | 2024-04-18 | Apeks                     | L   | 0.924      | -            | -                | -                | -         |    -3.46 | AW, H1te, kAlash, sFade8, sm3t              |
|           26 |     2819 | 2024-04-18 | EYEBALLERS                | W   | 0.923      | -            | -                | -                | -         |    16.51 | AW, H1te, kAlash, sFade8, sm3t              |
|           25 |     2873 | 2024-04-17 | Gaimin Gladiators         | W   | 0.918      | 0.143        | 0.092 (0.012)    | -                | -         |    26.70 | AW, H1te, kAlash, sFade8, sm3t              |
|           24 |     2925 | 2024-04-17 | HOTU                      | L   | 0.915      | -            | -                | -                | -         |   -13.82 | AW, H1te, kAlash, sFade8, sm3t              |
|           23 |     2974 | 2024-04-16 | UNiTY esports             | L   | 0.909      | -            | -                | -                | -         |   -12.49 | AW, H1te, kAlash, sFade8, sm3t              |
|           22 |     3002 | 2024-04-15 | Verdant                   | W   | 0.904      | 0.372        | 0.014 (0.005)    | 1.000 (0.337)    | -         |    16.60 | AW, H1te, kAlash, sFade8, sm3t              |
|           21 |     3150 | 2024-04-12 | Dynamo Eclot              | L   | 0.882      | -            | -                | -                | -         |    -8.14 | AW, H1te, kAlash, sFade8, sm3t              |
|           20 |     3386 | 2024-04-08 | Rhyno Esports             | W   | 0.856      | 0.333        | 0.029 (0.008)    | -                | -         |    17.81 | AW, H1te, kAlash, sFade8, sm3t              |
|           19 |     3454 | 2024-04-06 | HOTU                      | W   | 0.844      | -            | -                | -                | -         |    13.54 | AW, H1te, kAlash, sFade8, sm3t              |
|           18 |     3479 | 2024-04-06 | LEON Esports              | W   | 0.843      | -            | -                | -                | -         |    11.22 | AW, H1te, kAlash, sFade8, sm3t              |
|           17 |     3483 | 2024-04-06 | GamerLegion Academy       | W   | 0.842      | -            | -                | -                | -         |    16.67 | AW, H1te, kAlash, sFade8, sm3t              |
|           16 |     3897 | 2024-03-27 | Aurora Gaming             | L   | 0.777      | -            | -                | -                | -         |    -0.70 | AW, H1te, kAlash, sFade8, sm3t              |
|           15 |     3953 | 2024-03-26 | Permitta Esports          | W   | 0.771      | -            | -                | -                | -         |    18.17 | AW, H1te, kAlash, sFade8, sm3t              |
|           14 |     5477 | 2024-02-28 | UNiTY esports             | W   | 0.590      | 0.371        | 0.021 (0.005)    | -                | -         |    12.05 | AW, H1te, kAlash, sFade8, sm3t              |
|           13 |     5509 | 2024-02-27 | kONO.ECF                  | L   | 0.584      | -            | -                | -                | -         |    -4.43 | AW, H1te, kAlash, sFade8, sm3t              |
|           12 |     5522 | 2024-02-27 | B8                        | W   | 0.584      | 0.143        | 0.168 (0.014)    | -                | -         |    16.44 | cptkurtka023, esenthial, npl, OWNER, r1nkle |
|           11 |     5529 | 2024-02-27 | Zero Tenacity             | L   | 0.583      | -            | -                | -                | -         |    -3.19 | AW, H1te, kAlash, sFade8, sm3t              |
|           10 |     5559 | 2024-02-26 | ex-Turów Zgorzelec Esport | W   | 0.578      | -            | -                | -                | -         |    11.03 | AW, H1te, kAlash, sFade8, sm3t              |
|            9 |     5774 | 2024-02-23 | FAVBET Team               | L   | 0.557      | -            | -                | -                | -         |    -6.90 | AW, H1te, kAlash, sFade8, sm3t              |
|            8 |     5825 | 2024-02-22 | Aurora Young Blud         | W   | 0.550      | -            | -                | -                | -         |    10.13 | AW, H1te, kAlash, sFade8, sm3t              |
|            7 |     5828 | 2024-02-22 | HOTU                      | L   | 0.549      | -            | -                | -                | -         |    -5.52 | AW, H1te, kAlash, sFade8, sm3t              |
|            6 |     5880 | 2024-02-21 | Insilio                   | W   | 0.543      | -            | -                | -                | -         |    13.28 | faydett, FpSSS, Pipw, Polt, sugaR           |
|            5 |     6403 | 2024-02-12 | CYBERSHOKE Esports        | L   | 0.483      | -            | -                | -                | -         |   -10.41 | AW, H1te, kAlash, sFade8, sm3t              |
|            4 |     6485 | 2024-02-09 | GenOne                    | L   | 0.464      | -            | -                | -                | -         |    -8.88 | AW, H1te, kAlash, sFade8, sm3t              |
|            3 |     6492 | 2024-02-09 | FLuffy Gangsters          | W   | 0.463      | -            | -                | -                | -         |     4.45 | AW, H1te, kAlash, sFade8, sm3t              |
|            2 |     6550 | 2024-02-07 | L&G                       | W   | 0.451      | -            | -                | -                | -         |     3.44 | AW, H1te, kAlash, sFade8, sm3t              |
|            1 |     7797 | 2024-01-17 | Entropiq                  | L   | 0.311      | -            | -                | -                | -         |    -5.84 | AW, H1te, kAlash, sFade8, sm3t              |

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
