### Roster Details<br />
Team Name: FURIA Esports<br />
Roster: chelo, FalleN, KSCERATO, kye, yuurih<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [18](../standings_global.md)<br />
Regional Rank: [3]( ../standings_americas.md)<br />
Final Rank Value:  1445.6<br />
<br />
Final Rank Value (1445.6) = Starting Rank Value (1660.4) + Head To Head Adjustments (-214.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.706[<sup>1</sup>](#table2)
- Bounty Collected: 0.541[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.635<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1660.4
- 400 + ( ( 0.635 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1660.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       17 | 2024-05-05 | Monte              | L   | 1.000      | -            | -                | -                | -            |   -21.51 | chelo, FalleN, KSCERATO, kye, yuurih |
|           40 |       63 | 2024-05-04 | ENCE               | W   | 1.000      | 0.889        | 0.377 (0.335)    | 0.352 (0.313)    | true (1.000) |    12.83 | chelo, FalleN, KSCERATO, kye, yuurih |
|           39 |      110 | 2024-05-03 | Bad News Kangaroos | W   | 1.000      | 0.889        | 0.071 (0.063)    | 0.238 (0.212)    | true (1.000) |     1.70 | chelo, FalleN, KSCERATO, kye, yuurih |
|           38 |      195 | 2024-05-01 | FORZE Esports      | L   | 1.000      | -            | -                | -                | -            |   -27.03 | chelo, FalleN, KSCERATO, kye, yuurih |
|           37 |      234 | 2024-04-30 | Team Liquid        | L   | 1.000      | -            | -                | -                | -            |   -18.82 | chelo, FalleN, KSCERATO, kye, yuurih |
|           36 |      793 | 2024-04-19 | MIBR               | L   | 1.000      | -            | -                | -                | -            |   -12.03 | chelo, FalleN, KSCERATO, kye, yuurih |
|           35 |      834 | 2024-04-19 | Metizport          | W   | 1.000      | 0.589        | 0.188 (0.111)    | 1.000 (0.589)    | true (1.000) |     3.05 | chelo, FalleN, KSCERATO, kye, yuurih |
|           34 |      866 | 2024-04-18 | 9z Team            | L   | 1.000      | -            | -                | -                | -            |   -29.75 | chelo, FalleN, KSCERATO, kye, yuurih |
|           33 |     1307 | 2024-04-09 | HEROIC             | L   | 1.000      | -            | -                | -                | -            |   -11.49 | arT, chelo, FalleN, KSCERATO, yuurih |
|           32 |     1345 | 2024-04-08 | MOUZ               | L   | 1.000      | -            | -                | -                | -            |    -4.45 | arT, chelo, FalleN, KSCERATO, yuurih |
|           31 |     1358 | 2024-04-07 | Lynn Vision Gaming | W   | 1.000      | 0.624        | 0.155 (0.097)    | 0.554 (0.346)    | true (1.000) |     4.42 | arT, chelo, FalleN, KSCERATO, yuurih |
|           30 |     1934 | 2024-03-22 | Gaimin Gladiators  | L   | 0.905      | -            | -                | -                | -            |   -20.88 | arT, chelo, FalleN, KSCERATO, yuurih |
|           29 |     1964 | 2024-03-21 | FaZe Clan          | L   | 0.899      | -            | -                | -                | -            |    -3.01 | arT, chelo, FalleN, KSCERATO, yuurih |
|           28 |     1986 | 2024-03-21 | G2 Esports         | L   | 0.898      | -            | -                | -                | -            |    -4.26 | arT, chelo, FalleN, KSCERATO, yuurih |
|           27 |     2025 | 2024-03-20 | SAW                | W   | 0.892      | 1.000        | 0.263 (0.234)    | 0.590 (0.526)    | true (0.892) |    10.14 | arT, chelo, FalleN, KSCERATO, yuurih |
|           26 |     2057 | 2024-03-19 | ENCE               | W   | 0.885      | 1.000        | 0.377 (0.334)    | 0.352 (0.311)    | true (0.885) |    11.29 | arT, chelo, FalleN, KSCERATO, yuurih |
|           25 |     2089 | 2024-03-18 | KOI                | W   | 0.878      | 1.000        | 0.066 (0.058)    | 0.537 (0.472)    | true (0.878) |     2.07 | arT, chelo, FalleN, KSCERATO, yuurih |
|           24 |     2113 | 2024-03-17 | Lynn Vision Gaming | L   | 0.873      | -            | -                | -                | -            |   -23.14 | arT, chelo, FalleN, KSCERATO, yuurih |
|           23 |     2137 | 2024-03-17 | Legacy             | L   | 0.871      | -            | -                | -                | -            |   -25.31 | arT, chelo, FalleN, KSCERATO, yuurih |
|           22 |     2781 | 2024-03-03 | Complexity Gaming  | W   | 0.779      | -            | -                | -                | true (0.779) |     9.08 | arT, chelo, FalleN, KSCERATO, yuurih |
|           21 |     2871 | 2024-03-02 | Team Liquid        | W   | 0.772      | 0.143        | -                | 0.546 (0.060)    | true (0.772) |     5.81 | arT, chelo, FalleN, KSCERATO, yuurih |
|           20 |     2908 | 2024-03-01 | Nouns Esports      | W   | 0.766      | 0.143        | -                | 0.475 (0.052)    | true (0.766) |     0.19 | arT, chelo, FalleN, KSCERATO, yuurih |
|           19 |     3194 | 2024-02-23 | 9z Team            | L   | 0.720      | -            | -                | -                | -            |   -21.89 | arT, chelo, FalleN, KSCERATO, yuurih |
|           18 |     3230 | 2024-02-22 | 9z Team            | W   | 0.713      | -            | -                | -                | -            |     0.70 | arT, chelo, FalleN, KSCERATO, yuurih |
|           17 |     3237 | 2024-02-22 | Imperial Esports   | W   | 0.712      | 0.143        | 0.674 (0.069)    | 0.549 (0.056)    | -            |     9.52 | arT, chelo, FalleN, KSCERATO, yuurih |
|           16 |     3769 | 2024-02-10 | Metizport          | L   | 0.632      | -            | -                | -                | -            |   -19.10 | arT, chelo, FalleN, KSCERATO, yuurih |
|           15 |     3778 | 2024-02-10 | Metizport          | L   | 0.631      | -            | -                | -                | -            |   -19.22 | arT, chelo, FalleN, KSCERATO, yuurih |
|           14 |     4067 | 2024-02-01 | Apeks              | L   | 0.572      | -            | -                | -                | -            |   -14.45 | arT, chelo, FalleN, KSCERATO, yuurih |
|           13 |     4107 | 2024-01-31 | The MongolZ        | L   | 0.565      | -            | -                | -                | -            |    -9.63 | arT, chelo, FalleN, KSCERATO, yuurih |
|           12 |     5844 | 2023-12-08 | Team Spirit        | L   | 0.204      | -            | -                | -                | -            |    -1.76 | arT, chelo, FalleN, KSCERATO, yuurih |
|           11 |     5889 | 2023-12-07 | Astralis           | W   | 0.198      | -            | -                | -                | -            |     2.12 | arT, chelo, FalleN, KSCERATO, yuurih |
|           10 |     5940 | 2023-12-06 | Team Spirit        | L   | 0.191      | -            | -                | -                | -            |    -1.63 | arT, chelo, FalleN, KSCERATO, yuurih |
|            9 |     6041 | 2023-12-03 | Apeks              | W   | 0.171      | -            | -                | -                | -            |     1.07 | arT, chelo, FalleN, KSCERATO, yuurih |
|            8 |     6107 | 2023-12-02 | HAVU Gaming        | W   | 0.165      | -            | -                | -                | -            |     0.06 | arT, chelo, FalleN, KSCERATO, yuurih |
|            7 |     6160 | 2023-12-01 | MOUZ               | W   | 0.159      | 0.589        | 0.891 (0.083)    | -                | -            |     3.81 | arT, chelo, FalleN, KSCERATO, yuurih |
|            6 |     6210 | 2023-11-30 | Apeks              | L   | 0.151      | -            | -                | -                | -            |    -3.83 | arT, chelo, FalleN, KSCERATO, yuurih |
|            5 |     6217 | 2023-11-30 | Complexity Gaming  | W   | 0.151      | -            | -                | -                | -            |     1.59 | arT, chelo, FalleN, KSCERATO, yuurih |
|            4 |     6674 | 2023-11-19 | 9Pandas            | L   | 0.077      | -            | -                | -                | -            |    -2.32 | arT, chelo, FalleN, KSCERATO, yuurih |
|            3 |     6728 | 2023-11-18 | Aurora Gaming      | W   | 0.071      | 0.500        | 1.000 (0.035)    | -                | -            |     1.00 | arT, chelo, FalleN, KSCERATO, yuurih |
|            2 |     6774 | 2023-11-17 | Eternal Fire       | L   | 0.065      | -            | -                | -                | -            |    -0.65 | arT, chelo, FalleN, KSCERATO, yuurih |
|            1 |     6805 | 2023-11-16 | Aurora Gaming      | W   | 0.059      | -            | -                | -                | -            |     0.84 | arT, chelo, FalleN, KSCERATO, yuurih |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($60,852.89)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $12,000.00     | $12,000.00      |
| 2024-04-20 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-04-14 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-02-11 |      0.638 | $2,500.00      | $1,595.02       |
| 2023-12-03 |      0.171 | $100,000.00    | $17,106.48      |
| 2023-11-20 |      0.085 | $10,000.00     | $846.76         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
