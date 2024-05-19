### Roster Details<br />
Team Name: Metizport X<br />
Roster: fLickza, lindeen, p1ke, Wolf, ZapR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [309](../standings_global.md)<br />
Regional Rank: [188]( ../standings_europe.md)<br />
Final Rank Value:  603.3<br />
<br />
Final Rank Value (603.3) = Starting Rank Value (532.2) + Head To Head Adjustments (71.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.067<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 532.2
- 400 + ( ( 0.067 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 532.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      308 | 2024-04-28 | INFURITY Gaming                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.274 (0.039)    | 0 (0.000) |    10.96 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           12 |      608 | 2024-04-22 | Apeks Legends                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.058 (0.008)    | 0 (0.000) |     7.41 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           11 |     1044 | 2024-04-15 | 777 Esports                     | W   | 1.000      | 0.143        | 0.032 (0.005)    | 0.550 (0.079)    | 0 (0.000) |    23.27 | fLickza, lindeen, p1ke, Wolf, ZapR |
|           10 |     1227 | 2024-04-10 | Nordix Esport                   | L   | 1.000      | -            | -                | -                | -         |   -20.25 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            9 |     1622 | 2024-03-31 | 9INE Academy                    | L   | 0.964      | -            | -                | -                | -         |   -12.62 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            8 |     1664 | 2024-03-29 | Natus Vincere Youth             | L   | 0.951      | -            | -                | -                | -         |   -10.23 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            7 |     1914 | 2024-03-23 | Apeks Rebels                    | W   | 0.911      | 0.289        | 0.005 (0.001)    | 0.071 (0.019)    | 0 (0.000) |    18.14 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            6 |     2052 | 2024-03-19 | ALTERNATE aTTaX Evo             | W   | 0.885      | 0.289        | 0.005 (0.001)    | 0.198 (0.051)    | 0 (0.000) |    17.94 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            5 |     2090 | 2024-03-18 | Foxed Gaming                    | W   | 0.878      | 0.143        | 0.000 (0.000)    | 0.114 (0.014)    | 0 (0.000) |     7.08 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            4 |     2411 | 2024-03-11 | Bitfix Gaming                   | W   | 0.832      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | 0 (0.000) |     6.90 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            3 |     2761 | 2024-03-04 | Wizard esports (Norwegian team) | W   | 0.785      | 0.143        | 0.000 (0.000)    | 0.122 (0.014)    | 0 (0.000) |     7.46 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            2 |     3722 | 2024-02-12 | Static                          | W   | 0.645      | 0.143        | 0.000 (0.000)    | 0.226 (0.021)    | 0 (0.000) |     8.99 | fLickza, lindeen, p1ke, Wolf, ZapR |
|            1 |     3895 | 2024-02-05 | Vanir                           | W   | 0.598      | 0.143        | 0.000 (0.000)    | 0.070 (0.006)    | 0 (0.000) |     6.03 | fLickza, lindeen, p1ke, Wolf, ZapR |

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
