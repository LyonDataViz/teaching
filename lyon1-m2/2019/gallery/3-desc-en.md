**Spotify Listening Habits Visualization**

 

**Project Summary:**

 This project aims to explore personal Spotify data to provide a better understanding of listening behaviors. It addresses the need for users to discover their musical preferences, listening trends, and profile characteristics (dominant genres, favorite artists, seasonal variations). Personalized insights will be presented through clear and interactive visualizations.

 

**Target Audience and Tasks:**

* **Primary Audience:**  
  * Regular Spotify users who want to analyze their listening habits.  
  * Spotify employees, to enhance recommendations and understand listening trends.  
* **Main Tasks:**

  o   Identify annual listening habits (genres, artists, tracks).

  o   Analyze temporal and spatial trends (seasonal variations, specific times, artist origins).

  o   Provide interactive visualizations tailored to user preferences (heatmaps, bar charts, pie charts).

   

**Chosen Data Sources:**

* **Personal Data Request for the last 12 months:**  
  * **Streaming History:** Analyzing tracks played, listening duration, time of day, and device type.  
  * **Tracks Listened:** Classifying musical preferences (title, artist, genre, listening mode).  
  * **Playlists:** Studying playlists created to understand user preferences.  
  * **Spotify Wrapped:** Annual summary to identify key trends.  
       
* **Spotify API:** Enriching the data to obtain the genres listened to.  
   

**Organization:**

* **Communication Tools:**  
  * Discord for daily discussions.  
  * Emails for sharing documents and links.  
  * GitHub (Issues and Projects) for task and priority management.  
* **Work Sessions:**  
  * Weekly meetings to review progress, tracked with a Gantt chart and Scrum management methodology.  
* **Roles in the Team:**  
  * Tasks are distributed equally between the two members, allowing for a versatile collaboration.  
     

**Project Phases:**

1. **Setup Phase (03/12/2024 \- 10/12/2024):**

   ·        Create GitHub repository (SpotifyDataViz) and set up the project.

   ·        Brainstorming to define data and charts to explore.

   ·        Write the scoping document (objectives, target audience, tasks, sketches).

   ·        Request personal Spotify data from the last 12 months.

   ·        Set up a Gantt chart to track tasks.

2. **Data Collection and Analysis (17/12/2024):**

   ·        Download Spotify files (e.g., StreamingHistory\_music\_X.json).

   ·        Analyze and select relevant data.

   ·        Assign tasks and integrate the Spotify API to fill in missing data.

3. **First Visualization (24/12/2024):**

   ·        Create initial charts:

   o   Top 10 artists (vertical bars) with selectors (day, week, month).

   o   Radar chart to visualize monthly listening habits.

   ·        Update Gantt chart.

4. **Advanced Visualization (31/12/2024):**  
   ·        Develop new charts:

   o   Bubble chart for music genres.  
   o   Heatmaps (listening hours, days, and months).  
   o   Top 10 tracks (vertical bars) and user interface design.  
5. **Integration and Iterations (07/01/2025):**

   ·        Combine charts into a single interactive visualization with selectors.

   ·        Develop a world map to track artist origins.

6. **Mid-Presentation (14/01/2025):**

   ·        Challenges integrating heatmaps, adjust visualization.

   ·        Improve radar chart and simplify display.

7. **Final Presentation (21/01/2025):**

   ·        Redesign interface (abandon Bootstrap, cleaner design).

   ·        Finalize charts and integrate user selectors.

   ·        Deliver final project with a GitHub push and complete documentation.

   ·         

**Challenges Encountered:**

o   **Small Team:** Project done by two people, limiting parallel work.

o   **Time Constraints:** Difficulty in diving deeper into certain features.

o   **Interface Design:** Integrating charts was more complex than anticipated.

o   **Manual Mapping:** Long process to collect artist origins manually, leading to a smaller sample size.

**Resources Used:**

* **Bootstrap:** CSS framework for responsive interface (abandoned for a custom approach).  
* **GeoJSON:** Geospatial data representation for mapping artist origins.  
* **CodePen:** Prototyping and rapid testing of features.  
* **Git:** Version control via GitHub for collaboration and tracking.  
* **Spotify API:** For extracting additional data (genres, artists, etc.).  
* **Copilot:** Code generation/assistance.

