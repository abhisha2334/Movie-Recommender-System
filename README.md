

🎥 Movie Recommender System

Overview
This project is a Movie Recommender System that suggests the top 5 movies similar to a user-selected movie based on content similarity. The system uses vectorization techniques and cosine similarity to measure how closely related the movies are in terms of content (such as genres, descriptions, and keywords).

The project includes:
- A Machine Learning model that processes movie data and computes similarities.
- A Streamlit-based frontend for user interaction.
- Streamlit deployment for easy access and demonstration.

Table of Contents:
- Features
- Tech Stack
- Dataset
- Installation
- Usage
- Project Structure
- How It Works
- Deployment
- Contributing
- License

---

Features
- Movie Search: Select a movie from the database, and get 5 similar movies as recommendations.
- Content-based Filtering: The model recommends movies based on the content of the selected movie using cosine similarity.
- Interactive UI: A simple, intuitive interface built with Streamlit for easy user interaction.
- Scalable Deployment: Deployed on streamlit cloud for easy access and scalability.

---

Tech Stack

Backend:
- Python: Core programming language used.
- Pandas & NumPy: For data manipulation and computation.
- Scikit-learn: Used for vectorization (CountVectorizer) and calculating cosine distance.

Frontend:
- Streamlit: Python framework for creating interactive web apps.

Deployment:
- Streamlit cloud: Cloud platform for deployment.

---

Dataset
The dataset used contains:
- Movie titles
- Genres
- Overviews
- Keywords

These features are used to compute similarities between movies.

---

Installation

1. Clone the Repository

```bash
git clone https://github.com/your-username/movie-recommender-system.git
cd movie-recommender-system
```

2. Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install Dependencies

```bash
pip install -r requirements.txt
```

4. Run the App Locally

```bash
streamlit run app.py
```

---

Usage
1. Select a movie: Use the dropdown in the Streamlit app to select a movie from the database.
2. Get recommendations: The app will display the top 5 movies most similar to your selection.

Try the live version here: [Streamlit App Link](https://movie-recommender-system-evf8lqvyip2xcjzmak9eiq.streamlit.app/)

---

Project Structure
```
movie-recommender-system/
│
├── app.py                 # Streamlit app frontend
├── MoviePRO.ipynb               # ML model for movie recommendations
├── movies.csv             # Movie dataset
├── requirements.txt       # List of dependencies
├── app.py                 # Deployment
└── README.md              # Project documentation
```

---

How It Works

1. Data Preprocessing: The movie dataset is loaded and processed. This includes extracting key features such as genres, keywords, and overviews.
   
2. Vectorization: 
   - We use CountVectorizer to convert the text-based features into vectors.
   
3. Cosine Similarity: 
   - Cosine Similarity is calculated between the vectorized movies to determine how close or similar they are to one another.
   
4. Recommendations: 
   - Based on the similarity scores, the app recommends the top 5 movies that are most similar to the movie selected by the user.

---

Deployment

Streamlit Deployment Steps:
1.Create streamlit app: 
   - Log in to your streamlit account and create a new app.
   
2. Connect to your github repository:
   - Choose the branch and file.

3. Deploy the App:
   - Push your code to Streamlit.

4. Access the App:
   - The app will be accessible at the URL provided by Streamlit.

---

Contributing
Contributions are welcome! Feel free to open a pull request to improve the project.

---


Enjoy discovering new movies!

---

This version has the markdown syntax removed for a simpler text format. Let me know if you need any further modifications!
