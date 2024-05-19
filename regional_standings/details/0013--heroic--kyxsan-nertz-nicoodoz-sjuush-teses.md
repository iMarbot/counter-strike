### Roster Details<br />
Team Name: HEROIC<br />
Roster: kyxsan, NertZ, nicoodoz, sjuush, TeSeS<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [13](../standings_global.md)<br />
Regional Rank: [11]( ../standings_europe.md)<br />
Final Rank Value:  1574.8<br />
<br />
Final Rank Value (1574.8) = Starting Rank Value (1722.1) + Head To Head Adjustments (-147.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.619[<sup>1</sup>](#table2)
- Bounty Collected: 0.688[<sup>2</sup>](#table1)
- Opponent Network: 0.363[<sup>2</sup>](#table1)
- LAN Wins: 0.995[<sup>2</sup>](#table1)

The average of these factors is 0.666<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1722.1
- 400 + ( ( 0.666 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 1722.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           44 |       60 | 2024-05-04 | Ninjas in Pyjamas  | L   | 1.000      | -            | -                | -                | -         |   -29.01 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           43 |      102 | 2024-05-03 | BIG                | L   | 1.000      | -            | -                | -                | -         |   -24.47 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           42 |      120 | 2024-05-03 | FlyQuest           | W   | 1.000      | 0.889        | -                | 0.547 (0.486)    | 1 (1.000) |     7.25 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           41 |      149 | 2024-05-02 | Complexity Gaming  | L   | 1.000      | -            | -                | -                | -         |   -20.83 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           40 |      243 | 2024-04-30 | Ninjas in Pyjamas  | W   | 1.000      | 0.889        | 0.241 (0.215)    | 0.376 (0.334)    | 1 (1.000) |     1.98 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           39 |     1244 | 2024-04-10 | G2 Esports         | L   | 1.000      | -            | -                | -                | -         |    -7.72 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           38 |     1307 | 2024-04-09 | FURIA Esports      | W   | 1.000      | 0.624        | 0.384 (0.240)    | 0.361 (0.226)    | 1 (1.000) |    11.49 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           37 |     1348 | 2024-04-08 | 9z Team            | W   | 1.000      | 0.624        | -                | 0.376 (0.234)    | 1 (1.000) |     0.89 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           36 |     1360 | 2024-04-07 | Team Liquid        | L   | 1.000      | -            | -                | -                | -         |   -25.92 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           35 |     1898 | 2024-03-23 | PaiN Gaming        | L   | 0.912      | -            | -                | -                | -         |   -27.43 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           34 |     1948 | 2024-03-22 | Virtus.pro         | L   | 0.904      | -            | -                | -                | -         |   -12.91 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           33 |     1976 | 2024-03-21 | Complexity Gaming  | L   | 0.899      | -            | -                | -                | -         |   -21.81 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           32 |     1988 | 2024-03-21 | FaZe Clan          | W   | 0.898      | 1.000        | 1.000 (0.898)    | 0.566 (0.508)    | 1 (0.898) |    22.75 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           31 |     2099 | 2024-03-18 | Eternal Fire       | W   | 0.877      | 1.000        | 0.409 (0.359)    | 0.462 (0.406)    | 1 (0.877) |    17.42 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           30 |     2127 | 2024-03-17 | Imperial Esports   | W   | 0.872      | 1.000        | 0.674 (0.588)    | 0.549 (0.478)    | 1 (0.872) |     7.34 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           29 |     2143 | 2024-03-17 | Lynn Vision Gaming | W   | 0.871      | 1.000        | 0.155 (0.135)    | 0.554 (0.483)    | 1 (0.871) |     2.45 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           28 |     2325 | 2024-03-13 | Metizport          | W   | 0.844      | -            | -                | -                | -         |     1.49 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           27 |     2366 | 2024-03-12 | Virtus.pro         | L   | 0.839      | -            | -                | -                | -         |   -11.02 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           26 |     2408 | 2024-03-11 | ENCE               | W   | 0.832      | -            | -                | -                | -         |     9.12 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           25 |     2426 | 2024-03-11 | Preasy Esport      | W   | 0.831      | -            | -                | -                | -         |     0.79 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           24 |     2502 | 2024-03-09 | OG                 | L   | 0.818      | -            | -                | -                | -         |   -22.74 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           23 |     3253 | 2024-02-22 | GamerLegion        | W   | 0.711      | -            | -                | -                | 1 (0.711) |     7.65 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           22 |     3302 | 2024-02-21 | Team Spirit        | L   | 0.705      | -            | -                | -                | -         |    -6.17 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           21 |     3370 | 2024-02-20 | Astralis           | W   | 0.697      | -            | -                | -                | 1 (0.697) |     6.37 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           20 |     3396 | 2024-02-19 | Team Vitality      | L   | 0.692      | -            | -                | -                | -         |    -5.56 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           19 |     3418 | 2024-02-19 | Preasy Esport      | W   | 0.691      | -            | -                | -                | -         |     0.44 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           18 |     3857 | 2024-02-06 | G2 Esports         | L   | 0.605      | -            | -                | -                | -         |    -5.39 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           17 |     3866 | 2024-02-06 | GamerLegion        | W   | 0.604      | 1.000        | 0.194 (0.117)    | 0.419 (0.253)    | -         |     6.86 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           16 |     3906 | 2024-02-05 | Team Vitality      | W   | 0.597      | 1.000        | 1.000 (0.597)    | -                | -         |    14.30 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           15 |     3998 | 2024-02-03 | G2 Esports         | L   | 0.584      | -            | -                | -                | -         |    -4.67 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           14 |     4099 | 2024-01-31 | BIG                | W   | 0.566      | 1.000        | 0.470 (0.266)    | 0.400 (0.226)    | -         |     3.79 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           13 |     4119 | 2024-01-31 | Astralis           | W   | 0.564      | 1.000        | 0.179 (0.101)    | -                | -         |     5.90 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           12 |     4351 | 2024-01-25 | BIG                | L   | 0.525      | -            | -                | -                | -         |   -13.45 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           11 |     4375 | 2024-01-24 | Cloud9             | L   | 0.519      | -            | -                | -                | -         |    -5.97 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|           10 |     4566 | 2024-01-20 | IKLA               | W   | 0.490      | -            | -                | -                | -         |     0.08 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            9 |     4609 | 2024-01-19 | KOI                | L   | 0.484      | -            | -                | -                | -         |   -14.84 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            8 |     4655 | 2024-01-18 | MOUZ               | L   | 0.478      | -            | -                | -                | -         |    -4.46 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            7 |     4665 | 2024-01-18 | FORZE Esports      | W   | 0.478      | -            | -                | -                | -         |     0.10 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            6 |     4982 | 2024-01-11 | SINNERS Esports    | W   | 0.433      | -            | -                | -                | -         |     0.26 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            5 |     4986 | 2024-01-11 | IKLA               | W   | 0.432      | -            | -                | -                | -         |     0.06 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            4 |     5001 | 2024-01-11 | HAVU Gaming        | W   | 0.431      | -            | -                | -                | -         |     0.13 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            3 |     5044 | 2024-01-10 | GUN5 Esports       | W   | 0.426      | -            | -                | -                | -         |     0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            2 |     5060 | 2024-01-10 | Rustec             | W   | 0.426      | -            | -                | -                | -         |     0.04 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |
|            1 |     5106 | 2024-01-09 | Nemiga Gaming      | L   | 0.418      | -            | -                | -                | -         |   -11.94 | kyxsan, NertZ, nicoodoz, sjuush, TeSeS |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($38,496.47)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.24) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-05 |      1.000 | $7,000.00      | $7,000.00       |
| 2024-04-14 |      1.000 | $6,000.00      | $6,000.00       |
| 2024-03-31 |      0.965 | $20,000.00     | $19,304.63      |
| 2024-03-10 |      0.826 | $7,500.00      | $6,191.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
