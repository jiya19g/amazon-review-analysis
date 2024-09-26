# Amazon Fashion Reviews Analysis

This repository contains the analysis and visualizations of the **Amazon Fashion** dataset, which is part of the larger Amazon product review datasets. The project covers various aspects, including sentiment analysis, correlation analysis between review lengths and ratings, and visual representations of word distributions across different review ratings.

## Dataset

The dataset used in this project is the **Amazon Fashion** dataset, which contains product reviews specifically from the fashion category on Amazon. 

- **Dataset Download Link**: [AMAZON_FASHION.json.gz](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_v2/categoryFiles/AMAZON_FASHION.json.gz)
- **For Other Categories**: Check out the broader dataset collection at this link: [Amazon Product Review Datasets](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/)

## Project Overview

The key objectives of this project include:
- **Sentiment Analysis**: Understanding the correlation between review text length and star ratings.
- **Word Cloud Visualizations**: Visualizing the most frequent words for each rating (from 1-star to 5-star reviews).
- **Hypothesis Testing**: Conducting hypothesis tests on various correlations (e.g., number of reviews vs. average rating).
- **Visualizations**: Using word clouds, scatter plots, and histograms to represent different facets of the dataset.

Make sure you have Python installed in your environment. Then, follow these steps to set up and run the project:

1. Clone the repository and navigate to the project directory.
2. Install the required packages. If they are not present in your environment, install them using `requirements.txt`.

```bash
pip install -r requirements.txt
```
3. Alternatively, you can create and activate a virtual environment:
   
## Create Virtual Environment
To create a virtual environment, run the following command:

```bash
python -m venv venv
```
To activate the virtual environment, use one of the following commands based on your operating system:

On Windows:
```bash
venv\Scripts\activate
```
On macOS/Linux:
```bash
source venv/bin/activate
```

## Usage

1. Load the dataset from the provided link.
2. Explore the data and visualizations in the notebooks.
3. Feel free to modify or extend the code for further analysis.

## Contact

Feel free to contact me if you have any questions or suggestions.

## Citation

If you use this dataset in your work, please cite the following paper:

Ni, J., Li, J. and McAuley, J., 2019, November. Justifying recommendations using distantly-labeled reviews and fine-grained aspects. In Proceedings of the 2019 conference on empirical methods in natural language processing and the 9th international joint conference on natural language processing (EMNLP-IJCNLP) (pp. 188-197).
