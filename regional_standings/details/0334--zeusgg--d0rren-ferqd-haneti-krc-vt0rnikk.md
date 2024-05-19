### Roster Details<br />
Team Name: ZEUSGG<br />
Roster: d0RREN, ferqd, HANETi, krc, vt0rnikk<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [334](../standings_global.md)<br />
Regional Rank: [204]( ../standings_europe.md)<br />
Final Rank Value:  541.9<br />
<br />
Final Rank Value (541.9) = Starting Rank Value (521.2) + Head To Head Adjustments (20.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.218[<sup>2</sup>](#table1)
- Opponent Network: 0.026[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.061<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 521.2
- 400 + ( ( 0.061 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 521.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |      740 | 2024-04-20 | MIRAI Gaming | L   | 1.000      | -            | -                | -                | -         |    -8.22 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|           11 |      753 | 2024-04-20 | MIRAI Gaming | L   | 1.000      | -            | -                | -                | -         |    -8.82 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|           10 |     1149 | 2024-04-12 | The MongolZ  | L   | 1.000      | -            | -                | -                | -         |    -0.12 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            9 |     1151 | 2024-04-12 | The MongolZ  | L   | 1.000      | -            | -                | -                | -         |    -0.12 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            8 |     1759 | 2024-03-27 | LYG Gaming   | W   | 0.937      | 0.417        | 0.004 (0.002)    | 0.380 (0.149)    | 0 (0.000) |    23.76 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            7 |     1762 | 2024-03-27 | LYG Gaming   | L   | 0.937      | -            | -                | -                | -         |    -5.37 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            6 |     1825 | 2024-03-26 | TYLOO        | L   | 0.931      | -            | -                | -                | -         |    -1.77 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            5 |     1829 | 2024-03-26 | TYLOO        | L   | 0.931      | -            | -                | -                | -         |    -1.80 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            4 |     1847 | 2024-03-25 | -72C         | W   | 0.924      | 0.417        | 0.003 (0.001)    | 0.300 (0.116)    | 0 (0.000) |    24.24 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            3 |     1848 | 2024-03-25 | -72C         | L   | 0.924      | -            | -                | -                | -         |    -4.50 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            2 |     2342 | 2024-03-13 | -72C         | L   | 0.843      | -            | -                | -                | -         |    -4.49 | d0RREN, ferqd, HANETi, krc, vt0rnikk |
|            1 |     2381 | 2024-03-12 | Moon Esports | W   | 0.837      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.90 | d0RREN, ferqd, HANETi, krc, vt0rnikk |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
