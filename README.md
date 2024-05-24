# Inverted-Index-for-document-retrieval
Implemented a simple Inverted Index for document retrieval for the text document collection using python.
This project implements a simple Inverted Index for text document retrieval. An inverted index is a data structure used to map content in documents to their locations. It enables efficient full-text search across a collection of documents.

Key Features:
Document Indexing:

The index_documents function reads all text documents in a specified directory.
It tokenizes the content of each document into words, converts them to lowercase, and creates an index mapping each word to the documents it appears in.
Document Retrieval:

The open_documents_containing_word function allows users to search for documents containing a specific word.
It opens the documents where the word is found using the system's default text editor.
Usage:
Indexing:

The directory containing the text documents is indexed by calling the index_documents function.
Each word in the documents is mapped to the filenames in which it appears.
Searching:

The user inputs a word to search.
The program looks up the word in the index and opens the corresponding documents.
This project demonstrates the basics of text processing, tokenization using the NLTK library, and file handling in Python. It provides a foundational approach to building more advanced document retrieval systems.






