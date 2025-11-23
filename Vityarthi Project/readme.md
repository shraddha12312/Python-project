<<<<<<< MindTrack-CLI >>>>>>>
#Overview
MindTrack is a beginner-friendly Python project designed to help users track their emotional wellbeing through simple terminal-based interactions.
Users can write journal entries, log their daily mood, receive positive affirmations, and take a short stress-level questionnaire.
All data is stored locally in .txt and .csv files, making it lightweight and easy to run without installing external libraries.

#Features
It allows our users to:
-write and store their thoughts in journal
-log their moods to track
-get random positive affirmations whenever they need it
-take a simple quiz to determine their stress levels
Fully CLI based-works directly in terminal

#Technologies/tools used
python 3.13 for programming
.txt,.csv for data storage
random module for affirmations
datetime module for time tracking

#Steps to install and run the project
1.Download or clone the project
2.Ensure python is installed
3.Run the program
4.Follow the onscreen instructions

#Instructions for testing
   TEST                           ! EXPECTED OUTPUT
   Write a journal entry          ! Entry saved to journal.txt with date
   Viewing journal entries        ! Displays previously saved entries
   Log a mood                     ! New record added to mood.csv
   View mod logs                  ! Shows saved CSV entries 
   Get affirmations               ! Prints random positive message
   Take stress test               ! Outputs score and score category
