### Roster Details<br />
Team Name: Myth Avenue Gaming<br />
Roster: Derek, Fatalityyy, Jaytzy, Johnchen, WasteOfAmmo<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [185](../standings_global.md)<br />
Regional Rank: [28]( ../standings_asia.md)<br />
Final Rank Value:  739.1<br />
<br />
Final Rank Value (739.1) = Starting Rank Value (713.9) + Head To Head Adjustments (25.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.265[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 713.9
- 400 + ( ( 0.158 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 713.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           27 |     2383 | 2024-03-12 | -72C                        | L   | 0.837      | -            | -                | -                | -             |   -11.07 | Derek, Fatalityyy, Jaytzy, Johnchen, WasteOfAmmo |
|           26 |     2470 | 2024-03-10 | High Five (Chinese team)    | L   | 0.823      | -            | -                | -                | -             |    -9.69 | Derek, Jaytzy, Kayje, SiameseCv, WasteOfAmmo     |
|           25 |     2518 | 2024-03-09 | ATOX Esports                | L   | 0.817      | -            | -                | -                | -             |    -3.65 | Derek, Jaytzy, Kayje, SiameseCv, WasteOfAmmo     |
|           24 |     2548 | 2024-03-07 | High Five (Chinese team)    | L   | 0.808      | -            | -                | -                | -             |    -9.79 | Derek, Jaytzy, Kayje, SiameseCv, WasteOfAmmo     |
|           23 |     2646 | 2024-03-06 | SR Nacague                  | W   | 0.797      | 0.250        | 0.000 (0.000)    | 0.061 (0.012)    | false (0.000) |     4.58 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           22 |     2658 | 2024-03-06 | Jadeite                     | W   | 0.796      | 0.143        | 0.000 (0.000)    | -                | false (0.000) |     2.63 | Derek, Jaytzy, Kayje, SiameseCv, WasteOfAmmo     |
|           21 |     3510 | 2024-02-17 | High Five (Chinese team)    | L   | 0.676      | -            | -                | -                | -             |    -8.97 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           20 |     3546 | 2024-02-16 | GR Gaming                   | W   | 0.670      | 0.143        | 0.006 (0.001)    | 0.495 (0.047)    | false (0.000) |    12.75 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           19 |     3553 | 2024-02-16 | Lynn Vision Gaming          | L   | 0.669      | -            | -                | -                | -             |    -1.31 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           18 |     3604 | 2024-02-15 | SEAW                        | W   | 0.663      | 0.143        | 0.000 (0.000)    | 0.067 (0.006)    | false (0.000) |     3.99 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           17 |     3643 | 2024-02-14 | -72C                        | W   | 0.657      | 0.143        | 0.003 (0.000)    | 0.300 (0.028)    | false (0.000) |    10.93 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           16 |     3650 | 2024-02-14 | LYG Gaming                  | W   | 0.657      | 0.143        | 0.004 (0.000)    | 0.380 (0.036)    | false (0.000) |    11.15 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           15 |     3691 | 2024-02-13 | Team NKT                    | W   | 0.650      | 0.303        | 0.016 (0.003)    | 0.259 (0.051)    | false (0.000) |    12.62 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           14 |     3700 | 2024-02-13 | SR Nacague                  | W   | 0.649      | 0.303        | 0.000 (0.000)    | -                | false (0.000) |     2.87 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           13 |     3781 | 2024-02-09 | Jadeite                     | W   | 0.629      | -            | -                | -                | false (0.000) |     2.65 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           12 |     3808 | 2024-02-08 | Revolution                  | W   | 0.622      | 0.303        | -                | 0.042 (0.008)    | false (0.000) |     5.57 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           11 |     3835 | 2024-02-08 | SEAW                        | W   | 0.616      | 0.303        | -                | 0.067 (0.012)    | -             |     4.24 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|           10 |     4371 | 2024-01-24 | Team NKT                    | L   | 0.522      | -            | -                | -                | -             |    -6.92 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            9 |     4399 | 2024-01-24 | Noobs But Diligent          | L   | 0.517      | -            | -                | -                | -             |    -6.83 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            8 |     4444 | 2024-01-22 | GR Gaming                   | L   | 0.509      | -            | -                | -                | -             |    -6.30 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            7 |     4446 | 2024-01-22 | Aravt                       | W   | 0.509      | 0.143        | -                | 0.143 (0.010)    | -             |     5.06 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            6 |     4503 | 2024-01-21 | Troublemakers (Kyrgyz team) | L   | 0.498      | -            | -                | -                | -             |    -9.17 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            5 |     4518 | 2024-01-20 | Gods Reign                  | W   | 0.495      | 0.143        | 0.174 (0.012)    | 0.479 (0.034)    | -             |    12.19 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            4 |     4623 | 2024-01-19 | Drippy Lab                  | W   | 0.482      | -            | -                | -                | -             |     2.25 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            3 |     4745 | 2024-01-17 | Gods Reign                  | L   | 0.471      | -            | -                | -                | -             |    -3.23 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            2 |     4754 | 2024-01-17 | RESILIENCE                  | W   | 0.470      | -            | -                | -                | -             |     2.17 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |
|            1 |     4764 | 2024-01-17 | Enigma Gaming               | W   | 0.469      | 0.143        | 0.001 (0.000)    | -                | -             |     6.48 | ariucle, Derek, Jaytzy, Tugu, WasteOfAmmo        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,950.69)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
