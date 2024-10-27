# U.S.A-Presidential-Speech-Analysis-using-Machine-Learning
## Overview
This project analyzes the inaugural speeches of U.S. Presidents Franklin D. Roosevelt (1941), John F. Kennedy (1961), and Richard Nixon (1973). By leveraging the Natural Language Toolkit (NLTK) in Python, it performs a quantitative analysis of each speech's structure, including word count, character count, and sentence count, aiming to reveal stylistic and structural differences.

## Project Structure
### 1. Data Extraction
Dataset: The inaugural corpora dataset from the NLTK library retrieves the full text of each president's speech.
Speeches Extracted:
Roosevelt (1941)
Kennedy (1961)
Nixon (1973)
### 2. Text Preprocessing
Tokenization: Words and sentences are extracted from each speech for counting and further analysis.
Character, Word, and Sentence Counts: Each speech is analyzed to find the number of characters, words, and sentences, providing insight into speech length and density.
### 3. Feature Analysis
Character Count: Total characters per speech, excluding spaces and punctuation, are computed to understand length and verbosity.
Word Count: The number of words per speech provides a speech duration and pacing metric.
Sentence Count: Sentence counts indicate complexity and structure, which is useful for analyzing rhetorical style.
### Installation & Setup
git clone https://github.com/your-username/U.S.A-Presidential-Speech-Analysis.git
pip install -r requirements.txt
import nltk
nltk.download('inaugural')
nltk.download('punkt')
