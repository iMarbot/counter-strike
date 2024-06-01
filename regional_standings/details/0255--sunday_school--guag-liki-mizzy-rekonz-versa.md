### Roster Details<br />
Team Name: sunday school<br />
Roster: guag, Liki, mizzy, rekonz, versa<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [255](../standings_global.md)<br />
Regional Rank: [39]( ../standings_asia.md)<br />
Final Rank Value:  679.9<br />
<br />
Final Rank Value (679.9) = Starting Rank Value (667.2) + Head To Head Adjustments (12.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 667.2
- 400 + ( ( 0.131 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 667.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     2221 | 2024-04-26 | Party Astronauts   | L   | 0.980      | -            | -                | -                | -         |    -4.98 | guag, Liki, mizzy, rekonz, versa     |
|           10 |     2295 | 2024-04-25 | Apeks              | L   | 0.972      | -            | -                | -                | -         |    -1.50 | guag, Liki, mizzy, rekonz, versa     |
|            9 |     6004 | 2024-02-16 | KZG                | W   | 0.509      | 0.143        | 0.011 (0.001)    | 0.223 (0.016)    | 0 (0.000) |     9.39 | guag, Liki, mizzy, rekonz, versa     |
|            8 |     6009 | 2024-02-15 | Vantage Esports    | W   | 0.507      | 0.143        | 0.000 (0.000)    | 0.226 (0.016)    | 0 (0.000) |     7.54 | guag, Liki, mizzy, rekonz, versa     |
|            7 |     6067 | 2024-02-15 | KZG                | L   | 0.502      | -            | -                | -                | -         |    -6.49 | guag, Liki, mizzy, rekonz, versa     |
|            6 |     6070 | 2024-02-14 | DXA Esports        | W   | 0.501      | 0.143        | 0.005 (0.000)    | 0.196 (0.014)    | 0 (0.000) |     8.97 | guag, Liki, mizzy, rekonz, versa     |
|            5 |     7152 | 2024-01-23 | Bad News Kangaroos | L   | 0.355      | -            | -                | -                | -         |    -6.36 | gump, mizzy, rekonz, versa, viridian |
|            4 |     7497 | 2024-01-17 | Arcade Esports     | L   | 0.314      | -            | -                | -                | -         |    -4.89 | gump, mizzy, nexar, rekonz, versa    |
|            3 |     7588 | 2024-01-17 | StevosFirstCS2     | W   | 0.308      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     2.55 | gump, mizzy, nexar, rekonz, versa    |
|            2 |     7594 | 2024-01-17 | Altered Edge       | W   | 0.308      | 0.143        | 0.002 (0.000)    | 0.086 (0.004)    | 0 (0.000) |     4.25 | gump, mizzy, nexar, rekonz, versa    |
|            1 |     7736 | 2024-01-14 | Altered Edge       | W   | 0.294      | 0.143        | 0.002 (0.000)    | 0.086 (0.004)    | 0 (0.000) |     4.17 | gump, mizzy, nexar, rekonz, versa    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,976.20)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
