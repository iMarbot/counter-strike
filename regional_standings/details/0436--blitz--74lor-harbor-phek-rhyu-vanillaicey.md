### Roster Details<br />
Team Name: Blitz<br />
Roster: 74LOR, harbor, Phek, Rhyu, vanillaicey<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [436](../standings_global.md)<br />
Regional Rank: [65]( ../standings_asia.md)<br />
Final Rank Value:  485.8<br />
<br />
Final Rank Value (485.8) = Starting Rank Value (478.3) + Head To Head Adjustments (7.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.150[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.038<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 478.3
- 400 + ( ( 0.038 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 478.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     2869 | 2024-04-17 | DXA Esports              | L   | 0.915      | -            | -                | -                | -         |    -7.93 | 74LOR, harbor, Phek, Rhyu, vanillaicey     |
|           17 |     2877 | 2024-04-17 | really weird             | W   | 0.915      | 0.143        | 0.000 (0.000)    | 0.055 (0.007)    | 0 (0.000) |    10.90 | 74LOR, harbor, Phek, Rhyu, vanillaicey     |
|           16 |     4104 | 2024-03-21 | Altered Edge             | L   | 0.735      | -            | -                | -                | -         |    -6.94 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           15 |     4185 | 2024-03-19 | really weird             | W   | 0.722      | 0.270        | 0.000 (0.000)    | 0.055 (0.011)    | 0 (0.000) |     9.04 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           14 |     4390 | 2024-03-15 | Arcade Esports           | W   | 0.695      | 0.270        | 0.000 (0.000)    | 0.018 (0.003)    | 0 (0.000) |     8.50 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           13 |     4519 | 2024-03-13 | Underground Esports Club | W   | 0.682      | 0.270        | 0.000 (0.000)    | 0.070 (0.013)    | 0 (0.000) |    13.29 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           12 |     4767 | 2024-03-08 | MANTRA                   | L   | 0.648      | -            | -                | -                | -         |    -5.08 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           11 |     5791 | 2024-02-20 | Vantage Esports          | L   | 0.535      | -            | -                | -                | -         |    -4.38 | 74LOR, Mega2F, Phek, rev, vanillaicey      |
|           10 |     5799 | 2024-02-20 | Arcade Esports           | W   | 0.535      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     6.86 | harbor, HudzM, JiNxZiE, mag1c, PearL       |
|            9 |     5912 | 2024-02-17 | gjdpdffileljhkj          | L   | 0.521      | -            | -                | -                | -         |    -9.70 | BaN4na, Kiyo, NeoAgricola, rzar, sunshinez |
|            8 |     6181 | 2024-02-12 | Jehovah witness          | L   | 0.488      | -            | -                | -                | -         |    -6.96 | badge, DickStacy, mswag, stevie, Texta     |
|            7 |     7141 | 2024-01-24 | Rooster                  | L   | 0.355      | -            | -                | -                | -         |    -1.55 | 74LOR, COOOOOOFFEE, Phek, vanillaicey, ws  |
|            6 |     7147 | 2024-01-24 | Antic Esports            | W   | 0.355      | 0.143        | 0.000 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     5.59 | 74LOR, COOOOOOFFEE, Phek, vanillaicey, ws  |
|            5 |     7598 | 2024-01-17 | PatatiPatata             | L   | 0.308      | -            | -                | -                | -         |    -5.90 | Dronerin, LeveL, MONSTRAOOO, RMZER4, shnzt |
|            4 |     7719 | 2024-01-15 | sunday school            | L   | 0.295      | -            | -                | -                | -         |    -4.54 | 74LOR, Phek, sivart, vanillaicey, ws       |
|            3 |     7733 | 2024-01-14 | StevosFirstCS2           | W   | 0.295      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     4.79 | 74LOR, Phek, sivart, vanillaicey, ws       |
|            2 |     7811 | 2024-01-12 | DXA Esports              | L   | 0.281      | -            | -                | -                | -         |    -1.82 | 74LOR, Phek, sivart, vanillaicey, ws       |
|            1 |     7884 | 2024-01-11 | The Edgers               | W   | 0.274      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.38 | denz, E1F, r1ley, Tandoura, YBN fOReMan    |

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
