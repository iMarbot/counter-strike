### Roster Details<br />
Team Name: MIBR Female<br />
Roster: Babs, dani, ferzy, khizha, REGIANE<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [232](../standings_global.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
Final Rank Value:  700.5<br />
<br />
Final Rank Value (700.5) = Starting Rank Value (721.1) + Head To Head Adjustments (-20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.1
- 400 + ( ( 0.158 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 721.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      202 | 2024-05-26 | Atrix Esports           | W   | 1.000      | 0.250        | 0.006 (0.001)    | 0.190 (0.047)    | 0 (0.000) |    13.63 | Babs, dani, ferzy, khizha, REGIANE      |
|           23 |      258 | 2024-05-25 | Signatus                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.26 | Babs, dani, ferzy, khizha, REGIANE      |
|           22 |     2191 | 2024-04-27 | pugdesonesto            | L   | 0.984      | -            | -                | -                | -         |   -20.52 | Babs, dani, history, khizha, REGIANE    |
|           21 |     2200 | 2024-04-27 | ODDIK Academy           | L   | 0.984      | -            | -                | -                | -         |   -19.60 | Babs, dani, history, khizha, REGIANE    |
|           20 |     2551 | 2024-04-21 | Fluxo Demons            | L   | 0.943      | -            | -                | -                | -         |    -8.79 | Babs, dani, ferzy, khizha, REGIANE      |
|           19 |     3171 | 2024-04-11 | w7m esports Female      | W   | 0.878      | 0.332        | 0.010 (0.003)    | 0.091 (0.027)    | 0 (0.000) |    11.13 | Babs, dani, ferzy, khizha, REGIANE      |
|           18 |     3446 | 2024-04-06 | Fluxo Demons            | W   | 0.845      | 0.250        | 0.026 (0.006)    | 0.264 (0.056)    | 0 (0.000) |    18.61 | Babs, dani, ferzy, khizha, REGIANE      |
|           17 |     3448 | 2024-04-06 | HUMBLE.gg               | W   | 0.845      | -            | -                | -                | 0 (0.000) |     4.18 | Babs, dani, ferzy, khizha, REGIANE      |
|           16 |     3565 | 2024-04-04 | Atrix Esports           | W   | 0.831      | 0.332        | 0.006 (0.002)    | 0.190 (0.052)    | 0 (0.000) |    12.64 | Babs, dani, ferzy, khizha, REGIANE      |
|           15 |     3821 | 2024-03-28 | Illusion                | W   | 0.785      | 0.332        | 0.003 (0.001)    | 0.028 (0.007)    | 0 (0.000) |     9.65 | Babs, dani, ferzy, khizha, REGIANE      |
|           14 |     4070 | 2024-03-23 | Floripa Stars           | L   | 0.752      | -            | -                | -                | -         |   -13.00 | Babs, dani, ferzy, khizha, REGIANE      |
|           13 |     4074 | 2024-03-23 | MX Team                 | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.076 (0.008)    | 0 (0.000) |     8.88 | Babs, dani, ferzy, khizha, REGIANE      |
|           12 |     4081 | 2024-03-23 | ex-Martians             | L   | 0.751      | -            | -                | -                | -         |   -13.91 | Babs, dani, ferzy, khizha, REGIANE      |
|           11 |     4086 | 2024-03-23 | parece um barco andando | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     8.38 | Babs, dani, ferzy, khizha, REGIANE      |
|           10 |     4219 | 2024-03-20 | Fluxo Demons            | L   | 0.732      | -            | -                | -                | -         |    -6.68 | Babs, dani, ferzy, khizha, REGIANE      |
|            9 |     4577 | 2024-03-13 | FURIA Esports Female    | L   | 0.685      | -            | -                | -                | -         |    -7.99 | Babs, dani, ferzy, khizha, REGIANE      |
|            8 |     4915 | 2024-03-07 | ex-DIVINA Female        | W   | 0.645      | 0.332        | 0.004 (0.001)    | 0.053 (0.011)    | 0 (0.000) |     8.67 | Babs, dani, ferzy, khizha, REGIANE      |
|            7 |     5652 | 2024-02-24 | FURIA Esports Female    | L   | 0.565      | -            | -                | -                | -         |    -6.97 | Babs, dani, ferzy, khizha, REGIANE      |
|            6 |     5667 | 2024-02-24 | QUASE                   | L   | 0.564      | -            | -                | -                | -         |   -13.49 | Babs, dani, ferzy, khizha, REGIANE      |
|            5 |     5681 | 2024-02-24 | Hawks                   | L   | 0.564      | -            | -                | -                | -         |   -10.83 | Babs, dani, ferzy, khizha, REGIANE      |
|            4 |     6693 | 2024-02-03 | Fluxo Demons            | L   | 0.425      | -            | -                | -                | -         |    -4.50 | Babs, dani, ferzy, khizha, REGIANE      |
|            3 |     7116 | 2024-01-27 | DIVINA Female           | W   | 0.379      | 0.250        | 0.001 (0.000)    | 0.009 (0.001)    | -         |     2.89 | Babs, dani, ferzy, khizha, REGIANE      |
|            2 |     7131 | 2024-01-27 | team_armk4m             | W   | 0.379      | -            | -                | -                | -         |     1.69 | Babs, dani, ferzy, khizha, REGIANE      |
|            1 |     9714 | 2023-12-02 | DIVINA Female           | W   | 0.005      | 0.250        | 0.001 (0.000)    | 0.009 (0.000)    | -         |     0.04 | Babs, chjna4Q, ferzy, lulitenz, REGIANE |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,437.03)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $750.00        | $750.00         |
| 2024-04-21 |      0.945 | $1,250.00      | $1,181.60       |
| 2024-04-19 |      0.931 | $1,700.00      | $1,583.13       |
| 2024-04-06 |      0.845 | $750.00        | $634.11         |
| 2024-01-27 |      0.379 | $750.00        | $284.44         |
| 2023-12-02 |      0.005 | $750.00        | $3.75           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
