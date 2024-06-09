### Roster Details<br />
Team Name: ex-Sprout<br />
Roster: cej0t, fNk, podi, raalz, reiko<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [285](../standings_global.md)<br />
Regional Rank: [181]( ../standings_europe.md)<br />
Final Rank Value:  656.5<br />
<br />
Final Rank Value (656.5) = Starting Rank Value (626.5) + Head To Head Adjustments (30.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.218[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 626.5
- 400 + ( ( 0.111 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 626.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     3797 | 2024-03-29 | SINNERS Esports   | L   | 0.791      | -            | -                | -                | -         |    -3.17 | cej0t, fNk, podi, raalz, reiko              |
|           13 |     3835 | 2024-03-28 | Rebels Gaming     | L   | 0.784      | -            | -                | -                | -         |    -1.84 | cej0t, fNk, podi, raalz, reiko              |
|           12 |     4014 | 2024-03-25 | ALTERNATE aTTaX   | L   | 0.764      | -            | -                | -                | -         |    -4.42 | cej0t, fNk, podi, raalz, reiko              |
|           11 |     4286 | 2024-03-19 | B8                | L   | 0.722      | -            | -                | -                | -         |    -1.56 | cptkurtka023, esenthial, npl, OWNER, r1nkle |
|           10 |     5101 | 2024-03-05 | KOI               | L   | 0.631      | -            | -                | -                | -         |    -2.42 | cej0t, raalz, reiko, Sdaim, sL1m3           |
|            9 |     5128 | 2024-03-04 | Team Space        | W   | 0.625      | 0.143        | 0.009 (0.001)    | 0.457 (0.041)    | 0 (0.000) |    14.01 | enzero, fozil, TruNiQ, Vert, waterfaLLZ     |
|            8 |     5163 | 2024-03-04 | TOOMUCHVIDEOGAMES | W   | 0.625      | 0.143        | 0.000 (0.000)    | 0.101 (0.009)    | 0 (0.000) |     6.48 | kaavio, lehtori, N44M4, shaker, VORMISTO    |
|            7 |     5226 | 2024-03-03 | BetBoom Team      | L   | 0.617      | -            | -                | -                | -         |    -0.32 | Buzz, cej0t, raalz, reiko, sL1m3            |
|            6 |     5267 | 2024-03-02 | Team Secret       | W   | 0.612      | 0.143        | 0.000 (0.000)    | 0.230 (0.020)    | 0 (0.000) |    10.29 | anarkez, innocent, Kind0, Maze, Tauson      |
|            5 |     5310 | 2024-03-02 | NOM Esports       | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.360 (0.031)    | 0 (0.000) |    10.44 | dan1, Libido, meztal, MOREE, ultimate       |
|            4 |     9152 | 2023-12-12 | BIG               | L   | 0.070      | -            | -                | -                | -         |    -0.03 | cej0t, fNk, raalz, sL1m3, spooke            |
|            3 |     9197 | 2023-12-11 | Alliance          | W   | 0.064      | 0.384        | 0.004 (0.000)    | 0.529 (0.013)    | 0 (0.000) |     1.59 | cej0t, fNk, raalz, sL1m3, spooke            |
|            2 |     9441 | 2023-12-07 | Gaimin Gladiators | W   | 0.037      | 0.384        | 0.092 (0.001)    | 0.727 (0.010)    | 0 (0.000) |     1.15 | cej0t, fNk, raalz, sL1m3, spooke            |
|            1 |     9521 | 2023-12-06 | Alliance          | L   | 0.029      | -            | -                | -                | -         |    -0.19 | cej0t, fNk, raalz, sL1m3, spooke            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($77.52)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
