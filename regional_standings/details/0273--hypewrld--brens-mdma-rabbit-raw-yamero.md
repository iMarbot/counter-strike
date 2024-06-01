### Roster Details<br />
Team Name: hypewrld<br />
Roster: Brens, MDmA, rabbit, rAW, Yamero<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [273](../standings_global.md)<br />
Regional Rank: [173]( ../standings_europe.md)<br />
Final Rank Value:  659.9<br />
<br />
Final Rank Value (659.9) = Starting Rank Value (710.2) + Head To Head Adjustments (-50.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.266[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.165[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 710.2
- 400 + ( ( 0.152 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 710.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      908 | 2024-05-18 | Necrotic Esports | L   | 1.000      | -            | -                | -                | -         |   -21.85 | Brens, MDmA, rabbit, rAW, Yamero      |
|           16 |     1395 | 2024-05-12 | KUNGI            | L   | 1.000      | -            | -                | -                | -         |   -14.54 | Brens, flAir, rabbit, rAW, Yamero     |
|           15 |     1477 | 2024-05-11 | EC BANGA         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     7.08 | Brens, flAir, rabbit, rAW, Yamero     |
|           14 |     1758 | 2024-05-05 | atpūties         | L   | 1.000      | -            | -                | -                | -         |   -11.57 | Brens, rabbit, rAW, sqreet, Yamero    |
|           13 |     1781 | 2024-05-05 | CyberMAN         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.044 (0.006)    | 1 (1.000) |     5.32 | Brens, rabbit, rAW, sqreet, Yamero    |
|           12 |     2901 | 2024-04-16 | MightyWolves     | W   | 0.911      | 0.143        | 0.000 (0.000)    | 0.075 (0.010)    | 0 (0.000) |     7.17 | Brens, rabbit, rAW, sqreet, Yamero    |
|           11 |     3233 | 2024-04-09 | HAVENs           | W   | 0.864      | 0.143        | 0.000 (0.000)    | 0.040 (0.005)    | 0 (0.000) |     4.36 | Brens, rabbit, rAW, sqreet, Yamero    |
|           10 |     3332 | 2024-04-07 | EC BANGA         | L   | 0.850      | -            | -                | -                | -         |   -19.99 | Brens, rabbit, rAW, sqreet, Yamero    |
|            9 |     3639 | 2024-03-31 | sunshine!        | W   | 0.804      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.46 | Brens, rabbit, rAW, sqreet, Yamero    |
|            8 |     4554 | 2024-03-12 | LusHi            | W   | 0.677      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.21 | Brens, rabbit, rAW, sqreet, Yamero    |
|            7 |     4652 | 2024-03-10 | atpūties         | L   | 0.664      | -            | -                | -                | -         |    -8.89 | Brens, rabbit, rAW, sqreet, Yamero    |
|            6 |     5525 | 2024-02-24 | KUNGI            | L   | 0.564      | -            | -                | -                | -         |    -9.26 | Brens, flairr, rabbit, sqreet, Yamero |
|            5 |     5570 | 2024-02-24 | Wolves eSports   | W   | 0.562      | 0.143        | 0.002 (0.000)    | 0.109 (0.009)    | 1 (0.562) |     6.75 | Brens, flairr, rabbit, sqreet, Yamero |
|            4 |     8784 | 2023-12-14 | AKA HERO         | L   | 0.085      | -            | -                | -                | -         |    -1.68 | Brens, flairr, rabbit, sqreet, yamero |
|            3 |     8839 | 2023-12-13 | ENCE Prospects   | W   | 0.077      | 0.310        | 0.001 (0.000)    | 0.034 (0.001)    | 0 (0.000) |     1.09 | Brens, flairr, rabbit, sqreet, yamero |
|            2 |     8882 | 2023-12-12 | HAVENs           | W   | 0.071      | 0.310        | 0.000 (0.000)    | 0.040 (0.001)    | 0 (0.000) |     0.34 | Brens, flairr, rabbit, sqreet, yamero |
|            1 |     8921 | 2023-12-11 | Kova Gaming      | L   | 0.064      | -            | -                | -                | -         |    -1.32 | Brens, flairr, rabbit, sqreet, yamero |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($527.03)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $215.44        | $215.44         |
| 2024-02-24 |      0.564 | $487.51        | $275.04         |
| 2023-12-17 |      0.104 | $350.00        | $36.56          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
