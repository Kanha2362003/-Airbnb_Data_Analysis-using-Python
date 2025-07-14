# -Airbnb_Data_Analysis-using-Python
This project analyzes an Airbnb dataset to uncover insights into booking trends, price distribution, availability, and host activity. The goal is to help Airbnb hosts and stakeholders make data-driven decisions.

## -📌 Project Objective
The goal is to extract valuable insights for hosts, travelers, and stakeholders:
- Understand price distribution and factors that affect pricing.
- Identify top neighborhoods and room types.
- Analyze availability and seasonal trends.
- Discover trends in reviews and host activity.

- ## 🗂️ Dataset
- **Source:** Internal CSV (`airbnb_listings.csv`)
- **Size:** ~102,599 rows, 26 columns
- **Sample columns:** `price`, `service fee`, `neighbourhood group`, `room type`, `minimum nights`, `number of reviews`, `availability 365`, `house_rules`.


- ## 🔧 Tools & Technologies
- **Python:** pandas, numpy, matplotlib, seaborn
- **Jupyter Notebook:** For data cleaning and EDA
- **Optional:** Tableau or Power BI for dashboards

- ## ⚙️ Steps Covered

### 1️⃣ Data Cleaning
- Convert `price` and `service fee` to numeric.
- Handle missing values in `host name`, `reviews`, `availability`.
- Parse `last review` as `datetime`.

### 2️⃣ Exploratory Data Analysis (EDA)
- Price trends by neighborhood and room type.
- Availability trends across the year.
- Top hosts by number of listings.
- Reviews per month and ratings distribution.

### 3️⃣ Visualizations
- Histograms, boxplots, bar charts.
- Heatmaps for neighborhood vs availability.
- Map of listings (optional with `folium`).

### 4️⃣ Key Insights & Recommendations
- Average and median price per neighborhood.
- Which room type is most popular and profitable.
- Tips for hosts to increase occupancy and revenue.
