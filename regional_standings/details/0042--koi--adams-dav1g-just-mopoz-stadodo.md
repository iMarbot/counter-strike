### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [42](../standings_global.md)<br />
Regional Rank: [32]( ../standings_europe.md)<br />
Final Rank Value:  1076.4<br />
<br />
Final Rank Value (1076.4) = Starting Rank Value (1048.1) + Head To Head Adjustments (28.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.459[<sup>1</sup>](#table2)
- Bounty Collected: 0.479[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.222[<sup>2</sup>](#table1)

The average of these factors is 0.327<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1048.1
- 400 + ( ( 0.327 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1048.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |      217 | 2024-05-01 | Zero Tenacity         | L   | 1.000      | -            | -                | -                | -             |   -19.74 | adamS, dav1g, JUST, mopoz, stadodo         |
|           48 |      871 | 2024-04-18 | Guild Eagles          | L   | 1.000      | -            | -                | -                | -             |   -19.05 | adamS, dav1g, JUST, mopoz, stadodo         |
|           47 |      880 | 2024-04-18 | Fnatic                | W   | 1.000      | 0.143        | 0.334 (0.048)    | 0.683 (0.098)    | false (0.000) |    20.32 | adamS, dav1g, JUST, mopoz, stadodo         |
|           46 |     1001 | 2024-04-16 | BLEED Esports         | L   | 1.000      | -            | -                | -                | -             |   -15.64 | adamS, dav1g, JUST, mopoz, stadodo         |
|           45 |     1218 | 2024-04-10 | RUSH B (Russian team) | W   | 1.000      | 0.500        | -                | 0.471 (0.236)    | false (0.000) |     5.73 | adamS, dav1g, JUST, mopoz, stadodo         |
|           44 |     1282 | 2024-04-09 | Aurora Gaming         | W   | 1.000      | 0.500        | 1.000 (0.500)    | 0.799 (0.399)    | false (0.000) |    28.71 | adamS, dav1g, JUST, mopoz, stadodo         |
|           43 |     1291 | 2024-04-09 | Apeks                 | L   | 1.000      | -            | -                | -                | -             |    -6.70 | adamS, dav1g, JUST, mopoz, stadodo         |
|           42 |     1333 | 2024-04-08 | GUN5 Esports          | W   | 1.000      | -            | -                | -                | false (0.000) |     3.49 | adamS, dav1g, JUST, mopoz, stadodo         |
|           41 |     1335 | 2024-04-08 | Fnatic                | L   | 1.000      | -            | -                | -                | -             |   -10.72 | adamS, dav1g, JUST, mopoz, stadodo         |
|           40 |     1529 | 2024-04-03 | 9INE Academy          | W   | 0.985      | 0.500        | -                | 0.171 (0.084)    | false (0.000) |     2.70 | adamS, dav1g, JUST, mopoz, stadodo         |
|           39 |     1572 | 2024-04-02 | TSM                   | W   | 0.979      | 0.500        | -                | 0.183 (0.089)    | false (0.000) |     4.11 | adamS, dav1g, JUST, mopoz, stadodo         |
|           38 |     1698 | 2024-03-28 | EYEBALLERS            | L   | 0.944      | -            | -                | -                | -             |   -21.05 | adamS, dav1g, JUST, mopoz, stadodo         |
|           37 |     2089 | 2024-03-18 | FURIA Esports         | L   | 0.878      | -            | -                | -                | -             |    -2.07 | adamS, dav1g, JUST, mopoz, stadodo         |
|           36 |     2116 | 2024-03-17 | ENCE                  | L   | 0.873      | -            | -                | -                | -             |    -2.47 | adamS, dav1g, JUST, mopoz, stadodo         |
|           35 |     2142 | 2024-03-17 | SAW                   | L   | 0.871      | -            | -                | -                | -             |    -2.96 | adamS, dav1g, JUST, mopoz, stadodo         |
|           34 |     2403 | 2024-03-11 | B8                    | L   | 0.832      | -            | -                | -                | -             |   -17.18 | adamS, dav1g, JUST, mopoz, stadodo         |
|           33 |     2425 | 2024-03-11 | Apeks                 | L   | 0.831      | -            | -                | -                | -             |    -4.26 | adamS, dav1g, JUST, mopoz, stadodo         |
|           32 |     2604 | 2024-03-06 | 9Pandas               | W   | 0.799      | 0.500        | 0.085 (0.034)    | 0.661 (0.264)    | false (0.000) |    13.71 | adamS, dav1g, JUST, mopoz, stadodo         |
|           31 |     2672 | 2024-03-05 | FORZE Esports         | W   | 0.792      | 0.143        | 0.210 (0.024)    | 0.574 (0.065)    | -             |    12.85 | adamS, dav1g, JUST, mopoz, stadodo         |
|           30 |     2683 | 2024-03-05 | Nemiga Gaming         | W   | 0.792      | 0.143        | 0.680 (0.077)    | 0.910 (0.103)    | -             |    19.29 | adamS, dav1g, JUST, mopoz, stadodo         |
|           29 |     2737 | 2024-03-04 | ILLYRIANS             | W   | 0.786      | -            | -                | -                | -             |     3.11 | adamS, dav1g, JUST, mopoz, stadodo         |
|           28 |     2797 | 2024-03-03 | The Chosen Few        | L   | 0.778      | -            | -                | -                | -             |   -20.05 | adamS, dav1g, JUST, mopoz, stadodo         |
|           27 |     2848 | 2024-03-02 | PARIVISION            | W   | 0.772      | -            | -                | -                | -             |     5.39 | adamS, dav1g, JUST, mopoz, stadodo         |
|           26 |     2941 | 2024-02-29 | Aurora Gaming         | L   | 0.759      | -            | -                | -                | -             |    -2.08 | adamS, dav1g, JUST, mopoz, stadodo         |
|           25 |     2964 | 2024-02-29 | HAVU Gaming           | W   | 0.758      | -            | -                | -                | -             |     4.70 | adamS, dav1g, JUST, mopoz, stadodo         |
|           24 |     2982 | 2024-02-28 | FORZE Esports         | L   | 0.752      | -            | -                | -                | -             |   -12.36 | adamS, dav1g, JUST, mopoz, stadodo         |
|           23 |     3550 | 2024-02-16 | Fnatic                | W   | 0.670      | 0.143        | 0.334 (0.032)    | 0.683 (0.065)    | true (0.670)  |    14.34 | adamS, dav1g, JUST, mopoz, stadodo         |
|           22 |     3603 | 2024-02-15 | 9Pandas               | W   | 0.663      | 0.143        | 0.085 (0.008)    | 0.661 (0.063)    | true (0.663)  |    12.17 | adamS, dav1g, JUST, mopoz, stadodo         |
|           21 |     3621 | 2024-02-14 | 3DMAX                 | W   | 0.659      | -            | -                | -                | true (0.659)  |     7.57 | adamS, dav1g, JUST, mopoz, stadodo         |
|           20 |     3645 | 2024-02-14 | Natus Vincere         | L   | 0.657      | -            | -                | -                | -             |    -0.16 | adamS, dav1g, JUST, mopoz, stadodo         |
|           19 |     3994 | 2024-02-03 | SAW                   | L   | 0.584      | -            | -                | -                | -             |    -1.92 | adamS, dav1g, JUST, mopoz, stadodo         |
|           18 |     4027 | 2024-02-02 | Rhyno Esports         | W   | 0.578      | -            | -                | -                | -             |     5.22 | adamS, dav1g, JUST, mopoz, stadodo         |
|           17 |     4047 | 2024-02-02 | ABT Esports           | W   | 0.577      | -            | -                | -                | -             |     0.71 | adamS, dav1g, JUST, mopoz, stadodo         |
|           16 |     4171 | 2024-01-29 | EXO Clan              | L   | 0.553      | -            | -                | -                | -             |   -13.26 | adamS, dav1g, JUST, mopoz, stadodo         |
|           15 |     4539 | 2024-01-20 | Pera Esports          | W   | 0.492      | -            | -                | -                | -             |     4.84 | adamS, dav1g, JUST, mopoz, stadodo         |
|           14 |     4609 | 2024-01-19 | HEROIC                | W   | 0.484      | 0.143        | 0.243 (0.017)    | -                | -             |    14.84 | adamS, dav1g, JUST, mopoz, stadodo         |
|           13 |     4657 | 2024-01-18 | AMKAL ESPORTS         | L   | 0.478      | -            | -                | -                | -             |    -4.42 | adamS, dav1g, JUST, mopoz, stadodo         |
|           12 |     4671 | 2024-01-18 | Team Spirit           | W   | 0.478      | 0.143        | 1.000 (0.068)    | -                | -             |    14.86 | adamS, dav1g, JUST, mopoz, stadodo         |
|           11 |     5068 | 2024-01-09 | Entropiq              | W   | 0.420      | -            | -                | -                | -             |     2.75 | adamS, dav1g, JUST, mopoz, stadodo         |
|           10 |     5073 | 2024-01-09 | 9INE                  | W   | 0.419      | -            | -                | -                | -             |     0.93 | adamS, dav1g, JUST, mopoz, stadodo         |
|            9 |     5084 | 2024-01-09 | K10                   | W   | 0.419      | -            | -                | -                | -             |     4.06 | adamS, dav1g, JUST, mopoz, stadodo         |
|            8 |     5979 | 2023-12-05 | FORZE Esports         | L   | 0.186      | -            | -                | -                | -             |    -4.76 | adamS, bladE, dav1g, JUST, mopoz           |
|            7 |     6763 | 2023-11-17 | Apeks                 | L   | 0.066      | -            | -                | -                | -             |    -0.25 | CacaNito, jkaem, kyxsan, nawwk, sense      |
|            6 |     6781 | 2023-11-17 | Aurora Gaming         | W   | 0.064      | 0.143        | 1.000 (0.009)    | -                | -             |     1.95 | adamS, dav1g, JUST, Martinez, mopoz        |
|            5 |     6788 | 2023-11-17 | BetBoom Team          | L   | 0.063      | -            | -                | -                | -             |    -0.16 | danistzz, KaiR0N-, nafany, s1ren, zorte    |
|            4 |     6806 | 2023-11-16 | Team Space            | W   | 0.059      | -            | -                | -                | -             |     0.28 | enzero, fozil, leri511, TruNiQ, Vert       |
|            3 |     6844 | 2023-11-16 | MIBR                  | L   | 0.056      | -            | -                | -                | -             |    -0.06 | brnz4n, drop, exit, insani, saffee         |
|            2 |     6997 | 2023-11-12 | SAW                   | W   | 0.032      | -            | -                | -                | -             |     0.93 | aragornN, arrozdoce, ewjerkz, rmn, story   |
|            1 |     7179 | 2023-11-08 | The Prodigies         | W   | 0.005      | -            | -                | -                | -             |     0.01 | consss, jEROMEE, krii, NaToSaphiX, P4TriCK |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,526.57)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.965 | $10,000.00     | $9,652.31       |
| 2023-12-10 |      0.219 | $4,000.00      | $874.26         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
