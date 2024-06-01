### Roster Details<br />
Team Name: ALLINNERS<br />
Roster: demente, ismailz, kumao, molodoy, weaveR<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [265](../standings_global.md)<br />
Regional Rank: [169]( ../standings_europe.md)<br />
Final Rank Value:  669.0<br />
<br />
Final Rank Value (669.0) = Starting Rank Value (667.6) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 667.6
- 400 + ( ( 0.131 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 667.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |       56 | 2024-05-29 | ZennoX             | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.71 | demente, ismailz, kumao, molodoy, weaveR   |
|           11 |      373 | 2024-05-23 | YamatoCYBER        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.33 | demente, kumao, molodoy, singulier, wEAVER |
|           10 |      376 | 2024-05-23 | EVOLUTION          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.110 (0.016)    | 0 (0.000) |     6.78 | demente, kumao, molodoy, singulier, wEAVER |
|            9 |      377 | 2024-05-23 | AlaDos             | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |    10.14 | demente, kumao, molodoy, singulier, wEAVER |
|            8 |      873 | 2024-05-18 | StrikeArena        | L   | 1.000      | -            | -                | -                | -         |   -21.58 | d1aszz, demente, kumao, molodoy, weaveR    |
|            7 |      887 | 2024-05-18 | naChille           | L   | 1.000      | -            | -                | -                | -         |   -17.63 | d1aszz, demente, kumao, molodoy, weaveR    |
|            6 |     1385 | 2024-05-12 | TOR                | L   | 1.000      | -            | -                | -                | -         |   -10.63 | d1aszz, demente, kumao, molodoy, weaveR    |
|            5 |     1943 | 2024-05-01 | Inazuma 6          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.02 | d1aszz, demente, kumao, molodoy, weaveR    |
|            4 |     2109 | 2024-04-28 | TOR                | L   | 0.990      | -            | -                | -                | -         |   -11.56 | d1aszz, demente, kumao, molodoy, weaveR    |
|            3 |     2256 | 2024-04-26 | CUBE BY SND        | W   | 0.977      | 0.143        | 0.002 (0.000)    | 0.027 (0.004)    | 0 (0.000) |    13.39 | d1aszz, demente, kumao, molodoy, weaveR    |
|            2 |     2262 | 2024-04-26 | TOR                | W   | 0.976      | 0.143        | 0.014 (0.002)    | 0.196 (0.027)    | 0 (0.000) |    19.47 | d1aszz, demente, kumao, molodoy, weaveR    |
|            1 |     7676 | 2024-01-16 | ex-Anonymo Esports | L   | 0.304      | -            | -                | -                | -         |    -3.97 | alkarenn, demente, ismailz, kumao, wEAVER  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,592.31)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-12 |      1.000 | $1,137.64      | $1,137.64       |
| 2024-05-11 |      1.000 | $454.67        | $454.67         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
