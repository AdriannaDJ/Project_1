Project 1, Group 11: Final Analysis of Netflix Data

Megan Palma, Elizabeth Bradshaw, Adrianna Johnson, Arman Bains, Amit Suresh


Introduction:

In this analysis, we delve into substantial Netflix data to uncover trends, patterns, and comparisons that can inform strategic decisions and enhance the viewer experience. By leveraging data analytics techniques, we aim to gain a deeper understanding of genre popularity, content addition by year, TV and movie ratings, and duration of movies (by minute) and TV shows (by season). Through this exploration of Netflix data, we seek to extract actionable insights that can help to cater to all viewers and grow overall business for the streaming service.

Methodology:

We employed various techniques to derive meaningful insights from the Netflix dataset. Initially, we conducted data preprocessing steps to clean and prepare the data for analysis. This involved handling missing values, removing unnecessary columns, reducing to our targeted volume of countries, and splitting information into new columns to ensure consistency and accuracy. Once the data was preprocessed, we utilized data visualization techniques to present our findings effectively. Visualizations such as scatter plots, line graphs, stacked bar charts and pie charts were instrumental in conveying complex information in a clear and concise manner. These visual representations enhanced our understanding of the data and facilitated communication of key insights.

Major Findings: 

Megan: Most popular Genre for Top 10 Countries (Across Movies & TV Shows)

The goal of this question was to find the most popular genres for both Movies and TV shows. To find this I separated Movies and TV Shows into two separate data frames. Then further honed in the data to be the most popular TV Show and Genres for the top 10 countries. 
In the comparison for TV Shows the most popular genre is International TV Shows 22.6% and for Movies the most popular genre is drama at 21.4%. For TV Shows, the Drama category was ranked as the 2nd (tied with TV Comedy) most popular with 12.7%. For Movies, International Movies was ranked as number 2 at 19.7%. This shows that across both TV Shows and Movies the most popular genres are Dramas and the International genres. 

Elizabeth: Most popular genres by release year (Across Movies & TV Shows)

The goal of this question was to find out which TV show and movie genres were the most popular in the years they were released in, as well as to compare the most popular genres from both TV shows and movies.

I used aggregation to calculate the total count of each movie/TV show genre per year in the dataset, allowing me to determine which genre was the most popular each year based on the number of movies/TV shows belonging to each genre.

In comparison between the top genres in movies and TV shows, we found that the top 4 genres in both groups were the same (Dramas, Comedies, International, and Documentary/Docuseries). In addition, both groups also had Romance and Kids/Family in their top genres. These statistics were taken from the years 2000 and on for simplification. As the years go on, more and more movies and TV shows were added to Netflix, varying in the years each movie or TV show was originally released to the public. 

The numbers represented in the visualizations created show that, generally speaking, the genres that grow the most in number each year are the top 4 genres found in both movies and TV Shows. This shows us that over time, the movies and TV shows added to Netflix regardless of release year have very similar popular genres. The overlapping popular genres in both movies and TV shows were Drama, International, Comedy, Documentary/Docuseries, Romance, and Kids/Family.

Adrianna: Movies added per year for Top 10 Countries  (Across Movies & TV Shows)

TV shows produced in the United States are added to Netflix at a higher rate compared to other countries. In 2014, Netflix began adding more TV shows produced by countries outside of the United States starting with Canada. By 2017, several more countries were added to the mix on Netflix. Between 2020 and 2021, a decline occurred for the top countries including the United States, Japan, United Kingdom, and South Korea. The timeline of the decline lines up with the effects of the pause in production of all movies and TV shows during the Covid-19 pandemic.
In the movies category, the United States has the highest amount of movies added to Netflix overall. The United States has the highest rate of added productions in both movies and TV shows. India is the second highest country to have movies added to Netflix. The other top countries add less than 100 movies per year to Netflix's library. Starting in 2019, we begin to see the start of the decline from effects of the pause in production of all movies and TV shows during the Covid-19 pandemic.

Arman: Rating Percentages for Top 10 Countries (Across Movies & TV Shows)

The purpose of this question was to understand the breakdown of movie and tv ratings across the top 10 countries. To understand this breakdown I created two dataframes, one for movies and the other for tv ratings, which would display the percentage for all the ratings in the top ten countries. And then to visually understand the distribution of the ratings for each country I created two stacked bar graphs. 

