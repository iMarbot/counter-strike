### Roster Details<br />
Team Name: Team Spirit<br />
Roster: chopper, donk, magixx, sh1ro, zont1x<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [2](../standings_global.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
Final Rank Value:  1948.0<br />
<br />
Final Rank Value (1948.0) = Starting Rank Value (1904.6) + Head To Head Adjustments (43.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.743[<sup>2</sup>](#table1)
- Opponent Network: 0.291[<sup>2</sup>](#table1)
- LAN Wins: 0.927[<sup>2</sup>](#table1)

The average of these factors is 0.740<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1904.6
- 400 + ( ( 0.740 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1904.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       40 | 2024-05-29 | FaZe Clan         | W   | 1.000      | 0.624        | 1.000 (0.624)    | 0.457 (0.285)    | 1 (1.000) |    15.89 | chopper, donk, magixx, sh1ro, zont1x    |
|           35 |      127 | 2024-05-28 | Natus Vincere     | W   | 1.000      | 0.624        | 1.000 (0.624)    | -                | 1 (1.000) |    12.16 | chopper, donk, magixx, sh1ro, zont1x    |
|           34 |      160 | 2024-05-27 | FlyQuest          | W   | 1.000      | 0.624        | -                | 0.466 (0.291)    | 1 (1.000) |     2.08 | chopper, donk, magixx, sh1ro, zont1x    |
|           33 |      793 | 2024-05-19 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |   -12.47 | chopper, donk, magixx, sh1ro, zont1x    |
|           32 |      918 | 2024-05-18 | Team Falcons      | W   | 1.000      | 0.769        | 0.355 (0.273)    | -                | 1 (1.000) |     1.90 | chopper, donk, magixx, sh1ro, zont1x    |
|           31 |     1095 | 2024-05-16 | HEROIC            | W   | 1.000      | 0.769        | 0.322 (0.247)    | 0.463 (0.356)    | 1 (1.000) |     4.37 | chopper, donk, magixx, sh1ro, zont1x    |
|           30 |     1209 | 2024-05-15 | Aurora Gaming     | W   | 1.000      | 0.769        | 0.492 (0.378)    | 0.573 (0.441)    | 1 (1.000) |     1.20 | chopper, donk, magixx, sh1ro, zont1x    |
|           29 |     3829 | 2024-03-28 | FaZe Clan         | L   | 0.784      | -            | -                | -                | -         |   -11.28 | chopper, donk, magixx, sh1ro, zont1x    |
|           28 |     4132 | 2024-03-22 | Natus Vincere     | W   | 0.744      | 1.000        | 1.000 (0.744)    | 0.253 (0.188)    | 1 (0.744) |     9.61 | chopper, donk, magixx, sh1ro, zont1x    |
|           27 |     4155 | 2024-03-21 | Imperial Esports  | W   | 0.738      | 1.000        | 0.372 (0.275)    | 0.582 (0.429)    | 1 (0.738) |     1.94 | chopper, donk, magixx, sh1ro, zont1x    |
|           26 |     4190 | 2024-03-21 | Cloud9            | W   | 0.737      | -            | -                | -                | 1 (0.737) |     2.10 | chopper, donk, magixx, sh1ro, zont1x    |
|           25 |     4770 | 2024-03-10 | Metizport         | W   | 0.665      | 0.535        | -                | 0.698 (0.248)    | -         |     0.17 | chopper, donk, magixx, sh1ro, zont1x    |
|           24 |     4825 | 2024-03-09 | BIG               | W   | 0.658      | -            | -                | -                | -         |     1.00 | chopper, donk, magixx, sh1ro, zont1x    |
|           23 |     4883 | 2024-03-08 | Elevate           | W   | 0.650      | -            | -                | -                | -         |     0.05 | chopper, donk, magixx, sh1ro, zont1x    |
|           22 |     5871 | 2024-02-21 | HEROIC            | W   | 0.544      | -            | -                | -                | 1 (0.544) |     4.63 | chopper, donk, magixx, sh1ro, zont1x    |
|           21 |     5933 | 2024-02-20 | MOUZ              | L   | 0.537      | -            | -                | -                | -         |    -7.44 | chopper, donk, magixx, sh1ro, zont1x    |
|           20 |     5987 | 2024-02-19 | Astralis          | W   | 0.531      | -            | -                | -                | -         |     3.09 | chopper, donk, magixx, sh1ro, zont1x    |
|           19 |     6021 | 2024-02-19 | ENCE              | W   | 0.529      | -            | -                | -                | -         |     1.13 | chopper, donk, magixx, sh1ro, zont1x    |
|           18 |     6432 | 2024-02-11 | FaZe Clan         | W   | 0.477      | 1.000        | 1.000 (0.477)    | 0.457 (0.218)    | -         |     9.32 | chopper, donk, magixx, sh1ro, zont1x    |
|           17 |     6445 | 2024-02-10 | Team Falcons      | W   | 0.471      | -            | -                | -                | -         |     1.41 | chopper, donk, magixx, sh1ro, zont1x    |
|           16 |     6576 | 2024-02-06 | FaZe Clan         | W   | 0.443      | 1.000        | 1.000 (0.443)    | 0.457 (0.203)    | -         |     8.83 | chopper, donk, magixx, sh1ro, zont1x    |
|           15 |     6664 | 2024-02-04 | Complexity Gaming | W   | 0.430      | -            | -                | -                | -         |     1.70 | chopper, donk, magixx, sh1ro, zont1x    |
|           14 |     6730 | 2024-02-03 | Natus Vincere     | W   | 0.424      | 1.000        | 1.000 (0.424)    | -                | -         |     6.34 | chopper, donk, magixx, sh1ro, zont1x    |
|           13 |     6894 | 2024-02-01 | The MongolZ       | W   | 0.409      | 1.000        | -                | 0.619 (0.253)    | -         |     2.12 | chopper, donk, magixx, sh1ro, zont1x    |
|           12 |     6932 | 2024-01-31 | Apeks             | W   | 0.404      | -            | -                | -                | -         |     0.30 | chopper, donk, magixx, sh1ro, zont1x    |
|           11 |     7314 | 2024-01-25 | FaZe Clan         | L   | 0.363      | -            | -                | -                | -         |    -4.18 | baz, chopper, hally, sh1ro, zont1x      |
|           10 |     7362 | 2024-01-24 | Team Liquid       | L   | 0.356      | -            | -                | -                | -         |    -8.97 | baz, chopper, hally, sh1ro, zont1x      |
|            9 |     7589 | 2024-01-20 | MOUZ              | W   | 0.330      | -            | -                | -                | -         |     6.28 | chopper, donk, magixx, sh1ro, zont1x    |
|            8 |     7656 | 2024-01-19 | ex-Preasy Esport  | W   | 0.323      | -            | -                | -                | -         |     0.04 | chopper, donk, magixx, sh1ro, zont1x    |
|            7 |     7708 | 2024-01-18 | Entropiq          | W   | 0.318      | -            | -                | -                | -         |     0.01 | chopper, donk, magixx, sh1ro, zont1x    |
|            6 |     7732 | 2024-01-18 | KOI               | L   | 0.317      | -            | -                | -                | -         |    -9.92 | chopper, donk, magixx, sh1ro, zont1x    |
|            5 |     9254 | 2023-12-10 | Virtus.pro        | W   | 0.056      | -            | -                | -                | -         |     0.41 | ArtFr0st, chopper, donk, magixx, zont1x |
|            4 |     9299 | 2023-12-09 | MIBR              | W   | 0.049      | -            | -                | -                | -         |     0.25 | ArtFr0st, chopper, donk, magixx, zont1x |
|            3 |     9382 | 2023-12-08 | FURIA Esports     | W   | 0.043      | -            | -                | -                | -         |     0.10 | ArtFr0st, chopper, donk, magixx, zont1x |
|            2 |     9462 | 2023-12-07 | Virtus.pro        | L   | 0.035      | -            | -                | -                | -         |    -0.84 | ArtFr0st, chopper, donk, magixx, zont1x |
|            1 |     9513 | 2023-12-06 | FURIA Esports     | W   | 0.030      | -            | -                | -                | -         |     0.07 | ArtFr0st, chopper, donk, magixx, zont1x |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($352,159.03)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-19 |      1.000 | $100,000.00    | $100,000.00     |
| 2024-03-31 |      0.804 | $45,000.00     | $36,175.00      |
| 2024-03-10 |      0.665 | $20,000.00     | $13,290.28      |
| 2024-02-11 |      0.477 | $400,000.00    | $190,777.78     |
| 2024-01-28 |      0.384 | $5,000.00      | $1,920.14       |
| 2023-12-10 |      0.056 | $180,000.00    | $9,995.83       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
