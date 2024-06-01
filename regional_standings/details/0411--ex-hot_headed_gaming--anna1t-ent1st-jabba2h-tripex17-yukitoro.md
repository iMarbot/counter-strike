### Roster Details<br />
Team Name: ex-Hot Headed Gaming<br />
Roster: anna1t, Ent1st, jabba2h, tripex17, yukitoro<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [411](../standings_global.md)<br />
Regional Rank: [247]( ../standings_europe.md)<br />
Final Rank Value:  539.5<br />
<br />
Final Rank Value (539.5) = Starting Rank Value (506.1) + Head To Head Adjustments (33.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.199[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.052<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 506.1
- 400 + ( ( 0.052 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 506.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     5301 | 2024-02-28 | 0to100              | W   | 0.591      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.72 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           13 |     5360 | 2024-02-27 | LODIS               | W   | 0.584      | 0.371        | 0.001 (0.000)    | 0.140 (0.030)    | 0 (0.000) |    11.40 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           12 |     5601 | 2024-02-23 | Golden Sword        | W   | 0.558      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.69 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           11 |     5818 | 2024-02-19 | Kappa Bar           | W   | 0.531      | 0.371        | 0.000 (0.000)    | 0.062 (0.012)    | 0 (0.000) |     8.83 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|           10 |     6040 | 2024-02-15 | los kogutos         | W   | 0.504      | 0.371        | 0.000 (0.000)    | 0.026 (0.005)    | 0 (0.000) |     8.81 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            9 |     6149 | 2024-02-13 | FORZE Youngsters    | L   | 0.491      | -            | -                | -                | -         |    -4.51 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            8 |     6373 | 2024-02-06 | Zero Tenacity       | L   | 0.444      | -            | -                | -                | -         |    -0.60 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            7 |     6403 | 2024-02-05 | ex-FLuffy Gangsters | L   | 0.438      | -            | -                | -                | -         |    -6.80 | anna1t, Ent1st, jabba2h, Saturday, tripex17 |
|            6 |     6675 | 2024-02-01 | INGLORIOUS          | L   | 0.410      | -            | -                | -                | -         |    -2.71 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            5 |     7120 | 2024-01-24 | Nemiga Gaming       | L   | 0.357      | -            | -                | -                | -         |    -0.19 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            4 |     7215 | 2024-01-22 | ex-K10              | W   | 0.344      | 0.371        | 0.005 (0.001)    | 0.382 (0.049)    | 0 (0.000) |     9.49 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            3 |     8015 | 2024-01-10 | TSM                 | L   | 0.265      | -            | -                | -                | -         |    -1.72 | anna1t, Ent1st, jabba2h, tripex17, yukitoro |
|            2 |     9441 | 2023-12-02 | Gorillas            | L   | 0.005      | -            | -                | -                | -         |    -0.06 | anna1t, Ent1st, kRyTouS, PLANET, yukitoro   |
|            1 |     9457 | 2023-12-02 | adidas shoes        | W   | 0.004      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.05 | millert, p3kko, puuha, r1ksa, teme          |

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
