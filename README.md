# Minnesota Interstate Traffic Volume Analysis

## Project overview

This project analyzes hourly traffic volume on westbound Interstate 94 between Minneapolis and St. Paul, Minnesota. The goal is to help transportation stakeholders understand when traffic demand is highest and how weather, holidays, and time patterns affect roadway use.

## Business problem

Transportation planners need to anticipate periods of heavy roadway demand so they can make better decisions about traffic management, maintenance scheduling, traveler communication, and resource allocation.

## Dashboard

> Dashboard screenshot will be added to this section.

> Tableau Public link will be added after the visualization is published or its existing URL is recovered.

## Business questions

- When is traffic volume highest by hour, day, month, and season?
- How does traffic change on holidays compared with regular days?
- Which weather conditions are associated with higher or lower traffic volume?
- What recurring patterns could support transportation planning?

## Methods

1. Reviewed the data for missing values, duplicate records, and inconsistent categories.
2. Converted the date-time field into analysis-ready date parts, including hour, weekday, month, and year.
3. Compared traffic volume across time periods, holidays, and weather conditions.
4. Built interactive Tableau views to make the patterns easy to explore.
5. Summarized the results as operational recommendations.

## Key findings

1. **Traffic demand follows a strong daily cycle.** Volume rises during commuting periods and falls substantially overnight.
2. **Weekdays and weekends have different patterns.** Weekday traffic is more concentrated around commuting hours, while weekend demand is distributed differently throughout the day.
3. **Calendar and weather conditions affect roadway use.** Holidays and adverse weather can reduce or shift normal traffic patterns, so they should be considered alongside time-of-day trends.

## Recommendations

- Prioritize traffic monitoring and traveler messaging during recurring peak periods.
- Schedule planned maintenance during consistently lower-volume windows when operationally feasible.
- Use separate weekday, weekend, holiday, and severe-weather baselines instead of relying on one overall average.
- Combine historical trends with current weather information when planning staffing and congestion responses.

## Tools

- Tableau
- Microsoft Excel
- Data cleaning
- Exploratory data analysis
- Data visualization

## Data source

[Metro Interstate Traffic Volume dataset — UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)

The dataset contains hourly traffic, weather, and holiday observations collected at an I-94 traffic station in Minnesota.

## Presentation

> The project presentation will be uploaded here when the original PowerPoint file is reattached.

## Repository structure

```text
.
├── README.md
├── images/
│   └── dashboard.png
└── presentation/
    └── minnesota_traffic_volume_presentation.pptx
```

## Next update

Add the final dashboard screenshot, Tableau Public URL, and presentation file.
