### Roster Details<br />
Team Name: Intense Game<br />
Roster: bsd, ckzao, diozera, Domingues, Roz<br />
Region: [Americas]( ../standings_americas.md)<br />
<br />
Global Rank: [360](../standings_global.md)<br />
Regional Rank: [91]( ../standings_americas.md)<br />
Final Rank Value:  596.7<br />
<br />
Final Rank Value (596.7) = Starting Rank Value (610.8) + Head To Head Adjustments (-14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.176[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 610.8
- 400 + ( ( 0.104 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 610.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     6452 | 2024-02-04 | Bombril 1001 Utilidades   | L   | 0.431      | -            | -                | -                | -         |    -6.01 | bsd, ckzao, diozera, Domingues, Roz |
|           17 |     6497 | 2024-02-03 | MIBR Academy              | L   | 0.424      | -            | -                | -                | -         |    -4.98 | bsd, ckzao, diozera, Domingues, Roz |
|           16 |     6910 | 2024-01-27 | w7m esports               | L   | 0.379      | -            | -                | -                | -         |    -3.28 | bsd, ckzao, diozera, Roz, souz4h    |
|           15 |     7070 | 2024-01-25 | RED Canids                | L   | 0.366      | -            | -                | -                | -         |    -1.21 | bnc, bsd, ckzao, diozera, Roz       |
|           14 |     7081 | 2024-01-25 | 9z Academy                | W   | 0.364      | 0.143        | 0.002 (0.000)    | 0.311 (0.016)    | 0 (0.000) |     6.81 | bsd, ckzao, diozera, Domingues, Roz |
|           13 |     7105 | 2024-01-24 | paiN Gaming Academy       | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.064 (0.003)    | 0 (0.000) |     5.86 | bsd, ckzao, diozera, Domingues, Roz |
|           12 |     7565 | 2024-01-17 | Arena Jogue Fácil Esports | L   | 0.311      | -            | -                | -                | -         |    -4.83 | bsd, ckzao, diozera, Domingues, Roz |
|           11 |     7774 | 2024-01-13 | BESTIA                    | L   | 0.286      | -            | -                | -                | -         |    -1.13 | bsd, ckzao, DANVIET, diozera, Roz   |
|           10 |     7984 | 2024-01-10 | inSanitY Sports           | L   | 0.266      | -            | -                | -                | -         |    -5.51 | bsd, ckzao, DANVIET, diozera, Roz   |
|            9 |     8379 | 2023-12-20 | Sharks Youngsters         | L   | 0.124      | -            | -                | -                | -         |    -1.59 | bsd, ckzao, DANVIET, diozera, Roz   |
|            8 |     8393 | 2023-12-19 | TIMACETA                  | L   | 0.118      | -            | -                | -                | -         |    -1.76 | bsd, ckzao, DANVIET, diozera, Roz   |
|            7 |     8448 | 2023-12-17 | Sharks Youngsters         | W   | 0.104      | 0.143        | 0.003 (0.000)    | 0.422 (0.006)    | 0 (0.000) |     1.96 | bsd, ckzao, DANVIET, diozera, Roz   |
|            6 |     8574 | 2023-12-16 | Bombril 1001 Utilidades   | W   | 0.098      | 0.143        | 0.001 (0.000)    | 0.022 (0.000)    | 0 (0.000) |     1.58 | bsd, ckzao, DANVIET, diozera, Roz   |
|            5 |     8772 | 2023-12-14 | Myth e-Sports             | W   | 0.085      | 0.143        | 0.000 (0.000)    | 0.041 (0.001)    | 0 (0.000) |     1.36 | bsd, ckzao, DANVIET, Roz, suNday    |
|            4 |     8790 | 2023-12-14 | TIMACETA                  | L   | 0.084      | -            | -                | -                | -         |    -1.26 | bsd, ckzao, DANVIET, Roz, suNday    |
|            3 |     8817 | 2023-12-13 | Sharks Youngsters         | L   | 0.078      | -            | -                | -                | -         |    -0.99 | bsd, ckzao, DANVIET, Roz, suNday    |
|            2 |     8874 | 2023-12-12 | paiN Gaming Academy       | W   | 0.071      | 0.143        | 0.000 (0.000)    | 0.064 (0.001)    | 0 (0.000) |     1.11 | bsd, ckzao, DANVIET, Roz, suNday    |
|            1 |     9325 | 2023-12-04 | TIMACETA                  | L   | 0.019      | -            | -                | -                | -         |    -0.28 | bsd, ckzao, lealziNho, Roz, suNday  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($172.87)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-02-04 |      0.432 | $301.88        | $130.39         |
| 2023-12-20 |      0.125 | $308.12        | $38.64          |
| 2023-12-05 |      0.025 | $151.67        | $3.83           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
