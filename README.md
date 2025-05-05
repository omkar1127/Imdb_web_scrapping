# 🎬 IMDb Web Scraping - Top 250 Movies

## 📌 Overview
This project demonstrates web scraping techniques to extract data about the **Top 250 movies** from IMDb using a combination of **Selenium** and **BeautifulSoup**. The script handles dynamic content loading, parses the HTML structure, and organizes the extracted data into a structured format for further analysis.

### 🎯 Data Extracted
- Title  
- Release Year  
- Duration  
- Minimum Age Requirement  
- IMDb Rating  
- Vote Count  

---

## 🧰 Technologies Used
- **Selenium** – To render and interact with dynamic web pages  
- **BeautifulSoup** – To parse and extract data from HTML documents  
- **Pandas** – For structuring and exporting the data into CSV format  

---

## 🧠 Skills Utilized
- **Web Scraping with BeautifulSoup**: Extracted structured information from HTML tags and attributes  
- **Automated Web Interaction with Selenium**: Navigated pages and fetched dynamic content by simulating browser behavior  
- **Data Extraction & Parsing**: Identified and selected relevant data fields using CSS selectors and class names  
- **String Manipulation**: Cleaned and formatted text using string methods and regular expressions  
- **Pandas for Data Handling**: Organized data into a DataFrame and exported it as a CSV file  
- **Dynamic Web Handling with Implicit Waits**: Used `time.sleep()` to allow dynamic elements to load before scraping  
- **Error Handling**: Implemented conditionals to avoid runtime errors when encountering missing or malformed data  

---

## 📘 What I Learned
In this project, I learned how to use **BeautifulSoup** for parsing HTML, how to handle **dynamic content** with Selenium, and how to implement **pagination** to scrape multi-page data. I also practiced working with **implicit waits**, string formatting, and exporting structured datasets using **Pandas**.

---

## 📁 Output
The final dataset is saved as a CSV file:  
`imdb_top_250_movies.csv`

---

Feel free to fork, modify, or build upon this project!

