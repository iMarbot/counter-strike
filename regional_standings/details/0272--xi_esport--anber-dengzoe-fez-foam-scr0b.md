### Roster Details<br />
Team Name: XI Esport<br />
Roster: anber, Dengzoe, fez, foam, Scr0b<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [272](../standings_global.md)<br />
Regional Rank: [170]( ../standings_europe.md)<br />
Final Rank Value:  641.7<br />
<br />
Final Rank Value (641.7) = Starting Rank Value (693.3) + Head To Head Adjustments (-51.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.272[<sup>1</sup>](#table2)
- Bounty Collected: 0.262[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.3
- 400 + ( ( 0.148 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 693.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |       30 | 2024-05-05 | Kronjyllands Esport  | L   | 1.000      | -            | -                | -                | -         |   -22.73 | anber, Dengzoe, fez, foam, Scr0b    |
|           40 |      140 | 2024-05-02 | L&G                  | L   | 1.000      | -            | -                | -                | -         |   -12.54 | anber, Dengzoe, fez, foam, Scr0b    |
|           39 |      210 | 2024-05-01 | Natus Vincere Youth  | W   | 1.000      | 0.289        | 0.013 (0.004)    | 0.306 (0.089)    | 0 (0.000) |    19.25 | anber, Dengzoe, fez, foam, Scr0b    |
|           38 |      268 | 2024-04-29 | IMMAPROBLEM          | L   | 1.000      | -            | -                | -                | -         |   -21.52 | anber, Dengzoe, fez, foam, Scr0b    |
|           37 |      274 | 2024-04-29 | Astralis Talent      | L   | 1.000      | -            | -                | -                | -         |    -8.21 | anber, Dengzoe, fez, foam, Scr0b    |
|           36 |      304 | 2024-04-28 | L&G                  | W   | 1.000      | 0.289        | 0.012 (0.003)    | 0.276 (0.080)    | 0 (0.000) |    17.79 | anber, Dengzoe, fez, foam, Scr0b    |
|           35 |      484 | 2024-04-25 | KUUSAMO.gg           | W   | 1.000      | 0.289        | 0.005 (0.002)    | 0.153 (0.044)    | 0 (0.000) |    20.32 | anber, Dengzoe, fez, foam, Scr0b    |
|           34 |      515 | 2024-04-24 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -16.29 | anber, Dengzoe, fez, foam, Scr0b    |
|           33 |      602 | 2024-04-22 | Preasy Esport        | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.525 (0.075)    | 0 (0.000) |    17.43 | anber, Dengzoe, fez, foam, Scr0b    |
|           32 |      647 | 2024-04-21 | SINNERS Academy      | L   | 1.000      | -            | -                | -                | -         |   -14.07 | anber, Dengzoe, fez, foam, Scr0b    |
|           31 |      696 | 2024-04-20 | MASONIC              | L   | 1.000      | -            | -                | -                | -         |    -7.37 | anber, Dengzoe, fez, foam, Scr0b    |
|           30 |      948 | 2024-04-17 | KUUSAMO.gg           | W   | 1.000      | 0.289        | 0.005 (0.002)    | 0.153 (0.044)    | 0 (0.000) |    20.64 | anber, Dengzoe, fez, foam, Scr0b    |
|           29 |      997 | 2024-04-16 | WOPA Esport          | L   | 1.000      | -            | -                | -                | -         |   -11.29 | anber, Dengzoe, fez, foam, Scr0b    |
|           28 |     1844 | 2024-03-25 | Astralis Talent      | L   | 0.925      | -            | -                | -                | -         |    -6.68 | anber, Dengzoe, fez, foam, Scr0b    |
|           27 |     2267 | 2024-03-14 | Preasy Esport        | L   | 0.852      | -            | -                | -                | -         |   -10.81 | anber, Dengzoe, fez, foam, Scr0b    |
|           26 |     2371 | 2024-03-12 | Clownfiesta          | W   | 0.839      | -            | -                | -                | 0 (0.000) |     6.88 | anber, Dengzoe, fez, foam, Scr0b    |
|           25 |     2396 | 2024-03-11 | Astralis Talent      | L   | 0.832      | -            | -                | -                | -         |    -5.88 | anber, Dengzoe, fez, foam, Scr0b    |
|           24 |     2406 | 2024-03-11 | Copenhagen Wolves    | W   | 0.832      | 0.143        | -                | 0.417 (0.050)    | 0 (0.000) |    12.04 | anber, Dengzoe, fez, foam, Scr0b    |
|           23 |     2480 | 2024-03-09 | Begrip Gaming        | W   | 0.819      | 0.333        | 0.001 (0.000)    | 0.196 (0.053)    | 0 (0.000) |    11.63 | anber, Dengzoe, fez, foam, Scr0b    |
|           22 |     2564 | 2024-03-07 | ADEPTS               | L   | 0.806      | -            | -                | -                | -         |   -12.86 | anber, Dengzoe, fez, foam, Scr0b    |
|           21 |     2602 | 2024-03-06 | WOPA Esport          | L   | 0.799      | -            | -                | -                | -         |    -9.77 | anber, Dengzoe, fez, foam, Scr0b    |
|           20 |     2691 | 2024-03-05 | IMMAPROBLEM          | L   | 0.792      | -            | -                | -                | -         |   -17.35 | anber, Dengzoe, fez, foam, Scr0b    |
|           19 |     3018 | 2024-02-27 | Preasy Esport        | W   | 0.746      | 0.143        | 0.007 (0.001)    | 0.525 (0.056)    | 0 (0.000) |    14.30 | anber, Dengzoe, fez, foam, Scr0b    |
|           18 |     3025 | 2024-02-27 | Team Atlantic        | L   | 0.745      | -            | -                | -                | -         |   -16.26 | anber, Dengzoe, fez, foam, Scr0b    |
|           17 |     3750 | 2024-02-11 | GODSENT              | L   | 0.638      | -            | -                | -                | -         |    -7.82 | anber, Dengzoe, fez, foam, Scr0b    |
|           16 |     3858 | 2024-02-06 | IMMAPROBLEM          | W   | 0.605      | -            | -                | -                | 0 (0.000) |     5.96 | anber, Dengzoe, fez, foam, Scr0b    |
|           15 |     3882 | 2024-02-05 | Team Atlantic        | W   | 0.599      | -            | -                | -                | -         |     5.52 | anber, Dengzoe, fez, foam, Scr0b    |
|           14 |     3890 | 2024-02-05 | Copenhagen Wolves    | W   | 0.599      | -            | -                | -                | -         |     8.94 | anber, Dengzoe, fez, foam, Scr0b    |
|           13 |     3902 | 2024-02-05 | Preasy Esport        | L   | 0.598      | -            | -                | -                | -         |    -7.57 | anber, Dengzoe, fez, foam, Scr0b    |
|           12 |     3973 | 2024-02-03 | Lilmix               | L   | 0.585      | -            | -                | -                | -         |   -11.63 | anber, Dengzoe, fez, foam, Scr0b    |
|           11 |     4459 | 2024-01-22 | Astralis Talent      | W   | 0.506      | 0.143        | 0.030 (0.002)    | 0.613 (0.044)    | -         |    13.21 | anber, Dengzoe, fez, foam, Scr0b    |
|           10 |     4464 | 2024-01-22 | Sashi Esport         | L   | 0.505      | -            | -                | -                | -         |    -5.35 | anber, Dengzoe, fez, foam, Scr0b    |
|            9 |     4813 | 2024-01-16 | Endpoint             | L   | 0.465      | -            | -                | -                | -         |    -4.54 | anber, Dengzoe, fez, foam, Scr0b    |
|            8 |     5046 | 2024-01-10 | Kappa Bar            | W   | 0.426      | -            | -                | -                | -         |     6.36 | anber, Dengzoe, fez, foam, Scr0b    |
|            7 |     5670 | 2023-12-12 | Eternal Fire Academy | L   | 0.232      | -            | -                | -                | -         |    -3.39 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            6 |     5699 | 2023-12-11 | WOPA Esport          | W   | 0.225      | 0.333        | 0.009 (0.001)    | 0.485 (0.036)    | -         |     4.36 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            5 |     5923 | 2023-12-06 | Pungrottorna         | L   | 0.192      | -            | -                | -                | -         |    -4.59 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            4 |     5993 | 2023-12-05 | Preasy Esport        | W   | 0.184      | 0.333        | 0.007 (0.000)    | -                | -         |     3.92 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            3 |     6951 | 2023-11-13 | Exzentriq United     | L   | 0.039      | -            | -                | -                | -         |    -0.95 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            2 |     6964 | 2023-11-13 | MASONIC Academy      | W   | 0.039      | -            | -                | -                | -         |     0.20 | anber, Dengzoe, foam, Pellyy, Scr0b |
|            1 |     6974 | 2023-11-13 | IMMAPROBLEM          | L   | 0.038      | -            | -                | -                | -         |    -0.86 | anber, Dengzoe, foam, Pellyy, Scr0b |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($334.90)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
