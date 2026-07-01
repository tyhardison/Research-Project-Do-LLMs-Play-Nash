
Do LLMs Play Nash?
TAMU - Summer 1 - 2026
CSCE 631 - Final Project
By: Tyler Hardison
---------------------------------
---------------------------------

Howdy! In this directory you will find several subfolders.

The main deliverable is:
Tyler_Hardison_Report.pdf


If you wish to view the workbooks used to perform the experiments in this project please see:

Code <
-Final_Project_Part1.ipynb -- ran to collect data from the TAMU API system and export to csv
-Final_Project_Part2.ipynb -- ran to import the csv files and perform data analysis





*************************
****RUNNING THE CODE*****
*************************

**Note: this notebook is designed for Google Colab and utilizes google drive access**

**Note: running the data in part 1 generally takes a substantial amount of time and budget, so for testing I recommend only running a single non-thinking model
- data for this experiment was pulled over the course of multiple days.


In the Final_Project_Part1 code there are several details you must know to run it:

- in the first cell, your output directory will be in your logged in google drive
> LLM_Nash_Experiment


- in the intial setup (the to the cell containing "1) LLM Agent and Prompt Creation")
and MAX_TOKENS_STANDARD/MAX_TOKENS_REASONING must be set according to the model you would like to pull data for.


-additionally, you will need a key appropriate to your API system:
For the chat.tamu.ai system, our class has provided a key that is known

-CF_COOKIE must also contain the CF_Authorization value found by opening a chat then:
-- right click the screen
-- click inspect
-- got to applications
-- then in the menu, click CF_Authorizaiton
-- copy and paste into code cell

(Process identical to PA2 setup for our course)


In the Final_Project_Part2 code you will only need to grant access to your google drive and ensure all csv files listed are contained with the folder
- the data used in this experiment is provided in the folder csv_files, which you can use to test this portion




*************************
*****PROMPT LIBRARY******
*************************

- the prompt library contains the prompting setup that each model in the API is provided with
- a standard suffix, a random game selection, and a motivation





*************************
*****Other Material******
*************************

- all other material provided is strictly complimentary, some of which are resources included in the final report deliverable

This includes items in:
-additional_datasets
-Plots




