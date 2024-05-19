### Roster Details<br />
Team Name: VELOX Argentina<br />
Roster: JonY BoY, MRN1, nbl, roy, tutehen<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [297](../standings_global.md)<br />
Regional Rank: [66]( ../standings_americas.md)<br />
Final Rank Value:  616.1<br />
<br />
Final Rank Value (616.1) = Starting Rank Value (634.1) + Head To Head Adjustments (-18.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.272[<sup>1</sup>](#table2)
- Bounty Collected: 0.180[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 634.1
- 400 + ( ( 0.118 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 634.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     2492 | 2024-03-09 | Team Solid         | L   | 0.818      | -            | -                | -                | -             |    -6.14 | JonY BoY, MRN1, nbl, roy, tutehen |
|           10 |     2552 | 2024-03-07 | RED Canids         | L   | 0.807      | -            | -                | -                | -             |    -3.49 | JonY BoY, MRN1, nbl, roy, tutehen |
|            9 |     3391 | 2024-02-19 | Team Solid         | L   | 0.694      | -            | -                | -                | -             |    -5.62 | JonY BoY, MRN1, nbl, roy, tutehen |
|            8 |     5145 | 2024-01-08 | TIMACETA           | L   | 0.414      | -            | -                | -                | -             |    -6.01 | JonY BoY, MRN1, nbl, roy, tutehen |
|            7 |     5343 | 2023-12-17 | Case Esports       | L   | 0.266      | -            | -                | -                | -             |    -3.17 | JonY BoY, MRN1, nbl, roy, tutehen |
|            6 |     5571 | 2023-12-15 | 9z Academy         | W   | 0.253      | 0.303        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.65 | JonY BoY, MRN1, nbl, roy, tutehen |
|            5 |     6088 | 2023-12-02 | River Plate Gaming | W   | 0.166      | 0.284        | 0.001 (0.000)    | 0.015 (0.001)    | true (0.166)  |     2.46 | JonY BoY, MRN1, nbl, roy, tutehen |
|            4 |     6196 | 2023-11-30 | Dusty Roots        | W   | 0.152      | 0.284        | 0.005 (0.000)    | 0.352 (0.015)    | false (0.000) |     2.76 | JonY BoY, MRN1, nbl, roy, tutehen |
|            3 |     6232 | 2023-11-29 | Maycam Evolve      | W   | 0.147      | 0.284        | 0.000 (0.000)    | 0.005 (0.000)    | false (0.000) |     0.99 | JonY BoY, MRN1, nbl, roy, tutehen |
|            2 |     6287 | 2023-11-28 | River Plate Gaming | L   | 0.141      | -            | -                | -                | -             |    -2.34 | JonY BoY, MRN1, nbl, roy, tutehen |
|            1 |     6345 | 2023-11-27 | Daotsu Esports     | W   | 0.134      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     0.90 | JonY BoY, MRN1, nbl, roy, tutehen |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($331.30)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
