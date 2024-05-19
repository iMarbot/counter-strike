### Roster Details<br />
Team Name: Illuminar Gaming<br />
Roster: ANeraX, Furlan, keis, phr, ultimate<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [112](../standings_global.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
Final Rank Value:  832.2<br />
<br />
Final Rank Value (832.2) = Starting Rank Value (781.0) + Head To Head Adjustments (51.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.311[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.192<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.0
- 400 + ( ( 0.192 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 781.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      389 | 2024-04-27 | EYEBALLERS                  | L   | 1.000      | -            | -                | -                | -             |   -11.64 | ANeraX, Furlan, keis, phr, ultimate    |
|           22 |      448 | 2024-04-26 | Zero Tenacity               | L   | 1.000      | -            | -                | -                | -             |   -10.82 | ANeraX, Furlan, keis, phr, ultimate    |
|           21 |      589 | 2024-04-23 | Nexus Gaming                | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.772 (0.335)    | false (0.000) |    18.35 | ANeraX, Furlan, keis, phr, ultimate    |
|           20 |      633 | 2024-04-21 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -             |    -4.59 | ANeraX, Furlan, keis, phr, ultimate    |
|           19 |      729 | 2024-04-20 | ThunderFlash                | L   | 1.000      | -            | -                | -                | -             |   -17.83 | ANeraX, Furlan, keis, phr, ultimate    |
|           18 |      767 | 2024-04-20 | Viperio                     | W   | 1.000      | 0.143        | 0.006 (0.001)    | -                | false (0.000) |    12.12 | ANeraX, Furlan, keis, phr, ultimate    |
|           17 |      874 | 2024-04-18 | EsmagaB                     | W   | 1.000      | 0.143        | 0.016 (0.002)    | 0.559 (0.080)    | false (0.000) |    15.59 | ANeraX, Furlan, keis, phr, ultimate    |
|           16 |      937 | 2024-04-17 | Team Secret                 | W   | 1.000      | 0.143        | -                | 0.368 (0.053)    | false (0.000) |    10.30 | ANeraX, Furlan, keis, phr, ultimate    |
|           15 |     1060 | 2024-04-15 | Lilmix                      | L   | 1.000      | -            | -                | -                | -             |   -20.61 | ANeraX, Furlan, phr, splawik, ultimate |
|           14 |     1081 | 2024-04-14 | Viperio                     | L   | 1.000      | -            | -                | -                | -             |   -18.86 | ANeraX, Furlan, keis, phr, ultimate    |
|           13 |     1191 | 2024-04-11 | Astralis Talent             | W   | 1.000      | 0.333        | 0.030 (0.010)    | 0.613 (0.204)    | false (0.000) |    16.44 | ANeraX, Furlan, keis, phr, ultimate    |
|           12 |     1245 | 2024-04-10 | GamerLegion Academy         | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.567 (0.189)    | false (0.000) |    17.12 | ANeraX, Furlan, keis, phr, ultimate    |
|           11 |     1504 | 2024-04-04 | Johnny Speeds               | L   | 0.990      | -            | -                | -                | -             |   -14.20 | ANeraX, Furlan, phr, splawik, ultimate |
|           10 |     1542 | 2024-04-03 | Turów Zgorzelec Esport      | L   | 0.984      | -            | -                | -                | -             |   -17.67 | ANeraX, Furlan, keis, phr, ultimate    |
|            9 |     1590 | 2024-04-02 | UNiTY esports (Slovak team) | L   | 0.976      | -            | -                | -                | -             |   -13.13 | ANeraX, Furlan, keis, phr, ultimate    |
|            8 |     1639 | 2024-03-30 | Astralis Talent             | W   | 0.957      | 0.333        | 0.030 (0.010)    | 0.613 (0.196)    | false (0.000) |    15.40 | ANeraX, Furlan, keis, phr, ultimate    |
|            7 |     1770 | 2024-03-27 | ROSOMAHA                    | W   | 0.937      | 0.333        | -                | 0.136 (0.042)    | false (0.000) |     5.19 | ANeraX, Furlan, keis, phr, ultimate    |
|            6 |     1923 | 2024-03-23 | NOM Esports                 | W   | 0.909      | 0.333        | -                | 0.374 (0.113)    | false (0.000) |     9.79 | ANeraX, Furlan, keis, phr, ultimate    |
|            5 |     1940 | 2024-03-22 | LODIS                       | W   | 0.905      | -            | -                | -                | false (0.000) |     5.64 | ANeraX, Furlan, keis, phr, ultimate    |
|            4 |     1966 | 2024-03-21 | ENTERPRISE esports          | W   | 0.899      | 0.143        | 0.039 (0.005)    | 0.476 (0.061)    | -             |    18.00 | ANeraX, Furlan, keis, phr, ultimate    |
|            3 |     2024 | 2024-03-20 | ThunderFlash                | W   | 0.892      | 0.143        | 0.023 (0.003)    | -                | -             |    12.62 | ANeraX, Furlan, keis, phr, ultimate    |
|            2 |     2053 | 2024-03-19 | Mikstura1234                | W   | 0.885      | 0.143        | 0.003 (0.000)    | -                | -             |     8.71 | ANeraX, Furlan, keis, phr, ultimate    |
|            1 |     2076 | 2024-03-18 | Turów Zgorzelec Esport      | W   | 0.879      | 0.143        | 0.019 (0.002)    | 0.640 (0.080)    | -             |    15.28 | ANeraX, Furlan, keis, phr, ultimate    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,232.30)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
