### Roster Details<br />
Team Name: 1win Gang<br />
Roster: Deylary, f6tal, miu_u, Potya, unknxwn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [312](../standings_global.md)<br />
Regional Rank: [190]( ../standings_europe.md)<br />
Final Rank Value:  600.1<br />
<br />
Final Rank Value (600.1) = Starting Rank Value (660.9) + Head To Head Adjustments (-60.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.314[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.9
- 400 + ( ( 0.132 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 660.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      818 | 2024-04-19 | Fearless Cheetahs      | L   | 1.000      | -            | -                | -                | -         |   -10.15 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|           10 |     1104 | 2024-04-13 | Team Spirit Female     | L   | 1.000      | -            | -                | -                | -         |   -13.89 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            9 |     1222 | 2024-04-10 | Let Her Cook           | W   | 1.000      | 0.331        | 0.000 (0.000)    | 0.191 (0.063)    | 0 (0.000) |    15.04 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            8 |     1418 | 2024-04-06 | ENCE Athena            | L   | 1.000      | -            | -                | -                | -         |   -12.35 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            7 |     1693 | 2024-03-28 | Crescent (Female team) | L   | 0.945      | -            | -                | -                | -         |   -12.03 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            6 |     2261 | 2024-03-14 | NAVI Javelins          | L   | 0.852      | -            | -                | -                | -         |    -5.42 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            5 |     2567 | 2024-03-07 | Team Spirit Female     | L   | 0.805      | -            | -                | -                | -         |   -10.91 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            4 |     3096 | 2024-02-25 | Fearless Cheetahs      | L   | 0.732      | -            | -                | -                | -         |    -9.92 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            3 |     3154 | 2024-02-24 | Astralis Women         | W   | 0.725      | 0.250        | 0.007 (0.001)    | 0.101 (0.018)    | 0 (0.000) |    11.25 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            2 |     3175 | 2024-02-24 | Crescent (Female team) | L   | 0.723      | -            | -                | -                | -         |    -9.77 | Deylary, f6tal, miu_u, Potya, unknxwn    |
|            1 |     6108 | 2023-12-02 | FORZE Ladies           | L   | 0.165      | -            | -                | -                | -         |    -2.70 | aimamama, Deylary, IRBITka, miu_u, Potya |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,032.97)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      1.000 | $850.00        | $850.00         |
| 2024-02-25 |      0.732 | $250.00        | $182.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
