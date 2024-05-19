### Roster Details<br />
Team Name: Nordix Esport<br />
Roster: artstyle, markow, Norways, Redly, Smistadjr<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [357](../standings_global.md)<br />
Regional Rank: [223]( ../standings_europe.md)<br />
Final Rank Value:  421.4<br />
<br />
Final Rank Value (421.4) = Starting Rank Value (406.2) + Head To Head Adjustments (15.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.003<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 406.2
- 400 + ( ( 0.003 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 406.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      310 | 2024-04-28 | Vanir                           | L   | 1.000      | -            | -                | -                | -             |   -18.56 | artstyle, markow, Norways, Redly, Smistadjr |
|           14 |      610 | 2024-04-22 | INFURITY Gaming                 | L   | 1.000      | -            | -                | -                | -             |   -14.12 | artstyle, markow, Norways, Redly, Smistadjr |
|           13 |      651 | 2024-04-21 | En av de lette                  | L   | 1.000      | -            | -                | -                | -             |    -5.06 | artstyle, markow, Norways, Redly, Smistadjr |
|           12 |     1048 | 2024-04-15 | Apeks Legends                   | L   | 1.000      | -            | -                | -                | -             |   -18.29 | artstyle, markow, Norways, Redly, Smistadjr |
|           11 |     1227 | 2024-04-10 | Metizport X                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.300 (0.043)    | false (0.000) |    20.25 | artstyle, markow, Norways, Redly, Smistadjr |
|           10 |     2087 | 2024-03-18 | 777 Esports                     | L   | 0.879      | -            | -                | -                | -             |    -4.18 | artstyle, markow, Norways, Redly, Smistadjr |
|            9 |     2140 | 2024-03-17 | En av de lette                  | L   | 0.871      | -            | -                | -                | -             |    -4.57 | artstyle, markow, Norways, Redly, Smistadjr |
|            8 |     2167 | 2024-03-16 | Static                          | W   | 0.865      | 0.143        | 0.000 (0.000)    | 0.226 (0.028)    | false (0.000) |    15.05 | artstyle, markow, Norways, Redly, Smistadjr |
|            7 |     2316 | 2024-03-13 | Center Gaming                   | W   | 0.845      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | false (0.000) |    11.66 | artstyle, markow, Norways, Redly, Smistadjr |
|            6 |     2373 | 2024-03-12 | Foxed Gaming                    | W   | 0.838      | 0.143        | 0.000 (0.000)    | 0.114 (0.014)    | false (0.000) |    11.52 | artstyle, markow, Norways, Redly, Smistadjr |
|            5 |     2416 | 2024-03-11 | Foxed Gaming                    | W   | 0.832      | 0.143        | 0.000 (0.000)    | 0.114 (0.014)    | false (0.000) |    12.31 | artstyle, markow, Norways, Redly, Smistadjr |
|            4 |     2612 | 2024-03-06 | En av de lette                  | L   | 0.799      | -            | -                | -                | -             |    -3.53 | artstyle, markow, Norways, Redly, Smistadjr |
|            3 |     2760 | 2024-03-04 | Bitfix Gaming                   | W   | 0.785      | 0.143        | 0.000 (0.000)    | 0.031 (0.003)    | false (0.000) |    11.39 | artstyle, markow, Norways, Redly, Smistadjr |
|            2 |     3721 | 2024-02-12 | Wizard esports (Norwegian team) | L   | 0.645      | -            | -                | -                | -             |   -10.69 | artstyle, markow, Norways, Redly, Smistadjr |
|            1 |     3896 | 2024-02-05 | Static                          | W   | 0.598      | 0.143        | 0.000 (0.000)    | 0.226 (0.019)    | false (0.000) |    12.03 | artstyle, markow, Norways, Redly, Smistadjr |

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
