### Roster Details<br />
Team Name: Nexus Gaming<br />
Roster: BTN, ERSIN, ragga, s0und, XELLOW<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [107](../standings_global.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
Final Rank Value:  846.8<br />
<br />
Final Rank Value (846.8) = Starting Rank Value (954.8) + Head To Head Adjustments (-108.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.400[<sup>1</sup>](#table2)
- Bounty Collected: 0.437[<sup>2</sup>](#table1)
- Opponent Network: 0.282[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 954.8
- 400 + ( ( 0.280 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 954.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           88 |      124 | 2024-05-03 | ENCE Academy             | L   | 1.000      | -            | -                | -                | -             |   -19.18 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           87 |      199 | 2024-05-01 | ARCRED                   | L   | 1.000      | -            | -                | -                | -             |   -14.64 | BTN, ERSIN, fnl, ragga, XELLOW    |
|           86 |      212 | 2024-05-01 | Insilio                  | L   | 1.000      | -            | -                | -                | -             |   -12.57 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           85 |      260 | 2024-04-30 | Fnatic                   | L   | 1.000      | -            | -                | -                | -             |    -4.22 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           84 |      275 | 2024-04-29 | Endpoint                 | L   | 1.000      | -            | -                | -                | -             |   -16.27 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           83 |      285 | 2024-04-29 | VP.Prodigy               | L   | 1.000      | -            | -                | -                | -             |   -21.37 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           82 |      290 | 2024-04-29 | LEON Esports             | W   | 1.000      | -            | -                | -                | false (0.000) |     7.00 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           81 |      293 | 2024-04-29 | ENTERPRISE esports       | W   | 1.000      | 0.384        | 0.039 (0.015)    | 0.476 (0.183)    | false (0.000) |    13.49 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           80 |      470 | 2024-04-25 | Metizport                | W   | 1.000      | 0.384        | 0.188 (0.072)    | 1.000 (0.384)    | false (0.000) |    23.79 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           79 |      550 | 2024-04-24 | AMKAL ESPORTS            | L   | 1.000      | -            | -                | -                | -             |    -4.86 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           78 |      589 | 2024-04-23 | Illuminar Gaming         | L   | 1.000      | -            | -                | -                | -             |   -18.35 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           77 |      617 | 2024-04-22 | Zero Tenacity            | L   | 1.000      | -            | -                | -                | -             |   -14.13 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           76 |      631 | 2024-04-21 | Young Ninjas             | W   | 1.000      | 0.500        | 0.074 (0.037)    | 0.338 (0.169)    | false (0.000) |    16.79 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           75 |      646 | 2024-04-21 | PARIVISION               | L   | 1.000      | -            | -                | -                | -             |   -19.26 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           74 |      751 | 2024-04-20 | Permitta Esports         | W   | 1.000      | 0.500        | 0.063 (0.031)    | 1.000 (0.500)    | false (0.000) |    16.54 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           73 |      869 | 2024-04-18 | Young Ninjas             | L   | 1.000      | -            | -                | -                | -             |   -14.00 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           72 |      901 | 2024-04-18 | ENTERPRISE esports       | L   | 1.000      | -            | -                | -                | -             |   -15.68 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           71 |     1143 | 2024-04-12 | HyperSpirit              | L   | 1.000      | -            | -                | -                | -             |   -24.68 | BTN, ERSIN, fnl, ragga, XELLOW    |
|           70 |     1238 | 2024-04-10 | B8                       | W   | 1.000      | 0.384        | 0.088 (0.034)    | 0.589 (0.226)    | false (0.000) |    18.07 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           69 |     1443 | 2024-04-05 | SINNERS Esports          | L   | 0.998      | -            | -                | -                | -             |   -13.16 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           68 |     1845 | 2024-03-25 | Sashi Esport             | L   | 0.925      | -            | -                | -                | -             |   -11.03 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           67 |     2372 | 2024-03-12 | Nemiga Gaming            | W   | 0.839      | 0.371        | 0.680 (0.212)    | 0.910 (0.283)    | false (0.000) |    22.96 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           66 |     2419 | 2024-03-11 | RUBY                     | W   | 0.832      | 0.371        | -                | 0.882 (0.272)    | false (0.000) |    12.07 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           65 |     2496 | 2024-03-09 | INGLORIOUS               | W   | 0.818      | -            | -                | -                | false (0.000) |     9.57 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           64 |     2529 | 2024-03-08 | BLESSED (Ukrainian team) | W   | 0.812      | 0.371        | -                | 0.781 (0.236)    | false (0.000) |    11.87 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           63 |     2727 | 2024-03-04 | FORZE Esports            | L   | 0.786      | -            | -                | -                | -             |    -6.65 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           62 |     2741 | 2024-03-04 | KOMNATA                  | W   | 0.786      | -            | -                | -                | -             |     1.22 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           61 |     2798 | 2024-03-03 | TSM                      | L   | 0.778      | -            | -                | -                | -             |   -18.47 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           60 |     2807 | 2024-03-03 | Zero Tenacity            | W   | 0.778      | 0.371        | 0.095 (0.027)    | 1.000 (0.289)    | -             |    12.53 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           59 |     2832 | 2024-03-02 | GUN5 Esports             | W   | 0.773      | -            | -                | -                | -             |     4.51 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           58 |     2857 | 2024-03-02 | Aurora Young Blud        | W   | 0.772      | -            | -                | -                | -             |     8.15 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           57 |     2921 | 2024-03-01 | Passion UA               | W   | 0.764      | 0.371        | 0.114 (0.032)    | 0.980 (0.278)    | -             |    11.77 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           56 |     2952 | 2024-02-29 | INGLORIOUS               | L   | 0.758      | -            | -                | -                | -             |   -14.59 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           55 |     2992 | 2024-02-28 | Aurora Young Blud        | W   | 0.751      | -            | -                | -                | -             |     7.91 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           54 |     3073 | 2024-02-26 | EsmagaB                  | W   | 0.738      | -            | -                | -                | -             |     8.32 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           53 |     3164 | 2024-02-24 | L&G                      | W   | 0.724      | -            | -                | -                | -             |     2.60 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           52 |     3364 | 2024-02-20 | Guild Eagles             | L   | 0.697      | -            | -                | -                | -             |    -6.74 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           51 |     3405 | 2024-02-19 | Monte                    | L   | 0.692      | -            | -                | -                | -             |    -1.28 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           50 |     3420 | 2024-02-19 | Astralis                 | L   | 0.691      | -            | -                | -                | -             |    -0.64 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           49 |     3844 | 2024-02-07 | V1dar Gaming             | W   | 0.612      | -            | -                | -                | -             |     3.21 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           48 |     3900 | 2024-02-05 | Gaimin Gladiators        | L   | 0.598      | -            | -                | -                | -             |    -1.32 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           47 |     3928 | 2024-02-04 | BIG Academy              | L   | 0.591      | -            | -                | -                | -             |   -11.62 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           46 |     3951 | 2024-02-03 | 500                      | L   | 0.585      | -            | -                | -                | -             |   -11.76 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           45 |     3964 | 2024-02-03 | Jake Bube                | W   | 0.585      | -            | -                | -                | -             |     0.88 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           44 |     3995 | 2024-02-03 | AIRLYA                   | L   | 0.584      | -            | -                | -                | -             |   -16.55 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           43 |     4046 | 2024-02-02 | Royalty                  | W   | 0.578      | -            | -                | -                | -             |     0.81 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           42 |     4230 | 2024-01-28 | Passion UA               | L   | 0.543      | -            | -                | -                | -             |    -7.94 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           41 |     4319 | 2024-01-26 | GamerLegion Academy      | W   | 0.531      | -            | -                | -                | -             |     6.24 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           40 |     4543 | 2024-01-20 | OG                       | L   | 0.492      | -            | -                | -                | -             |    -1.70 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           39 |     4563 | 2024-01-20 | BIG                      | W   | 0.490      | 0.143        | 0.470 (0.033)    | -                | -             |    14.52 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           38 |     4597 | 2024-01-19 | SINNERS Esports          | W   | 0.486      | -            | -                | -                | -             |     9.11 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           37 |     4645 | 2024-01-18 | Gaimin Gladiators        | L   | 0.479      | -            | -                | -                | -             |    -0.92 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           36 |     4659 | 2024-01-18 | 9Pandas                  | L   | 0.478      | -            | -                | -                | -             |    -3.87 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           35 |     4777 | 2024-01-16 | Endpoint                 | W   | 0.466      | -            | -                | -                | -             |     5.78 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           34 |     4783 | 2024-01-16 | BLESSED (Ukrainian team) | W   | 0.466      | -            | -                | -                | -             |     5.29 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           33 |     4796 | 2024-01-16 | Alliance                 | W   | 0.466      | -            | -                | -                | -             |     6.76 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           32 |     4802 | 2024-01-16 | The Chosen Few           | W   | 0.465      | -            | -                | -                | -             |     5.14 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           31 |     4890 | 2024-01-13 | OG                       | L   | 0.444      | -            | -                | -                | -             |    -1.22 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           30 |     4922 | 2024-01-12 | Soda Gaming              | W   | 0.439      | -            | -                | -                | -             |     4.32 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           29 |     4930 | 2024-01-12 | JANO Esports             | W   | 0.439      | -            | -                | -                | -             |     4.46 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           28 |     4952 | 2024-01-12 | Astralis Talent          | L   | 0.436      | -            | -                | -                | -             |    -5.87 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           27 |     5063 | 2024-01-10 | WOPA Esport              | W   | 0.423      | -            | -                | -                | -             |     4.28 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           26 |     5102 | 2024-01-09 | K10                      | L   | 0.418      | -            | -                | -                | -             |    -6.75 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           25 |     5123 | 2024-01-09 | Team Space               | W   | 0.418      | -            | -                | -                | -             |     3.67 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           24 |     5154 | 2024-01-08 | Zero Tenacity            | L   | 0.410      | -            | -                | -                | -             |    -5.70 | BTN, CHANKY, ERSIN, ragga, XELLOW |
|           23 |     5180 | 2024-01-06 | Astralis Talent          | L   | 0.397      | -            | -                | -                | -             |    -5.43 | BTN, ERSIN, ragga, s0und, XELLOW  |
|           22 |     5185 | 2024-01-05 | Monte Gen                | L   | 0.391      | -            | -                | -                | -             |    -8.08 | BTN, CHANKY, ERSIN, ragga, XELLOW |
|           21 |     5312 | 2023-12-19 | MOUZ NXT                 | L   | 0.279      | -            | -                | -                | -             |    -2.59 | BTN, ragga, s0und, smekk, XELLOW  |
|           20 |     5313 | 2023-12-19 | Ex-Anonymo Esports       | L   | 0.278      | -            | -                | -                | -             |    -5.98 | BTN, ragga, s0und, smekk, XELLOW  |
|           19 |     5327 | 2023-12-18 | MOUZ NXT                 | W   | 0.271      | 0.354        | 0.215 (0.021)    | -                | -             |     6.06 | BTN, ragga, s0und, smekk, XELLOW  |
|           18 |     5331 | 2023-12-18 | Astralis Talent          | L   | 0.270      | -            | -                | -                | -             |    -3.79 | BTN, ragga, s0und, smekk, XELLOW  |
|           17 |     5380 | 2023-12-17 | Illuminar Gaming         | L   | 0.264      | -            | -                | -                | -             |    -5.99 | BTN, ragga, s0und, smekk, XELLOW  |
|           16 |     5597 | 2023-12-15 | Sashi Esport             | L   | 0.249      | -            | -                | -                | -             |    -6.04 | BTN, ragga, s0und, smekk, XELLOW  |
|           15 |     5679 | 2023-12-12 | WOPA Esport              | W   | 0.230      | -            | -                | -                | -             |     2.03 | BTN, ragga, s0und, smekk, XELLOW  |
|           14 |     5717 | 2023-12-10 | Natus Vincere Junior     | L   | 0.218      | -            | -                | -                | -             |    -4.31 | BTN, ragga, s0und, smekk, XELLOW  |
|           13 |     5903 | 2023-12-07 | Pompa Team               | W   | 0.196      | -            | -                | -                | -             |     0.53 | BTN, ragga, s0und, smekk, XELLOW  |
|           12 |     5925 | 2023-12-06 | GamerLegion Academy      | W   | 0.192      | -            | -                | -                | -             |     2.51 | BTN, ragga, s0und, smekk, XELLOW  |
|           11 |     6051 | 2023-12-03 | Lazer Cats               | W   | 0.170      | -            | -                | -                | -             |     0.78 | BTN, ragga, s0und, smekk, XELLOW  |
|           10 |     6159 | 2023-12-01 | BLESSED (Ukrainian team) | L   | 0.159      | -            | -                | -                | -             |    -3.26 | BTN, ragga, s0und, smekk, XELLOW  |
|            9 |     6205 | 2023-11-30 | BIG Academy              | L   | 0.152      | -            | -                | -                | -             |    -3.19 | BTN, ragga, s0und, smekk, XELLOW  |
|            8 |     6245 | 2023-11-29 | DMS                      | L   | 0.146      | -            | -                | -                | -             |    -3.88 | BTN, ragga, s0und, smekk, XELLOW  |
|            7 |     6485 | 2023-11-24 | TEAM ZOO BAR             | W   | 0.111      | -            | -                | -                | -             |     0.27 | BTN, ragga, s0und, smekk, XELLOW  |
|            6 |     6525 | 2023-11-23 | TSM                      | L   | 0.104      | -            | -                | -                | -             |    -2.63 | BTN, ragga, s0und, smekk, XELLOW  |
|            5 |     6595 | 2023-11-21 | Astralis Talent          | L   | 0.091      | -            | -                | -                | -             |    -1.36 | BTN, ragga, s0und, smekk, XELLOW  |
|            4 |     6814 | 2023-11-16 | Underrated               | W   | 0.059      | -            | -                | -                | -             |     0.12 | BTN, ragga, s0und, smekk, XELLOW  |
|            3 |     6824 | 2023-11-16 | GenOne                   | W   | 0.058      | -            | -                | -                | -             |     0.25 | BTN, ragga, s0und, smekk, XELLOW  |
|            2 |     6918 | 2023-11-14 | BALLISTIC                | W   | 0.046      | -            | -                | -                | -             |     0.06 | BTN, ragga, s0und, smekk, XELLOW  |
|            1 |     6935 | 2023-11-14 | Astralis Talent          | L   | 0.044      | -            | -                | -                | -             |    -0.64 | BTN, ragga, s0und, smekk, XELLOW  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,976.11)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-05-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-03-25 |      0.925 | $4,300.00      | $3,976.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
