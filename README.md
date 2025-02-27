Character Interaction Analysis in Pride and Prejudice Using a Knowledge Graph

Project Description

This project analyzes the interactions between characters in Pride and Prejudice by Jane Austen using a knowledge graph. The goal is to visualize and quantify how often characters interact throughout the novel. The analysis includes visualizing character relationships both within individual chapters and across the entire book, offering insights into the dynamic between key characters.

Steps:
Text Preprocessing:

The text is sourced from Project Gutenberg and cleaned to remove headers, footers, and non-novel content.
The novel is split into individual chapters using regular expressions to detect chapter markers.
Character Identification:

A list of primary characters and their aliases (e.g., "Lizzy" for Elizabeth Bennet, "Mr. Darcy" for Fitzwilliam Darcy) is used to track mentions of characters in the text.
Interaction Analysis:

For each chapter, a network graph is constructed where nodes represent characters, and edges between them represent interactions based on their co-occurrence in the same chapter. The interaction frequency is represented as edge weights.
Visualization:

The interaction data is visualized using network graphs to depict character relationships both within individual chapters and across the entire novel.
A final cumulative graph is generated to represent the overall character dynamics throughout the story.
Knowledge Graph:

The project outputs a knowledge graph that enables deeper exploration of character interactions and the relational structure of Pride and Prejudice.
Requirements
Python 3.x
Libraries:
nltk
networkx
matplotlib
requests
re
Installation
Clone this repository:

bash
Copy
Edit
git clone https://github.com/data-whisperer/Knowledge graph.git
Install the necessary Python dependencies:

nginx
Copy
Edit
pip install -r requirements.txt
Make sure to download the novel text from Project Gutenberg (or use the provided text file if included).

Usage
Run the main script to generate the interaction network:

nginx
Copy
Edit
python analyze_interactions.py
The script will generate network graphs in .png format for each chapter and a final cumulative graph for the entire novel.

Contributing
Feel free to fork the repository, submit issues, or create pull requests. Contributions are always welcome!

Acknowledgments
The text of Pride and Prejudice is available in the public domain from Project Gutenberg: Pride and Prejudice on Project Gutenberg.
The networkx library for network graph creation.
The nltk library for text preprocessing.
