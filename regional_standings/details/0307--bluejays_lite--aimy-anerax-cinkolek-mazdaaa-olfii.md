### Roster Details<br />
Team Name: BLUEJAYS Lite<br />
Roster: aimy, ANeraX, cinkolEK, mazdaaa, olfii<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [307](../standings_global.md)<br />
Regional Rank: [187]( ../standings_europe.md)<br />
Final Rank Value:  604.2<br />
<br />
Final Rank Value (604.2) = Starting Rank Value (600.9) + Head To Head Adjustments (3.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.225[<sup>1</sup>](#table2)
- Bounty Collected: 0.166[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.013[<sup>2</sup>](#table1)

The average of these factors is 0.101<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 600.9
- 400 + ( ( 0.101 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 600.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     4311 | 2024-01-26 | Preasy Esport         | L   | 0.532      | -            | -                | -                | -             |    -4.31 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            9 |     4352 | 2024-01-25 | AVEZ                  | W   | 0.525      | 0.289        | 0.000 (0.000)    | 0.017 (0.003)    | false (0.000) |     5.50 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            8 |     4463 | 2024-01-22 | Dynamo Eclot Thunders | W   | 0.505      | 0.289        | 0.000 (0.000)    | 0.035 (0.005)    | false (0.000) |     3.83 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            7 |     4673 | 2024-01-18 | AVEZ                  | L   | 0.478      | -            | -                | -                | -             |   -10.06 | aimy, ANeraX, cinkolEK, mazdaaa, olfii |
|            6 |     5666 | 2023-12-12 | Rhyno Esports         | L   | 0.232      | -            | -                | -                | -             |    -1.00 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            5 |     5688 | 2023-12-11 | ROSOMAHA              | W   | 0.226      | 0.333        | 0.000 (0.000)    | 0.136 (0.010)    | false (0.000) |     3.71 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            4 |     5721 | 2023-12-10 | ENTERPRISE esports    | W   | 0.218      | 0.333        | 0.000 (0.000)    | 0.017 (0.001)    | false (0.000) |     2.81 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            3 |     5879 | 2023-12-07 | Passion UA            | L   | 0.199      | -            | -                | -                | -             |    -0.58 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            2 |     5968 | 2023-12-05 | ZOTIX                 | W   | 0.186      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | false (0.000) |     1.42 | aimy, ANeraX, m1ght, mazdaaa, olfii    |
|            1 |     6463 | 2023-11-24 | Back2TheGame          | W   | 0.112      | 0.143        | 0.004 (0.000)    | 0.009 (0.000)    | true (0.112)  |     1.96 | All3n, Gontar, MAT1, showk, tein       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($55.95)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
