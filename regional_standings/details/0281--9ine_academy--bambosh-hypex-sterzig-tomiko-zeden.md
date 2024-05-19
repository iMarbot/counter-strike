### Roster Details<br />
Team Name: 9INE Academy<br />
Roster: Bambosh, hypex, Sterzig, tomiko, zEden<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [281](../standings_global.md)<br />
Regional Rank: [174]( ../standings_europe.md)<br />
Final Rank Value:  630.2<br />
<br />
Final Rank Value (630.2) = Starting Rank Value (663.2) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.300[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.2
- 400 + ( ( 0.133 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 663.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      492 | 2024-04-25 | V1dar Gaming       | L   | 1.000      | -            | -                | -                | -         |   -14.63 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           15 |      545 | 2024-04-24 | EXO Clan           | L   | 1.000      | -            | -                | -                | -         |    -4.66 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           14 |      739 | 2024-04-20 | System5            | L   | 1.000      | -            | -                | -                | -         |   -19.68 | Chill, keen, P4TriCK, Python, T4gg3D   |
|           13 |      823 | 2024-04-19 | ENTERPRISE esports | L   | 1.000      | -            | -                | -                | -         |    -5.79 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           12 |      934 | 2024-04-17 | Aurora Gaming      | L   | 1.000      | -            | -                | -                | -         |    -0.27 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           11 |     1137 | 2024-04-12 | Permitta Esports   | L   | 1.000      | -            | -                | -                | -         |    -5.66 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           10 |     1174 | 2024-04-11 | AVEZ               | L   | 1.000      | -            | -                | -                | -         |   -16.20 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            9 |     1210 | 2024-04-10 | M1 Gaming          | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.035 (0.005)    | 0 (0.000) |    12.72 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            8 |     1284 | 2024-04-09 | DEEZ NUTS          | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.094 (0.013)    | 0 (0.000) |    16.77 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            7 |     1529 | 2024-04-03 | KOI                | L   | 0.985      | -            | -                | -                | -         |    -2.70 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            6 |     1543 | 2024-04-03 | 9Pandas            | L   | 0.984      | -            | -                | -                | -         |    -1.99 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            5 |     1581 | 2024-04-02 | Apeks Rebels       | W   | 0.977      | 0.289        | 0.005 (0.002)    | 0.071 (0.020)    | 0 (0.000) |    16.33 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            4 |     1622 | 2024-03-31 | Metizport X        | W   | 0.964      | 0.289        | 0.000 (0.000)    | 0.300 (0.084)    | 0 (0.000) |    12.62 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            3 |     1634 | 2024-03-30 | SINNERS Academy    | L   | 0.958      | -            | -                | -                | -         |   -14.29 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            2 |     1687 | 2024-03-28 | TSM                | L   | 0.946      | -            | -                | -                | -         |   -11.49 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            1 |     1842 | 2024-03-25 | EPIC DUDES         | W   | 0.925      | 0.289        | 0.000 (0.000)    | 0.033 (0.009)    | 0 (0.000) |     5.84 | Bambosh, hypex, Sterzig, tomiko, zEden |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($739.38)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
