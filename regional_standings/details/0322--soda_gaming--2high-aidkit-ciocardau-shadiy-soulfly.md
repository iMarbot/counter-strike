### Roster Details<br />
Team Name: Soda Gaming<br />
Roster: 2high, aidKiT, Ciocardau, shadiy, soulfly<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [322](../standings_global.md)<br />
Regional Rank: [195]( ../standings_europe.md)<br />
Final Rank Value:  626.2<br />
<br />
Final Rank Value (626.2) = Starting Rank Value (626.5) + Head To Head Adjustments (-0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.193[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.004[<sup>2</sup>](#table1)

The average of these factors is 0.111<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 626.5
- 400 + ( ( 0.111 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 626.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |     5093 | 2024-03-03 | RoundsGG            | W   | 0.617      | 0.371        | 0.000 (0.000)    | 0.202 (0.046)    | 0 (0.000) |     9.45 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           28 |     5281 | 2024-02-29 | ILIN                | L   | 0.597      | -            | -                | -                | -         |   -10.61 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           27 |     6050 | 2024-02-15 | ALTERNATE aTTaX     | L   | 0.503      | -            | -                | -                | -         |    -1.87 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           26 |     6151 | 2024-02-13 | DASH                | L   | 0.491      | -            | -                | -                | -         |    -6.06 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           25 |     6214 | 2024-02-12 | ex-FLuffy Gangsters | L   | 0.483      | -            | -                | -                | -         |   -10.16 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           24 |     6676 | 2024-02-01 | lajtbitexe          | W   | 0.410      | 0.371        | 0.001 (0.000)    | 0.069 (0.011)    | 0 (0.000) |     5.88 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           23 |     6703 | 2024-01-31 | The Chosen Few      | L   | 0.404      | -            | -                | -                | -         |    -4.34 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           22 |     6717 | 2024-01-31 | Lilmix              | W   | 0.404      | 0.371        | 0.000 (0.000)    | 0.045 (0.007)    | 0 (0.000) |     4.86 | 2high, aidKiT, Ciocardau, shadiy, soulfly |
|           21 |     6965 | 2024-01-27 | Jake Bube           | L   | 0.377      | -            | -                | -                | -         |    -8.23 | 2high, adeX, Ciocardau, shadiy, Tapewaare |
|           20 |     6976 | 2024-01-27 | Regnum              | W   | 0.377      | 0.143        | 0.001 (0.000)    | 0.050 (0.003)    | 0 (0.000) |     5.81 | 2high, adeX, Ciocardau, shadiy, Tapewaare |
|           19 |     7516 | 2024-01-17 | Into The Breach     | L   | 0.312      | -            | -                | -                | -         |    -3.70 | Bymas, CRUC1AL, misutaaa, rallen, Thomas  |
|           18 |     7522 | 2024-01-17 | ENTERPRISE esports  | W   | 0.312      | 0.143        | -                | 0.010 (0.000)    | 0 (0.000) |     3.48 | 2h, Ciocardau, Kursy, shadiy, soulfly     |
|           17 |     7544 | 2024-01-17 | The Chosen Few      | W   | 0.311      | 0.143        | 0.002 (0.000)    | 0.262 (0.012)    | -         |     6.57 | hybrid, Libido, shaiK, Skrimo, SPELLAN    |
|           16 |     7636 | 2024-01-16 | Rebels Gaming       | L   | 0.305      | -            | -                | -                | -         |    -0.61 | casey, Flayy, kisserek, olimp, sNx        |
|           15 |     7681 | 2024-01-16 | emeryyCi            | W   | 0.304      | -            | -                | -                | -         |     2.03 | djabeU, frox, Futrzak, mill, nejk         |
|           14 |     7832 | 2024-01-12 | Nexus Gaming        | L   | 0.278      | -            | -                | -                | -         |    -1.54 | BTN, ERSIN, ragga, s0und, XELLOW          |
|           13 |     7858 | 2024-01-12 | EPIC DUDES          | W   | 0.278      | 0.143        | -                | 0.048 (0.002)    | -         |     2.78 | Askan, DEBRE, Distu, noleN, Straxy        |
|           12 |     7944 | 2024-01-11 | Team Space          | L   | 0.270      | -            | -                | -                | -         |    -1.94 | enzero, fozil, leri511, TruNiQ, Vert      |
|           11 |     7988 | 2024-01-10 | Zero Tenacity       | W   | 0.265      | 0.143        | 0.147 (0.006)    | 1.000 (0.038)    | -         |     7.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke  |
|           10 |     7995 | 2024-01-10 | SSX                 | W   | 0.265      | 0.143        | 0.000 (0.000)    | -                | -         |     3.43 | RpK, SHOGU, shox, SmithZz, zakarinh0      |
|            9 |     8113 | 2024-01-09 | Rhyno Esports       | L   | 0.257      | -            | -                | -                | -         |    -0.75 | DDias, krazy, renatoohaxx, snapy, TMKj    |
|            8 |     8401 | 2023-12-19 | Pera Esports        | L   | 0.116      | -            | -                | -                | -         |    -0.59 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            7 |     8404 | 2023-12-19 | GUN5 Esports        | L   | 0.116      | -            | -                | -                | -         |    -2.33 | FinigaN, lov1kus, ResoLuxe, supra, xiELO  |
|            6 |     9380 | 2023-12-03 | SSX                 | W   | 0.009      | 0.143        | 0.000 (0.000)    | -                | 1 (0.009) |     0.12 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            5 |     9389 | 2023-12-03 | 11minutostarde      | W   | 0.009      | 0.143        | 0.007 (0.000)    | 0.055 (0.000)    | 1 (0.009) |     0.19 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            4 |     9396 | 2023-12-03 | RGW Esports         | W   | 0.008      | 0.143        | 0.000 (0.000)    | 0.025 (0.000)    | 1 (0.008) |     0.09 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa   |
|            3 |     9435 | 2023-12-02 | Prodigy             | W   | 0.005      | -            | -                | -                | 1 (0.005) |     0.03 | consss, jEROME, NaToSaphiX, shr, STYKO    |
|            2 |     9466 | 2023-12-02 | 11minutostarde      | L   | 0.004      | -            | -                | -                | -         |    -0.04 | 2h, adeX, Ciocardau, God6y, shadiy        |
|            1 |     9482 | 2023-12-02 | BRODA               | W   | 0.003      | -            | -                | -                | 1 (0.003) |     0.02 | 2h, adeX, Ciocardau, God6y, shadiy        |

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
