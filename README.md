# FPL-Defence-Rotations

## Created for Fantasy Premier League 2020-21

Built on the philosophy of selecting attackers based on their form, and defenders based on their fixtures, FPL Defence Rotations is a tool which gives you the best options to rotate your defenders from in Fantasy Premier League according to favourable oppositions who play comparatively less attacking football than the rest of the clubs. 

#### Please join the [Slack Workspace](https://join.slack.com/t/fpldefencerotations/shared_invite/zt-k328w2ts-Vgw1c08pELUV6d7LKDZc8A) for better discussion on the project, football, and FPL.

Note: This project is different from [FPL Predictor](https://github.com/priyanshux/FPL-Predictor).

[Here](https://docs.google.com/spreadsheets/d/1blJu2sBmwoUA1Npiek3zm4vnPg7pBfS4KFraI2EdGQo/edit?usp=sharing) is the worksheet of all the compiled final results. The same results in CSV format can be found [here](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/).

## Updates, Issues and To-Do

1. The Fixture Difficulty Ratings concept was prepared prior to the start of this extraordinary season and is outdated.
2. The data fetched is till Gameweek 15.
3. Feature Request: Let managers choose their own Fixture Difficulty Ratings.
4. Feature Request: Take the Starting GW and Ending GW as input from the user and display the result.
5. Feature Request: Team Combos currently include all twenty clubs as default. Give the manager an option to select specific clubs as input and then prepare the corresponding combinations.
6. Enhancement: Write a script for combining the combinations CSV with the final results CSV.
6. Feature Request: Create a frontend dashboard to display the above mentioned features.
7. Enjoy the 2020-21 season :)

## Table of Contents

1. [Best Way To Use This Repo](https://github.com/priyanshux/FPL-Defence-Rotations#best-way-to-use-this-repo)

2. [Rotation Options Available](https://github.com/priyanshux/FPL-Defence-Rotations#rotation-options-available)

3. [Fixture Difficulty Ratings and FAQ](https://github.com/priyanshux/FPL-Defence-Rotations#fixture-difficulty-ratings-concept-for-defenders)

4. [Final Results](https://github.com/priyanshux/FPL-Defence-Rotations#final-results)

5. [Some Good Options](https://github.com/priyanshux/FPL-Defence-Rotations#some-good-options)

## Best Way To Use This Repo

1. Don't rely just on 'some' good options given below in the tables, I would recommend you to go through all the possible options in the final result for each case.

2. Pick one/two defenders you HAVE TO get, in most cases (including mine), it's just one - TAA.

3. For the remaining cases, think of another solid option you feel would be perfect to have in the team. Even though not as crucial as TAA, it was Vinagre in my case.

4. Now search for options including the word 'WOL'.

5. Don't stick to choices in the first 20 rows. A good combination would be having an 'Average per team' less than or around 2.1-2.2 and a Standard Deviation less than 1.

<sup>[Back To Top](https://github.com/priyanshux/FPL-Defence-Rotations#fpl-defence-rotations)</sup>


## Rotation Options Available:

1. Rotate 5 players, start 4 of them and keep 1 on the bench.

2. Rotate 5 players, start 3 of them and keep 2 on the bench.

3. Rotate 4 players, start 3 of them and keep 1 on the bench.

4. Rotate 4 players, start 2 of them and keep 2 on the bench.

5. Rotate 3 players, start 2 of them and keep 1 on the bench.

6. Rotate 3 players, start 1 of them and keep 2 on the bench.

7. Rotate 2 players, start 1 of them and keep 1 on the bench.


<sup>[Back To Top](https://github.com/priyanshux/FPL-Defence-Rotations#fpl-defence-rotations)</sup>


## Fixture Difficulty Ratings Concept For Defenders

Please note that this FDR Concept is specifically for defenders, so don't confuse or assume it to be an overall FDR. Difficulty against teams like SHU is considered to be pretty low since they don't score many goals (they scored 5th least number of goals last season, less than BOU who got relegated).

### Initial FDR 'Against' Using Attack Record (Ascending)

(Eg; Playing against FUL away from your home has 1.5 FDR. i.e Fulham plays on their home)

|Category 1    |Category 2    |Category 3    |Category 4    |Category 5    |Category 6    |Category 7    |
|:------------:|:------------:|:------------:|:------------:|:------------:|:------------:|:------------:|
|H - 1, A - 1.5|H - 1.5, A - 2|H - 2, A - 2.5|H - 2.5, A - 3|H - 3, A - 3.5|H - 3.5, A - 4|H - 4.5, A - 5|
|FUL           |LEE           |BUR           |WHU           |WOL           |CHE           |LIV           |
|CRY           |NEW           |EVE           |SOU           |ARS           |MUN           |MCI           |
|WBA           |SHU           |-             |-             |TOT           |-             |-             |
|-             |BHA           |-             |-             |LEI           |-             |-             |
|-             |AVL           |-             |-             |-             |-             |-             |


### Post Initial FDR 'For' Using Defence Record (Descending)

|Category A    |Category B    |Category C    |Category D    |
|:------------:|:------------:|:------------:|:------------:|
|LIV           |MUN           |ARS           |EVE           |
|MCI           |SHU           |TOT           |NEW           |
|-             |WOL           |BUR           |WHU           |
|-             |LEI           |BHA           |AVL           |
|-             |LEE           |SOU           |WBA           |
|-             |CHE           |CRY           |FUL           |

### Cases For Good Defence vs Poor Attack

|              |              |              |
|--------------|--------------|--------------|
|Category A    |-0.2 against category 1, 2, 3, 4|-0.1 against category 5|
|Category B    |-0.2 against category 1, 2, 3	|-      		        |
|Category C    |-0.1 against category 1, 2, 3	|+0.1 against category 6|
|Category D    |+0.1 against category 5			|+0.2 against category 6|

#### The final ratings till Gameweek 38 can be found [here](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/FPL_Defence_FDR.csv "Difficulty Ratings for Defenders").

<sup>[Back To Top](https://github.com/priyanshux/FPL-Defence-Rotations#fpl-defence-rotations)</sup>

### Frequently Asked Questions (FAQs)

#### 1. What do these numbers on ratings display?
The difficulty level to get a clean sheet in the specific match. It doesn't necessarily mean to tell you a lot about the overall defence of a team. The chances of these ratings increasing drastically would be much higher in the case of conceding 1 goal from no goals (costs you 4 points), when compared to the case of conceding 5 goals from 1 goals (costs you 2 points).

#### 2. Does it mean it doesn't consider the attacking returns?
Honestly, no. Since attacking returns can be very player specific (For eg; Joe Gomez won't get as many returns as TAA) and even though Liverpool defenders have a greater probability of gaining more points than Fulham's, it is tough to allot them into numbers. More so since you rarely rotate defenders using their attacking returns.

#### 3. For Category C and D, why haven't you considered an increment for Category 7?
Notice the difference in each case from Category 1 to 6, there's a 0.5 change for their Home/Away fixtures respectively. But in the case of Category 6 to 7, the difference is 1. And anyhow it wouldn't matter much since you'd always like to keep a defender on the bench when playing against LIV or MCI.

#### 4. How do you justify Fulham's difficulty level against Chelsea at home (3.7) with Liverpool's difficulty level against Chelsea away (4.0)? Won't it be much more difficult for Fulham?
The last part of Answer 1 answers this as well. Adding to that, if you go through the code of this repo, you'll find what this model does is sort the ratings of the combination in ascending order before discarding the higher ratings. And hence, I have focused more on the ratings < 3.5 since any rating higher than 3.5 would irrespective of the team be shifted to the bench and let the teams with lower ratings play in the starting 11. As long as you stick to the ratings in the upper half on the results (which I strongly recommend), you wouldn't see any 3.5+ being considered in most cases.

#### 5. The Google Sheets attached is confusing me, how am I supposed to read it?
There are a total of 14 sheets attached inside the worksheet, which you should be able to navigate through from the bottom left icon in [Google Sheets](https://docs.google.com/spreadsheets/d/1blJu2sBmwoUA1Npiek3zm4vnPg7pBfS4KFraI2EdGQo/edit?usp=sharing). The names are assigned in the format of GWxx_y_z where xx denotes until which GW, y denotes the number of players you wish to rotate and z denotes the number of players in your starting 11. For eg; GW15_4_3 denotes the list of GW1-15 for rotating 4 players where 3 of them start in the playing 11.

#### 6. Will you be creating such combinations during mid-season as well? If yes, will you update the ratings based on their then form?
Yes, I plan on doing this twice more before the season ends along with an updated difficulty ratings sheet.

<sup>[Back To Top](https://github.com/priyanshux/FPL-Defence-Rotations#fpl-defence-rotations)</sup>


## Final Results

[Here](https://docs.google.com/spreadsheets/d/1blJu2sBmwoUA1Npiek3zm4vnPg7pBfS4KFraI2EdGQo/edit?usp=sharing) is the worksheet of all the compiled final results. The same results in CSV format can be found [here](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/).

### Results for all the possible cases



1. [Rotation of 5 teams for 4 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_5_4.csv)

2. [Rotation of 5 teams for 3 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_5_3.csv)

3. [Rotation of 4 teams for 3 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_4_3.csv)

4. [Rotation of 4 teams for 2 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_4_2.csv)

5. [Rotation of 3 teams for 2 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_3_2.csv)

6. [Rotation of 3 teams for 1 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_3_1.csv)

7. [Rotation of 2 teams for 1 in playing XI - Gameweek 1-10](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW10_2_1.csv)

8. [Rotation of 5 teams for 4 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_5_4.csv)

9. [Rotation of 5 teams for 3 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_5_3.csv)

10. [Rotation of 4 teams for 3 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_4_3.csv)

11. [Rotation of 4 teams for 2 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_4_2.csv)

12. [Rotation of 3 teams for 2 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_3_2.csv)

13. [Rotation of 3 teams for 1 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_3_1.csv)

14. [Rotation of 2 teams for 1 in playing XI - Gameweek 1-15](https://github.com/priyanshux/FPL-Defence-Rotations/blob/master/Results/GW15_2_1.csv)

<sup>[Back To Top](https://github.com/priyanshux/FPL-Defence-Rotations#fpl-defence-rotations)</sup>


## Some Good Options

### Rotate defenders in GW 1-10

|5 Teams, 4 Starting|5 Teams, 3 Starting|4 Teams, 3 Starting|4 Teams, 2 Starting|3 Teams, 2 Starting|3 Teams, 1 Starting|2 Teams, 1 Starting|
|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|
|CHE,FUL,LEE,LEI,LIV|BHA,CHE,EVE,LEI,TOT|CRY,MUN,NEW,WOL    |ARS,CRY,EVE,WOL    |MUN,SOU,WBA        |CRY,EVE,LEI        |CRY,EVE            |
|CRY,LIV,MUN,NEW,SOU|CRY,MUN,SHU,SOU,WOL|CRY,LEI,MUN,SOU    |BHA,CHE,LEI,TOT    |CHE,FUL,LEI        |AVL,SOU,WBA        |CRY,NEW            |
|CHE,FUL,LIV,MUN,NEW|CRY,EVE,LIV,MUN,TOT|ARS,LEE,SHU,WOL    |CRY,MCI,MUN,SOU    |CRY,MUN,SOU        |AVL,LEI,SOU        |SHU,SOU            |
|BUR,CRY,EVE,LEI,SOU|AVL,BUR,LEI,LIV,TOT|ARS,MCI,SHU,TOT    |CRY,LEI,MUN,WOL    |BHA,CHE,LEI        |BHA,EVE,SOU        |LEE,WOL            |
|CRY,MUN,NEW,SOU,WOL|AVL,BHA,CHE,LEI,MCI|BHA,CHE,EVE,LEI    |BHA,CHE,LEE,LEI    |AVL,SHU,SOU        |EVE,WHU,WOL        |FUL,LEI            |
|FUL,LEI,LIV,MUN,SOU|CHE,CRY,MUN,SOU,WBA|BHA,EVE,LEI,SOU    |BUR,LEE,LEI,WOL    |CHE,LEE,WBA        |BHA,EVE,WHU        |LEE,LEI            |
|CRY,EVE,LIV,MUN,SOU|ARS,BHA,EVE,LEI,TOT|LEE,SHU,SOU,WOL*   |LEI,MUN,TOT,WOL    |BUR,FUL,LEI        |ARS,FUL,SHU        |BUR,LEI            |
|ARS,CRY,MUN,NEW,WOL|LIV,MUN,SHU,SOU,TOT|BHA,CHE,LEE,LEI    |BHA,EVE,LEI,SOU    |ARS,AVL,WBA        |ARS,FUL,NEW        |CRY,WBA            |
|CHE,LIV,MUN,TOT,WBA|CRY,EVE,LIV,MUN,SOU|BUR,EVE,LEI,SOU    |LEE,LEI,MUN,WOL    |CRY,EVE,SOU        |EVE,SOU,WBA        |BUR,WBA            |

### Rotate defenders in GW 1-15

|5 Teams, 4 Starting|5 Teams, 3 Starting|4 Teams, 3 Starting|4 Teams, 2 Starting|3 Teams, 2 Starting|3 Teams, 1 Starting|2 Teams, 1 Starting|
|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|-------------------|
|ARS,LIV,MCI,MUN,TOT|AVL,BHA,CHE,LEI,SOU|ARS,MCI,SHU,TOT    |AVL,LEI,MUN,SOU    |AVL,CHE,LEI        |ARS,AVL,LEI        |CRY,NEW            |
|AVL,LEI,LIV,MUN,SOU|CHE,FUL,LEE,LEI,LIV|CRY,MUN,NEW,SOU    |ARS,CRY,FUL,NEW    |CRY,MUN,WOL        |AVL,CRY,SOU        |AVL,LEI            |
|CHE,FUL,LEE,LEI,LIV|CRY,FUL,LEI,MUN,SOU|CHE,FUL,LEI,LIV    |CRY,MUN,NEW,SOU    |EVE,WBA,WHU        |AVL,CHE,LEI        |MUN,SOU            |
|AVL,CHE,LEE,LEI,LIV|BHA,CHE,EVE,LEI,LIV|BHA,EVE,LEI,SOU    |CHE,FUL,LEI,LIV    |BUR,FUL,LEI        |BHA,EVE,SOU        |BUR,WBA            |
|BUR,FUL,NEW,SHU,SOU|CHE,FUL,LEE,LIV,WBA|CHE,LEE,LEI,LIV    |ARS,AVL,LEI,TOT    |CHE,FUL,LEI        |BHA,CRY,SOU        |FUL,LEI            |
|BHA,CHE,LEE,LEI,LIV|ARS,BHA,MCI,SHU,TOT|LIV,MCI,MUN,TOT    |LEI,LIV,MUN,SOU    |CRY,MUN,SOU        |AVL,BUR,LEI        |FUL,SOU            |
|CRY,LIV,MUN,NEW,SOU|AVL,BHA,CHE,LEI,LIV|CHE,CRY,FUL,NEW    |CHE,FUL,LEE,LEI    |FUL,SHU,SOU        |CRY,FUL,SOU        |SHU,SOU            |
|ARS,BHA,MCI,SHU,TOT|MCI,MUN,SHU,SOU,TOT|ARS,FUL,SHU,SOU    |BHA,LEI,MUN,SOU    |CRY,EVE,NEW        |BHA,SHU,SOU        |BHA,SOU            |
|CHE,LEE,LEI,LIV,MUN|BUR,CHE,FUL,LEI,LIV|CRY,MUN,NEW,WOL    |CRY,MUN,WHU,WOL    |AVL,SHU,SOU        |BHA,EVE,LEI        |CRY,LEI            |


<sup>[Back To Top](https://github.com/priyanshux/FPL-Defence-Rotations#fpl-defence-rotations)</sup>


#### Footer

Feel free to contribute to this repo, or give any suggestions. Hope it helps your FPL season, good luck.
