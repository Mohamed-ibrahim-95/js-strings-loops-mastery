# JavaScript Strings & Loops Mastery — Progress Tracker

Difficulty tiers per level: Easy → Medium → Strong → Dragon (cumulative — each tier pulls in more concepts from previous levels).

## Level 0: Absolute Foundations
- [ ] Theory understood (variables, for-loop anatomy, comparisons, console.log)
- [ ] Easy: Print "Hello World" 5 times using a loop
- [ ] Medium: Print numbers 1→10, then 10→1
- [ ] Strong: Print even numbers 1-20 using modulo
- [ ] Dragon: Multiplication table with formatted template literal output

## Level 1: Pointer Movement (i)
- [ ] Theory understood (index, text.length, i++/i--, out-of-bounds)
- [ ] Easy: Print each character with its index
- [ ] Medium: Print the string in reverse (backward loop)
- [ ] Strong: Print every 3rd character (i += 3) without going out of bounds
- [ ] Dragon: Print every adjacent pair of characters + their index, safely

## Level 2: Building New Strings with result
- [ ] Theory understood (immutability, result += text[i])
- [ ] Easy: Copy a string using result
- [ ] Medium: Copy string without first and last character
- [ ] Strong: Reverse string using result = char + result (no backward loop)
- [ ] Dragon: Split even-index and odd-index characters into one result, log each step

## Level 3: Deletion via Skipping
- [ ] Theory understood (skip logic = deletion)
- [ ] Easy: Remove all spaces from a sentence
- [ ] Medium: Remove all digits from a string
- [ ] Strong: Remove only the first occurrence of a character (flag-based)
- [ ] Dragon: Clean a username (spaces + digits + first duplicate letter only)

## Level 4: Modification & Replacement
- [ ] Theory understood (replace vs delete vs keep)
- [ ] Easy: Replace all underscores with spaces
- [ ] Medium: Replace only the first occurrence of a character
- [ ] Strong: Replace every digit with double its value
- [ ] Dragon: Password sanitizer (@ → a, remove dashes, first X deleted / second X → !)

## Level 5: Counting with count
- [ ] Theory understood (why char comparisons work — ASCII/Unicode ranges)
- [ ] Easy: Count spaces in a sentence
- [ ] Medium: Count uppercase letters using character range
- [ ] Strong: Count special characters (not digit, not letter)
- [ ] Dragon: Count special characters AND build a letters-only result in one loop

## Level 6: Comparing Current vs Previous/Next Character
- [ ] Theory understood (text[i-1], text[i+1], boundary protection)
- [ ] Easy: Detect if each character differs from the next one
- [ ] Medium: Count consecutive "++" occurrences
- [ ] Strong: Count letters immediately followed by a digit
- [ ] Dragon: Count negated letters (preceded by "!") + strip "!" into result

## Level 7: Consecutive Duplicates
- [ ] Theory understood (group logic, N-1 rule)
- [ ] Easy: Count consecutive duplicate pairs in a word
- [ ] Medium: Remove consecutive duplicates, keep one per group
- [ ] Strong: Compress string ("aaabbc" → "a3b2c1")
- [ ] Dragon: Clean chat spam ("goooood morninggg") + count total spam chars

## Level 8: Global Duplicates
- [ ] **Scope lesson understood** (variable inside vs outside loop — persistent vs temporary)
- [ ] Theory understood (nested loops, text[i] === text[j] vs text[i] === text[i+1])
- [ ] Easy: Count how many times a specific character appears in the whole string
- [ ] Medium: Nested loop — print each character's total count (redundant printing expected)
- [ ] Strong: Fix redundant counting using an "already counted" check
- [ ] Dragon: Find the first non-repeating character (classic interview problem)

## Level 9: Flags (found / boolean state)
- [ ] Theory understood (false→true "does it exist?" vs true→false "is everything valid?")
- [ ] Easy: Does the string contain a digit? (loop-based, no includes)
- [ ] Medium: Are all characters digits?
- [ ] Strong: Does the string contain any duplicate character?
- [ ] Dragon: Validate a username (starts with letter + no special chars + no long consecutive repeats)

## Level 10: Nested Loops (formal i & j)
- [ ] Theory understood (outer/inner loop relationship, when j starts at 0 vs i+1)
- [ ] Easy: Print every possible (i, j) character pair
- [ ] Medium: Compare each character only with characters after it (j = i+1)
- [ ] Strong: Prevent double-counting duplicates using flag + nested loop
- [ ] Dragon: Sort characters alphabetically (simple Bubble Sort with nested loops)

## Level 11: The Window Pattern (i + j)
- [ ] Theory understood (text[i+j] === word[j], match/mismatch, allMatched)
- [ ] Easy: Does the string start with a given word? (manual startsWith)
- [ ] Medium: Does the string contain a given word anywhere? (manual includes)
- [ ] Strong: Find the first index of a word inside a string
- [ ] Dragon: Remove every occurrence of a full word from a string

## Level 12: Manual Control of i
- [ ] Theory understood (i += pattern.length - 1, jumping after a match)
- [ ] Easy: Skip a fixed-size chunk of characters (every 3 chars)
- [ ] Medium: Jump over a matched word entirely, no re-scanning
- [ ] Strong: Replace every occurrence of a word with a different-length word
- [ ] Dragon: Manually split a string on a delimiter (no split())

## Level 13: Building Custom String Functions
- [ ] Easy: customLength + customAt
- [ ] Medium: customIncludes + customStartsWith
- [ ] Strong: customIndexOf + customLastIndexOf + removeDuplicates
- [ ] Dragon: customSplit + customReplaceAll (fully manual, no built-ins)

## Level 14: Capstone Project — Text Sanitizer & Analyzer
- [ ] V1 (Easy): Clean the raw string (remove special characters only)
- [ ] V2 (Medium): + Compute character frequency statistics
- [ ] V3 (Strong): + Remove consecutive duplicates + replace patterns
- [ ] V4 (Dragon): + Find and delete a target word + sort unique characters alphabetically
- [ ] **Ready for Arrays** 🎉
