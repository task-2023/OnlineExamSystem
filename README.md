The Online Exam System Represents methods for user registration, login, exam-taking, and result submission.
Initializes the system with a provided username and password.
Displays a success message for registration.
Initializes variables like is LoggedIn, time Remaining, and arrays for storing user and correct answers.
Prompts the user to enter their username and password.
If the credentials match, sets the is LoggedIn flag to true and prints a success message; otherwise, prompts the user to try again.
Logs the user out by setting is LoggedIn to false, Prints a logout success message.
Checks if the user is logged in if not, prompts the user to log in first.
Presents a series of 10 multiple-choice questions to the user.
Asks the user to choose an option (1 or 2) for each question and stores the answers.
Provides an option to submit the exam immediately or auto-submit when the time is up.
Checks if the user is logged in if not, prompts the user to log in first.
Compares the user's answers with the correct answers and calculates the score.
Displays the user's score and logs them out.
In the main method, the program starts by asking the user to input a username and password.
Creates an instance of Online Exam System with the provided username and password.
Logs the user in and starts the exam.
The output may vary based on user input and the randomly generated correct answers.
