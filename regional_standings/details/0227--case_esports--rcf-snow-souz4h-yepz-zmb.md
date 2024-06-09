### Roster Details<br />
Team Name: Case Esports<br />
Roster: RCF, snow, souz4h, yepz, zmb<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [227](../standings_global.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
Final Rank Value:  704.6<br />
<br />
Final Rank Value (704.6) = Starting Rank Value (677.8) + Head To Head Adjustments (26.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 677.8
- 400 + ( ( 0.137 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 677.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |     7500 | 2024-01-21 | paiN Gaming               | L   | 0.339      | -            | -                | -                | -         |    -0.07 | RCF, snow, souz4h, yepz, zmb |
|           33 |     7513 | 2024-01-21 | Fluxo                     | W   | 0.337      | 0.143        | 0.065 (0.003)    | 0.474 (0.023)    | 0 (0.000) |     8.74 | RCF, snow, souz4h, yepz, zmb |
|           32 |     7548 | 2024-01-20 | adalYamigos               | W   | 0.332      | 0.143        | -                | 0.177 (0.008)    | 0 (0.000) |     4.76 | RCF, snow, souz4h, yepz, zmb |
|           31 |     7628 | 2024-01-19 | w7m esports               | L   | 0.326      | -            | -                | -                | -         |    -4.03 | RCF, snow, souz4h, yepz, zmb |
|           30 |     7643 | 2024-01-19 | RED Canids                | L   | 0.324      | -            | -                | -                | -         |    -1.61 | RCF, snow, souz4h, yepz, zmb |
|           29 |     7868 | 2024-01-16 | RED Canids                | L   | 0.305      | -            | -                | -                | -         |    -1.52 | RCF, snow, souz4h, yepz, zmb |
|           28 |     7875 | 2024-01-16 | paiN Gaming               | W   | 0.305      | 0.143        | 0.463 (0.020)    | 0.547 (0.024)    | 0 (0.000) |     9.56 | RCF, snow, souz4h, yepz, zmb |
|           27 |     7894 | 2024-01-16 | Hype Esports              | W   | 0.304      | 0.143        | -                | 0.054 (0.002)    | 0 (0.000) |     2.45 | RCF, snow, souz4h, yepz, zmb |
|           26 |     8023 | 2024-01-13 | w7m esports               | L   | 0.286      | -            | -                | -                | -         |    -3.52 | RCF, snow, souz4h, yepz, zmb |
|           25 |     8165 | 2024-01-11 | Galorys                   | L   | 0.272      | -            | -                | -                | -         |    -2.54 | RCF, snow, souz4h, yepz, zmb |
|           24 |     8171 | 2024-01-11 | Arena Jogue Fácil Esports | W   | 0.272      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.35 | RCF, snow, souz4h, yepz, zmb |
|           23 |     8178 | 2024-01-11 | Hype Esports              | W   | 0.271      | -            | -                | -                | 0 (0.000) |     2.20 | RCF, snow, souz4h, yepz, zmb |
|           22 |     8231 | 2024-01-10 | rebanho de naotransas     | W   | 0.266      | -            | -                | -                | 0 (0.000) |     1.41 | RCF, snow, souz4h, yepz, zmb |
|           21 |     8314 | 2024-01-09 | Flamengo Esports          | L   | 0.258      | -            | -                | -                | -         |    -5.82 | RCF, snow, souz4h, yepz, zmb |
|           20 |     8322 | 2024-01-09 | Yawara E-Sports           | W   | 0.258      | 0.143        | 0.002 (0.000)    | 0.319 (0.012)    | 0 (0.000) |     4.16 | RCF, snow, souz4h, yepz, zmb |
|           19 |     8418 | 2024-01-08 | KAMAV                     | W   | 0.253      | -            | -                | -                | 0 (0.000) |     1.33 | RCF, snow, souz4h, yepz, zmb |
|           18 |     8586 | 2023-12-23 | ODDIK                     | L   | 0.144      | -            | -                | -                | -         |    -0.90 | RCF, snow, souz4h, yepz, zmb |
|           17 |     8588 | 2023-12-23 | Team Solid                | W   | 0.143      | 0.303        | 0.062 (0.003)    | 0.334 (0.015)    | 0 (0.000) |     3.36 | RCF, snow, souz4h, yepz, zmb |
|           16 |     8625 | 2023-12-21 | Flamengo Esports          | W   | 0.131      | 0.303        | -                | 0.080 (0.003)    | -         |     1.18 | RCF, snow, souz4h, yepz, zmb |
|           15 |     8637 | 2023-12-20 | ODDIK                     | L   | 0.124      | -            | -                | -                | -         |    -0.77 | RCF, snow, souz4h, yepz, zmb |
|           14 |     8689 | 2023-12-17 | Team Solid                | L   | 0.106      | -            | -                | -                | -         |    -0.86 | RCF, snow, souz4h, yepz, zmb |
|           13 |     8698 | 2023-12-17 | VELOX Argentina           | W   | 0.105      | -            | -                | -                | -         |     1.19 | RCF, snow, souz4h, yepz, zmb |
|           12 |     8811 | 2023-12-16 | w7m esports               | L   | 0.099      | -            | -                | -                | -         |    -1.21 | RCF, snow, souz4h, yepz, zmb |
|           11 |     8977 | 2023-12-15 | Corinthians Esports       | W   | 0.092      | 0.143        | 0.000 (0.000)    | -                | -         |     1.19 | RCF, snow, souz4h, yepz, zmb |
|           10 |     8998 | 2023-12-15 | Flamengo Esports          | W   | 0.091      | 0.303        | -                | 0.080 (0.002)    | -         |     0.81 | RCF, snow, souz4h, yepz, zmb |
|            9 |     9036 | 2023-12-14 | TIMACETA                  | W   | 0.085      | 0.262        | 0.000 (0.000)    | -                | -         |     1.14 | RCF, snow, souz4h, yepz, zmb |
|            8 |     9072 | 2023-12-13 | w7m esports               | W   | 0.079      | 0.143        | 0.003 (0.000)    | 0.274 (0.003)    | -         |     1.54 | RCF, snow, souz4h, yepz, zmb |
|            7 |     9073 | 2023-12-13 | Arena Jogue Fácil Esports | L   | 0.079      | -            | -                | -                | -         |    -1.51 | RCF, snow, souz4h, yepz, zmb |
|            6 |     9097 | 2023-12-13 | 2Game Esports             | W   | 0.077      | 0.262        | 0.003 (0.000)    | 0.212 (0.004)    | -         |     1.29 | RCF, snow, souz4h, yepz, zmb |
|            5 |     9126 | 2023-12-12 | Dusty Roots               | W   | 0.072      | -            | -                | -                | -         |     0.81 | RCF, snow, souz4h, yepz, zmb |
|            4 |     9184 | 2023-12-11 | Corinthians Esports       | W   | 0.064      | -            | -                | -                | -         |     0.79 | RCF, snow, souz4h, yepz, zmb |
|            3 |     9544 | 2023-12-05 | Team Solid                | L   | 0.025      | -            | -                | -                | -         |    -0.20 | RCF, snow, souz4h, yepz, zmb |
|            2 |     9641 | 2023-12-03 | Sharks Esports            | L   | 0.011      | -            | -                | -                | -         |    -0.08 | RCF, snow, souz4h, yepz, zmb |
|            1 |     9715 | 2023-12-02 | Team Solid                | W   | 0.005      | 0.143        | 0.062 (0.000)    | -                | -         |     0.12 | RCF, snow, souz4h, yepz, zmb |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($397.62)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.144 | $1,500.00      | $216.39         |
| 2023-12-18 |      0.110 | $1,089.86      | $119.58         |
| 2023-12-17 |      0.106 | $500.00        | $52.85          |
| 2023-12-03 |      0.011 | $812.49        | $8.80           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
