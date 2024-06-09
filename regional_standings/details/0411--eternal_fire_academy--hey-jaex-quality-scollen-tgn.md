### Roster Details<br />
Team Name: Eternal Fire Academy<br />
Roster: hey, Jaex, Quality, scolleN, tgN<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [411](../standings_global.md)<br />
Regional Rank: [246]( ../standings_europe.md)<br />
Final Rank Value:  551.1<br />
<br />
Final Rank Value (551.1) = Starting Rank Value (529.7) + Head To Head Adjustments (21.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.064<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.7
- 400 + ( ( 0.064 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 529.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      273 | 2024-05-25 | VaselineWorms        | L   | 1.000      | -            | -                | -                | -         |    -7.66 | hey, Jaex, Quality, scolleN, tgN |
|           13 |      404 | 2024-05-23 | DASH                 | L   | 1.000      | -            | -                | -                | -         |   -10.03 | hey, Jaex, Quality, scolleN, tgN |
|           12 |      467 | 2024-05-22 | ADEPTS               | L   | 1.000      | -            | -                | -                | -         |    -9.29 | hey, Jaex, Quality, scolleN, tgN |
|           11 |      601 | 2024-05-21 | FLuffy Gangsters     | L   | 1.000      | -            | -                | -                | -         |   -11.20 | hey, Jaex, Quality, scolleN, tgN |
|           10 |      679 | 2024-05-20 | LOADING              | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.107 (0.040)    | 0 (0.000) |    16.57 | hey, Jaex, Quality, scolleN, tgN |
|            9 |     1319 | 2024-05-13 | LODIS                | W   | 1.000      | 0.372        | 0.001 (0.000)    | 0.140 (0.052)    | 0 (0.000) |    17.93 | hey, Jaex, Quality, scolleN, tgN |
|            8 |     1645 | 2024-05-08 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |    -1.85 | hey, Jaex, Quality, scolleN, tgN |
|            7 |     1652 | 2024-05-08 | RoundsGG             | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.251 (0.094)    | 0 (0.000) |    17.97 | hey, Jaex, Quality, scolleN, tgN |
|            6 |     1753 | 2024-05-06 | Grannys Knockers     | L   | 1.000      | -            | -                | -                | -         |    -5.58 | hey, Jaex, Quality, scolleN, tgN |
|            5 |     1789 | 2024-05-05 | VP.Prodigy           | L   | 1.000      | -            | -                | -                | -         |    -5.93 | hey, Jaex, Quality, scolleN, tgN |
|            4 |     1998 | 2024-05-01 | Raptors Esports Club | W   | 1.000      | 0.372        | 0.007 (0.003)    | 0.406 (0.151)    | 0 (0.000) |    26.55 | hey, Jaex, Quality, scolleN, tgN |
|            3 |     2416 | 2024-04-24 | kONO.ECF             | L   | 0.963      | -            | -                | -                | -         |    -3.02 | hey, Jaex, Quality, scolleN, tgN |
|            2 |     2503 | 2024-04-22 | AscendX Esports      | W   | 0.950      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.79 | hey, Jaex, Quality, scolleN, tgN |
|            1 |     3007 | 2024-04-15 | Young Gods           | L   | 0.904      | -            | -                | -                | -         |   -12.83 | hey, Jaex, Quality, scolleN, tgN |

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
