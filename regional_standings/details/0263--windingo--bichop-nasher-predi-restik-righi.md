### Roster Details<br />
Team Name: WINDINGO<br />
Roster: bichop, nasher, PREDI, restik, Righi<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [263](../standings_global.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
Final Rank Value:  653.2<br />
<br />
Final Rank Value (653.2) = Starting Rank Value (660.9) + Head To Head Adjustments (-7.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.290[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.9
- 400 + ( ( 0.131 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 660.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     5326 | 2023-12-18 | Patins da Ferrari         | L   | 0.272      | -            | -                | -                | -             |    -4.79 | bichop, nasher, PREDI, restik, Righi |
|           12 |     5437 | 2023-12-16 | Team Solid                | W   | 0.259      | 0.143        | 0.138 (0.005)    | 0.275 (0.010)    | false (0.000) |     6.44 | bichop, nasher, PREDI, restik, Righi |
|           11 |     5569 | 2023-12-15 | Arena Jogue Fácil Esports | W   | 0.253      | 0.143        | 0.002 (0.000)    | 0.125 (0.004)    | false (0.000) |     4.36 | bichop, nasher, PREDI, restik, Righi |
|           10 |     5633 | 2023-12-13 | Team Solid                | L   | 0.239      | -            | -                | -                | -             |    -1.53 | bichop, nasher, PREDI, restik, Righi |
|            9 |     5918 | 2023-12-06 | W7m esports               | L   | 0.193      | -            | -                | -                | -             |    -3.52 | bichop, nasher, PREDI, restik, Righi |
|            8 |     5978 | 2023-12-05 | Arena Jogue Fácil Esports | L   | 0.186      | -            | -                | -                | -             |    -2.84 | bichop, nasher, PREDI, restik, Righi |
|            7 |     6191 | 2023-11-30 | Patins da Ferrari         | L   | 0.153      | -            | -                | -                | -             |    -2.71 | bichop, nasher, PREDI, restik, Righi |
|            6 |     6238 | 2023-11-29 | 9z Academy                | L   | 0.146      | -            | -                | -                | -             |    -2.29 | bichop, nasher, PREDI, restik, Righi |
|            5 |     6297 | 2023-11-28 | Dusty Roots               | L   | 0.139      | -            | -                | -                | -             |    -2.04 | bichop, nasher, PREDI, restik, Righi |
|            4 |     6348 | 2023-11-27 | Astral Aces Esports       | W   | 0.133      | 0.284        | 0.000 (0.000)    | 0.009 (0.000)    | false (0.000) |     0.79 | bichop, nasher, PREDI, restik, Righi |
|            3 |     6500 | 2023-11-23 | Dusty Roots               | W   | 0.106      | 0.143        | 0.005 (0.000)    | 0.352 (0.005)    | false (0.000) |     1.81 | bichop, nasher, PREDI, restik, Righi |
|            2 |     6580 | 2023-11-21 | Team Solid                | L   | 0.093      | -            | -                | -                | -             |    -0.63 | bichop, nasher, PREDI, restik, Righi |
|            1 |     6856 | 2023-11-15 | Case Esports              | L   | 0.053      | -            | -                | -                | -             |    -0.72 | bichop, nasher, PREDI, restik, Righi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($565.42)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
