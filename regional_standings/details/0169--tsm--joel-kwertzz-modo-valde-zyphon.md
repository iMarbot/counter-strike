### Roster Details<br />
Team Name: TSM<br />
Roster: joel, KWERTZZ, MoDo, valde, Zyphon<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [169](../standings_global.md)<br />
Regional Rank: [116]( ../standings_europe.md)<br />
Final Rank Value:  760.3<br />
<br />
Final Rank Value (760.3) = Starting Rank Value (746.6) + Head To Head Adjustments (13.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.339[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.170<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 746.6
- 400 + ( ( 0.170 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 746.6


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
|           24 |     3166 | 2024-04-10 | FORZE Esports        | L   | 0.871      | -            | -                | -                | -         |    -3.84 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           23 |     3491 | 2024-04-04 | 9Pandas              | L   | 0.831      | -            | -                | -                | -         |    -2.46 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           22 |     3592 | 2024-04-02 | KOI                  | L   | 0.817      | -            | -                | -                | -         |    -4.83 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           21 |     3730 | 2024-03-28 | 9INE                 | W   | 0.784      | 0.500        | 0.002 (0.001)    | 0.092 (0.036)    | 0 (0.000) |     8.53 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           20 |     3801 | 2024-03-27 | Metizport            | L   | 0.777      | -            | -                | -                | -         |    -3.53 | joel, KWERTZZ, poizon, valde, Zyphon |
|           19 |     3861 | 2024-03-26 | kONO.ECF             | W   | 0.771      | 0.143        | 0.013 (0.001)    | 0.778 (0.086)    | 0 (0.000) |    16.92 | joel, KWERTZZ, poizon, valde, Zyphon |
|           18 |     4142 | 2024-03-20 | VP.Prodigy           | L   | 0.729      | -            | -                | -                | -         |    -8.62 | joel, KWERTZZ, poizon, valde, Zyphon |
|           17 |     4855 | 2024-03-06 | Sangal Esports       | L   | 0.638      | -            | -                | -                | -         |    -4.25 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           16 |     5072 | 2024-03-03 | The Chosen Few       | L   | 0.618      | -            | -                | -                | -         |    -8.51 | joel, KWERTZZ, poizon, valde, Zyphon |
|           15 |     5085 | 2024-03-03 | Nexus Gaming         | W   | 0.617      | 0.143        | 0.014 (0.001)    | 0.825 (0.073)    | 0 (0.000) |    14.05 | joel, KWERTZZ, poizon, valde, Zyphon |
|           14 |     5133 | 2024-03-02 | Balkan Bears         | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     4.26 | joel, KWERTZZ, poizon, valde, Zyphon |
|           13 |     5148 | 2024-03-02 | SIUUUU               | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.36 | joel, KWERTZZ, poizon, valde, Zyphon |
|           12 |     6238 | 2024-02-11 | Lilmix               | L   | 0.477      | -            | -                | -                | -         |    -5.51 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           11 |     6349 | 2024-02-08 | ex-Preasy Esport     | L   | 0.455      | -            | -                | -                | -         |    -4.11 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|           10 |     6365 | 2024-02-07 | Gaimin Gladiators    | L   | 0.449      | -            | -                | -                | -         |    -0.84 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            9 |     6437 | 2024-02-05 | Metizport            | W   | 0.436      | 0.371        | 0.088 (0.014)    | 0.698 (0.113)    | 0 (0.000) |    10.81 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            8 |     6571 | 2024-02-03 | ALTERNATE aTTaX      | W   | 0.422      | 0.371        | 0.004 (0.001)    | 0.103 (0.016)    | 0 (0.000) |     6.34 | joel, KWERTZZ, MoDo, valde, Zyphon   |
|            7 |     6741 | 2024-01-31 | GODSENT              | W   | 0.402      | 0.371        | 0.001 (0.000)    | 0.073 (0.011)    | 0 (0.000) |     5.03 | interz, joel, KWERTZZ, MoDo, valde   |
|            6 |     6811 | 2024-01-29 | FORZE Esports        | L   | 0.392      | -            | -                | -                | -         |    -6.85 | interz, joel, KWERTZZ, MoDo, valde   |
|            5 |     6996 | 2024-01-27 | MOUZ NXT             | W   | 0.375      | 0.371        | 0.157 (0.022)    | 0.950 (0.132)    | 0 (0.000) |    10.52 | interz, joel, KWERTZZ, MoDo, valde   |
|            4 |     7192 | 2024-01-23 | GODSENT              | L   | 0.348      | -            | -                | -                | -         |    -6.83 | interz, joel, KWERTZZ, MoDo, valde   |
|            3 |     7656 | 2024-01-16 | RUBY                 | L   | 0.304      | -            | -                | -                | -         |    -2.75 | interz, JACKZ, joel, MoDo, valde     |
|            2 |     7989 | 2024-01-10 | HAVU Gaming          | L   | 0.265      | -            | -                | -                | -         |    -3.88 | interz, JACKZ, joel, MoDo, valde     |
|            1 |     8015 | 2024-01-10 | ex-Hot Headed Gaming | W   | 0.265      | 0.143        | 0.000 (0.000)    | 0.086 (0.003)    | 0 (0.000) |     1.72 | interz, JACKZ, joel, MoDo, valde     |

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
