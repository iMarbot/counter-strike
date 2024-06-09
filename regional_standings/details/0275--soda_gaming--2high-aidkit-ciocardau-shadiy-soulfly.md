### Roster Details<br />
Team Name: Soda Gaming<br />
Roster: 2high, aidKiT, Ciocardau, shadiy, soulfly<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [275](../standings_global.md)<br />
Regional Rank: [177]( ../standings_europe.md)<br />
Final Rank Value:  662.5<br />
<br />
Final Rank Value (662.5) = Starting Rank Value (650.5) + Head To Head Adjustments (12.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.193[<sup>1</sup>](#table2)
- Bounty Collected: 0.260[<sup>2</sup>](#table1)
- Opponent Network: 0.036[<sup>2</sup>](#table1)
- LAN Wins: 0.004[<sup>2</sup>](#table1)

The average of these factors is 0.123<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 650.5
- 400 + ( ( 0.123 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 650.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |     5239 | 2024-03-03 | RoundsGG           | W   | 0.617      | 0.371        | -                | 0.251 (0.058)    | 0 (0.000) |     9.03 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           31 |     5431 | 2024-02-29 | ILIN               | L   | 0.597      | -            | -                | -                | -         |   -11.17 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           30 |     6231 | 2024-02-15 | ALTERNATE aTTaX    | L   | 0.503      | -            | -                | -                | -         |    -2.52 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           29 |     6336 | 2024-02-13 | DASH               | L   | 0.491      | -            | -                | -                | -         |    -6.62 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           28 |     6402 | 2024-02-12 | FLuffy Gangsters   | L   | 0.483      | -            | -                | -                | -         |    -9.57 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           27 |     6878 | 2024-02-01 | 1win               | W   | 0.411      | 0.371        | 0.050 (0.008)    | 0.898 (0.137)    | 0 (0.000) |    10.81 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           26 |     6885 | 2024-02-01 | lajtbitexe         | W   | 0.410      | 0.371        | 0.001 (0.000)    | 0.082 (0.012)    | 0 (0.000) |     5.71 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           25 |     6912 | 2024-01-31 | The Chosen Few     | L   | 0.404      | -            | -                | -                | -         |    -5.15 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           24 |     6929 | 2024-01-31 | Lilmix             | W   | 0.404      | 0.371        | 0.006 (0.001)    | 0.593 (0.089)    | 0 (0.000) |     9.67 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           23 |     7185 | 2024-01-27 | Jake Bube          | L   | 0.377      | -            | -                | -                | -         |    -8.55 | 2high, adeX, Ciocardau, shadiy, Tapewaare |
|           22 |     7196 | 2024-01-27 | Regnum             | W   | 0.377      | 0.143        | 0.001 (0.000)    | 0.050 (0.003)    | 0 (0.000) |     5.41 | 2high, adeX, Ciocardau, shadiy, Tapewaare |
|           21 |     7341 | 2024-01-24 | Sashi Esport       | L   | 0.358      | -            | -                | -                | -         |    -1.19 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           20 |     7357 | 2024-01-24 | GUN5 Esports       | W   | 0.357      | 0.371        | -                | 0.058 (0.008)    | -         |     3.90 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           19 |     7765 | 2024-01-17 | Into The Breach    | L   | 0.312      | -            | -                | -                | -         |    -3.98 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           18 |     7771 | 2024-01-17 | ENTERPRISE esports | W   | 0.312      | 0.143        | -                | 0.010 (0.000)    | -         |     3.21 | 2h, Ciocardau, Kursy, shadiy, soulfly     |
|           17 |     7793 | 2024-01-17 | The Chosen Few     | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.262 (0.012)    | -         |     6.01 | hybrid, Libido, shaiK, Skrimo, SPELLAN    |
|           16 |     7885 | 2024-01-16 | Rebels Gaming      | L   | 0.305      | -            | -                | -                | -         |    -0.68 | casey, Flayy, kisserek, olimp, sNx        |
|           15 |     7930 | 2024-01-16 | emeryyCi           | W   | 0.304      | -            | -                | -                | -         |     1.84 | djabeU, frox, Futrzak, mill, nejk         |
|           14 |     8085 | 2024-01-12 | Nexus Gaming       | L   | 0.278      | -            | -                | -                | -         |    -1.85 | BTN, ERSIN, ragga, s0und, XELLOW          |
|           13 |     8111 | 2024-01-12 | EPIC DUDES         | W   | 0.278      | 0.143        | -                | 0.048 (0.002)    | -         |     2.54 | Askan, DEBRE, Distu, noleN, Straxy        |
|           12 |     8197 | 2024-01-11 | Team Space         | L   | 0.270      | -            | -                | -                | -         |    -2.13 | enzero, fozil, leri511, TruNiQ, Vert      |
|           11 |     8242 | 2024-01-10 | Zero Tenacity      | W   | 0.265      | 0.143        | 0.147 (0.006)    | 1.000 (0.038)    | -         |     7.68 | aVN, brutmonster, Cjoffo, nEMANHA, simke  |
|           10 |     8249 | 2024-01-10 | SSX                | W   | 0.265      | 0.143        | 0.000 (0.000)    | -                | -         |     3.16 | RpK, SHOGU, shox, SmithZz, zakarinh0      |
|            9 |     8367 | 2024-01-09 | Rhyno Esports      | L   | 0.257      | -            | -                | -                | -         |    -0.83 | DDias, krazy, renatoohaxx, snapy, TMKj    |
|            8 |     8658 | 2023-12-19 | Pera Esports       | L   | 0.116      | -            | -                | -                | -         |    -0.68 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            7 |     8661 | 2023-12-19 | GUN5 Esports       | L   | 0.116      | -            | -                | -                | -         |    -2.43 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            6 |     9662 | 2023-12-03 | SSX                | W   | 0.009      | 0.143        | 0.000 (0.000)    | -                | 1 (0.009) |     0.11 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            5 |     9671 | 2023-12-03 | 11minutostarde     | W   | 0.009      | 0.143        | 0.007 (0.000)    | -                | 1 (0.009) |     0.18 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            4 |     9678 | 2023-12-03 | RGW Esports        | W   | 0.008      | 0.143        | 0.000 (0.000)    | -                | 1 (0.008) |     0.08 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa   |
|            3 |     9717 | 2023-12-02 | Prodigy            | W   | 0.005      | -            | -                | -                | 1 (0.005) |     0.03 | consss, jEROME, NaToSaphiX, shr, STYKO    |
|            2 |     9748 | 2023-12-02 | 11minutostarde     | L   | 0.004      | -            | -                | -                | -         |    -0.04 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            1 |     9764 | 2023-12-02 | BRODA              | W   | 0.003      | -            | -                | -                | 1 (0.003) |     0.02 | 2h, adeX, Ciocardau, God6y, shadiy        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20.26)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
