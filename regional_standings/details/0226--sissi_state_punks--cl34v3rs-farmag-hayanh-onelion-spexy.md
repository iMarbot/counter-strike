### Roster Details<br />
Team Name: Sissi State Punks<br />
Roster: Cl34v3rs, farmaG, hayanh, OneLion, Spexy<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [226](../standings_global.md)<br />
Regional Rank: [148]( ../standings_europe.md)<br />
Final Rank Value:  687.9<br />
<br />
Final Rank Value (687.9) = Starting Rank Value (678.0) + Head To Head Adjustments (9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 678.0
- 400 + ( ( 0.140 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 678.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      281 | 2024-04-29 | TeamOrangeGaming    | L   | 1.000      | -            | -                | -                | -         |   -11.21 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           12 |      370 | 2024-04-27 | TeamOrangeGaming    | L   | 1.000      | -            | -                | -                | -         |   -12.62 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           11 |      606 | 2024-04-22 | Wave Esports        | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.113 (0.016)    | 0 (0.000) |    10.97 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|           10 |     1046 | 2024-04-15 | SNOGARD Dragons     | L   | 1.000      | -            | -                | -                | -         |   -15.31 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            9 |     1320 | 2024-04-08 | EVOPLAY             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.025 (0.004)    | 0 (0.000) |     7.57 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            8 |     1535 | 2024-04-03 | ARROW (German team) | L   | 0.985      | -            | -                | -                | -         |   -15.95 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            7 |     1812 | 2024-03-26 | ALTERNATE aTTaX Evo | W   | 0.932      | 0.143        | 0.005 (0.001)    | 0.198 (0.026)    | 0 (0.000) |    12.33 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            6 |     1823 | 2024-03-26 | Pandaric eSports    | W   | 0.932      | 0.143        | 0.002 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.63 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            5 |     2155 | 2024-03-17 | SNOGARD Dragons     | L   | 0.870      | -            | -                | -                | -         |   -14.07 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            4 |     2218 | 2024-03-15 | Wave Esports        | W   | 0.858      | 0.143        | 0.004 (0.000)    | 0.113 (0.014)    | 0 (0.000) |    10.45 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            3 |     2255 | 2024-03-14 | SNOGARD Dragons     | W   | 0.852      | 0.143        | 0.009 (0.001)    | 0.117 (0.014)    | 0 (0.000) |    13.58 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            2 |     2866 | 2024-03-02 | Wave Esports        | W   | 0.772      | 0.143        | 0.004 (0.000)    | 0.113 (0.012)    | 0 (0.000) |    10.96 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |
|            1 |     3286 | 2024-02-21 | OTHERSCANTBEAT      | W   | 0.706      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     5.55 | Cl34v3rs, farmaG, hayanh, OneLion, Spexy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,417.58)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-27 |      1.000 | $267.57        | $267.57         |
| 2024-03-26 |      0.932 | $216.79        | $202.12         |
| 2024-03-17 |      0.870 | $1,089.86      | $947.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
