### Roster Details<br />
Team Name: Dynamo Eclot Thunders<br />
Roster: DOCKSTAR, fazery, olik, ono, Rutk0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [448](../standings_global.md)<br />
Regional Rank: [271]( ../standings_europe.md)<br />
Final Rank Value:  362.0<br />
<br />
Final Rank Value (362.0) = Starting Rank Value (402.1) + Head To Head Adjustments (-40.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 402.1
- 400 + ( ( 0.001 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 402.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1460 | 2024-05-11 | BRUTE                | L   | 1.000      | -            | -                | -                | -         |   -10.09 | DOCKSTAR, fazery, olik, ono, Rutk0     |
|           10 |     1568 | 2024-05-09 | VENI VIDI VICI       | L   | 1.000      | -            | -                | -                | -         |    -6.66 | DOCKSTAR, fazery, olik, ono, Rutk0     |
|            9 |     2269 | 2024-04-26 | EP Genesis           | L   | 0.976      | -            | -                | -                | -         |    -8.40 | DOCKSTAR, fazery, olik, pal0o, Rutk0   |
|            8 |     2419 | 2024-04-23 | Natus Vincere Junior | L   | 0.956      | -            | -                | -                | -         |    -3.28 | DOCKSTAR, fazery, olik, pal0o, Rutk0   |
|            7 |     2708 | 2024-04-19 | BRUTE                | W   | 0.929      | 0.289        | 0.000 (0.000)    | 0.157 (0.042)    | 0 (0.000) |    20.49 | DOCKSTAR, fazery, olik, pal0o, Rutk0   |
|            6 |     3939 | 2024-03-24 | SINNERS Academy      | L   | 0.757      | -            | -                | -                | -         |    -4.64 | DOCKSTAR, fazery, olik, pal0o, Rutk0   |
|            5 |     4131 | 2024-03-20 | Illuminar Junior     | L   | 0.731      | -            | -                | -                | -         |   -10.78 | DOCKSTAR, fazery, olik, pal0o, Rutk0   |
|            4 |     5447 | 2024-02-25 | SINNERS Academy      | L   | 0.571      | -            | -                | -                | -         |    -3.50 | B34V1S, DOCKSTAR, fazery, olik, pal0o  |
|            3 |     5716 | 2024-02-21 | Begrip Gaming        | L   | 0.543      | -            | -                | -                | -         |    -3.87 | B34V1S, DOCKSTAR, fazery, olik, pal0o  |
|            2 |     7221 | 2024-01-22 | BLUEJAYS Lite        | L   | 0.344      | -            | -                | -                | -         |    -4.37 | B34V1S, d0mZ1k, DOCKSTAR, fazery, olik |
|            1 |     7464 | 2024-01-18 | Sampi NEXT           | L   | 0.318      | -            | -                | -                | -         |    -5.00 | B34V1S, d0mZ1k, DOCKSTAR, fazery, olik |

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
