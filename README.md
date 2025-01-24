# The Problem

Using **TypeScript**, find all of the English words in a given string. For example, if you are given the word `WORKING`, you can easily find `WORK` and `KING`, but `ROW`, `RING`, and `KNOW` are also part of it. You have access to a utility class called `Dictionary`, which has one method, `isEnglishWord(word: string): boolean`. This method connects to a (mocked) online dictionary and returns `true` if the string passed to it is an English word, and `false` otherwise.

## Instructions

1. **Create a TypeScript project** to solve this problem. You will need to create the `Dictionary` class.
2. **Mock the `Dictionary.isEnglishWord(word: string): boolean` method** for your solution and tests.
3. **Write a function** that extracts all English words from the input string by testing every possible substring.
4. Ensure the output is a collection of strings **without duplicates**.
5. **Create tests** that exercise your class and methods. Ensure that the solution is well-tested for different cases.
6. Come prepared to discuss your design decisions.

## Example

For the input string `"WORKING"`, your solution should return the following words (if they are valid English words according to the `isEnglishWord` method):

- `WORK`
- `KING`
- `ROW`
- `RING`
- `KNOW`

## Notes

- You can assume that the dictionary only contains valid English words, and that the method `isEnglishWord` will accurately detect whether a given word is valid.
- Make sure to consider edge cases such as empty strings or strings with no valid words.
- Aim to implement a clean and efficient solution, with appropriate handling for performance and scalability.
