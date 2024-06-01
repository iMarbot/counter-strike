### Roster Details<br />
Team Name: 9INE<br />
Roster: Bambosh, hypex, Sterzig, tomiko, zEden<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [337](../standings_global.md)<br />
Regional Rank: [203]( ../standings_europe.md)<br />
Final Rank Value:  616.5<br />
<br />
Final Rank Value (616.5) = Starting Rank Value (661.2) + Head To Head Adjustments (-44.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.013[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 661.2
- 400 + ( ( 0.128 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 661.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     1174 | 2024-05-15 | EYEBALLERS         | L   | 1.000      | -            | -                | -                | -         |    -5.01 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           18 |     2330 | 2024-04-25 | V1dar Gaming       | L   | 0.968      | -            | -                | -                | -         |   -12.48 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           17 |     2387 | 2024-04-24 | EXO Clan           | L   | 0.962      | -            | -                | -                | -         |    -3.02 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           16 |     2607 | 2024-04-20 | System5            | L   | 0.936      | -            | -                | -                | -         |   -13.34 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           15 |     2701 | 2024-04-19 | ENTERPRISE esports | L   | 0.930      | -            | -                | -                | -         |    -5.77 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           14 |     2830 | 2024-04-17 | Aurora Gaming      | L   | 0.918      | -            | -                | -                | -         |    -0.35 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           13 |     3074 | 2024-04-12 | Permitta Esports   | L   | 0.884      | -            | -                | -                | -         |    -3.92 | bnox, maaryy, mASKED, morelz, Vegi     |
|           12 |     3116 | 2024-04-11 | AVEZ               | L   | 0.877      | -            | -                | -                | -         |    -8.80 | Bambosh, hypex, Sterzig, tomiko, zEden |
|           11 |     3157 | 2024-04-10 | M1 Gaming          | L   | 0.871      | -            | -                | -                | -         |   -16.02 | baljs, boll, Brain, fanatyk, PeTeRoOo  |
|           10 |     3239 | 2024-04-09 | DEEZ NUTS          | W   | 0.864      | 0.143        | 0.002 (0.000)    | 0.077 (0.010)    | 0 (0.000) |    12.30 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            9 |     3286 | 2024-04-08 | brazylijski luz    | W   | 0.857      | 0.143        | 0.013 (0.002)    | 0.490 (0.060)    | 0 (0.000) |    18.49 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            8 |     3547 | 2024-04-03 | KOI                | L   | 0.824      | -            | -                | -                | -         |    -2.78 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            7 |     3561 | 2024-04-03 | 9Pandas            | L   | 0.823      | -            | -                | -                | -         |    -1.45 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            6 |     3603 | 2024-04-02 | Apeks Rebels       | W   | 0.816      | 0.289        | 0.000 (0.000)    | 0.043 (0.010)    | 0 (0.000) |     9.33 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            5 |     3652 | 2024-03-31 | Metizport X        | W   | 0.803      | 0.289        | 0.008 (0.002)    | 0.210 (0.049)    | 0 (0.000) |    15.22 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            4 |     3671 | 2024-03-30 | SINNERS Academy    | L   | 0.797      | -            | -                | -                | -         |   -12.61 | BORO, DALIEN, dreez, majky, vANO       |
|            3 |     3730 | 2024-03-28 | TSM                | L   | 0.784      | -            | -                | -                | -         |    -8.53 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            2 |     4854 | 2024-03-06 | EYEBALLERS         | L   | 0.638      | -            | -                | -                | -         |    -3.86 | Bambosh, hypex, Sterzig, tomiko, zEden |
|            1 |     5352 | 2024-02-27 | Sangal Esports     | L   | 0.584      | -            | -                | -                | -         |    -2.13 | Bambosh, hypex, Sterzig, tomiko, zEden |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($697.48)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
