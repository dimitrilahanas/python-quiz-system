
# Console Quiz System 🧠📜

This is a beginner-friendly Python project that turns a plain `.txt` file into a working multiple-choice quiz in the console. It was created as a learning project to better understand file handling, basic logic, and working with AI-generated content in Python.

---

## 📝 Features

- Reads a `.txt` file containing quiz questions and answers.
- Generates a multiple-choice quiz in the console.
- Awards 1 point per correct answer.
- Uses AI to generate 3 additional incorrect options that are similar to the correct one.
- Keeps score and displays your result at the end.

---

## 📂 How to Use

1. **Prepare your quiz file**  
   Create a `.txt` file with your questions and answers. The format should look like this:

   ```
   What is the capital of France?|Paris
   Who wrote 'To Kill a Mockingbird'?|Harper Lee
   What is the largest planet in our solar system?|Jupiter
   ```

   Each line should have a question, followed by a pipe (`|`), then the correct answer.

2. **Place your file**  
   Put your quiz file in the same folder as the Python script. For example: `quiz.txt`.

3. **Run the program**  
   Run the Python script using:

   ```
   python main.py
   ```

4. **Take the quiz!**  
   The program will read the file, turn each question into a multiple-choice question, and let you choose an answer. You’ll get 1 point for each correct answer.

---

## ⚙️ How it Works

- The program reads each line from the file and separates the question from the correct answer.
- AI is used to generate 3 similar but incorrect options based on the correct answer.
- The correct answer and AI-generated distractors are shuffled and presented as a multiple-choice question.
- Your score is tracked and shown at the end of the quiz.

