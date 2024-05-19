### Roster Details<br />
Team Name: 00 Nation<br />
Roster: birdfromsky, FASHR, JDC, syrsoN, VLDN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [344](../standings_global.md)<br />
Regional Rank: [213]( ../standings_europe.md)<br />
Final Rank Value:  513.8<br />
<br />
Final Rank Value (513.8) = Starting Rank Value (504.2) + Head To Head Adjustments (9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 504.2
- 400 + ( ( 0.053 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 504.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     4737 | 2024-01-17 | VaselineWorms          | L   | 0.472      | -            | -                | -                | -         |    -4.45 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|           11 |     4781 | 2024-01-16 | Endpoint               | L   | 0.466      | -            | -                | -                | -         |    -2.01 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|           10 |     4797 | 2024-01-16 | Turów Zgorzelec Esport | W   | 0.466      | 0.143        | 0.019 (0.001)    | 0.640 (0.043)    | 0 (0.000) |    12.42 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|            9 |     4799 | 2024-01-16 | Blue Lock              | W   | 0.465      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.23 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|            8 |     5002 | 2024-01-11 | IKLA                   | L   | 0.431      | -            | -                | -                | -         |    -3.11 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|            7 |     5042 | 2024-01-10 | Viperio                | W   | 0.426      | 0.143        | 0.000 (0.000)    | 0.321 (0.020)    | 0 (0.000) |     8.58 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|            6 |     5121 | 2024-01-09 | 9INE                   | L   | 0.418      | -            | -                | -                | -         |    -5.35 | birdfromsky, FASHR, JDC, syrsoN, VLDN |
|            5 |     6379 | 2023-11-27 | Ex-Anonymo Esports     | L   | 0.130      | -            | -                | -                | -         |    -0.75 | birdfromsky, JDC, niko, susp, syrsoN  |
|            4 |     6601 | 2023-11-21 | EYEBALLERS             | L   | 0.091      | -            | -                | -                | -         |    -0.23 | birdfromsky, JDC, niko, susp, syrsoN  |
|            3 |     6822 | 2023-11-16 | Into The Breach        | L   | 0.058      | -            | -                | -                | -         |    -0.28 | birdfromsky, JDC, niko, susp, syrsoN  |
|            2 |     6875 | 2023-11-15 | For The Win Esports    | L   | 0.052      | -            | -                | -                | -         |    -0.46 | birdfromsky, JDC, niko, susp, syrsoN  |
|            1 |     6900 | 2023-11-15 | BIG                    | L   | 0.050      | -            | -                | -                | -         |    -0.01 | birdfromsky, JDC, niko, susp, syrsoN  |

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
