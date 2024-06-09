### Roster Details<br />
Team Name: Rebels Gaming<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [53](../standings_global.md)<br />
Regional Rank: [37]( ../standings_europe.md)<br />
Final Rank Value:  1042.4<br />
<br />
Final Rank Value (1042.4) = Starting Rank Value (1127.2) + Head To Head Adjustments (-84.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.440[<sup>2</sup>](#table1)
- Opponent Network: 0.245[<sup>2</sup>](#table1)
- LAN Wins: 0.293[<sup>2</sup>](#table1)

The average of these factors is 0.358<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1127.2
- 400 + ( ( 0.358 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1127.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |       96 | 2024-05-29 | UNiTY esports     | L   | 1.000      | -            | -                | -                | -         |   -24.10 | casey, Flayy, innocent, kisserek, olimp |
|           48 |      323 | 2024-05-25 | kONO.ECF          | W   | 1.000      | 0.371        | -                | 0.853 (0.316)    | 0 (0.000) |     7.78 | casey, Flayy, innocent, kisserek, olimp |
|           47 |      637 | 2024-05-21 | UNiTY esports     | L   | 1.000      | -            | -                | -                | -         |   -24.59 | casey, Flayy, innocent, kisserek, olimp |
|           46 |      690 | 2024-05-20 | The Prodigies     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.17 | casey, Flayy, innocent, kisserek, olimp |
|           45 |      938 | 2024-05-18 | B8                | L   | 1.000      | -            | -                | -                | -         |   -13.14 | casey, Flayy, innocent, kisserek, olimp |
|           44 |     1010 | 2024-05-17 | Gaimin Gladiators | W   | 1.000      | 0.384        | 0.092 (0.035)    | 0.727 (0.279)    | 0 (0.000) |    19.15 | casey, Flayy, innocent, kisserek, olimp |
|           43 |     1384 | 2024-05-12 | Permitta Esports  | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |     8.46 | casey, Flayy, innocent, kisserek, olimp |
|           42 |     1406 | 2024-05-12 | pasztetuwa        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.48 | casey, Flayy, innocent, kisserek, olimp |
|           41 |     1470 | 2024-05-11 | GenOne            | L   | 1.000      | -            | -                | -                | -         |   -28.26 | casey, Flayy, innocent, kisserek, olimp |
|           40 |     2170 | 2024-04-27 | Aurora Gaming     | L   | 0.987      | -            | -                | -                | -         |    -5.31 | casey, Flayy, innocent, kisserek, olimp |
|           39 |     2325 | 2024-04-25 | MIBR              | W   | 0.974      | 0.500        | 0.307 (0.150)    | 0.531 (0.258)    | 1 (0.974) |    28.84 | casey, Flayy, innocent, kisserek, olimp |
|           38 |     2327 | 2024-04-25 | Rooster           | W   | 0.973      | 0.500        | 0.014 (0.007)    | 0.229 (0.112)    | 1 (0.973) |     6.46 | casey, Flayy, innocent, kisserek, olimp |
|           37 |     2739 | 2024-04-19 | brazylijski luz   | L   | 0.931      | -            | -                | -                | -         |   -22.77 | casey, Flayy, innocent, kisserek, olimp |
|           36 |     2880 | 2024-04-17 | EYEBALLERS        | L   | 0.918      | -            | -                | -                | -         |   -21.79 | casey, Flayy, innocent, kisserek, olimp |
|           35 |     3097 | 2024-04-13 | Monte             | L   | 0.890      | -            | -                | -                | -         |    -9.03 | casey, Flayy, innocent, kisserek, olimp |
|           34 |     3314 | 2024-04-09 | B8                | W   | 0.864      | 0.500        | 0.168 (0.073)    | 0.963 (0.416)    | 0 (0.000) |    14.05 | casey, Flayy, innocent, kisserek, olimp |
|           33 |     3590 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.830      | 0.500        | 0.052 (0.022)    | 0.735 (0.305)    | -         |     7.37 | casey, Flayy, innocent, kisserek, olimp |
|           32 |     3659 | 2024-04-03 | SINNERS Esports   | L   | 0.822      | -            | -                | -                | -         |   -15.52 | casey, Flayy, innocent, kisserek, olimp |
|           31 |     3835 | 2024-03-28 | ex-Sprout         | W   | 0.784      | -            | -                | -                | -         |     1.84 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     3876 | 2024-03-27 | B8                | L   | 0.778      | -            | -                | -                | -         |   -10.71 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     3889 | 2024-03-27 | Sashi Esport      | W   | 0.778      | 0.143        | 0.154 (0.017)    | -                | -         |    10.66 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     3906 | 2024-03-27 | Passion UA        | W   | 0.777      | -            | -                | -                | -         |     8.18 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     3978 | 2024-03-26 | RoundsGG          | W   | 0.771      | -            | -                | -                | -         |     1.69 | casey, Flayy, innocent, kisserek, olimp |
|           26 |     5177 | 2024-03-04 | BLEED Esports     | L   | 0.624      | -            | -                | -                | -         |    -7.13 | casey, Flayy, kisserek, olimp, sNx      |
|           25 |     5238 | 2024-03-03 | Sangal Esports    | W   | 0.617      | 0.500        | 0.166 (0.051)    | 0.658 (0.203)    | -         |     7.66 | casey, Flayy, kisserek, olimp, sNx      |
|           24 |     5334 | 2024-03-02 | Aurora Gaming     | L   | 0.610      | -            | -                | -                | -         |    -2.75 | casey, Flayy, kisserek, olimp, sNx      |
|           23 |     5425 | 2024-02-29 | Sangal Esports    | W   | 0.597      | 0.500        | 0.166 (0.050)    | 0.658 (0.196)    | -         |     7.65 | casey, Flayy, kisserek, olimp, sNx      |
|           22 |     6655 | 2024-02-04 | Team Falcons      | L   | 0.431      | -            | -                | -                | -         |    -1.44 | casey, Flayy, kisserek, olimp, sNx      |
|           21 |     6742 | 2024-02-03 | FaZe Clan         | L   | 0.423      | -            | -                | -                | -         |    -0.09 | casey, Flayy, kisserek, olimp, sNx      |
|           20 |     6792 | 2024-02-02 | M80               | W   | 0.418      | 1.000        | 0.136 (0.057)    | 0.525 (0.219)    | 1 (0.418) |     9.62 | casey, Flayy, kisserek, olimp, sNx      |
|           19 |     6908 | 2024-01-31 | Eternal Fire      | L   | 0.405      | -            | -                | -                | -         |    -0.17 | casey, Flayy, kisserek, olimp, sNx      |
|           18 |     6934 | 2024-01-31 | Cloud9            | W   | 0.404      | 1.000        | 0.187 (0.075)    | -                | 1 (0.404) |    11.60 | casey, Flayy, kisserek, olimp, sNx      |
|           17 |     7086 | 2024-01-28 | 9Pandas           | L   | 0.384      | -            | -                | -                | -         |    -4.25 | casey, Flayy, kisserek, olimp, sNx      |
|           16 |     7269 | 2024-01-26 | ILIN              | W   | 0.370      | -            | -                | -                | -         |     0.56 | casey, Flayy, kisserek, olimp, sNx      |
|           15 |     7340 | 2024-01-24 | Grannys Knockers  | W   | 0.358      | -            | -                | -                | -         |     2.01 | casey, Flayy, kisserek, olimp, sNx      |
|           14 |     7417 | 2024-01-23 | Viperio           | L   | 0.351      | -            | -                | -                | -         |   -10.40 | casey, Flayy, kisserek, olimp, sNx      |
|           13 |     7421 | 2024-01-23 | Pera Esports      | L   | 0.350      | -            | -                | -                | -         |    -7.96 | casey, Flayy, kisserek, olimp, sNx      |
|           12 |     7451 | 2024-01-22 | Team Sampi        | L   | 0.344      | -            | -                | -                | -         |    -7.46 | casey, Flayy, kisserek, olimp, sNx      |
|           11 |     7469 | 2024-01-22 | ALTERNATE aTTaX   | W   | 0.344      | -            | -                | -                | -         |     4.28 | casey, Flayy, kisserek, olimp, sNx      |
|           10 |     7477 | 2024-01-22 | ex-Guild Eagles   | L   | 0.344      | -            | -                | -                | -         |    -7.29 | casey, Flayy, kisserek, olimp, sNx      |
|            9 |     7770 | 2024-01-17 | ex-Guild Eagles   | L   | 0.312      | -            | -                | -                | -         |    -6.83 | casey, Flayy, kisserek, olimp, sNx      |
|            8 |     7798 | 2024-01-17 | RUSH B            | W   | 0.311      | -            | -                | -                | -         |     1.15 | casey, Flayy, kisserek, olimp, sNx      |
|            7 |     7877 | 2024-01-16 | Passion UA        | L   | 0.305      | -            | -                | -                | -         |    -6.17 | casey, Flayy, kisserek, olimp, sNx      |
|            6 |     7885 | 2024-01-16 | Soda Gaming       | W   | 0.305      | -            | -                | -                | -         |     0.68 | casey, Flayy, kisserek, olimp, sNx      |
|            5 |     7904 | 2024-01-16 | Insilio           | W   | 0.304      | -            | -                | -                | -         |     2.17 | casey, Flayy, kisserek, olimp, sNx      |
|            4 |     8261 | 2024-01-10 | The Prodigies     | L   | 0.265      | -            | -                | -                | -         |    -7.96 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     8711 | 2023-12-17 | TSM               | L   | 0.104      | -            | -                | -                | -         |    -3.08 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     8854 | 2023-12-16 | lajtbitexe        | W   | 0.098      | -            | -                | -                | -         |     0.18 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     9000 | 2023-12-15 | 9Pandas           | L   | 0.091      | -            | -                | -                | -         |    -1.21 | casey, Flayy, kisserek, olimp, sNx      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($18,650.46)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-18 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-04-28 |      0.988 | $10,000.00     | $9,881.02       |
| 2024-02-11 |      0.477 | $10,000.00     | $4,769.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
