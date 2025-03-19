# Star Wars Script Analysis

This is a comprehensive text analysis project based on **Star Wars movie scripts** as part of the final project for the course **DS 5001 Exploratory Text Analytics (Spring 2024)**.
The project explores linguistic and narrative patterns across the six Star Wars episodes using diverse Natural Language Processing techniques and modeling workflows.

---

## Overview

The goal of this project is to analyze the Star Wars scripts corpus, going through the entire text analytics pipeline from data exploration to model interpretation. The analysis investigates stylistic and narrative structures within the scripts and identifies thematic, emotional, and semantic patterns.

### Data & Corpus:
- Six Star Wars episodes (Episodes I to VI) sourced from [IMSDb](https://imsdb.com/), freely available for educational use.
- Parsed into structured tables (F2-F5 levels) following the Standard Text Analytic Data Model.

---

## Techniques Used
- **Text Preprocessing**: Parsing scripts into structured formats (dialogue, descriptions, scenes)
- **Corpus Annotation**: POS tagging, tokenization, OHCO structure (movie > scene > paragraph > sentence > token)
- **TF-IDF Modeling**: Including reduced & normalized TF-IDF matrices
- **PCA (Principal Component Analysis)**: Variance and polarity analysis of script structure
- **LDA Topic Modeling**: Extracting latent topics across the corpus
- **Sentiment Analysis**: Lexicon-based sentiment mapping over chapters
- **Word2Vec & t-SNE**: Semantic clustering of terms
- **Visualizations**: PCA scatterplots, topic heatmaps, sentiment trends, network graphs

---

## Key Findings
- **Episodes IV-VI** show more variance in narrative structure compared to Episodes I-III, which align with their more dynamic storytelling and longer scripts.
- Sentiment analysis revealed that Episodes IV-VI show more emotional fluctuations (spikes of fear, surprise, and sadness), whereas Episodes I-III are more stable.
- PCA and LDA models successfully capture thematic clusters like *space battles*, *Jedi order*, and *starships* (e.g., Millennium Falcon, X-Wings).
- Word2Vec t-SNE visualization highlighted clusters of terms related to iconic Star Wars elements, such as *spaceships* and *Rebel Alliance characters*.
- The project supports the hypothesis that the storytelling approach and sentiment consistency might have contributed to the lower reception of Episodes I and II.

---

## Project Structure
- /notebooks/ #Jupyter notebooks for each modeling steps including exploratory process and results of each steps
- /data/ # Raw Star Wars scripts and materials needed for analysis
- /outputs/ # Model outputs and visualizations
- Readme.md #Project documentation

---

## How to Run
1. Clone this repository: git clone https://github.com/kmjhyn/star-wars-text-analysis.git
2. Open notebooks inside '/notebooks/' folder
3. Install dependencies
4. Follow notebooks sequentially from data preprocessing to model interpretation

*[Dataset can also be downloaded here(UVABOX)](https://virginia.box.com/s/84pl47ozfsggqgjvch5io0tekdzw51aw)*

---

## About the Course
- Course: DS 5001 Exploratory Text Analysis
- Instructor: Prof. Rafael Alvarado
- Institution: University of Virginia
- Semester: Spring 2024

---

## Contact
- Name: Ji Hyun Kim
- Github: [kmjhyn](https://github.com/kmjhyn/)
- Email: [school](mqa4qu@virginia.edu) [personal](jihyunkim1620@gmail.com)
- LinkedIn: [linkedin.com/in/jihyunkim1620](https://www.linkedin.com/in/jihyunkim1620/)
