# Spotify Personal Data Visualization

## Abstract

This project addresses the need for analyzing and visualizing Spotify users’ musical behaviors. Our goal is to provide interactive tools that allow users to explore their 
personal data, better understand their listening habits and uncover insights into their musical preferences, moods, and consumption patterns.

The data used in this project was sourced from the Spotify listening histories of several users. These datasets were obtained through Spotify’s personal data request feature. 
To ensure a legitimate and reliable source, we contacted friends and obtained their explicit consent to share their data. The files, containing information such as songs played,
favorite artists, preferred genres, and listening times were downloaded in JSON format.

After the five days required by Spotify to generate the files, users shared the data with us. We implemented a data processing and preparation pipeline to structure the 
information from the JSON files (history, playlists, etc.) for efficient and optimal use.

This project highlights an innovative approach to delivering personalized musical insights while maintaining transparency and respecting users’ data privacy.

## Questions

- Which artists dominate my musical universe?
- Which artists have had the greatest impact on my playlists?
- How do my listening habits vary from month to month?
- How do my listening habits differ between the morning, afternoon, and evening?
- Which music genres represent my preferences?
- Am I more inclined toward music or storytelling (podcasts) daily?
- Which of my playlists is the most content-rich?
  
## Visualizations

1. **Your Listening Ecosystem**
   A visual map highlighting your most-listened-to artists, showcasing the most intense points and the pillars of your musical year.

3. **Your Musical Icons of the Year!**
   A visualization where the size of rectangles reflects each artist's impact on your playlists, spotlighting your standout artists with interactive details.

5. **The Minutes That Defined Your Months!**  
   A colorful timeline chart showing your listening habits minute by minute for each month, revealing peaks and dips in your musical activity.

6. **Your Daily Listening Cycle**  
   A temporal analysis illustrating your listening habits throughout the day, divided into morning, afternoon, and evening patterns.

7. **The Music Genre That Defines You**  
   A pie chart displaying the distribution of your favorite music genres and providing a glimpse into your sonic universe.

8. **Your Balance Between Podcasts and Music**  
   A comparative visualization showing the share of your listening time dedicated to music versus podcasts, revealing your preferences between the two worlds.

9. **Top 20 Most Content-Rich Playlists: A Sea of Music**  
   An interactive ranking of playlists with the highest song counts, including filters to explore the evolution of their content over time.

## Technologies

* **D3.js**: (or D3 for Data-Driven Documents) is a JavaScript graphics library that enables the display of numerical data in a graphical and dynamic form. It is an important tool for adhering to W3C standards, utilizing common technologies such as SVG, JavaScript, and CSS for data visualization.le données.

* **HTML**: HyperText Markup Language, usually abbreviated as HTML or, in its latest version, HTML5, is the markup language designed for writing web pages.

* **CSS**: (Cascading Style Sheets) allows for the creation of visually appealing web pages.

* **GitHub**: For version control and management.

#### Note: 
During the development of this project, we primarily relied on the D3 documentation. The first visualization is directly inspired by an example provided in this documentation. We also used ChatGPT to assist us in working with the D3 language, while remaining attentive to potential errors it might produce.


