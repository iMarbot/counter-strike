### Roster Details<br />
Team Name: AKA HERO<br />
Roster: aaroNNN, hANNEs, HyDrO, Kirby, mexoozje<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [357](../standings_global.md)<br />
Regional Rank: [213]( ../standings_europe.md)<br />
Final Rank Value:  599.0<br />
<br />
Final Rank Value (599.0) = Starting Rank Value (615.9) + Head To Head Adjustments (-16.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.233[<sup>1</sup>](#table2)
- Bounty Collected: 0.188[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.106<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 615.9
- 400 + ( ( 0.106 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 615.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      677 | 2024-05-20 | Reveal                | L   | 1.000      | -            | -                | -                | -         |   -17.05 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|           14 |      967 | 2024-05-17 | ALTERNATE aTTaX Evo   | L   | 1.000      | -            | -                | -                | -         |   -13.41 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|           13 |     1349 | 2024-05-12 | Team Solid            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.091 (0.013)    | 0 (0.000) |    14.57 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|           12 |     1502 | 2024-05-10 | XPERION NXT           | L   | 1.000      | -            | -                | -                | -         |   -14.06 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|           11 |     2839 | 2024-04-17 | OTHERSCANTBEAT        | W   | 0.917      | 0.143        | 0.000 (0.000)    | 0.106 (0.014)    | 0 (0.000) |     9.71 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|           10 |     3178 | 2024-04-10 | Entropy Future        | W   | 0.870      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |    12.64 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|            9 |     3545 | 2024-04-03 | eSports Cologne       | L   | 0.824      | -            | -                | -                | -         |   -17.12 | aaroNNN, hANNEs, HyDrO, Kirby, mexoozje     |
|            8 |     4377 | 2024-03-15 | Pandaric eSports      | W   | 0.697      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.19 | kevka, masta, mexoozje, Nobody, SteryFrozen |
|            7 |     8731 | 2023-12-15 | PARTIZAN Junior       | L   | 0.091      | -            | -                | -                | -         |    -1.54 | aaroNNN, hANNEs, HeMan, HyDrO, Kirby        |
|            6 |     8784 | 2023-12-14 | hypewrld              | W   | 0.085      | 0.310        | 0.002 (0.000)    | 0.162 (0.004)    | 0 (0.000) |     1.68 | Brens, flairr, rabbit, sqreet, yamero       |
|            5 |     8877 | 2023-12-12 | FORZE Youngsters      | L   | 0.071      | -            | -                | -                | -         |    -1.04 | aaroNNN, hANNEs, HeMan, HyDrO, Kirby        |
|            4 |     8926 | 2023-12-11 | Dynamo Eclot Thunders | W   | 0.064      | 0.310        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.89 | aaroNNN, hANNEs, HeMan, HyDrO, Kirby        |
|            3 |     9105 | 2023-12-08 | SNOGARD Dragons       | L   | 0.044      | -            | -                | -                | -         |    -0.45 | kryptoN, LapeX, MoJo, ND, sehza             |
|            2 |     9363 | 2023-12-03 | eSports Cologne       | W   | 0.010      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.07 | aaroNNN, hANNEs, Heman, HyDrO, Kirby        |
|            1 |     9476 | 2023-12-02 | Playing Ducks         | W   | 0.004      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.03 | aaroNNN, hANNEs, Heman, HyDrO, Kirby        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($154.54)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $81.42         | $81.42          |
| 2023-12-17 |      0.104 | $700.00        | $73.11          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
