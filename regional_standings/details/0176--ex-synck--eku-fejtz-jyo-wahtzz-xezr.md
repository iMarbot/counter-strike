### Roster Details<br />
Team Name: ex-sYnck<br />
Roster: eku, fejtZ, Jyo, Wahtzz, xezr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [176](../standings_global.md)<br />
Regional Rank: [121]( ../standings_europe.md)<br />
Final Rank Value:  750.9<br />
<br />
Final Rank Value (750.9) = Starting Rank Value (699.1) + Head To Head Adjustments (51.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.164[<sup>1</sup>](#table2)
- Bounty Collected: 0.276[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.1
- 400 + ( ( 0.147 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 699.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |     4384 | 2024-03-15 | Endpoint           | L   | 0.696      | -            | -                | -                | -         |    -6.18 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           39 |     4446 | 2024-03-14 | Young Ninjas       | W   | 0.689      | 0.384        | 0.043 (0.011)    | 0.372 (0.098)    | 0 (0.000) |    16.41 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           38 |     5212 | 2024-03-02 | INGLORIOUS         | W   | 0.609      | 0.384        | 0.001 (0.000)    | 0.214 (0.050)    | 0 (0.000) |    11.02 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           37 |     5268 | 2024-02-29 | AURA               | L   | 0.597      | -            | -                | -                | -         |   -11.50 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           36 |     5287 | 2024-02-29 | Team Secret        | W   | 0.596      | 0.371        | -                | 0.230 (0.051)    | 0 (0.000) |     7.66 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           35 |     5568 | 2024-02-24 | ENCE Academy       | L   | 0.562      | -            | -                | -                | -         |    -6.66 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           34 |     5618 | 2024-02-23 | RoundsGG           | W   | 0.556      | 0.143        | -                | 0.202 (0.016)    | 1 (0.556) |     5.95 | Kollo, LYNXi, m0n0xx, p12, Welho              |
|           33 |     5640 | 2024-02-22 | ENCE Prospects     | W   | 0.551      | 0.143        | 0.001 (0.000)    | -                | 1 (0.551) |     7.25 | foqu, hattivati, Keksimage, Matz, Pasisaurus  |
|           32 |     6518 | 2024-02-03 | UNiTY esports      | L   | 0.424      | -            | -                | -                | -         |    -3.59 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           31 |     6537 | 2024-02-03 | L&G                | W   | 0.424      | -            | -                | -                | 0 (0.000) |     3.25 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           30 |     6550 | 2024-02-03 | EP Genesis         | W   | 0.423      | 0.143        | -                | 0.208 (0.013)    | 0 (0.000) |     3.27 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee    |
|           29 |     6609 | 2024-02-02 | Dynamo Eclot       | L   | 0.417      | -            | -                | -                | -         |    -1.58 | Blytz, Dytor, forsyy, kreaz, nbqq             |
|           28 |     6631 | 2024-02-02 | Infinite Gaming    | W   | 0.417      | -            | -                | -                | 0 (0.000) |     3.01 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           27 |     7264 | 2024-01-21 | 3DMAX              | L   | 0.338      | -            | -                | -                | -         |    -2.41 | Djoko, Ex3rcice, hAdji, Lucky, Maka           |
|           26 |     7271 | 2024-01-21 | Pera Esports       | L   | 0.337      | -            | -                | -                | -         |    -2.68 | Aaron, DGL, Kamion, msN, Porya                |
|           25 |     7279 | 2024-01-21 | Nexus Gaming       | L   | 0.336      | -            | -                | -                | -         |    -2.52 | BTN, ERSIN, ragga, s0und, XELLOW              |
|           24 |     7323 | 2024-01-20 | HEROIC             | L   | 0.331      | -            | -                | -                | -         |    -0.03 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS        |
|           23 |     7355 | 2024-01-20 | Entropiq           | W   | 0.329      | 0.143        | -                | 0.241 (0.011)    | 0 (0.000) |     4.39 | c0llins, Marix, mwlky, Oxygen, tiziaN         |
|           22 |     7412 | 2024-01-19 | ENTERPRISE esports | L   | 0.323      | -            | -                | -                | -         |    -2.14 | bajmi, Demho, Ex1st, fr3nd, TOAO              |
|           21 |     7462 | 2024-01-18 | FORZE Esports      | W   | 0.318      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     4.66 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           20 |     7485 | 2024-01-18 | AMKAL ESPORTS      | L   | 0.317      | -            | -                | -                | -         |    -0.64 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           19 |     7515 | 2024-01-17 | FreeESPI           | L   | 0.312      | -            | -                | -                | -         |    -6.47 | MAGILA, maty, slokker, spardaus, tAk          |
|           18 |     7527 | 2024-01-17 | KOI                | W   | 0.312      | 0.143        | 0.027 (0.001)    | 0.430 (0.019)    | -         |     7.79 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           17 |     7547 | 2024-01-17 | brazylijski luz    | W   | 0.311      | 0.143        | 0.013 (0.001)    | 0.490 (0.022)    | -         |     6.22 | Furlan, phr, POLO, Prism, Qlocuu              |
|           16 |     7777 | 2024-01-13 | Permitta Esports   | L   | 0.285      | -            | -                | -                | -         |    -1.89 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           15 |     7779 | 2024-01-13 | Gaimin Gladiators  | L   | 0.285      | -            | -                | -                | -         |    -0.37 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           14 |     7785 | 2024-01-13 | Betera Esports     | W   | 0.284      | 0.143        | 0.023 (0.001)    | -                | -         |     5.83 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           13 |     7793 | 2024-01-13 | LOADING            | W   | 0.283      | -            | -                | -                | -         |     2.06 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           12 |     7795 | 2024-01-13 | 00 Nation          | W   | 0.283      | -            | -                | -                | -         |     2.05 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|           11 |     7841 | 2024-01-12 | Sissi State Punks  | W   | 0.278      | 0.143        | 0.004 (0.000)    | -                | -         |     3.98 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy      |
|           10 |     7936 | 2024-01-11 | HEROIC             | L   | 0.270      | -            | -                | -                | -         |    -0.02 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|            9 |     7942 | 2024-01-11 | animeheroes        | W   | 0.270      | -            | -                | -                | -         |     2.31 | Brilliance, la3euka, SasukeQO, sunshine, z1k4 |
|            8 |     7997 | 2024-01-10 | XI Esport          | W   | 0.265      | 0.143        | -                | 0.277 (0.010)    | -         |     3.99 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|            7 |     8028 | 2024-01-10 | Sangal Esports     | W   | 0.265      | 0.143        | 0.166 (0.006)    | 0.577 (0.022)    | -         |     7.50 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr       |
|            6 |     8122 | 2024-01-09 | IKLA               | L   | 0.257      | -            | -                | -                | -         |    -5.54 | adeX, Kvem, Lekr0, MICHU, Topa                |
|            5 |     8598 | 2023-12-16 | GUN5 Esports       | L   | 0.097      | -            | -                | -                | -         |    -2.24 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|            4 |     9179 | 2023-12-07 | Endpoint           | L   | 0.036      | -            | -                | -                | -         |    -0.23 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|            3 |     9241 | 2023-12-06 | ALTERNATE aTTaX    | L   | 0.029      | -            | -                | -                | -         |    -0.43 | eku, fejtZ, Jyo, Wahtzz, xezr                 |
|            2 |     9346 | 2023-12-04 | paiN Gaming        | W   | 0.015      | 0.371        | 0.463 (0.003)    | -                | -         |     0.47 | biguzera, kauez, lux, n1ssim, nqz             |
|            1 |     9489 | 2023-12-02 | FreeESPI           | L   | 0.003      | -            | -                | -                | -         |    -0.06 | fierre, maty, spardaus, tAk, tooizera         |

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
