### Roster Details<br />
Team Name: 1win Gang<br />
Roster: Deylary, f6tal, miu_u, Potya, unknxwn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [332](../standings_global.md)<br />
Regional Rank: [200]( ../standings_europe.md)<br />
Final Rank Value:  617.8<br />
<br />
Final Rank Value (617.8) = Starting Rank Value (656.7) + Head To Head Adjustments (-38.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.292[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.126<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.7
- 400 + ( ( 0.126 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 656.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     2696 | 2024-04-19 | Fearless Cheetahs  | L   | 0.930      | -            | -                | -                | -         |   -11.07 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|           16 |     3025 | 2024-04-13 | Team Spirit Female | L   | 0.890      | -            | -                | -                | -         |   -13.09 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|           15 |     3033 | 2024-04-13 | woof woof          | W   | 0.890      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    10.02 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|           14 |     3175 | 2024-04-10 | Let Her Cook       | W   | 0.870      | 0.331        | 0.000 (0.000)    | 0.137 (0.040)    | 0 (0.000) |    12.10 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|           13 |     3413 | 2024-04-06 | ENCE Athena        | L   | 0.841      | -            | -                | -                | -         |   -11.50 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|           12 |     3737 | 2024-03-28 | Crescent           | L   | 0.784      | -            | -                | -                | -         |   -10.53 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|           11 |     4276 | 2024-03-17 | Nemesis            | L   | 0.710      | -            | -                | -                | -         |   -11.88 | Emmy, Hikomi, Lowlita, miila, Monkey D. Julie  |
|           10 |     4315 | 2024-03-16 | SNOGARD Female     | W   | 0.704      | 0.250        | 0.000 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     6.54 | Ivona, Julie, pauski, tinjau, Wuchtig          |
|            9 |     4327 | 2024-03-16 | ex-FORZE Ladies    | W   | 0.704      | 0.250        | 0.005 (0.001)    | 0.164 (0.029)    | 0 (0.000) |    11.71 | Deylary, donotbesadd, miu_u, panifika, unknxwn |
|            8 |     4421 | 2024-03-14 | NAVI Javelins      | L   | 0.691      | -            | -                | -                | -         |    -5.89 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            7 |     4803 | 2024-03-07 | Team Spirit Female | L   | 0.644      | -            | -                | -                | -         |    -9.18 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            6 |     5446 | 2024-02-25 | Fearless Cheetahs  | L   | 0.571      | -            | -                | -                | -         |    -8.00 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            5 |     5454 | 2024-02-25 | more whiskey       | W   | 0.570      | 0.250        | 0.000 (0.000)    | 0.056 (0.008)    | 0 (0.000) |     6.05 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            4 |     5533 | 2024-02-24 | Astralis Women     | W   | 0.564      | 0.250        | 0.003 (0.000)    | 0.054 (0.008)    | 0 (0.000) |     8.42 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            3 |     5560 | 2024-02-24 | Crescent           | L   | 0.562      | -            | -                | -                | -         |    -7.63 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            2 |     7332 | 2024-01-20 | ex-FORZE Ladies    | L   | 0.331      | -            | -                | -                | -         |    -4.85 | Deylary, f6tal, miu_u, Potya, unknxwn          |
|            1 |     9472 | 2023-12-02 | ex-FORZE Ladies    | L   | 0.004      | -            | -                | -                | -         |    -0.06 | aimamama, Deylary, IRBITka, miu_u, Potya       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,122.40)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.944 | $850.00        | $802.19         |
| 2024-03-17 |      0.710 | $250.00        | $177.50         |
| 2024-02-25 |      0.571 | $250.00        | $142.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
