### Roster Details<br />
Team Name: Apeks Rebels<br />
Roster: Boye, bq, Junyme, Q-Q, Tapewaare<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [236](../standings_global.md)<br />
Regional Rank: [152]( ../standings_europe.md)<br />
Final Rank Value:  677.2<br />
<br />
Final Rank Value (677.2) = Starting Rank Value (693.4) + Head To Head Adjustments (-16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.148<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.4
- 400 + ( ( 0.148 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 693.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1581 | 2024-04-02 | 9INE Academy    | L   | 0.977      | -            | -                | -                | -         |   -16.33 | Boye, bq, Junyme, Q-Q, Tapewaare      |
|           10 |     1600 | 2024-04-01 | SINNERS Academy | L   | 0.972      | -            | -                | -                | -         |   -16.03 | Boye, bq, Junyme, Q-Q, Tapewaare      |
|            9 |     1631 | 2024-03-30 | 777 Esports     | W   | 0.959      | 0.289        | 0.032 (0.009)    | 0.550 (0.153)    | 0 (0.000) |    18.52 | bobeksde, Boye, bq, spooke, Tapewaare |
|            8 |     1758 | 2024-03-27 | EP Genesis      | W   | 0.938      | 0.289        | 0.000 (0.000)    | 0.187 (0.051)    | 0 (0.000) |     9.61 | Boye, bq, Junyme, Q-Q, Tapewaare      |
|            7 |     1914 | 2024-03-23 | Metizport X     | L   | 0.911      | -            | -                | -                | -         |   -18.14 | Boye, bq, Junyme, Q-Q, Tapewaare      |
|            6 |     2063 | 2024-03-19 | EP Genesis      | W   | 0.884      | 0.289        | 0.000 (0.000)    | 0.187 (0.048)    | 0 (0.000) |     8.44 | Boye, bq, Junyme, Q-Q, Tapewaare      |
|            5 |     6405 | 2023-11-26 | GODSENT         | L   | 0.123      | -            | -                | -                | -         |    -1.37 | berzerk, bq, markow, Q-Q, Tapewaare   |
|            4 |     6429 | 2023-11-25 | Xtream e-sport  | W   | 0.118      | 0.143        | 0.001 (0.000)    | 0.004 (0.000)    | 1 (0.118) |     1.09 | berzerk, bq, markow, Q-Q, Tapewaare   |
|            3 |     6684 | 2023-11-19 | 777 Esports     | L   | 0.076      | -            | -                | -                | -         |    -1.42 | berzerk, bq, markow, Q-Q, Tapewaare   |
|            2 |     6979 | 2023-11-13 | Team Universe   | L   | 0.038      | -            | -                | -                | -         |    -0.74 | berzerk, bq, markow, Q-Q, Tapewaare   |
|            1 |     7142 | 2023-11-09 | RoundsGG        | W   | 0.011      | 0.289        | 0.000 (0.000)    | 0.170 (0.001)    | 0 (0.000) |     0.19 | berzerk, bq, markow, Q-Q, Tapewaare   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($864.35)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-11-26 |      0.123 | $3,831.20      | $472.34         |
| 2023-11-19 |      0.076 | $4,632.25      | $354.28         |
| 2023-11-13 |      0.038 | $1,000.00      | $37.73          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
