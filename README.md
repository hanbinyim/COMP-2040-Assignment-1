# COMP-2040-Assignment-1

Text Statistics Program

This program reads text from a file named input.txt, analyzes the content, and outputs six statistics about the text. The results are displayed on the console and also written to a file named output.txt.

The program calculates:
1. Word count  
2. Unique word count  
3. Character count (with spaces)  
4. Character count (no spaces)  
5. Average word length (1 decimal place)  
6. Most common word(s) and their frequency  

- All words are converted to lower-case letters 
- A word is defined as a sequence of letters a-z, A-Z
- Apostrophes, hyphens, digits, punctuation, and underscores are separators.  
- "Characters with spaces" counts every character in the file 
- "Characters no spaces" excludes all whitespace (spaces, tabs, newlines).  


The program writes exactly these six lines in order:
Word count: <int>
Unique words: <int>
Characters (with spaces): <int>
Characters (no spaces): <int>
Average word length: <float with 1 decimal>
Most common word(s): <words or blank> (<int>)


# To run the program,
1. Place your input text in a file named input.txt (in the same directory as `main.py`).
2. Run the program from the terminal:

```bash
python main.py

Results will appear in the console and new file named output.txt