### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [57](../standings_global.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
Final Rank Value:  1025.7<br />
<br />
Final Rank Value (1025.7) = Starting Rank Value (964.9) + Head To Head Adjustments (60.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.134[<sup>2</sup>](#table1)
- LAN Wins: 0.160[<sup>2</sup>](#table1)

The average of these factors is 0.278<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 964.9
- 400 + ( ( 0.278 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 964.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           55 |     1597 | 2024-05-09 | B8                 | L   | 1.000      | -            | -                | -                | -         |   -13.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           54 |     2030 | 2024-05-01 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |   -17.09 | adamS, dav1g, JUST, mopoz, stadodo |
|           53 |     2809 | 2024-04-18 | ex-Guild Eagles    | L   | 0.924      | -            | -                | -                | -         |   -17.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           52 |     2821 | 2024-04-18 | Fnatic             | W   | 0.923      | 0.143        | 0.147 (0.019)    | 0.480 (0.063)    | 0 (0.000) |    17.69 | adamS, dav1g, JUST, mopoz, stadodo |
|           51 |     2865 | 2024-04-17 | UNiTY esports      | W   | 0.918      | 0.143        | -                | 0.766 (0.100)    | 0 (0.000) |     8.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           50 |     2966 | 2024-04-16 | BLEED Esports      | L   | 0.910      | -            | -                | -                | -         |    -8.87 | adamS, dav1g, JUST, mopoz, stadodo |
|           49 |     3242 | 2024-04-10 | RUSH B             | W   | 0.871      | 0.500        | -                | 0.446 (0.194)    | 0 (0.000) |     6.26 | adamS, dav1g, JUST, mopoz, stadodo |
|           48 |     3315 | 2024-04-09 | Aurora Gaming      | W   | 0.864      | 0.500        | 0.492 (0.213)    | 0.573 (0.248)    | 0 (0.000) |    23.99 | adamS, dav1g, JUST, mopoz, stadodo |
|           47 |     3327 | 2024-04-09 | Apeks              | L   | 0.863      | -            | -                | -                | -         |    -7.28 | adamS, dav1g, JUST, mopoz, stadodo |
|           46 |     3375 | 2024-04-08 | GUN5 Esports       | W   | 0.857      | -            | -                | -                | 0 (0.000) |     3.12 | adamS, dav1g, JUST, mopoz, stadodo |
|           45 |     3377 | 2024-04-08 | Fnatic             | L   | 0.856      | -            | -                | -                | -         |    -9.92 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |     3634 | 2024-04-03 | 9INE               | W   | 0.824      | -            | -                | -                | 0 (0.000) |     2.73 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |     3681 | 2024-04-02 | TSM                | W   | 0.817      | 0.500        | -                | 0.170 (0.069)    | 0 (0.000) |     5.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |     3839 | 2024-03-28 | EYEBALLERS         | L   | 0.783      | -            | -                | -                | -         |   -16.63 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     4311 | 2024-03-18 | FURIA Esports      | L   | 0.717      | -            | -                | -                | -         |    -2.79 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     4340 | 2024-03-17 | ENCE               | L   | 0.712      | -            | -                | -                | -         |    -2.36 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     4380 | 2024-03-17 | SAW                | L   | 0.710      | -            | -                | -                | -         |    -3.00 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     4593 | 2024-03-13 | Sangal Esports     | W   | 0.684      | 0.500        | 0.166 (0.057)    | 0.658 (0.225)    | -         |     8.94 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     4718 | 2024-03-11 | B8                 | L   | 0.671      | -            | -                | -                | -         |    -8.64 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     4743 | 2024-03-11 | Apeks              | L   | 0.670      | -            | -                | -                | -         |    -5.19 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     4984 | 2024-03-06 | 9Pandas            | W   | 0.638      | 0.500        | 0.110 (0.035)    | 0.710 (0.226)    | -         |    13.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     5072 | 2024-03-05 | FORZE Esports      | W   | 0.631      | 0.143        | 0.101 (0.009)    | -                | -         |    10.17 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     5086 | 2024-03-05 | Nemiga Gaming      | W   | 0.631      | 0.143        | 0.358 (0.032)    | 0.895 (0.081)    | -         |    15.20 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     5101 | 2024-03-05 | ex-Sprout          | W   | 0.631      | -            | -                | -                | -         |     2.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     5139 | 2024-03-04 | ghoulsW            | W   | 0.625      | -            | -                | -                | -         |     0.97 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     5151 | 2024-03-04 | ILLYRIANS          | W   | 0.625      | -            | -                | -                | -         |     3.41 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     5230 | 2024-03-03 | The Chosen Few     | L   | 0.617      | -            | -                | -                | -         |   -15.39 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     5266 | 2024-03-02 | BLEED Esports      | W   | 0.612      | 0.143        | 0.248 (0.022)    | 0.714 (0.062)    | -         |    14.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     5294 | 2024-03-02 | PARIVISION         | W   | 0.611      | -            | -                | -                | -         |     6.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     5409 | 2024-02-29 | Aurora Gaming      | L   | 0.598      | -            | -                | -                | -         |    -1.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     5434 | 2024-02-29 | HAVU Gaming        | W   | 0.597      | -            | -                | -                | -         |     3.66 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     5461 | 2024-02-28 | FORZE Esports      | L   | 0.591      | -            | -                | -                | -         |    -9.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     5478 | 2024-02-28 | kONO.ECF           | W   | 0.590      | 0.143        | -                | 0.853 (0.072)    | -         |     7.91 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     6179 | 2024-02-16 | Fnatic             | W   | 0.509      | 0.143        | 0.147 (0.011)    | -                | 1 (0.509) |    10.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     6244 | 2024-02-15 | 9Pandas            | W   | 0.502      | -            | -                | -                | 1 (0.502) |    11.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     6273 | 2024-02-14 | 3DMAX              | W   | 0.497      | -            | -                | -                | 1 (0.497) |     7.20 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     6299 | 2024-02-14 | Natus Vincere      | L   | 0.496      | -            | -                | -                | -         |    -0.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     6765 | 2024-02-03 | SAW                | L   | 0.423      | -            | -                | -                | -         |    -1.46 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     6810 | 2024-02-02 | Rhyno Esports      | W   | 0.417      | -            | -                | -                | -         |     7.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     6838 | 2024-02-02 | ABT Esports        | W   | 0.416      | -            | -                | -                | -         |     0.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     7014 | 2024-01-29 | EXO Clan           | L   | 0.392      | -            | -                | -                | -         |    -5.98 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     7564 | 2024-01-20 | Pera Esports       | W   | 0.331      | -            | -                | -                | -         |     4.42 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     7588 | 2024-01-20 | ENTERPRISE esports | L   | 0.330      | -            | -                | -                | -         |    -5.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     7655 | 2024-01-19 | HEROIC             | W   | 0.323      | 0.143        | 0.322 (0.015)    | -                | -         |    10.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     7719 | 2024-01-18 | AMKAL ESPORTS      | L   | 0.317      | -            | -                | -                | -         |    -2.13 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     7732 | 2024-01-18 | Team Spirit        | W   | 0.317      | 0.143        | 1.000 (0.045)    | -                | -         |     9.92 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     7776 | 2024-01-17 | ex-sYnck           | L   | 0.312      | -            | -                | -                | -         |    -7.55 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     7795 | 2024-01-17 | ILLYRIANS          | W   | 0.311      | -            | -                | -                | -         |     2.13 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     8304 | 2024-01-09 | ENTERPRISE esports | L   | 0.259      | -            | -                | -                | -         |    -4.06 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     8307 | 2024-01-09 | Entropiq           | W   | 0.259      | -            | -                | -                | -         |     1.26 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     8315 | 2024-01-09 | 9INE               | W   | 0.258      | -            | -                | -                | -         |     0.76 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     8333 | 2024-01-09 | ex-K10             | W   | 0.258      | -            | -                | -                | -         |     3.08 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     8354 | 2024-01-09 | Betera Esports     | W   | 0.257      | -            | -                | -                | -         |     2.46 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     8383 | 2024-01-09 | premghouls         | W   | 0.257      | -            | -                | -                | -         |     0.33 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     9565 | 2023-12-05 | FORZE Esports      | L   | 0.024      | -            | -                | -                | -         |    -0.65 | adamS, bladE, dav1g, JUST, mopoz   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,268.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |
| 2023-12-10 |      0.058 | $4,000.00      | $230.00         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
