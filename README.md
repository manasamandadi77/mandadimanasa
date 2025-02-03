Console-Based Quiz Application
A Java-based console quiz application that offers an engaging gameplay experience with lifelines and dynamic questions.

Features
Interactive Gameplay: Players can answer multiple-choice questions with real-time feedback on their responses.
Lifelines: Includes two lifelines:
50-50: Eliminates two incorrect options, leaving one correct and one incorrect option.
Audience Poll: Displays audience support percentages for each option.
Dynamic Questions: Randomized question options and lifeline behaviors for an enhanced user experience.
Prize Progression: Displays prize amounts won at each level, encouraging players to progress further.
Input Validation: Ensures players provide valid responses for seamless gameplay.
Rules
Players must pick options only from the given choices.
Each lifeline can be used only once.
Incorrect answers terminate the game, displaying the total prize won.
Technologies Used
Programming Language: Java
Development Tools: JDK, any IDE (Eclipse, IntelliJ IDEA, etc.)
How to Run
Clone the repository or download the source code.
Compile the Java files using the following command:
javac ConductQuiz.java
Run the application using:
java quiz.ConductQuiz
Follow the on-screen instructions to play the quiz.
Game Flow
The player enters their name, address, and phone number.
Questions are displayed one by one, with four options and a fifth option for lifelines.
If a lifeline is chosen, the player can select from the reduced or analyzed options.
Correct answers move the player to the next question, while incorrect answers end the game.
File Structure
quiz/
  |- Candidate.java  // Handles player details and feedback.
  |- Question.java   // Manages question data and lifeline logic.
  |- ConductQuiz.java // Main class to run the application.
License
This project is open-source and available for educational purposes.
