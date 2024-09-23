# North American Word Chain
## Introduction
The Word Chain Geography Game is a software application designed to enhance users' knowledge of North America's states and their capital cities through an engaging word chain game. Players are required to form chains of words where each word begins with the last letter of the previous word, using only the names of North America's states/provinces and their corresponsing capital cities

## Creators
Simran Kaur Kullar, 
Hailey Pong, 
Maneet Kaur Chahal, 
Kareena Sen, 
Victor Yung Wai Tan

## Installation Instructions
To install the Word Chain Game, follow these steps:
1. Have JDK downloaded on your device. If you don't have one, install through Oracle: https://www.oracle.com/ca-en/java/technologies/downloads/
2. Download WorldChain.JAR file. It has to be in your default directory (documents, downloads etc).
3. Go to your device's terminal
   ![image](https://github.com/user-attachments/assets/def0b61b-c1fb-41c9-9bb5-2d82de2bf77a)
(You can search on your computer.)
3. Move to the directory where WorldChain.jar is located in using the command: cd "Your File Location". If you have created a folder inside of your directory, then make sure you cd "File Location" until you are in the directory. You can type in ls to see the content of the file.
4. IMPORTANT: Make sure facts.csv and your WorldChain.JAR file is in the same folder! It will not load the data and you won't be able to play the game. If you want background music, make sure the WAV files are in the same directory as well.
5. Type command: java -jar WroldChain.jar
   ![image](https://github.com/user-attachments/assets/7ed61bad-0d74-4a39-8d05-b9c083400f77)
   (Eg. My WorldChain.jar was in downloads file so "cd downloads". You can see I am in the downloads folder."
   5. Application should open 
![image](https://github.com/user-attachments/assets/5a9d0069-8b6b-487a-b10a-9fa21c1e7db5)
Note that I have WorldChain.JAR and facts.csv on the same file.

## Required Libraries and Third Party Tools
• JDK 22

## User Guide
1. Upon opening the software, you will be greeted with a login page.
2. For players, login with your user ID, if you don't have an account, create an account and sign in.
3. To play the game, simply click on the "Start Game" button from the main menu and choose your level. However, you have ti unlock the level in order to play the harder mode. In the game, input a US state or capital city that starts with the last letter of the previous word.
4. Continue forming word chains until you successfully complete the lvel or decide to end the game,
5. Enjoy and learn about US geography while playing!
6. Bonus: If you get 0 wrong answers and complete the stage, you get a medal!

## Writing High Scores into CSV files
• There are three CSV files: highScoresEasy.csv, highScoresMedium.csv, and highScoresHard.java, and to **download** the files:
    • User must navigate to the leaderboard and 
         • press the * *"Easy"* * button to download the highScoresEasy.csv 
         • press the * *"Medium* * button to download the highScoresMedium.csv
         • press the * *"Hard"* * button to download the highScoresHard.csv
         • but whatever current level (easy, medium, or hard) user navigated through on the leaderboard, will download that csv high scores of the leaderboard of that level by default

## Game Mechanics and Rules
• The game is case sensitive: ensure the first letter of each word is capitalized
• Lives vary by difficulty: 7 lives in Easy, 5 in Normal, and 3 in Hard
• Incorrect answers result in the loss of a life. the Game ends when all lives are lost
• Achievements are unlocked at 100 points: Bronze for Easy, Silver for Medium, and Gold for Hard
• Correct answers result in gaining points: 6 points for Easy, 4 points for Normal, 2 for Hard

## Instructor Mode
• Upon opening the software, you will be greeted with a login page
• To access the instructor mode, click on the "Instructor Dashboard" button
• Enter the instructor;s pin (4351) when prompted
• You will be directed to the isntructor dashboard, where you can access additional features such as tracking student progress

## Debugging Mode
• ID = admin@2398!
• PIN = 2024WINTERTERM
• Enter the pin on login page. It will lead to protected page where you have to enter the PIN to identify you are an admin
• You are set to have reached the end game, which means you can jump from levels to levels and test the game

## Game Mechanices and RUles:
• Rules
    • Our game is case sensitive: ensure the first letter of each word is capitalized
    • Step 1
         • Choose your level. You have to complete the previous level in order to play the next level
    • Step 2
         • Type in your answer and enter to submit. You will lose a life(heart) if your answer is wrong
    • Step 3
         • Reach 100 points to complete a level

• Lives and Difficulty levels
    • In easy mode, players start with 7 lives. For a slightly tougher challenge, normal mode can be unlocked in easy is completed, hard is unlocked if normal is completed
    • Players lose a life each time an incorrect answer in entered. The game ends when players run out of lives

## Scoring and Achievements
    • Accumulate points with each correct

