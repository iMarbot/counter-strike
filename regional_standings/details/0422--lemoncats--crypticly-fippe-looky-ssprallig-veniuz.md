### Roster Details<br />
Team Name: Lemoncats<br />
Roster: Crypticly, fippe, looky, SSprallig, veniuz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [422](../standings_global.md)<br />
Regional Rank: [256]( ../standings_europe.md)<br />
Final Rank Value:  516.0<br />
<br />
Final Rank Value (516.0) = Starting Rank Value (525.6) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.6
- 400 + ( ( 0.062 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 525.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      646 | 2024-05-20 | Nexus Gaming  | L   | 1.000      | -            | -                | -                | -         |    -4.31 | Crypticly, fippe, looky, SSprallig, veniuz |
|            9 |      753 | 2024-05-19 | Preasy Esport | W   | 1.000      | 0.354        | 0.008 (0.003)    | 0.642 (0.227)    | 0 (0.000) |    26.40 | Crypticly, fippe, looky, SSprallig, veniuz |
|            8 |     1806 | 2024-05-04 | Begrip Gaming | L   | 1.000      | -            | -                | -                | -         |   -14.87 | Ayoh, fippe, looky, mogv, veniuz           |
|            7 |     2350 | 2024-04-24 | Kappa Bar     | L   | 0.964      | -            | -                | -                | -         |   -12.33 | delle, jocab, phzy, Silence, TIM           |
|            6 |     2354 | 2024-04-24 | WompWomp      | W   | 0.964      | 0.143        | 0.002 (0.000)    | 0.110 (0.015)    | 0 (0.000) |    19.80 | pAblo, Sn0w, TiiREX, walleN, wiking        |
|            5 |     2416 | 2024-04-23 | Curlews       | W   | 0.957      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     9.66 | Ayoh, fippe, looky, mogv, veniuz           |
|            4 |     2755 | 2024-04-18 | regelett      | L   | 0.924      | -            | -                | -                | -         |   -18.62 | Ayoh, fippe, looky, mogv, veniuz           |
|            3 |     3495 | 2024-04-04 | Young Gods    | L   | 0.830      | -            | -                | -                | -         |   -12.39 | Ayoh, fippe, looky, mogv, veniuz           |
|            2 |     4130 | 2024-03-20 | Full Kareta   | W   | 0.731      | 0.143        | 0.000 (0.000)    | 0.027 (0.003)    | 0 (0.000) |     7.56 | Ayoh, fippe, looky, mogv, veniuz           |
|            1 |     4483 | 2024-03-13 | plusW         | L   | 0.684      | -            | -                | -                | -         |   -10.43 | Ayoh, fippe, looky, mogv, veniuz           |

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
