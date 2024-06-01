### Roster Details<br />
Team Name: KOI<br />
Roster: adamS, dav1g, JUST, mopoz, stadodo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [58](../standings_global.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
Final Rank Value:  1015.8<br />
<br />
Final Rank Value (1015.8) = Starting Rank Value (960.6) + Head To Head Adjustments (55.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.428[<sup>2</sup>](#table1)
- Opponent Network: 0.124[<sup>2</sup>](#table1)
- LAN Wins: 0.160[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 960.6
- 400 + ( ( 0.275 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 960.6


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
|           54 |     1581 | 2024-05-09 | B8                 | L   | 1.000      | -            | -                | -                | -         |   -12.68 | adamS, dav1g, JUST, mopoz, stadodo |
|           53 |     1999 | 2024-05-01 | Zero Tenacity      | L   | 1.000      | -            | -                | -                | -         |   -16.80 | adamS, dav1g, JUST, mopoz, stadodo |
|           52 |     2753 | 2024-04-18 | ex-Guild Eagles    | L   | 0.924      | -            | -                | -                | -         |   -17.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           51 |     2765 | 2024-04-18 | Fnatic             | W   | 0.923      | 0.143        | 0.147 (0.019)    | 0.480 (0.063)    | 0 (0.000) |    18.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           50 |     2906 | 2024-04-16 | BLEED Esports      | L   | 0.910      | -            | -                | -                | -         |    -8.57 | adamS, dav1g, JUST, mopoz, stadodo |
|           49 |     3169 | 2024-04-10 | RUSH B             | W   | 0.871      | 0.500        | -                | 0.446 (0.194)    | 0 (0.000) |     6.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           48 |     3236 | 2024-04-09 | Aurora Gaming      | W   | 0.864      | 0.500        | 0.492 (0.213)    | 0.616 (0.266)    | 0 (0.000) |    24.51 | adamS, dav1g, JUST, mopoz, stadodo |
|           47 |     3248 | 2024-04-09 | Apeks              | L   | 0.863      | -            | -                | -                | -         |    -7.10 | adamS, dav1g, JUST, mopoz, stadodo |
|           46 |     3294 | 2024-04-08 | GUN5 Esports       | W   | 0.857      | -            | -                | -                | 0 (0.000) |     3.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           45 |     3296 | 2024-04-08 | Fnatic             | L   | 0.856      | -            | -                | -                | -         |    -9.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           44 |     3547 | 2024-04-03 | 9INE               | W   | 0.824      | -            | -                | -                | 0 (0.000) |     2.78 | adamS, dav1g, JUST, mopoz, stadodo |
|           43 |     3592 | 2024-04-02 | TSM                | W   | 0.817      | 0.500        | -                | 0.146 (0.060)    | 0 (0.000) |     4.83 | adamS, dav1g, JUST, mopoz, stadodo |
|           42 |     3746 | 2024-03-28 | EYEBALLERS         | L   | 0.783      | -            | -                | -                | -         |   -16.55 | adamS, dav1g, JUST, mopoz, stadodo |
|           41 |     4206 | 2024-03-18 | FURIA Esports      | L   | 0.717      | -            | -                | -                | -         |    -2.73 | adamS, dav1g, JUST, mopoz, stadodo |
|           40 |     4235 | 2024-03-17 | ENCE               | L   | 0.712      | -            | -                | -                | -         |    -2.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           39 |     4275 | 2024-03-17 | SAW                | L   | 0.710      | -            | -                | -                | -         |    -2.95 | adamS, dav1g, JUST, mopoz, stadodo |
|           38 |     4479 | 2024-03-13 | Sangal Esports     | W   | 0.684      | 0.500        | 0.166 (0.057)    | 0.577 (0.197)    | 0 (0.000) |     8.53 | adamS, dav1g, JUST, mopoz, stadodo |
|           37 |     4596 | 2024-03-11 | B8                 | L   | 0.671      | -            | -                | -                | -         |    -8.59 | adamS, dav1g, JUST, mopoz, stadodo |
|           36 |     4621 | 2024-03-11 | Apeks              | L   | 0.670      | -            | -                | -                | -         |    -5.06 | adamS, dav1g, JUST, mopoz, stadodo |
|           35 |     4853 | 2024-03-06 | 9Pandas            | W   | 0.638      | 0.500        | 0.110 (0.035)    | 0.660 (0.210)    | -         |    13.34 | adamS, dav1g, JUST, mopoz, stadodo |
|           34 |     4933 | 2024-03-05 | FORZE Esports      | W   | 0.631      | 0.143        | 0.111 (0.010)    | -                | -         |    10.54 | adamS, dav1g, JUST, mopoz, stadodo |
|           33 |     4946 | 2024-03-05 | Nemiga Gaming      | W   | 0.631      | 0.143        | 0.366 (0.033)    | 0.830 (0.075)    | -         |    15.40 | adamS, dav1g, JUST, mopoz, stadodo |
|           32 |     4958 | 2024-03-05 | ex-Sprout          | W   | 0.631      | -            | -                | -                | -         |     2.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           31 |     4993 | 2024-03-04 | ghoulsW            | W   | 0.625      | -            | -                | -                | -         |     0.99 | adamS, dav1g, JUST, mopoz, stadodo |
|           30 |     5005 | 2024-03-04 | ILLYRIANS          | W   | 0.625      | -            | -                | -                | -         |     3.44 | adamS, dav1g, JUST, mopoz, stadodo |
|           29 |     5084 | 2024-03-03 | The Chosen Few     | L   | 0.617      | -            | -                | -                | -         |   -15.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           28 |     5118 | 2024-03-02 | BLEED Esports      | W   | 0.612      | 0.143        | 0.248 (0.022)    | 0.677 (0.059)    | -         |    14.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           27 |     5146 | 2024-03-02 | PARIVISION         | W   | 0.611      | -            | -                | -                | -         |     7.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           26 |     5260 | 2024-02-29 | Aurora Gaming      | L   | 0.598      | -            | -                | -                | -         |    -1.67 | adamS, dav1g, JUST, mopoz, stadodo |
|           25 |     5284 | 2024-02-29 | HAVU Gaming        | W   | 0.597      | -            | -                | -                | -         |     3.73 | adamS, dav1g, JUST, mopoz, stadodo |
|           24 |     5310 | 2024-02-28 | FORZE Esports      | L   | 0.591      | -            | -                | -                | -         |    -8.90 | adamS, dav1g, JUST, mopoz, stadodo |
|           23 |     5327 | 2024-02-28 | kONO.ECF           | W   | 0.590      | 0.143        | -                | 0.778 (0.066)    | -         |     7.47 | adamS, dav1g, JUST, mopoz, stadodo |
|           22 |     6003 | 2024-02-16 | Fnatic             | W   | 0.509      | 0.143        | 0.147 (0.011)    | -                | 1 (0.509) |    10.86 | adamS, dav1g, JUST, mopoz, stadodo |
|           21 |     6063 | 2024-02-15 | 9Pandas            | W   | 0.502      | 0.143        | -                | 0.660 (0.047)    | 1 (0.502) |    11.76 | adamS, dav1g, JUST, mopoz, stadodo |
|           20 |     6092 | 2024-02-14 | 3DMAX              | W   | 0.497      | -            | -                | -                | 1 (0.497) |     7.27 | adamS, dav1g, JUST, mopoz, stadodo |
|           19 |     6118 | 2024-02-14 | Natus Vincere      | L   | 0.496      | -            | -                | -                | -         |    -0.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           18 |     6562 | 2024-02-03 | SAW                | L   | 0.423      | -            | -                | -                | -         |    -1.43 | adamS, dav1g, JUST, mopoz, stadodo |
|           17 |     6607 | 2024-02-02 | Rhyno Esports      | W   | 0.417      | -            | -                | -                | -         |     7.35 | adamS, dav1g, JUST, mopoz, stadodo |
|           16 |     6633 | 2024-02-02 | ABT Esports        | W   | 0.416      | -            | -                | -                | -         |     0.85 | adamS, dav1g, JUST, mopoz, stadodo |
|           15 |     6798 | 2024-01-29 | EXO Clan           | L   | 0.392      | -            | -                | -                | -         |    -6.08 | adamS, dav1g, JUST, mopoz, stadodo |
|           14 |     7321 | 2024-01-20 | Pera Esports       | W   | 0.331      | -            | -                | -                | -         |     4.56 | adamS, dav1g, JUST, mopoz, stadodo |
|           13 |     7344 | 2024-01-20 | ENTERPRISE esports | L   | 0.330      | -            | -                | -                | -         |    -5.31 | adamS, dav1g, JUST, mopoz, stadodo |
|           12 |     7409 | 2024-01-19 | HEROIC             | W   | 0.323      | 0.143        | 0.322 (0.015)    | -                | -         |    10.07 | adamS, dav1g, JUST, mopoz, stadodo |
|           11 |     7471 | 2024-01-18 | AMKAL ESPORTS      | L   | 0.317      | -            | -                | -                | -         |    -2.11 | adamS, dav1g, JUST, mopoz, stadodo |
|           10 |     7483 | 2024-01-18 | Team Spirit        | W   | 0.317      | 0.143        | 1.000 (0.045)    | -                | -         |     9.93 | adamS, dav1g, JUST, mopoz, stadodo |
|            9 |     7527 | 2024-01-17 | ex-sYnck           | L   | 0.312      | -            | -                | -                | -         |    -7.79 | adamS, dav1g, JUST, mopoz, stadodo |
|            8 |     7546 | 2024-01-17 | ILLYRIANS          | W   | 0.311      | -            | -                | -                | -         |     2.16 | adamS, dav1g, JUST, mopoz, stadodo |
|            7 |     8050 | 2024-01-09 | ENTERPRISE esports | L   | 0.259      | -            | -                | -                | -         |    -4.21 | adamS, dav1g, JUST, mopoz, stadodo |
|            6 |     8053 | 2024-01-09 | Entropiq           | W   | 0.259      | -            | -                | -                | -         |     1.28 | adamS, dav1g, JUST, mopoz, stadodo |
|            5 |     8061 | 2024-01-09 | 9INE               | W   | 0.258      | -            | -                | -                | -         |     0.77 | adamS, dav1g, JUST, mopoz, stadodo |
|            4 |     8079 | 2024-01-09 | ex-K10             | W   | 0.258      | -            | -                | -                | -         |     2.92 | adamS, dav1g, JUST, mopoz, stadodo |
|            3 |     8100 | 2024-01-09 | Betera Esports     | W   | 0.257      | -            | -                | -                | -         |     2.50 | adamS, dav1g, JUST, mopoz, stadodo |
|            2 |     8129 | 2024-01-09 | premghouls         | W   | 0.257      | -            | -                | -                | -         |     0.34 | adamS, dav1g, JUST, mopoz, stadodo |
|            1 |     9283 | 2023-12-05 | FORZE Esports      | L   | 0.024      | -            | -                | -                | -         |    -0.63 | adamS, bladE, dav1g, JUST, mopoz   |

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
