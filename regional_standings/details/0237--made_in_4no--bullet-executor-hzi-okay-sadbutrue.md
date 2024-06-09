### Roster Details<br />
Team Name: Made In 4No<br />
Roster: BulleT, ExecutoR, HZI, OKay, sadbutrue<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [237](../standings_global.md)<br />
Regional Rank: [31]( ../standings_asia.md)<br />
Final Rank Value:  696.7<br />
<br />
Final Rank Value (696.7) = Starting Rank Value (691.3) + Head To Head Adjustments (5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.234[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 691.3
- 400 + ( ( 0.143 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 691.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     3524 | 2024-04-05 | Grayfox Esports | L   | 0.837      | -            | -                | -                | -         |   -14.92 | BulleT, ExecutoR, HZI, OKay, sadbutrue              |
|            9 |     3542 | 2024-04-05 | StrikingKats    | W   | 0.835      | 0.270        | 0.001 (0.000)    | 0.023 (0.005)    | 0 (0.000) |     6.77 | BulleT, ExecutoR, HZI, OKay, sadbutrue              |
|            8 |     4339 | 2024-03-17 | True Rippers    | W   | 0.712      | 0.242        | 0.025 (0.004)    | 0.241 (0.042)    | 0 (0.000) |    13.31 | BulleT, ExecutoR, HZI, OKay, sadbutrue              |
|            7 |     4369 | 2024-03-17 | opium5          | W   | 0.710      | 0.242        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.68 | BulleT, ExecutoR, HZI, OKay, sadbutrue              |
|            6 |     6539 | 2024-02-07 | Gods Reign      | L   | 0.454      | -            | -                | -                | -         |    -6.93 | BulleT, ExecutoR, insmutje, OKay, olofmeister       |
|            5 |     6760 | 2024-02-03 | st4rboys        | W   | 0.423      | 0.143        | 0.014 (0.001)    | 0.088 (0.005)    | 0 (0.000) |     6.69 | Ang3l10wow, Bloody, Dynamite, Scoffic, Sharpshooter |
|            4 |     6900 | 2024-02-01 | Team Mystic     | W   | 0.409      | 0.143        | 0.000 (0.000)    | 0.011 (0.001)    | 0 (0.000) |     2.19 | Flica, Hatz, Kamikaze, KHG, Protagonist             |
|            3 |     6983 | 2024-01-30 | Come Mid        | L   | 0.397      | -            | -                | -                | -         |    -9.25 | BoNo, HSB, Rocky, sadbutrue, SOULM8                 |
|            2 |     7056 | 2024-01-29 | Team Paradox    | W   | 0.389      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.93 | ackerman, aloneguy, AyaaNNNN, Psy, ShAyAaN          |
|            1 |     7105 | 2024-01-28 | vRn             | W   | 0.382      | 0.143        | 0.000 (0.000)    | 0.011 (0.001)    | 0 (0.000) |     1.96 | Abdur, Kriminal, Musab, Sr., traNz                  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,036.41)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-06 |      0.844 | $400.00        | $337.44         |
| 2024-03-17 |      0.712 | $500.00        | $355.80         |
| 2024-02-10 |      0.469 | $5,000.00      | $2,343.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
