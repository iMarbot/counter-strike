### Roster Details<br />
Team Name: Soda Gaming<br />
Roster: 2high, aidKiT, Ciocardau, shadiy, soulfly<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [199](../standings_global.md)<br />
Regional Rank: [131]( ../standings_europe.md)<br />
Final Rank Value:  722.3<br />
<br />
Final Rank Value (722.3) = Starting Rank Value (755.4) + Head To Head Adjustments (-33.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.094[<sup>2</sup>](#table1)

The average of these factors is 0.179<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 755.4
- 400 + ( ( 0.179 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 755.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |     2806 | 2024-03-03 | RoundsGG               | W   | 0.778      | 0.371        | 0.000 (0.000)    | 0.170 (0.049)    | 0 (0.000) |    12.10 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           36 |     2961 | 2024-02-29 | ILIN                   | L   | 0.758      | -            | -                | -                | -         |   -15.25 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           35 |     3591 | 2024-02-15 | ALTERNATE aTTaX        | L   | 0.664      | -            | -                | -                | -         |    -3.78 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           34 |     3673 | 2024-02-13 | DASH                   | L   | 0.652      | -            | -                | -                | -         |    -9.70 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           33 |     3732 | 2024-02-12 | FLuffy Gangsters       | L   | 0.644      | -            | -                | -                | -         |   -14.82 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           32 |     4079 | 2024-02-01 | Lajtbitexe             | W   | 0.571      | 0.371        | -                | 0.033 (0.007)    | 0 (0.000) |     4.48 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           31 |     4101 | 2024-01-31 | The Chosen Few         | L   | 0.566      | -            | -                | -                | -         |    -7.97 | 2high, aidKiT, Ciocardau, shadiy, soulfly       |
|           30 |     4270 | 2024-01-27 | Jake Bube              | L   | 0.538      | -            | -                | -                | -         |   -13.66 | 2high, adeX, Ciocardau, shadiy, Tapewaare       |
|           29 |     4276 | 2024-01-27 | Regnum                 | W   | 0.538      | 0.143        | 0.003 (0.000)    | 0.046 (0.003)    | 0 (0.000) |     6.36 | 2high, adeX, Ciocardau, shadiy, Tapewaare       |
|           28 |     4696 | 2024-01-17 | Into The Breach        | L   | 0.473      | -            | -                | -                | -         |    -6.26 | Bymas, CRUC1AL, misutaaa, rallen, Thomas        |
|           27 |     4702 | 2024-01-17 | ENTERPRISE esports     | W   | 0.473      | -            | -                | -                | 0 (0.000) |     3.37 | 2h, Ciocardau, Kursy, shadiy, soulfly           |
|           26 |     4721 | 2024-01-17 | The Chosen Few         | W   | 0.472      | 0.143        | 0.007 (0.000)    | 0.457 (0.031)    | 0 (0.000) |     8.09 | hybrid, Libido, shaiK, Skrimo, SPELLAN          |
|           25 |     4788 | 2024-01-16 | Rebels Gaming          | L   | 0.466      | -            | -                | -                | -         |    -1.34 | casey, Flayy, kisserek, olimp, sNx              |
|           24 |     4922 | 2024-01-12 | Nexus Gaming           | L   | 0.439      | -            | -                | -                | -         |    -4.32 | BTN, ERSIN, ragga, s0und, XELLOW                |
|           23 |     5003 | 2024-01-11 | Team Space             | L   | 0.431      | -            | -                | -                | -         |    -7.39 | enzero, fozil, leri511, TruNiQ, Vert            |
|           22 |     5032 | 2024-01-10 | Zero Tenacity          | W   | 0.426      | 0.143        | 0.095 (0.006)    | 1.000 (0.061)    | -         |     9.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke        |
|           21 |     5038 | 2024-01-10 | SSX                    | W   | 0.426      | 0.143        | 0.001 (0.000)    | -                | -         |     4.34 | RpK, SHOGU, shox, SmithZz, zakarinh0            |
|           20 |     5111 | 2024-01-09 | Rhyno Esports          | L   | 0.418      | -            | -                | -                | -         |    -3.71 | DDias, krazy, renatoohaxx, snapy, TMKj          |
|           19 |     5317 | 2023-12-19 | Pera Esports           | L   | 0.277      | -            | -                | -                | -         |    -2.55 | 2h, adeX, Ciocardau, God6y, shadiy              |
|           18 |     5320 | 2023-12-19 | GUN5 Esports           | L   | 0.277      | -            | -                | -                | -         |    -5.80 | FinigaN, lov1kus, ResoLuxe, supra, xiELO        |
|           17 |     6049 | 2023-12-03 | SSX                    | W   | 0.170      | -            | -                | -                | 1 (0.170) |     1.74 | 2h, adeX, Ciocardau, God6y, shadiy              |
|           16 |     6056 | 2023-12-03 | SYMPA LA FORCE         | W   | 0.170      | -            | -                | -                | 1 (0.170) |     1.60 | 2h, adeX, Ciocardau, God6y, shadiy              |
|           15 |     6062 | 2023-12-03 | RGW Esports            | W   | 0.169      | -            | -                | -                | 1 (0.169) |     1.73 | Dodal, Empera, Myzunic, sOSEIRy, ViTaaa         |
|           14 |     6085 | 2023-12-02 | Prodigy (Agency)       | W   | 0.166      | -            | -                | -                | 1 (0.166) |     0.67 | consss, jEROME, NaToSaphiX, shr, STYKO          |
|           13 |     6105 | 2023-12-02 | SYMPA LA FORCE         | L   | 0.165      | -            | -                | -                | -         |    -3.66 | 2h, adeX, Ciocardau, God6y, shadiy              |
|           12 |     6114 | 2023-12-02 | BRODA                  | W   | 0.165      | -            | -                | -                | 1 (0.165) |     0.61 | 2h, adeX, Ciocardau, God6y, shadiy              |
|           11 |     6255 | 2023-11-29 | Turów Zgorzelec Esport | W   | 0.145      | 0.371        | 0.019 (0.001)    | 0.640 (0.034)    | -         |     2.67 | b1elany, darko, gRuChA, kadziu, Markoś          |
|           10 |     6399 | 2023-11-26 | BetBoom Team           | W   | 0.124      | 0.143        | 0.571 (0.010)    | 0.824 (0.015)    | -         |     3.84 | 2h, adeX, Ciocardau, God6y, shadiy              |
|            9 |     6433 | 2023-11-25 | Metizport              | W   | 0.118      | 0.143        | 0.188 (0.003)    | 1.000 (0.017)    | -         |     3.00 | 2h, adeX, Ciocardau, God6y, shadiy              |
|            8 |     6548 | 2023-11-22 | JESTE                  | W   | 0.099      | -            | -                | -                | -         |     0.37 | 2h, adeX, Ciocardau, God6y, shadiy              |
|            7 |     6621 | 2023-11-20 | Inferus eSports        | W   | 0.086      | -            | -                | -                | -         |     0.52 | eksiver, H0k17, lockstock, natalia_audi, scRipt |
|            6 |     6636 | 2023-11-20 | MASONIC Academy        | W   | 0.085      | -            | -                | -                | -         |     0.32 | Ch4se, Falk, koei, Logic, OzN3X                 |
|            5 |     6724 | 2023-11-18 | Guild Eagles           | W   | 0.071      | 0.143        | 0.037 (0.000)    | 0.586 (0.006)    | -         |     1.83 | 2h, adeX, Ciocardau, God6y, shadiy              |
|            4 |     6834 | 2023-11-16 | BALLISTIC              | W   | 0.057      | -            | -                | -                | -         |     0.22 | 2h, adeX, Ciocardau, God6y, shadiy              |
|            3 |     6967 | 2023-11-13 | Wu-Tang Clan           | L   | 0.039      | -            | -                | -                | -         |    -0.99 | innocent, Kind0, Maze, szejn, tvs               |
|            2 |     7070 | 2023-11-11 | Alliance               | W   | 0.024      | 0.143        | 0.017 (0.000)    | 0.729 (0.002)    | -         |     0.51 | avid, b0denmaster, PlesseN, robiin, twist       |
|            1 |     7201 | 2023-11-08 | INGLORIOUS             | L   | 0.004      | -            | -                | -                | -         |    -0.06 | Drobnyy, Esphirion, Jad0R1x, LAYM, V1           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,412.06)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-03 |      0.170 | $2,177.34      | $370.96         |
| 2023-11-26 |      0.124 | $8,387.83      | $1,041.10       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
