### Roster Details<br />
Team Name: CUBE BY SND<br />
Roster: alkarenn, dosikzz, maison, OxygeN, rinn<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [231](../standings_global.md)<br />
Regional Rank: [151]( ../standings_europe.md)<br />
Final Rank Value:  681.3<br />
<br />
Final Rank Value (681.3) = Starting Rank Value (683.7) + Head To Head Adjustments (-2.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.347[<sup>1</sup>](#table2)
- Bounty Collected: 0.202[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.018[<sup>2</sup>](#table1)

The average of these factors is 0.143<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 683.7
- 400 + ( ( 0.143 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 683.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      414 | 2024-04-26 | Lewandownskie               | L   | 1.000      | -            | -                | -                | -         |   -17.74 | alkarenn, dosikzz, maison, OxygeN, rinn    |
|            9 |      423 | 2024-04-26 | ALLINNERS                   | L   | 1.000      | -            | -                | -                | -         |   -22.69 | alkarenn, dosikzz, maison, OxygeN, rinn    |
|            8 |      428 | 2024-04-26 | XGOD                        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.056 (0.008)    | 0 (0.000) |     6.77 | alkarenn, dosikzz, maison, OxygeN, rinn    |
|            7 |     3303 | 2024-02-21 | EVO-Cyber                   | W   | 0.705      | 0.143        | 0.004 (0.000)    | 0.048 (0.005)    | 0 (0.000) |     9.25 | Adaikz, dosikzz, mag1k3Y, OxygeN, rinn     |
|            6 |     3353 | 2024-02-20 | Troublemakers (Kyrgyz team) | W   | 0.698      | 0.143        | 0.001 (0.000)    | 0.116 (0.012)    | 0 (0.000) |    10.53 | Adaikz, dosikzz, mag1k3Y, OxygeN, rinn     |
|            5 |     3442 | 2024-02-18 | Lewandownskie               | W   | 0.685      | 0.143        | 0.004 (0.000)    | 0.181 (0.018)    | 0 (0.000) |    10.33 | Adaikz, dosikzz, mag1k3Y, OxygeN, rinn     |
|            4 |     3502 | 2024-02-17 | STEALTH (Kazakh team)       | W   | 0.677      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.62 | d1aszz, dART, Gilzerra, Goodlikee, kaelz7z |
|            3 |     6071 | 2023-12-02 | STEALTH (Kazakh team)       | L   | 0.169      | -            | -                | -                | -         |    -2.63 | alkarenn, dosikzz, OxygeN, rinn, syph0     |
|            2 |     6131 | 2023-12-02 | Temp (Kazakh team)          | W   | 0.163      | 0.342        | 0.004 (0.000)    | 0.001 (0.000)    | 1 (0.163) |     2.02 | alkarenn, dosikzz, OxygeN, rinn, syph0     |
|            1 |     6147 | 2023-12-01 | Depo                        | L   | 0.162      | -            | -                | -                | -         |    -1.85 | alkarenn, dosikzz, OxygeN, rinn, syph0     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,090.82)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-26 |      1.000 | $568.82        | $568.82         |
| 2024-02-21 |      0.705 | $1,677.29      | $1,182.18       |
| 2023-12-03 |      0.170 | $2,000.00      | $339.81         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
