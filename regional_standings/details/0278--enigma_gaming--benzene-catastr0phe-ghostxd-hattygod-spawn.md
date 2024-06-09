### Roster Details<br />
Team Name: Enigma Gaming<br />
Roster: Benzene, Catastr0phE, ghostxD, hattygOD, SpawN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [278](../standings_global.md)<br />
Regional Rank: [42]( ../standings_asia.md)<br />
Final Rank Value:  661.8<br />
<br />
Final Rank Value (661.8) = Starting Rank Value (687.0) + Head To Head Adjustments (-25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.235[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 687.0
- 400 + ( ( 0.141 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 687.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     6504 | 2024-02-09 | Grayfox Esports    | L   | 0.461      | -            | -                | -                | -         |    -7.16 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|           13 |     6528 | 2024-02-08 | dreamScape         | W   | 0.456      | 0.303        | 0.001 (0.000)    | 0.049 (0.007)    | 0 (0.000) |     6.61 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|           12 |     6842 | 2024-02-02 | 2ez Gaming         | L   | 0.416      | -            | -                | -                | -         |    -7.51 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|           11 |     6942 | 2024-01-31 | Firedup Gaming     | L   | 0.403      | -            | -                | -                | -         |    -7.79 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|           10 |     7059 | 2024-01-29 | Gods Reign         | L   | 0.389      | -            | -                | -                | -         |    -2.75 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            9 |     7102 | 2024-01-28 | True Rippers       | L   | 0.382      | -            | -                | -                | -         |    -4.55 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            8 |     7206 | 2024-01-27 | Gods Reign         | L   | 0.376      | -            | -                | -                | -         |    -5.80 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            7 |     7275 | 2024-01-26 | Grayfox Esports    | L   | 0.370      | -            | -                | -                | -         |    -6.17 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            6 |     7315 | 2024-01-25 | Firedup Gaming     | W   | 0.363      | 0.143        | 0.000 (0.000)    | 0.032 (0.002)    | 0 (0.000) |     4.14 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            5 |     7605 | 2024-01-20 | Gods Reign         | W   | 0.329      | 0.143        | 0.086 (0.004)    | 0.461 (0.022)    | 1 (0.329) |     8.12 | Benzene, Catastr0phE, hattygOD, Rider, SpawN   |
|            4 |     7850 | 2024-01-17 | Myth Avenue Gaming | L   | 0.308      | -            | -                | -                | -         |    -5.04 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            3 |     8628 | 2023-12-21 | Wasted Potential   | W   | 0.130      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.04 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            2 |     8639 | 2023-12-20 | Gods Reign         | W   | 0.123      | 0.143        | 0.086 (0.002)    | 0.461 (0.008)    | 0 (0.000) |     3.06 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |
|            1 |     8780 | 2023-12-16 | Marcos Gaming      | L   | 0.101      | -            | -                | -                | -         |    -1.34 | Benzene, Catastr0phE, ghostxD, hattygOD, SpawN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,094.93)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-26 |      0.370 | $180.49        | $66.73          |
| 2024-01-20 |      0.329 | $3,007.52      | $989.14         |
| 2023-12-21 |      0.130 | $300.60        | $39.06          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
