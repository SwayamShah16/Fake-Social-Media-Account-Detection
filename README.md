# Fake Social Media Account Detection

## Project Overview

This project implements a machine learning-based solution to detect and identify fake or fraudulent social media accounts. Using classification algorithms and data analysis, the system analyzes various profile attributes and behavioral patterns to distinguish between genuine and fake accounts.

## Problem Statement

Social media platforms face a growing challenge with fake accounts used for spam, fraud, impersonation, and malicious activities. This project develops an intelligent classification system to automatically identify suspicious accounts based on their profile characteristics and engagement patterns.

## Key Features

- **Data Analysis & Exploration**: Comprehensive exploratory data analysis (EDA) to understand patterns in authentic vs. fake accounts
- **Data Visualization**: Detailed visualizations of key features and their distributions
- **Machine Learning Classification**: Multiple classification models trained to predict account authenticity
- **Performance Assessment**: Detailed evaluation metrics and model performance analysis
- **Interactive Interface**: Web-based dashboard for easy prediction and visualization

## Project Structure

- **Data Files**:
  - `train.csv`: Training dataset with labeled accounts
  - `test.csv`: Testing dataset for model evaluation
  - `profile_info.csv`: Profile information reference data

- **Analysis Notebooks**:
  - `eda.ipynb`: Exploratory data analysis and insights
  - `eda_testing.ipynb`: Testing data analysis
  - `data_visualization.ipynb`: Advanced data visualization and patterns
  - `classification_models_used.ipynb`: Implementation of classification models
  - `Performance_assessment.ipynb`: Model evaluation and metrics
  - `libraries.ipynb`: Required libraries and dependencies

- **Web Interface**:
  - `index.html`: Interactive dashboard frontend
  - `styles.css`: Styling and layout
  - `scripts.js`: Client-side functionality

- **Documentation**:
  - `Fake Social Account Detection Poster.pdf`: Project poster
  - `DOC-20250329-WA0003.pptx`: Presentation slides

## Technologies Used

- **Python**: Core programming language
- **Jupyter Notebooks**: Data analysis and model development
- **scikit-learn**: Machine learning algorithms
- **pandas & NumPy**: Data manipulation and analysis
- **Matplotlib & Seaborn**: Data visualization
- **HTML/CSS/JavaScript**: Web interface
- **Classification Algorithms**: Multiple models including Logistic Regression, Random Forest, SVM, etc.

## Methodology

1. **Data Exploration**: Analyze account features and identify patterns
2. **Data Preprocessing**: Clean and prepare data for modeling
3. **Feature Analysis**: Understand feature importance and relationships
4. **Model Development**: Train and compare multiple classification algorithms
5. **Performance Evaluation**: Assess model accuracy, precision, recall, and F1-score
6. **Deployment**: Deploy through interactive web interface

## Features Analyzed

The models analyze various profile attributes including:
- Account age and activity patterns
- Follower/following ratios
- Post frequency and engagement rates
- Profile completeness
- Username patterns
- Bio information

## Results

The classification models achieve strong performance in distinguishing between legitimate and fake accounts, with detailed performance metrics available in the `Performance_assessment.ipynb` notebook.

## Usage

1. Explore the analysis through Jupyter notebooks
2. Review visualizations in `data_visualization.ipynb`
3. Check model performance in `Performance_assessment.ipynb`
4. Use the interactive web interface by opening `index.html` in a browser

## Future Enhancements

- Integration with real-time data streams
- Deep learning models for enhanced accuracy
- Multi-platform account detection
- Automated alert system for suspicious accounts
- Real-time API deployment

## Author

Swayam Shah

## License

This project is open for educational and research purposes.

