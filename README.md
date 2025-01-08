# Time Table Generator
This Java program generates a timetable based on certain predefined rules and conditions.

## Rules

- A Teacher can have a maximum of 2 lectures in a day.
- A Teacher can take a maximum of 1 lecture in a particular class on any given day.
- A Teacher can take a maximum of 2 lectures for a particular class in a week.
- A Class can have a maximum of 3 lectures in a day.



## Flow

When the program starts, it will prompt for:
1. The number of rooms available and their capacities.
2. The capacities of the classes.

## Functionality

The program performs the following checks for each time slot:
- Whether a teacher is available.
- Whether the class is free.
- Whether any room is available.
- If a room is available, whether it has the capacity to accommodate the class.

Considering these checks and the predefined rules, the program generates a timetable.

At the end, the program displays the classes that were unable to schedule all of their lectures.

## Instructions

1. Clone or download the repository.
2. Open the project in a Java IDE (e.g., Eclipse, IntelliJ).
3. Run the program.
4. Follow the prompts to input room and class capacities.
5. View the generated timetable, which will be displayed in the console.

Enjoy using the Timetable Generator!
