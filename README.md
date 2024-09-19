# Content-Patterns-and-Trends-on-Netflix

![Netflix](https://github.com/user-attachments/assets/f2abb82d-c9eb-43f6-80e7-401666d150ec)

## Overview

This project involves an in-depth analysis of Netflix’s content library using structured query language (SQL). The primary goal is to extract actionable insights from the Netflix dataset, helping the platform refine its content strategy, understand global trends, and optimize user engagement. The analysis focuses on different content attributes, such as genre, release year, country of origin, directors, and cast, to evaluate and explore content performance across various dimensions.

## Objective

- Examine the Distribution of Content Types (Movies vs. TV Shows).
- Identify the most common ratings for movies and TV shows.
- Analyze Content by Release Year, Country of Origin, and Duration.
- Categorize and Explore Content Based on Specific Criteria and Keywords.

## Dataset

The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Movies Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)

## Schema

```sql
DROP TABLE IF EXISTS netflix;
CREATE TABLE netflix
(
	show_id	VARCHAR(6),
	type    VARCHAR(10),
	title	VARCHAR(250),
	director VARCHAR(550),
	casts	VARCHAR(1050),
	country	VARCHAR(550),
	date_added	VARCHAR(55),
	release_year	INT,
	rating	VARCHAR(15),
	duration	VARCHAR(15),
	listed_in	VARCHAR(250),
	description VARCHAR(550)
);
```
## Findings and Conclusion

- **Content Distribution:** The dataset contains a diverse range of movies and TV shows with varying ratings and genres.
- **Common Ratings:** Insights into the most common ratings provide an understanding of the content's target audience.
- **Geographical Insights:** The top countries and the average content releases by India highlight regional content distribution.
- **Content Categorization:** Categorizing content based on specific keywords helps in understanding the nature of content available on Netflix.

This analysis provides a comprehensive view of Netflix's content and can help inform content strategy and decision-making.
