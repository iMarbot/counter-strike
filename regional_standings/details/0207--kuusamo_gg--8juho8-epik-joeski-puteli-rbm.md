### Roster Details<br />
Team Name: KUUSAMO.gg<br />
Roster: 8Juho8, epik, joeski, Puteli, rbm<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [207](../standings_global.md)<br />
Regional Rank: [138]( ../standings_europe.md)<br />
Final Rank Value:  719.9<br />
<br />
Final Rank Value (719.9) = Starting Rank Value (775.4) + Head To Head Adjustments (-55.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.247[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.4
- 400 + ( ( 0.184 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 775.4


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
|           13 |       49 | 2024-05-29 | Team Flow          | L   | 1.000      | -            | -                | -                | -         |   -23.24 | 8Juho8, epik, joeski, Puteli, rbm |
|           12 |     2322 | 2024-04-25 | XI Esport          | L   | 0.969      | -            | -                | -                | -         |   -19.46 | 8Juho8, epik, joeski, Puteli, rbm |
|           11 |     2490 | 2024-04-21 | DUSTY              | W   | 0.944      | 0.289        | 0.006 (0.002)    | 0.148 (0.040)    | 0 (0.000) |    11.63 | 8Juho8, epik, joeski, Puteli, rbm |
|           10 |     2849 | 2024-04-17 | XI Esport          | L   | 0.916      | -            | -                | -                | -         |   -18.72 | 8Juho8, epik, joeski, Puteli, rbm |
|            9 |     3997 | 2024-03-23 | Johnny Speeds      | L   | 0.751      | -            | -                | -                | -         |    -5.33 | 8Juho8, epik, joeski, Puteli, rbm |
|            8 |     3998 | 2024-03-23 | KILLBOX            | W   | 0.750      | 0.143        | 0.000 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     3.97 | 8Juho8, epik, joeski, Puteli, rbm |
|            7 |     4004 | 2024-03-23 | RektGeT            | W   | 0.750      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.64 | 8Juho8, epik, joeski, Puteli, rbm |
|            6 |     5172 | 2024-03-02 | ENCE Prospects     | W   | 0.611      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.611) |     7.05 | 8Juho8, epik, Ounli, Puteli, rbm  |
|            5 |     5209 | 2024-03-02 | SatulanHaistelijat | W   | 0.609      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.609) |     2.25 | 8Juho8, epik, Ounli, Puteli, rbm  |
|            4 |     5598 | 2024-02-23 | RoundsGG           | L   | 0.558      | -            | -                | -                | -         |   -12.32 | 8Juho8, epik, joeski, Puteli, rbm |
|            3 |     5603 | 2024-02-23 | ENCE Prospects     | W   | 0.557      | 0.143        | 0.001 (0.000)    | 0.034 (0.003)    | 1 (0.557) |     6.36 | 8Juho8, epik, joeski, Puteli, rbm |
|            2 |     5612 | 2024-02-23 | zmail ja mimmit    | W   | 0.557      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.557) |     2.02 | 8Juho8, epik, joeski, Puteli, rbm |
|            1 |     5641 | 2024-02-22 | RoundsGG           | L   | 0.551      | -            | -                | -                | -         |   -12.37 | 8Juho8, epik, joeski, Puteli, rbm |

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
