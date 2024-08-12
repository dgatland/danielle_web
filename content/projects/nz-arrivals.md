---
title: "NZ Arrivals (and the Impacts of COVID-19)"
date: 2020-03-01
featured: true
description: "I developed a Python dashboard to visualise and monitor the impact of COVID-19 on the number of weekly 
international travellers to New Zealand."
tags: ["Python","Dashboard", "Data Visualisation"]
image: "/images/nzarrivals_chart.png"
link: "https://nzarrivals.onrender.com/"
fact: ""
weight: 500
sitemap:
  priority : 0.8
---

This was a personal interest project I created during one of Auckland's COVID-19 lockdowns. As New Zealand's borders
went through various levels of restrictions on international travel to New Zealand, I was curious to see how the
international arrivals fluctuated and compared to previous years. Rather than simply creating some charts at the time, I 
decided to create an interactive dashboard that I could update over time with new data, to monitor the trend of
international arrivals as the world 'returned to normal'.

This was the first interactive dashboard/web-app I had ever made, and I used Plotly's Dash library in Python. I learnt a lot through 
this dashboard, which I have applied to subsequent projects (although I haven't retrospectively applied all of those 
lessons to this dashboard). This dashboard has continued to be a useful and interesting resource to review. 

For example, the screenshot below shows how travel grew between May-August 2021 during a relaxation of New Zealand's border 
restrictions, but then reduced again once restrictions tightened. In the dashboard itself, you can toggle on
markers showing key dates for border restrictions and local lockdowns in New Zealand, as a reference point.

![Screenshot of chart from NZ Arrivals dashboard](/images/nzarrivals_chart.png)

**Note:** due to limitations on the server that the app is being hosted on, it is likely to take around a minute to load
when you initially follow the project link below.