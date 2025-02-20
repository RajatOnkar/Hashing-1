# Hashing-1
Explain your approach in **three sentences only** at top of your code


## Problem 1:
Given an array of strings, group anagrams together.

Example:
Input: ["eat", "tea", "tan", "ate", "nat", "bat"],
Output:
[
  ["ate","eat","tea"],
  ["nat","tan"],
  ["bat"]
]

Note:
All inputs will be in lowercase.
The order of your output does not matter.
#
# Generate a prime product for all character combinations. Even if the characters are interchanged the
# product remains the same.
# Initialize a hashmap and store all the combinations that match the product.
# Return the result strings in the form of array else it will be an empty string.
#


## Problem 2:
Given two strings s and t, determine if they are isomorphic.
Two strings are isomorphic if the characters in s can be replaced to get t.
All occurrences of a character must be replaced with another character while preserving the order of characters. No two characters may map to the same character but a character may map to itself.

Example 1:
Input: s = "egg", t = "add"
Output: true

Example 2:
Input: s = "foo", t = "bar"
Output: false

Example 3:
Input: s = "paper", t = "title"
Output: true
Note:
You may assume both s and t have the same length.
#
# Generate a prime product for all character combinations. Even if the characters are interchanged the
# product remains the same.
# Initialize a hashmap and store all the combinations that match the product.
# Return the result strings in the form of array else it will be an empty string.
#

## Problem 3:
Given a pattern and a string str, find if str follows the same pattern.
Here follow means a full match, such that there is a bijection between a letter in pattern and a non-empty word in str.

Example 1:
Input: pattern = "abba", str = "dog cat cat dog"
Output: true

Example 2:
Input:pattern = "abba", str = "dog cat cat fish"
Output: false

Example 3:
Input: pattern = "aaaa", str = "dog cat cat dog"
Output: false

Example 4:
Input: pattern = "abba", str = "dog dog dog dog"
Output: false
Notes:
You may assume pattern contains only lowercase letters, and str contains lowercase letters that may be separated by a single space.
#
# For the given pattern string we have to check whether the characters of first string if replaced by 
# words is exactly identical.
# We will initialize two hashmaps. store the first string array character as key and word
# of second string array as value.
# If the word does not exist we append, else we will check if the character has a different word 
# stored we return False. If everything matches we return True.
#