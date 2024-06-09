### Roster Details<br />
Team Name: BLUEJAYS Lite<br />
Roster: aimy, ANeraX, cinkolEK, mazdaaa, olfii<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [451](../standings_global.md)<br />
Regional Rank: [272]( ../standings_europe.md)<br />
Final Rank Value:  472.7<br />
<br />
Final Rank Value (472.7) = Starting Rank Value (468.8) + Head To Head Adjustments (3.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.134[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.034<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 468.8
- 400 + ( ( 0.034 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 468.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     7078 | 2024-01-28 | EXO Clan              | L   | 0.384      | -            | -                | -                | -         |    -0.64 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            9 |     7253 | 2024-01-26 | Preasy Esport         | L   | 0.371      | -            | -                | -                | -         |    -1.14 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            8 |     7306 | 2024-01-25 | ex-AVEZ               | W   | 0.364      | 0.289        | 0.000 (0.000)    | 0.025 (0.003)    | 0 (0.000) |     4.62 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            7 |     7464 | 2024-01-22 | Dynamo Eclot Thunders | W   | 0.344      | 0.289        | 0.000 (0.000)    | 0.026 (0.003)    | 0 (0.000) |     4.37 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            6 |     7738 | 2024-01-18 | ex-AVEZ               | L   | 0.317      | -            | -                | -                | -         |    -5.94 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            5 |     9136 | 2023-12-12 | Rhyno Esports         | L   | 0.071      | -            | -                | -                | -         |    -0.09 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            4 |     9179 | 2023-12-11 | ROSOMAHA              | W   | 0.065      | 0.333        | 0.000 (0.000)    | 0.145 (0.003)    | 0 (0.000) |     1.39 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            3 |     9230 | 2023-12-10 | ENTERPRISE esports    | W   | 0.057      | 0.333        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     1.04 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            2 |     9431 | 2023-12-07 | Passion UA            | L   | 0.038      | -            | -                | -                | -         |    -0.05 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            1 |     9554 | 2023-12-05 | ZOTIX                 | W   | 0.025      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.31 | aimy, ANeraX, m1ght, mazdaaa, olfii    |

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
