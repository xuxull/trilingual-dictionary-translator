# Trilingual Translator Dictionary

This is a GUI-based **English-Chinese-Russian dictionary application**, created by [xuxull](https://github.com/xuxull) using **Java Swing**.  
It allows users to:
- Enter English sentences via dialog input
- Translate words into Chinese and Russian
- Save new translations to a dictionary file
- View the dictionary in a separate window

## Features

- 🌐 Supports English ➜ Chinese and Russian word mapping
- 💾 Saves user-entered words to a CSV file
- 🧠 Uses a HashMap as an in-memory dictionary
- 🖼️ User-friendly GUI with input dialogs and buttons
- 📂 Persistent data storage for future sessions

## How to Compile & Run

Make sure you have Java installed (`javac` and `java` commands available).

1. Compile:
   ```bash
   javac Main.java
2. Run:
   ```bash
   java Main
If the program detects an existing CSV file, it will load your saved dictionary automatically.

Files
Main.java -- main class that launches the program

Translator.java -- handles translation logic and file I/O

dictionary.csv -- stores saved words and translations (auto-created)


Author
Made with ❤️ by xuxull as a summer Java project and language-learning tool.
