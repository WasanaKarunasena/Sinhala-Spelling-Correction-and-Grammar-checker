Sinhala Text Spell and Grammar Checker
This project implements a Sinhala language spell and grammar checker using pre-trained models and a dictionary-based approach for spell correction. It includes functionalities for correcting spelling mistakes, grammar errors in Sinhala text.

Features
Spell Correction: Detect and correct spelling mistakes in Sinhala text using a dictionary-based approach.
Grammar Checking: Use a pre-trained grammar correction model to identify grammar issues and provide suggestions.
User-Friendly Outputs: Results are saved as text files and visualized as screenshots for easy interpretation.
Batch Processing: Analyze multiple paragraphs in multiple runs to evaluate accuracy.

Installation


Clone the repository:


git clone https://github.com/WasanaKarunasena/Sinhala-Spelling-Correction-and-Grammar-checker.git
cd Sinhala-Spelling-Correction-and-Grammar-checker
Install required Python packages:


pip install -r requirements.txt


Download and prepare the grammar correction model:

Place the pre-trained Sinhala grammar model in the models/sinhala_grammar_model directory.

Upload a Sinhala spell dictionary:

Use the upload function in the script or save your dictionary as spell_dictionary.txt in the project root directory.

Format: incorrect_word,correct_word (one pair per line).
