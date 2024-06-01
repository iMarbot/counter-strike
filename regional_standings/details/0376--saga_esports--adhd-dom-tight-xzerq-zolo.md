### Roster Details<br />
Team Name: SAGA Esports<br />
Roster: ADHD, DOM, Tight, xZerq, Zolo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [376](../standings_global.md)<br />
Regional Rank: [224]( ../standings_europe.md)<br />
Final Rank Value:  581.8<br />
<br />
Final Rank Value (581.8) = Starting Rank Value (583.5) + Head To Head Adjustments (-1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.090<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 583.5
- 400 + ( ( 0.090 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 583.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3978 | 2024-03-23 | DUSTY       | L   | 0.751      | -            | -                | -                | -         |    -8.20 | ADHD, DOM, Tight, xZerq, Zolo |
|            9 |     4031 | 2024-03-22 | Þór         | W   | 0.744      | 0.143        | 0.000 (0.000)    | 0.090 (0.010)    | 1 (0.744) |    10.34 | ADHD, DOM, Tight, xZerq, Zolo |
|            8 |     4424 | 2024-03-14 | FH          | W   | 0.691      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.87 | ADHD, DOM, Tight, xZerq, Zolo |
|            7 |     5925 | 2024-02-17 | ÍBV Esports | W   | 0.518      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.07 | ADHD, DOM, Tight, xZerq, Zolo |
|            6 |     6146 | 2024-02-13 | Breiðablik  | L   | 0.491      | -            | -                | -                | -         |    -9.38 | ADHD, DOM, Tight, xZerq, Zolo |
|            5 |     6318 | 2024-02-08 | Þór         | L   | 0.458      | -            | -                | -                | -         |    -8.63 | ADHD, DOM, Tight, xZerq, Zolo |
|            4 |     7314 | 2024-01-20 | Þór         | W   | 0.331      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 0 (0.000) |     2.74 | ADHD, DOM, Tight, xZerq, Zolo |
|            3 |     7452 | 2024-01-18 | Ármann      | W   | 0.318      | 0.143        | 0.000 (0.000)    | 0.054 (0.002)    | 0 (0.000) |     3.84 | ADHD, DOM, Tight, xZerq, Zolo |
|            2 |     7924 | 2024-01-11 | DUSTY       | L   | 0.271      | -            | -                | -                | -         |    -2.55 | ADHD, DOM, Tight, xZerq, Zolo |
|            1 |     9279 | 2023-12-05 | ÍA Akranes  | W   | 0.025      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.20 | ADHD, DOM, Tight, xZerq, Zolo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($817.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
