### Roster Details<br />
Team Name: Static<br />
Roster: mathio, Sulfur, thomass1, YoHz, zame<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [340](../standings_global.md)<br />
Regional Rank: [209]( ../standings_europe.md)<br />
Final Rank Value:  516.6<br />
<br />
Final Rank Value (516.6) = Starting Rank Value (514.7) + Head To Head Adjustments (1.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.058<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 514.7
- 400 + ( ( 0.058 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 514.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      309 | 2024-04-28 | Foxed Gaming      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.114 (0.016)    | false (0.000) |     9.77 | mathio, Sulfur, thomass1, YoHz, zame       |
|           17 |      407 | 2024-04-26 | Esport Harte      | L   | 1.000      | -            | -                | -                | -             |   -13.12 | berzerk, mathio, thomass1, YoHz, zame      |
|           16 |      412 | 2024-04-26 | JANO Esports      | L   | 1.000      | -            | -                | -                | -             |    -7.21 | berzerk, mathio, thomass1, YoHz, zame      |
|           15 |      417 | 2024-04-26 | Preasy Esport     | L   | 1.000      | -            | -                | -                | -             |    -8.77 | berzerk, mathio, thomass1, YoHz, zame      |
|           14 |      424 | 2024-04-26 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -             |    -0.58 | berzerk, mathio, thomass1, YoHz, zame      |
|           13 |      609 | 2024-04-22 | Bitfix Gaming     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.031 (0.004)    | false (0.000) |     8.40 | mathio, Sulfur, thomass1, YoHz, zame       |
|           12 |      802 | 2024-04-19 | Heimo Esports     | W   | 1.000      | 0.143        | 0.020 (0.003)    | 0.229 (0.033)    | false (0.000) |    25.02 | berzerk, mathio, thomass1, YoHz, zame      |
|           11 |      805 | 2024-04-19 | Foxed Gaming      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.114 (0.016)    | false (0.000) |    10.07 | berzerk, mathio, thomass1, YoHz, zame      |
|           10 |      810 | 2024-04-19 | Khai Thonq        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |    11.73 | berzerk, mathio, thomass1, YoHz, zame      |
|            9 |     1330 | 2024-04-08 | 777 Esports       | L   | 1.000      | -            | -                | -                | -             |    -4.92 | mathio, Sulfur, thomass1, YoHz, zame       |
|            8 |     2167 | 2024-03-16 | Nordix Esport     | L   | 0.865      | -            | -                | -                | -             |   -15.05 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            7 |     2317 | 2024-03-13 | 777 Esports       | L   | 0.845      | -            | -                | -                | -             |    -5.16 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            6 |     2417 | 2024-03-11 | INFURITY Gaming   | W   | 0.832      | 0.143        | 0.000 (0.000)    | 0.274 (0.033)    | false (0.000) |    10.56 | mathio, rinji2k, Sulfur, thomass1, zame    |
|            5 |     2489 | 2024-03-09 | INFURITY Gaming   | L   | 0.819      | -            | -                | -                | -             |   -15.73 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            4 |     2615 | 2024-03-06 | Cashout Cavaliers | W   | 0.799      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     8.83 | forb1dden, mathio, Sulfur, thomass1, Zypno |
|            3 |     2755 | 2024-03-04 | Apeks Legends     | W   | 0.785      | 0.143        | 0.000 (0.000)    | 0.058 (0.006)    | false (0.000) |     9.03 | mathio, Sulfur, thomass1, YoHz, zame       |
|            2 |     3722 | 2024-02-12 | Metizport X       | L   | 0.645      | -            | -                | -                | -             |    -8.99 | mathio, Sulfur, thomass1, YoHz, zame       |
|            1 |     3896 | 2024-02-05 | Nordix Esport     | L   | 0.598      | -            | -                | -                | -             |   -12.03 | mathio, Sulfur, thomass1, YoHz, zame       |

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
