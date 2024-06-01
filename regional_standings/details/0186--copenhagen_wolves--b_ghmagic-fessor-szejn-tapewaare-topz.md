### Roster Details<br />
Team Name: Copenhagen Wolves<br />
Roster: BøghmagiC, Fessor, szejn, Tapewaare, tOPZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [186](../standings_global.md)<br />
Regional Rank: [126]( ../standings_europe.md)<br />
Final Rank Value:  742.4<br />
<br />
Final Rank Value (742.4) = Starting Rank Value (588.2) + Head To Head Adjustments (154.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.092<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 588.2
- 400 + ( ( 0.092 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 588.2


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
|           19 |       66 | 2024-05-29 | Preasy Esport    | W   | 1.000      | 0.333        | 0.008 (0.003)    | 0.642 (0.214)    | 0 (0.000) |    14.47 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           18 |       86 | 2024-05-29 | Denial           | W   | 1.000      | 0.354        | 0.000 (0.000)    | 0.138 (0.049)    | 0 (0.000) |    10.51 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           17 |      115 | 2024-05-28 | The Agency Clan  | W   | 1.000      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     7.99 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           16 |      132 | 2024-05-28 | ENCE Academy     | L   | 1.000      | -            | -                | -                | -         |   -14.36 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           15 |      161 | 2024-05-27 | Astralis Talent  | W   | 1.000      | 0.143        | 0.012 (0.002)    | 0.452 (0.065)    | 0 (0.000) |    17.30 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           14 |      173 | 2024-05-27 | XI Esport        | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.277 (0.040)    | 0 (0.000) |    15.26 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           13 |      178 | 2024-05-27 | WOPA Esport      | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.594 (0.085)    | 0 (0.000) |    18.25 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           12 |      182 | 2024-05-27 | Sashi Esport     | L   | 1.000      | -            | -                | -                | -         |    -1.34 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           11 |      189 | 2024-05-27 | Permitta Esports | W   | 1.000      | 0.333        | 0.029 (0.010)    | 1.000 (0.333)    | 0 (0.000) |    21.43 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|           10 |      220 | 2024-05-26 | Nexus Gaming     | L   | 1.000      | -            | -                | -                | -         |    -7.50 | BøghmagiC, Fessor, szejn, Tapewaare, tOPZ |
|            9 |      336 | 2024-05-24 | LODIS            | W   | 1.000      | 0.372        | 0.001 (0.000)    | 0.140 (0.052)    | 0 (0.000) |    12.04 | artie, Basso, BøghmagiC, Fessor, szejn    |
|            8 |      877 | 2024-05-18 | VP.Prodigy       | L   | 1.000      | -            | -                | -                | -         |    -8.41 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            7 |      907 | 2024-05-18 | VP.Prodigy       | L   | 1.000      | -            | -                | -                | -         |    -9.03 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            6 |      974 | 2024-05-17 | MASONIC          | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.182 (0.026)    | 0 (0.000) |    22.18 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            5 |     1006 | 2024-05-17 | PSYCHOACTiVE     | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.51 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            4 |     1081 | 2024-05-16 | Rhyno Esports    | L   | 1.000      | -            | -                | -                | -         |    -4.72 | Basso, BøghmagiC, Fessor, szejn, vigg0    |
|            3 |     1150 | 2024-05-15 | Lemondogs        | W   | 1.000      | 0.372        | -                | 0.274 (0.102)    | -         |    15.48 | artie, Basso, BøghmagiC, Fessor, szejn    |
|            2 |     1156 | 2024-05-15 | LOG Esports      | W   | 1.000      | -            | -                | -                | -         |    10.06 | artie, Basso, BøghmagiC, Fessor, szejn    |
|            1 |     1182 | 2024-05-15 | MASONIC          | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.182 (0.026)    | -         |    24.14 | Basso, BøghmagiC, Fessor, szejn, vigg0    |

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
