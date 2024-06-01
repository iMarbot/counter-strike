### Roster Details<br />
Team Name: Canon Event<br />
Roster: Blizz, BoBo, Coppo, Kras, mitzy<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [441](../standings_global.md)<br />
Regional Rank: [66]( ../standings_asia.md)<br />
Final Rank Value:  453.9<br />
<br />
Final Rank Value (453.9) = Starting Rank Value (513.8) + Head To Head Adjustments (-59.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.223[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 513.8
- 400 + ( ( 0.056 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 513.8


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
|           19 |      517 | 2024-05-22 | DXA Esports        | L   | 1.000      | -            | -                | -                | -         |    -8.11 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           18 |      525 | 2024-05-22 | DXA Esports        | L   | 1.000      | -            | -                | -                | -         |    -8.69 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           17 |      714 | 2024-05-20 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.14 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           16 |      717 | 2024-05-20 | FlyQuest           | L   | 1.000      | -            | -                | -                | -         |    -0.14 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           15 |     1202 | 2024-05-15 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -3.41 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           14 |     1207 | 2024-05-15 | Rooster            | L   | 1.000      | -            | -                | -                | -         |    -3.53 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           13 |     2861 | 2024-04-17 | Rooster            | L   | 0.915      | -            | -                | -                | -         |    -3.23 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           12 |     2873 | 2024-04-17 | Arcade Esports     | W   | 0.915      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |    10.79 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           11 |     3200 | 2024-04-10 | KZG                | L   | 0.868      | -            | -                | -                | -         |    -6.15 | Blizz, BoBo, Coppo, Kras, mitzy  |
|           10 |     3205 | 2024-04-10 | KZG                | L   | 0.868      | -            | -                | -                | -         |    -6.49 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            9 |     3573 | 2024-04-03 | Mindfreak          | L   | 0.822      | -            | -                | -                | -         |    -5.41 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            8 |     3576 | 2024-04-03 | Mindfreak          | L   | 0.821      | -            | -                | -                | -         |    -5.67 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            7 |     3830 | 2024-03-27 | Vantage Esports    | L   | 0.776      | -            | -                | -                | -         |    -6.77 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            6 |     3833 | 2024-03-27 | Vantage Esports    | L   | 0.775      | -            | -                | -                | -         |    -7.16 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            5 |     4145 | 2024-03-20 | Bad News Kangaroos | L   | 0.728      | -            | -                | -                | -         |    -2.33 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            4 |     4146 | 2024-03-20 | Bad News Kangaroos | L   | 0.728      | -            | -                | -                | -         |    -2.39 | Blizz, BoBo, Coppo, Kras, mitzy  |
|            3 |     6369 | 2024-02-07 | FlyQuest           | L   | 0.448      | -            | -                | -                | -         |    -0.08 | Blizz, BoBo, Coppo, Kras, Redav  |
|            2 |     9123 | 2023-12-08 | TEAM RKON          | L   | 0.042      | -            | -                | -                | -         |    -0.70 | Blizz, Coppo, Kras, LBoBo, Redav |
|            1 |     9185 | 2023-12-07 | DXA Esports        | L   | 0.035      | -            | -                | -                | -         |    -0.26 | Blizz, Coppo, Kras, LBoBo, Redav |

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
