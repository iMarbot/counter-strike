### Roster Details<br />
Team Name: Revenge Nation<br />
Roster: HorizoN, MagiC, S0ph3R, TABEN, xam<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [205](../standings_global.md)<br />
Regional Rank: [137]( ../standings_europe.md)<br />
Final Rank Value:  707.3<br />
<br />
Final Rank Value (707.3) = Starting Rank Value (726.3) + Head To Head Adjustments (-19.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.423[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.164<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 726.3
- 400 + ( ( 0.164 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 726.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     2549 | 2024-03-07 | Villainous                 | W   | 0.808      | 0.371        | 0.002 (0.001)    | 0.082 (0.024)    | false (0.000) |     8.32 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           16 |     2662 | 2024-03-05 | LOSTHILLS                  | W   | 0.794      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.96 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           15 |     3557 | 2024-02-15 | FLUFFY AIMERS              | L   | 0.667      | -            | -                | -                | -             |   -11.33 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           14 |     4298 | 2024-01-26 | LOS                        | L   | 0.534      | -            | -                | -                | -             |   -12.46 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           13 |     4417 | 2024-01-23 | One More Esports           | L   | 0.514      | -            | -                | -                | -             |    -8.23 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           12 |     5019 | 2024-01-10 | Rocket                     | L   | 0.428      | -            | -                | -                | -             |    -7.79 | HorizoN, MagiC, S0ph3R, TABEN, xam          |
|           11 |     5065 | 2024-01-09 | MishMash Gaming            | W   | 0.421      | 0.143        | 0.000 (0.000)    | 0.015 (0.001)    | false (0.000) |     2.83 | HorizoN, MagiC, Rulik, S0ph3R, TABEN        |
|           10 |     5135 | 2024-01-08 | Team Dennys                | W   | 0.415      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.06 | carN, MOOSELFLiES, mst, OrnateRope, Two-Six |
|            9 |     5421 | 2023-12-16 | Rocket                     | L   | 0.261      | -            | -                | -                | -             |    -4.87 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            8 |     5625 | 2023-12-13 | One More Esports           | L   | 0.241      | -            | -                | -                | -             |    -3.99 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            7 |     5682 | 2023-12-11 | Pantsu                     | W   | 0.228      | 0.371        | 0.005 (0.000)    | 0.020 (0.002)    | false (0.000) |     2.86 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            6 |     5708 | 2023-12-10 | MIGHT                      | W   | 0.221      | 0.371        | 0.003 (0.000)    | 0.213 (0.017)    | false (0.000) |     3.39 | djay, Louie, Nifty, scar, stamina           |
|            5 |     5750 | 2023-12-09 | LAG Gaming (American team) | W   | 0.214      | 0.371        | 0.033 (0.003)    | 0.405 (0.032)    | false (0.000) |     5.33 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            4 |     5859 | 2023-12-07 | Team Steve                 | W   | 0.201      | 0.371        | 0.000 (0.000)    | 0.007 (0.000)    | false (0.000) |     0.89 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |
|            3 |     5908 | 2023-12-06 | Spectre Tavius             | W   | 0.194      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     0.85 | Dante, jaay, oreosss, rayxts, YOSH1         |
|            2 |     5954 | 2023-12-05 | LAG Gaming (American team) | L   | 0.188      | -            | -                | -                | -             |    -1.22 | based, Experative, Nyyx, ogwizard, X-23     |
|            1 |     6945 | 2023-11-13 | Carpe Diem                 | L   | 0.041      | -            | -                | -                | -             |    -0.64 | HorizoN, NIGHT666LADE, Rulik, S0ph3R, TABEN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,874.82)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-11 |      0.834 | $7,000.00      | $5,838.84       |
| 2023-12-13 |      0.241 | $4,300.00      | $1,035.98       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
