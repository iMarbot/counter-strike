### Roster Details<br />
Team Name: inSanitY Sports<br />
Roster: iDk, Maluk3, nks, pesadelo, Tomate<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [444](../standings_global.md)<br />
Regional Rank: [111]( ../standings_americas.md)<br />
Final Rank Value:  495.5<br />
<br />
Final Rank Value (495.5) = Starting Rank Value (493.4) + Head To Head Adjustments (2.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.180[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 493.4
- 400 + ( ( 0.046 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 493.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     4256 | 2024-03-19 | Dusty Roots            | L   | 0.725      | -            | -                | -                | -         |    -6.81 | iDk, Maluk3, nks, pesadelo, Tomate      |
|           16 |     4520 | 2024-03-14 | KRÜ Esports            | L   | 0.692      | -            | -                | -                | -         |    -3.71 | iDk, Maluk3, nks, pesadelo, Tomate      |
|           15 |     4601 | 2024-03-13 | LA RUGONETA            | W   | 0.684      | 0.262        | 0.000 (0.000)    | 0.057 (0.010)    | 0 (0.000) |    13.63 | iDk, Maluk3, nks, pesadelo, Tomate      |
|           14 |     4656 | 2024-03-12 | Case Esports           | L   | 0.679      | -            | -                | -                | -         |    -2.38 | bt0, iDk, Maluk3, nks, pesadelo         |
|           13 |     6202 | 2024-02-15 | MIBR Academy           | L   | 0.505      | -            | -                | -                | -         |    -3.50 | iDk, Maluk3, nks, pesadelo, Tomate      |
|           12 |     6349 | 2024-02-13 | adalYamigos            | L   | 0.490      | -            | -                | -                | -         |    -4.46 | iDk, Maluk3, nks, pesadelo, Tomate      |
|           11 |     6373 | 2024-02-12 | Galorys                | L   | 0.485      | -            | -                | -                | -         |    -2.12 | iDk, Maluk3, nks, pesadelo, Tomate      |
|           10 |     7048 | 2024-01-29 | MIBR Academy           | W   | 0.391      | 0.143        | 0.005 (0.000)    | 0.448 (0.025)    | 0 (0.000) |     9.35 | antonini, iDk, Maluk3, pesadelo, Tomate |
|            9 |     7129 | 2024-01-27 | adalYamigos            | L   | 0.379      | -            | -                | -                | -         |    -3.40 | antonini, iDk, Maluk3, pesadelo, Tomate |
|            8 |     7446 | 2024-01-22 | paiN Gaming            | L   | 0.346      | -            | -                | -                | -         |    -0.02 | antonini, iDk, Maluk3, pesadelo, Tomate |
|            7 |     7953 | 2024-01-15 | w7m esports            | L   | 0.299      | -            | -                | -                | -         |    -1.71 | antonini, iDk, Maluk3, pesadelo, prt    |
|            6 |     8025 | 2024-01-13 | Legacy                 | L   | 0.286      | -            | -                | -                | -         |    -0.50 | antonini, iDk, Maluk3, pesadelo, prt    |
|            5 |     8169 | 2024-01-11 | Galorys                | L   | 0.272      | -            | -                | -                | -         |    -1.09 | antonini, iDk, Maluk3, pesadelo, prt    |
|            4 |     8180 | 2024-01-11 | caradecachorro         | W   | 0.271      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     4.52 | antonini, iDk, Maluk3, pesadelo, prt    |
|            3 |     8238 | 2024-01-10 | Intense Game           | W   | 0.266      | 0.143        | 0.001 (0.000)    | 0.028 (0.001)    | 0 (0.000) |     5.47 | antonini, iDk, Maluk3, pesadelo, prt    |
|            2 |     9178 | 2023-12-11 | ex-Corinthians Esports | L   | 0.065      | -            | -                | -                | -         |    -1.06 | DANVIET, Demonos, fREQ, proSHOW, r4ul   |
|            1 |     9359 | 2023-12-08 | Team Solid             | L   | 0.045      | -            | -                | -                | -         |    -0.15 | CSO, gbb, Lcm, nolkz, xureba            |

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
