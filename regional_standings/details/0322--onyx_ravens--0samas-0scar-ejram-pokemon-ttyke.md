### Roster Details<br />
Team Name: Onyx Ravens<br />
Roster: 0SAMAS, 0scar, Ejram, PokemoN, TTyke<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [322](../standings_global.md)<br />
Regional Rank: [51]( ../standings_asia.md)<br />
Final Rank Value:  629.2<br />
<br />
Final Rank Value (629.2) = Starting Rank Value (625.9) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.254[<sup>1</sup>](#table2)
- Bounty Collected: 0.170[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.9
- 400 + ( ( 0.111 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 625.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     2759 | 2024-04-19 | JiJieHao          | L   | 0.930      | -            | -                | -                | -         |   -16.98 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke              |
|           14 |     2815 | 2024-04-18 | JiJieHao          | W   | 0.923      | 0.143        | 0.000 (0.000)    | 0.103 (0.014)    | 0 (0.000) |    11.65 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke              |
|           13 |     2835 | 2024-04-18 | NoChance          | W   | 0.922      | 0.143        | 0.000 (0.000)    | 0.025 (0.003)    | 0 (0.000) |     6.56 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke              |
|           12 |     2901 | 2024-04-17 | XO Esports        | W   | 0.916      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.31 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke              |
|           11 |     3949 | 2024-03-26 | Gaimin Gladiators | L   | 0.771      | -            | -                | -                | -         |    -0.55 | 0SAMAS, 0scar, Ejram, PokemoN, TTyke              |
|           10 |     7067 | 2024-01-28 | JiJieHao          | L   | 0.385      | -            | -                | -                | -         |    -7.52 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            9 |     7100 | 2024-01-28 | 15 Average Gaming | L   | 0.383      | -            | -                | -                | -         |    -8.17 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            8 |     7256 | 2024-01-26 | JiJieHao          | W   | 0.371      | 0.143        | 0.000 (0.000)    | 0.103 (0.005)    | 0 (0.000) |     4.18 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            7 |     7267 | 2024-01-26 | Nixuh             | W   | 0.370      | 0.143        | 0.001 (0.000)    | 0.080 (0.004)    | 0 (0.000) |     5.89 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            6 |     8392 | 2024-01-09 | 4Point5           | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.77 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            5 |     8996 | 2023-12-15 | THE SUSPECT       | L   | 0.091      | -            | -                | -                | -         |    -1.50 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            4 |     9007 | 2023-12-15 | Endpoint          | L   | 0.090      | -            | -                | -                | -         |    -0.40 | 0SAMAS, Ejram, PokemoN, TTyke, tudsoN             |
|            3 |     9217 | 2023-12-10 | R8 Esports        | W   | 0.058      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 1 (0.058) |     0.65 | Alylelely, Ba6ooooy, HopeDaBe4st, Lacore, tr1     |
|            2 |     9224 | 2023-12-10 | ACME              | W   | 0.057      | 0.143        | 0.006 (0.000)    | 0.026 (0.000)    | 1 (0.057) |     1.09 | alwkze, Faller, JaiHind, R2B2, Zayed              |
|            1 |     9247 | 2023-12-10 | lost cause        | W   | 0.056      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.056) |     0.39 | modepsychos, papatiti, PatroN, Pers, SultanDaKing |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($350.11)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-16 |      0.096 | $2,000.00      | $192.78         |
| 2023-12-10 |      0.058 | $2,723.01      | $157.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
