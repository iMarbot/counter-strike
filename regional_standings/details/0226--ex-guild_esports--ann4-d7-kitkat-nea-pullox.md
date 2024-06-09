### Roster Details<br />
Team Name: ex-Guild Esports<br />
Roster: Ann4, D7, KiTKaT, Nea, pullox<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [226](../standings_global.md)<br />
Regional Rank: [153]( ../standings_europe.md)<br />
Final Rank Value:  704.6<br />
<br />
Final Rank Value (704.6) = Starting Rank Value (693.1) + Head To Head Adjustments (11.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.305[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.144<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.1
- 400 + ( ( 0.144 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 693.1


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
|           18 |      893 | 2024-05-18 | NIP Impact         | L   | 1.000      | -            | -                | -                | -         |   -14.74 | Ann4, D7, KiTKaT, Nea, pullox              |
|           17 |      928 | 2024-05-18 | VIOLET             | W   | 1.000      | 0.281        | 0.000 (0.000)    | 0.051 (0.014)    | 0 (0.000) |     6.94 | Ann4, D7, KiTKaT, Nea, pullox              |
|           16 |     2540 | 2024-04-21 | Fearless Cheetahs  | W   | 0.944      | 0.331        | 0.006 (0.002)    | 0.149 (0.046)    | 0 (0.000) |    14.92 | kr4sy, Ksu, t4tty, victoria, vilga         |
|           15 |     2643 | 2024-04-20 | Let Her Cook       | L   | 0.936      | -            | -                | -                | -         |   -18.97 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           14 |     2749 | 2024-04-19 | Team Pigeons       | L   | 0.930      | -            | -                | -                | -         |    -9.82 | Ann4, D7, KiTKaT, Nea, pullox              |
|           13 |     3247 | 2024-04-10 | NIP Impact         | W   | 0.870      | 0.331        | 0.007 (0.002)    | 0.303 (0.087)    | 0 (0.000) |    13.91 | aiM, jenkon, Nayomy, Qiyarah, ramziiN      |
|           12 |     3489 | 2024-04-06 | NIP Impact         | L   | 0.842      | -            | -                | -                | -         |   -13.95 | aiM, jenkon, Nayomy, Qiyarah, ramziiN      |
|           11 |     3501 | 2024-04-06 | Permitta W         | W   | 0.841      | 0.262        | -                | 0.051 (0.011)    | 0 (0.000) |     6.10 | amyb, Gaba, Mrs_Fire, pavlla, Tynka        |
|           10 |     3830 | 2024-03-28 | BIG EQUIPA         | W   | 0.784      | 0.331        | 0.002 (0.001)    | 0.267 (0.069)    | 0 (0.000) |    12.72 | Ann4, D7, KiTKaT, Nea, pullox              |
|            9 |     4181 | 2024-03-21 | Astralis Women     | W   | 0.738      | 0.331        | 0.003 (0.001)    | 0.054 (0.013)    | 0 (0.000) |     8.73 | Ann4, D7, KiTKaT, Nea, pullox              |
|            8 |     4595 | 2024-03-13 | ENCE Athena        | L   | 0.684      | -            | -                | -                | -         |   -11.15 | Aida, Emmsan, miLo, Waldee, xia            |
|            7 |     5711 | 2024-02-24 | BIG EQUIPA         | L   | 0.563      | -            | -                | -                | -         |    -9.23 | JennyR, juliano, kyossa, pauliiee, Zana    |
|            6 |     5725 | 2024-02-24 | Fearless Cheetahs  | W   | 0.562      | 0.143        | 0.006 (0.001)    | 0.149 (0.012)    | 0 (0.000) |     8.27 | Ann4, D7, KiTKaT, Nea, pullox              |
|            5 |     6267 | 2024-02-14 | Team Spirit Female | W   | 0.498      | 0.143        | 0.005 (0.000)    | 0.216 (0.015)    | 0 (0.000) |     7.34 | Ann4, D7, KiTKaT, Nea, pullox              |
|            4 |     6278 | 2024-02-14 | Astralis Women     | W   | 0.497      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     6.50 | Ann4, D7, KiTKaT, Nea, pullox              |
|            3 |     7515 | 2024-01-21 | Nemesis            | L   | 0.337      | -            | -                | -                | -         |    -6.22 | Ann4, D7, KiTKaT, kr4sylya, pullox         |
|            2 |     7518 | 2024-01-21 | ex-FORZE Ladies    | W   | 0.337      | 0.250        | 0.005 (0.000)    | 0.164 (0.014)    | 0 (0.000) |     5.07 | DeJaWoo, k175un4, sosya, Stormy, wieenn    |
|            1 |     7582 | 2024-01-20 | Team Spirit Female | W   | 0.330      | 0.250        | 0.005 (0.000)    | 0.216 (0.018)    | -         |     5.08 | Ann4, D7, KiTKaT, kr4sylya, pullox         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,594.28)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.944 | $1,600.00      | $1,510.00       |
| 2024-01-21 |      0.337 | $250.00        | $84.28          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
