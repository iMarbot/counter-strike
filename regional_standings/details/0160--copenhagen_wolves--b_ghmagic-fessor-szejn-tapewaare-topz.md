### Roster Details<br />
Team Name: Copenhagen Wolves<br />
Roster: BøghmagiC, Fessor, szejn, Tapewaare, tOPZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [160](../standings_global.md)<br />
Regional Rank: [112]( ../standings_europe.md)<br />
Final Rank Value:  770.6<br />
<br />
Final Rank Value (770.6) = Starting Rank Value (599.2) + Head To Head Adjustments (171.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.121[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.098<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 599.2
- 400 + ( ( 0.098 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 599.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |       70 | 2024-05-29 | Preasy Esport    | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.705 (0.235)    | 0 (0.000) |    13.32 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           20 |       93 | 2024-05-29 | Denial           | W   | 1.000      | 0.354        | 0.000 (0.000)    | 0.138 (0.049)    | 0 (0.000) |     9.36 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           19 |      123 | 2024-05-28 | The Agency Clan  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.99 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           18 |      139 | 2024-05-28 | ENCE Academy     | L   | 1.000      | -            | -                | -                | -         |   -15.50 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           17 |      168 | 2024-05-27 | Astralis Talent  | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.452 (0.065)    | 0 (0.000) |    16.08 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           16 |      181 | 2024-05-27 | XI Esport        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.277 (0.040)    | 0 (0.000) |    13.89 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           15 |      186 | 2024-05-27 | WOPA Esport      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.594 (0.085)    | 0 (0.000) |    16.14 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           14 |      190 | 2024-05-27 | Sashi Esport     | L   | 1.000      | -            | -                | -                | -         |    -1.62 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           13 |      197 | 2024-05-27 | Permitta Esports | W   | 1.000      | 0.333        | 0.025 (0.008)    | 1.000 (0.333)    | 0 (0.000) |    20.47 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           12 |      228 | 2024-05-26 | Nexus Gaming     | L   | 1.000      | -            | -                | -                | -         |    -8.91 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           11 |      345 | 2024-05-24 | LODIS            | W   | 1.000      | 0.372        | 0.001 (0.000)    | 0.140 (0.052)    | 0 (0.000) |    10.92 | artie, Basso, BøghmagiC, Fessor, szejn    |
|           10 |      504 | 2024-05-22 | WOPA Esport      | W   | 1.000      | 0.354        | 0.003 (0.001)    | 0.594 (0.210)    | 0 (0.000) |    18.62 | BøghmagiC, Fessor, szejn, tOPZ, vigg0     |
|            9 |      666 | 2024-05-20 | IMMAPROBLEM      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.40 | BøghmagiC, Fessor, Svedjehed, szejn, tOPZ |
|            8 |      889 | 2024-05-18 | VP.Prodigy       | L   | 1.000      | -            | -                | -                | -         |    -7.94 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            7 |      919 | 2024-05-18 | VP.Prodigy       | L   | 1.000      | -            | -                | -                | -         |    -8.50 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            6 |      986 | 2024-05-17 | MASONIC          | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.182 (0.026)    | -         |    21.86 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            5 |     1018 | 2024-05-17 | PSYCHOACTiVE     | W   | 1.000      | -            | -                | -                | -         |    10.14 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            4 |     1091 | 2024-05-16 | Rhyno Esports    | L   | 1.000      | -            | -                | -                | -         |    -4.69 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            3 |     1159 | 2024-05-15 | Lemondogs        | W   | 1.000      | 0.372        | -                | 0.314 (0.117)    | -         |    15.30 | artie, Basso, BøghmagiC, Fessor, szejn    |
|            2 |     1165 | 2024-05-15 | LOG Esports      | W   | 1.000      | -            | -                | -                | -         |     9.30 | artie, Basso, BøghmagiC, Fessor, szejn    |
|            1 |     1192 | 2024-05-15 | MASONIC          | W   | 1.000      | 0.143        | 0.018 (0.003)    | -                | -         |    23.82 | Basso, BøghmagiC, Fessor, szejn, vigg0    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
