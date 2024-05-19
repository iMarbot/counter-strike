### Roster Details<br />
Team Name: GamerLegion Academy<br />
Roster: Darber, Goody, leaf, rud, shadiy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [99](../standings_global.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
Final Rank Value:  864.9<br />
<br />
Final Rank Value (864.9) = Starting Rank Value (876.0) + Head To Head Adjustments (-11.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.422[<sup>1</sup>](#table2)
- Bounty Collected: 0.343[<sup>2</sup>](#table1)
- Opponent Network: 0.194[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 876.0
- 400 + ( ( 0.240 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 876.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           47 |       33 | 2024-05-05 | MOUZ NXT                    | L   | 1.000      | -            | -                | -                | -             |    -9.44 | Darber, Goody, leaf, rud, shadiy |
|           46 |       71 | 2024-05-04 | B8                          | L   | 1.000      | -            | -                | -                | -             |    -9.88 | Darber, Goody, leaf, rud, shadiy |
|           45 |      122 | 2024-05-03 | Preasy Esport               | L   | 1.000      | -            | -                | -                | -             |   -21.61 | cryths, Darber, Goody, leaf, rud |
|           44 |      221 | 2024-05-01 | RUBY                        | W   | 1.000      | 0.435        | 0.012 (0.005)    | 0.882 (0.383)    | false (0.000) |    18.43 | Darber, Goody, leaf, rud, shadiy |
|           43 |      228 | 2024-04-30 | Team Sampi                  | L   | 1.000      | -            | -                | -                | -             |   -11.27 | Darber, Goody, leaf, rud, shadiy |
|           42 |      259 | 2024-04-30 | NOM Esports                 | L   | 1.000      | -            | -                | -                | -             |   -23.81 | cryths, Darber, Goody, leaf, rud |
|           41 |      392 | 2024-04-27 | EXO Clan                    | W   | 1.000      | 0.143        | 0.019 (0.003)    | -                | false (0.000) |    17.05 | Darber, Goody, leaf, rud, sSen   |
|           40 |      441 | 2024-04-26 | JANO Esports                | W   | 1.000      | -            | -                | -                | false (0.000) |     9.45 | Darber, Goody, leaf, rud, sSen   |
|           39 |      450 | 2024-04-26 | EXO Clan                    | W   | 1.000      | 0.333        | 0.019 (0.006)    | 0.418 (0.139)    | false (0.000) |    19.02 | cryths, Darber, Goody, leaf, rud |
|           38 |      596 | 2024-04-22 | JANO Esports                | W   | 1.000      | -            | -                | -                | false (0.000) |    10.46 | Darber, Goody, leaf, rud, sSen   |
|           37 |      820 | 2024-04-19 | RUBY                        | L   | 1.000      | -            | -                | -                | -             |   -11.03 | Darber, Goody, leaf, rud, sSen   |
|           36 |      830 | 2024-04-19 | Insilio                     | W   | 1.000      | 0.371        | 0.020 (0.007)    | 0.875 (0.325)    | false (0.000) |    19.75 | Darber, Goody, leaf, rud, sSen   |
|           35 |     1245 | 2024-04-10 | Illuminar Gaming            | L   | 1.000      | -            | -                | -                | -             |   -17.12 | Darber, Goody, leaf, msN, rud    |
|           34 |     1354 | 2024-04-08 | Johnny Speeds               | L   | 1.000      | -            | -                | -                | -             |   -15.01 | Darber, Goody, leaf, msN, rud    |
|           33 |     1408 | 2024-04-06 | DMS                         | L   | 1.000      | -            | -                | -                | -             |   -22.28 | Darber, Goody, leaf, msN, rud    |
|           32 |     1507 | 2024-04-04 | Sashi Esport                | W   | 0.989      | 0.333        | 0.055 (0.018)    | 0.256 (0.084)    | false (0.000) |    10.55 | Darber, Goody, leaf, msN, rud    |
|           31 |     1643 | 2024-03-30 | Natus Vincere Junior        | W   | 0.957      | 0.333        | 0.025 (0.008)    | 0.492 (0.157)    | false (0.000) |    15.92 | Darber, Goody, leaf, nestee, rud |
|           30 |     1704 | 2024-03-28 | Passion UA                  | W   | 0.944      | 0.333        | 0.114 (0.036)    | 0.980 (0.308)    | false (0.000) |    18.80 | Darber, Goody, leaf, nestee, rud |
|           29 |     1832 | 2024-03-26 | Sashi Esport                | W   | 0.930      | 0.333        | 0.055 (0.017)    | 0.256 (0.079)    | false (0.000) |    11.86 | Darber, Goody, leaf, nestee, rud |
|           28 |     1868 | 2024-03-24 | Permitta Esports            | W   | 0.916      | 0.333        | 0.063 (0.019)    | 1.000 (0.305)    | -             |    20.11 | Darber, Goody, leaf, nestee, rud |
|           27 |     2072 | 2024-03-19 | Viperio                     | W   | 0.883      | 0.333        | -                | 0.321 (0.095)    | -             |     8.24 | Darber, Goody, leaf, nestee, rud |
|           26 |     2227 | 2024-03-15 | ROSOMAHA                    | W   | 0.857      | -            | -                | -                | -             |     5.99 | Darber, Goody, leaf, nestee, rud |
|           25 |     2500 | 2024-03-09 | BLESSED (Ukrainian team)    | L   | 0.818      | -            | -                | -                | -             |   -10.47 | Darber, Goody, leaf, nestee, rud |
|           24 |     2533 | 2024-03-08 | AVEZ                        | W   | 0.811      | -            | -                | -                | -             |     7.34 | Darber, Goody, leaf, nestee, rud |
|           23 |     2572 | 2024-03-07 | BRUTE                       | W   | 0.805      | -            | -                | -                | -             |     4.40 | Darber, Goody, leaf, nestee, rud |
|           22 |     2631 | 2024-03-06 | SINNERS Academy             | W   | 0.797      | 0.289        | -                | 0.296 (0.068)    | -             |     7.66 | Darber, Goody, leaf, nestee, rud |
|           21 |     2764 | 2024-03-04 | Begrip Gaming               | W   | 0.784      | -            | -                | -                | -             |     7.18 | Darber, Goody, leaf, nestee, rud |
|           20 |     2855 | 2024-03-02 | ARCRED                      | L   | 0.772      | -            | -                | -                | -             |   -11.30 | Darber, Goody, leaf, nestee, rud |
|           19 |     2937 | 2024-02-29 | Ex-KRC Genk Esports         | W   | 0.759      | 0.371        | 0.008 (0.002)    | -                | -             |     9.89 | aNdu, Darber, leaf, nestee, rud  |
|           18 |     2949 | 2024-02-29 | 0to100                      | W   | 0.758      | -            | -                | -                | -             |     2.07 | aNdu, Darber, leaf, nestee, rud  |
|           17 |     3288 | 2024-02-21 | Lajtbitexe                  | W   | 0.706      | -            | -                | -                | -             |     4.15 | aNdu, Darber, leaf, nestee, rud  |
|           16 |     3415 | 2024-02-19 | UNiTY esports (Slovak team) | L   | 0.691      | -            | -                | -                | -             |    -7.43 | aNdu, Darber, leaf, nestee, rud  |
|           15 |     3580 | 2024-02-15 | BAKS Esports                | W   | 0.665      | -            | -                | -                | -             |     6.20 | Darber, Goody, leaf, nestee, rud |
|           14 |     3592 | 2024-02-15 | K10                         | L   | 0.664      | -            | -                | -                | -             |    -9.68 | Darber, Goody, leaf, nestee, rud |
|           13 |     3793 | 2024-02-09 | Kappa Bar                   | L   | 0.625      | -            | -                | -                | -             |   -13.75 | Darber, leaf, nestee, rud, Trax  |
|           12 |     3825 | 2024-02-08 | Rhyno Esports               | L   | 0.618      | -            | -                | -                | -             |    -7.38 | aNdu, Darber, leaf, nestee, rud  |
|           11 |     4072 | 2024-02-01 | DASH                        | L   | 0.572      | -            | -                | -                | -             |   -12.28 | aNdu, Darber, leaf, nestee, rud  |
|           10 |     4109 | 2024-01-31 | RUBY                        | L   | 0.565      | -            | -                | -                | -             |    -7.72 | aNdu, Darber, leaf, nestee, rud  |
|            9 |     4319 | 2024-01-26 | Nexus Gaming                | L   | 0.531      | -            | -                | -                | -             |    -6.24 | aNdu, Darber, leaf, nestee, rud  |
|            8 |     4355 | 2024-01-25 | Natus Vincere Youth         | L   | 0.525      | -            | -                | -                | -             |   -11.26 | aNdu, Darber, leaf, nestee, rud  |
|            7 |     5725 | 2023-12-10 | Sashi Esport                | L   | 0.218      | -            | -                | -                | -             |    -4.77 | aNdu, Darber, leaf, nestee, rud  |
|            6 |     5832 | 2023-12-08 | Monte Gen                   | L   | 0.205      | -            | -                | -                | -             |    -3.91 | aNdu, Darber, leaf, nestee, rud  |
|            5 |     5925 | 2023-12-06 | Nexus Gaming                | L   | 0.192      | -            | -                | -                | -             |    -2.51 | aNdu, Darber, leaf, nestee, rud  |
|            4 |     5939 | 2023-12-06 | Begrip Gaming               | W   | 0.191      | -            | -                | -                | -             |     1.28 | aNdu, Darber, leaf, nestee, rud  |
|            3 |     6016 | 2023-12-04 | FALKE ESPORTS               | W   | 0.179      | -            | -                | -                | -             |     0.61 | aNdu, Darber, leaf, nestee, rud  |
|            2 |     6116 | 2023-12-02 | Preasy Esport               | W   | 0.164      | -            | -                | -                | -             |     2.21 | aNdu, Darber, leaf, nestee, rud  |
|            1 |     6251 | 2023-11-29 | Team 7AM                    | W   | 0.145      | -            | -                | -                | -             |     0.47 | aNdu, Darber, leaf, nestee, rud  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,764.35)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-30 |      0.957 | $6,000.00      | $5,741.39       |
| 2024-03-09 |      0.818 | $1,000.00      | $817.73         |
| 2023-12-08 |      0.205 | $1,000.00      | $205.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
