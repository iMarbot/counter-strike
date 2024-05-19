### Roster Details<br />
Team Name: HyperSpirit<br />
Roster: ADRON, GEOHYPE, kritik, smekk, swiiffter<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [202](../standings_global.md)<br />
Regional Rank: [134]( ../standings_europe.md)<br />
Final Rank Value:  711.6<br />
<br />
Final Rank Value (711.6) = Starting Rank Value (735.6) + Head To Head Adjustments (-24.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.326[<sup>1</sup>](#table2)
- Bounty Collected: 0.267[<sup>2</sup>](#table1)
- Opponent Network: 0.083[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 735.6
- 400 + ( ( 0.169 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 735.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |      151 | 2024-05-02 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -19.59 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           25 |      480 | 2024-04-25 | Team PeeP            | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | 0 (0.000) |     4.93 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           24 |      537 | 2024-04-24 | Aurora Young Blud    | L   | 1.000      | -            | -                | -                | -         |   -13.48 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           23 |     1143 | 2024-04-12 | Nexus Gaming         | W   | 1.000      | 0.371        | 0.031 (0.012)    | 0.772 (0.287)    | 0 (0.000) |    24.68 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           22 |     1170 | 2024-04-11 | ThunderFlash         | L   | 1.000      | -            | -                | -                | -         |   -13.41 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           21 |     1969 | 2024-03-21 | Raptors Esports Club | L   | 0.899      | -            | -                | -                | -         |   -10.10 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           20 |     2028 | 2024-03-20 | WOPA Esport          | W   | 0.891      | 0.333        | 0.009 (0.003)    | 0.485 (0.144)    | 0 (0.000) |    15.26 | ADRON, kritik, smekk, starkiller, swiiffter |
|           19 |     2049 | 2024-03-19 | LEON Esports         | W   | 0.886      | 0.333        | 0.003 (0.001)    | 0.357 (0.105)    | 0 (0.000) |    13.60 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           18 |     2096 | 2024-03-18 | ADEPTS               | W   | 0.878      | 0.333        | 0.002 (0.001)    | 0.116 (0.034)    | 0 (0.000) |    12.52 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           17 |     2219 | 2024-03-15 | Preasy Esport        | W   | 0.858      | 0.333        | 0.007 (0.002)    | 0.525 (0.150)    | 0 (0.000) |    15.58 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           16 |     2322 | 2024-03-13 | Oxuji Esports        | W   | 0.845      | 0.333        | 0.000 (0.000)    | 0.058 (0.016)    | 0 (0.000) |     8.05 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           15 |     2462 | 2024-03-10 | LEON Esports         | L   | 0.824      | -            | -                | -                | -         |   -12.13 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           14 |     2560 | 2024-03-07 | Part Timers          | W   | 0.806      | 0.333        | 0.000 (0.000)    | 0.123 (0.033)    | 0 (0.000) |     6.67 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           13 |     2739 | 2024-03-04 | AMKAL ESPORTS        | L   | 0.786      | -            | -                | -                | -         |    -1.45 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           12 |     2851 | 2024-03-02 | 9INE                 | L   | 0.772      | -            | -                | -                | -         |   -14.22 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           11 |     3752 | 2024-02-11 | DASH                 | L   | 0.638      | -            | -                | -                | -         |    -8.69 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|           10 |     3980 | 2024-02-03 | L&G                  | L   | 0.584      | -            | -                | -                | -         |   -13.19 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            9 |     4269 | 2024-01-27 | AIRLYA               | L   | 0.538      | -            | -                | -                | -         |   -12.60 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            8 |     4326 | 2024-01-26 | 500                  | L   | 0.531      | -            | -                | -                | -         |    -6.69 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            7 |     4327 | 2024-01-26 | ILLYRIANS            | W   | 0.531      | 0.143        | 0.001 (0.000)    | 0.308 (0.023)    | 0 (0.000) |     8.36 | ADRON, GEOHYPE, kritik, smekk, swiiffter    |
|            6 |     4921 | 2024-01-12 | Team Space           | L   | 0.439      | -            | -                | -                | -         |    -6.79 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            5 |     5043 | 2024-01-10 | HAVU Gaming          | L   | 0.426      | -            | -                | -                | -         |    -4.26 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            4 |     5674 | 2023-12-12 | Passion UA           | L   | 0.231      | -            | -                | -                | -         |    -1.32 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            3 |     5698 | 2023-12-11 | TOOMUCHVIDEOGAMES    | W   | 0.225      | 0.333        | -                | 0.161 (0.012)    | 0 (0.000) |     1.56 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            2 |     5759 | 2023-12-09 | Team OWL             | W   | 0.212      | -            | -                | -                | -         |     1.34 | ADRON, awks, GEOHYPE, kritik, swiiffter     |
|            1 |     5881 | 2023-12-07 | RUR Esports          | W   | 0.199      | 0.333        | 0.000 (0.000)    | -                | -         |     1.33 | ADRON, awks, GEOHYPE, kritik, swiiffter     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,368.47)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
