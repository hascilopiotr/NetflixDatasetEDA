Netflix Content Strategy Analysis (EDA) 

What's This Project About?

Ever wondered what makes Netflix tick? This project dives deep into a massive Netflix dataset to uncover the strategies behind their content library. Using the power of Python (specifically Pandas, Seaborn, and Matplotlib), we aren't just looking at rows and columns—we're telling the story of how streaming has evolved, what genres dominate our screens, and which countries are producing the next big hits.

The Data

We are working with the netflix1.csv dataset, which is essentially a snapshot of Netflix's library.

What's Inside: It contains details like the type of content (Movie or TV Show), titles, countries of origin, release years, ratings, and genres.

Cleaning Up: Before analyzing, we did some housekeeping. We removed unnecessary columns (like 'director'), cleaned up missing data, and converted dates into a format that lets us track trends over time.

The Toolkit

To make sense of this data, we used a classic Python data science stack:

Pandas: For slicing, dicing, and cleaning the data.

Matplotlib & Seaborn: To turn boring numbers into beautiful, insightful charts.

Numpy: For the heavy mathematical lifting.

The Story the Data Tells

Here are the key questions we answered with our visualizations:

1. Movies vs. TV Shows: The Battle for Dominance

We started by asking a simple question: Is Netflix a movie platform or a TV show platform? We analyzed the ratio to see which format currently rules the library.

2. The Content Explosion

By plotting a line chart over time, we visualized Netflix's growth spurt. You can literally see the moment streaming took over the world based on how much content was added year over year.

3. Global Content Powerhouses

Who is producing the most content? We broke down the top 10 countries for both Movies and TV Shows. This reveals not just Hollywood's dominance, but the rise of international hubs like South Korea, India, and the UK.

4. What Are We Watching?

Genres can be messy—often a single movie is listed under three different categories. We used a technique to "explode" these lists, allowing us to count every single genre tag. The result? A clear picture of the most popular genres on the platform.

5. Who Is It For? (Ratings & Release Lag)

Ratings: We looked at the distribution of content ratings (like TV-MA vs. PG-13) to see if Netflix leans more towards family-friendly content or mature audiences.

The Nostalgia Factor: We compared the release year of a title vs. the year it was added to Netflix. This interesting scatter plot shows us how much "classic" content is being added versus brand-new releases.

📷 Preview



<img width="576" height="453" alt="image" src="https://github.com/user-attachments/assets/bc895e28-3e20-413f-976e-151a823fa400" />

<img width="756" height="413" alt="image" src="https://github.com/user-attachments/assets/503514d8-3ef5-4644-baa8-14c76048c2b1" />

"The Heatmap below shows the concentration of genres produced by specific countries."
<img width="621" height="543" alt="image" src="https://github.com/user-attachments/assets/a818c743-c183-4c8a-baf6-16f84eeffe7d" />


🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
