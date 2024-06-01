### Roster Details<br />
Team Name: Legacy<br />
Roster: b4rtiN, dumau, latto, NEKIZ, saadzin<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [48](../standings_global.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
Final Rank Value:  1058.6<br />
<br />
Final Rank Value (1058.6) = Starting Rank Value (1012.0) + Head To Head Adjustments (46.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.389[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.081[<sup>2</sup>](#table1)
- LAN Wins: 0.348[<sup>2</sup>](#table1)

The average of these factors is 0.301<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1012.0
- 400 + ( ( 0.301 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1012.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      476 | 2024-05-22 | NRG              | L   | 1.000      | -            | -                | -                | -         |   -19.66 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           33 |      537 | 2024-05-21 | Carpe Diem       | W   | 1.000      | 0.384        | -                | 0.243 (0.093)    | 0 (0.000) |     3.90 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           32 |      945 | 2024-05-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -21.07 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           31 |     1021 | 2024-05-16 | MIGHT            | W   | 1.000      | 0.143        | -                | 0.207 (0.030)    | 0 (0.000) |     2.30 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           30 |     1026 | 2024-05-16 | underdogs        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.69 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           29 |     1031 | 2024-05-16 | MishMash Gaming  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.64 | b4rtiN, dumau, latto, NEKIZ, saadzin  |
|           28 |     2670 | 2024-04-19 | M80              | L   | 0.932      | -            | -                | -                | -         |    -8.29 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           27 |     2738 | 2024-04-18 | Elevate          | W   | 0.926      | 0.143        | 0.012 (0.002)    | 0.475 (0.063)    | 0 (0.000) |     7.31 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           26 |     2744 | 2024-04-18 | Team Liquid      | L   | 0.925      | -            | -                | -                | -         |    -1.38 | b4rtiN, dumau, latto, NEKIZ, Stewie2K |
|           25 |     4140 | 2024-03-20 | The MongolZ      | L   | 0.729      | -            | -                | -                | -         |    -1.46 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           24 |     4177 | 2024-03-19 | Apeks            | W   | 0.723      | 1.000        | 0.085 (0.062)    | 0.345 (0.249)    | 1 (0.723) |    16.13 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           23 |     4218 | 2024-03-18 | GamerLegion      | L   | 0.716      | -            | -                | -                | -         |    -6.33 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           22 |     4238 | 2024-03-17 | Cloud9           | L   | 0.711      | -            | -                | -                | -         |    -2.01 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           21 |     4265 | 2024-03-17 | FURIA Esports    | W   | 0.710      | 1.000        | 0.138 (0.098)    | 0.267 (0.190)    | 1 (0.710) |    19.71 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           20 |     5037 | 2024-03-04 | M80              | W   | 0.624      | 0.143        | 0.136 (0.012)    | 0.525 (0.047)    | 1 (0.624) |    14.98 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           19 |     5060 | 2024-03-03 | MIBR             | W   | 0.618      | 0.143        | 0.307 (0.027)    | 0.512 (0.045)    | 1 (0.618) |    18.47 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           18 |     5132 | 2024-03-02 | Nouns Esports    | W   | 0.611      | 0.143        | 0.071 (0.006)    | 0.507 (0.044)    | 1 (0.611) |     7.35 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           17 |     5219 | 2024-03-01 | paiN Gaming      | L   | 0.605      | -            | -                | -                | -         |    -0.83 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           16 |     7204 | 2024-01-22 | Sharks Esports   | L   | 0.346      | -            | -                | -                | -         |    -7.26 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           15 |     7313 | 2024-01-20 | RED Canids       | W   | 0.331      | 0.143        | 0.076 (0.004)    | -                | -         |     4.82 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           14 |     7386 | 2024-01-19 | paiN Gaming      | W   | 0.326      | 0.143        | 0.463 (0.022)    | -                | -         |     9.92 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           13 |     7397 | 2024-01-19 | 9z Team          | W   | 0.324      | 0.143        | 0.107 (0.005)    | 0.547 (0.025)    | -         |     8.37 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           12 |     7611 | 2024-01-16 | RED Canids       | L   | 0.306      | -            | -                | -                | -         |    -5.01 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           11 |     7617 | 2024-01-16 | w7m esports      | W   | 0.306      | -            | -                | -                | -         |     2.01 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|           10 |     7625 | 2024-01-16 | Imperial Esports | W   | 0.305      | 0.143        | 0.372 (0.016)    | 0.582 (0.025)    | -         |     9.17 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            9 |     7700 | 2024-01-15 | Galorys          | W   | 0.299      | -            | -                | -                | -         |     2.72 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            8 |     7750 | 2024-01-14 | RED Canids       | L   | 0.292      | -            | -                | -                | -         |    -4.77 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            7 |     7772 | 2024-01-13 | inSanitY Sports  | W   | 0.286      | -            | -                | -                | -         |     0.50 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            6 |     8048 | 2024-01-09 | Flamengo Esports | L   | 0.260      | -            | -                | -                | -         |    -7.64 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            5 |     8052 | 2024-01-09 | w7m esports      | W   | 0.259      | -            | -                | -                | -         |     1.71 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            4 |     8057 | 2024-01-09 | caradecachorro   | W   | 0.258      | -            | -                | -                | -         |     0.47 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            3 |     8070 | 2024-01-09 | adalYamigos      | W   | 0.258      | -            | -                | -                | -         |     0.88 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            2 |     8170 | 2024-01-08 | 4i20 Friends     | W   | 0.252      | -            | -                | -                | -         |     0.25 | b4rtiN, coldzera, dumau, latto, NEKIZ |
|            1 |     9473 | 2023-12-02 | RED Canids       | L   | 0.004      | -            | -                | -                | -         |    -0.06 | b4rtiN, coldzera, dumau, latto, NEKIZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,038.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
