### Roster Details<br />
Team Name: MASONIC<br />
Roster: Botman, Falk, Frøslev, Noruyp, Zanto<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [207](../standings_global.md)<br />
Regional Rank: [139]( ../standings_europe.md)<br />
Final Rank Value:  717.7<br />
<br />
Final Rank Value (717.7) = Starting Rank Value (865.6) + Head To Head Adjustments (-147.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.364[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.029[<sup>2</sup>](#table1)
- LAN Wins: 0.298[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 865.6
- 400 + ( ( 0.229 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 865.6


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
|           19 |       60 | 2024-05-29 | Heimo Esports        | L   | 1.000      | -            | -                | -                | -         |   -15.19 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           18 |       97 | 2024-05-29 | CYBERSHOKE Esports   | L   | 1.000      | -            | -                | -                | -         |   -13.44 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           17 |      230 | 2024-05-26 | Necrotic Esports     | L   | 1.000      | -            | -                | -                | -         |   -24.20 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           16 |      264 | 2024-05-25 | UNiTY esports        | L   | 1.000      | -            | -                | -                | -         |   -12.07 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           15 |      566 | 2024-05-21 | Natus Vincere Junior | L   | 1.000      | -            | -                | -                | -         |   -16.18 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           14 |      986 | 2024-05-17 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -21.86 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           13 |     1115 | 2024-05-16 | EYEBALLERS           | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.508 (0.073)    | 0 (0.000) |    20.14 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           12 |     1192 | 2024-05-15 | Copenhagen Wolves    | L   | 1.000      | -            | -                | -                | -         |   -23.82 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           11 |     1284 | 2024-05-14 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -16.28 | Botman, Falk, Frøslev, Noruyp, Zanto |
|           10 |     1329 | 2024-05-13 | BRUTE                | W   | 1.000      | 0.354        | 0.000 (0.000)    | 0.157 (0.055)    | 0 (0.000) |     4.67 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            9 |     1598 | 2024-05-09 | Astralis Talent      | L   | 1.000      | -            | -                | -                | -         |   -18.99 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            8 |     1673 | 2024-05-08 | Viperio              | L   | 1.000      | -            | -                | -                | -         |   -19.76 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            7 |     1809 | 2024-05-05 | Sashi Esport         | L   | 1.000      | -            | -                | -                | -         |    -3.06 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            6 |     2562 | 2024-04-21 | Astralis Talent      | W   | 0.942      | 0.143        | 0.012 (0.002)    | 0.452 (0.061)    | 1 (0.942) |    14.08 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            5 |     2582 | 2024-04-21 | Copenhagen Wolves    | W   | 0.941      | 0.143        | 0.000 (0.000)    | 0.387 (0.052)    | 1 (0.941) |     7.65 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            4 |     2613 | 2024-04-20 | XI Esport            | W   | 0.937      | 0.143        | 0.001 (0.000)    | 0.277 (0.037)    | 1 (0.937) |     7.54 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            3 |     3087 | 2024-04-13 | Esport Harte         | L   | 0.890      | -            | -                | -                | -         |   -23.70 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            2 |     3093 | 2024-04-13 | TOOMUCHVIDEOGAMES    | W   | 0.890      | 0.143        | 0.000 (0.000)    | 0.101 (0.013)    | 0 (0.000) |     3.74 | Botman, Falk, Frøslev, Noruyp, Zanto |
|            1 |     3101 | 2024-04-13 | Kronjyllands Esport  | W   | 0.890      | 0.143        | 0.000 (0.000)    | 0.028 (0.003)    | 0 (0.000) |     2.83 | Botman, Falk, Frøslev, Noruyp, Zanto |

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
