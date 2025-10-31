#  NYT News Analyzer

**Author:** Astrid Barreras  
**Stack:** Python, Pandas, Matplotlib, Seaborn, Requests API  
**Last Updated:** March 2025  

---

##  Project Overview

The **NYT News Analyzer** automates data collection and analysis from the **New York Times Article Search API**.  
It retrieves articles by **section** and **date range**, extracts key metadata, and performs exploratory analysis on:

- Most frequently mentioned **keywords**
- Top **authors** over time
- Article **volume trends** (daily, weekly, monthly)

The project showcases end-to-end **API integration**, **data wrangling**, **feature engineering**, and **visualization** in Python.

---

##  Repository Contents

| File | Description |
|------|--------------|
| `nyt_news_analyzer.ipynb` | Main Python script containing all data functions and the `main()` workflow. |
| `nyt_news_analyzer.pdf` | Rendered workflow report showing outputs, plots, and analysis summary. |


---

##  How to Run the Analyzer

1. **Clone this repo**
   ```
   git clone https://github.com/albarreras/nyt-news-analyzer.git
   cd nyt-news-analyzer
  
2. Create your API key file. Inside the project folder, create config.py:
   ```
    API_KEY = "your-nyt-api-key-here"

3. Run the main program
    ```
    python nyt_news_analyzer.py

 
4. You’ll be prompted to:

- Select a section (e.g., “Arts”, “Sports”, “Technology”)

- Enter a date range (MM-DD-YYYY)

- Choose periodicity (daily / weekly / monthly)

5. Output:

- A CSV file saved to /data/ containing fetched articles

- Multiple visualizations (keyword frequency, author trends, etc.)

- Summary of the most frequent keywords and article counts over time

## Example Results

From the “Arts” section between Jan 1 – Mar 22 2025, the Analyzer found 50 articles.
Top keywords included:

Keyword	Frequency
- Television	17
- Art	13
- Personal Profile	7
- Pop and Rock Music	6
- Hong Kong / Art Basel	5


