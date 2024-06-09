### Roster Details<br />
Team Name: Team Solid<br />
Roster: AntoN, muSh, oqmty, Rekxs, Wolf<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [393](../standings_global.md)<br />
Regional Rank: [235]( ../standings_europe.md)<br />
Final Rank Value:  569.8<br />
<br />
Final Rank Value (569.8) = Starting Rank Value (627.8) + Head To Head Adjustments (-58.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.176[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 627.8
- 400 + ( ( 0.112 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 627.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1316 | 2024-05-13 | Entropy Future         | L   | 1.000      | -            | -                | -                | -         |   -17.59 | AntoN, muSh, oqmty, Rekxs, Wolf        |
|           11 |     1361 | 2024-05-12 | AKA HERO               | L   | 1.000      | -            | -                | -                | -         |   -14.55 | AntoN, muSh, oqmty, Rekxs, Wolf        |
|           10 |     1854 | 2024-05-04 | mYinsanity             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |     8.30 | AntoN, davesoN, fearz, muSh, rekxs     |
|            9 |     1874 | 2024-05-04 | Lostik                 | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |    11.22 | AntoN, davesoN, fearz, muSh, rekxs     |
|            8 |     2134 | 2024-04-28 | Lausanne-Sport Esports | L   | 0.990      | -            | -                | -                | -         |   -12.44 | AntoN, davesoN, muSh, oqmty, Rekxs     |
|            7 |     2339 | 2024-04-25 | mYinsanity             | W   | 0.971      | 0.143        | 0.001 (0.000)    | 0.124 (0.017)    | 0 (0.000) |    16.75 | AntoN, davesoN, muSh, oqmty, Rekxs     |
|            6 |     2410 | 2024-04-24 | ALTERNATE aTTaX Evo    | L   | 0.964      | -            | -                | -                | -         |   -11.30 | AntoN, muSh, oqmty, Rekxs, Wolf        |
|            5 |     2756 | 2024-04-19 | XPERION NXT            | L   | 0.930      | -            | -                | -                | -         |   -13.02 | AntoN, muSh, oqmty, Rekxs, Wolf        |
|            4 |     3236 | 2024-04-10 | eSports Cologne        | L   | 0.871      | -            | -                | -                | -         |   -17.52 | AntoN, davesoN, muSh, oqmty, Rekxs     |
|            3 |     7559 | 2024-01-20 | mYinsanity             | L   | 0.331      | -            | -                | -                | -         |    -5.20 | DAVEN, Firelegends, JuN1, p3kko, reezk |
|            2 |     7577 | 2024-01-20 | Ayriks Academy         | W   | 0.331      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.31 | Breaker, niox, NoRulezZ, proxi, yaankz |
|            1 |     7584 | 2024-01-20 | Lausanne-Sport Esports | L   | 0.330      | -            | -                | -                | -         |    -4.94 | DexxM, Diviiii, Razzmo, xReal, zed     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($601.97)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-22 |      1.000 | $54.28         | $54.28          |
| 2024-04-28 |      0.990 | $553.06        | $547.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
