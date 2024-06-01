### Roster Details<br />
Team Name: ex-KRC Genk Esports<br />
Roster: CrePoW, HiddeH, JuN1, Wumbo, yoomswa<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [370](../standings_global.md)<br />
Regional Rank: [221]( ../standings_europe.md)<br />
Final Rank Value:  589.7<br />
<br />
Final Rank Value (589.7) = Starting Rank Value (641.0) + Head To Head Adjustments (-51.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.220[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 641.0
- 400 + ( ( 0.118 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 641.0


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
|           27 |      661 | 2024-05-20 | Young Gods           | L   | 1.000      | -            | -                | -                | -         |   -18.07 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           26 |      693 | 2024-05-20 | Lemondogs            | L   | 1.000      | -            | -                | -                | -         |   -15.38 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           25 |      747 | 2024-05-19 | Aurora Young Blud    | L   | 1.000      | -            | -                | -                | -         |    -9.46 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           24 |     1424 | 2024-05-11 | TopTab Club          | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.135 (0.050)    | 0 (0.000) |    11.28 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           23 |     1673 | 2024-05-07 | ex-K10               | L   | 1.000      | -            | -                | -                | -         |    -9.22 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           22 |     1877 | 2024-05-03 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -13.11 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           21 |     1967 | 2024-05-01 | Denial               | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.138 (0.051)    | 0 (0.000) |    14.29 | CrePoW, HiddeH, JuN1, Wumbo, yoomswa            |
|           20 |     3872 | 2024-03-26 | ALTERNATE aTTaX      | L   | 0.771      | -            | -                | -                | -         |    -3.78 | AyeZ, CrePoW, JuN1, Wumbo, yOOm                 |
|           19 |     5256 | 2024-02-29 | GamerLegion Academy  | L   | 0.598      | -            | -                | -                | -         |    -5.39 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm               |
|           18 |     5270 | 2024-02-29 | Lemondogs            | W   | 0.597      | 0.371        | 0.000 (0.000)    | 0.274 (0.061)    | 0 (0.000) |     8.38 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm               |
|           17 |     5527 | 2024-02-24 | GUN5 Esports         | L   | 0.564      | -            | -                | -                | -         |    -9.50 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm               |
|           16 |     5605 | 2024-02-23 | 0to100               | W   | 0.557      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.66 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm               |
|           15 |     6190 | 2024-02-12 | Lilmix               | L   | 0.484      | -            | -                | -                | -         |    -3.67 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm               |
|           14 |     6358 | 2024-02-07 | LODIS                | L   | 0.451      | -            | -                | -                | -         |    -7.48 | asran, fugor, GruBy, Mride, pawkoem             |
|           13 |     6414 | 2024-02-05 | DASH                 | L   | 0.438      | -            | -                | -                | -         |    -5.93 | cairne, Dawy, Flierax, kRyTouS, Merl            |
|           12 |     6835 | 2024-01-29 | Preasy Esport        | L   | 0.390      | -            | -                | -                | -         |    -3.02 | beccie, Equip, Griller, Skejs, VireZ            |
|           11 |     6953 | 2024-01-27 | Natus Vincere Junior | W   | 0.378      | 0.289        | 0.006 (0.001)    | 0.422 (0.046)    | 0 (0.000) |     7.84 | cmtry, dziugss, froz1k, qzr, UNBR0KEN           |
|           10 |     7108 | 2024-01-24 | Gaimin Gladiators    | L   | 0.358      | -            | -                | -                | -         |    -0.33 | CrePoW, MAGILA, Philong, Wumbo, yOOm            |
|            9 |     7265 | 2024-01-21 | Passion UA           | L   | 0.338      | -            | -                | -                | -         |    -1.35 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX    |
|            8 |     7349 | 2024-01-20 | AVEZ                 | W   | 0.330      | 0.289        | 0.006 (0.001)    | 0.209 (0.020)    | 0 (0.000) |     7.81 | AntyVirus, przemeklovel, SpavaQ, stussyy, Yamii |
|            7 |     7556 | 2024-01-17 | GUN5 Esports         | L   | 0.311      | -            | -                | -                | -         |    -6.33 | FinigaN, lov1kus, supra, xiELO, znxxX           |
|            6 |     7685 | 2024-01-16 | Begrip Gaming        | W   | 0.303      | 0.289        | 0.000 (0.000)    | 0.317 (0.028)    | 0 (0.000) |     4.34 | AyeZ, CrePoW, Philong, Wumbo, yOOm              |
|            5 |     8727 | 2023-12-15 | Rhyno Esports        | L   | 0.091      | -            | -                | -                | -         |    -0.28 | DDias, Icarus, krazy, snapy, TMKj               |
|            4 |     8787 | 2023-12-14 | Passion UA           | W   | 0.084      | 0.333        | 0.057 (0.002)    | 1.000 (0.028)    | 0 (0.000) |     2.37 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX    |
|            3 |     8830 | 2023-12-13 | VP.Prodigy           | L   | 0.078      | -            | -                | -                | -         |    -0.62 | CrePoW, Philong, ReFuZR, Wumbo, yOOm            |
|            2 |     8923 | 2023-12-11 | showmakerz           | W   | 0.064      | 0.333        | 0.000 (0.000)    | 0.201 (0.004)    | 0 (0.000) |     0.72 | CrePoW, Philong, ReFuZR, Wumbo, yOOm            |
|            1 |     9162 | 2023-12-07 | WOPA Esport          | W   | 0.037      | 0.333        | 0.003 (0.000)    | 0.594 (0.007)    | 0 (0.000) |     0.87 | brzer, buNNy, Gnøffe, Leakz, LUMSEN             |

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
