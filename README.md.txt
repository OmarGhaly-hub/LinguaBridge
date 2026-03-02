# LinguaBridge
### English-Arabic Linguistic Contrast Analyzer

LinguaBridge is a Python-based NLP tool that analyzes any English sentence 
and explains its key structural and grammatical differences from Arabic.

## Motivation
Language should not be a barrier to knowledge. LinguaBridge was built to 
help language learners understand not just *what* a translation is, 
but *why* the structure changes between English and Arabic.

## Features
- Detects 8 linguistic contrast rules automatically
- Uses spaCy for grammatical analysis
- Rules curated by a linguistics specialist

## Rules Detected
1. Copula dropping
2. Definite article differences
3. Indefinite article absence
4. Adjective-noun order reversal
5. Plural distinction (including Muthanna)
6. Subject-verb order
7. Grammatical gender
8. Object pronoun attachment

## Tech Stack
- Python
- spaCy (en_core_web_sm)

## How to Run
1. Install spaCy: `pip install spacy`
2. Download model: `python -m spacy download en_core_web_sm`
3. Open `LinguaBridge.ipynb` in Jupyter Notebook
4. Run all cells