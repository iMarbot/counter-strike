### Roster Details<br />
Team Name: ex-Anonymo Esports<br />
Roster: m4tthi, reiko, SaMey, Sobol, virtuoso<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [214](../standings_global.md)<br />
Regional Rank: [144]( ../standings_europe.md)<br />
Final Rank Value:  713.1<br />
<br />
Final Rank Value (713.1) = Starting Rank Value (698.4) + Head To Head Adjustments (14.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.277[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.051[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 698.4
- 400 + ( ( 0.147 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 698.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |     5648 | 2024-02-22 | The Chosen Few         | L   | 0.551      | -            | -                | -                | -         |    -7.31 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           56 |     5660 | 2024-02-22 | Verdant                | L   | 0.550      | -            | -                | -                | -         |    -3.18 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           55 |     5696 | 2024-02-21 | ARCRED                 | W   | 0.544      | 0.371        | -                | 0.630 (0.127)    | 0 (0.000) |    10.01 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           54 |     5714 | 2024-02-21 | Eternal Fire Academy   | L   | 0.544      | -            | -                | -                | -         |   -10.11 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           53 |     5760 | 2024-02-20 | kONO.ECF               | L   | 0.537      | -            | -                | -                | -         |    -4.54 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           52 |     5839 | 2024-02-19 | Entropiq               | L   | 0.530      | -            | -                | -                | -         |    -9.42 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           51 |     6254 | 2024-02-10 | The Chosen Few         | L   | 0.471      | -            | -                | -                | -         |    -7.01 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           50 |     6272 | 2024-02-10 | FURIA Esports          | L   | 0.470      | -            | -                | -                | -         |    -0.33 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           49 |     6277 | 2024-02-10 | Apeks                  | L   | 0.469      | -            | -                | -                | -         |    -0.85 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           48 |     6393 | 2024-02-06 | Monte Gen              | L   | 0.442      | -            | -                | -                | -         |    -5.82 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           47 |     6419 | 2024-02-05 | GenOne                 | W   | 0.437      | 0.371        | -                | 0.442 (0.072)    | 0 (0.000) |     4.85 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           46 |     6434 | 2024-02-05 | esmagaB                | W   | 0.436      | 0.333        | 0.008 (0.001)    | 0.460 (0.067)    | 0 (0.000) |     8.98 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           45 |     6506 | 2024-02-03 | Young Ninjas           | L   | 0.424      | -            | -                | -                | -         |    -3.79 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           44 |     6572 | 2024-02-03 | Betera Esports         | L   | 0.422      | -            | -                | -                | -         |    -5.27 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           43 |     6705 | 2024-01-31 | VP.Prodigy             | L   | 0.404      | -            | -                | -                | -         |    -4.66 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           42 |     6719 | 2024-01-31 | CYBERSHOKE Esports     | W   | 0.404      | 0.371        | 0.002 (0.000)    | -                | 0 (0.000) |     5.82 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           41 |     6724 | 2024-01-31 | Golden Sword           | W   | 0.403      | -            | -                | -                | 0 (0.000) |     1.57 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           40 |     6775 | 2024-01-30 | Viperio                | W   | 0.395      | 0.333        | -                | 0.189 (0.025)    | 0 (0.000) |     3.78 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           39 |     6794 | 2024-01-29 | 9Pandas                | L   | 0.392      | -            | -                | -                | -         |    -0.96 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           38 |     6815 | 2024-01-29 | XI Esport              | W   | 0.392      | -            | -                | -                | 0 (0.000) |     5.22 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           37 |     6858 | 2024-01-28 | Into The Breach        | W   | 0.384      | -            | -                | -                | 0 (0.000) |     6.30 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           36 |     6865 | 2024-01-28 | Permitta Esports       | W   | 0.384      | 0.143        | 0.029 (0.002)    | 1.000 (0.055)    | 0 (0.000) |     9.51 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           35 |     6872 | 2024-01-28 | 9INE                   | W   | 0.383      | -            | -                | -                | 0 (0.000) |     3.80 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           34 |     6968 | 2024-01-27 | Into The Breach        | L   | 0.377      | -            | -                | -                | -         |    -5.69 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           33 |     7562 | 2024-01-17 | Capcarap               | L   | 0.311      | -            | -                | -                | -         |    -7.62 | DARIEN, Maki, rbfurious, simon71, zeins        |
|           32 |     7623 | 2024-01-16 | JANO Esports           | L   | 0.305      | -            | -                | -                | -         |    -7.48 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           31 |     7635 | 2024-01-16 | LEON Esports           | W   | 0.305      | 0.143        | -                | 0.564 (0.025)    | -         |     5.08 | eightz, facecrack, JIaYm, k0s, z1w0w           |
|           30 |     7676 | 2024-01-16 | ALLINNERS              | W   | 0.304      | -            | -                | -                | -         |     3.97 | alkarenn, demente, ismailz, kumao, wEAVER      |
|           29 |     7783 | 2024-01-13 | OG                     | L   | 0.284      | -            | -                | -                | -         |    -0.62 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           28 |     7789 | 2024-01-13 | FAVBET Team            | W   | 0.283      | 0.143        | 0.008 (0.000)    | 0.666 (0.027)    | -         |     5.93 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           27 |     7833 | 2024-01-12 | Lausanne-Sport Esports | W   | 0.278      | -            | -                | -                | -         |     2.93 | Diviiii, Razzmo, SBT, shr, xReal               |
|           26 |     7845 | 2024-01-12 | En av de lette         | W   | 0.278      | 0.143        | 0.009 (0.000)    | -                | -         |     4.65 | Grus, H4RR3, PALM1, SLY, truth                 |
|           25 |     7938 | 2024-01-11 | Pera Esports           | L   | 0.270      | -            | -                | -                | -         |    -1.98 | Aaron, DGL, Kamion, msN, Porya                 |
|           24 |     7947 | 2024-01-11 | Betera Esports         | W   | 0.270      | 0.143        | 0.023 (0.001)    | -                | -         |     5.52 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           23 |     7992 | 2024-01-10 | CYBERSHOKE Esports     | W   | 0.265      | -            | -                | -                | -         |     4.56 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz      |
|           22 |     8023 | 2024-01-10 | MASTЕR CLUB            | W   | 0.265      | -            | -                | -                | -         |     1.27 | darkONAIR, maeghz, necrett, shr1mzy, tohru     |
|           21 |     8085 | 2024-01-09 | kONO.ECF               | L   | 0.257      | -            | -                | -                | -         |    -2.37 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy |
|           20 |     8119 | 2024-01-09 | Lilmix                 | W   | 0.257      | -            | -                | -                | -         |     2.48 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           19 |     8209 | 2024-01-06 | Natus Vincere Junior   | L   | 0.237      | -            | -                | -                | -         |    -2.98 | dem0n, fnl, Krabeni, Magic, makazze            |
|           18 |     8214 | 2024-01-06 | Betera Esports         | L   | 0.236      | -            | -                | -                | -         |    -2.71 | alex666, lollipop21k, MaSvAl, nifee, sad       |
|           17 |     8235 | 2024-01-04 | brazylijski luz        | W   | 0.222      | 0.354        | 0.013 (0.001)    | 0.490 (0.039)    | -         |     4.50 | Furlan, phr, POLO, Prism, Qlocuu               |
|           16 |     8337 | 2023-12-23 | Team Spirit Academy    | L   | 0.142      | -            | -                | -                | -         |    -2.05 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           15 |     8356 | 2023-12-22 | Natus Vincere Junior   | W   | 0.135      | 0.333        | 0.010 (0.000)    | -                | -         |     2.66 | dem0n, fnl, Krabeni, Magic, makazze            |
|           14 |     8375 | 2023-12-21 | Team Spirit Academy    | L   | 0.129      | -            | -                | -                | -         |    -1.87 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           13 |     8396 | 2023-12-19 | Nexus Gaming           | W   | 0.117      | 0.354        | 0.014 (0.001)    | 0.825 (0.034)    | -         |     2.85 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           12 |     8402 | 2023-12-19 | Sashi Esport           | W   | 0.116      | 0.333        | 0.172 (0.007)    | 1.000 (0.039)    | -         |     3.25 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           11 |     8410 | 2023-12-18 | ROYALS                 | W   | 0.111      | -            | -                | -                | -         |     1.84 | devraNN, Joey, oskvr, Ping, Swaggy             |
|           10 |     8511 | 2023-12-17 | Sashi Esport           | W   | 0.102      | -            | -                | -                | -         |     0.99 | Fessor, n1Xen, nut nut, PR1mE, Speedy          |
|            9 |     8853 | 2023-12-13 | NOM Esports            | W   | 0.075      | -            | -                | -                | -         |     1.00 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            8 |     8938 | 2023-12-11 | ex-Guild Eagles        | L   | 0.062      | -            | -                | -                | -         |    -0.36 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            7 |     9026 | 2023-12-09 | AGO esports            | W   | 0.050      | -            | -                | -                | -         |     0.25 | Chill, Dementor, DEPRESHN, Svedjehed, tAk      |
|            6 |     9098 | 2023-12-08 | Creeps                 | L   | 0.044      | -            | -                | -                | -         |    -1.08 | andr1x, DiMKE, Dragon, Impulse, Kind0          |
|            5 |     9172 | 2023-12-07 | ALTERNATE aTTaX        | W   | 0.037      | -            | -                | -                | -         |     0.61 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            4 |     9294 | 2023-12-05 | GODSENT                | W   | 0.024      | -            | -                | -                | -         |     0.34 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            3 |     9306 | 2023-12-05 | ex-Guild Eagles        | L   | 0.023      | -            | -                | -                | -         |    -0.14 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy    |
|            2 |     9333 | 2023-12-04 | Into The Breach        | W   | 0.018      | -            | -                | -                | -         |     0.30 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            1 |     9504 | 2023-12-02 | Fluxo                  | W   | 0.002      | -            | -                | -                | -         |     0.05 | lunAtic, reiko, SaMey, Sobol, virtuoso         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($748.02)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.142 | $3,000.00      | $425.00         |
| 2023-12-13 |      0.078 | $500.00        | $38.76          |
| 2023-12-13 |      0.076 | $1,250.00      | $95.49          |
| 2023-12-07 |      0.038 | $5,000.00      | $188.77         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
