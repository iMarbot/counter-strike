### Roster Details<br />
Team Name: Martians<br />
Roster: bpg, impax, kindg, shine, spankeer<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [314](../standings_global.md)<br />
Regional Rank: [73]( ../standings_americas.md)<br />
Final Rank Value:  595.2<br />
<br />
Final Rank Value (595.2) = Starting Rank Value (636.9) + Head To Head Adjustments (-41.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 636.9
- 400 + ( ( 0.119 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 636.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      169 | 2024-05-01 | Corinthians Esports    | L   | 1.000      | -            | -                | -                | -         |   -13.90 | bpg, impax, kindg, shine, spankeer      |
|           12 |      184 | 2024-05-01 | MIBR Academy           | L   | 1.000      | -            | -                | -                | -         |   -11.23 | bpg, impax, kindg, shine, spankeer      |
|           11 |     1879 | 2024-03-23 | 2024                   | W   | 0.913      | 0.143        | 0.001 (0.000)    | 0.130 (0.017)    | 0 (0.000) |    14.17 | DANVIET, farias, Lineko, PremiuM, xns   |
|           10 |     1887 | 2024-03-23 | Corinthians Esports    | L   | 0.913      | -            | -                | -                | -         |   -11.28 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     1893 | 2024-03-23 | MIBR Female            | W   | 0.912      | 0.143        | 0.027 (0.004)    | 0.199 (0.026)    | 0 (0.000) |    17.74 | bpg, impax, kindg, shine, spankeer      |
|            8 |     2252 | 2024-03-14 | Bounty Hunters Esports | L   | 0.852      | -            | -                | -                | -         |   -16.06 | cAnnon, impax, kindg, shine, spankeer   |
|            7 |     2359 | 2024-03-12 | Intense Game           | L   | 0.840      | -            | -                | -                | -         |    -8.15 | bsd, ckzao, diozera, mxa, Roz           |
|            6 |     3134 | 2024-02-24 | CSGONET                | W   | 0.726      | 0.143        | 0.000 (0.000)    | 0.032 (0.003)    | 0 (0.000) |     6.84 | cAnnon, impax, kindg, shine, spankeer   |
|            5 |     3146 | 2024-02-24 | Myth e-Sports          | L   | 0.725      | -            | -                | -                | -         |   -11.37 | crownzera, Farw, MyRoN, nz1, zhoki      |
|            4 |     4240 | 2024-01-27 | LA RUGONETA            | L   | 0.540      | -            | -                | -                | -         |   -10.45 | abizz, BK1, KAISER, naz, relentless     |
|            3 |     5344 | 2023-12-17 | Dusty Roots            | L   | 0.266      | -            | -                | -                | -         |    -3.74 | cAnnon, impax, kindg, shine, spankeer   |
|            2 |     5428 | 2023-12-16 | Rocket.GG              | W   | 0.260      | 0.143        | 0.001 (0.000)    | 0.070 (0.003)    | 0 (0.000) |     4.01 | cAnnon, impax, kindg, shine, spankeer   |
|            1 |     5432 | 2023-12-16 | Bulls 95               | W   | 0.260      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.71 | cAnnon, impax, kindg, shine, spankeer   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($143.65)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-26 |      0.934 | $130.68        | $122.00         |
| 2023-12-17 |      0.266 | $81.37         | $21.65          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
