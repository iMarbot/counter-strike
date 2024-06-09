### Roster Details<br />
Team Name: Pera Esports<br />
Roster: Aaron, bibu, DGL, kory, Porya<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [66](../standings_global.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
Final Rank Value:  972.7<br />
<br />
Final Rank Value (972.7) = Starting Rank Value (914.8) + Head To Head Adjustments (57.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.155[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.253<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 914.8
- 400 + ( ( 0.253 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 914.8


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
|           62 |       68 | 2024-05-29 | Lilmix             | W   | 1.000      | 0.143        | -                | 0.593 (0.085)    | 0 (0.000) |     7.86 | Aaron, bibu, DGL, kory, Porya      |
|           61 |      477 | 2024-05-22 | System5            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.60 | Aaron, bibu, Ciocardau, DGL, Porya |
|           60 |      587 | 2024-05-21 | EYEBALLERS         | W   | 1.000      | 0.500        | 0.012 (0.006)    | 0.508 (0.254)    | 0 (0.000) |    13.10 | Aaron, bibu, Ciocardau, DGL, Porya |
|           59 |      750 | 2024-05-19 | Permitta Esports   | W   | 1.000      | 0.143        | 0.025 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    11.89 | Aaron, bibu, DGL, kory, Porya      |
|           58 |      761 | 2024-05-19 | MANGANES           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.84 | Aaron, bibu, DGL, kory, Porya      |
|           57 |      770 | 2024-05-19 | DASH               | W   | 1.000      | 0.143        | -                | 0.385 (0.055)    | 0 (0.000) |     5.82 | Aaron, bibu, DGL, kory, Porya      |
|           56 |      786 | 2024-05-19 | brazylijski luz    | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.514 (0.073)    | 0 (0.000) |    13.29 | Aaron, bibu, DGL, kory, Porya      |
|           55 |      896 | 2024-05-18 | Lazer Cats         | L   | 1.000      | -            | -                | -                | -         |   -23.22 | Aaron, bibu, DGL, kory, Porya      |
|           54 |      915 | 2024-05-18 | 2HEADS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.50 | Aaron, bibu, DGL, kory, Porya      |
|           53 |      987 | 2024-05-17 | 1win               | L   | 1.000      | -            | -                | -                | -         |   -11.22 | Aaron, DGL, EspiranTo, kory, Porya |
|           52 |      992 | 2024-05-17 | Verdant            | W   | 1.000      | 0.143        | 0.014 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    15.58 | Aaron, DGL, EspiranTo, kory, Porya |
|           51 |     1003 | 2024-05-17 | Dynamo Eclot       | W   | 1.000      | 0.143        | 0.097 (0.014)    | 0.940 (0.134)    | -         |    16.11 | Aaron, DGL, EspiranTo, kory, Porya |
|           50 |     1014 | 2024-05-17 | ghoulsW            | W   | 1.000      | -            | -                | -                | -         |     3.38 | Aaron, DGL, EspiranTo, kory, Porya |
|           49 |     1105 | 2024-05-16 | ghoulsW            | W   | 1.000      | -            | -                | -                | -         |     3.49 | Aaron, AMANEK, DGL, kory, Porya    |
|           48 |     1160 | 2024-05-15 | Apeks              | W   | 1.000      | -            | -                | -                | -         |     6.30 | Aaron, bibu, Ciocardau, DGL, Porya |
|           47 |     1202 | 2024-05-15 | EC BANGA           | W   | 1.000      | -            | -                | -                | -         |     2.58 | Aaron, AMANEK, DGL, kory, Porya    |
|           46 |     1261 | 2024-05-14 | ALTERNATE aTTaX    | W   | 1.000      | 0.500        | 0.052 (0.026)    | 0.735 (0.368)    | -         |    19.58 | Aaron, bibu, Ciocardau, DGL, Porya |
|           45 |     1865 | 2024-05-04 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -1.31 | Aaron, bibu, Ciocardau, DGL, Porya |
|           44 |     1916 | 2024-05-03 | BIG                | L   | 1.000      | -            | -                | -                | -         |    -2.28 | Aaron, bibu, Ciocardau, DGL, Porya |
|           43 |     1950 | 2024-05-02 | Ninjas in Pyjamas  | W   | 1.000      | 0.889        | 0.118 (0.105)    | 0.285 (0.253)    | 1 (1.000) |    24.21 | Aaron, bibu, Ciocardau, DGL, Porya |
|           42 |     2063 | 2024-04-30 | Complexity Gaming  | L   | 1.000      | -            | -                | -                | -         |    -0.65 | Aaron, bibu, Ciocardau, DGL, Porya |
|           41 |     2619 | 2024-04-20 | EYEBALLERS         | L   | 0.937      | -            | -                | -                | -         |   -13.23 | Aaron, bibu, Ciocardau, DGL, Porya |
|           40 |     3644 | 2024-04-03 | SAW                | L   | 0.823      | -            | -                | -                | -         |    -1.46 | Aaron, bibu, Ciocardau, DGL, Porya |
|           39 |     3907 | 2024-03-27 | Sashi Esport       | L   | 0.777      | -            | -                | -                | -         |    -6.21 | Aaron, DGL, HS, Porya, pr1metapz   |
|           38 |     3979 | 2024-03-26 | The glecs          | W   | 0.771      | -            | -                | -                | -         |     1.56 | Aaron, DGL, HS, Porya, pr1metapz   |
|           37 |     4489 | 2024-03-15 | Betera Esports     | L   | 0.697      | -            | -                | -                | -         |   -12.22 | Aaron, bibu, DGL, msN, Porya       |
|           36 |     5133 | 2024-03-04 | Insilio            | L   | 0.625      | -            | -                | -                | -         |    -8.36 | Aaron, DGL, Kamion, msN, Porya     |
|           35 |     5145 | 2024-03-04 | IMMAPROBLEM        | W   | 0.625      | -            | -                | -                | -         |     2.27 | Aaron, DGL, Kamion, msN, Porya     |
|           34 |     5307 | 2024-03-02 | Balkan Bears       | L   | 0.611      | -            | -                | -                | -         |   -17.30 | Aaron, DGL, Kamion, msN, Porya     |
|           33 |     5568 | 2024-02-26 | System5            | L   | 0.578      | -            | -                | -                | -         |   -14.53 | Aaron, bibu, DGL, msN, Porya       |
|           32 |     5931 | 2024-02-20 | ex-Preasy Esport   | L   | 0.537      | -            | -                | -                | -         |    -8.30 | Aaron, DGL, Kamion, msN, Porya     |
|           31 |     6005 | 2024-02-19 | GamerLegion        | L   | 0.530      | -            | -                | -                | -         |    -2.44 | Aaron, DGL, Kamion, msN, Porya     |
|           30 |     6014 | 2024-02-19 | Cloud9             | L   | 0.530      | -            | -                | -                | -         |    -0.72 | Aaron, DGL, Kamion, msN, Porya     |
|           29 |     6152 | 2024-02-16 | SINNERS Esports    | L   | 0.511      | -            | -                | -                | -         |    -7.03 | Aaron, DGL, Kamion, msN, Porya     |
|           28 |     7302 | 2024-01-25 | ex-Guild Eagles    | W   | 0.364      | -            | -                | -                | -         |     6.57 | Aaron, DGL, Kamion, msN, Porya     |
|           27 |     7336 | 2024-01-24 | Viperio            | W   | 0.358      | -            | -                | -                | -         |     1.47 | Aaron, DGL, Kamion, msN, Porya     |
|           26 |     7416 | 2024-01-23 | ALTERNATE aTTaX    | W   | 0.351      | 0.143        | 0.052 (0.003)    | -                | -         |     6.76 | Aaron, DGL, Kamion, msN, Porya     |
|           25 |     7421 | 2024-01-23 | Rebels Gaming      | W   | 0.350      | 0.143        | 0.062 (0.003)    | -                | -         |     7.96 | Aaron, DGL, Kamion, msN, Porya     |
|           24 |     7450 | 2024-01-22 | ex-Guild Eagles    | W   | 0.344      | -            | -                | -                | -         |     6.38 | Aaron, DGL, Kamion, msN, Porya     |
|           23 |     7467 | 2024-01-22 | Team Sampi         | L   | 0.344      | -            | -                | -                | -         |    -4.88 | Aaron, DGL, Kamion, msN, Porya     |
|           22 |     7475 | 2024-01-22 | Viperio            | W   | 0.344      | -            | -                | -                | -         |     1.42 | Aaron, DGL, Kamion, msN, Porya     |
|           21 |     7514 | 2024-01-21 | ex-sYnck           | W   | 0.337      | -            | -                | -                | -         |     3.06 | Aaron, DGL, Kamion, msN, Porya     |
|           20 |     7521 | 2024-01-21 | Gaimin Gladiators  | L   | 0.336      | -            | -                | -                | -         |    -1.27 | Aaron, DGL, Kamion, msN, Porya     |
|           19 |     7564 | 2024-01-20 | KOI                | L   | 0.331      | -            | -                | -                | -         |    -4.42 | Aaron, DGL, Kamion, msN, Porya     |
|           18 |     7587 | 2024-01-20 | Astralis           | L   | 0.330      | -            | -                | -                | -         |    -0.16 | Aaron, DGL, Kamion, msN, Porya     |
|           17 |     7657 | 2024-01-19 | IKLA               | W   | 0.323      | -            | -                | -                | -         |     1.48 | Aaron, DGL, Kamion, msN, Porya     |
|           16 |     7711 | 2024-01-18 | EYEBALLERS         | W   | 0.318      | -            | -                | -                | -         |     5.09 | Aaron, DGL, Kamion, msN, Porya     |
|           15 |     7733 | 2024-01-18 | Eternal Fire       | L   | 0.317      | -            | -                | -                | -         |    -0.06 | Aaron, DGL, Kamion, msN, Porya     |
|           14 |     8168 | 2024-01-11 | IKLA               | L   | 0.272      | -            | -                | -                | -         |    -7.42 | Aaron, DGL, Kamion, msN, Porya     |
|           13 |     8176 | 2024-01-11 | SINNERS Esports    | L   | 0.271      | -            | -                | -                | -         |    -3.07 | Aaron, DGL, Kamion, msN, Porya     |
|           12 |     8191 | 2024-01-11 | ex-Anonymo Esports | W   | 0.270      | -            | -                | -                | -         |     2.02 | Aaron, DGL, Kamion, msN, Porya     |
|           11 |     8201 | 2024-01-11 | Permitta Esports   | W   | 0.270      | 0.143        | -                | 1.000 (0.039)    | -         |     4.76 | Aaron, DGL, Kamion, msN, Porya     |
|           10 |     8252 | 2024-01-10 | esmagaB            | W   | 0.265      | -            | -                | -                | -         |     3.49 | Aaron, DGL, Kamion, msN, Porya     |
|            9 |     8283 | 2024-01-10 | ENRAGE             | W   | 0.265      | -            | -                | -                | -         |     0.88 | Aaron, DGL, Kamion, msN, Porya     |
|            8 |     8346 | 2024-01-09 | Sashi Esport       | L   | 0.257      | -            | -                | -                | -         |    -2.41 | Aaron, DGL, Kamion, msN, Porya     |
|            7 |     8369 | 2024-01-09 | szczury123         | W   | 0.257      | -            | -                | -                | -         |     0.42 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     8638 | 2023-12-20 | Metizport          | W   | 0.124      | 0.333        | 0.088 (0.004)    | -                | -         |     2.28 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     8645 | 2023-12-20 | Sprout             | W   | 0.122      | -            | -                | -                | -         |     0.50 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     8654 | 2023-12-19 | GUN5 Esports       | W   | 0.117      | -            | -                | -                | -         |     0.38 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     8658 | 2023-12-19 | Soda Gaming        | W   | 0.116      | -            | -                | -                | -         |     0.68 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     8660 | 2023-12-19 | Metizport          | L   | 0.116      | -            | -                | -                | -         |    -1.52 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     9657 | 2023-12-03 | showmakerz         | W   | 0.010      | -            | -                | -                | -         |     0.03 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,500.93)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $500.00        | $500.00         |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2023-12-20 |      0.124 | $8,000.00      | $991.11         |
| 2023-12-03 |      0.010 | $1,000.00      | $9.81           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
