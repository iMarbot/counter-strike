### Roster Details<br />
Team Name: Ex-sYnck<br />
Roster: eku, fejtZ, Jyo, Wahtzz, xezr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [301](../standings_global.md)<br />
Regional Rank: [183]( ../standings_europe.md)<br />
Final Rank Value:  611.6<br />
<br />
Final Rank Value (611.6) = Starting Rank Value (555.4) + Head To Head Adjustments (56.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.078<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 555.4
- 400 + ( ( 0.078 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 555.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     2223 | 2024-03-15 | Endpoint      | L   | 0.857      | -            | -                | -                | -         |    -5.39 | eku, fejtZ, Jyo, Wahtzz, xezr |
|           13 |     2284 | 2024-03-14 | Young Ninjas  | W   | 0.850      | 0.384        | 0.074 (0.024)    | 0.338 (0.110)    | 0 (0.000) |    23.72 | eku, fejtZ, Jyo, Wahtzz, xezr |
|           12 |     2900 | 2024-03-02 | INGLORIOUS    | W   | 0.770      | 0.384        | 0.005 (0.001)    | 0.358 (0.106)    | 0 (0.000) |    19.54 | eku, fejtZ, Jyo, Wahtzz, xezr |
|           11 |     2948 | 2024-02-29 | GODSENT       | L   | 0.758      | -            | -                | -                | -         |    -5.42 | eku, fejtZ, Jyo, Wahtzz, xezr |
|           10 |     2966 | 2024-02-29 | Team Secret   | W   | 0.757      | 0.371        | 0.000 (0.000)    | 0.368 (0.104)    | 0 (0.000) |    16.20 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            9 |     6247 | 2023-11-29 | Nemiga Gaming | L   | 0.146      | -            | -                | -                | -         |    -0.07 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            8 |     6265 | 2023-11-29 | Insilio       | L   | 0.145      | -            | -                | -                | -         |    -0.56 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            7 |     6370 | 2023-11-27 | Kappa Bar     | W   | 0.132      | 0.371        | 0.002 (0.000)    | 0.149 (0.007)    | 0 (0.000) |     2.74 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            6 |     6394 | 2023-11-26 | Lemondogs     | W   | 0.125      | 0.371        | 0.000 (0.000)    | 0.252 (0.012)    | 0 (0.000) |     2.07 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            5 |     6472 | 2023-11-24 | LF0           | W   | 0.112      | 0.371        | 0.006 (0.000)    | 0.026 (0.001)    | 0 (0.000) |     2.19 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            4 |     6770 | 2023-11-17 | ESCAPIST      | W   | 0.065      | 0.371        | 0.000 (0.000)    | 0.013 (0.000)    | 0 (0.000) |     0.99 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            3 |     7096 | 2023-11-10 | The Witchers  | W   | 0.018      | 0.371        | 0.035 (0.000)    | 0.158 (0.001)    | 0 (0.000) |     0.44 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            2 |     7143 | 2023-11-09 | L&G           | L   | 0.011      | -            | -                | -                | -         |    -0.18 | eku, fejtZ, Jyo, Wahtzz, xezr |
|            1 |     7194 | 2023-11-08 | Lajtbitexe    | L   | 0.005      | -            | -                | -                | -         |    -0.08 | eku, fejtZ, Jyo, Wahtzz, xezr |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
