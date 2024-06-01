### Roster Details<br />
Team Name: Team Spirit Academy<br />
Roster: alkarenn, alpha, kyousuke, Mokuj1n, syph0<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [145](../standings_global.md)<br />
Regional Rank: [101]( ../standings_europe.md)<br />
Final Rank Value:  785.4<br />
<br />
Final Rank Value (785.4) = Starting Rank Value (669.4) + Head To Head Adjustments (115.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.337[<sup>2</sup>](#table1)
- Opponent Network: 0.192[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 669.4
- 400 + ( ( 0.132 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 669.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |      394 | 2024-05-23 | esmagaB            | W   | 1.000      | 0.372        | 0.008 (0.003)    | 0.460 (0.171)    | 0 (0.000) |    18.17 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|           10 |      487 | 2024-05-22 | Rustec             | L   | 1.000      | -            | -                | -                | -         |   -12.36 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            9 |      505 | 2024-05-22 | 1win               | L   | 1.000      | -            | -                | -                | -         |    -6.31 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            8 |      598 | 2024-05-21 | ENTERPRISE esports | W   | 1.000      | 0.372        | 0.010 (0.004)    | 0.809 (0.301)    | 0 (0.000) |    20.82 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            7 |      692 | 2024-05-20 | ThunderFlash       | L   | 1.000      | -            | -                | -                | -         |   -10.04 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            6 |     1074 | 2024-05-16 | Zero Tenacity      | W   | 1.000      | 0.372        | 0.147 (0.055)    | 1.000 (0.372)    | 0 (0.000) |    25.28 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            5 |     1162 | 2024-05-15 | CYBERSHOKE Esports | W   | 1.000      | 0.372        | 0.000 (0.000)    | 0.468 (0.174)    | 0 (0.000) |    14.53 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            4 |     1269 | 2024-05-14 | Permitta Esports   | W   | 1.000      | 0.372        | 0.029 (0.011)    | 1.000 (0.372)    | 0 (0.000) |    20.29 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            3 |     1731 | 2024-05-06 | Nemiga Gaming      | L   | 1.000      | -            | -                | -                | -         |    -1.84 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            2 |     1916 | 2024-05-02 | HOTU               | W   | 1.000      | 0.372        | 0.004 (0.002)    | 0.524 (0.195)    | 0 (0.000) |    21.86 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |
|            1 |     2375 | 2024-04-24 | Dynamo Eclot       | W   | 0.963      | 0.372        | 0.097 (0.035)    | 0.936 (0.336)    | 0 (0.000) |    25.55 | alkarenn, alpha, kyousuke, Mokuj1n, syph0 |

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
