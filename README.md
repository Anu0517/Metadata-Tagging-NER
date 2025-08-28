# Metadata-Tagging-NER

A spaCy-based tool for named entity recognition (NER) to extract metadata (e.g., persons, organizations) from news text.

## Overview
- **Purpose**: Tags entities in news articles for metadata extraction.
- **Tech Stack**: Python, spaCy, Pandas, NumPy.
- **Dataset**: News Category Dataset from Kaggle (Data_Train and Data_Test CSV files).

## Setup
1. Clone the repository:
git clone https://github.com/Anu0517/Metadata-Tagging-NER.git
cd Metadata-Tagging-NER

2. Install dependencies:
pip install -r requirements.txt
!python -m spacy download en_core_web_sm

3. Download the News Category Dataset from Kaggle[](https://www.kaggle.com/datasets/akash14/news-category-dataset) and place `Data_Train.csv` and `Data_Test.csv` in `data/`.

## Usage
- Open `notebooks/metadata_tagging_ner.ipynb` in Google Colab.
- Upload `Data_Train.csv` and `Data_Test.csv` and run all cells sequentially.
- View the entity type distribution visualization and download `person_entities.csv` if the notebook confirms file creation.

## Results
- Extracts entities like PERSON, ORGANIZATION; displays distribution via visualization.

## Files
- `notebooks/metadata_tagging_ner.ipynb`: Main notebook with entity tagging, visualization, and file-saving.
- `data/Data_Train.csv`: [Input training dataset](https://www.kaggle.com/datasets/akash14/news-category-dataset)
- `data/Data_Test.csv`: [Input test dataset](https://www.kaggle.com/datasets/akash14/news-category-dataset)
- `requirements.txt`: Dependency list.

## Future Improvements
- Fine-tune spaCy model with custom data.
- Add PDF support with PyPDF2.
- Expand to more entity types or enhance visualization.

## Contact
- GitHub: [Anu0517](https://github.com/Anu0517)
