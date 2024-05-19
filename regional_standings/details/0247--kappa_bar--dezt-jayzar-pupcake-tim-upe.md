### Roster Details<br />
Team Name: Kappa Bar<br />
Roster: dezt, jayzaR, pupcake, TIM, upE<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [247](../standings_global.md)<br />
Regional Rank: [158]( ../standings_europe.md)<br />
Final Rank Value:  669.0<br />
<br />
Final Rank Value (669.0) = Starting Rank Value (679.6) + Head To Head Adjustments (-10.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.269[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.6
- 400 + ( ( 0.141 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 679.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           41 |     2919 | 2024-03-01 | BAKS Esports             | W   | 0.764      | 0.371        | 0.003 (0.001)    | 0.084 (0.024)    | 0 (0.000) |    11.13 | dezt, jayzaR, pupcake, TIM, upE             |
|           40 |     3071 | 2024-02-26 | ALTERNATE aTTaX Evo      | W   | 0.739      | 0.289        | 0.005 (0.001)    | 0.198 (0.042)    | 0 (0.000) |    13.86 | dezt, jayzaR, pupcake, TIM, upE             |
|           39 |     3244 | 2024-02-22 | BLESSED (Ukrainian team) | L   | 0.712      | -            | -                | -                | -         |    -7.09 | dezt, jayzaR, pupcake, TIM, upE             |
|           38 |     3349 | 2024-02-20 | CYBERSHOKE Esports       | L   | 0.698      | -            | -                | -                | -         |    -8.94 | dezt, jayzaR, pupcake, TIM, upE             |
|           37 |     3397 | 2024-02-19 | Ex-Hot Headed Gaming     | L   | 0.692      | -            | -                | -                | -         |   -15.65 | dezt, jayzaR, pupcake, TIM, upE             |
|           36 |     3670 | 2024-02-13 | RUBY                     | L   | 0.652      | -            | -                | -                | -         |    -4.11 | dezt, jayzaR, pupcake, TIM, upE             |
|           35 |     3793 | 2024-02-09 | GamerLegion Academy      | W   | 0.625      | 0.371        | 0.043 (0.010)    | 0.567 (0.132)    | 0 (0.000) |    13.75 | dezt, jayzaR, pupcake, TIM, upE             |
|           34 |     3897 | 2024-02-05 | Nemiga Gaming            | L   | 0.598      | -            | -                | -                | -         |    -0.52 | dezt, jayzaR, pupcake, TIM, upE             |
|           33 |     3975 | 2024-02-03 | Sashi Esport             | L   | 0.585      | -            | -                | -                | -         |    -1.96 | dezt, jayzaR, pupcake, TIM, upE             |
|           32 |     4070 | 2024-02-01 | Gaimin Gladiators        | L   | 0.572      | -            | -                | -                | -         |    -0.33 | dezt, jayzaR, pupcake, TIM, upE             |
|           31 |     4100 | 2024-01-31 | Passion UA               | L   | 0.566      | -            | -                | -                | -         |    -2.68 | dezt, jayzaR, pupcake, TIM, upE             |
|           30 |     4138 | 2024-01-30 | LODIS                    | W   | 0.559      | 0.371        | 0.002 (0.000)    | 0.139 (0.029)    | 0 (0.000) |     8.41 | dezt, jayzaR, pupcake, TIM, upE             |
|           29 |     4377 | 2024-01-24 | EsmagaB                  | L   | 0.519      | -            | -                | -                | -         |    -3.77 | dezt, jayzaR, pupcake, TIM, upE             |
|           28 |     4940 | 2024-01-12 | Insilio                  | L   | 0.439      | -            | -                | -                | -         |    -2.71 | dezt, jayzaR, pupcake, TIM, upE             |
|           27 |     5046 | 2024-01-10 | XI Esport                | L   | 0.426      | -            | -                | -                | -         |    -6.36 | dezt, jayzaR, pupcake, TIM, upE             |
|           26 |     5216 | 2024-01-03 | Begrip Gaming            | L   | 0.378      | -            | -                | -                | -         |    -6.57 | dezt, jayzaR, pupcake, TIM, upE             |
|           25 |     5619 | 2023-12-14 | Astralis Talent          | L   | 0.243      | -            | -                | -                | -         |    -1.33 | ANSG1, JBOEN, kiR, kroK, tOPZ               |
|           24 |     5641 | 2023-12-13 | Lilmix                   | W   | 0.239      | 0.143        | -                | 0.098 (0.003)    | 0 (0.000) |     3.98 | dezt, jayzaR, pupcake, TIM, upE             |
|           23 |     5647 | 2023-12-13 | Homegrown                | W   | 0.238      | -            | -                | -                | 0 (0.000) |     1.30 | Gibsand, kurtaliz, meinz, wiking, z1egers   |
|           22 |     5702 | 2023-12-11 | Sashi Esport             | W   | 0.224      | 0.303        | 0.013 (0.001)    | 0.057 (0.004)    | 0 (0.000) |     4.05 | dezt, jayzaR, pupcake, TIM, upE             |
|           21 |     5977 | 2023-12-05 | Curlews                  | W   | 0.186      | -            | -                | -                | 0 (0.000) |     1.04 | jayzaR, jocab, pupcake, TIM, upE            |
|           20 |     5999 | 2023-12-05 | Sashi Esport             | L   | 0.184      | -            | -                | -                | -         |    -2.47 | jayzaR, pupcake, TIM, tvs, upE              |
|           19 |     6156 | 2023-12-01 | Alliance                 | L   | 0.159      | -            | -                | -                | -         |    -1.17 | jayzaR, jocab, pupcake, TIM, upE            |
|           18 |     6263 | 2023-11-29 | GODSENT                  | L   | 0.145      | -            | -                | -                | -         |    -1.54 | bobeksde, eraa, Golden, Plopski, Ro1f       |
|           17 |     6304 | 2023-11-28 | ARCRED                   | L   | 0.139      | -            | -                | -                | -         |    -1.30 | 1NVISIBLEE, DSSj, hurtslxrd, Ryujin, shg    |
|           16 |     6321 | 2023-11-28 | Turów Zgorzelec Esport   | W   | 0.138      | 0.371        | 0.019 (0.001)    | 0.640 (0.033)    | 0 (0.000) |     3.04 | b1elany, darko, gRuChA, kadziu, Markoś      |
|           15 |     6370 | 2023-11-27 | Ex-sYnck                 | L   | 0.132      | -            | -                | -                | -         |    -2.74 | eku, fejtZ, Jyo, Wahtzz, xezr               |
|           14 |     6378 | 2023-11-27 | Illuminar Gaming         | L   | 0.130      | -            | -                | -                | -         |    -1.61 | jayzaR, jocab, pupcake, TIM, upE            |
|           13 |     6395 | 2023-11-26 | AGO esports              | W   | 0.125      | 0.303        | 0.004 (0.000)    | -                | 0 (0.000) |     1.83 | delle, Dementor, DEPRESHN, Svedjehed, tAk   |
|           12 |     6444 | 2023-11-25 | NOM Esports              | L   | 0.117      | -            | -                | -                | -         |    -1.79 | AMSALEM, BluePho3nix, dan1, ultimate, Zax1e |
|           11 |     6505 | 2023-11-23 | BLESSED (Ukrainian team) | W   | 0.106      | 0.371        | 0.018 (0.001)    | 0.781 (0.031)    | -         |     2.35 | bondik, Edward, MUV, Smash, t3ns1on         |
|           10 |     6518 | 2023-11-23 | V1dar Gaming             | L   | 0.105      | -            | -                | -                | -         |    -2.09 | 1mpala, 4X1s, Alv, lom1k, torox             |
|            9 |     6570 | 2023-11-22 | Lazer Cats               | W   | 0.098      | -            | -                | -                | -         |     1.31 | 7oX1C, Burmylov, m1she4ka, neiter, t0kk     |
|            8 |     6640 | 2023-11-20 | DMS                      | L   | 0.085      | -            | -                | -                | -         |    -1.45 | AW, H1te, kAlash, sFade8, sm3t              |
|            7 |     6677 | 2023-11-19 | Lemondogs                | L   | 0.077      | -            | -                | -                | -         |    -1.85 | jayzaR, jocab, pupcake, TIM, upE            |
|            6 |     6809 | 2023-11-16 | Gaimin Gladiators        | W   | 0.059      | 0.371        | 0.194 (0.004)    | 0.989 (0.022)    | -         |     1.83 | kraghen, Nodios, Patti, Queenix, salazar    |
|            5 |     6851 | 2023-11-16 | Sprout Academy           | W   | 0.056      | -            | -                | -                | -         |     0.45 | jayzaR, jocab, pupcake, TIM, upE            |
|            4 |     6883 | 2023-11-15 | TSM                      | W   | 0.052      | 0.371        | 0.008 (0.000)    | 0.043 (0.001)    | -         |     0.87 | jayzaR, jocab, pupcake, TIM, upE            |
|            3 |     6970 | 2023-11-13 | Pungrottorna             | W   | 0.038      | -            | -                | -                | -         |     0.31 | jayzaR, jocab, pupcake, TIM, upE            |
|            2 |     7135 | 2023-11-09 | Lilmix                   | L   | 0.012      | -            | -                | -                | -         |    -0.17 | dex, L00m1, melonhead, quix, SeBreeZe       |
|            1 |     7186 | 2023-11-08 | Kappa Bar                | W   | 0.005      | -            | -                | -                | -         |     0.06 | AlekS, b0bbzki, HugoXD, nomiss, zen         |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($247.37)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
