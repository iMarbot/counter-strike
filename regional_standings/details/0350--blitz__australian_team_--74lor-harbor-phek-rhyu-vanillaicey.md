### Roster Details<br />
Team Name: Blitz (Australian team)<br />
Roster: 74LOR, harbor, Phek, Rhyu, vanillaicey<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [350](../standings_global.md)<br />
Regional Rank: [56]( ../standings_asia.md)<br />
Final Rank Value:  492.1<br />
<br />
Final Rank Value (492.1) = Starting Rank Value (482.7) + Head To Head Adjustments (9.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.164[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.042<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 482.7
- 400 + ( ( 0.042 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 482.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      969 | 2024-04-17 | DXA Esports                      | L   | 1.000      | -            | -                | -                | -         |    -8.46 | 74LOR, harbor, Phek, Rhyu, vanillaicey     |
|           12 |     1998 | 2024-03-21 | Altered Edge                     | L   | 0.896      | -            | -                | -                | -         |    -8.20 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           11 |     2229 | 2024-03-15 | Arcade Esports (Australian team) | W   | 0.856      | 0.270        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.00 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|           10 |     2344 | 2024-03-13 | Underground Esports Club         | W   | 0.843      | 0.270        | 0.000 (0.000)    | 0.112 (0.026)    | 0 (0.000) |    15.54 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|            9 |     2544 | 2024-03-08 | MANTRA                           | L   | 0.810      | -            | -                | -                | -         |    -6.36 | deStiny, Phek, rev, Rhyu, vanillaicey      |
|            8 |     3383 | 2024-02-20 | Arcade Esports (Australian team) | W   | 0.696      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.22 | harbor, HudzM, JiNxZiE, mag1c, PearL       |
|            7 |     3701 | 2024-02-12 | Jehovah witness                  | L   | 0.649      | -            | -                | -                | -         |    -9.30 | badge, DickStacy, mswag, stevie, Texta     |
|            6 |     4403 | 2024-01-24 | Rooster                          | L   | 0.516      | -            | -                | -                | -         |    -2.09 | 74LOR, COOOOOOFFEE, Phek, vanillaicey, ws  |
|            5 |     4407 | 2024-01-24 | Antic Esports                    | W   | 0.516      | 0.143        | 0.000 (0.000)    | 0.068 (0.005)    | 0 (0.000) |    10.33 | 74LOR, COOOOOOFFEE, Phek, vanillaicey, ws  |
|            4 |     4762 | 2024-01-17 | PatatiPatata                     | L   | 0.469      | -            | -                | -                | -         |    -9.17 | Dronerin, LeveL, MONSTRAOOO, RMZER4, shnzt |
|            3 |     4855 | 2024-01-14 | StevosFirstCS2                   | W   | 0.456      | 0.143        | 0.000 (0.000)    | 0.032 (0.002)    | 0 (0.000) |     7.41 | 74LOR, Phek, sivart, vanillaicey, ws       |
|            2 |     4908 | 2024-01-12 | DXA Esports                      | L   | 0.442      | -            | -                | -                | -         |    -2.75 | 74LOR, Phek, sivart, vanillaicey, ws       |
|            1 |     4960 | 2024-01-11 | The Edgers                       | W   | 0.435      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.26 | denz, E1F, r1ley, Tandoura, YBN fOReMan    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
