### Roster Details<br />
Team Name: ENCE<br />
Roster: dycha, gla1ve, Goofy, hades, Kylar<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [23](../standings_global.md)<br />
Regional Rank: [16]( ../standings_europe.md)<br />
Final Rank Value:  1387.4<br />
<br />
Final Rank Value (1387.4) = Starting Rank Value (1558.6) + Head To Head Adjustments (-171.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.703[<sup>1</sup>](#table2)
- Bounty Collected: 0.568[<sup>2</sup>](#table1)
- Opponent Network: 0.251[<sup>2</sup>](#table1)
- LAN Wins: 0.814[<sup>2</sup>](#table1)

The average of these factors is 0.584<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1558.6
- 400 + ( ( 0.584 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1558.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |       63 | 2024-05-04 | FURIA Esports          | L   | 1.000      | -            | -                | -                | -         |   -12.83 | dycha, gla1ve, Goofy, hades, Kylar       |
|           36 |      111 | 2024-05-03 | GamerLegion            | L   | 1.000      | -            | -                | -                | -         |   -13.67 | dycha, gla1ve, Goofy, hades, Kylar       |
|           35 |      139 | 2024-05-02 | Monte                  | W   | 1.000      | 0.889        | 0.199 (0.177)    | 0.378 (0.336)    | 1 (1.000) |    11.33 | dycha, gla1ve, Goofy, hades, Kylar       |
|           34 |      206 | 2024-05-01 | Bad News Kangaroos     | W   | 1.000      | 0.889        | 0.071 (0.063)    | 0.238 (0.212)    | 1 (1.000) |     2.26 | dycha, gla1ve, Goofy, hades, Kylar       |
|           33 |      250 | 2024-04-30 | GamerLegion            | L   | 1.000      | -            | -                | -                | -         |   -14.42 | dycha, gla1ve, Goofy, hades, Kylar       |
|           32 |      833 | 2024-04-19 | AMKAL ESPORTS          | L   | 1.000      | -            | -                | -                | -         |   -24.92 | dycha, gla1ve, Goofy, hades, Kylar       |
|           31 |      952 | 2024-04-17 | ENTERPRISE esports     | W   | 1.000      | 0.384        | -                | 0.476 (0.183)    | -         |     1.73 | dycha, gla1ve, Goofy, hades, Kylar       |
|           30 |     1234 | 2024-04-10 | OG                     | L   | 1.000      | -            | -                | -                | -         |   -20.65 | dycha, gla1ve, Goofy, hades, Kylar       |
|           29 |     1339 | 2024-04-08 | FORZE Esports          | L   | 1.000      | -            | -                | -                | -         |   -27.41 | dycha, gla1ve, Goofy, hades, Kylar       |
|           28 |     1501 | 2024-04-04 | Aurora Young Blud      | W   | 0.990      | 0.384        | -                | 0.422 (0.161)    | -         |     0.62 | dycha, gla1ve, Goofy, hades, Kylar       |
|           27 |     2057 | 2024-03-19 | FURIA Esports          | L   | 0.885      | -            | -                | -                | -         |   -11.29 | dycha, gla1ve, Goofy, hades, Kylar       |
|           26 |     2104 | 2024-03-18 | PaiN Gaming            | L   | 0.877      | -            | -                | -                | -         |   -25.61 | dycha, gla1ve, Goofy, hades, Kylar       |
|           25 |     2116 | 2024-03-17 | KOI                    | W   | 0.873      | 1.000        | 0.066 (0.058)    | 0.537 (0.469)    | 1 (0.873) |     2.47 | dycha, gla1ve, Goofy, hades, Kylar       |
|           24 |     2148 | 2024-03-17 | Imperial Esports       | L   | 0.871      | -            | -                | -                | -         |   -15.05 | dycha, gla1ve, Goofy, hades, Kylar       |
|           23 |     2376 | 2024-03-12 | B8                     | L   | 0.838      | -            | -                | -                | -         |   -25.04 | dycha, gla1ve, Goofy, hades, Kylar       |
|           22 |     2408 | 2024-03-11 | HEROIC                 | L   | 0.832      | -            | -                | -                | -         |    -9.12 | dycha, gla1ve, Goofy, hades, Kylar       |
|           21 |     2427 | 2024-03-11 | Metizport              | W   | 0.831      | 0.143        | 0.188 (0.022)    | 1.000 (0.119)    | -         |     2.07 | dycha, gla1ve, Goofy, hades, Kylar       |
|           20 |     3265 | 2024-02-22 | Astralis               | W   | 0.710      | 0.143        | 0.179 (0.018)    | -                | 1 (0.710) |    10.22 | dycha, gla1ve, Goofy, hades, Kylar       |
|           19 |     3312 | 2024-02-21 | Team Vitality          | L   | 0.704      | -            | -                | -                | -         |    -3.26 | dycha, gla1ve, Goofy, hades, Kylar       |
|           18 |     3371 | 2024-02-20 | GamerLegion            | W   | 0.697      | 0.143        | 0.194 (0.019)    | -                | 1 (0.697) |    11.82 | dycha, gla1ve, Goofy, hades, Kylar       |
|           17 |     3411 | 2024-02-19 | Guild Eagles           | W   | 0.691      | -            | -                | -                | 1 (0.691) |     1.26 | dycha, gla1ve, Goofy, hades, Kylar       |
|           16 |     3426 | 2024-02-19 | Team Spirit            | L   | 0.690      | -            | -                | -                | -         |    -3.14 | dycha, gla1ve, Goofy, hades, Kylar       |
|           15 |     3789 | 2024-02-09 | Team Falcons           | L   | 0.625      | -            | -                | -                | -         |   -13.99 | dycha, gla1ve, Goofy, hades, Kylar       |
|           14 |     3856 | 2024-02-06 | MOUZ                   | L   | 0.605      | -            | -                | -                | -         |    -3.05 | dycha, gla1ve, Goofy, hades, Kylar       |
|           13 |     3903 | 2024-02-05 | G2 Esports             | W   | 0.598      | 1.000        | 0.866 (0.518)    | 0.477 (0.285)    | 1 (0.598) |    16.10 | dycha, gla1ve, Goofy, hades, Kylar       |
|           12 |     3943 | 2024-02-03 | Team Vitality          | W   | 0.586      | 1.000        | 1.000 (0.586)    | 0.353 (0.207)    | 1 (0.586) |    16.33 | dycha, gla1ve, Goofy, hades, Kylar       |
|           11 |     4036 | 2024-02-02 | The MongolZ            | W   | 0.578      | 1.000        | 0.292 (0.169)    | 0.663 (0.383)    | 1 (0.578) |    11.62 | dycha, gla1ve, Goofy, hades, Kylar       |
|           10 |     4064 | 2024-02-01 | Astralis               | W   | 0.572      | 1.000        | 0.179 (0.103)    | 0.279 (0.159)    | 1 (0.572) |     9.66 | dycha, gla1ve, Goofy, hades, Kylar       |
|            9 |     4114 | 2024-01-31 | BIG                    | L   | 0.565      | -            | -                | -                | -         |   -10.91 | dycha, gla1ve, Goofy, hades, Kylar       |
|            8 |     4728 | 2024-01-17 | ENTERPRISE esports     | L   | 0.472      | -            | -                | -                | -         |   -14.82 | dycha, gla1ve, Goofy, hades, Kylar       |
|            7 |     5644 | 2023-12-13 | BIG                    | L   | 0.239      | -            | -                | -                | -         |    -4.75 | Krimbo, mantuu, prosus, s1n, tabseN      |
|            6 |     5680 | 2023-12-12 | FORZE Esports          | W   | 0.229      | -            | -                | -                | -         |     0.12 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            5 |     5928 | 2023-12-06 | EYEBALLERS             | L   | 0.192      | -            | -                | -                | -         |    -5.84 | HEAP, JW, Peppzor, Sapec, SHiNE          |
|            4 |     5985 | 2023-12-05 | SINNERS Esports        | L   | 0.185      | -            | -                | -                | -         |    -5.60 | beastik, KWERTZZ, oskar, SHOCK, ZEDKO    |
|            3 |     6393 | 2023-11-26 | Rebels Gaming          | L   | 0.125      | -            | -                | -                | -         |    -3.51 | Goofy, hades, jcobbb, KEi, Kylar         |
|            2 |     6421 | 2023-11-25 | Ex-Anonymo Esports     | W   | 0.119      | -            | -                | -                | -         |     0.04 | Goofy, hades, jcobbb, KEi, Kylar         |
|            1 |     6542 | 2023-11-22 | Turów Zgorzelec Esport | W   | 0.099      | -            | -                | -                | -         |     0.05 | Goofy, hades, jcobbb, KEi, Kylar         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($59,787.30)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.38) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      1.000 | $15,000.00     | $15,000.00      |
| 2024-03-31 |      0.965 | $10,000.00     | $9,652.31       |
| 2024-02-11 |      0.638 | $40,000.00     | $25,520.37      |
| 2023-12-13 |      0.239 | $3,500.00      | $835.06         |
| 2023-12-10 |      0.219 | $6,000.00      | $1,311.39       |
| 2023-11-26 |      0.125 | $3,755.12      | $468.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