For the movie ratings a large chunk of the percentages fell to the United States and India. The United States, not surprisingly accounted for the largest percentage at 55.19%. India with its booming Bollywood industry tagged along at second place with a percentage of 23.94%. Interestingly a predominant portion of India’s movie ratings came from TV-14, which accounted a staggering 14.10% for the entire data for all countries combined. Movie rating distribution for the United States was not as one-sided compared to India, but clearly there were two ratings that accounted for the bulk. These were TV-MA and R at 16.43% and 11.80% respectively. The R rating for some reason was very low or non-existent for the other countries outside of the United States. For example it was zero in South Korea and Japan and its second highest proportion was just 0.88%, which was the percentage for the United Kingdom. 

TV rating distributions were slightly more competitive compared to those of movies. The United States was still on top at 47.86%. But other countries had strong showings, particularly the United Kingdom, Japan and South Korea. The ratings were 13.41%, 10.57% and 9.95% respectively for those nations. Those three countries contributed very low to the movie ratings, especially South Korea, whose movie rating was just 1.1%. So it seems some nations invest more resources to their tv show industry to attract larger audiences, rather than aiming to acquire viewership through their movie industries. Both Japan and South Korea drew large success from the TV-14 rating. The United KIngdom did well in TV-MA and TV-14 also. And the same applied to the United States, who had ratings of 19.84% and 12.15% for TV-MA and TV-14 respectively. 

Amit: Average Number of Show Seasons / movie duration for Top 10 Countries (Across Movies & TV Shows)

After analyzing the data on Netflix titles, I noticed several trends concerning tv shows and films. I specifically focused on two areas, starting with the amount of movie/television titles produced by the top 10 recurring countries as well as their duration, whether that was the number of seasons or length of a movie. I also grouped the top 10 genres and began to understand which genre had the most amount of seasons. Of the 8,806 titles within the data sheet, 6,131 were films and the remaining 2,676 television shows. 

The top 10 countries producing films and tv shows were the United States, India, United Kingdom, Canada, Spain, Japan, South Korea, France, Australia, and China. The US produced the most combined movies/tv shows as per the data with 2800 titles, followed by India which was just shy of a thousand titles. When it came to the average seasons and movie duration per country, the United States again held the largest amount for each, 760 tv seasons produced.

The top recurring movie genres include dramas, international movies, documentaries, stand-up comedies, to name a few, while the top recurring tv show genres included international tv shows, tv dramas, kids' tv, reality tv, etc. The difference in the number of film title genres to tv show title genres is stark. The peak of the movie genre are dramas and international films having 362 titles, whereas Kids' TV has 220 titles.

Finally the combined data of top countries that were responsible for producing either tv shows or films displays that collaborations between the UK, US, and Japan helped produce over 200 films, while Denmark, Singapore, Canada, and US on average produced 13 tv seasons.

Conclusion / Recommendations:

Based on the statistical analysis conducted, several key findings and insights have emerged. 
Overall, the US and India contribute the most content to Netflix, with overlapping popular genres of Drama, International, Comedy, Documentary/Docuseries, Romance, and Kids/Family. It makes sense that the main ratings for the content produced by these two countries were in a range of TV-14 (mostly India), TV-MA and R (latter two mainly the US, making up most of the rated R content out of all of the data). By leveraging both these main insights and more detailed statistical analyses, Netflix can strategically enhance its content offerings by focusing on popular genres and countries producing content. Furthermore, addressing data accuracy issues, such as misplacement of information in columns and challenges in separating TV show seasons from movie durations, for example, is crucial for ensuring the reliability and validity of future analyses. Given the vast amount of data available, the selective approach taken in narrowing down to top countries and genres demonstrates the importance of focusing on key factors for informed decision-making and strategic planning.

As for next steps with our analysis, this is all merely a jumping off point. With many other streaming services out there such as Hulu, Amazon Prime, and Disney Plus, the amount of similar data from other sources is vast, most likely. If our team could analyze other streaming service data and draw similar conclusions, or find significant differences, there would be a lot of added value to our final analysis. Even without other streaming service data, we could draw more conclusions from our original data set. Such analysis could explore data or answer questions such as popular directors or cast members, the least popular genres, or find how many movies or TV shows are on Netflix per release year. We could further answer questions such as whether Netflix should be adding movies or TV shows from specific genres or of specific ratings based on parameters like country.
