### Roster Details<br />
Team Name: DMS<br />
Roster: AW, H1te, kAlash, sFade8, sm3t<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [90](../standings_global.md)<br />
Regional Rank: [63]( ../standings_europe.md)<br />
Final Rank Value:  890.4<br />
<br />
Final Rank Value (890.4) = Starting Rank Value (721.9) + Head To Head Adjustments (168.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.259[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.9
- 400 + ( ( 0.158 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 721.9


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
|           64 |      233 | 2024-05-26 | GUN5 Esports              | L   | 1.000      | -            | -                | -                | -         |   -20.50 | AW, H1te, kAlash, sFade8, sm3t              |
|           63 |      351 | 2024-05-24 | VP.Prodigy                | L   | 1.000      | -            | -                | -                | -         |   -18.15 | AW, H1te, kAlash, sFade8, sm3t              |
|           62 |      369 | 2024-05-24 | BetBoom Team              | L   | 1.000      | -            | -                | -                | -         |    -2.78 | AW, H1te, kAlash, sFade8, sm3t              |
|           61 |      414 | 2024-05-23 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -6.59 | AW, H1te, kAlash, sFade8, sm3t              |
|           60 |      467 | 2024-05-22 | Endpoint                  | L   | 1.000      | -            | -                | -                | -         |   -20.36 | AW, H1te, kAlash, sFade8, sm3t              |
|           59 |      484 | 2024-05-22 | Insilio                   | W   | 1.000      | 0.372        | -                | 0.717 (0.267)    | 0 (0.000) |    15.22 | AW, H1te, kAlash, sFade8, sm3t              |
|           58 |      588 | 2024-05-21 | EYEBALLERS                | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.508 (0.221)    | 0 (0.000) |    14.68 | AW, H1te, kAlash, sFade8, sm3t              |
|           57 |      613 | 2024-05-21 | MOUZ NXT                  | W   | 1.000      | 0.435        | 0.157 (0.068)    | 0.950 (0.413)    | 0 (0.000) |    19.09 | AW, H1te, kAlash, sFade8, sm3t              |
|           56 |      743 | 2024-05-19 | Team Space                | L   | 1.000      | -            | -                | -                | -         |   -17.57 | AW, H1te, kAlash, sFade8, sm3t              |
|           55 |      870 | 2024-05-18 | 777 Esports               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.95 | AW, H1te, kAlash, sFade8, sm3t              |
|           54 |      922 | 2024-05-18 | Team Sampi                | W   | 1.000      | 0.435        | 0.039 (0.017)    | 0.665 (0.289)    | 0 (0.000) |    19.17 | AW, H1te, kAlash, sFade8, sm3t              |
|           53 |     1013 | 2024-05-17 | MOUZ NXT                  | L   | 1.000      | -            | -                | -                | -         |   -10.22 | AW, H1te, kAlash, sFade8, sm3t              |
|           52 |     1068 | 2024-05-16 | B8                        | L   | 1.000      | -            | -                | -                | -         |    -6.99 | AW, H1te, kAlash, sFade8, sm3t              |
|           51 |     1145 | 2024-05-15 | FLuffy Gangsters          | L   | 1.000      | -            | -                | -                | -         |   -26.25 | AW, H1te, kAlash, sFade8, sm3t              |
|           50 |     1166 | 2024-05-15 | Monte                     | L   | 1.000      | -            | -                | -                | -         |    -4.75 | AW, H1te, kAlash, sFade8, sm3t              |
|           49 |     1267 | 2024-05-14 | Rare Atom                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.97 | AW, H1te, kAlash, sFade8, sm3t              |
|           48 |     1294 | 2024-05-14 | Sangal Esports            | W   | 1.000      | 0.435        | 0.166 (0.072)    | 0.577 (0.251)    | 0 (0.000) |    21.29 | AW, H1te, kAlash, sFade8, sm3t              |
|           47 |     1309 | 2024-05-13 | ENRAGE                    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.33 | AW, H1te, kAlash, sFade8, sm3t              |
|           46 |     1329 | 2024-05-13 | Heimo Esports             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.44 | AW, H1te, kAlash, sFade8, sm3t              |
|           45 |     1354 | 2024-05-12 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.86 | AW, H1te, kAlash, sFade8, sm3t              |
|           44 |     1360 | 2024-05-12 | brazylijski luz           | W   | 1.000      | -            | -                | -                | -         |    15.26 | AW, H1te, kAlash, sFade8, sm3t              |
|           43 |     1366 | 2024-05-12 | CourageG                  | W   | 1.000      | -            | -                | -                | -         |     2.33 | AW, H1te, kAlash, sFade8, sm3t              |
|           42 |     1376 | 2024-05-12 | Team Flow                 | W   | 1.000      | -            | -                | -                | -         |     4.68 | AW, H1te, kAlash, sFade8, sm3t              |
|           41 |     1449 | 2024-05-11 | CYBERSHOKE Esports        | W   | 1.000      | -            | -                | -                | -         |     8.88 | AW, H1te, kAlash, sFade8, sm3t              |
|           40 |     1534 | 2024-05-10 | Astralis Talent           | W   | 1.000      | -            | -                | -                | -         |    12.18 | AW, H1te, kAlash, sFade8, sm3t              |
|           39 |     1572 | 2024-05-09 | Viperio                   | L   | 1.000      | -            | -                | -                | -         |   -18.94 | AW, H1te, kAlash, sFade8, sm3t              |
|           38 |     1617 | 2024-05-08 | LEON Esports              | W   | 1.000      | 0.372        | -                | 0.564 (0.210)    | -         |    10.42 | AW, H1te, kAlash, sFade8, sm3t              |
|           37 |     1648 | 2024-05-08 | Astralis Talent           | W   | 1.000      | -            | -                | -                | -         |    12.04 | AW, H1te, kAlash, sFade8, sm3t              |
|           36 |     1716 | 2024-05-06 | Entropiq                  | W   | 1.000      | -            | -                | -                | -         |     8.97 | AW, H1te, kAlash, sFade8, sm3t              |
|           35 |     1972 | 2024-05-01 | RUBY                      | W   | 1.000      | 0.372        | 0.012 (0.004)    | 0.728 (0.271)    | -         |    19.88 | AW, H1te, kAlash, sFade8, sm3t              |
|           34 |     2062 | 2024-04-29 | Lilmix                    | L   | 0.997      | -            | -                | -                | -         |   -17.15 | AW, H1te, kAlash, sFade8, sm3t              |
|           33 |     2124 | 2024-04-28 | Alliance                  | L   | 0.989      | -            | -                | -                | -         |   -14.22 | AW, H1te, kAlash, sFade8, sm3t              |
|           32 |     2275 | 2024-04-26 | BLEED Esports             | L   | 0.976      | -            | -                | -                | -         |    -3.15 | AW, H1te, kAlash, sFade8, sm3t              |
|           31 |     2379 | 2024-04-24 | DASH                      | W   | 0.963      | -            | -                | -                | -         |     9.04 | AW, H1te, kAlash, sFade8, sm3t              |
|           30 |     2390 | 2024-04-24 | Permitta Esports          | L   | 0.962      | -            | -                | -                | -         |   -10.89 | AW, H1te, kAlash, sFade8, sm3t              |
|           29 |     2415 | 2024-04-23 | esmagaB                   | W   | 0.957      | 0.372        | -                | 0.460 (0.164)    | -         |    13.28 | AW, H1te, kAlash, sFade8, sm3t              |
|           28 |     2562 | 2024-04-20 | RUSH B                    | L   | 0.937      | -            | -                | -                | -         |   -16.02 | AW, H1te, kAlash, sFade8, sm3t              |
|           27 |     2752 | 2024-04-18 | Apeks                     | L   | 0.924      | -            | -                | -                | -         |    -3.28 | AW, H1te, kAlash, sFade8, sm3t              |
|           26 |     2763 | 2024-04-18 | EYEBALLERS                | W   | 0.923      | -            | -                | -                | -         |    17.63 | AW, H1te, kAlash, sFade8, sm3t              |
|           25 |     2816 | 2024-04-17 | Gaimin Gladiators         | W   | 0.918      | 0.143        | 0.092 (0.012)    | -                | -         |    26.76 | AW, H1te, kAlash, sFade8, sm3t              |
|           24 |     2868 | 2024-04-17 | HOTU                      | L   | 0.915      | -            | -                | -                | -         |   -13.77 | AW, H1te, kAlash, sFade8, sm3t              |
|           23 |     2913 | 2024-04-16 | UNiTY esports             | L   | 0.909      | -            | -                | -                | -         |   -11.92 | AW, H1te, kAlash, sFade8, sm3t              |
|           22 |     2941 | 2024-04-15 | Verdant                   | W   | 0.904      | 0.372        | 0.014 (0.005)    | 1.000 (0.337)    | -         |    16.47 | AW, H1te, kAlash, sFade8, sm3t              |
|           21 |     3084 | 2024-04-12 | Dynamo Eclot              | L   | 0.882      | -            | -                | -                | -         |    -7.79 | AW, H1te, kAlash, sFade8, sm3t              |
|           20 |     3305 | 2024-04-08 | Rhyno Esports             | W   | 0.856      | 0.333        | 0.029 (0.008)    | -                | -         |    17.93 | AW, H1te, kAlash, sFade8, sm3t              |
|           19 |     3371 | 2024-04-06 | HOTU                      | W   | 0.844      | -            | -                | -                | -         |    13.60 | AW, H1te, kAlash, sFade8, sm3t              |
|           18 |     3396 | 2024-04-06 | LEON Esports              | W   | 0.843      | -            | -                | -                | -         |    11.53 | AW, H1te, kAlash, sFade8, sm3t              |
|           17 |     3400 | 2024-04-06 | GamerLegion Academy       | W   | 0.842      | -            | -                | -                | -         |    17.11 | AW, H1te, kAlash, sFade8, sm3t              |
|           16 |     3804 | 2024-03-27 | Aurora Gaming             | L   | 0.777      | -            | -                | -                | -         |    -0.61 | AW, H1te, kAlash, sFade8, sm3t              |
|           15 |     3856 | 2024-03-26 | Permitta Esports          | W   | 0.771      | -            | -                | -                | -         |    18.14 | AW, H1te, kAlash, sFade8, sm3t              |
|           14 |     5326 | 2024-02-28 | UNiTY esports             | W   | 0.590      | 0.371        | 0.021 (0.005)    | 0.766 (0.168)    | -         |    12.40 | AW, H1te, kAlash, sFade8, sm3t              |
|           13 |     5356 | 2024-02-27 | kONO.ECF                  | L   | 0.584      | -            | -                | -                | -         |    -4.65 | AW, H1te, kAlash, sFade8, sm3t              |
|           12 |     5369 | 2024-02-27 | B8                        | W   | 0.584      | 0.143        | 0.168 (0.014)    | -                | -         |    16.54 | cptkurtka023, esenthial, npl, OWNER, r1nkle |
|           11 |     5376 | 2024-02-27 | Zero Tenacity             | L   | 0.583      | -            | -                | -                | -         |    -2.82 | AW, H1te, kAlash, sFade8, sm3t              |
|           10 |     5402 | 2024-02-26 | ex-Turów Zgorzelec Esport | W   | 0.578      | -            | -                | -                | -         |    10.88 | AW, H1te, kAlash, sFade8, sm3t              |
|            9 |     5614 | 2024-02-23 | FAVBET Team               | L   | 0.557      | -            | -                | -                | -         |    -6.72 | AW, H1te, kAlash, sFade8, sm3t              |
|            8 |     5664 | 2024-02-22 | Aurora Young Blud         | W   | 0.550      | -            | -                | -                | -         |    10.30 | AW, H1te, kAlash, sFade8, sm3t              |
|            7 |     5667 | 2024-02-22 | HOTU                      | L   | 0.549      | -            | -                | -                | -         |    -5.46 | AW, H1te, kAlash, sFade8, sm3t              |
|            6 |     5717 | 2024-02-21 | Insilio                   | W   | 0.543      | -            | -                | -                | -         |    13.51 | faydett, FpSSS, Pipw, Polt, sugaR           |
|            5 |     6215 | 2024-02-12 | CYBERSHOKE Esports        | L   | 0.483      | -            | -                | -                | -         |    -7.60 | AW, H1te, kAlash, sFade8, sm3t              |
|            4 |     6297 | 2024-02-09 | GenOne                    | L   | 0.464      | -            | -                | -                | -         |    -8.64 | AW, H1te, kAlash, sFade8, sm3t              |
|            3 |     6304 | 2024-02-09 | ex-FLuffy Gangsters       | W   | 0.463      | -            | -                | -                | -         |     3.57 | AW, H1te, kAlash, sFade8, sm3t              |
|            2 |     6357 | 2024-02-07 | L&G                       | W   | 0.451      | -            | -                | -                | -         |     3.55 | AW, H1te, kAlash, sFade8, sm3t              |
|            1 |     7548 | 2024-01-17 | Entropiq                  | L   | 0.311      | -            | -                | -                | -         |    -5.66 | AW, H1te, kAlash, sFade8, sm3t              |

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
