# IFCSP--Formative-1-Maths-Quiz
## Project Planning


## 🧮 Maths Quiz – Times Tables (Python)
Overview
This is a simple, interactive times tables quiz written in Python.
Each question randomly picks two integers between 1 and 20, asks the user to compute their product, validates the input, and keeps prompting until the correct answer is given. The program can be configured to ask a fixed number of questions in a session.
### Key features
* Random multiplication questions (1–20)
* Input validation (rejects non‑numeric answers gracefully)
* “Try again” loop until the user gets it right
* Configurable number of questions per run

### How to Run the Code:
1. save the code in a file, e.g., Formative1_Maths Quiz
2. open a terminal in the file's directory - this was done via VSCode
3. Run:
   <img width="84" height="20" alt="image" src="https://github.com/user-attachments/assets/8cf9a823-b642-4fa7-8cde-7228950c9617" />
4. whilst this runs, you may need to select kernel (normal python base)
5. as you work your way down, you will need to run each code one by one and by default the program will ask 4 questions in total as shown below:

<img width="145" height="47" alt="image" src="https://github.com/user-attachments/assets/a15cafa3-23c7-4977-afa9-7a3a7a1847f5" />

### Functions
- times_tables()
  This generates two random numbers (1-20), multiplies them and returns the numbers and the answer
- ask_maths_question()
  This displays the multiplication question, validates an input and loops until the correct answer is given
- run_program(number_question)
  This will run the quiz for the specified number of questions

## An example of this output:
What is 7 * 6: **42**
That is correct! Well done!

What is 10 * 3: **abc**
Input Value not a number, try again

What is 10 * 3: **30**
That is correct! Well done!

This can also be shown here in my code:
<img width="284" height="169" alt="image" src="https://github.com/user-attachments/assets/2853c3c8-5e27-4190-8a22-00befc86c1d5" />

- this loop is what makes it easier for the code to run when it gets different answers inputted and this is what happens when an integer is not given as an answer.

#### For next time:
I will try to add scores, different difficulty levels and even try different operations rather than multiplication (adding, subtracting, etc)

