### Roster Details<br />
Team Name: Metizport X<br />
Roster: fLickza, lindeen, p1ke, Wolf, ZapR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [224](../standings_global.md)<br />
Regional Rank: [151]( ../standings_europe.md)<br />
Final Rank Value:  706.3<br />
<br />
Final Rank Value (706.3) = Starting Rank Value (692.0) + Head To Head Adjustments (14.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.322[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 692.0
- 400 + ( ( 0.144 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 692.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      221 | 2024-05-26 | 777 Esports          | L   | 1.000      | -            | -                | -                | -         |   -12.44 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           15 |     1401 | 2024-05-12 | Wizard esports       | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.110 (0.016)    | 0 (0.000) |    12.10 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           14 |     1446 | 2024-05-11 | 777 Esports          | L   | 1.000      | -            | -                | -                | -         |   -13.05 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           13 |     2139 | 2024-04-28 | INFURITY Gaming      | W   | 0.990      | 0.143        | 0.000 (0.000)    | 0.180 (0.025)    | 0 (0.000) |     9.35 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           12 |     2506 | 2024-04-22 | Apeks Legends        | W   | 0.950      | 0.143        | 0.000 (0.000)    | 0.037 (0.005)    | 0 (0.000) |     4.45 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           11 |     3014 | 2024-04-15 | 777 Esports          | W   | 0.904      | 0.143        | 0.029 (0.004)    | 0.463 (0.060)    | 0 (0.000) |    17.18 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           10 |     3254 | 2024-04-10 | Nordix Esport        | L   | 0.870      | -            | -                | -                | -         |   -15.51 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            9 |     3745 | 2024-03-31 | 9INE                 | L   | 0.803      | -            | -                | -                | -         |   -15.20 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            8 |     3799 | 2024-03-29 | Natus Vincere Junior | L   | 0.790      | -            | -                | -                | -         |   -12.17 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            7 |     4104 | 2024-03-23 | Apeks Rebels         | W   | 0.750      | 0.289        | 0.000 (0.000)    | 0.043 (0.009)    | 0 (0.000) |     6.05 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            6 |     4267 | 2024-03-19 | ALTERNATE aTTaX Evo  | W   | 0.724      | 0.289        | 0.002 (0.000)    | 0.239 (0.050)    | 0 (0.000) |    10.70 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            5 |     4312 | 2024-03-18 | Foxed Gaming         | W   | 0.717      | 0.143        | 0.000 (0.000)    | 0.077 (0.008)    | 0 (0.000) |     4.66 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            4 |     4727 | 2024-03-11 | Bitfix Gaming        | W   | 0.671      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     3.02 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            3 |     5187 | 2024-03-04 | Wizard esports       | W   | 0.624      | 0.143        | 0.004 (0.000)    | 0.110 (0.010)    | 0 (0.000) |     7.96 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            2 |     6391 | 2024-02-12 | Static               | W   | 0.484      | 0.143        | 0.000 (0.000)    | 0.158 (0.011)    | 0 (0.000) |     3.86 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            1 |     6621 | 2024-02-05 | Vanir                | W   | 0.437      | 0.143        | -                | 0.052 (0.003)    | -         |     3.37 | fLickza, lindeen, p1ke, Wolf, ZapR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,362.31)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />