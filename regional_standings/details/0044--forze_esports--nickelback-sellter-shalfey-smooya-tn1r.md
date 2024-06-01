### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: NickelBack, SELLTER, shalfey, smooya, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [44](../standings_global.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
Final Rank Value:  1077.5<br />
<br />
Final Rank Value (1077.5) = Starting Rank Value (981.2) + Head To Head Adjustments (96.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.512[<sup>1</sup>](#table2)
- Bounty Collected: 0.417[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.286<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 981.2
- 400 + ( ( 0.286 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 981.2


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
|           37 |     1843 | 2024-05-04 | Monte                | L   | 1.000      | -            | -                | -                | -         |    -9.75 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           36 |     1908 | 2024-05-02 | GamerLegion          | L   | 1.000      | -            | -                | -                | -         |    -9.93 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           35 |     1974 | 2024-05-01 | FURIA Esports        | W   | 1.000      | 0.889        | 0.138 (0.122)    | 0.267 (0.237)    | 1 (1.000) |    26.03 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           34 |     2022 | 2024-04-30 | Monte                | L   | 1.000      | -            | -                | -                | -         |    -9.33 | NickelBack, SELLTER, shalfey, smooya, tN1R |
|           33 |     3075 | 2024-04-12 | BIG                  | L   | 0.883      | -            | -                | -                | -         |    -4.31 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           32 |     3128 | 2024-04-11 | Aurora Gaming        | L   | 0.876      | -            | -                | -                | -         |    -4.08 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           31 |     3166 | 2024-04-10 | TSM                  | W   | 0.871      | 0.500        | -                | 0.146 (0.063)    | 0 (0.000) |     3.84 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           30 |     3234 | 2024-04-09 | brazylijski luz      | W   | 0.864      | 0.500        | 0.013 (0.006)    | 0.490 (0.212)    | 0 (0.000) |     4.55 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           29 |     3300 | 2024-04-08 | ENCE                 | W   | 0.856      | 0.687        | 0.202 (0.119)    | 0.280 (0.165)    | 0 (0.000) |    23.48 | kelieN, SELLTER, shalfey, sstiNiX, tN1R    |
|           28 |     3792 | 2024-03-27 | 500                  | L   | 0.778      | -            | -                | -                | -         |   -18.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           27 |     3806 | 2024-03-27 | Team Secret          | W   | 0.777      | -            | -                | -                | 0 (0.000) |     2.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           26 |     3880 | 2024-03-26 | GUN5 Esports         | W   | 0.771      | -            | -                | -                | 0 (0.000) |     2.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           25 |     3896 | 2024-03-26 | Apeks                | W   | 0.769      | -            | -                | -                | 0 (0.000) |     2.11 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           24 |     3923 | 2024-03-25 | B8                   | L   | 0.764      | -            | -                | -                | -         |   -10.17 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           23 |     3952 | 2024-03-24 | BetBoom Team         | W   | 0.756      | 0.143        | 0.390 (0.042)    | 0.712 (0.077)    | 0 (0.000) |    19.89 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           22 |     4007 | 2024-03-23 | VP.Prodigy           | W   | 0.750      | 0.143        | -                | 0.752 (0.080)    | 0 (0.000) |     6.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           21 |     4040 | 2024-03-22 | ex-Preasy Esport     | W   | 0.743      | -            | -                | -                | 0 (0.000) |    10.72 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           20 |     4093 | 2024-03-21 | PARIVISION           | L   | 0.737      | -            | -                | -                | -         |   -15.16 | kelieN, SELLTER, shalfey, spirit, tN1R     |
|           19 |     4137 | 2024-03-20 | Natus Vincere Junior | W   | 0.730      | -            | -                | -                | -         |     4.97 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           18 |     4933 | 2024-03-05 | KOI                  | L   | 0.631      | -            | -                | -                | -         |   -10.54 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           17 |     4944 | 2024-03-05 | AMKAL ESPORTS        | W   | 0.631      | 0.143        | 0.146 (0.013)    | -                | -         |    13.10 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           16 |     4961 | 2024-03-05 | 3DMAX                | W   | 0.631      | 0.143        | 0.106 (0.010)    | -                | -         |     7.62 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           15 |     4995 | 2024-03-04 | Nexus Gaming         | W   | 0.625      | 0.143        | -                | 0.825 (0.074)    | -         |     6.82 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           14 |     5013 | 2024-03-04 | naaaa                | W   | 0.625      | -            | -                | -                | -         |     0.55 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           13 |     5121 | 2024-03-02 | Metizport            | L   | 0.612      | -            | -                | -                | -         |   -10.06 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           12 |     5161 | 2024-03-02 | RoundsGG             | W   | 0.611      | -            | -                | -                | -         |     1.59 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           11 |     5227 | 2024-03-01 | Aurora Gaming        | L   | 0.604      | -            | -                | -                | -         |    -1.99 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|           10 |     5261 | 2024-02-29 | 9Pandas              | W   | 0.598      | 0.143        | 0.110 (0.009)    | 0.660 (0.056)    | -         |    13.20 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            9 |     5310 | 2024-02-28 | KOI                  | W   | 0.591      | -            | -                | -                | -         |     8.90 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            8 |     5328 | 2024-02-28 | Aurora Gaming        | W   | 0.590      | 0.143        | 0.492 (0.041)    | 0.616 (0.052)    | -         |    16.98 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            7 |     5355 | 2024-02-27 | V1dar Gaming         | W   | 0.584      | -            | -                | -                | -         |     3.02 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            6 |     5366 | 2024-02-27 | ARCRED               | W   | 0.584      | 0.143        | -                | 0.630 (0.053)    | -         |     4.53 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            5 |     5400 | 2024-02-26 | Sangal Esports       | W   | 0.578      | 0.143        | 0.166 (0.014)    | -                | -         |    10.08 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            4 |     6292 | 2024-02-09 | Sashi Esport         | L   | 0.464      | -            | -                | -                | -         |    -6.13 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            3 |     6305 | 2024-02-09 | RUBY                 | W   | 0.463      | -            | -                | -                | -         |     6.24 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            2 |     6320 | 2024-02-08 | BetBoom Team         | W   | 0.458      | 0.143        | 0.390 (0.025)    | -                | -         |    13.26 | gokushima, r3salt, SELLTER, shalfey, tN1R  |
|            1 |     6336 | 2024-02-08 | Sashi Esport         | L   | 0.457      | -            | -                | -                | -         |    -5.93 | gokushima, r3salt, SELLTER, shalfey, tN1R  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,526.56)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      0.896 | $26,250.00     | $23,526.56      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
