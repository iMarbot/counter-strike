### Roster Details<br />
Team Name: Dusty Roots<br />
Roster: alexer, maxxkor, Owen$inhoM, tom1jed, zock<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [246](../standings_global.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
Final Rank Value:  691.6<br />
<br />
Final Rank Value (691.6) = Starting Rank Value (678.9) + Head To Head Adjustments (12.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.278[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.137<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.9
- 400 + ( ( 0.137 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 678.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |       37 | 2024-05-29 | Case Esports           | L   | 1.000      | -            | -                | -                | -         |    -8.30 | alexer, maxxkor, Owen$inhoM, tom1jed, zock |
|           36 |      113 | 2024-05-28 | VELOX Argentina        | W   | 1.000      | 0.284        | 0.000 (0.000)    | -                | 0 (0.000) |    10.75 | alexer, maxxkor, Owen$inhoM, tom1jed, zock |
|           35 |      159 | 2024-05-27 | LA RUGONETA            | W   | 1.000      | 0.284        | -                | 0.055 (0.016)    | 0 (0.000) |     7.74 | alexer, maxxkor, Owen$inhoM, tom1jed, zock |
|           34 |      191 | 2024-05-27 | Galorys                | L   | 1.000      | -            | -                | -                | -         |    -9.01 | alexer, maxxkor, Owen$inhoM, tom1jed, zock |
|           33 |      446 | 2024-05-22 | inSanitY Sports        | W   | 1.000      | 0.143        | -                | 0.271 (0.039)    | 0 (0.000) |    17.84 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           32 |     1608 | 2024-05-08 | inSanitY Sports        | L   | 1.000      | -            | -                | -                | -         |   -13.98 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           31 |     1893 | 2024-05-03 | KRÜ Esports            | L   | 1.000      | -            | -                | -                | -         |   -10.76 | deco, maxxkor, Owen$inhoM, tom1jed, try    |
|           30 |     1928 | 2024-05-02 | TEAM ORUGA             | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |    12.22 | gAtito, kissmyaug, matinaso, pegin, toto   |
|           29 |     1935 | 2024-05-02 | BESTIA                 | L   | 1.000      | -            | -                | -                | -         |    -8.39 | deco, maxxkor, Owen$inhoM, tom1jed, try    |
|           28 |     1971 | 2024-05-01 | Case Esports           | L   | 1.000      | -            | -                | -                | -         |    -9.54 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           27 |     1993 | 2024-05-01 | Sensei Team            | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    17.43 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           26 |     2130 | 2024-04-28 | LaChampionsLiga        | W   | 0.991      | -            | -                | -                | 0 (0.000) |     9.72 | deco, maxxkor, Owen$inhoM, tom1jed, try    |
|           25 |     2187 | 2024-04-27 | ZVIJERI                | W   | 0.985      | -            | -                | -                | 0 (0.000) |     5.45 | deco, maxxkor, Owen$inhoM, tom1jed, try    |
|           24 |     2387 | 2024-04-24 | Vikings KR             | L   | 0.965      | -            | -                | -                | -         |   -12.88 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           23 |     2798 | 2024-04-18 | 9z Academy             | W   | 0.925      | 0.143        | 0.002 (0.000)    | 0.311 (0.041)    | 0 (0.000) |    12.37 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           22 |     2957 | 2024-04-16 | ODDIK Academy          | W   | 0.912      | 0.143        | 0.001 (0.000)    | 0.134 (0.017)    | 0 (0.000) |    12.29 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           21 |     3074 | 2024-04-13 | Sharks Youngsters      | W   | 0.891      | 0.143        | 0.003 (0.000)    | 0.407 (0.052)    | 0 (0.000) |    13.23 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           20 |     3080 | 2024-04-13 | 9z Academy             | L   | 0.891      | -            | -                | -                | -         |   -14.97 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           19 |     3128 | 2024-04-12 | Vex Dragons            | W   | 0.885      | -            | -                | -                | -         |     5.28 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           18 |     3569 | 2024-04-04 | FURIA Academy          | L   | 0.831      | -            | -                | -                | -         |   -14.09 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           17 |     3711 | 2024-04-01 | Corinthians Esports    | W   | 0.811      | 0.143        | 0.002 (0.000)    | 0.458 (0.053)    | -         |    13.69 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           16 |     3825 | 2024-03-28 | Bounty Hunters Esports | L   | 0.784      | -            | -                | -                | -         |   -16.14 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           15 |     3945 | 2024-03-26 | paiN Gaming Academy    | W   | 0.772      | 0.143        | 0.005 (0.001)    | 0.346 (0.038)    | -         |    15.28 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           14 |     4119 | 2024-03-22 | Intense Game           | L   | 0.745      | -            | -                | -                | -         |    -9.70 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           13 |     4156 | 2024-03-21 | TIME DE PESO           | W   | 0.738      | -            | -                | -                | -         |     5.96 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           12 |     4172 | 2024-03-21 | Vikings KR             | L   | 0.738      | -            | -                | -                | -         |   -10.55 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           11 |     4227 | 2024-03-20 | MIBR Academy           | W   | 0.731      | 0.262        | 0.005 (0.001)    | 0.448 (0.086)    | -         |    13.62 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|           10 |     4256 | 2024-03-19 | inSanitY Sports        | W   | 0.725      | -            | -                | -                | -         |     6.81 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            9 |     4524 | 2024-03-14 | Yawara E-Sports        | W   | 0.692      | 0.262        | 0.002 (0.000)    | 0.319 (0.058)    | -         |    12.48 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            8 |     5977 | 2024-02-19 | Salão do Corte         | L   | 0.533      | -            | -                | -                | -         |    -8.98 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            7 |     6151 | 2024-02-16 | FURIA Academy          | L   | 0.511      | -            | -                | -                | -         |    -9.86 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            6 |     6387 | 2024-02-12 | Case Esports           | L   | 0.484      | -            | -                | -                | -         |    -3.70 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            5 |     7149 | 2024-01-27 | phantom troupe         | L   | 0.378      | -            | -                | -                | -         |    -7.02 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            4 |     7154 | 2024-01-27 | Vex Dragons            | W   | 0.378      | -            | -                | -                | -         |     2.19 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            3 |     7163 | 2024-01-27 | Full House Gaming      | L   | 0.378      | -            | -                | -                | -         |    -6.17 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            2 |     7294 | 2024-01-25 | Flamengo Esports       | L   | 0.366      | -            | -                | -                | -         |    -7.61 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |
|            1 |     7951 | 2024-01-15 | paiN Gaming            | L   | 0.299      | -            | -                | -                | -         |    -0.04 | alexer, guishu, KvNs, maxxkor, Owen$inhoM  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($769.93)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
