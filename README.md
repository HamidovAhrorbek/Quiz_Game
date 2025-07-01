🧠 Quiz_Game

A simple command-line Python quiz game that tests your knowledge with multiple-choice questions. Built using object-oriented programming for clear and modular code organization.

📋 Features

* Interactive command-line interface

* Question and answer logic handled through classes

* Keeps track of the score

* Modular design using separate files for:
    
    * Questions (question_model.py)
    * Quiz logic (quiz_brain.py)
    * Data source (data.py)
    
    
🚀 How It Works

1. Loads a list of questions and answers from data.py.

2. Each question is wrapped in a Question object.

3. The game loops through all questions using QuizBrain.

4. The user inputs their answer, and the program tells them whether they were correct.

5. Final score is displayed at the end.


🧱 Project Structure

Quiz_Game/

* main.py                # Main driver code
* question_model.py      # Contains the Question class
* quiz_brain.py          # Contains the QuizBrain class (quiz logic)
* data.py                # Contains the question_data list (questions & answers)


📦 Requirements

* Python 3.x

* No external dependencies


▶️ How to Run


1. Clone the repository:

git clone https://github.com/yourusername/Quiz_Game.git
cd Quiz_Game

2. Run the game:
   
python main.py


📝 Example Output

Q1: Is the sky blue? (True/False): true

You got it right!

Your current score is: 1/1

...

You've completed the quiz

Your final score was: 8/10.

📚 Acknowledgments

* Inspired by beginner Python projects to demonstrate OOP concepts.

* Useful for learners who want to practice working with classes and control flow.







































































