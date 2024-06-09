### Roster Details<br />
Team Name: eSports Recife<br />
Roster: DANVIET, farias, PremiuM, voltera, xns<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [168](../standings_global.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
Final Rank Value:  765.2<br />
<br />
Final Rank Value (765.2) = Starting Rank Value (675.5) + Head To Head Adjustments (89.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.044[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.136<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 675.5
- 400 + ( ( 0.136 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 675.5


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
|           32 |      114 | 2024-05-28 | Hype Esports           | W   | 1.000      | 0.143        | -                | 0.218 (0.031)    | 0 (0.000) |    12.48 | DANVIET, farias, PremiuM, voltera, xns |
|           31 |      119 | 2024-05-28 | Sensei Team            | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.482 (0.069)    | 0 (0.000) |    15.82 | DANVIET, farias, PremiuM, voltera, xns |
|           30 |      130 | 2024-05-28 | Bounty Hunters Esports | L   | 1.000      | -            | -                | -                | -         |   -19.50 | DANVIET, farias, PremiuM, voltera, xns |
|           29 |      153 | 2024-05-27 | Full House Gaming      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.205 (0.029)    | 0 (0.000) |    12.08 | DANVIET, farias, PremiuM, voltera, xns |
|           28 |      187 | 2024-05-27 | Corinthians Esports    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.06 | DANVIET, farias, PremiuM, voltera, xns |
|           27 |      286 | 2024-05-25 | Imperium Nexus eSports | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.22 | DANVIET, farias, PremiuM, voltera, xns |
|           26 |      335 | 2024-05-24 | Vikings KR             | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.313 (0.045)    | 0 (0.000) |    16.88 | DANVIET, farias, PremiuM, voltera, xns |
|           25 |      344 | 2024-05-24 | 9z Academy             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.311 (0.044)    | 0 (0.000) |    12.61 | DANVIET, farias, PremiuM, voltera, xns |
|           24 |      389 | 2024-05-23 | Sensei Team            | L   | 1.000      | -            | -                | -                | -         |   -14.55 | DANVIET, farias, PremiuM, voltera, xns |
|           23 |      456 | 2024-05-22 | paiN Gaming Academy    | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    15.25 | DANVIET, farias, PremiuM, voltera, xns |
|           22 |      662 | 2024-05-20 | Yawara E-Sports        | L   | 1.000      | -            | -                | -                | -         |   -18.23 | DANVIET, farias, PremiuM, voltera, xns |
|           21 |     1058 | 2024-05-16 | TIME DE PESO           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.90 | DANVIET, farias, PremiuM, voltera, xns |
|           20 |     2041 | 2024-04-30 | Full House Gaming      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.205 (0.029)    | 0 (0.000) |    15.01 | DANVIET, farias, PremiuM, voltera, xns |
|           19 |     2125 | 2024-04-28 | Sensei Team            | W   | 0.991      | 0.143        | 0.003 (0.000)    | 0.482 (0.068)    | -         |    18.37 | DANVIET, farias, PremiuM, voltera, xns |
|           18 |     2177 | 2024-04-27 | Full House Gaming      | L   | 0.985      | -            | -                | -                | -         |   -15.48 | DANVIET, farias, PremiuM, voltera, xns |
|           17 |     2189 | 2024-04-27 | Smoke Gaming           | W   | 0.985      | -            | -                | -                | -         |    11.86 | DANVIET, farias, PremiuM, voltera, xns |
|           16 |     2194 | 2024-04-27 | NIGERIA 96             | W   | 0.984      | 0.143        | 0.001 (0.000)    | 0.140 (0.020)    | -         |    12.70 | DANVIET, farias, PremiuM, voltera, xns |
|           15 |     2204 | 2024-04-27 | CSGONET                | W   | 0.984      | -            | -                | -                | -         |     8.53 | DANVIET, farias, PremiuM, voltera, xns |
|           14 |     2950 | 2024-04-16 | ODDIK                  | L   | 0.912      | -            | -                | -                | -         |    -5.84 | DANVIET, farias, PremiuM, voltera, xns |
|           13 |     3079 | 2024-04-13 | Corinthians Esports    | L   | 0.891      | -            | -                | -                | -         |   -13.67 | DANVIET, farias, PremiuM, voltera, xns |
|           12 |     3127 | 2024-04-12 | ATECUBANOS             | W   | 0.885      | -            | -                | -                | -         |     4.69 | DANVIET, farias, PremiuM, voltera, xns |
|           11 |     3129 | 2024-04-12 | SoJoga                 | W   | 0.885      | -            | -                | -                | -         |    12.34 | DANVIET, farias, PremiuM, voltera, xns |
|           10 |     3712 | 2024-04-01 | Vikings KR             | L   | 0.811      | -            | -                | -                | -         |   -11.72 | honda, JLK, ksloks, realz1n, rem1x     |
|            9 |     3796 | 2024-03-29 | MIBR Academy           | W   | 0.791      | 0.143        | 0.005 (0.001)    | 0.448 (0.051)    | -         |    13.75 | bobz, card, max, mlhzin, nicks         |
|            8 |     4008 | 2024-03-25 | TIME DE PESO           | W   | 0.764      | -            | -                | -                | -         |     6.16 | fbz, flpzin, gon, guH, stainzin        |
|            7 |     4064 | 2024-03-23 | ex-Martians            | L   | 0.752      | -            | -                | -                | -         |   -13.01 | DANVIET, farias, Lineko, PremiuM, xns  |
|            6 |     4068 | 2024-03-23 | CSGONET                | W   | 0.752      | -            | -                | -                | -         |     6.77 | DANVIET, farias, Lineko, PremiuM, xns  |
|            5 |     4072 | 2024-03-23 | Formula 1              | W   | 0.751      | -            | -                | -                | -         |    10.59 | cLd, Ogoid, Scoreed, strawdeuS, thz    |
|            4 |     4083 | 2024-03-23 | Full House Gaming      | L   | 0.751      | -            | -                | -                | -         |   -11.62 | arcz, balencyy, lucky-, RoDfps_, shun7 |
|            3 |     4089 | 2024-03-23 | pugdesonesto           | W   | 0.751      | 0.143        | 0.001 (0.000)    | -                | -         |    10.01 | freitas, imoto, kxr, protado, vzn      |
|            2 |     4157 | 2024-03-21 | Intense Game           | L   | 0.738      | -            | -                | -                | -         |    -9.78 | bsd, ckzao, diozera, fREQ, mxa         |
|            1 |     4175 | 2024-03-21 | FURIA Academy          | L   | 0.738      | -            | -                | -                | -         |   -13.99 | Bruninho, cerolzin, GYZER, kye, mello  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($663.78)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-30 |      1.000 | $586.12        | $586.12         |
| 2024-03-26 |      0.772 | $100.52        | $77.66          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
