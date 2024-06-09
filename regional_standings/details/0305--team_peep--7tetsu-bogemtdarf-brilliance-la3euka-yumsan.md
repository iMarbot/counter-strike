### Roster Details<br />
Team Name: Team PeeP<br />
Roster: 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [305](../standings_global.md)<br />
Regional Rank: [190]( ../standings_europe.md)<br />
Final Rank Value:  642.5<br />
<br />
Final Rank Value (642.5) = Starting Rank Value (604.2) + Head To Head Adjustments (38.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.275[<sup>2</sup>](#table1)
- Opponent Network: 0.127[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 604.2
- 400 + ( ( 0.100 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 604.2


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
|           24 |       85 | 2024-05-29 | RUSH B                | L   | 1.000      | -            | -                | -                | -         |    -7.16 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           23 |      182 | 2024-05-27 | Donstu Esports        | L   | 1.000      | -            | -                | -                | -         |   -17.56 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           22 |      265 | 2024-05-25 | VaselineWorms         | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.418 (0.156)    | 0 (0.000) |    19.83 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           21 |      289 | 2024-05-25 | 5goblinz              | L   | 1.000      | -            | -                | -                | -         |   -21.65 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           20 |      352 | 2024-05-24 | GamerLegion Academy   | W   | 1.000      | 0.372        | 0.018 (0.007)    | 0.691 (0.257)    | 0 (0.000) |    20.52 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           19 |      421 | 2024-05-23 | RUBY                  | L   | 1.000      | -            | -                | -                | -         |    -4.29 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           18 |      470 | 2024-05-22 | FLuffy Gangsters      | L   | 1.000      | -            | -                | -                | -         |   -13.17 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           17 |      602 | 2024-05-21 | Rhyno Esports         | W   | 1.000      | 0.372        | 0.029 (0.011)    | 0.567 (0.211)    | 0 (0.000) |    26.34 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           16 |      682 | 2024-05-20 | Raptors Esports Club  | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    21.95 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           15 |      706 | 2024-05-20 | Endpoint              | L   | 1.000      | -            | -                | -                | -         |    -5.31 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           14 |      751 | 2024-05-19 | V1dar Gaming          | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.595 (0.221)    | 0 (0.000) |    23.42 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           13 |      806 | 2024-05-19 | BAKS Esports          | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.171 (0.024)    | 0 (0.000) |    15.97 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           12 |      967 | 2024-05-17 | LYG Gaming            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.275 (0.039)    | 0 (0.000) |    21.94 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           11 |      980 | 2024-05-17 | 1win Academy          | L   | 1.000      | -            | -                | -                | -         |   -12.86 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|           10 |      998 | 2024-05-17 | Academy Cybersport XP | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.61 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            9 |     1407 | 2024-05-12 | GUN5 Esports          | L   | 1.000      | -            | -                | -                | -         |   -10.69 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            8 |     1629 | 2024-05-08 | ADEPTS                | L   | 1.000      | -            | -                | -                | -         |   -10.89 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            7 |     1803 | 2024-05-05 | naChille              | L   | 1.000      | -            | -                | -                | -         |   -14.52 | bogemtdarf, h1kan, la3euka, m1QUSE, YumsaN      |
|            6 |     2358 | 2024-04-25 | HyperSpirit           | L   | 0.970      | -            | -                | -                | -         |    -8.96 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            5 |     2404 | 2024-04-24 | Lilmix                | W   | 0.964      | 0.372        | 0.006 (0.002)    | 0.593 (0.213)    | 0 (0.000) |    22.94 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            4 |     2557 | 2024-04-21 | Nemiga Gaming         | L   | 0.943      | -            | -                | -                | -         |    -0.97 | bogemtdarf, h1kan, la3euka, LECY, YumsaN        |
|            3 |     3086 | 2024-04-13 | RUSH B                | L   | 0.890      | -            | -                | -                | -         |    -5.74 | bogemtdarf, h1kan, la3euka, LECY, YumsaN        |
|            2 |     3143 | 2024-04-12 | Passion UA            | L   | 0.883      | -            | -                | -                | -         |    -3.23 | 7tetsu, bogemtdarf, Brilliance, la3euka, YumsaN |
|            1 |     3427 | 2024-04-07 | esmagaB               | L   | 0.849      | -            | -                | -                | -         |    -6.20 | abiraju, bogemtdarf, la3euka, LECY, YumsaN      |

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
