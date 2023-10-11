### Welcome to the Pumpkin BOMB challenge

In this challenge you are trying to estimate the number of elastic bands it takes to **IMPLODE** four different pumpkins. We will be using size 64 (3.5 inch by 0.25 inch) elastic bands on implosion day. The features for all of our historical data is listed below: 

| #   | Year | Name    | Width_cm | Height_cm | Circumference_cm | Mass_g | State | Elastics | Elastic Size |
| --- | ---- | ------- | -------- | --------- | ---------------- | ------ | ----- | -------- | ------------ |
| 1   | 2021 | 20211   | 11.5     | 9         | 36.5             | 600    | 1     | 247      | 64           |
| 2   | 2021 | 20212   | 14.5     | 12        | 49               | 1400   | 1     | 373      | 64           |
| 3   | 2021 | 20213   | 19.5     | 16.5      | 61               | 2100   | 0.4   | 68       | 64           |
| 4   | 2021 | 20214   | 19.5     | 23        | 59.5             | 3400   | 1     | 239      | 64           |
| 5   | 2021 | 20215   | 20       | 22.5      | 65               | 4025   | 1     | 285      | 64           |
| 6   | 2021 | 20216   | 24       | 21.5      | 80               | 4575   | 1     | 214      | 64           |
| 7   | 2021 | 20217   | 27.5     | 25.5      | 86               | 4500   | 1     | 174      | 64           |
| 8   | 2021 | 20218   | 30       | 26.5      | 91.5             | 6000   | 0.8   | 184      | 64           |
| 9   | 2021 | 20219   | 29       | 25.5      | 90               | 6000   | 1     | 231      | 64           |
| 10  | 2021 | 202110  | 29.5     | 25        | 90               | 5500   | 1     | 189      | 64           |
| 11  | 2022 | 20221   | 25       | 20.5      | 79               | 3350   | 0.9   | 85       | 63           |
| 12  | 2022 | 20228   | 22.5     | 25        | 73.5             | 3600   | 0.7   | 78       | 63           |
| 13  | 2022 | 20225   | 22.5     | 21        | 75.5             | 3200   | 0.5   | 52       | 63           |
| 14  | 2022 | 2022A1  | 26       | 20.5      | 78.5             | 3885   | 0.95  | 152      | 63           |
| 15  | 2022 | 2022A3  | 21.5     | 20.5      | 63.5             | 2450   | 0.6   | 69       | 63           |
| 16  | 2022 | 2022A4  | 23.5     | 23.5      | 75.5             | 3850   |       | 85       | 63           |
| 17  | 2022 | 2022A5  | 25.5     | 21        | 83               | 4100   | 0.6   | 95       | 63           |
| 18  | 2022 | 2022A6  | 28       | 23        | 86               | 5000   | 1     | 203      | 63           |
| 19  | 2022 | 2022A9  | 30       | 24        | 98.5             | 6100   | 0.9   | 116      | 64           |
| 20  | 2022 | 2022B4  | 25       | 21        | 78               | 3950   | 1     | 139      | 64           |
| 21  | 2022 | 2022B8  | 28       | 22        | 91.5             | 5000   | 1     | 109      | 64           |
| 22  | 2022 | 2022C1  | 24       | 23        | 77.75            | 3200   | 0.4   | 46       | 64           |
| 23  | 2022 | 2022C6  | 24.5     | 18.5      | 80               | 3750   | 1     |         |              |
| 24  | 2022 | 2022C7  | 23.5     | 24        | 81               | 4700   | 0.95  | 136      | 63           |
| 25  | 2022 | 2022ML1 | 12       | 11.5      | 37               | 800    | 1     | 461      | 64           |
| 26  | 2022 | 2022ML2 | 14       | 12.5      | 44               | 1160   | 1     | 303      | 63           |
| 27  | 2022 | 20224   | 24       | 24        | 75.5             | 4200   | 0.8   | 142      | 63           |
| 28  | 2022 | 2022B1  | 27.5     | 24.25     | 82.75            | 4500   |       | 81       | 63           |
| 29  | 2022 | 2022B3  | 29.7     | 26.8      | 97               | 7000   |       | 102      | 63           |
| 30  | 2022 | 2022B5  | 26.4     | 22.3      | 80.3             | 4000   |       | 135      | 63           |
| 31  | 2022 | 2022B7  | 28.3     | 22.4      | 77.3             | 3500   |       | 97       | 63           |
| 32  | 2022 | 2022A8  | 31.2     | 27        | 93.1             | 6000   |       | 113      | 63           |
| 33  | 2022 |         | 29.6     | 24.9      | 81.2             | 4000   |       | 136      | 63           |
| 34  | 2022 | 2022C9  | 28.8     | 20.6      | 77.03            | 3066   |       | 85       | 63           |
| 35  | 2023 | 2023A   |          |           |                  |        |       |          |              |
| 36  | 2023 | 2023B   |          |           |                  |        |       |          |              |
| 37  | 2023 | 2023C   |          |           |                  |        |       |          |              |
| 38  | 2023 | 2023D   |          |           |                  |        |       |          |              |

Each pumpkin has a unique shape and size. Can you tell how big they are? 

We have created <a href="https://drive.google.com/file/d/1YJOabLfp-1xUdJ0rJRpUtZUwLfkyxJCw/view?usp=sharing"> this video </a> to help you understand what this will look like, and to aid in your estimation. Can you figure out the diameter of the pumpkin in the video? 

You will work in teams of 1-4. Each team must be **clearly** identified. If you submit on multiple teams you will be **disqualified**. Submit estimations (and justifications) using <a href="https://docs.google.com/forms/d/e/1FAIpQLScYvUw0pf3RL44HbeIg2dF3PVjdkYKmFR5zs3R9aRcPOPwQOw/viewform?usp=sf_link"> this form</a>.  

There will be prizes awared for the: 
* Closest estimation 
* Best estimation strategy 

GOOD LUCK and **MATH ON!** 

<!--
### RESULTS 
Check out <a href="https://drive.google.com/file/d/14eTkhJX0YxVpIDKtIBcO2I2xVMjszutn/view?usp=sharing"> this video</a>. --> 



