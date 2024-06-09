### Roster Details<br />
Team Name: GamerLegion<br />
Roster: acoR, isak, Keoz, Snax, volt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [30](../standings_global.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
Final Rank Value:  1248.8<br />
<br />
Final Rank Value (1248.8) = Starting Rank Value (1218.1) + Head To Head Adjustments (30.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.470[<sup>1</sup>](#table2)
- Bounty Collected: 0.451[<sup>2</sup>](#table1)
- Opponent Network: 0.137[<sup>2</sup>](#table1)
- LAN Wins: 0.552[<sup>2</sup>](#table1)

The average of these factors is 0.403<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1218.1
- 400 + ( ( 0.403 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1218.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     4240 | 2024-03-20 | Imperial Esports  | L   | 0.730      | -            | -                | -                | -         |    -5.13 | acoR, isak, Keoz, Snax, volt |
|           25 |     4284 | 2024-03-19 | Eternal Fire      | L   | 0.723      | -            | -                | -                | -         |    -0.89 | acoR, isak, Keoz, Snax, volt |
|           24 |     4323 | 2024-03-18 | Legacy            | W   | 0.716      | 1.000        | 0.027 (0.019)    | 0.307 (0.220)    | 1 (0.716) |     6.32 | acoR, isak, Keoz, Snax, volt |
|           23 |     4338 | 2024-03-17 | SAW               | L   | 0.712      | -            | -                | -                | -         |    -7.01 | acoR, isak, Keoz, Snax, volt |
|           22 |     4379 | 2024-03-17 | AMKAL ESPORTS     | W   | 0.710      | 1.000        | 0.146 (0.104)    | 0.565 (0.401)    | 1 (0.710) |     8.46 | acoR, isak, Keoz, Snax, volt |
|           21 |     4878 | 2024-03-08 | BIG               | L   | 0.650      | -            | -                | -                | -         |    -6.64 | acoR, isak, Keoz, Snax, volt |
|           20 |     5705 | 2024-02-24 | 9Pandas           | L   | 0.563      | -            | -                | -                | -         |   -10.56 | acoR, isak, Keoz, Snax, volt |
|           19 |     5727 | 2024-02-24 | ex-Guild Eagles   | W   | 0.562      | 0.143        | 0.015 (0.001)    | 0.475 (0.038)    | 1 (0.562) |     3.25 | acoR, isak, Keoz, Snax, volt |
|           18 |     5770 | 2024-02-23 | Fnatic            | W   | 0.557      | 0.143        | 0.147 (0.012)    | 0.480 (0.038)    | 1 (0.557) |     5.53 | acoR, isak, Keoz, Snax, volt |
|           17 |     5817 | 2024-02-22 | HEROIC            | L   | 0.550      | -            | -                | -                | -         |    -1.11 | acoR, isak, Keoz, Snax, volt |
|           16 |     5883 | 2024-02-21 | OG                | W   | 0.543      | 0.143        | 0.277 (0.021)    | 0.257 (0.020)    | 1 (0.543) |     6.79 | acoR, isak, Keoz, Snax, volt |
|           15 |     5953 | 2024-02-20 | ENCE              | L   | 0.536      | -            | -                | -                | -         |    -4.18 | acoR, isak, Keoz, Snax, volt |
|           14 |     6005 | 2024-02-19 | Pera Esports      | W   | 0.530      | 0.143        | 0.028 (0.002)    | 0.542 (0.041)    | 1 (0.530) |     2.44 | acoR, isak, Keoz, Snax, volt |
|           13 |     6023 | 2024-02-19 | Team Vitality     | L   | 0.529      | -            | -                | -                | -         |    -0.64 | acoR, isak, Keoz, Snax, volt |
|           12 |     6582 | 2024-02-06 | HEROIC            | L   | 0.443      | -            | -                | -                | -         |    -0.83 | acoR, isak, Keoz, Snax, volt |
|           11 |     6632 | 2024-02-05 | MOUZ              | L   | 0.437      | -            | -                | -                | -         |    -0.25 | acoR, isak, Keoz, Snax, volt |
|           10 |     6674 | 2024-02-04 | Monte             | W   | 0.429      | 1.000        | 0.181 (0.078)    | 0.387 (0.166)    | 1 (0.429) |     8.06 | acoR, isak, Keoz, Snax, volt |
|            9 |     6895 | 2024-02-01 | Virtus.pro        | W   | 0.409      | 1.000        | 0.271 (0.111)    | 0.331 (0.136)    | 1 (0.409) |    12.00 | acoR, isak, Keoz, Snax, volt |
|            8 |     6927 | 2024-01-31 | M80               | W   | 0.404      | 1.000        | 0.136 (0.055)    | 0.525 (0.212)    | 1 (0.404) |     7.20 | acoR, isak, Keoz, Snax, volt |
|            7 |     7257 | 2024-01-26 | FaZe Clan         | L   | 0.370      | -            | -                | -                | -         |    -0.16 | acoR, isak, Keoz, Snax, volt |
|            6 |     7318 | 2024-01-25 | Team Liquid       | L   | 0.362      | -            | -                | -                | -         |    -0.93 | acoR, isak, Keoz, Snax, volt |
|            5 |     7375 | 2024-01-24 | FaZe Clan         | W   | 0.356      | 0.581        | 1.000 (0.207)    | 0.457 (0.094)    | 1 (0.356) |    11.06 | acoR, isak, Keoz, Snax, volt |
|            4 |     8975 | 2023-12-15 | Complexity Gaming | L   | 0.093      | -            | -                | -                | -         |    -0.37 | acoR, aNdu, isak, Keoz, Snax |
|            3 |     8997 | 2023-12-15 | Apeks             | L   | 0.091      | -            | -                | -                | -         |    -1.39 | acoR, aNdu, isak, Keoz, Snax |
|            2 |     9504 | 2023-12-06 | BetBoom Team      | L   | 0.031      | -            | -                | -                | -         |    -0.22 | acoR, isak, Keoz, Snax, volt |
|            1 |     9600 | 2023-12-05 | Cloud9            | L   | 0.022      | -            | -                | -                | -         |    -0.12 | acoR, isak, Keoz, Snax, volt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($22,467.04)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.804 | $10,000.00     | $8,038.89       |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-02-11 |      0.477 | $16,000.00     | $7,631.11       |
| 2024-01-28 |      0.384 | $8,500.00      | $3,264.24       |
| 2023-12-17 |      0.105 | $2,000.00      | $210.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
