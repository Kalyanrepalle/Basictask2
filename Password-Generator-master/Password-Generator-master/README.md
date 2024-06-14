# Password Generator

## Introduction

During the Winter Break of my second year, after completing the Object-Oriented Effective Java Programming course, I was looking for a practical project to apply my Java skills. One night, while discussing online security with my father, I realized the importance of having strong passwords. Inspired by this conversation, I decided to create a Java Console Application for generating random passwords and checking their strength.

## Features

### 1. Password Generation

- Users specify their preferences for including uppercase letters, lowercase letters, numbers, and symbols.
- Users input the desired length of the password.
- Based on user preferences, a password alphabet is generated.
- Random characters from the password alphabet are combined to create a completely random string.
- The generated password is displayed on the console.

### 2. Password Strength Check

The strength of the password is evaluated based on the following criteria:

- Usage of uppercase letters.
- Usage of lowercase letters.
- Usage of numbers.
- Usage of symbols.
- Length of the password (8 or more characters for decent strength, 16 or more for good strength).

A score is calculated based on these criteria, and a corresponding strength message (weak/medium/good/great) is displayed to the user.

### 3. Displaying Useful Information

Users receive tips on password security, such as avoiding password reuse, character repetition, keyboard patterns, dictionary words, and sequential characters.

## Next Steps

While the current version of the project is functional in the console, I plan to enhance the user experience by creating a graphical user interface (GUI) for the application. This GUI version will be available in the Password-Services repository.

## How to Use

To use the Password Generator, simply run the Java Console Application and follow the prompts to generate a password or check its strength.

## Contributions

Contributions to improve the functionality and usability of the Password Generator are welcome. Feel free to submit pull requests or open issues for any suggestions or bug reports.

