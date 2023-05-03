Download Link: https://assignmentchef.com/product/solved-cs-module-a
<br>
You will create a program that uses a Critter class to move around a Grid, which is also a class.  The Critter and the Grid classes will be in separate files.




The Critter class will have a data member to count the number of moves made.  It will also need data members to hold the current x and y coordinates.  It will have a member function that randomly moves it one space in one of 4 directions.   You will create both the source and header files for the class.




The Grid class has a 2D array data member. This will be an array of type character.  It will have an updateLocation() function that will be used by the Critter class to pass the new location of the Critter to be displayed.




For the array ou will use a space character, ‘ ‘ for empty and a single ‘C’ for the location of the

Critter.  The Grid will have one Critter that moves around.  The starting location will be random.  The Critter will move around until it would exit the gird.  In that case it is squashed.  The program should terminate normally and tell the user how many steps the Critter took.  After every move the grid will be displayed to the user.




Hint:  For testing, use small arrays.  There’s only one Critter after all. JJ




You will create a program that prompts the user for the number of rows and columns.  It must be at least 1 x 1.  It will create the Grid and Critter, run the simulation, display the grid after each move, and inform the user when the Critter gets squashed showing the number of moves made.




NOTE:  <strong>You must always do reasonable input validation. </strong> If you have a question about what is “reasonable” ask your grader, any TA, or the instructor.  You don’t have the tools yet to check everything easily.  We don’t want you spending more time on that than anything else.  In this case you’re checking for integer input to verify each is greater than 0.




Once your program is working and you have eliminated the bugs create a makefile to build your program.  You do not need a complicated makefile.  You can have a single target that just includes what you typed into the command line for testing.




Include a second target <em>clean</em> that removes extraneous files such as .o files or a.out.




Finally, you should include all 6 files into a zip archive.  You must submit only the zip file in TEACH by the due date.  We will only accept submissions in TEACH that are in a zip file and that include the makefile.




<strong>HINT:</strong>  If you look at the assignment you’ll see that much of this module is similar to what is required in the assignment.  Develop the module while doing the design for the assignment.  You can avoid making the same mistake(s) twice.




<h1>On The Horizon</h1>




Remember we are laying the foundation for future parts of your program!  Yes, this is cumbersome for what it does.  What’s coming?  More than one Critter moving around.  More than one type of Critter.  What would that mean for technical skills?  Inheritance.  Pointers to objects.  We do a lot with pointers so you might begin reviewing your notes and the test. JJ