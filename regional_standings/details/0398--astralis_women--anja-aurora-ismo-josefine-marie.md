### Roster Details<br />
Team Name: Astralis Women<br />
Roster: anja, aurora, Ismo, josefine, marie<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [398](../standings_global.md)<br />
Regional Rank: [238]( ../standings_europe.md)<br />
Final Rank Value:  564.0<br />
<br />
Final Rank Value (564.0) = Starting Rank Value (639.1) + Head To Head Adjustments (-75.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.280[<sup>1</sup>](#table2)
- Bounty Collected: 0.184[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.002[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.1
- 400 + ( ( 0.118 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 639.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      932 | 2024-05-18 | Team Spirit Female | L   | 1.000      | -            | -                | -                | -         |   -12.43 | anja, aurora, Ismo, josefine, marie       |
|           21 |     2748 | 2024-04-19 | ENCE Athena        | L   | 0.930      | -            | -                | -                | -         |   -10.99 | anja, aurora, Ismo, josefine, marie       |
|           20 |     3048 | 2024-04-14 | NAVI Javelins      | L   | 0.896      | -            | -                | -                | -         |    -6.96 | anja, aurora, Ismo, josefine, marie       |
|           19 |     3088 | 2024-04-13 | NIP Impact         | L   | 0.890      | -            | -                | -                | -         |    -9.16 | anja, aurora, Ismo, josefine, marie       |
|           18 |     3147 | 2024-04-12 | Permitta W         | W   | 0.883      | 0.303        | 0.000 (0.000)    | 0.051 (0.014)    | 0 (0.000) |    10.23 | anja, aurora, Ismo, josefine, marie       |
|           17 |     3176 | 2024-04-11 | Team Pigeons       | L   | 0.877      | -            | -                | -                | -         |    -5.88 | anja, aurora, Ismo, josefine, marie       |
|           16 |     3250 | 2024-04-10 | Team Pigeons       | L   | 0.870      | -            | -                | -                | -         |    -6.15 | anja, aurora, Ismo, josefine, marie       |
|           15 |     3370 | 2024-04-08 | Permitta W         | W   | 0.857      | 0.303        | 0.000 (0.000)    | 0.051 (0.013)    | 0 (0.000) |     9.52 | anja, aurora, Ismo, josefine, marie       |
|           14 |     3637 | 2024-04-03 | NIP Impact         | L   | 0.824      | -            | -                | -                | -         |   -10.06 | anja, aurora, Ismo, josefine, marie       |
|           13 |     4181 | 2024-03-21 | ex-Guild Esports   | L   | 0.738      | -            | -                | -                | -         |    -8.73 | anja, aurora, Ismo, josefine, marie       |
|           12 |     4992 | 2024-03-06 | BIG EQUIPA         | L   | 0.638      | -            | -                | -                | -         |    -6.94 | anja, aurora, Ismo, josefine, marie       |
|           11 |     5693 | 2024-02-24 | 1win Gang          | L   | 0.564      | -            | -                | -                | -         |    -8.41 | anja, aurora, Ismo, josefine, marie       |
|           10 |     5724 | 2024-02-24 | Nemesis            | L   | 0.562      | -            | -                | -                | -         |    -9.12 | anja, aurora, Ismo, josefine, marie       |
|            9 |     6036 | 2024-02-18 | ex-FORZE Ladies    | W   | 0.525      | 0.143        | 0.005 (0.000)    | 0.164 (0.012)    | 0 (0.000) |     9.13 | anja, aurora, Ismo, josefine, marie       |
|            8 |     6046 | 2024-02-18 | Team Spirit Female | L   | 0.524      | -            | -                | -                | -         |    -7.14 | anja, aurora, Ismo, josefine, marie       |
|            7 |     6103 | 2024-02-17 | 5bites             | W   | 0.518      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     4.55 | anja, aurora, Ismo, josefine, marie       |
|            6 |     6278 | 2024-02-14 | ex-Guild Esports   | L   | 0.497      | -            | -                | -                | -         |    -6.50 | anja, aurora, Ismo, josefine, marie       |
|            5 |     9661 | 2023-12-03 | Team Finland       | L   | 0.009      | -            | -                | -                | -         |    -0.18 | amyb, miLo, oona, Siljeeeh, Waldee        |
|            4 |     9675 | 2023-12-03 | Team Sweden        | W   | 0.009      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.009) |     0.07 | anja, aurora, Ismo, josefine, marie       |
|            3 |     9679 | 2023-12-03 | Team Norway        | W   | 0.008      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.008) |     0.06 | anja, aurora, Ismo, josefine, marie       |
|            2 |     9779 | 2023-12-02 | Team Iceland       | W   | 0.003      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.003) |     0.02 | Eneka, Jazzycakes, nutellaalb, S1u, tania |
|            1 |     9791 | 2023-12-02 | Team Finland       | L   | 0.002      | -            | -                | -                | -         |    -0.04 | anja, aurora, Ismo, josefine, marie       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($815.77)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.944 | $850.00        | $802.19         |
| 2023-12-03 |      0.009 | $1,437.91      | $13.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
