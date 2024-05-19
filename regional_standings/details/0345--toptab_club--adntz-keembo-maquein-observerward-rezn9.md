### Roster Details<br />
Team Name: TopTab Club<br />
Roster: ADntZ, keembo, maQuein, observerward, rezn9<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [345](../standings_global.md)<br />
Regional Rank: [214]( ../standings_europe.md)<br />
Final Rank Value:  511.2<br />
<br />
Final Rank Value (511.2) = Starting Rank Value (520.8) + Head To Head Adjustments (-9.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 520.8
- 400 + ( ( 0.061 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 520.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      409 | 2024-04-26 | Kappa Bar              | L   | 1.000      | -            | -                | -                | -         |   -15.14 | ADntZ, keembo, maQuein, observerward, rezn9 |
|           10 |      599 | 2024-04-22 | Lemondogs              | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.252 (0.094)    | 0 (0.000) |    17.86 | ADntZ, keembo, maQuein, observerward, rezn9 |
|            9 |      703 | 2024-04-20 | Grindas                | L   | 1.000      | -            | -                | -                | -         |    -8.13 | ADntZ, feetje, keembo, maQuein, rezn9       |
|            8 |     1034 | 2024-04-15 | Raptors Esports Club   | L   | 1.000      | -            | -                | -                | -         |    -4.21 | ADntZ, keembo, maQuein, observerward, rezn9 |
|            7 |     1171 | 2024-04-11 | ARCRED                 | L   | 1.000      | -            | -                | -                | -         |    -4.93 | ADntZ, keembo, maQuein, observerward, rezn9 |
|            6 |     2207 | 2024-03-15 | Turów Zgorzelec Esport | L   | 0.859      | -            | -                | -                | -         |    -4.62 | ADntZ, keembo, maQuein, rezn9, SKYLLLER     |
|            5 |     2367 | 2024-03-12 | Raptors Esports Club   | L   | 0.839      | -            | -                | -                | -         |    -4.05 | ADntZ, keembo, maQuein, rezn9, SKYLLLER     |
|            4 |     2687 | 2024-03-05 | DUSTY                  | W   | 0.792      | 0.333        | 0.015 (0.004)    | 0.233 (0.061)    | 0 (0.000) |    18.77 | ADntZ, keembo, maQuein, rezn9, SKYLLLER     |
|            3 |     5397 | 2023-12-17 | Lewandownskie          | L   | 0.263      | -            | -                | -                | -         |    -2.46 | ADntZ, keembo, maQuein, rezn9, SKYLLLER     |
|            2 |     5498 | 2023-12-16 | XGOD                   | L   | 0.256      | -            | -                | -                | -         |    -4.28 | ADntZ, keembo, maQuein, rezn9, SKYLLLER     |
|            1 |     6731 | 2023-11-18 | LEON Esports           | W   | 0.071      | 0.143        | 0.003 (0.000)    | 0.357 (0.004)    | 0 (0.000) |     1.62 | ADntZ, keembo, maQuein, rezn9, SKYLLLER     |

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
