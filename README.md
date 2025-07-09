Number Guessing Game (Assembly Language)
This is a simple console-based Number Guessing Game developed using Assembly Language, the MASM assembler, and the Irvine32 library. The game demonstrates fundamental programming concepts in a low-level environment, including conditional logic, loops, user input/output, and random number generation.

How It Works
The program generates a random number between 1 and 10.
The user is given 3 attempts to guess the correct number.
After each guess, the game gives hints: "Too High" or "Too Low".
If guessed correctly, the player sees a congratulatory message.
If not, it ends with a "Game Over" message showing the correct number.

Key Concepts Used
Random number generation using Irvine32's RandomRange
Loops and conditional branching for control flow
User interaction using ReadInt and WriteString
Data comparison and feedback logic

Requirements
MASM32 assembler
Irvine32 Library
Windows OS with 32-bit support or emulator (like DOSBox, VirtualBox, etc.)

Educational Use
This project is ideal for students and beginners learning assembly language. It provides hands-on experience with hardware-near execution, reinforcing logical thinking and problem-solving skills in a low-level context.
