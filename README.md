# morseCode

Write a program to translate Morse code to text (see https://en.wikipedia.org/wiki/Morse_code). The user will enter dots and dashes, and the program will displayed the translated Morse code.

On the screen there should be 3 buttons to enter a dot, a dash, or a space.  Space will be used to signify the end of a letter (because Morse code is ambiguous without it).  In addition, the program should respond to the user typing a dot (period), dash (minus sign), or a space on the keyboard.

In the output section, the program should display the translated message, the Morse code entered for the current letter, and every possible letter that starts with the Morse code entered so far.  For example, if the user enters ". ." (dot dot), the program should display the letters F, H, I, S, U, and V.  For each letter, display the full Morse code for the letter, highlighting the part that has been entered.

After a space is entered, the letter should be added to the message, and the Morse code area and the possible letters should be cleared.

If Morse code is entered that doesn't correspond to a letter, then when the user enters a space, put a question mark in the translated message.
