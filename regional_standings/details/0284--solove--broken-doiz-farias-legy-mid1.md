### Roster Details<br />
Team Name: SOLOVE<br />
Roster: brokeN, doiz, farias, legy, mid1<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [284](../standings_global.md)<br />
Regional Rank: [60]( ../standings_americas.md)<br />
Final Rank Value:  629.1<br />
<br />
Final Rank Value (629.1) = Starting Rank Value (630.4) + Head To Head Adjustments (-1.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.225[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.4
- 400 + ( ( 0.116 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 630.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     4242 | 2024-01-27 | TEAM ORUGA                     | L   | 0.540      | -            | -                | -                | -             |    -9.46 | brokeN, doiz, farias, legy, mid1      |
|           11 |     4246 | 2024-01-27 | Full House Gaming              | W   | 0.540      | 0.143        | 0.003 (0.000)    | 0.153 (0.012)    | false (0.000) |     9.16 | brokeN, doiz, farias, legy, mid1      |
|           10 |     4253 | 2024-01-27 | Fluxo Demons                   | W   | 0.539      | 0.143        | 0.065 (0.005)    | 0.289 (0.022)    | false (0.000) |    14.31 | brokeN, doiz, farias, legy, mid1      |
|            9 |     4262 | 2024-01-27 | Yawara E-Sports                | L   | 0.539      | -            | -                | -                | -             |    -6.28 | brokeN, doiz, farias, legy, mid1      |
|            8 |     5582 | 2023-12-15 | Yawara E-Sports                | W   | 0.252      | 0.143        | 0.005 (0.000)    | 0.361 (0.013)    | false (0.000) |     5.04 | brokeN, doiz, legy, PremiuM, timid    |
|            7 |     5612 | 2023-12-14 | Hype E-Sports (Brazilian team) | L   | 0.245      | -            | -                | -                | -             |    -4.33 | brokeN, doiz, legy, PremiuM, timid    |
|            6 |     5631 | 2023-12-13 | TIMACETA                       | L   | 0.240      | -            | -                | -                | -             |    -3.51 | brokeN, doiz, legy, PremiuM, timid    |
|            5 |     5664 | 2023-12-12 | Arena Jogue Fácil Esports      | L   | 0.233      | -            | -                | -                | -             |    -3.18 | brokeN, doiz, legy, PremiuM, timid    |
|            4 |     5690 | 2023-12-11 | Arena Jogue Fácil Esports      | L   | 0.226      | -            | -                | -                | -             |    -3.15 | brokeN, doiz, legy, PremiuM, timid    |
|            3 |     5880 | 2023-12-07 | Vex Dragons                    | W   | 0.199      | 0.262        | 0.000 (0.000)    | 0.018 (0.001)    | false (0.000) |     2.78 | brokeN, doiz, legy, PremiuM, timid    |
|            2 |     6258 | 2023-11-29 | Corinthians Esports            | L   | 0.145      | -            | -                | -                | -             |    -2.34 | brokeN, doiz, legy, PremiuM, timid    |
|            1 |     7042 | 2023-11-11 | 9z Academy                     | L   | 0.027      | -            | -                | -                | -             |    -0.39 | AmBiTioN, brokeN, doiz, legy, PremiuM |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($57.97)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-30 |      0.560 | $100.98        | $56.51          |
| 2023-11-11 |      0.027 | $53.57         | $1.46           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
