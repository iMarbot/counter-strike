### Roster Details<br />
Team Name: Wave Esports<br />
Roster: GHOST, S1M, sjN, syncD, XCR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [317](../standings_global.md)<br />
Regional Rank: [193]( ../standings_europe.md)<br />
Final Rank Value:  589.0<br />
<br />
Final Rank Value (589.0) = Starting Rank Value (643.3) + Head To Head Adjustments (-54.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 643.3
- 400 + ( ( 0.123 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 643.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      606 | 2024-04-22 | Sissi State Punks    | L   | 1.000      | -            | -                | -                | -         |   -10.97 | GHOST, S1M, sjN, syncD, XCR      |
|           16 |     1139 | 2024-04-12 | ALTERNATE aTTaX      | L   | 1.000      | -            | -                | -                | -         |   -20.28 | GHOST, S1M, sjN, syncD, XCR      |
|           15 |     1399 | 2024-04-06 | OTHERSCANTBEAT       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     9.84 | delkore, GHOST, sjN, syncD, XCR  |
|           14 |     1472 | 2024-04-04 | Calm Fit             | W   | 0.992      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.36 | delkore, GHOST, sjN, syncD, XCR  |
|           13 |     1601 | 2024-04-01 | TeamOrangeGaming     | L   | 0.971      | -            | -                | -                | -         |    -8.13 | delkore, sjN, Snance, syncD, XCR |
|           12 |     1822 | 2024-03-26 | ALTERNATE aTTaX Evo  | L   | 0.932      | -            | -                | -                | -         |   -13.00 | delkore, sjN, Snance, syncD, XCR |
|           11 |     2218 | 2024-03-15 | Sissi State Punks    | L   | 0.858      | -            | -                | -                | -         |   -10.45 | delkore, sjN, Snance, syncD, XCR |
|           10 |     2622 | 2024-03-06 | ALTERNATE aTTaX Evo  | L   | 0.798      | -            | -                | -                | -         |   -11.11 | delkore, sjN, Snance, syncD, XCR |
|            9 |     2866 | 2024-03-02 | Sissi State Punks    | L   | 0.772      | -            | -                | -                | -         |   -10.96 | delkore, sjN, Snance, syncD, XCR |
|            8 |     3443 | 2024-02-18 | SNOGARD Dragons      | W   | 0.685      | 0.143        | 0.009 (0.001)    | 0.117 (0.011)    | 0 (0.000) |    13.03 | delkore, sjN, Snance, syncD, XCR |
|            7 |     3875 | 2024-02-05 | OTHERSCANTBEAT       | W   | 0.599      | 0.143        | 0.000 (0.000)    | 0.028 (0.002)    | 0 (0.000) |     5.69 | delkore, sjN, Snance, syncD, XCR |
|            6 |     4462 | 2024-01-22 | ALTERNATE aTTaX Evo  | L   | 0.505      | -            | -                | -                | -         |    -6.41 | delkore, sjN, Snance, syncD, XCR |
|            5 |     5837 | 2023-12-08 | ONYX Dojo            | W   | 0.205      | 0.143        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     1.34 | GHOST, hayanh, sjN, Snance, XCR  |
|            4 |     6103 | 2023-12-02 | UNEVEN               | W   | 0.165      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.07 | GHOST, hayanh, sjN, Snance, XCR  |
|            3 |     6161 | 2023-12-01 | AMAWU                | W   | 0.158      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.03 | GHOST, hayanh, sjN, Snance, XCR  |
|            2 |     6625 | 2023-11-20 | Reveal (German team) | L   | 0.086      | -            | -                | -                | -         |    -1.40 | S1M, sjN, Snance, Spexy, XCR     |
|            1 |     6742 | 2023-11-18 | ARROW (German team)  | L   | 0.070      | -            | -                | -                | -         |    -0.94 | S1M, sjN, Snance, Spexy, XCR     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($578.46)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-26 |      0.932 | $81.30         | $75.79          |
| 2024-03-06 |      0.798 | $81.34         | $64.94          |
| 2023-12-16 |      0.258 | $1,527.04      | $393.57         |
| 2023-12-08 |      0.205 | $215.47        | $44.16          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
