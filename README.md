# Recowatch - Movie Recommendation Website

Recowatch is a web-based application that provides movie recommendations based on user input. This application is built using the Flask web framework and utilizes cosine similarity to determine the top 5 most similar movies based on several indicators, including ratings, genres, and directors of the movies.

## Features

- **Movie Recommendation**: Users can input the name of a movie they like, and Recowatch will provide recommendations for similar movies.
- **Cosine Similarity**: The application uses cosine similarity to calculate the similarity between movies, taking into account various factors like user ratings, genres, and directors.
- **User-Friendly Interface**: The web-based interface is intuitive and easy to use, allowing users to quickly find movie recommendations.

## Getting Started

To run the Recowatch application on your local machine, follow these steps:

1. **Clone the Repository**:
```
git clone https://github.com/othmanlutfii/recowatch.git
```

2. **Install Dependencies**:

Use the provided `requirements.txt` file to install the required packages:
```
pip install -r requirements.txt
```

3. **Run the Application**:

Start the Flask development server:
```
python webapp.py
```
4. **Access the Application**:

Open a web browser and go to http://localhost:5000 to access the Recowatch website.



