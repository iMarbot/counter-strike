### Roster Details<br />
Team Name: LYG Gaming<br />
Roster: deffen, Haski4, Sange, Soundwave, ZinGY<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [125](../standings_global.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
Final Rank Value:  810.0<br />
<br />
Final Rank Value (810.0) = Starting Rank Value (785.1) + Head To Head Adjustments (25.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.294[<sup>1</sup>](#table2)
- Bounty Collected: 0.373[<sup>2</sup>](#table1)
- Opponent Network: 0.110[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.194<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 785.1
- 400 + ( ( 0.194 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 785.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |      742 | 2024-04-20 | High Five (Chinese team)    | W   | 1.000      | 0.417        | 0.045 (0.019)    | 0.282 (0.117)    | false (0.000) |    13.51 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           43 |      755 | 2024-04-20 | High Five (Chinese team)    | W   | 1.000      | 0.417        | 0.045 (0.019)    | 0.282 (0.117)    | false (0.000) |    14.75 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           42 |      966 | 2024-04-17 | Team NKT                    | L   | 1.000      | -            | -                | -                | -             |   -25.20 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           41 |     1010 | 2024-04-16 | 2ez Gaming                  | W   | 1.000      | -            | -                | -                | false (0.000) |     2.67 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           40 |     1236 | 2024-04-10 | Clutch Gaming               | L   | 1.000      | -            | -                | -                | -             |   -16.77 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           39 |     1241 | 2024-04-10 | Clutch Gaming               | L   | 1.000      | -            | -                | -                | -             |   -18.30 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           38 |     1298 | 2024-04-09 | The MongolZ                 | L   | 1.000      | -            | -                | -                | -             |    -0.58 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           37 |     1301 | 2024-04-09 | The MongolZ                 | L   | 1.000      | -            | -                | -                | -             |    -0.58 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           36 |     1561 | 2024-04-03 | The MongolZ                 | L   | 0.983      | -            | -                | -                | -             |    -0.60 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           35 |     1588 | 2024-04-02 | Lynn Vision Gaming          | L   | 0.977      | -            | -                | -                | -             |    -3.12 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           34 |     1593 | 2024-04-02 | The MongolZ                 | W   | 0.976      | 0.143        | 0.292 (0.041)    | 0.663 (0.092)    | false (0.000) |    30.23 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           33 |     1665 | 2024-03-29 | The QUBE Esports            | W   | 0.951      | 0.417        | 0.004 (0.002)    | 0.168 (0.066)    | false (0.000) |    13.51 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           32 |     1667 | 2024-03-29 | The QUBE Esports            | W   | 0.951      | 0.417        | 0.004 (0.002)    | 0.168 (0.066)    | false (0.000) |    14.69 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           31 |     1759 | 2024-03-27 | ZEUSGG                      | L   | 0.937      | -            | -                | -                | -             |   -23.76 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           30 |     1762 | 2024-03-27 | ZEUSGG                      | W   | 0.937      | -            | -                | -                | false (0.000) |     5.37 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           29 |     2273 | 2024-03-14 | ATOX Esports                | L   | 0.851      | -            | -                | -                | -             |    -4.75 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           28 |     2278 | 2024-03-14 | ATOX Esports                | W   | 0.851      | 0.417        | 0.112 (0.040)    | 0.769 (0.273)    | false (0.000) |    22.52 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           27 |     2337 | 2024-03-13 | TYLOO                       | W   | 0.843      | 0.143        | 0.131 (0.016)    | 0.592 (0.071)    | false (0.000) |    22.05 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           26 |     2340 | 2024-03-13 | The Huns Esports            | W   | 0.843      | 0.143        | -                | 0.434 (0.052)    | false (0.000) |    18.73 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           25 |     2382 | 2024-03-12 | Troublemakers (Kyrgyz team) | W   | 0.837      | -            | -                | -                | -             |    10.32 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           24 |     2640 | 2024-03-06 | Gods Reign                  | W   | 0.797      | 0.417        | 0.174 (0.058)    | 0.479 (0.159)    | -             |    17.06 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           23 |     2648 | 2024-03-06 | Gods Reign                  | L   | 0.797      | -            | -                | -                | -             |    -7.93 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           22 |     2709 | 2024-03-05 | GR Gaming                   | L   | 0.790      | -            | -                | -                | -             |    -7.79 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           21 |     2712 | 2024-03-05 | GR Gaming                   | L   | 0.790      | -            | -                | -                | -             |    -8.28 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           20 |     3317 | 2024-02-21 | MIRAI Gaming                | L   | 0.704      | -            | -                | -                | -             |   -13.04 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           19 |     3322 | 2024-02-21 | MIRAI Gaming                | L   | 0.704      | -            | -                | -                | -             |   -13.84 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           18 |     3421 | 2024-02-19 | Born In Far East            | W   | 0.690      | 0.417        | 0.003 (0.001)    | -                | -             |     9.43 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           17 |     3424 | 2024-02-19 | Born In Far East            | W   | 0.690      | -            | -                | -                | -             |    10.02 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           16 |     3512 | 2024-02-16 | VexX Gaming                 | L   | 0.674      | -            | -                | -                | -             |   -12.04 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           15 |     3650 | 2024-02-14 | Myth Avenue Gaming          | L   | 0.657      | -            | -                | -                | -             |   -11.15 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           14 |     3683 | 2024-02-13 | -72C                        | L   | 0.651      | -            | -                | -                | -             |   -10.57 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           13 |     3689 | 2024-02-13 | -72C                        | W   | 0.651      | 0.417        | -                | 0.300 (0.081)    | -             |    10.12 | deffen, Haski4, Sange, Soundwave, ZinGY        |
|           12 |     4393 | 2024-01-24 | Wings Up Gaming             | L   | 0.517      | -            | -                | -                | -             |    -8.70 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|           11 |     4398 | 2024-01-24 | Gods Reign                  | W   | 0.517      | 0.143        | 0.174 (0.013)    | -                | -             |    11.44 | clouda, Crazy_Gamer, CycloneF, f1redup, Ph1NNN |
|           10 |     4489 | 2024-01-22 | Aravt                       | L   | 0.504      | -            | -                | -                | -             |   -12.15 | fury5k, MagnumZ, NEUZ, ROUX, tamir             |
|            9 |     4844 | 2024-01-15 | The Huns Esports            | L   | 0.456      | -            | -                | -                | -             |    -4.74 | AceX, Haski4, Sange, Soundwave, ZinGY          |
|            8 |     5946 | 2023-12-06 | The MongolZ                 | L   | 0.190      | -            | -                | -                | -             |    -0.05 | Haski4, Sange, Soundwave, zeins, ZinGY         |
|            7 |     6002 | 2023-12-05 | Clutch Gaming               | W   | 0.184      | -            | -                | -                | -             |     2.45 | Haski4, Sange, Soundwave, zeins, ZinGY         |
|            6 |     6141 | 2023-12-02 | GR Gaming                   | L   | 0.163      | -            | -                | -                | -             |    -2.35 | AceX, Haski4, Sange, zeins, ZinGY              |
|            5 |     6144 | 2023-12-02 | EXO SIA                     | W   | 0.162      | -            | -                | -                | -             |     0.53 | Chinits, craigy, Jaro, mikozu, P4P1CH1NO       |
|            4 |     6574 | 2023-11-22 | -72C                        | W   | 0.097      | -            | -                | -                | -             |     1.54 | 1nhuman, borosto, forzetsky, m3wsu, shandarez  |
|            3 |     6847 | 2023-11-16 | NewHappy                    | L   | 0.056      | -            | -                | -                | -             |    -1.01 | AceX, Haski4, Sange, Soundwave, zeins          |
|            2 |     6891 | 2023-11-15 | Rare Atom                   | W   | 0.050      | -            | -                | -                | -             |     0.71 | AceX, Haski4, Sange, Soundwave, zeins          |
|            1 |     6937 | 2023-11-14 | NewHappy                    | W   | 0.044      | -            | -                | -                | -             |     0.59 | Haski4, Sange, Soundwave, zeins, ZinGY         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($622.22)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-17 |      0.681 | $500.00        | $340.25         |
| 2023-12-10 |      0.217 | $1,300.00      | $281.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
