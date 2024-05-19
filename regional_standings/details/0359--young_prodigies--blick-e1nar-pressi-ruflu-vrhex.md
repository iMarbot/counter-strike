### Roster Details<br />
Team Name: Young Prodigies<br />
Roster: Blick, E1nar, Pressi, RuflU, Vrhex<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [359](../standings_global.md)<br />
Regional Rank: [225]( ../standings_europe.md)<br />
Final Rank Value:  409.1<br />
<br />
Final Rank Value (409.1) = Starting Rank Value (400.3) + Head To Head Adjustments (8.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.3
- 400 + ( ( 0.000 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 400.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3489 | 2024-02-17 | FH                      | W   | 0.679      | 0.143        | 0.000 (0.000)    | 0.040 (0.004)    | 0 (0.000) |    10.29 | Blick, E1nar, Pressi, RuflU, Vrhex |
|           12 |     3572 | 2024-02-15 | Ármann                  | L   | 0.666      | -            | -                | -                | -         |    -7.04 | Blick, E1nar, Pressi, RuflU, Vrhex |
|           11 |     3854 | 2024-02-06 | DUSTY                   | L   | 0.606      | -            | -                | -                | -         |    -2.47 | Blick, E1nar, Pressi, RuflU, Vrhex |
|           10 |     4133 | 2024-01-30 | ÍA Akranes              | W   | 0.559      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     8.37 | Blick, E1nar, Pressi, RuflU, Vrhex |
|            9 |     4535 | 2024-01-20 | SAGA Esports            | L   | 0.492      | -            | -                | -                | -         |    -3.66 | Blick, E1nar, Pressi, RuflU, Vrhex |
|            8 |     4784 | 2024-01-16 | ÍBV Esports             | W   | 0.466      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.18 | Blick, E1nar, Pressi, RuflU, Vrhex |
|            7 |     5075 | 2024-01-09 | Breiðablik              | L   | 0.419      | -            | -                | -                | -         |    -4.67 | Blick, E1nar, Pressi, RuflU, Vrhex |
|            6 |     5866 | 2023-12-07 | Þór                     | L   | 0.199      | -            | -                | -                | -         |    -2.22 | Blick, E1nar, Pressi, RuflU, Vrhex |
|            5 |     6298 | 2023-11-28 | AURORA (Icelandic team) | W   | 0.139      | 0.143        | 0.000 (0.000)    | 0.037 (0.001)    | 0 (0.000) |     2.18 | Blick, E1nar, Pressi, RuflU, Vrhex |
|            4 |     6662 | 2023-11-19 | SAGA Esports            | L   | 0.079      | -            | -                | -                | -         |    -0.59 | Blick, dezt, Pressi, Vrhex, yz0    |
|            3 |     6802 | 2023-11-16 | FH                      | W   | 0.059      | 0.143        | 0.000 (0.000)    | 0.040 (0.000)    | 0 (0.000) |     0.93 | Blick, dezt, Pressi, Vrhex, yz0    |
|            2 |     6912 | 2023-11-14 | DUSTY                   | L   | 0.046      | -            | -                | -                | -         |    -0.15 | Blick, dezt, Pressi, Vrhex, yz0    |
|            1 |     6917 | 2023-11-14 | FH                      | W   | 0.046      | 0.143        | 0.000 (0.000)    | 0.040 (0.000)    | 0 (0.000) |     0.72 | Blick, dezt, Pressi, Vrhex, yz0    |

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
