### Roster Details<br />
Team Name: DASH<br />
Roster: cairne, Dawy, Flierax, Merl, Psycho<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [225](../standings_global.md)<br />
Regional Rank: [152]( ../standings_europe.md)<br />
Final Rank Value:  704.6<br />
<br />
Final Rank Value (704.6) = Starting Rank Value (694.6) + Head To Head Adjustments (10.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.210[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.106[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 694.6
- 400 + ( ( 0.145 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 694.6


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
|           44 |      404 | 2024-05-23 | Eternal Fire Academy   | W   | 1.000      | 0.372        | -                | 0.136 (0.051)    | 0 (0.000) |    10.03 | cairne, Dawy, Flierax, Merl, Psycho    |
|           43 |      511 | 2024-05-22 | NOM Esports            | W   | 1.000      | 0.372        | -                | 0.360 (0.134)    | 0 (0.000) |    15.63 | cairne, Dawy, Flierax, Merl, Psycho    |
|           42 |      600 | 2024-05-21 | Dynamo Eclot           | L   | 1.000      | -            | -                | -                | -         |    -6.96 | cairne, Dawy, Flierax, Merl, Psycho    |
|           41 |      615 | 2024-05-21 | Denial                 | W   | 1.000      | 0.372        | -                | 0.138 (0.051)    | 0 (0.000) |    12.13 | cairne, Dawy, Flierax, Merl, Psycho    |
|           40 |      681 | 2024-05-20 | Lemondogs              | W   | 1.000      | 0.372        | -                | 0.314 (0.117)    | 0 (0.000) |    14.27 | cairne, Dawy, Flierax, Merl, Psycho    |
|           39 |      770 | 2024-05-19 | Pera Esports           | L   | 1.000      | -            | -                | -                | -         |    -5.82 | cairne, Dawy, Flierax, Merl, Psycho    |
|           38 |      781 | 2024-05-19 | PCIFIC Espor           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.55 | cairne, Dawy, Flierax, Merl, Psycho    |
|           37 |      904 | 2024-05-18 | Lazer Cats             | L   | 1.000      | -            | -                | -                | -         |   -13.35 | cairne, Dawy, Flierax, Merl, Psycho    |
|           36 |     1001 | 2024-05-17 | Verdant                | L   | 1.000      | -            | -                | -                | -         |    -5.92 | cairne, Dawy, Flierax, Merl, Psycho    |
|           35 |     1008 | 2024-05-17 | Permitta Academy       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.46 | cairne, Dawy, Flierax, Merl, Psycho    |
|           34 |     1083 | 2024-05-16 | V1dar Gaming           | L   | 1.000      | -            | -                | -                | -         |   -10.32 | cairne, Dawy, Flierax, Merl, Psycho    |
|           33 |     1286 | 2024-05-14 | GenOne                 | L   | 1.000      | -            | -                | -                | -         |   -14.50 | cairne, Dawy, Flierax, Merl, Psycho    |
|           32 |     1337 | 2024-05-13 | Permitta Esports       | L   | 1.000      | -            | -                | -                | -         |    -8.06 | cairne, Dawy, Flierax, Merl, Psycho    |
|           31 |     1464 | 2024-05-11 | B8                     | L   | 1.000      | -            | -                | -                | -         |    -3.25 | cairne, Dawy, Flierax, Merl, Psycho    |
|           30 |     1662 | 2024-05-08 | ENTERPRISE esports     | L   | 1.000      | -            | -                | -                | -         |    -8.31 | cairne, Dawy, Flierax, Merl, Psycho    |
|           29 |     2000 | 2024-05-01 | ex-K10                 | W   | 1.000      | 0.372        | 0.005 (0.002)    | 0.517 (0.193)    | 0 (0.000) |    19.74 | cairne, Dawy, Flierax, Merl, Psycho    |
|           28 |     2423 | 2024-04-24 | DMS                    | L   | 0.963      | -            | -                | -                | -         |    -9.16 | cairne, Dawy, Flierax, Merl, Psycho    |
|           27 |     2470 | 2024-04-23 | Aurora Young Blud      | L   | 0.956      | -            | -                | -                | -         |   -12.58 | cairne, Dawy, Flierax, Merl, Psycho    |
|           26 |     2512 | 2024-04-22 | HOTU                   | L   | 0.950      | -            | -                | -                | -         |    -9.64 | cairne, Dawy, Flierax, Merl, Psycho    |
|           25 |     2832 | 2024-04-18 | Lausanne-Sport Esports | W   | 0.922      | 0.372        | 0.002 (0.001)    | 0.306 (0.105)    | 0 (0.000) |    16.39 | cairne, Dawy, Flierax, Merl, Psycho    |
|           24 |     4042 | 2024-03-24 | L&G                    | L   | 0.757      | -            | -                | -                | -         |   -11.67 | cairne, Dawy, esenthial, Flierax, Merl |
|           23 |     4330 | 2024-03-18 | kONO.ECF               | L   | 0.715      | -            | -                | -                | -         |    -5.46 | cairne, Flierax, kRyTouS, Merl, onic   |
|           22 |     4389 | 2024-03-17 | kONO.ECF               | W   | 0.710      | 0.143        | 0.013 (0.001)    | 0.853 (0.087)    | 0 (0.000) |    17.22 | cairne, Flierax, kRyTouS, Merl, onic   |
|           21 |     4414 | 2024-03-16 | nomatter               | W   | 0.704      | -            | -                | -                | 0 (0.000) |     5.28 | cairne, Flierax, kRyTouS, Merl, onic   |
|           20 |     5170 | 2024-03-04 | ghoulsW                | L   | 0.625      | -            | -                | -                | -         |   -15.57 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           19 |     5270 | 2024-03-02 | BetBoom Team           | L   | 0.612      | -            | -                | -                | -         |    -0.48 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           18 |     5284 | 2024-03-02 | ROSOMAHA               | W   | 0.611      | -            | -                | -                | -         |     6.40 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           17 |     5606 | 2024-02-25 | ENTERPRISE esports     | L   | 0.571      | -            | -                | -                | -         |    -3.29 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           16 |     5692 | 2024-02-24 | INGLORIOUS             | L   | 0.564      | -            | -                | -                | -         |    -7.85 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           15 |     5764 | 2024-02-23 | The Chosen Few         | W   | 0.557      | 0.371        | 0.000 (0.000)    | 0.262 (0.054)    | -         |    10.01 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           14 |     5811 | 2024-02-22 | kONO.ECF               | L   | 0.551      | -            | -                | -                | -         |    -4.02 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           13 |     5858 | 2024-02-21 | VP.Prodigy             | L   | 0.544      | -            | -                | -                | -         |    -5.75 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           12 |     6336 | 2024-02-13 | Soda Gaming            | W   | 0.491      | -            | -                | -                | -         |     6.62 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           11 |     6393 | 2024-02-12 | RUBY                   | L   | 0.484      | -            | -                | -                | -         |    -3.58 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|           10 |     6414 | 2024-02-11 | AURA                   | L   | 0.478      | -            | -                | -                | -         |    -9.61 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            9 |     6418 | 2024-02-11 | 500                    | W   | 0.478      | 0.143        | 0.002 (0.000)    | -                | -         |     9.05 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            8 |     6428 | 2024-02-11 | HyperSpirit            | W   | 0.477      | 0.143        | 0.004 (0.000)    | -                | -         |     7.72 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            7 |     6612 | 2024-02-05 | ex-KRC Genk Esports    | W   | 0.438      | 0.371        | 0.000 (0.000)    | -                | -         |     6.87 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            6 |     6661 | 2024-02-04 | Passion UA             | W   | 0.431      | 0.371        | 0.057 (0.009)    | 1.000 (0.160)    | -         |    11.47 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            5 |     6806 | 2024-02-02 | LODIS                  | W   | 0.417      | 0.371        | 0.001 (0.000)    | -                | -         |     5.54 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            4 |     6835 | 2024-02-02 | ghoulsW                | L   | 0.417      | -            | -                | -                | -         |   -10.26 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            3 |     6874 | 2024-02-01 | GamerLegion Academy    | W   | 0.411      | 0.371        | 0.018 (0.003)    | 0.691 (0.105)    | -         |     8.69 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            2 |     7453 | 2024-01-22 | RoundsGG               | W   | 0.344      | -            | -                | -                | -         |     4.40 | cairne, Dawy, Flierax, kRyTouS, Merl   |
|            1 |     7471 | 2024-01-22 | esmagaB                | L   | 0.344      | -            | -                | -                | -         |    -3.08 | cairne, Dawy, Flierax, kRyTouS, Merl   |

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
