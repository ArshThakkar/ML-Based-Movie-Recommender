# CineSage: Smart Movie Recommendations Web App

CineSage is a smart movie recommendations web application that provides personalized movie suggestions based on user preferences and movie genres. Built using Streamlit and Python, CineSage integrates machine learning algorithms to deliver accurate and customized movie recommendations to users.

## Features

- **User-Friendly Interface**: CineSage offers an intuitive and easy-to-use interface for users to explore movie recommendations effortlessly.
  
- **Multiple Recommendation Types**: Users can choose between different recommendation types, including movie-based and genre-based recommendations, to suit their preferences.
  
- **IMDb Integration**: The application integrates with IMDb to fetch movie information, including director, cast, story, and IMDb rating, providing comprehensive insights for users.
  
- **Dynamic Movie Posters**: CineSage dynamically fetches movie posters from IMDb to enhance the visual experience of users browsing movie recommendations.
  
- **Customizable Recommendations**: Users can adjust parameters such as IMDb score and the number of recommended movies to tailor the recommendations to their liking.

## Installation

To run CineSage locally, follow these steps:

1. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/your-username/cinesage.git
   ```
   
2. Navigate to the project directory.
   ```bash
   cd cinesage
   ```
   
3. Install the required dependencies using pip.
   ```bash
   pip install -r requirements.txt
   ```
   
4. Run the Streamlit application.
   ```bash
   streamlit run app.py
   ```

5. Access the web application in your browser at `http://localhost:8501`.

## Usage

1. Visit the CineSage web app hosted at [link]().
   
2. Select the type of recommendation you prefer (movie-based or genre-based).
   
3. Choose your preferred movie or movie genres.
   
4. Optionally, select whether you want to fetch movie posters.
   
5. Adjust additional parameters such as IMDb score and the number of recommended movies.
   
6. Explore personalized movie recommendations and discover your next favorite film!

## Technologies Used

- **Streamlit**: Front-end framework for building interactive web applications in Python.
  
- **Python**: Programming language used for application logic and backend processing.
  
- **Beautiful Soup**: Python library for web scraping IMDb data to provide movie information.
  
- **PIL**: Python Imaging Library for image processing and displaying dynamic movie posters.

## Contributing

Contributions to CineSage are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
