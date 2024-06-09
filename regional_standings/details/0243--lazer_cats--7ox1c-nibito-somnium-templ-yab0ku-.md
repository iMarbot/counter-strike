### Roster Details<br />
Team Name: Lazer Cats<br />
Roster: 7oX1C, nibito, somnium, Templ, yab0ku-<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [243](../standings_global.md)<br />
Regional Rank: [160]( ../standings_europe.md)<br />
Final Rank Value:  692.9<br />
<br />
Final Rank Value (692.9) = Starting Rank Value (696.9) + Head To Head Adjustments (-4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.245[<sup>2</sup>](#table1)
- Opponent Network: 0.053[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 696.9
- 400 + ( ( 0.146 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 696.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |       52 | 2024-05-29 | Sissi State Punks | L   | 1.000      | -            | -                | -                | -         |   -16.23 | 7oX1C, nibito, somnium, Templ, yab0ku-        |
|           19 |      795 | 2024-05-19 | REDPack Esports   | L   | 1.000      | -            | -                | -                | -         |   -24.34 | 7oX1C, nibito, somnium, Templ, yab0ku-        |
|           18 |      881 | 2024-05-18 | Quixal            | L   | 1.000      | -            | -                | -                | -         |   -17.65 | 7oX1C, nibito, somnium, Templ, yab0ku-        |
|           17 |      896 | 2024-05-18 | Pera Esports      | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.542 (0.077)    | 0 (0.000) |    23.22 | 7oX1C, nibito, somnium, Templ, yab0ku-        |
|           16 |      904 | 2024-05-18 | DASH              | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.385 (0.055)    | 0 (0.000) |    13.35 | 7oX1C, nibito, somnium, Templ, yab0ku-        |
|           15 |     1900 | 2024-05-03 | L&G               | L   | 1.000      | -            | -                | -                | -         |   -12.48 | 7oX1C, levantino, somnium, Templ, yab0ku-     |
|           14 |     1952 | 2024-05-02 | los kogutos       | L   | 1.000      | -            | -                | -                | -         |    -9.79 | 7oX1C, levantino, somnium, Templ, yab0ku-     |
|           13 |     2065 | 2024-04-30 | SINNERS Academy   | W   | 1.000      | 0.289        | 0.001 (0.000)    | 0.227 (0.066)    | 0 (0.000) |    13.02 | 7oX1C, levantino, somnium, Templ, yab0ku-     |
|           12 |     2211 | 2024-04-27 | EP Genesis        | W   | 0.984      | 0.289        | 0.000 (0.000)    | 0.208 (0.059)    | 0 (0.000) |     8.92 | 7oX1C, levantino, somnium, Templ, yab0ku-     |
|           11 |     2616 | 2024-04-20 | L&G               | L   | 0.937      | -            | -                | -                | -         |   -13.21 | 7oX1C, F1xMe, somnium, Templ, yab0ku-         |
|           10 |     2671 | 2024-04-20 | ThunderFlash      | W   | 0.936      | 0.143        | 0.012 (0.002)    | 0.423 (0.057)    | 0 (0.000) |    19.29 | 7oX1C, F1xMe, somnium, Templ, yab0ku-         |
|            9 |     2828 | 2024-04-18 | Sashi Academy     | W   | 0.923      | 0.289        | 0.001 (0.000)    | 0.090 (0.024)    | 0 (0.000) |    11.44 | 7oX1C, levantino, Templ, Wonderful_Y, yab0ku- |
|            8 |     2991 | 2024-04-16 | Viperio           | L   | 0.908      | -            | -                | -                | -         |   -12.05 | 7oX1C, somnium, Templ, Wonderful_Y, yab0ku-   |
|            7 |     3031 | 2024-04-15 | 1win              | L   | 0.901      | -            | -                | -                | -         |    -5.07 | 7oX1C, somnium, Templ, Wonderful_Y, yab0ku-   |
|            6 |     3417 | 2024-04-07 | HOTU              | L   | 0.850      | -            | -                | -                | -         |    -9.32 | 7oX1C, somnium, Templ, Wonderful_Y, yab0ku-   |
|            5 |     3422 | 2024-04-07 | LEON Esports      | W   | 0.849      | 0.143        | 0.001 (0.000)    | 0.564 (0.068)    | 0 (0.000) |    14.24 | 7oX1C, somnium, Templ, Wonderful_Y, yab0ku-   |
|            4 |     3428 | 2024-04-07 | Verdant           | W   | 0.849      | 0.143        | 0.014 (0.002)    | 1.000 (0.121)    | 0 (0.000) |    21.26 | 7oX1C, somnium, Templ, Wonderful_Y, yab0ku-   |
|            3 |     3752 | 2024-03-31 | L&G               | L   | 0.802      | -            | -                | -                | -         |   -11.35 | 7oX1C, munch, somnium, Templ, yab0ku-         |
|            2 |     3779 | 2024-03-30 | Passion UA        | L   | 0.796      | -            | -                | -                | -         |    -5.07 | 7oX1C, munch, somnium, Templ, yab0ku-         |
|            1 |     4050 | 2024-03-24 | Gorillas          | W   | 0.755      | 0.143        | 0.000 (0.000)    | 0.037 (0.004)    | 0 (0.000) |     7.80 | 7oX1C, munch, somnium, Templ, yab0ku-         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($955.52)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-04 |      1.000 | $500.00        | $500.00         |
| 2024-04-20 |      0.937 | $376.72        | $353.07         |
| 2024-03-31 |      0.803 | $127.64        | $102.45         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
