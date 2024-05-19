### Roster Details<br />
Team Name: Raptors Esports Club<br />
Roster: BehinDx, Karrar, moz, PrimeOPI, wfn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [103](../standings_global.md)<br />
Regional Rank: [75]( ../standings_europe.md)<br />
Final Rank Value:  856.1<br />
<br />
Final Rank Value (856.1) = Starting Rank Value (869.2) + Head To Head Adjustments (-13.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.362[<sup>1</sup>](#table2)
- Bounty Collected: 0.325[<sup>2</sup>](#table1)
- Opponent Network: 0.075[<sup>2</sup>](#table1)
- LAN Wins: 0.185[<sup>2</sup>](#table1)

The average of these factors is 0.237<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 869.2
- 400 + ( ( 0.237 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 869.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      192 | 2024-05-01 | Eternal Fire Academy | L   | 1.000      | -            | -                | -                | -         |   -27.51 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           30 |      231 | 2024-04-30 | Part Timers          | W   | 1.000      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.54 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           29 |      561 | 2024-04-23 | Team Invictum        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |     3.73 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           28 |      996 | 2024-04-16 | Dynamo Eclot         | W   | 1.000      | 0.371        | 0.189 (0.070)    | 0.953 (0.354)    | 0 (0.000) |    21.57 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           27 |     1034 | 2024-04-15 | TopTab Club          | W   | 1.000      | 0.371        | -                | 0.065 (0.024)    | 0 (0.000) |     4.21 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           26 |     1752 | 2024-03-27 | Ninjas in Pyjamas    | L   | 0.938      | -            | -                | -                | -         |    -5.26 | alex, BluePho3nix, maxster, REZ, Silence        |
|           25 |     1799 | 2024-03-26 | Grannys Knockers     | W   | 0.932      | 0.143        | 0.061 (0.008)    | 0.177 (0.024)    | 0 (0.000) |    17.20 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           24 |     1889 | 2024-03-23 | Dynamo Eclot         | L   | 0.912      | -            | -                | -                | -         |    -6.17 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           23 |     1969 | 2024-03-21 | HyperSpirit          | W   | 0.899      | 0.333        | 0.009 (0.003)    | 0.293 (0.088)    | 0 (0.000) |    10.10 | ADRON, GEOHYPE, kritik, smekk, swiiffter        |
|           22 |     2017 | 2024-03-20 | Dynamo Eclot         | L   | 0.892      | -            | -                | -                | -         |    -5.50 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           21 |     2080 | 2024-03-18 | WOPA Esport          | W   | 0.879      | 0.333        | 0.009 (0.003)    | 0.485 (0.142)    | 0 (0.000) |    11.34 | brzer, Gnøffe, Leakz, LUMSEN, Pellyy            |
|           20 |     2257 | 2024-03-14 | EXO Clan             | L   | 0.852      | -            | -                | -                | -         |   -11.12 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           19 |     2367 | 2024-03-12 | TopTab Club          | W   | 0.839      | 0.333        | -                | 0.065 (0.018)    | -         |     4.05 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           18 |     2563 | 2024-03-07 | XGOD                 | W   | 0.806      | -            | -                | -                | -         |     3.33 | Dosia, dukefissura, ice, kade0, mou             |
|           17 |     3014 | 2024-02-27 | The Neighbours       | L   | 0.746      | -            | -                | -                | -         |   -16.58 | AwaykeN, Duplicate, eraa, RuStY, Thomas         |
|           16 |     3133 | 2024-02-24 | Rum Bumpers          | W   | 0.726      | 0.143        | 0.002 (0.000)    | -                | 1 (0.726) |     7.17 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           15 |     3170 | 2024-02-24 | K10                  | L   | 0.724      | -            | -                | -                | -         |   -11.14 | Rezst, shyyne, SLY, Tree, yz0                   |
|           14 |     3201 | 2024-02-23 | The Last Resort      | W   | 0.720      | 0.143        | 0.001 (0.000)    | 0.240 (0.025)    | 1 (0.720) |     6.90 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo            |
|           13 |     3342 | 2024-02-20 | K10                  | L   | 0.699      | -            | -                | -                | -         |   -11.46 | Kisynergy, Rezst, shyyne, Tree, yz0             |
|           12 |     3568 | 2024-02-15 | Viperio              | W   | 0.666      | 0.143        | -                | 0.321 (0.031)    | -         |     5.71 | cryths, mAnGo, MMS, ReegaN, zodi                |
|           11 |     3668 | 2024-02-13 | Verdant              | L   | 0.652      | -            | -                | -                | -         |    -6.38 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|           10 |     3786 | 2024-02-09 | REDACTED             | W   | 0.626      | -            | -                | -                | -         |     1.41 | Avi, FelixO, frosty, Heartles, tua              |
|            9 |     3810 | 2024-02-08 | The Last Resort      | W   | 0.619      | 0.143        | 0.001 (0.000)    | 0.240 (0.021)    | -         |     5.13 | AdamJC, Bigun, Fizzy, Flicky, ve1nzo            |
|            8 |     3853 | 2024-02-06 | Team Invictum        | W   | 0.606      | -            | -                | -                | -         |     1.41 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|            7 |     3990 | 2024-02-03 | Viperio              | L   | 0.584      | -            | -                | -                | -         |   -14.68 | BehinDx, Karrar, moz, PrimeOPI, wfn             |
|            6 |     5727 | 2023-12-10 | K10                  | L   | 0.217      | -            | -                | -                | -         |    -3.24 | BehinDx, Fizzy, Karrar, luccs, moz              |
|            5 |     5762 | 2023-12-09 | Viperio              | W   | 0.212      | -            | -                | -                | 1 (0.212) |     1.25 | JAUSTERE, MMS, papp, ReegaN, zodi               |
|            4 |     5782 | 2023-12-09 | Verdant              | L   | 0.210      | -            | -                | -                | -         |    -2.17 | BehinDx, Fizzy, Karrar, luccs, moz              |
|            3 |     6349 | 2023-11-27 | The Last Resort      | W   | 0.132      | 0.143        | 0.001 (0.000)    | -                | -         |     1.06 | AdamJC, Bigun, Flicky, ve1nzo, Wiiam            |
|            2 |     6743 | 2023-11-18 | Endpoint             | L   | 0.070      | -            | -                | -                | -         |    -1.17 | BehinDx, Fizzy, Karrar, luccs, PrimeOPI         |
|            1 |     6803 | 2023-11-16 | Souls-Land           | W   | 0.059      | -            | -                | -                | -         |     0.15 | Harborboy, Kisynergy, SundanceK1d, wh1mzzz, xrt |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,715.17)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-23 |      0.912 | $2,200.00      | $2,007.09       |
| 2024-02-24 |      0.726 | $824.13        | $598.38         |
| 2023-12-10 |      0.219 | $501.92        | $109.70         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
