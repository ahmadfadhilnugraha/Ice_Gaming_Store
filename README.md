# Ice_Gaming_Store
The project analyzes video game success factors using data from the "Ice" online store to inform effective marketing strategies.

## Goals

1. Identify key factors influencing the success of video games.
2. Analyze sales trends across different platforms, genres, and regions.
3. Determine the impact of user and critic reviews on game sales.
4. Conduct hypothesis tests to gain deeper insights into gaming trends.

## Steps

1. **Data Preparation**: Clean and preprocess the dataset, handle missing values, and calculate total sales for each game.
2. **Data Analysis**: Explore the number of games released each year, sales variations across platforms, and the relationship between reviews and sales.
3. **User Profiling**: Analyze user demographics and preferences for different regions.
4. **Hypothesis Testing**: Evaluate hypotheses regarding platform and genre ratings.

## Data Description

  * Name
  * Platform
  * Year of Release
  * Genre
  * NA sales (sales in North America, in million USD)
  * EU sales (sales in Europe, in million USD)
  * JP sales (sales in Japan, in million USD)
  * Other sales (sales in other countries, in million USD)
  * Critic Score (score from critics, maximum 100)
  * User Score (score from users, maximum 10)
  * Rating (ESRB)

## Conclusion

- Dataset overview:
  - Contains 16,715 rows, with significant null values in key columns like 'Name,' 'Year_of_Release,' 'Genre,' 'Critic_Score,' 'User_Score,' and 'Rating.'
  - 'User_Score' and 'Rating' lack nearly a third of their values, requiring further investigation.
  - Some column names have a mix of uppercase and lowercase letters, needing correction.
  - Non-uniqueness in the 'Name' column suggests potential duplicate data.
  - Data types need scrutiny, with 'Year_of_Release' ideally containing integers and 'User_Score' in float64 format.
  - Consideration given to excluding game data from 1980 to 2016 for predictions in 2017.

- Data analysis:
  - Peak in game releases between 1995 and 2016, with a significant increase from 2007 to 2010.
  - Top 6 platforms by total sales: PS2, X360, Wii, PS3, DS, and PS, with notable fluctuations over the years.
  - Correlation analysis reveals nuanced relationships between critical acclaim, user satisfaction, and sales performance.
  - Regional variations in gaming platform preferences and genre popularity.
  - Strong sales for games with the "Everyone" rating across regions, but prevalence of games with an "Unknown" rating, especially in Japan.

- Hypothesis testing:
  - Tested average user scores for Xbox One and PC users, rejecting the null hypothesis.
  - Tested average user scores for Action and Sports genres, also rejecting the null hypothesis.

- Summary:
  - Dataset analysis provides insights into game release trends, platform performance, genre popularity, and regional preferences.
  - Hypothesis testing supports differences in user scores across platforms and genres, guiding strategic decisions for game developers and publishers.

## Future Work

- Implement machine learning models to predict game success factors and sales trends.
- Explore the impact of marketing campaigns and social media engagement on game sales.
- Conduct sentiment analysis on user reviews to assess the overall sentiment towards different games.
- Investigate emerging gaming technologies, such as virtual reality and augmented reality, and their potential influence on the gaming industry.
- Collaborate with industry experts and stakeholders to validate findings and gain additional insights into the gaming market.
