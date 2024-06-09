### Roster Details<br />
Team Name: L&G<br />
Roster: crickey, kr1vda, OneUn1que, rjy, somnium<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [442](../standings_global.md)<br />
Regional Rank: [268]( ../standings_europe.md)<br />
Final Rank Value:  501.1<br />
<br />
Final Rank Value (501.1) = Starting Rank Value (526.1) + Head To Head Adjustments (-25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 526.1
- 400 + ( ( 0.062 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 526.1


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
|           19 |     5314 | 2024-03-02 | BLEED Esports        | L   | 0.611      | -            | -                | -                | -         |    -0.34 | crickey, kr1vda, OneUn1que, rjy, somnium     |
|           18 |     5423 | 2024-02-29 | Passion UA           | L   | 0.597      | -            | -                | -                | -         |    -1.59 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           17 |     5475 | 2024-02-28 | Copenhagen Wolves    | L   | 0.590      | -            | -                | -                | -         |    -6.27 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           16 |     5707 | 2024-02-24 | Nexus Gaming         | L   | 0.563      | -            | -                | -                | -         |    -1.92 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           15 |     5875 | 2024-02-21 | V1dar Gaming         | L   | 0.544      | -            | -                | -                | -         |    -4.66 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           14 |     5990 | 2024-02-19 | RoundsGG             | L   | 0.531      | -            | -                | -                | -         |    -6.18 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           13 |     6169 | 2024-02-16 | ILIN                 | L   | 0.510      | -            | -                | -                | -         |    -7.25 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           12 |     6225 | 2024-02-15 | GUN5 Esports         | L   | 0.504      | -            | -                | -                | -         |    -7.49 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           11 |     6520 | 2024-02-08 | Grannys Knockers     | W   | 0.457      | 0.371        | 0.006 (0.001)    | 0.517 (0.088)    | 0 (0.000) |    11.62 | crickey, jackast, kr1vda, OneUn1que, somnium |
|           10 |     6550 | 2024-02-07 | DMS                  | L   | 0.451      | -            | -                | -                | -         |    -3.44 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            9 |     6602 | 2024-02-05 | Gaimin Gladiators    | L   | 0.438      | -            | -                | -                | -         |    -0.23 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            8 |     6624 | 2024-02-05 | Sashi Esport         | L   | 0.437      | -            | -                | -                | -         |    -0.69 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            7 |     6740 | 2024-02-03 | ex-sYnck             | L   | 0.424      | -            | -                | -                | -         |    -2.86 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            6 |     6748 | 2024-02-03 | HyperSpirit          | W   | 0.423      | 0.143        | 0.004 (0.000)    | 0.356 (0.022)    | 0 (0.000) |    10.26 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            5 |     6847 | 2024-02-02 | Team Secret          | L   | 0.415      | -            | -                | -                | -         |    -4.86 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            4 |     6985 | 2024-01-30 | MOUZ NXT             | L   | 0.396      | -            | -                | -                | -         |    -0.46 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            3 |     7918 | 2024-01-16 | The Witchers         | L   | 0.304      | -            | -                | -                | -         |    -2.50 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            2 |     8476 | 2024-01-05 | Natus Vincere Junior | L   | 0.230      | -            | -                | -                | -         |    -1.41 | crickey, jackast, kr1vda, OneUn1que, somnium |
|            1 |     8570 | 2023-12-28 | Passion UA           | W   | 0.176      | 0.354        | 0.057 (0.004)    | 1.000 (0.062)    | 0 (0.000) |     5.22 | crickey, jackast, kr1vda, OneUn1que, somnium |

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
