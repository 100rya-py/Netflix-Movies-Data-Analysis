# 🎬 Netflix Movies Data Analysis

## 👋 Welcome!
Hi there! Welcome to my deep dive into the Netflix movie library. 🍿

In this project, I didn't just want to crunch numbers; I wanted to understand **what makes Netflix tick**. [cite_start]I analyzed a dataset of nearly 10,000 movies to uncover content trends, audience preferences, and the explosion of content production in recent years[cite: 351, 436].

Whether you are a data enthusiast or just a movie buff, I hope you find these insights as fascinating as I did!

---

## 🛠️ Tech Stack & Tools
I used Python to power this analysis, relying on these libraries to clean, crunch, and visualize the data:
* **Python:** The core language for the project.
* **Pandas:** For data manipulation and cleaning.
* **Seaborn & Matplotlib:** For creating the visualizations.
* **NumPy:** For numerical operations.

---

## 🧹 From Messy Data to Clear Insights
Real-world data is rarely perfect. Before visualizing, I spent time refining the dataset to ensure accuracy.

### Key Cleaning Steps:
* **Standardization:** The dataset started with **9,827 rows**. [cite_start]I converted the `Release_Date` to a proper datetime format and extracted the **Year** to analyze production timelines[cite: 351, 356, 357].
* [cite_start]**Noise Reduction:** I dropped columns that didn't add statistical value, such as `Overview`, `Original_Language`, and `Poster_Url`[cite: 358].
* **Genre "Explosion":** Movies often fit into multiple genres (e.g., "Action, Sci-Fi"). [cite_start]I "exploded" the genre column so I could count each genre individually for accurate frequency analysis[cite: 362, 363].
* [cite_start]**Vote Segmentation:** Instead of looking at raw ratings, I categorized movies into `Popular`, `Average`, `Below_Avg`, and `Not_Popular` based on statistical quartiles to better understand audience engagement[cite: 360, 361].

---

## 🔍 What I Found (The Fun Stuff)

### 1. 🎭 Drama is King
[cite_start]When I looked at the sheer volume of content, **Drama** is the undisputed king of Netflix genres[cite: 368].
* [cite_start]**Why?** This suggests Netflix places a massive strategic emphasis on storytelling and emotionally engaging content[cite: 369, 459].

### 2. 🕷️ Blockbusters Drive Popularity
While Drama provides the volume, **Action and Sci-Fi** drive the hype.
* [cite_start]**Highest Popularity:** The movie *Spider-Man: No Way Home* took the top spot[cite: 402].
* [cite_start]**Insight:** Audiences clearly prefer high-energy, visually rich, and franchise-driven content when it comes to peak popularity[cite: 404, 508].

### 3. 📉 The Niche Struggle
[cite_start]On the flip side, movies with the lowest popularity often belonged to niche genres (like History or War) or featured heavy/dark themes (like *The United States vs. Billie Holiday*), which tend to have limited mass appeal[cite: 406, 408].

### 4. 🚀 The 2020 Content Boom
Analyzing the timeline revealed a massive surge in production volume recently.
* [cite_start]**Peak Year:** The year **2020** recorded the highest number of movies filmed in this dataset[cite: 410, 427].
* [cite_start]**Takeaway:** This confirms Netflix's aggressive pivot toward ramping up original content production during this period[cite: 431].

---

## 💡 Business Conclusions
If I were presenting this to Netflix executives, here is what I would say:
1.  [cite_start]**Content Balance:** Continue using **Drama** to fill the library with volume, but rely on high-budget **Action/Sci-Fi** titles to drive massive popularity spikes[cite: 429, 430].
2.  [cite_start]**Growth Strategy:** The data confirms a successful strategy of aggressive content expansion between 2018 and 2020[cite: 431].

---

## 📷 Visualizations
*You can view the full code and interactive plots in the [Jupyter Notebook](Netflix Movies Data Analysis.ipynb).*
