# Test Case 1 

## Test Details

* Test Case ID:
  * 1
* Test Case Name:
  * 3.4 Load Game Requirements
* Component: 
  * Story mode
* Test Case Designer:
  * Arthur and Kiath
* Creation Date:
  * October 9, 2018
* Modified By:
  * Arthur and Kiath
* Modified Date:
  * October 16, 2018
* Requirements Covered:
  * Only Works in story mode.
* Test Description/Purpose:
  * Game data in online mode is loaded from the database.
* Pre-Test Conditions:
  * Go into Story mode to see if the user can load the last saved game file.

## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 |Start up the game to make sure the game starts up with story mode.|The game started in story mode to start new game was a success.|√|			
| 2 |Start new game by picking one of the six characters that all have different puzzles to beat in order to complete the game.|Started a new game with one of the six characters revealing their path to complete the game.|√|			
| 3 |Play through one level in story mode and perform a successful save.|After playing through one level saving the current progress was successful.|√|			
| 4 |Join an online multiplayer server to try to load the saved game file from story mode.|After joining an online multiplayer server the game data in online mode is loaded from the database.|√|			
| 5 |Start story mode back up and play through another level to preform an overwrite saved game file over the first one.|Played through another level in story mode and created a new saved game file.|√|			
| 6 |Join back on another online multiplayer server to see if saved data loads.|This time in online multiplayer the game data didn't load from the database.|√|						

## Overall Test Status: 
While playing "PLEX" multiplayer online mode I came across game data loading from the database that should only be loaded in story mode. First, I started up story mode, choose a charatcer to run through one level, and created a saved game file. Next, I had joined the PLEX multiplayer online mode and the game data had loaded from the database. Based on the specification requirements this test had failed. In result, I went back to story mode to run through another level and create a new saved game file to overwrite the first. In addition, I started the online multiplayer mode back up and this time the game data didn't load from the database. To conculde, the first saved game file must of been a bug or glitch that caused the test to fail.   

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 | 10/9/2018 | 10/9/2018 | Success |			
| 2 | 10/10/2018 | 10/10/2018 | Success |			
| 3 | 10/11/2018 | 10/11/2018 | Success |
| 4 | 10/12/2018 | 10/12/2018 | Failed |
| 5 | 10/14/2018 | 10/14/2018 | Success |
| 6 | 10/16/2018 | 10/16/2018 | Success |
