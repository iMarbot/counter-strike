### Roster Details<br />
Team Name: Pera Esports<br />
Roster: Aaron, bibu, Ciocardau, DGL, Porya<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [78](../standings_global.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
Final Rank Value:  900.9<br />
<br />
Final Rank Value (900.9) = Starting Rank Value (922.5) + Head To Head Adjustments (-21.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.458[<sup>1</sup>](#table2)
- Bounty Collected: 0.388[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.263<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 922.5
- 400 + ( ( 0.263 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 922.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |       77 | 2024-05-04 | FlyQuest                     | L   | 1.000      | -            | -                | -                | -         |    -1.76 | Aaron, bibu, Ciocardau, DGL, Porya |
|           43 |      119 | 2024-05-03 | BIG                          | L   | 1.000      | -            | -                | -                | -         |    -2.03 | Aaron, bibu, Ciocardau, DGL, Porya |
|           42 |      150 | 2024-05-02 | Ninjas in Pyjamas            | W   | 1.000      | 0.889        | 0.241 (0.215)    | 0.376 (0.334)    | 1 (1.000) |    25.38 | Aaron, bibu, Ciocardau, DGL, Porya |
|           41 |      242 | 2024-04-30 | Complexity Gaming            | L   | 1.000      | -            | -                | -                | -         |    -0.94 | Aaron, bibu, Ciocardau, DGL, Porya |
|           40 |      701 | 2024-04-20 | EYEBALLERS                   | L   | 1.000      | -            | -                | -                | -         |   -14.32 | Aaron, bibu, DGL, kory, Porya      |
|           39 |     1539 | 2024-04-03 | SAW                          | L   | 0.984      | -            | -                | -                | -         |    -1.23 | Aaron, bibu, DGL, kory, Porya      |
|           38 |     1602 | 2024-04-01 | RUSH B (Russian team)        | W   | 0.971      | 0.500        | 0.006 (0.003)    | 0.471 (0.229)    | 0 (0.000) |    12.65 | Aaron, bibu, DGL, kory, Porya      |
|           37 |     1757 | 2024-03-27 | Sashi Esport                 | L   | 0.938      | -            | -                | -                | -         |    -8.22 | Aaron, DGL, HS, Porya, pr1metapz   |
|           36 |     1816 | 2024-03-26 | The glecs                    | W   | 0.932      | -            | -                | -                | 0 (0.000) |     1.76 | Aaron, DGL, HS, Porya, pr1metapz   |
|           35 |     2220 | 2024-03-15 | Betera Esports               | L   | 0.858      | -            | -                | -                | -         |   -15.24 | Aaron, DGL, kory, msN, Porya       |
|           34 |     2722 | 2024-03-04 | Insilio                      | L   | 0.786      | -            | -                | -                | -         |   -10.15 | Aaron, DGL, Kamion, msN, Porya     |
|           33 |     2731 | 2024-03-04 | IMMAPROBLEM                  | W   | 0.786      | -            | -                | -                | 0 (0.000) |     2.72 | Aaron, DGL, Kamion, msN, Porya     |
|           32 |     2859 | 2024-03-02 | Balkan Bears (Romanian team) | L   | 0.772      | -            | -                | -                | -         |   -21.94 | Aaron, DGL, Kamion, msN, Porya     |
|           31 |     3069 | 2024-02-26 | System5                      | L   | 0.739      | -            | -                | -                | -         |   -20.93 | Aaron, DGL, kory, msN, Porya       |
|           30 |     3352 | 2024-02-20 | Preasy Esport                | L   | 0.698      | -            | -                | -                | -         |    -9.81 | Aaron, DGL, Kamion, msN, Porya     |
|           29 |     3412 | 2024-02-19 | GamerLegion                  | L   | 0.691      | -            | -                | -                | -         |    -0.66 | Aaron, DGL, Kamion, msN, Porya     |
|           28 |     3419 | 2024-02-19 | Cloud9                       | L   | 0.691      | -            | -                | -                | -         |    -0.28 | Aaron, DGL, Kamion, msN, Porya     |
|           27 |     3527 | 2024-02-16 | SINNERS Esports              | L   | 0.672      | -            | -                | -                | -         |   -10.61 | Aaron, DGL, Kamion, msN, Porya     |
|           26 |     4350 | 2024-01-25 | Guild Eagles                 | W   | 0.526      | 0.143        | 0.037 (0.003)    | 0.586 (0.044)    | 0 (0.000) |    10.85 | Aaron, DGL, Kamion, msN, Porya     |
|           25 |     4374 | 2024-01-24 | Viperio                      | W   | 0.519      | -            | -                | -                | 0 (0.000) |     2.04 | Aaron, DGL, Kamion, msN, Porya     |
|           24 |     4428 | 2024-01-23 | ALTERNATE aTTaX              | W   | 0.512      | 0.143        | 0.110 (0.008)    | 0.723 (0.053)    | 0 (0.000) |    10.18 | Aaron, DGL, Kamion, msN, Porya     |
|           23 |     4432 | 2024-01-23 | Rebels Gaming                | W   | 0.511      | 0.143        | 0.121 (0.009)    | -                | 0 (0.000) |    12.00 | Aaron, DGL, Kamion, msN, Porya     |
|           22 |     4454 | 2024-01-22 | Guild Eagles                 | W   | 0.506      | 0.143        | 0.037 (0.003)    | 0.586 (0.042)    | 0 (0.000) |    10.91 | Aaron, DGL, Kamion, msN, Porya     |
|           21 |     4466 | 2024-01-22 | Team Sampi                   | L   | 0.505      | -            | -                | -                | -         |    -5.93 | Aaron, DGL, Kamion, msN, Porya     |
|           20 |     4473 | 2024-01-22 | Viperio                      | W   | 0.505      | -            | -                | -                | 0 (0.000) |     2.02 | Aaron, DGL, Kamion, msN, Porya     |
|           19 |     4506 | 2024-01-21 | Gaimin Gladiators            | L   | 0.497      | -            | -                | -                | -         |    -1.13 | Aaron, DGL, Kamion, msN, Porya     |
|           18 |     4539 | 2024-01-20 | KOI                          | L   | 0.492      | -            | -                | -                | -         |    -4.84 | Aaron, DGL, Kamion, msN, Porya     |
|           17 |     4557 | 2024-01-20 | Astralis                     | L   | 0.491      | -            | -                | -                | -         |    -0.56 | Aaron, DGL, Kamion, msN, Porya     |
|           16 |     4611 | 2024-01-19 | IKLA                         | W   | 0.484      | -            | -                | -                | -         |     4.04 | Aaron, DGL, Kamion, msN, Porya     |
|           15 |     4649 | 2024-01-18 | EYEBALLERS                   | W   | 0.479      | 0.143        | 0.051 (0.004)    | 0.533 (0.036)    | -         |     8.12 | Aaron, DGL, Kamion, msN, Porya     |
|           14 |     4672 | 2024-01-18 | Eternal Fire                 | L   | 0.478      | -            | -                | -                | -         |    -0.12 | Aaron, DGL, Kamion, msN, Porya     |
|           13 |     4981 | 2024-01-11 | IKLA                         | L   | 0.433      | -            | -                | -                | -         |   -10.34 | Aaron, DGL, Kamion, msN, Porya     |
|           12 |     4988 | 2024-01-11 | SINNERS Esports              | L   | 0.432      | -            | -                | -                | -         |    -5.76 | Aaron, DGL, Kamion, msN, Porya     |
|           11 |     4998 | 2024-01-11 | Ex-Anonymo Esports           | W   | 0.431      | 0.143        | 0.019 (0.001)    | -                | -         |     4.19 | Aaron, DGL, Kamion, msN, Porya     |
|           10 |     5006 | 2024-01-11 | Permitta Esports             | W   | 0.431      | 0.143        | 0.063 (0.004)    | 1.000 (0.062)    | -         |     8.00 | Aaron, DGL, Kamion, msN, Porya     |
|            9 |     5040 | 2024-01-10 | EsmagaB                      | W   | 0.426      | 0.143        | -                | 0.559 (0.034)    | -         |     5.61 | Aaron, DGL, Kamion, msN, Porya     |
|            8 |     5095 | 2024-01-09 | Sashi Esport                 | L   | 0.418      | -            | -                | -                | -         |    -4.10 | Aaron, DGL, Kamion, msN, Porya     |
|            7 |     5304 | 2023-12-20 | Metizport                    | W   | 0.285      | 0.333        | 0.188 (0.018)    | 1.000 (0.095)    | -         |     5.59 | Aaron, DGL, Kamion, msN, Porya     |
|            6 |     5314 | 2023-12-19 | GUN5 Esports                 | W   | 0.278      | -            | -                | -                | -         |     1.55 | Aaron, DGL, Kamion, msN, Porya     |
|            5 |     5317 | 2023-12-19 | Soda Gaming                  | W   | 0.277      | -            | -                | -                | -         |     2.55 | Aaron, DGL, Kamion, msN, Porya     |
|            4 |     5319 | 2023-12-19 | Metizport                    | L   | 0.277      | -            | -                | -                | -         |    -3.33 | Aaron, DGL, Kamion, msN, Porya     |
|            3 |     6045 | 2023-12-03 | Molotov Gaming               | W   | 0.171      | -            | -                | -                | -         |     0.27 | Aaron, DGL, Kamion, msN, Porya     |
|            2 |     6583 | 2023-11-21 | Endpoint                     | W   | 0.092      | 0.384        | -                | 0.785 (0.028)    | -         |     1.16 | Aaron, DGL, Kamion, msN, Porya     |
|            1 |     6603 | 2023-11-21 | GODSENT                      | W   | 0.091      | -            | -                | -                | -         |     0.96 | Aaron, DGL, Kamion, msN, Porya     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,373.66)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2023-12-20 |      0.285 | $8,000.00      | $2,279.63       |
| 2023-12-03 |      0.171 | $1,000.00      | $170.88         |
| 2023-11-21 |      0.092 | $10,000.00     | $923.15         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
