### Roster Details<br />
Team Name: TOR<br />
Roster: BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [155](../standings_global.md)<br />
Regional Rank: [108]( ../standings_europe.md)<br />
Final Rank Value:  770.3<br />
<br />
Final Rank Value (770.3) = Starting Rank Value (813.4) + Head To Head Adjustments (-43.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.351[<sup>1</sup>](#table2)
- Bounty Collected: 0.224[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.221[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.4
- 400 + ( ( 0.203 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 813.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           25 |      184 | 2024-05-27 | Aurora Young Blud | L   | 1.000      | -            | -                | -                | -         |   -15.20 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           24 |      261 | 2024-05-25 | ZEROvariant       | L   | 1.000      | -            | -                | -                | -         |   -26.00 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           23 |      489 | 2024-05-22 | Donstu Esports    | L   | 1.000      | -            | -                | -                | -         |   -24.99 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           22 |      564 | 2024-05-21 | 1win Academy      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.075 (0.011)    | 0 (0.000) |     7.91 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           21 |      762 | 2024-05-19 | StrikeArena       | W   | 1.000      | 0.143        | -                | 0.055 (0.008)    | 0 (0.000) |     5.29 | adai, mag1k3Y, maison, mo0n, R3LiFwOw            |
|           20 |      874 | 2024-05-18 | naChille          | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.140 (0.020)    | 0 (0.000) |     8.19 | dukefissura, ice, kade0, mou, rinnn              |
|           19 |      886 | 2024-05-18 | StrikeArena       | W   | 1.000      | 0.143        | -                | 0.055 (0.008)    | 0 (0.000) |     4.75 | adai, mag1k3Y, maison, mo0n, R3LiFwOw            |
|           18 |     1385 | 2024-05-12 | ALLINNERS         | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.191 (0.027)    | 1 (1.000) |    10.63 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           17 |     1469 | 2024-05-11 | naChille          | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.140 (0.020)    | 1 (1.000) |     8.76 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           16 |     2109 | 2024-04-28 | ALLINNERS         | W   | 0.990      | 0.143        | 0.005 (0.001)    | 0.191 (0.027)    | 0 (0.000) |    11.56 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           15 |     2248 | 2024-04-26 | CUBE BY SND       | W   | 0.977      | 0.143        | 0.002 (0.000)    | -                | 0 (0.000) |     9.54 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           14 |     2255 | 2024-04-26 | naChille          | W   | 0.977      | 0.143        | 0.004 (0.001)    | 0.140 (0.020)    | 0 (0.000) |     9.53 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           13 |     2262 | 2024-04-26 | ALLINNERS         | L   | 0.976      | -            | -                | -                | -         |   -19.47 | BLVCKM4GIC, def1zer, forkyz, Pumpkin66, tasman   |
|           12 |     4373 | 2024-03-15 | TEAM MAX          | L   | 0.698      | -            | -                | -                | -         |   -17.37 | BLVCKM4GIC, def1zer, Pumpkin66, tasman, TNDKingg |
|           11 |     4472 | 2024-03-13 | Virtuoso Squad    | W   | 0.685      | 0.333        | -                | 0.063 (0.014)    | -         |     3.49 | hahanz0, Maha, N1ghtMan, sinkieee, V0R4yn        |
|           10 |     4595 | 2024-03-11 | ADEPTS            | L   | 0.671      | -            | -                | -                | -         |    -9.17 | cHeuuuuk, Chuckyy, Oxbrandd, prn, Tarkky         |
|            9 |     4747 | 2024-03-08 | Clownfiesta       | W   | 0.651      | 0.333        | -                | 0.035 (0.008)    | -         |     3.05 | f1nch, Maison, Pepo, SOKER, WorldEdit            |
|            8 |     5867 | 2024-02-18 | CUBE BY SND       | L   | 0.524      | -            | -                | -                | -         |   -11.26 | adai, dosikzz, mag1k3Y, OxygeN, rinn             |
|            7 |     5960 | 2024-02-17 | NoMercy           | W   | 0.515      | 0.143        | 0.000 (0.000)    | -                | -         |     4.92 | baytereQ, clovisz, confiden7, GetZati, m1te      |
|            6 |     8012 | 2024-01-10 | RUSH B            | L   | 0.265      | -            | -                | -                | -         |    -4.70 | BLVCKM4GIC, def1zer, forkyz, tasman, TNDKingg    |
|            5 |     8421 | 2023-12-18 | VaselineWorms     | L   | 0.109      | -            | -                | -                | -         |    -2.16 | aliot, kashl1d, Muk0s, relaxxie, zweih           |
|            4 |     8479 | 2023-12-17 | FORZE Youngsters  | W   | 0.103      | 0.143        | 0.001 (0.000)    | -                | -         |     0.90 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |
|            3 |     8505 | 2023-12-17 | TopTab Club       | W   | 0.102      | -            | -                | -                | -         |     0.51 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |
|            2 |     8643 | 2023-12-16 | LF0               | L   | 0.095      | -            | -                | -                | -         |    -2.26 | HUckLer, lesswill, SP1NT, SUROVIY666, Xerison    |
|            1 |     8759 | 2023-12-15 | Temp              | W   | 0.088      | 0.143        | 0.000 (0.000)    | -                | 1 (0.088) |     0.43 | BLVCKM4GIC, def1zer, ICY, Pumpkin66, TNDKingg    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,248.72)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $2,275.29      | $2,275.29       |
| 2024-05-11 |      1.000 | $1,818.66      | $1,818.66       |
| 2023-12-15 |      0.088 | $1,752.09      | $154.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
