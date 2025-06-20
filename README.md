# Steam Games Data Analysis Project

## Project Overview
A comprehensive data science project analyzing computer game data from the Steam platform. This project serves as a final project for the [Introduction to Data Science course](https://campus.gov.il/course/hit-acd-rfp4-datascienceintro-he/) and includes all classic stages of a data science project - from data collection to machine learning predictions.

## Project Objectives
The goal was to explore and analyze extensive data on computer games from the Steam platform, discover patterns and trends in the data, and build a predictive model for new games.

## Project Stages

### 1. Data Collection (Web Scraping & Crawling)
- **Tools**: Beautiful Soup
- **Data Source**: [Steam Store Website](https://store.steampowered.com/contenthub/querypaginated/tags/ConcurrentUsers/render/)
- **Output**: Raw game data scraped from thousands of Steam games
- **Process**: Automated crawling and scraping of game information including metadata, ratings, pricing, and user statistics

### 2. Data Processing and Cleaning
- **Tools**: Pandas
- **Process**: Data cleaning, transformation, and preprocessing
- **Activities**:
  - Handling missing values
  - Data type conversions
  - Feature engineering
  - Data validation and quality assurance
- **Output**: Clean, structured dataset ready for analysis

### 3. Data Visualization and Exploratory Analysis
- **Tools**: Matplotlib, Seaborn, Plotly (assumed)
- **Process**: Comprehensive graphical analysis of the cleaned data
- **Visualizations**:
  - Distribution plots
  - Correlation matrices
  - Trend analysis
  - Comparative visualizations
- **Purpose**: Understanding data patterns and relationships

### 4. Machine Learning Prediction
- **Tools**: Scikit-learn (sklearn)
- **Objective**: Predict outcomes for new games based on learned patterns
- **Process**:
  - Feature selection
  - Model training and validation
  - Performance evaluation
  - Model optimization

## Project Structure

The entire project is contained within a Jupyter Notebook with the following sections:

1. **Section 1**: Web Scraping and Crawling
2. **Section 2**: Data Processing and Cleaning
3. **Section 3**: Data Visualization and Analysis
4. **Section 4**: Machine Learning Predictions

## How to Run the Project

### Prerequisites
```bash
pip install pandas beautifulsoup4 scikit-learn matplotlib seaborn jupyter requests
```

### Running the Project
1. Clone this repository
2. Open the Jupyter Notebook
3. Run cells sequentially:
   - **Section 1**: To see the web scraping process
   - **Section 2**: For data cleaning and processing
   - **Section 3**: For data visualization and analysis
   - **Section 4**: For machine learning predictions

### Alternative: View Results Only
- The scraped data is available in the CSV file included in the repository
- You can skip Section 1 and work directly with the processed data

## Key Findings and Conclusions

After comprehensive data exploration and analysis, we concluded that the available data from the scraped Steam website was insufficient for reliable predictions. However, this conclusion was reached through:

- Thorough data investigation
- Complete statistical analysis
- Proper machine learning methodology
- Comprehensive validation processes

This finding itself represents valuable insight into the limitations of the available data sources and the importance of data quality in predictive modeling.

## Technologies Used

- **Python**: Primary programming language
- **Beautiful Soup**: Web scraping and parsing
- **Pandas**: Data manipulation and analysis
- **Scikit-learn**: Machine learning algorithms
- **Jupyter Notebook**: Development environment
- **Matplotlib/Seaborn**: Data visualization

## Course Information

This project was developed as part of the [Introduction to Data Science](https://campus.gov.il/course/hit-acd-rfp4-datascienceintro-he/) digital course and was evaluated by the course instructors.

## Project Status

✅ **Completed** - Final project submission

## Files in Repository

- `main_notebook.ipynb` - Main Jupyter notebook containing all project code
- `games_dataset_final.csv` - Scraped and processed game data
- `מצגת פרויקט יהל ויונתן.pptx` - Project presentation slides
- `youtube link.txt` - Link to project video presentation
- `README.md` - This file

## Authors

**Yonatan Atia** and **Yahel Sade**

Developed as part of the Introduction to Data Science course curriculum.

---

**Note**: This project demonstrates the complete data science workflow, including the important lesson that not all data sources are suitable for predictive modeling, which is itself a valuable scientific finding.
