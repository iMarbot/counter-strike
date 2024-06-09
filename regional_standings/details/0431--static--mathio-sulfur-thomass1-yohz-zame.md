### Roster Details<br />
Team Name: Static<br />
Roster: mathio, Sulfur, thomass1, YoHz, zame<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [431](../standings_global.md)<br />
Regional Rank: [260]( ../standings_europe.md)<br />
Final Rank Value:  522.4<br />
<br />
Final Rank Value (522.4) = Starting Rank Value (508.6) + Head To Head Adjustments (13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 508.6
- 400 + ( ( 0.053 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 508.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     1521 | 2024-05-10 | Nordix Esport     | L   | 1.000      | -            | -                | -                | -         |   -12.96 | mathio, Sulfur, thomass1, YoHz, zame       |
|           18 |     2140 | 2024-04-28 | Foxed Gaming      | W   | 0.990      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |    12.48 | mathio, Sulfur, thomass1, YoHz, zame       |
|           17 |     2277 | 2024-04-26 | Esport Harte      | L   | 0.978      | -            | -                | -                | -         |   -13.99 | berzerk, mathio, thomass1, YoHz, zame      |
|           16 |     2282 | 2024-04-26 | JANO Esports      | L   | 0.977      | -            | -                | -                | -         |    -7.43 | berzerk, mathio, thomass1, YoHz, zame      |
|           15 |     2287 | 2024-04-26 | Preasy Esport     | L   | 0.977      | -            | -                | -                | -         |    -7.70 | berzerk, mathio, thomass1, YoHz, zame      |
|           14 |     2293 | 2024-04-26 | Sashi Esport      | L   | 0.977      | -            | -                | -                | -         |    -0.72 | berzerk, mathio, thomass1, YoHz, zame      |
|           13 |     2507 | 2024-04-22 | Bitfix Gaming     | W   | 0.950      | 0.143        | 0.000 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     8.18 | mathio, Sulfur, thomass1, YoHz, zame       |
|           12 |     2732 | 2024-04-19 | Heimo Esports     | W   | 0.931      | 0.143        | 0.011 (0.001)    | 0.217 (0.029)    | 0 (0.000) |    22.55 | berzerk, mathio, thomass1, YoHz, zame      |
|           11 |     2736 | 2024-04-19 | Foxed Gaming      | W   | 0.931      | 0.143        | 0.000 (0.000)    | 0.077 (0.010)    | 0 (0.000) |    12.16 | berzerk, mathio, thomass1, YoHz, zame      |
|           10 |     2744 | 2024-04-19 | Khai Thonq        | W   | 0.930      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.31 | berzerk, mathio, thomass1, YoHz, zame      |
|            9 |     3372 | 2024-04-08 | 777 Esports       | L   | 0.857      | -            | -                | -                | -         |    -4.45 | mathio, Sulfur, thomass1, YoHz, zame       |
|            8 |     4417 | 2024-03-16 | Nordix Esport     | L   | 0.704      | -            | -                | -                | -         |    -6.79 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            7 |     4604 | 2024-03-13 | 777 Esports       | L   | 0.684      | -            | -                | -                | -         |    -4.16 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            6 |     4736 | 2024-03-11 | INFURITY Gaming   | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.180 (0.017)    | 0 (0.000) |    10.76 | mathio, rinji2k, Sulfur, thomass1, zame    |
|            5 |     4828 | 2024-03-09 | INFURITY Gaming   | L   | 0.657      | -            | -                | -                | -         |   -10.35 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            4 |     4998 | 2024-03-06 | Cashout Cavaliers | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.99 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            3 |     5181 | 2024-03-04 | Apeks Legends     | W   | 0.624      | 0.143        | 0.000 (0.000)    | 0.037 (0.003)    | 0 (0.000) |     7.16 | mathio, Sulfur, thomass1, YoHz, zame       |
|            2 |     6391 | 2024-02-12 | Metizport X       | L   | 0.484      | -            | -                | -                | -         |    -3.86 | mathio, Sulfur, thomass1, YoHz, zame       |
|            1 |     6622 | 2024-02-05 | Nordix Esport     | L   | 0.437      | -            | -                | -                | -         |    -4.39 | mathio, Sulfur, thomass1, YoHz, zame       |

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
