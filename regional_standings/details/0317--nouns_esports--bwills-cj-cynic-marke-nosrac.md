### Roster Details<br />
Team Name: Nouns Esports<br />
Roster: Bwills, cJ, cynic, MarKE, nosraC<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [317](../standings_global.md)<br />
Regional Rank: [72]( ../standings_americas.md)<br />
Final Rank Value:  633.4<br />
<br />
Final Rank Value (633.4) = Starting Rank Value (629.9) + Head To Head Adjustments (3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.272[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 629.9
- 400 + ( ( 0.113 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 629.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     8685 | 2023-12-17 | FPL Friends        | L   | 0.106      | -            | -                | -                | -         |    -1.68 | Bwills, cJ, cynic, MarKE, nosraC |
|           11 |     8690 | 2023-12-17 | Carpe Diem         | W   | 0.106      | 0.294        | 0.000 (0.000)    | 0.243 (0.008)    | 0 (0.000) |     1.68 | Bwills, cJ, cynic, MarKE, nosraC |
|           10 |     8795 | 2023-12-16 | Team DNA           | W   | 0.100      | 0.294        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.67 | Bwills, cJ, cynic, MarKE, nosraC |
|            9 |     8800 | 2023-12-16 | old mythic         | W   | 0.099      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.67 | Bwills, cJ, cynic, MarKE, nosraC |
|            8 |     9071 | 2023-12-13 | M80                | L   | 0.079      | -            | -                | -                | -         |    -0.07 | Bwills, cJ, cynic, MarKE, nosraC |
|            7 |     9125 | 2023-12-12 | NRG                | W   | 0.072      | 0.303        | 0.010 (0.000)    | 0.555 (0.012)    | 0 (0.000) |     1.72 | Bwills, cJ, cynic, MarKE, nosraC |
|            6 |     9164 | 2023-12-11 | Akimbo Esports     | W   | 0.066      | 0.303        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.64 | Bwills, cJ, cynic, MarKE, nosraC |
|            5 |     9356 | 2023-12-08 | Party Astronauts   | L   | 0.046      | -            | -                | -                | -         |    -0.73 | Bwills, cJ, cynic, MarKE, nosraC |
|            4 |     9405 | 2023-12-07 | Unjustified Gaming | W   | 0.039      | 0.500        | 0.001 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.59 | Bwills, cJ, cynic, MarKE, nosraC |
|            3 |     9476 | 2023-12-06 | BOSS               | L   | 0.033      | -            | -                | -                | -         |    -0.23 | Bwills, cJ, cynic, MarKE, nosraC |
|            2 |     9540 | 2023-12-05 | Evil Geniuses      | W   | 0.026      | 0.500        | 0.001 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.39 | Bwills, cJ, cynic, MarKE, nosraC |
|            1 |     9703 | 2023-12-02 | ex-CatEvil         | L   | 0.006      | -            | -                | -                | -         |    -0.10 | Bwills, cJ, cynic, MarKE, nosraC |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($631.53)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-17 |      0.106 | $1,000.00      | $106.25         |
| 2023-12-13 |      0.079 | $1,000.00      | $79.44          |
| 2023-12-10 |      0.059 | $7,500.00      | $445.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
