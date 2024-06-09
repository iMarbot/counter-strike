### Roster Details<br />
Team Name: KUUSAMO.gg<br />
Roster: 8Juho8, epik, joeski, Puteli, rbm<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [203](../standings_global.md)<br />
Regional Rank: [137]( ../standings_europe.md)<br />
Final Rank Value:  720.0<br />
<br />
Final Rank Value (720.0) = Starting Rank Value (774.8) + Head To Head Adjustments (-54.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.247[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.8
- 400 + ( ( 0.184 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 774.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |       51 | 2024-05-29 | Team Flow          | L   | 1.000      | -            | -                | -                | -         |   -23.23 | 8Juho8, epik, joeski, Puteli, rbm |
|           12 |     2362 | 2024-04-25 | XI Esport          | L   | 0.969      | -            | -                | -                | -         |   -19.33 | 8Juho8, epik, joeski, Puteli, rbm |
|           11 |     2543 | 2024-04-21 | DUSTY              | W   | 0.944      | 0.289        | 0.006 (0.002)    | 0.148 (0.040)    | 0 (0.000) |    11.20 | 8Juho8, epik, joeski, Puteli, rbm |
|           10 |     2905 | 2024-04-17 | XI Esport          | L   | 0.916      | -            | -                | -                | -         |   -18.64 | 8Juho8, epik, joeski, Puteli, rbm |
|            9 |     4094 | 2024-03-23 | Johnny Speeds      | L   | 0.751      | -            | -                | -                | -         |    -5.30 | 8Juho8, epik, joeski, Puteli, rbm |
|            8 |     4095 | 2024-03-23 | KILLBOX            | W   | 0.750      | 0.143        | 0.000 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     3.97 | 8Juho8, epik, joeski, Puteli, rbm |
|            7 |     4101 | 2024-03-23 | RektGeT            | W   | 0.750      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.63 | 8Juho8, epik, joeski, Puteli, rbm |
|            6 |     5320 | 2024-03-02 | ENCE Prospects     | W   | 0.611      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.611) |     7.04 | 8Juho8, epik, Ounli, Puteli, rbm  |
|            5 |     5358 | 2024-03-02 | SatulanHaistelijat | W   | 0.609      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.609) |     2.24 | 8Juho8, epik, Ounli, Puteli, rbm  |
|            4 |     5758 | 2024-02-23 | RoundsGG           | L   | 0.558      | -            | -                | -                | -         |   -11.84 | 8Juho8, epik, joeski, Puteli, rbm |
|            3 |     5763 | 2024-02-23 | ENCE Prospects     | W   | 0.557      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.557) |     6.37 | 8Juho8, epik, joeski, Puteli, rbm |
|            2 |     5772 | 2024-02-23 | zmail ja mimmit    | W   | 0.557      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.557) |     2.02 | 8Juho8, epik, joeski, Puteli, rbm |
|            1 |     5801 | 2024-02-22 | RoundsGG           | L   | 0.551      | -            | -                | -                | -         |   -11.90 | 8Juho8, epik, joeski, Puteli, rbm |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($662.79)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
