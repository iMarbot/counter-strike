### Roster Details<br />
Team Name: PARIVISION<br />
Roster: ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [75](../standings_global.md)<br />
Regional Rank: [52]( ../standings_europe.md)<br />
Final Rank Value:  930.1<br />
<br />
Final Rank Value (930.1) = Starting Rank Value (934.5) + Head To Head Adjustments (-4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.265[<sup>1</sup>](#table2)
- Bounty Collected: 0.436[<sup>2</sup>](#table1)
- Opponent Network: 0.352[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.263<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.5
- 400 + ( ( 0.263 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 934.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      720 | 2024-05-20 | Sangal Esports    | L   | 1.000      | -            | -                | -                | -         |    -9.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           43 |      968 | 2024-05-17 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.147 (0.073)    | 1.000 (0.500)    | 0 (0.000) |    19.04 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           42 |     1053 | 2024-05-16 | Aurora Gaming     | L   | 1.000      | -            | -                | -                | -         |    -2.95 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           41 |     1102 | 2024-05-16 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -0.28 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           40 |     1150 | 2024-05-15 | B8                | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.963 (0.482)    | 0 (0.000) |    24.28 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           39 |     1392 | 2024-05-12 | 5W Gaming         | L   | 1.000      | -            | -                | -                | -         |   -28.57 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           38 |     1537 | 2024-05-10 | Sangal Esports    | L   | 1.000      | -            | -                | -                | -         |   -10.89 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           37 |     1585 | 2024-05-09 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -14.41 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           36 |     2015 | 2024-05-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -16.70 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           35 |     2038 | 2024-05-01 | Fnatic            | L   | 1.000      | -            | -                | -                | -         |    -7.94 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           34 |     2114 | 2024-04-29 | Zero Tenacity     | W   | 0.996      | 0.500        | 0.147 (0.073)    | 1.000 (0.498)    | 0 (0.000) |    17.33 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           33 |     2214 | 2024-04-27 | Sangal Esports    | W   | 0.983      | 0.500        | 0.166 (0.082)    | 0.658 (0.324)    | 0 (0.000) |    19.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2304 | 2024-04-26 | SINNERS Esports   | W   | 0.976      | 0.435        | 0.011 (0.005)    | 0.582 (0.247)    | 0 (0.000) |    18.81 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2364 | 2024-04-25 | ex-Guild Eagles   | W   | 0.969      | 0.384        | 0.015 (0.006)    | 0.475 (0.177)    | 0 (0.000) |    19.22 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           30 |     2426 | 2024-04-24 | MOUZ NXT          | W   | 0.963      | 0.435        | 0.157 (0.066)    | 0.977 (0.409)    | 0 (0.000) |    22.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2555 | 2024-04-21 | Nexus Gaming      | W   | 0.943      | 0.435        | -                | 0.857 (0.351)    | 0 (0.000) |    17.18 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2567 | 2024-04-21 | B8                | L   | 0.942      | -            | -                | -                | -         |    -7.37 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2737 | 2024-04-19 | Zero Tenacity     | L   | 0.931      | -            | -                | -                | -         |   -11.11 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2893 | 2024-04-17 | HAVU Gaming       | W   | 0.917      | -            | -                | -                | 0 (0.000) |     7.95 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2904 | 2024-04-17 | Permitta Esports  | L   | 0.916      | -            | -                | -                | -         |    -9.94 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           24 |     3188 | 2024-04-11 | 500               | L   | 0.877      | -            | -                | -                | -         |   -13.37 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           23 |     3240 | 2024-04-10 | Aurora Gaming     | L   | 0.871      | -            | -                | -                | -         |    -1.85 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           22 |     3316 | 2024-04-09 | RUSH B            | L   | 0.864      | -            | -                | -                | -         |   -16.60 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           21 |     3630 | 2024-04-03 | MOUZ NXT          | L   | 0.824      | -            | -                | -                | -         |    -7.72 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           20 |     3691 | 2024-04-02 | AMKAL ESPORTS     | L   | 0.816      | -            | -                | -                | -         |    -6.60 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           19 |     3698 | 2024-04-02 | Insilio           | L   | 0.816      | -            | -                | -                | -         |   -12.12 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           18 |     3717 | 2024-04-01 | Metizport         | W   | 0.810      | 0.384        | 0.088 (0.027)    | 0.698 (0.217)    | 0 (0.000) |    17.42 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           17 |     3951 | 2024-03-26 | Betera Esports    | L   | 0.771      | -            | -                | -                | -         |   -14.71 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           16 |     4192 | 2024-03-21 | FORZE Esports     | W   | 0.737      | -            | -                | -                | -         |     5.78 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           15 |     4613 | 2024-03-13 | 3DMAX             | W   | 0.683      | 0.500        | 0.106 (0.036)    | -                | -         |    11.56 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           14 |     4879 | 2024-03-08 | B8                | W   | 0.650      | 0.500        | 0.168 (0.055)    | 0.963 (0.313)    | -         |    15.80 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           13 |     5012 | 2024-03-06 | Apeks             | W   | 0.637      | -            | -                | -                | -         |     3.95 | alpha, ArtFr0st, BELCHONOKK, Patsi, Qikert |
|           12 |     5166 | 2024-03-04 | Fnatic            | L   | 0.625      | -            | -                | -                | -         |    -4.40 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     5294 | 2024-03-02 | KOI               | L   | 0.611      | -            | -                | -                | -         |    -6.98 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     5344 | 2024-03-02 | Gaimin Gladiators | L   | 0.609      | -            | -                | -                | -         |    -2.48 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     5439 | 2024-02-29 | Monte             | L   | 0.596      | -            | -                | -                | -         |    -1.77 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     7012 | 2024-01-29 | GUN5 Esports      | L   | 0.392      | -            | -                | -                | -         |   -10.56 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     7035 | 2024-01-29 | M1X               | W   | 0.392      | -            | -                | -                | -         |     1.71 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     7768 | 2024-01-17 | Insilio           | L   | 0.312      | -            | -                | -                | -         |    -5.25 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     7777 | 2024-01-17 | ex-Preasy Esport  | W   | 0.312      | -            | -                | -                | -         |     4.85 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     7800 | 2024-01-17 | kONO.ECF          | W   | 0.311      | -            | -                | -                | -         |     4.18 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     7897 | 2024-01-16 | EYEBALLERS        | L   | 0.304      | -            | -                | -                | -         |    -5.02 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     7912 | 2024-01-16 | LODIS             | W   | 0.304      | -            | -                | -                | -         |     1.67 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     8278 | 2024-01-10 | francesinha       | L   | 0.265      | -            | -                | -                | -         |    -7.71 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($500.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
