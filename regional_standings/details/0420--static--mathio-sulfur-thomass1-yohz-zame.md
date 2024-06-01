### Roster Details<br />
Team Name: Static<br />
Roster: mathio, Sulfur, thomass1, YoHz, zame<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [420](../standings_global.md)<br />
Regional Rank: [254]( ../standings_europe.md)<br />
Final Rank Value:  521.9<br />
<br />
Final Rank Value (521.9) = Starting Rank Value (508.8) + Head To Head Adjustments (13.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 508.8
- 400 + ( ( 0.053 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 508.8


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
|           19 |     1508 | 2024-05-10 | Nordix Esport     | L   | 1.000      | -            | -                | -                | -         |   -12.91 | mathio, Sulfur, thomass1, YoHz, zame       |
|           18 |     2105 | 2024-04-28 | Foxed Gaming      | W   | 0.990      | 0.143        | 0.000 (0.000)    | 0.077 (0.011)    | 0 (0.000) |    12.50 | mathio, Sulfur, thomass1, YoHz, zame       |
|           17 |     2241 | 2024-04-26 | Esport Harte      | L   | 0.978      | -            | -                | -                | -         |   -13.99 | berzerk, mathio, thomass1, YoHz, zame      |
|           16 |     2246 | 2024-04-26 | JANO Esports      | L   | 0.977      | -            | -                | -                | -         |    -7.92 | berzerk, mathio, thomass1, YoHz, zame      |
|           15 |     2251 | 2024-04-26 | Preasy Esport     | L   | 0.977      | -            | -                | -                | -         |    -7.84 | berzerk, mathio, thomass1, YoHz, zame      |
|           14 |     2257 | 2024-04-26 | Sashi Esport      | L   | 0.977      | -            | -                | -                | -         |    -0.71 | berzerk, mathio, thomass1, YoHz, zame      |
|           13 |     2456 | 2024-04-22 | Bitfix Gaming     | W   | 0.950      | 0.143        | 0.000 (0.000)    | 0.020 (0.003)    | 0 (0.000) |     8.18 | mathio, Sulfur, thomass1, YoHz, zame       |
|           12 |     2678 | 2024-04-19 | Heimo Esports     | W   | 0.931      | 0.143        | 0.011 (0.001)    | 0.217 (0.029)    | 0 (0.000) |    22.52 | berzerk, mathio, thomass1, YoHz, zame      |
|           11 |     2682 | 2024-04-19 | Foxed Gaming      | W   | 0.931      | 0.143        | 0.000 (0.000)    | 0.077 (0.010)    | 0 (0.000) |    12.16 | berzerk, mathio, thomass1, YoHz, zame      |
|           10 |     2688 | 2024-04-19 | Khai Thonq        | W   | 0.930      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.30 | berzerk, mathio, thomass1, YoHz, zame      |
|            9 |     3291 | 2024-04-08 | 777 Esports       | L   | 0.857      | -            | -                | -                | -         |    -4.49 | mathio, Sulfur, thomass1, YoHz, zame       |
|            8 |     4311 | 2024-03-16 | Nordix Esport     | L   | 0.704      | -            | -                | -                | -         |    -6.78 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            7 |     4489 | 2024-03-13 | 777 Esports       | L   | 0.684      | -            | -                | -                | -         |    -4.18 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            6 |     4614 | 2024-03-11 | INFURITY Gaming   | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.180 (0.017)    | 0 (0.000) |    10.76 | mathio, rinji2k, Sulfur, thomass1, zame    |
|            5 |     4703 | 2024-03-09 | INFURITY Gaming   | L   | 0.657      | -            | -                | -                | -         |   -10.35 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            4 |     4867 | 2024-03-06 | Cashout Cavaliers | W   | 0.637      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.99 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            3 |     5035 | 2024-03-04 | Apeks Legends     | W   | 0.624      | 0.143        | 0.000 (0.000)    | 0.037 (0.003)    | 0 (0.000) |     7.15 | mathio, Sulfur, thomass1, YoHz, zame       |
|            2 |     6204 | 2024-02-12 | Metizport X       | L   | 0.484      | -            | -                | -                | -         |    -3.86 | mathio, Sulfur, thomass1, YoHz, zame       |
|            1 |     6423 | 2024-02-05 | Nordix Esport     | L   | 0.437      | -            | -                | -                | -         |    -4.38 | mathio, Sulfur, thomass1, YoHz, zame       |

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
