### Roster Details<br />
Team Name: AURA<br />
Roster: bobeksde, eraa, FRANSSON, Hype, RuStY<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [210](../standings_global.md)<br />
Regional Rank: [141]( ../standings_europe.md)<br />
Final Rank Value:  718.0<br />
<br />
Final Rank Value (718.0) = Starting Rank Value (605.8) + Head To Head Adjustments (112.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.326[<sup>2</sup>](#table1)
- Opponent Network: 0.078[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.8
- 400 + ( ( 0.101 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 605.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |     3791 | 2024-03-27 | Aurora Gaming             | L   | 0.778      | -            | -                | -                | -         |    -0.46 | bobeksde, eraa, FRANSSON, Hype, RuStY        |
|           35 |     3803 | 2024-03-27 | 3DMAX                     | W   | 0.777      | 0.143        | 0.106 (0.012)    | 0.301 (0.033)    | 0 (0.000) |    19.27 | bobeksde, eraa, FRANSSON, Hype, RuStY        |
|           34 |     3866 | 2024-03-26 | Nemiga Gaming             | W   | 0.771      | 0.143        | 0.366 (0.040)    | 0.830 (0.092)    | 0 (0.000) |    23.01 | bobeksde, eraa, FRANSSON, Hype, RuStY        |
|           33 |     4560 | 2024-03-12 | MOUZ NXT                  | L   | 0.677      | -            | -                | -                | -         |    -2.07 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           32 |     4662 | 2024-03-10 | FAVBET Team               | W   | 0.664      | 0.371        | 0.008 (0.002)    | 0.666 (0.164)    | 0 (0.000) |    16.23 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           31 |     4711 | 2024-03-09 | Kappa Borr                | L   | 0.657      | -            | -                | -                | -         |   -15.30 | jayzaR, Ludwig, Twinkey, virree, zen         |
|           30 |     4714 | 2024-03-09 | EPIC DUDES                | W   | 0.657      | -            | -                | -                | 0 (0.000) |     3.62 | Askan, Distu, otto, Straxy, toshas           |
|           29 |     4727 | 2024-03-09 | Young Ninjas              | L   | 0.656      | -            | -                | -                | -         |    -3.82 | BluePho3nix, jocab, maxster, MisteM, Silence |
|           28 |     4814 | 2024-03-07 | Passion UA                | L   | 0.644      | -            | -                | -                | -         |    -3.69 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           27 |     4891 | 2024-03-06 | Zero Tenacity             | L   | 0.636      | -            | -                | -                | -         |    -2.61 | aVN, brutmonster, Cjoffo, nEMANHA, simke     |
|           26 |     4913 | 2024-03-06 | Team Sampi                | L   | 0.635      | -            | -                | -                | -         |    -4.04 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           25 |     4968 | 2024-03-05 | Endpoint                  | L   | 0.630      | -            | -                | -                | -         |    -4.39 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           24 |     5055 | 2024-03-04 | BLEED Esports             | L   | 0.622      | -            | -                | -                | -         |    -1.09 | CeRq, CYPHER, faveN, hampus, lauNX           |
|           23 |     5082 | 2024-03-03 | Fnatic                    | L   | 0.617      | -            | -                | -                | -         |    -1.61 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           22 |     5124 | 2024-03-02 | UNiTY esports             | W   | 0.612      | 0.143        | 0.021 (0.002)    | 0.766 (0.067)    | 0 (0.000) |    13.71 | K1-FiDa, Levi, M1key, NIO, Pechyn            |
|           21 |     5150 | 2024-03-02 | ex-Turów Zgorzelec Esport | W   | 0.611      | 0.143        | 0.006 (0.000)    | 0.375 (0.033)    | 0 (0.000) |    12.76 | AxEcHo, darko, kadziu, Markoś, xKacpersky    |
|           20 |     5203 | 2024-03-02 | Permitta Esports          | L   | 0.609      | -            | -                | -                | -         |    -3.01 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           19 |     5252 | 2024-02-29 | ex-FLuffy Gangsters       | W   | 0.598      | -            | -                | -                | 0 (0.000) |     6.59 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           18 |     5268 | 2024-02-29 | ex-sYnck                  | W   | 0.597      | 0.371        | -                | 0.206 (0.046)    | 0 (0.000) |    11.50 | eku, fejtZ, Jyo, Wahtzz, xezr                |
|           17 |     5292 | 2024-02-29 | BLEED Esports             | L   | 0.596      | -            | -                | -                | -         |    -0.80 | CeRq, CYPHER, faveN, hampus, lauNX           |
|           16 |     5365 | 2024-02-27 | Croatia                   | L   | 0.584      | -            | -                | -                | -         |   -12.65 | Consume, Maki, rbfurious, ROGA, Šego         |
|           15 |     5403 | 2024-02-26 | IMMAPROBLEM               | W   | 0.578      | -            | -                | -                | 0 (0.000) |     6.08 | Damkilde, daxy, J3nsyy, notaN, vester        |
|           14 |     5643 | 2024-02-22 | GenOne                    | W   | 0.551      | 0.371        | -                | 0.442 (0.091)    | 0 (0.000) |     8.34 | devoduvek, drac, Revol, SIXER, unshaark      |
|           13 |     5656 | 2024-02-22 | los kogutos               | W   | 0.551      | -            | -                | -                | -         |     6.14 | darchevile, hotd0g, Nami, sh3nanigan, swiz   |
|           12 |     5662 | 2024-02-22 | HOTU                      | W   | 0.550      | 0.371        | 0.004 (0.001)    | 0.524 (0.107)    | -         |    13.43 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           11 |     5838 | 2024-02-19 | Team Secret               | W   | 0.530      | 0.371        | -                | 0.230 (0.045)    | -         |     9.27 | bobeksde, eraa, Golden, Plopski, RuStY       |
|           10 |     6192 | 2024-02-12 | FORZE Youngsters          | L   | 0.484      | -            | -                | -                | -         |    -7.09 | boN11, kelieN, matusik, spirit, sstiNiX      |
|            9 |     6211 | 2024-02-12 | MOUZ NXT                  | L   | 0.484      | -            | -                | -                | -         |    -1.12 | bobeksde, eraa, Golden, Plopski, RuStY       |
|            8 |     6226 | 2024-02-11 | DASH                      | W   | 0.478      | 0.143        | 0.000 (0.000)    | -                | -         |     9.52 | cairne, Dawy, Flierax, kRyTouS, Merl         |
|            7 |     6231 | 2024-02-11 | Sashi Esport              | W   | 0.477      | -            | -                | -                | -         |     7.31 | b0RUP, Fessor, n1Xen, niko, nut nut          |
|            6 |     6237 | 2024-02-11 | XI Esport                 | W   | 0.477      | 0.143        | 0.001 (0.000)    | -                | -         |     9.08 | anber, Dengzoe, fez, foam, Scr0b             |
|            5 |     6268 | 2024-02-10 | 0to100                    | L   | 0.470      | -            | -                | -                | -         |   -11.34 | aidKiT, Chawzyyy, NENO, stressarN, stYleEeZ  |
|            4 |     6339 | 2024-02-08 | Sangal Esports            | W   | 0.456      | 0.384        | 0.166 (0.029)    | 0.577 (0.101)    | -         |    13.22 | Ganginho, LNZ, sausol, xfl0ud, yxngstxr      |
|            3 |     6531 | 2024-02-03 | showmakerz                | L   | 0.424      | -            | -                | -                | -         |    -7.70 | agoz, bsover, jakoby, julle, Leon1das        |
|            2 |     6604 | 2024-02-02 | EYEBALLERS                | L   | 0.417      | -            | -                | -                | -         |    -2.09 | bobeksde, eraa, Golden, Plopski, RuStY       |
|            1 |     6611 | 2024-02-02 | XI Esport                 | W   | 0.417      | 0.143        | 0.001 (0.000)    | -                | -         |     7.96 | anber, Dengzoe, fez, foam, Scr0b             |

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
