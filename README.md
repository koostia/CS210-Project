# GoodHabits - Habit Tracker By Konstantin Putilkin

## What will the application do?  

Adopting a healthy habit will do miracles for your quality of life and health! 
This application will help you form and adopt a steady list of habits that 
can help you improve your physical and mental well-being.

With a variety of healthy habits that you can choose and integrate into your daily routine, this application will
help your reach one step closer towards achieving your goals.

Some healthy habits you can choose are:
- Exercise
- Meditate
- Hydrate
- Call a Friend
- Write
- Read
- Eat Fruits & Veggies



## Who will use it?

Anyone can use this application, whether your young or old, fit or unfit, it simply doesn't matter. I believe that anyone can adapt into a healthier lifestyle and change for the better.

## Why is this project of interest to you?

Like I said above, I believe that anyone can adapt into a healthier lifestyle and change for the better. I can vouch for the statement above as I became who I am today because of healthy habits. 

## User Stories

- As a user, I want to be able to add a habit to my daily routines list (Grade)

- As a user, I want to be able to view the list of habits on daily routines list
- As a user, I want to be able to mark a habit as complete on my daily routines list (Grade)
- As a user, I want to be able to delete a habit from my daily routines list (Grade)
- As a user, I want to be able to see the number of incomplete and number of completed habits on my daily routines list
- As a user, I want to be able to view a list of habits I can choose from
- As a user, I want to be able to make a custom habit that I can add to my daily routines list (Grade)
- As a user, when I select the quit option from the application menu, I want to be reminded to save my daily routine list to file and have the option to do so or not.
- As a user, when I start the application, I want to be given the option to load my daily routine list from file.

## Phase 4: Task 2

Test and design a class in your model package that is robust.  You must have at least one method that throws a checked exception.  You must have one test for the case where the exception is expected and another where the exception is not expected.

Class HabitsList was designed to be more robust with a limit on the amount of Habits you can put on the list. If it goes over the limit, a FullListException will be thrown.

Method addHabit and addCustomHabit was designed to throw that exception. Class HabitsApp has try catch blocks to catch this exception.

## Phase 4: Task 3

If I had more time, would I have refactored the code to improve my design?

Of course, currently I had all classes nested within the MainWindow class. This type of design proved to be extremely messy and hard to look at.

The changes I would have made was unnesting the classes within MainWindow and made them separate. Assign the many methods in MainWindow to their respective classes.

This change would've allowed me to incorporate more relationships between different classes and simplified the code tremendously.