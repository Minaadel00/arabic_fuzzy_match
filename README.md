# Arabic Fuzzy Matching with RapidFuzz

This Python script performs advanced fuzzy matching for Arabic text, specifically optimized for company names and addresses. It cleans Arabic text, removes common stopwords, and uses a hybrid scoring approach (Token Set + Token Sort) via the `rapidfuzz` library to map messy distributor records to a master company list.

## Features
- Arabic letter normalization (أ, إ, آ -> ا) etc.
- Smart blocking to optimize performance.
- Hybrid scoring for high accuracy.
- Progress tracking using `tqdm`.

## Installation
```bash
pip install -r requirements.txt