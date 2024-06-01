### Roster Details<br />
Team Name: Gaimin Gladiators<br />
Roster: kraghen, Nodios, Patti, Queenix, salazar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [39](../standings_global.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
Final Rank Value:  1128.2<br />
<br />
Final Rank Value (1128.2) = Starting Rank Value (1291.6) + Head To Head Adjustments (-163.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.491[<sup>1</sup>](#table2)
- Bounty Collected: 0.493[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.477[<sup>2</sup>](#table1)

The average of these factors is 0.438<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1291.6
- 400 + ( ( 0.438 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1291.6


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
|           85 |      137 | 2024-05-28 | The MongolZ         | L   | 1.000      | -            | -                | -                | -         |    -2.42 | kraghen, Nodios, Patti, Queenix, salazar      |
|           84 |      949 | 2024-05-17 | ENCE                | L   | 1.000      | -            | -                | -                | -         |    -9.13 | kraghen, Nodios, Patti, Queenix, salazar      |
|           83 |      971 | 2024-05-17 | GamerLegion         | L   | 1.000      | -            | -                | -                | -         |   -10.94 | kraghen, Nodios, Patti, Queenix, salazar      |
|           82 |      998 | 2024-05-17 | Rebels Gaming       | L   | 1.000      | -            | -                | -                | -         |   -19.32 | kraghen, Nodios, Patti, Queenix, salazar      |
|           81 |     1177 | 2024-05-15 | BLEED Esports       | W   | 1.000      | 0.384        | 0.248 (0.095)    | 0.677 (0.260)    | 0 (0.000) |    16.58 | kraghen, Nodios, Patti, Queenix, salazar      |
|           80 |     1700 | 2024-05-07 | Grannys Knockers    | L   | 1.000      | -            | -                | -                | -         |   -26.80 | kraghen, Nodios, Patti, Queenix, salazar      |
|           79 |     1736 | 2024-05-06 | 500                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.16 | kraghen, Nodios, Patti, Queenix, salazar      |
|           78 |     1761 | 2024-05-05 | Sashi Esport        | W   | 1.000      | 0.143        | 0.172 (0.025)    | -                | 0 (0.000) |    20.08 | kraghen, Nodios, Patti, Queenix, salazar      |
|           77 |     1773 | 2024-05-05 | Kronjyllands Esport | W   | 1.000      | -            | -                | -                | -         |     0.76 | kraghen, Nodios, Patti, Queenix, salazar      |
|           76 |     1783 | 2024-05-05 | Esport Harte        | W   | 1.000      | -            | -                | -                | -         |     0.45 | kraghen, Nodios, Patti, Queenix, salazar      |
|           75 |     1884 | 2024-05-03 | AMKAL ESPORTS       | L   | 1.000      | -            | -                | -                | -         |   -13.91 | kraghen, Nodios, Patti, Queenix, salazar      |
|           74 |     1919 | 2024-05-02 | HAVU Gaming         | W   | 1.000      | -            | -                | -                | -         |     2.47 | kraghen, Nodios, Patti, Queenix, salazar      |
|           73 |     1935 | 2024-05-02 | SINNERS Esports     | W   | 1.000      | 0.435        | -                | 0.560 (0.243)    | -         |     7.50 | kraghen, Nodios, Patti, Queenix, salazar      |
|           72 |     2023 | 2024-04-30 | AMKAL ESPORTS       | L   | 1.000      | -            | -                | -                | -         |   -14.77 | kraghen, Nodios, Patti, Queenix, salazar      |
|           71 |     2080 | 2024-04-29 | kONO.ECF            | L   | 0.996      | -            | -                | -                | -         |   -25.42 | kraghen, Nodios, Patti, Queenix, salazar      |
|           70 |     2133 | 2024-04-28 | 9Pandas             | L   | 0.988      | -            | -                | -                | -         |   -22.27 | kraghen, Nodios, Patti, Queenix, salazar      |
|           69 |     2282 | 2024-04-26 | ALTERNATE aTTaX     | L   | 0.975      | -            | -                | -                | -         |   -26.27 | kraghen, Nodios, Patti, Queenix, salazar      |
|           68 |     2426 | 2024-04-23 | Sashi Esport        | L   | 0.956      | -            | -                | -                | -         |   -17.14 | kraghen, Nodios, Patti, Queenix, salazar      |
|           67 |     2462 | 2024-04-22 | BLEED Esports       | L   | 0.949      | -            | -                | -                | -         |   -16.40 | kraghen, Nodios, Patti, Queenix, salazar      |
|           66 |     2505 | 2024-04-21 | AMKAL ESPORTS       | W   | 0.943      | 0.384        | 0.146 (0.053)    | 0.565 (0.205)    | -         |    10.79 | kraghen, Nodios, Patti, Queenix, salazar      |
|           65 |     2642 | 2024-04-20 | Nemiga Gaming       | W   | 0.935      | 0.384        | 0.366 (0.131)    | 0.830 (0.298)    | -         |    11.91 | kraghen, Nodios, Patti, Queenix, salazar      |
|           64 |     2816 | 2024-04-17 | DMS                 | L   | 0.918      | -            | -                | -                | -         |   -26.76 | kraghen, Nodios, Patti, Queenix, salazar      |
|           63 |     2871 | 2024-04-17 | SINNERS Esports     | W   | 0.915      | 0.384        | -                | 0.560 (0.197)    | -         |     6.11 | kraghen, Nodios, Patti, Queenix, salazar      |
|           62 |     2924 | 2024-04-16 | Permitta Esports    | W   | 0.909      | 0.384        | -                | 1.000 (0.349)    | -         |     4.61 | kraghen, Nodios, Patti, Queenix, salazar      |
|           61 |     3815 | 2024-03-27 | B8                  | L   | 0.777      | -            | -                | -                | -         |   -16.77 | baz, cptkurtka023, esenthial, npl, OWNER      |
|           60 |     3852 | 2024-03-26 | Onyx Ravens         | W   | 0.771      | -            | -                | -                | -         |     0.56 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke          |
|           59 |     4005 | 2024-03-23 | G2 Esports          | L   | 0.750      | -            | -                | -                | -         |    -1.37 | HooXi, huNter-, m0NESY, nexa, NiKo            |
|           58 |     4027 | 2024-03-22 | FURIA Esports       | W   | 0.744      | 1.000        | 0.138 (0.103)    | 0.267 (0.199)    | 1 (0.744) |    15.93 | arT, chelo, FalleN, KSCERATO, yuurih          |
|           57 |     4069 | 2024-03-21 | Cloud9              | L   | 0.738      | -            | -                | -                | -         |    -5.01 | kraghen, Nodios, Patti, Queenix, salazar      |
|           56 |     4100 | 2024-03-21 | MOUZ                | L   | 0.736      | -            | -                | -                | -         |    -0.47 | kraghen, Nodios, Patti, Queenix, salazar      |
|           55 |     4170 | 2024-03-19 | Imperial Esports    | W   | 0.724      | 1.000        | 0.372 (0.269)    | 0.582 (0.421)    | 1 (0.724) |    17.53 | decenty, felps, HEN1, noway, VINI             |
|           54 |     4219 | 2024-03-18 | Lynn Vision Gaming  | W   | 0.716      | 1.000        | 0.063 (0.045)    | 0.414 (0.296)    | 1 (0.716) |     7.39 | EmiliaQAQ, Jee, Starry, westmelon, z4KR       |
|           53 |     4254 | 2024-03-17 | The MongolZ         | W   | 0.711      | 1.000        | 0.192 (0.136)    | 0.619 (0.440)    | 1 (0.711) |    19.49 | 910, bLitz, mzinho, Senzu, Techno4K           |
|           52 |     4286 | 2024-03-17 | Cloud9              | L   | 0.709      | -            | -                | -                | -         |    -4.27 | kraghen, Nodios, Patti, Queenix, salazar      |
|           51 |     4989 | 2024-03-04 | B8                  | L   | 0.625      | -            | -                | -                | -         |   -13.55 | cptkurtka023, esenthial, npl, OWNER, r1nkle   |
|           50 |     5004 | 2024-03-04 | LEON Esports        | W   | 0.625      | -            | -                | -                | -         |     1.07 | eightz, facecrack, JIaYm, k0s, z1w0w          |
|           49 |     5054 | 2024-03-04 | BetBoom Team        | L   | 0.622      | -            | -                | -                | -         |    -7.02 | kraghen, Nodios, Patti, Queenix, salazar      |
|           48 |     5064 | 2024-03-03 | ex-Preasy Esport    | L   | 0.618      | -            | -                | -                | -         |   -16.34 | kraghen, Nodios, Patti, Queenix, salazar      |
|           47 |     5075 | 2024-03-03 | Fnatic              | W   | 0.618      | -            | -                | -                | -         |     5.87 | kraghen, Nodios, Patti, Queenix, salazar      |
|           46 |     5083 | 2024-03-03 | SINNERS Esports     | W   | 0.617      | -            | -                | -                | -         |     3.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK          |
|           45 |     5111 | 2024-03-03 | Monte               | W   | 0.615      | 0.500        | 0.181 (0.056)    | -                | -         |    10.73 | kraghen, Nodios, Patti, Queenix, salazar      |
|           44 |     5126 | 2024-03-02 | JANO Esports        | W   | 0.612      | -            | -                | -                | -         |     1.20 | allu, doto, jelo, Jerppa, Sm1llee             |
|           43 |     5141 | 2024-03-02 | TEAM MAX            | W   | 0.611      | -            | -                | -                | -         |     0.30 | kL1o, Malkiss, tooizera, treckiz, zecco       |
|           42 |     5196 | 2024-03-02 | PARIVISION          | W   | 0.609      | -            | -                | -                | -         |     2.50 | kraghen, Nodios, Patti, Queenix, salazar      |
|           41 |     5666 | 2024-02-22 | ex-Guild Eagles     | W   | 0.550      | -            | -                | -                | 1 (0.550) |     3.05 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy   |
|           40 |     5735 | 2024-02-21 | Apeks               | L   | 0.542      | -            | -                | -                | -         |    -8.57 | kraghen, Nodios, Patti, Queenix, salazar      |
|           39 |     5788 | 2024-02-20 | OG                  | W   | 0.536      | -            | -                | -                | 1 (0.536) |     6.83 | F1KU, HeavyGod, k1to, Nexius, regali          |
|           38 |     5824 | 2024-02-19 | MOUZ                | L   | 0.531      | -            | -                | -                | -         |    -0.30 | kraghen, Nodios, Patti, Queenix, salazar      |
|           37 |     5846 | 2024-02-19 | Monte               | W   | 0.529      | -            | -                | -                | 1 (0.529) |    10.43 | kraghen, Nodios, Patti, Queenix, salazar      |
|           36 |     6315 | 2024-02-09 | ex-Preasy Esport    | L   | 0.462      | -            | -                | -                | -         |   -12.51 | Altekz, dupreeh, refrezh, roeJ, TMB           |
|           35 |     6365 | 2024-02-07 | TSM                 | W   | 0.449      | -            | -                | -                | -         |     0.84 | joel, KWERTZZ, MoDo, valde, Zyphon            |
|           34 |     6404 | 2024-02-05 | L&G                 | W   | 0.438      | -            | -                | -                | -         |     0.23 | kraghen, Nodios, Patti, Queenix, salazar      |
|           33 |     6427 | 2024-02-05 | Nexus Gaming        | W   | 0.437      | -            | -                | -                | -         |     1.78 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           32 |     6433 | 2024-02-05 | Insilio             | W   | 0.437      | -            | -                | -                | -         |     2.11 | kraghen, Nodios, Patti, Queenix, salazar      |
|           31 |     6444 | 2024-02-05 | ex-Preasy Esport    | W   | 0.435      | -            | -                | -                | -         |     1.77 | kraghen, Nodios, Patti, Queenix, salazar      |
|           30 |     6502 | 2024-02-03 | Sashi Esport        | L   | 0.424      | -            | -                | -                | -         |    -9.95 | Cabbi, IceBerg, kwezz, Lucky, MistR           |
|           29 |     6514 | 2024-02-03 | Lilmix              | W   | 0.424      | -            | -                | -                | -         |     1.34 | Brillo, dex, poiii, quix, zyyx                |
|           28 |     6524 | 2024-02-03 | Johnny Speeds       | W   | 0.424      | -            | -                | -                | -         |     3.05 | chawzyyy, L00m1, Lekr0, spooke, truth         |
|           27 |     6606 | 2024-02-02 | showmakerz          | L   | 0.417      | -            | -                | -                | -         |   -12.91 | agoz, jakoby, julle, Leon1das, majkn          |
|           26 |     6638 | 2024-02-02 | Into The Breach     | W   | 0.416      | -            | -                | -                | -         |     0.75 | Bymas, CRUC1AL, misutaaa, rallen, Thomas      |
|           25 |     6666 | 2024-02-01 | Kappa Bar           | W   | 0.411      | -            | -                | -                | -         |     0.20 | kraghen, Nodios, Patti, Queenix, salazar      |
|           24 |     6782 | 2024-01-29 | 500                 | L   | 0.392      | -            | -                | -                | -         |   -11.55 | dennyslaw, Patrick, Rainwaker, REDSTAR, SHiPZ |
|           23 |     6820 | 2024-01-29 | lajtbitexe          | W   | 0.392      | -            | -                | -                | -         |     0.29 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko |
|           22 |     6885 | 2024-01-28 | Sangal Esports      | W   | 0.382      | 0.371        | 0.166 (0.024)    | -                | -         |     3.03 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr       |
|           21 |     7108 | 2024-01-24 | ex-KRC Genk Esports | W   | 0.358      | -            | -                | -                | -         |     0.33 | CrePoW, MAGILA, Philong, Wumbo, yOOm          |
|           20 |     7143 | 2024-01-24 | Alliance            | W   | 0.355      | -            | -                | -                | -         |     0.97 | avid, b0denmaster, PlesseN, robiin, twist     |
|           19 |     7278 | 2024-01-21 | Pera Esports        | W   | 0.336      | -            | -                | -                | -         |     1.32 | Aaron, DGL, Kamion, msN, Porya                |
|           18 |     7327 | 2024-01-20 | Fnatic              | L   | 0.331      | -            | -                | -                | -         |    -7.23 | afro, bodyy, KRIMZ, kyuubii, matys            |
|           17 |     7358 | 2024-01-20 | Permitta Esports    | W   | 0.329      | -            | -                | -                | -         |     1.46 | bnox, maaryy, mASKED, morelz, Vegi            |
|           16 |     7416 | 2024-01-19 | 9Pandas             | L   | 0.323      | -            | -                | -                | -         |    -6.66 | kraghen, Nodios, Patti, Queenix, salazar      |
|           15 |     7457 | 2024-01-18 | Nexus Gaming        | W   | 0.318      | -            | -                | -                | -         |     1.19 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           14 |     7487 | 2024-01-18 | Natus Vincere       | L   | 0.317      | -            | -                | -                | -         |    -0.38 | kraghen, Nodios, Patti, Queenix, salazar      |
|           13 |     7776 | 2024-01-13 | OG                  | W   | 0.285      | -            | -                | -                | -         |     3.45 | kraghen, Nodios, Patti, Queenix, salazar      |
|           12 |     7779 | 2024-01-13 | ex-sYnck            | W   | 0.285      | -            | -                | -                | -         |     0.37 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           11 |     7782 | 2024-01-13 | 500                 | W   | 0.284      | -            | -                | -                | -         |     0.51 | kraghen, Nodios, Patti, Queenix, salazar      |
|           10 |     7791 | 2024-01-13 | UNiTY esports       | W   | 0.283      | -            | -                | -                | -         |     1.08 | Levi, luko, M1key, NIO, Pechyn                |
|            9 |     7835 | 2024-01-12 | The Witchers        | W   | 0.278      | -            | -                | -                | -         |     0.36 | Dragon, fear, Sdaim, smooya, synyx            |
|            8 |     7854 | 2024-01-12 | fragmatic           | W   | 0.278      | -            | -                | -                | -         |     0.13 | bodik, mattloo, Pikor, shiny, tuscan4ik       |
|            7 |     8026 | 2024-01-10 | animeheroes         | L   | 0.265      | -            | -                | -                | -         |    -8.22 | Brilliance, la3euka, SasukeQO, sunshine, z1k4 |
|            6 |     8062 | 2024-01-09 | Fnatic              | L   | 0.258      | -            | -                | -                | -         |    -5.86 | kraghen, Nodios, Patti, Queenix, salazar      |
|            5 |     8076 | 2024-01-09 | brazylijski luz     | W   | 0.258      | -            | -                | -                | -         |     0.54 | kraghen, Nodios, Patti, Queenix, salazar      |
|            4 |     8096 | 2024-01-09 | Untouchabless       | W   | 0.257      | -            | -                | -                | -         |     0.06 | datyx, kjuK, Kokaina, MahaR, onStyle          |
|            3 |     8107 | 2024-01-09 | LOADING             | W   | 0.257      | -            | -                | -                | -         |     0.09 | AMANEK, devoduvek, drac, Kyojin, SIXER        |
|            2 |     9168 | 2023-12-07 | ex-Sprout           | L   | 0.037      | -            | -                | -                | -         |    -1.15 | cej0t, fNk, raalz, sL1m3, spooke              |
|            1 |     9228 | 2023-12-06 | 9Pandas             | L   | 0.030      | -            | -                | -                | -         |    -0.63 | clax, d1Ledez, glowiing, iDISBALANCE, seized  |

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
