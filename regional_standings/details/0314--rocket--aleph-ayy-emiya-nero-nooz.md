### Roster Details<br />
Team Name: Rocket<br />
Roster: aleph, ayy, EMIYA, nero, nooz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [314](../standings_global.md)<br />
Regional Rank: [73]( ../standings_americas.md)<br />
Final Rank Value:  629.6<br />
<br />
Final Rank Value (629.6) = Starting Rank Value (520.7) + Head To Head Adjustments (108.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 520.7
- 400 + ( ( 0.059 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 520.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     5966 | 2024-02-16 | G3             | W   | 0.512      | 0.143        | 0.006 (0.000)    | 0.202 (0.015)    | 0 (0.000) |    11.63 | aleph, ayy, EMIYA, nero, nooz   |
|           25 |     5967 | 2024-02-16 | MIGHT          | W   | 0.512      | 0.143        | -                | 0.207 (0.015)    | 0 (0.000) |     9.66 | aleph, ayy, EMIYA, nero, nooz   |
|           24 |     6018 | 2024-02-15 | Revel          | W   | 0.506      | -            | -                | -                | 0 (0.000) |     3.81 | aleph, ayy, EMIYA, nero, nooz   |
|           23 |     6647 | 2024-02-01 | BOSS           | L   | 0.413      | -            | -                | -                | -         |    -2.62 | aleph, ayy, EMIYA, nero, nooz   |
|           22 |     6655 | 2024-02-01 | Nouns Esports  | L   | 0.412      | -            | -                | -                | -         |    -1.84 | aleph, ayy, EMIYA, nero, nooz   |
|           21 |     6893 | 2024-01-27 | LAG Gaming     | W   | 0.379      | 0.143        | 0.013 (0.001)    | 0.335 (0.018)    | 0 (0.000) |    10.40 | aleph, ayy, EMIYA, nero, nooz   |
|           20 |     7004 | 2024-01-26 | Limitless      | W   | 0.373      | 0.143        | 0.001 (0.000)    | 0.123 (0.007)    | 0 (0.000) |     7.53 | aleph, ayy, EMIYA, nero, nooz   |
|           19 |     7011 | 2024-01-26 | WICKED         | W   | 0.373      | 0.143        | 0.009 (0.000)    | 0.129 (0.007)    | 0 (0.000) |     7.86 | aleph, ayy, EMIYA, nero, nooz   |
|           18 |     7445 | 2024-01-18 | Nouns Esports  | L   | 0.319      | -            | -                | -                | -         |    -1.24 | aleph, ayy, EMIYA, nero, nooz   |
|           17 |     7449 | 2024-01-18 | Carpe Diem     | W   | 0.319      | 0.143        | -                | 0.243 (0.011)    | 0 (0.000) |     5.81 | aleph, ayy, EMIYA, nero, nooz   |
|           16 |     7500 | 2024-01-17 | FLUFFY AIMERS  | W   | 0.313      | -            | -                | -                | 0 (0.000) |     5.43 | aleph, ayy, EMIYA, nero, nooz   |
|           15 |     7739 | 2024-01-14 | NRG            | W   | 0.293      | 0.143        | 0.010 (0.000)    | 0.555 (0.023)    | 0 (0.000) |     7.59 | aleph, ayy, droid, Elk, nero    |
|           14 |     7742 | 2024-01-14 | BOSS           | L   | 0.293      | -            | -                | -                | -         |    -1.51 | aleph, ayy, droid, Elk, nero    |
|           13 |     7769 | 2024-01-13 | Carpe Diem     | W   | 0.286      | 0.143        | -                | 0.243 (0.010)    | 0 (0.000) |     5.43 | aleph, ayy, droid, Elk, nero    |
|           12 |     7809 | 2024-01-12 | For Fun        | W   | 0.281      | 0.143        | 0.007 (0.000)    | -                | -         |     6.76 | aleph, ayy, droid, Elk, nero    |
|           11 |     7823 | 2024-01-12 | M80            | L   | 0.280      | -            | -                | -                | -         |    -0.15 | aleph, ayy, droid, Elk, nero    |
|           10 |     7878 | 2024-01-12 | For Fun        | W   | 0.275      | 0.143        | 0.007 (0.000)    | -                | -         |     6.76 | aleph, ayy, droid, Elk, nero    |
|            9 |     7888 | 2024-01-11 | LOS            | W   | 0.274      | -            | -                | -                | -         |     4.13 | aleph, ayy, droid, Elk, nero    |
|            8 |     7901 | 2024-01-11 | The Nomads     | W   | 0.273      | -            | -                | -                | -         |     3.65 | aleph, ayy, droid, Elk, nero    |
|            7 |     7906 | 2024-01-11 | Villainous     | W   | 0.273      | 0.143        | -                | 0.093 (0.004)    | -         |     5.74 | aleph, ayy, droid, Elk, nero    |
|            6 |     7967 | 2024-01-10 | Revenge Nation | W   | 0.267      | 0.143        | 0.019 (0.001)    | 0.186 (0.007)    | -         |     6.28 | aleph, ayy, droid, Elk, nero    |
|            5 |     8155 | 2024-01-08 | Detonate       | W   | 0.254      | 0.143        | 0.001 (0.000)    | -                | -         |     5.21 | aleph, ayy, droid, nero, nooz   |
|            4 |     8424 | 2023-12-17 | MIGHT          | L   | 0.107      | -            | -                | -                | -         |    -0.97 | aleph, droid, nero, nooz, R2D2J |
|            3 |     8429 | 2023-12-17 | Bad News Bears | W   | 0.106      | -            | -                | -                | -         |     1.43 | aleph, droid, nero, nooz, R2D2J |
|            2 |     8534 | 2023-12-16 | Revenge Nation | W   | 0.100      | 0.143        | 0.019 (0.000)    | -                | -         |     2.38 | aleph, droid, nero, nooz, R2D2J |
|            1 |     8710 | 2023-12-15 | LAG Gaming     | L   | 0.093      | -            | -                | -                | -         |    -0.24 | aleph, droid, nero, nooz, R2D2J |

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
