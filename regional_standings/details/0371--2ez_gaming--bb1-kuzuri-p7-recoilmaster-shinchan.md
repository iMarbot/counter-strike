### Roster Details<br />
Team Name: 2ez Gaming<br />
Roster: bb1, Kuzuri, p7, Recoilmaster, ShinChAn<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [371](../standings_global.md)<br />
Regional Rank: [58]( ../standings_asia.md)<br />
Final Rank Value:  586.8<br />
<br />
Final Rank Value (586.8) = Starting Rank Value (620.3) + Head To Head Adjustments (-33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 620.3
- 400 + ( ( 0.108 - 0.000 ) / ( 0.786 - 0.000 ) ) * 1600 = 620.3


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
|           21 |     2915 | 2024-04-16 | LYG Gaming      | L   | 0.909      | -            | -                | -                | -         |    -8.09 | bb1, Kuzuri, p7, Recoilmaster, ShinChAn  |
|           20 |     3750 | 2024-03-28 | Crescent        | L   | 0.783      | -            | -                | -                | -         |   -15.94 | bb1, Kuzuri, p7, Recoilmaster, ShinChAn  |
|           19 |     3754 | 2024-03-28 | Carnival Gaming | L   | 0.782      | -            | -                | -                | -         |   -12.42 | bb1, Kuzuri, p7, Recoilmaster, ShinChAn  |
|           18 |     5108 | 2024-03-03 | True Rippers    | L   | 0.615      | -            | -                | -                | -         |    -6.16 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           17 |     5191 | 2024-03-02 | RETALIATION     | W   | 0.610      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.17 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           16 |     5206 | 2024-03-02 | Marcos Gaming   | L   | 0.609      | -            | -                | -                | -         |    -8.51 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           15 |     5470 | 2024-02-24 | Gods Reign      | L   | 0.568      | -            | -                | -                | -         |    -3.50 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           14 |     5726 | 2024-02-21 | LOT Gaming      | W   | 0.543      | 0.143        | 0.000 (0.000)    | 0.014 (0.001)    | 0 (0.000) |     5.76 | bb1, iFRAGEZ, p7, Recoilmaster, ShinChAn |
|           13 |     5841 | 2024-02-19 | Marcos Gaming   | W   | 0.530      | 0.143        | 0.001 (0.000)    | 0.091 (0.007)    | 0 (0.000) |     9.46 | bb1, iFRAGEZ, p7, Recoilmaster, ShinChAn |
|           12 |     6637 | 2024-02-02 | Enigma Gaming   | W   | 0.416      | 0.143        | 0.004 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     7.51 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           11 |     6692 | 2024-02-01 | Gods Reign      | W   | 0.409      | 0.143        | 0.004 (0.000)    | 0.105 (0.006)    | 0 (0.000) |     8.14 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|           10 |     6733 | 2024-01-31 | Gods Reign      | L   | 0.403      | -            | -                | -                | -         |    -2.00 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            9 |     6838 | 2024-01-29 | True Rippers    | L   | 0.389      | -            | -                | -                | -         |    -3.46 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            8 |     6971 | 2024-01-27 | Firedup Gaming  | L   | 0.377      | -            | -                | -                | -         |    -6.32 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            7 |     7363 | 2024-01-20 | DEWA United     | L   | 0.329      | -            | -                | -                | -         |    -3.83 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            6 |     7369 | 2024-01-20 | RESILIENCE      | W   | 0.328      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.27 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            5 |     7422 | 2024-01-19 | SR Nacague      | L   | 0.322      | -            | -                | -                | -         |    -6.85 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            4 |     7575 | 2024-01-17 | Troublemakers   | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.087 (0.004)    | 0 (0.000) |     5.47 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            3 |     7580 | 2024-01-17 | RESILIENCE      | W   | 0.310      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     2.24 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            2 |     7587 | 2024-01-17 | DEWA United     | L   | 0.309      | -            | -                | -                | -         |    -3.59 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |
|            1 |     7604 | 2024-01-17 | Little Boy's    | W   | 0.308      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.18 | bb1, IFRAGEZ, p7, RecoilMaster, ShinChAn |

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
