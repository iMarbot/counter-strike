### Roster Details<br />
Team Name: Monte<br />
Roster: DemQQ, hAdji, kRaSnaL, STYKO, Woro2k<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [31](../standings_global.md)<br />
Regional Rank: [21]( ../standings_europe.md)<br />
Final Rank Value:  1242.3<br />
<br />
Final Rank Value (1242.3) = Starting Rank Value (1320.1) + Head To Head Adjustments (-77.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.574[<sup>1</sup>](#table2)
- Bounty Collected: 0.484[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 0.439[<sup>2</sup>](#table1)

The average of these factors is 0.453<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1320.1
- 400 + ( ( 0.453 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1320.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           45 |      155 | 2024-05-27 | Team Falcons      | L   | 1.000      | -            | -                | -                | -         |    -8.04 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           44 |      176 | 2024-05-27 | Team Vitality     | L   | 1.000      | -            | -                | -                | -         |    -1.08 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           43 |      626 | 2024-05-21 | Sangal Esports    | L   | 1.000      | -            | -                | -                | -         |   -22.65 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           42 |      733 | 2024-05-20 | Sashi Esport      | W   | 1.000      | 0.500        | 0.154 (0.077)    | 1.000 (0.500)    | 0 (0.000) |    14.38 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           41 |      913 | 2024-05-18 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -         |   -16.60 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           40 |      991 | 2024-05-17 | BLEED Esports     | W   | 1.000      | 0.500        | 0.248 (0.124)    | 0.714 (0.357)    | 0 (0.000) |    11.23 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           39 |     1099 | 2024-05-16 | kONO.ECF          | W   | 1.000      | 0.384        | -                | 0.853 (0.328)    | 0 (0.000) |     3.40 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           38 |     1176 | 2024-05-15 | DMS               | W   | 1.000      | 0.500        | -                | 0.754 (0.377)    | -         |     4.75 | DemQQ, hAdji, kRaSnaL, STYKO, Woro2k |
|           37 |     1686 | 2024-05-07 | FaZe Clan         | L   | 1.000      | -            | -                | -                | -         |    -0.62 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           36 |     1790 | 2024-05-05 | FURIA Esports     | W   | 1.000      | 0.889        | 0.138 (0.122)    | 0.267 (0.237)    | 1 (1.000) |    20.36 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           35 |     1866 | 2024-05-04 | FORZE Esports     | W   | 1.000      | 0.889        | 0.101 (0.090)    | 0.372 (0.330)    | 1 (1.000) |     9.64 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           34 |     1938 | 2024-05-02 | ENCE              | L   | 1.000      | -            | -                | -                | -         |   -11.08 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           33 |     2003 | 2024-05-01 | Team Liquid       | L   | 1.000      | -            | -                | -                | -         |    -3.47 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           32 |     2053 | 2024-04-30 | FORZE Esports     | W   | 1.000      | 0.889        | 0.101 (0.090)    | 0.372 (0.330)    | 1 (1.000) |     9.22 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           31 |     2734 | 2024-04-19 | OG                | L   | 0.931      | -            | -                | -                | -         |   -13.97 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           30 |     2826 | 2024-04-18 | paiN Gaming       | L   | 0.923      | -            | -                | -                | -         |    -4.81 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           29 |     3097 | 2024-04-13 | Rebels Gaming     | W   | 0.890      | 0.500        | -                | 0.411 (0.183)    | -         |     9.03 | DemQQ, hAdji, kRaSnaL, ryu, Woro2k   |
|           28 |     3145 | 2024-04-12 | Sangal Esports    | W   | 0.883      | 0.500        | 0.166 (0.073)    | 0.658 (0.291)    | -         |     5.41 | DemQQ, hAdji, kRaSnaL, ryu, Woro2k   |
|           27 |     3635 | 2024-04-03 | Metizport         | L   | 0.824      | -            | -                | -                | -         |   -18.46 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           26 |     3646 | 2024-04-03 | Apeks             | W   | 0.823      | -            | -                | -                | -         |    12.25 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           25 |     3682 | 2024-04-02 | GamerLegion       | W   | 0.817      | -            | -                | -                | -         |    12.28 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           24 |     3696 | 2024-04-02 | Ninjas in Pyjamas | L   | 0.816      | -            | -                | -                | -         |   -17.14 | DemQQ, Gizmy, kRaSnaL, ryu, Woro2k   |
|           23 |     3741 | 2024-03-31 | RUSH B            | L   | 0.803      | -            | -                | -                | -         |   -23.54 | DemQQ, hAdji, kRaSnaL, ryu, Woro2k   |
|           22 |     3834 | 2024-03-28 | Betera Esports    | L   | 0.784      | -            | -                | -                | -         |   -22.55 | DemQQ, hAdji, kRaSnaL, ryu, Woro2k   |
|           21 |     3985 | 2024-03-26 | System5           | W   | 0.771      | -            | -                | -                | -         |     0.79 | DemQQ, hAdji, kRaSnaL, ryu, Woro2k   |
|           20 |     4837 | 2024-03-09 | Metizport         | L   | 0.657      | -            | -                | -                | -         |   -16.66 | DemQQ, kRaSnaL, leen, sdy, Woro2k    |
|           19 |     4914 | 2024-03-07 | Imperial Esports  | W   | 0.645      | 0.535        | 0.372 (0.128)    | 0.582 (0.201)    | -         |    15.13 | DemQQ, kRaSnaL, leen, sdy, Woro2k    |
|           18 |     5259 | 2024-03-03 | Gaimin Gladiators | L   | 0.615      | -            | -                | -                | -         |   -10.77 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k  |
|           17 |     5315 | 2024-03-02 | 3DMAX             | L   | 0.611      | -            | -                | -                | -         |   -17.03 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k  |
|           16 |     5439 | 2024-02-29 | PARIVISION        | W   | 0.596      | -            | -                | -                | -         |     1.77 | DemQQ, Gizmy, kRaSnaL, Kvem, Woro2k  |
|           15 |     5900 | 2024-02-21 | Astralis          | L   | 0.542      | -            | -                | -                | -         |    -2.40 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|           14 |     5957 | 2024-02-20 | Apeks             | L   | 0.536      | -            | -                | -                | -         |   -10.49 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|           13 |     5998 | 2024-02-19 | Nexus Gaming      | W   | 0.531      | -            | -                | -                | 1 (0.531) |     1.32 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k   |
|           12 |     6018 | 2024-02-19 | Gaimin Gladiators | L   | 0.529      | -            | -                | -                | -         |   -10.47 | br0, DemQQ, Gizmy, kRaSnaL, Woro2k   |
|           11 |     6037 | 2024-02-18 | Aurora Gaming     | W   | 0.525      | 0.143        | 0.492 (0.037)    | -                | -         |    10.51 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|           10 |     6048 | 2024-02-18 | SINNERS Esports   | W   | 0.524      | -            | -                | -                | -         |     2.21 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            9 |     6116 | 2024-02-17 | Aurora Gaming     | W   | 0.517      | 0.143        | 0.492 (0.036)    | -                | -         |    10.78 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            8 |     6124 | 2024-02-17 | The Chosen Few    | W   | 0.516      | -            | -                | -                | -         |     0.68 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            7 |     6583 | 2024-02-06 | G2 Esports        | L   | 0.443      | -            | -                | -                | -         |    -0.93 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            6 |     6637 | 2024-02-05 | Cloud9            | W   | 0.436      | 1.000        | 0.187 (0.082)    | -                | 1 (0.436) |    10.16 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            5 |     6674 | 2024-02-04 | GamerLegion       | L   | 0.429      | -            | -                | -                | -         |    -8.06 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            4 |     8717 | 2023-12-17 | Apeks             | L   | 0.104      | -            | -                | -                | -         |    -2.03 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            3 |     8826 | 2023-12-16 | BESTIA            | W   | 0.098      | -            | -                | -                | 1 (0.098) |     0.07 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            2 |     8979 | 2023-12-15 | Virtus.pro        | L   | 0.092      | -            | -                | -                | -         |    -0.32 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |
|            1 |     9008 | 2023-12-15 | BESTIA            | W   | 0.090      | -            | -                | -                | 1 (0.090) |     0.07 | br0, DemQQ, kRaSnaL, sdy, Woro2k     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54,355.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.18) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $4,000.00      | $4,000.00       |
| 2024-05-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-05-18 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-05-12 |      1.000 | $17,500.00     | $17,500.00      |
| 2024-04-20 |      0.938 | $5,000.00      | $4,689.81       |
| 2024-03-10 |      0.665 | $7,500.00      | $4,983.85       |
| 2024-02-11 |      0.477 | $16,000.00     | $7,631.11       |
| 2023-12-17 |      0.105 | $10,000.00     | $1,051.16       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
