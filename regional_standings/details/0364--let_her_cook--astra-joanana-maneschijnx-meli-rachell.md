### Roster Details<br />
Team Name: Let Her Cook<br />
Roster: ASTRA, Joanana, ManeschijnX, meli, RacheLL<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [364](../standings_global.md)<br />
Regional Rank: [216]( ../standings_europe.md)<br />
Final Rank Value:  594.1<br />
<br />
Final Rank Value (594.1) = Starting Rank Value (542.0) + Head To Head Adjustments (52.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.254[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.070<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 542.0
- 400 + ( ( 0.070 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 542.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      917 | 2024-05-18 | NIP Impact         | L   | 1.000      | -            | -                | -                | -         |   -10.49 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           13 |     2589 | 2024-04-20 | ex-Guild Esports   | W   | 0.936      | 0.331        | 0.005 (0.002)    | 0.166 (0.051)    | 0 (0.000) |    19.31 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           12 |     2695 | 2024-04-19 | Team Spirit Female | W   | 0.930      | 0.331        | 0.005 (0.002)    | 0.216 (0.067)    | 0 (0.000) |    17.50 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|           11 |     3117 | 2024-04-11 | NIP Impact         | L   | 0.877      | -            | -                | -                | -         |    -8.40 | ASTRA, Joanana, kezziwOw, meli, RacheLL    |
|           10 |     3175 | 2024-04-10 | 1win Gang          | L   | 0.870      | -            | -                | -                | -         |   -12.10 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|            9 |     3242 | 2024-04-09 | Team Spirit Female | W   | 0.863      | 0.303        | 0.005 (0.001)    | 0.216 (0.057)    | 0 (0.000) |    16.89 | ASTRA, Joanana, kezziwOw, meli, RacheLL    |
|            8 |     3408 | 2024-04-06 | Fearless Cheetahs  | L   | 0.842      | -            | -                | -                | -         |    -8.74 | ASTRA, Joanana, kezziwOw, meli, RacheLL    |
|            7 |     3417 | 2024-04-06 | Questionmark       | W   | 0.841      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.11 | ASTRA, Joanana, kezziwOw, meli, RacheLL    |
|            6 |     3551 | 2024-04-03 | NAVI Javelins      | W   | 0.824      | 0.331        | 0.024 (0.007)    | 0.265 (0.072)    | 0 (0.000) |    20.85 | ASTRA, Joanana, ManeschijnX, meli, RacheLL |
|            5 |     5465 | 2024-02-25 | BIG EQUIPA         | L   | 0.569      | -            | -                | -                | -         |    -5.31 | JennyR, juliano, kyossa, pauliiee, Zana    |
|            4 |     5550 | 2024-02-24 | Nemesis            | W   | 0.563      | 0.143        | 0.002 (0.000)    | 0.089 (0.007)    | 0 (0.000) |    10.82 | amyb, Emmy, Gaba, Lowlita, Monkey D. Julie |
|            3 |     5563 | 2024-02-24 | Dogenjoyers        | W   | 0.562      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.46 | anniken, Glymir, KiTTy-KaT, maliTy, Mar1on |
|            2 |     7274 | 2024-01-21 | Nemesis            | L   | 0.337      | -            | -                | -                | -         |    -3.97 | Joanana, kezziwOw, meli, RacheLL, suns1de  |
|            1 |     7336 | 2024-01-20 | depression         | W   | 0.331      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.23 | Joanana, kezziwOw, meli, RacheLL, suns1de  |

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
