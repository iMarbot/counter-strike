### Roster Details<br />
Team Name: Denial<br />
Roster: Andree, Flaua, Inspire, mertz, mupzG<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [373](../standings_global.md)<br />
Regional Rank: [223]( ../standings_europe.md)<br />
Final Rank Value:  594.2<br />
<br />
Final Rank Value (594.2) = Starting Rank Value (577.7) + Head To Head Adjustments (16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.087<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 577.7
- 400 + ( ( 0.087 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 577.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |       93 | 2024-05-29 | Copenhagen Wolves   | L   | 1.000      | -            | -                | -                | -         |    -9.36 | Andree, Flaua, Inspire, mertz, mupzG         |
|           17 |      209 | 2024-05-26 | VP.Prodigy          | L   | 1.000      | -            | -                | -                | -         |    -5.17 | Andree, Flaua, Inspire, mertz, mupzG         |
|           16 |      459 | 2024-05-22 | Young Gods          | L   | 1.000      | -            | -                | -                | -         |   -18.02 | Andree, Flaua, Inspire, mertz, mupzG         |
|           15 |      484 | 2024-05-22 | VaselineWorms       | L   | 1.000      | -            | -                | -                | -         |   -11.50 | Andree, Flaua, Inspire, mertz, mupzG         |
|           14 |      491 | 2024-05-22 | AscendX Esports     | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.45 | Andree, Flaua, Inspire, mertz, mupzG         |
|           13 |      510 | 2024-05-22 | Preasy Esport       | W   | 1.000      | 0.354        | 0.008 (0.003)    | 0.705 (0.250)    | 0 (0.000) |    20.89 | Andree, Flaua, Inspire, mertz, mupzG         |
|           12 |      594 | 2024-05-21 | Passion UA          | L   | 1.000      | -            | -                | -                | -         |    -4.43 | Andree, Flaua, Inspire, mertz, mupzG         |
|           11 |      611 | 2024-05-21 | kONO.ECF            | W   | 1.000      | 0.372        | 0.013 (0.005)    | 0.853 (0.318)    | 0 (0.000) |    26.02 | Andree, Flaua, Inspire, mertz, mupzG         |
|           10 |      615 | 2024-05-21 | DASH                | L   | 1.000      | -            | -                | -                | -         |   -12.13 | Andree, Flaua, Inspire, mertz, mupzG         |
|            9 |      722 | 2024-05-20 | Preasy Esport       | W   | 1.000      | 0.354        | 0.008 (0.003)    | 0.705 (0.250)    | 0 (0.000) |    23.34 | Andree, Flaua, Inspire, mertz, mupzG         |
|            8 |      764 | 2024-05-19 | Nexus Gaming        | L   | 1.000      | -            | -                | -                | -         |    -5.53 | Andree, Flaua, Inspire, mertz, mupzG         |
|            7 |     1336 | 2024-05-13 | HyperSpirit         | L   | 1.000      | -            | -                | -                | -         |    -7.92 | Andree, Flaua, Inspire, mertz, mupzG         |
|            6 |     1994 | 2024-05-01 | ex-KRC Genk Esports | L   | 1.000      | -            | -                | -                | -         |   -10.71 | Andree, Flaua, Inspire, mertz, mupzG         |
|            5 |     2009 | 2024-05-01 | ADEPTS              | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.291 (0.108)    | 0 (0.000) |    22.52 | Andree, Flaua, Inspire, mertz, mupzG         |
|            4 |     2057 | 2024-04-30 | LOG Esports         | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.024 (0.009)    | 0 (0.000) |    12.76 | Andree, Flaua, Inspire, mertz, mupzG         |
|            3 |     2963 | 2024-04-16 | Rhyno Esports       | L   | 0.910      | -            | -                | -                | -         |    -2.92 | DDias, krazy, renatoohaxx, snapy, TMKj       |
|            2 |     3012 | 2024-04-15 | EXO Clan            | L   | 0.904      | -            | -                | -                | -         |    -2.19 | Andree, Flaua, Inspire, mertz, mupzG         |
|            1 |     3259 | 2024-04-10 | VP.Prodigy          | L   | 0.869      | -            | -                | -                | -         |    -4.63 | dwushka, KusMe, shady, Something, xdENiSZERA |

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
