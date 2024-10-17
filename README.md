# 📊 Word Analytics Project 📊

This project is a web-based word analytics tool that allows users to analyze a given noun from German, English, or French. The tool provides various analyses, including language identification, word properties, and palindrome visualization.

### Features

The Word Analytics project offers the following features:

1.	**Language Identification:**
   Determines whether the word is in German, English, or French, based on its suffix.

2.	**Additional Analyses:**
	•	Length of the word.
	•	Checks if the first letter is capitalized.
	•	Count of distinct letters in the word.
	•	Calculation of the ratio of consonants to vowels.
	•	Inversion of the word’s case (lowercase becomes uppercase and vice versa).
	•	Calculation of the word’s worth (where a=1, b=2, …, z=26).

3.	**Palindrome Visualization:** Displays a colored rectangle for each letter in the word:
	•	Green if the letter helps form a palindrome.
	•	Red if the letter doesn’t contribute to the palindrome.

### How to Use

	1.	Open the index.html file in a web browser.
	2.	Enter a noun (from German, English, or French) in the input field.
	3.	Click the Analyze! button.
	4.	The results will be displayed under the analysis section, and if the word is a palindrome, a colored visualization will appear.

### Installation

To run the project locally:

1.	Clone the repository:

    `$git clone https://github.com/your-username/word-analytics-project.git`


2.	Navigate to the project directory:

    `$cd word-analytics-project`


3.	Open index.html in your preferred browser:

  For MacOS: `$open index.html`  
  For Windows: `$start index.html` 

No additional installations are required as this is a pure front-end project.

### Features Overview

##### 1. Language Identification

The system identifies the language of the word based on common suffixes:

	•	German: Words ending with heit, keit, chen.
	•	English: Words ending with ness, nce, ty.
	•	French: Words ending with que, age.

##### 2. Word Properties Analysis

	•	Length: The total number of characters in the word.
	•	First Letter Capitalized: Checks whether the first letter of the word is capitalized.
	•	Distinct Letters: The number of unique letters in the word.
	•	Consonant-Vowel Ratio: Calculates the ratio between consonants and vowels in the word.
	•	Case Inversion: Inverts the word’s letter case (e.g., “Cat” becomes “cAT”).
	•	Word Worth: Calculates the worth of the word where each letter has a corresponding numeric value (a=1, b=2, …, z=26).

##### 3. Palindrome Visualization

If the entered word is a palindrome (a word that reads the same forwards and backwards), it displays colored boxes for each letter:

	•	**Green:** The letter contributes to the palindrome.
	•	**Red:** The letter does not contribute to the palindrome.

