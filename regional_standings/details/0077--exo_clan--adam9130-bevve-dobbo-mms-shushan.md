### Roster Details<br />
Team Name: EXO Clan<br />
Roster: Adam9130, bevve, dobbo, MMS, shushan<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [77](../standings_global.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
Final Rank Value:  901.5<br />
<br />
Final Rank Value (901.5) = Starting Rank Value (872.3) + Head To Head Adjustments (29.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.366[<sup>1</sup>](#table2)
- Bounty Collected: 0.390[<sup>2</sup>](#table1)
- Opponent Network: 0.089[<sup>2</sup>](#table1)
- LAN Wins: 0.106[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 872.3
- 400 + ( ( 0.238 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 872.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |      152 | 2024-05-02 | Zero Tenacity        | L   | 1.000      | -            | -                | -                | -         |   -11.08 | Adam9130, bevve, dobbo, MMS, shushan       |
|           22 |      232 | 2024-04-30 | Halal5               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.63 | Adam9130, bevve, dobbo, MMS, shushan       |
|           21 |      252 | 2024-04-30 | Preasy Esport        | L   | 1.000      | -            | -                | -                | -         |   -23.97 | Adam9130, bevve, dobbo, MMS, shushan       |
|           20 |      392 | 2024-04-27 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -17.05 | Adam9130, bevve, dobbo, MMS, shushan       |
|           19 |      450 | 2024-04-26 | GamerLegion Academy  | L   | 1.000      | -            | -                | -                | -         |   -19.02 | Adam9130, bevve, dobbo, MMS, shushan       |
|           18 |      479 | 2024-04-25 | VP.Prodigy           | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.762 (0.109)    | 0 (0.000) |     9.09 | Adam9130, bevve, dobbo, MMS, shushan       |
|           17 |      545 | 2024-04-24 | 9INE Academy         | W   | 1.000      | 0.143        | 0.005 (0.001)    | -                | 0 (0.000) |     4.66 | Adam9130, bevve, dobbo, MMS, shushan       |
|           16 |      562 | 2024-04-23 | Nemiga Gaming        | W   | 1.000      | 0.371        | 0.680 (0.253)    | 0.910 (0.338)    | 0 (0.000) |    26.30 | Adam9130, bevve, dobbo, MMS, shushan       |
|           15 |     1032 | 2024-04-15 | Kappa Bar            | W   | 1.000      | 0.371        | -                | 0.200 (0.074)    | 0 (0.000) |     3.31 | Adam9130, bevve, dobbo, MMS, shushan       |
|           14 |     1657 | 2024-03-29 | K10                  | W   | 0.952      | 0.143        | 0.015 (0.002)    | 0.418 (0.057)    | 1 (0.952) |    10.69 | Adam9130, bevve, dobbo, eraa, Thomas       |
|           13 |     2050 | 2024-03-19 | Verdant              | W   | 0.886      | 0.143        | 0.027 (0.003)    | 0.662 (0.084)    | 0 (0.000) |    13.38 | Adam9130, bevve, dobbo, eraa, RuStY        |
|           12 |     2257 | 2024-03-14 | Raptors Esports Club | W   | 0.852      | 0.143        | 0.017 (0.002)    | 0.384 (0.047)    | 0 (0.000) |    11.12 | BehinDx, Karrar, moz, PrimeOPI, wfn        |
|           11 |     2364 | 2024-03-12 | The Last Resort      | W   | 0.839      | 0.143        | -                | 0.240 (0.029)    | 0 (0.000) |     6.32 | Adam9130, bevve, dobbo, eraa, RuStY        |
|           10 |     3847 | 2024-02-07 | Sashi Esport         | L   | 0.610      | -            | -                | -                | -         |   -12.11 | Adam9130, AwaykeN, bevve, dobbo, Duplicate |
|            9 |     4041 | 2024-02-02 | Sashi Academy        | W   | 0.578      | -            | -                | -                | 0 (0.000) |     4.26 | Adam9130, AwaykeN, bevve, dobbo, Duplicate |
|            8 |     4075 | 2024-02-01 | Preasy Esport        | W   | 0.571      | 0.289        | 0.007 (0.001)    | 0.525 (0.087)    | -         |     6.15 | Adam9130, AwaykeN, bevve, dobbo, Duplicate |
|            7 |     4089 | 2024-02-01 | AVEZ                 | W   | 0.570      | 0.289        | 0.007 (0.001)    | 0.160 (0.026)    | -         |     4.49 | Adam9130, AwaykeN, bevve, dobbo, Duplicate |
|            6 |     4146 | 2024-01-30 | Insilio              | L   | 0.558      | -            | -                | -                | -         |    -7.16 | faydett, FpSSS, Pipw, Polt, sugaR          |
|            5 |     4156 | 2024-01-29 | Into The Breach      | W   | 0.553      | 0.143        | 0.022 (0.002)    | -                | -         |     7.80 | Bymas, CRUC1AL, misutaaa, rallen, Thomas   |
|            4 |     4171 | 2024-01-29 | KOI                  | W   | 0.553      | 0.143        | 0.066 (0.005)    | 0.537 (0.042)    | -         |    13.26 | Adam9130, AwaykeN, bevve, dobbo, Duplicate |
|            3 |     4308 | 2024-01-26 | Raptors Esports Club | W   | 0.532      | -            | -                | -                | -         |     2.36 | Finui, Igorek, OxidE, PALM1, Rutk0         |
|            2 |     4349 | 2024-01-25 | Raptors Esports Club | W   | 0.526      | -            | -                | -                | -         |     2.38 | Finui, Igorek, OxidE, PALM1, Rutk0         |
|            1 |     4931 | 2024-01-12 | ARCRED               | L   | 0.439      | -            | -                | -                | -         |    -7.62 | Adam9130, AwaykeN, bevve, dobbo, Duplicate |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,958.33)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-03-29 |      0.952 | $1,892.86      | $1,802.87       |
| 2024-02-02 |      0.578 | $2,000.00      | $1,155.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
