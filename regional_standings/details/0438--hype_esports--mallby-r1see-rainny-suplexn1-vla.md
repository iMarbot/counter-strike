### Roster Details<br />
Team Name: Hype Esports<br />
Roster: MaLLby, r1see, rainny, supLexN1, vLa<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [438](../standings_global.md)<br />
Regional Rank: [110]( ../standings_americas.md)<br />
Final Rank Value:  511.4<br />
<br />
Final Rank Value (511.4) = Starting Rank Value (492.5) + Head To Head Adjustments (18.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.178[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.046<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 492.5
- 400 + ( ( 0.046 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 492.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     4539 | 2024-03-14 | Peak Academy        | W   | 0.691      | 0.262        | 0.001 (0.000)    | 0.083 (0.015)    | 0 (0.000) |    14.27 | MaLLby, r1see, rainny, supLexN1, vLa   |
|           12 |     4662 | 2024-03-12 | Galorys             | L   | 0.679      | -            | -                | -                | -         |    -3.40 | MaLLby, r1see, rainny, supLexN1, vLa   |
|           11 |     4702 | 2024-03-11 | MIBR Academy        | L   | 0.672      | -            | -                | -                | -         |    -4.85 | MaLLby, r1see, rainny, supLexN1, vLa   |
|           10 |     6263 | 2024-02-14 | Sharks Esports      | L   | 0.499      | -            | -                | -                | -         |    -1.35 | MaLLby, r1see, rainny, supLexN1, vLa   |
|            9 |     7065 | 2024-01-28 | Imperial Esports    | L   | 0.385      | -            | -                | -                | -         |    -0.04 | leleo, MaLLby, RICIOLI, supLexN1, vLa  |
|            8 |     7069 | 2024-01-28 | Corinthians Esports | W   | 0.385      | 0.143        | 0.002 (0.000)    | 0.458 (0.025)    | 0 (0.000) |     9.14 | leleo, MaLLby, RICIOLI, supLexN1, vLa  |
|            7 |     7121 | 2024-01-27 | MON$TERS            | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.42 | leleo, MaLLby, RICIOLI, supLexN1, vLa  |
|            6 |     7443 | 2024-01-22 | Imperial Esports    | L   | 0.346      | -            | -                | -                | -         |    -0.03 | Lineko, MaLLby, RICIOLI, supLexN1, vLa |
|            5 |     7894 | 2024-01-16 | Case Esports        | L   | 0.304      | -            | -                | -                | -         |    -2.45 | Lineko, MaLLby, RICIOLI, supLexN1, vLa |
|            4 |     8178 | 2024-01-11 | Case Esports        | L   | 0.271      | -            | -                | -                | -         |    -2.20 | Lineko, MaLLby, RICIOLI, supLexN1, vLa |
|            3 |     8232 | 2024-01-10 | marretada do thor   | W   | 0.266      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.09 | Lineko, MaLLby, RICIOLI, supLexN1, vLa |
|            2 |     8320 | 2024-01-09 | ODDIK               | L   | 0.258      | -            | -                | -                | -         |    -0.63 | Lineko, MaLLby, RICIOLI, supLexN1, vLa |
|            1 |     8417 | 2024-01-08 | Martians            | W   | 0.253      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.96 | Lineko, MaLLby, RICIOLI, supLexN1, vLa |

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
