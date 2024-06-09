### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [45](../standings_global.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
Final Rank Value:  1081.6<br />
<br />
Final Rank Value (1081.6) = Starting Rank Value (967.0) + Head To Head Adjustments (114.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.502[<sup>1</sup>](#table2)
- Bounty Collected: 0.417[<sup>2</sup>](#table1)
- Opponent Network: 0.091[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 967.0
- 400 + ( ( 0.279 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 967.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     1866 | 2024-05-04 | Monte                | L   | 1.000      | -            | -                | -                | -         |    -9.64 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           31 |     1934 | 2024-05-02 | GamerLegion          | L   | 1.000      | -            | -                | -                | -         |   -10.15 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           30 |     2002 | 2024-05-01 | FURIA Esports        | W   | 1.000      | 0.889        | 0.138 (0.122)    | 0.267 (0.237)    | 1 (1.000) |    25.91 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           29 |     2053 | 2024-04-30 | Monte                | L   | 1.000      | -            | -                | -                | -         |    -9.22 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           28 |     3141 | 2024-04-12 | BIG                  | L   | 0.883      | -            | -                | -                | -         |    -4.58 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           27 |     3198 | 2024-04-11 | Aurora Gaming        | L   | 0.876      | -            | -                | -                | -         |    -4.79 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           26 |     3381 | 2024-04-08 | ENCE                 | W   | 0.856      | 0.687        | 0.202 (0.119)    | 0.280 (0.165)    | 0 (0.000) |    23.27 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           25 |     3885 | 2024-03-27 | 500                  | L   | 0.778      | -            | -                | -                | -         |   -18.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           24 |     3899 | 2024-03-27 | Team Secret          | W   | 0.777      | -            | -                | -                | 0 (0.000) |     1.90 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           23 |     3977 | 2024-03-26 | GUN5 Esports         | W   | 0.771      | -            | -                | -                | 0 (0.000) |     2.19 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           22 |     4049 | 2024-03-24 | BetBoom Team         | W   | 0.756      | 0.143        | 0.390 (0.042)    | 0.712 (0.077)    | 0 (0.000) |    19.83 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           21 |     4105 | 2024-03-23 | VP.Prodigy           | W   | 0.750      | 0.143        | -                | 0.829 (0.089)    | 0 (0.000) |     6.23 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     4138 | 2024-03-22 | ex-Preasy Esport     | W   | 0.743      | 0.143        | 0.052 (0.005)    | -                | 0 (0.000) |    10.68 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           19 |     4239 | 2024-03-20 | Natus Vincere Junior | W   | 0.730      | -            | -                | -                | 0 (0.000) |     5.22 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     5072 | 2024-03-05 | KOI                  | L   | 0.631      | -            | -                | -                | -         |   -10.17 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     5084 | 2024-03-05 | AMKAL ESPORTS        | W   | 0.631      | 0.143        | 0.146 (0.013)    | 0.565 (0.051)    | 0 (0.000) |    13.39 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     5104 | 2024-03-05 | 3DMAX                | W   | 0.631      | 0.143        | 0.106 (0.010)    | -                | 0 (0.000) |     7.95 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     5141 | 2024-03-04 | Nexus Gaming         | W   | 0.625      | 0.143        | -                | 0.857 (0.077)    | -         |     6.76 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     5159 | 2024-03-04 | naaaa                | W   | 0.625      | -            | -                | -                | -         |     0.58 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     5269 | 2024-03-02 | Metizport            | L   | 0.612      | -            | -                | -                | -         |    -9.70 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     5309 | 2024-03-02 | RoundsGG             | W   | 0.611      | -            | -                | -                | -         |     1.87 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     5376 | 2024-03-01 | Aurora Gaming        | L   | 0.604      | -            | -                | -                | -         |    -1.97 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     5410 | 2024-02-29 | 9Pandas              | W   | 0.598      | 0.143        | 0.110 (0.009)    | 0.710 (0.061)    | -         |    13.65 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     5461 | 2024-02-28 | KOI                  | W   | 0.591      | -            | -                | -                | -         |     9.34 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     5479 | 2024-02-28 | Aurora Gaming        | W   | 0.590      | 0.143        | 0.492 (0.041)    | -                | -         |    16.99 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     5508 | 2024-02-27 | V1dar Gaming         | W   | 0.584      | 0.143        | -                | 0.595 (0.050)    | -         |     3.41 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     5519 | 2024-02-27 | ARCRED               | W   | 0.584      | 0.143        | -                | 0.630 (0.053)    | -         |     4.78 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     5557 | 2024-02-26 | Sangal Esports       | W   | 0.578      | 0.143        | 0.166 (0.014)    | 0.658 (0.054)    | -         |    10.96 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     6480 | 2024-02-09 | Sashi Esport         | L   | 0.464      | -            | -                | -                | -         |    -5.96 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     6493 | 2024-02-09 | RUBY                 | W   | 0.463      | -            | -                | -                | -         |     6.56 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     6508 | 2024-02-08 | BetBoom Team         | W   | 0.458      | 0.143        | 0.390 (0.025)    | -                | -         |    13.35 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     6524 | 2024-02-08 | Sashi Esport         | L   | 0.457      | -            | -                | -                | -         |    -5.74 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($30,526.56)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      0.896 | $26,250.00     | $23,526.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
