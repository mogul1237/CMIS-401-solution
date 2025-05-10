# CMIS-401-solution

Download Here: [CMIS 401 solution](https://jarviscodinghub.com/assignment/cmis-401-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

CMIS 401 Design a Java application that will read Solution

1
Final Project
This assignment demonstrates your understanding of the concepts from the CMIS 141 class. This
homework consists of 1 programming assignment worth 25 points.
Before attempting this project, be sure you have completed all of the reading assignments, hands-on
labs, discussions, and assignments to date.
1. (25 points) Design a Java application that will read a file containing data related to the
passengers on the Titanic. The description of the file is shown below. The application should
provide statistical results on the passengers including:
a. Total number of passengers on the Titanic
b. Total number of passengers who perished on the Titanic
c. Total number of Passengers who survived the sinking of the Titanic
d. Number of passengers who survived the sinking of the Titanic as a function of the
passenger class (e.g. 1,2,3)
e. Number of passengers who survived the sinking of the Titanic as a function of the
passenger gender (e.g., male, female)
f. A list of the names of passengers who paid greater than $200 for their tickets
g. A list of the names of passengers who were less than 10 years old who survived the
sinking of the Titanic
h. A list of the names of passengers who were less than 10 years old who perished on the
Titanic
i. The count of the number of passengers as a function of the first letter of their last name.
(e.g., A: 13, B:33 …)
j. Additional statistical results you add to enhance the functionality
The following are some design criteria and specific requirements that need to be addressed:
a. Use command line arguments to send in the name of the Titanic file.
b. Use a 2D array to store the Titanic data. (Hint: You will probably need to store the array
as String values and then convert to other types as needed since some data is null)
c. You should create at least 2 Java classes – Titanic and TestTitanic. You are welcome to
create additional classes if you want to further separate the functionality.
d. You should create separate methods for each of the required functionality. (e.g.
getTotalPassengers() will return the total number of passengers on the Titanic.)
e. A user-friendly and well-organized menu should be used for users to select which data
to return. A sample menu is shown in run example. You are free to enhance your design
and you should add additional menu items and functionality.
f. The menu system should be displayed at the command prompt, and continue to
redisplay after results are returned or until Q is selected. If a user enters an invalid menu
item, the system should redisplay the menu with a prompt asking them to enter a valid
menu selection
g. The application should keep track of the elapsed time (in seconds) between once the
application starts and when the user quits the program. After the program is exited, the
2
application should provide a prompt thanking the user for trying the Titanic program
and providing the total time elapsed.
Here is sample run:
java TestTitanic Titanic.txt
********** Welcome to the Titanic Statistical Application **************************
Enter the number of the question you want answered. Enter ‘Q’ to quit the program :
1. How many passengers were on the Titanic?
2. What percentage of passengers perished on the Titanic?
3. What percentage passengers survived the sinking of the Titanic?
4. What percentage of passengers survived for each of the three classes?
5. What percentage of passengers survived as a function of gender?
6. What specific passengers paid more than $200 for their tickets?
7. What specific passengers who were less than 10 years old perished on the titanic?
8. What specific passengers who were less than 10 years old survived the sinking of the titanic?
9. For each letter in the alphabet, how many passengers last names started with that letter?
Q. Quit the program
Enter your selection: 1
There were 1310 Passengers on the Titanic.
Enter the number of the question you want answered. Enter ‘Q’ to quit the program :
1. How many passengers were on the Titanic?
2. What percentage of passengers perished on the Titanic?
3. What percentage passengers survived the sinking of the Titanic?
4. What percentage of passengers survived for each of the three classes?
5. What percentage of passengers survived as a function of gender?
6. What specific passengers paid more than $200 for their tickets?
7. What specific passengers who were less than 10 years old perished on the titanic?
8. What specific passengers who were less than 10 years old survived the sinking of the titanic?
9. For each letter in the alphabet, how many passengers last names started with that letter?
Q. Quit the program
Enter your selection: 6
The following passengers paid more than $200 for their tickets:
Allen, Miss. Elisabeth Walton
Astor, Col. John Jacob
Astor, Mrs. John Jacob (Madeleine Talmadge Force)
Baxter, Mr. Quigg Edmond
Baxter, Mrs. James (Helene DeLaudeniere Chaput)
Bidois, Miss. Rosalie
Bird, Miss. Ellen
Bowen, Miss. Grace Scott
3
Cardeza, Mr. Thomas Drake Martinez
Cardeza, Mrs. James Warburton Martinez (Charlotte Wardle Drake)
Chaudanson, Miss. Victorine
Douglas, Mrs. Frederick Charles (Mary Helene Baxter)
Endres, Miss. Caroline Louise
Farthing, Mr. John
Fortune, Miss. Alice Elizabeth
Fortune, Miss. Ethel Flora
Fortune, Miss. Mabel Helen
Fortune, Mr. Charles Alexander
Fortune, Mr. Mark
Fortune, Mrs. Mark (Mary McDougald)
Geiger, Miss. Amalie
Keeping, Mr. Edwin
Kreuchen, Miss. Emilie
Lesurer, Mr. Gustave J
Madill, Miss. Georgette Alexandra
Robbins, Mr. Victor
Robert, Mrs. Edward Scott (Elisabeth Walton McMillan)
Ryerson, Master. John Borie
Ryerson, Miss. Emily Borie
Ryerson, Miss. Susan Parker “Suzette”
Ryerson, Mr. Arthur Larned
Ryerson, Mrs. Arthur Larned (Emily Maria Borie)
Straus, Mr. Isidor
Straus, Mrs. Isidor (Rosalie Ida Blun)
Ward, Miss. Anna
Widener, Mr. George Dunton
Widener, Mr. Harry Elkins
Widener, Mrs. George Dunton (Eleanor Elkins)
Enter the number of the question you want answered. Enter ‘Q’ to quit the program :
1. How many passengers were on the Titanic?
2. What percentage of passengers perished on the Titanic?
3. What percentage passengers survived the sinking of the Titanic?
4. What percentage of passengers survived for each of the three classes?
5. What percentage of passengers survived as a function of gender?
6. What specific passengers paid more than $200 for their tickets?
7. What specific passengers who were less than 10 years old perished on the titanic?
8. What specific passengers who were less than 10 years old survived the sinking of the titanic?
9. For each letter in the alphabet, how many passengers last names started with that letter?
Q. Quit the program
Enter your selection: Q
Thank you for trying the Titanic Program.
Elapsed time in seconds was: 95
4
Grading Rubric:
The following grading rubric will be used to determine your grade:
Attribute Exceeds Meets Does not meet
Design (5 points) (5 points)
Exhibits proper use of
parameters, and
selection of data types
all of the time.
Employs correct and
appropriate use of
programming structures
(loops, conditionals,
classes etc.) all of the
time.
Efficient algorithms used
all of the time.
(3-4 points)
Exhibits proper use of
parameters, and
selection of data types
most of the time.
Employs correct and
appropriate use of
programming structures
(loops, conditionals,
classes etc.) most of the
time.
Efficient algorithms used
most of the time.
(0-2 points)
Rarely exhibits proper
use of parameters, and
selection of data types.
Rarely employs correct
and appropriate use of
programming structures
(loops, conditionals,
classes etc.)
Poorly structured and
inefficient algorithms.
Functionality (10
points)
(9-10 points)
Extra effort was
apparent through the
addition of significant
and additional
functionality beyond the
scope of the
assignment.
(7-8 points)
Program fulfills most
functionality.
Most requirements
were fulfilled.
Screen captures
provided demonstrating
the successful compiling
and running of the
program.
(0-6 points)
Program does not fulfill
functionality.
Few requirements were
fulfilled.
Test cases (5 points) (5 points)
Test cases provide
comprehensive
coverage of all code
paths.
Discussion of run-time
errors included.
(3-4 points)
Test cases provide
coverage of most code
paths.
Test cases results well
documented providing
pass/fail results for each
test case.
(0-2 points)
No or insufficient test
cases
Minimal supporting
evidence provided to
verify testing actually
took place.
Java Style Guide (5
points)
(5 points)
Code impeccably neat
and well-organized.
(3-4 points)
Header comments
include filename,
(0-2 points)
Code rarely follows
recommended Java style
guide
5
Extensive In-line
comments providing
additional insight into
code design and
functionality
author, date and brief
purpose of the program.
In-line comments used
to describe major
functionality of the
code.
Meaningful variable
names and prompts
applied.
Class names are written
in UpperCamelCase.
Variable names are
written in
lowerCamelCase.
Constant names are in
written in All Capitals.
Braces use K&R style.
Submission requirements:
Your deliverables include all Java files (.java) and a single word (or PDF) document. The Java files should
be named appropriately for your applications. Your word document should include screen shots
showing the successful compiling and running of each application, and a detailed description of the test
plan for each application. The test plan should include the input, expected output, actual output and if
the test case passed or failed. Submit your files to the Final Project assignment area no later than the
due date listed in the calendar.
Titanic Data Description:
The attached tab delimited file, named titanic.txt contains the known passengers on the Titanic. There
are 5 fields included in the file in the order:
Passenger class (1,2,3)
Survived (1=yes, 0=no)
Name (Passenger name)
sex (male or female)
age (some values are blank)
fare (some values are blank)
