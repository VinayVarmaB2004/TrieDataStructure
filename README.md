# TrieDataStructure
🔥 Project Title:
Enhanced Trie-Based Word Search with Auto-Correction, Wildcard Matching, and Real-Time Suggestions

💡 Project Overview:
This project is a Streamlit-based web application that allows users to search for words dynamically using an enhanced Trie data structure. The application provides real-time suggestions as the user types, offering:

Prefix matching
Auto-correction for typos
Wildcard support (* and ? patterns)
Real-time dynamic suggestions without pressing Enter
Beautiful UI with a responsive and stylish design

🚀 Tech Stack:
Backend: Python with Trie implementation
UI Framework: Streamlit for building an interactive web application
Data Source: NLTK's WordNet dataset for word definitions
Styling: Custom CSS for a modern, sleek, and visually appealing interface

💻 How It Works:
Input Handling:

Users type a word or wildcard pattern in the input field.
The query is stored in Streamlit’s session state, enabling real-time updates.
Search Logic:

If the query contains wildcards (* or ?), the app performs a wildcard search.
Otherwise, it uses prefix matching to suggest words.
If no matches are found, the app applies auto-correction using Levenshtein distance.
Display:

The app shows two-column suggestions with word meanings.
If no results are found, it displays a "No matches found" message.
