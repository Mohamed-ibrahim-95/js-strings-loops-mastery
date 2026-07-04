# JavaScript Strings & Loops Mastery — Study Progress Tracker

Learning stages per level: Basic → Applied → Advanced → Cumulative
Each stage builds on the previous one and prepares for the next level.

## Level 0: Absolute Foundations

* [x] Core explanation: variables, for-loop anatomy, comparisons, console.log
* [ ] Basic task: Understand how to print "Hello World" multiple times using a loop
* [ ] Applied task: Understand how to print numbers in ascending and descending order
* [ ] Advanced task: Understand how to detect and print even numbers using modulo
* [ ] Cumulative task: Understand how to build a multiplication table with formatted template literal output

## Level 1: Pointer Movement (i)

* [ ] Core explanation: index, text.length, i++ / i--, out-of-bounds
* [ ] Basic task: Understand how to access and print each character with its index
* [ ] Applied task: Understand how to move through a string in reverse using a backward loop
* [ ] Advanced task: Understand how to move through a string using steps such as i += 3 without going out of bounds
* [ ] Cumulative task: Understand how to read adjacent character pairs safely using indexes

## Level 2: Building New Strings with result

* [ ] Core explanation: string immutability, result += text[i]
* [ ] Basic task: Understand how to copy a string manually using result
* [ ] Applied task: Understand how to copy a string while excluding the first and last characters
* [ ] Advanced task: Understand how to reverse a string using result = char + result without a backward loop
* [ ] Cumulative task: Understand how to separate even-index and odd-index characters into one result while tracing each step

## Level 3: Deletion via Skipping

* [ ] Core explanation: skip logic as a way to delete characters
* [ ] Basic task: Understand how to remove spaces from a sentence
* [ ] Applied task: Understand how to remove digits from a string
* [ ] Advanced task: Understand how to remove only the first occurrence of a character using a flag
* [ ] Cumulative task: Understand how to clean a username by removing spaces, digits, and only the first duplicate letter

## Level 4: Modification & Replacement

* [ ] Core explanation: the difference between replace, delete, and keep
* [ ] Basic task: Understand how to replace underscores with spaces
* [ ] Applied task: Understand how to replace only the first occurrence of a character
* [ ] Advanced task: Understand how to replace every digit with double its value
* [ ] Cumulative task: Understand how to sanitize a password using multiple replacement and deletion rules

## Level 5: Counting with count

* [ ] Core explanation: count variable, character comparisons, ASCII and Unicode ranges
* [ ] Basic task: Understand how to count spaces in a sentence
* [ ] Applied task: Understand how to count uppercase letters using character ranges
* [ ] Advanced task: Understand how to count special characters that are not digits and not letters
* [ ] Cumulative task: Understand how to count special characters and build a letters-only result in one loop

## Level 6: Comparing Current vs Previous/Next Character

* [ ] Core explanation: text[i - 1], text[i + 1], and boundary protection
* [ ] Basic task: Understand how to compare each character with the next character
* [ ] Applied task: Understand how to count consecutive "++" occurrences
* [ ] Advanced task: Understand how to count letters that are immediately followed by a digit
* [ ] Cumulative task: Understand how to detect negated letters preceded by "!" and remove "!" while building a new result

## Level 7: Consecutive Duplicates

* [ ] Core explanation: group logic and the N-1 comparison rule
* [ ] Basic task: Understand how to count consecutive duplicate pairs in a word
* [ ] Applied task: Understand how to remove consecutive duplicates while keeping one character per group
* [ ] Advanced task: Understand how to compress a string such as "aaabbc" into "a3b2c1"
* [ ] Cumulative task: Understand how to clean chat spam such as "goooood morninggg" and count total spam characters

## Level 8: Global Duplicates

* [ ] Core explanation: variable scope inside vs outside loops, persistent vs temporary variables
* [ ] Core explanation: nested loops, text[i] === text[j], and the difference between global duplicates and consecutive duplicates
* [ ] Basic task: Understand how to count how many times a specific character appears in the whole string
* [ ] Applied task: Understand how to use a nested loop to print each character's total count, including the redundant-counting problem
* [ ] Advanced task: Understand how to prevent redundant counting using an already-counted check
* [ ] Cumulative task: Understand how to find the first non-repeating character

## Level 9: Flags (found / boolean state)

* [ ] Core explanation: boolean flags, false → true for existence checks, and true → false for validation checks
* [ ] Basic task: Understand how to detect whether a string contains a digit without using includes()
* [ ] Applied task: Understand how to check whether all characters are digits
* [ ] Advanced task: Understand how to detect whether a string contains any duplicate character
* [ ] Cumulative task: Understand how to validate a username using multiple rules: starts with a letter, contains no special characters, and has no long consecutive repeats

## Level 10: Nested Loops (formal i & j)

* [ ] Core explanation: outer loop and inner loop relationship, and when j starts at 0 vs i + 1
* [ ] Basic task: Understand how to print every possible (i, j) character pair
* [ ] Applied task: Understand how to compare each character only with the characters after it using j = i + 1
* [ ] Advanced task: Understand how to prevent double-counting duplicates using a flag with a nested loop
* [ ] Cumulative task: Understand how to sort characters alphabetically using a simple Bubble Sort with nested loops

## Level 11: The Window Pattern (i + j)

* [ ] Core explanation: text[i + j] === word[j], match, mismatch, and allMatched logic
* [ ] Basic task: Understand how to manually check whether a string starts with a given word
* [ ] Applied task: Understand how to manually check whether a string contains a given word anywhere
* [ ] Advanced task: Understand how to find the first index of a word inside a string
* [ ] Cumulative task: Understand how to remove every occurrence of a full word from a string

## Level 12: Manual Control of i

* [ ] Core explanation: controlling i manually, jumping after a match, and using i += pattern.length - 1
* [ ] Basic task: Understand how to skip a fixed-size chunk of characters
* [ ] Applied task: Understand how to jump over a matched word entirely without re-scanning
* [ ] Advanced task: Understand how to replace every occurrence of a word with another word of a different length
* [ ] Cumulative task: Understand how to manually split a string on a delimiter without using split()

## Level 13: Building Custom String Functions

* [ ] Basic task: Understand how to build customLength and customAt manually
* [ ] Applied task: Understand how to build customIncludes and customStartsWith manually
* [ ] Advanced task: Understand how to build customIndexOf, customLastIndexOf, and removeDuplicates manually
* [ ] Cumulative task: Understand how to build customSplit and customReplaceAll manually without relying on built-in methods

## Level 14: Capstone Project — Text Sanitizer & Analyzer

* [ ] V1: Understand how to clean a raw string by removing special characters only
* [ ] V2: Understand how to compute character frequency statistics
* [ ] V3: Understand how to remove consecutive duplicates and replace patterns
* [ ] V4: Understand how to find and delete a target word, then sort unique characters alphabetically
* [ ] Ready for Arrays
