### Roster Details<br />
Team Name: Corinthians Esports<br />
Roster: hazart, ph1, pooldolsk, rainny, zock9<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [352](../standings_global.md)<br />
Regional Rank: [86]( ../standings_americas.md)<br />
Final Rank Value:  606.4<br />
<br />
Final Rank Value (606.4) = Starting Rank Value (597.4) + Head To Head Adjustments (9.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.206[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.097<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 597.4
- 400 + ( ( 0.097 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 597.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |     7344 | 2024-01-24 | Formiguinhas              | L   | 0.358      | -            | -                | -                | -         |    -7.76 | hazart, ph1, pooldolsk, rainny, zock9    |
|           16 |     7402 | 2024-01-23 | pugdesonesto              | W   | 0.352      | 0.143        | 0.001 (0.000)    | 0.146 (0.007)    | 0 (0.000) |     5.99 | hazart, ph1, pooldolsk, rainny, zock9    |
|           15 |     7412 | 2024-01-23 | Bombril 1001 Utilidades   | W   | 0.351      | 0.143        | 0.001 (0.000)    | 0.022 (0.001)    | 0 (0.000) |     5.62 | hazart, ph1, pooldolsk, rainny, zock9    |
|           14 |     7463 | 2024-01-22 | Sharks Youngsters         | W   | 0.344      | 0.143        | 0.003 (0.000)    | 0.407 (0.020)    | 0 (0.000) |     6.54 | hazart, ph1, pooldolsk, rainny, zock9    |
|           13 |     7648 | 2024-01-19 | MIBR Academy              | L   | 0.324      | -            | -                | -                | -         |    -3.83 | hazart, ph1, pooldolsk, rainny, zock9    |
|           12 |     8614 | 2023-12-21 | 9z Academy                | L   | 0.133      | -            | -                | -                | -         |    -1.68 | japinha, ph1, pooldolsk, rainny, zock9   |
|           11 |     8692 | 2023-12-17 | pugdesonesto              | W   | 0.105      | 0.143        | 0.001 (0.000)    | 0.146 (0.002)    | 0 (0.000) |     1.88 | japinha, ph1, pooldolsk, rainny, zock9   |
|           10 |     8816 | 2023-12-16 | TEAM ORUGA                | W   | 0.099      | 0.143        | 0.000 (0.000)    | 0.094 (0.001)    | 0 (0.000) |     1.58 | gAtito, kissmyaug, pegin, rushardo, zLN  |
|            9 |     8820 | 2023-12-16 | Vex Dragons               | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.44 | crownzera, machado, sanc, void, wallz1k  |
|            8 |     8840 | 2023-12-16 | 9z Academy                | L   | 0.098      | -            | -                | -                | -         |    -1.23 | divine, MaxOff, perez, slashzz, Tomate   |
|            7 |     8852 | 2023-12-16 | O Plano B                 | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.77 | ivanzinho, kenznk, NyRo, s1cko, yangue   |
|            6 |     8868 | 2023-12-16 | 2Game Esports B           | W   | 0.097      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.77 | kelvin, LeoZ, nickWRLD, spARK, ZvDo      |
|            5 |     9184 | 2023-12-11 | Case Esports              | L   | 0.064      | -            | -                | -                | -         |    -0.79 | RCF, snow, souz4h, yepz, zmb             |
|            4 |     9365 | 2023-12-08 | Arena Jogue Fácil Esports | L   | 0.044      | -            | -                | -                | -         |    -0.69 | guizin, ph1, pooldolsk, rainny, zock9    |
|            3 |     9412 | 2023-12-07 | ex-Corinthians Esports    | W   | 0.038      | 0.262        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     0.41 | DANVIET, Demonos, fREQ, proSHOW, r4ul    |
|            2 |     9713 | 2023-12-02 | w7m esports               | L   | 0.005      | -            | -                | -                | -         |    -0.09 | Alisson, koala, pooldolsk, rainny, zock9 |
|            1 |     9716 | 2023-12-02 | Patrulha Canina           | W   | 0.005      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.04 | dudinho, huffy, kln, lokyy, sanc         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($43.15)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
