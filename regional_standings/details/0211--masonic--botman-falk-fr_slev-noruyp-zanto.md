### Roster Details<br />
Team Name: MASONIC<br />
Roster: Botman, Falk, Frøslev, Noruyp, Zanto<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [211](../standings_global.md)<br />
Regional Rank: [142]( ../standings_europe.md)<br />
Final Rank Value:  716.6<br />
<br />
Final Rank Value (716.6) = Starting Rank Value (865.8) + Head To Head Adjustments (-149.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.364[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.028[<sup>2</sup>](#table1)
- LAN Wins: 0.298[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.8
- 400 + ( ( 0.229 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 865.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |       58 | 2024-05-29 | Heimo Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.22 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           18 |       90 | 2024-05-29 | CYBERSHOKE Esports   | L   | 1.000      | -            | -                | -                | -         |   -13.26 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           17 |      222 | 2024-05-26 | Necrotic Esports     | L   | 1.000      | -            | -                | -                | -         |   -24.16 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           16 |      256 | 2024-05-25 | UNiTY esports        | L   | 1.000      | -            | -                | -                | -         |   -11.83 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           15 |      555 | 2024-05-21 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -16.75 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           14 |      974 | 2024-05-17 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -22.18 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           13 |     1105 | 2024-05-16 | EYEBALLERS           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.508 (0.073)    | 0 (0.000) |    20.47 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           12 |     1182 | 2024-05-15 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -24.14 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           11 |     1273 | 2024-05-14 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -15.79 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           10 |     1317 | 2024-05-13 | BRUTE                | W   | 1.000      | 0.354        | 0.000 (0.000)    | 0.157 (0.055)    | 0 (0.000) |     4.67 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            9 |     1582 | 2024-05-09 | Astralis Talent      | L   | 1.000      | -            | -                | -                | -         |   -19.14 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            8 |     1655 | 2024-05-08 | Viperio              | L   | 1.000      | -            | -                | -                | -         |   -19.81 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            7 |     1786 | 2024-05-05 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -3.04 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            6 |     2509 | 2024-04-21 | Astralis Talent      | W   | 0.942      | 0.143        | 0.012 (0.002)    | 0.452 (0.061)    | 1 (0.942) |    14.02 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            5 |     2529 | 2024-04-21 | Copenhagen Wolves    | W   | 0.941      | 0.143        | 0.000 (0.000)    | 0.309 (0.042)    | 1 (0.941) |     6.64 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            4 |     2560 | 2024-04-20 | XI Esport            | W   | 0.937      | 0.143        | 0.001 (0.000)    | 0.277 (0.037)    | 1 (0.937) |     7.46 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            3 |     3021 | 2024-04-13 | Esport Harte         | L   | 0.890      | -            | -                | -                | -         |   -23.70 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            2 |     3027 | 2024-04-13 | TOOMUCHVIDEOGAMES    | W   | 0.890      | 0.143        | 0.000 (0.000)    | 0.101 (0.013)    | 0 (0.000) |     3.72 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            1 |     3035 | 2024-04-13 | Kronjyllands Esport  | W   | 0.890      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     2.83 | Botman, Falk, Frøslev, Noruyp, Zanto |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,383.14)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
