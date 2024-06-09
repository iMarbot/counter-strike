### Roster Details<br />
Team Name: phantom troupe<br />
Roster: edv, FasteR, mattexx, n0page, stalfer<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [381](../standings_global.md)<br />
Regional Rank: [95]( ../standings_americas.md)<br />
Final Rank Value:  584.6<br />
<br />
Final Rank Value (584.6) = Starting Rank Value (603.4) + Head To Head Adjustments (-18.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.218[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.100<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 603.4
- 400 + ( ( 0.100 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 603.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      843 | 2024-05-18 | Hawks         | L   | 1.000      | -            | -                | -                | -         |   -15.19 | edv, FasteR, mattexx, n0page, stalfer |
|           13 |      852 | 2024-05-18 | pugdesonesto  | L   | 1.000      | -            | -                | -                | -         |   -16.25 | edv, FasteR, mattexx, n0page, stalfer |
|           12 |      862 | 2024-05-18 | beliebers     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.23 | edv, FasteR, mattexx, n0page, stalfer |
|           11 |     4912 | 2024-03-07 | 9z Academy    | L   | 0.646      | -            | -                | -                | -         |    -8.99 | edv, FasteR, gtw, n0page, redi        |
|           10 |     5634 | 2024-02-24 | SoJoga        | L   | 0.566      | -            | -                | -                | -         |    -8.02 | edv, FasteR, gtw, n0page, redi        |
|            9 |     5650 | 2024-02-24 | Myth e-Sports | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.041 (0.003)    | 0 (0.000) |     8.68 | edv, FasteR, gtw, n0page, redi        |
|            8 |     5656 | 2024-02-24 | Hazap Esports | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.037 (0.003)    | 0 (0.000) |     7.85 | edv, FasteR, gtw, n0page, redi        |
|            7 |     5661 | 2024-02-24 | QUASE         | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     6.59 | edv, FasteR, gtw, n0page, redi        |
|            6 |     5669 | 2024-02-24 | NIGERIA 96    | L   | 0.564      | -            | -                | -                | -         |    -8.61 | edv, FasteR, gtw, n0page, redi        |
|            5 |     5682 | 2024-02-24 | pugdesonesto  | W   | 0.564      | 0.143        | 0.001 (0.000)    | 0.146 (0.012)    | 0 (0.000) |     9.24 | edv, FasteR, gtw, n0page, redi        |
|            4 |     7139 | 2024-01-27 | Romanticos    | L   | 0.378      | -            | -                | -                | -         |    -5.22 | edv, FasteR, gtw, n0page, redi        |
|            3 |     7149 | 2024-01-27 | Dusty Roots   | W   | 0.378      | 0.143        | 0.003 (0.000)    | 0.425 (0.023)    | 0 (0.000) |     7.02 | edv, FasteR, gtw, n0page, redi        |
|            2 |     7159 | 2024-01-27 | TEAM ORUGA    | L   | 0.378      | -            | -                | -                | -         |    -5.95 | edv, FasteR, gtw, n0page, redi        |
|            1 |     7169 | 2024-01-27 | Martians      | W   | 0.378      | 0.143        | 0.000 (0.000)    | 0.010 (0.001)    | 0 (0.000) |     2.83 | edv, FasteR, gtw, n0page, redi        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($76.38)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
