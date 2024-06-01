### Roster Details<br />
Team Name: L&G<br />
Roster: crickey, kr1vda, OneUn1que, rjy, somnium<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [433](../standings_global.md)<br />
Regional Rank: [262]( ../standings_europe.md)<br />
Final Rank Value:  489.4<br />
<br />
Final Rank Value (489.4) = Starting Rank Value (519.5) + Head To Head Adjustments (-30.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.059<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 519.5
- 400 + ( ( 0.059 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 519.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     5166 | 2024-03-02 | BLEED Esports        | L   | 0.611      | -            | -                | -                | -         |    -0.33 | crickey, kr1vda, OneUn1que, rjy, somnium     |
|           18 |     5273 | 2024-02-29 | Passion UA           | L   | 0.597      | -            | -                | -                | -         |    -1.56 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           17 |     5324 | 2024-02-28 | Copenhagen Wolves    | L   | 0.590      | -            | -                | -                | -         |    -6.50 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           16 |     5547 | 2024-02-24 | Nexus Gaming         | L   | 0.563      | -            | -                | -                | -         |    -1.66 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           15 |     5712 | 2024-02-21 | V1dar Gaming         | L   | 0.544      | -            | -                | -                | -         |    -4.72 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           14 |     5819 | 2024-02-19 | RoundsGG             | L   | 0.531      | -            | -                | -                | -         |    -6.45 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           13 |     5994 | 2024-02-16 | ILIN                 | L   | 0.510      | -            | -                | -                | -         |    -7.09 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           12 |     6044 | 2024-02-15 | GUN5 Esports         | L   | 0.504      | -            | -                | -                | -         |    -7.22 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           11 |     6332 | 2024-02-08 | Grindas              | W   | 0.457      | 0.371        | 0.000 (0.000)    | 0.030 (0.005)    | 0 (0.000) |     6.53 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           10 |     6357 | 2024-02-07 | DMS                  | L   | 0.451      | -            | -                | -                | -         |    -3.55 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            9 |     6404 | 2024-02-05 | Gaimin Gladiators    | L   | 0.438      | -            | -                | -                | -         |    -0.23 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            8 |     6425 | 2024-02-05 | Sashi Esport         | L   | 0.437      | -            | -                | -                | -         |    -0.65 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            7 |     6537 | 2024-02-03 | ex-sYnck             | L   | 0.424      | -            | -                | -                | -         |    -3.25 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            6 |     6545 | 2024-02-03 | HyperSpirit          | W   | 0.423      | 0.143        | 0.004 (0.000)    | 0.356 (0.022)    | 0 (0.000) |    10.37 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            5 |     6642 | 2024-02-02 | Team Secret          | L   | 0.415      | -            | -                | -                | -         |    -4.80 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            4 |     6769 | 2024-01-30 | MOUZ NXT             | L   | 0.396      | -            | -                | -                | -         |    -0.46 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            3 |     7669 | 2024-01-16 | The Witchers         | L   | 0.304      | -            | -                | -                | -         |    -2.44 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            2 |     8221 | 2024-01-05 | Natus Vincere Junior | L   | 0.230      | -            | -                | -                | -         |    -1.37 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            1 |     8313 | 2023-12-28 | Passion UA           | W   | 0.176      | 0.354        | 0.057 (0.004)    | 1.000 (0.062)    | 0 (0.000) |     5.21 | crickey, jackast, kr1vda, OneUn1que, somnium |

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
