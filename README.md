# Pig Latin Translator

##### By: Excellent Student

#### An Application for translating English into Pig Latin

## Technologies Used

* Javascript
* HTML/CSS
* Bootstrap

## Setup/Installation Requirements

* Clone or download this repository onto your desktop
* Navigate to top-level of directory
* Open index.html in the browser of your choice

## Tests:

#### Describe: vowelWord()

Test: "It will return a word with "way" at the end."
Code: 
word = "apple";
vowelWord(word);
Expected Output: "appleway"

Test: "It will return null if given a word that does not start with a vowel."
Code:
word = "bananas";
vowelWord(word);
Expected Output: null

Test: "It will return null if not given a string."
Code:
word = 1;
vowelWord(word);
Expected Output: null

#### Describe: consonantWord()

Test: "It will return a word starting with a consonant as a word with the consonant moved to the end plus "ay"."
Code: 
word = "bananas";
consonantWord(word);
Expected Output: "ananasbay"

Test: "It will return a word starting with multiple consonants with that block of consonants at the end of the word plus "ay"."
Code:
word = "block";
consonantWord(word);
Expected Output: "ockblay"

Test: "It will return null if given a word that does not start with a consonant."
Code:
word = "apple";
consonantWord(word);
Expected Output: null

Test: "It will return null if not given a string."
Code:
word = 1;
consonantWord(word);
Expected Output: null

#### Describe: quWord()

Test: "It will return a word which has moved all letters up to "qu" to the end plus "ay"."
Code: 
word = "quit";
quWord(word);
Expected Output: "itquay"

Test: "It will correctly process the word if the qu does not come as the first two letters"
Code:
word = "squirm";
quWord(word);
Expected Output: "irmsquay"

Test: "It will return null if given a word that does not contain qu."
Code:
word = "plug";
quWord(word);
Expected Output: null

Test: "It will return null if the word starts with a vowel."
Code:
word = "apple";
quWord(word);
Expected Output: null

Test: "It will return null if given a word that starts with q but the second character is not u."
Code:
word = "qanat";
quWord(word);
Expected Output: null

Test: "It will return null if not given a string."
Code:
word = 1;
quWord(word);
Expected Output: null

## License

[MIT](https://opensource.org/licenses/MIT)


Copyright (c) 2021 Excellent Student