### Roster Details<br />
Team Name: SAW<br />
Roster: arrozdoce, ewjerkz, MUTiRiS, rmn, story<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [19](../standings_global.md)<br />
Regional Rank: [13]( ../standings_europe.md)<br />
Final Rank Value:  1385.4<br />
<br />
Final Rank Value (1385.4) = Starting Rank Value (1365.1) + Head To Head Adjustments (20.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.512[<sup>1</sup>](#table2)
- Bounty Collected: 0.592[<sup>2</sup>](#table1)
- Opponent Network: 0.276[<sup>2</sup>](#table1)
- LAN Wins: 0.520[<sup>2</sup>](#table1)

The average of these factors is 0.475<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1365.1
- 400 + ( ( 0.475 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1365.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |     1024 | 2024-05-17 | Aurora Gaming             | L   | 1.000      | -            | -                | -                | -         |   -18.23 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           40 |     1076 | 2024-05-16 | Eternal Fire              | L   | 1.000      | -            | -                | -                | -         |    -3.72 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           39 |     1113 | 2024-05-16 | Aurora Gaming             | W   | 1.000      | 0.769        | 0.492 (0.378)    | 0.573 (0.441)    | 0 (0.000) |    13.05 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           38 |     2150 | 2024-04-28 | Virtus.pro                | L   | 0.990      | -            | -                | -                | -         |    -6.04 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           37 |     2209 | 2024-04-27 | Eternal Fire              | W   | 0.984      | 0.889        | 1.000 (0.874)    | 0.402 (0.351)    | 1 (0.984) |    27.88 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           36 |     2303 | 2024-04-26 | Imperial Esports          | W   | 0.976      | 0.889        | 0.372 (0.323)    | 0.582 (0.505)    | 1 (0.976) |    19.26 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           35 |     2425 | 2024-04-24 | Virtus.pro                | L   | 0.963      | -            | -                | -                | -         |    -4.91 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           34 |     2987 | 2024-04-16 | Team Sampi                | L   | 0.909      | -            | -                | -                | -         |   -25.29 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           33 |     3241 | 2024-04-10 | 9Pandas                   | W   | 0.871      | 0.500        | 0.110 (0.048)    | 0.710 (0.309)    | 0 (0.000) |     5.36 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           32 |     3544 | 2024-04-05 | ex-Turów Zgorzelec Esport | W   | 0.835      | 0.384        | -                | 0.491 (0.158)    | 0 (0.000) |     0.89 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           31 |     3583 | 2024-04-04 | Betera Esports            | W   | 0.830      | 0.500        | -                | 0.257 (0.107)    | -         |     1.57 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           30 |     3644 | 2024-04-03 | Pera Esports              | W   | 0.823      | 0.500        | 0.028 (0.012)    | 0.542 (0.223)    | -         |     1.46 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           29 |     4233 | 2024-03-20 | FURIA Esports             | L   | 0.731      | -            | -                | -                | -         |   -10.29 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           28 |     4279 | 2024-03-19 | paiN Gaming               | L   | 0.723      | -            | -                | -                | -         |    -5.87 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           27 |     4315 | 2024-03-18 | Cloud9                    | L   | 0.717      | -            | -                | -                | -         |    -7.93 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           26 |     4338 | 2024-03-17 | GamerLegion               | W   | 0.712      | 1.000        | 0.075 (0.053)    | -                | 1 (0.712) |     7.01 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           25 |     4380 | 2024-03-17 | KOI                       | W   | 0.710      | 1.000        | 0.027 (0.020)    | 0.455 (0.323)    | 1 (0.710) |     3.00 | arrozdoce, ewjerkz, MUTiRiS, roman, story |
|           24 |     4591 | 2024-03-13 | System5                   | W   | 0.684      | -            | -                | -                | -         |     0.42 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           23 |     4784 | 2024-03-10 | OG                        | W   | 0.664      | 0.535        | 0.277 (0.098)    | -                | -         |     5.68 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           22 |     4872 | 2024-03-08 | Cloud9                    | W   | 0.651      | 0.535        | 0.187 (0.065)    | -                | -         |    13.89 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           21 |     4949 | 2024-03-07 | Team Liquid               | W   | 0.643      | 0.535        | 0.493 (0.170)    | 0.621 (0.214)    | -         |    16.26 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           20 |     5567 | 2024-02-26 | RUSH B                    | W   | 0.578      | 0.500        | -                | 0.446 (0.129)    | -         |     0.64 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           19 |     6122 | 2024-02-17 | Fnatic                    | W   | 0.517      | -            | -                | -                | 1 (0.517) |     3.58 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           18 |     6150 | 2024-02-16 | ENTERPRISE esports        | W   | 0.511      | -            | -                | -                | 1 (0.511) |     1.90 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           17 |     6237 | 2024-02-15 | Ninjas in Pyjamas         | W   | 0.503      | -            | -                | -                | 1 (0.503) |     0.58 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           16 |     6286 | 2024-02-14 | 9Pandas                   | L   | 0.497      | -            | -                | -                | -         |   -11.35 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           15 |     6311 | 2024-02-14 | Virtus.pro                | L   | 0.496      | -            | -                | -                | -         |    -2.20 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           14 |     6668 | 2024-02-04 | Rhyno Esports             | W   | 0.430      | -            | -                | -                | -         |     1.74 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           13 |     6765 | 2024-02-03 | KOI                       | W   | 0.423      | -            | -                | -                | -         |     1.46 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           12 |     6870 | 2024-02-01 | AL-QATRAO                 | W   | 0.411      | -            | -                | -                | -         |     0.42 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           11 |     6873 | 2024-02-01 | The Agency Clan           | W   | 0.411      | -            | -                | -                | -         |     0.11 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|           10 |     6883 | 2024-02-01 | AL-QATRAO                 | L   | 0.410      | -            | -                | -                | -         |   -12.53 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            9 |     7592 | 2024-01-20 | 9Pandas                   | W   | 0.330      | -            | -                | -                | -         |     2.77 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            8 |     7659 | 2024-01-19 | Zero Tenacity             | W   | 0.323      | -            | -                | -                | -         |     1.64 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            7 |     7713 | 2024-01-18 | Virtus.pro                | L   | 0.317      | -            | -                | -                | -         |    -1.34 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            6 |     7722 | 2024-01-18 | Fnatic                    | W   | 0.317      | -            | -                | -                | -         |     2.05 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            5 |     9202 | 2023-12-11 | FORZE Esports             | L   | 0.063      | -            | -                | -                | -         |    -1.91 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            4 |     9523 | 2023-12-06 | 9Pandas                   | L   | 0.029      | -            | -                | -                | -         |    -0.67 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            3 |     9601 | 2023-12-05 | RED Canids                | W   | 0.022      | -            | -                | -                | -         |     0.08 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            2 |     9621 | 2023-12-04 | Zero Tenacity             | W   | 0.016      | -            | -                | -                | -         |     0.10 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |
|            1 |     9658 | 2023-12-03 | Aurora Gaming             | L   | 0.010      | -            | -                | -                | -         |    -0.10 | arrozdoce, ewjerkz, MUTiRiS, rmn, story   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,556.70)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |
| 2024-03-10 |      0.665 | $20,000.00     | $13,290.28      |
| 2023-12-13 |      0.078 | $500.00        | $38.76          |
| 2023-12-07 |      0.038 | $5,000.00      | $188.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
