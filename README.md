# Netflix Content Analysis

A comprehensive data analysis project exploring Netflix's content catalog using Python data science libraries. This project analyzes various aspects of Netflix's movies and TV shows, including content distribution, ratings, countries of origin, genres, directors, and actors.

## 📊 Project Overview

This analysis explores Netflix's content dataset to uncover insights about:

- Distribution of Movies vs TV Shows
- Top content-producing countries
- Content rating distributions
- Most popular genres
- Prolific directors and actors
- Geographic visualization of content distribution

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Static data visualization
- **Seaborn**: Statistical data visualization
- **Plotly Express**: Interactive visualizations

## 📁 Project Structure

```
netflix/
├── netflixanalysis.ipynb                        # Main Jupyter notebook with analysis
├── Netflix.csv                                  # Netflix dataset
├── README.md                                    # Project documentation
├── netflix_country_map.html                     # Interactive country map visualization
├── Movies vs TV Shows on Netflix.png            # Content type distribution chart
├── Top 10 Content Producing Countries.png       # Top countries bar chart
├── Distribution of Content Ratings.png          # Content ratings distribution
├── Top 10 Genres on Netflix.png                 # Popular genres analysis
├── Top 10 Directors with Most Netflix Titles.png # Directors frequency chart
└── Top 10 Most Frequent Actors on Netflix.png   # Actors frequency chart
```

## 🔍 Analysis Highlights

### 1. Data Preprocessing

- Handled missing values in country and rating columns
- Converted date_added to datetime format for temporal analysis
- Cleaned and processed categorical data

### 2. Content Type Analysis

- **Movies vs TV Shows Distribution**: Visual comparison of content types available on Netflix

### 3. Geographic Analysis

- **Top 10 Content Producing Countries**: Identified countries with the highest Netflix content contribution
- **Interactive World Map**: Geographic visualization showing Netflix content distribution globally

### 4. Content Rating Analysis

- **Rating Distribution**: Analysis of content ratings (G, PG, PG-13, R, etc.) across Netflix catalog

### 5. Genre Analysis

- **Top 10 Genres**: Most popular content genres on Netflix platform

### 6. Industry Analysis

- **Top 10 Directors**: Directors with the most Netflix titles
- **Top 10 Actors**: Most frequently appearing actors in Netflix content

## 📈 Key Visualizations

1. **Content Type Distribution**: Bar chart showing Movies vs TV Shows ratio
2. **Geographic Distribution**: Interactive choropleth map and top countries bar chart
3. **Rating Analysis**: Distribution of content ratings across the platform
4. **Genre Popularity**: Horizontal bar chart of top genres
5. **Industry Insights**: Director and actor frequency analysis

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn plotly
```

### Running the Analysis

1. Clone this repository
2. Ensure `Netflix.csv` is in the project directory
3. Open `netflixanalysis.ipynb` in Jupyter Notebook or VS Code
4. Run all cells to generate the analysis and visualizations

## 📊 Dataset Information

The analysis uses a Netflix dataset (`Netflix.csv`) containing information about:

- Show/Movie titles
- Content type (Movie/TV Show)
- Director and cast information
- Country of origin
- Release year and date added to Netflix
- Content rating
- Duration
- Genre categories (listed_in)
- Description

## 🎯 Key Insights

The analysis reveals important patterns in Netflix's content strategy, including:

- Content distribution across different regions
- Popular genres and rating preferences
- Prolific content creators in the Netflix ecosystem
- Temporal trends in content addition

## 📝 Future Enhancements

- Temporal analysis of content addition trends
- Sentiment analysis of content descriptions
- Duration analysis for different content types
- Correlation analysis between various content attributes
- Machine learning models for content recommendation

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or additional analysis features.

## 📄 License

This project is open source and available under the MIT License.

---

**Note**: This analysis is for educational and research purposes. The Netflix dataset used is publicly available and does not contain proprietary information.
