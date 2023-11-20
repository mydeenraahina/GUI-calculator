<div align='center'>

<h1>THIS IS A /GUI-calculator USING PYTHON Tkinter</h1>
<p>Your code follows a clear and structured pattern for implementing a simple quiz game. Here's an overview of the working pattern: Welcome Message and Initial Input: The program starts with a welcome message, prompting the user to decide whether they want to play the game or not. python Copy code print("Welcome to our quiz") choice = input("Do you want to play this game? (yes/no): ") Main Game Loop (main_block function): The main_block function contains the main loop that controls the flow of the game. If the user chooses to play (yes), it calls the play function to start the quiz. If the user chooses not to play (no), the program exits. If the user enters an invalid choice, it prompts the user to try again. python Copy code while True: if choice.lower() == "yes": print("Let's play") play() elif choice.lower() == "no": print("Exit!") break else: print("You entered a wrong value") Quiz (play function): The play function contains the logic for asking questions and keeping track of the user's score. It uses a dictionary (answers) to store correct answers for each question. The user is prompted with questions, and their input is compared to the correct answer. The score is updated based on correct and incorrect answers. python Copy code score_gain += ask_question("India is a ________ country: ", answers['question1'], score_gain, score_loss) score_gain += ask_question("Capital of India: ", answers['question2'], score_gain, score_loss) # ... Repeat for other questions Input Validation: The program includes some basic input validation, checking if the user enters yes or no. If the user enters an invalid value, they are prompted to try again. python Copy code else: print("You entered a wrong value") Continuation or Exit: After each round of the quiz, the user is given the option to continue playing or exit the game. The program handles the user's choice and either continues the game or exits the loop. python Copy code choice = input("Do you want to continue this game? (yes/no): ") Overall, your code follows a clear flow, starting with user input, entering the main loop for the game, playing the quiz, and allowing the user to decide whether to continue or exit. It's a well-struct</p>

<h4> <span> · </span> <a href="https://github.com/MydeenRaahia//GUI-calculator/blob/master/README.md"> Documentation </a> <span> · </span> <a href="https://github.com/MydeenRaahia//GUI-calculator/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/MydeenRaahia//GUI-calculator/issues"> Request Feature </a> </h4>


</div>




## :star2: About the Project

## :handshake: Contact

MYDEENRAAHINA - - mydeenraahina862@gmail.com

Project Link: [https://github.com/mydeenraahina/GUI-calculator](https://github.com/mydeenraahina/GUI-calculator)
