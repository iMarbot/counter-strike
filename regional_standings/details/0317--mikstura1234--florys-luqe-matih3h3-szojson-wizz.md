### Roster Details<br />
Team Name: Mikstura1234<br />
Roster: Florys, Luqe, MATIH3H3, Szojson, wizz<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [317](../standings_global.md)<br />
Regional Rank: [192]( ../standings_europe.md)<br />
Final Rank Value:  629.1<br />
<br />
Final Rank Value (629.1) = Starting Rank Value (666.0) + Head To Head Adjustments (-36.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.255[<sup>1</sup>](#table2)
- Bounty Collected: 0.158[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.109[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.0
- 400 + ( ( 0.131 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 666.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     4023 | 2024-03-22 | ex-Turów Zgorzelec Esport | L   | 0.745      | -            | -                | -                | -         |    -7.80 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|           11 |     4090 | 2024-03-21 | ThunderFlash              | L   | 0.737      | -            | -                | -                | -         |    -7.01 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|           10 |     4122 | 2024-03-20 | LODIS                     | L   | 0.731      | -            | -                | -                | -         |   -13.71 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            9 |     4165 | 2024-03-19 | Illuminar Gaming          | L   | 0.724      | -            | -                | -                | -         |    -8.12 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            8 |     4199 | 2024-03-18 | ENTERPRISE esports        | L   | 0.718      | -            | -                | -                | -         |    -4.83 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            7 |     4647 | 2024-03-10 | KU AZS UZ                 | W   | 0.664      | 0.143        | 0.000 (0.000)    | 0.018 (0.002)    | 0 (0.000) |     3.98 | Florys, Luqe, Speeky, Szojson, wizz   |
|            6 |     4650 | 2024-03-10 | delusional esports        | W   | 0.664      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.86 | Florys, Luqe, Speeky, Szojson, wizz   |
|            5 |     5460 | 2024-02-25 | KOMNATA                   | L   | 0.569      | -            | -                | -                | -         |    -9.11 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            4 |     5506 | 2024-02-24 | MASARNIA                  | W   | 0.565      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.21 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            3 |     5936 | 2024-02-17 | widelec                   | L   | 0.517      | -            | -                | -                | -         |    -8.01 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            2 |     5941 | 2024-02-17 | akceptuj                  | W   | 0.517      | 0.143        | 0.001 (0.000)    | 0.028 (0.002)    | 1 (0.517) |     7.68 | Florys, Luqe, MATIH3H3, Szojson, wizz |
|            1 |     5947 | 2024-02-17 | Nygusy                    | W   | 0.517      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.517) |     2.97 | Florys, Luqe, MATIH3H3, Szojson, wizz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($360.99)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-21 |      0.943 | $246.46        | $232.49         |
| 2024-02-17 |      0.517 | $248.34        | $128.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
