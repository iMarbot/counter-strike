### Roster Details<br />
Team Name: Denial<br />
Roster: Andree, Flaua, Inspire, mertz, mupzG<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [365](../standings_global.md)<br />
Regional Rank: [217]( ../standings_europe.md)<br />
Final Rank Value:  593.9<br />
<br />
Final Rank Value (593.9) = Starting Rank Value (574.3) + Head To Head Adjustments (19.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.086[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.086<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 574.3
- 400 + ( ( 0.086 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 574.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       86 | 2024-05-29 | Copenhagen Wolves   | L   | 1.000      | -            | -                | -                | -         |   -10.51 | Andree, Flaua, Inspire, mertz, mupzG |
|           14 |      201 | 2024-05-26 | VP.Prodigy          | L   | 1.000      | -            | -                | -                | -         |    -5.69 | Andree, Flaua, Inspire, mertz, mupzG |
|           13 |      453 | 2024-05-22 | Young Gods          | L   | 1.000      | -            | -                | -                | -         |   -18.17 | Andree, Flaua, Inspire, mertz, mupzG |
|           12 |      478 | 2024-05-22 | VaselineWorms       | L   | 1.000      | -            | -                | -                | -         |   -11.50 | Andree, Flaua, Inspire, mertz, mupzG |
|           11 |      485 | 2024-05-22 | AscendX Esports     | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.40 | Andree, Flaua, Inspire, mertz, mupzG |
|           10 |      503 | 2024-05-22 | Preasy Esport       | W   | 1.000      | 0.354        | 0.008 (0.003)    | 0.642 (0.227)    | 0 (0.000) |    20.73 | Andree, Flaua, Inspire, mertz, mupzG |
|            9 |      583 | 2024-05-21 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |    -4.67 | Andree, Flaua, Inspire, mertz, mupzG |
|            8 |      600 | 2024-05-21 | kONO.ECF            | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.778 (0.290)    | 0 (0.000) |    25.80 | Andree, Flaua, Inspire, mertz, mupzG |
|            7 |      604 | 2024-05-21 | DASH                | L   | 1.000      | -            | -                | -                | -         |   -13.24 | Andree, Flaua, Inspire, mertz, mupzG |
|            6 |      710 | 2024-05-20 | Preasy Esport       | W   | 1.000      | 0.354        | 0.008 (0.003)    | 0.642 (0.227)    | 0 (0.000) |    23.12 | Andree, Flaua, Inspire, mertz, mupzG |
|            5 |      752 | 2024-05-19 | Nexus Gaming        | L   | 1.000      | -            | -                | -                | -         |    -5.47 | Andree, Flaua, Inspire, mertz, mupzG |
|            4 |     1324 | 2024-05-13 | HyperSpirit         | L   | 1.000      | -            | -                | -                | -         |    -8.05 | Andree, Flaua, Inspire, mertz, mupzG |
|            3 |     1967 | 2024-05-01 | ex-KRC Genk Esports | L   | 1.000      | -            | -                | -                | -         |   -14.29 | Andree, Flaua, Inspire, mertz, mupzG |
|            2 |     1980 | 2024-05-01 | ADEPTS              | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.291 (0.108)    | 0 (0.000) |    23.17 | Andree, Flaua, Inspire, mertz, mupzG |
|            1 |     2025 | 2024-04-30 | LOG Esports         | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.024 (0.009)    | 0 (0.000) |    12.97 | Andree, Flaua, Inspire, mertz, mupzG |

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
