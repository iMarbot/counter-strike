### Roster Details<br />
Team Name: Illuminar Gaming<br />
Roster: Furlan, phr, POLO, Prism, Qlocuu<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [154](../standings_global.md)<br />
Regional Rank: [105]( ../standings_europe.md)<br />
Final Rank Value:  773.0<br />
<br />
Final Rank Value (773.0) = Starting Rank Value (758.1) + Head To Head Adjustments (14.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.318[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.180<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 758.1
- 400 + ( ( 0.180 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 758.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           42 |     2888 | 2024-03-02 | Sashi Esport           | L   | 0.770      | -            | -                | -                | -             |    -3.95 | Furlan, phr, POLO, Prism, Qlocuu        |
|           41 |     2969 | 2024-02-29 | Viperio                | L   | 0.757      | -            | -                | -                | -             |   -15.38 | Furlan, phr, POLO, Prism, Qlocuu        |
|           40 |     3113 | 2024-02-25 | MOUZ NXT               | L   | 0.729      | -            | -                | -                | -             |    -3.28 | Furlan, phr, POLO, Prism, Qlocuu        |
|           39 |     3172 | 2024-02-24 | The Chosen Few         | W   | 0.724      | 0.143        | 0.007 (0.001)    | 0.457 (0.047)    | false (0.000) |    12.00 | Furlan, phr, POLO, Prism, Qlocuu        |
|           38 |     3430 | 2024-02-19 | Entropiq               | L   | 0.689      | -            | -                | -                | -             |   -10.75 | Furlan, phr, POLO, Prism, Qlocuu        |
|           37 |     3450 | 2024-02-18 | ARCRED                 | W   | 0.685      | 0.143        | -                | 0.825 (0.081)    | false (0.000) |    11.68 | Furlan, phr, POLO, Prism, Qlocuu        |
|           36 |     3509 | 2024-02-17 | Natus Vincere Junior   | W   | 0.676      | 0.333        | 0.025 (0.006)    | 0.492 (0.111)    | false (0.000) |    12.47 | Furlan, phr, POLO, Prism, Qlocuu        |
|           35 |     3547 | 2024-02-16 | Sashi Esport           | L   | 0.670      | -            | -                | -                | -             |    -9.58 | Furlan, phr, POLO, Prism, Qlocuu        |
|           34 |     3608 | 2024-02-15 | Viperio                | L   | 0.663      | -            | -                | -                | -             |   -13.77 | Furlan, phr, POLO, Prism, Qlocuu        |
|           33 |     3637 | 2024-02-14 | Entropiq               | L   | 0.658      | -            | -                | -                | -             |   -10.22 | Furlan, phr, POLO, Prism, Qlocuu        |
|           32 |     3735 | 2024-02-12 | WOPA Esport            | W   | 0.644      | 0.303        | 0.009 (0.002)    | 0.485 (0.095)    | false (0.000) |     9.05 | Furlan, phr, POLO, Prism, Qlocuu        |
|           31 |     3805 | 2024-02-09 | Dynamo Eclot           | L   | 0.623      | -            | -                | -                | -             |    -2.43 | Furlan, m4tthi, Prism, Qlocuu, virtuoso |
|           30 |     3908 | 2024-02-05 | Copenhagen Wolves      | W   | 0.597      | 0.303        | -                | 0.417 (0.075)    | false (0.000) |     6.38 | Furlan, phr, POLO, Prism, Qlocuu        |
|           29 |     4162 | 2024-01-29 | Sashi Esport           | L   | 0.553      | -            | -                | -                | -             |    -3.35 | Furlan, phr, POLO, Prism, Qlocuu        |
|           28 |     4176 | 2024-01-29 | GenOne                 | W   | 0.553      | -            | -                | -                | false (0.000) |     3.91 | Furlan, phr, POLO, Prism, Qlocuu        |
|           27 |     5082 | 2024-01-09 | Gaimin Gladiators      | L   | 0.419      | -            | -                | -                | -             |    -0.36 | Furlan, phr, POLO, Prism, Qlocuu        |
|           26 |     5094 | 2024-01-09 | Nemiga Gaming          | W   | 0.418      | 0.143        | 0.680 (0.041)    | 0.910 (0.054)    | false (0.000) |    12.55 | Furlan, phr, POLO, Prism, Qlocuu        |
|           25 |     5107 | 2024-01-09 | Team Secret            | W   | 0.418      | -            | -                | -                | false (0.000) |     4.44 | Furlan, phr, POLO, Prism, Qlocuu        |
|           24 |     5197 | 2024-01-04 | Ex-Anonymo Esports     | L   | 0.383      | -            | -                | -                | -             |    -5.72 | Furlan, phr, POLO, Prism, Qlocuu        |
|           23 |     5251 | 2023-12-29 | Alliance               | L   | 0.343      | -            | -                | -                | -             |    -3.84 | Furlan, phr, POLO, Qlocuu, swiz         |
|           22 |     5256 | 2023-12-28 | VP.Prodigy             | L   | 0.336      | -            | -                | -                | -             |    -4.27 | Furlan, phr, POLO, Qlocuu, swiz         |
|           21 |     5261 | 2023-12-27 | Rhyno Esports          | W   | 0.330      | 0.371        | 0.047 (0.006)    | 0.446 (0.055)    | false (0.000) |     7.36 | Furlan, phr, POLO, Qlocuu, swiz         |
|           20 |     5295 | 2023-12-21 | Viperio                | W   | 0.291      | -            | -                | -                | false (0.000) |     2.50 | Furlan, phr, POLO, Prism, Qlocuu        |
|           19 |     5323 | 2023-12-19 | Astralis Talent        | W   | 0.276      | 0.303        | 0.030 (0.002)    | 0.613 (0.051)    | -             |     6.55 | Furlan, phr, POLO, Prism, Qlocuu        |
|           18 |     5380 | 2023-12-17 | Nexus Gaming           | W   | 0.264      | 0.303        | 0.031 (0.003)    | 0.772 (0.062)    | -             |     5.99 | Furlan, phr, POLO, Prism, Qlocuu        |
|           17 |     5593 | 2023-12-15 | Passion UA             | W   | 0.250      | 0.303        | 0.114 (0.009)    | 0.980 (0.074)    | -             |     6.30 | Furlan, phr, POLO, Prism, Qlocuu        |
|           16 |     5655 | 2023-12-13 | Astralis Talent        | W   | 0.236      | 0.303        | 0.030 (0.002)    | -                | -             |     5.71 | Furlan, phr, POLO, Prism, Qlocuu        |
|           15 |     5678 | 2023-12-12 | The Witchers           | L   | 0.231      | -            | -                | -                | -             |    -3.37 | Furlan, phr, POLO, Prism, Qlocuu        |
|           14 |     5745 | 2023-12-10 | Pompa Team             | W   | 0.216      | -            | -                | -                | -             |     1.44 | Furlan, phr, POLO, Prism, Qlocuu        |
|           13 |     5841 | 2023-12-08 | Zero Tenacity          | L   | 0.204      | -            | -                | -                | -             |    -1.52 | Furlan, phr, POLO, Prism, Qlocuu        |
|           12 |     5896 | 2023-12-07 | Lazer Cats             | W   | 0.197      | -            | -                | -                | -             |     2.01 | Furlan, phr, POLO, Prism, Qlocuu        |
|           11 |     6017 | 2023-12-04 | Pompa Team             | L   | 0.178      | -            | -                | -                | -             |    -4.45 | Furlan, phr, POLO, Prism, Qlocuu        |
|           10 |     6337 | 2023-11-28 | Sashi Esport           | L   | 0.136      | -            | -                | -                | -             |    -2.38 | Furlan, phr, POLO, Prism, Qlocuu        |
|            9 |     6378 | 2023-11-27 | Kappa Bar              | W   | 0.130      | -            | -                | -                | -             |     1.61 | Furlan, phr, POLO, Prism, Qlocuu        |
|            8 |     6401 | 2023-11-26 | Astralis Talent        | W   | 0.124      | 0.303        | 0.030 (0.001)    | -                | -             |     3.00 | Furlan, phr, POLO, Prism, Qlocuu        |
|            7 |     6408 | 2023-11-26 | Sashi Esport           | L   | 0.123      | -            | -                | -                | -             |    -2.14 | Furlan, phr, POLO, Prism, Qlocuu        |
|            6 |     6523 | 2023-11-23 | AGO esports            | W   | 0.104      | -            | -                | -                | -             |     1.18 | Furlan, phr, POLO, Prism, Qlocuu        |
|            5 |     6647 | 2023-11-20 | Project G              | W   | 0.084      | -            | -                | -                | -             |     0.49 | Furlan, phr, POLO, Prism, Qlocuu        |
|            4 |     6665 | 2023-11-19 | ENTERPRISE esports     | L   | 0.078      | -            | -                | -                | -             |    -0.61 | Furlan, phr, POLO, Prism, Qlocuu        |
|            3 |     6723 | 2023-11-18 | Turów Zgorzelec Esport | L   | 0.071      | -            | -                | -                | -             |    -0.91 | Furlan, phr, POLO, Prism, Qlocuu        |
|            2 |     6870 | 2023-11-15 | ENTERPRISE esports     | W   | 0.052      | -            | -                | -                | -             |     1.23 | Furlan, phr, POLO, Prism, Qlocuu        |
|            1 |     6990 | 2023-11-13 | NOM Esports            | L   | 0.036      | -            | -                | -                | -             |    -0.68 | Furlan, phr, POLO, Prism, Qlocuu        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,591.92)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-19 |      0.276 | $3,500.00      | $967.20         |
| 2023-12-02 |      0.166 | $3,774.51      | $624.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
