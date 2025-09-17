# Netflix-Dataset
Netflix Dataset Description 🎬

The Netflix dataset provides valuable insights into one of the world’s leading streaming platforms. It covers both Movies and TV Shows, making it useful for exploring:
✨ Viewer preferences
✨ Content distribution
✨ Global production trends

📂 Dataset Features (11 Columns):
Show_Id → Unique identifier for each show
Category → Movie 🎥 or TV Show 📺
Title → Name of the content
Director → Director’s name
Cast → Main actors/actresses
Country → Country of production
Release_Date → Date of release
Rating → Audience age rating (G, PG, R, TV-MA)
Duration → Movie length or number of seasons
Type → Genre (Drama, Comedy, Action, Horror…)
Description → Short summary of the content

⚙️ Data Processing & Cleaning:
✔️ isnull() → detect missing values
✔️ fillna("Unknown") → handle missing data
✔️ duplicated() → remove duplicates
✔️ unique() → check unique values

📊 Visualization Insights:
Top Producers: U.S. 🇺🇸 & India 🇮🇳 dominate content production
Movies > TV Shows → Movies are more popular
Trends Over Time: Production surged after 2016, with peaks between 2018–2020
Duration: Most movies last 80–110 minutes, peaking near 100 minutes

🤖 Modeling Approaches:
🔹 K-Means Clustering → Groups content into distinct categories
🔹 Agglomerative Clustering → Builds hierarchical groupings (e.g., “Teen TV Shows” inside “TV Shows”)

✨ Key Findings:
Movies dominate the catalog, guiding content strategy
Post-2016 boom → Originals drive Netflix’s growth
Genres & Ratings strongly influence engagement
Release Year & Duration show meaningful patterns

🎯 Purpose:
This dataset supports optimizing content strategy, enhancing user experience, and improving recommendation systems by analyzing real-world entertainment patterns.
