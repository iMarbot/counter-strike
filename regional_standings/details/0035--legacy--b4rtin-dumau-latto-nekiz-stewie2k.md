### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, Stewie2K<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [35](../standings_global.md)<br />
Regional Rank: [7]( ../standings_americas.md)<br />
Final Rank Value:  1164.7<br />
<br />
Final Rank Value (1164.7) = Starting Rank Value (1134.0) + Head To Head Adjustments (30.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.451[<sup>1</sup>](#table2)
- Bounty Collected: 0.466[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.456[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1134.0
- 400 + ( ( 0.370 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1134.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |      795 | 2024-04-19 | M80              | L   | 1.000      | -            | -                | -                | -             |   -11.85 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           29 |      858 | 2024-04-18 | Elevate          | W   | 1.000      | 0.143        | 0.030 (0.004)    | 0.268 (0.038)    | false (0.000) |     3.85 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           28 |      863 | 2024-04-18 | Team Liquid      | L   | 1.000      | -            | -                | -                | -             |    -6.43 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           27 |     2032 | 2024-03-20 | The MongolZ      | L   | 0.890      | -            | -                | -                | -             |    -2.40 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           26 |     2065 | 2024-03-19 | Apeks            | W   | 0.884      | 1.000        | 0.253 (0.224)    | 0.459 (0.406)    | true (0.884)  |    20.85 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           25 |     2101 | 2024-03-18 | GamerLegion      | L   | 0.877      | -            | -                | -                | -             |    -3.22 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           24 |     2118 | 2024-03-17 | Cloud9           | L   | 0.873      | -            | -                | -                | -             |    -1.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           23 |     2137 | 2024-03-17 | FURIA Esports    | W   | 0.871      | 1.000        | 0.384 (0.335)    | 0.361 (0.315)    | true (0.871)  |    25.31 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           22 |     2757 | 2024-03-04 | M80              | W   | 0.785      | 0.143        | 0.155 (0.017)    | 0.405 (0.045)    | true (0.785)  |    16.97 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           21 |     2778 | 2024-03-03 | MIBR             | W   | 0.779      | 0.143        | 0.654 (0.073)    | 0.616 (0.069)    | true (0.779)  |    23.01 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           20 |     2836 | 2024-03-02 | Nouns Esports    | W   | 0.773      | 0.143        | -                | 0.475 (0.052)    | true (0.773)  |     2.61 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           19 |     4451 | 2024-01-22 | Sharks Esports   | L   | 0.507      | -            | -                | -                | -             |   -12.15 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           18 |     4534 | 2024-01-20 | RED Canids       | W   | 0.492      | 0.143        | 0.108 (0.008)    | 0.532 (0.037)    | false (0.000) |     4.43 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           17 |     4595 | 2024-01-19 | 9z Team          | W   | 0.486      | 0.143        | 0.057 (0.004)    | 0.376 (0.026)    | false (0.000) |     4.86 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           16 |     4770 | 2024-01-16 | RED Canids       | L   | 0.467      | -            | -                | -                | -             |   -10.62 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           15 |     4779 | 2024-01-16 | Imperial Esports | W   | 0.466      | 0.143        | 0.674 (0.045)    | 0.549 (0.037)    | false (0.000) |    13.81 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           14 |     4826 | 2024-01-15 | Galorys          | W   | 0.460      | 0.143        | 0.048 (0.003)    | 0.598 (0.039)    | false (0.000) |     3.24 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           13 |     4866 | 2024-01-14 | RED Canids       | L   | 0.453      | -            | -                | -                | -             |   -10.47 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           12 |     5066 | 2024-01-09 | Flamengo Esports | L   | 0.421      | -            | -                | -                | -             |   -12.68 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           11 |     5146 | 2024-01-08 | 4i20 Friends     | W   | 0.414      | -            | -                | -                | -             |     0.23 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           10 |     6109 | 2023-12-02 | RED Canids       | L   | 0.165      | -            | -                | -                | -             |    -3.95 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            9 |     6169 | 2023-12-01 | TSM              | L   | 0.157      | -            | -                | -                | -             |    -4.50 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     6194 | 2023-11-30 | 9Pandas          | L   | 0.152      | -            | -                | -                | -             |    -2.35 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     6381 | 2023-11-27 | Zero Tenacity    | L   | 0.130      | -            | -                | -                | -             |    -2.93 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     6396 | 2023-11-26 | SAW              | L   | 0.124      | -            | -                | -                | -             |    -0.47 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     6812 | 2023-11-16 | 9Pandas          | L   | 0.059      | -            | -                | -                | -             |    -0.92 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     6845 | 2023-11-16 | SINNERS Esports  | L   | 0.056      | -            | -                | -                | -             |    -1.23 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     6926 | 2023-11-14 | Endpoint         | W   | 0.045      | 0.589        | 0.005 (0.000)    | -                | -             |     0.24 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     6983 | 2023-11-13 | 9Pandas          | L   | 0.037      | -            | -                | -                | -             |    -0.59 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     7007 | 2023-11-12 | Endpoint         | L   | 0.031      | -            | -                | -                | -             |    -0.81 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,652.31)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
