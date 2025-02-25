# **Spotify Data Analysis and Visualization**

## **Project Overview**
This project is a comprehensive **Spotify Data Analysis and Visualization** using **Power BI and Python**. The dataset was enriched with **album cover URLs** using the **Spotify Developer API**, and extensive **data cleaning, transformation, and visualization** were performed to extract meaningful insights about music trends, track popularity, and genre distribution. 

The project showcases the integration of **Python (Pandas, Spotipy) and Power BI**, leveraging **DAX functions** to create advanced calculations and **interactive dashboards** for better data-driven decision-making.

---

## **Features**
- **Data Enrichment using Spotify API**: Track album cover URLs were added using Python.
- **Power Query Transformations**: Data cleaning, type conversion, and duplicate removal.
- **DAX Measures & Calculations**: Created key performance indicators such as popularity, streaming trends, and genre-wise insights.
- **Dynamic & Interactive Dashboard**: Included various charts like bar charts, treemaps, donut charts, and waterfall charts.
- **Data Relationships & Modeling**: Established connections between Tracks, Artists, Albums, and Genres tables.
- **Visually Engaging Report**: Integrated album cover images into the Power BI report.
- **Advanced Filtering & Slicers**: Users can filter data by genre, artist, and song popularity.

---

## **Technologies Used**
- **Python**: Data extraction and preprocessing (Pandas, Spotipy)
- **Spotify API**: Fetching track metadata and album cover images
- **Power BI**: Data modeling, visualization, and interactive dashboard
- **DAX (Data Analysis Expressions)**: Custom measures and calculated columns

---

## **Setup Instructions**
### **Open Power BI Report**
- Load `Spotify.pbix` to explore the interactive dashboard.

---

## **Power BI Report Structure**
### **Data Modeling**
- **Tracks Table**: Contains track details, popularity, and album images.
- **Artists Table**: Stores artist-wise analysis.
- **Albums Table**: Includes album-specific data.
- **Genres Table**: Groups songs based on their genre classification.

### **DAX Calculations**
- **Total Streams**: `SUM(SpotifyData[streams])`
- **Average Popularity**: `AVERAGE(SpotifyData[popularity])`
- **Major vs. Minor Key Classification**: `CONCATENATE(SpotifyData[key], " ", SpotifyData[mode])`

### **Dashboard Visuals**
- **Top Artists and Tracks (Bar Chart)**
- **Streaming Trends Over Time (Line Chart)**
- **Genre Distribution (Treemap)**
- **Acoustic vs. Electronic Songs (Donut Chart)**
- **Music Feature Impact on Popularity (Waterfall Chart)**

---

## **Future Improvements**
- **Real-time Data Updates**: Automating data refresh using the Spotify API.
- **Sentiment Analysis**: Analyzing lyrics to classify songs based on emotions.
- **Playlist Analysis**: Exploring trends within user-generated playlists.
- **Integration with Machine Learning**: Predicting song popularity based on key features.

---


## **Contact**
For any inquiries or collaborations, please reach out via **[Navneeth C](https://www.linkedin.com/in/navneeth-c-a07279259/)**.

---
