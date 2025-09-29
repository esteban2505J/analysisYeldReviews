# Review Summarization Service

## Overview

This repository contains code and analysis for a project aimed at developing a service that summarizes customer reviews from websites such as Yelp. The service helps businesses quickly obtain actionable insights from large amounts of user feedback, enabling them to answer important questions like:

- What factors drive negative customer reviews?
- Did a recent policy change improve customer ratings?

## Dataset

The analysis is based on a dataset of reviews, which includes:
- Customer comments (text)
- Star ratings
- Additional metadata (where available)

All review data is assumed to come from a single business.

## Features

- Automatic text analysis of thousands of reviews
- Identification of key topics and trends
- Tracking sentiment over time and relating findings to business changes


## Getting Started

1. Clone the repository.
2. Place your review dataset (`sdata.csv`) in the `/data` folder.
3. Open and run `analysis.ipynb` in the `/notebooks` directory.

## Requirements

- Python 3.8+
- pandas
- nltk
- jupyter

(See requirements.txt for details)

## Usage

All code and analysis are contained in the Jupyter Notebook. Run each cell and review the outputs to follow the structure of the project and see key findings.

## License

This project is for educational purposes and has the MIT license.


