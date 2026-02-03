# 🎬 Netflix Movies Data Analysis

## 👋 Welcome!
Hi there! Welcome to my deep dive into the Netflix movie library. 🍿

In this project, I didn't just want to crunch numbers; I wanted to understand **what makes Netflix tick**. I analyzed a dataset of nearly 10,000 movies to uncover content trends, audience preferences, and the explosion of content production in recent years.

Whether you are a data enthusiast or just a movie buff, I hope you find these insights as fascinating as I did!

---
## 📊 Project Presentation
View the detailed business insights and findings in the presentation:
[📄 View Project PPT](https://github.com/100rya-py/Netflix-Movies-Data-Analysis/blob/main/Netflix-Movies-Data-Analysis-Presentation.pdf)

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
* **Standardization:** The dataset started with **9,827 rows**. I converted the `Release_Date` to a proper datetime format and extracted the **Year** to analyze production timelines.
* **Noise Reduction:** I dropped columns that didn't add statistical value, such as `Overview`, `Original_Language`, and `Poster_Url`.
* **Genre "Explosion":** Movies often fit into multiple genres (e.g., "Action, Sci-Fi"). I "exploded" the genre column so I could count each genre individually for accurate frequency analysis.
* **Vote Segmentation:** Instead of looking at raw ratings, I categorized movies into `Popular`, `Average`, `Below_Avg`, and `Not_Popular` based on statistical quartiles to better understand audience engagement.

---

## 🔍 What I Found (The Fun Stuff)

### 1. 🎭 Drama is King
When I looked at the sheer volume of content, **Drama** is the undisputed king of Netflix genres.
* **Why?** This suggests Netflix places a massive strategic emphasis on storytelling and emotionally engaging content.

### 2. 🕷️ Blockbusters Drive Popularity
While Drama provides the volume, **Action and Sci-Fi** drive the hype.
* **Highest Popularity:** The movie *Spider-Man: No Way Home* took the top spot.
* **Insight:** Audiences clearly prefer high-energy, visually rich, and franchise-driven content when it comes to peak popularity.

### 3. 📉 The Niche Struggle
On the flip side, movies with the lowest popularity often belonged to niche genres (like History or War) or featured heavy/dark themes (like *The United States vs. Billie Holiday*), which tend to have limited mass appeal.

### 4. 🚀 The 2020 Content Boom
Analyzing the timeline revealed a massive surge in production volume recently.
* **Peak Year:** The year **2020** recorded the highest number of movies filmed in this dataset.
* **Takeaway:** This confirms Netflix's aggressive pivot toward ramping up original content production during this period.

---

## 💡 Business Conclusions
If I were presenting this to Netflix executives, here is what I would say:
1.  **Content Balance:** Continue using **Drama** to fill the library with volume, but rely on high-budget **Action/Sci-Fi** titles to drive massive popularity spikes.
2.  **Growth Strategy:** The data confirms a successful strategy of aggressive content expansion between 2018 and 2020.

---

## 📷 Visualizations
*You can view the full code and interactive plots in the Jupyter Notebook.*
