### Roster Details<br />
Team Name: LODIS<br />
Roster: aimy, asran, fugor, Mride, pawkoem<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [320](../standings_global.md)<br />
Regional Rank: [195]( ../standings_europe.md)<br />
Final Rank Value:  581.6<br />
<br />
Final Rank Value (581.6) = Starting Rank Value (659.9) + Head To Head Adjustments (-78.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 659.9
- 400 + ( ( 0.131 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 659.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |        8 | 2024-05-05 | Lemondogs              | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.252 (0.094)    | 0 (0.000) |    15.59 | aimy, asran, fugor, Mride, pawkoem          |
|           22 |       14 | 2024-05-05 | Kappa Bar              | L   | 1.000      | -            | -                | -                | -         |   -16.09 | aimy, asran, fugor, Mride, pawkoem          |
|           21 |     1064 | 2024-04-14 | Young Ninjas           | L   | 1.000      | -            | -                | -                | -         |    -3.23 | aimy, asran, fugor, Mride, pawkoem          |
|           20 |     1940 | 2024-03-22 | Illuminar Gaming       | L   | 0.905      | -            | -                | -                | -         |    -5.64 | aimy, asran, fugor, Mride, pawkoem          |
|           19 |     1981 | 2024-03-21 | Turów Zgorzelec Esport | L   | 0.899      | -            | -                | -                | -         |    -7.01 | aimy, asran, fugor, Mride, pawkoem          |
|           18 |     2015 | 2024-03-20 | Mikstura1234           | L   | 0.892      | -            | -                | -                | -         |   -11.90 | aimy, asran, fugor, Mride, pawkoem          |
|           17 |     2060 | 2024-03-19 | ENTERPRISE esports     | L   | 0.885      | -            | -                | -                | -         |    -4.17 | aimy, asran, fugor, Mride, pawkoem          |
|           16 |     2094 | 2024-03-18 | ThunderFlash           | W   | 0.878      | 0.143        | 0.023 (0.003)    | 0.274 (0.034)    | 0 (0.000) |    20.08 | aimy, asran, fugor, Mride, pawkoem          |
|           15 |     2456 | 2024-03-10 | DEEZ NUTS              | L   | 0.825      | -            | -                | -                | -         |   -10.40 | avis, b1elany, ewrzyn, sh3nanigan, zaNNN    |
|           14 |     2976 | 2024-02-28 | Copenhagen Wolves      | L   | 0.752      | -            | -                | -                | -         |   -11.60 | Basso, Fessor, Svedjehed, szejn, vigg0      |
|           13 |     3023 | 2024-02-27 | Ex-Hot Headed Gaming   | L   | 0.745      | -            | -                | -                | -         |   -14.90 | asran, fugor, GruBy, Mride, pawkoem         |
|           12 |     3070 | 2024-02-26 | 0to100                 | W   | 0.739      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.98 | juliustbe, kerogi, krea6on, uQlutzavr, v1ze |
|           11 |     3093 | 2024-02-25 | Golden Sword           | W   | 0.732      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.67 | asran, fugor, GruBy, Mride, pawkoem         |
|           10 |     3240 | 2024-02-22 | Grindas                | L   | 0.712      | -            | -                | -                | -         |    -9.35 | AwwEzz, BaGyZ, prochas, Sidivo, slokker     |
|            9 |     3712 | 2024-02-12 | K10                    | L   | 0.646      | -            | -                | -                | -         |    -4.52 | Rezst, shyyne, SLY, Tree, yz0               |
|            8 |     3717 | 2024-02-12 | ALTERNATE aTTaX        | L   | 0.645      | -            | -                | -                | -         |    -2.41 | asran, fugor, GruBy, Mride, pawkoem         |
|            7 |     3822 | 2024-02-08 | V1dar Gaming           | L   | 0.618      | -            | -                | -                | -         |   -10.39 | asran, fugor, GruBy, Mride, pawkoem         |
|            6 |     3843 | 2024-02-07 | Ex-KRC Genk Esports    | W   | 0.612      | 0.371        | 0.008 (0.002)    | 0.181 (0.041)    | 0 (0.000) |    13.28 | asran, fugor, GruBy, Mride, pawkoem         |
|            5 |     3880 | 2024-02-05 | MOUZ NXT               | L   | 0.599      | -            | -                | -                | -         |    -1.55 | Burmylov, Chr1zN, Neityu, PR, sirah         |
|            4 |     4026 | 2024-02-02 | DASH                   | L   | 0.578      | -            | -                | -                | -         |    -7.25 | asran, fugor, GruBy, Mride, pawkoem         |
|            3 |     4138 | 2024-01-30 | Kappa Bar              | L   | 0.559      | -            | -                | -                | -         |    -8.41 | asran, fugor, GruBy, Mride, pawkoem         |
|            2 |     4715 | 2024-01-17 | GODSENT                | L   | 0.472      | -            | -                | -                | -         |    -4.70 | asran, fugor, GruBy, Mride, pawkoem         |
|            1 |     4804 | 2024-01-16 | PARIVISION             | L   | 0.465      | -            | -                | -                | -         |    -3.39 | ArtFr0st, Jerry, Patsi, Qikert, X5G7V       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($369.69)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
