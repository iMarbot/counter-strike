### Roster Details<br />
Team Name: 0to100<br />
Roster: juliustbe, kerogi, krea6on, uQlutzavr, v1ze<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [454](../standings_global.md)<br />
Regional Rank: [274]( ../standings_europe.md)<br />
Final Rank Value:  455.8<br />
<br />
Final Rank Value (455.8) = Starting Rank Value (478.6) + Head To Head Adjustments (-22.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.155[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.039<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 478.6
- 400 + ( ( 0.039 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 478.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     5419 | 2024-02-29 | GamerLegion Academy  | L   | 0.597      | -            | -                | -                | -         |    -2.43 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|            9 |     5452 | 2024-02-28 | ex-Hot Headed Gaming | L   | 0.591      | -            | -                | -                | -         |    -7.44 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|            8 |     5569 | 2024-02-26 | LODIS                | L   | 0.578      | -            | -                | -                | -         |    -5.27 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|            7 |     5765 | 2024-02-23 | ex-KRC Genk Esports  | L   | 0.557      | -            | -                | -                | -         |    -3.96 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|            6 |     6543 | 2024-02-07 | FORZE Youngsters     | L   | 0.451      | -            | -                | -                | -         |    -3.50 | kelieN, matusik, spirit, sstiNiX, yoshi     |
|            5 |     6598 | 2024-02-05 | gbcxz                | W   | 0.438      | 0.371        | 0.000 (0.000)    | 0.003 (0.001)    | 0 (0.000) |     9.06 | AxM, gonk, Najsuuuu, next1me, smooho        |
|            4 |     6616 | 2024-02-05 | RoundsGG             | L   | 0.437      | -            | -                | -                | -         |    -4.30 | Kollo, LYNXi, m0n0xx, p12, Welho            |
|            3 |     6657 | 2024-02-04 | Nemiga Gaming        | L   | 0.431      | -            | -                | -                | -         |    -0.19 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|            2 |     6970 | 2024-01-30 | BAKS Esports         | L   | 0.398      | -            | -                | -                | -         |    -3.73 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|            1 |     7567 | 2024-01-20 | ex-K10               | L   | 0.331      | -            | -                | -                | -         |    -1.03 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |

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
