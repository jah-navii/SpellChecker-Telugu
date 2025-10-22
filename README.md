# Telugu Spell Checker

A simple Telugu Spell Checker using Levenshtein distance and prefix-based grouping.

## Repository Link  
[View on GitHub](https://github.com/jah-navii/SpellChecker-Telugu)

## Setup

1. Clone the repo and open the folder.  
2. Open checker.ipynb in Google Colab for better results
3. Upload vocabulary.txt in the runtime of google colab
4. Run all cells in the notebook
5. Type telugu words to check spelling. Type 'exit' to quit.

## How it works

- Loads Telugu words from `vocabulary.txt`
- Groups words by prefixes for fast lookup
- Calculates Levenshtein distance between input and candidates
- Suggests top 3–5 closest matches for misspelled words

## Example Test Words

పుస్తకము → పుస్తకం  
విధ్యార్ధి → విద్యార్థి  
ప్రబుత్వం → ప్రభుత్వం  
మనసి → మనిషి  
ఆకాసం → ఆకాశం  

## Dataset

Use a cleaned Telugu vocabulary file with one word per line.  
You can improve results with datasets like:
- AI4Bharat IndicNLP Catalog  
- IndoWordNet  
- L3Cube IndicNews  
