# Anagram-Finder

![image](https://github.com/deeparsh7/AnagramFinder/assets/121679549/04e0ab8a-6476-4dc9-a676-305c911019fe)


Anagram Finder is a Python script that helps you identify pairs of anagram words within a given list of words. Anagrams are words or phrases formed by rearranging the letters of another word or phrase, typically using all the original letters exactly once.

** About the Project**

This project aims to help you quickly identify pairs of anagram words within a given list of words. It utilizes a Python script that employs an efficient anagram-checking algorithm, based on sorting and set operations, to accurately and rapidly identify anagram pairs.

**Getting Started**

To use the Anagram Finder, follow these instructions:

To open and run the code in Google Colab, follow these steps:

Go to the GitHub repository containing the code : https://github.com/deeparsh7/AnagramFinder

Click on the AnagramFinder.ipynb notebook file.

On the top-left corner of the notebook page, you'll see a "Open in Colab" button. Click on it to open the notebook in Google Colab.

Open in Colab

Google Colab will open the notebook in a new tab. You can now run the code .

**Prerequisites**

- Python 3.x

**How It Works**
This script checks for anagrams in a list of words provided by the user. It defines a function are_anagrams(text1, text2) that determines if two words are anagrams by sorting their characters and comparing them. The user is prompted to input words separated by spaces or commas.

The script initializes data structures: an empty list for words, a set for visited words, and a list for anagram_pairs.

It iterates through the words list, avoiding duplicate comparisons, and checks for anagrams using the are_anagrams function. Anagrams are stored in the anagram_pairs list, and non-anagram words are stored in the non_anagram_set.

Finally, the script prints anagram pairs and non-anagrams if they exist, and displays a message if no anagram pairs or non-anagrams are found. The time and space complexity of the algorithm are explained in the previous responses.

**Functionality**
The Anagram Detector script provides the following functionality:

Accepts a list of words as input from the user.

Identifies anagram pairs within the input list using an efficient algorithm.

Displays the identified anagram pairs and non-anagram words.

Delivers clear and visually organized output, showcasing the identified anagram pairs and non-anagram words in a well-structured manner.

**Results**
The script will display the identified anagram pairs and non-anagram words from the input list, providing a clear distinction between the two categories.

**Time and Space Complexity**

The time complexity of the anagram detection algorithm implemented in this script is O(n^2), where 'n' is the number of words provided. 

The space complexity is O(n), where 'n' is the number of words provided.
 
In terms of efficiency, the space complexity is more efficient compared to the time complexity.



Contact
as7112@srmist.edu.in,arshdeep72140@gmail.com
