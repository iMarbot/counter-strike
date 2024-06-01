### Roster Details<br />
Team Name: Raptors Esports Club<br />
Roster: AdamJC, BehinDx, Karrar, PrimeOPI, wfn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [126](../standings_global.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
Final Rank Value:  812.8<br />
<br />
Final Rank Value (812.8) = Starting Rank Value (849.5) + Head To Head Adjustments (-36.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.178[<sup>2</sup>](#table1)

The average of these factors is 0.221<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 849.5
- 400 + ( ( 0.221 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 849.5


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
|           41 |      112 | 2024-05-28 | Halal5                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.20 | AdamJC, BehinDx, Karrar, PrimeOPI, wfn   |
|           40 |      338 | 2024-05-24 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -13.11 | BehinDx, deuce, Karrar, PrimeOPI, wfn    |
|           39 |      558 | 2024-05-21 | Halal5                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.65 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           38 |      574 | 2024-05-21 | EXO Clan               | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.510 (0.073)    | 0 (0.000) |    16.20 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           37 |      671 | 2024-05-20 | Team PeeP              | L   | 1.000      | -            | -                | -                | -         |   -22.92 | BehinDx, deuce, Karrar, PrimeOPI, wfn    |
|           36 |      878 | 2024-05-18 | Viperio                | L   | 1.000      | -            | -                | -                | -         |   -18.41 | AdamJC, BehinDx, Karrar, PrimeOPI, wfn   |
|           35 |      973 | 2024-05-17 | GamerLegion Academy    | L   | 1.000      | -            | -                | -                | -         |   -15.14 | BehinDx, deuce, Karrar, PrimeOPI, wfn    |
|           34 |     1053 | 2024-05-16 | FearFerox              | W   | 1.000      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     7.70 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           33 |     1147 | 2024-05-15 | Lausanne-Sport Esports | W   | 1.000      | 0.372        | 0.002 (0.001)    | 0.257 (0.096)    | 0 (0.000) |    11.44 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           32 |     1159 | 2024-05-15 | Verdant                | L   | 1.000      | -            | -                | -                | -         |   -12.41 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           31 |     1549 | 2024-05-09 | The Last Resort        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.35 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           30 |     1554 | 2024-05-09 | JANO Esports           | L   | 1.000      | -            | -                | -                | -         |   -21.48 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           29 |     1671 | 2024-05-07 | ROYALS                 | W   | 1.000      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     8.79 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           28 |     1971 | 2024-05-01 | Eternal Fire Academy   | L   | 1.000      | -            | -                | -                | -         |   -27.05 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           27 |     2018 | 2024-04-30 | Part Timers            | W   | 1.000      | -            | -                | -                | -         |     8.31 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           26 |     2308 | 2024-04-25 | los kogutos            | L   | 0.970      | -            | -                | -                | -         |   -16.53 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           25 |     2405 | 2024-04-23 | Team Invictum          | W   | 0.958      | -            | -                | -                | -         |     6.93 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           24 |     2900 | 2024-04-16 | Dynamo Eclot           | W   | 0.911      | 0.372        | 0.097 (0.033)    | 0.936 (0.317)    | -         |    19.55 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           23 |     2940 | 2024-04-15 | TopTab Club            | W   | 0.904      | 0.372        | -                | 0.135 (0.045)    | -         |     4.05 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           22 |     3808 | 2024-03-27 | Ninjas in Pyjamas      | L   | 0.777      | -            | -                | -                | -         |    -5.04 | alex, BluePho3nix, maxster, REZ, Silence |
|           21 |     3860 | 2024-03-26 | ex-Preasy Esport       | W   | 0.771      | 0.143        | 0.052 (0.006)    | 0.381 (0.042)    | -         |    17.25 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           20 |     3979 | 2024-03-23 | Dynamo Eclot           | L   | 0.751      | -            | -                | -                | -         |    -5.67 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           19 |     4071 | 2024-03-21 | HyperSpirit            | W   | 0.738      | 0.333        | 0.004 (0.001)    | 0.356 (0.088)    | -         |     9.51 | ADRON, GEOHYPE, kritik, smekk, swiiffter |
|           18 |     4125 | 2024-03-20 | Dynamo Eclot           | L   | 0.731      | -            | -                | -                | -         |    -5.13 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           17 |     4196 | 2024-03-18 | WOPA Esport            | W   | 0.718      | 0.333        | 0.003 (0.001)    | 0.594 (0.142)    | -         |    10.63 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy     |
|           16 |     4369 | 2024-03-15 | fragmatic              | W   | 0.698      | 0.333        | -                | 0.118 (0.027)    | -         |     3.91 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           15 |     4417 | 2024-03-14 | EXO Clan               | L   | 0.691      | -            | -                | -                | -         |    -6.41 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           14 |     4550 | 2024-03-12 | TopTab Club            | W   | 0.678      | 0.333        | -                | 0.135 (0.031)    | -         |     3.46 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           13 |     4799 | 2024-03-07 | naChille               | W   | 0.645      | 0.333        | 0.004 (0.001)    | 0.140 (0.030)    | -         |     5.67 | Dosia, dukefissura, ice, kade0, mou      |
|           12 |     5348 | 2024-02-27 | The Neighbours         | L   | 0.585      | -            | -                | -                | -         |   -13.23 | AwaykeN, Duplicate, eraa, RuStY, Thomas  |
|           11 |     5466 | 2024-02-25 | EXO Clan               | L   | 0.568      | -            | -                | -                | -         |    -5.75 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           10 |     5497 | 2024-02-24 | Part Timers            | W   | 0.565      | -            | -                | -                | 1 (0.565) |     6.22 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|            9 |     5529 | 2024-02-24 | ROYALS                 | W   | 0.564      | 0.143        | 0.003 (0.000)    | -                | 1 (0.564) |     6.11 | jeyN, joeyyy, oskvr, Ping, Swaggy        |
|            8 |     5555 | 2024-02-24 | ex-K10                 | L   | 0.563      | -            | -                | -                | -         |    -9.13 | Rezst, shyyne, SLY, Tree, yz0            |
|            7 |     5596 | 2024-02-23 | The Last Resort        | W   | 0.558      | -            | -                | -                | 1 (0.558) |     4.99 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo     |
|            6 |     5752 | 2024-02-20 | ex-K10                 | L   | 0.538      | -            | -                | -                | -         |    -9.20 | Kisynergy, Rezst, shyyne, Tree, yz0      |
|            5 |     6028 | 2024-02-15 | Viperio                | W   | 0.505      | -            | -                | -                | -         |     4.02 | cryths, mAnGo, MMS, ReegaN, zodi         |
|            4 |     6145 | 2024-02-13 | Verdant                | L   | 0.491      | -            | -                | -                | -         |    -4.54 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|            3 |     6288 | 2024-02-09 | REDACTED               | W   | 0.465      | -            | -                | -                | -         |     1.15 | Avi, FelixO, frosty, Heartles, tua       |
|            2 |     6371 | 2024-02-06 | Team Invictum          | W   | 0.445      | -            | -                | -                | -         |     1.10 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|            1 |     6558 | 2024-02-03 | Viperio                | L   | 0.423      | -            | -                | -                | -         |   -10.78 | BehinDx, Karrar, moz, PrimeOPI, wfn      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,122.28)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.751 | $2,200.00      | $1,652.75       |
| 2024-02-25 |      0.570 | $824.13        | $469.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
