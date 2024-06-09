### Roster Details<br />
Team Name: ex-sYnck<br />
Roster: eku, fejtZ, Jyo, Wahtzz, xezr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [165](../standings_global.md)<br />
Regional Rank: [115]( ../standings_europe.md)<br />
Final Rank Value:  766.9<br />
<br />
Final Rank Value (766.9) = Starting Rank Value (732.3) + Head To Head Adjustments (34.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.164[<sup>1</sup>](#table2)
- Bounty Collected: 0.302[<sup>2</sup>](#table1)
- Opponent Network: 0.071[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 732.3
- 400 + ( ( 0.164 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 732.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           51 |     4493 | 2024-03-15 | Endpoint           | L   | 0.696      | -            | -                | -                | -         |    -6.61 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           50 |     4560 | 2024-03-14 | Young Ninjas       | W   | 0.689      | 0.384        | 0.043 (0.011)    | 0.372 (0.098)    | 0 (0.000) |    16.02 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           49 |     4953 | 2024-03-07 | Sashi Esport       | L   | 0.643      | -            | -                | -                | -         |    -3.54 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           48 |     5361 | 2024-03-02 | INGLORIOUS         | W   | 0.609      | 0.384        | -                | 0.223 (0.052)    | 0 (0.000) |    10.59 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           47 |     5418 | 2024-02-29 | AURA               | L   | 0.597      | -            | -                | -                | -         |   -11.93 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           46 |     5437 | 2024-02-29 | Team Secret        | W   | 0.596      | 0.371        | -                | 0.230 (0.051)    | 0 (0.000) |     7.18 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           45 |     5539 | 2024-02-27 | Dynamo Eclot       | L   | 0.582      | -            | -                | -                | -         |    -2.41 | Blytz, Dytor, forsyy, kreaz, nbqq              |
|           44 |     5728 | 2024-02-24 | ENCE Academy       | L   | 0.562      | -            | -                | -                | -         |    -7.21 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           43 |     5778 | 2024-02-23 | RoundsGG           | W   | 0.556      | -            | -                | -                | 1 (0.556) |     5.90 | Kollo, LYNXi, m0n0xx, p12, Welho               |
|           42 |     5800 | 2024-02-22 | ENCE Prospects     | W   | 0.551      | -            | -                | -                | 1 (0.551) |     6.66 | foqu, hattivati, Keksimage, Matz, Pasisaurus   |
|           41 |     6006 | 2024-02-19 | ILIN               | L   | 0.530      | -            | -                | -                | -         |   -12.43 | abiraju, aviva, bogemtdarf, fineshine, lampada |
|           40 |     6334 | 2024-02-13 | Lilmix             | W   | 0.491      | 0.371        | 0.006 (0.001)    | 0.593 (0.108)    | 0 (0.000) |     9.36 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           39 |     6380 | 2024-02-12 | kONO.ECF           | W   | 0.484      | 0.371        | 0.013 (0.002)    | 0.853 (0.154)    | 0 (0.000) |    11.20 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           38 |     6399 | 2024-02-12 | Permitta Esports   | L   | 0.484      | -            | -                | -                | -         |    -3.58 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           37 |     6542 | 2024-02-07 | lajtbitexe         | L   | 0.451      | -            | -                | -                | -         |    -9.51 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           36 |     6552 | 2024-02-07 | VP.Prodigy         | L   | 0.451      | -            | -                | -                | -         |    -4.99 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           35 |     6721 | 2024-02-03 | UNiTY esports      | L   | 0.424      | -            | -                | -                | -         |    -4.13 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           34 |     6740 | 2024-02-03 | L&G                | W   | 0.424      | -            | -                | -                | 0 (0.000) |     2.86 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           33 |     6753 | 2024-02-03 | EP Genesis         | W   | 0.423      | -            | -                | -                | 0 (0.000) |     2.80 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee     |
|           32 |     6813 | 2024-02-02 | Dynamo Eclot       | L   | 0.417      | -            | -                | -                | -         |    -1.86 | Blytz, Dytor, forsyy, kreaz, nbqq              |
|           31 |     6836 | 2024-02-02 | Infinite Gaming    | W   | 0.417      | -            | -                | -                | 0 (0.000) |     2.56 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           30 |     6876 | 2024-02-01 | Zero Tenacity      | W   | 0.411      | 0.371        | 0.147 (0.022)    | 1.000 (0.152)    | -         |    10.94 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           29 |     6914 | 2024-01-31 | BAKS Esports       | W   | 0.404      | 0.371        | -                | 0.171 (0.026)    | -         |     4.41 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           28 |     7415 | 2024-01-23 | INGLORIOUS         | L   | 0.351      | -            | -                | -                | -         |    -5.68 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           27 |     7507 | 2024-01-21 | 3DMAX              | L   | 0.338      | -            | -                | -                | -         |    -2.71 | Djoko, Ex3rcice, hAdji, Lucky, Maka            |
|           26 |     7514 | 2024-01-21 | Pera Esports       | L   | 0.337      | -            | -                | -                | -         |    -3.06 | Aaron, DGL, Kamion, msN, Porya                 |
|           25 |     7522 | 2024-01-21 | Nexus Gaming       | L   | 0.336      | -            | -                | -                | -         |    -3.02 | BTN, ERSIN, ragga, s0und, XELLOW               |
|           24 |     7566 | 2024-01-20 | HEROIC             | L   | 0.331      | -            | -                | -                | -         |    -0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS         |
|           23 |     7599 | 2024-01-20 | Entropiq           | W   | 0.329      | -            | -                | -                | -         |     4.00 | c0llins, Marix, mwlky, Oxygen, tiziaN          |
|           22 |     7658 | 2024-01-19 | ENTERPRISE esports | L   | 0.323      | -            | -                | -                | -         |    -2.26 | bajmi, Demho, Ex1st, fr3nd, TOAO               |
|           21 |     7710 | 2024-01-18 | FORZE Esports      | W   | 0.318      | 0.143        | 0.010 (0.000)    | -                | -         |     4.79 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           20 |     7734 | 2024-01-18 | AMKAL ESPORTS      | L   | 0.317      | -            | -                | -                | -         |    -0.74 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           19 |     7764 | 2024-01-17 | FreeESPI           | L   | 0.312      | -            | -                | -                | -         |    -6.83 | MAGILA, maty, slokker, spardaus, tAk           |
|           18 |     7776 | 2024-01-17 | KOI                | W   | 0.312      | 0.143        | 0.027 (0.001)    | 0.455 (0.020)    | -         |     7.55 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           17 |     7796 | 2024-01-17 | brazylijski luz    | W   | 0.311      | 0.143        | 0.013 (0.001)    | 0.514 (0.023)    | -         |     5.89 | Furlan, phr, POLO, Prism, Qlocuu               |
|           16 |     8030 | 2024-01-13 | Permitta Esports   | L   | 0.285      | -            | -                | -                | -         |    -2.09 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           15 |     8032 | 2024-01-13 | Gaimin Gladiators  | L   | 0.285      | -            | -                | -                | -         |    -0.44 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           14 |     8038 | 2024-01-13 | Betera Esports     | W   | 0.284      | 0.143        | 0.023 (0.001)    | -                | -         |     5.49 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           13 |     8046 | 2024-01-13 | LOADING            | W   | 0.283      | -            | -                | -                | -         |     1.22 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           12 |     8048 | 2024-01-13 | 00 Nation          | W   | 0.283      | -            | -                | -                | -         |     1.78 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           11 |     8094 | 2024-01-12 | Sissi State Punks  | W   | 0.278      | -            | -                | -                | -         |     3.58 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy       |
|           10 |     8189 | 2024-01-11 | HEROIC             | L   | 0.270      | -            | -                | -                | -         |    -0.03 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|            9 |     8195 | 2024-01-11 | animeheroes        | W   | 0.270      | -            | -                | -                | -         |     2.02 | Brilliance, la3euka, SasukeQO, sunshine, z1k4  |
|            8 |     8251 | 2024-01-10 | XI Esport          | W   | 0.265      | -            | -                | -                | -         |     3.62 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|            7 |     8282 | 2024-01-10 | Sangal Esports     | W   | 0.265      | 0.143        | 0.166 (0.006)    | 0.658 (0.025)    | -         |     7.45 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr        |
|            6 |     8376 | 2024-01-09 | IKLA               | L   | 0.257      | -            | -                | -                | -         |    -5.88 | adeX, Kvem, Lekr0, MICHU, Topa                 |
|            5 |     8859 | 2023-12-16 | GUN5 Esports       | L   | 0.097      | -            | -                | -                | -         |    -2.34 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|            4 |     9452 | 2023-12-07 | Endpoint           | L   | 0.036      | -            | -                | -                | -         |    -0.26 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|            3 |     9522 | 2023-12-06 | ALTERNATE aTTaX    | L   | 0.029      | -            | -                | -                | -         |    -0.14 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|            2 |     9628 | 2023-12-04 | paiN Gaming        | W   | 0.015      | 0.371        | 0.463 (0.003)    | -                | -         |     0.47 | biguzera, kauez, lux, n1ssim, nqz              |
|            1 |     9771 | 2023-12-02 | FreeESPI           | L   | 0.003      | -            | -                | -                | -         |    -0.07 | fierre, maty, spardaus, tAk, tooizera          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2.34)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
