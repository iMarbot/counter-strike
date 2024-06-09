### Roster Details<br />
Team Name: detoks<br />
Roster: darchevile, hotd0g, KukuBambo, next1me, xKacpersky<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [439](../standings_global.md)<br />
Regional Rank: [266]( ../standings_europe.md)<br />
Final Rank Value:  509.0<br />
<br />
Final Rank Value (509.0) = Starting Rank Value (498.6) + Head To Head Adjustments (10.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.191[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.049<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 498.6
- 400 + ( ( 0.049 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 498.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     8560 | 2023-12-29 | onliners5                 | L   | 0.184      | -            | -                | -                | -         |    -2.12 | darchevile, hotd0g, KukuBambo, next1me, xKacpersky |
|           12 |     8563 | 2023-12-29 | plusW                     | W   | 0.184      | 0.143        | 0.000 (0.000)    | 0.094 (0.002)    | 0 (0.000) |     3.06 | darchevile, hotd0g, KukuBambo, next1me, xKacpersky |
|           11 |     8616 | 2023-12-21 | Looking4org               | W   | 0.132      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.91 | darchevile, hotd0g, KukuBambo, next1me, xKacpersky |
|           10 |     8624 | 2023-12-21 | XI Esport                 | W   | 0.131      | 0.143        | 0.001 (0.000)    | 0.277 (0.005)    | 0 (0.000) |     3.06 | darchevile, hotd0g, KukuBambo, next1me, xKacpersky |
|            9 |     8773 | 2023-12-17 | Astralis Talent           | L   | 0.102      | -            | -                | -                | -         |    -0.28 | darchevile, hotd0g, KukuBambo, maaryy, tomiko      |
|            8 |     8895 | 2023-12-16 | NOM Esports               | W   | 0.096      | 0.303        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.08 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e        |
|            7 |     9009 | 2023-12-15 | Nexus Gaming              | L   | 0.090      | -            | -                | -                | -         |    -0.26 | BTN, ragga, s0und, smekk, XELLOW                   |
|            6 |     9019 | 2023-12-15 | ex-Turów Zgorzelec Esport | L   | 0.089      | -            | -                | -                | -         |    -0.45 | darchevile, hotd0g, KukuBambo, maaryy, tomiko      |
|            5 |     9158 | 2023-12-12 | Kappa Bar                 | W   | 0.068      | 0.303        | 0.000 (0.000)    | 0.062 (0.001)    | 0 (0.000) |     1.16 | dezt, jayzaR, pupcake, TIM, upE                    |
|            4 |     9200 | 2023-12-11 | UNiTY esports             | W   | 0.063      | 0.333        | 0.021 (0.000)    | 0.766 (0.016)    | 0 (0.000) |     1.80 | darchevile, hotd0g, KukuBambo, maaryy, tomiko      |
|            3 |     9282 | 2023-12-09 | Team Spirit Academy       | L   | 0.051      | -            | -                | -                | -         |    -0.34 | alpha, baz, keegaN, Magnojez, notineki             |
|            2 |     9527 | 2023-12-06 | The Witchers              | W   | 0.028      | 0.303        | 0.009 (0.000)    | 0.060 (0.001)    | 0 (0.000) |     0.68 | darchevile, hotd0g, KukuBambo, maaryy, tomiko      |
|            1 |     9780 | 2023-12-02 | Passion UA                | W   | 0.003      | 0.303        | 0.057 (0.000)    | 1.000 (0.001)    | 0 (0.000) |     0.07 | jackasmo, jambo, marat2k, s-chilla, zeRRoFIX       |

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
