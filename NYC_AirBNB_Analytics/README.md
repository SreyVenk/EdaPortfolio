#  NYC Airbnb Data Analysis

This project explores the 2019 New York City Airbnb dataset to uncover insights about pricing, location, availability, and customer activity. Using Python and visualization tools, we perform exploratory data analysis (EDA) to understand what factors might influence a successful Airbnb listing.

---

##  Dataset
- **Source**: [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
- **File used**: `AB_NYC_2019.csv`
- **Size**: ~49,000 listings across 5 boroughs

---

##  Tools Used
- Python  
- Pandas  
- Seaborn & Matplotlib  
- (Optional) Folium for mapping

---

##  Key Questions Explored
- Which boroughs and neighborhoods have the most listings?
- How are prices distributed across boroughs and room types?
- Are availability and review rates linked to location?
- Do location (latitude/longitude) influence monthly reviews?

---

##  Key Findings
- **Manhattan and Brooklyn dominate** in listing volume and pricing.
- **Entire homes/apartments** are the most expensive and most common room type in Manhattan.
- **Longitude** has a small positive correlation with `reviews_per_month`, suggesting **eastern areas like Manhattan and Brooklyn** attract more guests.
- **Latitude** shows **almost no correlation**, meaning north-south location has less impact.
- Price has **low correlation** with most variables—indicating that **pricing is complex and likely influenced by external factors** like property quality, photos, or host reputation.

---

##  Files Included
- `nyc_airbnb_eda.ipynb` – Main analysis notebook
- `AB_NYC_2019.csv` – Dataset used
- `README.md` – Project overview

---

##  Next Steps (Optional Ideas)
- Add a predictive model to estimate price
- Explore trends over time using review history
- Build an interactive map with Folium or Streamlit

---

##  Author
Himari Eriguchi  
Aspiring Data Scientist | Computer Science & Data Science | https://www.linkedin.com/in/sreyesvenkat/


