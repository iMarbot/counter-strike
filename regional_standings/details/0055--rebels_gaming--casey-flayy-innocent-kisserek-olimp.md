### Roster Details<br />
Team Name: Rebels Gaming<br />
Roster: casey, Flayy, innocent, kisserek, olimp<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [55](../standings_global.md)<br />
Regional Rank: [38]( ../standings_europe.md)<br />
Final Rank Value:  1035.8<br />
<br />
Final Rank Value (1035.8) = Starting Rank Value (1122.3) + Head To Head Adjustments (-86.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.441[<sup>2</sup>](#table1)
- Opponent Network: 0.233[<sup>2</sup>](#table1)
- LAN Wins: 0.293[<sup>2</sup>](#table1)

The average of these factors is 0.355<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1122.3
- 400 + ( ( 0.355 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1122.3


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
|           47 |       89 | 2024-05-29 | UNiTY esports     | L   | 1.000      | -            | -                | -                | -         |   -23.77 | casey, Flayy, innocent, kisserek, olimp |
|           46 |      315 | 2024-05-25 | kONO.ECF          | W   | 1.000      | 0.371        | -                | 0.778 (0.288)    | 0 (0.000) |     7.79 | casey, Flayy, innocent, kisserek, olimp |
|           45 |      626 | 2024-05-21 | UNiTY esports     | L   | 1.000      | -            | -                | -                | -         |   -24.21 | casey, Flayy, innocent, kisserek, olimp |
|           44 |      679 | 2024-05-20 | The Prodigies     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.70 | casey, Flayy, innocent, kisserek, olimp |
|           43 |      926 | 2024-05-18 | B8                | L   | 1.000      | -            | -                | -                | -         |   -12.62 | casey, Flayy, innocent, kisserek, olimp |
|           42 |      998 | 2024-05-17 | Gaimin Gladiators | W   | 1.000      | 0.384        | 0.092 (0.035)    | 0.711 (0.273)    | 0 (0.000) |    19.32 | casey, Flayy, innocent, kisserek, olimp |
|           41 |     1371 | 2024-05-12 | Permitta Esports  | W   | 1.000      | 0.143        | -                | 1.000 (0.143)    | 0 (0.000) |     7.91 | casey, Flayy, innocent, kisserek, olimp |
|           40 |     1393 | 2024-05-12 | pasztetuwa        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.53 | casey, Flayy, innocent, kisserek, olimp |
|           39 |     1457 | 2024-05-11 | GenOne            | L   | 1.000      | -            | -                | -                | -         |   -28.11 | casey, Flayy, innocent, kisserek, olimp |
|           38 |     2135 | 2024-04-27 | Aurora Gaming     | L   | 0.987      | -            | -                | -                | -         |    -4.60 | casey, Flayy, innocent, kisserek, olimp |
|           37 |     2288 | 2024-04-25 | MIBR              | W   | 0.974      | 0.500        | 0.307 (0.150)    | 0.512 (0.249)    | 1 (0.974) |    28.93 | casey, Flayy, innocent, kisserek, olimp |
|           36 |     2290 | 2024-04-25 | Rooster           | W   | 0.973      | 0.500        | 0.014 (0.007)    | 0.229 (0.112)    | 1 (0.973) |     6.32 | casey, Flayy, innocent, kisserek, olimp |
|           35 |     2684 | 2024-04-19 | brazylijski luz   | L   | 0.931      | -            | -                | -                | -         |   -22.90 | casey, Flayy, innocent, kisserek, olimp |
|           34 |     2823 | 2024-04-17 | EYEBALLERS        | L   | 0.918      | -            | -                | -                | -         |   -20.88 | casey, Flayy, innocent, kisserek, olimp |
|           33 |     3031 | 2024-04-13 | Monte             | L   | 0.890      | -            | -                | -                | -         |    -9.01 | casey, Flayy, innocent, kisserek, olimp |
|           32 |     3235 | 2024-04-09 | B8                | W   | 0.864      | 0.500        | 0.168 (0.073)    | 0.952 (0.411)    | 0 (0.000) |    14.56 | casey, Flayy, innocent, kisserek, olimp |
|           31 |     3504 | 2024-04-04 | ALTERNATE aTTaX   | W   | 0.830      | 0.500        | 0.052 (0.021)    | 0.679 (0.282)    | -         |     7.58 | casey, Flayy, innocent, kisserek, olimp |
|           30 |     3572 | 2024-04-03 | SINNERS Esports   | L   | 0.822      | -            | -                | -                | -         |   -16.57 | casey, Flayy, innocent, kisserek, olimp |
|           29 |     3741 | 2024-03-28 | ex-Sprout         | W   | 0.784      | -            | -                | -                | -         |     1.92 | casey, Flayy, innocent, kisserek, olimp |
|           28 |     3783 | 2024-03-27 | B8                | L   | 0.778      | -            | -                | -                | -         |   -10.24 | casey, Flayy, innocent, kisserek, olimp |
|           27 |     3796 | 2024-03-27 | Sashi Esport      | W   | 0.778      | 0.143        | 0.172 (0.019)    | -                | -         |    10.72 | casey, Flayy, innocent, kisserek, olimp |
|           26 |     3813 | 2024-03-27 | Passion UA        | W   | 0.777      | -            | -                | -                | -         |     8.30 | casey, Flayy, innocent, kisserek, olimp |
|           25 |     3881 | 2024-03-26 | RoundsGG          | W   | 0.771      | -            | -                | -                | -         |     1.59 | casey, Flayy, innocent, kisserek, olimp |
|           24 |     3917 | 2024-03-25 | Aurora Gaming     | L   | 0.764      | -            | -                | -                | -         |    -3.33 | casey, Flayy, innocent, kisserek, olimp |
|           23 |     5031 | 2024-03-04 | BLEED Esports     | L   | 0.624      | -            | -                | -                | -         |    -7.09 | casey, Flayy, kisserek, olimp, sNx      |
|           22 |     5092 | 2024-03-03 | Sangal Esports    | W   | 0.617      | 0.500        | 0.166 (0.051)    | 0.577 (0.178)    | -         |     7.29 | casey, Flayy, kisserek, olimp, sNx      |
|           21 |     5186 | 2024-03-02 | Aurora Gaming     | L   | 0.610      | -            | -                | -                | -         |    -2.56 | casey, Flayy, kisserek, olimp, sNx      |
|           20 |     5275 | 2024-02-29 | Sangal Esports    | W   | 0.597      | 0.500        | 0.166 (0.050)    | 0.577 (0.172)    | -         |     7.26 | casey, Flayy, kisserek, olimp, sNx      |
|           19 |     6453 | 2024-02-04 | Team Falcons      | L   | 0.431      | -            | -                | -                | -         |    -1.39 | casey, Flayy, kisserek, olimp, sNx      |
|           18 |     6539 | 2024-02-03 | FaZe Clan         | L   | 0.423      | -            | -                | -                | -         |    -0.08 | casey, Flayy, kisserek, olimp, sNx      |
|           17 |     6589 | 2024-02-02 | M80               | W   | 0.418      | 1.000        | 0.136 (0.057)    | 0.525 (0.219)    | 1 (0.418) |     9.83 | casey, Flayy, kisserek, olimp, sNx      |
|           16 |     6699 | 2024-01-31 | Eternal Fire      | L   | 0.405      | -            | -                | -                | -         |    -0.17 | casey, Flayy, kisserek, olimp, sNx      |
|           15 |     6722 | 2024-01-31 | Cloud9            | W   | 0.404      | 1.000        | 0.187 (0.075)    | -                | 1 (0.404) |    11.63 | casey, Flayy, kisserek, olimp, sNx      |
|           14 |     6868 | 2024-01-28 | 9Pandas           | L   | 0.384      | -            | -                | -                | -         |    -4.34 | casey, Flayy, kisserek, olimp, sNx      |
|           13 |     7045 | 2024-01-26 | ILIN              | W   | 0.370      | -            | -                | -                | -         |     0.57 | casey, Flayy, kisserek, olimp, sNx      |
|           12 |     7110 | 2024-01-24 | Grindas           | W   | 0.358      | -            | -                | -                | -         |     0.42 | casey, Flayy, kisserek, olimp, sNx      |
|           11 |     7179 | 2024-01-23 | Viperio           | L   | 0.351      | -            | -                | -                | -         |   -10.40 | casey, Flayy, kisserek, olimp, sNx      |
|           10 |     7182 | 2024-01-23 | Pera Esports      | L   | 0.350      | -            | -                | -                | -         |    -7.87 | casey, Flayy, kisserek, olimp, sNx      |
|            9 |     7210 | 2024-01-22 | Team Sampi        | L   | 0.344      | -            | -                | -                | -         |    -7.47 | casey, Flayy, kisserek, olimp, sNx      |
|            8 |     7226 | 2024-01-22 | ALTERNATE aTTaX   | W   | 0.344      | -            | -                | -                | -         |     1.26 | casey, Flayy, kisserek, olimp, sNx      |
|            7 |     7234 | 2024-01-22 | ex-Guild Eagles   | L   | 0.344      | -            | -                | -                | -         |    -7.29 | casey, Flayy, kisserek, olimp, sNx      |
|            6 |     7521 | 2024-01-17 | ex-Guild Eagles   | L   | 0.312      | -            | -                | -                | -         |    -6.83 | casey, Flayy, kisserek, olimp, sNx      |
|            5 |     7549 | 2024-01-17 | RUSH B            | W   | 0.311      | -            | -                | -                | -         |     1.15 | casey, Flayy, kisserek, olimp, sNx      |
|            4 |     7628 | 2024-01-16 | Passion UA        | L   | 0.305      | -            | -                | -                | -         |    -6.27 | casey, Flayy, kisserek, olimp, sNx      |
|            3 |     7636 | 2024-01-16 | Soda Gaming       | W   | 0.305      | -            | -                | -                | -         |     0.61 | casey, Flayy, kisserek, olimp, sNx      |
|            2 |     7655 | 2024-01-16 | Insilio           | W   | 0.304      | -            | -                | -                | -         |     2.26 | casey, Flayy, kisserek, olimp, sNx      |
|            1 |     8007 | 2024-01-10 | The Prodigies     | L   | 0.265      | -            | -                | -                | -         |    -7.96 | casey, Flayy, kisserek, olimp, sNx      |

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
