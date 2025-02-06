Movie Recommendation System
see demo: http://18.233.147.185:8501/

Overview
This project is a movie recommendation system developed using Python, Streamlit, and the TMDB dataset. The system analyzes user preferences to provide personalized movie suggestions, enhancing the overall viewing experience.

Technologies Used
Python
Streamlit
TMDB API
Pandas
NumPy
scikit-learn
Features
User-Friendly Interface: Built with Streamlit, allowing users to interact easily and receive real-time recommendations.
Personalized Recommendations: Utilizes cosine similarity for collaborative filtering, offering tailored movie suggestions based on user input.
Data Processing: Processes and analyzes the TMDB dataset to extract relevant movie information.
ScreenShot
Screenshot 2024-10-22 210257

Installation
Clone the repository:

git clone https://github.com/2003saurabh/movie-recommendation-system.git
cd movie-recommendation-system
Install the required packages:

pip install -r requirements.txt
Run the Streamlit application:

streamlit run app.py
Usage
Open the application in your web browser.
Input your preferences, and receive personalized movie recommendations.
Future Enhancements
Incorporate user ratings and feedback for improved personalization.
Expand the dataset to include more diverse movie options.
License
This project is licensed under the MIT License.

Acknowledgments
TMDB for providing the movie dataset.
Streamlit for the user-friendly interface framework.
