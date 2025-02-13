# Netflix Content Analysis

This project analyzes Netflix's content dataset to uncover trends in content additions, genres, ratings, and more. The goal is to understand Netflix's content strategy, including seasonal trends, popular genres, and the distribution of movies vs. TV shows.

## 📊 Project Overview

The dataset contains information about Netflix content, including titles, directors, countries, release years, ratings, and more. Below is a detailed description of the dataset:

### Dataset Description

| Column Name    | Data Type      | Description                                      |
|----------------|----------------|--------------------------------------------------|
| `type`         | `object`       | Type of content: Movie or TV Show.               |
| `title`        | `object`       | Name of the movie or TV show.                    |
| `director`     | `object`       | Director of the content.                         |
| `country`      | `object`       | Country of origin.                               |
| `date_added`   | `datetime64[ns]`| Date the content was added to Netflix.           |
| `release_year` | `int64`        | Year the content was released.                   |
| `rating`       | `object`       | Content rating (e.g., TV-MA, PG-13).             |
| `duration`     | `object`       | Length of the content (in minutes or seasons).   |
| `category`     | `object`       | Genre or category of the content.                |

---


---

## 📈 Key Insights

### 1. Trend of Releases Over Time
- Analyzed whether Netflix is increasing or decreasing its content production.
- Identified spikes in releases, indicating strategic content expansion.

### 2. Most Popular Content-Producing Countries
- Determined which countries contribute the most Netflix content.
- Checked if Netflix is dominated by Hollywood or if there is a rise in international content (e.g., India, South Korea).

### 3. Movie Duration Trends
- Found the most common duration for Netflix movies and TV Shows.

### 4. Seasonal Trends in Content Additions
- Identified which months Netflix adds the most content.
- Checked for spikes before holiday seasons (e.g., December, summer).

### 5. Directors with the Most Titles
- Discovered if certain directors are heavily featured on Netflix.

### 6. TV Shows vs. Movies
- Compared the number of TV shows vs. movies on Netflix.
- Checked if Netflix is shifting towards more series over time.

---

## Analysis

# Trend of Releases Over Time

Netflix has been steadily increasing the amount of content over the years, increasing massively since 2016 andh having huge spike in 2020, due to the pandemic.

![obraz](https://github.com/user-attachments/assets/3f332541-dae0-4a67-80a1-1c6b51246da2)

Number of releases is rather evenly spread through the year, with massive dips in February and May.

![obraz](https://github.com/user-attachments/assets/447118a6-0ac0-4e9b-b858-ca2736443d14)

## Country Analysis

United States massively dwarfs other countries with over 3000 releses. India in second place only has slightly above 1000 in comparison.

![obraz](https://github.com/user-attachments/assets/9eeffe4e-9312-4143-b7dc-c4a067208e3f)


United States releases around half of the amount pf content, that all the other countries did combined.

![obraz](https://github.com/user-attachments/assets/c62c8421-f16c-442e-8cc7-c44a9c9700c6)

## Category Analysis

The most popular categories are Dramas and Comedies.

![obraz](https://github.com/user-attachments/assets/5aa57253-3c4e-4736-b60f-0beddd317938)


## Movie vs TV Shows

There's double the amount of movie than TV Shows.

![obraz](https://github.com/user-attachments/assets/4b9aa3b3-0573-416c-830d-784a19b31565)

Movies are especially popular in India (Bollywood), in contrast with TV Shows being more popular in Pakistan as well in Japan and South Korea, where K-dramas are very popular.

![obraz](https://github.com/user-attachments/assets/23371145-a833-4080-87db-9fe080b6e433)


## Length Analysis

Movies have varied lengths, with the highest concentration at around 100 minutes.

![obraz](https://github.com/user-attachments/assets/32cef367-3778-4c83-a8fa-463562ccb7cd)

In comparison TV Shows are massively dominated by 1 season length, reducing drastically with more seasons. For example the amount of 3 seasons shows in only about 20% of those with 1 season.

![obraz](https://github.com/user-attachments/assets/fd98da5a-ada6-4d92-9181-bfacad9ff74d)


## Director Analysis

Indian directors are producing more content than non indian ones.

![obraz](https://github.com/user-attachments/assets/edebbc0a-b068-489d-9211-ea98f134cfea)

## Rating Analysis

The most popluar rating is TV-MA, which means "not suitable for children under 17", with the second most popular being TV-14, which means "not suitable for children under 14"

![obraz](https://github.com/user-attachments/assets/d6db2b97-326f-4f33-b64a-38778f02ad81)

Interestingly content rated R didn't see the post pandemic dip, that all the others did and remained steady. Content rated for childer (PG-13, TV-Y7) even had slight increased after pandemic.

![obraz](https://github.com/user-attachments/assets/1a6aba55-bcf2-43df-a195-3c2cf31e2212)

