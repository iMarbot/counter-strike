### Roster Details<br />
Team Name: Crescent<br />
Roster: akiyanora, amore, ayaka, M4rgo, meo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [228](../standings_global.md)<br />
Regional Rank: [153]( ../standings_europe.md)<br />
Final Rank Value:  703.5<br />
<br />
Final Rank Value (703.5) = Starting Rank Value (694.2) + Head To Head Adjustments (9.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.2
- 400 + ( ( 0.145 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 694.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      203 | 2024-05-26 | NIP Impact         | W   | 1.000      | 0.250        | 0.007 (0.002)    | 0.303 (0.076)    | 0 (0.000) |    17.85 | akiyanora, amore, ayaka, M4rgo, meo          |
|           20 |      219 | 2024-05-26 | wwaves             | W   | 1.000      | 0.250        | 0.000 (0.000)    | 0.051 (0.013)    | 0 (0.000) |     8.01 | akiyanora, amore, ayaka, M4rgo, meo          |
|           19 |      269 | 2024-05-25 | raregodz           | W   | 1.000      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.49 | akiyanora, amore, ayaka, M4rgo, meo          |
|           18 |      867 | 2024-05-18 | Team Pigeons       | L   | 1.000      | -            | -                | -                | -         |    -6.97 | akiyanora, amore, ayaka, M4rgo, meo          |
|           17 |      915 | 2024-05-18 | ex-FORZE Ladies    | W   | 1.000      | 0.281        | 0.005 (0.001)    | 0.164 (0.046)    | 0 (0.000) |    16.57 | akiyanora, amore, ayaka, M4rgo, meo          |
|           16 |     1769 | 2024-05-05 | Team Pigeons       | L   | 1.000      | -            | -                | -                | -         |    -6.94 | akiyanora, amore, ayaka, M4rgo, meo          |
|           15 |     1809 | 2024-05-04 | Team Spirit Female | W   | 1.000      | 0.250        | 0.005 (0.001)    | 0.216 (0.054)    | 0 (0.000) |    15.18 | akiyanora, amore, ayaka, M4rgo, meo          |
|           14 |     1817 | 2024-05-04 | NOFEAR5            | W   | 1.000      | 0.250        | 0.002 (0.001)    | 0.002 (0.001)    | 0 (0.000) |    15.51 | akiyanora, amore, ayaka, M4rgo, meo          |
|           13 |     2195 | 2024-04-27 | Team Spirit Female | L   | 0.982      | -            | -                | -                | -         |   -15.32 | akiyanora, amore, ayaka, M4rgo, meo          |
|           12 |     2206 | 2024-04-27 | VForVictory        | W   | 0.982      | -            | -                | -                | 0 (0.000) |     6.01 | akiyanora, amore, ayaka, M4rgo, meo          |
|           11 |     2694 | 2024-04-19 | NAVI Javelins      | L   | 0.930      | -            | -                | -                | -         |    -8.03 | akiyanora, amore, ayaka, M4rgo, meo          |
|           10 |     3110 | 2024-04-11 | Fearless Cheetahs  | L   | 0.877      | -            | -                | -                | -         |   -12.36 | kr4sy, Ksu, t4tty, victoria, vilga           |
|            9 |     3186 | 2024-04-10 | Permitta W         | L   | 0.869      | -            | -                | -                | -         |   -20.23 | amyb, Gaba, Mrs_Fire, pavlla, Tynka          |
|            8 |     3297 | 2024-04-08 | Team Pigeons       | L   | 0.856      | -            | -                | -                | -         |    -8.47 | akiyanora, amore, ayaka, M4rgo, meo          |
|            7 |     3737 | 2024-03-28 | 1win Gang          | W   | 0.784      | 0.331        | 0.004 (0.001)    | 0.118 (0.031)    | 0 (0.000) |    10.53 | akiyanora, amore, ayaka, M4rgo, meo          |
|            6 |     4129 | 2024-03-20 | Team Spirit Female | L   | 0.731      | -            | -                | -                | -         |   -11.57 | akiyanora, amore, ayaka, M4rgo, meo          |
|            5 |     5548 | 2024-02-24 | NAVI Javelins      | L   | 0.563      | -            | -                | -                | -         |    -6.76 | akiyanora, amore, ayaka, M4rgo, meo          |
|            4 |     5560 | 2024-02-24 | 1win Gang          | W   | 0.562      | 0.143        | 0.004 (0.000)    | 0.118 (0.010)    | 0 (0.000) |     7.63 | Deylary, f6tal, miu_u, Potya, unknxwn        |
|            3 |     5872 | 2024-02-18 | ex-FORZE Ladies    | W   | 0.524      | 0.143        | 0.005 (0.000)    | 0.164 (0.012)    | 0 (0.000) |     7.96 | k175un4, mikeri, sosya, Stormy, wieenn       |
|            2 |     5923 | 2024-02-17 | Questionmark       | W   | 0.518      | 0.143        | 0.000 (0.000)    | 0.021 (0.002)    | -         |     6.51 | ASTRA, IRBITka, Missy, oxycet, twix          |
|            1 |     6094 | 2024-02-14 | more whiskey       | L   | 0.497      | -            | -                | -                | -         |   -11.26 | aiveri, Hikomi, takitaki, turboxgirl, v1spel |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,990.94)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-26 |      1.000 | $750.00        | $750.00         |
| 2024-05-05 |      1.000 | $250.00        | $250.00         |
| 2024-04-21 |      0.944 | $1,050.00      | $990.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
