### Roster Details<br />
Team Name: Case Esports<br />
Roster: RCF, snow, souz4h, yepz, zmb<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [225](../standings_global.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
Final Rank Value:  705.1<br />
<br />
Final Rank Value (705.1) = Starting Rank Value (678.2) + Head To Head Adjustments (26.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.2
- 400 + ( ( 0.137 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 678.2


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
|           34 |     7257 | 2024-01-21 | paiN Gaming               | L   | 0.339      | -            | -                | -                | -         |    -0.07 | RCF, snow, souz4h, yepz, zmb |
|           33 |     7270 | 2024-01-21 | Fluxo                     | W   | 0.337      | 0.143        | 0.065 (0.003)    | 0.474 (0.023)    | 0 (0.000) |     8.76 | RCF, snow, souz4h, yepz, zmb |
|           32 |     7305 | 2024-01-20 | adalYamigos               | W   | 0.332      | 0.143        | -                | 0.177 (0.008)    | 0 (0.000) |     4.76 | RCF, snow, souz4h, yepz, zmb |
|           31 |     7384 | 2024-01-19 | w7m esports               | L   | 0.326      | -            | -                | -                | -         |    -3.98 | RCF, snow, souz4h, yepz, zmb |
|           30 |     7399 | 2024-01-19 | RED Canids                | L   | 0.324      | -            | -                | -                | -         |    -1.59 | RCF, snow, souz4h, yepz, zmb |
|           29 |     7619 | 2024-01-16 | RED Canids                | L   | 0.305      | -            | -                | -                | -         |    -1.50 | RCF, snow, souz4h, yepz, zmb |
|           28 |     7626 | 2024-01-16 | paiN Gaming               | W   | 0.305      | 0.143        | 0.463 (0.020)    | 0.524 (0.023)    | 0 (0.000) |     9.56 | RCF, snow, souz4h, yepz, zmb |
|           27 |     7645 | 2024-01-16 | Hype Esports              | W   | 0.304      | 0.143        | -                | 0.054 (0.002)    | 0 (0.000) |     2.45 | RCF, snow, souz4h, yepz, zmb |
|           26 |     7770 | 2024-01-13 | w7m esports               | L   | 0.286      | -            | -                | -                | -         |    -3.47 | RCF, snow, souz4h, yepz, zmb |
|           25 |     7912 | 2024-01-11 | Galorys                   | L   | 0.272      | -            | -                | -                | -         |    -2.50 | RCF, snow, souz4h, yepz, zmb |
|           24 |     7918 | 2024-01-11 | Arena Jogue Fácil Esports | W   | 0.272      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.35 | RCF, snow, souz4h, yepz, zmb |
|           23 |     7925 | 2024-01-11 | Hype Esports              | W   | 0.271      | -            | -                | -                | 0 (0.000) |     2.20 | RCF, snow, souz4h, yepz, zmb |
|           22 |     7977 | 2024-01-10 | rebanho de naotransas     | W   | 0.266      | -            | -                | -                | 0 (0.000) |     1.40 | RCF, snow, souz4h, yepz, zmb |
|           21 |     8060 | 2024-01-09 | Flamengo Esports          | L   | 0.258      | -            | -                | -                | -         |    -5.83 | RCF, snow, souz4h, yepz, zmb |
|           20 |     8068 | 2024-01-09 | Yawara E-Sports           | W   | 0.258      | 0.143        | 0.002 (0.000)    | 0.319 (0.012)    | 0 (0.000) |     4.15 | RCF, snow, souz4h, yepz, zmb |
|           19 |     8164 | 2024-01-08 | KAMAV                     | W   | 0.253      | -            | -                | -                | 0 (0.000) |     1.33 | RCF, snow, souz4h, yepz, zmb |
|           18 |     8329 | 2023-12-23 | ODDIK                     | L   | 0.144      | -            | -                | -                | -         |    -0.90 | RCF, snow, souz4h, yepz, zmb |
|           17 |     8331 | 2023-12-23 | Team Solid                | W   | 0.143      | 0.303        | 0.062 (0.003)    | 0.332 (0.014)    | 0 (0.000) |     3.35 | RCF, snow, souz4h, yepz, zmb |
|           16 |     8368 | 2023-12-21 | Flamengo Esports          | W   | 0.131      | 0.303        | -                | 0.080 (0.003)    | -         |     1.18 | RCF, snow, souz4h, yepz, zmb |
|           15 |     8380 | 2023-12-20 | ODDIK                     | L   | 0.124      | -            | -                | -                | -         |    -0.77 | RCF, snow, souz4h, yepz, zmb |
|           14 |     8432 | 2023-12-17 | Team Solid                | L   | 0.106      | -            | -                | -                | -         |    -0.86 | RCF, snow, souz4h, yepz, zmb |
|           13 |     8440 | 2023-12-17 | VELOX Argentina           | W   | 0.105      | -            | -                | -                | -         |     1.19 | RCF, snow, souz4h, yepz, zmb |
|           12 |     8551 | 2023-12-16 | w7m esports               | L   | 0.099      | -            | -                | -                | -         |    -1.20 | RCF, snow, souz4h, yepz, zmb |
|           11 |     8716 | 2023-12-15 | Corinthians Esports       | W   | 0.092      | 0.143        | 0.000 (0.000)    | -                | -         |     1.19 | RCF, snow, souz4h, yepz, zmb |
|           10 |     8737 | 2023-12-15 | Flamengo Esports          | W   | 0.091      | 0.303        | -                | 0.080 (0.002)    | -         |     0.81 | RCF, snow, souz4h, yepz, zmb |
|            9 |     8773 | 2023-12-14 | TIMACETA                  | W   | 0.085      | 0.262        | 0.000 (0.000)    | -                | -         |     1.14 | RCF, snow, souz4h, yepz, zmb |
|            8 |     8809 | 2023-12-13 | w7m esports               | W   | 0.079      | 0.143        | 0.003 (0.000)    | 0.259 (0.003)    | -         |     1.56 | RCF, snow, souz4h, yepz, zmb |
|            7 |     8810 | 2023-12-13 | Arena Jogue Fácil Esports | L   | 0.079      | -            | -                | -                | -         |    -1.50 | RCF, snow, souz4h, yepz, zmb |
|            6 |     8833 | 2023-12-13 | 2Game Esports             | W   | 0.077      | 0.262        | 0.003 (0.000)    | 0.212 (0.004)    | -         |     1.30 | RCF, snow, souz4h, yepz, zmb |
|            5 |     8862 | 2023-12-12 | Dusty Roots               | W   | 0.072      | -            | -                | -                | -         |     0.81 | RCF, snow, souz4h, yepz, zmb |
|            4 |     8918 | 2023-12-11 | CEBOLOS                   | W   | 0.064      | -            | -                | -                | -         |     0.75 | RCF, snow, souz4h, yepz, zmb |
|            3 |     9262 | 2023-12-05 | Team Solid                | L   | 0.025      | -            | -                | -                | -         |    -0.20 | RCF, snow, souz4h, yepz, zmb |
|            2 |     9359 | 2023-12-03 | Sharks Esports            | L   | 0.011      | -            | -                | -                | -         |    -0.08 | RCF, snow, souz4h, yepz, zmb |
|            1 |     9433 | 2023-12-02 | Team Solid                | W   | 0.005      | 0.143        | 0.062 (0.000)    | -                | -         |     0.12 | RCF, snow, souz4h, yepz, zmb |

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
