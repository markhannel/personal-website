---
title: "When Is the Gym Least Crowded? Building a Gym Occupancy Dashboard"
date: 2025-01-10
tags: ["Web Scraping", "Grafana", "InfluxDB"]
---


## 📌 TL;DR 

I wanted to stop guessing when my local gym would be packed, so I built a personal dashboard to tell me.

![Gym Dashboard](/images/projects/Blink-Monitor-Example.png)

## 💾 The Full Story

Blinks app and website offer limited information on how many people are in the gym.
 
## 🥃 Distilled Story

- Deployed a script to scrape real-time gym occupancy data from Blink's exposed API
- Stored the data in a time-series database (InfluxDB) for efficient querying and retention
- Visualized occupancy trends using a Grafana dashboard for monitoring and analysis

## 🚀 Next Steps 