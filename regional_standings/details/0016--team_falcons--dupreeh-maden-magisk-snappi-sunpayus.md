### Roster Details<br />
Team Name: Team Falcons<br />
Roster: dupreeh, maden, Magisk, Snappi, SunPayus<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [16](../standings_global.md)<br />
Regional Rank: [12]( ../standings_europe.md)<br />
Final Rank Value:  1433.8<br />
<br />
Final Rank Value (1433.8) = Starting Rank Value (1481.5) + Head To Head Adjustments (-47.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.690[<sup>1</sup>](#table2)
- Bounty Collected: 0.539[<sup>2</sup>](#table1)
- Opponent Network: 0.199[<sup>2</sup>](#table1)
- LAN Wins: 0.697[<sup>2</sup>](#table1)

The average of these factors is 0.531<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1481.5
- 400 + ( ( 0.531 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1481.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      103 | 2024-05-28 | Team Liquid       | L   | 1.000      | -            | -                | -                | -         |    -8.28 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           25 |      148 | 2024-05-27 | Monte             | W   | 1.000      | 0.624        | 0.181 (0.113)    | 0.363 (0.226)    | 1 (1.000) |     7.82 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           24 |      167 | 2024-05-27 | G2 Esports        | L   | 1.000      | -            | -                | -                | -         |    -4.58 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           23 |      906 | 2024-05-18 | Team Spirit       | L   | 1.000      | -            | -                | -                | -         |    -1.88 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           22 |     1005 | 2024-05-17 | Virtus.pro        | W   | 1.000      | 0.769        | 0.271 (0.208)    | 0.331 (0.255)    | 1 (1.000) |    24.19 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           21 |     1158 | 2024-05-15 | BetBoom Team      | W   | 1.000      | 0.769        | 0.390 (0.299)    | 0.712 (0.547)    | 1 (1.000) |    11.39 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           20 |     1259 | 2024-05-14 | Virtus.pro        | L   | 1.000      | -            | -                | -                | -         |    -6.34 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           19 |     2202 | 2024-04-27 | G2 Esports        | L   | 0.982      | -            | -                | -                | -         |    -4.09 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           18 |     2278 | 2024-04-26 | BetBoom Team      | L   | 0.975      | -            | -                | -                | -         |   -18.53 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           17 |     2326 | 2024-04-25 | TYLOO             | W   | 0.969      | 0.889        | 0.035 (0.030)    | 0.433 (0.373)    | 1 (0.969) |     1.72 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           16 |     2388 | 2024-04-24 | The MongolZ       | L   | 0.962      | -            | -                | -                | -         |   -10.32 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           15 |     2829 | 2024-04-17 | RUBY              | L   | 0.918      | -            | -                | -                | -         |   -27.49 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           14 |     4851 | 2024-03-06 | Metizport         | L   | 0.638      | -            | -                | -                | -         |   -18.54 | maden, Magisk, s1mple, Snappi, SunPayus  |
|           13 |     6002 | 2024-02-16 | AMKAL ESPORTS     | L   | 0.509      | -            | -                | -                | -         |   -13.67 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           12 |     6062 | 2024-02-15 | Eternal Fire      | L   | 0.502      | -            | -                | -                | -         |    -2.13 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           11 |     6093 | 2024-02-14 | FaZe Clan         | L   | 0.497      | -            | -                | -                | -         |    -0.96 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           10 |     6108 | 2024-02-14 | 3DMAX             | W   | 0.496      | 0.143        | 0.106 (0.008)    | 0.301 (0.021)    | 1 (0.496) |     0.68 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            9 |     6257 | 2024-02-10 | Team Spirit       | L   | 0.471      | -            | -                | -                | -         |    -1.40 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            8 |     6294 | 2024-02-09 | ENCE              | W   | 0.464      | 1.000        | 0.202 (0.094)    | 0.280 (0.130)    | 1 (0.464) |     6.33 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            7 |     6381 | 2024-02-06 | Natus Vincere     | W   | 0.443      | 1.000        | 1.000 (0.443)    | 0.253 (0.112)    | 1 (0.443) |    12.51 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            6 |     6411 | 2024-02-05 | Complexity Gaming | W   | 0.438      | 1.000        | 0.260 (0.114)    | 0.219 (0.096)    | 1 (0.438) |     8.20 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            5 |     6453 | 2024-02-04 | Rebels Gaming     | W   | 0.431      | 1.000        | 0.062 (0.027)    | 0.418 (0.180)    | 1 (0.431) |     1.39 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            4 |     6568 | 2024-02-03 | Eternal Fire      | L   | 0.423      | -            | -                | -                | -         |    -1.45 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            3 |     7058 | 2024-01-26 | Team Vitality     | L   | 0.369      | -            | -                | -                | -         |    -1.30 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            2 |     7172 | 2024-01-23 | OG                | W   | 0.351      | 0.581        | 0.277 (0.057)    | 0.257 (0.052)    | 1 (0.351) |     1.85 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            1 |     7227 | 2024-01-22 | Astralis          | L   | 0.344      | -            | -                | -                | -         |    -2.84 | BOROS, maden, Magisk, Snappi, SunPayus   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106,742.36)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.35) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-29 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-05-19 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-05-12 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-03-10 |      0.665 | $5,000.00      | $3,322.57       |
| 2024-02-11 |      0.477 | $80,000.00     | $38,155.56      |
| 2024-01-28 |      0.384 | $8,500.00      | $3,264.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
