# Exploring and Visualizing News Headlines
This repository contains code for exploring and visualizing a dataset of news headlines. The code utilizes various data analysis and visualization techniques to gain insights into the dataset's structure, distribution, and content. The code is written in Python and uses popular libraries such as Pandas, Matplotlib, Seaborn, NLTK, and Transformers.

## Dataset

The dataset used in this analysis is stored in a CSV file named `ireland-news-headlines.csv`. The file contains news headlines and their corresponding categories. Before performing any analysis, the dataset is preprocessed to remove duplicates and missing values.

## Data Exploration

The code starts with an exploration of the dataset. It provides an overview of the headline categories and their counts. The categories are further updated to simplify their names by keeping only the first two subcategories. This simplification enhances the analysis and visualization process.

## Visualization

The code includes several visualizations to gain insights into the dataset:

### Distribution of Headlines Across Subcategories

This plot visualizes the distribution of headlines across different subcategories within each main category. It provides a bar chart that compares the number of headlines in each subcategory, offering insights into the prominence or prevalence of news-related topics within the dataset.

### Distribution of Headlines Across Main Categories

This plot focuses on the distribution of headlines across main categories. By grouping the headlines based on their main category, the plot illustrates the imbalance in the distribution of headlines among the different categories.

### Word Cloud

The word cloud visualization displays the most frequently occurring words in the headlines of a specific category. By generating a word cloud, the code allows for quick identification of common or significant terms associated with the specified category, aiding in understanding the prominent themes or topics covered in the headlines.

### PCA (Principal Component Analysis)

The PCA plot utilizes the BERT language model to embed the headlines into a lower-dimensional space. By projecting the embeddings onto two or three dimensions using PCA, the code provides a visual representation that reveals patterns, clusters, or separations between different categories of headlines. This visualization aids in exploring relationships and similarities among the headlines and potentially uncovers underlying structures within the data.

## Dependencies

The code requires the following Python libraries to be installed:

- pandas
- torch
- wordcloud
- sklearn
- transformers
- seaborn
- matplotlib
- nltk

Make sure to install the required dependencies before running the code.

## Usage

To run the code, follow these steps:

1. Clone the repository to your local machine.
2. Add the `ireland-news-headlines.csv` file manually to the `data` directory. It can be found [here](https://www.kaggle.com/datasets/therohk/ireland-historical-news?select=ireland-news-headlines.csv "Irish Times - Waxy-Wany News | Kaggle") It couldn't be uploaded directly to the repository because of it's size.
3. Open and run the `visualisation.ipynb` notebook.

## Results

The code generates visualizations that provide insights into the dataset, including the distribution of headlines across categories, the most frequent words in each category, and the relationships between headlines using PCA. These visualizations help in understanding the dataset's structure, identifying imbalances, and discovering underlying patterns or themes.

Please refer to the generated plots and their corresponding explanations in the code for detailed interpretations of the results.

## Conclusion

This code provides a comprehensive analysis and visualization of news headlines. It enables users to explore the dataset, gain insights into category distributions, and visualize prominent words and relationships. By understanding the dataset's structure and content, stakeholders can make informed decisions and draw meaningful conclusions from the news headline data.

Note: The code can be modified to adapt to different datasets and specific analysis requirements. Feel free to experiment and enhance the code based on your needs.