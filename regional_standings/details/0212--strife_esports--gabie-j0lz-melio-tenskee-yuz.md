### Roster Details<br />
Team Name: Strife Esports<br />
Roster: Gabie, J0LZ, Melio, TENSKEE, YuZ<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [212](../standings_global.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
Final Rank Value:  716.6<br />
<br />
Final Rank Value (716.6) = Starting Rank Value (698.5) + Head To Head Adjustments (18.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.337[<sup>1</sup>](#table2)
- Bounty Collected: 0.237[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 698.5
- 400 + ( ( 0.147 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 698.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |        3 | 2024-05-29 | Victorum       | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.54 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           17 |     1794 | 2024-05-04 | Team VALORANT  | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     4.70 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           16 |     1797 | 2024-05-04 | iBuyPoutine    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     5.14 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           15 |     2480 | 2024-04-21 | For Fun        | L   | 0.944      | -            | -                | -                | -         |   -12.57 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           14 |     2885 | 2024-04-16 | Take Flyte     | L   | 0.912      | -            | -                | -                | -         |   -11.65 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           13 |     3961 | 2024-03-23 | Revenge Nation | L   | 0.753      | -            | -                | -                | -         |   -11.63 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           12 |     4050 | 2024-03-21 | Final Form     | W   | 0.740      | 0.371        | 0.008 (0.002)    | 0.074 (0.020)    | 0 (0.000) |    10.32 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           11 |     4149 | 2024-03-19 | Akimbo Esports | W   | 0.726      | 0.371        | 0.008 (0.002)    | 0.155 (0.042)    | 0 (0.000) |    13.00 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|           10 |     4190 | 2024-03-18 | Xiaoma Gaming  | W   | 0.719      | 0.371        | 0.005 (0.001)    | 0.075 (0.020)    | 0 (0.000) |    12.36 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|            9 |     4358 | 2024-03-15 | The Nomads     | W   | 0.700      | 0.371        | 0.002 (0.000)    | 0.056 (0.014)    | 0 (0.000) |     6.74 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|            8 |     4403 | 2024-03-14 | G3             | W   | 0.693      | 0.371        | 0.000 (0.000)    | 0.037 (0.009)    | 0 (0.000) |     5.35 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|            7 |     4686 | 2024-03-09 | Akimbo Esports | L   | 0.660      | -            | -                | -                | -         |    -8.45 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|            6 |     4781 | 2024-03-07 | Pryde          | W   | 0.646      | 0.371        | 0.000 (0.000)    | 0.043 (0.010)    | 0 (0.000) |     4.80 | Gabie, J0LZ, Melio, TENSKEE, YuZ       |
|            5 |     6016 | 2024-02-15 | LAG Gaming     | L   | 0.506      | -            | -                | -                | -         |    -3.36 | FAME, J0LZ, Melio, TENSKEE, YuZ        |
|            4 |     8434 | 2023-12-17 | FPL Friends    | L   | 0.106      | -            | -                | -                | -         |    -1.97 | CLASIA, Pol0, PwnAlone, silas, steel   |
|            3 |     8536 | 2023-12-16 | FLUFFY AIMERS  | W   | 0.100      | 0.294        | 0.001 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     1.22 | FAME, Gabie, J0LZ, Melio, TENSKEE      |
|            2 |     8552 | 2023-12-16 | NuTorious      | W   | 0.099      | -            | -                | -                | -         |     0.50 | looke, Sham, stuffing, Toasty, Tyler69 |
|            1 |     8947 | 2023-12-10 | Final Form     | L   | 0.060      | -            | -                | -                | -         |    -1.00 | cypress, mcniff, raw1, Slash, slump    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,236.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
