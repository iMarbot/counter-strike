### Roster Details<br />
Team Name: Ex-Hot Headed Gaming<br />
Roster: anna1t, Ent1st, jabba2h, tripex17, yukitoro<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [332](../standings_global.md)<br />
Regional Rank: [202]( ../standings_europe.md)<br />
Final Rank Value:  543.2<br />
<br />
Final Rank Value (543.2) = Starting Rank Value (513.5) + Head To Head Adjustments (29.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 513.5
- 400 + ( ( 0.057 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 513.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     2975 | 2024-02-28 | 0to100                 | W   | 0.752      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     7.17 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           16 |     3023 | 2024-02-27 | LODIS                  | W   | 0.745      | 0.371        | 0.002 (0.001)    | 0.139 (0.039)    | false (0.000) |    14.90 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           15 |     3206 | 2024-02-23 | Golden Sword           | W   | 0.719      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     7.33 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           14 |     3397 | 2024-02-19 | Kappa Bar              | W   | 0.692      | 0.371        | 0.002 (0.000)    | 0.149 (0.038)    | false (0.000) |    15.65 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           13 |     3672 | 2024-02-13 | FORZE Youngsters       | L   | 0.652      | -            | -                | -                | -             |    -4.86 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           12 |     3855 | 2024-02-06 | Zero Tenacity          | L   | 0.606      | -            | -                | -                | -             |    -1.50 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           11 |     3878 | 2024-02-05 | FLuffy Gangsters       | L   | 0.599      | -            | -                | -                | -             |    -7.90 | anna1t, Ent1st, jabba2h, Saturday, tripex17 |
|           10 |     4078 | 2024-02-01 | INGLORIOUS             | L   | 0.571      | -            | -                | -                | -             |    -3.06 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            9 |     4384 | 2024-01-24 | Nemiga Gaming          | L   | 0.518      | -            | -                | -                | -             |    -0.20 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            8 |     6089 | 2023-12-02 | 4ERNOTA                | L   | 0.166      | -            | -                | -                | -             |    -2.77 | anna1t, Ent1st, kRyTouS, PLANET, yukitoro   |
|            7 |     6252 | 2023-11-29 | CYBERSHOKE Esports     | W   | 0.145      | 0.371        | 0.004 (0.000)    | 0.220 (0.012)    | false (0.000) |     3.57 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz   |
|            6 |     6267 | 2023-11-29 | DMS                    | L   | 0.145      | -            | -                | -                | -             |    -1.50 | AW, H1te, kAlash, sFade8, sm3t              |
|            5 |     6367 | 2023-11-27 | Ex-Anonymo Esports     | W   | 0.132      | 0.371        | 0.019 (0.001)    | 0.295 (0.014)    | false (0.000) |     3.36 | lunAtic, reiko, SaMey, Sobol, virtuoso      |
|            4 |     6480 | 2023-11-24 | TEAM ZOO BAR           | L   | 0.111      | -            | -                | -                | -             |    -1.81 | AMANEK, devoduvek, drac, Kyojin, SIXER      |
|            3 |     6515 | 2023-11-23 | TY                     | L   | 0.105      | -            | -                | -                | -             |    -0.89 | fierre, maty, spardaus, tooizera, yakuza    |
|            2 |     6565 | 2023-11-22 | BALLISTIC              | W   | 0.098      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.06 | affect1oN, Fak1E, gooddeph, reNIK, SasukeQO |
|            1 |     6928 | 2023-11-14 | Turów Zgorzelec Esport | W   | 0.045      | 0.371        | 0.019 (0.000)    | 0.640 (0.011)    | false (0.000) |     1.20 | b1elany, darko, gRuChA, kadziu, Markoś      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
