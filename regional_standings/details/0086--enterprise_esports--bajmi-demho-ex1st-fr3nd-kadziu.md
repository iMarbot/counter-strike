### Roster Details<br />
Team Name: ENTERPRISE esports<br />
Roster: bajmi, Demho, Ex1st, fr3nd, kadziu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [86](../standings_global.md)<br />
Regional Rank: [64]( ../standings_europe.md)<br />
Final Rank Value:  885.1<br />
<br />
Final Rank Value (885.1) = Starting Rank Value (955.7) + Head To Head Adjustments (-70.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.416[<sup>1</sup>](#table2)
- Bounty Collected: 0.404[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.092[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 955.7
- 400 + ( ( 0.280 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 955.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           59 |       44 | 2024-05-04 | MOUZ NXT                 | W   | 1.000      | 0.435        | 0.215 (0.094)    | 1.000 (0.435)    | 0 (0.000) |    22.15 | bajmi, Demho, Ex1st, fr3nd, kadziu          |
|           58 |      185 | 2024-05-01 | ENCE Academy             | W   | 1.000      | 0.435        | 0.028 (0.012)    | 0.267 (0.116)    | 0 (0.000) |    12.16 | bajmi, Demho, Ex1st, fr3nd, kadziu          |
|           57 |      240 | 2024-04-30 | EYEBALLERS               | L   | 1.000      | -            | -                | -                | -         |   -12.20 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           56 |      293 | 2024-04-29 | Nexus Gaming             | L   | 1.000      | -            | -                | -                | -         |   -13.49 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           55 |      390 | 2024-04-27 | Permitta Esports         | L   | 1.000      | -            | -                | -                | -         |   -14.43 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           54 |      439 | 2024-04-26 | Insilio                  | L   | 1.000      | -            | -                | -                | -         |   -12.99 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           53 |      592 | 2024-04-23 | ALTERNATE aTTaX          | L   | 1.000      | -            | -                | -                | -         |   -16.20 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           52 |      640 | 2024-04-21 | ThunderFlash             | L   | 1.000      | -            | -                | -                | -         |   -20.41 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           51 |      711 | 2024-04-20 | Permitta Esports         | W   | 1.000      | 0.143        | 0.063 (0.009)    | 1.000 (0.143)    | 0 (0.000) |    15.37 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           50 |      775 | 2024-04-20 | ALTERNATE aTTaX          | L   | 1.000      | -            | -                | -                | -         |   -15.88 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           49 |      823 | 2024-04-19 | 9INE Academy             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.79 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           48 |      885 | 2024-04-18 | MOUZ NXT                 | L   | 1.000      | -            | -                | -                | -         |   -10.14 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           47 |      901 | 2024-04-18 | Nexus Gaming             | W   | 1.000      | 0.384        | 0.031 (0.012)    | 0.772 (0.297)    | 0 (0.000) |    15.68 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           46 |      952 | 2024-04-17 | ENCE                     | L   | 1.000      | -            | -                | -                | -         |    -1.73 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           45 |     1250 | 2024-04-10 | AMKAL ESPORTS            | W   | 1.000      | 0.384        | 0.209 (0.080)    | 0.756 (0.291)    | 0 (0.000) |    24.39 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           44 |     1417 | 2024-04-06 | Team Sampi               | L   | 1.000      | -            | -                | -                | -         |   -10.69 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           43 |     1536 | 2024-04-03 | Permitta Esports         | W   | 0.985      | 0.384        | 0.063 (0.024)    | 1.000 (0.378)    | 0 (0.000) |    15.50 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           42 |     1807 | 2024-03-26 | Heimo Esports            | L   | 0.932      | -            | -                | -                | -         |   -21.57 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           41 |     1936 | 2024-03-22 | ThunderFlash             | W   | 0.905      | -            | -                | -                | 0 (0.000) |     8.74 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           40 |     1966 | 2024-03-21 | Illuminar Gaming         | L   | 0.899      | -            | -                | -                | -         |   -18.00 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           39 |     2027 | 2024-03-20 | Turów Zgorzelec Esport   | W   | 0.891      | 0.143        | -                | 0.640 (0.081)    | -         |     8.45 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           38 |     2060 | 2024-03-19 | LODIS                    | W   | 0.885      | -            | -                | -                | -         |     4.17 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           37 |     2082 | 2024-03-18 | Mikstura1234             | W   | 0.879      | -            | -                | -                | -         |     5.44 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           36 |     2517 | 2024-03-09 | Team Sampi               | L   | 0.817      | -            | -                | -                | -         |   -10.71 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           35 |     2627 | 2024-03-06 | INGLORIOUS               | L   | 0.798      | -            | -                | -                | -         |   -16.19 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           34 |     2649 | 2024-03-06 | Permitta Esports         | L   | 0.797      | -            | -                | -                | -         |   -11.31 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           33 |     2732 | 2024-03-04 | Nemiga Gaming            | L   | 0.786      | -            | -                | -                | -         |    -2.85 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           32 |     2748 | 2024-03-04 | Turów Zgorzelec Esport   | W   | 0.786      | 0.143        | -                | 0.640 (0.072)    | -         |     8.09 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           31 |     2858 | 2024-03-02 | Sashi Esport             | W   | 0.772      | 0.143        | 0.055 (0.006)    | -                | -         |     7.10 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           30 |     2902 | 2024-03-02 | Team Sampi               | W   | 0.769      | 0.371        | 0.108 (0.031)    | 0.709 (0.202)    | -         |    14.03 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           29 |     2979 | 2024-02-28 | BLESSED (Ukrainian team) | L   | 0.752      | -            | -                | -                | -         |   -15.11 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           28 |     2988 | 2024-02-28 | RUBY                     | L   | 0.752      | -            | -                | -                | -         |   -12.54 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           27 |     3024 | 2024-02-27 | Eternal Fire Academy     | W   | 0.745      | -            | -                | -                | -         |     4.52 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           26 |     3098 | 2024-02-25 | DASH                     | W   | 0.732      | -            | -                | -                | -         |     5.61 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           25 |     3525 | 2024-02-16 | SAW                      | L   | 0.672      | -            | -                | -                | -         |    -1.24 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           24 |     3598 | 2024-02-15 | BetBoom Team             | L   | 0.664      | -            | -                | -                | -         |    -1.13 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           23 |     3616 | 2024-02-14 | Natus Vincere            | L   | 0.659      | -            | -                | -                | -         |    -0.08 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           22 |     3639 | 2024-02-14 | AMKAL ESPORTS            | W   | 0.657      | 0.143        | 0.209 (0.020)    | 0.756 (0.071)    | 1 (0.657) |    17.20 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           21 |     3790 | 2024-02-09 | HOTU                     | L   | 0.625      | -            | -                | -                | -         |   -13.95 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           20 |     3919 | 2024-02-04 | Team Spirit Academy      | L   | 0.592      | -            | -                | -                | -         |   -12.65 | bajmi, Demho, Ex1st, fr3nd, TOAO            |
|           19 |     5924 | 2023-12-06 | Nemiga Gaming            | W   | 0.192      | 0.371        | 0.680 (0.049)    | -                | -         |     5.35 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|           18 |     5975 | 2023-12-05 | Endpoint                 | L   | 0.186      | -            | -                | -                | -         |    -3.75 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|           17 |     6092 | 2023-12-02 | Turów Zgorzelec Esport   | W   | 0.166      | -            | -                | -                | 1 (0.166) |     1.70 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|           16 |     6201 | 2023-11-30 | The Witchers             | L   | 0.152      | -            | -                | -                | -         |    -3.44 | fear, Sdaim, smooya, soulfly, synyx         |
|           15 |     6302 | 2023-11-28 | Lajtbitexe               | W   | 0.139      | -            | -                | -                | -         |     0.42 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|           14 |     6431 | 2023-11-25 | Rebels Gaming            | L   | 0.118      | -            | -                | -                | -         |    -0.84 | Flayy, kisserek, moonwalk, olimp, sNx       |
|           13 |     6516 | 2023-11-23 | GenOne                   | W   | 0.105      | -            | -                | -                | -         |     0.45 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig    |
|           12 |     6563 | 2023-11-22 | Ex-Anonymo Esports       | W   | 0.098      | -            | -                | -                | -         |     0.81 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|           11 |     6628 | 2023-11-20 | KOMNATA                  | W   | 0.085      | -            | -                | -                | -         |     0.12 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|           10 |     6665 | 2023-11-19 | Illuminar Gaming         | W   | 0.078      | -            | -                | -                | -         |     0.61 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|            9 |     6705 | 2023-11-18 | AGO esports              | W   | 0.072      | -            | -                | -                | -         |     0.35 | delle, Dementor, DEPRESHN, Svedjehed, tAk   |
|            8 |     6772 | 2023-11-17 | Lilmix                   | W   | 0.065      | -            | -                | -                | -         |     0.42 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|            7 |     6826 | 2023-11-16 | PACT                     | W   | 0.058      | -            | -                | -                | -         |     0.16 | blacktear5, jedqr, m4tthi, snatchie, SZPERO |
|            6 |     6870 | 2023-11-15 | Illuminar Gaming         | L   | 0.052      | -            | -                | -                | -         |    -1.23 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|            5 |     6921 | 2023-11-14 | AGO esports              | W   | 0.045      | -            | -                | -                | -         |     0.22 | delle, Dementor, DEPRESHN, Svedjehed, tAk   |
|            4 |     6959 | 2023-11-13 | EHawks                   | L   | 0.039      | -            | -                | -                | -         |    -1.12 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|            3 |     6976 | 2023-11-13 | Los Alpacas              | W   | 0.038      | -            | -                | -                | -         |     0.17 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|            2 |     7086 | 2023-11-10 | Lemondogs                | W   | 0.019      | -            | -                | -                | -         |     0.06 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |
|            1 |     7189 | 2023-11-08 | JESTE                    | W   | 0.005      | -            | -                | -                | -         |     0.01 | bajmi, Demho, Ex1st, fr3nd, Klameczka       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,244.25)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $500.00        | $500.00         |
| 2024-04-21 |      1.000 | $2,464.60      | $2,464.60       |
| 2023-12-02 |      0.166 | $18,872.57     | $3,123.59       |
| 2023-11-26 |      0.125 | $1,251.71      | $156.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
