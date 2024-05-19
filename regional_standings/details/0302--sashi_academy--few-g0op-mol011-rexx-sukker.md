### Roster Details<br />
Team Name: Sashi Academy<br />
Roster: Few, G0op, Mol011, ReXx, Sukker<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [302](../standings_global.md)<br />
Regional Rank: [184]( ../standings_europe.md)<br />
Final Rank Value:  610.9<br />
<br />
Final Rank Value (610.9) = Starting Rank Value (660.4) + Head To Head Adjustments (-49.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.4
- 400 + ( ( 0.131 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 660.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      263 | 2024-04-29 | Sashi Esport             | L   | 1.000      | -            | -                | -                | -         |    -0.81 | Few, G0op, Mol011, ReXx, Sukker |
|           19 |      266 | 2024-04-29 | Copenhagen Wolves        | L   | 1.000      | -            | -                | -                | -         |   -14.39 | Few, G0op, Mol011, ReXx, Sukker |
|           18 |      595 | 2024-04-22 | IMMAPROBLEM              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.136 (0.019)    | 0 (0.000) |    11.73 | Few, G0op, Mol011, ReXx, Sukker |
|           17 |      695 | 2024-04-20 | Preasy Esport            | L   | 1.000      | -            | -                | -                | -         |   -11.96 | Few, G0op, Mol011, ReXx, Sukker |
|           16 |     1004 | 2024-04-16 | WOPA Esport              | L   | 1.000      | -            | -                | -                | -         |   -10.80 | Few, G0op, Mol011, ReXx, Sukker |
|           15 |     1041 | 2024-04-15 | Astralis Talent          | L   | 1.000      | -            | -                | -                | -         |    -8.03 | Few, G0op, Mol011, ReXx, Sukker |
|           14 |     1694 | 2024-03-28 | Natus Vincere Youth      | L   | 0.945      | -            | -                | -                | -         |   -12.66 | Few, G0op, Mol011, ReXx, Sukker |
|           13 |     1824 | 2024-03-26 | 777 Esports              | L   | 0.931      | -            | -                | -                | -         |    -9.81 | Few, G0op, Mol011, ReXx, Sukker |
|           12 |     1941 | 2024-03-22 | BRUTE                    | W   | 0.905      | 0.289        | 0.000 (0.000)    | 0.122 (0.032)    | 0 (0.000) |     9.38 | Few, G0op, Mol011, ReXx, Sukker |
|           11 |     2754 | 2024-03-04 | BRUTE                    | L   | 0.785      | -            | -                | -                | -         |   -16.50 | Few, G0op, Mol011, ReXx, Sukker |
|           10 |     2870 | 2024-03-02 | BLESSED (Ukrainian team) | L   | 0.772      | -            | -                | -                | -         |    -6.00 | Few, G0op, Mol011, ReXx, Sukker |
|            9 |     4041 | 2024-02-02 | EXO Clan                 | L   | 0.578      | -            | -                | -                | -         |    -4.26 | Few, G0op, Mol011, ReXx, Sukker |
|            8 |     4117 | 2024-01-31 | Preasy Esport            | W   | 0.564      | 0.289        | 0.007 (0.001)    | 0.525 (0.086)    | 0 (0.000) |    11.45 | Few, G0op, Mol011, ReXx, Sukker |
|            7 |     4196 | 2024-01-29 | AVEZ                     | W   | 0.552      | 0.289        | 0.007 (0.001)    | 0.160 (0.025)    | 0 (0.000) |     9.15 | Few, G0op, Mol011, ReXx, Sukker |
|            6 |     4275 | 2024-01-27 | Sampi NEXT               | W   | 0.538      | 0.289        | 0.000 (0.000)    | 0.039 (0.006)    | 0 (0.000) |     5.04 | Few, G0op, Mol011, ReXx, Sukker |
|            5 |     4380 | 2024-01-24 | BRUTE                    | W   | 0.519      | 0.289        | 0.000 (0.000)    | 0.122 (0.018)    | 0 (0.000) |     5.18 | Few, G0op, Mol011, ReXx, Sukker |
|            4 |     4499 | 2024-01-21 | EPIC DUDES               | W   | 0.499      | 0.289        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.00 | Few, G0op, Mol011, ReXx, Sukker |
|            3 |     4747 | 2024-01-17 | Preasy Esport            | L   | 0.471      | -            | -                | -                | -         |    -4.51 | Few, G0op, Mol011, ReXx, Sukker |
|            2 |     6312 | 2023-11-28 | BRUTE                    | L   | 0.138      | -            | -                | -                | -         |    -3.16 | ClinuO, Few, G0op, ReXx, zEden  |
|            1 |     6598 | 2023-11-21 | ROSOMAHA                 | L   | 0.091      | -            | -                | -                | -         |    -1.58 | ClinuO, Few, G0op, ReXx, zEden  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($577.73)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
