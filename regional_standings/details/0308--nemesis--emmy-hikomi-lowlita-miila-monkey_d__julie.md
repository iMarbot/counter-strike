### Roster Details<br />
Team Name: Nemesis<br />
Roster: Emmy, Hikomi, Lowlita, miila, Monkey D. Julie<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [308](../standings_global.md)<br />
Regional Rank: [189]( ../standings_europe.md)<br />
Final Rank Value:  635.0<br />
<br />
Final Rank Value (635.0) = Starting Rank Value (637.8) + Head To Head Adjustments (-2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.198[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.8
- 400 + ( ( 0.117 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 637.8


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
|           10 |     4276 | 2024-03-17 | 1win Gang         | W   | 0.710      | 0.250        | 0.004 (0.001)    | 0.118 (0.021)    | 0 (0.000) |    11.88 | Emmy, Hikomi, Lowlita, miila, Monkey D. Julie |
|            9 |     4316 | 2024-03-16 | 5bites            | W   | 0.704      | 0.250        | 0.000 (0.000)    | 0.019 (0.003)    | 0 (0.000) |     6.77 | Emmy, Hikomi, Lowlita, miila, Monkey D. Julie |
|            8 |     4323 | 2024-03-16 | endless           | W   | 0.704      | 0.250        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     5.14 | Emmy, Hikomi, Lowlita, miila, Monkey D. Julie |
|            7 |     5180 | 2024-03-02 | BIG EQUIPA        | L   | 0.610      | -            | -                | -                | -         |    -7.16 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |
|            6 |     5453 | 2024-02-25 | Fearless Cheetahs | L   | 0.570      | -            | -                | -                | -         |    -7.37 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |
|            5 |     5534 | 2024-02-24 | Dogenjoyers       | W   | 0.564      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.85 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |
|            4 |     5550 | 2024-02-24 | Let Her Cook      | L   | 0.563      | -            | -                | -                | -         |   -10.82 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |
|            3 |     5564 | 2024-02-24 | Astralis Women    | W   | 0.562      | 0.143        | 0.003 (0.000)    | 0.054 (0.004)    | 0 (0.000) |     9.12 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |
|            2 |     5928 | 2024-02-17 | ex-FORZE Ladies   | L   | 0.518      | -            | -                | -                | -         |    -7.09 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |
|            1 |     6095 | 2024-02-14 | ENCE Athena       | L   | 0.497      | -            | -                | -                | -         |    -7.10 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($532.50)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
