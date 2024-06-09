### Roster Details<br />
Team Name: Raptors Esports Club<br />
Roster: AdamJC, BehinDx, Karrar, PrimeOPI, wfn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [145](../standings_global.md)<br />
Regional Rank: [102]( ../standings_europe.md)<br />
Final Rank Value:  792.2<br />
<br />
Final Rank Value (792.2) = Starting Rank Value (850.5) + Head To Head Adjustments (-58.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.092[<sup>2</sup>](#table1)
- LAN Wins: 0.178[<sup>2</sup>](#table1)

The average of these factors is 0.222<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.5
- 400 + ( ( 0.222 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 850.5


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
|           44 |      120 | 2024-05-28 | Halal5                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.96 | AdamJC, BehinDx, Karrar, PrimeOPI, wfn   |
|           43 |      347 | 2024-05-24 | HOTU                   | L   | 1.000      | -            | -                | -                | -         |   -11.73 | BehinDx, deuce, Karrar, PrimeOPI, wfn    |
|           42 |      569 | 2024-05-21 | Halal5                 | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.55 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           41 |      585 | 2024-05-21 | EXO Clan               | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.579 (0.083)    | 0 (0.000) |    17.67 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           40 |      682 | 2024-05-20 | Team PeeP              | L   | 1.000      | -            | -                | -                | -         |   -21.95 | BehinDx, deuce, Karrar, PrimeOPI, wfn    |
|           39 |      890 | 2024-05-18 | Viperio                | L   | 1.000      | -            | -                | -                | -         |   -17.18 | AdamJC, BehinDx, Karrar, PrimeOPI, wfn   |
|           38 |      985 | 2024-05-17 | GamerLegion Academy    | L   | 1.000      | -            | -                | -                | -         |   -14.37 | BehinDx, deuce, Karrar, PrimeOPI, wfn    |
|           37 |     1063 | 2024-05-16 | FearFerox              | W   | 1.000      | 0.143        | 0.001 (0.000)    | -                | 0 (0.000) |     8.68 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           36 |     1156 | 2024-05-15 | Lausanne-Sport Esports | W   | 1.000      | 0.372        | 0.002 (0.001)    | 0.306 (0.114)    | 0 (0.000) |    13.77 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           35 |     1168 | 2024-05-15 | Verdant                | L   | 1.000      | -            | -                | -                | -         |   -10.81 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           34 |     1564 | 2024-05-09 | The Last Resort        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.68 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           33 |     1569 | 2024-05-09 | JANO Esports           | L   | 1.000      | -            | -                | -                | -         |   -19.54 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           32 |     1689 | 2024-05-07 | ROYALS                 | W   | 1.000      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     9.74 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           31 |     1736 | 2024-05-06 | Grannys Knockers       | L   | 1.000      | -            | -                | -                | -         |   -15.24 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           30 |     1998 | 2024-05-01 | Eternal Fire Academy   | L   | 1.000      | -            | -                | -                | -         |   -26.55 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           29 |     2008 | 2024-05-01 | ex-K10                 | L   | 1.000      | -            | -                | -                | -         |   -18.24 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           28 |     2049 | 2024-04-30 | Part Timers            | W   | 1.000      | 0.143        | -                | 0.218 (0.031)    | -         |     9.14 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           27 |     2345 | 2024-04-25 | los kogutos            | L   | 0.970      | -            | -                | -                | -         |   -16.86 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           26 |     2450 | 2024-04-23 | Team Invictum          | W   | 0.958      | -            | -                | -                | -         |     7.11 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           25 |     2958 | 2024-04-16 | Dynamo Eclot           | W   | 0.911      | 0.372        | 0.097 (0.033)    | 0.940 (0.319)    | -         |    19.70 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           24 |     3001 | 2024-04-15 | TopTab Club            | W   | 0.904      | 0.372        | -                | 0.135 (0.045)    | -         |     4.16 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           23 |     3901 | 2024-03-27 | Ninjas in Pyjamas      | L   | 0.777      | -            | -                | -                | -         |    -4.89 | alex, BluePho3nix, maxster, REZ, Silence |
|           22 |     3957 | 2024-03-26 | ex-Preasy Esport       | W   | 0.771      | 0.143        | 0.052 (0.006)    | 0.381 (0.042)    | -         |    17.53 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           21 |     4077 | 2024-03-23 | Dynamo Eclot           | L   | 0.751      | -            | -                | -                | -         |    -5.61 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           20 |     4169 | 2024-03-21 | HyperSpirit            | W   | 0.738      | 0.333        | 0.004 (0.001)    | 0.356 (0.088)    | -         |     9.69 | ADRON, GEOHYPE, kritik, smekk, swiiffter |
|           19 |     4225 | 2024-03-20 | Dynamo Eclot           | L   | 0.731      | -            | -                | -                | -         |    -5.07 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           18 |     4301 | 2024-03-18 | WOPA Esport            | W   | 0.718      | 0.333        | 0.003 (0.001)    | 0.594 (0.142)    | -         |    10.89 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy     |
|           17 |     4477 | 2024-03-15 | fragmatic              | W   | 0.698      | -            | -                | -                | -         |     4.05 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           16 |     4531 | 2024-03-14 | EXO Clan               | L   | 0.691      | -            | -                | -                | -         |    -5.96 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           15 |     4670 | 2024-03-12 | TopTab Club            | W   | 0.678      | 0.333        | -                | 0.135 (0.031)    | -         |     3.58 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           14 |     4928 | 2024-03-07 | naChille               | W   | 0.645      | 0.333        | 0.004 (0.001)    | 0.140 (0.030)    | -         |     5.83 | Dosia, dukefissura, ice, kade0, mou      |
|           13 |     5501 | 2024-02-27 | The Neighbours         | L   | 0.585      | -            | -                | -                | -         |   -13.31 | AwaykeN, Duplicate, eraa, RuStY, Thomas  |
|           12 |     5624 | 2024-02-25 | EXO Clan               | L   | 0.568      | -            | -                | -                | -         |    -5.34 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           11 |     5657 | 2024-02-24 | Part Timers            | W   | 0.565      | -            | -                | -                | 1 (0.565) |     7.22 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|           10 |     5689 | 2024-02-24 | ROYALS                 | W   | 0.564      | 0.143        | 0.003 (0.000)    | -                | 1 (0.564) |     6.30 | jeyN, joeyyy, oskvr, Ping, Swaggy        |
|            9 |     5715 | 2024-02-24 | ex-K10                 | L   | 0.563      | -            | -                | -                | -         |    -8.62 | Rezst, shyyne, SLY, Tree, yz0            |
|            8 |     5756 | 2024-02-23 | The Last Resort        | W   | 0.558      | -            | -                | -                | 1 (0.558) |     5.20 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo     |
|            7 |     5853 | 2024-02-21 | Part Timers            | L   | 0.545      | -            | -                | -                | -         |   -10.63 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|            6 |     5919 | 2024-02-20 | ex-K10                 | L   | 0.538      | -            | -                | -                | -         |    -8.96 | Kisynergy, Rezst, shyyne, Tree, yz0      |
|            5 |     6204 | 2024-02-15 | Viperio                | W   | 0.505      | -            | -                | -                | -         |     4.20 | cryths, mAnGo, MMS, ReegaN, zodi         |
|            4 |     6328 | 2024-02-13 | Verdant                | L   | 0.491      | -            | -                | -                | -         |    -4.50 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|            3 |     6476 | 2024-02-09 | REDACTED               | W   | 0.465      | -            | -                | -                | -         |     1.14 | Avi, FelixO, frosty, Heartles, tua       |
|            2 |     6566 | 2024-02-06 | Team Invictum          | W   | 0.445      | -            | -                | -                | -         |     1.10 | BehinDx, Karrar, moz, PrimeOPI, wfn      |
|            1 |     6761 | 2024-02-03 | Viperio                | L   | 0.423      | -            | -                | -                | -         |   -10.75 | BehinDx, Karrar, moz, PrimeOPI, wfn      |

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
