# news-language-classifier
Data analysis script used to classify social media captions by emotional, sensational, and violent language patterns.
Script de análisis de datos utilizado para clasificar los textos de publicaciones en redes sociales según patrones de lenguaje emocional, sensacionalista y violento.


*Media Caption Language Analysis*

Overview

This project is a Python-based exploratory analysis of media captions. It applies rule-based text processing to classify captions according to the presence of emotional language, excessive adjectives, and violence-related vocabulary.


*Methodology*

The process includes:

Text normalization (lowercasing, removing accents, cleaning whitespace)

Rule-based matching against predefined vocabularies:
Emotional language
Excessive adjectives
Violence-related terms
Scoring system to estimate content intensity (scale 1–5)

The script generates three main columns:

tiene_lenguaje_problematico: indicates whether any target vocabulary is present
nivel_intensidad: score from 1 to 5 based on language intensity
categorias_identificadas: labels indicating detected language categories

Tools Used
Python
pandas
re (regular expressions)
unicodedata
tqdm


Author

Lía Barrios
