# MovieMatcher: An Interactive Movie Recommendation Dashboard

## Overview
The Interactive Movie Recommendation System is a project designed to provide movie recommendations based on user input. Utilizing data from the GroupLens 25 million dataset, the project builds a recommendation system within a Jupyter Notebook environment. By leveraging libraries such as pandas, scikit-learn, and IPython widgets, the project creates an engaging and interactive experience for users to discover new movies.

The primary objective is to offer personalized movie suggestions by analyzing patterns in movie ratings and user preferences. The project includes data preprocessing, search engine development, and a recommendation engine. An interactive Jupyter Notebook interface allows users to input movie titles and receive tailored recommendations, making it a fun and insightful tool for movie enthusiasts.

## Project Implementation

### Data Preparation
- **Import Libraries:** Utilize pandas and re for data manipulation and cleaning.
- **Read Data:** Load `movies.csv` and `ratings.csv` files.
- **Clean Titles:** Remove special characters from movie titles for accurate search results.

### Building the Search Engine
- **TF-IDF Vectorization:** term frequency-inverse document frequency (TF-IDF) to convert movie titles into numerical format.
- **Cosine Similarity:** Calculate similarity between user input and existing movie titles.
- **Search Function:** Develop a function to clean input, transform it into a vector, and find the most similar movie titles.

### Developing the Recommendation Engine
- **User Identification:** Identify users who liked the same movies and find other movies they liked.
- **Filter Recommendations:** Narrow down recommendations to movies liked by a significant percentage of similar users.
- **Score Calculation:** Compare similarity ratios with the general user population to rank recommendations.

### Integrating Interactive Widgets
- **Input Widget:** Create a text box for movie title input.
- **Output Widget:** Display recommendations dynamically based on user input.
- **Observer Function:** Capture user input and update recommendations in real-time.

## Conclusion
The Interactive Movie Recommendation System showcases the application of data science and machine learning in providing personalized movie suggestions. It emphasizes the significance of leveraging historical data and user preferences to enhance user experiences. This project serves as an educational initiative, demonstrating the potential of interactive tools and recommendation systems in the entertainment industry. By blending data-driven insights and technological advancements, the system empowers users to discover new movies and enjoy a more tailored viewing experience.
