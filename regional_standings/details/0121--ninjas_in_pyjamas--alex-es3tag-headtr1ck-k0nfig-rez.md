### Roster Details<br />
Team Name: Ninjas in Pyjamas<br />
Roster: alex, es3tag, headtr1ck, k0nfig, REZ<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [121](../standings_global.md)<br />
Regional Rank: [86]( ../standings_europe.md)<br />
Final Rank Value:  816.0<br />
<br />
Final Rank Value (816.0) = Starting Rank Value (799.3) + Head To Head Adjustments (16.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.324[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.057[<sup>2</sup>](#table1)

The average of these factors is 0.201<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 799.3
- 400 + ( ( 0.201 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 799.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     3596 | 2024-02-15 | SAW                 | L   | 0.664      | -            | -                | -                | -         |    -0.62 | alex, es3tag, headtr1ck, k0nfig, REZ |
|           11 |     3632 | 2024-02-14 | AMKAL ESPORTS       | L   | 0.658      | -            | -                | -                | -         |    -2.09 | alex, es3tag, headtr1ck, k0nfig, REZ |
|           10 |     3640 | 2024-02-14 | Eternal Fire        | L   | 0.657      | -            | -                | -                | -         |    -0.09 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            9 |     4190 | 2024-01-29 | Dynamo Eclot        | L   | 0.553      | -            | -                | -                | -         |    -2.46 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            8 |     4328 | 2024-01-26 | G2 Esports          | L   | 0.531      | -            | -                | -                | -         |    -0.04 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            7 |     4435 | 2024-01-23 | Complexity Gaming   | W   | 0.511      | 0.581        | 0.271 (0.081)    | 0.274 (0.081)    | 1 (0.511) |    15.81 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            6 |     4490 | 2024-01-22 | G2 Esports          | L   | 0.503      | -            | -                | -                | -         |    -0.04 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            5 |     4694 | 2024-01-17 | 500                 | L   | 0.473      | -            | -                | -                | -         |    -7.45 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            4 |     4698 | 2024-01-17 | Team Spirit Academy | W   | 0.473      | 0.143        | 0.021 (0.001)    | 0.422 (0.028)    | 0 (0.000) |     7.81 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            3 |     4725 | 2024-01-17 | CYBERSHOKE Esports  | W   | 0.472      | 0.143        | 0.004 (0.000)    | 0.220 (0.015)    | 0 (0.000) |     5.88 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            2 |     6534 | 2023-11-23 | Natus Vincere       | L   | 0.103      | -            | -                | -                | -         |    -0.01 | alex, es3tag, headtr1ck, k0nfig, REZ |
|            1 |     6576 | 2023-11-22 | FaZe Clan           | L   | 0.096      | -            | -                | -                | -         |    -0.00 | alex, es3tag, headtr1ck, k0nfig, REZ |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,880.05)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-01-28 |      0.545 | $8,500.00      | $4,633.29       |
| 2023-11-26 |      0.125 | $10,000.00     | $1,246.76       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
