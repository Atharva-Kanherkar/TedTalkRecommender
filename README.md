 Ted Talks Recommendation System

A machine learning-based recommendation system to suggest Ted Talks to users based on content similarity.

Table of Contents

Overview

Dataset

Technologies Used

Installation

Usage

Results

Contributing

License

Overview

This project builds a recommendation system using Natural Language Processing (NLP) techniques to suggest Ted Talks based on their descriptions. The system uses TF-IDF Vectorization and cosine similarity to find the most relevant talks.

Dataset

The dataset used is the Ted Talks dataset containing:

Title

Description

Tags

Speaker name

Views

Ratings

Technologies Used

Python

Pandas

Scikit-learn

Numpy

Flask (for serving recommendations via API)

Installation

Clone the repository:

git clone https://github.com/username/ted-talks-recommendation.git
cd ted-talks-recommendation

Install dependencies:

pip install -r requirements.txt

Download the dataset and place it inside the project folder.

Usage

Run the recommendation script:

python recommend.py

To get recommendations via API, start the Flask server:

python app.py

Visit http://localhost:5000/recommend?title=Your_Ted_Talk_Title to get recommendations.

Results

The system recommends top 5 similar talks based on their description similarity.

Example Output:

1. How to make stress your friend - Kelly McGonigal
2. The power of vulnerability - Brené Brown
3. Your elusive creative genius - Elizabeth Gilbert
4. Why we do what we do - Tony Robbins
5. The puzzle of motivation - Dan Pink

Contributing

Contributions are welcome! Feel free to submit a pull request.

License

This project is licensed under the MIT License.

