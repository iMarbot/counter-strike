### Roster Details<br />
Team Name: ex-KRC Genk Esports<br />
Roster: CrePoW, HiddeH, JuN1, Wumbo, yoomswa<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [291](../standings_global.md)<br />
Regional Rank: [183]( ../standings_europe.md)<br />
Final Rank Value:  650.4<br />
<br />
Final Rank Value (650.4) = Starting Rank Value (708.5) + Head To Head Adjustments (-58.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.305[<sup>2</sup>](#table1)
- Opponent Network: 0.078[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.152<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 708.5
- 400 + ( ( 0.152 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 708.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           33 |      672 | 2024-05-20 | Young Gods           | L   | 1.000      | -            | -                | -                | -         |   -20.63 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           32 |      704 | 2024-05-20 | Lemondogs            | L   | 1.000      | -            | -                | -                | -         |   -17.90 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           31 |      759 | 2024-05-19 | Aurora Young Blud    | L   | 1.000      | -            | -                | -                | -         |   -12.25 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           30 |     1437 | 2024-05-11 | TopTab Club          | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.135 (0.050)    | 0 (0.000) |     8.67 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           29 |     1691 | 2024-05-07 | ex-K10               | L   | 1.000      | -            | -                | -                | -         |   -12.35 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           28 |     1901 | 2024-05-03 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -16.68 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           27 |     1994 | 2024-05-01 | Denial               | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.138 (0.051)    | 0 (0.000) |    10.71 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           26 |     2407 | 2024-04-24 | Dynamo Eclot         | W   | 0.964      | 0.372        | 0.097 (0.035)    | 0.940 (0.337)    | 0 (0.000) |    24.62 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           25 |     2496 | 2024-04-22 | Young Ninjas         | W   | 0.951      | 0.372        | 0.043 (0.015)    | 0.372 (0.132)    | 0 (0.000) |    23.52 | jocab, MisteM, Silence, sprayxd, xKacpersky     |
|           24 |     2738 | 2024-04-19 | Nemiga Gaming        | L   | 0.931      | -            | -                | -                | -         |    -1.41 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           23 |     2959 | 2024-04-16 | Rustec               | L   | 0.911      | -            | -                | -                | -         |    -8.77 | Dima, eLa1z, Fleer, KaRnez, t3nzy               |
|           22 |     2970 | 2024-04-16 | esmagaB              | L   | 0.910      | -            | -                | -                | -         |    -9.16 | Ag1l, aragornN, P3R3IIRA, pr, rafaxF            |
|           21 |     3969 | 2024-03-26 | ALTERNATE aTTaX      | L   | 0.771      | -            | -                | -                | -         |    -4.81 | AyeZ, CrePoW, JuN1, Wumbo, yOOm                 |
|           20 |     5405 | 2024-02-29 | GamerLegion Academy  | L   | 0.598      | -            | -                | -                | -         |    -6.59 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|           19 |     5420 | 2024-02-29 | Lemondogs            | W   | 0.597      | 0.371        | 0.000 (0.000)    | 0.314 (0.070)    | 0 (0.000) |     7.06 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|           18 |     5687 | 2024-02-24 | GUN5 Esports         | L   | 0.564      | -            | -                | -                | -         |   -10.71 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|           17 |     5765 | 2024-02-23 | 0to100               | W   | 0.557      | -            | -                | -                | 0 (0.000) |     3.96 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|           16 |     6375 | 2024-02-12 | Lilmix               | L   | 0.484      | -            | -                | -                | -         |    -4.87 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|           15 |     6551 | 2024-02-07 | LODIS                | L   | 0.451      | -            | -                | -                | -         |    -8.45 | asran, fugor, GruBy, Mride, pawkoem             |
|           14 |     6612 | 2024-02-05 | DASH                 | L   | 0.438      | -            | -                | -                | -         |    -6.87 | cairne, Dawy, Flierax, kRyTouS, Merl            |
|           13 |     6965 | 2024-01-30 | EXO Clan             | L   | 0.398      | -            | -                | -                | -         |    -2.21 | Adam9130, AwaykeN, bevve, dobbo, Duplicate      |
|           12 |     7051 | 2024-01-29 | Preasy Esport        | L   | 0.390      | -            | -                | -                | -         |    -3.78 | beccie, Equip, Griller, Skejs, VireZ            |
|           11 |     7172 | 2024-01-27 | Natus Vincere Junior | W   | 0.378      | 0.289        | 0.006 (0.001)    | 0.444 (0.049)    | 0 (0.000) |     6.90 | cmtry, dziugss, froz1k, qzr, UNBR0KEN           |
|           10 |     7338 | 2024-01-24 | Gaimin Gladiators    | L   | 0.358      | -            | -                | -                | -         |    -0.46 | CrePoW, MAGILA, Philong, Wumbo, yOOm            |
|            9 |     7508 | 2024-01-21 | Passion UA           | L   | 0.338      | -            | -                | -                | -         |    -1.77 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX    |
|            8 |     7593 | 2024-01-20 | AVEZ                 | W   | 0.330      | 0.289        | 0.006 (0.001)    | 0.285 (0.027)    | 0 (0.000) |     7.32 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            7 |     7805 | 2024-01-17 | GUN5 Esports         | L   | 0.311      | -            | -                | -                | -         |    -7.08 | FinigaN, lov1kus, supra, xiELO, znxxX           |
|            6 |     7934 | 2024-01-16 | Begrip Gaming        | W   | 0.303      | 0.289        | 0.000 (0.000)    | 0.317 (0.028)    | 0 (0.000) |     3.49 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|            5 |     8988 | 2023-12-15 | Rhyno Esports        | L   | 0.091      | -            | -                | -                | -         |    -0.39 | DDias, Icarus, krazy, snapy, TMKj               |
|            4 |     9050 | 2023-12-14 | Passion UA           | W   | 0.084      | 0.333        | 0.057 (0.002)    | 1.000 (0.028)    | 0 (0.000) |     2.27 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX    |
|            3 |     9094 | 2023-12-13 | VP.Prodigy           | L   | 0.078      | -            | -                | -                | -         |    -0.78 | CrePoW, Philong, ReFuZR, Wumbo, yOOm            |
|            2 |     9189 | 2023-12-11 | showmakerz           | W   | 0.064      | -            | -                | -                | -         |     0.57 | CrePoW, Philong, ReFuZR, Wumbo, yOOm            |
|            1 |     9435 | 2023-12-07 | WOPA Esport          | W   | 0.037      | 0.333        | 0.003 (0.000)    | 0.594 (0.007)    | -         |     0.77 | brzer, buNNy, Gnøffe, Leakz, LUMSEN             |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104.58)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
