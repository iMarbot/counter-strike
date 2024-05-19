### Roster Details<br />
Team Name: Flamengo Esports<br />
Roster: ALLE, danoco, LUCAS1, realz1n, rem1x<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [304](../standings_global.md)<br />
Regional Rank: [69]( ../standings_americas.md)<br />
Final Rank Value:  605.9<br />
<br />
Final Rank Value (605.9) = Starting Rank Value (531.3) + Head To Head Adjustments (74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.066<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 531.3
- 400 + ( ( 0.066 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 531.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     4302 | 2024-01-26 | ODDIK             | L   | 0.533      | -            | -                | -                | -             |    -2.42 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           17 |     4305 | 2024-01-26 | Yawara E-Sports   | W   | 0.532      | 0.143        | 0.005 (0.000)    | 0.361 (0.027)    | false (0.000) |    11.12 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           16 |     4345 | 2024-01-25 | Dusty Roots       | W   | 0.527      | 0.143        | 0.005 (0.000)    | 0.352 (0.027)    | false (0.000) |    10.57 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           15 |     4495 | 2024-01-21 | RED Canids        | L   | 0.500      | -            | -                | -                | -             |    -2.02 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           14 |     4500 | 2024-01-21 | TIMACETA          | W   | 0.498      | 0.143        | 0.001 (0.000)    | 0.145 (0.010)    | false (0.000) |    10.30 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           13 |     4527 | 2024-01-20 | Galorys           | W   | 0.493      | 0.143        | 0.048 (0.003)    | 0.598 (0.042)    | false (0.000) |    12.98 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           12 |     4585 | 2024-01-19 | ODDIK             | L   | 0.487      | -            | -                | -                | -             |    -2.00 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           11 |     4592 | 2024-01-19 | BESTIA            | L   | 0.486      | -            | -                | -                | -             |    -3.22 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|           10 |     5066 | 2024-01-09 | Legacy            | W   | 0.421      | 0.143        | 0.061 (0.004)    | 0.262 (0.016)    | false (0.000) |    12.68 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|            9 |     5069 | 2024-01-09 | ODDIK             | W   | 0.420      | 0.143        | 0.015 (0.001)    | 0.402 (0.024)    | false (0.000) |    11.67 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|            8 |     5072 | 2024-01-09 | Case Esports      | W   | 0.419      | 0.143        | 0.010 (0.001)    | 0.142 (0.008)    | false (0.000) |     9.93 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|            7 |     5140 | 2024-01-08 | A FUNDACAO        | W   | 0.414      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.18 | ALLE, danoco, LUCAS1, realz1n, rem1x  |
|            6 |     6706 | 2023-11-18 | RED Canids        | L   | 0.072      | -            | -                | -                | -             |    -0.23 | ALLE, danoco, realz1n, rem1x, RICIOLI |
|            5 |     6758 | 2023-11-17 | Case Esports      | L   | 0.067      | -            | -                | -                | -             |    -0.57 | ALLE, danoco, realz1n, rem1x, RICIOLI |
|            4 |     6759 | 2023-11-17 | Sharks Esports    | L   | 0.066      | -            | -                | -                | -             |    -0.25 | ALLE, danoco, realz1n, rem1x, RICIOLI |
|            3 |     6811 | 2023-11-16 | Case Esports      | W   | 0.059      | 0.303        | 0.010 (0.000)    | 0.142 (0.003)    | false (0.000) |     1.35 | ALLE, danoco, realz1n, rem1x, RICIOLI |
|            2 |     6909 | 2023-11-14 | RED Canids        | L   | 0.046      | -            | -                | -                | -             |    -0.15 | ALLE, danoco, realz1n, rem1x, RICIOLI |
|            1 |     6993 | 2023-11-12 | Patins da Ferrari | W   | 0.033      | 0.303        | 0.001 (0.000)    | 0.034 (0.000)    | false (0.000) |     0.64 | ALLE, danoco, realz1n, rem1x, RICIOLI |

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
