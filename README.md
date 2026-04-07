# Morse Code Translator (Python)

A simple, lightweight CLI tool written in Python to convert standard text into Morse Code. This project is a practical exercise in Python dictionary operations and string manipulation.

## 🚀 Features
- **Fast Conversion**: Translates letters (A-Z), numbers (0-9), and common punctuation instantly.
- **Robust Error Handling**: Uses the `.get()` method to handle characters not present in the dictionary without crashing.
- **Clean Formatting**: Automatically adds spaces between Morse characters for better readability.
- **User-Friendly**: Includes a simple loop for continuous input and a clear exit command.

## 🛠️ How It Works
The core of the translation logic uses Python's **List Comprehension** for efficiency:
```python
output = " ".join([morse_dict.get(char, "") for char in input_message])
```
📋 How to Use
Clone the repository:
```Bash
git clone [https://github.com/YOUR_USERNAME/morse-code-translator-py.git](https://github.com/YOUR_USERNAME/morse-code-translator-py.git)
```
Navigate to the directory:
```Bash
cd morse-code-translator-py
```

Run the script:
```Bash
python morse_translator.py
```

Follow the prompt: Enter your text, and the Morse code will be printed in the terminal.

📖 Dictionary Support
Letters: A-Z (Case-insensitive)
Numbers: 0-9
Special Characters: . , ? ! / ( ) & : ; = + - _ " $ @
