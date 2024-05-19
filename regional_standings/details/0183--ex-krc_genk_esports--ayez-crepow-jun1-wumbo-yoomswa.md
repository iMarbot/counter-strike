### Roster Details<br />
Team Name: Ex-KRC Genk Esports<br />
Roster: AyeZ, CrePoW, JuN1, Wumbo, yoomswa<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [183](../standings_global.md)<br />
Regional Rank: [124]( ../standings_europe.md)<br />
Final Rank Value:  740.6<br />
<br />
Final Rank Value (740.6) = Starting Rank Value (807.1) + Head To Head Adjustments (-66.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.223[<sup>2</sup>](#table1)

The average of these factors is 0.205<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 807.1
- 400 + ( ( 0.205 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 807.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |      104 | 2024-05-03 | GenOne               | L   | 1.000      | -            | -                | -                | -         |   -19.98 | AyeZ, CrePoW, JuN1, Wumbo, yoomswa           |
|           19 |      188 | 2024-05-01 | Denial (Danish team) | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | 0 (0.000) |     6.74 | AyeZ, CrePoW, JuN1, Wumbo, yoomswa           |
|           18 |     1080 | 2024-04-14 | Mugiwaras            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.035 (0.005)    | 1 (1.000) |    12.79 | AyeZ, CrePoW, dash, Swes, yOOm               |
|           17 |     1082 | 2024-04-14 | Pertinax Esports     | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (1.000) |     6.93 | AyeZ, CrePoW, dash, Swes, yOOm               |
|           16 |     1808 | 2024-03-26 | ALTERNATE aTTaX      | L   | 0.932      | -            | -                | -                | -         |    -7.30 | AyeZ, CrePoW, JuN1, Wumbo, yOOm              |
|           15 |     2937 | 2024-02-29 | GamerLegion Academy  | L   | 0.759      | -            | -                | -                | -         |    -9.89 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm            |
|           14 |     2950 | 2024-02-29 | Lemondogs            | W   | 0.758      | 0.371        | 0.000 (0.000)    | 0.252 (0.071)    | 0 (0.000) |     6.61 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm            |
|           13 |     3151 | 2024-02-24 | GUN5 Esports         | L   | 0.725      | -            | -                | -                | -         |   -15.37 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm            |
|           12 |     3210 | 2024-02-23 | 0to100               | W   | 0.719      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.67 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm            |
|           11 |     3709 | 2024-02-12 | Lilmix               | L   | 0.646      | -            | -                | -                | -         |   -14.07 | AyeZ, CrePoW, MAGILA, Wumbo, yOOm            |
|           10 |     3843 | 2024-02-07 | LODIS                | L   | 0.612      | -            | -                | -                | -         |   -13.28 | asran, fugor, GruBy, Mride, pawkoem          |
|            9 |     3888 | 2024-02-05 | DASH                 | L   | 0.599      | -            | -                | -                | -         |   -10.83 | cairne, Dawy, Flierax, kRyTouS, Merl         |
|            8 |     4376 | 2024-01-24 | Gaimin Gladiators    | L   | 0.519      | -            | -                | -                | -         |    -0.55 | CrePoW, MAGILA, Philong, Wumbo, yOOm         |
|            7 |     4498 | 2024-01-21 | Passion UA           | L   | 0.499      | -            | -                | -                | -         |    -4.33 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            6 |     4730 | 2024-01-17 | GUN5 Esports         | L   | 0.472      | -            | -                | -                | -         |   -10.25 | FinigaN, lov1kus, supra, xiELO, znxxX        |
|            5 |     5573 | 2023-12-15 | Rhyno Esports        | L   | 0.252      | -            | -                | -                | -         |    -2.60 | DDias, Icarus, krazy, snapy, TMKj            |
|            4 |     5611 | 2023-12-14 | Passion UA           | W   | 0.245      | 0.333        | 0.114 (0.009)    | 0.980 (0.080)    | 0 (0.000) |     5.86 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            3 |     5643 | 2023-12-13 | VP.Prodigy           | L   | 0.239      | -            | -                | -                | -         |    -3.60 | CrePoW, Philong, ReFuZR, Wumbo, yOOm         |
|            2 |     5693 | 2023-12-11 | Pungrottorna         | W   | 0.225      | 0.333        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     1.04 | CrePoW, Philong, ReFuZR, Wumbo, yOOm         |
|            1 |     5882 | 2023-12-07 | WOPA Esport          | W   | 0.199      | 0.333        | 0.009 (0.001)    | 0.485 (0.032)    | 0 (0.000) |     2.86 | brzer, buNNy, Gnøffe, Leakz, LUMSEN          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,332.71)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-14 |      1.000 | $1,067.07      | $1,067.07       |
| 2023-12-17 |      0.266 | $1,000.00      | $265.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
