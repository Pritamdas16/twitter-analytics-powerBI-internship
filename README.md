# Twitter Analytics Dashboard – Power BI Internship Project

## Domain
Data Analytics

## Tool Used
- Microsoft Power BI

## Dataset
- Twitter Analytics Dataset (Training Project Dataset)

## Project Overview
This project is an extension of the Twitter Analytics training dashboard, developed as part of a Data Analytics internship.  
All internship tasks have been implemented as additional report pages using the same dataset, in accordance with internship guidelines.

The dashboard analyzes tweet engagement, interactions, and trends using calculated columns, time-based filters, and business rules.

---

## Internship Tasks Implemented

### Task 1: Media Engagement vs Media Views
- Scatter chart analyzing the relationship between media engagements and media views.
- Filters include replies threshold, tweet word count, odd dates, and time logic (6 PM – 11 PM IST).

### Task 2: Click Interactions by Tweet Category
- Clustered bar/column chart comparing URL clicks, profile clicks, and hashtag clicks.
- Breakdown by tweet category with date, word count, and time-based conditions (3 PM – 5 PM IST).

### Task 3: Top 10 Tweets by Likes and Retweets
- Visualization showing top-performing tweets based on combined likes and retweets.
- Weekend tweets excluded and additional content-based filters applied.

### Task 4: Engagement Rate Trend Analysis
- Line chart showing monthly trends of average engagement rate.
- Separate lines for tweets with media and without media.
- Time-based and content-based rules applied.

### Task 5: Media Engagement Comparison
- Comparison of replies, retweets, and likes for tweets with media engagements above the median value.
- Date range and parity-based conditions applied.

### Task 6: Engagement Rate Comparison – App Opens
- Comparison of engagement rates for tweets with and without app opens.
- Weekday-only analysis with time, date, and content-based filters.

---

## Data Transformations & Calculated Columns
- TweetWordCount
- TweetCharacterCount
- IsOddDate / IsEvenDate
- Time-based columns (IsTime_3PM_5PM, IsTime_6PM_11PM, IsTime_7AM_11AM, IsValidTime)
- Interaction flags (HasAnyClick, AppOpenFlag)
- Text-based exclusion columns (NoLetterC, NoLetterD, NoLetterS)

---

## Project Files
- **Power BI Report:** `Twitter_Analytics_Master.pbix`
- **Screenshots:** Available in the `screenshots` folder
- **Documentation:** Complete project report available in the `documentation` folder

---

## Note
Some visuals may appear blank after applying all business constraints due to limited data availability within specific conditions.  
This reflects strict business rules rather than implementation issues.

---

## Author
Internship Project – Data Analytics
