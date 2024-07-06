# Book Recommender System

## Tech Stack
Tech Stack Used:
1. Python: Programming language used for developing the recommender system.
2. Flask: Micro web framework used for deploying the recommender system as a web application.
3. NumPy: Library used for numerical operations.
4. Pandas: Library used for data manipulation and analysis.
5. Gunicorn: Python WSGI HTTP Server for running the application in a production environment.
6. HTML, CSS: Used for creating the frontend of the web application, providing a user-friendly interface for interacting with the recommender system.

## Technique Used - Collaborative Filtering

## Data Source
The dataset used for the recommender system is taken from [Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset).

## Initial Setup for Recommender System Deployment

1. **Clone the Repository and Create a Virtual Environment**
   - Clone the repository and navigate into the project directory.
   - Create and activate a virtual environment.
   
   ```bash
   $ https://github.com/Notmrabhi/AspirenexBookRecommenderSystem.git
   $ cd BookRecommenderSystem
   ```

2. **Install Dependencies**
   
   ```bash
   $ (venv) pip install Flask==1.1.2 numpy==1.20.3 pandas==1.4.1 
   ```

3. **Prepare the Data**
   - Ensure you have the necessary data files in the appropriate directory.
   - You can preprocess the data using Pandas for creating a user-item interaction matrix or any other required formats.

4. **Run the Recommender System**
   - Run the Flask application to start the web server.
   
   ```bash
   $ python app.py
   ```

6. **For the Demo of the Project, watch the video tutorial**
   [Click here]([https://youtu.be/Ycsc2ugyIp0?si=J3q5oY9W9e78m9RH](https://youtu.be/hsnswqR760c?si=W6f4p46dfTATK0Lt)).

## Usage
Instructions on how to use your recommender system will be provided here. Describe how users can input their preferences and how the system generates recommendations.



Replace `yourusername` with your actual GitHub username and provide additional details specific to your project where necessary. This template includes the necessary steps for setting up, running, and optionally deploying the Book Recommender system using the specified tech stack.