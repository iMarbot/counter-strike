### Roster Details<br />
Team Name: ADEPTS<br />
Roster: cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [313](../standings_global.md)<br />
Regional Rank: [191]( ../standings_europe.md)<br />
Final Rank Value:  596.2<br />
<br />
Final Rank Value (596.2) = Starting Rank Value (643.3) + Head To Head Adjustments (-47.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
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


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      191 | 2024-05-01 | Kappa Bar            | L   | 1.000      | -            | -                | -                | -         |   -18.20 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            9 |      200 | 2024-05-01 | Denial (Danish team) | L   | 1.000      | -            | -                | -                | -         |   -20.33 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            8 |      239 | 2024-04-30 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -17.02 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            7 |      516 | 2024-04-24 | Aurora Young Blud    | L   | 1.000      | -            | -                | -                | -         |    -9.88 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            6 |     2096 | 2024-03-18 | HyperSpirit          | L   | 0.878      | -            | -                | -                | -         |   -12.52 | ADRON, GEOHYPE, kritik, smekk, swiiffter |
|            5 |     2120 | 2024-03-17 | Team OWL             | W   | 0.872      | 0.333        | 0.000 (0.000)    | 0.036 (0.011)    | 0 (0.000) |     7.36 | aNsavage, NeoLife, Nosik, s7xWn, Snoob   |
|            4 |     2164 | 2024-03-16 | WOPA Esport          | L   | 0.866      | -            | -                | -                | -         |   -10.08 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            3 |     2402 | 2024-03-11 | Lewandownskie        | W   | 0.832      | 0.333        | 0.004 (0.001)    | 0.181 (0.050)    | 0 (0.000) |    13.04 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            2 |     2564 | 2024-03-07 | XI Esport            | W   | 0.806      | 0.333        | 0.002 (0.001)    | 0.313 (0.084)    | 0 (0.000) |    12.86 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |
|            1 |     2676 | 2024-03-05 | FALKE ESPORTS        | W   | 0.792      | 0.333        | 0.000 (0.000)    | 0.021 (0.006)    | 0 (0.000) |     7.64 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($273.69)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
