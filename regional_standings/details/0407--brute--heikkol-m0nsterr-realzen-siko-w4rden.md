### Roster Details<br />
Team Name: BRUTE<br />
Roster: heikkoL, m0nsterr, realzen, SiKO, w4rden<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [407](../standings_global.md)<br />
Regional Rank: [244]( ../standings_europe.md)<br />
Final Rank Value:  544.3<br />
<br />
Final Rank Value (544.3) = Starting Rank Value (550.9) + Head To Head Adjustments (-6.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.074<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 550.9
- 400 + ( ( 0.074 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 550.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      779 | 2024-05-19 | Dynamo Eclot          | L   | 1.000      | -            | -                | -                | -         |    -3.16 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           25 |      997 | 2024-05-17 | UNiTY esports         | L   | 1.000      | -            | -                | -                | -         |    -4.14 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           24 |     1088 | 2024-05-16 | Dynamo Eclot          | W   | 1.000      | 0.143        | 0.097 (0.014)    | 0.936 (0.134)    | 0 (0.000) |    28.83 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           23 |     1317 | 2024-05-13 | MASONIC               | L   | 1.000      | -            | -                | -                | -         |    -4.67 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           22 |     1384 | 2024-05-12 | SINNERS Academy       | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.227 (0.032)    | 0 (0.000) |    20.91 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           21 |     1460 | 2024-05-11 | Dynamo Eclot Thunders | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.026 (0.004)    | 0 (0.000) |    10.09 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           20 |     1570 | 2024-05-09 | SINNERS Academy       | L   | 1.000      | -            | -                | -                | -         |    -9.12 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           19 |     2413 | 2024-04-23 | EP Genesis            | L   | 0.957      | -            | -                | -                | -         |   -13.64 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           18 |     2708 | 2024-04-19 | Dynamo Eclot Thunders | L   | 0.929      | -            | -                | -                | -         |   -20.49 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           17 |     3409 | 2024-04-06 | Verdant               | L   | 0.842      | -            | -                | -                | -         |    -2.54 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           16 |     3611 | 2024-04-02 | ROSOMAHA              | L   | 0.815      | -            | -                | -                | -         |   -11.67 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           15 |     3889 | 2024-03-26 | Natus Vincere Junior  | L   | 0.771      | -            | -                | -                | -         |    -7.24 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           14 |     4036 | 2024-03-22 | Sashi Academy         | L   | 0.743      | -            | -                | -                | -         |    -8.80 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           13 |     4809 | 2024-03-07 | GamerLegion Academy   | L   | 0.644      | -            | -                | -                | -         |    -4.31 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           12 |     4876 | 2024-03-06 | Team Universe         | L   | 0.637      | -            | -                | -                | -         |   -12.32 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           11 |     5034 | 2024-03-04 | Sashi Academy         | W   | 0.624      | 0.289        | 0.001 (0.000)    | 0.088 (0.016)    | 0 (0.000) |    12.10 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|           10 |     5038 | 2024-03-04 | Dynamo Eclot          | L   | 0.624      | -            | -                | -                | -         |    -0.97 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            9 |     5077 | 2024-03-03 | SINNERS Academy       | L   | 0.618      | -            | -                | -                | -         |    -8.18 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            8 |     5262 | 2024-02-29 | VENI VIDI VICI        | W   | 0.598      | 0.143        | 0.001 (0.000)    | 0.075 (0.006)    | 0 (0.000) |    10.55 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            7 |     5322 | 2024-02-28 | Preasy Esport         | W   | 0.590      | 0.289        | 0.008 (0.001)    | 0.642 (0.110)    | 0 (0.000) |    15.03 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            6 |     5372 | 2024-02-27 | EP Genesis            | L   | 0.584      | -            | -                | -                | -         |    -9.94 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            5 |     5415 | 2024-02-26 | SINNERS Academy       | W   | 0.577      | 0.143        | 0.001 (0.000)    | 0.227 (0.019)    | 0 (0.000) |    11.11 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            4 |     5526 | 2024-02-24 | Sampi NEXT            | W   | 0.564      | 0.289        | 0.000 (0.000)    | 0.055 (0.009)    | 0 (0.000) |     7.44 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            3 |     7114 | 2024-01-24 | Sashi Academy         | L   | 0.357      | -            | -                | -                | -         |    -4.16 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            2 |     7276 | 2024-01-21 | Preasy Esport         | L   | 0.337      | -            | -                | -                | -         |    -1.49 | heikkoL, m0nsterr, realzen, SiKO, w4rden |
|            1 |     7570 | 2024-01-17 | EPIC DUDES            | W   | 0.311      | 0.289        | 0.000 (0.000)    | 0.048 (0.004)    | 0 (0.000) |     4.11 | heikkoL, m0nsterr, realzen, SiKO, w4rden |

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
