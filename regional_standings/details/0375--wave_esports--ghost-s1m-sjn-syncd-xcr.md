### Roster Details<br />
Team Name: Wave Esports<br />
Roster: GHOST, S1M, sjN, syncD, XCR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [375](../standings_global.md)<br />
Regional Rank: [223]( ../standings_europe.md)<br />
Final Rank Value:  584.0<br />
<br />
Final Rank Value (584.0) = Starting Rank Value (632.6) + Head To Head Adjustments (-48.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.248[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.6
- 400 + ( ( 0.114 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 632.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |       69 | 2024-05-29 | Sampi NEXT          | L   | 1.000      | -            | -                | -                | -         |   -21.18 | GHOST, S1M, sjN, syncD, XCR      |
|           20 |      387 | 2024-05-23 | EVOPLAY             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.015 (0.002)    | 0 (0.000) |    13.98 | GHOST, S1M, sjN, syncD, XCR      |
|           19 |      488 | 2024-05-22 | SNOGARD Dragons     | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.137 (0.020)    | 0 (0.000) |    21.71 | GHOST, S1M, sjN, syncD, XCR      |
|           18 |     1165 | 2024-05-15 | ARROW               | L   | 1.000      | -            | -                | -                | -         |    -8.63 | GHOST, S1M, sjN, syncD, XCR      |
|           17 |     2453 | 2024-04-22 | Sissi State Punks   | L   | 0.950      | -            | -                | -                | -         |   -11.36 | GHOST, S1M, sjN, syncD, XCR      |
|           16 |     2833 | 2024-04-17 | mYinsanity          | W   | 0.917      | 0.143        | 0.001 (0.000)    | 0.124 (0.016)    | 0 (0.000) |    17.20 | GHOST, S1M, sjN, syncD, XCR      |
|           15 |     3076 | 2024-04-12 | ALTERNATE aTTaX     | L   | 0.883      | -            | -                | -                | -         |    -3.27 | GHOST, S1M, sjN, syncD, XCR      |
|           14 |     3338 | 2024-04-07 | ex-RED              | L   | 0.850      | -            | -                | -                | -         |   -12.45 | delkore, GHOST, sjN, syncD, XCR  |
|           13 |     3390 | 2024-04-06 | OTHERSCANTBEAT      | W   | 0.843      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.14 | delkore, GHOST, sjN, syncD, XCR  |
|           12 |     3436 | 2024-04-05 | mYinsanity          | L   | 0.838      | -            | -                | -                | -         |   -10.82 | delkore, GHOST, sjN, syncD, XCR  |
|           11 |     3482 | 2024-04-04 | Calm Fit            | W   | 0.831      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.67 | delkore, GHOST, sjN, syncD, XCR  |
|           10 |     3625 | 2024-04-01 | TeamOrangeGaming    | L   | 0.810      | -            | -                | -                | -         |    -7.32 | GHOST, S1M, sjN, syncD, XCR      |
|            9 |     3890 | 2024-03-26 | ALTERNATE aTTaX Evo | L   | 0.771      | -            | -                | -                | -         |    -9.19 | delkore, sjN, Snance, syncD, XCR |
|            8 |     4378 | 2024-03-15 | Sissi State Punks   | L   | 0.697      | -            | -                | -                | -         |    -9.14 | delkore, sjN, Snance, syncD, XCR |
|            7 |     4810 | 2024-03-07 | EPIC DUDES          | L   | 0.644      | -            | -                | -                | -         |   -13.55 | delkore, sjN, Snance, syncD, XCR |
|            6 |     4874 | 2024-03-06 | ALTERNATE aTTaX Evo | L   | 0.637      | -            | -                | -                | -         |    -7.73 | delkore, sjN, Snance, syncD, XCR |
|            5 |     5169 | 2024-03-02 | Sissi State Punks   | W   | 0.611      | 0.143        | 0.004 (0.000)    | 0.226 (0.020)    | 0 (0.000) |    10.78 | delkore, sjN, Snance, syncD, XCR |
|            4 |     5868 | 2024-02-18 | SNOGARD Dragons     | L   | 0.524      | -            | -                | -                | -         |    -5.58 | delkore, sjN, Snance, syncD, XCR |
|            3 |     6399 | 2024-02-05 | OTHERSCANTBEAT      | W   | 0.438      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.00 | delkore, sjN, Snance, syncD, XCR |
|            2 |     6833 | 2024-01-29 | TeamOrangeGaming    | L   | 0.391      | -            | -                | -                | -         |    -3.48 | delkore, sjN, Snance, syncD, XCR |
|            1 |     7220 | 2024-01-22 | ALTERNATE aTTaX Evo | L   | 0.344      | -            | -                | -                | -         |    -4.37 | delkore, sjN, Snance, syncD, XCR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($277.44)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-25 |      1.000 | $162.85        | $162.85         |
| 2024-03-26 |      0.771 | $81.30         | $62.70          |
| 2024-03-06 |      0.638 | $81.34         | $51.90          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
