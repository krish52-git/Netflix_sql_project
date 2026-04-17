# 🎬 Netflix Data Analysis using SQL
![NETFLIX]("C:\Users\ASUS\Downloads\ebace1d6-e939-407c-b934-1e02dcd523c9.tmp")


## 📌 Project Overview

This project focuses on analyzing the Netflix dataset using SQL to extract meaningful business insights. The analysis covers content distribution, trends, ratings, and patterns in movies and TV shows available on Netflix.

---

## 🎯 Objectives

* Understand the distribution of Movies vs TV Shows
* Analyze ratings and content trends
* Identify top contributing countries
* Explore content growth over time
* Perform actor, director, and genre-based analysis

---

## 📂 Dataset
- <a href="https://github.com/krish52-git/Netflix_sql_project/blob/main/netflix_titles.csv">
The dataset contains information about Netflix content, including:

* Show ID
* Type (Movie / TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Rating
* Duration
* Genre (listed_in)
* Description

---

## 🛠️ Tools & Technologies

* SQL (PostgreSQL / MySQL)
* VS Code (SQLTools Extension)

---

## 📊 Business Problems & Analysis
- <a href="https://github.com/krish52-git/Netflix_sql_project/blob/main/Business%20Problems%20Netflix.sql">
### 1. Movies vs TV Shows Count

Analyzed the distribution of content types available on Netflix.

### 2. Most Common Rating

Identified the most frequently occurring ratings for Movies and TV Shows.

### 3. Movies Released in a Specific Year

Filtered movies based on release year (e.g., 2020).

### 4. Top 5 Countries with Most Content

Determined which countries contribute the most content.

### 5. Longest Movie

Identified the movie with the maximum duration.

### 6. Content Added in Last 5 Years

Analyzed recently added content trends.

### 7. Content by Director

Filtered all content created by a specific director (e.g., Rajiv Chilaka).

### 8. TV Shows with More Than 5 Seasons

Identified long-running TV shows.

### 9. Content Count by Genre

Analyzed the distribution of genres.

### 10. Year-wise Content in India

Found top 5 years with highest content production in India.

### 11. Documentary Movies

Filtered movies belonging to the documentary genre.

### 12. Content Without Director

Identified missing data in the director field.

### 13. Movies by Salman Khan (Last 10 Years)

Analyzed actor-specific appearances over time.

### 14. Top 10 Actors in Indian Movies

Identified actors with the highest number of appearances.

### 15. Content Categorization (Good vs Bad)

Classified content based on keywords like 'kill' and 'violence' in descriptions.

---

## 🔍 Sample SQL Query

```sql
SELECT type, COUNT(*) AS total
FROM netflix
GROUP BY type;
```

---

## 📈 Key Insights

* Movies dominate the Netflix platform compared to TV Shows
* Certain countries produce significantly more content
* Content addition has increased in recent years
* A small group of actors appear frequently in Indian movies
* Keywords in descriptions can be used to classify content sentiment

---

## 💡 Conclusion

This project demonstrates how SQL can be used to analyze real-world streaming data and generate actionable insights. It highlights trends in content production, user preferences, and platform growth.

---

## 🚀 Future Improvements

* Data visualization using Python (Matplotlib / Pandas)
* Dashboard creation using Power BI / Tableau
* Advanced analytics and recommendation systems

---

## 📂 Project Structure

* `netflix_titles.csv` → Dataset
* `queries.sql` → SQL queries used for analysis
* `README.md` → Project documentation

---

## 🔗 Connect with Me

* LinkedIn:[ https://linkedin.com/in/your-profile](https://www.linkedin.com/in/krishna-kumar-m-6328b3249/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BqoBxBu9zRlSxjUQkyzIK9g%3D%3D)

---

