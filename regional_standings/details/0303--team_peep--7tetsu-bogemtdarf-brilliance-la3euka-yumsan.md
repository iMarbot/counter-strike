### Roster Details<br />
Team Name: Team PeeP<br />
Roster: 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [303](../standings_global.md)<br />
Regional Rank: [185]( ../standings_europe.md)<br />
Final Rank Value:  640.9<br />
<br />
Final Rank Value (640.9) = Starting Rank Value (602.8) + Head To Head Adjustments (38.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.124[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 602.8
- 400 + ( ( 0.100 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 602.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |       78 | 2024-05-29 | RUSH B                | L   | 1.000      | -            | -                | -                | -         |    -7.34 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           23 |      174 | 2024-05-27 | Donstu Esports        | L   | 1.000      | -            | -                | -                | -         |   -17.53 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           22 |      257 | 2024-05-25 | VaselineWorms         | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.424 (0.158)    | 0 (0.000) |    19.96 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           21 |      281 | 2024-05-25 | 5goblinz              | L   | 1.000      | -            | -                | -                | -         |   -21.59 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           20 |      343 | 2024-05-24 | GamerLegion Academy   | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    20.83 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           19 |      413 | 2024-05-23 | RUBY                  | L   | 1.000      | -            | -                | -                | -         |    -4.32 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           18 |      464 | 2024-05-22 | FLuffy Gangsters      | L   | 1.000      | -            | -                | -                | -         |   -14.18 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           17 |      591 | 2024-05-21 | Rhyno Esports         | W   | 1.000      | 0.372        | 0.029 (0.011)    | 0.518 (0.193)    | 0 (0.000) |    26.08 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           16 |      671 | 2024-05-20 | Raptors Esports Club  | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    22.92 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           15 |      695 | 2024-05-20 | Endpoint              | L   | 1.000      | -            | -                | -                | -         |    -5.71 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           14 |      739 | 2024-05-19 | V1dar Gaming          | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.567 (0.211)    | 0 (0.000) |    23.16 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           13 |      794 | 2024-05-19 | BAKS Esports          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.151 (0.022)    | 0 (0.000) |    16.15 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           12 |      955 | 2024-05-17 | LYG Gaming            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.275 (0.039)    | 0 (0.000) |    22.12 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           11 |      968 | 2024-05-17 | 1win Academy          | L   | 1.000      | -            | -                | -                | -         |   -12.78 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           10 |      986 | 2024-05-17 | Academy Cybersport XP | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.66 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            9 |     1394 | 2024-05-12 | GUN5 Esports          | L   | 1.000      | -            | -                | -                | -         |   -10.98 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            8 |     1615 | 2024-05-08 | ADEPTS                | L   | 1.000      | -            | -                | -                | -         |    -9.97 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            7 |     1780 | 2024-05-05 | naChille              | L   | 1.000      | -            | -                | -                | -         |   -14.45 | bogemtdarf, h1kan, la3euka, m1QUSE, YumsaN      |
|            6 |     2318 | 2024-04-25 | HyperSpirit           | L   | 0.970      | -            | -                | -                | -         |    -8.89 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            5 |     2363 | 2024-04-24 | Lilmix                | W   | 0.964      | 0.372        | 0.006 (0.002)    | 0.581 (0.208)    | 0 (0.000) |    22.78 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            4 |     2504 | 2024-04-21 | Nemiga Gaming         | L   | 0.943      | -            | -                | -                | -         |    -0.94 | bogemtdarf, h1kan, la3euka, LECY, YumsaN        |
|            3 |     3020 | 2024-04-13 | RUSH B                | L   | 0.890      | -            | -                | -                | -         |    -5.94 | bogemtdarf, h1kan, la3euka, LECY, YumsaN        |
|            2 |     3078 | 2024-04-12 | Passion UA            | L   | 0.883      | -            | -                | -                | -         |    -3.58 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            1 |     3346 | 2024-04-07 | esmagaB               | L   | 0.849      | -            | -                | -                | -         |    -6.38 | abiraju, bogemtdarf, la3euka, LECY, YumsaN      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
