### Roster Details<br />
Team Name: GenOne<br />
Roster: AMANEK, Brooxsy, Graviti, Kursy, Razzmo<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [283](../standings_global.md)<br />
Regional Rank: [176]( ../standings_europe.md)<br />
Final Rank Value:  629.3<br />
<br />
Final Rank Value (629.3) = Starting Rank Value (563.4) + Head To Head Adjustments (66.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.061[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.082<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 563.4
- 400 + ( ( 0.082 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 563.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2740 | 2024-03-04 | 3DMAX                | L   | 0.786      | -            | -                | -                | -             |    -3.22 | AMANEK, Brooxsy, Graviti, Kursy, Razzmo |
|           12 |     2846 | 2024-03-02 | BetBoom Team         | L   | 0.772      | -            | -                | -                | -             |    -0.27 | AMANEK, Brooxsy, Graviti, Kursy, Razzmo |
|           11 |     2920 | 2024-03-01 | HOTU                 | W   | 0.764      | 0.371        | 0.011 (0.003)    | 0.323 (0.092)    | false (0.000) |    17.57 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|           10 |     2943 | 2024-02-29 | FLuffy Gangsters     | W   | 0.759      | 0.371        | 0.000 (0.000)    | 0.264 (0.074)    | false (0.000) |    12.51 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            9 |     3160 | 2024-02-24 | Eternal Fire Academy | W   | 0.724      | 0.371        | 0.013 (0.003)    | 0.179 (0.048)    | false (0.000) |    14.92 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            8 |     3254 | 2024-02-22 | Insilio              | L   | 0.711      | -            | -                | -                | -             |    -2.42 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            7 |     3301 | 2024-02-21 | Team Secret          | L   | 0.705      | -            | -                | -                | -             |    -7.78 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            6 |     3357 | 2024-02-20 | Permitta Esports     | L   | 0.698      | -            | -                | -                | -             |    -2.10 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            5 |     3495 | 2024-02-17 | RUBY                 | L   | 0.678      | -            | -                | -                | -             |    -2.94 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            4 |     3536 | 2024-02-16 | The Chosen Few       | W   | 0.671      | 0.371        | 0.007 (0.002)    | 0.457 (0.114)    | false (0.000) |    16.31 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            3 |     3679 | 2024-02-13 | Aurora Young Blud    | W   | 0.651      | 0.371        | 0.017 (0.004)    | 0.422 (0.102)    | false (0.000) |    16.51 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            2 |     3820 | 2024-02-08 | VP.Prodigy           | W   | 0.618      | 0.371        | 0.029 (0.007)    | 0.762 (0.175)    | false (0.000) |    16.50 | AMANEK, bibu, Graviti, Kursy, Razzmo    |
|            1 |     3891 | 2024-02-05 | Lajtbitexe           | L   | 0.598      | -            | -                | -                | -             |    -9.62 | AMANEK, bibu, Graviti, Kursy, Razzmo    |

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
