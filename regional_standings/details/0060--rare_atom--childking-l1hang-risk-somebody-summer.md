### Roster Details<br />
Team Name: Rare Atom<br />
Roster: ChildKing, L1haNg, risk, somebody, Summer<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [60](../standings_global.md)<br />
Regional Rank: [6]( ../standings_asia.md)<br />
Final Rank Value:  949.7<br />
<br />
Final Rank Value (949.7) = Starting Rank Value (798.0) + Head To Head Adjustments (151.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.424[<sup>1</sup>](#table2)
- Bounty Collected: 0.329[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 798.0
- 400 + ( ( 0.201 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 798.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      656 | 2024-04-21 | ATOX Esports             | W   | 1.000      | 0.143        | 0.112 (0.016)    | 0.769 (0.110)    | false (0.000) |    21.57 | ChildKing, L1haNg, risk, somebody, Summer |
|           10 |      675 | 2024-04-20 | High Five (Chinese team) | W   | 1.000      | 0.143        | 0.045 (0.006)    | 0.282 (0.040)    | false (0.000) |     8.33 | ChildKing, L1haNg, risk, somebody, Summer |
|            9 |      837 | 2024-04-19 | The MongolZ              | L   | 1.000      | -            | -                | -                | -             |    -0.86 | ChildKing, L1haNg, risk, somebody, Summer |
|            8 |      850 | 2024-04-19 | TYLOO                    | W   | 1.000      | 0.143        | 0.131 (0.019)    | 0.592 (0.085)    | false (0.000) |    21.24 | ChildKing, L1haNg, risk, somebody, Summer |
|            7 |      887 | 2024-04-18 | Lynn Vision Gaming       | W   | 1.000      | 0.143        | 0.155 (0.022)    | 0.554 (0.079)    | false (0.000) |    26.16 | ChildKing, L1haNg, risk, somebody, Summer |
|            6 |      902 | 2024-04-18 | The MongolZ              | L   | 1.000      | -            | -                | -                | -             |    -0.67 | ChildKing, L1haNg, risk, somebody, Summer |
|            5 |      907 | 2024-04-18 | Lynn Vision Gaming       | W   | 1.000      | 0.143        | 0.155 (0.022)    | 0.554 (0.079)    | false (0.000) |    27.79 | ChildKing, L1haNg, risk, somebody, Summer |
|            4 |      910 | 2024-04-17 | Rooster                  | W   | 1.000      | 0.143        | 0.031 (0.004)    | 0.312 (0.045)    | false (0.000) |    18.29 | ChildKing, L1haNg, risk, somebody, Summer |
|            3 |      958 | 2024-04-17 | Team NKT                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | false (0.000) |     5.75 | ChildKing, L1haNg, risk, somebody, Summer |
|            2 |      965 | 2024-04-17 | MIRAI Gaming             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.246 (0.035)    | false (0.000) |    11.79 | ChildKing, L1haNg, risk, somebody, Summer |
|            1 |     1013 | 2024-04-16 | Born In Far East         | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.138 (0.020)    | false (0.000) |    12.31 | ChildKing, L1haNg, risk, somebody, Summer |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,906.26)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
