### Roster Details<br />
Team Name: AURA<br />
Roster: bobeksde, eraa, FRANSSON, Hype, RuStY<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [201](../standings_global.md)<br />
Regional Rank: [136]( ../standings_europe.md)<br />
Final Rank Value:  722.8<br />
<br />
Final Rank Value (722.8) = Starting Rank Value (612.9) + Head To Head Adjustments (109.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.093[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.105<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 612.9
- 400 + ( ( 0.105 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 612.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |     3884 | 2024-03-27 | Aurora Gaming             | L   | 0.778      | -            | -                | -                | -         |    -0.51 | bobeksde, eraa, FRANSSON, Hype, RuStY          |
|           36 |     3896 | 2024-03-27 | 3DMAX                     | W   | 0.777      | 0.143        | 0.106 (0.012)    | -                | 0 (0.000) |    19.21 | bobeksde, eraa, FRANSSON, Hype, RuStY          |
|           35 |     3963 | 2024-03-26 | Nemiga Gaming             | W   | 0.771      | 0.143        | 0.358 (0.039)    | 0.895 (0.099)    | 0 (0.000) |    22.93 | bobeksde, eraa, FRANSSON, Hype, RuStY          |
|           34 |     4680 | 2024-03-12 | MOUZ NXT                  | L   | 0.677      | -            | -                | -                | -         |    -1.98 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           33 |     4787 | 2024-03-10 | FAVBET Team               | W   | 0.664      | 0.371        | 0.008 (0.002)    | 0.845 (0.208)    | 0 (0.000) |    16.30 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           32 |     4836 | 2024-03-09 | Kappa Borr                | L   | 0.657      | -            | -                | -                | -         |   -15.41 | jayzaR, Ludwig, Twinkey, virree, zen           |
|           31 |     4839 | 2024-03-09 | EPIC DUDES                | W   | 0.657      | -            | -                | -                | 0 (0.000) |     3.53 | Askan, Distu, otto, Straxy, toshas             |
|           30 |     4852 | 2024-03-09 | Young Ninjas              | L   | 0.656      | -            | -                | -                | -         |    -3.92 | BluePho3nix, jocab, maxster, MisteM, Silence   |
|           29 |     4943 | 2024-03-07 | Passion UA                | L   | 0.644      | -            | -                | -                | -         |    -3.68 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           28 |     5023 | 2024-03-06 | Zero Tenacity             | L   | 0.636      | -            | -                | -                | -         |    -2.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke       |
|           27 |     5052 | 2024-03-06 | Team Sampi                | L   | 0.635      | -            | -                | -                | -         |    -4.10 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           26 |     5112 | 2024-03-05 | Endpoint                  | L   | 0.630      | -            | -                | -                | -         |    -4.44 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           25 |     5201 | 2024-03-04 | BLEED Esports             | L   | 0.622      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, lauNX             |
|           24 |     5228 | 2024-03-03 | Fnatic                    | L   | 0.617      | -            | -                | -                | -         |    -1.64 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           23 |     5272 | 2024-03-02 | UNiTY esports             | W   | 0.612      | 0.143        | 0.021 (0.002)    | 0.766 (0.067)    | 0 (0.000) |    13.52 | K1-FiDa, Levi, M1key, NIO, Pechyn              |
|           22 |     5298 | 2024-03-02 | ex-Turów Zgorzelec Esport | W   | 0.611      | 0.143        | 0.006 (0.000)    | 0.491 (0.043)    | 0 (0.000) |    13.05 | AxEcHo, darko, kadziu, Markoś, xKacpersky      |
|           21 |     5352 | 2024-03-02 | Permitta Esports          | L   | 0.609      | -            | -                | -                | -         |    -2.97 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           20 |     5401 | 2024-02-29 | FLuffy Gangsters          | W   | 0.598      | 0.371        | -                | 0.394 (0.087)    | 0 (0.000) |     8.01 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           19 |     5418 | 2024-02-29 | ex-sYnck                  | W   | 0.597      | 0.371        | -                | 0.255 (0.057)    | 0 (0.000) |    11.93 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           18 |     5442 | 2024-02-29 | BLEED Esports             | L   | 0.596      | -            | -                | -                | -         |    -0.80 | CeRq, CYPHER, faveN, hampus, lauNX             |
|           17 |     5518 | 2024-02-27 | Croatia                   | L   | 0.584      | -            | -                | -                | -         |   -12.72 | Consume, Maki, rbfurious, ROGA, Šego           |
|           16 |     5532 | 2024-02-27 | kONO.ECF                  | L   | 0.583      | -            | -                | -                | -         |    -3.22 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy |
|           15 |     5560 | 2024-02-26 | IMMAPROBLEM               | W   | 0.578      | -            | -                | -                | 0 (0.000) |     5.95 | Damkilde, daxy, J3nsyy, notaN, vester          |
|           14 |     5803 | 2024-02-22 | GenOne                    | W   | 0.551      | 0.371        | -                | 0.442 (0.091)    | 0 (0.000) |     8.25 | devoduvek, drac, Revol, SIXER, unshaark        |
|           13 |     5816 | 2024-02-22 | los kogutos               | W   | 0.551      | -            | -                | -                | -         |     5.98 | darchevile, hotd0g, Nami, sh3nanigan, swiz     |
|           12 |     5823 | 2024-02-22 | HOTU                      | W   | 0.550      | 0.371        | 0.004 (0.001)    | 0.580 (0.118)    | -         |    13.47 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           11 |     6010 | 2024-02-19 | Team Secret               | W   | 0.530      | 0.371        | -                | 0.230 (0.045)    | -         |     9.17 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           10 |     6378 | 2024-02-12 | FORZE Youngsters          | L   | 0.484      | -            | -                | -                | -         |    -6.66 | boN11, kelieN, matusik, spirit, sstiNiX        |
|            9 |     6398 | 2024-02-12 | MOUZ NXT                  | L   | 0.484      | -            | -                | -                | -         |    -1.09 | bobeksde, eraa, Golden, Plopski, RuStY         |
|            8 |     6414 | 2024-02-11 | DASH                      | W   | 0.478      | 0.143        | 0.000 (0.000)    | -                | -         |     9.61 | cairne, Dawy, Flierax, kRyTouS, Merl           |
|            7 |     6419 | 2024-02-11 | Sashi Esport              | W   | 0.477      | -            | -                | -                | -         |     7.19 | b0RUP, Fessor, n1Xen, niko, nut nut            |
|            6 |     6425 | 2024-02-11 | XI Esport                 | W   | 0.477      | 0.143        | 0.001 (0.000)    | -                | -         |     8.98 | anber, Dengzoe, fez, foam, Scr0b               |
|            5 |     6456 | 2024-02-10 | 0to100                    | L   | 0.470      | -            | -                | -                | -         |   -11.44 | aidKiT, Chawzyyy, NENO, stressarN, stYleEeZ    |
|            4 |     6527 | 2024-02-08 | Sangal Esports            | W   | 0.456      | 0.384        | 0.166 (0.029)    | 0.658 (0.115)    | -         |    13.32 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr        |
|            3 |     6734 | 2024-02-03 | showmakerz                | L   | 0.424      | -            | -                | -                | -         |    -7.73 | agoz, bsover, jakoby, julle, Leon1das          |
|            2 |     6807 | 2024-02-02 | EYEBALLERS                | L   | 0.417      | -            | -                | -                | -         |    -2.15 | bobeksde, eraa, Golden, Plopski, RuStY         |
|            1 |     6815 | 2024-02-02 | XI Esport                 | W   | 0.417      | 0.143        | 0.001 (0.000)    | -                | -         |     7.87 | anber, Dengzoe, fez, foam, Scr0b               |

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
