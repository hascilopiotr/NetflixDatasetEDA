Netflix Content Strategy Analysis (EDA) 🎬

📌 Overview

This project performs an Exploratory Data Analysis (EDA) on a Netflix dataset to understand the content strategy of the platform. Using Python libraries such as Pandas, Seaborn, and Matplotlib, we analyze trends regarding content types (Movies vs. TV Shows), production countries, genres, and release timing.

📂 Dataset

The analysis is based on the netflix1.csv dataset.

Key Attributes: type, title, country, date_added, release_year, rating, duration, listed_in (genres).

Preprocessing: The 'director' column was dropped, missing values were handled, and date columns were converted to datetime objects for time-series analysis.

🛠️ Technologies Used

Python

Pandas (Data Manipulation)

Matplotlib (Data Visualization)

Seaborn (Statistical Data Visualization)

Numpy (Numerical operations)

📊 Key Analyses & Visualizations

1. Content Segmentation

Movies vs. TV Shows: Analyzed the ratio of content types available on the platform.

Growth Over Time: A line chart visualization showing the volume of content added to Netflix over the years.

2. Geographical Analysis

Top 10 Countries: Bar charts displaying the top content-producing countries for both Movies and TV Shows separately.

3. Genre Analysis

Data Transformation: Utilized the explode() function to separate titles listed under multiple genres.

Top Genres: Visualized the most popular genres for Movies and TV Shows.

4. Rating & Release Trends

Content Ratings: A count plot showing the distribution of content ratings (e.g., TV-MA, PG-13).

Release vs. Added Year: A scatter plot analyzing the lag between a title's original release year and the year it was added to Netflix.

5. Country-Genre Heatmap

A heatmap visualizing the relationship between the Top 5 Countries and the Top 5 Genres, revealing regional content preferences.

📷 Preview



<img width="576" height="453" alt="image" src="https://github.com/user-attachments/assets/bc895e28-3e20-413f-976e-151a823fa400" />

<img width="756" height="413" alt="image" src="https://github.com/user-attachments/assets/503514d8-3ef5-4644-baa8-14c76048c2b1" />

"The Heatmap below shows the concentration of genres produced by specific countries."
<img width="621" height="543" alt="image" src="https://github.com/user-attachments/assets/a818c743-c183-4c8a-baf6-16f84eeffe7d" />


🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
