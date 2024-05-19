### Roster Details<br />
Team Name: VaselineWorms<br />
Roster: aliot, kashl1d, relaxxie, Twizell, zweih<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [289](../standings_global.md)<br />
Regional Rank: [179]( ../standings_europe.md)<br />
Final Rank Value:  623.9<br />
<br />
Final Rank Value (623.9) = Starting Rank Value (655.2) + Head To Head Adjustments (-31.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.2
- 400 + ( ( 0.129 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 655.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      190 | 2024-05-01 | Aurora Young Blud               | W   | 1.000      | 0.371        | 0.017 (0.006)    | 0.422 (0.157)    | false (0.000) |    22.58 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           17 |      474 | 2024-04-25 | Lemondogs                       | L   | 1.000      | -            | -                | -                | -             |   -17.72 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           16 |      883 | 2024-04-18 | Rustec                          | L   | 1.000      | -            | -                | -                | -             |   -13.67 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           15 |     1232 | 2024-04-10 | GenOne                          | L   | 1.000      | -            | -                | -                | -             |   -17.10 | aliot, kashl1d, relaxxie, Twizell, zweih   |
|           14 |     2957 | 2024-02-29 | Golden Sword                    | W   | 0.758      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     4.17 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           13 |     3104 | 2024-02-25 | 1win                            | L   | 0.731      | -            | -                | -                | -             |    -7.82 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           12 |     3307 | 2024-02-21 | GUN5 Esports                    | L   | 0.705      | -            | -                | -                | -             |   -11.66 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           11 |     3319 | 2024-02-21 | ILIN                            | L   | 0.704      | -            | -                | -                | -             |   -13.21 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|           10 |     3414 | 2024-02-19 | RoundsGG                        | W   | 0.691      | 0.371        | 0.000 (0.000)    | 0.170 (0.044)    | false (0.000) |    11.74 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            9 |     3437 | 2024-02-18 | Cerberus eSports (Russian team) | W   | 0.686      | 0.284        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.49 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            8 |     4188 | 2024-01-29 | Team Spirit Academy             | L   | 0.553      | -            | -                | -                | -             |    -5.23 | alpha, baz, keegaN, Magnojez, notineki     |
|            7 |     4711 | 2024-01-17 | GUN5 Esports                    | L   | 0.473      | -            | -                | -                | -             |    -7.34 | FinigaN, lov1kus, supra, xiELO, znxxX      |
|            6 |     4737 | 2024-01-17 | 00 Nation                       | W   | 0.472      | 0.143        | 0.000 (0.000)    | 0.048 (0.003)    | false (0.000) |     4.45 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            5 |     5328 | 2023-12-18 | LF0                             | W   | 0.271      | 0.143        | 0.006 (0.000)    | 0.026 (0.001)    | false (0.000) |     4.12 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            4 |     5330 | 2023-12-18 | Lewandownskie                   | W   | 0.270      | 0.143        | 0.004 (0.000)    | 0.181 (0.007)    | false (0.000) |     4.46 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            3 |     5376 | 2023-12-17 | Team OWL                        | W   | 0.264      | 0.143        | 0.000 (0.000)    | 0.036 (0.001)    | false (0.000) |     2.32 | aliot, kashl1d, Muk0s, relaxxie, zweih     |
|            2 |     5398 | 2023-12-17 | BAKS Esports                    | W   | 0.263      | 0.143        | 0.003 (0.000)    | 0.084 (0.003)    | false (0.000) |     4.21 | datet, elocurse, Middlesex, reyoz, twizell |
|            1 |     5500 | 2023-12-16 | VP.Prodigy                      | L   | 0.256      | -            | -                | -                | -             |    -2.16 | aliot, kashl1d, Muk0s, relaxxie, zweih     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($171.56)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
