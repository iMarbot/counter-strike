### Roster Details<br />
Team Name: NOM Esports<br />
Roster: AMSALEM, BluePho3nix, dan1, ultimate, Zax1e<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [207](../standings_global.md)<br />
Regional Rank: [33]( ../standings_asia.md)<br />
Final Rank Value:  706.2<br />
<br />
Final Rank Value (706.2) = Starting Rank Value (687.6) + Head To Head Adjustments (18.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.282[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.145<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 687.6
- 400 + ( ( 0.145 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 687.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     5300 | 2023-12-21 | Natus Vincere Junior | L   | 0.289      | -            | -                | -                | -             |    -2.81 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           18 |     5308 | 2023-12-20 | Sashi Esport         | W   | 0.283      | 0.333        | 0.193 (0.018)    | 1.000 (0.094)    | false (0.000) |     7.94 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           17 |     5332 | 2023-12-18 | The Witchers         | W   | 0.269      | 0.333        | 0.035 (0.003)    | 0.158 (0.014)    | false (0.000) |     5.24 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           16 |     5508 | 2023-12-16 | Natus Vincere Junior | L   | 0.256      | -            | -                | -                | -             |    -2.36 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           15 |     5588 | 2023-12-15 | AGO esports          | W   | 0.251      | 0.333        | 0.004 (0.000)    | -                | false (0.000) |     3.44 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           14 |     5615 | 2023-12-14 | WOPA Esport          | W   | 0.244      | 0.303        | 0.009 (0.001)    | 0.485 (0.036)    | false (0.000) |     4.67 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           13 |     5634 | 2023-12-13 | Rhyno Esports        | L   | 0.239      | -            | -                | -                | -             |    -1.50 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           12 |     5652 | 2023-12-13 | Passion UA           | L   | 0.237      | -            | -                | -                | -             |    -1.08 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           11 |     5654 | 2023-12-13 | Ex-Anonymo Esports   | L   | 0.236      | -            | -                | -                | -             |    -2.82 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           10 |     5697 | 2023-12-11 | LEON Esports         | W   | 0.225      | 0.333        | 0.003 (0.000)    | 0.357 (0.027)    | false (0.000) |     3.57 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            9 |     5789 | 2023-12-09 | Sashi Esport         | W   | 0.209      | 0.303        | 0.013 (0.001)    | 0.057 (0.004)    | false (0.000) |     3.66 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            8 |     5868 | 2023-12-07 | FALKE ESPORTS        | W   | 0.199      | 0.333        | -                | 0.021 (0.001)    | false (0.000) |     1.66 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            7 |     5970 | 2023-12-05 | Team OWL             | L   | 0.186      | -            | -                | -                | -             |    -4.43 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            6 |     6106 | 2023-12-02 | Team Spirit Academy  | L   | 0.165      | -            | -                | -                | -             |    -1.81 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            5 |     6281 | 2023-11-29 | Sashi Esport         | L   | 0.143      | -            | -                | -                | -             |    -2.07 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            4 |     6383 | 2023-11-27 | Sashi Esport         | W   | 0.129      | 0.303        | 0.013 (0.001)    | 0.057 (0.002)    | false (0.000) |     2.21 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            3 |     6444 | 2023-11-25 | Kappa Bar            | W   | 0.117      | 0.303        | 0.002 (0.000)    | 0.149 (0.005)    | false (0.000) |     1.79 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            2 |     6530 | 2023-11-23 | Astralis Talent      | W   | 0.104      | 0.303        | 0.030 (0.001)    | 0.613 (0.019)    | false (0.000) |     2.71 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            1 |     6990 | 2023-11-13 | Illuminar Gaming     | W   | 0.036      | 0.303        | 0.010 (0.000)    | 0.243 (0.003)    | -             |     0.68 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($445.16)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.303 | $500.00        | $151.37         |
| 2023-12-17 |      0.266 | $300.00        | $79.69          |
| 2023-11-29 |      0.143 | $1,500.00      | $214.10         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
