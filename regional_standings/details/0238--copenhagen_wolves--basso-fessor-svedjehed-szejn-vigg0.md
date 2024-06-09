### Roster Details<br />
Team Name: Copenhagen Wolves<br />
Roster: Basso, Fessor, Svedjehed, szejn, vigg0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [238](../standings_global.md)<br />
Regional Rank: [157]( ../standings_europe.md)<br />
Final Rank Value:  696.0<br />
<br />
Final Rank Value (696.0) = Starting Rank Value (658.5) + Head To Head Adjustments (37.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.292[<sup>2</sup>](#table1)
- Opponent Network: 0.118[<sup>2</sup>](#table1)
- LAN Wins: 0.099[<sup>2</sup>](#table1)

The average of these factors is 0.127<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 658.5
- 400 + ( ( 0.127 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 658.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           50 |     1646 | 2024-05-08 | Sashi Esport         | W   | 1.000      | 0.143        | 0.154 (0.022)    | 1.000 (0.143)    | 0 (0.000) |    30.33 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           49 |     1728 | 2024-05-06 | Kappa Bar            | L   | 1.000      | -            | -                | -                | -         |   -20.42 | artie, Basso, Fessor, Svedjehed, szejn    |
|           48 |     1732 | 2024-05-06 | Astralis Talent      | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.452 (0.065)    | 0 (0.000) |    20.46 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           47 |     1745 | 2024-05-06 | IMMAPROBLEM          | L   | 1.000      | -            | -                | -                | -         |   -20.01 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           46 |     1758 | 2024-05-06 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -10.32 | Altekz, Fessor, Svedjehed, szejn, vigg0   |
|           45 |     1852 | 2024-05-04 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -13.00 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           44 |     1879 | 2024-05-04 | Johnny Speeds        | L   | 1.000      | -            | -                | -                | -         |    -4.52 | Basso, Fessor, Logic, Svedjehed, vigg0    |
|           43 |     2029 | 2024-05-01 | ex-K10               | W   | 1.000      | 0.333        | 0.005 (0.002)    | 0.517 (0.172)    | 0 (0.000) |    19.39 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           42 |     2080 | 2024-04-30 | kONO.ECF             | L   | 1.000      | -            | -                | -                | -         |    -6.13 | Basso, Fessor, smF, Svedjehed, szejn      |
|           41 |     2090 | 2024-04-29 | Sashi Academy        | W   | 0.997      | -            | -                | -                | 0 (0.000) |    12.50 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           40 |     2093 | 2024-04-29 | AscendX Esports      | W   | 0.997      | -            | -                | -                | 0 (0.000) |     4.65 | artie, Basso, Fessor, Svedjehed, szejn    |
|           39 |     2246 | 2024-04-27 | Johnny Speeds        | L   | 0.982      | -            | -                | -                | -         |    -3.66 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           38 |     2346 | 2024-04-25 | FAVBET Team          | W   | 0.970      | 0.372        | 0.008 (0.003)    | 0.845 (0.305)    | 0 (0.000) |    24.55 | artie, Basso, Fessor, Svedjehed, szejn    |
|           37 |     2349 | 2024-04-25 | Young Gods           | L   | 0.970      | -            | -                | -                | -         |   -19.32 | artie, Basso, Fessor, Svedjehed, szejn    |
|           36 |     2399 | 2024-04-24 | XI Esport            | W   | 0.964      | 0.143        | -                | 0.277 (0.038)    | 0 (0.000) |    14.34 | Altekz, Basso, Fessor, Svedjehed, vigg0   |
|           35 |     2582 | 2024-04-21 | MASONIC              | L   | 0.941      | -            | -                | -                | -         |    -7.65 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           34 |     2614 | 2024-04-20 | Floki Esport         | W   | 0.937      | -            | -                | -                | 1 (0.937) |     5.22 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           33 |     2875 | 2024-04-17 | GamerLegion          | L   | 0.918      | -            | -                | -                | -         |    -1.25 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           32 |     3009 | 2024-04-15 | Preasy Esport        | W   | 0.904      | 0.143        | 0.008 (0.001)    | 0.705 (0.091)    | 0 (0.000) |    18.34 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           31 |     3234 | 2024-04-10 | ARROW                | L   | 0.871      | -            | -                | -                | -         |   -10.87 | artie, Basso, Fessor, Svedjehed, szejn    |
|           30 |     3365 | 2024-04-08 | ADEPTS               | W   | 0.857      | 0.372        | 0.005 (0.001)    | 0.291 (0.093)    | 0 (0.000) |    19.48 | artie, Basso, Fessor, Svedjehed, szejn    |
|           29 |     4721 | 2024-03-11 | XI Esport            | L   | 0.671      | -            | -                | -                | -         |   -10.32 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           28 |     4740 | 2024-03-11 | Preasy Esport        | L   | 0.671      | -            | -                | -                | -         |    -6.19 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           27 |     4980 | 2024-03-06 | IMMAPROBLEM          | W   | 0.638      | -            | -                | -                | -         |     7.23 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           26 |     4991 | 2024-03-06 | Team Atlantic        | W   | 0.638      | -            | -                | -                | -         |     6.72 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           25 |     5003 | 2024-03-06 | WOPA Esport          | L   | 0.637      | -            | -                | -                | -         |    -6.37 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           24 |     5424 | 2024-02-29 | UNiTY esports        | W   | 0.597      | 0.371        | 0.021 (0.005)    | 0.766 (0.170)    | -         |    14.30 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           23 |     5453 | 2024-02-28 | LODIS                | W   | 0.591      | 0.371        | 0.001 (0.000)    | -                | -         |     8.97 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           22 |     5467 | 2024-02-28 | Astralis Talent      | L   | 0.591      | -            | -                | -                | -         |    -3.12 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           21 |     5475 | 2024-02-28 | L&G                  | W   | 0.590      | -            | -                | -                | -         |     6.27 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           20 |     5804 | 2024-02-22 | VP.Prodigy           | L   | 0.551      | -            | -                | -                | -         |    -3.83 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           19 |     5815 | 2024-02-22 | INGLORIOUS           | L   | 0.551      | -            | -                | -                | -         |    -5.66 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           18 |     5996 | 2024-02-19 | Sashi Esport         | L   | 0.531      | -            | -                | -                | -         |    -5.51 | Basso, Fessor, Svedjehed, szejn, vigg0    |
|           17 |     6209 | 2024-02-15 | 1win                 | L   | 0.504      | -            | -                | -                | -         |    -2.31 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           16 |     6214 | 2024-02-15 | HOTU                 | L   | 0.504      | -            | -                | -                | -         |    -3.89 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           15 |     6223 | 2024-02-15 | Team Spirit Academy  | L   | 0.504      | -            | -                | -                | -         |    -5.22 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           14 |     6233 | 2024-02-15 | Zero Tenacity        | L   | 0.503      | -            | -                | -                | -         |    -1.69 | Basso, fierre, Svedjehed, szejn, vigg0    |
|           13 |     6535 | 2024-02-08 | WOPA Esport          | L   | 0.455      | -            | -                | -                | -         |    -4.58 | Basso, mupzG, smF, Svedjehed, szejn       |
|           12 |     6597 | 2024-02-05 | IMMAPROBLEM          | L   | 0.438      | -            | -                | -                | -         |    -9.37 | Basso, smF, Svedjehed, szejn, vigg0       |
|           11 |     6614 | 2024-02-05 | XI Esport            | L   | 0.438      | -            | -                | -                | -         |    -6.89 | Basso, smF, Svedjehed, szejn, vigg0       |
|           10 |     6639 | 2024-02-05 | brazylijski luz      | L   | 0.436      | -            | -                | -                | -         |    -4.40 | Basso, mupzG, smF, Svedjehed, szejn       |
|            9 |     6867 | 2024-02-01 | Preasy Esport        | W   | 0.411      | 0.143        | 0.008 (0.000)    | 0.705 (0.041)    | -         |     9.47 | Basso, smF, Svedjehed, szejn, vigg0       |
|            8 |     6961 | 2024-01-30 | Astralis Talent      | L   | 0.398      | -            | -                | -                | -         |    -2.50 | Basso, smF, Svedjehed, szejn, vigg0       |
|            7 |     6972 | 2024-01-30 | WOPA Esport          | L   | 0.398      | -            | -                | -                | -         |    -3.98 | Basso, smF, Svedjehed, szejn, vigg0       |
|            6 |     7342 | 2024-01-24 | GenOne               | W   | 0.358      | 0.371        | -                | 0.442 (0.059)    | -         |     5.17 | fierre, Svedjehed, szejn, tooizera, vigg0 |
|            5 |     7409 | 2024-01-23 | Golden Sword         | W   | 0.351      | -            | -                | -                | -         |     2.00 | Basso, fierre, Svedjehed, szejn, tooizera |
|            4 |     7449 | 2024-01-22 | Sashi Esport         | W   | 0.345      | 0.143        | 0.024 (0.001)    | -                | -         |     7.15 | Basso, smF, Svedjehed, szejn, vigg0       |
|            3 |     7474 | 2024-01-22 | Team Atlantic        | W   | 0.344      | -            | -                | -                | -         |     3.38 | Basso, smF, Svedjehed, szejn, vigg0       |
|            2 |     7786 | 2024-01-17 | Natus Vincere Junior | L   | 0.311      | -            | -                | -                | -         |    -3.21 | Basso, mupzG, Svedjehed, szejn, vigg0     |
|            1 |     7820 | 2024-01-17 | Lilmix               | W   | 0.311      | -            | -                | -                | -         |     3.70 | Basso, mupzG, Svedjehed, szejn, vigg0     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
