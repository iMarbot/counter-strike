### Roster Details<br />
Team Name: BAKS Esports<br />
Roster: datet, elocurse, Middlesex, z1k4, z1Nny<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [377](../standings_global.md)<br />
Regional Rank: [226]( ../standings_europe.md)<br />
Final Rank Value:  591.4<br />
<br />
Final Rank Value (591.4) = Starting Rank Value (629.3) + Head To Head Adjustments (-37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.185[<sup>2</sup>](#table1)
- Opponent Network: 0.015[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 629.3
- 400 + ( ( 0.113 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 629.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       91 | 2024-05-29 | FORZE Youngsters     | L   | 1.000      | -            | -                | -                | -         |   -21.30 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           29 |      122 | 2024-05-28 | ZEROvariant          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    12.75 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           28 |      756 | 2024-05-19 | TopTab Club          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.135 (0.019)    | 0 (0.000) |    11.30 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           27 |      806 | 2024-05-19 | Team PeeP            | L   | 1.000      | -            | -                | -                | -         |   -15.97 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           26 |      922 | 2024-05-18 | ZEROvariant          | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.138 (0.020)    | 0 (0.000) |    10.91 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           25 |      981 | 2024-05-17 | LYG Gaming           | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.275 (0.039)    | 0 (0.000) |    22.40 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           24 |      997 | 2024-05-17 | YYHuT-1              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     8.72 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           23 |     1205 | 2024-05-15 | 5x404                | L   | 1.000      | -            | -                | -                | -         |   -19.09 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           22 |     3948 | 2024-03-26 | MANGANES             | L   | 0.772      | -            | -                | -                | -         |   -14.34 | datet, elocurse, Middlesex, z1k4, z1Nny        |
|           21 |     5386 | 2024-03-01 | Kappa Bar            | L   | 0.603      | -            | -                | -                | -         |   -11.41 | datet, elocurse, Middlesex, reyoz, twizell     |
|           20 |     5407 | 2024-02-29 | lajtbitexe           | W   | 0.598      | 0.371        | 0.001 (0.000)    | 0.082 (0.018)    | 0 (0.000) |     9.55 | datet, elocurse, Middlesex, reyoz, twizell     |
|           19 |     5484 | 2024-02-28 | ILIN                 | L   | 0.590      | -            | -                | -                | -         |    -9.85 | datet, elocurse, Middlesex, reyoz, twizell     |
|           18 |     5935 | 2024-02-20 | unluckyday           | L   | 0.537      | -            | -                | -                | -         |    -7.12 | datet, elocurse, Middlesex, reyoz, twizell     |
|           17 |     6001 | 2024-02-19 | V1dar Gaming         | L   | 0.531      | -            | -                | -                | -         |    -6.87 | datet, elocurse, Middlesex, reyoz, twizell     |
|           16 |     6030 | 2024-02-18 | L1ZUN4IKI            | W   | 0.525      | 0.284        | 0.000 (0.000)    | 0.014 (0.002)    | 0 (0.000) |     8.77 | datet, elocurse, Middlesex, reyoz, twizell     |
|           15 |     6217 | 2024-02-15 | GamerLegion Academy  | L   | 0.504      | -            | -                | -                | -         |    -4.25 | datet, elocurse, Middlesex, reyoz, twizell     |
|           14 |     6270 | 2024-02-14 | Zero Tenacity        | L   | 0.498      | -            | -                | -                | -         |    -1.40 | datet, elocurse, Middlesex, reyoz, twizell     |
|           13 |     6549 | 2024-02-07 | RoundsGG             | L   | 0.451      | -            | -                | -                | -         |    -7.20 | datet, elocurse, Middlesex, reyoz, twizell     |
|           12 |     6871 | 2024-02-01 | kONO.ECF             | L   | 0.411      | -            | -                | -                | -         |    -2.49 | byr9, kensizor, munch, Polbandana, s4ltovsk1yy |
|           11 |     6914 | 2024-01-31 | ex-sYnck             | L   | 0.404      | -            | -                | -                | -         |    -4.41 | eku, fejtZ, Jyo, Wahtzz, xezr                  |
|           10 |     6970 | 2024-01-30 | 0to100               | W   | 0.398      | 0.371        | 0.000 (0.000)    | 0.012 (0.002)    | 0 (0.000) |     3.73 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze    |
|            9 |     7260 | 2024-01-26 | ENTERPRISE esports   | L   | 0.370      | -            | -                | -                | -         |    -1.29 | bajmi, Demho, Ex1st, fr3nd, TOAO               |
|            8 |     7304 | 2024-01-25 | GODSENT              | L   | 0.364      | -            | -                | -                | -         |    -5.38 | datet, elocurse, Middlesex, reyoz, twizell     |
|            7 |     7650 | 2024-01-19 | ex-Hot Headed Gaming | W   | 0.324      | 0.371        | 0.000 (0.000)    | 0.086 (0.010)    | 0 (0.000) |     3.35 | datet, elocurse, Middlesex, reyoz, twizell     |
|            6 |     8090 | 2024-01-12 | UNiTY esports        | L   | 0.278      | -            | -                | -                | -         |    -1.45 | datet, elocurse, Middlesex, reyoz, twizell     |
|            5 |     8108 | 2024-01-12 | RUSH B               | W   | 0.278      | 0.143        | 0.001 (0.000)    | 0.446 (0.018)    | 0 (0.000) |     5.93 | datet, elocurse, Middlesex, reyoz, twizell     |
|            4 |     8766 | 2023-12-17 | VaselineWorms        | L   | 0.102      | -            | -                | -                | -         |    -1.21 | datet, elocurse, Middlesex, reyoz, twizell     |
|            3 |     8843 | 2023-12-16 | Betera Esports       | L   | 0.098      | -            | -                | -                | -         |    -0.85 | alex666, lollipop21k, MaSvAl, nifee, sad       |
|            2 |     8858 | 2023-12-16 | PrizyvaNet           | W   | 0.097      | -            | -                | -                | -         |     0.67 | datet, elocurse, Middlesex, reyoz, twizell     |
|            1 |     8906 | 2023-12-16 | Nemiga Gaming        | L   | 0.095      | -            | -                | -                | -         |    -0.09 | datet, elocurse, Middlesex, reyoz, twizell     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($322.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
