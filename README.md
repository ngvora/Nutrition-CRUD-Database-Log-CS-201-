# Nutrition Diary CS 201 Portfolio Project - Nehal Vora

# What it is

Nutrition Diary Food Tracker is an application that allows you to create specific user diaries and search a food item to input from the FDA food database into your diary. It allows you to edit and update an existing user diary and gives you to option to add or delete food items from that file. It also keeps track of all the user diaries in the diary_list.txt file.

# Files to Download 

FDA Food Database File to be read by the program can be downloaded using this link. 
https://drive.google.com/file/d/1CU04kfc18ld8KZqVt0BeBIXa0aTGnjQ6/view?usp=sharing

# How to use
Video Demo Link:
In your terminal, change the directory to the folder the program is in and input the following command:
gcc -Wall string.c dynamic.c UNORDEREDSET.c UNORDEREDMAP.c main2.c ROW.c -g3

The program will present you with the following options:
1) Open a new diary (open <diaryname>)
 To execute this command, input "open" followed by the name of the diary you are trying to create.
 For example, to open a diary named Nehal I would enter the command "open Nehal".
 
 You will now enter into a menu for the diary file:
 a)Insert (insert <name|vendor|keyword> <key>)
 To add a new food into the diary, enter "insert" followed by "<name|vendor|keyword> <key>" where name stands for the exact food name, vendor stands for the manufacturer name and keyword is for a general item you want to search for using a key.
 Once you have the search results displayed, select the item you want to be inserted into your food diary.
 b) Delete (delete)
 To delete a food from the diary, enter "delete" followed by "<name|vendor|keyword> <key>" where name stands for the exact food name, vendor stands for the manufacturer name and keyword is for a general item you want to delete for using a key.
  This will delete the food item that matches your query.
 c) Print (print)
 To print the user nutrition diary, enter "print".
 d) Quit (quit)
 Enter "quit" to exit the menu.
 
2) Update an existing diary (update <diaryname>)
 Use this command to open and update a diary that has already been created. To execute this command, input "update" followed by the name    of the diary you want to update.
 For example, to update the diary Nehal input "update Nehal".
  
  You will now enter into a menu for the diary file:
 a)Insert (insert <name|vendor|keyword> <key>)
 To add a new food into the diary, enter "insert" followed by "<name|vendor|keyword> <key>" where name stands for the exact food name, vendor stands for the manufacturer name and keyword is for a general item you want to search for using a key.
 Once you have the search results displayed, select the item you want to be inserted into your food diary.
 b) Delete (delete)
 To delete a food from the diary, enter "delete" followed by "<name|vendor|keyword> <key>" where name stands for the exact food name, vendor stands for the manufacturer name and keyword is for a general item you want to delete for using a key.
  This will delete the food item that matches your query.
 c) Print (print)
 To print the user nutrition diary, enter "print".
 d) Quit (quit)
 Enter "quit" to exit the menu.
  
3) Delete Diary (delete <diaryname>)
 Use this command to delete a diary that has already been created. To execute this command, input "delete" followed by the name of the diary you want to delete.
 For example, to delete the diary Nehal input "delete Nehal".
 
4) View all the diaries stored in the system (view list)
This command will show you all the diaries currently in the system and will help you keep track of them.
To execute this command, enter the following input "view list".
 
# Additional Notes
This program uses hashtables and dynammic arrays to load the database in. It has an average search time of O(logn).
