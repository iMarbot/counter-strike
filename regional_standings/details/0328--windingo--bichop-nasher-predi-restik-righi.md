### Roster Details<br />
Team Name: WINDINGO<br />
Roster: bichop, nasher, PREDI, restik, Righi<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [328](../standings_global.md)<br />
Regional Rank: [77]( ../standings_americas.md)<br />
Final Rank Value:  623.1<br />
<br />
Final Rank Value (623.1) = Starting Rank Value (624.7) + Head To Head Adjustments (-1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.244[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 624.7
- 400 + ( ( 0.111 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 624.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     8668 | 2023-12-18 | Corinthians Esports       | L   | 0.111      | -            | -                | -                | -         |    -1.79 | bichop, nasher, PREDI, restik, Righi |
|           10 |     8672 | 2023-12-18 | w7m esports               | L   | 0.110      | -            | -                | -                | -         |    -1.08 | bichop, nasher, PREDI, restik, Righi |
|            9 |     8821 | 2023-12-16 | Team Solid                | W   | 0.098      | 0.143        | 0.062 (0.001)    | 0.334 (0.005)    | 0 (0.000) |     2.49 | bichop, nasher, PREDI, restik, Righi |
|            8 |     8983 | 2023-12-15 | Arena Jogue Fácil Esports | W   | 0.092      | 0.143        | 0.000 (0.000)    | 0.038 (0.000)    | 0 (0.000) |     1.38 | bichop, nasher, PREDI, restik, Righi |
|            7 |     9077 | 2023-12-13 | Team Solid                | L   | 0.078      | -            | -                | -                | -         |    -0.48 | bichop, nasher, PREDI, restik, Righi |
|            6 |     9168 | 2023-12-11 | TIMACETA                  | L   | 0.065      | -            | -                | -                | -         |    -1.02 | bichop, nasher, PREDI, restik, Righi |
|            5 |     9408 | 2023-12-07 | Meta Gaming               | L   | 0.039      | -            | -                | -                | -         |    -0.85 | bichop, nasher, PREDI, restik, Righi |
|            4 |     9480 | 2023-12-06 | Boca Juniors Gaming       | W   | 0.032      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.22 | bichop, nasher, PREDI, restik, Righi |
|            3 |     9482 | 2023-12-06 | w7m esports               | L   | 0.032      | -            | -                | -                | -         |    -0.32 | bichop, nasher, PREDI, restik, Righi |
|            2 |     9542 | 2023-12-05 | Flamengo Esports          | W   | 0.026      | 0.262        | 0.000 (0.000)    | 0.080 (0.001)    | 0 (0.000) |     0.29 | bichop, nasher, PREDI, restik, Righi |
|            1 |     9566 | 2023-12-05 | Arena Jogue Fácil Esports | L   | 0.024      | -            | -                | -                | -         |    -0.41 | bichop, nasher, PREDI, restik, Righi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($239.16)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
