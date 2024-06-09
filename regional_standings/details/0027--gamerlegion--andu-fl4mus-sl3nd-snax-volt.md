### Roster Details<br />
Team Name: GamerLegion<br />
Roster: aNdu, FL4MUS, sl3nd, Snax, volt<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [27](../standings_global.md)<br />
Regional Rank: [18]( ../standings_europe.md)<br />
Final Rank Value:  1287.2<br />
<br />
Final Rank Value (1287.2) = Starting Rank Value (1245.2) + Head To Head Adjustments (42.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.606[<sup>1</sup>](#table2)
- Bounty Collected: 0.477[<sup>2</sup>](#table1)
- Opponent Network: 0.263[<sup>2</sup>](#table1)
- LAN Wins: 0.317[<sup>2</sup>](#table1)

The average of these factors is 0.416<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1245.2
- 400 + ( ( 0.416 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 1245.2


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
|           15 |      505 | 2024-05-22 | Eternal Fire      | L   | 1.000      | -            | -                | -                | -         |    -1.99 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           14 |      574 | 2024-05-21 | AMKAL ESPORTS     | W   | 1.000      | 0.769        | 0.146 (0.113)    | 0.565 (0.435)    | 0 (0.000) |    15.62 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           13 |      939 | 2024-05-18 | Fnatic            | W   | 1.000      | 0.769        | 0.147 (0.113)    | 0.480 (0.369)    | 0 (0.000) |    11.64 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           12 |      983 | 2024-05-17 | Gaimin Gladiators | W   | 1.000      | 0.769        | 0.092 (0.071)    | 0.727 (0.559)    | 0 (0.000) |    11.14 | aNdu, FL4MUS, sl3nd, Snax, volt |
|           11 |     1684 | 2024-05-07 | Virtus.pro        | L   | 1.000      | -            | -                | -                | -         |    -2.97 | aNdu, isak, sl3nd, Snax, volt   |
|           10 |     1908 | 2024-05-03 | ENCE              | W   | 1.000      | 0.889        | 0.202 (0.179)    | 0.280 (0.249)    | 1 (1.000) |    19.81 | aNdu, isak, sl3nd, Snax, volt   |
|            9 |     1934 | 2024-05-02 | FORZE Esports     | W   | 1.000      | 0.889        | 0.101 (0.090)    | 0.372 (0.330)    | 1 (1.000) |    10.15 | aNdu, isak, sl3nd, Snax, volt   |
|            8 |     2019 | 2024-05-01 | MOUZ              | L   | 1.000      | -            | -                | -                | -         |    -0.50 | aNdu, isak, sl3nd, Snax, volt   |
|            7 |     2071 | 2024-04-30 | ENCE              | W   | 1.000      | 0.889        | 0.202 (0.179)    | 0.280 (0.249)    | 1 (1.000) |    21.30 | aNdu, isak, sl3nd, Snax, volt   |
|            6 |     2823 | 2024-04-18 | Sashi Esport      | L   | 0.923      | -            | -                | -                | -         |   -20.24 | aNdu, isak, sl3nd, Snax, volt   |
|            5 |     2875 | 2024-04-17 | Copenhagen Wolves | W   | 0.918      | 0.143        | 0.000 (0.000)    | 0.387 (0.051)    | 0 (0.000) |     1.25 | aNdu, isak, sl3nd, Snax, volt   |
|            4 |     2975 | 2024-04-16 | MOUZ NXT          | W   | 0.909      | 0.384        | 0.157 (0.055)    | 0.977 (0.341)    | 0 (0.000) |     9.46 | aNdu, isak, sl3nd, Snax, volt   |
|            3 |     3682 | 2024-04-02 | Monte             | L   | 0.817      | -            | -                | -                | -         |   -12.28 | aNdu, isak, sl3nd, Snax, volt   |
|            2 |     3697 | 2024-04-02 | FAVBET Team       | L   | 0.816      | -            | -                | -                | -         |   -21.36 | aNdu, isak, sl3nd, Snax, volt   |
|            1 |     3720 | 2024-04-01 | GUN5 Esports      | W   | 0.809      | 0.384        | 0.000 (0.000)    | 0.143 (0.044)    | 0 (0.000) |     0.98 | aNdu, isak, sl3nd, Snax, volt   |

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
