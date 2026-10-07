# 🚴 Cyclistic Trip Data Analysis

---

## 🎯Business Task: 
Maximizing the number of annual members to support future growth by converting casual riders to members. To do that, there are 3 questions that need to be answered:
1. How do annual members and casual riders use Cyclistic bikes diferently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to infuence casual riders to become members?

---

## 📊 Data Overview

| | |
|---|---|
| **Source** | Motivate International Inc. (Divvy Bike Share) |
| **Analysis Period** | 01/2025 – 12/2025 |
| **Original Dataset** | [divvy-tripdata.s3.amazonaws.com](https://divvy-tripdata.s3.amazonaws.com/index.html) |
| **Data License** | [Divvy Data License Agreement](https://divvybikes.com/data-license-agreement) |
| **Raw Data Size** | ~1.1 GB (5.3 million rows) |
| **Processed Data Size** | ~900 MB (5.174 million rows) |

---

## 📖 Column Descriptions

| # | Column | Description |
|---|---|---|
| 1 | `ride_id` | Unique ID for each ride |
| 2 | `rideable_type` | Type of bike (classic or electric bike) |
| 3 | `started_at` | Trip start date and time |
| 4 | `ended_at` | Trip end date and time |
| 5 | `start_station_name` | Trip start station |
| 6 | `start_station_id` | Trip start station ID |
| 7 | `end_station_name` | Trip end station |
| 8 | `end_station_id` | Trip end station ID |
| 9 | `start_lat` | Starting latitude of the trip |
| 10 | `start_lng` | Starting longitude of the trip |
| 11 | `end_lat` | Ending latitude of the trip |
| 12 | `end_lng` | Ending longitude of the trip |
| 13 | `member_casual` | Rider type — **Casual**: single-ride or day pass purchasers; **Member**: annual subscription holders |

---

## ⚠️ Notes & Limitations

- No personally identifiable information (PII) is included in this dataset.

---

## 🔄 Pipeline
Google Colab (Data Cleaning + Transforming) => Google Big Query (Data Source) => Connected Sheet (Google Sheet - Analyzing \& Visualization)

---

## 📈 Presentation

🔗 **[View the Slides on Canva](https://canva.link/yvlw5sdetgopx2u)**

---

## 📄 License

This project uses public data made available by Motivate International Inc. 
under the [Divvy Data License Agreement](https://divvybikes.com/data-license-agreement). 
"Cyclistic" is a fictional company name used for this case study; the underlying 
data is sourced from Divvy, Chicago's real bike-share system.
