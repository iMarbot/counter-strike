### Roster Details<br />
Team Name: Hawks (Argentinian team)<br />
Roster: guidimon, KUN, matinaso, pablek, pegin<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [242](../standings_global.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
Final Rank Value:  671.0<br />
<br />
Final Rank Value (671.0) = Starting Rank Value (656.2) + Head To Head Adjustments (14.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.129<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.2
- 400 + ( ( 0.129 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 656.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1839 | 2024-03-25 | MIBR Academy            | L   | 0.926      | -            | -                | -                | -         |   -12.48 | guidimon, KUN, matinaso, pablek, pegin  |
|           10 |     1929 | 2024-03-22 | Bombril 1001 Utilidades | L   | 0.906      | -            | -                | -                | -         |   -13.20 | guidimon, KUN, matinaso, pablek, pegin  |
|            9 |     2009 | 2024-03-20 | Intense Game            | L   | 0.893      | -            | -                | -                | -         |   -12.59 | guidimon, KUN, matinaso, pablek, pegin  |
|            8 |     2018 | 2024-03-20 | Sharks Youngsters       | W   | 0.892      | 0.143        | 0.004 (0.000)    | 0.211 (0.027)    | 0 (0.000) |    11.93 | guidimon, KUN, matinaso, pablek, pegin  |
|            7 |     3011 | 2024-02-27 | NIGERIA 96              | W   | 0.746      | 0.143        | 0.002 (0.000)    | 0.095 (0.010)    | 0 (0.000) |    10.57 | guidimon, KUN, nacho, nasher, pablek    |
|            6 |     3095 | 2024-02-25 | SoJoga Academy          | W   | 0.732      | 0.143        | 0.001 (0.000)    | 0.109 (0.011)    | 0 (0.000) |    11.09 | Colt, k1not1, Patoz1k, pkN, telezin     |
|            5 |     3132 | 2024-02-24 | NIGERIA 96              | L   | 0.726      | -            | -                | -                | -         |   -12.50 | deemO, leozik4, nv1nJ, predict, t9mpest |
|            4 |     3136 | 2024-02-24 | Myth e-Sports           | W   | 0.726      | 0.143        | 0.000 (0.000)    | 0.070 (0.007)    | 0 (0.000) |    10.36 | guidimon, KUN, nacho, nasher, pablek    |
|            3 |     3141 | 2024-02-24 | SoJoga Academy          | W   | 0.726      | 0.143        | 0.001 (0.000)    | 0.109 (0.011)    | 0 (0.000) |    10.68 | guidimon, KUN, nacho, nasher, pablek    |
|            2 |     3148 | 2024-02-24 | MIBR Female             | W   | 0.725      | 0.143        | 0.027 (0.003)    | 0.199 (0.021)    | 0 (0.000) |    14.13 | Babs, dani, ferzy, khizha, REGIANE      |
|            1 |     3393 | 2024-02-19 | 9z Team                 | L   | 0.694      | -            | -                | -                | -         |    -3.19 | guidimon, KUN, nacho, nasher, pablek    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($449.56)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
