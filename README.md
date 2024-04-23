# Randomly_Jock_Application
simple joke-telling application that randomly selects a joke from an array and presents it to the user.
step1:-
Header Files: The application contains three standard C library header files.
stdio.h: Used for input and output operations.
stdlib.h: Used to allocate memory, generate random numbers, and perform various utility tasks.
time.h: This file contains time-related functions that are used to seed the random number generator.
Function definitions:

step2:-
void TellJoke(): This method returns an array of jokes. It chooses a joke at random from the array and prints it to the terminal.


step3:-

Main function:
Declares a char-type variable playAgain to hold the user's decision to play again.
Prints a welcome message.
Enters the do-while loop:
Calls the tellJoke() method to show a joke.
Asks the user whether they would like to hear another joke.
Reads the user's input (y or n) into the playAgain variable.
Continues looping if the user enters y or Y.
When the loop finishes, it prints a goodbye message.

step4:-
tellJoke() Function: Declares an array of strings (jokes[]) with numerous jokes.
The number of jokes in the array is calculated using sizeof(jokes) / sizeof(jokes[0]).
Seeds the random number generator with srand(time(NULL)).
The function rand()% numJokes generates a random index between 0 and numJokes - 1.
Prints a randomly chosen joke to the console.

Overall, the application offers a basic interactive experience in which the user may enjoy a random joke and opt to hear more if they so desire.







