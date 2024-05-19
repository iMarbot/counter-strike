### Roster Details<br />
Team Name: Noobs But Diligent<br />
Roster: chuzhongT, expSasiKi, HiNa, lan, rubeN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [148](../standings_global.md)<br />
Regional Rank: [22]( ../standings_asia.md)<br />
Final Rank Value:  775.3<br />
<br />
Final Rank Value (775.3) = Starting Rank Value (777.9) + Head To Head Adjustments (-2.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.390[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.111[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.9
- 400 + ( ( 0.190 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 777.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |       34 | 2024-05-05 | E9 esports         | L   | 1.000      | -            | -                | -                | -             |   -13.16 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|           10 |       73 | 2024-05-04 | Sheer Conquer      | W   | 1.000      | 0.143        | 0.035 (0.005)    | 0.211 (0.030)    | true (1.000)  |    17.94 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            9 |       89 | 2024-05-03 | E9 esports         | L   | 1.000      | -            | -                | -                | -             |   -12.91 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            8 |      772 | 2024-04-20 | Sheer Conquer      | L   | 1.000      | -            | -                | -                | -             |   -13.28 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            7 |      785 | 2024-04-19 | Exusiai            | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.000 (0.000)    | false (0.000) |     6.35 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            6 |     2384 | 2024-03-12 | TYLOO              | L   | 0.837      | -            | -                | -                | -             |    -4.77 | aliver, chuzhongT, expSasiKi, rubeN, Tw1nk1e17 |
|            5 |     2433 | 2024-03-11 | MOLEGAN            | W   | 0.830      | 0.250        | 0.000 (0.000)    | 0.028 (0.006)    | false (0.000) |     2.70 | aliver, chuzhongT, expSasiKi, Miami, rubeN     |
|            4 |     2540 | 2024-03-08 | Team NKT           | W   | 0.810      | 0.250        | 0.016 (0.003)    | 0.259 (0.053)    | false (0.000) |    13.38 | aliver, chuzhongT, expSasiKi, Miami, rubeN     |
|            3 |     2644 | 2024-03-06 | Serenity Esports   | W   | 0.797      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     2.67 | aliver, chuzhongT, expSasiKi, Miami, rubeN     |
|            2 |     4388 | 2024-01-24 | NewHappy           | L   | 0.517      | -            | -                | -                | -             |    -8.34 | chuzhongT, expSasiKi, HiNa, Nuko, rubeN        |
|            1 |     4399 | 2024-01-24 | Myth Avenue Gaming | W   | 0.517      | 0.143        | 0.012 (0.001)    | 0.302 (0.022)    | false (0.000) |     6.83 | chuzhongT, expSasiKi, HiNa, Nuko, rubeN        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,310.31)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $2,763.46      | $2,763.46       |
| 2024-04-20 |      1.000 | $1,105.00      | $1,105.00       |
| 2024-03-19 |      0.884 | $500.00        | $441.85         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
