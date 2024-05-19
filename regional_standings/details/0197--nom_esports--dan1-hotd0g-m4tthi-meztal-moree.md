### Roster Details<br />
Team Name: NOM Esports<br />
Roster: dan1, hotd0g, m4tthi, meztal, MOREE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [197](../standings_global.md)<br />
Regional Rank: [130]( ../standings_europe.md)<br />
Final Rank Value:  726.1<br />
<br />
Final Rank Value (726.1) = Starting Rank Value (647.7) + Head To Head Adjustments (78.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.336[<sup>2</sup>](#table1)
- Opponent Network: 0.163[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 647.7
- 400 + ( ( 0.125 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 647.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |       19 | 2024-05-05 | Johnny Speeds               | L   | 1.000      | -            | -                | -                | -             |    -6.75 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           31 |       53 | 2024-05-04 | 1win                        | L   | 1.000      | -            | -                | -                | -             |   -11.15 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           30 |      121 | 2024-05-03 | UNiTY esports (Slovak team) | W   | 1.000      | 0.333        | 0.055 (0.018)    | 0.727 (0.242)    | false (0.000) |    22.43 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           29 |      259 | 2024-04-30 | GamerLegion Academy         | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.567 (0.189)    | false (0.000) |    23.81 | dan1, eku, hotd0g, meztal, MOREE      |
|           28 |      444 | 2024-04-26 | Preasy Esport               | W   | 1.000      | 0.333        | 0.007 (0.002)    | 0.525 (0.175)    | false (0.000) |    15.66 | dan1, eku, hotd0g, meztal, MOREE      |
|           27 |      829 | 2024-04-19 | JANO Esports                | L   | 1.000      | -            | -                | -                | -             |   -13.45 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           26 |      886 | 2024-04-18 | RUBY                        | L   | 1.000      | -            | -                | -                | -             |    -6.06 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           25 |      954 | 2024-04-17 | Team Sampi                  | W   | 1.000      | 0.143        | 0.108 (0.015)    | 0.709 (0.101)    | false (0.000) |    27.59 | dan1, hotd0g, m4tthi, meztal, MOREE   |
|           24 |     1259 | 2024-04-10 | Viperio                     | L   | 1.000      | -            | -                | -                | -             |   -12.93 | dan1, jce, m4tthi, meztal, MOREE      |
|           23 |     1379 | 2024-04-07 | Lilmix                      | L   | 1.000      | -            | -                | -                | -             |   -16.50 | dan1, jce, meztal, MOREE, shushan     |
|           22 |     1705 | 2024-03-28 | ROSOMAHA                    | L   | 0.943      | -            | -                | -                | -             |   -20.04 | aidKiT, dan1, meztal, MOREE, shushan  |
|           21 |     1923 | 2024-03-23 | Illuminar Gaming            | L   | 0.909      | -            | -                | -                | -             |    -9.79 | aidKiT, dan1, meztal, MOREE, shushan  |
|           20 |     2440 | 2024-03-11 | MOUZ NXT                    | L   | 0.829      | -            | -                | -                | -             |    -3.51 | dan1, Libido, meztal, MOREE, ultimate |
|           19 |     2516 | 2024-03-09 | Astralis Talent             | W   | 0.817      | 0.303        | 0.030 (0.007)    | 0.613 (0.152)    | false (0.000) |    18.58 | dan1, Libido, meztal, MOREE, ultimate |
|           18 |     2546 | 2024-03-08 | Natus Vincere Junior        | W   | 0.809      | 0.303        | 0.025 (0.006)    | 0.492 (0.121)    | false (0.000) |    17.50 | dan1, Libido, meztal, MOREE, ultimate |
|           17 |     2587 | 2024-03-07 | MOUZ NXT                    | L   | 0.803      | -            | -                | -                | -             |    -2.63 | dan1, Libido, meztal, MOREE, ultimate |
|           16 |     2769 | 2024-03-04 | ENCE Academy                | W   | 0.784      | 0.303        | 0.028 (0.007)    | -                | false (0.000) |    18.03 | dan1, Libido, meztal, MOREE, ultimate |
|           15 |     2911 | 2024-03-01 | Endpoint                    | L   | 0.766      | -            | -                | -                | -             |    -6.80 | dan1, Libido, meztal, MOREE, ultimate |
|           14 |     2933 | 2024-02-29 | FORZE Youngsters            | W   | 0.759      | -            | -                | -                | false (0.000) |    12.63 | dan1, Libido, meztal, MOREE, ultimate |
|           13 |     3006 | 2024-02-28 | Passion UA                  | W   | 0.749      | 0.303        | 0.114 (0.026)    | 0.980 (0.222)    | false (0.000) |    18.89 | dan1, Libido, meztal, MOREE, ultimate |
|           12 |     3173 | 2024-02-24 | Verdant                     | W   | 0.724      | 0.303        | 0.027 (0.006)    | 0.662 (0.145)    | false (0.000) |    19.55 | dan1, Libido, meztal, MOREE, ultimate |
|           11 |     3236 | 2024-02-22 | INGLORIOUS                  | W   | 0.712      | 0.371        | -                | 0.358 (0.095)    | -             |    16.36 | dan1, Libido, meztal, MOREE, ultimate |
|           10 |     3246 | 2024-02-22 | Zero Tenacity               | L   | 0.712      | -            | -                | -                | -             |    -3.54 | dan1, Libido, meztal, MOREE, ultimate |
|            9 |     3255 | 2024-02-22 | CYBERSHOKE Esports          | L   | 0.711      | -            | -                | -                | -             |    -8.48 | dan1, Libido, meztal, MOREE, ultimate |
|            8 |     3362 | 2024-02-20 | Nemiga Gaming               | L   | 0.697      | -            | -                | -                | -             |    -0.49 | dan1, Libido, meztal, MOREE, ultimate |
|            7 |     3578 | 2024-02-15 | VP.Prodigy                  | L   | 0.665      | -            | -                | -                | -             |    -5.02 | dan1, Libido, meztal, MOREE, ultimate |
|            6 |     3714 | 2024-02-12 | BLESSED (Ukrainian team)    | W   | 0.646      | 0.371        | 0.018 (0.004)    | 0.781 (0.187)    | -             |    14.46 | dan1, Libido, meztal, MOREE, ultimate |
|            5 |     3728 | 2024-02-12 | HOTU                        | L   | 0.645      | -            | -                | -                | -             |    -5.87 | dan1, Libido, meztal, MOREE, ultimate |
|            4 |     3747 | 2024-02-11 | INGLORIOUS                  | L   | 0.639      | -            | -                | -                | -             |    -5.59 | dan1, Libido, meztal, MOREE, ultimate |
|            3 |     3753 | 2024-02-11 | Viperio                     | W   | 0.638      | -            | -                | -                | -             |    11.19 | dan1, Libido, meztal, MOREE, ultimate |
|            2 |     3773 | 2024-02-10 | Lilmix                      | L   | 0.631      | -            | -                | -                | -             |   -10.67 | dan1, Libido, meztal, MOREE, ultimate |
|            1 |     5150 | 2024-01-08 | 15 Average Gaming           | L   | 0.412      | -            | -                | -                | -             |    -9.02 | dan1, meztal, MOREE, ultimate, Zax1e  |

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
