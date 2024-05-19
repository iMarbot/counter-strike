### Roster Details<br />
Team Name: The Chosen Few<br />
Roster: choiv7, KalubeR, shaiK, Skrimo, SPELLAN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [95](../standings_global.md)<br />
Regional Rank: [70]( ../standings_europe.md)<br />
Final Rank Value:  869.8<br />
<br />
Final Rank Value (869.8) = Starting Rank Value (812.9) + Head To Head Adjustments (56.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.335[<sup>2</sup>](#table1)
- Opponent Network: 0.182[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.208<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 812.9
- 400 + ( ( 0.208 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 812.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |     2222 | 2024-03-15 | Permitta Esports         | L   | 0.857      | -            | -                | -                | -             |    -9.01 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           45 |     2269 | 2024-03-14 | Endpoint                 | W   | 0.852      | 0.371        | -                | 0.785 (0.248)    | false (0.000) |    13.28 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           44 |     2374 | 2024-03-12 | ARCRED                   | W   | 0.838      | 0.371        | -                | 0.825 (0.257)    | false (0.000) |    12.42 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           43 |     2499 | 2024-03-09 | Passion UA               | W   | 0.818      | 0.371        | 0.114 (0.035)    | 0.980 (0.298)    | false (0.000) |    16.13 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           42 |     2619 | 2024-03-06 | Insilio                  | L   | 0.799      | -            | -                | -                | -             |    -8.01 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           41 |     2783 | 2024-03-03 | Metizport                | L   | 0.779      | -            | -                | -                | -             |    -4.78 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           40 |     2789 | 2024-03-03 | TSM                      | W   | 0.779      | -            | -                | -                | false (0.000) |     8.89 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           39 |     2797 | 2024-03-03 | KOI                      | W   | 0.778      | 0.143        | 0.066 (0.007)    | -                | false (0.000) |    20.05 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           38 |     2825 | 2024-03-02 | Lilmix                   | W   | 0.773      | -            | -                | -                | false (0.000) |     6.83 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           37 |     2854 | 2024-03-02 | Sashi Esport             | W   | 0.772      | 0.143        | 0.193 (0.021)    | 1.000 (0.110)    | false (0.000) |    19.75 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           36 |     2917 | 2024-03-01 | BLESSED (Ukrainian team) | L   | 0.765      | -            | -                | -                | -             |   -10.10 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           35 |     2951 | 2024-02-29 | Verdant                  | W   | 0.758      | 0.371        | 0.027 (0.008)    | 0.662 (0.186)    | false (0.000) |    15.64 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           34 |     3036 | 2024-02-27 | VP.Prodigy               | L   | 0.744      | -            | -                | -                | -             |   -10.42 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           33 |     3172 | 2024-02-24 | Illuminar Gaming         | L   | 0.724      | -            | -                | -                | -             |   -12.00 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           32 |     3209 | 2024-02-23 | DASH                     | L   | 0.719      | -            | -                | -                | -             |   -13.61 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           31 |     3214 | 2024-02-23 | Aurora Young Blud        | W   | 0.718      | 0.371        | 0.017 (0.005)    | 0.422 (0.113)    | false (0.000) |    10.79 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           30 |     3245 | 2024-02-22 | Ex-Anonymo Esports       | W   | 0.712      | 0.371        | 0.019 (0.005)    | 0.295 (0.078)    | false (0.000) |     9.96 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           29 |     3257 | 2024-02-22 | Permitta Esports         | W   | 0.711      | 0.371        | 0.063 (0.017)    | 1.000 (0.264)    | -             |    17.26 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           28 |     3483 | 2024-02-17 | Entropiq                 | L   | 0.679      | -            | -                | -                | -             |   -11.02 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           27 |     3500 | 2024-02-17 | Monte                    | L   | 0.677      | -            | -                | -                | -             |    -0.78 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           26 |     3536 | 2024-02-16 | GenOne                   | L   | 0.671      | -            | -                | -                | -             |   -16.31 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           25 |     3629 | 2024-02-14 | HOTU                     | W   | 0.658      | 0.371        | 0.011 (0.003)    | 0.323 (0.079)    | -             |     9.82 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           24 |     3725 | 2024-02-12 | Endpoint                 | W   | 0.645      | 0.371        | -                | 0.785 (0.188)    | -             |    11.93 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           23 |     3817 | 2024-02-08 | Team Spirit Academy      | L   | 0.619      | -            | -                | -                | -             |    -8.92 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           22 |     3922 | 2024-02-04 | AIRLYA                   | W   | 0.591      | -            | -                | -                | -             |     4.14 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           21 |     3944 | 2024-02-03 | Zero Tenacity            | L   | 0.586      | -            | -                | -                | -             |    -5.58 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           20 |     4022 | 2024-02-02 | Natus Vincere Junior     | W   | 0.578      | 0.143        | 0.025 (0.002)    | -                | -             |     9.95 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           19 |     4033 | 2024-02-02 | Jake Bube                | W   | 0.578      | -            | -                | -                | -             |     3.27 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           18 |     4048 | 2024-02-02 | Natus Vincere Junior     | L   | 0.577      | -            | -                | -                | -             |    -8.16 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           17 |     4101 | 2024-01-31 | Soda Gaming              | W   | 0.566      | 0.371        | 0.009 (0.002)    | -                | -             |     7.97 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           16 |     4158 | 2024-01-29 | RUBY                     | L   | 0.553      | -            | -                | -                | -             |    -6.80 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           15 |     4172 | 2024-01-29 | HAVU Gaming              | W   | 0.553      | -            | -                | -                | -             |    10.72 | choiv7, KalubeR, shaiK, Skrimo, SPELLAN |
|           14 |     4721 | 2024-01-17 | Soda Gaming              | L   | 0.472      | -            | -                | -                | -             |    -8.09 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|           13 |     4802 | 2024-01-16 | Nexus Gaming             | L   | 0.465      | -            | -                | -                | -             |    -5.14 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|           12 |     4943 | 2024-01-12 | 500                      | L   | 0.439      | -            | -                | -                | -             |    -7.17 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|           11 |     5357 | 2023-12-17 | WinX                     | W   | 0.265      | -            | -                | -                | -             |     2.05 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|           10 |     5368 | 2023-12-17 | Gr Infractional          | W   | 0.264      | -            | -                | -                | -             |     1.37 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            9 |     6096 | 2023-12-02 | 4ERNOTA                  | L   | 0.165      | -            | -                | -                | -             |    -4.45 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            8 |     6158 | 2023-12-01 | POLET                    | W   | 0.159      | -            | -                | -                | -             |     0.72 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            7 |     6166 | 2023-12-01 | Lemondogs                | L   | 0.158      | -            | -                | -                | -             |    -3.92 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            6 |     6484 | 2023-11-24 | L&G                      | L   | 0.111      | -            | -                | -                | -             |    -2.87 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            5 |     6508 | 2023-11-23 | Viperio                  | W   | 0.105      | -            | -                | -                | -             |     0.81 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            4 |     6561 | 2023-11-22 | BAKS Esports             | W   | 0.098      | -            | -                | -                | -             |     0.91 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            3 |     6714 | 2023-11-18 | Hatred                   | L   | 0.072      | -            | -                | -                | -             |    -1.78 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            2 |     6765 | 2023-11-17 | K10                      | W   | 0.066      | -            | -                | -                | -             |     1.26 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |
|            1 |     7168 | 2023-11-08 | Lajtbitexe               | L   | 0.006      | -            | -                | -                | -             |    -0.14 | hybrid, Libido, shaiK, Skrimo, SPELLAN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,066.90)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-25 |      0.925 | $750.00        | $693.51         |
| 2023-12-17 |      0.265 | $1,394.51      | $369.48         |
| 2023-11-18 |      0.072 | $54.58         | $3.91           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
