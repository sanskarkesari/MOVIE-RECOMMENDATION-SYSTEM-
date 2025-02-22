# Movie Recommendation System

## Overview
This project implements a **Movie Recommendation System** using **Collaborative Filtering, Content-Based Filtering, and a Hybrid Model** to deliver personalized movie recommendations. The system processes data, applies machine learning models, and presents recommendations through a user-friendly interface.

## Features
- **Collaborative Filtering**: Recommends movies based on similar users' preferences.
- **Content-Based Filtering**: Suggests movies with similar attributes to those a user has liked.
- **Hybrid Model**: It Combines both approaches for improved accuracy.

## Dataset
- **MovieLens 100K Dataset**
- Contains **100,000 ratings** from **943 users** on **1,682 movies**
- Includes movie metadata such as title, genre, and release year

## Tech Stack
- **Data Processing**: MySQL, Python
- **Machine Learning**: Collaborative Filtering, Content-Based Filtering, Hybrid Model
- **Backend**: JSP, MongoDB 
- **Deployment**: Google Colab for model training and processing.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/sanskarkesari/movie-recommendation-system.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Set up the MySQL database and import dataset.
4. Run data processing scripts in Google Colab.
5. Execute python scripts for each recommendation model.
6. Load results into colab properly.

## Usage
1. **Upload MovieLens Dataset** to MySQL.
2. **Process Data** using Google Colab.
3. **Access Web GUI** to view recommendations.

## Results
- **Collaborative Filtering RMSE**: 1.9488
- **Content-Based Filtering RMSE**: 1.1257
- **Hybrid Model RMSE**: 1.2717
- The **Hybrid Model** provided the best recommendation accuracy.

## Contributors
- **Vikrant Kumar Singh**  
- **Priyanshu Dalakoti**  
- **Sanskar Kesari**  
- **Devansh Bhavsar**  

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- **MovieLens Dataset by University of Minnesota**
- **Apache Hadoop & Big Data Tools**

