# Movie Recommender System

This project is a **Movie Recommender System** built using **Streamlit**, **Python**, and the **TMDb API**. 
It allows users to input a movie name and get recommendations for similar movies along with their posters.

---

## Features
- **Movie Recommendations**: Recommends movies similar to the user's input.
- **Poster Fetching**: Displays the poster of the recommended movies using the TMDb API.
- **Interactive UI**: A simple and user-friendly interface built with Streamlit.

---

## Installation

### Prerequisites
1. Python 3.7 or higher installed.
2. `pip` for managing Python packages.
3. An API key from [The Movie Database (TMDb)](https://www.themoviedb.org/).

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommender-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd movie-recommender-system
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Place the `movies.pkl` and `similarity.pkl` files in the project directory.

---

## Usage

1. Run the application:
   ```bash
   streamlit run app.py
   ```
2. Open the application in your browser (usually at `http://localhost:8501`).
3. Select a movie from the dropdown menu and click **Recommend**.
4. View the recommended movies and their posters.

---

## File Structure
```
movie-recommender-system/
|-- app.py                 # Main application file
|-- movies.pkl             # Preprocessed movie dataset
|-- similarity.pkl         # Precomputed similarity matrix
|-- movies.pkl             # Preprocessed movie dataset
|-- movies.pkl             # Preprocessed movie dataset
|-- requirements.txt       # Required Python libraries
|-- README.md              # Project documentation (this file)
```

---

## API Integration
This project uses **The Movie Database (TMDb) API** for fetching movie posters.

### Setting Up TMDb API
1. Sign up for a free account on [TMDb](https://www.themoviedb.org/).
2. Navigate to the **API** section in your account settings.
3. Generate an API key.
4. Replace the placeholder API key in `app.py` with your actual API key:
   ```python
   api_key = "your_api_key_here"
   ```

---

## Dependencies
- **Streamlit**: For building the web interface.
- **Pickle**: For loading preprocessed data.
- **Requests**: For making API calls to TMDb.

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

## Example
### Input
- Select a movie: "The Dark Knight"

### Output
- A list of 5 recommended movies along with their posters.
