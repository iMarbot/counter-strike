### Roster Details<br />
Team Name: Reason Gaming<br />
Roster: Byfield, Cha0s, CJE, FincHY, Rezzed<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [174](../standings_global.md)<br />
Regional Rank: [118]( ../standings_europe.md)<br />
Final Rank Value:  751.3<br />
<br />
Final Rank Value (751.3) = Starting Rank Value (808.3) + Head To Head Adjustments (-57.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.332[<sup>1</sup>](#table2)
- Bounty Collected: 0.196[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.294[<sup>2</sup>](#table1)

The average of these factors is 0.206<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 808.3
- 400 + ( ( 0.206 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 808.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      691 | 2024-04-20 | Team Sodality        | L   | 1.000      | -            | -                | -                | -             |   -25.42 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|           10 |      794 | 2024-04-19 | BLUEJAYS Royal       | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.22 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            9 |      796 | 2024-04-19 | Costco Guys          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     3.43 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            8 |     1606 | 2024-04-01 | Verdant              | L   | 0.970      | -            | -                | -                | -             |    -8.93 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            7 |     1618 | 2024-03-31 | Ahoka                | W   | 0.965      | 0.143        | 0.006 (0.001)    | 0.067 (0.009)    | true (0.965)  |    14.93 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            6 |     1637 | 2024-03-30 | Ahoka                | L   | 0.958      | -            | -                | -                | -             |   -15.01 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            5 |     1649 | 2024-03-30 | The Mighty Sun       | W   | 0.957      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | true (0.957)  |     3.22 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            4 |     3080 | 2024-02-26 | Permitta Esports     | L   | 0.736      | -            | -                | -                | -             |    -5.02 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            3 |     3184 | 2024-02-24 | The Last Resort      | L   | 0.723      | -            | -                | -                | -             |   -14.13 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            2 |     3197 | 2024-02-23 | Disco Diggers        | W   | 0.720      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | true (0.720)  |     2.24 | Byfield, Cha0s, CJE, FincHY, Rezzed |
|            1 |     3785 | 2024-02-09 | Raptors Esports Club | L   | 0.626      | -            | -                | -                | -             |   -15.57 | Byfield, Cha0s, CJE, FincHY, RezzeD |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,532.55)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
