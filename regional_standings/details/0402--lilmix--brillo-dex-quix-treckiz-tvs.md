### Roster Details<br />
Team Name: Lilmix<br />
Roster: Brillo, dex, quix, treckiz, tvs<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [402](../standings_global.md)<br />
Regional Rank: [241]( ../standings_europe.md)<br />
Final Rank Value:  548.9<br />
<br />
Final Rank Value (548.9) = Starting Rank Value (549.9) + Head To Head Adjustments (-1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.217[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.074<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 549.9
- 400 + ( ( 0.074 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 549.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |     6707 | 2024-01-31 | RUBY                | L   | 0.404      | -            | -                | -                | -         |    -1.35 | Brillo, dex, quix, treckiz, tvs                |
|           23 |     6717 | 2024-01-31 | Soda Gaming         | L   | 0.404      | -            | -                | -                | -         |    -4.86 | Brillo, dex, quix, treckiz, tvs                |
|           22 |     7214 | 2024-01-22 | FORZE Youngsters    | L   | 0.344      | -            | -                | -                | -         |    -4.19 | Brillo, dex, quix, treckiz, tvs                |
|           21 |     7571 | 2024-01-17 | Copenhagen Wolves   | L   | 0.311      | -            | -                | -                | -         |    -3.97 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           20 |     7857 | 2024-01-12 | Permitta Esports    | L   | 0.278      | -            | -                | -                | -         |    -0.90 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           19 |     7873 | 2024-01-12 | Permitta Esports    | L   | 0.276      | -            | -                | -                | -         |    -0.90 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           18 |     7935 | 2024-01-11 | ALTERNATE aTTaX     | W   | 0.270      | 0.143        | 0.004 (0.000)    | 0.103 (0.004)    | 1 (0.270) |     6.18 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           17 |     7940 | 2024-01-11 | Momenta             | W   | 0.270      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 1 (0.270) |     2.52 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           16 |     7953 | 2024-01-11 | Team Spirit Academy | L   | 0.269      | -            | -                | -                | -         |    -2.24 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           15 |     8119 | 2024-01-09 | ex-Anonymo Esports  | L   | 0.257      | -            | -                | -                | -         |    -2.48 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           14 |     8195 | 2024-01-07 | Permitta Esports    | W   | 0.242      | 0.333        | 0.029 (0.002)    | 1.000 (0.081)    | 0 (0.000) |     6.90 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           13 |     8211 | 2024-01-06 | ROSOMAHA            | L   | 0.236      | -            | -                | -                | -         |    -3.26 | Brillo, dex, L00m1, quix, treckiz              |
|           12 |     8244 | 2024-01-03 | Begrip Gaming       | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.317 (0.010)    | 0 (0.000) |     4.03 | Brillo, Chawzyyy, dex, L00m1, quix             |
|           11 |     8255 | 2024-01-03 | RawkAndRawl         | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     2.09 | Brillo, Chawzyyy, dex, L00m1, quix             |
|           10 |     8263 | 2024-01-03 | stcity              | W   | 0.217      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.06 | Brillo, Chawzyyy, dex, L00m1, quix             |
|            9 |     8450 | 2023-12-17 | Metizport           | L   | 0.104      | -            | -                | -                | -         |    -0.28 | Brillo, dex, L00m1, quix, SeBreeZe             |
|            8 |     8468 | 2023-12-17 | Alliance            | L   | 0.103      | -            | -                | -                | -         |    -0.47 | Brillo, dex, L00m1, quix, SeBreeZe             |
|            7 |     8491 | 2023-12-17 | Uruguay3            | W   | 0.102      | 0.143        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.102) |     1.25 | Brillo, dex, L00m1, quix, SeBreeZe             |
|            6 |     8827 | 2023-12-13 | Kappa Bar           | L   | 0.078      | -            | -                | -                | -         |    -1.30 | Brillo, dex, L00m1, quix, SeBreeZe             |
|            5 |     8836 | 2023-12-13 | G-Units             | W   | 0.077      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.73 | Brillo, dex, L00m1, quix, SeBreeZe             |
|            4 |     9267 | 2023-12-05 | flowskola           | L   | 0.025      | -            | -                | -                | -         |    -0.55 | Chawzyyy, magi, MistFire, realyummy, Svedjehed |
|            3 |     9324 | 2023-12-04 | Uruguay3            | L   | 0.019      | -            | -                | -                | -         |    -0.36 | draken, hampus, HugoXD, KALLE, susp            |
|            2 |     9326 | 2023-12-04 | Silencers           | W   | 0.018      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | FakeN, Kuzzel, Pesjov, Pumpli, Slipsyz         |
|            1 |     9328 | 2023-12-04 | Kolon 3             | W   | 0.018      | 0.143        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.17 | 1Knas, Brillo, dezt, treckiz, tvs              |

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
