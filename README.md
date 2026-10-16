# Find-largest-word-cpp

# Largest Word in a String (C++)

A beginner-friendly C++ program that finds the largest (longest) word in a sentence entered by the user.

## About

The program reads a full line of text, splits it into words using spaces, and keeps track of the longest word found. It then prints that word and its length.

## Example

```
Enter a string: I love programming in C++
Largest word: programming
Length: 11
```

## How It Works

1. Read the full line using `getline(cin, str)`.
2. Add a space at the end of the string so the last word is also checked.
3. Go through each character one by one:
   - If it is not a space, add it to the current word.
   - If it is a space, the word is complete. Compare its length with the largest word so far and save it if it is longer. Then reset the current word.
4. Print the largest word and its length.

## Things to Note

- If two words have the same length, the first one is kept.
- Extra spaces between words are handled correctly.
- Punctuation counts as part of a word (for example, `Hello,` has length 6).

## Concepts Used

- Strings (`string`)
- Input and output (`cin`, `cout`, `getline`)
- `for` loop
- `if` / `else` conditions
- String indexing (`str[i]`)
- `length()` function

## How to Run

Make sure a C++ compiler such as `g++` is installed.

```bash
# Compile
g++ largest_word.cpp -o largest_word

# Run (Linux / macOS)
./largest_word

# Run (Windows)
largest_word.exe
```

## Project Structure

```
largest-word-cpp/
├── README.md
└── largest_word.cpp
```

## Author

NAYLA IRFAN

B.Tech CSE, 1st Semester

## License

This project is free to use for learning purposes.
