### Roster Details<br />
Team Name: LOG Esports<br />
Roster: fix, gbs, juliustbe, SlaxLer, v1ze<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [453](../standings_global.md)<br />
Regional Rank: [273]( ../standings_europe.md)<br />
Final Rank Value:  467.7<br />
<br />
Final Rank Value (467.7) = Starting Rank Value (531.2) + Head To Head Adjustments (-63.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.065<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 531.2
- 400 + ( ( 0.065 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 531.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     1165 | 2024-05-15 | Copenhagen Wolves   | L   | 1.000      | -            | -                | -                | -         |    -9.30 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            9 |     1318 | 2024-05-13 | ex-K10              | L   | 1.000      | -            | -                | -                | -         |    -5.12 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            8 |     1643 | 2024-05-08 | TopTab Club         | L   | 1.000      | -            | -                | -                | -         |   -13.93 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            7 |     1995 | 2024-05-01 | Verdant             | L   | 1.000      | -            | -                | -                | -         |    -3.32 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            6 |     2057 | 2024-04-30 | Denial              | L   | 1.000      | -            | -                | -                | -         |   -12.76 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            5 |     2402 | 2024-04-24 | VP.Prodigy          | L   | 0.964      | -            | -                | -                | -         |    -4.57 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            4 |     2495 | 2024-04-22 | FLuffy Gangsters    | L   | 0.951      | -            | -                | -                | -         |   -10.40 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            3 |     2906 | 2024-04-17 | ENRAGE              | L   | 0.916      | -            | -                | -                | -         |   -13.78 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            2 |     3003 | 2024-04-15 | LOADING             | L   | 0.904      | -            | -                | -                | -         |   -13.24 | fix, gbs, juliustbe, SlaxLer, v1ze |
|            1 |     3364 | 2024-04-08 | GamerLegion Academy | W   | 0.857      | 0.372        | 0.018 (0.006)    | 0.691 (0.221)    | 0 (0.000) |    22.99 | fix, gbs, juliustbe, SlaxLer, v1ze |

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
