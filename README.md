# RecommendationPal: Tag & Title Based Book & Movie Recommender

PersonalPal is a content-based recommendation system that suggests books and movies based on user-defined tags, using TF-IDF and cosine similarity.
It demonstrates how simple natural language inputs can be transformed into meaningful content recommendations through machine learning techniques.
## Features
- Content-based filtering using TF-IDF and cosine similarity
- Accepts user-defined tags (e.g., "thriller", "magic", "romance")
- Recommends both books and movies
- Built entirely in Jupyter Notebook with clear, modular logic
## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

## Project Structure
Recommendations-pal-ML-Project/

├── personalpal.ipynb # Main notebook

├── Data/ # Folder for datasets (excluded from GitHub)

├── README.md

├── .gitignore

└── requirements.txt

## External Datasets

Due to GitHub's file size limits, the complete dataset (including files >100MB) is hosted on Google Drive.
Download all 8 datasets from the link below and place them in a folder named `Data/` inside the project directory:
Download: [Google Drive Folder](https://drive.google.com/drive/folders/136fX_Jzk3j4Gs6tjVNYXwoc7k1LSnzow?usp=sharing)
## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Varshith2403315/Recommendations-pal-ML-Project.git
   cd Recommendations-pal-ML-Project
2. Download the datasets and move them into a folder called Data/ in the project root.
3. pip install -r requirements.txt
4. jupyter notebook personalpal.ipynb
