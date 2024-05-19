### Roster Details<br />
Team Name: GenOne<br />
Roster: aidKiT, bibu, EIZA, Graviti, Sterzig<br />
Region: [Europe]( ../standings_europe.md)<br />
<br />
Global Rank: [280](../standings_global.md)<br />
Regional Rank: [173]( ../standings_europe.md)<br />
Final Rank Value:  630.4<br />
<br />
Final Rank Value (630.4) = Starting Rank Value (622.7) + Head To Head Adjustments (7.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.232[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 622.7
- 400 + ( ( 0.112 - 0.000 ) / ( 0.806 - 0.000 ) ) * 1600 = 622.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins      | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     5053 | 2024-01-10 | Team Space               | L   | 0.426      | -            | -                | -                | -             |    -4.88 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|           20 |     5362 | 2023-12-17 | EYEBALLERS               | L   | 0.264      | -            | -                | -                | -             |    -1.20 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|           19 |     5456 | 2023-12-16 | Sangal Esports           | W   | 0.259      | 0.294        | 0.000 (0.000)    | 0.350 (0.027)    | false (0.000) |     4.60 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|           18 |     5469 | 2023-12-16 | ILIN                     | W   | 0.258      | 0.294        | 0.000 (0.000)    | 0.348 (0.026)    | false (0.000) |     3.24 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|           17 |     5937 | 2023-12-06 | Zero Tenacity            | L   | 0.191      | -            | -                | -                | -             |    -0.81 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           16 |     6214 | 2023-11-30 | TSM                      | W   | 0.151      | 0.371        | 0.008 (0.000)    | 0.043 (0.002)    | false (0.000) |     2.91 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           15 |     6325 | 2023-11-28 | Endpoint                 | L   | 0.138      | -            | -                | -                | -             |    -0.96 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           14 |     6516 | 2023-11-23 | ENTERPRISE esports       | L   | 0.105      | -            | -                | -                | -             |    -0.45 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           13 |     6526 | 2023-11-23 | DMS                      | W   | 0.104      | 0.371        | 0.000 (0.000)    | 0.504 (0.020)    | false (0.000) |     1.76 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           12 |     6644 | 2023-11-20 | Insilio                  | W   | 0.084      | 0.371        | 0.020 (0.001)    | 0.875 (0.027)    | false (0.000) |     2.24 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           11 |     6661 | 2023-11-19 | The Witchers             | L   | 0.079      | -            | -                | -                | -             |    -0.72 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|           10 |     6672 | 2023-11-19 | Grindas                  | W   | 0.078      | 0.294        | 0.002 (0.000)    | 0.332 (0.008)    | false (0.000) |     1.49 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|            9 |     6769 | 2023-11-17 | BLESSED (Ukrainian team) | L   | 0.065      | -            | -                | -                | -             |    -0.47 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|            8 |     6785 | 2023-11-17 | Sashi Esport             | L   | 0.064      | -            | -                | -                | -             |    -0.14 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|            7 |     6815 | 2023-11-16 | Grindas                  | W   | 0.059      | 0.371        | 0.002 (0.000)    | 0.332 (0.007)    | false (0.000) |     1.12 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|            6 |     6824 | 2023-11-16 | Nexus Gaming             | L   | 0.058      | -            | -                | -                | -             |    -0.25 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|            5 |     6850 | 2023-11-16 | GODSENT                  | L   | 0.056      | -            | -                | -                | -             |    -0.48 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|            4 |     6975 | 2023-11-13 | ESCAPIST                 | W   | 0.038      | 0.371        | 0.000 (0.000)    | 0.013 (0.000)    | false (0.000) |     0.47 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|            3 |     7073 | 2023-11-11 | GUN5 Esports             | L   | 0.023      | -            | -                | -                | -             |    -0.34 | aidKiT, bibu, EIZA, Graviti, Sterzig     |
|            2 |     7104 | 2023-11-10 | Ex-Anonymo Esports       | W   | 0.017      | 0.371        | 0.019 (0.000)    | 0.295 (0.002)    | false (0.000) |     0.37 | aidKiT, bibu, Get_Jeka, Graviti, Sterzig |
|            1 |     7147 | 2023-11-09 | CYBERSHOKE Esports       | W   | 0.010      | 0.143        | 0.004 (0.000)    | 0.220 (0.000)    | false (0.000) |     0.21 | aidKiT, bibu, EIZA, Graviti, Sterzig     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($78.63)
- Divide that value by the 5th highest value among all rosters ($158,437.64)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
