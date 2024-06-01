### Roster Details<br />
Team Name: Noobs But Diligent<br />
Roster: chuzhongT, expSasiKi, HiNa, lan, rubeN<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [183](../standings_global.md)<br />
Regional Rank: [20]( ../standings_asia.md)<br />
Final Rank Value:  743.6<br />
<br />
Final Rank Value (743.6) = Starting Rank Value (750.4) + Head To Head Adjustments (-6.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.172<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 750.4
- 400 + ( ( 0.172 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 750.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1788 | 2024-05-05 | E9 esports         | L   | 1.000      | -            | -                | -                | -         |   -12.87 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|           10 |     1836 | 2024-05-04 | Sheer Conquer      | W   | 1.000      | 0.143        | 0.017 (0.002)    | 0.151 (0.022)    | 1 (1.000) |    17.82 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            9 |     1857 | 2024-05-03 | E9 esports         | L   | 1.000      | -            | -                | -                | -         |   -12.60 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            8 |     2644 | 2024-04-20 | Sheer Conquer      | L   | 0.935      | -            | -                | -                | -         |   -12.55 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            7 |     2657 | 2024-04-19 | Exusiai            | W   | 0.934      | 0.143        | 0.003 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.59 | chuzhongT, expSasiKi, HiNa, lan, rubeN         |
|            6 |     4570 | 2024-03-12 | TYLOO              | L   | 0.676      | -            | -                | -                | -         |    -6.10 | aliver, chuzhongT, expSasiKi, rubeN, Tw1nk1e17 |
|            5 |     4629 | 2024-03-11 | MOLEGAN            | W   | 0.669      | 0.250        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     2.54 | aliver, chuzhongT, expSasiKi, Miami, rubeN     |
|            4 |     4762 | 2024-03-08 | Team NKT           | W   | 0.649      | 0.250        | 0.006 (0.001)    | 0.150 (0.024)    | 0 (0.000) |     9.99 | aliver, chuzhongT, expSasiKi, Miami, rubeN     |
|            3 |     4899 | 2024-03-06 | Serenity Esports   | W   | 0.636      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.46 | aliver, chuzhongT, expSasiKi, Miami, rubeN     |
|            2 |     7126 | 2024-01-24 | NewHappy           | L   | 0.356      | -            | -                | -                | -         |    -6.67 | chuzhongT, expSasiKi, HiNa, Nuko, rubeN        |
|            1 |     7137 | 2024-01-24 | Myth Avenue Gaming | W   | 0.356      | 0.143        | 0.005 (0.000)    | 0.192 (0.010)    | 0 (0.000) |     4.64 | chuzhongT, expSasiKi, HiNa, Nuko, rubeN        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,157.65)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $2,763.46      | $2,763.46       |
| 2024-04-20 |      0.935 | $1,105.00      | $1,032.87       |
| 2024-03-19 |      0.723 | $500.00        | $361.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
