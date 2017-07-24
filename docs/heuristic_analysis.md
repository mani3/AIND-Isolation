# Heuristic Analysis

## Custom Score

|               | Description                            |
|---------------|----------------------------------------|
| custom_score  | Use heuristic value opposite Open Move |
| custom_score2 | Multiply a random number (0 ~ 1) and a score to square of the distance from the center of the board to the position of the player.   |
| custom_score3 | Multiply a random number (0 ~ 1) and the number of moves available to the two players. |



## Results

I tried 100 attempts. Using a random number like `custom_store3` rather than a simple An "improved" evaluation function raised the score. 

```
                        *************************
                             Playing Matches
                        *************************

 Match #   Opponent    AB_Improved   AB_Custom   AB_Custom_2  AB_Custom_3
                        Won | Lost   Won | Lost   Won | Lost   Won | Lost
    1       Random      94  |   6    91  |   9    95  |   5    94  |   6
    2       MM_Open     78  |  22    69  |  31    74  |  26    79  |  21
    3      MM_Center    88  |  12    86  |  14    84  |  16    89  |  11
    4     MM_Improved   68  |  32    70  |  30    64  |  36    77  |  23
    5       AB_Open     46  |  54    49  |  51    46  |  54    59  |  41
    6      AB_Center    53  |  47    52  |  48    61  |  39    59  |  41
    7     AB_Improved   47  |  53    40  |  60    52  |  48    50  |  50
--------------------------------------------------------------------------
           Win Rate:      67.7%        65.3%        68.0%        72.4%
```


