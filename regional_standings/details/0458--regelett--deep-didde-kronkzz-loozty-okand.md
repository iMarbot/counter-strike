### Roster Details<br />
Team Name: regelett<br />
Roster: DeeP, didde, Kronkzz, Loozty, okand<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [458](../standings_global.md)<br />
Regional Rank: [277]( ../standings_europe.md)<br />
Final Rank Value:  415.4<br />
<br />
Final Rank Value (415.4) = Starting Rank Value (401.1) + Head To Head Adjustments (14.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.001<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 401.1
- 400 + ( ( 0.001 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 401.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      485 | 2024-05-22 | Kappa Borr    | L   | 1.000      | -            | -                | -                | -         |   -12.00 | DeeP, didde, Kronkzz, Loozty, okand |
|           12 |     1270 | 2024-05-14 | Lemondogs     | L   | 1.000      | -            | -                | -                | -         |    -7.34 | DeeP, didde, Kronkzz, Loozty, okand |
|           11 |     1883 | 2024-05-03 | Flying Angels | L   | 1.000      | -            | -                | -                | -         |    -7.18 | DeeP, Kronkzz, LK, Loozty, okand    |
|           10 |     1884 | 2024-05-03 | Odjur         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.028 (0.004)    | 0 (0.000) |    17.98 | DeeP, Kronkzz, LK, Loozty, okand    |
|            9 |     1887 | 2024-05-03 | Ljusdalspeekk | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    14.20 | DeeP, Kronkzz, LK, Loozty, okand    |
|            8 |     1939 | 2024-05-02 | Full Kareta   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.027 (0.004)    | 0 (0.000) |    14.51 | DeeP, didde, Kronkzz, Loozty, okand |
|            7 |     2420 | 2024-04-24 | Kario Mart    | L   | 0.963      | -            | -                | -                | -         |   -14.17 | DeeP, didde, Kronkzz, Loozty, okand |
|            6 |     2811 | 2024-04-18 | Lemoncats     | W   | 0.924      | 0.143        | 0.000 (0.000)    | 0.101 (0.013)    | 0 (0.000) |    18.64 | DeeP, didde, Kronkzz, Loozty, okand |
|            5 |     3244 | 2024-04-10 | showmakerz    | L   | 0.871      | -            | -                | -                | -         |    -7.46 | DeeP, jujje, Kronkzz, Loozty, okand |
|            4 |     3523 | 2024-04-05 | Begrip Gaming | L   | 0.837      | -            | -                | -                | -         |    -7.58 | DeeP, didde, Kronkzz, Loozty, okand |
|            3 |     3832 | 2024-03-28 | Lemondogs     | L   | 0.784      | -            | -                | -                | -         |    -5.92 | DeeP, didde, Kronkzz, Loozty, okand |
|            2 |     4131 | 2024-03-22 | Curlews       | W   | 0.744      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.34 | DeeP, didde, Kronkzz, Loozty, okand |
|            1 |     4671 | 2024-03-12 | Johnny Speeds | L   | 0.678      | -            | -                | -                | -         |    -0.67 | DeeP, didde, Kronkzz, Loozty, okand |

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