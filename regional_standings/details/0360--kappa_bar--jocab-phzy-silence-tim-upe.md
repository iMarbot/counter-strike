### Roster Details<br />
Team Name: Kappa Bar<br />
Roster: jocab, phzy, Silence, TIM, upE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [360](../standings_global.md)<br />
Regional Rank: [215]( ../standings_europe.md)<br />
Final Rank Value:  601.7<br />
<br />
Final Rank Value (601.7) = Starting Rank Value (513.5) + Head To Head Adjustments (88.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.204[<sup>2</sup>](#table1)
- Opponent Network: 0.020[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.056<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 513.5
- 400 + ( ( 0.056 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 513.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      597 | 2024-05-21 | showmakerz    | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.201 (0.029)    | 0 (0.000) |    14.70 | jocab, phzy, Silence, TIM, upE                 |
|            9 |     2389 | 2024-04-24 | Johnny Speeds | L   | 0.965      | -            | -                | -                | -         |    -2.24 | Chawzyyy, draken, Lekr0, Ro1f, spooke          |
|            8 |     2391 | 2024-04-24 | Lemoncats     | W   | 0.964      | 0.143        | 0.000 (0.000)    | 0.101 (0.014)    | 0 (0.000) |    12.37 | delle, jocab, phzy, Silence, TIM               |
|            7 |     2396 | 2024-04-24 | Alliance      | W   | 0.964      | 0.143        | 0.004 (0.001)    | 0.529 (0.073)    | 0 (0.000) |    25.88 | delle, jocab, phzy, Silence, TIM               |
|            6 |     3887 | 2024-03-27 | Kappa Borr    | W   | 0.778      | 0.143        | 0.000 (0.000)    | 0.127 (0.014)    | 0 (0.000) |    11.38 | jocab, phzy, Silence, TIM, upE                 |
|            5 |     4123 | 2024-03-22 | Lilmix        | W   | 0.744      | 0.143        | 0.006 (0.001)    | 0.593 (0.063)    | 0 (0.000) |    18.46 | jocab, phzy, Silence, TIM, upE                 |
|            4 |     4608 | 2024-03-13 | Full Kareta   | W   | 0.684      | 0.143        | 0.000 (0.000)    | 0.027 (0.003)    | 0 (0.000) |     7.32 | jocab, phzy, Silence, TIM, upE                 |
|            3 |     9543 | 2023-12-05 | angelnumbers  | L   | 0.025      | -            | -                | -                | -         |    -0.26 | JiBe, nomiss, Twinkey, VIRREE, zen             |
|            2 |     9546 | 2023-12-05 | flowskola     | W   | 0.025      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.27 | Chawzyyy, magi, MistFire, realyummy, Svedjehed |
|            1 |     9564 | 2023-12-05 | Curlews       | W   | 0.024      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.27 | jayzaR, jocab, pupcake, TIM, upE               |

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
