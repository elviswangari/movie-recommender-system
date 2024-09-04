# Movie Recommender System

## Overview

This project is a comprehensive Movie Recommender System that suggests movies based on user preferences and movie features. It leverages various machine learning techniques including collaborative filtering, content-based filtering, and hybrid models to deliver personalized recommendations.

## Features

- **Data Cleaning:** Handles missing values, outliers, and ensures data consistency.
- **Exploratory Data Analysis (EDA):** Visualizes user behavior, rating distributions, and genre popularity.
- **Feature Engineering:** Constructs user-movie interaction matrices and applies dimensionality reduction techniques.
- **Modeling:** Implements collaborative filtering, matrix factorization (SVD, NMF), content-based filtering, and hybrid models.
- **Evaluation:** Assesses model performance using metrics like RMSE, Precision, and Mean Average Precision.
- **Deployment:** Includes API development for serving recommendations and integration with web or mobile applications.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/elviswangari/movie-recommender-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd movie-recommender-system
    ```

3. Install required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preparation:** Place your movie and rating datasets in the `data/` directory.
2. **Run EDA:** Use the provided notebooks to perform exploratory data analysis and visualization.
3. **Train Model:** Run the training scripts to build the recommendation model.
4. **Serve Recommendations:** Use the API script to serve recommendations to users.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
