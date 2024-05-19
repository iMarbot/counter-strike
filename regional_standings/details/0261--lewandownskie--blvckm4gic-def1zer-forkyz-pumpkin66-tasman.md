### Roster Details<br />
Team Name: Lewandownskie<br />
Roster: BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [261](../standings_global.md)<br />
Regional Rank: [163]( ../standings_europe.md)<br />
Final Rank Value:  653.8<br />
<br />
Final Rank Value (653.8) = Starting Rank Value (670.4) + Head To Head Adjustments (-16.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.295[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.028[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 670.4
- 400 + ( ( 0.136 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 670.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      414 | 2024-04-26 | CUBE BY SND                  | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.138 (0.020)    | false (0.000) |    17.74 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           17 |      422 | 2024-04-26 | XGOD                         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.056 (0.008)    | false (0.000) |     9.40 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           16 |      429 | 2024-04-26 | ALLINNERS                    | L   | 1.000      | -            | -                | -                | -             |   -20.74 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           15 |     2212 | 2024-03-15 | TEAM MAX (European mix-team) | L   | 0.859      | -            | -                | -                | -             |   -17.54 | BLVCKM4GIC, def1zer, Pumpkin66, tasman, TNDKingg |
|           14 |     2304 | 2024-03-13 | Virtuoso Squad               | W   | 0.846      | 0.333        | 0.000 (0.000)    | 0.063 (0.018)    | false (0.000) |     5.07 | hahanz0, Maha, N1ghtMan, sinkieee, V0R4yn        |
|           13 |     2402 | 2024-03-11 | ADEPTS                       | L   | 0.832      | -            | -                | -                | -             |   -13.04 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky         |
|           12 |     2527 | 2024-03-08 | Clownfiesta                  | W   | 0.812      | 0.333        | 0.000 (0.000)    | 0.029 (0.008)    | false (0.000) |     6.61 | f1nch, Maison, Pepo, SOKER, WorldEdit            |
|           11 |     3442 | 2024-02-18 | CUBE BY SND                  | L   | 0.685      | -            | -                | -                | -             |   -10.33 | Adaikz, dosikzz, mag1k3Y, OxygeN, rinn           |
|           10 |     3508 | 2024-02-17 | NoMercy (Kazakh team)        | W   | 0.676      | 0.143        | 0.001 (0.000)    | 0.027 (0.003)    | false (0.000) |     7.44 | baytereQ, clovisz, confiden7, GetZati, m1te      |
|            9 |     5050 | 2024-01-10 | RUSH B (Russian team)        | L   | 0.426      | -            | -                | -                | -             |    -4.43 | BLVCKM4GIC, def1zer, forkyz, tasman, TNDKingg    |
|            8 |     5330 | 2023-12-18 | VaselineWorms                | L   | 0.270      | -            | -                | -                | -             |    -4.46 | aliot, kashl1d, Muk0s, relaxxie, zweih           |
|            7 |     5374 | 2023-12-17 | FORZE Youngsters             | W   | 0.264      | 0.143        | 0.003 (0.000)    | 0.123 (0.005)    | false (0.000) |     4.34 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |
|            6 |     5397 | 2023-12-17 | TopTab Club                  | W   | 0.263      | 0.143        | -                | 0.065 (0.002)    | false (0.000) |     2.46 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |
|            5 |     5499 | 2023-12-16 | LF0                          | L   | 0.256      | -            | -                | -                | -             |    -4.36 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison    |
|            4 |     5596 | 2023-12-15 | Temp (Kazakh team)           | W   | 0.249      | 0.143        | 0.004 (0.000)    | 0.001 (0.000)    | true (0.249)  |     3.15 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |
|            3 |     6402 | 2023-11-26 | Temp (Kazakh team)           | W   | 0.124      | 0.143        | 0.004 (0.000)    | 0.001 (0.000)    | false (0.000) |     1.60 | mag1k3Y, maison, plushax, smiley, w1nt3r         |
|            2 |     7057 | 2023-11-11 | Temp (Kazakh team)           | W   | 0.025      | 0.143        | 0.004 (0.000)    | 0.001 (0.000)    | false (0.000) |     0.32 | mag1k3Y, maison, plushax, smiley, w1nt3r         |
|            1 |     7071 | 2023-11-11 | HOTLINE                      | W   | 0.024      | 0.143        | 0.000 (0.000)    | -                | -             |     0.22 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($651.84)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-15 |      0.249 | $1,752.09      | $436.97         |
| 2023-11-26 |      0.124 | $1,738.97      | $214.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
