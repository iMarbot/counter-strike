### Roster Details<br />
Team Name: TSM<br />
Roster: joel, KWERTZZ, MoDo, valde, Zyphon<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [156](../standings_global.md)<br />
Regional Rank: [109]( ../standings_europe.md)<br />
Final Rank Value:  776.1<br />
<br />
Final Rank Value (776.1) = Starting Rank Value (764.4) + Head To Head Adjustments (11.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.308[<sup>2</sup>](#table1)
- Opponent Network: 0.070[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 764.4
- 400 + ( ( 0.179 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 764.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     2740 | 2024-04-19 | Sangal Esports       | L   | 0.931      | -            | -                | -                | -         |    -5.75 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           25 |     3239 | 2024-04-10 | FORZE Esports        | L   | 0.871      | -            | -                | -                | -         |   -14.72 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           24 |     3312 | 2024-04-09 | Betera Esports       | W   | 0.864      | 0.500        | 0.023 (0.010)    | 0.257 (0.111)    | 0 (0.000) |    16.98 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           23 |     3576 | 2024-04-04 | 9Pandas              | L   | 0.831      | -            | -                | -                | -         |    -2.47 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           22 |     3681 | 2024-04-02 | KOI                  | L   | 0.817      | -            | -                | -                | -         |    -5.10 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           21 |     3824 | 2024-03-28 | 9INE                 | W   | 0.784      | 0.500        | 0.002 (0.001)    | 0.092 (0.036)    | 0 (0.000) |     8.04 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           20 |     3894 | 2024-03-27 | Metizport            | L   | 0.777      | -            | -                | -                | -         |    -4.05 | joel, KWERTZZ, poizon, valde, Zyphon |
|           19 |     3958 | 2024-03-26 | kONO.ECF             | W   | 0.771      | 0.143        | 0.013 (0.001)    | 0.853 (0.094)    | 0 (0.000) |    17.15 | joel, KWERTZZ, poizon, valde, Zyphon |
|           18 |     4244 | 2024-03-20 | VP.Prodigy           | L   | 0.729      | -            | -                | -                | -         |    -8.68 | joel, KWERTZZ, poizon, valde, Zyphon |
|           17 |     4986 | 2024-03-06 | Sangal Esports       | L   | 0.638      | -            | -                | -                | -         |    -4.21 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           16 |     5218 | 2024-03-03 | The Chosen Few       | L   | 0.618      | -            | -                | -                | -         |    -9.26 | joel, KWERTZZ, poizon, valde, Zyphon |
|           15 |     5231 | 2024-03-03 | Nexus Gaming         | W   | 0.617      | 0.143        | 0.003 (0.000)    | 0.857 (0.076)    | 0 (0.000) |    13.34 | joel, KWERTZZ, poizon, valde, Zyphon |
|           14 |     5281 | 2024-03-02 | Balkan Bears         | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     3.92 | joel, KWERTZZ, poizon, valde, Zyphon |
|           13 |     5296 | 2024-03-02 | SIUUUU               | W   | 0.611      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     2.15 | joel, KWERTZZ, poizon, valde, Zyphon |
|           12 |     6426 | 2024-02-11 | Lilmix               | L   | 0.477      | -            | -                | -                | -         |    -6.16 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           11 |     6537 | 2024-02-08 | ex-Preasy Esport     | L   | 0.455      | -            | -                | -                | -         |    -4.37 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           10 |     6559 | 2024-02-07 | Gaimin Gladiators    | L   | 0.449      | -            | -                | -                | -         |    -0.92 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            9 |     6638 | 2024-02-05 | Metizport            | W   | 0.436      | 0.371        | 0.088 (0.014)    | 0.698 (0.113)    | 0 (0.000) |    10.58 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            8 |     6774 | 2024-02-03 | ALTERNATE aTTaX      | W   | 0.422      | 0.371        | 0.052 (0.008)    | 0.735 (0.115)    | 0 (0.000) |    10.20 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            7 |     6954 | 2024-01-31 | GODSENT              | W   | 0.402      | 0.371        | 0.001 (0.000)    | 0.084 (0.012)    | 0 (0.000) |     4.89 | interz, joel, KWERTZZ, MoDo, valde   |
|            6 |     7027 | 2024-01-29 | FORZE Esports        | L   | 0.392      | -            | -                | -                | -         |    -7.70 | interz, joel, KWERTZZ, MoDo, valde   |
|            5 |     7216 | 2024-01-27 | MOUZ NXT             | W   | 0.375      | 0.371        | 0.157 (0.022)    | 0.977 (0.136)    | 0 (0.000) |    10.46 | interz, joel, KWERTZZ, MoDo, valde   |
|            4 |     7432 | 2024-01-23 | GODSENT              | L   | 0.348      | -            | -                | -                | -         |    -7.04 | interz, joel, KWERTZZ, MoDo, valde   |
|            3 |     7905 | 2024-01-16 | RUBY                 | L   | 0.304      | -            | -                | -                | -         |    -3.07 | interz, JACKZ, joel, MoDo, valde     |
|            2 |     8243 | 2024-01-10 | HAVU Gaming          | L   | 0.265      | -            | -                | -                | -         |    -4.09 | interz, JACKZ, joel, MoDo, valde     |
|            1 |     8269 | 2024-01-10 | ex-Hot Headed Gaming | W   | 0.265      | 0.143        | -                | 0.086 (0.003)    | -         |     1.59 | interz, JACKZ, joel, MoDo, valde     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,385.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-02-09 |      0.462 | $3,000.00      | $1,385.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
