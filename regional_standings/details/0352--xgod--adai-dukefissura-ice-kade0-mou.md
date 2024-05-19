### Roster Details<br />
Team Name: XGOD<br />
Roster: adai, dukefissura, ice, kade0, mou<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [352](../standings_global.md)<br />
Regional Rank: [219]( ../standings_europe.md)<br />
Final Rank Value:  484.0<br />
<br />
Final Rank Value (484.0) = Starting Rank Value (502.2) + Head To Head Adjustments (-18.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.051<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 502.2
- 400 + ( ( 0.051 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 502.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |       27 | 2024-05-05 | Team PeeP                   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.070 (0.010)    | 0 (0.000) |    14.06 | adai, dukefissura, ice, kade0, mou            |
|           18 |       82 | 2024-05-04 | VP.Prodigy                  | L   | 1.000      | -            | -                | -                | -         |    -4.18 | adai, dukefissura, ice, kade0, mou            |
|           17 |      422 | 2024-04-26 | Lewandownskie               | L   | 1.000      | -            | -                | -                | -         |    -9.40 | adai, dukefissura, ice, kade0, mou            |
|           16 |      428 | 2024-04-26 | CUBE BY SND                 | L   | 1.000      | -            | -                | -                | -         |    -6.77 | adai, dukefissura, ice, kade0, mou            |
|           15 |     1391 | 2024-04-06 | RUSH B (Russian team)       | L   | 1.000      | -            | -                | -                | -         |    -4.28 | adai, dukefissura, ice, kade0, mou            |
|           14 |     2563 | 2024-03-07 | Raptors Esports Club        | L   | 0.806      | -            | -                | -                | -         |    -3.33 | Dosia, dukefissura, ice, kade0, mou           |
|           13 |     4798 | 2024-01-16 | Alliance                    | L   | 0.465      | -            | -                | -                | -         |    -1.50 | Dosia, dukefissura, ice, kade0, mou           |
|           12 |     5097 | 2024-01-09 | 9INE                        | L   | 0.418      | -            | -                | -                | -         |    -5.30 | Dosia, dukefissura, ice, kade0, mou           |
|           11 |     5364 | 2023-12-17 | VP.Prodigy                  | L   | 0.264      | -            | -                | -                | -         |    -1.11 | Dosia, dukefissura, ice, kade0, mou           |
|           10 |     5375 | 2023-12-17 | BebraFPL1                   | W   | 0.264      | 0.143        | 0.001 (0.000)    | 0.013 (0.000)    | 0 (0.000) |     4.36 | bodyaN, klydeep, Maloy24, MoWeL, t1murj4N     |
|            9 |     5485 | 2023-12-16 | LF0                         | L   | 0.257      | -            | -                | -                | -         |    -2.47 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison |
|            8 |     5498 | 2023-12-16 | TopTab Club                 | W   | 0.256      | 0.143        | 0.000 (0.000)    | 0.065 (0.002)    | 0 (0.000) |     4.28 | ADntZ, keembo, maQuein, rezn9, SKYLLLER       |
|            7 |     6241 | 2023-11-29 | Turów Zgorzelec Esport      | L   | 0.146      | -            | -                | -                | -         |    -0.65 | b1elany, darko, gRuChA, kadziu, Markoś        |
|            6 |     6309 | 2023-11-28 | Grindas                     | L   | 0.139      | -            | -                | -                | -         |    -1.08 | Dosia, ice, kade0, mou, ProbLeM               |
|            5 |     6473 | 2023-11-24 | SHIPACHI                    | L   | 0.112      | -            | -                | -                | -         |    -1.94 | Brilliance, F1n3tw, kenhy, Remill, z1k4       |
|            4 |     6703 | 2023-11-18 | Grindas                     | L   | 0.072      | -            | -                | -                | -         |    -0.56 | AwwEzz, BaGyZ, MAGILA, prochas, Sidivo        |
|            3 |     6709 | 2023-11-18 | UNiTY esports (Slovak team) | W   | 0.072      | 0.294        | 0.055 (0.001)    | 0.727 (0.015)    | 0 (0.000) |     2.12 | Dosia, ice, kade0, mou, ProbLeM               |
|            2 |     6783 | 2023-11-17 | INGLORIOUS                  | L   | 0.064      | -            | -                | -                | -         |    -0.34 | Dosia, ice, kade0, mou, ProbLeM               |
|            1 |     7162 | 2023-11-08 | Endpoint                    | L   | 0.006      | -            | -                | -                | -         |    -0.02 | AZUWU, HeavyGod, MiGHTYMAX, sl3nd, Surreal    |

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
