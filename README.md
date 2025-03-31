# Movie Recommender System

This is a simple **Movie Recommender System** built using **Streamlit** and **TMDB API** to fetch movie posters. It suggests movies based on similarity scores.

## Features
- Select a movie from the dropdown list.
- Get five movie recommendations based on similarity.
- Displays posters of recommended movies.

## Tech Stack
- Python
- Streamlit
- Pandas
- Pickle
- Requests (for API calls)
- TMDB API

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/movie-recommender.git
   ```
2. Navigate to the project folder:
   ```sh
   cd movie-recommender
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Running the Application
Run the Streamlit app using:
```sh
streamlit run app.py
```

## Project Structure
```
├── app.py                        # Main Streamlit app
├── datasets                      # contains the datasets used in this project
├── Movie Recommender.ipynb       # jupyter notebook
├── requirements.txt              # Required Python dependencies
├── README.md                     # Project documentation
```

## TMDB API Key
Make sure you have a valid TMDB API key. Update `fetch_poster` function in `app.py` with your API key:
```python
url = f"https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY&language=en-US"
```

## Contributing
Feel free to fork the repo, make changes, and submit a pull request!


