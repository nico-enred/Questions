English translation thanks to(DeepSeek).

========================================= QUESTIONS — Getting Started

WHAT IS THIS?

Questions is a quiz game for the classroom. Teachers prepare the questions (in a file with a CSV extension) and students play
by answering, with a scoreboard, countdown timer and different game modes.

It runs locally, with no internet connection required to play (the connection is only used to check whether a new version exists
and to download it).

GETTING STARTED

Unzip the entire folder wherever you want to keep it (desktop, USB drive, etc.). Do not move or delete any of the folders inside it 
(Images, JSON, etc.): the program needs them to work properly.

Double-click on "Question_version_____.exe" to open the program.

The first time you open it there will be no question categories loaded yet. This is normal: you need to add at least one question 
file before you can play.

ADDING QUESTION CATEGORIES

On the main screen, click "Configuración" (Settings).

Click the button to add categories and select the folder on your computer where you have saved the CSV files with the questions 
(one per category, for example "maths.csv", "geography.csv"...).

The program automatically detects all CSV files in that folder and adds them as new categories (just make sure you have 
selected the correct folder).

Format of each CSV file (one question per line): question (row 1-column 1), correct answer (row 1-column 2), 
distractor answer 2 (row 1-column 3), distractor answer 3 (row 1-column 4), distractor answer 4 (row 1-column 5).

Example:   
What is the capital of France?,Paris,London,Rome,Berlin (one field per cell of the row)
What is 2+2?,4,3,5,6  (one field per cell of the row)
Who painted the Mona Lisa?,Leonardo da Vinci,Picasso,Velázquez,Goya  (one field per cell of the row)

IMPORTANT:

If you use LibreOffice to create the CSV, uncheck the "Tab" box in the initial dialog when opening an existing CSV,
and leave commas marked as separators. If you are creating it from scratch: when saving, use File > Save As > Text CSV, 
check the "Edit filter settings" box, and in the dialog select Comma as the field delimiter (or separator). Uncheck Tab 
(if the option appears).

If you use Excel on Windows:

Make sure the Windows list separator is set to comma (,). It can be changed in Control Panel > Region >
Additional settings > List separator.

When saving, use the "CSV UTF-8 (comma delimited)" option if available.

From that same screen you can also delete categories you no longer want to use.

 Once imported, the CSV files are no longer needed: the game saves its own internal copy of the questions. 
 You can move or delete the original CSV files without affecting the game.

The game is portable. That is, if you copy the folder where the executable is located and paste it on another
computer, all the content you had already loaded (CSV files, Statistics, etc.) travels with that folder.

   

PLAYING A GAME

From the main screen, click "Jugar" (Play).

Choose a colour by clicking the colour button (each click changes it).

Type your name and press Enter.

Select which categories you want to play with (you can select several or all of them, but you must choose at least one,
otherwise there would be no questions to show).

Choose the game mode:

Time limit: it shows the seconds you have to answer. If they run out, the question is counted as failed.

Mistake limit: you can set the maximum number of mistakes you can make. If you exceed it, the game ends.

You can also choose to have no mistake or time limit.

Click "Empezar a jugar" (Start playing) when everything is ready.

DURING THE GAME

You will see the question and four possible answers.

The scoreboard at the top shows your name, correct answers, mistakes, the current category, how many questions you have
answered and the total.

If you chose a mode with a time limit, you will see a countdown timer that changes colour as it runs out.

The game ends automatically when the available questions run out, or when the limit you chose is reached (time or mistakes).
From there you can return to the main menu and play again.

UPDATES

If the computer has an internet connection, the program automatically checks whether a new version exists.

If there is one, you will see a notice next to the Configuración (Settings) button. Click there to see what has changed in 
the new version and decide whether you want to update.

If there is no internet connection, the program works normally for playing; it simply will not be able to check for available updates.

SOMETHING IS NOT WORKING

If the program does not find any categories when you click "Jugar" (Play), go to Configuración (Settings) and add at least one 
CSV question file.

Note: this is my first programming project, so you may find bugs and things that can be improved. Right now I am in
'make it work (first)' mode, and I hope to move on to 'make it nice' mode in a few months.

=========================================
