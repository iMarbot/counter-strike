### Roster Details<br />
Team Name: FORZE Esports<br />
Roster: kelieN, r3salt, SELLTER, spirit, tN1R<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [159](../standings_global.md)<br />
Regional Rank: [111]( ../standings_europe.md)<br />
Final Rank Value:  772.2<br />
<br />
Final Rank Value (772.2) = Starting Rank Value (736.1) + Head To Head Adjustments (36.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.291[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.1
- 400 + ( ( 0.165 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 736.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3239 | 2024-04-10 | TSM              | W   | 0.871      | 0.500        | 0.011 (0.005)    | 0.170 (0.074)    | 0 (0.000) |    14.72 | kelieN, r3salt, SELLTER, spirit, tN1R    |
|           12 |     3313 | 2024-04-09 | brazylijski luz  | W   | 0.864      | 0.500        | 0.013 (0.006)    | 0.514 (0.222)    | 0 (0.000) |    15.48 | kelieN, r3salt, SELLTER, spirit, tN1R    |
|           11 |     3993 | 2024-03-26 | Apeks            | W   | 0.769      | 0.500        | 0.002 (0.001)    | 0.052 (0.020)    | 0 (0.000) |     9.14 | kelieN, r3salt, SELLTER, spirit, tN1R    |
|           10 |     4019 | 2024-03-25 | B8               | L   | 0.764      | -            | -                | -                | -         |    -2.37 | kelieN, r3salt, SELLTER, spirit, tN1R    |
|            9 |     4192 | 2024-03-21 | PARIVISION       | L   | 0.737      | -            | -                | -                | -         |    -5.78 | kelieN, r3salt, SELLTER, spirit, tN1R    |
|            8 |     7600 | 2024-01-20 | ex-Preasy Esport | L   | 0.329      | -            | -                | -                | -         |    -2.78 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            7 |     7645 | 2024-01-19 | Aurora Gaming    | W   | 0.324      | 0.143        | 0.492 (0.023)    | 0.573 (0.027)    | 0 (0.000) |    10.05 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            6 |     7710 | 2024-01-18 | ex-sYnck         | L   | 0.318      | -            | -                | -                | -         |    -4.79 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            5 |     7727 | 2024-01-18 | HEROIC           | L   | 0.317      | -            | -                | -                | -         |    -0.03 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            4 |     9159 | 2023-12-12 | ENCE             | L   | 0.068      | -            | -                | -                | -         |    -0.04 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            3 |     9202 | 2023-12-11 | SAW              | W   | 0.063      | 0.384        | 0.112 (0.003)    | 0.388 (0.009)    | 0 (0.000) |     1.91 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            2 |     9456 | 2023-12-07 | EYEBALLERS       | W   | 0.036      | 0.384        | 0.012 (0.000)    | 0.508 (0.007)    | 0 (0.000) |     0.83 | gokushima, kelieN, r3salt, shalfey, tN1R |
|            1 |     9584 | 2023-12-05 | ex-Preasy Esport | L   | 0.023      | -            | -                | -                | -         |    -0.20 | gokushima, kelieN, r3salt, shalfey, tN1R |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,077.52)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $3,000.00      | $3,000.00       |
| 2023-12-13 |      0.078 | $1,000.00      | $77.52          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
