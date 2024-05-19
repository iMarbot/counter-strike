### Roster Details<br />
Team Name: Ex-Anonymo Esports<br />
Roster: m4tthi, reiko, SaMey, Sobol, virtuoso<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [164](../standings_global.md)<br />
Regional Rank: [110]( ../standings_europe.md)<br />
Final Rank Value:  761.1<br />
<br />
Final Rank Value (761.1) = Starting Rank Value (771.6) + Head To Head Adjustments (-10.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.366[<sup>1</sup>](#table2)
- Bounty Collected: 0.309[<sup>2</sup>](#table1)
- Opponent Network: 0.073[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.187<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 771.6
- 400 + ( ( 0.187 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 771.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           64 |     3245 | 2024-02-22 | The Chosen Few           | L   | 0.712      | -            | -                | -                | -         |    -9.96 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           63 |     3256 | 2024-02-22 | Verdant                  | L   | 0.711      | -            | -                | -                | -         |    -5.58 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           62 |     3292 | 2024-02-21 | ARCRED                   | W   | 0.706      | 0.371        | -                | 0.825 (0.216)    | 0 (0.000) |    12.65 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           61 |     3308 | 2024-02-21 | Eternal Fire Academy     | L   | 0.705      | -            | -                | -                | -         |   -13.03 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           60 |     3350 | 2024-02-20 | TBA.ECF                  | L   | 0.698      | -            | -                | -                | -         |   -13.17 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           59 |     3417 | 2024-02-19 | Entropiq                 | L   | 0.691      | -            | -                | -                | -         |   -10.65 | m4tthi, reiko, SaMey, Sobol, virtuoso          |
|           58 |     3892 | 2024-02-05 | GenOne                   | W   | 0.598      | 0.371        | -                | 0.323 (0.072)    | 0 (0.000) |     4.28 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           57 |     4103 | 2024-01-31 | VP.Prodigy               | L   | 0.566      | -            | -                | -                | -         |    -7.49 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           56 |     4110 | 2024-01-31 | CYBERSHOKE Esports       | W   | 0.565      | 0.371        | -                | 0.220 (0.046)    | 0 (0.000) |     6.72 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           55 |     4115 | 2024-01-31 | Golden Sword             | W   | 0.565      | -            | -                | -                | 0 (0.000) |     1.69 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           54 |     4735 | 2024-01-17 | Capcarap                 | L   | 0.472      | -            | -                | -                | -         |   -12.35 | DARIEN, Maki, rbfurious, simon71, zeins        |
|           53 |     4778 | 2024-01-16 | JANO Esports             | L   | 0.466      | -            | -                | -                | -         |    -8.08 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           52 |     4787 | 2024-01-16 | LEON Esports             | W   | 0.466      | -            | -                | -                | 0 (0.000) |     5.03 | eightz, facecrack, JIaYm, k0s, z1w0w           |
|           51 |     4811 | 2024-01-16 | RealGamers               | W   | 0.465      | -            | -                | -                | 0 (0.000) |     4.21 | alkarenn, demente, ismailz, kumao, wEAVER      |
|           50 |     4886 | 2024-01-13 | OG                       | L   | 0.445      | -            | -                | -                | -         |    -0.72 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           49 |     4891 | 2024-01-13 | BLESSED (Ukrainian team) | W   | 0.444      | 0.143        | -                | 0.781 (0.050)    | 0 (0.000) |     7.42 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           48 |     4929 | 2024-01-12 | En av de lette           | W   | 0.439      | -            | -                | -                | 0 (0.000) |     6.26 | Grus, H4RR3, PALM1, SLY, truth                 |
|           47 |     4998 | 2024-01-11 | Pera Esports             | L   | 0.431      | -            | -                | -                | -         |    -4.19 | Aaron, DGL, Kamion, msN, Porya                 |
|           46 |     5036 | 2024-01-10 | CYBERSHOKE Esports       | W   | 0.426      | -            | -                | -                | 0 (0.000) |     5.74 | fen2k, FenomeN, flamie, Re1GN, sh1nejezzz      |
|           45 |     5057 | 2024-01-10 | MASTЕR CLUB              | W   | 0.426      | -            | -                | -                | 0 (0.000) |     1.35 | darkONAIR, maeghz, necrett, shr1mzy, tohru     |
|           44 |     5090 | 2024-01-09 | TBA.ECF                  | L   | 0.418      | -            | -                | -                | -         |    -9.35 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy |
|           43 |     5115 | 2024-01-09 | Lilmix                   | W   | 0.418      | -            | -                | -                | -         |     4.93 | Brillo, dex, L00m1, quix, SeBreeZe             |
|           42 |     5177 | 2024-01-06 | Natus Vincere Junior     | L   | 0.398      | -            | -                | -                | -         |    -5.87 | dem0n, fnl, Krabeni, Magic, makazze            |
|           41 |     5197 | 2024-01-04 | Illuminar Gaming         | W   | 0.383      | 0.354        | -                | 0.243 (0.033)    | -         |     5.72 | Furlan, phr, POLO, Prism, Qlocuu               |
|           40 |     5278 | 2023-12-23 | Team Spirit Academy      | L   | 0.303      | -            | -                | -                | -         |    -4.51 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           39 |     5292 | 2023-12-22 | Natus Vincere Junior     | W   | 0.296      | 0.333        | 0.025 (0.002)    | 0.492 (0.049)    | -         |     5.43 | dem0n, fnl, Krabeni, Magic, makazze            |
|           38 |     5299 | 2023-12-21 | Team Spirit Academy      | L   | 0.290      | -            | -                | -                | -         |    -4.37 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           37 |     5313 | 2023-12-19 | Nexus Gaming             | W   | 0.278      | 0.354        | 0.031 (0.003)    | 0.772 (0.076)    | -         |     5.98 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           36 |     5318 | 2023-12-19 | Sashi Esport             | W   | 0.277      | 0.333        | 0.193 (0.018)    | 1.000 (0.092)    | -         |     7.34 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           35 |     5654 | 2023-12-13 | NOM Esports              | W   | 0.236      | -            | -                | -                | -         |     2.82 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           34 |     5705 | 2023-12-11 | Guild Eagles             | L   | 0.223      | -            | -                | -                | -         |    -1.31 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           33 |     5770 | 2023-12-09 | AGO esports              | W   | 0.211      | -            | -                | -                | -         |     2.18 | Chill, Dementor, DEPRESHN, Svedjehed, tAk      |
|           32 |     5892 | 2023-12-07 | ALTERNATE aTTaX          | W   | 0.198      | 0.384        | 0.110 (0.008)    | 0.723 (0.055)    | -         |     5.22 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           31 |     5984 | 2023-12-05 | GODSENT                  | W   | 0.185      | 0.384        | 0.026 (0.002)    | -                | -         |     3.21 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           30 |     5996 | 2023-12-05 | Guild Eagles             | L   | 0.184      | -            | -                | -                | -         |    -1.09 | gxx-, juanflatroo, rigoN, SENER1, sinnopsyy    |
|           29 |     6015 | 2023-12-04 | Into The Breach          | W   | 0.179      | 0.589        | 0.022 (0.002)    | -                | -         |     3.12 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           28 |     6130 | 2023-12-02 | Fluxo                    | W   | 0.163      | 0.589        | 0.153 (0.015)    | 0.484 (0.046)    | -         |     4.21 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           27 |     6215 | 2023-11-30 | Lemondogs                | W   | 0.151      | -            | -                | -                | -         |     1.22 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           26 |     6300 | 2023-11-28 | Bleiz                    | W   | 0.139      | -            | -                | -                | -         |     0.67 | CagXD, Cryveng, day0s, LeeN, m4tthi            |
|           25 |     6317 | 2023-11-28 | RoundsGG                 | L   | 0.138      | -            | -                | -                | -         |    -2.42 | Kollo, LYNXi, m0n0xx, p12, Welho               |
|           24 |     6323 | 2023-11-28 | Nemiga Gaming            | L   | 0.138      | -            | -                | -                | -         |    -0.19 | 1eeR, almazer, FL4MUS, khaN, riskyb0b          |
|           23 |     6330 | 2023-11-28 | MOUZ NXT                 | L   | 0.137      | -            | -                | -                | -         |    -0.61 | Chr1zN, Neityu, Nexius, PR, sirah              |
|           22 |     6367 | 2023-11-27 | Ex-Hot Headed Gaming     | L   | 0.132      | -            | -                | -                | -         |    -3.36 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           21 |     6374 | 2023-11-27 | BALLISTIC                | W   | 0.131      | -            | -                | -                | -         |     0.45 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           20 |     6379 | 2023-11-27 | 00 Nation                | W   | 0.130      | -            | -                | -                | -         |     0.75 | birdfromsky, JDC, niko, susp, syrsoN           |
|           19 |     6421 | 2023-11-25 | ENCE                     | L   | 0.119      | -            | -                | -                | -         |    -0.04 | Goofy, hades, jcobbb, KEi, Kylar               |
|           18 |     6501 | 2023-11-23 | TUSTE CHOPAKI            | W   | 0.106      | -            | -                | -                | -         |     0.57 | asran, GruBy, mASKED, Mride, sk1tt             |
|           17 |     6563 | 2023-11-22 | ENTERPRISE esports       | L   | 0.098      | -            | -                | -                | -         |    -0.81 | bajmi, Demho, Ex1st, fr3nd, Klameczka          |
|           16 |     6604 | 2023-11-21 | FORZE Esports            | L   | 0.090      | -            | -                | -                | -         |    -1.38 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           15 |     6634 | 2023-11-20 | Rebels Gaming            | W   | 0.085      | 0.143        | 0.121 (0.001)    | -                | -         |     2.43 | Flayy, kisserek, moonwalk, olimp, sNx          |
|           14 |     6727 | 2023-11-18 | Into The Breach          | L   | 0.071      | -            | -                | -                | -         |    -0.99 | bodyy, Bymas, CRUC1AL, misutaaa, rallen        |
|           13 |     6810 | 2023-11-16 | AGO esports              | L   | 0.059      | -            | -                | -                | -         |    -1.22 | delle, Dementor, DEPRESHN, Svedjehed, tAk      |
|           12 |     6862 | 2023-11-15 | 3DMAX                    | W   | 0.052      | 0.589        | 0.062 (0.002)    | -                | -         |     1.20 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           11 |     6888 | 2023-11-15 | Turów Zgorzelec Esport   | L   | 0.051      | -            | -                | -                | -         |    -0.68 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|           10 |     6898 | 2023-11-15 | Preasy Esport            | L   | 0.050      | -            | -                | -                | -         |    -0.43 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            9 |     6930 | 2023-11-14 | PACT                     | W   | 0.044      | -            | -                | -                | -         |     0.30 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            8 |     6988 | 2023-11-13 | MOUZ NXT                 | W   | 0.036      | 0.589        | 0.215 (0.005)    | -                | -         |     0.99 | Chr1zN, Neityu, Nexius, PR, sirah              |
|            7 |     7000 | 2023-11-12 | Metizport                | L   | 0.032      | -            | -                | -                | -         |    -0.20 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            6 |     7066 | 2023-11-11 | Aurora Young Blud        | L   | 0.024      | -            | -                | -                | -         |    -0.32 | bl1x1, bluewh1te, Easy, malinov, sh1geo        |
|            5 |     7093 | 2023-11-10 | TUSTE CHOPAKI            | W   | 0.018      | -            | -                | -                | -         |     0.10 | asran, GruBy, mASKED, Mride, sk1tt             |
|            4 |     7099 | 2023-11-10 | LF0                      | W   | 0.018      | -            | -                | -                | -         |     0.19 | lunAtic, reiko, SaMey, Sobol, virtuoso         |
|            3 |     7104 | 2023-11-10 | GenOne                   | L   | 0.017      | -            | -                | -                | -         |    -0.37 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig       |
|            2 |     7110 | 2023-11-10 | Team Sampi               | L   | 0.016      | -            | -                | -                | -         |    -0.09 | fino, matys, sAvana1, T4gg3D, The eLiVe        |
|            1 |     7202 | 2023-11-08 | Alliance                 | L   | 0.004      | -            | -                | -                | -         |    -0.05 | lunAtic, reiko, SaMey, Sobol, virtuoso         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,955.70)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.303 | $3,000.00      | $908.19         |
| 2023-12-13 |      0.239 | $500.00        | $119.29         |
| 2023-12-07 |      0.199 | $5,000.00      | $994.10         |
| 2023-12-02 |      0.166 | $2,516.34      | $416.48         |
| 2023-11-26 |      0.125 | $1,251.71      | $156.06         |
| 2023-11-18 |      0.072 | $5,000.00      | $361.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
