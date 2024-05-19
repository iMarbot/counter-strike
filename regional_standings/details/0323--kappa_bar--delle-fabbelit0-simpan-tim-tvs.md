### Roster Details<br />
Team Name: Kappa Bar<br />
Roster: delle, Fabbelit0, simpan, TIM, tvs<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [323](../standings_global.md)<br />
Regional Rank: [196]( ../standings_europe.md)<br />
Final Rank Value:  574.5<br />
<br />
Final Rank Value (574.5) = Starting Rank Value (513.7) + Head To Head Adjustments (60.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.207[<sup>2</sup>](#table1)
- Opponent Network: 0.022[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.057<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 513.7
- 400 + ( ( 0.057 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 513.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |       14 | 2024-05-05 | LODIS       | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.139 (0.052)    | 0 (0.000) |    16.09 | delle, Fabbelit0, simpan, TIM, tvs   |
|            9 |      191 | 2024-05-01 | ADEPTS      | W   | 1.000      | 0.371        | 0.002 (0.001)    | 0.116 (0.043)    | 0 (0.000) |    18.20 | delle, Fabbelit0, simpan, TIM, tvs   |
|            8 |      409 | 2024-04-26 | TopTab Club | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.065 (0.024)    | 0 (0.000) |    15.14 | delle, Fabbelit0, simpan, TIM, tvs   |
|            7 |      421 | 2024-04-26 | Team PeeP   | L   | 1.000      | -            | -                | -                | -         |   -20.04 | delle, Fabbelit0, simpan, TIM, tvs   |
|            6 |     1032 | 2024-04-15 | EXO Clan    | L   | 1.000      | -            | -                | -                | -         |    -3.31 | delle, Fabbelit0, simpan, TIM, tvs   |
|            5 |     1323 | 2024-04-08 | VP.Prodigy  | L   | 1.000      | -            | -                | -                | -         |    -4.89 | delle, Evarizta, Fabbelit0, TIM, tvs |
|            4 |     1739 | 2024-03-27 | Kappa Borr  | W   | 0.939      | 0.143        | 0.000 (0.000)    | 0.119 (0.016)    | 0 (0.000) |    15.62 | delle, jocab, TIM, tvs, upE          |
|            3 |     1932 | 2024-03-22 | Lilmix      | W   | 0.906      | 0.143        | 0.000 (0.000)    | 0.604 (0.078)    | 0 (0.000) |    18.03 | delle, jocab, TIM, tvs, upE          |
|            2 |     2320 | 2024-03-13 | Full Kareta | W   | 0.845      | 0.143        | 0.000 (0.000)    | 0.035 (0.004)    | 0 (0.000) |     9.06 | delle, jocab, TIM, tvs, upE          |
|            1 |     2509 | 2024-03-09 | Alliance    | L   | 0.817      | -            | -                | -                | -         |    -3.03 | delle, dezt, TIM, tvs, upE           |

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
