### Roster Details<br />
Team Name: PARIVISION<br />
Roster: ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [74](../standings_global.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
Final Rank Value:  929.1<br />
<br />
Final Rank Value (929.1) = Starting Rank Value (934.1) + Head To Head Adjustments (-5.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.265[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.343[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.262<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 934.1
- 400 + ( ( 0.262 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 934.1


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
|           44 |      708 | 2024-05-20 | Sangal Esports    | L   | 1.000      | -            | -                | -                | -         |   -10.48 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           43 |      956 | 2024-05-17 | Zero Tenacity     | W   | 1.000      | 0.500        | 0.147 (0.073)    | 1.000 (0.500)    | 0 (0.000) |    18.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           42 |     1041 | 2024-05-16 | Aurora Gaming     | L   | 1.000      | -            | -                | -                | -         |    -2.67 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           41 |     1092 | 2024-05-16 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -0.28 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           40 |     1141 | 2024-05-15 | B8                | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.952 (0.476)    | 0 (0.000) |    24.51 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           39 |     1379 | 2024-05-12 | 5W Gaming         | L   | 1.000      | -            | -                | -                | -         |   -28.56 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           38 |     1523 | 2024-05-10 | Sangal Esports    | L   | 1.000      | -            | -                | -                | -         |   -12.03 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           37 |     1569 | 2024-05-09 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -15.47 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           36 |     1986 | 2024-05-01 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -17.34 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           35 |     2007 | 2024-05-01 | Fnatic            | L   | 1.000      | -            | -                | -                | -         |    -8.07 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           34 |     2079 | 2024-04-29 | Zero Tenacity     | W   | 0.996      | 0.500        | 0.147 (0.073)    | 1.000 (0.498)    | 0 (0.000) |    17.35 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           33 |     2179 | 2024-04-27 | Sangal Esports    | W   | 0.983      | 0.500        | 0.166 (0.082)    | 0.577 (0.283)    | 0 (0.000) |    18.05 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           32 |     2268 | 2024-04-26 | SINNERS Esports   | W   | 0.976      | 0.435        | -                | 0.560 (0.238)    | 0 (0.000) |    18.20 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           31 |     2323 | 2024-04-25 | ex-Guild Eagles   | W   | 0.969      | 0.384        | -                | 0.475 (0.177)    | 0 (0.000) |    18.80 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           30 |     2382 | 2024-04-24 | MOUZ NXT          | W   | 0.963      | 0.435        | 0.157 (0.066)    | 0.950 (0.397)    | 0 (0.000) |    21.77 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |     2502 | 2024-04-21 | Nexus Gaming      | W   | 0.943      | 0.435        | 0.014 (0.006)    | 0.825 (0.338)    | 0 (0.000) |    16.68 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |     2514 | 2024-04-21 | B8                | L   | 0.942      | -            | -                | -                | -         |    -6.96 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |     2683 | 2024-04-19 | Zero Tenacity     | L   | 0.931      | -            | -                | -                | -         |   -11.02 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |     2836 | 2024-04-17 | HAVU Gaming       | W   | 0.917      | -            | -                | -                | 0 (0.000) |     7.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           25 |     2848 | 2024-04-17 | Permitta Esports  | L   | 0.916      | -            | -                | -                | -         |   -10.56 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           24 |     3120 | 2024-04-11 | 500               | L   | 0.877      | -            | -                | -                | -         |   -13.82 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           23 |     3167 | 2024-04-10 | Aurora Gaming     | L   | 0.871      | -            | -                | -                | -         |    -1.64 | ArtFr0st, notineki, Patsi, Qikert, X5G7V   |
|           22 |     3237 | 2024-04-09 | RUSH B            | L   | 0.864      | -            | -                | -                | -         |   -17.23 | ArtFr0st, notineki, Patsi, Qikert, X5G7V   |
|           21 |     3543 | 2024-04-03 | MOUZ NXT          | L   | 0.824      | -            | -                | -                | -         |    -8.35 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           20 |     3601 | 2024-04-02 | AMKAL ESPORTS     | L   | 0.816      | -            | -                | -                | -         |    -6.87 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           19 |     3608 | 2024-04-02 | Insilio           | L   | 0.816      | -            | -                | -                | -         |   -12.36 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           18 |     3627 | 2024-04-01 | Metizport         | W   | 0.810      | 0.384        | 0.088 (0.027)    | 0.698 (0.217)    | 0 (0.000) |    17.51 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           17 |     3854 | 2024-03-26 | Betera Esports    | L   | 0.771      | -            | -                | -                | -         |   -15.07 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           16 |     4093 | 2024-03-21 | FORZE Esports     | W   | 0.737      | 0.500        | 0.111 (0.041)    | -                | -         |    15.16 | ArtFr0st, notineki, Patsi, Qikert, X5G7V   |
|           15 |     4498 | 2024-03-13 | 3DMAX             | W   | 0.683      | 0.500        | 0.106 (0.036)    | -                | -         |    11.52 | ArtFr0st, notineki, Patsi, Qikert, X5G7V   |
|           14 |     4752 | 2024-03-08 | B8                | W   | 0.650      | 0.500        | 0.168 (0.055)    | 0.952 (0.309)    | -         |    15.78 | ArtFr0st, notineki, Patsi, Qikert, X5G7V   |
|           13 |     4881 | 2024-03-06 | Apeks             | W   | 0.637      | -            | -                | -                | -         |     3.97 | ArtFr0st, notineki, Patsi, Qikert, X5G7V   |
|           12 |     5020 | 2024-03-04 | Fnatic            | L   | 0.625      | -            | -                | -                | -         |    -4.42 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     5146 | 2024-03-02 | KOI               | L   | 0.611      | -            | -                | -                | -         |    -7.08 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           10 |     5196 | 2024-03-02 | Gaimin Gladiators | L   | 0.609      | -            | -                | -                | -         |    -2.50 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            9 |     5289 | 2024-02-29 | Monte             | L   | 0.596      | -            | -                | -                | -         |    -1.80 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     6796 | 2024-01-29 | GUN5 Esports      | L   | 0.392      | -            | -                | -                | -         |   -10.57 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     6819 | 2024-01-29 | M1X               | W   | 0.392      | -            | -                | -                | -         |     1.72 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     7519 | 2024-01-17 | Insilio           | L   | 0.312      | -            | -                | -                | -         |    -5.14 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     7528 | 2024-01-17 | ex-Preasy Esport  | W   | 0.312      | -            | -                | -                | -         |     4.82 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     7551 | 2024-01-17 | kONO.ECF          | W   | 0.311      | -            | -                | -                | -         |     4.02 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     7648 | 2024-01-16 | EYEBALLERS        | L   | 0.304      | -            | -                | -                | -         |    -5.04 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     7663 | 2024-01-16 | LODIS             | W   | 0.304      | -            | -                | -                | -         |     1.65 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     8024 | 2024-01-10 | francesinha       | L   | 0.265      | -            | -                | -                | -         |    -7.71 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

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
