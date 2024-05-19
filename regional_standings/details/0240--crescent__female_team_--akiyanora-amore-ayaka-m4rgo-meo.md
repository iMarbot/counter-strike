### Roster Details<br />
Team Name: Crescent (Female team)<br />
Roster: akiyanora, amore, ayaka, M4rgo, meo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [240](../standings_global.md)<br />
Regional Rank: [154]( ../standings_europe.md)<br />
Final Rank Value:  672.7<br />
<br />
Final Rank Value (672.7) = Starting Rank Value (689.3) + Head To Head Adjustments (-16.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 689.3
- 400 + ( ( 0.146 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 689.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |       18 | 2024-05-05 | Team Pigeons               | L   | 1.000      | -            | -                | -                | -         |    -5.14 | akiyanora, amore, ayaka, M4rgo, meo    |
|           14 |       50 | 2024-05-04 | Team Spirit Female         | W   | 1.000      | 0.250        | 0.011 (0.003)    | 0.205 (0.051)    | 0 (0.000) |    15.13 | akiyanora, amore, ayaka, M4rgo, meo    |
|           13 |       58 | 2024-05-04 | NOFEAR5                    | W   | 1.000      | 0.250        | 0.018 (0.004)    | 0.017 (0.004)    | 0 (0.000) |    19.07 | akiyanora, amore, ayaka, M4rgo, meo    |
|           12 |      375 | 2024-04-27 | Team Spirit Female         | L   | 1.000      | -            | -                | -                | -         |   -15.56 | akiyanora, amore, ayaka, M4rgo, meo    |
|           11 |      383 | 2024-04-27 | VForVictory                | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.97 | akiyanora, amore, ayaka, M4rgo, meo    |
|           10 |      816 | 2024-04-19 | NAVI Javelins              | L   | 1.000      | -            | -                | -                | -         |    -6.87 | akiyanora, amore, ayaka, M4rgo, meo    |
|            9 |     1168 | 2024-04-11 | Fearless Cheetahs          | L   | 1.000      | -            | -                | -                | -         |   -13.14 | kr4sy, Ksu, t4tty, victoria, vilga     |
|            8 |     1233 | 2024-04-10 | Permitta W                 | L   | 1.000      | -            | -                | -                | -         |   -23.11 | amyb, Gaba, Mrs_Fire, pavlla, Tynka    |
|            7 |     1336 | 2024-04-08 | Team Pigeons               | L   | 1.000      | -            | -                | -                | -         |    -7.07 | akiyanora, amore, ayaka, M4rgo, meo    |
|            6 |     1693 | 2024-03-28 | 1win Gang                  | W   | 0.945      | 0.331        | 0.007 (0.002)    | 0.061 (0.019)    | 0 (0.000) |    12.03 | akiyanora, amore, ayaka, M4rgo, meo    |
|            5 |     2021 | 2024-03-20 | Team Spirit Female         | L   | 0.892      | -            | -                | -                | -         |   -13.69 | akiyanora, amore, ayaka, M4rgo, meo    |
|            4 |     3165 | 2024-02-24 | NAVI Javelins              | L   | 0.724      | -            | -                | -                | -         |    -7.03 | akiyanora, amore, ayaka, M4rgo, meo    |
|            3 |     3175 | 2024-02-24 | 1win Gang                  | W   | 0.723      | 0.143        | 0.007 (0.001)    | 0.061 (0.006)    | 0 (0.000) |     9.77 | Deylary, f6tal, miu_u, Potya, unknxwn  |
|            2 |     3445 | 2024-02-18 | FORZE Ladies               | W   | 0.685      | 0.143        | 0.002 (0.000)    | 0.057 (0.006)    | 0 (0.000) |     9.56 | k175un4, mikeri, sosya, Stormy, wieenn |
|            1 |     3480 | 2024-02-17 | Questionmark (Female team) | W   | 0.679      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.44 | ASTRA, IRBITka, Missy, oxycet, twix    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,300.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $250.00        | $250.00         |
| 2024-04-21 |      1.000 | $1,050.00      | $1,050.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
