### Roster Details<br />
Team Name: Sprout<br />
Roster: Anlelele, Buzz, cej0t, raalz, sL1m3<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [268](../standings_global.md)<br />
Regional Rank: [171]( ../standings_europe.md)<br />
Final Rank Value:  663.7<br />
<br />
Final Rank Value (663.7) = Starting Rank Value (568.2) + Head To Head Adjustments (95.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.298[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.083<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 568.2
- 400 + ( ( 0.083 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 568.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |     4826 | 2024-03-07 | Alliance            | L   | 0.642      | -            | -                | -                | -         |    -5.55 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           29 |     5384 | 2024-02-27 | Permitta Esports    | L   | 0.582      | -            | -                | -                | -         |    -2.73 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           28 |     5405 | 2024-02-26 | B8                  | L   | 0.578      | -            | -                | -                | -         |    -1.34 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           27 |     6302 | 2024-02-09 | Fnatic              | W   | 0.463      | 0.143        | 0.147 (0.010)    | 0.480 (0.032)    | 0 (0.000) |    13.61 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           26 |     6307 | 2024-02-09 | 3DMAX               | W   | 0.463      | 0.143        | 0.106 (0.007)    | 0.301 (0.020)    | 0 (0.000) |    12.27 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           25 |     6361 | 2024-02-07 | Metizport           | L   | 0.450      | -            | -                | -                | -         |    -2.04 | Anlelele, Buzz, cej0t, raalz, sL1m3   |
|           24 |     6752 | 2024-01-30 | Nemiga Gaming       | L   | 0.398      | -            | -                | -                | -         |    -0.41 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           23 |     6757 | 2024-01-30 | Dynamo Eclot        | W   | 0.397      | 0.143        | 0.097 (0.005)    | 0.936 (0.053)    | 0 (0.000) |    11.56 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           22 |     6772 | 2024-01-30 | ALTERNATE aTTaX     | L   | 0.396      | -            | -                | -                | -         |    -4.69 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           21 |     6779 | 2024-01-29 | Team Spirit Academy | W   | 0.392      | 0.143        | 0.004 (0.000)    | 0.229 (0.013)    | 0 (0.000) |     8.04 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           20 |     6795 | 2024-01-29 | ex-K10              | W   | 0.392      | 0.143        | 0.005 (0.000)    | 0.382 (0.021)    | 0 (0.000) |     9.42 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           19 |     6954 | 2024-01-27 | 9INE                | W   | 0.377      | -            | -                | -                | 0 (0.000) |     5.31 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           18 |     6963 | 2024-01-27 | Verdant             | W   | 0.377      | 0.143        | 0.014 (0.001)    | 1.000 (0.054)    | 0 (0.000) |    10.78 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           17 |     6969 | 2024-01-27 | BLEED Esports       | W   | 0.377      | 0.143        | 0.248 (0.013)    | 0.677 (0.036)    | 0 (0.000) |    11.57 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           16 |     7063 | 2024-01-26 | ex-Preasy Esport    | W   | 0.368      | 0.371        | 0.052 (0.007)    | 0.381 (0.052)    | 0 (0.000) |    10.07 | Anlelele, cej0t, raalz, Sdaim, sL1m3  |
|           15 |     7493 | 2024-01-18 | ex-Guild Eagles     | L   | 0.316      | -            | -                | -                | -         |    -1.04 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           14 |     7509 | 2024-01-17 | 500                 | W   | 0.312      | 0.143        | 0.002 (0.000)    | 0.479 (0.021)    | 0 (0.000) |     7.46 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           13 |     7517 | 2024-01-17 | GUN5 Esports        | W   | 0.312      | -            | -                | -                | -         |     4.57 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           12 |     7531 | 2024-01-17 | ROSOMAHA            | W   | 0.311      | -            | -                | -                | -         |     5.35 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           11 |     7559 | 2024-01-17 | shovel              | W   | 0.311      | -            | -                | -                | -         |     2.73 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|           10 |     7842 | 2024-01-12 | LOADING             | L   | 0.278      | -            | -                | -                | -         |    -5.37 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            9 |     7860 | 2024-01-12 | Balkan Bears        | W   | 0.278      | -            | -                | -                | -         |     2.41 | Anlelele, cej0t, raalz, sL1m3, Zyphon |
|            8 |     8388 | 2023-12-20 | Pera Esports        | L   | 0.122      | -            | -                | -                | -         |    -0.48 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            7 |     8416 | 2023-12-18 | ARCRED              | W   | 0.109      | 0.333        | -                | 0.630 (0.023)    | -         |     2.62 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            6 |     8419 | 2023-12-18 | showmakerz          | W   | 0.109      | -            | -                | -                | -         |     1.59 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            5 |     9051 | 2023-12-09 | TSM                 | L   | 0.048      | -            | -                | -                | -         |    -0.61 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            4 |     9119 | 2023-12-08 | ALTERNATE aTTaX     | L   | 0.042      | -            | -                | -                | -         |    -0.40 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            3 |     9247 | 2023-12-06 | Endpoint            | W   | 0.028      | 0.371        | 0.012 (0.000)    | -                | -         |     0.80 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            2 |     9336 | 2023-12-04 | RED Canids          | L   | 0.017      | -            | -                | -                | -         |    -0.05 | Anlelele, cej0t, raalz, sL1m3, spooke |
|            1 |     9391 | 2023-12-03 | G2 Esports          | L   | 0.009      | -            | -                | -                | -         |     0.00 | Anlelele, cej0t, raalz, sL1m3, spooke |

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
