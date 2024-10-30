# WORD_COUNTER
The project serves as an introduction to user input handling, function creation, and basic string manipulation. It’s also a good exercise in validating inputs and displaying formatted output for the user.
The Word Counter project focuses on building a Python program that counts words in a sentence or paragraph entered by the user. This project strengthens skills in handling user input, string processing, function creation, and error handling.

Code Breakdown:
count_words(text) function: This function processes the input text by splitting it into individual words (using spaces as delimiters). It calculates and returns the total word count.

Logic: The split() function breaks down the text into a list of words, and len() counts the number of elements in this list, providing the word count.
main() function: This function orchestrates the program flow.

It greets the user and prompts them to enter text.
It checks if the input is empty; if so, it displays an error and exits the program to avoid counting issues.
If valid, the function calls count_words, receives the word count, and displays it.
Error Handling and User Guidance:

The program uses a simple check to ensure the input isn’t empty, offering a prompt for correct input if needed.
