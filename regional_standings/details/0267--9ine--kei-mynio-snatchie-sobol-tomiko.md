### Roster Details<br />
Team Name: 9INE<br />
Roster: KEi, mynio, snatchie, Sobol, tomiko<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [267](../standings_global.md)<br />
Regional Rank: [166]( ../standings_europe.md)<br />
Final Rank Value:  649.3<br />
<br />
Final Rank Value (649.3) = Starting Rank Value (567.7) + Head To Head Adjustments (81.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.058[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.085<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 567.7
- 400 + ( ( 0.085 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 567.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2711 | 2024-03-05 | Dynamo Eclot    | L   | 0.790      | -            | -                | -                | -             |    -1.38 | KEi, mynio, snatchie, Sobol, tomiko |
|           19 |     2720 | 2024-03-04 | Passion UA      | L   | 0.786      | -            | -                | -                | -             |    -4.32 | KEi, mynio, SaMey, Sobol, tomiko    |
|           18 |     2747 | 2024-03-04 | Lilmix          | W   | 0.786      | 0.143        | 0.000 (0.000)    | 0.604 (0.068)    | false (0.000) |    11.62 | KEi, mynio, SaMey, Sobol, tomiko    |
|           17 |     2799 | 2024-03-03 | ILIN            | L   | 0.778      | -            | -                | -                | -             |   -11.83 | KEi, mynio, snatchie, Sobol, tomiko |
|           16 |     2833 | 2024-03-02 | ARCRED          | W   | 0.773      | 0.143        | 0.004 (0.000)    | 0.825 (0.091)    | false (0.000) |    18.17 | KEi, mynio, snatchie, Sobol, tomiko |
|           15 |     2851 | 2024-03-02 | HyperSpirit     | W   | 0.772      | 0.143        | 0.009 (0.001)    | 0.293 (0.032)    | false (0.000) |    14.22 | KEi, mynio, snatchie, Sobol, tomiko |
|           14 |     2925 | 2024-03-01 | Alliance        | W   | 0.763      | 0.371        | 0.017 (0.005)    | 0.729 (0.206)    | false (0.000) |    19.53 | KEi, mynio, snatchie, Sobol, tomiko |
|           13 |     3076 | 2024-02-26 | Entropiq        | L   | 0.737      | -            | -                | -                | -             |    -5.45 | KEi, mynio, SaMey, Sobol, tomiko    |
|           12 |     3748 | 2024-02-11 | Lilmix          | L   | 0.639      | -            | -                | -                | -             |    -9.97 | Bambosh, KEi, mhL, mynio, tomiko    |
|           11 |     3751 | 2024-02-11 | KOMNATA         | W   | 0.638      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     4.59 | Bambosh, KEi, mhL, mynio, tomiko    |
|           10 |     3774 | 2024-02-10 | ILLYRIANS       | L   | 0.631      | -            | -                | -                | -             |    -6.98 | Bambosh, KEi, mhL, mynio, tomiko    |
|            9 |     3870 | 2024-02-06 | Alliance        | L   | 0.603      | -            | -                | -                | -             |    -4.31 | KEi, mynio, SaMey, Sobol, tomiko    |
|            8 |     4266 | 2024-01-27 | Into The Breach | W   | 0.538      | 0.143        | 0.022 (0.002)    | 0.193 (0.015)    | false (0.000) |    12.89 | Bambosh, KEi, mhL, mynio, tomiko    |
|            7 |     4268 | 2024-01-27 | K10             | W   | 0.538      | 0.143        | 0.015 (0.001)    | 0.418 (0.032)    | false (0.000) |    14.13 | Bambosh, KEi, mhL, mynio, tomiko    |
|            6 |     4791 | 2024-01-16 | JANO Esports    | L   | 0.466      | -            | -                | -                | -             |    -4.05 | Bambosh, KEi, mhL, mynio, tomiko    |
|            5 |     4809 | 2024-01-16 | Metizport       | W   | 0.465      | 0.143        | 0.188 (0.013)    | 1.000 (0.066)    | false (0.000) |    13.23 | Bambosh, KEi, mhL, mynio, tomiko    |
|            4 |     5073 | 2024-01-09 | KOI             | L   | 0.419      | -            | -                | -                | -             |    -0.93 | Bambosh, KEi, mhL, mynio, tomiko    |
|            3 |     5088 | 2024-01-09 | Zero Tenacity   | W   | 0.418      | 0.143        | 0.095 (0.006)    | 1.000 (0.060)    | false (0.000) |    11.76 | Bambosh, KEi, mhL, mynio, tomiko    |
|            2 |     5097 | 2024-01-09 | XGOD            | W   | 0.418      | 0.143        | 0.000 (0.000)    | 0.056 (0.003)    | false (0.000) |     5.30 | Bambosh, KEi, mhL, mynio, tomiko    |
|            1 |     5121 | 2024-01-09 | 00 Nation       | W   | 0.418      | 0.143        | -                | 0.048 (0.003)    | -             |     5.35 | Bambosh, KEi, mhL, mynio, tomiko    |

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
