### Roster Details<br />
Team Name: Canon Event<br />
Roster: Blizz, BoBo, Coppo, Kras, mitzy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [456](../standings_global.md)<br />
Regional Rank: [69]( ../standings_asia.md)<br />
Final Rank Value:  447.7<br />
<br />
Final Rank Value (447.7) = Starting Rank Value (513.6) + Head To Head Adjustments (-65.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.223[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 513.6
- 400 + ( ( 0.056 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 513.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      524 | 2024-05-22 | DXA Esports        | L   | 1.000      | -            | -                | -                | -         |    -8.01 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           20 |      532 | 2024-05-22 | DXA Esports        | L   | 1.000      | -            | -                | -                | -         |    -8.58 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           19 |      726 | 2024-05-20 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.13 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           18 |      729 | 2024-05-20 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.13 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           17 |     1212 | 2024-05-15 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -3.14 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           16 |     1217 | 2024-05-15 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -3.25 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           15 |     2918 | 2024-04-17 | Rooster            | L   | 0.915      | -            | -                | -                | -         |    -2.88 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           14 |     2930 | 2024-04-17 | Arcade Esports     | W   | 0.915      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |    11.06 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           13 |     3276 | 2024-04-10 | KZG                | L   | 0.868      | -            | -                | -                | -         |    -6.32 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           12 |     3282 | 2024-04-10 | KZG                | L   | 0.868      | -            | -                | -                | -         |    -6.68 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           11 |     3660 | 2024-04-03 | Mindfreak          | L   | 0.822      | -            | -                | -                | -         |    -5.23 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           10 |     3664 | 2024-04-03 | Mindfreak          | L   | 0.821      | -            | -                | -                | -         |    -5.48 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            9 |     3923 | 2024-03-27 | Vantage Esports    | L   | 0.776      | -            | -                | -                | -         |    -6.30 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            8 |     3928 | 2024-03-27 | Vantage Esports    | L   | 0.775      | -            | -                | -                | -         |    -6.64 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            7 |     4247 | 2024-03-20 | Bad News Kangaroos | L   | 0.728      | -            | -                | -                | -         |    -2.25 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            6 |     4248 | 2024-03-20 | Bad News Kangaroos | L   | 0.728      | -            | -                | -                | -         |    -2.31 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            5 |     5540 | 2024-02-27 | Arcade Esports     | L   | 0.582      | -            | -                | -                | -         |    -4.22 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            4 |     5543 | 2024-02-27 | Arcade Esports     | L   | 0.582      | -            | -                | -                | -         |    -4.38 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            3 |     6563 | 2024-02-07 | FlyQuest           | L   | 0.448      | -            | -                | -                | -         |    -0.08 | Blizz, BoBo, Coppo, Kras, Redav  |
|            2 |     9393 | 2023-12-08 | TEAM RKON          | L   | 0.042      | -            | -                | -                | -         |    -0.70 | Blizz, Coppo, Kras, LBoBo, Redav |
|            1 |     9458 | 2023-12-07 | DXA Esports        | L   | 0.035      | -            | -                | -                | -         |    -0.26 | Blizz, Coppo, Kras, LBoBo, Redav |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($100.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
