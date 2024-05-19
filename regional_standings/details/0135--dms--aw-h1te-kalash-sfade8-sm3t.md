### Roster Details<br />
Team Name: DMS<br />
Roster: AW, H1te, kAlash, sFade8, sm3t<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [135](../standings_global.md)<br />
Regional Rank: [94]( ../standings_europe.md)<br />
Final Rank Value:  793.1<br />
<br />
Final Rank Value (793.1) = Starting Rank Value (649.8) + Head To Head Adjustments (143.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.336[<sup>2</sup>](#table1)
- Opponent Network: 0.168[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 649.8
- 400 + ( ( 0.126 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 649.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |      193 | 2024-05-01 | RUBY                        | W   | 1.000      | 0.371        | -                | 0.882 (0.327)    | false (0.000) |    22.22 | AW, H1te, kAlash, sFade8, sm3t              |
|           42 |      271 | 2024-04-29 | Lilmix                      | L   | 1.000      | -            | -                | -                | -             |   -19.85 | AW, H1te, kAlash, sFade8, sm3t              |
|           41 |      320 | 2024-04-28 | Alliance                    | L   | 1.000      | -            | -                | -                | -             |   -14.03 | AW, H1te, kAlash, sFade8, sm3t              |
|           40 |      440 | 2024-04-26 | BLEED Esports               | L   | 1.000      | -            | -                | -                | -             |    -3.56 | AW, H1te, kAlash, sFade8, sm3t              |
|           39 |      536 | 2024-04-24 | DASH                        | W   | 1.000      | 0.371        | -                | 0.251 (0.093)    | false (0.000) |    11.32 | AW, H1te, kAlash, sFade8, sm3t              |
|           38 |      548 | 2024-04-24 | Permitta Esports            | L   | 1.000      | -            | -                | -                | -             |   -10.27 | AW, H1te, kAlash, sFade8, sm3t              |
|           37 |      572 | 2024-04-23 | EsmagaB                     | W   | 1.000      | 0.371        | 0.016 (0.006)    | 0.559 (0.207)    | false (0.000) |    16.33 | AW, H1te, kAlash, sFade8, sm3t              |
|           36 |      698 | 2024-04-20 | RUSH B (Russian team)       | L   | 1.000      | -            | -                | -                | -             |   -13.64 | AW, H1te, kAlash, sFade8, sm3t              |
|           35 |      870 | 2024-04-18 | Apeks                       | L   | 1.000      | -            | -                | -                | -             |    -1.74 | AW, H1te, kAlash, sFade8, sm3t              |
|           34 |      879 | 2024-04-18 | EYEBALLERS                  | W   | 1.000      | 0.143        | 0.051 (0.007)    | -                | false (0.000) |    21.17 | AW, H1te, kAlash, sFade8, sm3t              |
|           33 |      923 | 2024-04-17 | Gaimin Gladiators           | W   | 1.000      | 0.143        | 0.194 (0.028)    | 0.989 (0.141)    | false (0.000) |    30.52 | AW, H1te, kAlash, sFade8, sm3t              |
|           32 |      967 | 2024-04-17 | HOTU                        | L   | 1.000      | -            | -                | -                | -             |   -15.32 | AW, H1te, kAlash, sFade8, sm3t              |
|           31 |     1008 | 2024-04-16 | UNiTY esports (Slovak team) | L   | 1.000      | -            | -                | -                | -             |   -10.58 | AW, H1te, kAlash, sFade8, sm3t              |
|           30 |     1147 | 2024-04-12 | Dynamo Eclot                | L   | 1.000      | -            | -                | -                | -             |    -7.17 | AW, H1te, kAlash, sFade8, sm3t              |
|           29 |     1344 | 2024-04-08 | Rhyno Esports               | W   | 1.000      | 0.333        | 0.047 (0.016)    | 0.446 (0.149)    | false (0.000) |    19.62 | AW, H1te, kAlash, sFade8, sm3t              |
|           28 |     1404 | 2024-04-06 | LEON Esports                | W   | 1.000      | -            | -                | -                | false (0.000) |    12.95 | AW, H1te, kAlash, sFade8, sm3t              |
|           27 |     1408 | 2024-04-06 | GamerLegion Academy         | W   | 1.000      | 0.143        | 0.043 (0.006)    | 0.567 (0.081)    | false (0.000) |    22.28 | AW, H1te, kAlash, sFade8, sm3t              |
|           26 |     1748 | 2024-03-27 | Aurora Gaming               | L   | 0.938      | -            | -                | -                | -             |    -0.37 | AW, H1te, kAlash, sFade8, sm3t              |
|           25 |     1795 | 2024-03-26 | Permitta Esports            | W   | 0.932      | 0.143        | 0.063 (0.008)    | 1.000 (0.133)    | false (0.000) |    23.35 | AW, H1te, kAlash, sFade8, sm3t              |
|           24 |     2995 | 2024-02-28 | UNiTY esports (Slovak team) | W   | 0.751      | 0.371        | 0.055 (0.015)    | 0.727 (0.203)    | false (0.000) |    17.39 | AW, H1te, kAlash, sFade8, sm3t              |
|           23 |     3031 | 2024-02-27 | B8                          | W   | 0.745      | 0.143        | 0.088 (0.009)    | -                | -             |    19.51 | cptkurtka023, esenthial, npl, OWNER, r1nkle |
|           22 |     3037 | 2024-02-27 | Zero Tenacity               | L   | 0.744      | -            | -                | -                | -             |    -4.55 | AW, H1te, kAlash, sFade8, sm3t              |
|           21 |     3063 | 2024-02-26 | Turów Zgorzelec Esport      | W   | 0.739      | -            | -                | -                | -             |    16.87 | AW, H1te, kAlash, sFade8, sm3t              |
|           20 |     3217 | 2024-02-23 | BLESSED (Ukrainian team)    | L   | 0.718      | -            | -                | -                | -             |    -7.42 | AW, H1te, kAlash, sFade8, sm3t              |
|           19 |     3260 | 2024-02-22 | Aurora Young Blud           | W   | 0.711      | 0.371        | 0.017 (0.005)    | 0.422 (0.112)    | -             |    15.85 | AW, H1te, kAlash, sFade8, sm3t              |
|           18 |     3263 | 2024-02-22 | HOTU                        | L   | 0.711      | -            | -                | -                | -             |    -6.57 | AW, H1te, kAlash, sFade8, sm3t              |
|           17 |     3311 | 2024-02-21 | Insilio                     | W   | 0.704      | 0.371        | 0.020 (0.005)    | 0.875 (0.229)    | -             |    19.05 | faydett, FpSSS, Pipw, Polt, sugaR           |
|           16 |     3733 | 2024-02-12 | CYBERSHOKE Esports          | L   | 0.644      | -            | -                | -                | -             |    -8.39 | AW, H1te, kAlash, sFade8, sm3t              |
|           15 |     3792 | 2024-02-09 | GenOne                      | L   | 0.625      | -            | -                | -                | -             |   -11.31 | AW, H1te, kAlash, sFade8, sm3t              |
|           14 |     3797 | 2024-02-09 | FLuffy Gangsters            | W   | 0.624      | -            | -                | -                | -             |     7.60 | AW, H1te, kAlash, sFade8, sm3t              |
|           13 |     3842 | 2024-02-07 | L&G                         | W   | 0.612      | -            | -                | -                | -             |     7.16 | AW, H1te, kAlash, sFade8, sm3t              |
|           12 |     4723 | 2024-01-17 | Entropiq                    | L   | 0.472      | -            | -                | -                | -             |    -4.28 | AW, H1te, kAlash, sFade8, sm3t              |
|           11 |     6245 | 2023-11-29 | Nexus Gaming                | W   | 0.146      | -            | -                | -                | -             |     3.88 | AW, H1te, kAlash, sFade8, sm3t              |
|           10 |     6267 | 2023-11-29 | Ex-Hot Headed Gaming        | W   | 0.145      | -            | -                | -                | -             |     1.50 | AW, H1te, kAlash, sFade8, sm3t              |
|            9 |     6359 | 2023-11-27 | For The Win Esports         | L   | 0.132      | -            | -                | -                | -             |    -1.85 | AW, H1te, kAlash, sFade8, sm3t              |
|            8 |     6365 | 2023-11-27 | Lajtbitexe                  | W   | 0.132      | -            | -                | -                | -             |     1.59 | AW, H1te, kAlash, sFade8, sm3t              |
|            7 |     6375 | 2023-11-27 | The Witchers                | L   | 0.131      | -            | -                | -                | -             |    -1.31 | AW, H1te, kAlash, sFade8, sm3t              |
|            6 |     6465 | 2023-11-24 | EHawks                      | L   | 0.112      | -            | -                | -                | -             |    -2.26 | AW, H1te, kAlash, sFade8, sm3t              |
|            5 |     6479 | 2023-11-24 | HOTU                        | L   | 0.111      | -            | -                | -                | -             |    -1.05 | AW, H1te, kAlash, sFade8, sm3t              |
|            4 |     6510 | 2023-11-23 | Lemondogs                   | L   | 0.105      | -            | -                | -                | -             |    -1.99 | AW, H1te, kAlash, sFade8, sm3t              |
|            3 |     6526 | 2023-11-23 | GenOne                      | L   | 0.104      | -            | -                | -                | -             |    -1.76 | AW, H1te, kAlash, sFade8, sm3t              |
|            2 |     6640 | 2023-11-20 | Kappa Bar                   | W   | 0.085      | -            | -                | -                | -             |     1.45 | AW, H1te, kAlash, sFade8, sm3t              |
|            1 |     6645 | 2023-11-20 | L&G                         | W   | 0.084      | -            | -                | -                | -             |     0.94 | AW, H1te, kAlash, sFade8, sm3t              |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
