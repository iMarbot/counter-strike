### Roster Details<br />
Team Name: EP Genesis<br />
Roster: fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [329](../standings_global.md)<br />
Regional Rank: [201]( ../standings_europe.md)<br />
Final Rank Value:  550.4<br />
<br />
Final Rank Value (550.4) = Starting Rank Value (510.4) + Head To Head Adjustments (40.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.4
- 400 + ( ( 0.056 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 510.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      273 | 2024-04-29 | L&G                         | L   | 1.000      | -            | -                | -                | -         |    -8.92 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           12 |      360 | 2024-04-27 | Lazer Cats                  | L   | 1.000      | -            | -                | -                | -         |   -11.95 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           11 |      435 | 2024-04-26 | Dynamo Eclot Thunders       | W   | 1.000      | 0.289        | 0.000 (0.000)    | 0.035 (0.010)    | 0 (0.000) |     8.15 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|           10 |      569 | 2024-04-23 | BRUTE                       | W   | 1.000      | 0.289        | 0.000 (0.000)    | 0.122 (0.035)    | 0 (0.000) |    12.41 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            9 |     1758 | 2024-03-27 | Apeks Rebels                | L   | 0.938      | -            | -                | -                | -         |    -9.61 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            8 |     1904 | 2024-03-23 | ALTERNATE aTTaX Evo         | W   | 0.912      | 0.289        | 0.005 (0.001)    | 0.198 (0.052)    | 0 (0.000) |    18.77 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            7 |     2063 | 2024-03-19 | Apeks Rebels                | L   | 0.884      | -            | -                | -                | -         |    -8.44 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            6 |     2485 | 2024-03-09 | FALKE ESPORTS               | W   | 0.819      | 0.333        | 0.000 (0.000)    | 0.021 (0.006)    | 0 (0.000) |    11.02 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            5 |     2581 | 2024-03-07 | UNiTY esports (Slovak team) | L   | 0.804      | -            | -                | -                | -         |    -4.22 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            4 |     2630 | 2024-03-06 | Lan Party Hotel             | W   | 0.797      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.63 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            3 |     2686 | 2024-03-05 | Begrip Gaming               | W   | 0.792      | 0.333        | 0.001 (0.000)    | 0.196 (0.052)    | 0 (0.000) |    16.25 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            2 |     2763 | 2024-03-04 | UNiTY esports (Slovak team) | L   | 0.785      | -            | -                | -                | -         |    -3.55 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |
|            1 |     3033 | 2024-02-27 | BRUTE                       | W   | 0.745      | 0.143        | 0.000 (0.000)    | 0.122 (0.013)    | 0 (0.000) |    12.44 | fajrness, Happyy, NIKOLAJ, PerdY, Snaxieee |

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
