### Roster Details<br />
Team Name: Grannys Knockers<br />
Roster: Anlelele, b0RUP, kristou, niko, TMB<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [94](../standings_global.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
Final Rank Value:  882.4<br />
<br />
Final Rank Value (882.4) = Starting Rank Value (828.7) + Head To Head Adjustments (53.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.361[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.121[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.211<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 828.7
- 400 + ( ( 0.211 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 828.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1664 | 2024-05-08 | Sashi Esport      | L   | 1.000      | -            | -                | -                | -         |    -3.19 | Anlelele, b0RUP, kristou, niko, TMB             |
|           11 |     1720 | 2024-05-07 | Gaimin Gladiators | W   | 1.000      | 0.143        | 0.092 (0.013)    | 0.727 (0.104)    | 0 (0.000) |    26.54 | Anlelele, b0RUP, kristou, niko, TMB             |
|           10 |     1768 | 2024-05-06 | brazylijski luz   | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.514 (0.073)    | 0 (0.000) |    17.00 | Anlelele, b0RUP, kristou, niko, TMB             |
|            9 |     1957 | 2024-05-02 | Endpoint          | L   | 1.000      | -            | -                | -                | -         |   -10.13 | b0RUP, kristou, niko, refrezh, TMB              |
|            8 |     2118 | 2024-04-29 | MOUZ NXT          | L   | 0.995      | -            | -                | -                | -         |    -7.38 | b0RUP, kristou, niko, refrezh, TMB              |
|            7 |     2165 | 2024-04-28 | Nemiga Gaming     | W   | 0.988      | 0.435        | 0.358 (0.154)    | 0.895 (0.385)    | 0 (0.000) |    27.11 | b0RUP, kristou, niko, refrezh, TMB              |
|            6 |     2369 | 2024-04-25 | Nexus Gaming      | W   | 0.969      | 0.435        | 0.003 (0.001)    | 0.857 (0.361)    | 0 (0.000) |    18.05 | BTN, ERSIN, ragga, s0und, XELLOW                |
|            5 |     2485 | 2024-04-23 | Sangal Esports    | L   | 0.954      | -            | -                | -                | -         |    -6.90 | b0RUP, kristou, niko, refrezh, TMB              |
|            4 |     2498 | 2024-04-22 | Zero Tenacity     | L   | 0.950      | -            | -                | -                | -         |    -8.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke        |
|            3 |     2524 | 2024-04-22 | Permitta Esports  | L   | 0.948      | -            | -                | -                | -         |    -9.53 | bnox, maaryy, mASKED, morelz, Vegi              |
|            2 |     3026 | 2024-04-15 | Sashi Esport      | L   | 0.902      | -            | -                | -                | -         |    -6.13 | Cabbi, IceBerg, kwezz, Lucky, MistR             |
|            1 |     3349 | 2024-04-09 | kONO.ECF          | W   | 0.861      | 0.384        | 0.013 (0.004)    | 0.853 (0.282)    | 0 (0.000) |    16.39 | amster, byr9, kensizor, Polbandana, s4ltovsk1yy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,064.11)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
