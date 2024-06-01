### Roster Details<br />
Team Name: Pera Esports<br />
Roster: Aaron, bibu, DGL, kory, Porya<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [65](../standings_global.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
Final Rank Value:  977.2<br />
<br />
Final Rank Value (977.2) = Starting Rank Value (920.7) + Head To Head Adjustments (56.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.392[<sup>1</sup>](#table2)
- Bounty Collected: 0.360[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.256<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 920.7
- 400 + ( ( 0.256 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 920.7


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
|           63 |       64 | 2024-05-29 | Lilmix             | W   | 1.000      | 0.143        | -                | 0.581 (0.083)    | 0 (0.000) |     7.51 | Aaron, bibu, DGL, kory, Porya      |
|           62 |      471 | 2024-05-22 | System5            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.50 | Aaron, bibu, DGL, kory, Porya      |
|           61 |      576 | 2024-05-21 | EYEBALLERS         | W   | 1.000      | 0.500        | 0.012 (0.006)    | 0.508 (0.254)    | 0 (0.000) |    13.14 | Aaron, bibu, DGL, kory, Porya      |
|           60 |      738 | 2024-05-19 | Permitta Esports   | W   | 1.000      | 0.143        | 0.029 (0.004)    | 1.000 (0.143)    | 0 (0.000) |    10.94 | Aaron, bibu, DGL, kory, Porya      |
|           59 |      749 | 2024-05-19 | MANGANES           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.73 | Aaron, bibu, DGL, kory, Porya      |
|           58 |      758 | 2024-05-19 | DASH               | W   | 1.000      | 0.143        | -                | 0.358 (0.051)    | 0 (0.000) |     5.03 | Aaron, bibu, DGL, kory, Porya      |
|           57 |      774 | 2024-05-19 | brazylijski luz    | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.490 (0.070)    | 0 (0.000) |    12.77 | Aaron, bibu, DGL, kory, Porya      |
|           56 |      884 | 2024-05-18 | Lazer Cats         | L   | 1.000      | -            | -                | -                | -         |   -23.50 | Aaron, bibu, DGL, kory, Porya      |
|           55 |      903 | 2024-05-18 | 2HEADS             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.44 | Aaron, bibu, DGL, kory, Porya      |
|           54 |      975 | 2024-05-17 | 1win               | L   | 1.000      | -            | -                | -                | -         |   -11.52 | Aaron, DGL, EspiranTo, kory, Porya |
|           53 |      980 | 2024-05-17 | Verdant            | W   | 1.000      | 0.143        | 0.014 (0.002)    | 1.000 (0.143)    | 0 (0.000) |    14.95 | Aaron, DGL, EspiranTo, kory, Porya |
|           52 |      991 | 2024-05-17 | Dynamo Eclot       | W   | 1.000      | 0.143        | 0.097 (0.014)    | 0.936 (0.134)    | -         |    16.28 | Aaron, DGL, EspiranTo, kory, Porya |
|           51 |     1002 | 2024-05-17 | ghoulsW            | W   | 1.000      | -            | -                | -                | -         |     3.24 | Aaron, DGL, EspiranTo, kory, Porya |
|           50 |     1095 | 2024-05-16 | ghoulsW            | W   | 1.000      | -            | -                | -                | -         |     3.35 | Aaron, AMANEK, DGL, kory, Porya    |
|           49 |     1151 | 2024-05-15 | Apeks              | W   | 1.000      | -            | -                | -                | -         |     6.25 | Aaron, bibu, DGL, kory, Porya      |
|           48 |     1192 | 2024-05-15 | EC BANGA           | W   | 1.000      | -            | -                | -                | -         |     2.47 | Aaron, AMANEK, DGL, kory, Porya    |
|           47 |     1251 | 2024-05-14 | ALTERNATE aTTaX    | W   | 1.000      | 0.500        | 0.052 (0.026)    | 0.679 (0.340)    | -         |    19.10 | Aaron, bibu, DGL, kory, Porya      |
|           46 |     1842 | 2024-05-04 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -1.42 | Aaron, bibu, Ciocardau, DGL, Porya |
|           45 |     1891 | 2024-05-03 | BIG                | L   | 1.000      | -            | -                | -                | -         |    -2.30 | Aaron, bibu, Ciocardau, DGL, Porya |
|           44 |     1923 | 2024-05-02 | Ninjas in Pyjamas  | W   | 1.000      | 0.889        | 0.118 (0.105)    | 0.285 (0.253)    | 1 (1.000) |    23.89 | Aaron, bibu, Ciocardau, DGL, Porya |
|           43 |     2030 | 2024-04-30 | Complexity Gaming  | L   | 1.000      | -            | -                | -                | -         |    -0.68 | Aaron, bibu, Ciocardau, DGL, Porya |
|           42 |     2566 | 2024-04-20 | EYEBALLERS         | L   | 0.937      | -            | -                | -                | -         |   -12.86 | Aaron, bibu, DGL, kory, Porya      |
|           41 |     3557 | 2024-04-03 | SAW                | L   | 0.823      | -            | -                | -                | -         |    -1.54 | Aaron, bibu, DGL, kory, Porya      |
|           40 |     3626 | 2024-04-01 | RUSH B             | W   | 0.810      | 0.500        | -                | 0.446 (0.181)    | -         |    10.44 | Aaron, bibu, DGL, kory, Porya      |
|           39 |     3814 | 2024-03-27 | Sashi Esport       | L   | 0.777      | -            | -                | -                | -         |    -6.38 | Aaron, DGL, HS, Porya, pr1metapz   |
|           38 |     3882 | 2024-03-26 | The glecs          | W   | 0.771      | -            | -                | -                | -         |     1.57 | Aaron, DGL, HS, Porya, pr1metapz   |
|           37 |     4381 | 2024-03-15 | Betera Esports     | L   | 0.697      | -            | -                | -                | -         |   -12.28 | Aaron, DGL, kory, msN, Porya       |
|           36 |     4987 | 2024-03-04 | Insilio            | L   | 0.625      | -            | -                | -                | -         |    -8.33 | Aaron, DGL, Kamion, msN, Porya     |
|           35 |     4999 | 2024-03-04 | IMMAPROBLEM        | W   | 0.625      | -            | -                | -                | -         |     2.27 | Aaron, DGL, Kamion, msN, Porya     |
|           34 |     5159 | 2024-03-02 | Balkan Bears       | L   | 0.611      | -            | -                | -                | -         |   -17.29 | Aaron, DGL, Kamion, msN, Porya     |
|           33 |     5411 | 2024-02-26 | System5            | L   | 0.578      | -            | -                | -                | -         |   -14.50 | Aaron, DGL, kory, msN, Porya       |
|           32 |     5763 | 2024-02-20 | ex-Preasy Esport   | L   | 0.537      | -            | -                | -                | -         |    -8.37 | Aaron, DGL, Kamion, msN, Porya     |
|           31 |     5834 | 2024-02-19 | GamerLegion        | L   | 0.530      | -            | -                | -                | -         |    -2.42 | Aaron, DGL, Kamion, msN, Porya     |
|           30 |     5842 | 2024-02-19 | Cloud9             | L   | 0.530      | -            | -                | -                | -         |    -0.72 | Aaron, DGL, Kamion, msN, Porya     |
|           29 |     5979 | 2024-02-16 | SINNERS Esports    | L   | 0.511      | -            | -                | -                | -         |    -7.52 | Aaron, DGL, Kamion, msN, Porya     |
|           28 |     7076 | 2024-01-25 | ex-Guild Eagles    | W   | 0.364      | -            | -                | -                | -         |     6.44 | Aaron, DGL, Kamion, msN, Porya     |
|           27 |     7106 | 2024-01-24 | Viperio            | W   | 0.358      | -            | -                | -                | -         |     1.45 | Aaron, DGL, Kamion, msN, Porya     |
|           26 |     7178 | 2024-01-23 | ALTERNATE aTTaX    | W   | 0.351      | -            | -                | -                | -         |     2.72 | Aaron, DGL, Kamion, msN, Porya     |
|           25 |     7182 | 2024-01-23 | Rebels Gaming      | W   | 0.350      | 0.143        | 0.062 (0.003)    | -                | -         |     7.87 | Aaron, DGL, Kamion, msN, Porya     |
|           24 |     7209 | 2024-01-22 | ex-Guild Eagles    | W   | 0.344      | -            | -                | -                | -         |     6.32 | Aaron, DGL, Kamion, msN, Porya     |
|           23 |     7224 | 2024-01-22 | Team Sampi         | L   | 0.344      | -            | -                | -                | -         |    -5.02 | Aaron, DGL, Kamion, msN, Porya     |
|           22 |     7232 | 2024-01-22 | Viperio            | W   | 0.344      | -            | -                | -                | -         |     1.38 | Aaron, DGL, Kamion, msN, Porya     |
|           21 |     7271 | 2024-01-21 | ex-sYnck           | W   | 0.337      | -            | -                | -                | -         |     2.68 | Aaron, DGL, Kamion, msN, Porya     |
|           20 |     7278 | 2024-01-21 | Gaimin Gladiators  | L   | 0.336      | -            | -                | -                | -         |    -1.32 | Aaron, DGL, Kamion, msN, Porya     |
|           19 |     7321 | 2024-01-20 | KOI                | L   | 0.331      | -            | -                | -                | -         |    -4.56 | Aaron, DGL, Kamion, msN, Porya     |
|           18 |     7343 | 2024-01-20 | Astralis           | L   | 0.330      | -            | -                | -                | -         |    -0.16 | Aaron, DGL, Kamion, msN, Porya     |
|           17 |     7411 | 2024-01-19 | IKLA               | W   | 0.323      | -            | -                | -                | -         |     1.46 | Aaron, DGL, Kamion, msN, Porya     |
|           16 |     7463 | 2024-01-18 | EYEBALLERS         | W   | 0.318      | -            | -                | -                | -         |     5.00 | Aaron, DGL, Kamion, msN, Porya     |
|           15 |     7484 | 2024-01-18 | Eternal Fire       | L   | 0.317      | -            | -                | -                | -         |    -0.06 | Aaron, DGL, Kamion, msN, Porya     |
|           14 |     7915 | 2024-01-11 | IKLA               | L   | 0.272      | -            | -                | -                | -         |    -7.43 | Aaron, DGL, Kamion, msN, Porya     |
|           13 |     7923 | 2024-01-11 | SINNERS Esports    | L   | 0.271      | -            | -                | -                | -         |    -3.41 | Aaron, DGL, Kamion, msN, Porya     |
|           12 |     7938 | 2024-01-11 | ex-Anonymo Esports | W   | 0.270      | -            | -                | -                | -         |     1.98 | Aaron, DGL, Kamion, msN, Porya     |
|           11 |     7948 | 2024-01-11 | Permitta Esports   | W   | 0.270      | 0.143        | 0.029 (0.001)    | -                | -         |     4.62 | Aaron, DGL, Kamion, msN, Porya     |
|           10 |     7998 | 2024-01-10 | esmagaB            | W   | 0.265      | -            | -                | -                | -         |     3.38 | Aaron, DGL, Kamion, msN, Porya     |
|            9 |     8029 | 2024-01-10 | ENRAGE             | W   | 0.265      | -            | -                | -                | -         |     0.85 | Aaron, DGL, Kamion, msN, Porya     |
|            8 |     8092 | 2024-01-09 | Sashi Esport       | L   | 0.257      | -            | -                | -                | -         |    -2.46 | Aaron, DGL, Kamion, msN, Porya     |
|            7 |     8115 | 2024-01-09 | szczury123         | W   | 0.257      | -            | -                | -                | -         |     0.41 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     8381 | 2023-12-20 | Metizport          | W   | 0.124      | 0.333        | 0.088 (0.004)    | -                | -         |     2.24 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     8388 | 2023-12-20 | Sprout             | W   | 0.122      | -            | -                | -                | -         |     0.48 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     8397 | 2023-12-19 | GUN5 Esports       | W   | 0.117      | -            | -                | -                | -         |     0.36 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     8401 | 2023-12-19 | Soda Gaming        | W   | 0.116      | -            | -                | -                | -         |     0.59 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     8403 | 2023-12-19 | Metizport          | L   | 0.116      | -            | -                | -                | -         |    -1.56 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     9375 | 2023-12-03 | showmakerz         | W   | 0.010      | -            | -                | -                | -         |     0.03 | Aaron, DGL, Kamion, msN, Porya     |

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
