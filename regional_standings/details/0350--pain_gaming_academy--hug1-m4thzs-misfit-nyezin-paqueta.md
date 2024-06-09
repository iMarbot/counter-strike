### Roster Details<br />
Team Name: paiN Gaming Academy<br />
Roster: hug1, m4thzs, misfit, nyezin, paqueta<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [350](../standings_global.md)<br />
Regional Rank: [85]( ../standings_americas.md)<br />
Final Rank Value:  607.7<br />
<br />
Final Rank Value (607.7) = Starting Rank Value (606.1) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.219[<sup>1</sup>](#table2)
- Bounty Collected: 0.182[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 606.1
- 400 + ( ( 0.101 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 606.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     6265 | 2024-02-14 | MIBR Academy              | L   | 0.498      | -            | -                | -                | -         |    -5.58 | hug1, m4thzs, misfit, nyezin, paqueta |
|           14 |     6479 | 2024-02-09 | Projeto KinGui            | W   | 0.464      | 0.143        | 0.000 (0.000)    | 0.021 (0.001)    | 0 (0.000) |     5.11 | hug1, misfit, nolkz, nyezin, paqueta  |
|           13 |     6593 | 2024-02-05 | Bounty Hunters Esports    | W   | 0.438      | 0.143        | 0.000 (0.000)    | 0.102 (0.006)    | 0 (0.000) |     5.43 | hug1, m4thzs, misfit, nyezin, paqueta |
|           12 |     6694 | 2024-02-03 | Bombril 1001 Utilidades   | L   | 0.425      | -            | -                | -                | -         |    -6.18 | hug1, m4thzs, misfit, nyezin, paqueta |
|           11 |     6907 | 2024-01-31 | Intense Game              | W   | 0.405      | 0.143        | 0.003 (0.000)    | 0.334 (0.019)    | 0 (0.000) |     8.07 | hug1, m4thzs, misfit, nyezin, paqueta |
|           10 |     6919 | 2024-01-31 | Bombril 1001 Utilidades   | L   | 0.404      | -            | -                | -                | -         |    -5.85 | hug1, m4thzs, misfit, nyezin, paqueta |
|            9 |     7047 | 2024-01-29 | Projeto KinGui            | L   | 0.391      | -            | -                | -                | -         |    -8.13 | hug1, m4thzs, misfit, nyezin, paqueta |
|            8 |     7235 | 2024-01-26 | 9z Academy                | W   | 0.372      | 0.143        | 0.002 (0.000)    | 0.311 (0.017)    | 0 (0.000) |     6.87 | hug1, m4thzs, misfit, nyezin, paqueta |
|            7 |     7335 | 2024-01-24 | Intense Game              | L   | 0.358      | -            | -                | -                | -         |    -5.88 | hug1, m4thzs, misfit, nyezin, paqueta |
|            6 |     7407 | 2024-01-23 | Arena Jogue Fácil Esports | W   | 0.351      | 0.143        | 0.000 (0.000)    | 0.038 (0.002)    | 0 (0.000) |     5.53 | hug1, m4thzs, misfit, nyezin, paqueta |
|            5 |     8615 | 2023-12-21 | TEAM ORUGA                | W   | 0.133      | 0.143        | 0.000 (0.000)    | 0.094 (0.002)    | 0 (0.000) |     2.07 | hug1, m4thzs, misfit, nyezin, paqueta |
|            4 |     8982 | 2023-12-15 | TIMACETA                  | L   | 0.092      | -            | -                | -                | -         |    -1.37 | hug1, m4thzs, misfit, nyezin, paqueta |
|            3 |     9049 | 2023-12-14 | Sharks Youngsters         | W   | 0.084      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     1.30 | hug1, m4thzs, misfit, nyezin, paqueta |
|            2 |     9089 | 2023-12-13 | Myth e-Sports             | W   | 0.078      | 0.143        | 0.000 (0.000)    | 0.041 (0.000)    | 0 (0.000) |     1.26 | hug1, m4thzs, misfit, nyezin, paqueta |
|            1 |     9138 | 2023-12-12 | Intense Game              | L   | 0.071      | -            | -                | -                | -         |    -1.11 | hug1, m4thzs, misfit, nyezin, paqueta |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($82.58)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
