### Roster Details<br />
Team Name: NOM Esports<br />
Roster: AMSALEM, BluePho3nix, dan1, ultimate, Zax1e<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [300](../standings_global.md)<br />
Regional Rank: [48]( ../standings_asia.md)<br />
Final Rank Value:  645.0<br />
<br />
Final Rank Value (645.0) = Starting Rank Value (639.1) + Head To Head Adjustments (5.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.224[<sup>1</sup>](#table2)
- Bounty Collected: 0.240[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.118<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.1
- 400 + ( ( 0.118 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 639.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     8633 | 2023-12-21 | Natus Vincere Junior | L   | 0.128      | -            | -                | -                | -         |    -1.21 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           17 |     8647 | 2023-12-20 | Sashi Esport         | W   | 0.122      | 0.333        | 0.154 (0.006)    | 1.000 (0.041)    | 0 (0.000) |     3.52 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           16 |     8680 | 2023-12-18 | The Witchers         | W   | 0.108      | 0.333        | 0.009 (0.000)    | 0.060 (0.002)    | 0 (0.000) |     2.02 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           15 |     8895 | 2023-12-16 | detoks               | L   | 0.096      | -            | -                | -                | -         |    -2.08 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           14 |     8914 | 2023-12-16 | Natus Vincere Junior | L   | 0.095      | -            | -                | -                | -         |    -0.89 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           13 |     9011 | 2023-12-15 | AGO esports          | W   | 0.090      | 0.333        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.58 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           12 |     9054 | 2023-12-14 | WOPA Esport          | W   | 0.083      | 0.303        | 0.003 (0.000)    | 0.594 (0.015)    | 0 (0.000) |     1.91 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           11 |     9078 | 2023-12-13 | Rhyno Esports        | L   | 0.078      | -            | -                | -                | -         |    -0.23 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           10 |     9113 | 2023-12-13 | Passion UA           | L   | 0.076      | -            | -                | -                | -         |    -0.25 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            9 |     9117 | 2023-12-13 | ex-Anonymo Esports   | L   | 0.075      | -            | -                | -                | -         |    -1.00 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            8 |     9194 | 2023-12-11 | LEON Esports         | W   | 0.064      | 0.333        | 0.001 (0.000)    | 0.564 (0.012)    | 0 (0.000) |     1.32 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            7 |     9229 | 2023-12-10 | FALKE ESPORTS        | W   | 0.057      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.69 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            6 |     9295 | 2023-12-09 | Lazer Cats           | W   | 0.050      | 0.333        | 0.000 (0.000)    | 0.013 (0.000)    | 0 (0.000) |     0.47 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            5 |     9317 | 2023-12-09 | Sashi Esport         | W   | 0.048      | 0.303        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.63 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            4 |     9415 | 2023-12-07 | Team LRP Poland      | W   | 0.038      | 0.333        | 0.001 (0.000)    | 0.056 (0.001)    | 0 (0.000) |     0.74 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            3 |     9557 | 2023-12-05 | Donstu Esports       | L   | 0.025      | -            | -                | -                | -         |    -0.51 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            2 |     9604 | 2023-12-05 | Lilmix               | W   | 0.022      | 0.303        | 0.000 (0.000)    | 0.044 (0.000)    | 0 (0.000) |     0.26 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|            1 |     9750 | 2023-12-02 | Team Spirit Academy  | L   | 0.004      | -            | -                | -                | -         |    -0.05 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($102.21)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2023-12-23 |      0.142 | $500.00        | $70.83          |
| 2023-12-17 |      0.105 | $300.00        | $31.38          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
