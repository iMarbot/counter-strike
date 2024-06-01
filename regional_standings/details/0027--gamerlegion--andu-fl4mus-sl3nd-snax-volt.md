### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, Snax, volt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [27](../standings_global.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
Final Rank Value:  1288.4<br />
<br />
Final Rank Value (1288.4) = Starting Rank Value (1248.6) + Head To Head Adjustments (39.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.606[<sup>1</sup>](#table2)
- Bounty Collected: 0.478[<sup>2</sup>](#table1)
- Opponent Network: 0.266[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.417<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1248.6
- 400 + ( ( 0.417 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 1248.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      498 | 2024-05-22 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -1.98 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |      563 | 2024-05-21 | AMKAL ESPORTS     | W   | 1.000      | 0.769        | 0.146 (0.113)    | 0.565 (0.435)    | 0 (0.000) |    15.53 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |      927 | 2024-05-18 | Fnatic            | W   | 1.000      | 0.769        | 0.147 (0.113)    | 0.480 (0.369)    | 0 (0.000) |    11.51 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |      971 | 2024-05-17 | Gaimin Gladiators | W   | 1.000      | 0.769        | 0.092 (0.071)    | 0.711 (0.546)    | 0 (0.000) |    10.94 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     1666 | 2024-05-07 | Virtus.pro        | L   | 1.000      | -            | -                | -                | -         |    -2.99 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     1883 | 2024-05-03 | ENCE              | W   | 1.000      | 0.889        | 0.202 (0.179)    | 0.280 (0.249)    | 1 (1.000) |    19.66 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     1908 | 2024-05-02 | FORZE Esports     | W   | 1.000      | 0.889        | 0.111 (0.099)    | 0.440 (0.392)    | 1 (1.000) |     9.93 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     1989 | 2024-05-01 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.50 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2038 | 2024-04-30 | ENCE              | W   | 1.000      | 0.889        | 0.202 (0.179)    | 0.280 (0.249)    | 1 (1.000) |    21.15 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2767 | 2024-04-18 | Sashi Esport      | L   | 0.923      | -            | -                | -                | -         |   -20.22 | aNdu, isak, sl3nd, Snax, volt   |
|            5 |     2818 | 2024-04-17 | Copenhagen Wolves | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.309 (0.040)    | 0 (0.000) |     1.02 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2914 | 2024-04-16 | MOUZ NXT          | W   | 0.909      | 0.384        | 0.157 (0.055)    | 0.950 (0.332)    | 0 (0.000) |     9.01 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3593 | 2024-04-02 | Monte             | L   | 0.817      | -            | -                | -                | -         |   -12.50 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3607 | 2024-04-02 | FAVBET Team       | L   | 0.816      | -            | -                | -                | -         |   -21.68 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3628 | 2024-04-01 | GUN5 Esports      | W   | 0.809      | 0.384        | 0.000 (0.000)    | 0.143 (0.044)    | 0 (0.000) |     0.93 | aNdu, isak, sl3nd, Snax, volt   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($67,500.00)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.22) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-23 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-05-12 |      1.000 | $17,500.00     | $17,500.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
