### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, Nodios, Patti, Queenix, salazar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [39](../standings_global.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
Final Rank Value:  1131.5<br />
<br />
Final Rank Value (1131.5) = Starting Rank Value (1293.3) + Head To Head Adjustments (-161.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.491[<sup>1</sup>](#table2)
- Bounty Collected: 0.492[<sup>2</sup>](#table1)
- Opponent Network: 0.298[<sup>2</sup>](#table1)
- LAN Wins: 0.477[<sup>2</sup>](#table1)

The average of these factors is 0.440<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1293.3
- 400 + ( ( 0.440 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1293.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           87 |      144 | 2024-05-28 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -2.45 | kraghen, Nodios, Patti, Queenix, salazar      |
|           86 |      961 | 2024-05-17 | ENCE                | L   | 1.000      | -            | -                | -                | -         |    -9.19 | kraghen, Nodios, Patti, Queenix, salazar      |
|           85 |      983 | 2024-05-17 | GamerLegion         | L   | 1.000      | -            | -                | -                | -         |   -11.14 | kraghen, Nodios, Patti, Queenix, salazar      |
|           84 |     1010 | 2024-05-17 | Rebels Gaming       | L   | 1.000      | -            | -                | -                | -         |   -19.15 | kraghen, Nodios, Patti, Queenix, salazar      |
|           83 |     1187 | 2024-05-15 | BLEED Esports       | W   | 1.000      | 0.384        | 0.248 (0.095)    | 0.714 (0.274)    | 0 (0.000) |    16.37 | kraghen, Nodios, Patti, Queenix, salazar      |
|           82 |     1720 | 2024-05-07 | Grannys Knockers    | L   | 1.000      | -            | -                | -                | -         |   -26.54 | kraghen, Nodios, Patti, Queenix, salazar      |
|           81 |     1759 | 2024-05-06 | 500                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.19 | kraghen, Nodios, Patti, Queenix, salazar      |
|           80 |     1784 | 2024-05-05 | Sashi Esport        | W   | 1.000      | 0.143        | 0.154 (0.022)    | -                | 0 (0.000) |    19.93 | kraghen, Nodios, Patti, Queenix, salazar      |
|           79 |     1796 | 2024-05-05 | Kronjyllands Esport | W   | 1.000      | -            | -                | -                | -         |     0.74 | kraghen, Nodios, Patti, Queenix, salazar      |
|           78 |     1806 | 2024-05-05 | Esport Harte        | W   | 1.000      | -            | -                | -                | -         |     0.44 | kraghen, Nodios, Patti, Queenix, salazar      |
|           77 |     1909 | 2024-05-03 | AMKAL ESPORTS       | L   | 1.000      | -            | -                | -                | -         |   -14.01 | kraghen, Nodios, Patti, Queenix, salazar      |
|           76 |     1946 | 2024-05-02 | HAVU Gaming         | W   | 1.000      | -            | -                | -                | -         |     2.43 | kraghen, Nodios, Patti, Queenix, salazar      |
|           75 |     1962 | 2024-05-02 | SINNERS Esports     | W   | 1.000      | 0.435        | -                | 0.582 (0.253)    | -         |     7.65 | kraghen, Nodios, Patti, Queenix, salazar      |
|           74 |     2054 | 2024-04-30 | AMKAL ESPORTS       | L   | 1.000      | -            | -                | -                | -         |   -14.87 | kraghen, Nodios, Patti, Queenix, salazar      |
|           73 |     2115 | 2024-04-29 | kONO.ECF            | L   | 0.996      | -            | -                | -                | -         |   -25.33 | kraghen, Nodios, Patti, Queenix, salazar      |
|           72 |     2168 | 2024-04-28 | 9Pandas             | L   | 0.988      | -            | -                | -                | -         |   -21.95 | kraghen, Nodios, Patti, Queenix, salazar      |
|           71 |     2319 | 2024-04-26 | ALTERNATE aTTaX     | L   | 0.975      | -            | -                | -                | -         |   -26.37 | kraghen, Nodios, Patti, Queenix, salazar      |
|           70 |     2474 | 2024-04-23 | Sashi Esport        | L   | 0.956      | -            | -                | -                | -         |   -17.37 | kraghen, Nodios, Patti, Queenix, salazar      |
|           69 |     2514 | 2024-04-22 | BLEED Esports       | L   | 0.949      | -            | -                | -                | -         |   -16.74 | kraghen, Nodios, Patti, Queenix, salazar      |
|           68 |     2558 | 2024-04-21 | AMKAL ESPORTS       | W   | 0.943      | 0.384        | 0.146 (0.053)    | 0.565 (0.205)    | -         |    10.67 | kraghen, Nodios, Patti, Queenix, salazar      |
|           67 |     2696 | 2024-04-20 | Nemiga Gaming       | W   | 0.935      | 0.384        | 0.358 (0.129)    | 0.895 (0.322)    | -         |    11.64 | kraghen, Nodios, Patti, Queenix, salazar      |
|           66 |     2873 | 2024-04-17 | DMS                 | L   | 0.918      | -            | -                | -                | -         |   -26.70 | kraghen, Nodios, Patti, Queenix, salazar      |
|           65 |     2928 | 2024-04-17 | SINNERS Esports     | W   | 0.915      | 0.384        | -                | 0.582 (0.205)    | -         |     6.92 | kraghen, Nodios, Patti, Queenix, salazar      |
|           64 |     2985 | 2024-04-16 | Permitta Esports    | W   | 0.909      | 0.384        | -                | 1.000 (0.349)    | -         |     4.78 | kraghen, Nodios, Patti, Queenix, salazar      |
|           63 |     3605 | 2024-04-04 | JANO Esports        | W   | 0.828      | -            | -                | -                | -         |     1.25 | allu, doto, Jerppa, juho, Sm1llee             |
|           62 |     3908 | 2024-03-27 | B8                  | L   | 0.777      | -            | -                | -                | -         |   -17.00 | baz, cptkurtka023, esenthial, npl, OWNER      |
|           61 |     3949 | 2024-03-26 | Onyx Ravens         | W   | 0.771      | -            | -                | -                | -         |     0.55 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke          |
|           60 |     4102 | 2024-03-23 | G2 Esports          | L   | 0.750      | -            | -                | -                | -         |    -1.39 | HooXi, huNter-, m0NESY, nexa, NiKo            |
|           59 |     4125 | 2024-03-22 | FURIA Esports       | W   | 0.744      | 1.000        | 0.138 (0.103)    | 0.267 (0.199)    | 1 (0.744) |    15.86 | arT, chelo, FalleN, KSCERATO, yuurih          |
|           58 |     4167 | 2024-03-21 | Cloud9              | L   | 0.738      | -            | -                | -                | -         |    -5.06 | kraghen, Nodios, Patti, Queenix, salazar      |
|           57 |     4200 | 2024-03-21 | MOUZ                | L   | 0.736      | -            | -                | -                | -         |    -0.49 | kraghen, Nodios, Patti, Queenix, salazar      |
|           56 |     4273 | 2024-03-19 | Imperial Esports    | W   | 0.724      | 1.000        | 0.372 (0.269)    | 0.582 (0.421)    | 1 (0.724) |    17.46 | decenty, felps, HEN1, noway, VINI             |
|           55 |     4324 | 2024-03-18 | Lynn Vision Gaming  | W   | 0.716      | 1.000        | 0.063 (0.045)    | 0.431 (0.309)    | 1 (0.716) |     7.34 | EmiliaQAQ, Jee, Starry, westmelon, z4KR       |
|           54 |     4359 | 2024-03-17 | The MongolZ         | W   | 0.711      | 1.000        | 0.192 (0.136)    | 0.619 (0.440)    | 1 (0.711) |    19.43 | 910, bLitz, mzinho, Senzu, Techno4K           |
|           53 |     4392 | 2024-03-17 | Cloud9              | L   | 0.709      | -            | -                | -                | -         |    -4.32 | kraghen, Nodios, Patti, Queenix, salazar      |
|           52 |     5135 | 2024-03-04 | B8                  | L   | 0.625      | -            | -                | -                | -         |   -13.58 | cptkurtka023, esenthial, npl, OWNER, r1nkle   |
|           51 |     5150 | 2024-03-04 | LEON Esports        | W   | 0.625      | -            | -                | -                | -         |     1.07 | eightz, facecrack, JIaYm, k0s, z1w0w          |
|           50 |     5200 | 2024-03-04 | BetBoom Team        | L   | 0.622      | -            | -                | -                | -         |    -7.02 | kraghen, Nodios, Patti, Queenix, salazar      |
|           49 |     5210 | 2024-03-03 | ex-Preasy Esport    | L   | 0.618      | -            | -                | -                | -         |   -16.31 | kraghen, Nodios, Patti, Queenix, salazar      |
|           48 |     5221 | 2024-03-03 | Fnatic              | W   | 0.618      | -            | -                | -                | -         |     5.85 | kraghen, Nodios, Patti, Queenix, salazar      |
|           47 |     5229 | 2024-03-03 | SINNERS Esports     | W   | 0.617      | -            | -                | -                | -         |     3.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK          |
|           46 |     5259 | 2024-03-03 | Monte               | W   | 0.615      | 0.500        | 0.181 (0.056)    | -                | -         |    10.77 | kraghen, Nodios, Patti, Queenix, salazar      |
|           45 |     5274 | 2024-03-02 | JANO Esports        | W   | 0.612      | -            | -                | -                | -         |     1.23 | allu, doto, jelo, Jerppa, Sm1llee             |
|           44 |     5289 | 2024-03-02 | TEAM MAX            | W   | 0.611      | -            | -                | -                | -         |     0.30 | kL1o, Malkiss, tooizera, treckiz, zecco       |
|           43 |     5344 | 2024-03-02 | PARIVISION          | W   | 0.609      | -            | -                | -                | -         |     2.48 | kraghen, Nodios, Patti, Queenix, salazar      |
|           42 |     5827 | 2024-02-22 | ex-Guild Eagles     | W   | 0.550      | -            | -                | -                | 1 (0.550) |     3.12 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           41 |     5901 | 2024-02-21 | Apeks               | L   | 0.542      | -            | -                | -                | -         |    -8.69 | kraghen, Nodios, Patti, Queenix, salazar      |
|           40 |     5958 | 2024-02-20 | OG                  | W   | 0.536      | -            | -                | -                | 1 (0.536) |     6.75 | F1KU, HeavyGod, k1to, Nexius, regali          |
|           39 |     5995 | 2024-02-19 | MOUZ                | L   | 0.531      | -            | -                | -                | -         |    -0.31 | kraghen, Nodios, Patti, Queenix, salazar      |
|           38 |     6018 | 2024-02-19 | Monte               | W   | 0.529      | -            | -                | -                | 1 (0.529) |    10.47 | kraghen, Nodios, Patti, Queenix, salazar      |
|           37 |     6503 | 2024-02-09 | ex-Preasy Esport    | L   | 0.462      | -            | -                | -                | -         |   -12.49 | Altekz, dupreeh, refrezh, roeJ, TMB           |
|           36 |     6559 | 2024-02-07 | TSM                 | W   | 0.449      | -            | -                | -                | -         |     0.92 | joel, KWERTZZ, MoDo, valde, Zyphon            |
|           35 |     6602 | 2024-02-05 | L&G                 | W   | 0.438      | -            | -                | -                | -         |     0.23 | kraghen, Nodios, Patti, Queenix, salazar      |
|           34 |     6627 | 2024-02-05 | Nexus Gaming        | W   | 0.437      | -            | -                | -                | -         |     1.71 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           33 |     6633 | 2024-02-05 | Insilio             | W   | 0.437      | -            | -                | -                | -         |     2.03 | kraghen, Nodios, Patti, Queenix, salazar      |
|           32 |     6646 | 2024-02-05 | ex-Preasy Esport    | W   | 0.435      | -            | -                | -                | -         |     1.78 | kraghen, Nodios, Patti, Queenix, salazar      |
|           31 |     6705 | 2024-02-03 | Sashi Esport        | L   | 0.424      | -            | -                | -                | -         |   -10.07 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           30 |     6717 | 2024-02-03 | Lilmix              | W   | 0.424      | -            | -                | -                | -         |     1.23 | Brillo, dex, poiii, quix, zyyx                |
|           29 |     6727 | 2024-02-03 | Johnny Speeds       | W   | 0.424      | -            | -                | -                | -         |     3.05 | chawzyyy, L00m1, Lekr0, spooke, truth         |
|           28 |     6809 | 2024-02-02 | showmakerz          | L   | 0.417      | -            | -                | -                | -         |   -12.90 | agoz, jakoby, julle, Leon1das, majkn          |
|           27 |     6843 | 2024-02-02 | Into The Breach     | W   | 0.416      | -            | -                | -                | -         |     0.75 | Bymas, CRUC1AL, misutaaa, rallen, Thomas      |
|           26 |     6872 | 2024-02-01 | Kappa Bar           | W   | 0.411      | -            | -                | -                | -         |     0.20 | kraghen, Nodios, Patti, Queenix, salazar      |
|           25 |     6998 | 2024-01-29 | 500                 | L   | 0.392      | -            | -                | -                | -         |   -11.56 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           24 |     7036 | 2024-01-29 | lajtbitexe          | W   | 0.392      | -            | -                | -                | -         |     0.32 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko |
|           23 |     7103 | 2024-01-28 | Sangal Esports      | W   | 0.382      | 0.371        | 0.166 (0.024)    | -                | -         |     3.27 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr       |
|           22 |     7310 | 2024-01-25 | VaselineWorms       | W   | 0.364      | -            | -                | -                | -         |     0.51 | kraghen, Nodios, Patti, Queenix, salazar      |
|           21 |     7338 | 2024-01-24 | ex-KRC Genk Esports | W   | 0.358      | -            | -                | -                | -         |     0.46 | CrePoW, MAGILA, Philong, Wumbo, yOOm          |
|           20 |     7378 | 2024-01-24 | Alliance            | W   | 0.355      | -            | -                | -                | -         |     0.97 | avid, b0denmaster, PlesseN, robiin, twist     |
|           19 |     7521 | 2024-01-21 | Pera Esports        | W   | 0.336      | -            | -                | -                | -         |     1.27 | Aaron, DGL, Kamion, msN, Porya                |
|           18 |     7571 | 2024-01-20 | Fnatic              | L   | 0.331      | -            | -                | -                | -         |    -7.24 | afro, bodyy, KRIMZ, kyuubii, matys            |
|           17 |     7602 | 2024-01-20 | Permitta Esports    | W   | 0.329      | -            | -                | -                | -         |     1.49 | bnox, maaryy, mASKED, morelz, Vegi            |
|           16 |     7662 | 2024-01-19 | 9Pandas             | L   | 0.323      | -            | -                | -                | -         |    -6.53 | kraghen, Nodios, Patti, Queenix, salazar      |
|           15 |     7705 | 2024-01-18 | Nexus Gaming        | W   | 0.318      | -            | -                | -                | -         |     1.09 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           14 |     7736 | 2024-01-18 | Natus Vincere       | L   | 0.317      | -            | -                | -                | -         |    -0.38 | kraghen, Nodios, Patti, Queenix, salazar      |
|           13 |     8029 | 2024-01-13 | OG                  | W   | 0.285      | -            | -                | -                | -         |     3.42 | kraghen, Nodios, Patti, Queenix, salazar      |
|           12 |     8032 | 2024-01-13 | ex-sYnck            | W   | 0.285      | -            | -                | -                | -         |     0.44 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           11 |     8035 | 2024-01-13 | 500                 | W   | 0.284      | -            | -                | -                | -         |     0.51 | kraghen, Nodios, Patti, Queenix, salazar      |
|           10 |     8044 | 2024-01-13 | UNiTY esports       | W   | 0.283      | -            | -                | -                | -         |     1.07 | Levi, luko, M1key, NIO, Pechyn                |
|            9 |     8088 | 2024-01-12 | The Witchers        | W   | 0.278      | -            | -                | -                | -         |     0.36 | Dragon, fear, Sdaim, smooya, synyx            |
|            8 |     8107 | 2024-01-12 | fragmatic           | W   | 0.278      | -            | -                | -                | -         |     0.13 | bodik, mattloo, Pikor, shiny, tuscan4ik       |
|            7 |     8280 | 2024-01-10 | animeheroes         | L   | 0.265      | -            | -                | -                | -         |    -8.22 | Brilliance, la3euka, SasukeQO, sunshine, z1k4 |
|            6 |     8316 | 2024-01-09 | Fnatic              | L   | 0.258      | -            | -                | -                | -         |    -5.87 | kraghen, Nodios, Patti, Queenix, salazar      |
|            5 |     8330 | 2024-01-09 | brazylijski luz     | W   | 0.258      | -            | -                | -                | -         |     0.55 | kraghen, Nodios, Patti, Queenix, salazar      |
|            4 |     8350 | 2024-01-09 | Untouchabless       | W   | 0.257      | -            | -                | -                | -         |     0.06 | datyx, kjuK, Kokaina, MahaR, onStyle          |
|            3 |     8361 | 2024-01-09 | LOADING             | W   | 0.257      | -            | -                | -                | -         |     0.06 | AMANEK, devoduvek, drac, Kyojin, SIXER        |
|            2 |     9441 | 2023-12-07 | ex-Sprout           | L   | 0.037      | -            | -                | -                | -         |    -1.15 | cej0t, fNk, raalz, sL1m3, spooke              |
|            1 |     9509 | 2023-12-06 | 9Pandas             | L   | 0.030      | -            | -                | -                | -         |    -0.61 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($27,663.30)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-18 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-05-09 |      1.000 | $532.06        | $532.06         |
| 2024-05-04 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-04-22 |      0.949 | $5,000.00      | $4,745.14       |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |
| 2024-02-09 |      0.462 | $5,000.00      | $2,308.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
