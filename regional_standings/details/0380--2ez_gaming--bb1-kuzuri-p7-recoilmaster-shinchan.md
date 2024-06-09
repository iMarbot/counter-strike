### Roster Details<br />
Team Name: 2ez Gaming<br />
Roster: bb1, Kuzuri, p7, Recoilmaster, ShinChAn<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [380](../standings_global.md)<br />
Regional Rank: [59]( ../standings_asia.md)<br />
Final Rank Value:  585.9<br />
<br />
Final Rank Value (585.9) = Starting Rank Value (619.9) + Head To Head Adjustments (-34.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 619.9
- 400 + ( ( 0.108 - 0.000 ) / ( 0.787 - 0.000 ) ) * 1600 = 619.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |     2976 | 2024-04-16 | LYG Gaming      | L   | 0.909      | -            | -                | -                | -         |    -8.17 | bb1, Kuzuri, p7, Recoilmaster, ShinChAn  |
|           20 |     3843 | 2024-03-28 | Crescent        | L   | 0.783      | -            | -                | -                | -         |   -15.92 | bb1, Kuzuri, p7, Recoilmaster, ShinChAn  |
|           19 |     3847 | 2024-03-28 | Carnival Gaming | L   | 0.782      | -            | -                | -                | -         |   -12.41 | bb1, Kuzuri, p7, Recoilmaster, ShinChAn  |
|           18 |     5256 | 2024-03-03 | True Rippers    | L   | 0.615      | -            | -                | -                | -         |    -6.15 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           17 |     5339 | 2024-03-02 | RETALIATION     | W   | 0.610      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.18 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           16 |     5355 | 2024-03-02 | Marcos Gaming   | L   | 0.609      | -            | -                | -                | -         |    -8.50 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           15 |     5628 | 2024-02-24 | Gods Reign      | L   | 0.568      | -            | -                | -                | -         |    -3.98 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           14 |     5890 | 2024-02-21 | LOT Gaming      | W   | 0.543      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     5.77 | bb1, iFRAGEZ, p7, Recoilmaster, ShinChAn |
|           13 |     6013 | 2024-02-19 | Marcos Gaming   | W   | 0.530      | 0.143        | 0.001 (0.000)    | 0.091 (0.007)    | 0 (0.000) |     9.46 | bb1, iFRAGEZ, p7, Recoilmaster, ShinChAn |
|           12 |     6842 | 2024-02-02 | Enigma Gaming   | W   | 0.416      | 0.143        | 0.004 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     7.51 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           11 |     6901 | 2024-02-01 | Gods Reign      | W   | 0.409      | 0.143        | 0.004 (0.000)    | 0.105 (0.006)    | 0 (0.000) |     8.14 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           10 |     6946 | 2024-01-31 | Gods Reign      | L   | 0.403      | -            | -                | -                | -         |    -2.01 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            9 |     7054 | 2024-01-29 | True Rippers    | L   | 0.389      | -            | -                | -                | -         |    -3.46 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            8 |     7191 | 2024-01-27 | Firedup Gaming  | L   | 0.377      | -            | -                | -                | -         |    -6.32 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            7 |     7607 | 2024-01-20 | DEWA United     | L   | 0.329      | -            | -                | -                | -         |    -3.88 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            6 |     7613 | 2024-01-20 | RESILIENCE      | W   | 0.328      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.28 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            5 |     7669 | 2024-01-19 | SR Nacague      | L   | 0.322      | -            | -                | -                | -         |    -6.85 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            4 |     7824 | 2024-01-17 | Troublemakers   | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.087 (0.004)    | 0 (0.000) |     5.46 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            3 |     7829 | 2024-01-17 | RESILIENCE      | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.24 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            2 |     7836 | 2024-01-17 | DEWA United     | L   | 0.309      | -            | -                | -                | -         |    -3.64 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            1 |     7853 | 2024-01-17 | Little Boy's    | W   | 0.308      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.19 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($196.47)
- Divide that value by the 5th highest value among all rosters ($300,806.11)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
