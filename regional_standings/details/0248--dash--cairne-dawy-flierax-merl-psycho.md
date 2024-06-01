### Roster Details<br />
Team Name: DASH<br />
Roster: cairne, Dawy, Flierax, Merl, Psycho<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [248](../standings_global.md)<br />
Regional Rank: [163]( ../standings_europe.md)<br />
Final Rank Value:  684.5<br />
<br />
Final Rank Value (684.5) = Starting Rank Value (683.4) + Head To Head Adjustments (1.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.210[<sup>1</sup>](#table2)
- Bounty Collected: 0.261[<sup>2</sup>](#table1)
- Opponent Network: 0.086[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.139<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.4
- 400 + ( ( 0.139 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 683.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           43 |      396 | 2024-05-23 | Eternal Fire Academy   | W   | 1.000      | 0.372        | -                | 0.136 (0.051)    | 0 (0.000) |    10.90 | cairne, Dawy, Flierax, Merl, Psycho    |
|           42 |      504 | 2024-05-22 | NOM Esports            | W   | 1.000      | 0.372        | -                | 0.360 (0.134)    | 0 (0.000) |    16.47 | cairne, Dawy, Flierax, Merl, Psycho    |
|           41 |      589 | 2024-05-21 | Dynamo Eclot           | L   | 1.000      | -            | -                | -                | -         |    -6.00 | cairne, Dawy, Flierax, Merl, Psycho    |
|           40 |      604 | 2024-05-21 | Denial                 | W   | 1.000      | 0.372        | -                | 0.138 (0.051)    | 0 (0.000) |    13.24 | cairne, Dawy, Flierax, Merl, Psycho    |
|           39 |      670 | 2024-05-20 | Lemondogs              | W   | 1.000      | 0.372        | -                | 0.274 (0.102)    | 0 (0.000) |    14.94 | cairne, Dawy, Flierax, Merl, Psycho    |
|           38 |      758 | 2024-05-19 | Pera Esports           | L   | 1.000      | -            | -                | -                | -         |    -5.03 | cairne, Dawy, Flierax, Merl, Psycho    |
|           37 |      769 | 2024-05-19 | PCIFIC Espor           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.23 | cairne, Dawy, Flierax, Merl, Psycho    |
|           36 |      892 | 2024-05-18 | Lazer Cats             | L   | 1.000      | -            | -                | -                | -         |   -12.23 | cairne, Dawy, Flierax, Merl, Psycho    |
|           35 |      989 | 2024-05-17 | Verdant                | L   | 1.000      | -            | -                | -                | -         |    -5.37 | cairne, Dawy, Flierax, Merl, Psycho    |
|           34 |      996 | 2024-05-17 | Permitta Academy       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.19 | cairne, Dawy, Flierax, Merl, Psycho    |
|           33 |     1073 | 2024-05-16 | V1dar Gaming           | L   | 1.000      | -            | -                | -                | -         |    -9.54 | cairne, Dawy, Flierax, Merl, Psycho    |
|           32 |     1275 | 2024-05-14 | GenOne                 | L   | 1.000      | -            | -                | -                | -         |   -13.14 | cairne, Dawy, Flierax, Merl, Psycho    |
|           31 |     1325 | 2024-05-13 | Permitta Esports       | L   | 1.000      | -            | -                | -                | -         |    -7.82 | cairne, Dawy, Flierax, Merl, Psycho    |
|           30 |     1451 | 2024-05-11 | B8                     | L   | 1.000      | -            | -                | -                | -         |    -2.65 | cairne, Dawy, Flierax, Merl, Psycho    |
|           29 |     1644 | 2024-05-08 | ENTERPRISE esports     | L   | 1.000      | -            | -                | -                | -         |    -7.83 | cairne, Dawy, Flierax, Merl, Psycho    |
|           28 |     2379 | 2024-04-24 | DMS                    | L   | 0.963      | -            | -                | -                | -         |    -9.04 | cairne, Dawy, Flierax, Merl, Psycho    |
|           27 |     2422 | 2024-04-23 | Aurora Young Blud      | L   | 0.956      | -            | -                | -                | -         |   -12.29 | cairne, Dawy, Flierax, Merl, Psycho    |
|           26 |     2460 | 2024-04-22 | HOTU                   | L   | 0.950      | -            | -                | -                | -         |    -9.51 | cairne, Dawy, Flierax, Merl, Psycho    |
|           25 |     2776 | 2024-04-18 | Lausanne-Sport Esports | W   | 0.922      | 0.372        | 0.002 (0.001)    | 0.257 (0.088)    | 0 (0.000) |    14.66 | cairne, Dawy, Flierax, Merl, Psycho    |
|           24 |     3945 | 2024-03-24 | L&G                    | L   | 0.757      | -            | -                | -                | -         |   -11.36 | cairne, Dawy, esenthial, Flierax, Merl |
|           23 |     4225 | 2024-03-18 | kONO.ECF               | L   | 0.715      | -            | -                | -                | -         |    -5.79 | cairne, Flierax, kRyTouS, Merl, onic   |
|           22 |     4283 | 2024-03-17 | kONO.ECF               | W   | 0.710      | 0.143        | 0.013 (0.001)    | 0.778 (0.079)    | 0 (0.000) |    16.88 | cairne, Flierax, kRyTouS, Merl, onic   |
|           21 |     4308 | 2024-03-16 | nomatter               | W   | 0.704      | -            | -                | -                | 0 (0.000) |     5.52 | cairne, Flierax, kRyTouS, Merl, onic   |
|           20 |     5024 | 2024-03-04 | ghoulsW                | L   | 0.625      | -            | -                | -                | -         |   -15.36 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           19 |     5122 | 2024-03-02 | BetBoom Team           | L   | 0.612      | -            | -                | -                | -         |    -0.46 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           18 |     5136 | 2024-03-02 | ROSOMAHA               | W   | 0.611      | 0.143        | 0.000 (0.000)    | -                | 0 (0.000) |     6.66 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           17 |     5448 | 2024-02-25 | ENTERPRISE esports     | L   | 0.571      | -            | -                | -                | -         |    -3.51 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           16 |     5532 | 2024-02-24 | INGLORIOUS             | L   | 0.564      | -            | -                | -                | -         |    -7.68 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           15 |     5604 | 2024-02-23 | The Chosen Few         | W   | 0.557      | 0.371        | 0.002 (0.000)    | 0.262 (0.054)    | -         |    10.63 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           14 |     5651 | 2024-02-22 | kONO.ECF               | L   | 0.551      | -            | -                | -                | -         |    -4.17 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           13 |     5695 | 2024-02-21 | VP.Prodigy             | L   | 0.544      | -            | -                | -                | -         |    -5.88 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           12 |     6151 | 2024-02-13 | Soda Gaming            | W   | 0.491      | -            | -                | -                | -         |     6.06 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           11 |     6206 | 2024-02-12 | RUBY                   | L   | 0.484      | -            | -                | -                | -         |    -3.43 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           10 |     6226 | 2024-02-11 | AURA                   | L   | 0.478      | -            | -                | -                | -         |    -9.52 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            9 |     6230 | 2024-02-11 | 500                    | W   | 0.478      | 0.143        | 0.002 (0.000)    | 0.479 (0.033)    | -         |     9.18 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            8 |     6240 | 2024-02-11 | HyperSpirit            | W   | 0.477      | 0.143        | 0.004 (0.000)    | -                | -         |     8.00 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            7 |     6414 | 2024-02-05 | ex-KRC Genk Esports    | W   | 0.438      | 0.371        | 0.000 (0.000)    | -                | -         |     5.93 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            6 |     6458 | 2024-02-04 | Passion UA             | W   | 0.431      | 0.371        | 0.057 (0.009)    | 1.000 (0.160)    | -         |    11.49 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            5 |     6603 | 2024-02-02 | LODIS                  | W   | 0.417      | 0.371        | 0.001 (0.000)    | -                | -         |     5.57 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            4 |     6630 | 2024-02-02 | ghoulsW                | L   | 0.417      | -            | -                | -                | -         |   -10.12 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            3 |     6668 | 2024-02-01 | GamerLegion Academy    | W   | 0.411      | 0.371        | 0.018 (0.003)    | 0.691 (0.105)    | -         |     8.86 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            2 |     7212 | 2024-01-22 | RoundsGG               | W   | 0.344      | -            | -                | -                | -         |     4.33 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            1 |     7228 | 2024-01-22 | esmagaB                | L   | 0.344      | -            | -                | -                | -         |    -2.99 | cairne, Dawy, Flierax, kRyTouS, Merl   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($51.22)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
