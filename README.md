![header](https://github.com/ankysoemitro/Project1_MovieAnalysis/assets/152271063/d871c8ba-c9e8-4991-81b3-94dc409657c6)

# Unveiling Trends for Microsoft's Cinematic Odyssey with Data Analytics

**Authors:** Andrinny Soemitro
***

## Overview

This project analyzes diverse datasets on box office trends to assist Microsoft in navigating cinematic landscape for their new movie studio venture. Descriptive analysis of genres, budgets, and revenue shows that Animation, Sci-Fi, Adventure, Fantasy and Comedy yielded higher revenue compared to the other genres. Microsoft can utilize this analysis to strategically plan their first film debut, leveraging the data for informed decision-making.

## Business Problem

Microsoft's transition from technology to entertainment requires a refined strategy due to its limited experience in the film industry. Analyzing diverse datasets, the project addresses challenges by examining genre trends, profitability, and the correlation between budget, film ratings, and financial success, providing crucial insights for Microsoft to align its strategies with market demands in the unfamiliar domain of movie production.

## Data

The datasets used in this project were sourced from Internet Movie Database (IMDb), The Movie Database (TMdb) and Rotten Tomatoes. Each movie is identified by title and/or movie id with set of data such as genres, year release, budget, runtime and gross.


## Methods

This project uses descriptive analysis to gain insight into cinematic landscape, including genres distribution over the years,  relationship between budget and revenue, relationship between average ratings and runtime and average revenue by genre.

## Results

The analysis reveals a consistent trend over the years, indicating that movies falling under the Documentary, Drama, and Comedy genres are more frequently produced.

![genreyear2](https://github.com/ankysoemitro/Project1_MovieAnalysis/assets/152271063/c494798a-274f-4cba-9893-4dabafd5d17e)


The analysis further uncovers a positive correlation between higher budgets and increased revenue, indicating that movies with larger budgets are more likely to achieve higher financial success. Notably, the three genres with the highest average revenue are Animation, Sci-Fi, and Adventure.

![budgetrevenue](https://github.com/ankysoemitro/Project1_MovieAnalysis/assets/152271063/10b652b8-72be-4853-9d97-a827a94ee1f5)


![revenuegenre](https://github.com/ankysoemitro/Project1_MovieAnalysis/assets/152271063/6c92d9cc-4d21-45ff-b7e3-0d95ddffc5eb)


The analysis of the average rating to runtime indicates that as the movie duration increases, the ratings tend to decrease.

![runtimerating](https://github.com/ankysoemitro/Project1_MovieAnalysis/assets/152271063/98b78f7b-137f-4064-b7b7-802553b70039)


## Conclusions

**Key Recommendations:**
* **Focusing on genre for film production.** Microsoft should produce film in genres that have consistently demonstrated higher average revenue, including Animation, Sci-Fi, Adventure, Fantasy and Comedy.

* **Optimizing Budget Allocation.** The analysis showed a positive correlation between budget and revenue.Microsoft can enhance its budget allocation by strategically investing more in genres with the potential for higher returns. This ensures that financial resources are directed toward areas that have proven to be profitable in the film industry.

* **Considering producing films with shorter runtime.** A positive correlation between higher ratings and shorter runtime was shown in the analysis. Microsoft could explore content creation with shorter durations. This is particularly relevant in genres where audience preferences align with shorter films. Creating content that resonates with viewer preferences could contribute to higher audience satisfaction and, consequently, better financial performance.

**Limitations:**
* **Data limitation.** The analysis relies heavily on the given datasets, and the datasets' ability to represent the entire film industry is essential. Future efforts might involve obtaining more varied and comprehensive datasets to strengthen the reliability of the recommendations and conclusions.

* **Market demographic and dynamics.** As with many industries, various external factors can influence film industry. Factors such as cultural trends, cultural context,  global events, and technological advancements can play a big role in the creation of success film. Due to time constrains, analysis was not performed.

* **Genre categorization.**  Film genres are not always rigidly defined, and the process of categorization can involve subjective judgments as it is a process done by contributions from different people with different discipline and/or expertise. The lack of strict universal criteria, and their fluid nature allows for the incorporation of multiple elements. Hence, giving rise to new sub-genres. 

**Future Steps:**
* **Enhance data sources and quality.**  To resolve discrepencies in values from various sources, Microsoft should set up clear data protocols to ensure reliability and quality of the data.

* **Predictive analytics for genre trends.** Implement machine learning models that analyze historical data and industry trends to predict upcoming popular genres.

* **Collaboration with the film industry experts.** More holistic approach needed to better understand the global trend of film industry. Collaboration with the film industry experts can capture a much more broad perspective.


# For More Information

See the full analysis in the <a href="C:\Users\ankys\Project1_MovieAnalysis\Microsoft_Movie_Analysis.ipynb">Jupyter Notebook</a> or review this <a href="C:\Users\ankys\Project1_MovieAnalysis\Microsoft_Movie_Analysis_Presentation.pdf">presentation</a>.
<<<<<<< HEAD

=======
>>>>>>> 51efde72ff9db7a40fd554269f9a863b3aa13041

# Repository Structure

```
├── Code
│   └── eda_notebook.ipynb
├── Images
├── zippedData
├── .gitignore
├── Microsoft_Movie_Analysis.ipynb
├── Microsoft_Movie_Analysis_Presentation.pdf
└── README.md
```
