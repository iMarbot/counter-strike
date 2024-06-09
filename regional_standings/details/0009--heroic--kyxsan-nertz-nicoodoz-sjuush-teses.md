### Roster Details<br />
Team Name: HEROIC<br />
Roster: kyxsan, NertZ, nicoodoz, sjuush, TeSeS<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [9](../standings_global.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
Final Rank Value:  1629.7<br />
<br />
Final Rank Value (1629.7) = Starting Rank Value (1773.2) + Head To Head Adjustments (-143.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.670[<sup>1</sup>](#table2)
- Bounty Collected: 0.688[<sup>2</sup>](#table1)
- Opponent Network: 0.345[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.676<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1773.2
- 400 + ( ( 0.676 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1773.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |       34 | 2024-05-29 | BIG                | W   | 1.000      | 0.624        | 0.215 (0.134)    | -                | 1 (1.000) |     6.51 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           55 |       76 | 2024-05-29 | Natus Vincere      | W   | 1.000      | 0.624        | 1.000 (0.624)    | -                | 1 (1.000) |    24.23 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           54 |      126 | 2024-05-28 | M80                | W   | 1.000      | 0.624        | -                | 0.525 (0.327)    | 1 (1.000) |     4.66 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           53 |      158 | 2024-05-27 | Virtus.pro         | L   | 1.000      | -            | -                | -                | -         |   -14.21 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           52 |      888 | 2024-05-18 | MOUZ               | L   | 1.000      | -            | -                | -                | -         |    -3.33 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           51 |      988 | 2024-05-17 | MIBR               | W   | 1.000      | 0.769        | 0.307 (0.236)    | 0.531 (0.408)    | 1 (1.000) |    13.63 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           50 |     1095 | 2024-05-16 | Team Spirit        | L   | 1.000      | -            | -                | -                | -         |    -4.37 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           49 |     1190 | 2024-05-15 | MIBR               | W   | 1.000      | 0.769        | 0.307 (0.236)    | 0.531 (0.408)    | 1 (1.000) |    14.36 | degster, kyxsan, NertZ, sjuush, TeSeS  |
|           48 |     1842 | 2024-05-04 | Ninjas in Pyjamas  | L   | 1.000      | -            | -                | -                | -         |   -29.81 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           47 |     1899 | 2024-05-03 | BIG                | L   | 1.000      | -            | -                | -                | -         |   -26.14 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           46 |     1917 | 2024-05-03 | FlyQuest           | W   | 1.000      | 0.889        | -                | 0.466 (0.414)    | 1 (1.000) |     7.79 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           45 |     1949 | 2024-05-02 | Complexity Gaming  | L   | 1.000      | -            | -                | -                | -         |   -19.65 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           44 |     2064 | 2024-04-30 | Ninjas in Pyjamas  | W   | 1.000      | 0.889        | 0.118 (0.105)    | 0.285 (0.253)    | 1 (1.000) |     1.31 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           43 |     2882 | 2024-04-17 | brazylijski luz    | L   | 0.918      | -            | -                | -                | -         |   -28.68 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           42 |     3272 | 2024-04-10 | G2 Esports         | L   | 0.869      | -            | -                | -                | -         |    -9.87 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           41 |     3344 | 2024-04-09 | FURIA Esports      | W   | 0.862      | -            | -                | -                | 1 (0.862) |     4.60 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           40 |     3391 | 2024-04-08 | 9z Team            | W   | 0.855      | 0.624        | -                | 0.547 (0.292)    | 1 (0.855) |     2.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           39 |     3403 | 2024-04-07 | Team Liquid        | L   | 0.853      | -            | -                | -                | -         |   -16.87 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           38 |     4085 | 2024-03-23 | paiN Gaming        | L   | 0.751      | -            | -                | -                | -         |   -16.12 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           37 |     4141 | 2024-03-22 | Virtus.pro         | L   | 0.743      | -            | -                | -                | -         |   -12.49 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           36 |     4180 | 2024-03-21 | Complexity Gaming  | L   | 0.738      | -            | -                | -                | -         |   -17.53 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           35 |     4193 | 2024-03-21 | FaZe Clan          | W   | 0.737      | 1.000        | 1.000 (0.737)    | 0.457 (0.336)    | 1 (0.737) |    18.43 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           34 |     4321 | 2024-03-18 | Eternal Fire       | W   | 0.716      | 1.000        | 1.000 (0.716)    | 0.402 (0.288)    | -         |    14.78 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           33 |     4355 | 2024-03-17 | Imperial Esports   | W   | 0.711      | 1.000        | 0.372 (0.265)    | 0.582 (0.414)    | -         |     4.96 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           32 |     4382 | 2024-03-17 | Lynn Vision Gaming | W   | 0.710      | 1.000        | -                | 0.431 (0.306)    | -         |     0.77 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           31 |     4614 | 2024-03-13 | Metizport          | W   | 0.683      | -            | -                | -                | -         |     0.67 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           30 |     4669 | 2024-03-12 | Virtus.pro         | L   | 0.678      | -            | -                | -                | -         |   -11.15 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           29 |     4723 | 2024-03-11 | ENCE               | W   | 0.671      | -            | -                | -                | -         |     4.13 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           28 |     4744 | 2024-03-11 | ex-Preasy Esport   | W   | 0.670      | -            | -                | -                | -         |     0.40 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           27 |     4843 | 2024-03-09 | OG                 | L   | 0.657      | -            | -                | -                | -         |   -19.69 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           26 |     5010 | 2024-03-06 | Young Ninjas       | W   | 0.637      | -            | -                | -                | -         |     0.23 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           25 |     5817 | 2024-02-22 | GamerLegion        | W   | 0.550      | -            | -                | -                | -         |     1.11 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           24 |     5871 | 2024-02-21 | Team Spirit        | L   | 0.544      | -            | -                | -                | -         |    -4.63 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           23 |     5952 | 2024-02-20 | Astralis           | W   | 0.536      | -            | -                | -                | -         |     6.48 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           22 |     5988 | 2024-02-19 | Team Vitality      | L   | 0.531      | -            | -                | -                | -         |    -6.30 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           21 |     6012 | 2024-02-19 | ex-Preasy Esport   | W   | 0.530      | -            | -                | -                | -         |     0.19 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           20 |     6570 | 2024-02-06 | G2 Esports         | L   | 0.444      | -            | -                | -                | -         |    -6.04 | HooXi, huNter-, m0NESY, nexa, NiKo     |
|           19 |     6582 | 2024-02-06 | GamerLegion        | W   | 0.443      | -            | -                | -                | -         |     0.83 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           18 |     6636 | 2024-02-05 | Team Vitality      | W   | 0.436      | 1.000        | 0.696 (0.303)    | -                | -         |     8.65 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           17 |     6770 | 2024-02-03 | G2 Esports         | L   | 0.423      | -            | -                | -                | -         |    -5.58 | HooXi, huNter-, m0NESY, nexa, NiKo     |
|           16 |     6909 | 2024-01-31 | BIG                | W   | 0.404      | -            | -                | -                | -         |     1.81 | Krimbo, mantuu, prosus, s1n, tabseN    |
|           15 |     6941 | 2024-01-31 | Astralis           | W   | 0.403      | 1.000        | 0.395 (0.159)    | -                | -         |     5.19 | blameF, dev1ce, jabbi, Staehr, stavn   |
|           14 |     7303 | 2024-01-25 | BIG                | L   | 0.364      | -            | -                | -                | -         |    -9.99 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           13 |     7337 | 2024-01-24 | Cloud9             | L   | 0.358      | -            | -                | -                | -         |    -9.05 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           12 |     7566 | 2024-01-20 | ex-sYnck           | W   | 0.331      | -            | -                | -                | -         |     0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           11 |     7601 | 2024-01-20 | IKLA               | W   | 0.329      | -            | -                | -                | -         |     0.02 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           10 |     7655 | 2024-01-19 | KOI                | L   | 0.323      | -            | -                | -                | -         |   -10.06 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            9 |     7717 | 2024-01-18 | MOUZ               | L   | 0.317      | -            | -                | -                | -         |    -2.34 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            8 |     7727 | 2024-01-18 | FORZE Esports      | W   | 0.317      | -            | -                | -                | -         |     0.03 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            7 |     8167 | 2024-01-11 | SINNERS Esports    | W   | 0.272      | -            | -                | -                | -         |     0.14 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     8174 | 2024-01-11 | IKLA               | W   | 0.271      | -            | -                | -                | -         |     0.01 | adeX, Kvem, Lekr0, MICHU, Topa         |
|            5 |     8189 | 2024-01-11 | ex-sYnck           | W   | 0.270      | -            | -                | -                | -         |     0.03 | eku, fejtZ, Jyo, Wahtzz, xezr          |
|            4 |     8194 | 2024-01-11 | HAVU Gaming        | W   | 0.270      | -            | -                | -                | -         |     0.03 | airax, Banjo, ottoNd, sLowi, uli       |
|            3 |     8256 | 2024-01-10 | GUN5 Esports       | W   | 0.265      | -            | -                | -                | -         |     0.01 | FinigaN, lov1kus, supra, xiELO, znxxX  |
|            2 |     8284 | 2024-01-10 | Rustec             | W   | 0.264      | -            | -                | -                | -         |     0.04 | Dima, eLa1z, f0lya, KaRnez, t3NZY      |
|            1 |     8359 | 2024-01-09 | Nemiga Gaming      | L   | 0.257      | -            | -                | -                | -         |    -7.66 | 1eeR, FL4MUS, khaN, riskyb0b, Xant3r   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($96,799.41)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.32) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      0.895 | $6,000.00      | $5,370.97       |
| 2024-03-31 |      0.804 | $20,000.00     | $16,077.78      |
| 2024-03-10 |      0.665 | $7,500.00      | $4,983.85       |
| 2024-02-11 |      0.477 | $24,000.00     | $11,446.67      |
| 2024-01-28 |      0.384 | $5,000.00      | $1,920.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
