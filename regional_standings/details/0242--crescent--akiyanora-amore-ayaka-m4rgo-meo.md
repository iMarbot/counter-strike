### Roster Details<br />
Team Name: Crescent<br />
Roster: akiyanora, amore, ayaka, M4rgo, meo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [242](../standings_global.md)<br />
Regional Rank: [159]( ../standings_europe.md)<br />
Final Rank Value:  694.0<br />
<br />
Final Rank Value (694.0) = Starting Rank Value (693.7) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.7
- 400 + ( ( 0.145 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 693.7


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
|           22 |      211 | 2024-05-26 | NIP Impact         | W   | 1.000      | 0.250        | 0.007 (0.002)    | 0.303 (0.076)    | 0 (0.000) |    18.20 | akiyanora, amore, ayaka, M4rgo, meo          |
|           21 |      227 | 2024-05-26 | wwaves             | W   | 1.000      | 0.250        | 0.000 (0.000)    | 0.051 (0.013)    | 0 (0.000) |     8.33 | akiyanora, amore, ayaka, M4rgo, meo          |
|           20 |      277 | 2024-05-25 | raregodz           | W   | 1.000      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.75 | akiyanora, amore, ayaka, M4rgo, meo          |
|           19 |      879 | 2024-05-18 | Team Pigeons       | L   | 1.000      | -            | -                | -                | -         |    -7.01 | akiyanora, amore, ayaka, M4rgo, meo          |
|           18 |      927 | 2024-05-18 | ex-FORZE Ladies    | W   | 1.000      | 0.281        | 0.005 (0.001)    | 0.164 (0.046)    | 0 (0.000) |    17.01 | akiyanora, amore, ayaka, M4rgo, meo          |
|           17 |     1792 | 2024-05-05 | Team Pigeons       | L   | 1.000      | -            | -                | -                | -         |    -6.98 | akiyanora, amore, ayaka, M4rgo, meo          |
|           16 |     1832 | 2024-05-04 | Team Spirit Female | W   | 1.000      | 0.250        | 0.005 (0.001)    | 0.216 (0.054)    | 0 (0.000) |    15.63 | akiyanora, amore, ayaka, M4rgo, meo          |
|           15 |     1840 | 2024-05-04 | NOFEAR5            | W   | 1.000      | 0.250        | 0.002 (0.001)    | 0.002 (0.001)    | 0 (0.000) |    15.99 | akiyanora, amore, ayaka, M4rgo, meo          |
|           14 |     2230 | 2024-04-27 | Team Spirit Female | L   | 0.982      | -            | -                | -                | -         |   -14.80 | akiyanora, amore, ayaka, M4rgo, meo          |
|           13 |     2241 | 2024-04-27 | VForVictory        | W   | 0.982      | -            | -                | -                | 0 (0.000) |     6.35 | akiyanora, amore, ayaka, M4rgo, meo          |
|           12 |     2750 | 2024-04-19 | NAVI Javelins      | L   | 0.930      | -            | -                | -                | -         |    -7.66 | akiyanora, amore, ayaka, M4rgo, meo          |
|           11 |     3177 | 2024-04-11 | Fearless Cheetahs  | L   | 0.877      | -            | -                | -                | -         |   -11.54 | kr4sy, Ksu, t4tty, victoria, vilga           |
|           10 |     3261 | 2024-04-10 | Permitta W         | L   | 0.869      | -            | -                | -                | -         |   -19.81 | amyb, Gaba, Mrs_Fire, pavlla, Tynka          |
|            9 |     3378 | 2024-04-08 | Team Pigeons       | L   | 0.856      | -            | -                | -                | -         |    -8.54 | akiyanora, amore, ayaka, M4rgo, meo          |
|            8 |     3831 | 2024-03-28 | 1win Gang          | W   | 0.784      | 0.331        | 0.004 (0.001)    | 0.118 (0.031)    | 0 (0.000) |    11.01 | akiyanora, amore, ayaka, M4rgo, meo          |
|            7 |     4229 | 2024-03-20 | Team Spirit Female | L   | 0.731      | -            | -                | -                | -         |   -11.11 | akiyanora, amore, ayaka, M4rgo, meo          |
|            6 |     4596 | 2024-03-13 | Let Her Cook       | L   | 0.684      | -            | -                | -                | -         |   -14.59 | Joanana, ManeschijnX, meli, RacheLL, suns1de |
|            5 |     5708 | 2024-02-24 | NAVI Javelins      | L   | 0.563      | -            | -                | -                | -         |    -6.77 | akiyanora, amore, ayaka, M4rgo, meo          |
|            4 |     5720 | 2024-02-24 | 1win Gang          | W   | 0.562      | 0.143        | 0.004 (0.000)    | 0.118 (0.010)    | 0 (0.000) |     7.63 | Deylary, f6tal, miu_u, Potya, unknxwn        |
|            3 |     6045 | 2024-02-18 | ex-FORZE Ladies    | W   | 0.524      | 0.143        | 0.005 (0.000)    | 0.164 (0.012)    | 0 (0.000) |     7.96 | k175un4, mikeri, sosya, Stormy, wieenn       |
|            2 |     6096 | 2024-02-17 | Questionmark       | W   | 0.518      | 0.143        | 0.000 (0.000)    | 0.021 (0.002)    | -         |     6.51 | ASTRA, IRBITka, Missy, oxycet, twix          |
|            1 |     6275 | 2024-02-14 | more whiskey       | L   | 0.497      | -            | -                | -                | -         |   -11.26 | aiveri, Hikomi, takitaki, turboxgirl, v1spel |

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
