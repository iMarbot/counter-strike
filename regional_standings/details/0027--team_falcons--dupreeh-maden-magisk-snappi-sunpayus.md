### Roster Details<br />
Team Name: Team Falcons<br />
Roster: dupreeh, maden, Magisk, Snappi, SunPayus<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [27](../standings_global.md)<br />
Regional Rank: [20]( ../standings_europe.md)<br />
Final Rank Value:  1324.2<br />
<br />
Final Rank Value (1324.2) = Starting Rank Value (1359.5) + Head To Head Adjustments (-35.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.732[<sup>1</sup>](#table2)
- Bounty Collected: 0.537[<sup>2</sup>](#table1)
- Opponent Network: 0.153[<sup>2</sup>](#table1)
- LAN Wins: 0.512[<sup>2</sup>](#table1)

The average of these factors is 0.484<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1359.5
- 400 + ( ( 0.484 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1359.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins     | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      380 | 2024-04-27 | G2 Esports        | L   | 1.000      | -            | -                | -                | -            |    -2.18 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           21 |      443 | 2024-04-26 | BetBoom Team      | L   | 1.000      | -            | -                | -                | -            |   -12.75 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           20 |      489 | 2024-04-25 | TYLOO             | W   | 1.000      | 0.889        | 0.131 (0.117)    | 0.592 (0.526)    | true (1.000) |     4.70 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           19 |      546 | 2024-04-24 | The MongolZ       | L   | 1.000      | -            | -                | -                | -            |    -6.96 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           18 |      933 | 2024-04-17 | RUBY              | L   | 1.000      | -            | -                | -                | -            |   -28.77 | dupreeh, maden, Magisk, Snappi, SunPayus |
|           17 |     2603 | 2024-03-06 | Metizport         | L   | 0.799      | -            | -                | -                | -            |   -20.64 | maden, Magisk, s1mple, Snappi, SunPayus  |
|           16 |     3549 | 2024-02-16 | AMKAL ESPORTS     | L   | 0.670      | -            | -                | -                | -            |   -15.82 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           15 |     3602 | 2024-02-15 | Eternal Fire      | L   | 0.663      | -            | -                | -                | -            |    -2.24 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           14 |     3622 | 2024-02-14 | FaZe Clan         | L   | 0.658      | -            | -                | -                | -            |    -0.81 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           13 |     3636 | 2024-02-14 | 3DMAX             | W   | 0.658      | 0.143        | 0.062 (0.006)    | 0.393 (0.037)    | true (0.658) |     1.74 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           12 |     3764 | 2024-02-10 | Team Spirit       | L   | 0.632      | -            | -                | -                | -            |    -1.55 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           11 |     3789 | 2024-02-09 | ENCE              | W   | 0.625      | 1.000        | 0.377 (0.236)    | 0.352 (0.220)    | true (0.625) |    13.99 | BOROS, maden, Magisk, Snappi, SunPayus   |
|           10 |     3862 | 2024-02-06 | Natus Vincere     | W   | 0.605      | 1.000        | 1.000 (0.605)    | 0.406 (0.246)    | true (0.605) |    18.30 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            9 |     3886 | 2024-02-05 | Complexity Gaming | W   | 0.599      | 1.000        | 0.271 (0.163)    | 0.274 (0.164)    | true (0.599) |    13.05 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            8 |     3916 | 2024-02-04 | Rebels Gaming     | W   | 0.592      | 1.000        | 0.121 (0.072)    | 0.376 (0.222)    | true (0.592) |     4.09 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            7 |     3999 | 2024-02-03 | Eternal Fire      | L   | 0.584      | -            | -                | -                | -            |    -1.43 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            6 |     4337 | 2024-01-26 | Team Vitality     | L   | 0.530      | -            | -                | -                | -            |    -0.76 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            5 |     4423 | 2024-01-23 | OG                | W   | 0.512      | 0.581        | 0.594 (0.177)    | 0.390 (0.116)    | true (0.512) |     7.28 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            4 |     4469 | 2024-01-22 | Astralis          | L   | 0.505      | -            | -                | -                | -            |    -4.43 | BOROS, maden, Magisk, Snappi, SunPayus   |
|            3 |     7023 | 2023-11-12 | FaZe Clan         | L   | 0.029      | -            | -                | -                | -            |    -0.03 | maden, NertZ, Snappi, SunPayus, VLDN     |
|            2 |     7215 | 2023-11-08 | Astralis          | L   | 0.003      | -            | -                | -                | -            |    -0.08 | b0RUP, blameF, Buzz, dev1ce, Staehr      |
|            1 |     7218 | 2023-11-07 | TYLOO             | W   | 0.001      | 0.769        | 0.131 (0.000)    | 0.592 (0.001)    | true (0.001) |     0.01 | advent, JamYoung, kaze, Mercury, Moseyuh |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($68,332.01)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.43) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-03-10 |      0.826 | $5,000.00      | $4,127.89       |
| 2024-02-11 |      0.638 | $80,000.00     | $51,040.74      |
| 2024-01-28 |      0.545 | $8,500.00      | $4,633.29       |
| 2023-11-12 |      0.031 | $50,000.00     | $1,530.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
