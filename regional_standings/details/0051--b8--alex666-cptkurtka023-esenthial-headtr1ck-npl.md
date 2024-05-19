### Roster Details<br />
Team Name: B8<br />
Roster: alex666, cptkurtka023, esenthial, headtr1ck, npl<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [51](../standings_global.md)<br />
Regional Rank: [36]( ../standings_europe.md)<br />
Final Rank Value:  1023.9<br />
<br />
Final Rank Value (1023.9) = Starting Rank Value (945.4) + Head To Head Adjustments (78.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.487[<sup>1</sup>](#table2)
- Bounty Collected: 0.377[<sup>2</sup>](#table1)
- Opponent Network: 0.236[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.275<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 945.4
- 400 + ( ( 0.275 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 945.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           36 |       71 | 2024-05-04 | GamerLegion Academy   | W   | 1.000      | 0.435        | 0.043 (0.019)    | 0.567 (0.246)    | false (0.000) |     9.88 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           35 |      163 | 2024-05-02 | Permitta Esports      | W   | 1.000      | 0.384        | 0.063 (0.024)    | 1.000 (0.384)    | false (0.000) |    11.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           34 |      186 | 2024-05-01 | Nemiga Gaming         | L   | 1.000      | -            | -                | -                | -             |    -6.44 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           33 |      204 | 2024-05-01 | V1dar Gaming          | W   | 1.000      | 0.435        | -                | 0.345 (0.150)    | false (0.000) |     4.04 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           32 |      222 | 2024-05-01 | SINNERS Esports       | W   | 1.000      | 0.384        | 0.038 (0.014)    | 0.534 (0.205)    | false (0.000) |    13.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           31 |      248 | 2024-04-30 | Alliance              | W   | 1.000      | 0.500        | 0.017 (0.008)    | 0.729 (0.364)    | false (0.000) |    10.25 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           30 |      255 | 2024-04-30 | Zero Tenacity         | L   | 1.000      | -            | -                | -                | -             |   -16.35 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           29 |      577 | 2024-04-23 | BLEED Esports         | L   | 1.000      | -            | -                | -                | -             |    -8.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           28 |      597 | 2024-04-22 | Passion UA            | W   | 1.000      | 0.500        | 0.114 (0.057)    | 0.980 (0.490)    | false (0.000) |    13.69 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           27 |      657 | 2024-04-21 | PARIVISION            | W   | 1.000      | 0.500        | -                | 0.374 (0.187)    | false (0.000) |     9.40 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           26 |      841 | 2024-04-19 | HAVU Gaming           | W   | 1.000      | 0.500        | 0.024 (0.012)    | 0.213 (0.107)    | false (0.000) |     8.05 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           25 |      953 | 2024-04-17 | Zero Tenacity         | L   | 1.000      | -            | -                | -                | -             |   -19.42 | alex666, cptkurtka023, esenthial, headtr1ck, npl |
|           24 |     1022 | 2024-04-16 | AMKAL ESPORTS         | L   | 1.000      | -            | -                | -                | -             |    -8.57 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           23 |     1238 | 2024-04-10 | Nexus Gaming          | L   | 1.000      | -            | -                | -                | -             |   -18.07 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           22 |     1281 | 2024-04-09 | Rebels Gaming         | L   | 1.000      | -            | -                | -                | -             |    -9.99 | baz, cptkurtka023, esenthial, headtr1ck, npl     |
|           21 |     1997 | 2024-03-21 | BetBoom Team          | L   | 0.897      | -            | -                | -                | -             |    -2.80 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           20 |     2071 | 2024-03-19 | Sprout                | W   | 0.883      | -            | -                | -                | false (0.000) |     0.78 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           19 |     2365 | 2024-03-12 | Metizport             | L   | 0.839      | -            | -                | -                | -             |    -8.76 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           18 |     2376 | 2024-03-12 | ENCE                  | W   | 0.838      | 0.143        | 0.377 (0.045)    | -                | false (0.000) |    25.04 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           17 |     2403 | 2024-03-11 | KOI                   | W   | 0.832      | -            | -                | -                | -             |    17.18 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           16 |     2424 | 2024-03-11 | Virtus.pro            | L   | 0.831      | -            | -                | -                | -             |    -0.43 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           15 |     2679 | 2024-03-05 | Johnny Speeds         | W   | 0.792      | -            | -                | -                | -             |     8.63 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           14 |     2684 | 2024-03-05 | Passion UA            | W   | 0.792      | 0.143        | 0.114 (0.013)    | 0.980 (0.111)    | -             |    10.86 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           13 |     2695 | 2024-03-05 | UGANDA (Finnish team) | W   | 0.792      | -            | -                | -                | -             |     2.03 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           12 |     2723 | 2024-03-04 | Gaimin Gladiators     | W   | 0.786      | 0.143        | 0.194 (0.022)    | 0.989 (0.111)    | -             |    22.06 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           11 |     2749 | 2024-03-04 | Alliance              | W   | 0.786      | -            | -                | -                | -             |     9.15 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|           10 |     2829 | 2024-03-02 | Fnatic                | L   | 0.773      | -            | -                | -                | -             |    -4.67 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            9 |     3031 | 2024-02-27 | DMS                   | L   | 0.745      | -            | -                | -                | -             |   -19.51 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            8 |     3066 | 2024-02-26 | Sprout                | W   | 0.739      | -            | -                | -                | -             |     1.74 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            7 |     3458 | 2024-02-18 | Aurora Gaming         | L   | 0.684      | -            | -                | -                | -             |    -0.79 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            6 |     3533 | 2024-02-16 | 500                   | W   | 0.671      | -            | -                | -                | -             |     7.19 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            5 |     3544 | 2024-02-16 | Pera Esports          | W   | 0.671      | -            | -                | -                | -             |     4.03 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            4 |     4016 | 2024-02-02 | 9Pandas               | W   | 0.579      | -            | -                | -                | -             |    13.87 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            3 |     4023 | 2024-02-02 | Team Sampi            | W   | 0.578      | 0.143        | 0.108 (0.009)    | -                | -             |    10.63 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            2 |     4042 | 2024-02-02 | POVYDLO ESPORTS       | W   | 0.578      | -            | -                | -                | -             |     0.87 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |
|            1 |     4174 | 2024-01-29 | Into The Breach       | L   | 0.553      | -            | -                | -                | -             |   -11.10 | cptkurtka023, esenthial, npl, OWNER, r1nkle      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($14,000.00)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.09) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-04-24 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-04-20 |      1.000 | $1,500.00      | $1,500.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
