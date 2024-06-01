### Roster Details<br />
Team Name: MIBR Female<br />
Roster: Babs, dani, ferzy, khizha, REGIANE<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [233](../standings_global.md)<br />
Regional Rank: [50]( ../standings_americas.md)<br />
Final Rank Value:  700.3<br />
<br />
Final Rank Value (700.3) = Starting Rank Value (721.6) + Head To Head Adjustments (-21.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.353[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 721.6
- 400 + ( ( 0.158 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 721.6


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
|           23 |      194 | 2024-05-26 | Atrix Esports           | W   | 1.000      | 0.250        | 0.006 (0.001)    | 0.190 (0.047)    | 0 (0.000) |    13.68 | Babs, dani, ferzy, khizha, REGIANE      |
|           22 |      250 | 2024-05-25 | Signatus                | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.27 | Babs, dani, ferzy, khizha, REGIANE      |
|           21 |     2156 | 2024-04-27 | pugdesonesto            | L   | 0.984      | -            | -                | -                | -         |   -20.31 | Babs, dani, history, khizha, REGIANE    |
|           20 |     2165 | 2024-04-27 | ODDIK Academy           | L   | 0.984      | -            | -                | -                | -         |   -19.49 | Babs, dani, history, khizha, REGIANE    |
|           19 |     2498 | 2024-04-21 | Fluxo Demons            | L   | 0.943      | -            | -                | -                | -         |    -8.76 | Babs, dani, ferzy, khizha, REGIANE      |
|           18 |     3105 | 2024-04-11 | w7m esports Female      | W   | 0.878      | 0.332        | 0.010 (0.003)    | 0.091 (0.027)    | 0 (0.000) |    11.17 | Babs, dani, ferzy, khizha, REGIANE      |
|           17 |     3363 | 2024-04-06 | Fluxo Demons            | W   | 0.845      | 0.250        | 0.026 (0.006)    | 0.264 (0.056)    | 0 (0.000) |    18.64 | Babs, dani, ferzy, khizha, REGIANE      |
|           16 |     3365 | 2024-04-06 | HUMBLE.gg               | W   | 0.845      | -            | -                | -                | 0 (0.000) |     4.19 | Babs, dani, ferzy, khizha, REGIANE      |
|           15 |     3480 | 2024-04-04 | Atrix Esports           | W   | 0.831      | 0.332        | 0.006 (0.002)    | 0.190 (0.052)    | 0 (0.000) |    12.68 | Babs, dani, ferzy, khizha, REGIANE      |
|           14 |     3727 | 2024-03-28 | Illusion                | W   | 0.785      | 0.332        | 0.003 (0.001)    | 0.028 (0.007)    | 0 (0.000) |     9.69 | Babs, dani, ferzy, khizha, REGIANE      |
|           13 |     3972 | 2024-03-23 | Floripa Stars           | L   | 0.752      | -            | -                | -                | -         |   -12.95 | Babs, dani, ferzy, khizha, REGIANE      |
|           12 |     3976 | 2024-03-23 | MX Team                 | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.076 (0.008)    | 0 (0.000) |     8.91 | Babs, dani, ferzy, khizha, REGIANE      |
|           11 |     3983 | 2024-03-23 | ex-Martians             | L   | 0.751      | -            | -                | -                | -         |   -13.87 | Babs, dani, ferzy, khizha, REGIANE      |
|           10 |     3989 | 2024-03-23 | parece um barco andando | W   | 0.751      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | 0 (0.000) |     8.42 | Babs, dani, ferzy, khizha, REGIANE      |
|            9 |     4119 | 2024-03-20 | Fluxo Demons            | L   | 0.732      | -            | -                | -                | -         |    -6.64 | Babs, dani, ferzy, khizha, REGIANE      |
|            8 |     4463 | 2024-03-13 | FURIA Esports Female    | L   | 0.685      | -            | -                | -                | -         |    -7.95 | Babs, dani, ferzy, khizha, REGIANE      |
|            7 |     4787 | 2024-03-07 | ex-DIVINA Female        | W   | 0.645      | 0.332        | 0.004 (0.001)    | 0.053 (0.011)    | 0 (0.000) |     8.71 | Babs, dani, ferzy, khizha, REGIANE      |
|            6 |     5492 | 2024-02-24 | FURIA Esports Female    | L   | 0.565      | -            | -                | -                | -         |    -6.94 | Babs, dani, ferzy, khizha, REGIANE      |
|            5 |     5507 | 2024-02-24 | QUASE                   | L   | 0.564      | -            | -                | -                | -         |   -13.47 | Babs, dani, ferzy, khizha, REGIANE      |
|            4 |     5521 | 2024-02-24 | Hawks                   | L   | 0.564      | -            | -                | -                | -         |   -10.79 | Babs, dani, ferzy, khizha, REGIANE      |
|            3 |     6490 | 2024-02-03 | Fluxo Demons            | L   | 0.425      | -            | -                | -                | -         |    -4.47 | Babs, dani, ferzy, khizha, REGIANE      |
|            2 |     6898 | 2024-01-27 | DIVINA Female           | W   | 0.379      | 0.250        | 0.001 (0.000)    | 0.009 (0.001)    | -         |     2.91 | Babs, dani, ferzy, khizha, REGIANE      |
|            1 |     9432 | 2023-12-02 | DIVINA Female           | W   | 0.005      | 0.250        | 0.001 (0.000)    | 0.009 (0.000)    | -         |     0.04 | Babs, chjna4Q, ferzy, lulitenz, REGIANE |

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
