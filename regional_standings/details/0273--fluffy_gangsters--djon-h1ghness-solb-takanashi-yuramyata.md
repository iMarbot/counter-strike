### Roster Details<br />
Team Name: FLuffy Gangsters<br />
Roster: Djon, h1ghnesS, SoLb, takanashi, yuramyata<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [273](../standings_global.md)<br />
Regional Rank: [171]( ../standings_europe.md)<br />
Final Rank Value:  641.2<br />
<br />
Final Rank Value (641.2) = Starting Rank Value (558.3) + Head To Head Adjustments (82.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.251[<sup>2</sup>](#table1)
- Opponent Network: 0.068[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.080<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 558.3
- 400 + ( ( 0.080 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 558.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |      517 | 2024-04-24 | LOADING (French team)  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.070 (0.026)    | false (0.000) |     6.70 | Djon, h1ghnesS, SoLb, takanashi, yuramyata     |
|           16 |      601 | 2024-04-22 | LOG Esports            | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     6.24 | Djon, h1ghnesS, SoLb, takanashi, yuramyata     |
|           15 |      821 | 2024-04-19 | Dynamo Eclot           | L   | 1.000      | -            | -                | -                | -             |    -3.04 | Djon, h1ghnesS, SoLb, takanashi, yuramyata     |
|           14 |     1036 | 2024-04-15 | Aurora Young Blud      | W   | 1.000      | 0.371        | 0.017 (0.006)    | 0.422 (0.157)    | false (0.000) |    21.09 | Djon, h1ghnesS, SoLb, takanashi, yuramyata     |
|           13 |     2934 | 2024-02-29 | GODSENT                | L   | 0.759      | -            | -                | -                | -             |    -6.19 | bobeksde, eraa, Golden, Plopski, RuStY         |
|           12 |     2943 | 2024-02-29 | GenOne                 | L   | 0.759      | -            | -                | -                | -             |   -12.51 | AMANEK, bibu, Graviti, Kursy, Razzmo           |
|           11 |     3289 | 2024-02-21 | Team Secret            | W   | 0.706      | 0.371        | 0.000 (0.000)    | 0.368 (0.097)    | false (0.000) |    13.73 | b1st, Djon, h1ghnesS, mo5kow, takanashi        |
|           10 |     3399 | 2024-02-19 | Lausanne-Sport Esports | W   | 0.692      | 0.371        | 0.004 (0.001)    | 0.241 (0.062)    | false (0.000) |    14.71 | b1st, Djon, h1ghnesS, mo5kow, takanashi        |
|            9 |     3634 | 2024-02-14 | ILIN                   | W   | 0.658      | 0.371        | 0.000 (0.000)    | 0.348 (0.085)    | false (0.000) |    10.05 | abiraju, aviva, bogemtdarf, fineshine, lampada |
|            8 |     3710 | 2024-02-12 | Lajtbitexe             | W   | 0.646      | 0.371        | 0.000 (0.000)    | 0.033 (0.008)    | false (0.000) |     9.17 | baljs, eltrzzi, Frontsiderr, PeTeRoOo, suonko  |
|            7 |     3732 | 2024-02-12 | Soda Gaming            | W   | 0.644      | 0.371        | 0.009 (0.002)    | 0.182 (0.043)    | false (0.000) |    14.82 | b1st, Djon, h1ghnesS, mo5kow, takanashi        |
|            6 |     3797 | 2024-02-09 | DMS                    | L   | 0.624      | -            | -                | -                | -             |    -7.60 | AW, H1te, kAlash, sFade8, sm3t                 |
|            5 |     3878 | 2024-02-05 | Ex-Hot Headed Gaming   | W   | 0.599      | 0.371        | 0.000 (0.000)    | 0.117 (0.026)    | false (0.000) |     7.90 | b1st, Djon, h1ghnesS, mo5kow, takanashi        |
|            4 |     4024 | 2024-02-02 | Endpoint               | L   | 0.578      | -            | -                | -                | -             |    -3.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher      |
|            3 |     4081 | 2024-02-01 | ARCRED                 | W   | 0.571      | 0.371        | 0.004 (0.001)    | 0.825 (0.175)    | false (0.000) |    14.84 | 1NVISIBLEE, DSSj, Get_Jeka, shg, synyx         |
|            2 |     4310 | 2024-01-26 | 9Pandas                | L   | 0.532      | -            | -                | -                | -             |    -0.60 | clax, d1Ledez, glowiing, iDISBALANCE, seized   |
|            1 |     4320 | 2024-01-26 | Entropiq               | L   | 0.531      | -            | -                | -                | -             |    -3.28 | c0llins, Marix, mwlky, Oxygen, tiziaN          |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
