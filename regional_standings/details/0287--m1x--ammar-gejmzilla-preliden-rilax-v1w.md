### Roster Details<br />
Team Name: M1X<br />
Roster: ammar, gejmzilla, prelideN, rilax, v1w<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [287](../standings_global.md)<br />
Regional Rank: [177]( ../standings_europe.md)<br />
Final Rank Value:  625.2<br />
<br />
Final Rank Value (625.2) = Starting Rank Value (642.6) + Head To Head Adjustments (-17.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.270[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.029[<sup>2</sup>](#table1)

The average of these factors is 0.122<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 642.6
- 400 + ( ( 0.122 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 642.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |       64 | 2024-05-04 | ILLYRIANS             | L   | 1.000      | -            | -                | -                | -             |    -9.91 | ammar, gejmzilla, prelideN, rilax, v1w       |
|           17 |       74 | 2024-05-04 | Regnum                | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.046 (0.007)    | false (0.000) |    17.20 | ammar, gejmzilla, prelideN, rilax, v1w       |
|           16 |      116 | 2024-05-03 | Kum sa Kosova         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.96 | ammar, arbnorz, gejmzilla, prelideN, rilax   |
|           15 |      437 | 2024-04-26 | ILLYRIANS             | L   | 1.000      | -            | -                | -                | -             |   -10.37 | ammar, Dinsanety, gejmzilla, rosoneriii, v1w |
|           14 |     1074 | 2024-04-14 | HEROES (Kosovar team) | L   | 1.000      | -            | -                | -                | -             |   -10.63 | cerber, gulito, Krabeni, makazze, rosoneriii |
|           13 |     2733 | 2024-03-04 | HAVU Gaming           | L   | 0.786      | -            | -                | -                | -             |    -6.22 | gejmzilla, kressy, PrelideN, rilax, v1w      |
|           12 |     4187 | 2024-01-29 | PARIVISION            | L   | 0.553      | -            | -                | -                | -             |    -3.65 | gejmzilla, PALM1, PrelideN, rilax, zur1s     |
|           11 |     5381 | 2023-12-17 | Midnight              | L   | 0.263      | -            | -                | -                | -             |    -4.16 | ammar, cerber, deb0, gejmzilla, v1w          |
|           10 |     5454 | 2023-12-16 | Ezezepanamera         | W   | 0.259      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | true (0.259)  |     1.65 | dilla, gmart1nii, MELLOWi, muLche, noaHH2    |
|            9 |     5943 | 2023-12-06 | Passion UA            | L   | 0.190      | -            | -                | -                | -             |    -0.69 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX |
|            8 |     6044 | 2023-12-03 | HamaKura              | W   | 0.171      | 0.294        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.09 | ammar, cerber, deb0, gejmzilla, v1w          |
|            7 |     6139 | 2023-12-02 | The Witchers          | L   | 0.163      | -            | -                | -                | -             |    -1.58 | fear, Sdaim, smooya, soulfly, synyx          |
|            6 |     6392 | 2023-11-26 | Zero Tenacity         | L   | 0.125      | -            | -                | -                | -             |    -0.56 | ammar, cerber, deb0, gejmzilla, v1w          |
|            5 |     6424 | 2023-11-25 | PSYCHOACTiVE          | W   | 0.118      | 0.143        | 0.000 (0.000)    | 0.019 (0.000)    | false (0.000) |     1.31 | andr1x, DiMKE, Impulse, Katalic, sarenii     |
|            4 |     6478 | 2023-11-24 | ILLYRIANS             | W   | 0.111      | 0.143        | 0.001 (0.000)    | 0.308 (0.005)    | false (0.000) |     2.18 | ammar, cerber, deb0, gejmzilla, v1w          |
|            3 |     6567 | 2023-11-22 | RUR Esports           | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | false (0.000) |     0.97 | ammar, cerber, deb0, gejmzilla, v1w          |
|            2 |     6615 | 2023-11-20 | Zero Tenacity         | L   | 0.086      | -            | -                | -                | -             |    -0.37 | ammar, cerber, deb0, gejmzilla, v1w          |
|            1 |     6871 | 2023-11-15 | Sashi Esport          | L   | 0.052      | -            | -                | -                | -             |    -0.64 | aizy, n1Xen, NutNut, PR1mE, Speedy           |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($315.45)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-17 |      0.265 | $545.37        | $144.57         |
| 2023-12-03 |      0.171 | $1,000.00      | $170.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
