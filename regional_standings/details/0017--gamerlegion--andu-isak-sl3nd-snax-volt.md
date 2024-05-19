### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, isak, sl3nd, Snax, volt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [17](../standings_global.md)<br />
Regional Rank: [14]( ../standings_europe.md)<br />
Final Rank Value:  1461.4<br />
<br />
Final Rank Value (1461.4) = Starting Rank Value (1593.6) + Head To Head Adjustments (-132.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.584[<sup>1</sup>](#table2)
- Bounty Collected: 0.585[<sup>2</sup>](#table1)
- Opponent Network: 0.327[<sup>2</sup>](#table1)
- LAN Wins: 0.911[<sup>2</sup>](#table1)

The average of these factors is 0.602<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1593.6
- 400 + ( ( 0.602 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1593.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |      111 | 2024-05-03 | ENCE                     | W   | 1.000      | 0.889        | 0.377 (0.335)    | 0.352 (0.313)    | true (1.000) |    13.67 | aNdu, isak, sl3nd, Snax, volt |
|           39 |      135 | 2024-05-02 | FORZE Esports            | W   | 1.000      | 0.889        | 0.210 (0.187)    | 0.574 (0.510)    | true (1.000) |     5.23 | aNdu, isak, sl3nd, Snax, volt |
|           38 |      207 | 2024-05-01 | MOUZ                     | L   | 1.000      | -            | -                | -                | -            |    -2.52 | aNdu, isak, sl3nd, Snax, volt |
|           37 |      250 | 2024-04-30 | ENCE                     | W   | 1.000      | 0.889        | 0.377 (0.335)    | 0.352 (0.313)    | true (1.000) |    14.42 | aNdu, isak, sl3nd, Snax, volt |
|           36 |      882 | 2024-04-18 | Sashi Esport             | L   | 1.000      | -            | -                | -                | -            |   -27.95 | aNdu, isak, sl3nd, Snax, volt |
|           35 |      925 | 2024-04-17 | Copenhagen Wolves        | W   | 1.000      | -            | -                | -                | -            |     0.32 | aNdu, isak, sl3nd, Snax, volt |
|           34 |     1009 | 2024-04-16 | MOUZ NXT                 | W   | 1.000      | 0.384        | 0.215 (0.083)    | 1.000 (0.384)    | -            |     3.05 | aNdu, isak, sl3nd, Snax, volt |
|           33 |     1573 | 2024-04-02 | Monte                    | L   | 0.978      | -            | -                | -                | -            |   -21.64 | aNdu, isak, sl3nd, Snax, volt |
|           32 |     1584 | 2024-04-02 | BLESSED (Ukrainian team) | L   | 0.977      | -            | -                | -                | -            |   -29.20 | aNdu, isak, sl3nd, Snax, volt |
|           31 |     1604 | 2024-04-01 | GUN5 Esports             | W   | 0.970      | -            | -                | -                | -            |     0.31 | aNdu, isak, sl3nd, Snax, volt |
|           30 |     2030 | 2024-03-20 | Imperial Esports         | L   | 0.891      | -            | -                | -                | -            |   -14.90 | acoR, isak, Keoz, Snax, volt  |
|           29 |     2069 | 2024-03-19 | Eternal Fire             | L   | 0.884      | -            | -                | -                | -            |    -5.39 | acoR, isak, Keoz, Snax, volt  |
|           28 |     2101 | 2024-03-18 | Legacy                   | W   | 0.877      | 1.000        | -                | 0.262 (0.230)    | true (0.877) |     3.22 | acoR, isak, Keoz, Snax, volt  |
|           27 |     2114 | 2024-03-17 | SAW                      | L   | 0.873      | -            | -                | -                | -            |   -15.09 | acoR, isak, Keoz, Snax, volt  |
|           26 |     2141 | 2024-03-17 | AMKAL ESPORTS            | W   | 0.871      | 1.000        | 0.209 (0.182)    | 0.756 (0.659)    | true (0.871) |     3.06 | acoR, isak, Keoz, Snax, volt  |
|           25 |     2530 | 2024-03-08 | BIG                      | L   | 0.811      | -            | -                | -                | -            |   -17.03 | acoR, isak, Keoz, Snax, volt  |
|           24 |     3162 | 2024-02-24 | 9Pandas                  | L   | 0.724      | -            | -                | -                | -            |   -20.65 | acoR, isak, Keoz, Snax, volt  |
|           23 |     3182 | 2024-02-24 | Guild Eagles             | W   | 0.723      | -            | -                | -                | true (0.723) |     1.37 | acoR, isak, Keoz, Snax, volt  |
|           22 |     3215 | 2024-02-23 | Fnatic                   | W   | 0.718      | -            | -                | -                | true (0.718) |     2.77 | acoR, isak, Keoz, Snax, volt  |
|           21 |     3253 | 2024-02-22 | HEROIC                   | L   | 0.711      | -            | -                | -                | -            |    -7.65 | acoR, isak, Keoz, Snax, volt  |
|           20 |     3314 | 2024-02-21 | OG                       | W   | 0.704      | 0.143        | 0.594 (0.060)    | -                | true (0.704) |     3.96 | acoR, isak, Keoz, Snax, volt  |
|           19 |     3371 | 2024-02-20 | ENCE                     | L   | 0.697      | -            | -                | -                | -            |   -11.82 | acoR, isak, Keoz, Snax, volt  |
|           18 |     3412 | 2024-02-19 | Pera Esports             | W   | 0.691      | -            | -                | -                | true (0.691) |     0.66 | acoR, isak, Keoz, Snax, volt  |
|           17 |     3428 | 2024-02-19 | Team Vitality            | L   | 0.690      | -            | -                | -                | -            |    -3.52 | acoR, isak, Keoz, Snax, volt  |
|           16 |     3866 | 2024-02-06 | HEROIC                   | L   | 0.604      | -            | -                | -                | -            |    -6.86 | acoR, isak, Keoz, Snax, volt  |
|           15 |     3904 | 2024-02-05 | MOUZ                     | L   | 0.598      | -            | -                | -                | -            |    -3.52 | acoR, isak, Keoz, Snax, volt  |
|           14 |     3930 | 2024-02-04 | Monte                    | W   | 0.590      | 1.000        | 0.199 (0.117)    | 0.378 (0.223)    | true (0.590) |     4.12 | acoR, isak, Keoz, Snax, volt  |
|           13 |     4087 | 2024-02-01 | Virtus.pro               | W   | 0.570      | 1.000        | 0.454 (0.259)    | 0.416 (0.237)    | -            |    12.33 | acoR, isak, Keoz, Snax, volt  |
|           12 |     4108 | 2024-01-31 | M80                      | W   | 0.565      | 1.000        | 0.155 (0.088)    | 0.405 (0.229)    | -            |     2.94 | acoR, isak, Keoz, Snax, volt  |
|           11 |     4314 | 2024-01-26 | FaZe Clan                | L   | 0.532      | -            | -                | -                | -            |    -1.55 | acoR, isak, Keoz, Snax, volt  |
|           10 |     4362 | 2024-01-25 | Team Liquid              | L   | 0.523      | -            | -                | -                | -            |   -12.34 | acoR, isak, Keoz, Snax, volt  |
|            9 |     4402 | 2024-01-24 | FaZe Clan                | W   | 0.517      | 0.581        | 1.000 (0.300)    | 0.566 (0.170)    | -            |    14.80 | acoR, isak, Keoz, Snax, volt  |
|            8 |     5932 | 2023-12-06 | BetBoom Team             | L   | 0.192      | -            | -                | -                | -            |    -3.88 | acoR, isak, Keoz, Snax, volt  |
|            7 |     6006 | 2023-12-05 | Cloud9                   | L   | 0.183      | -            | -                | -                | -            |    -1.35 | acoR, isak, Keoz, Snax, volt  |
|            6 |     6167 | 2023-12-01 | ENCE                     | L   | 0.157      | -            | -                | -                | -            |    -4.91 | acoR, isak, Keoz, Snax, volt  |
|            5 |     6272 | 2023-11-29 | HAVU Gaming              | L   | 0.144      | -            | -                | -                | -            |    -4.47 | acoR, isak, Keoz, Snax, volt  |
|            4 |     6278 | 2023-11-29 | Fnatic                   | W   | 0.144      | -            | -                | -                | -            |     0.46 | acoR, isak, Keoz, Snax, volt  |
|            3 |     6445 | 2023-11-25 | Virtus.pro               | L   | 0.117      | -            | -                | -                | -            |    -1.30 | acoR, isak, Keoz, Snax, volt  |
|            2 |     6462 | 2023-11-24 | 3DMAX                    | W   | 0.112      | -            | -                | -                | -            |     0.09 | acoR, isak, Keoz, Snax, volt  |
|            1 |     6488 | 2023-11-24 | MIBR                     | L   | 0.111      | -            | -                | -                | -            |    -1.44 | acoR, isak, Keoz, Snax, volt  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,707.36)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.19) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-31 |      0.965 | $10,000.00     | $9,652.31       |
| 2024-03-10 |      0.826 | $5,000.00      | $4,127.89       |
| 2024-02-11 |      0.638 | $16,000.00     | $10,208.15      |
| 2024-01-28 |      0.545 | $8,500.00      | $4,633.29       |
| 2023-12-03 |      0.171 | $10,000.00     | $1,710.65       |
| 2023-11-26 |      0.125 | $3,000.00      | $375.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
