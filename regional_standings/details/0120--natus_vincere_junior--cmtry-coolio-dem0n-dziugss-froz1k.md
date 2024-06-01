### Roster Details<br />
Team Name: Natus Vincere Junior<br />
Roster: cmtry, coolio, dem0n, dziugss, froz1k<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [120](../standings_global.md)<br />
Regional Rank: [83]( ../standings_europe.md)<br />
Final Rank Value:  832.5<br />
<br />
Final Rank Value (832.5) = Starting Rank Value (760.6) + Head To Head Adjustments (72.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.300[<sup>2</sup>](#table1)
- Opponent Network: 0.101[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.177<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 760.6
- 400 + ( ( 0.177 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 760.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           30 |       55 | 2024-05-29 | GameAgents            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.42 | cmtry, coolio, dem0n, dziugss, froz1k          |
|           29 |       85 | 2024-05-29 | Young Ninjas          | W   | 1.000      | 0.333        | 0.043 (0.014)    | 0.372 (0.124)    | 0 (0.000) |    19.05 | cmtry, dem0n, dziugss, froz1k, Krabeni         |
|           28 |      345 | 2024-05-24 | The Agency Clan       | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.80 | cmtry, dem0n, dziugss, froz1k, Krabeni         |
|           27 |      361 | 2024-05-24 | ENCE Academy          | W   | 1.000      | 0.333        | 0.012 (0.004)    | 0.337 (0.112)    | 0 (0.000) |    12.77 | cmtry, dem0n, dziugss, froz1k, Krabeni         |
|           26 |      502 | 2024-05-22 | Permitta Esports      | W   | 1.000      | 0.333        | 0.029 (0.010)    | 1.000 (0.333)    | 0 (0.000) |    16.37 | cmtry, dem0n, dziugss, froz1k, Krabeni         |
|           25 |      555 | 2024-05-21 | MASONIC               | W   | 1.000      | 0.354        | 0.018 (0.006)    | 0.182 (0.064)    | 0 (0.000) |    16.75 | cmtry, dem0n, dziugss, froz1k, Krabeni         |
|           24 |      595 | 2024-05-21 | Illuminar Gaming      | W   | 1.000      | 0.143        | 0.004 (0.001)    | 0.403 (0.058)    | 0 (0.000) |    16.17 | cmtry, dem0n, dziugss, froz1k, Krabeni         |
|           23 |     1992 | 2024-05-01 | XI Esport             | L   | 1.000      | -            | -                | -                | -         |   -19.89 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           22 |     2074 | 2024-04-29 | lajtbitexe            | W   | 0.996      | -            | -                | -                | 0 (0.000) |     7.80 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           21 |     2118 | 2024-04-28 | los kogutos           | L   | 0.989      | -            | -                | -                | -         |   -11.48 | chudy2k, darchevile, Enzo, Nami, yvro          |
|           20 |     2419 | 2024-04-23 | Dynamo Eclot Thunders | W   | 0.956      | -            | -                | -                | 0 (0.000) |     3.28 | coolio, dziugss, froz1k, qzr, UNBR0KEN         |
|           19 |     3443 | 2024-04-05 | 777 Esports           | W   | 0.837      | 0.289        | 0.029 (0.007)    | 0.463 (0.112)    | 0 (0.000) |    14.76 | Affava, Hagmeister, MadeInRed, Viktha, wenba   |
|           18 |     3556 | 2024-04-03 | SINNERS Academy       | W   | 0.823      | 0.289        | 0.001 (0.000)    | 0.227 (0.054)    | -         |     9.80 | BORO, DALIEN, dreez, majky, vANO               |
|           17 |     3705 | 2024-03-29 | Metizport X           | W   | 0.790      | 0.289        | 0.008 (0.002)    | 0.210 (0.048)    | -         |    12.34 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           16 |     3739 | 2024-03-28 | Sashi Academy         | W   | 0.784      | 0.289        | 0.001 (0.000)    | -                | -         |    10.01 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           15 |     3889 | 2024-03-26 | BRUTE                 | W   | 0.771      | -            | -                | -                | -         |     7.24 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           14 |     4029 | 2024-03-22 | 777 Esports           | L   | 0.744      | -            | -                | -                | -         |    -9.40 | Affava, artstyle, Hagmeister, MadeInRed, wenba |
|           13 |     4555 | 2024-03-12 | CUBE BY SND           | L   | 0.677      | -            | -                | -                | -         |   -11.33 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           12 |     4661 | 2024-03-10 | Les Gaulois           | W   | 0.664      | -            | -                | -                | -         |     2.87 | HippoV, Kanky, NeOo, Quentin, Yeneurs          |
|           11 |     4807 | 2024-03-07 | fragmatic             | L   | 0.644      | -            | -                | -                | -         |   -15.54 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|           10 |     4870 | 2024-03-06 | HAVENs                | W   | 0.637      | -            | -                | -                | -         |     2.73 | keni, proxi, v1trage, WIPSKY, yaankz           |
|            9 |     5280 | 2024-02-29 | SINNERS Academy       | L   | 0.597      | -            | -                | -                | -         |   -12.46 | BORO, dreez, luke, majky, vANO                 |
|            8 |     5455 | 2024-02-25 | Begrip Gaming         | L   | 0.570      | -            | -                | -                | -         |   -12.39 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|            7 |     5698 | 2024-02-21 | SINNERS Academy       | W   | 0.544      | 0.289        | -                | 0.227 (0.036)    | -         |     5.91 | BORO, dreez, luke, majky, vANO                 |
|            6 |     6766 | 2024-01-30 | AVEZ                  | L   | 0.397      | -            | -                | -                | -         |    -5.10 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|            5 |     6876 | 2024-01-28 | Sampi NEXT            | W   | 0.383      | -            | -                | -                | -         |     1.46 | bestch, DALIEN, EMCOR, ramon, Verttzzz         |
|            4 |     6953 | 2024-01-27 | ex-KRC Genk Esports   | L   | 0.378      | -            | -                | -                | -         |    -7.84 | cmtry, dziugss, froz1k, qzr, UNBR0KEN          |
|            3 |     7082 | 2024-01-25 | GamerLegion Academy   | W   | 0.364      | 0.289        | 0.018 (0.002)    | 0.691 (0.073)    | -         |     6.88 | aNdu, Darber, leaf, nestee, rud                |
|            2 |     7404 | 2024-01-19 | Apeks Rebels          | W   | 0.324      | -            | -                | -                | -         |     2.22 | Boye, bq, Junyme, Q-Q, Tapewaare               |
|            1 |     9358 | 2023-12-03 | SINNERS Academy       | L   | 0.011      | -            | -                | -                | -         |    -0.22 | BORO, dreez, luke, majky, vANO                 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,673.89)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
