### Roster Details<br />
Team Name: PARIVISION<br />
Roster: ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [73](../standings_global.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
Final Rank Value:  910.9<br />
<br />
Final Rank Value (910.9) = Starting Rank Value (872.6) + Head To Head Adjustments (38.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.412[<sup>2</sup>](#table1)
- Opponent Network: 0.255[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 872.6
- 400 + ( ( 0.238 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 872.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      205 | 2024-05-01 | Passion UA            | L   | 1.000      | -            | -                | -                | -         |   -15.65 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           29 |      224 | 2024-05-01 | Fnatic                | L   | 1.000      | -            | -                | -                | -         |    -4.86 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           28 |      287 | 2024-04-29 | Zero Tenacity         | W   | 1.000      | 0.500        | 0.095 (0.047)    | 1.000 (0.500)    | 0 (0.000) |    18.14 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           27 |      434 | 2024-04-26 | SINNERS Esports       | W   | 1.000      | 0.435        | 0.038 (0.016)    | 0.534 (0.232)    | 0 (0.000) |    18.84 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           26 |      486 | 2024-04-25 | Guild Eagles          | W   | 1.000      | 0.384        | 0.037 (0.014)    | 0.586 (0.225)    | 0 (0.000) |    21.18 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           25 |      539 | 2024-04-24 | MOUZ NXT              | W   | 1.000      | 0.435        | 0.215 (0.094)    | 1.000 (0.435)    | 0 (0.000) |    23.28 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           24 |      646 | 2024-04-21 | Nexus Gaming          | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.772 (0.335)    | 0 (0.000) |    19.26 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           23 |      657 | 2024-04-21 | B8                    | L   | 1.000      | -            | -                | -                | -         |    -9.40 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           22 |      806 | 2024-04-19 | Zero Tenacity         | L   | 1.000      | -            | -                | -                | -         |   -12.23 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           21 |      936 | 2024-04-17 | HAVU Gaming           | W   | 1.000      | 0.500        | 0.024 (0.012)    | 0.213 (0.107)    | 0 (0.000) |    12.74 | ArtFr0st, BELCHONOKK, Jerry, Patsi, Qikert |
|           20 |      947 | 2024-04-17 | Permitta Esports      | L   | 1.000      | -            | -                | -                | -         |   -11.04 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           19 |     1176 | 2024-04-11 | 500                   | L   | 1.000      | -            | -                | -                | -         |   -12.07 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           18 |     1216 | 2024-04-10 | Aurora Gaming         | L   | 1.000      | -            | -                | -                | -         |    -1.00 | ArtFr0st, Jerry, notineki, Patsi, Qikert   |
|           17 |     1283 | 2024-04-09 | RUSH B (Russian team) | L   | 1.000      | -            | -                | -                | -         |   -17.47 | ArtFr0st, Jerry, notineki, Patsi, Qikert   |
|           16 |     1527 | 2024-04-03 | MOUZ NXT              | L   | 0.985      | -            | -                | -                | -         |    -8.71 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           15 |     1579 | 2024-04-02 | AMKAL ESPORTS         | L   | 0.978      | -            | -                | -                | -         |    -6.68 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           14 |     1585 | 2024-04-02 | Insilio               | L   | 0.977      | -            | -                | -                | -         |   -12.39 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           13 |     1603 | 2024-04-01 | Metizport             | W   | 0.971      | 0.384        | 0.188 (0.070)    | 1.000 (0.373)    | 0 (0.000) |    24.44 | ArtFr0st, bl1x1, Jerry, Patsi, Qikert      |
|           12 |     1794 | 2024-03-26 | Betera Esports        | L   | 0.932      | -            | -                | -                | -         |   -15.69 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|           11 |     1987 | 2024-03-21 | FORZE Esports         | W   | 0.898      | 0.500        | 0.210 (0.094)    | 0.574 (0.258)    | 0 (0.000) |    21.96 | ArtFr0st, Jerry, notineki, Patsi, Qikert   |
|           10 |     2626 | 2024-03-06 | En av de lette        | W   | 0.798      | 0.500        | 0.020 (0.008)    | 0.129 (0.051)    | 0 (0.000) |     8.22 | ArtFr0st, Jerry, notineki, Patsi, Qikert   |
|            9 |     2745 | 2024-03-04 | Fnatic                | L   | 0.786      | -            | -                | -                | -         |    -3.12 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            8 |     2848 | 2024-03-02 | KOI                   | L   | 0.772      | -            | -                | -                | -         |    -5.39 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            7 |     2886 | 2024-03-02 | Gaimin Gladiators     | L   | 0.771      | -            | -                | -                | -         |    -1.48 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            6 |     4187 | 2024-01-29 | M1X                   | W   | 0.553      | -            | -                | -                | 0 (0.000) |     3.65 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            5 |     4699 | 2024-01-17 | Insilio               | L   | 0.473      | -            | -                | -                | -         |    -6.41 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            4 |     4707 | 2024-01-17 | Preasy Esport         | W   | 0.473      | 0.143        | 0.106 (0.007)    | -                | -         |     9.58 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            3 |     4726 | 2024-01-17 | TBA.ECF               | W   | 0.472      | 0.143        | -                | 0.460 (0.031)    | -         |     3.23 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            2 |     4794 | 2024-01-16 | EYEBALLERS            | L   | 0.466      | -            | -                | -                | -         |    -5.96 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |
|            1 |     4804 | 2024-01-16 | LODIS                 | W   | 0.465      | -            | -                | -                | -         |     3.39 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($500.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
