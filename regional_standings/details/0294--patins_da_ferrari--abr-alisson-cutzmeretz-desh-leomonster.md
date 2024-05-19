### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: abr, Alisson, CutzMeretz, desh, Leomonster<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [294](../standings_global.md)<br />
Regional Rank: [63]( ../standings_americas.md)<br />
Final Rank Value:  620.1<br />
<br />
Final Rank Value (620.1) = Starting Rank Value (617.5) + Head To Head Adjustments (2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.190[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.110<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 617.5
- 400 + ( ( 0.110 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 617.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     4827 | 2024-01-15 | Imperial Esports          | L   | 0.460      | -            | -                | -                | -             |    -0.06 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           19 |     4865 | 2024-01-14 | Sharks Esports            | L   | 0.453      | -            | -                | -                | -             |    -2.57 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           18 |     5071 | 2024-01-09 | ODDIK                     | L   | 0.419      | -            | -                | -                | -             |    -2.22 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           17 |     5077 | 2024-01-09 | TIMACETA                  | W   | 0.419      | 0.143        | 0.001 (0.000)    | 0.145 (0.009)    | false (0.000) |     7.48 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           16 |     5310 | 2023-12-19 | ODDIK                     | L   | 0.279      | -            | -                | -                | -             |    -1.52 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           15 |     5326 | 2023-12-18 | WINDINGO                  | W   | 0.272      | 0.303        | 0.004 (0.000)    | 0.026 (0.002)    | false (0.000) |     4.79 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           14 |     5462 | 2023-12-16 | ODDIK                     | L   | 0.259      | -            | -                | -                | -             |    -1.37 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           13 |     5564 | 2023-12-15 | Case Esports              | L   | 0.253      | -            | -                | -                | -             |    -2.82 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           12 |     5632 | 2023-12-13 | Arena Jogue Fácil Esports | W   | 0.240      | 0.143        | 0.002 (0.000)    | 0.125 (0.004)    | false (0.000) |     4.43 | abr, Alisson, CutzMeretz, desh, Leomonster     |
|           11 |     6185 | 2023-11-30 | Case Esports              | L   | 0.153      | -            | -                | -                | -             |    -1.75 | abr, Alisson, CutzMeretz, Leomonster, supLexN1 |
|           10 |     6191 | 2023-11-30 | WINDINGO                  | W   | 0.153      | 0.143        | 0.004 (0.000)    | 0.026 (0.001)    | false (0.000) |     2.71 | bichop, nasher, PREDI, restik, Righi           |
|            9 |     6291 | 2023-11-28 | Corinthians Esports       | L   | 0.140      | -            | -                | -                | -             |    -2.18 | DANVIET, Demonos, fREQ, proSHOW, r4ul          |
|            8 |     6307 | 2023-11-28 | Team Solid                | L   | 0.139      | -            | -                | -                | -             |    -0.76 | abr, Alisson, CutzMeretz, Leomonster, supLexN1 |
|            7 |     6460 | 2023-11-24 | Fluxo                     | L   | 0.113      | -            | -                | -                | -             |    -0.31 | chay, Lucaozy, PKL, v$m, zevy                  |
|            6 |     6521 | 2023-11-23 | Sharks Esports            | L   | 0.104      | -            | -                | -                | -             |    -0.58 | doc, drg, gafolo, rdnzao, togs                 |
|            5 |     6922 | 2023-11-14 | Case Esports              | L   | 0.045      | -            | -                | -                | -             |    -0.53 | abr, Alisson, CutzMeretz, Leomonster, supLexN1 |
|            4 |     6993 | 2023-11-12 | Flamengo Esports          | L   | 0.033      | -            | -                | -                | -             |    -0.64 | abr, Alisson, CutzMeretz, Leomonster, supLexN1 |
|            3 |     7083 | 2023-11-10 | Age Sports                | W   | 0.019      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     0.14 | antonini, iDk, Maluk3, pesadelo, prt           |
|            2 |     7112 | 2023-11-09 | 9z Academy                | W   | 0.014      | 0.143        | 0.003 (0.000)    | 0.237 (0.000)    | false (0.000) |     0.24 | divine, MaxOff, perez, slashzz, Tomate         |
|            1 |     7115 | 2023-11-09 | Vex Dragons               | W   | 0.013      | 0.143        | 0.000 (0.000)    | 0.018 (0.000)    | false (0.000) |     0.19 | crownzera, machado, sanc, void, wallz1k        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($141.35)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
